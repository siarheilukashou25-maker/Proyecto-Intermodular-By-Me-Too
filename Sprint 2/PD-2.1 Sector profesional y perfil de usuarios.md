# 2.1. Sector y perfil de usuarios — *By Me Too!*

> **Cómo leer este documento.** El análisis va **de lo macro a lo micro**: primero el país y la sociedad, después la digitalización y el sector, luego el tipo de organización que usará la aplicación, a continuación las personas concretas y, por último, las decisiones de interfaz que se derivan de todo ello.
>
> Cada término técnico, sigla o anglicismo se explica la primera vez que aparece. Las cifras externas proceden de las fuentes del apartado **Referencias** (consultadas el 20/10/2026). Los datos marcados como **[Encuesta]** proceden de la encuesta propia del equipo (N = 75, es decir, 75 personas respondieron), recogida en el apartado 1.1.3 de la memoria.

---

## 2.1.1. Caracterización del sector

### A. Nivel macro: contexto social y económico en España

**Vivienda compartida.** La dificultad de acceso a la vivienda hace que compartir piso sea una solución cada vez más habitual. Según el portal inmobiliario idealista, en 2025 la oferta de habitaciones en piso compartido creció un **19 %** interanual (es decir, respecto al año anterior) y el precio medio de una habitación alcanzó los **425 €/mes** (575 € en Madrid y 600 € en Barcelona) [1].

**Consecuencia para el proyecto:** cada vez más personas sin vínculo familiar conviven y comparten gastos cotidianos, que es exactamente el problema que resuelve *By Me Too!*.

### B. Nivel país: digitalización de la población

| Indicador | Dato | Qué significa para la app | Fuente |
| --- | --- | --- | --- |
| Uso de Internet (16–74 años) | 96,3 % en los últimos 3 meses; 92,5 % a diario (2025) | Casi toda la población potencial está conectada a diario | [2] |
| Hogares solo con móvil | 50,3 % de los hogares no tiene teléfono fijo, solo móvil | El móvil es el dispositivo central del hogar | [2] |
| Compras por Internet | 59,6 % compró en línea en los últimos 3 meses | Los usuarios conocen los flujos de compra digitales | [2] |
| Banca por Internet | 74,7 % la usa | Manejar dinero desde el móvil es un hábito normal | [2] |
| Competencias digitales | 66,5 % tiene habilidades digitales básicas o superiores (INE 2025); según la Comisión Europea, España (66,2 %) supera la media de la UE (55,6 %) (2024) | El usuario medio entiende interfaces móviles estándar, pero no todos son expertos | [2], [4] |

*INE: Instituto Nacional de Estadística, organismo oficial que elabora las estadísticas de España. UE: Unión Europea.*

### C. Nivel sector: pagos y organización doméstica digital

**Ámbito de actividad.** *By Me Too!* se sitúa entre dos sectores digitales:

1. **Finanzas personales y pagos P2P.** *P2P* (del inglés *peer-to-peer*, "de persona a persona") son los pagos que se hacen directamente entre particulares, sin una tienda de por medio; por ejemplo, devolverle a un compañero de piso lo que adelantó.
2. **Organización doméstica y compra de alimentación:** listas de la compra compartidas.

**Tendencia principal: el pago P2P instantáneo ya está normalizado.** Bizum (sistema español de pago instantáneo entre particulares desde la app del banco) tuvo en 2025 **30,6 millones de usuarios**, **1.237 millones de operaciones** (+13,2 %) y un volumen de **67.751 millones de euros** [3]. Pagar ya no es el problema; el problema es **saber cuánto debe cada uno**. Por eso el proyecto no integra pagos dentro de la app (Memoria 1.6.1) y se centra en el cálculo.

**Plataformas móviles.** En España, el 73,19 % de los móviles usa **Android** (sistema de Google) y el 26,8 % **iOS** (sistema de Apple, iPhone) (septiembre 2026) [5]. Un mismo grupo de convivencia suele mezclar ambos, así que la app debe funcionar en los dos.

**Competencia.**

