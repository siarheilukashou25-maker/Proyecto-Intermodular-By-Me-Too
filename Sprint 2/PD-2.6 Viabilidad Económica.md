## 1. Viabilidad Comercial y Económica

### 1.1. Estudio de Mercado y Competencia
**1. Proyectos similares y soluciones actuales (Competencia)**
Actualmente, el mercado carece de una solución unificada para este nicho. Según nuestra encuesta a 75 usuarios, la "competencia" real son métodos manuales y desorganizados: un 48,5% utiliza libretas físicas en casa, un 24,2% usa grupos en apps de mensajería rápida y un 21,3% no utiliza ninguna herramienta. Aunque existen apps genéricas de listas de la compra o de reparto de gastos (como Splitwise), ninguna integra la gestión simultánea de la cesta y la división automática del precio unitario por producto.
* **Debilidades actuales del mercado:** El 82,7% de los usuarios afirma que olvida productos por no llevar listas completas o actualizadas.
* **Fortaleza de By Me Too!:** El 95% de los encuestados afirma que usaría nuestra aplicación. La funcionalidad de añadir/borrar productos en conjunto es considerada imprescindible por el 80%, y la división de gastos cuenta con un 100% de aceptación específica en entornos de pisos compartidos.

**2. Tendencias demográficas, culturales y de ingresos**
* **Demografía:** El público objetivo principal es joven. El 80% de los usuarios tiene entre 19 y 40 años, siendo el 70% estudiantes universitarios o personas recién insertadas en el mundo laboral. Esto indica ingresos medios-bajos, lo que justifica el modelo de negocio Freemium para no crear barreras de entrada.
* **Cultura de consumo:** La compra sigue siendo una actividad muy tradicional; el 97% acude de forma presencial al supermercado. Además, es una tarea muy recurrente: el 90% hace la compra con una frecuencia de entre 2 y 7 días.
* **Preferencia de establecimientos:** Existe un monopolio claro en la preferencia de los usuarios, con Mercadona acaparando un 92% del interés, muy por delante de competidores como Lidl y Día (21% cada uno). Esto es clave para futuras estrategias de marketing o integración de catálogos.

### 1.2. Estudio de Costes (Directos e Indirectos)
El proyecto se desarrolla entre el 21 de septiembre de 2026 y el 22 de febrero de 2027 (un periodo de 22 semanas o 5 meses en total).

**1. Cálculo de Horas y Coste de Personal:**
* **Horas totales del proyecto:** 40 h (Sprints 1-2) + 780 h (restantes) = **820 horas de ingeniería del software** (Promedio de 205 horas por desarrollador).
* **Coste Hora Directo (Interno): 15,89 € / hora** (Basado en Convenio TIC para DAM Junior: 22.000 € brutos + 30% SS / 1.800h anuales).
* **Valoración Mano de Obra Interna:** $820 \text{ h} \times 15{,}89 \text{ €/h} = \mathbf{13.029{,}80 \text{ €}}$.

**2. Costes Indirectos (Suministros y Mantenimiento):**
Para el desarrollo durante estos 5 meses en modalidad de teletrabajo/oficina, se asumen los siguientes costes operativos:
* **Internet (Fibra Óptica):** Estimado en 35 €/mes. Total (5 meses): 175,00 €.
* **Suministro Eléctrico (Luz):** Consumo estimado de 4 portátiles y monitores (aprox. 150W por puesto). Para 820 horas de trabajo total: $820 \text{ h} \times 0,15 \text{ kW} = 123 \text{ kWh}$. A un precio medio de 0,16 €/kWh, supone unos 20,00 €.
* **Mantenimiento y Amortización de Hardware:** Estimando 4 equipos valorados en 800 € con una vida útil de 4 años (48 meses). La depreciación por 5 meses de uso es de 333,33 €.
* **Total Costes Indirectos:** $\mathbf{528{,}33 \text{ €}}$.

**3. Capital Monetario (Software y Servicios):**
* Google Play (23€) + Apple Dev (92€) + Firebase 5 meses (75€) + Dominio (25€) + Marca (125€) + Marketing (100€) = **440,00 €**.

