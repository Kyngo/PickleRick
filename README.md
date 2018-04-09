# Pickle Rick
## Bot de Telegram (no muy) inteligente - Basado en el bot creado por Mutex (@Markov_bot)
---
## FAQ
### ¿Qué hace este bot?
Hablar. Mucho, si se desea. 

### ¿Cómo funciona?
El bot almacena los mensajes que lee en los chats e intenta predecir cómo poder hablar, usando el algoritmo de cadenas de Markov.
Creará frases más (poco) inteligentes y variadas a medida que hables por un grupo con el bot.

### ¿Cómo lo puedo probar?
Habla con https://t.me/pickle_rick_bot para probarlo.

### Pero... ¿Puedes ver los mensajes?
No. Podéis ver el código fuente y comprobarlo vosotr@s mism@s. El bot los guarda en un fichero binario.

### ¿Puedo usar este código?
Claro. Bajo la licencia GPL v3.

---

## Instalación
Este bot requiere una serie de paquetes:
* opus-core
* espeak
* python3

También debe poder escribir y leer allí donde lo pongas.

## Fichero config.json

Debe tener una estructura como la siguiente:

```
{
	"token": "TOKEN_DE_TELEGRAM",
	"user_agent": "Mozilla/5.0 KyngoNet",
	"creator_id": 123456789
}
```


Donde pone "creator_id" debe ir tu ID de Telegram. De esta forma, el bot te podrá hablar.
¿No sabes tu número de ID de Telegram? Pregúntale a KyngoBot (/info)
https://t.me/kyngobot

---

## Crédito:
El bot fue creado originalmente por Mutex. Yo he cogido su trabajo y lo he modificado bajo la licencia GPL v3.
https://github.com/39bit/Markov_Bot
