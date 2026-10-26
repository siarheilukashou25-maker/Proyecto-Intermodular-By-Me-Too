# DI 2.3 — Análisis comparativo de mercado (benchmarking)

**Proyecto:** By Me Too! / Comprame!

## 1. Introducción

El objetivo de este análisis de mercado es estudiar diferentes aplicaciones que existen actualmente para gestionar gastos compartidos y organizar las cuentas entre varias personas. A través de esta comparación, se pretende conocer las soluciones disponibles, identificar sus principales ventajas y limitaciones y determinar qué valor diferencial podría aportar nuestro proyecto.

**By Me Too! / Comprame!** es una propuesta de aplicación móvil orientada a facilitar la organización de las compras compartidas y el reparto de gastos entre personas que conviven. La idea es permitir la creación de grupos de convivencia, el registro de compras, la selección de los participantes en cada gasto y la consulta de los saldos correspondientes.

Como el proyecto todavía se encuentra en fase de planificación, las características descritas en este documento se consideran objetivos y propuestas para el futuro desarrollo, no funcionalidades que ya estén implementadas.

## 2.3.1. Identificación de software competidor

Para realizar el benchmarking se han seleccionado cuatro alternativas que permiten registrar gastos, compartirlos con otras personas y calcular cuánto debe cada participante.

### 1. Splitwise

**Página oficial:** https://www.splitwise.com/

Splitwise es una aplicación diseñada para registrar gastos compartidos entre amigos, parejas y compañeros de piso. Permite crear grupos, introducir pagos, repartir gastos y consultar los saldos pendientes. También ofrece acceso desde dispositivos móviles y la web, recordatorios de pagos y funciones avanzadas incluidas en su versión de pago. El plan gratuito tiene restricciones en el número de gastos que se pueden añadir diariamente, mientras que Splitwise Pro elimina ese límite e incluye herramientas adicionales.

**Ventajas:**
- Permite organizar los gastos por grupos.
- Facilita el seguimiento de las deudas entre participantes.
- Está disponible en dispositivos móviles y en la web.
- Ofrece funciones avanzadas para gestionar los gastos.

**Limitaciones:**
- La versión gratuita tiene restricciones en el número de gastos diarios.
- Algunas funciones avanzadas requieren una suscripción.
- Está centrada en el reparto de gastos y no específicamente en la planificación de las compras domésticas.

### 2. tricount

**Página oficial:** https://www.tricount.com/es-es/

tricount es una aplicación para gestionar gastos compartidos entre amigos, parejas y compañeros de piso. Permite crear grupos, añadir gastos, indicar quién ha pagado y seleccionar quién participa en cada gasto. También ofrece repartos personalizados, fotografías de recibos y seguimiento de saldos. Su página oficial presenta el registro de gastos compartidos como un servicio gratuito.

**Ventajas:**
- Interfaz orientada a registrar y repartir gastos de forma sencilla.
- Permite consultar quién ha pagado y cuánto debe cada persona.
- Ofrece repartos personalizados y fotografías de recibos.
- Puede utilizarse para organizar gastos de viviendas compartidas.

**Limitaciones:**
- Su objetivo principal es controlar los gastos y saldar deudas.
- La planificación específica de una compra doméstica podría requerir funciones adicionales.
- También está orientada a viajes y otros gastos en grupo.

### 3. Splid

**Página oficial:** https://splid.teamturtle.com/

Splid es una aplicación centrada en simplificar el reparto de gastos entre varias personas. Permite crear grupos, registrar pagos, dividir importes de manera equitativa o personalizada y calcular las cantidades que debe cada participante. También admite el uso sin conexión, diferentes monedas y la exportación de resúmenes, aunque algunas opciones pueden requerir una compra dentro de la aplicación.

**Ventajas:**
- Se centra en las funciones esenciales de reparto de gastos.
- Permite trabajar sin conexión a Internet.
- Admite diferentes monedas y repartos no equitativos.
- Ofrece resúmenes exportables.

**Limitaciones:**
- Su enfoque principal es el reparto de gastos, no la organización integral de las compras domésticas.
- Algunas opciones de exportación pueden ser de pago.
- La disponibilidad y la experiencia de uso dependen de la plataforma y la versión utilizada.

