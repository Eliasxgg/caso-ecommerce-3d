# Resultados y aprendizajes del proyecto

## Qué me permitió construir y entender

El resultado tecnológico fue una tienda académica desplegada en VPS, con catálogo, pedidos y cotizador integrado. El trabajo me acercó a la operación de una aplicación accesible desde Internet: dominio, Cloudflare, HTTPS, proxy, WordPress, datos y servicios externos.

La formulación aportó otra perspectiva: cada función debía relacionarse con información que necesita el cliente o con una actividad del equipo. Una tienda también requiere pensar en solicitudes, confirmaciones, comunicación, producción y seguimiento.

## Evidencia de la demo

Las capturas documentan una estimación para un cubo de prueba, un pedido simulado con desglose y acceso al PDF, y notificaciones recibidas por Mailpit. Son pruebas separadas. [Ver recorrido visual](RECORRIDO_VISUAL.md).

## Aprendizajes del entorno original

| Área | Qué aprendí a relacionar | Aplicación |
| --- | --- | --- |
| Propuesta y experiencia | Convertir una necesidad en funciones y contenido | Catálogo, opciones y recorrido de pedido |
| WordPress/WooCommerce | Configurar páginas y conectarlas con administración | Productos, cuentas, carrito, checkout y estados |
| Dominio y acceso | Distinguir DNS, proxy externo, HTTPS y origen | Cloudflare y Nginx Proxy Manager |
| Servicios en VPS | Reconocer dependencias, redes, configuración y persistencia | Ubuntu, Compose, MariaDB, Redis y cotizador |
| Protección | Separar borde, servidor, aplicación y archivos | Cloudflare, controles Ubuntu, Wordfence y ClamAV |
| Integración | Distinguir visualización, estimación y decisión | Three.js, servicio Python y revisión del equipo |
| Comunicación | Relacionar eventos con mensajes y documentos | Fluent SMTP, Brevo y PDF |
| SEO y seguimiento | Separar contenido, indexación y medición | Rank Math, Site Kit, Analytics y Search Console |
| Continuidad | Comprender qué conservar y cómo recuperarlo | Datos, archivos, configuración y copias cifradas |

Son aprendizajes de diseño, configuración, integración y revisión con acompañamiento. No equivalen a dominio avanzado de cada tecnología.

## Decisiones que ahora puedo explicar mejor

### El acceso al sitio tiene varias capas

Una visita pasa por el dominio y Cloudflare antes de llegar al proxy y a la aplicación. Esto me ayudó a entender por qué un problema de acceso no siempre se resuelve cambiando WordPress y por qué la administración requiere controles distintos del recorrido del cliente.

### La protección tiene responsabilidades diferentes

Wordfence protege la aplicación; no reemplaza los controles del servidor o del origen. El tratamiento de archivos es otra responsabilidad. Conocí esas capas mediante configuración asistida, sin atribuirme una especialización en seguridad.

### Una estimación no sustituye una revisión

Modelo y parámetros orientan una solicitud, pero el equipo debe revisar viabilidad y condiciones antes de comprometer fabricación. El recorrido distingue cálculo, propuesta y pedido.

### La comunicación forma parte de la operación

Pantalla, correo y documento deben expresar el mismo estado. La configuración SMTP y los PDF me ayudaron a relacionar las acciones de la tienda con lo que recibe el cliente.

### Medir, indexar y vender son procesos distintos

Las herramientas de Google y los ajustes SEO ayudan a observar y preparar el canal. No prueban demanda, ventas ni rentabilidad. Los documentos académicos también distinguen proyecciones y actividades exploratorias de resultados comerciales.

### Recuperar exige conocer datos y configuración

Los respaldos contemplaban más que archivos visibles. La recuperación reforzó mi comprensión de persistencia y separación entre datos, código, configuración y accesos.

## Qué aportó la formulación académica

Los avances trabajaron problema, alternativas, entorno, roles, riesgos y operación bajo demanda. Ayudaron a situar la web dentro de un proyecto con producción física y atención.

Las responsabilidades previstas y las metas financieras se mantienen como planificación. Las actividades exploratorias de los documentos corresponden a versiones anteriores y operaciones simuladas; no se convierten aquí en ventas o validación del sitio posterior.

## Mejoras para una siguiente etapa

- **Operación:** documentar conexiones, mantenimiento y responsables para reducir dependencia de configuraciones recordadas de memoria.
- **Continuidad:** repetir la recuperación desde copias externas y documentar un futuro despliegue, además de la instalación aislada ya comprobada en local.
- **Experiencia:** aclarar qué necesita aprobación y cuál es el siguiente paso del cliente.
- **Seguimiento:** relacionar el recorrido con pedidos cuando exista una operación con datos propios, respetando privacidad y consentimiento.
- **Producción:** contrastar estimaciones con resultados físicos antes de ajustar condiciones comerciales.

Son propuestas, no mejoras comerciales ya medidas.

## Papel secundario de la adaptación local

La adaptación permite revisar catálogo, cotizador, solicitud, pedido simulado, PDF y correo interno desde una PC. Reemplaza pago y SMTP externos por servicios de prueba y utiliza datos ficticios.

Recuperación y pruebas fueron asistidas por IA. Las 14 capturas renovadas el 26/11/2026 proceden de la demo final que corresponde a la implementación privada verificada, con presentación original recuperada. No acreditan VPS activa, cobros, entregas ni reproducción completa de la infraestructura perimetral en Windows.

Se comprobaron compra con envío y recogida, variantes, solicitud y aprobación administrativa, contacto, documentos y SMTP local. Estas comprobaciones permiten explicar la relación entre servicios y estados; no se presentan como nuevas ventas ni como desarrollo manual individual. [Evidencia y estado](EVIDENCIA_Y_ESTADO.md).
