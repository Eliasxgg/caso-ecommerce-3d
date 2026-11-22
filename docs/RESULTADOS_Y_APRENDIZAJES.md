# Resultados y aprendizajes

## Qué resultado tuvo el proyecto

El resultado fue una tienda académica que reúne catálogo, compra y solicitud de piezas personalizadas, con un panel para administrar la operación. La integración permitió conectar la experiencia del cliente con cotización, pedido, documentos y correo.

Más allá de la apariencia de la web, el aprendizaje principal fue entender que un e-commerce depende de varias partes que deben funcionar juntas. WordPress es el centro del sitio, pero necesita datos, archivos, conexiones y herramientas de seguimiento.

## Lo que aprendí al construirlo

| Área | Aprendizaje | Relación con el proyecto |
| --- | --- | --- |
| WordPress y diseño | Organizar páginas, navegación, categorías y contenido | Convertir una propuesta de clase en una experiencia de tienda |
| WooCommerce | Relacionar catálogo, carrito, checkout y estados de pedidos | Entender el recorrido entre la compra y su administración |
| Integración | Reconocer qué hace la web y qué se delega a un servicio | Conectar el cotizador y presentar sus resultados en la tienda |
| Operación | Trabajar con Ubuntu, Docker Compose, configuración y volúmenes | Entender servicios, dependencias y conservación de datos |
| Correo | Relacionar eventos de la tienda con transporte SMTP y adjuntos | Trabajar con Fluent SMTP/Brevo en el proyecto y Mailpit en local |
| SEO | Conocer ajustes del sitio y el proceso de indexación | Trabajar con Rank Math y conocer la vinculación con Search Console |
| Medición | Entender que una web puede conectarse con herramientas de métricas | Acercamiento a Google Site Kit y a la lectura de información del sitio |
| Protección | Conocer herramientas del sitio y revisión de archivos | Wordfence en el entorno original y ClamAV en el cotizador |
| Recuperación | Distinguir respaldo histórico de instalación reutilizable | Separar datos privados, claves y servicios de demostración |

La implementación tuvo asistencia importante de IA. Estos aprendizajes corresponden a mi participación en el diseño, configuración, integración y revisión; no implican que haya programado todos los componentes ni que administre cada tecnología de forma independiente.

## Decisiones que ahora puedo explicar mejor

### Una estimación no es una aprobación

La pieza personalizada necesita reunir información antes de convertirse en un pedido. Mostrar una estimación ayuda al cliente, pero no elimina la revisión del equipo. Esto me permitió distinguir cálculo, propuesta y confirmación dentro de un proceso de negocio.

### El correo es parte del recorrido

Una solicitud o un pedido también genera información fuera de la pantalla. Trabajar con SMTP y documentos me ayudó a relacionar el estado de la operación con el mensaje que recibe el cliente y con el documento que debe acompañarlo.

### SEO y medición tienen procesos propios

Conocer Rank Math, Site Kit y Search Console me mostró que publicar la web no termina el trabajo. También hay que preparar el contenido para buscadores, conocer el proceso de indexación y consultar métricas cuando estén disponibles. No presento esa vinculación como garantía de posicionamiento ni como medición instantánea.

### La infraestructura sostiene la aplicación

El uso de contenedores me permitió ver responsabilidades distintas: aplicación, base, caché, cálculo, archivos y correo. La adaptación local hizo visible por qué los datos deben persistir y por qué una conexión que funciona en VPS puede necesitar otra configuración en la PC.

## Mejoras que plantearía para una siguiente versión

- **Hacer más claro el siguiente paso de una cotización:** indicar qué está pendiente de revisión y cómo continuar cuando el equipo responda.
- **Dar seguimiento al recorrido:** medir visitas, consultas y solicitudes con una configuración adecuada, y después relacionarlas con pedidos confirmados.
- **Mantener comunicación coherente:** revisar que pantalla, correo y PDF expresen el mismo estado y las mismas condiciones.
- **Documentar operación y mantenimiento:** conexiones, respaldo, restauración y actualización de servicios para reducir dependencia de configuraciones recordadas de memoria.
- **Contrastar estimaciones con fabricación:** si se retoma la operación, comparar cálculos con piezas realmente producidas antes de ajustar condiciones comerciales.

Son propuestas de mejora, no resultados de campañas o experimentos realizados con clientes.

## Alcance de la demostración

Las capturas muestran la tienda recuperada y el laboratorio reproducible. Las pruebas locales incluyeron catálogo, cálculo de un modelo de ejemplo, solicitud y revisión, pedido simulado, documentos PDF y correo en Mailpit. El detalle operativo se conserva con la implementación privada.

La demostración no procesa cobros ni envía mensajes a Internet. No presenta ventas obtenidas, métricas reales de clientes, pruebas físicas de impresión ni un servicio público actualmente activo. Los plugins y servicios del entorno original se describen como contexto y aprendizaje; no se afirma que todas sus cuentas estén conectadas en la copia local.
