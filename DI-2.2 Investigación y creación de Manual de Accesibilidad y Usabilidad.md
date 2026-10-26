# DI 2.2 – Investigación y creación de un manual de accesibilidad y usabilidad

## 1. Introducción

Cuando se desarrolla una aplicación, es importante tener en cuenta tanto su funcionamiento como la facilidad con la que los usuarios pueden utilizarla. Una aplicación debe permitir realizar las tareas para las que ha sido diseñada, pero también debe ofrecer una interfaz clara, intuitiva y accesible.

La accesibilidad y la usabilidad son dos aspectos fundamentales en el diseño de interfaces. La accesibilidad busca reducir las barreras que pueden dificultar el uso de una aplicación, mientras que la usabilidad se centra en conseguir que los usuarios puedan utilizarla de forma sencilla y eficiente.

El objetivo de este manual es investigar las principales características, pautas y estándares relacionados con la accesibilidad y la usabilidad, y establecer una serie de medidas que sirvan como referencia durante el desarrollo de nuestro proyecto.

En este caso, el manual está orientado a **By Me Too! / Comprame!**, una aplicación móvil destinada a facilitar la gestión de compras compartidas y el reparto de gastos entre personas que conviven.

Como el desarrollo de las interfaces todavía no ha comenzado, las medidas recogidas en este documento se plantean como recomendaciones que se tendrán en cuenta durante las futuras fases de diseño y programación. Posteriormente, se podrán comprobar mediante pruebas si se han aplicado correctamente.

## 2. Accesibilidad

### 2.1. ¿Qué es la accesibilidad?

La accesibilidad digital consiste en diseñar aplicaciones que puedan ser utilizadas por el mayor número de personas posible, independientemente de sus capacidades o necesidades.

Algunas personas pueden tener dificultades para distinguir determinados colores, leer textos pequeños o utilizar una pantalla táctil. Otras pueden necesitar tecnologías de apoyo, como lectores de pantalla, para acceder a la información.

Por este motivo, es importante diseñar interfaces que reduzcan estas barreras y permitan a los usuarios acceder a las funciones de la aplicación.

La accesibilidad no debe considerarse únicamente al final del desarrollo, sino desde las primeras decisiones relacionadas con el diseño de la interfaz.

### 2.2. Importancia de la accesibilidad

Aplicar medidas de accesibilidad permite que más personas puedan utilizar una aplicación de forma autónoma y comprender correctamente la información que presenta.

Además, muchas de estas medidas benefician a todos los usuarios. Por ejemplo, utilizar textos claros, botones fáciles de identificar y mensajes de error comprensibles mejora la experiencia general.

En nuestro proyecto, la accesibilidad será especialmente importante en las pantallas de registro de compras, consulta de gastos y visualización de los importes correspondientes a cada miembro del grupo.

### 2.3. Principales pautas de accesibilidad

Para desarrollar una interfaz accesible, se deben tener en cuenta las siguientes recomendaciones:

- Utilizar combinaciones de colores que permitan distinguir correctamente los textos del fondo.
- Mantener un tamaño de letra adecuado y facilitar la lectura del contenido.
- No utilizar únicamente el color para transmitir información importante.
- Proporcionar nombres o descripciones accesibles a los botones y otros elementos interactivos.
- Permitir que los usuarios utilicen las funciones de la aplicación mediante los mecanismos de navegación compatibles con la plataforma.
- Organizar la información de forma lógica y coherente.
- Evitar que los elementos interactivos sean demasiado pequeños o difíciles de utilizar.
- Mostrar los errores mediante mensajes claros que permitan comprender cómo solucionarlos.

Estas recomendaciones ayudarán a reducir las dificultades de uso y servirán como referencia durante el diseño de las interfaces.

## 3. Usabilidad

### 3.1. ¿Qué es la usabilidad?

La usabilidad se refiere a la facilidad con la que una persona puede aprender a utilizar una aplicación, comprender su funcionamiento y completar las tareas que necesita realizar.