| Tipo de solución | Ejemplos | Qué ofrecen | Qué les falta para nuestro público |
| --- | --- | --- | --- |
| Reparto de gastos | Splitwise, Tricount | Registrar quién pagó y quién debe a quién. Tricount declara más de 20 millones de usuarios [6]; Splitwise se dirige a "amigos y compañeros de piso" [7] | Reparten por gasto total; no gestionan la lista de la compra |
| Listas de la compra | Bring!, Listonic, Google Keep | Listas compartidas en tiempo real | No reparten gastos |
| Mensajería | WhatsApp | Chat de grupo | No está pensada para listas ni cuentas (**[Encuesta]** el 24,2 % organiza la compra por chat) |

### D. Nivel organización: quién usa la aplicación

La app no se dirige a empresas, sino a particulares:

- **B2B** (*business-to-business*, "de empresa a empresa"): productos que una empresa vende a otras empresas (por ejemplo, un programa de contabilidad para despachos).
- **B2C** (*business-to-consumer*, "de empresa a consumidor"): productos dirigidos directamente al usuario final particular.

***By Me Too!* es un producto B2C.** La "organización" que la utiliza no es una empresa, sino un **grupo de convivencia informal**: un piso compartido, una familia o el grupo de un evento.

### E. Nivel micro: la actividad concreta (la compra compartida)

| Característica | Dato | Fuente |
| --- | --- | --- |
| Tamaño del grupo | 2–10 personas | Memoria 1.5 |
| Estructura | Sin jerarquía: todos los miembros son iguales; quien crea el grupo actúa como administrador | Memoria 1.5 |
| Frecuencia | 66,7 % compra cada semana; 90 % cada 2–7 días | **[Encuesta]** |
| Canal | 97 % compra en tienda física (presencial) | **[Encuesta]** |
| Herramientas actuales | 48,5 % libreta compartida, 24,2 % chat, 21,3 % ninguna | **[Encuesta]** |
| Problema principal | 82,7 % olvida productos por no llevar la lista completa | **[Encuesta]** |

### Tabla 1. Resumen del sector y sus características organizativas (de macro a micro)

| Nivel | Característica clave | Dato principal | Fuente |
| --- | --- | --- | --- |
| Social | El piso compartido crece | Oferta de habitaciones +19 %; 425 €/mes | [1] |
| País | Población muy conectada, móvil como centro | 92,5 % usa Internet a diario; 50,3 % hogares solo móvil | [2] |
| País | Competencias digitales medias-altas | 66,5 % básicas o superiores | [2] |
| Sector | Pago P2P normalizado | Bizum: 30,6 M usuarios | [3] |
| Sector | Mercado Android + iOS | 73 % / 27 % | [5] |
| Sector | Competidores no unen lista + reparto | Splitwise, Tricount, Bring! | [6], [7] |
| Organización | B2C: grupo informal sin jerarquía | 2–10 miembros | Memoria 1.5 |
| Actividad | Compra presencial, semanal, con olvidos | 66,7 % semanal; 82,7 % olvida productos | **[Encuesta]** |

### Necesidades tecnológicas del sector

| Necesidad | Requisito tecnológico derivado |
| --- | --- |
| Varias personas editan la misma lista a la vez | **Sincronización en tiempo real**: un cambio en un móvil aparece en los demás en segundos. Se usará **Firebase** (servicio de Google que ofrece base de datos en la nube y autenticación de usuarios) |
| Registrar la compra rápido en el supermercado | Interfaz móvil usable con una mano. **KPI** (*Key Performance Indicator*, "indicador clave de rendimiento", una métrica medible del éxito): registrar 5 productos en ≤ 60 s |
| Reparto justo por producto | Algoritmo de reparto común / personal / parcial con control de céntimos |
| Confianza en los saldos | Historial visible de quién pagó qué y por qué |
| Pago fuera de la app (Bizum, efectivo) | Mostrar importes claros y fáciles de copiar; sin pasarela de pago |
| Datos personales de otras personas | Cumplir el **RGPD** (Reglamento General de Protección de Datos de la UE) y la **LOPDGDD** (Ley Orgánica española de Protección de Datos Personales y garantía de los derechos digitales) |
| Grupos que mezclan Android e iOS | Desarrollo **multiplataforma** (un solo código para varios sistemas) con **Flutter** (herramienta de Google para crear apps para Android, iOS y escritorio a la vez) |

