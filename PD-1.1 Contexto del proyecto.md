# 1. Contexto del proyecto

### 1.1. Nivel Español: convivencia y recursos
Las Personas somos seres  sociales por naturaleza viven en familia, entré amigos, una relación o en un apartamento.Si bien en las familias suele ser los padres quien pagan la mayoría de cosas , al vivir con por ejemplo compañeros de piso, significa buscar un equilibrio que sea bueno para todos y cuando se trata de ir al supermercado o pagar las facturas esto puede resultar en muchos problemas.

### 1.1.2. Nivel social: el auge de los pisos compartidos en España
Vivir fuera del núcleo familiar es una necesidad económica estructural:
- **Emancipación tardía:** Supera los **30,2 años** y solo el **14,5 %** está emancipado (Consejo de la Juventud, 2025). Un **48 %** de 25 a 34 años vive con sus padres (frente al 30 % en la UE).
- **Precio y oferta:** El precio medio de una habitación es de **425 €/mes** (+19 % en oferta en 2025, idealista).
- **Perfil:** El **44 %** tiene de 18 a 24 años y el **31,1 %** supera los 35 (se comparte por obligación ante alquileres altos y precariedad).

### 1.1.3. Nivel doméstico: la compra como gasto frecuente
La compra es el gasto más recurrente y mezclado del hogar. Según nuestra encuesta (**N = 75**, `docs/AnálisisDeMercado.md`):
- **Frecuencia:** El **66,7 %** compra semanalmente y el **90 %** cada 2–7 días (97 % de forma presencial).
- **Listas y despistes:** El **71 %** hace lista (48,5 % en libreta compartida, 24,2 % en chat), pero el **82,7 %** olvida productos por no llevarla completa. El **21,3 %** no usa ninguna herramienta.
- **Preferencias:** Mercadona encabeza con un **92 %**. El **80 %** tiene entre 19 y 40 años (70 % estudiantes o recién titulados).

### 1.1.4. Nivel tecnológico y sectorial: el nicho de mercado
Aunque el smartphone organiza la vida diaria, la gestión doméstica sigue haciéndose en libretas, chats o de cabeza. En este escenario, **By Me Too!** se posiciona en la intersección entre listas de la compra y finanzas personales, resolviendo los huecos del mercado:

| Tipo de empresa | Ejemplos | Qué ofrecen | Qué **no** resuelve para nuestro público |
|---|---|---|---|
| **Reparto de gastos** | Splitwise, Tricount | App de gastos y deudas | Reparten por gasto total; el desglose por producto es de pago o manual. **No gestionan listas**. |
| **Listas de compra** | Bring! , Listonic | Listas compartidas en tiempo real (Bring! >21M de usuarios) | **No reparten gastos** entre los miembros. |
| **Grandes tecnológicas** | Google Keep, Apple, WhatsApp | Notas, listas y chat genéricos | Herramientas genéricas (el 24,2 % usa chats). |
| **Distribución minorista** | Mercadona, Dia | Compra online, cupones y fidelización | Enfocadas en su tienda y un solo comprador; sin grupo ni reparto. |

**Nuestra solución:** Ninguna herramienta une **lista compartida + reparto por producto** adaptada a un grupo de iguales. El proyecto consiste en el desarrollo de una aplicación móvil para administrar compras compartidas entre compañeros de piso, estructurada en dos bloques:
1. **Administración integral** de perfiles y grupos de convivencia .
2. **Registro detallado de tiques** y liquidación automática de cuentas entre los miembros.

### 1.1.5. La empresa tipo del proyecto: estructura y funciones

By Me Too! adopta la estructura de una **startup de software** con metodología **Scrum** (roles rotativos entre el equipo):

```text

                 ┌─────────────────────────────┐
                 │        Scrum Master         │
                 └──────────────┬──────────────┘
        ┌──────────────┬────────┴──┬──────────────┬──────────────┐
┌───────▼──────┐┌──────▼───────┐┌─────▼──────┐┌──────▼──────┐┌──────▼───────┐
│ Diseño UX/UI ││  Front-end   ││  Back-end  ││     QA      ││ Marketing y  │
│ Figma, Base44││ Interfaz app ││ (Firebase) ││ Smoke tests ││ comunidad    │
└──────────────┘└──────────────┘└────────────┘└─────────────┘└──────────────┘
        Administración, fiscalidad y laboral: gestoría externa
```

| rol | Funciones principales | Evidencia en el proyecto |
|---|---|---|
| **Dirección / Product Owner** | Definir visión, priorizar backlog y validar entregas | Project «By Me Too!», encuesta de mercado |
| **Scrum Master** | Facilitar ceremonias y eliminar bloqueos | 8 sprints planificados en el Project |
| **Diseño UX/UI** | Investigación de usuario y prototipado | Wireframe, Figma y Base44 |
| **Desarrollo front-end** | Construcción de la interfaz | `LoginWindow` y `MainWindow` |
| **Desarrollo back-end** | Lógica de reparto y persistencia de datos | Esqueleto MVC, capa de datos en Firebase |
| **QA** | Pruebas y control de calidad | Documento de smoke test |
| **Marketing y comunidad** | Difusión en redes sociales | Estrategia de lanzamiento |
| **Administración (externa)** | Obligaciones fiscales y laborales | Gestoría externa |
