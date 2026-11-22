# Resultados, decisiones y aprendizajes

## Evidencia funcional

Las pruebas se realizaron sobre demostraciones locales. Distingo la copia recuperada del proyecto de la distribución nueva, que genera datos ficticios y no importa la base histórica.

| Comprobación | Evidencia observada | Qué permite concluir |
| --- | --- | --- |
| Instalación desde volúmenes vacíos | WordPress 7.1.5, dependencias, seis productos ficticios y cuatro categorías | La distribución puede crear un laboratorio nuevo sin restaurar datos del sitio antiguo |
| Geometría de prueba | Cubo sintético de 20 × 20 × 20 mm aceptado y analizado | El servicio recibe y procesa un modelo de prueba; no valida todo archivo posible |
| Laminado y precio | Perfil A1 Mini adaptado, 3.63 g y unos 10.27 minutos por pieza; 15 copias por $3.60 | Hay conexión entre geometría, configuración, estimación y precio de ejemplo |
| Solicitud y revisión | Solicitud guardada en el flujo administrativo; aprobación comprobada en la copia recuperada | El proceso contempla intervención del equipo antes de continuar con la compra |
| Compra de prueba | Checkout de bloques recorrido en la copia recuperada; pago simulado invocado desde WooCommerce en la distribución limpia | El flujo local de pedido puede llegar a Procesando sin realizar un cobro |
| Factura | PDF generado y un adjunto de factura comprobado para el correo del cliente | El flujo de pedido puede producir y adjuntar el documento |
| Correo | Mensajes de cotización y pedido recibidos en Mailpit, con PDF adjunto | El transporte SMTP local y los adjuntos funcionan en las pruebas |
| Conservación y operación | Pedido/factura conservados al recrear contenedores en la copia recuperada; instalador repetido conserva la instalación limpia | Los datos de prueba no dependen exclusivamente de la vida de un contenedor |

El cubo, los importes y los pedidos son fixtures y operaciones de demostración. No son ventas, ingresos, resultados de marketing ni validación de una tarifa de impresión.

## Qué aprendí del proceso

**Una estimación necesita contexto.** Escala, relleno, capa, material, cantidad y orientación cambian el cálculo. El perfil adaptado a PrusaSlicer puede diferir de Bambu Studio y no sustituye una prueba física de fabricación.

**La operación depende de varias conexiones.** Una web que carga no garantiza que funcione la API del cotizador, que se genere una factura o que llegue un correo. La recuperación ayudó a comprobar esas partes por separado.

**Una copia de respaldo y una instalación reproducible resuelven problemas distintos.** La recuperación permitió conservar el proyecto; la distribución limpia hizo necesario crear páginas, preparar las carpetas de documentos y sustituir dependencias de la configuración antigua.

**Los servicios de prueba permiten revisar el recorrido.** Mailpit conserva mensajes y adjuntos; la pasarela simulada permite comprobar estados de pedidos. Ninguno demuestra entrega externa ni procesamiento bancario real.

La recuperación y estas correcciones fueron asistidas por IA. Las presento como trabajo realizado con acompañamiento y como oportunidades para reforzar mi capacidad de operación y diagnóstico.

## Recomendaciones de negocio derivadas del diseño

Son propuestas para una siguiente versión, no conclusiones de un experimento con clientes:

1. **Mostrar el precio como preliminar y aclarar el envío.** Evitar que el cliente interprete la estimación como una oferta de fabricación ya aprobada.
2. **Informar el estado de revisión y el siguiente paso.** La solicitud debe indicar qué falta por confirmar y cómo continuar cuando el equipo responda.
3. **Registrar estimación y revisión final.** Comparar más adelante material, tiempo y precio estimados con los de piezas realmente fabricadas ayudaría a ajustar el modelo de costos.
4. **Medir el recorrido con datos propios.** En una operación real convendría observar cargas, solicitudes, aprobaciones y pedidos pagados para identificar dónde se pierde continuidad, sin atribuir esos indicadores a las pruebas actuales.

## Límites del corte publicado

No se hicieron pruebas de cobro real de Wompi, SMTP externo, carga de producción ni calidad física de impresión. La subida y el cálculo en la distribución limpia se verificaron desde la integración WordPress–API. La galería muestra el modelo sintético calculado en la copia recuperada y abierto después en su interfaz, con esa procedencia identificada.

La revisión de archivos para compartir fue enfocada en secretos y datos personales; no equivale a una auditoría exhaustiva de vulnerabilidades de todas las dependencias. No se publican los reportes internos, las bases ni las cuentas del proyecto.