---

## 2.1.2. Segmentación de perfiles de usuario
 
**Segmentar** es dividir a los usuarios en grupos con necesidades parecidas. Cada grupo se describe con una **ficha de persona**:
 
- **User Persona** ("persona de usuario"): personaje ficticio, pero basado en datos reales, que representa a **quien usa** la app: qué hace con ella, dónde, cuándo y qué le cuesta. Sirve para diseñar pantallas, flujos y controles.
- **Buyer Persona** ("persona compradora"): personaje que representa a **quien decide pagar** por el producto: qué le convence, cuánto está dispuesto a pagar y qué le frena. Sirve para el modelo de negocio y el marketing.
Ambas coinciden solo cuando quien usa y quien paga es la misma persona. En un software de empresa (B2B) suelen ser distintas: lo compra un directivo y lo usa un empleado.
 
**Modelo de negocio de *By Me Too!*: freemium.** *Freemium* (de *free*, "gratis", y *premium*) es un modelo en el que la app es gratuita para todos y existe una suscripción opcional de pago con ventajas extra. Por tanto:
 
- **Todos los perfiles son User Persona**, porque todos usan la app, paguen o no.
- **Solo una parte es además Buyer Persona**: quien decide pagar la suscripción premium.
> Nota: la Memoria (1.6.1) excluye los pagos *entre miembros* dentro de la app (las deudas se saldan por Bizum, efectivo o transferencia). La suscripción premium es otra cosa: es el pago del usuario a *By Me Too!*.
 
**Plan gratuito y plan premium (propuesta del equipo):**
 
| | Gratuito | Premium |
| --- | --- | --- |
| Grupos | Número limitado (propuesta: hasta 2 grupos activos) | Más grupos (propuesta: ilimitados) |
| Anuncios | Sí | **Sin anuncios** |
| Escaneo de tiques por **OCR** (*Optical Character Recognition*, "reconocimiento óptico de caracteres": la app lee el texto de una foto del tique) | No | Sí (**versión futura**, Memoria 1.6.1) |
| Lista compartida, reparto y saldos | Sí | Sí |
| **Precio propuesto** | 0 € | **1,99 €/mes o 14,99 €/año** (≈ 37 % de ahorro con el pago anual) |
 
*Justificación del precio.* Es una **propuesta propia del equipo**, no un dato de mercado. Se basa en que: (1) el público principal son estudiantes y jóvenes recién titulados (**[Encuesta]** 70 %), con poco presupuesto; (2) el competidor directo Splitwise también usa un modelo freemium con suscripción mensual o anual que elimina anuncios y añade escaneo de tiques, y limita el plan gratuito a 4 gastos al día [14], [15]; (3) Tricount es totalmente gratuito y sin anuncios [6], así que el premium debe ser barato para que el plan gratuito con anuncios no haga huir al usuario hacia la competencia. El precio exacto de Splitwise Pro no aparece en sus páginas públicas, por lo que no se usa como cifra de comparación. El precio se validará con el grupo piloto (Memoria, OE-X5).
 
Las fichas son **arquetipos** (modelos representativos de un grupo, no personas reales); los nombres y detalles personales son inventados. Se basan en la encuesta (80 % entre 19 y 40 años; 70 % estudiantes o recién titulados) y en los grupos detectados en la memoria (1.2.4): compañeros de piso, familias y grupos de eventos.
 
### Ficha 1 — "La organizadora del piso" (User Persona principal + Buyer Persona)
 
