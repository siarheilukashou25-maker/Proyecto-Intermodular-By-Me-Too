### Esquema del proyecto: 
### Descripción del equipo de trabajo

El proyecto está compuesto por un equipo reducido de 4 integrantes del ciclo de Desarrollo de Aplicaciones Multiplataforma (DAM): **Pablo , Roberto, Siarhei y Elias**. 

Dado que el equipo debe cubrir todas las áreas del desarrollo de software y la gestión del proyecto, se ha adoptado una estructura ágil basada en la metodología **SCRUM**, combinando especializaciones técnicas individuales con un esquema de **roles rotativos** en cada sprint.

---

#### 1. Miembros del equipo y especialización técnica

Para maximizar la eficiencia en el desarrollo, cada integrante asume un rol técnico principal basado en sus competencias:

* **Product Owner y Analista de Requisitos:**
  * **Miembro asignado:** Siarhei.
  * **Funciones:** Recogida de necesidades de usuarios potenciales mediante encuestas, priorización del *Product Backlog* en GitHub Projects, delimitación del MVP y validación funcional del software frente a las historias de usuario.
* **Desarrollador Front-End e Interfaz de Usuario:**
  * **Miembro asignado:** Elias.
  * **Funciones:** Diseñar los prototipos interactivos en Figma/Base44 e implementar la interfaz de usuario con Flutter y componentes multiplataforma, garantizando la usabilidad y la sincronización en tiempo real.
* **Desarrollador Back-End y Arquitectura de Datos:**
  * **Miembro asignado:** Pablo.
  * **Funciones:** Implementar la lógica de negocio, programar el algoritmo de reparto (común, personal y parcial) y gestionar la persistencia e integración con la base de datos en la nube (Firebase), también gestionará las dependecias y Apis necesarias para el desglose de productos seleccionables por el usuario.
* **QA Tester y Responsable de Calidad:**
  * **Miembro asignado:** Roberto.
  * **Funciones:** Diseñar y ejecutar las pruebas mediante las herramientas de flutter , y controlar que no existan *bugs* críticos abiertos antes de cada entrega.

---

#### 2. Planificación de Sprints y Rotación del Scrum Master

El desarrollo del proyecto se estructura en **8 Sprints de aproximadamente dos semanas de duración cada uno**, abarcando desde el 21/09/2026 hasta el 22/02/2027. 

Con el objetivo de que todos los integrantes adquieran experiencia en la facilitación ágil y la eliminación de bloqueos, el rol de **Scrum Master** se rotará en parejas de Sprints entre los 4 miembros del equipo:

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

---

#### 3. Ventajas de esta organización
1. **Polivalencia del equipo:** La rotación del rol de Scrum Master permite que todo el equipo conozca de primera mano la gestión de tareas, etiquetado (`PD-` y `DI-`) y seguimiento en el tablero Kanban.
2. **Especialización técnica:** Mantener un rol técnico principal durante todo el proyecto evita pérdidas de tiempo por cambio de contexto técnico y asegura entregables de alta calidad en cada área.
#### Arquitecturas:
- (Frontend). Figma/Base44/Draw.io/Flutter(dart)
- (Backend). [ Lógica de negocio distribuida a través del uso de acceso a datos ] Enlazaremos Flutter con Java para el backend mediante API REST 
- (Base de Datos). Firebase

#### Recursos Hardware y Software
- Equipos de sobremesa y portátiles con potencia de procesamiento, memoria RAM y almacenamiento para trabajar de manera óptima y con la posibilidad de usar emuladores.
- Conexión a Internet.
- Conexión a la red eléctrica.
- Entorno de trabajo preparado.
- Dispositivos físicos con Android y iOS para el despliegue y testeo en condiciones reales. Android Studio para emular diferentes dispositivos y hacer testing/QA
- Sistema Operativos (Windows,Linux,macOs)
- (Entorno de Desarrollo). Visual Studio Code/Apache NetBeans/Android Studio/Xcode
- (Gestión de Proyecto). Github
- (Comunicación) Discord/Whatsapp

### 4. Estudio Económico, Costes de Mano de Obra y Análisis de Riesgos

#### 4.1. Cálculo Exacto de Horas de Ingenería (Invertidas y Futuras)

El proyecto se desarrolla entre el **21 de septiembre de 2026 y el 22 de febrero de 2027** (un periodo de 22 semanas en total).

* **Horas ya invertidas (Fase Inicial / Sprints 1-2):**
  * **40 horas acumuladas** en conjunto por el equipo (10 horas dedicadas por cada uno de los 4 integrantes) en labores de toma de requerimientos, validación con encuestas, diseño de prototipos y arquitectura base.
