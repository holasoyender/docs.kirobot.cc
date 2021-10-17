---
description: Como configurar a deKiro
---

# Configuración

{% hint style="success" %}
Te recomendamos usar un IDE especial para editar el archivo. Si no tienes uno, puedes configurarlo en cualquier editor y verificarlo en [https://yamlvalidator.com/](https://yamlvalidator.com)
{% endhint %}

### Como configurar

Todo menos el AutoMod tiene que ir entre comillas (`" "`) y en el caso de tener múltiples argumentos, tendrán que ir separados por comas (`[" ", " "]`).

### Idiomas permitidos

Actualmente solo están disponibles 2 idiomas:  **esp** (Español de España) y **eng** (Ingles de Estados Unidos)

Puedes contribuir añadiendo un idioma en el [servidor de soporte](https://discord.gg/Rwy8J35) y obtendrás una badge de contribuyente!

### Moderación

Para poder usar el comando **mute** (silenciar) debes especificar la ID del rol de mute en el apartado de  `muteRoleID` 

### Logs

Si quieres que **deKiro **haga logs de las acciones del servidor, debes de especificar una ID de canal valida en el apartado `logChannelID`

Para ignorar usuarios o canales debes poner sus IDs en `ignoredChannelsIDs` e `ignoredUsersIDs` respectivamente.

### AutoMod

Para activar **deKiro AutoMod** debes de poner `true`en el apartado de `active`, para filtrar toda invitación a servidores externos debes de activarlo en el apartado de `deleteInvites`con `true`.

Cualquier palabra que se ponga en `bannedWords`será borrada por el **AutoMod** 

Para ignorar usuarios o canales debes poner sus IDs en `ignoredChannelsIDs` e `ignoredUsersIDs` respectivamente (como en el apartado de Logs).

### Bienvenidas

Para activar las bienvenidas, debes de poner `true`en el apartado de `active`.

#### Mensaje por MD

Se mandará un mensaje por MD al nuevo usuario con el texto que se ponga dentro de `welcomeMessageMD`, están disponibles para ello las siguientes variables:

```bash
{servidor} : Nombre del servidor
{server}: Nombre del servidor

{salto} : Salto de línea
{jump}: Salto de línea

{usuario} : Nombre y discriminator del usuario (Antonio#6234)
{user} : Nombre y discriminator del usuario (Pepe#6234)
```

#### Banner de bienvenida y rol

Se mandará un banner de bienvenida al canal especificado en `welcomeChannelID`con la imagen de fondo que se especifique en `welcomeImageLink`\
\
La imagen de `welcomeImageLink` debe de tener un tamaño de `1024x450`pixeles.\
\
También se asignará a los nuevos usuarios con el rol especificado en `welcomeRoleID`.

![](../.gitbook/assets/unknown\[3].png)
