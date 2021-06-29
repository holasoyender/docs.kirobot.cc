---
description: Aqui tienes un ejemplo de archivo de configuración
---

# Ejemplo config

```yaml
#  ██╗░░██╗   ██╗   ██████╗░   ░█████╗░   ██████╗░   ░█████╗░   ████████╗
#  ██║░██╔╝   ██║   ██╔══██╗   ██╔══██╗   ██╔══██╗   ██╔══██╗   ╚══██╔══╝
#  █████═╝░   ██║   ██████╔╝   ██║░░██║   ██████╦╝   ██║░░██║   ░░░██║░░░
#  ██╔═██╗░   ██║   ██╔══██╗   ██║░░██║   ██╔══██╗   ██║░░██║   ░░░██║░░░
#  ██║░╚██╗   ██║   ██║░░██║   ╚█████╔╝   ██████╦╝   ╚█████╔╝   ░░░██║░░░
#  ╚═╝░░╚═╝   ╚═╝   ╚═╝░░╚═╝   ░╚════╝░   ╚═════╝░   ░╚════╝░   ░░░╚═╝░░░
#Este es el archivo de configuración para el servidor: KiroBot. Aprende a configurarlo en https://www.kirobot.cc

#Para aquellas configuraciones que contengan una array ([]) si se quiere añadir más de una ID se deberá separarlas entre comas
#Ejemplo:   ignoredUsersIDs:  ["396683727868264449", "410092970562420739"]

prefix: "k/"                # Prefijo que usará el bot para los comandos

lang: "esp"                 # Idioma con el que trabajará el bot. Idiomas validos: "eng" y "esp"

moderation:
    muteRoleID: "760505713758961686"            # Entre comillas la ID del rol que se dará a los usuarios silenciados

logs:
    logChannelID: "769990731972214786"          # Entre comillas la ID del canal de logs
    ignoredChannelsIDs: ["810469825003388968", "234395307759108106"]                      # Entre comillas y separado por comas las IDs de los canales a ignorar por los logs
    ignoredUsersIDs: ["810800509719019532"]       # Entre comillas y separado por comas las IDs de los usuarios a ignorar por los logs

automod:
    active: true                   # true Para activar KiroBot AutoMod, false para desactivarlo
    deleteInvites: true            # true Para activar el filtrado de invitaciones, false para desactivarlo
    bannedWords: ["tonto", "gokory"]           # Entre comillas y separado por comas las palabras que borrará el bot
    ignoredChannelsIDs: ["468564048552787969", "736254609324245152"]          # Entre comillas y separado por comas las IDs de los canales a ignorar por el AutoMod
    ignoredUsersIDs: ["683040899881763091"]              # Entre comillas y separado por comas las IDs de los usuarios a ignorar por el AutoMod
        
welcomes:           # Documentación en https://docs.kirobot.cc/
    active: false                  # true para activar las bienvenidas, false para desactivarlo
    welcomeMessageMD: ""           # Mensaje a enviar por MD cuando se una un usuario, vacío para desactivarlo
    welcomeImageLink: ""             # Link de Imgur de la imagen de fondo a enviar por el canal de bienvenidas cuando se una un usuario, vacío para desactivarlo
    welcomeChannelID: ""            # Canal para enviar la foto de bienvenida, vacío para desactivarlo
    welcomeRoleID: ""                   # ID del rol a dar cuando se una un nuevo usuario
```

