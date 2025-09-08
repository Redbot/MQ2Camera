---
tags:
  - plugin
resource_link: "https://www.redguides.com/community/resources/mq2camera.106/"
support_link: "https://www.redguides.com/community/threads/mq2camera.37154/"
repository: "https://github.com/brainiac/MQ2Camera"
config: "mq2camera.ini"
authors: "brainiac, Knightly"
tagline: "MQ2 plugin to manipulate the game's third person camera."
quick_start: "https://www.youtube.com/watch?v=0EOjsJ13ELY"
---

# MQ2Camera

<!--desc-start-->
MacroQuest plugin to manipulate the game's third person camera, providing a distance option that lets you zoom the camera further away from your character.
<!--desc-end-->

## Commands

<a href="cmd-camera/">
{% 
  include-markdown "projects/mq2camera/cmd-camera.md" 
  start="<!--cmd-syntax-start-->" 
  end="<!--cmd-syntax-end-->" 
%}
</a>
:    {% include-markdown "projects/mq2camera/cmd-camera.md" 
        start="<!--cmd-desc-start-->" 
        end="<!--cmd-desc-end-->" 
        trailing-newlines=false 
     %} {{ readMore('projects/mq2camera/cmd-camera.md') }}

## Settings

```ini
[MQ2Camera]
MaxDistance=300.00
```

## Video

- [MQ2Camera Quick Demo Video](https://www.youtube.com/watch?v=0EOjsJ13ELY)