| Campo | Descripción |
| --- | --- |
| **Nombre / edad** | Lucía, 22 años |
| **Rol laboral** | Estudiante universitaria; comparte piso con 3 personas. Hace la compra semanal y adelanta el dinero. **Rol en la app:** administradora del grupo y compradora habitual. |
| **Competencias digitales previas** | Altas. Usa a diario WhatsApp, Instagram, Bizum y banca móvil; ha probado Splitwise o Google Keep. Maneja con soltura gestos táctiles, notificaciones y enlaces compartidos. |
| **Entorno de uso habitual** | Móvil Android. En el supermercado: de pie, empujando el carro, con una mano ocupada y prisa. En casa: en el sofá, revisando el tique. Sesiones cortas, 2–3 veces por semana. |
| **Objetivos principales** | 1) Llevar la lista completa y no olvidar productos. 2) Registrar la compra en menos de un minuto. 3) Marcar qué es común y qué es personal. 4) Recuperar su dinero sin tener que reclamarlo en persona. |
| **Frustraciones** | Mensajes dispersos en el chat, productos duplicados, cálculos con la calculadora, incomodidad al pedir dinero. |
| **Frase** | "Yo pago todo y luego nunca sé cuánto me debe cada uno." |
| **Como Buyer Persona** | **Compradora probable del premium.** Es quien descubre la app y convence al grupo. Motivos para pagar: quitar los anuncios, que abre a diario, y, en el futuro, el OCR para no teclear tiques largos. Freno: presupuesto de estudiante; solo paga si el precio es bajo (pago anual) y la ventaja se nota desde el primer día. |
 
### Ficha 2 — "El compañero que paga" (usuario participante)
 
| Campo | Descripción |
| --- | --- |
| **Nombre / edad** | Andrés, 29 años |
| **Rol laboral** | Trabajador a jornada completa en piso compartido. Casi nunca hace la compra. **Rol en la app:** participante; añade productos y consulta su saldo. |
| **Competencias digitales previas** | Medias-altas. Usa banca móvil y Bizum, pero no quiere aprender herramientas nuevas: espera que la app se entienda sola. |
| **Entorno de uso habitual** | iPhone, en ratos muertos (transporte, descanso del trabajo). Uso breve y esporádico: abrir, ver cuánto debe, hacer un Bizum, cerrar. A veces desde el ordenador del trabajo (versión de escritorio). |
| **Objetivos principales** | 1) Añadir rápido a la lista lo que necesita. 2) Saber de un vistazo cuánto debe y a quién. 3) Entender por qué debe esa cantidad. 4) Saldar la deuda sin discusiones. |
| **Frustraciones** | Pagar productos que no consume, recordatorios insistentes, pantallas cargadas de información. |
| **Frase** | "Dime cuánto es y te hago un Bizum." |
| **Como Buyer Persona** | **No es comprador.** Abre la app poco y no necesita más grupos, así que no pagaría. Es importante que el plan gratuito le resulte cómodo: si los anuncios le molestan, deja de usarla y el grupo entero se resiente. |
 
### Ficha 3 — "La organizadora del evento" (User Persona ocasional + Buyer Persona)
 
| Campo | Descripción |
| --- | --- |
| **Nombre / edad** | Marta, 38 años |
| **Rol laboral** | Profesional con familia; organiza cumpleaños, barbacoas o viajes con amigos y familiares. **Rol en la app:** crea un grupo temporal y compra de forma puntual. |
| **Competencias digitales previas** | Medias. Usa WhatsApp, banca online y compras por Internet; menos habituada a gestos avanzados o a apps de finanzas. |
| **Entorno de uso habitual** | Móvil (Android o iOS) en varias tiendas distintas; después del evento, en casa con varios tiques. Uso intenso durante unos días y luego nada. |
| **Objetivos principales** | 1) Crear el grupo e invitar a todos en segundos (enlace por WhatsApp). 2) Repartir ciertos productos solo entre quienes los consumen (por ejemplo, bebidas alcohólicas o menú infantil). 3) Cerrar el evento con todos los saldos a cero. |
| **Frustraciones** | Que los invitados tengan que registrarse con muchos pasos; perder la cuenta de varios tiques; repartos "a partes iguales" que no son justos. |
| **Frase** | "Quiero cerrar las cuentas del cumpleaños el mismo día." |
| **Como Buyer Persona** | **Compradora posible.** Tiene más poder adquisitivo y crea muchos grupos temporales (cada evento es un grupo), por lo que choca antes con el límite de grupos del plan gratuito. Motivo para pagar: más grupos y, en el futuro, el OCR para los varios tiques de un evento. Freno: uso intermitente; prefiere un pago mensual que pueda cancelar cuando no organiza nada. |
 
---

## 2.1.3. Implicaciones para el diseño de la interfaz

