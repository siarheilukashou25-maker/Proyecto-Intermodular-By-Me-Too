## 1. Viabilidad Legal, Fiscal y PRL

El proyecto debe cumplir tanto con la normativa aplicable a la constitución de la actividad comercial, como con el marco jurídico que regula el desarrollo de software y el tratamiento de datos.

### 1.1. Obligaciones Legales y Fiscales
Para operar en el mercado español y publicar en Google Play y App Store de forma comercial, el equipo promotor deberá constituirse legalmente:
* **Forma jurídica inicial:** Alta en el Régimen Especial de Trabajadores Autónomos (RETA) para los fundadores, aprovechando la tarifa plana inicial. En fases de escalabilidad, se constituirá una Sociedad Limitada (S.L.).
* **Obligaciones fiscales:** Presentación trimestral de IVA, Retenciones de IRPF y Tributación de beneficios a través del Impuesto de Sociedades (25% en régimen general, 15% para empresas de nueva creación).

### 1.2. Privacidad y Seguridad en el Software (RGPD / LOPDGDD)
El tratamiento de datos exige el consentimiento explícito de los usuarios. Para garantizar la privacidad desde el diseño (Privacy by Design), se implementarán las siguientes medidas técnicas en el software:
* **Criptografía de Credenciales:** No se almacenará ninguna contraseña en texto plano. Se implementará el algoritmo de hashing BCrypt con un factor de coste (salt) y las comunicaciones transitarán bajo canales seguros TLS (HTTPS).
* **Derechos ARSOPL (Derecho al Olvido):** Para permitir la baja de usuarios sin romper la integridad referencial de los balances matemáticos de los grupos, se aplicará la anonimización de los registros históricos (sustituyendo los datos personales por un ID genérico como "Usuario Borrado").

### 1.3. Propiedad Intelectual y Licencias
Para evitar conflictos de derechos de autor, el código fuente propio del proyecto se distribuirá bajo una licencia comercial propietaria. Por otro lado, todas las dependencias tecnológicas de terceros utilizadas (como el SDK de Flutter, dependencias de Firebase o tipografías de Google Fonts) operan bajo licencias abiertas y permisivas (como MIT o Apache 2.0), garantizando que no existen incompatibilidades legales para su explotación comercial.

### 1.4. Accesibilidad Universal (UNE-EN 301 549 y WCAG)
La interfaz de usuario se diseñará cumpliendo con los criterios de accesibilidad:
* Se garantizará un ratio de contraste mínimo de 4.5:1 para facilitar la lectura.
* Se hará uso del widget `Semantics` en Flutter para que los elementos interactivos puedan ser interpretados correctamente por lectores de pantalla (TalkBack / VoiceOver).

### 1.5. Prevención de Riesgos Laborales (PRL)
Dado que el desarrollo de software es una actividad intensiva en PVD (Pantallas de Visualización de Datos), se contemplan los siguientes riesgos y medidas preventivas:
* **Riesgos ergonómicos:** Fatiga visual, cervicalgias y síndrome del túnel carpiano.
  * *Medidas:* Sillas ergonómicas ajustables, monitores a la altura de los ojos.
* **Riesgos psicosociales:** Estrés por plazos de entrega y sedentarismo.
  * *Medidas:* Pausas visuales (regla 20-20-20), metodologías ágiles para evitar cuellos de botella en las entregas, y fomento de la desconexión digital fuera de las horas estipuladas.