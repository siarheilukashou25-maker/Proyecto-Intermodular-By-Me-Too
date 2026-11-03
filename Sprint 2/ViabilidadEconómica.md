## 3. Viabilidad Comercial y Económica

### 3.1. Estudio de Mercado y Competencia
**1. Proyectos similares y soluciones actuales (Competencia)**
Actualmente, el mercado carece de una solución unificada para este nicho. Según nuestra encuesta a 75 usuarios, la "competencia" real son métodos manuales y desorganizados: un 48,5% utiliza libretas físicas en casa, un 24,2% usa grupos en apps de mensajería rápida y un 21,3% no utiliza ninguna herramienta. Aunque existen apps genéricas de listas de la compra o de reparto de gastos (como Splitwise), ninguna integra la gestión simultánea de la cesta y la división automática del precio unitario por producto.
* **Debilidades actuales del mercado:** El 82,7% de los usuarios afirma que olvida productos por no llevar listas completas o actualizadas.
* **Fortaleza de By Me Too!:** El 95% de los encuestados afirma que usaría nuestra aplicación. La funcionalidad de añadir/borrar productos en conjunto es considerada imprescindible por el 80%, y la división de gastos cuenta con un 100% de aceptación específica en entornos de pisos compartidos.

**2. Tendencias demográficas, culturales y de ingresos**
* **Demografía:** El público objetivo principal es joven. El 80% de los usuarios tiene entre 19 y 40 años, siendo el 70% estudiantes universitarios o personas recién insertadas en el mundo laboral. Esto indica ingresos medios-bajos, lo que justifica el modelo de negocio Freemium para no crear barreras de entrada.
* **Cultura de consumo:** La compra sigue siendo una actividad muy tradicional; el 97% acude de forma presencial al supermercado. Además, es una tarea muy recurrente: el 90% hace la compra con una frecuencia de entre 2 y 7 días.
* **Preferencia de establecimientos:** Existe un monopolio claro en la preferencia de los usuarios, con Mercadona acaparando un 92% del interés, muy por delante de competidores como Lidl y Día (21% cada uno). Esto es clave para futuras estrategias de marketing o integración de catálogos.

### 3.2. Presupuesto y Costes
El proyecto se desarrolla entre el 21 de septiembre de 2026 y el 22 de febrero de 2027 (un periodo de 22 semanas en total).

**Cálculo de Horas de Ingeniería:**
* **Horas ya invertidas (Sprints 1-2):** 40 horas acumuladas en conjunto por el equipo (10 horas por cada integrante).
* **Horas futuras planificadas:** 19,5 semanas restantes $\times$ 40 horas/semana conjuntas = 780 horas.
* **Cálculo Total del Proyecto:** $40 \text{ h} + 780 \text{ h} = 820 \text{ horas de ingeniería del software}$ (Promedio de 205 horas por desarrollador).

**Coste de Mano de Obra (DAM Junior 2026):**
Para valorar económicamente el esfuerzo, se toma como referencia el salario bajo el Convenio Colectivo TIC en España:
* Salario Bruto Anual (Junior 0-1 años): 22.000 € / año.
* Seguridad Social empresa (+30%): 6.600 € / año.
* Coste Total Empresa Anual: 28.600 € / año.
* Jornada Anual: 1.800 horas / año.
* **Coste Hora Directo (Interno): 15,89 € / hora**.
* **Tarifa Hora Mercado: 22,00 € / hora**.
* **Valoración Mano de Obra en By Me Too! (Interno):** $820 \text{ h} \times 15{,}89 \text{ €/h} = 13.029{,}80 \text{ €}$.

**Capital Monetario Directo (Infraestructura y Licencias):**
* Google Play Developer Account: 23,00 €.
* Apple Developer Program: 92,00 €.
* Servicios Cloud (Firebase Blaze - 5 meses): 75,00 €.
* Dominio y Hosting Landing: 25,00 €.
* Registro de Marca (OEPM): 125,00 €.
* Marketing Piloto: 100,00 €.
* Entornos (IDE/Git): 0,00 €.
* **Total Capital Directo: 440,00 €**.

**Coste Total Estimado del Proyecto:**
$$\text{Mano de Obra (Interna)} (13.029{,}80\text{ €}) + \text{Capital Directo} (440{,}00\text{ €}) = \mathbf{13.469{,}80\text{ €}}$$

### 3.3. Modelo de Monetización y Rentabilidad
Para garantizar la viabilidad del proyecto a medio y largo plazo, se define un modelo de negocio con tres vías principales de generación de ingresos:

1. **Modelo Freemium (Suscripción In-App):**
   * **Plan Gratuito:** Permite administrar hasta 2 grupos de convivencia con cestas ilimitadas y repartos estándar.
   * **Plan Premium ($1{,}99\text{ €/mes}$ o $14{,}99\text{ €/año}$ por grupo):** Historial ilimitado de tiques, exportación de informes mensuales a PDF/Excel, gastos recurrentes programados y escaneo inteligente de tiques (previsto para V2.0).
2. **Publicidad Contextual (Google AdMob):** Inserción de banners discretos en la pantalla de liquidación con ofertas y promociones locales.
3. **Afiliación y Cashbacks:** Integración con plataformas de entrega a domicilio, obteniendo una comisión por cesta convertida.

**Estimación de Rentabilidad (Break-Even):**
Con una base inicial en la prueba piloto de 500 usuarios activos (aprox. 125 grupos):
* Si el 4% convierte a Premium: $20 \text{ usuarios} \times 1{,}99 \text{ €/mes} = 39{,}80 \text{ €/mes}$.
* Ingresos estimados por publicidad AdMob: $\sim 15{,}00 \text{ €/mes}$.
* Ingresos Mensuales Iniciales: $\sim 54{,}80 \text{ €/mes}$.
* **Conclusión:** Los ingresos iniciales cubren holgadamente los costes operativos Cloud ($\sim 15 \text{ €/mes}$), alcanzando el Punto de Equilibrio Operativo (Break-Even) a partir de solo 200 usuarios activos, garantizando la sostenibilidad financiera.

### 3.4. Financiación Pública y Ayudas al Emprendimiento
Para sufragar los costes iniciales y escalar el producto, se identifican las siguientes líneas de subvención:
1. **Programa Kit Digital:** Bonos digitales para pymes y autónomos para financiar la infraestructura web y el marketing.
2. **ENISA (Jóvenes Emprendedores):** Préstamos participativos del Ministerio de Industria, orientados a pymes de reciente constitución con proyectos innovadores de base tecnológica.
3. **Ayudas Autonómicas:** Subvenciones a fondo perdido para el fomento del empleo autónomo (ej. cuota cero o ayudas al inicio de actividad).

---