Aquí se traduce todo lo anterior en decisiones de diseño, también de lo general a lo concreto: **plataforma → estructura de pantalla (layouts) → cantidad de información (densidad) → elementos interactivos (controles) → atajos**.

### 1. Interfaces (plataforma)

*Interfaz: la parte de la aplicación con la que el usuario interactúa (pantallas, botones, textos).*

| Decisión | Justificación |
| --- | --- |
| **Mobile-first** ("primero el móvil"): se diseña antes para el móvil y después se adapta al escritorio, que queda como interfaz secundaria (consulta y revisión de tiques) | 50,3 % de hogares solo con móvil [2]; uso en el supermercado (Fichas 1 y 3) |
| Una sola app para **Android e iOS** (Flutter) | 73 % / 27 % [5]; los grupos mezclan ambos sistemas (Fichas 1 y 2) |
| Invitación al grupo mediante **enlace** que se comparte por WhatsApp | **[Encuesta]** el 24,2 % ya organiza la compra por chat; Ficha 3 |

### 2. Layouts (distribución de la pantalla)

*Layout: cómo se colocan y organizan los elementos dentro de la pantalla.*

| Layout | Justificación |
| --- | --- |
| **Barra de navegación inferior** con 3–4 secciones (Cestas, Saldos, Grupo, Perfil) | Queda al alcance del pulgar: en el estudio de Steven Hoober, el 49 % de las interacciones observadas fue con una sola mano [13] |
| **Acciones principales en la mitad inferior** de la pantalla | Mismo motivo [13]; Ficha 1 con el carro |
| **Lista vertical de tarjetas** (bloques rectangulares, uno por producto), separadas en "pendiente" y "comprado" | Lectura rápida en el supermercado |
| **Pantalla de saldos tipo resumen**: arriba, una tarjeta con el saldo propio; debajo, "quién debe a quién" | Ficha 2 |
| **Orientación vertical** (*portrait*, móvil "de pie") como prioritaria | En el mismo estudio, el 90 % del uso con dos manos fue en vertical [13] |
| **Escritorio: dos paneles** (cestas a la izquierda, detalle o tabla a la derecha) | Más espacio disponible; revisión de varios tiques (Ficha 3) |

### 3. Densidad de datos (cuánta información por pantalla)

*Densidad de datos: cantidad de información que se muestra a la vez en una pantalla. Alta densidad = mucha información junta; baja = poca y más espaciada.*

- **Baja densidad en el móvil.** En la pantalla principal solo lo esencial: nombre del producto, quién lo añadió y estado. El saldo se muestra como **una cifra grande con color** (debes / te deben).
- **Divulgación progresiva** (*progressive disclosure*): técnica que muestra primero solo las opciones más importantes y deja el resto en una pantalla secundaria, a la que se llega bajo petición [8]. Así el desglose por producto y el historial no saturan la pantalla, pero siguen disponibles. Responde a la Ficha 2: "dime cuánto es" sin perder el "por qué".
- **Densidad media-alta en escritorio.** Tabla de tiques con columnas (producto, precio, quién pagó, participantes) para revisar varios a la vez (Ficha 3).

### 4. Controles (elementos interactivos)

*Control: cualquier elemento que el usuario toca o rellena: botones, casillas, campos de texto, interruptores…*

| Control | Criterio |
| --- | --- |
| **Zonas táctiles de 44 × 44 pt** como tamaño por defecto (*pt*, punto: unidad de medida de pantalla de Apple, independiente de la resolución). Nunca por debajo de 24 × 24 px (*px*, píxel), mínimo que fija WCAG 2.2 | Apple HIG [9]; WCAG 2.2, criterio 2.5.8 [10]. *HIG* (*Human Interface Guidelines*): guía oficial de diseño de Apple. *WCAG* (*Web Content Accessibility Guidelines*): pautas internacionales de accesibilidad del W3C, el organismo que crea los estándares de la web |
| **Teclado numérico** en los campos de precio y formato automático de euros y céntimos | Recomendación de Nielsen Norman Group (consultora de referencia en usabilidad) de elegir el teclado adecuado a cada campo [11]; KPI ≤ 60 s |
| Etiqueta del campo **encima**, no como *placeholder* (texto gris de ejemplo dentro del campo, que desaparece al escribir) | Nielsen Norman Group [11] |
| **Chips** (pequeñas etiquetas pulsables con el nombre de cada miembro) para elegir participantes, en vez de listas desplegables | Ficha 3 (reparto parcial), menos toques |
| **Contraste mínimo 4,5:1** entre texto y fondo (3:1 en texto grande) | WCAG 2.2, criterio 1.4.3 [12]. El contraste es la diferencia de luminosidad entre texto y fondo; cuanto mayor, más legible |
| Saldos en rojo/verde **siempre con texto o signo** ("Debes 12,40 €") | Las personas con daltonismo no deben depender del color |
| Confirmación y opción **"Deshacer"** al borrar productos o cestas | Varias personas editan la misma lista a la vez |

