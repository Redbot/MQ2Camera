---
tags:
  - plugin
---

# MQ2Camera

<!--desc-start-->
MacroQuest plugin to manipulate the game's third person camera, providing a distance option that lets you zoom the camera further away from your character.
<!--desc-end-->

## Commands

<a href="cmd-camera/">
{% 
  include-markdown "plugins/community-plugins/mq2camera/cmd-camera.md" 
  start="<!--cmd-syntax-start-->" 
  end="<!--cmd-syntax-end-->" 
%}
</a>
:    {% include-markdown "plugins/community-plugins/mq2camera/cmd-camera.md" 
        start="<!--cmd-desc-start-->" 
        end="<!--cmd-desc-end-->" 
        trailing-newlines=false 
     %} {{ readMore('plugins/community-plugins/mq2camera/cmd-camera.md') }}

## Settings

```ini
[MQ2Camera]
MaxDistance=300.00
```

## Video

- [MQ2Camera Quick Demo Video](https://www.youtube.com/watch?v=0EOjsJ13ELY)