Una aplicación con buena usabilidad presenta la información de manera ordenada, utiliza elementos reconocibles y permite realizar las acciones principales sin generar confusión.

Por ejemplo, al registrar una compra, el usuario debería poder identificar fácilmente dónde introducir el nombre del producto, su precio y las personas que participan en el gasto.

### 3.2. Importancia de la usabilidad

Una buena usabilidad permite reducir los errores y facilita que los usuarios completen sus tareas sin tener que dedicar demasiado tiempo a comprender la interfaz.

Por el contrario, una aplicación con una navegación confusa, formularios complicados o información desorganizada puede provocar que los usuarios cometan errores o tengan dificultades para utilizar determinadas funciones.

En By Me Too! / Comprame!, la usabilidad tendrá especial importancia porque los usuarios necesitarán registrar compras, consultar gastos y comprender cómo se distribuyen los importes entre los integrantes de un grupo.

Por tanto, las principales funciones deberán ser fáciles de localizar y utilizar.

### 3.3. Principales características de una interfaz usable

Para conseguir una buena usabilidad, se tendrán en cuenta los siguientes principios:

- **Claridad:** la información debe presentarse de forma comprensible.
- **Consistencia:** los elementos que cumplen funciones similares deben mantener un diseño y comportamiento coherentes.
- **Facilidad de aprendizaje:** los usuarios deben poder comprender rápidamente cómo utilizar la aplicación.
- **Prevención de errores:** la interfaz debe ayudar a evitar errores y facilitar su corrección.
- **Retroalimentación:** la aplicación debe informar sobre el resultado de las acciones realizadas.
- **Eficiencia:** las tareas habituales deben poder completarse sin pasos innecesarios.
- **Simplicidad:** se debe evitar la presencia de elementos que no aporten valor o dificulten la navegación.

Estos principios servirán como guía para diseñar una aplicación fácil de utilizar y adaptada a las necesidades de sus usuarios.

## 4. Estándares y recomendaciones

Existen diferentes estándares y recomendaciones que ayudan a diseñar interfaces accesibles y fáciles de utilizar. Estos documentos sirven como referencia para identificar buenas prácticas y establecer criterios durante el desarrollo.

### 4.1. WCAG

Las WCAG (*Web Content Accessibility Guidelines*) son las pautas de accesibilidad para el contenido web desarrolladas por el World Wide Web Consortium (W3C).

Su objetivo es establecer criterios que permitan mejorar la accesibilidad del contenido y facilitar su uso a personas con diferentes capacidades.

La versión WCAG 2.2 constituye una referencia actual para evaluar la accesibilidad. Aunque se centra en el contenido web, sus criterios también pueden orientar el diseño de aplicaciones móviles. El W3C dispone de documentación específica para explicar cómo aplicar estas pautas a las aplicaciones móviles.

Las WCAG se organizan en cuatro principios fundamentales:

- **Perceptible:** la información debe poder percibirse. Por ejemplo, los textos deben ser legibles y las imágenes informativas deben disponer de alternativas adecuadas.
- **Operable:** los componentes y funciones deben poder utilizarse mediante los mecanismos de interacción disponibles.
- **Comprensible:** la información y el funcionamiento de la interfaz deben resultar fáciles de entender.
- **Robusto:** el contenido debe poder interpretarse correctamente mediante diferentes tecnologías y tecnologías de apoyo compatibles.

Estos principios servirán como referencia para tomar decisiones de diseño y revisar posteriormente las interfaces de la aplicación.

### 4.2. Recomendaciones de usabilidad

Además de las pautas de accesibilidad, existen recomendaciones generales que ayudan a mejorar la experiencia de los usuarios.

Entre las más importantes se encuentran:

