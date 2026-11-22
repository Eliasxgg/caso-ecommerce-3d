# Recorrido visual

Las imágenes muestran demostraciones locales del proyecto. **No representan una tienda comercial activa ni pagos reales.** Las primeras cuatro proceden de la copia recuperada; la última corresponde al laboratorio reproducible con datos ficticios. Los modelos y pedidos utilizados como evidencia son de prueba.

## 1. Presentación de la tienda

La portada introduce los productos, el material y las dos entradas principales: explorar el catálogo o solicitar una pieza personalizada.

![Inicio de la tienda](../assets/01-inicio.jpg)

La interfaz conserva la identidad azul oscuro, naranja y celeste del proyecto. El aviso superior identifica el entorno local.

## 2. Catálogo de productos

Las tarjetas presentan imagen, precio, categoría y opciones de compra. Esta captura conserva el catálogo académico recuperado; la distribución nueva genera seis productos ficticios con ilustraciones geométricas.

![Tarjetas de productos del catálogo recuperado](../assets/02-catalogo.jpg)

Las marcas o personajes que aparecen incidentalmente en la interfaz no implican afiliación comercial ni se ofrecen como recursos descargables de este caso.

## 3. Cotizador y vista del modelo

Se utilizó un cubo STL sintético de 20 mm. La pantalla muestra la estimación para **15 copias: $3.60**, unos **54.4 g** de material y **2 h 34 min** de impresión estimada, con los parámetros de prueba.

![Modelo sintético en el visor 3D, estimación y opciones de material y capa](../assets/03-cotizador.jpg)

El cálculo se preparó a través de la integración WordPress–cotizador y se abrió después en la interfaz. No se alteraron los valores de la pantalla para la captura. El precio es preliminar y está sujeto a revisión; no es una tarifa comercial recomendada.

## 4. Confirmación del pedido simulado

La confirmación permite consultar piezas, subtotal, envío, método de pago y factura. El pedido mostrado utilizó datos ficticios y la pasarela **Pago de prueba — sin cobro real**.

<details>
<summary>Ver la confirmación completa del pedido de prueba</summary>

![Confirmación del pedido simulado con datos ficticios](../assets/04-pedido.jpg)

</details>

Esta captura se obtuvo al recorrer el checkout en la copia local recuperada. El laboratorio limpio también comprobó el pago y la generación de factura desde WooCommerce; ambas pruebas se distinguen en [resultados y alcance](RESULTADOS_Y_APRENDIZAJES.md).

## 5. Notificaciones y documentos por SMTP local

Mailpit permite revisar los mensajes que genera la aplicación. La bandeja muestra correos de nueva solicitud, nuevo pedido y confirmación; los indicadores de adjunto permiten identificar los documentos PDF.

![Correos de pedido y cotización recibidos en el buzón SMTP local](../assets/05-smtp.jpg)

Los destinatarios son direcciones ficticias. Los mensajes permanecen en Docker: esta evidencia no acredita entrega a un buzón de Internet. La versión final de la prueba adjuntó la factura al correo del cliente y el PDF preliminar a la solicitud de revisión.

## Cómo interpretar las evidencias

- La identidad visual recuperada y la distribución limpia forman parte de la misma evolución del proyecto, pero utilizan conjuntos de datos distintos.
- No se publican la base histórica, archivos de clientes, documentos completos del curso ni accesos a administración.
- Las capturas demuestran funciones observadas; no prueban rendimiento con carga real, calidad física de una impresión ni resultados comerciales.
- Los avisos y logotipos heredados sobre Wompi describen la integración del proyecto original. Los pagos de estas demostraciones son simulados.
