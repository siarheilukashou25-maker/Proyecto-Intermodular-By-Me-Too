## 1. Viabilidad Técnica

### 1.1. Arquitectura y Pila Tecnológica (Tech Stack)
Para garantizar la viabilidad técnica del proyecto y cumplir con los objetivos del producto mínimo viable (MVP), se ha seleccionado una arquitectura basada en microservicios y tecnologías multiplataforma:
* **Frontend (Cliente Móvil): Flutter y Dart.** Se opta por este framework para desarrollar una única base de código que permita compilar la aplicación de forma nativa tanto para Android como para iOS. Esto reduce los tiempos de desarrollo y garantiza una interfaz gráfica (UI) uniforme en ambas plataformas. Herramientas complementarias: Figma/Base44/Draw.io para diseño.
* **Backend (Lógica de Negocio): Java mediante API REST.** Para la implementación del algoritmo de reparto (común, personal y parcial) y la gestión de la lógica compleja, se utilizará Java distribuida a través del uso de acceso a datos. Esta decisión responde a la curva de aprendizaje actual del equipo, aprovechando los conocimientos sólidos adquiridos en el ciclo formativo (SGE y Acceso a Datos) para asegurar un backend robusto. A largo plazo (Post-MVP), se evaluará la refactorización de esta lógica a Dart puro para unificar el stack tecnológico.
* **Base de Datos y Backend as a Service (BaaS): Firebase.** Su infraestructura NoSQL (Cloud Firestore) se elige específicamente por su capacidad de sincronización en tiempo real, un requisito funcional crítico para que varios usuarios actualicen la cesta de la compra simultáneamente. Además, su SDK nativo permite la persistencia de datos offline, garantizando el funcionamiento de la app en supermercados con conectividad inestable o nula.

### 1.2. Requisitos de Hardware y Software
Al tratarse de una aplicación de gestión orientada a texto, listas y cálculos de balances, los requisitos de hardware para el usuario final son muy accesibles, maximizando así la cuota de mercado.

**Para el usuario final (Cliente):**
* **Sistemas Operativos Soportados:** Android 8.0 (Oreo) / iOS 12.0 o superior. Estas versiones garantizan la compatibilidad plena con el SDK de Flutter y las librerías de Firebase.
* **Memoria RAM:** 2 GB de RAM o superior. Cantidad suficiente para mantener los listeners de Firebase en segundo plano.
* **Almacenamiento:** Aproximadamente 50 MB de espacio libre.
* **Conectividad:** Conexión a internet (Wi-Fi, 4G, 5G) para la sincronización en tiempo real.

**Para el equipo de desarrollo (Recursos):**
* Equipos de sobremesa y portátiles con potencia de procesamiento, memoria RAM y almacenamiento para trabajar de manera óptima y con la posibilidad de usar emuladores.
* Conexión a Internet y a la red eléctrica.
* Entorno de trabajo preparado.
* Dispositivos físicos con Android y iOS para el despliegue y testeo en condiciones reales.
* Sistema Operativos: Windows, Linux, macOs.
* Entorno de Desarrollo: Visual Studio Code, Apache NetBeans, Android Studio, Xcode.
* Gestión de Proyecto y Comunicación: Github, Discord, Whatsapp.

### 1.3. Control del Alcance y MoSCoW
Dado que el tiempo de desarrollo está estrictamente limitado a los 8 Sprints planificados, se aplica el método de priorización MoSCoW para definir el alcance exacto del Producto Mínimo Viable (MVP) y evitar la corrupción del alcance (scope creep).

| Categoría | Requisitos funcionales y técnicos | Justificación en el control de alcance |
| :--- | :--- | :--- |
| **Must have (Obligatorio)** | - Autenticación y registro de usuarios.<br>- Creación de grupos de convivencia y unión a grupos existentes.<br>- Añadir tiques de compra y seleccionar productos.<br>- Algoritmo de división de gastos (común, personal, parcial) entre participantes. | Núcleo funcional (MVP). Si estos requisitos no están al 100%, la aplicación no cumple su propósito principal ni los objetivos formativos esenciales. |
| **Should have (Debería tener)** | - Sincronización en tiempo real de la cesta de la compra.<br>- Historial de tiques y cálculo de balances periódicos.<br>- Resumen de gastos del grupo filtrado por meses. | Funcionalidades de alto impacto que aportan gran valor a la experiencia, programables una vez el núcleo esté finalizado. |
| **Could have (Podría tener)** | - Panel de estadísticas de gastos propios cruzando datos de diferentes grupos.<br>- Escaneo inteligente de tiques mediante cámara (OCR/IA).<br>- Exportación de informes mensuales a PDF o Excel. | Mejoras deseables y características secundarias. Solo se abordarán si sobran tiempo y recursos en los últimos Sprints. |
| **Won't have (No tendrá por ahora)** | - Pasarela de pago real con tarjeta bancaria para saldar deudas dentro de la app.<br>- Integración automática con las APIs de los supermercados. | Funcionalidades explícitamente descartadas para esta versión. Se sustituyen por liquidaciones manuales para evitar infraestructuras complejas fuera del alcance del MVP. |

### 1.4. Matriz de Riesgos y Curva de Aprendizaje
El éxito técnico del software puede verse afectado por diversas barreras y riesgos específicos identificados. 

El equipo de desarrollo cuenta con un nivel avanzado y una base sólida en Java (adquirida en los módulos de Acceso a Datos y SGE), lo que garantiza la viabilidad de la construcción de la lógica del backend. Sin embargo, el uso de Flutter (Dart) y Firebase representa un riesgo técnico de probabilidad alta, ya que el equipo debe autoformarse desde cero. 

Para evitar que esta curva de aprendizaje comprometa los plazos de entrega, se planificarán **Spikes Técnicos** acotados estrictamente en el tiempo (time-boxed) durante los primeros Sprints:
* **Spike Técnico 1 (Flutter y UI):** Un experimento de máximo 8 horas asignado al desarrollador Front-End para construir una pantalla de prueba con navegación básica.
* **Spike Técnico 2 (Firebase y Tiempo Real):** Una prueba de concepto (PoC) enfocada exclusivamente en validar la conexión, autenticación (Auth) y lectura/escritura en Cloud Firestore.

**Matriz de Riesgos Técnicos y Mitigación:**

| Riesgo Técnico | Impacto | Probabilidad | Estrategia de Mitigación |
|---|---|---|---|
| **Errores en algoritmos de reparto de céntimos** | **Alto** | Media | Automatización de pruebas unitarias con `flutter_test` / JUnit evaluando casos límite de división decimal e indivisible. |
| **Conflictos de concurrencia en tiempo real** | **Alto** | Media | Implementación de transacciones atómicas en Firebase Cloud Firestore para evitar lecturas/escrituras simultáneas corruptas. |
| **Curva de aprendizaje en Flutter / Dart** | **Medio** | Alta | Realización de Spikes técnicos iniciales y uso de arquitecturas de componentes estándar (Provider / BLoC). |
| **Fallos de conectividad en supermercados** | **Medio** | Alta | Configuración de la persistencia local fuera de línea (offline persistence) nativa del SDK de Firestore. |
| **Retrasos en la aprobación de las Stores** | **Bajo** | Media | Generación y validación temprana de builds de prueba mediante Google Play Internal Testing. |

---