- Mantener una navegación sencilla.
- Utilizar nombres claros para los botones y las opciones de los menús.
- Mostrar mensajes que informen del resultado de las acciones.
- Evitar pasos innecesarios en las tareas habituales.
- Mantener una estructura visual coherente entre las pantallas.
- Facilitar la identificación y corrección de errores.
- Presentar la información de forma ordenada.
- Evitar solicitar información que no sea necesaria para completar una tarea.

Estas recomendaciones serán útiles para diseñar las futuras pantallas y facilitar el uso de las principales funciones del proyecto.

## 5. Medidas previstas para las interfaces del proyecto

En este apartado se recogen las medidas de accesibilidad y usabilidad que se tendrán en cuenta durante el diseño y desarrollo de By Me Too! / Comprame!.

Como las interfaces todavía no se han implementado, las medidas se presentan como criterios previstos para orientar el trabajo. Su aplicación se comprobará a medida que avance el desarrollo.

### 5.1. Contraste de colores

**Medida prevista:**

Se utilizarán combinaciones de colores que permitan distinguir correctamente los textos, los fondos y los elementos interactivos.

También se evitará utilizar exclusivamente el color para diferenciar información importante, como los gastos pendientes o los importes correspondientes a cada persona.

Como referencia, se tendrán en cuenta los criterios de contraste de las WCAG 2.2. Para el texto normal, el nivel AA establece una relación de contraste mínima de 4,5:1, salvo las excepciones contempladas en las pautas.

**Importancia:**

Un contraste adecuado facilita la lectura y permite identificar mejor la información. Esto resulta especialmente importante en una aplicación donde los usuarios necesitarán consultar precios, cantidades y balances económicos.

### 5.2. Tamaño y legibilidad del texto

**Medida prevista:**

Se utilizarán fuentes legibles y tamaños de texto adecuados para dispositivos móviles. También se procurará que exista una separación suficiente entre los distintos elementos y que el contenido pueda visualizarse correctamente cuando el usuario amplíe el texto, siempre que la plataforma lo permita.

**Importancia:**

Estas medidas facilitan la lectura y ayudan a evitar que los usuarios tengan dificultades para comprender los datos mostrados.

En nuestra aplicación, será importante que los precios, los nombres de los productos y los balances puedan consultarse sin esfuerzo.

### 5.3. Identificación de botones y elementos interactivos

**Medida prevista:**

Los botones, iconos y controles tendrán nombres o etiquetas que permitan identificar claramente su función.

Por ejemplo, las acciones para añadir una compra, editar un gasto o consultar un balance deberán ser fáciles de distinguir.

Cuando se utilicen iconos sin texto visible, se procurará proporcionar un nombre accesible que explique su función.

**Importancia:**

Esta medida facilita la comprensión de la interfaz y permite que los usuarios identifiquen las acciones disponibles sin tener que adivinar su significado.

También favorece el uso de tecnologías de apoyo.

### 5.4. Navegación accesible

**Medida prevista:**

Se diseñará una navegación coherente entre las distintas pantallas y se tendrá en cuenta la compatibilidad con las funciones de accesibilidad de la plataforma móvil.

Los elementos interactivos deberán poder identificarse y utilizarse correctamente mediante los mecanismos de navegación compatibles con la aplicación.

**Importancia:**

Una navegación clara facilita el acceso a las diferentes funciones y evita que los usuarios se pierdan al cambiar de pantalla.

Además, tener en cuenta la accesibilidad desde el principio permite detectar posibles barreras antes de que el diseño esté terminado.

### 5.5. Organización de la información

**Medida prevista:**

La información se organizará mediante secciones diferenciadas y una jerarquía visual coherente.

Las pantallas relacionadas con las compras, los integrantes del grupo y los balances deberán presentar los datos de forma ordenada, dando prioridad a la información más relevante para cada tarea.

**Importancia:**

Una buena organización permite localizar rápidamente los datos necesarios y facilita la comprensión del funcionamiento de la aplicación.

En particular, ayudará a que los usuarios distingan entre las compras registradas, los participantes y los importes asociados.

### 5.6. Formularios para registrar compras

