# Presentación Bot Botánico

Proyecto sobre el escenario **"Biodiversidad"** de Make: un bot de Telegram que identifica plantas a partir de una foto, revisa su salud y explica cómo cuidarlas usando un agente de IA.

Bot de Telegram: **@BIODIVERSITY_DSBOT**

## Contenido

- `Presentacion_Bot_Botanico.pptx`: presentación de 6 diapositivas (qué hace, cómo funciona, qué necesita y QR del bot).
- `index.html`: página interactiva con la mascota Maceti, la demostración del recorrido del mensaje, la lista de requisitos y el QR. Es un solo archivo; ábrelo en el navegador o visítala en GitHub Pages: https://cesargm-max.github.io/Presentacion-Bot-botanico/

## Cómo funciona el escenario

1. **Telegram › Watch Updates**: se activa al instante con cada mensaje.
2. **Router**: separa los mensajes con foto de los que no la traen.
3. **Telegram › Download a File**: descarga la foto (ruta con foto).
4. **Agente de IA**: actúa como botánico amigable y responde en español, máximo 200 palabras.
5. **Telegram › Send a Reply Message**: envía la respuesta al chat. Sin foto, responde con un mensaje de bienvenida.

## Qué necesita para funcionar

- Cuenta de Make con el escenario "Biodiversidad".
- Bot de Telegram conectado en Make.
- Webhook instantáneo de Telegram.
- Proveedor de IA (Make's AI Provider).
- Escenario activado (ON).

## Probarlo sin Telegram

La sección "Otras formas de probarlo" de la página ofrece:

- **Ejemplos**: botones con plantas de muestra (potus, cactus, suculenta, monstera, una taza y un mensaje de texto) que muestran cómo responde el bot. Las respuestas están escritas de antemano; no se conectan al bot real.
- **Telegram Web**: botón que abre el bot en https://web.telegram.org (necesita una cuenta de Telegram, pero no la app).
- **Chat en vivo con Claude**: solo funciona cuando la página se abre dentro de Claude; en GitHub Pages no aparece.
