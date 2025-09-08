---
tags:
  - command
---

# /camera

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/camera distance [reset | <distance>] [save]
/camera attach [target | id <spawn_id> | <spawn_name>]
/camera [info | detach | reset]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Manipulate the game's third person camera. No parameters shows usage.
<!--cmd-desc-end-->

## Options

`distance <value> [save]`
:   Set a new maximum distance. Cannot be lower than the default max camera distance.

`distance reset [save]`
:   Reset camera distance to default.

`info`
:   show the current settings for the camera distance

`attach target`
:   Attach camera to your target.

`attach id <spawn_id>`
:   Attach camera to spawn by ID.

`attach <spawn_name>`
:   Attach camera to spawn by name (partial matching).

`attach`
:   Reset camera to your character.

`detach`
:   Reset camera to your character.

`reset`
:   Reset camera to your character.

**save** - If save is specified, the value will be written to the INI file and automatically applied the next time the plugin is loaded.