**Medida prevista:**

El formulario para registrar una compra deberá identificar claramente los datos que se deben introducir, como el nombre del producto y su precio, así como las personas que participan en el gasto cuando corresponda.

Los campos estarán correctamente etiquetados y los errores de introducción se comunicarán mediante mensajes comprensibles.

También se evitarán campos innecesarios que puedan complicar el proceso.

**Importancia:**

Un formulario sencillo facilita el registro de las compras y reduce la posibilidad de introducir información incorrecta.

Esta medida es especialmente relevante porque el registro de compras constituye una de las funciones principales del proyecto.

### 5.7. Visualización y reparto de gastos

**Medida prevista:**

Los importes y balances se presentarán de manera clara, indicando a qué persona o grupo corresponde cada cantidad.

Cuando se muestre el reparto de un gasto, se procurará que el usuario pueda entender cómo se distribuye el importe y qué cantidad corresponde a cada participante.

No se utilizará únicamente el color para indicar si un importe está pendiente, pagado o asociado a una determinada situación.

**Importancia:**

La información económica debe ser fácil de interpretar para evitar confusiones entre los integrantes del grupo.

Una presentación clara de los importes ayudará a los usuarios a comprender la distribución de los gastos y consultar su situación económica dentro de la aplicación.

### 5.8. Diseño adaptable a dispositivos móviles

**Medida prevista:**

La interfaz se diseñará teniendo en cuenta los tamaños de pantalla de los dispositivos móviles en los que se vaya a utilizar la aplicación.

Se procurará que los textos sean legibles, que la información no quede cortada y que los elementos interactivos dispongan de espacio suficiente para utilizarlos cómodamente.

También se tendrá en cuenta la posibilidad de ampliar el contenido y las preferencias de visualización compatibles con la plataforma.

**Importancia:**

Un diseño adaptado facilita el uso de la aplicación en diferentes dispositivos y mejora la experiencia general.

Además, disponer de elementos fáciles de identificar y pulsar resulta importante para las personas con dificultades de visión o de movilidad.

### 5.9. Consistencia visual

**Medida prevista:**

Se mantendrán criterios comunes de diseño en las distintas pantallas, especialmente en los botones, los colores, la tipografía, los iconos y la distribución de los elementos.

Las acciones similares deberán presentarse de una manera coherente.

**Importancia:**

La consistencia visual facilita el aprendizaje de la aplicación y permite que los usuarios reconozcan los elementos que ya conocen.

Esto ayudará a que las funciones de gestión de compras y consulta de gastos resulten más intuitivas.

### 5.10. Mensajes de confirmación y error

**Medida prevista:**

La aplicación proporcionará mensajes claros cuando una acción se complete correctamente o cuando se produzca un error.

Por ejemplo, después de registrar una compra, se podrá mostrar una confirmación que indique que se ha guardado correctamente.

Cuando se detecte un dato incorrecto, el mensaje deberá explicar el problema y, cuando sea posible, cómo solucionarlo.

En las acciones que puedan provocar la pérdida de información, como eliminar una compra, se valorará incluir una confirmación previa.

**Importancia:**

Los mensajes informativos permiten que los usuarios comprendan el resultado de sus acciones y sepan cómo actuar ante un error.

Además, las confirmaciones en operaciones importantes pueden ayudar a prevenir modificaciones o eliminaciones accidentales.

### 5.11. Simplicidad de la navegación

**Medida prevista:**

Se procurará que las funciones principales de la aplicación sean fáciles de localizar y que las tareas habituales puedan completarse sin pasos innecesarios.

La navegación deberá permitir acceder de forma clara a las compras, los grupos y la información relacionada con los gastos.

**Importancia:**

Una navegación sencilla reduce el tiempo necesario para aprender a utilizar la aplicación y facilita su uso habitual.

En By Me Too! / Comprame!, esto será importante para que los usuarios puedan registrar compras y consultar balances sin tener que recorrer demasiadas pantallas.

