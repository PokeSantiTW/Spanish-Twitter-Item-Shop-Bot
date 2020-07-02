# Spanish Fortnite Shop

## Creador Original

Todo el mérito del bot al creador original: [EthanC](https://github.com/EthanC/Athena). Yo solo lo he querido traducir y modificar algunas cosas que no estaban hechas para que más gente pueda usarla ^^

## Bot de la Tienda de Objetos para Twitter

Este bot tiene la función de usar la API de Fortnite-API y crear una imagen de la Tienda de Objetos actual para así, publicarla en Twitter

Un ejemplo sería el siguiente:

<p align="center">
    <img src="https://i.imgur.com/EV3RNBl.jpg" width="650px" draggable="true">
</p>

## Requisitos Previos

Para instalar esto debes tener Python en tu máquina (Windows, Linux, etc.). El como instalarlo ya es algo más complejo, así que te recomiendo buscar tutoriales (Si lo escribo yo, al final saldrá mal jaja). Aquí los requisitos:

- [Python 3.7](https://www.python.org/downloads/)
- [Requests](http://docs.python-requests.org/en/master/user/install/)
- [coloredlogs](https://pypi.org/project/coloredlogs/)
- [Pillow](https://pillow.readthedocs.io/en/stable/installation.html#basic-installation)
- [python-twitter](https://github.com/bear/python-twitter#installing)

Necesitarás una [Key de la API de Fortnite-API](https://fortnite-api.com/profile) para poder introducirlo en configuration.json. También hará falta una cuenta en [Developer Twitter](https://developer.twitter.com/en/apps) y así tener acceso a las llaves de la API de tu cuenta.

## Como usarlo

Abre `configuration.json` en un editor de texto y completa los campos correspondientes. Una vez terminado, guarda el archivo.

- `delayStart`: Esta función introducirá un retraso al generador de la imagen. Ponlo a `0` para que empiece automáticamente.
- `supportACreator`: Si tienes Código de Creador, puedes ponerlo aquí para que se publique en el Tweet. Si no, déjalo en blanco.
- `twitter`: Pon `enabled` a `false` si no quieres que la imagen de la Tienda sea tweeteada.

Puedes editar las imagenes que se encuentran en `assets/images/` a tu gusto. ¡No cambies las resoluciones si no es necesario! 

Este repositorio se actualizará con nuevas imagenes si hacen falta.

Spanish Fortnite Shop se debe usar en un programador de tareas como [cron](https://en.wikipedia.org/wiki/Cron) en Linux o [z-cron](https://www.z-cron.com/es/) en Windows.

## Comando para iniciar.

```
python itemshop.py
```
o (más en Linux)
```
python3 itemshop.py
```

## Creditos

- Item Shop data provided by [Fortnite-API](https://fortnite-api.com/)
- Burbank font property of [Adobe](https://fonts.adobe.com/fonts/burbank)
- Luckiest Guy font property of [Google](https://fonts.google.com/specimen/Luckiest+Guy)
