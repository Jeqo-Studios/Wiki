---
description: >-
  Learn how to configure language and locale settings for our Minecraft plugins
  to match your preferred language and regional preferences.
---

# 🗨️ Language/Locale

{% code title="messages.yml" %}
```yaml
# All messages support Minecraft (&f) and hex (#ffffff) color codes.
# Kick-on-decline and welcome messages have multi-line support.
welcome-message:
  - ' '
  - ' '
  - '                           #fc1c1cGizmo - Made by Jeqo'
  - '                             #acb5bfwww.jeqo.net/gizmo'
  - ' '
  - ' '
first-join-welcome-message:
  - ' '
  - ' '
  - '                           #fc1c1cGizmo - Made by Jeqo'
  - '                             #acb5bfwww.jeqo.net/gizmo'
  - ' '
  - ' '

kick-on-decline:
  - '&cYou must download the server resource pack to play!'
  - ' '
  - '#fc1c1cGizmo - Made by Jeqo'
  - '#acb5bfwww.jeqo.net/gizmo'

no-pack-loaded: '&7Server resource pack not detected-skipping welcome screen.'
no-permission: '#fc1c1cAccess denied.'
player-not-found: '&7Player not found.'

show-screen: '&7Displaying test screen.'
show-screen-others: '&7Displaying test screen to %player_name%'

config-reloaded: '&7Configuration reloaded.'
```
{% endcode %}