## 6. Plan de comprobación de accesibilidad y usabilidad

Una vez que comience el desarrollo de la aplicación, será necesario comprobar que las medidas propuestas se han aplicado correctamente.

Las pruebas se realizarán de forma progresiva, a medida que se desarrollen las diferentes pantallas y funcionalidades.

### 6.1. Revisión de accesibilidad

Se realizarán las siguientes comprobaciones:

- Revisar el contraste entre los textos y los fondos.
- Comprobar que el tamaño del texto permite leer correctamente la información.
- Verificar que los botones y controles tienen nombres accesibles.
- Revisar que la información no depende únicamente del color.
- Comprobar el funcionamiento con las herramientas de accesibilidad disponibles en la plataforma móvil.
- Verificar que los elementos interactivos se pueden identificar y utilizar correctamente.

### 6.2. Revisión de usabilidad

Para comprobar la facilidad de uso de la aplicación, se revisarán aspectos como los siguientes:

- Comprobar si las funciones principales se encuentran fácilmente.
- Verificar que los formularios se entienden y se pueden completar sin dificultades innecesarias.
- Revisar que los mensajes de error explican cómo corregir los problemas.
- Comprobar que las compras y los balances se presentan de forma clara.
- Observar si los usuarios pueden completar las tareas principales sin ayuda.
- Identificar pasos innecesarios o elementos que puedan generar confusión.

### 6.3. Herramientas y pruebas

Se podrán utilizar herramientas automáticas para detectar determinados problemas técnicos, junto con revisiones manuales de las interfaces.

En función de la tecnología utilizada para desarrollar la aplicación, se seleccionarán las herramientas más adecuadas para comprobar la accesibilidad.

También se podrán realizar pruebas con usuarios para identificar dificultades que no se detecten mediante herramientas automáticas.

Estas comprobaciones permitirán revisar las decisiones de diseño y realizar los ajustes necesarios antes de dar por finalizada la aplicación.

## 7. Conclusión

La accesibilidad y la usabilidad son aspectos fundamentales en el desarrollo de una aplicación, ya que influyen directamente en la facilidad con la que las personas pueden utilizarla y comprender su funcionamiento.

A través de la investigación realizada, se han identificado diferentes pautas, estándares y recomendaciones que pueden servir como referencia para el futuro desarrollo de By Me Too! / Comprame!.

Las medidas propuestas se centran especialmente en las necesidades de una aplicación de compras compartidas, teniendo en cuenta aspectos como el registro de productos, la introducción de precios, la selección de participantes y la consulta de balances.

Como el desarrollo de las interfaces todavía no ha comenzado, este manual servirá como guía para orientar las decisiones de diseño y programación. Posteriormente, las medidas podrán comprobarse mediante revisiones y pruebas de accesibilidad y usabilidad.

De esta manera, se pretende que la aplicación no solo cumpla con sus funcionalidades principales, sino que también ofrezca una experiencia clara, coherente y accesible para sus usuarios.

## 8. Fuentes consultadas

- **W3C – Web Content Accessibility Guidelines (WCAG) 2.2.**  
  https://www.w3.org/TR/WCAG22/

- **W3C – Web Accessibility Initiative (WAI): Introducción a la accesibilidad web.**  
  https://www.w3.org/WAI/fundamentals/accessibility-intro/es

- **W3C – Guidance on Applying WCAG 2.2 to Mobile Applications.**  
  https://www.w3.org/TR/wcag2mobile-22/

- **W3C – Mobile Accessibility.**  
  https://www.w3.org/WAI/standards-guidelines/mobile/

- **Junta de Andalucía – Norma de usabilidad en sitios web.**  
  https://desarrollo.juntadeandalucia.es/recursos/reglas-pautas/norma-usabilidad-en-sitios-web

- **Repositorio del proyecto – By Me Too! / Comprame!**  
  https://github.com/siarheilukashou25-maker/By-Me-Too