### 4. Spliit

**Página oficial:** https://spliit.app/  
**Repositorio del proyecto:** https://github.com/spliit-app/spliit

Spliit es una alternativa de código abierto para compartir gastos. Permite crear grupos, registrar gastos, consultar balances, introducir reembolsos y clasificar los gastos por categorías. También permite adjuntar imágenes y utilizar una aplicación web progresiva (PWA). Al disponer de código abierto bajo licencia MIT, ofrece la posibilidad de estudiar el código y desplegar una instancia propia. No obstante, alojarla requiere conocimientos técnicos y recursos para mantener el servicio y la base de datos.

**Ventajas:**
- Es una solución de código abierto.
- Permite consultar y repartir los gastos de un grupo.
- Ofrece categorías y búsqueda de gastos.
- Puede desplegarse en una infraestructura propia.

**Limitaciones:**
- El alojamiento propio requiere configuración y mantenimiento.
- Su función principal sigue siendo la gestión de gastos compartidos.
- Las funciones y la experiencia pueden depender de la instancia utilizada.

## 2.3.2. Análisis comparativo

Para comparar las alternativas se han utilizado criterios relacionados con el coste, la facilidad de aprendizaje, la experiencia de usuario, la compatibilidad entre plataformas, la generación de informes y la capacidad de adaptación.

### comparativa

| Criterio | Splitwise | tricount | Splid | Spliit | By Me Too! / Comprame! (propuesta) |
|---|---|---|---|---|---|
| **Coste de uso** | Plan gratuito con límites y suscripción Pro. | Registro de gastos gratuito según su web oficial. | Descarga gratuita con algunas compras dentro de la aplicación. | Uso gratuito de la instancia oficial; alojamiento propio con costes potenciales. | Por definir según las decisiones del proyecto. |
| **Coste de implantación** | No exige servidor propio al usuario. | No exige gestionar infraestructura propia. | No exige gestionar infraestructura propia. | La instalación propia puede requerir configuración y mantenimiento. | Se valorarán desarrollo, pruebas, publicación y mantenimiento. |
| **Curva de aprendizaje** | Baja: registro de gastos y consulta de saldos. | Baja: creación de grupos y gastos sencilla. | Baja: se centra en el reparto de gastos. | Baja o media, según la instancia y el usuario. | Se buscará una curva baja con procesos sencillos. |
| **Experiencia de usuario** | Seguimiento de gastos y deudas. | Compartir gastos de forma sencilla. | Interfaz centrada en funciones esenciales. | Interfaz web para grupos y gastos. | Se priorizarán compras domésticas y saldos claros. |
| **Multiplataforma** | Móvil y web. | Aplicaciones móviles; comprobar disponibilidad por plataforma. | Disponibilidad móvil; comprobar opciones por dispositivo. | Aplicación web progresiva y ecosistema web. | Se plantea como aplicación móvil; plataformas por determinar. |
| **Creación de grupos** | Sí. | Sí. | Sí. | Sí. | Función prevista. |
| **Registro de gastos** | Sí. | Sí. | Sí. | Sí. | Función prevista para compras compartidas. |
| **Reparto entre participantes** | Sí. | Sí, con reparto personalizado. | Sí, con repartos personalizados. | Sí, con reparto desigual. | Se plantea seleccionar participantes y reparto. |
| **Consulta de saldos** | Sí. | Sí. | Sí. | Sí. | Función prevista. |
| **Informes y exportación** | Herramientas de análisis; algunas son Pro. | Información de gastos; opciones variables. | Exportación de resúmenes; algunas opciones de pago. | Balances y herramientas de gestión. | Se estudiarán resúmenes de compras domésticas. |
| **Extensibilidad** | Depende de las opciones de la plataforma. | Depende de las funciones del servicio. | Depende de las funciones de la aplicación. | Código abierto: puede modificarse y mantenerse. | Se valorará una estructura que facilite añadir funciones. |
| **Limitaciones** | Límites gratuitos y funciones avanzadas de pago. | Orientación general al reparto de gastos. | Enfoque reducido al reparto y control de gastos. | El despliegue propio requiere conocimientos técnicos. | Las funciones y la experiencia aún no están validadas. |