### 5. Atajos

*Atajo: forma rápida de hacer una acción frecuente con menos pasos.*

| Atajo | Perfil |
| --- | --- |
| **FAB** (*Floating Action Button*, "botón de acción flotante"): botón redondo "+" fijo en una esquina inferior para añadir producto desde cualquier punto de la cesta | Fichas 1 y 2 |
| **Swipe** (deslizar el dedo sobre un elemento) o un toque para marcar un producto como comprado | Ficha 1 (una mano libre) |
| Asignación rápida con chips "Común / Solo yo / Elegir…" | Fichas 1 y 3 |
| "Repetir la última compra" y sugerencias de productos frecuentes | Ficha 1 (**[Encuesta]** compra semanal) |
| Botón **"Copiar importe"** del saldo para pegarlo en Bizum | Ficha 2 [3] |
| En escritorio, atajos de teclado: Ctrl+N (nuevo producto), Intro (confirmar), Supr (eliminar) | Ficha 2 (uso desde el ordenador) |

---

## Referencias

[1] idealista, "La oferta de habitaciones crece un 19%, mientras el precio aumenta un 4% en 2025", 16/01/2026. https://www.idealista.com/news/inmobiliario/vivienda/2026/01/16/879857-la-oferta-de-habitaciones-crece-un-19-mientras-el-precio-aumenta-un-4-en-2025

[2] Instituto Nacional de Estadística (INE), "Encuesta sobre Equipamiento y Uso de Tecnologías de Información y Comunicación en los Hogares (TIC-H). Año 2025", nota de prensa, 20/11/2025. https://www.ine.es/dyngs/Prensa/TICH2025.htm

[3] EFE / Infobae, "El volumen de operaciones con Bizum creció un 53 % en 2025 y se situó en 67.751 millones", 19/01/2026. https://www.infobae.com/espana/agencias/2026/01/19/el-volumen-de-operaciones-con-bizum-crecio-un-53-en-2025-y-se-situo-en-67751-millones/

[4] Comisión Europea, Digital Skills and Jobs Platform, "Spain: a snapshot of digital skills". https://digital-skills-jobs.europa.eu/en/latest/briefs/spain-snapshot-digital-skills

[5] StatCounter Global Stats, "Mobile Operating System Market Share Spain" (septiembre 2026). https://gs.statcounter.com/os-market-share/mobile/spain

[6] Tricount, sitio oficial. https://www.tricount.com/

[7] Splitwise, sitio oficial. https://www.splitwise.com/

[8] Nielsen Norman Group, "Progressive Disclosure". https://www.nngroup.com/articles/progressive-disclosure/

[9] Apple, Human Interface Guidelines, "Accessibility". https://developer.apple.com/design/human-interface-guidelines/accessibility

[10] W3C, "Understanding SC 2.5.8: Target Size (Minimum)", WCAG 2.2. https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html

[11] Nielsen Norman Group, "Mobile Input Checklist". https://www.nngroup.com/articles/mobile-input-checklist/

[12] W3C, "Understanding SC 1.4.3: Contrast (Minimum)", WCAG 2.2. https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html

[13] S. Hoober, "How Do Users Really Hold Mobile Devices?", UXmatters, 18/02/2013. https://www.uxmatters.com/mt/archives/2013/02/how-do-users-really-hold-mobile-devices.php

Fuente interna: encuesta del equipo *By Me Too!* (N = 75), Memoria del proyecto, apartado 1.1.3.
