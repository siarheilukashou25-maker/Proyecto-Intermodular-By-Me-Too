### Esquema del proyecto: 
### Descripción del equipo de trabajo

El proyecto está compuesto por un equipo reducido de 4 integrantes del ciclo de Desarrollo de Aplicaciones Multiplataforma (DAM): **Pablo , Roberto, Siarhei y Elias**. 

Dado que el equipo debe cubrir todas las áreas del desarrollo de software y la gestión del proyecto, se ha adoptado una estructura ágil basada en la metodología **SCRUM**, combinando especializaciones técnicas individuales con un esquema de **roles rotativos** en cada sprint.

---

#### 1. Miembros del equipo y especialización técnica

Para maximizar la eficiencia en el desarrollo, cada integrante asume un rol técnico principal basado en sus competencias:

* **Product Owner**
  * **Miembro asignado:** Willman Acosta Lugo.
  * **Funciones:** Guía principal. Colaborador y juez de los sprints realizados por el equipo de desarrollo.
**Analista de Requisitos:**
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

### 5 Justificación e Integración Intermodular

El proyecto **By Me Too!** se ha diseñado como una solución integral que aglutina y pone en práctica todos los conocimientos, competencias y resultados de aprendizaje adquiridos durante el segundo curso del ciclo formativo de Desarrollo de Aplicaciones Multiplataforma (DAM). 

A continuación, se detalla la justificación y el grado de implicación de cada módulo profesional en el desarrollo del proyecto:

*   **Programación Multimedia y Dispositivos Móviles (PMDM):** 
    *   Es el pilar central del proyecto para la creación del cliente (Frontend). Se aplica en el desarrollo completo de la aplicación móvil (utilizando Flutter/Dart o tecnologías equivalentes), gestionando el ciclo de vida de la aplicación, la navegación entre pantallas y el uso de componentes nativos del dispositivo.
    *   Permite implementar la lógica de sincronización en tiempo real y la gestión del estado de la aplicación cuando los usuarios añaden productos a la cesta virtual.
*   **Acceso a Datos (AD):** 
    *   Resulta fundamental para garantizar la persistencia de la información. Se aplica en la integración de la aplicación con la base de datos en la nube (Firebase).
    *   Incluye la estructuración de los datos (usuarios, grupos de convivencia, tiques, productos y balances), las operaciones CRUD (Crear, Leer, Actualizar, Borrar) y el mapeo de los datos JSON/NoSQL a objetos del modelo de negocio.
*   **Desarrollo de Interfaces (DI):** 
    *   Se aplica directamente en las fases de diseño y prototipado visual de todas las pantallas mediante herramientas como Figma y Base44.
    *   Asegura que la aplicación cumpla con los estándares de usabilidad, accesibilidad y experiencia de usuario (UX/UI), permitiendo que el registro de compras sea rápido e intuitivo (en menos de 60 segundos) y adaptándose a diferentes tamaños de pantalla.
*   **Sistemas de Gestión Empresarial (SGE):** 
    *   La aplicación "By Me Too!" actúa en la práctica como un **micro-ERP (Sistema de Planificación de Recursos Empresariales)** orientado al ámbito doméstico.
    *   Se aplican los conceptos de este módulo al modelar los módulos de "clientes/usuarios", gestión de "inventario/compras" y la lógica de cálculo financiero para automatizar la liquidación de cuentas y deudas entre los miembros del grupo de convivencia.
*   **Itinerario para la empleabilidad(IPE):** 
    *   Justifica la existencia misma del proyecto desde una perspectiva de mercado. Se aplica en la identificación del problema, la definición del público objetivo (compañeros de piso y familias) y el estudio de viabilidad técnica y económica.Ayudará con las referencias legales.
    *   Define la estructura organizativa del equipo de trabajo, las obligaciones legales (cumplimiento del RGPD) y la estrategia de comercialización o distribución.
*   **Proyecto Intermodular:** 
    *   Actúa como hilo conductor, obligando a aplicar metodologías de desarrollo ágil (Scrum), control de versiones (Git/GitHub) y la elaboración de una documentación técnica estructurada que certifica la trazabilidad completa desde la idea inicial hasta el despliegue del producto final.

---------
### 6 Encuesta de mercado:

**1. Proyectos similares y soluciones actuales (Competencia)**
Actualmente, el mercado carece de una solución unificada para este nicho. Según nuestra encuesta a 75 usuarios, la "competencia" real son métodos manuales y desorganizados: un 48,5% utiliza libretas físicas en casa, un 24,2% usa grupos en apps de mensajería rápida y un 21,3% no utiliza ninguna herramienta. Aunque existen apps genéricas de listas de la compra o de reparto de gastos (como Splitwise), ninguna integra la **gestión simultánea de la cesta y la división automática del precio unitario por producto**. 

* **Debilidades actuales del mercado:** El 82,7% de los usuarios afirma que olvida productos por no llevar listas completas o actualizadas.
* **Fortaleza de By Me Too!:** El 95% de los encuestados afirma que usaría nuestra aplicación. La funcionalidad de añadir/borrar productos en conjunto es considerada imprescindible por el 80%, y la división de gastos cuenta con un 100% de aceptación específica en entornos de pisos compartidos.

**2. Tendencias demográficas, culturales y de ingresos**
* **Demografía:** El público objetivo principal es joven. El 80% de los usuarios tiene entre 19 y 40 años, siendo el 70% estudiantes universitarios o personas recién insertadas en el mundo laboral. Esto indica ingresos medios-bajos, lo que justifica el modelo de negocio *Freemium* para no crear barreras de entrada.
* **Cultura de consumo:** La compra sigue siendo una actividad muy tradicional; el 97% acude de forma presencial al supermercado. Además, es una tarea muy recurrente: el 90% hace la compra con una frecuencia de entre 2 y 7 días.
* **Preferencia de establecimientos:** Existe un monopolio claro en la preferencia de los usuarios, con Mercadona acaparando un 92% del interés, muy por delante de competidores como Lidl y Día (21% cada uno). Esto es clave para futuras estrategias de marketing o integración de catálogos.

--------------
### 7 Marco Legal, Fiscal y Prevención de Riesgos

La viabilidad comercial del proyecto exige el cumplimiento de normativas legales, obligaciones fiscales y protección de los trabajadores.

#### 7.1. Obligaciones Legales y Fiscales
Para operar en el mercado español y publicar en Google Play y App Store de forma comercial, el equipo promotor deberá constituirse legalmente:
* **Forma jurídica inicial:** Alta en el Régimen Especial de Trabajadores Autónomos (RETA) para los fundadores, aprovechando la tarifa plana inicial. En fases de escalabilidad, se constituirá una Sociedad Limitada (S.L.).
* **Obligaciones fiscales:** 
  * Presentación trimestral de IVA .
  * Retenciones de IRPF .
  * Tributación de beneficios a través del Impuesto de Sociedades (25% en régimen general, 15% para empresas de nueva creación).
* **Protección de Datos:** Cumplimiento estricto del RGPD (Reglamento General de Protección de Datos) europeo y la LOPDGDD española, requiriendo el consentimiento explícito para procesar datos financieros, historiales de compra y credenciales de autenticación.

#### 7.2. Prevención de Riesgos Laborales (PRL)
Dado que el desarrollo de software es una actividad intensiva en PVD (Pantallas de Visualización de Datos), se contemplan los siguientes riesgos y medidas preventivas:

* **Riesgos ergonómicos:** Fatiga visual, cervicalgias y síndrome del túnel carpiano.
  * *Medidas:* Sillas ergonómicas ajustables, monitores a la altura de los ojos.
* **Riesgos psicosociales:** Estrés por plazos de entrega y sedentarismo.
  * *Medidas:* Pausas visuales (regla 20-20-20), metodologías ágiles para evitar cuellos de botella en las entregas, y fomento de la desconexión digital fuera de las horas estipuladas.

---

### 8 Financiación Pública y Ayudas al Emprendimiento

Para sufragar los costes iniciales y escalar el producto, se identifican las siguientes líneas de subvención y ayudas aplicables al sector TIC en España:

1. **Programa Kit Digital:** Impulsado por el Gobierno de España, ofrece bonos digitales para pymes y autónomos. Aunque está orientado a la digitalización, puede aprovecharse para financiar la infraestructura web y el marketing de la aplicación.
2. **ENISA (Jóvenes Emprendedores):** Préstamos participativos del Ministerio de Industria, sin avales personales, orientados a pymes de reciente constitución (menos de 24 meses) con proyectos innovadores de base tecnológica.
3. **Ayudas Autonómicas:** Subvenciones a fondo perdido para el fomento del empleo autónomo en la comunidad autónoma correspondiente (ej. cuota cero o ayudas al inicio de actividad).

