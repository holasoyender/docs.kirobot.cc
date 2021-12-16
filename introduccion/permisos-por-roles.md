---
description: Una guía de como usar los permisos por roles de deKiro
cover: >-
  https://images.unsplash.com/photo-1500042600524-37ecb686c775?crop=entropy&cs=srgb&fm=jpg&ixid=MnwxOTcwMjR8MHwxfHNlYXJjaHw3fHxjb2xvcnN8ZW58MHx8fHwxNjM5NjkyMDc2&ixlib=rb-1.2.1&q=85
coverY: 0
---

# Permisos por roles

**deKiro** cuenta con un modulo de permisos por roles, esto significa que independientemente de los permisos de servidor del usuario, podrá accionar comandos de mayor nivel si posee un rol especificado en la configuración.\
Los roles disponibles son los siguientes (con sus correspondientes comandos)

### Moderador:

La ID del rol especificado en el apartado de `modRoleID`dentro del módulo `moderation`tendrá permisos para ejecutar estos comandos:

```
Lista de comandos disponibles con el rol "Moderador":
 - Ban 
 - Clear 
 - Delinfr 
 - Infrs
 - Kick
 - Modinf
 - Mute
 - Limitar
 - Tempban
 - Tempmute
 - Unban
 - Unmute
 - Vozkick
 - Warn
```

### Administrador:

La ID del rol especificado en el apartado de `adminRoleID`dentro del módulo `moderation`tendrá permisos para ejecutar estos comandos:

```
Lista de comandos disponibles con el rol "Administrador":
 - Todos los comandos del rol de "Moderador"
 - Custom
 - Darrol
 - Delinfrs
 - Deshabilitar/habilitar comandos
 - Poll
 - Quitarrol
 - Sorteo
```

### Configurador:

La ID del rol especificado en el apartado de `configRoleID`dentro del módulo `moderation`tendrá permisos para ejecutar estos comandos:

```
Lista de comandos disponibles con el rol "Configurador":
 - Exportar
 - Importar
 - Iniciar
```

### Sorteo:

La ID del rol especificado en el apartado de `giveawayRoleID`dentro del módulo `moderation`tendrá permisos para ejecutar el comando de **sorteo.**