> **Nota:** La curva de aprendizaje y la experiencia de usuario son valoraciones cualitativas basadas en el enfoque y las funciones descritas por cada producto, no en una prueba de usabilidad realizada por nuestro equipo. Los precios y las condiciones comerciales pueden cambiar.

### Comparación del coste de implantación

Es importante distinguir entre el coste que asume una persona usuaria y el coste de desarrollar y mantener una aplicación.

- **Aplicaciones comerciales:** Splitwise, tricount y Splid permiten utilizar sus servicios sin desplegar un servidor propio, aunque pueden incluir límites o compras dentro de la aplicación.
- **Software de código abierto:** Spliit permite estudiar y desplegar el código, pero una instalación propia puede implicar gastos de alojamiento, base de datos, dominio, mantenimiento y administración.
- **By Me Too! / Comprame!:** al tratarse de un proyecto en desarrollo, todavía no se puede establecer un coste definitivo. Será necesario valorar el tiempo de programación, las pruebas, la infraestructura y el mantenimiento.

Que una aplicación sea gratuita para el usuario no significa que su desarrollo y mantenimiento no tengan costes.

## Comparación de usabilidad

Las cuatro alternativas estudiadas permiten registrar gastos y consultar el resultado de los repartos. Por ello, By Me Too! no debería diferenciarse únicamente por ofrecer estas mismas funciones. La oportunidad consiste en estudiar cómo facilitar una tarea concreta: organizar las compras que comparten las personas de una vivienda y conocer con claridad cómo se distribuye su coste.

Para conseguirlo, se propone priorizar:

- Un acceso sencillo a los grupos de convivencia.
- Un registro de compras con los datos imprescindibles.
- Una selección clara de las personas que participan en cada compra.
- Una presentación comprensible de los saldos.
- Una navegación consistente y adaptada a dispositivos móviles.
- Mensajes claros al guardar los datos o cuando se produzca un error.

Estas decisiones deberán comprobarse mediante pruebas con usuarios cuando exista una primera versión funcional.

## 3. Justificación de la propuesta y ventajas competitivas

El análisis muestra que ya existen aplicaciones maduras para dividir gastos. Por tanto, no sería correcto afirmar que By Me Too! es la primera aplicación que permite registrar compras compartidas, crear grupos o calcular deudas.

La propuesta de valor debe centrarse en la experiencia que se pretende ofrecer a las personas que comparten vivienda y realizan compras para el hogar.

### Ventaja 1. Enfoque en las compras domésticas

Mientras las alternativas estudiadas sirven para distintos contextos —como viajes, cenas, eventos o convivencia—, By Me Too! pretende dar prioridad a las compras compartidas de la vida cotidiana. Este enfoque permitiría organizar la información alrededor de qué compras se han realizado para el hogar, quién ha participado y cómo se distribuye el importe.

### Ventaja 2. Organización de los grupos de convivencia

La aplicación plantea utilizar grupos que representen a las personas que comparten vivienda. Esto permitiría reunir las compras y los saldos de cada grupo en un mismo espacio, facilitando su consulta.

### Ventaja 3. Registro de compras orientado a la sencillez

Se propone diseñar un proceso de registro que solicite únicamente la información necesaria para añadir una compra y seleccionar a sus participantes. Reducir los pasos innecesarios puede facilitar el uso habitual de la aplicación.

### Ventaja 4. Claridad en el reparto de los gastos

Una prioridad será presentar los saldos de forma comprensible para que cada integrante pueda saber cuánto le corresponde y cómo queda el balance del grupo. La información deberá mostrarse de manera clara, evitando cálculos manuales y reduciendo posibles malentendidos.

### Ventaja 5. Diseño centrado en la accesibilidad y la usabilidad

El proyecto también tendrá en cuenta las recomendaciones del manual de accesibilidad y usabilidad elaborado en la actividad DI 2.2. Se propone utilizar textos legibles, contrastes adecuados, controles fáciles de identificar, formularios claros y una navegación consistente.

### Ventaja 6. Posibilidad de evolución

Al tratarse de un proyecto propio, el equipo podrá priorizar las mejoras según las necesidades detectadas durante el desarrollo y las pruebas. Entre las posibles ampliaciones que se podrían estudiar están los resúmenes periódicos de compras, la clasificación por categorías o la consulta del gasto acumulado del hogar. Estas funciones deberán valorarse según el alcance del proyecto y no se consideran implementadas actualmente.