### 1.3. Presupuesto Total y Contraste de Valor (Punto 2.1)
**Contraste con el valor de mercado:** Mientras que el coste de producción interno es de aproximadamente 15.89 €/hora, si este desarrollo se externalizara a una consultora de software a precio de mercado (tarifa media de 22,00 €/hora), el coste de la aplicación ascendería a $820 \text{ h} \times 22 \text{ €} = 18.040 \text{ €}$ (+ IVA y margen comercial). Esto demuestra una alta eficiencia y viabilidad al desarrollarlo internamente.

Para consolidar el presupuesto de producción, se aplica un 10% de contingencias sobre el subtotal para cubrir posibles desviaciones de tiempo o incrementos en las tarifas cloud:

| Categoría | Concepto | Coste Estimado (€) |
| :--- | :--- | :--- |
| **Personal** | 820 horas de desarrollo (15,89 €/h) | 13.029,80 € |
| **Hardware** | Amortización de 4 equipos de desarrollo (5 meses) | 333,33 € |
| **Software / Servicios** | Licencias, Firebase, dominios, marca y marketing | 440,00 € |
| **Costes Indirectos** | Internet (175 €) y Suministro Eléctrico (20 €) | 195,00 € |
| **Subtotal** | Coste base de producción | **13.998,13 €** |
| **Contingencias** | Fondo de reserva para imprevistos (10%) | 1.399,81 € |
| **Total Presupuesto** | **Coste total de desarrollo del MVP** | **15.397,94 €** |

### 1.4. Modelo de Monetización y Rentabilidad
Para garantizar la viabilidad del proyecto a medio y largo plazo, se define un modelo de negocio con tres vías principales de generación de ingresos:

1. **Modelo Freemium (Suscripción In-App):**
   * **Plan Gratuito:** Permite administrar hasta 2 grupos de convivencia con cestas ilimitadas y repartos estándar.
   * **Plan Premium ($1{,}99\text{ €/mes}$ o $14{,}99\text{ €/año}$ por grupo):** Historial ilimitado de tiques, exportación de informes mensuales a PDF/Excel, gastos recurrentes programados y escaneo inteligente de tiques.
2. **Publicidad Contextual (Google AdMob):** Inserción de banners discretos en la pantalla de liquidación con ofertas y promociones locales.
3. **Afiliación y Cashbacks:** Integración con plataformas de entrega a domicilio.

**Estimación de Rentabilidad (Break-Even):**
Con una base inicial en la prueba piloto de 500 usuarios activos:
* Si el 4% convierte a Premium: $20 \text{ usuarios} \times 1{,}99 \text{ €/mes} = 39{,}80 \text{ €/mes}$.
* Ingresos estimados por publicidad AdMob: $\sim 15{,}00 \text{ €/mes}$.
* Ingresos Mensuales Iniciales: $\sim 54{,}80 \text{ €/mes}$.
* **Conclusión:** Los ingresos iniciales cubren holgadamente los costes operativos Cloud mensuales tras el despliegue ($\sim 15 \text{ €/mes}$), garantizando el Break-Even operativo con tan solo 200 usuarios activos.

### 1.5. Financiación Pública y Ayudas al Emprendimiento
Para sufragar los costes iniciales y escalar el producto, se identifican las siguientes líneas de subvención:
1. **Programa Kit Digital:** Bonos digitales para pymes y autónomos para financiar infraestructura web.
2. **ENISA (Jóvenes Emprendedores):** Préstamos participativos orientados a pymes de reciente constitución con base tecnológica.
3. **Ayudas Autonómicas:** Subvenciones a fondo perdido para el fomento del empleo autónomo.

### 1.6. Fuentes y Referencias Económicas
* **Costes Salariales:** *Resolución de la Dirección General de Trabajo por la que se registra y publica el XVIII Convenio colectivo estatal de empresas de consultoría, tecnologías de la información y estudios de mercado y de la opinión pública (BOE).*
* **Tarifas de Infraestructura:** *Google Play Console (fees)*, *Apple Developer Enterprise Program*, y *Firebase Pricing Calculator*.
* **Mercado Energético:** *Red Eléctrica de España (REE)*. Precio voluntario para el pequeño consumidor (PVPC) aplicado al cálculo de consumo en remoto.
* **Financiación Pública:** *Bases Reguladoras del Programa Kit Digital (Acelera Pyme - Red.es).*