* **Horas futuras planificadas (Octubre 2026 – Febrero 2027):**
  * **Semanas restantes de desarrollo:** ~19,5 semanas.
  * **Carga de trabajo acordada:** **40 horas semanales en conjunto** como mínimo (10 horas semanales por integrante).
  * **Cálculo de horas futuras:** $19{,}5 \text{ semanas} \times 40 \text{ horas/semana} = \mathbf{780 \text{ horas}}$.
* **Cálculo Total del Proyecto:**
  $$\text{Horas Totales} = 40 \text{ h (invertidas)} + 780 \text{ h (futuras)} = \mathbf{820 \text{ horas de ingeniería del software}}$$
  *(Representa un promedio de **205 horas de trabajo individual** por cada uno de los 4 desarrolladores).*

---

#### 4.2. Coste de Mano de Obra (Estudio Salarial DAM Junior 2026)

Para valorar económicamente el esfuerzo del equipo, se toma como referencia el salario de un **Desarrollador de Aplicaciones Multiplataforma (DAM) Junior en su primer año de trabajo en España** bajo el Convenio Colectivo Estatal de Consultoría y Tecnologías de la Información (TIC):

| Concepto Salarial | Importe / Valor | Fuente de Referencia |
|---|---|---|
| **Salario Bruto Anual (Junior 0-1 años)** | 22.000 € / año | Media sectorial DAM España 2026 |
| **Seguridad Social a cargo empresa (+30%)** | 6.600 € / año | Cotización contingencias comunes/desempleo |
| **Coste Total Empresa Anual** | **28.600 € / año** | Salario Bruto + Cargas Sociales |
| **Jornada Anual Convenio TIC** | 1.800 horas / año | Jornada laboral ordinaria anual |
| **Coste Hora Directo (Interno)** | **15,89 € / hora** | $\frac{28.600\ \text{€}}{1.800\ \text{h}}$ |
| **Tarifa Hora Mercado (Freelance / Consultoría)** | **22,00 € / hora** | Tarifa media de facturación junior |

##### Valoración económica de la Mano de Obra en "By Me Too!":

1. **A Coste Interno / Empresa ($15{,}89\text{ €/h}$):**
   * **Horas ya invertidas (40 h):** $635{,}60\text{ €}$
   * **Horas futuras (780 h):** $12.394{,}20\text{ €}$
   * **Coste Total Mano de Obra:** $\mathbf{13.029{,}80\text{ €}}$
2. **A Tarifa de Mercado Freelance ($22{,}00\text{ €/h}$):**
   * **Valor de Mercado de la Ingeniería:** $820 \text{ h} \times 22 \text{ €/h} = \mathbf{18.040{,}00\text{ €}}$

---

#### 4.3. Capital Monetario Directo Necesario (Infraestructura y Licencias)

Al margen del coste en horas de desarrollo, el proyecto requiere una inversión directa de capital en licencias, servicios cloud e infraestructura legal para su salida al mercado:

| Partida / Recurso | Descripción | Coste Estimado |
|---|---|---|
| **Google Play Developer Account** | Cuenta de desarrollador Google Play (Pago único) | 23,00 € (25 USD) |
| **Apple Developer Program** | Licencia anual de distribución en App Store | 92,00 € (99 USD) |
| **Servicios Cloud (Firebase Blaze)** | Base de datos NoSQL, autenticación y hosting (5 meses) | 75,00 € (~15 €/mes) |
| **Dominio y Web de Captación** | Registro de dominio (`bymetoo.app`) y hosting Landing | 25,00 € / año |
| **Registro de Marca (OEPM)** | Protección del nombre comercial "By Me Too!" en España | 125,00 € |
| **Marketing y Difusión Piloto** | Campañas iniciales en redes sociales universiarias | 100,00 € |
| **Entorno y Herramientas (IDE/Git)** | VS Code, Android Studio, Figma, GitHub (Planes Free/Student) | 0,00 € |
| **CAPITAL DIRECTO TOTAL REQUERIDO** | **Gasto en servicios y licencias** | **440,00 €** |

---

#### 4.4. Coste Total Estimado del Proyecto

El presupuesto global consolidado para la entrega del MVP V1.0 en febrero de 2027 asciende a:

$$\text{Coste Total} = \text{Mano de Obra (Interna)} + \text{Capital Directo} = 13.029{,}80\text{ €} + 440{,}00\text{ €} = \mathbf{13.469{,}80\text{ €}}$$

