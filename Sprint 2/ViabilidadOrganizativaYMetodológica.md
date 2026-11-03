## 1. Viabilidad Organizativa y Metodología

### 1.1. Equipo de Trabajo y Especialización
El proyecto está compuesto por un equipo reducido de 4 integrantes del ciclo de Desarrollo de Aplicaciones Multiplataforma (DAM): Pablo, Roberto, Siarhei y Elias. Dado que el equipo debe cubrir todas las áreas del desarrollo de software y la gestión del proyecto, se ha adoptado una estructura ágil basada en la metodología SCRUM, combinando especializaciones técnicas individuales con un esquema de roles rotativos en cada sprint.

Para maximizar la eficiencia en el desarrollo, cada integrante asume un rol técnico principal basado en sus competencias:
* **Product Owner:** Miembro asignado: Willman Acosta Lugo. Funciones: Guía principal. Colaborador y juez de los sprints realizados por el equipo de desarrollo.
* **Analista de Requisitos:** Miembro asignado: Siarhei. Funciones: Recogida de necesidades de usuarios potenciales mediante encuestas, priorización del Product Backlog en GitHub Projects, delimitación del MVP y validación funcional del software frente a las historias de usuario.
* **Desarrollador Front-End e Interfaz de Usuario:** Miembro asignado: Elias. Funciones: Diseñar los prototipos interactivos en Figma/Base44 e implementar la interfaz de usuario con Flutter y componentes multiplataforma, garantizando la usabilidad y la sincronización en tiempo real.
* **Desarrollador Back-End y Arquitectura de Datos:** Miembro asignado: Pablo. Funciones: Implementar la lógica de negocio, programar el algoritmo de reparto (común, personal y parcial) y gestionar la persistencia e integración con la base de datos en la nube (Firebase), también gestionará las dependecias y Apis necesarias para el desglose de productos seleccionables por el usuario.
* **QA Tester y Responsable de Calidad:** Miembro asignado: Roberto. Funciones: Diseñar y ejecutar las pruebas mediante las herramientas de flutter , y controlar que no existan bugs críticos abiertos antes de cada entrega.

### 1.2. Planificación de Sprints y Scrum
El desarrollo del proyecto se estructura en 8 Sprints de aproximadamente dos semanas de duración cada uno, abarcando desde el 21/09/2026 hasta el 22/02/2027. Con el objetivo de que todos los integrantes adquieran experiencia en la facilitación ágil y la eliminación de bloqueos, el rol de Scrum Master se rotará en parejas de Sprints entre los 4 miembros del equipo:

| Sprint | Fechas aproximadas | Fase del Proyecto | Scrum Master | Responsabilidades del Scrum Master en el Sprint |
|---|---|---|---|---|
| **Sprint 1** | 21/09 - 05/10 | Fase 1: Planificación y Validación | **Siarhei** | Facilitar la encuesta inicial, creación del tablero en GitHub Projects y definición del MVP. |
| **Sprint 2** | 06/10 - 19/10 | Fase 1: Viabilidad y Arquitectura | **Siarhei** | Supervisar el estudio de viabilidad técnica, elección de tecnologías y redacción del Capítulo 2. |
| **Sprint 3** | 20/10 - 02/11 | Fase 2: Autenticación y Grupos | **Elias** | Coordinar el Sprint Planning para el registro de usuarios, creación de grupos e inicio de sesión. |
| **Sprint 4** | 03/11 - 16/11 | Fase 2: Lista Compartida | **Pablo** | Facilitar la implementación de la sincronización de listas en tiempo real y resolver bloqueos de concurrencia. |
| **Sprint 5** | 17/11 - 30/11 | Fase 2: Algoritmo de Reparto | **Pablo** | Asegurar la integración continua del módulo de reparto (gastos comunes y parciales). |
| **Sprint 6** | 01/12 - 14/12 | Fase 2 y 3: Balances y Pruebas | **Roberto** | Gestionar la integración del cálculo de balances periódicos y coordinar la primera batería de Smoke Tests. |
| **Sprint 7** | 15/12 - 15/01 | Fase 3 y 4: Pruebas y Despliegue | **Roberto** | Dirigir la ejecución de pruebas con usuarios piloto, evaluación SUS y control de regresión. |
| **Sprint 8** | 16/01 - 22/02 | Fase 4: Manuales y Cierre | **Elias** | Coordinar la entrega de manuales técnicos/usuario, revisión final de la memoria y preparación del lanzamiento. |