## 4. Limitaciones y aspectos que deben validarse

Aunque la propuesta tiene un enfoque concreto, todavía no se puede afirmar que sea mejor que las alternativas existentes. Para justificar una ventaja competitiva real, será necesario desarrollar una primera versión y compararla con las necesidades de sus usuarios.

Durante el desarrollo se deberán comprobar los siguientes aspectos:

1. **Facilidad de uso:** medir si los usuarios pueden registrar una compra y consultar el saldo sin ayuda.
2. **Rapidez:** comprobar cuántos pasos son necesarios para completar las tareas habituales.
3. **Comprensión de los saldos:** verificar que las personas entienden cuánto les corresponde pagar.
4. **Accesibilidad:** revisar el contraste, la legibilidad, los controles y los mensajes de error.
5. **Compatibilidad:** probar la aplicación en los dispositivos y plataformas que finalmente se decidan.
6. **Utilidad:** preguntar a personas que compartan vivienda si las funciones propuestas resuelven sus necesidades cotidianas.
7. **Mantenimiento:** valorar los recursos necesarios para corregir errores y añadir mejoras.

También habrá que considerar que los competidores ya disponen de funciones que pueden resultar suficientes para muchos usuarios. Por ello, la diferenciación deberá demostrarse mediante una experiencia útil y sencilla, no solo mediante una lista de características.

## 5. Conclusión

El benchmarking realizado permite identificar varias alternativas consolidadas para compartir gastos: Splitwise, tricount, Splid y Spliit. Todas ofrecen herramientas para registrar pagos, organizar grupos o calcular balances, aunque presentan diferencias en sus modelos de precios, funciones, plataformas y posibilidades de personalización.

A partir de este análisis, se propone orientar By Me Too! / Comprame! hacia la organización de las compras domésticas entre personas que conviven. Su posible valor diferencial estará en ofrecer un proceso sencillo para registrar compras, seleccionar a los participantes y consultar el reparto de los gastos del hogar.

**La ventaja competitiva no consiste en inventar el reparto de gastos, sino en adaptar esa experiencia a las necesidades concretas de la convivencia y facilitar su uso diario.**

Esta ventaja es, por ahora, una hipótesis de diseño. Para confirmarla, será necesario desarrollar la aplicación, realizar pruebas de usabilidad y accesibilidad y recoger las opiniones de usuarios potenciales.


## 6. Fuentes consultadas

[1] Splitwise, “Splitwise: Share expenses with friends and family.” [En línea]. Disponible en: https://www.splitwise.com/. [Accedido: 23-oct-2026].

[2] Splitwise, “Splitwise Pro.” [En línea]. Disponible en: https://www.splitwise.com/pro. [Accedido: 23-oct-2026].

[3] Splitwise, “What is Splitwise Pro?” *Splitwise Knowledge Base*. [En línea]. Disponible en: https://kb.splitwise.com/pro/what-is-splitwise-pro. [Accedido: 24-oct-2026].

[4] tricount, “tricount: Comparte gastos fácilmente.” [En línea]. Disponible en: https://www.tricount.com/es-es/. [Accedido: 24-oct-2026].

[5] tricount, “Features.” [En línea]. Disponible en: https://www.tricount.com/es-es/features. [Accedido: 25-oct-2026].

[6] Team Turtle, “Splid – Split group bills,” *Google Play Store*. [En línea]. Disponible en: https://play.google.com/store/apps/details?id=splid.teamturtle.com.splid. [Accedido: 25-oct-2026].

[7] Spliit, “Spliit — Split expenses with friends.” [En línea]. Disponible en: https://spliit.app/. [Accedido: 25-oct-2026].

[8] Spliit, “Spliit: Open-source expense splitting application,” *GitHub repository*. [En línea]. Disponible en: https://github.com/spliit-app/spliit. [Accedido: 25-oct-2026].

[9] By Me Too!, “Repositorio del proyecto By Me Too! / Comprame!,” *GitHub*. [En línea]. Disponible en: https://github.com/siarheilukashou25-maker/By-Me-Too. [Accedido: 25-oct-2026].
