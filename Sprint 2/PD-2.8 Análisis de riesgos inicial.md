## 2.8 Análisis de Riesgos Inicial

El desarrollo de software convive siempre con la incertidumbre: los problemas no avisan y surgen cuando menos se espera. Si no se anticipan los tropiezos —ya sean fallos técnicos, falta de tiempo, descuidos en la organización o problemas dentro del equipo—, cualquier imprevisto puede descarrilar el proyecto. Evaluar el impacto de estos riesgos y aplicar buenas prácticas de prevención desde el primer día es lo que garantiza que **By Me Too! / Cómprame!** llegue a tiempo a su entrega final (prevista entre el 21 de septiembre de 2026 y el 22 de febrero de 2027) estable y funcional.

Para estructurar la gestión de riesgos en este proyecto, nos apoyamos en tres pilares prácticos de la industria: las normas internacionales de gestión de riesgos, el catálogo de errores frecuentes en desarrollo de software y las mecánicas preventivas que ya trae la metodología Scrum.

En primer lugar, el estándar **ISO 31000** explica que para gestionar riesgos no basta con reaccionar sobre la marcha, sino que se necesita un *«marco de trabajo estructurado que define claramente roles, responsabilidades y procesos»* orientados a *«identificar, evaluar, controlar y hacer seguimiento de los riesgos, enfatizando la mejora continua»* [1]. Aplicar estas rutinas en proyectos informáticos aporta una *«mayor previsibilidad del proyecto y control de desviaciones»*, algo fundamental para *«reducir retrasos significativos y evitar incrementos no deseados en el presupuesto»* [1].

Por otro lado, al analizar de dónde vienen los problemas, autores de referencia como Hughes, Cotterell y Boehm señalan que los riesgos suelen golpear en tres frentes: en el proyecto por *«las restricciones de recursos, las políticas internas, los problemas de coordinación interna del equipo»*, en el proceso por *«una gestión pobre de requisitos o una planificación ineficaz»*, o directamente en el producto por *«la falta de experiencia en el dominio o interfaces definidas deficientemente»* [2]. Para evitar que estos factores paralicen el desarrollo, el modelo de Hughes & Cotterell propone una dinámica constante de *«identificación, análisis y priorización, planificación y monitorización continua»* [2], lo que nos permite detectar a tiempo tanto las flaquezas del equipo como las complicaciones tecnológicas.

Finalmente, utilizar **Scrum** no es solo una forma de repartir las tareas en Sprints, sino la primera línea de defensa del equipo. Esta metodología lleva la prevención de riesgos *«integrada en su propio ADN»* [3]. Al trabajar con entregas cortas y mantener visibles los obstáculos en el tablero —donde el Scrum Master se encarga de resolver las interrupciones (*impediments*)—, se evita que los fallos se acumulen a última hora: *«la flexibilidad reduce los riesgos de negocio, el feedback periódico minimiza errores de interpretación en los requisitos y la entrega iterativa reduce el riesgo de inversión»* [3]. Además, esta dinámica permite *«incluir los riesgos —y las acciones para combatirlos— como historias de usuario»* en el propio *Product Backlog* [3], impidiendo que un despiste se transforme en un problema grave (*issue*) difícil de solucionar.

Teniendo en cuenta estos tres enfoques, el análisis y gestión de riesgos iniciales de **By Me Too! / Cómprame!** se organizan en las tres fases que se detallan a continuación.

---

### 2.8.1 Identificación de Riesgos

En esta fase se han detectado los riesgos típicos que amenazan el ciclo de desarrollo (tales como retrasos en la curva de aprendizaje de librerías gráficas, problemas de rendimiento en dispositivos cliente, incompatibilidades en el empaquetado multiplataforma o fluctuaciones en el alcance del proyecto).

Para el contexto real de este proyecto —un equipo reducido de 4 estudiantes de DAM con recursos económicos nulos y la necesidad de aprender tecnologías simultáneamente—, se han identificado 12 amenazas principales distribuidas en factores de personal, proyecto, producto y métodos.

---

### 2.8.2 Evaluación de Riesgos

Cada riesgo identificado ha sido evaluado asignándole una **Probabilidad de ocurrencia** (Baja, Media, Alta) y un **Impacto potencial** (Bajo, Medio, Alto), determinando su nivel de **Severidad / Criticidad**.

Para representar visualmente esta priorización, se utiliza la **matriz de riesgos**, definida como *«una de las herramientas más básicas pero efectivas en la gestión de riesgos»* que permite obtener una *«visión rápida y clara de qué riesgos deben priorizarse inmediatamente y cuáles pueden gestionarse con menor urgencia»* [1]. Esta evaluación objetiva sustenta la toma de decisiones del equipo en datos reales y concretos [1].

---

### 2.8.3 Plan de Mitigación

#### Matriz Integrada de Análisis y Plan de Gestión de Riesgos

La siguiente tabla reúne la síntesis completa de la identificación, evaluación y respuesta preventiva/correctiva diseñada para el proyecto:

| Riesgo | Descripción | Probabilidad | Impacto | Severidad / Criticidad | Medida de Prevención | Plan de Contingencia |
| :--- | :--- | :---: | :---: | :---: | :--- | :--- |
| **Falta de tiempo por mala planificación (21/09/26 - 22/02/27)** | Mala planificación en añadido a la acumulación de entregas en otros módulos del ciclo DAM que reducen la dedicación al proyecto en la ventana de 5 meses. | **Alta** | **Alto** | **Crítica** | Elaborar un cronograma detallado por Sprints al inicio, reservando un margen de 2 semanas antes del 22 de febrero. | Reducir el alcance cancelando funcionalidades secundarias para priorizar únicamente la aplicación funcional. |
| **Aprendizaje simultáneo de tecnologías** | Necesidad de aprender herramientas (ej. Flutter, Firebase o backend en Java) al mismo tiempo que se implementa el código. | **Alta** | **Medio** | **Alta** | Realizar investigaciones y prototipado técnico rápido. | Asignar las tareas complejas a quien domine más. |
| **Inexperiencia del equipo** | Primer proyecto software de esta escala, complejidad y arquitectura desarrollado de principio a fin por el grupo. | **Alta** | **Medio** | **Alta** | Adoptar patrones de diseño estándar ya conocidos en el ciclo y tener una buena comunicación. | Solicitar ayuda a los profesores con los temas relacionados. |
| **Equipo reducido (4 personas)** | Poca disponibilidad de personal para cubrir simultáneamente roles de gestión, desarrollo, UX y QA y realizar desarrollo. | **Media** | **Alto** | **Alta** | Definir responsabilidades claras por área pero manteniendo la polivalencia y rotación de roles en Scrum. | Redistribuir la carga de trabajo del miembro sobrecargado entre los otros 3 integrantes de forma temporal y solcitar apoyo por parte del product owner. |
| **Recursos económicos limitados** | Dependencia exclusiva de niveles gratuitos de plataformas Cloud, IDEs y herramientas SaaS. | **Baja** | **Medio** | **Media** | Seleccionar tecnologías *open-source* o con capas gratuitas amplias (Firebase Spark Plan, GitHub, Figma Free). | Migrar a alternativas si se agota la cuota gratuita. |
| **Intentar abarcar demasiado** | Sobrecargar la aplicación con funciones avanzadas  no esenciales. | **Alta** | **Alto** | **Crítica** | Cementar el Producto Mínimo Viable (MVP) en las primeras semanas. | Descartar automáticamente cualquier función que no sea indispensable. |
| **Falta de definición de requisitos** | Ambigüedad a la hora de definir cuáles son los requisitos | **Media** | **Alto** | **Alta** | Redactar  **Criterios de Aceptación** definidos antes de iniciar cada Sprint. | Pausar la programación de la tarea confusa hasta refinarla con el Product Owner en el *Sprint Planning*. |
| **Falta de seguimiento de Scrum** | Saltarse las reuniones (Dailies, Reviews) o no actualizar el Backlog, perdiendo la visibilidad del progreso. | **Media** | **Medio** | **Media** | Fijar horarios estrictos para la *Daily* y tareas y usar un tablero digital (GitHub Projects). | El Scrum Master debe intervenir para reestructurar las ceremonias y auditar el estado real del tablero. |
| **Mal control de versiones** | Conflictos masivos en Git, subida de código roto a la rama `main` o pérdida de trabajo por sobrescrituras. | **Media** | **Alto** | **Alta** | Establecer una convención estricta de ramas y **prohibir subidas directas a `main`** sin *Pull Request*. | Revertir la rama principal al último *commit* estable conocido mediante etiquetas (*tags*) o ramas de respaldo. |
| **Invertir tiempo en detalles secundarios (Gold-plating)** | Perder horas puliendo animaciones complejas de la interfaz o estilos visuales antes de que la lógica funcione. | **Alta** | **Medio** | **Media** | Aplicar el principio "Primero que funcione, luego que sea bonito". Diseñar layouts básicos antes de estilizar. | Cortar el desarrollo visual en el momento en que cumpla con la usabilidad mínima y pasar a la lógica de negocio. |
| **Cambios de ideas en el desarrollo** | Modificar la lógica, la arquitectura o diseño a mitad del proyecto por probar nuevos enfoques. | **Media** | **Alto** | **Alta** | Validar el diseño en prototipos y diagramas UML **antes** de empezar a escribir código. | Exigir aprobación unánime del equipo antes de aplicar un cambio estructural que afecte a código ya escrito. |
| **Fallos de compatibilidad** | Problemas al integrar dependencias, librerías de terceros, versiones de Java/Dart o emuladores móviles. | **Media** | **Medio** | **Media** | Fijar las versiones de las librerías  desde el inicio. | Aislar las librerías conflictivas  o buscar una alternativa más estable. |

---

### Referencias

* **[1]** OpenWebinars, «Risk Management: protege la continuidad de los proyectos IT», *OpenWebinars Blog*. Disponibilidad: `https://openwebinars.net/blog/risk-management-protege-la-continuidad-de-los-proyectos-it/`
* **[2]** A. D. R. M. GitHub Notes, «Unidad 2.5: Gestión de Riesgos», *Apuntes de Planificación y Gestión de Proyectos (PGP)*. Disponibilidad: `https://adrm.github.io/apuntes-cuarto/pgp/2_5_gestion_riesgos.html`
* **[3]** Wolf Project, «La gestión de riesgos en Scrum», *Wolf Project Blog*. Disponibilidad: `https://wolfproject.es/scrum-riesgos-gestion/`