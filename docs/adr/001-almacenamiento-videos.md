
Decisión sobre la estrategia de almacenamiento de videos para EducaMás

20 de marzo de 2026

3. Contexto
La empresa EducaMás está desarrollando una plataforma de cursos online que incluirá contenido en video, texto, ejercicios prácticos y foros de discusión.
Uno de los principales desafíos técnicos es definir la estrategia de almacenamiento y distribución de los videos de los cursos, considerando rendimiento, costos y escalabilidad.

Se han planteado dos alternativas:

🔹 Opción A: Almacenamiento en la nube con CDN
- Uso de servicios como almacenamiento en la nube combinado con una CDN para distribuir el contenido de manera eficiente a los usuarios.

🔹 Opción B: Servidores propios
- Almacenamiento de videos en infraestructura propia gestionada por la empresa.

Factores relevantes

Volumen estimado de videos:
- Se esperan aproximadamente 500 horas de video en el primer año, con crecimiento progresivo.

Tráfico esperado:
- Hasta 10.000 usuarios concurrentes en horarios pico.

Presupuesto:
- Presupuesto inicial limitado, con necesidad de optimizar inversión en infraestructura.

Requisitos de rendimiento:
- Baja latencia en reproducción
- Streaming fluido sin interrupciones
- Alta disponibilidad

Requisitos de seguridad:
- Protección contra descargas no autorizadas
- Control de acceso a contenido
- Posible uso de URLs firmadas o DRM

Conocimientos técnicos del equipo:
- Experiencia moderada en gestión de servidores
- Baja experiencia en CDN y servicios cloud

4. Decisión

Se elige la Opción A: Almacenamiento en la nube con CDN

Justificación

La opción A es la más adecuada debido a que:

- Permite escalar fácilmente ante crecimiento de usuarios.
- Ofrece mejor rendimiento global, especialmente con usuarios distribuidos geográficamente.
- Reduce la carga operativa del equipo.
- Proporciona herramientas integradas de seguridad.
- Evita inversión inicial en hardware.

Comparación de opciones

🟢 Opción A: Nube + CDN

Ventajas:
- Alta escalabilidad automática
- Baja latencia gracias a CDN
- Alta disponibilidad (SLA del proveedor)
- Seguridad avanzada integrada
- Menor carga de mantenimiento

Desventajas:
- Dependencia de proveedores externos
- Costos variables según uso
- Curva de aprendizaje inicial

🔴 Opción B: Servidores propios

Ventajas:
- Control total de la infraestructura
- Costos más predecibles a largo plazo (en algunos casos)
- Independencia de proveedores

Desventajas:
- Alta inversión inicial en hardware
- Escalabilidad limitada
- Mayor complejidad operativa
- Riesgo de fallas y menor disponibilidad
- Mayor esfuerzo en seguridad y optimización de streaming

5. Consecuencias
Impacto en el desarrollo
- Se deberá integrar con APIs de servicios cloud
- Configuración de almacenamiento y CDN
- Implementación de mecanismos de seguridad (tokens, URLs firmadas)

Impacto en el mantenimiento
- La infraestructura será gestionada principalmente por el proveedor cloud
- El equipo se enfocará en desarrollo y mejoras del producto

Impacto en los costos

Costos variables por:
- Almacenamiento
- Transferencia de datos

Se eliminan costos de:
- Compra de servidores
- Mantenimiento físico
- Personal especializado en infraestructura

Riesgos
- Dependencia de proveedores externos
- Incremento de costos con alto tráfico
- Posibles problemas si el proveedor tiene caídas

6. Estado
 Aceptado
