---
description: >-
  Learn how to set up and modify the config.yml file to tailor our Minecraft
  plugins to your specific needs.
---

# 📜 Configuration

The main configuration file for Gizmo is generated as 'config.yml' in the root of the Gizmo directory.

<pre class="language-yaml" data-title="config.yml"><code class="lang-yaml"><strong>debug-mode: false
</strong># -------------------------------------------------- #
#
# Gizmo [version] - Made by Jeqo
#
# Discord:
# https://jeqo.net/discord
#
# Resource &#x26; Data Pack Guides:
# https://jeqo.net/guides
#
# -------------------------------------------------- #
background-color: '&#x26;0' # Minecraft color and hex code supported (i.e. &#x26;0 or #000000).

delay: 0 # The delay (in ticks; 20 ticks per second) for the welcome screen to be displayed after joining.
delay-background: false # Display the background texture while the delay is active.

enable-fade: true # Fade the screen with your background texture when advancing.
fade-time: 10 # The duration (in ticks; 20 ticks per second) for the fade.

# Execute commands from the player or console, or send a message.
# Valid prefixes: [player], [console], [message]
# To disable commands -> commands-on-advance: []
commands-on-advance:
  - '[player] balance'
  - '[console] give %player% dirt 1'
  - '[message] Is that dirt in your inventory? Ew...'

# Give the player invulnerability when loading the pack.
# Recommended if you don't have a plugin that keeps your players safe whilst loading the pack.
player-invulnerable-during-load: true
blindness-during-prompt: true # Give players blindness when they have the pack prompt.

kick-on-decline: false # Kick the player if they don't accept the pack.

hide-join-messages: false # If true, player join messages will be hidden.
hide-quit-messages: false # If true, player quit messages will be hidden.

sound-on-pack-load: # Play a sound when the player's pack finishes loading.
  enable: true
  sound: ENTITY_PLAYER_LEVELUP
  volume: 0.5
  pitch: 1

sound-on-advance: # Play a sound when the player advances from the welcome screen.
  enable: true
  sound: ENTITY_CHICKEN_EGG
  volume: 0.5
  pitch: 1
</code></pre>