**Ventajas de esta organización:**
1. **Polivalencia del equipo:** La rotación del rol de Scrum Master permite que todo el equipo conozca de primera mano la gestión de tareas, etiquetado (`PD-` y `DI-`) y seguimiento en el tablero Kanban.
2. **Especialización técnica:** Mantener un rol técnico principal durante todo el proyecto evita pérdidas de tiempo por cambio de contexto técnico y asegura entregables de alta calidad en cada área.

### 1.3. Justificación e Integración Intermodular
El proyecto By Me Too! se ha diseñado como una solución integral que aglutina y pone en práctica todos los conocimientos, competencias y resultados de aprendizaje adquiridos durante el segundo curso del ciclo formativo de Desarrollo de Aplicaciones Multiplataforma (DAM). A continuación, se detalla la justificación y el grado de implicación de cada módulo:
* **Programación Multimedia y Dispositivos Móviles (PMDM):** Es el pilar central del proyecto para la creación del cliente (Frontend). Se aplica en el desarrollo completo de la aplicación móvil (utilizando Flutter/Dart o tecnologías equivalentes), gestionando el ciclo de vida de la aplicación, la navegación entre pantallas y el uso de componentes nativos del dispositivo. Permite implementar la lógica de sincronización en tiempo real y la gestión del estado de la aplicación cuando los usuarios añaden productos a la cesta virtual.
* **Acceso a Datos (AD):** Resulta fundamental para garantizar la persistencia de la información. Se aplica en la integración de la aplicación con la base de datos en la nube (Firebase). Incluye la estructuración de los datos (usuarios, grupos de convivencia, tiques, productos y balances), las operaciones CRUD (Crear, Leer, Actualizar, Borrar) y el mapeo de los datos JSON/NoSQL a objetos del modelo de negocio.
* **Desarrollo de Interfaces (DI):** Se aplica directamente en las fases de diseño y prototipado visual de todas las pantallas mediante herramientas como Figma y Base44. Asegura que la aplicación cumpla con los estándares de usabilidad, accesibilidad y experiencia de usuario (UX/UI), permitiendo que el registro de compras sea rápido e intuitivo (en menos de 60 segundos) y adaptándose a diferentes tamaños de pantalla.
* **Sistemas de Gestión Empresarial (SGE):** La aplicación "By Me Too!" actúa en la práctica como un micro-ERP (Sistema de Planificación de Recursos Empresariales) orientado al ámbito doméstico. Se aplican los conceptos de este módulo al modelar los módulos de "clientes/usuarios", gestión de "inventario/compras" y la lógica de cálculo financiero para automatizar la liquidación de cuentas y deudas entre los miembros del grupo de convivencia.
* **Itinerario para la empleabilidad (IPE):** Justifica la existencia misma del proyecto desde una perspectiva de mercado. Se aplica en la identificación del problema, la definición del público objetivo (compañeros de piso y familias) y el estudio de viabilidad técnica y económica. Ayudará con las referencias legales. Define la estructura organizativa del equipo de trabajo, las obligaciones legales (cumplimiento del RGPD) y la estrategia de comercialización o distribución.
* **Proyecto Intermodular:** Actúa como hilo conductor, obligando a aplicar metodologías de desarrollo ágil (Scrum), control de versiones (Git/GitHub) y la elaboración de una documentación técnica estructurada que certifica la trazabilidad completa desde la idea inicial hasta el despliegue del producto final.

---