---

#### 4.5. Matriz de Riesgos Técnicos y Medidas de Mitigación

El éxito técnico del software puede verse afectado por las siguientes barreras y riesgos específicos identificados:

| Riesgo Técnico | Impacto | Probabilidad | Estrategia de Mitigación |
|---|---|---|---|
| **Errores en algoritmos de reparto de céntimos** | **Alto** | Media | Automatización de pruebas unitarias con `flutter_test` / JUnit evaluando casos límite de división decimal e indivisible. |
| **Conflictos de concurrencia en tiempo real** | **Alto** | Media | Implementación de transacciones atómicas en Firebase Cloud Firestore para evitar lecturas/escrituras simultáneas corruptas. |
| **Curva de aprendizaje en Flutter / Dart** | **Medio** | Alta | Realización de Spikes técnicos iniciales y uso de arquitecturas de componentes estándar (Provider / BLoC). |
| **Fallos de conectividad en supermercados** | **Medio** | Alta | Configuración de la persistencia local fuera de línea (*offline persistence*) nativa del SDK de Firestore. |
| **Retrasos en la aprobación de las Stores** | **Bajo** | Media | Generación y validación temprana de builds de prueba mediante Google Play Internal Testing. |

---

#### 4.6. Estudio de Impacto y Modelo de Monetización

Para garantizar la viabilidad del proyecto a medio y largo plazo, se define un modelo de negocio con tres vías principales de generación de ingresos:

##### 1. Modelo Freemium (Suscripción In-App)
* **Plan Gratuito:** Permite administrar hasta 2 grupos de convivencia con cestas ilimitadas y repartos estándar.
* **Plan Premium "By Me Too Pro" ($1{,}99\text{ €/mes}$ o $14{,}99\text{ €/año}$ por grupo):**
  * Historial ilimitado de tiques pasados.
  * Exportación de informes mensuales de gastos a PDF/Excel.
  * Gastos recurrentes programados (alquiler, suministros).
  * Escaneo inteligente de tiques mediante OCR/IA (previsto para V2.0).

##### 2. Publicidad Contextual No Intrusiva (Google AdMob)
* Inserción de banners discretos en la pantalla de liquidación con ofertas y promociones de cadenas de supermercados locales (Mercadona, Carrefour, Lidl).

##### 3. Afiliación y Cashbacks
* Integración con plataformas de entrega a domicilio y supermercados online, obteniendo una comisión por cada cesta de la compra convertida desde la app.

##### Estimación de Rentabilidad y Punto de Equilibrio (Break-Even):
* Con una base inicial en la prueba piloto de **500 usuarios activos (aprox. 125 grupos)**:
  * Si el $4\%$ convierte a la versión Premium: $20 \text{ usuarios} \times 1{,}99 \text{ €/mes} = 39{,}80 \text{ €/mes}$.
  * Ingresos estimados por publicidad AdMob: $\sim 15{,}00 \text{ €/mes}$.
  * **Ingresos Mensuales Iniciales:** $\mathbf{\sim 54{,}80 \text{ €/mes}}$.
* **Conclusión de Viabilidad:** Los ingresos iniciales cubren holgadamente los costes operativos de infraestructura Cloud ($\sim 15 \text{ €/mes}$), alcanzando el **Punto de Equilibrio Operativo (Break-Even)** a partir de solo **200 usuarios activos**, garantizando la sostenibilidad financiera de la aplicación sin requerir financiación externa pesada.

#### Justificación e Integración Intermodular

-----
### Resultados previstos:
Ingresos previstos respecto a los gastos(materiales,mano de obra,transporte,Costes Operativos e Indirectos, ubicación física, Costes de Infraestructura y Licencias,mantenimiento,)

---------
### Encuesta de mercado:
Proyectos similares(fortalezas,debilidades,precios,marketing,calidad,lealtad)
Considerar tendencias demográficas, culturas,ingresos.

--------------
### Decisión siguiendo el Plan de negocios:
- Organigrama: donde se evidencien los roles de trabajo. 
- Mercadeo y comercialización: las estrategias para dar a conocer el proyecto. 
- Ubicación o posibles ubicaciones del proyecto. 
- Materiales, equipos y recursos: con el mayor nivel de detalle posible. 
- Costos laborales: los gastos en personal. 
- Cantidad de mano de obra necesaria y las capacidades requeridas. 
- Gastos generales como seguros, impuestos, préstamos y servicios públicos. 
- Costos durante la operación, en caso de que aplique.

