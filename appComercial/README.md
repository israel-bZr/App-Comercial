# Miga Dorada — panadería de barrio

Sitio comercial adaptable a móvil y escritorio. Incluye catálogo filtrable, carrito guardado en el navegador, pedido por WhatsApp y un asistente de respuestas predefinidas que funciona sin IA.

## Cómo abrirla

Abre `index.html` en un navegador. No requiere instalación ni servidor para las funciones incluidas. Las fotografías y tipografías se cargan desde internet.

## Personalizar

- Edita el catálogo, precios, categorías y fotos en `app.js`, en el arreglo `products`.
- Cambia el nombre, dirección, horario y contenido de la página en `index.html`.
- Edita las preguntas rápidas y las respuestas en el arreglo `faq` de `app.js`.
- Actualiza el enlace `https://wa.me/` en `app.js` con el número comercial en formato internacional para enviar pedidos directamente al negocio.

## Preparada para incorporar IA

El asistente responde desde el navegador, comparando palabras clave con respuestas predefinidas. El punto marcado `answerWithAI` en `app.js` indica dónde conectar posteriormente un endpoint propio. Mantén las credenciales y claves de proveedor en un servidor, nunca en el código visible del navegador.

Los precios, la ubicación, el horario, la política de envío y el contacto incluidos son datos de ejemplo; reemplázalos por los datos reales antes de publicar.
