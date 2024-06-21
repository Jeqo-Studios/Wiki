---
description: >-
  Many files are generated for both Bloons Legacy and Bloons Premium, this will
  include the configuration file, the language file(s), and the example balloon
  configurations.
---

# 📁 Default Files

{% code title="config.yml" %}
```yaml
# --------------------------------------------------#
#
# Bloons x.x.x
# Made by Jeqo
#
# Wiki:     https://jeqo.net/wiki/bloons
# Discord:     https://jeqo.net/discord
#
# Default Assets Made by TwistedDreams
# Get custom balloons and more for your server:
# https://mcmodels.net/vendors/pixelsonpoint/
#
# --------------------------------------------------#
#                     SETTINGS                      #
# --------------------------------------------------#
#
# Send a message to operators when they join if there is a Bloons update.
check-for-updates: true
# The language file to load. This will be used for all messages in the plugin.
language: en_US
# Do you want to close the menu when a player equips a balloon?
close-on-equip: true
# Do you want to close the menu when a player unequips a balloon?
close-on-unequip: true
# Do you want to hide balloons that the player does not have permission for?
hide-balloons-without-permission: true
# Title for the balloons menu.
menu-title: "&f"
# Amount of slots per page. Valid values: 27, 36, 45, and 54. 9 of these slots will be used for the menu buttons.
menu-size: 54
# Amount of slots from the top that you want the balloons to appear in. Valid values: 9, 18, 27, 36, and 45.
# This has the be at least 9 less than the menu-size!
balloon-slots: 45
# Notice: Keep buttons in the last row of your entire menu to avoid any bugs!
buttons:
  previous-page:
    material: FLINT
    custom-model-data: 1
    name: '<gray>← ᴘʀᴇᴠɪᴏᴜs ᴘᴀɢᴇ'
    slots:
      - 48
  unequip:
    material: FLINT
    custom-model-data: 2
    name: '<gray>ᴜɴᴇǫᴜɪᴘ ʙᴀʟʟᴏᴏɴ'
    slots:
      - 49
  next-page:
    material: FLINT
    custom-model-data: 3
    name: '<gray>ɴᴇxᴛ ᴘᴀɢᴇ →'
    slots:
      - 50
```
{% endcode %}



{% code title="languages/en_US.yml" %}
```yaml
messages:
  prefix: '<gradient:#ff00cc:#5555ff>[Bloons]</gradient> <white>'
  no-permission: '<#fc1c1c>Access denied.'
  player-not-found: '<#fc1c1c>Player not found.'
  config-reloaded: '<green>Config reloaded.'
  command-disabled: '<#fc1c1c>This command is currently disabled!'

  equipped: '%s <green>equipped!'
  unequipped: '<green>Your balloon has been stored safely.'
  balloon-not-found: '<#fc1c1c>Balloon not found.'
  not-equipped: '<#fc1c1c>You do not currently have a balloon equipped.'

  material-not-dyeable: 'Material %s is not a dyeable material.'
  invalid-rgb-values: 'RGB values must be between 0 and 255 to be valid.'
  balloon-not-set: 'The balloon %s is not set in the configuration!'
  material-not-set: 'The material of the balloon %s is not set in the configuration!'
  material-not-valid: 'The material of the balloon %s is not a valid material! Material: %s'
  material-is-not-valid: 'Material %s is not a valid material!'
  invalid-item-meta: 'ItemMeta is not valid for material: %s'

  no-balloons-registered: 'No balloons are found! Cannot create a menu with no balloons.'

  configuration-folder-not-found: 'Configuration folder not found: %s'
  no-configuration-files-found: 'No configuration files found in the folder: %s'
  configuration-section-not-found: 'Configuration section not found for file: %s'
  balloon-type-not-found: 'Error processing balloon type for section: %s in file: %s. Balloon type does not exist or is null.'
  balloon-process-error: 'Error processing balloon for section: %s in file: %s. Error: %s'

  menu-slot-out-of-bounds: '%s menu page button slot(s) out of bounds!'

  invalid-hex-code: 'Invalid hex code: %s'
```
{% endcode %}

{% code title="balloons/color_pack_example.yml" %}
```yaml
# A configuration like this is expressed as a balloon "pack" internally
# It can contain all the way from one balloon to technically an infinite
# amount of balloons, as long as the server can handle it.
blue:
  type: single # The type of balloon, this must be single for single balloons
  id: blue
  permission: balloon.blue
  material: FLINT
  custom-model-data: 4
  name: '<blue>Blue <white>Balloon'
  lore:
    - '&8Bloons Default Balloon'
    - ''
    - '&eᴄʟɪᴄᴋ ᴛᴏ ᴇǫᴜɪᴘ'
green:
  type: single
  id: green
  permission: balloon.green
  material: FLINT
  custom-model-data: 5
  name: '<green>Green <white>Balloon'
  lore:
    - '&8Bloons Default Balloon'
    - ''
    - '&eᴄʟɪᴄᴋ ᴛᴏ ᴇǫᴜɪᴘ'
pink:
  type: single
  id: pink
  permission: balloon.pink
  material: FLINT
  custom-model-data: 6
  name: '<light_purple>Pink <white>Balloon'
  lore:
    - '&8Bloons Default Balloon'
    - ''
    - '&eᴄʟɪᴄᴋ ᴛᴏ ᴇǫᴜɪᴘ'
yellow:
  id: yellow
  permission: balloon.yellow
  material: FLINT
  custom-model-data: 7
  name: '<yellow>Yellow <white>Balloon'
  lore:
    - '&8Bloons Default Balloon'
    - ''
    - '&eᴄʟɪᴄᴋ ᴛᴏ ᴇǫᴜɪᴘ'
```
{% endcode %}

{% code title="balloons/dyeable_example.yml" %}
```yaml
# This is an example of a singular balloon config, this is a dyeable balloon that
# can be dyed to any color in the game. This is a very simple example of a balloon
# that contains just one segment.
dyeable_example:
  type: single
  id: dyeable_example
  permission: balloon.dyeable
  material: LEATHER_HORSE_ARMOR
  color: '#ffffff'
  custom-model-data: 1
  name: '<white>Dyeable Balloon'
  lore:
    - '&8Bloons Example Balloon'
    - ''
    - '&eᴄʟɪᴄᴋ ᴛᴏ ᴇǫᴜɪᴘ'
```
{% endcode %}

{% code title="balloons/multipart_example.yml (premium only)" %}
```yaml
# This is an example of a configuration which only holds the configuration data of
# a singular multipart balloon. This is a train balloon that has a head, body, and tail.
multipart_example:
  type: multipart # The type of balloon, this must be multipart for multipart balloons
  id: multipart_example # The id of the balloon, this must be unique
  permission: balloon.multipart_example
  name: '<white>Multipart Balloon'
  lore:
    - '&8Bloons Default Balloon'
    - ''
    - '&eᴄʟɪᴄᴋ ᴛᴏ ᴇǫᴜɪᴘ'
  node-count: 5 # The amount of nodes/models in the balloon including the head and tail
  distance-between-nodes: 2.0 # The distance between nodes/models in blocks
  leash-height: 1.2 # The height of the leash from the zero relative to the balloon
  head-node-offset: 0.0 # The offset of length of head node segments in blocks
  body-node-offset: 0.0 # The offset of length of body node segments in blocks
  tail-node-offset: 0.0 # The offset of length of tail node segments in blocks
  max-joint-angle: 35.0 # The max angle in degrees of freedom for each joint between nodes
  y-axis-interpolation: 0.2 # The amount of interpolation between nodes on the Y axis (must be between 0.0 and 1.0)
  turning-spline-interpolation: 0.5 # The amount of interpolation for the spline when turning
  passive-sine-wave-speed: 0.05 # The speed of the passive sine wave
  passive-sine-wave-amplitude: 0.5 # The amplitude of the passive sine wave
  passive-nose-sine-wave-amplitude: 0.5 # The amplitude of the passive sine wave for the nose
  head: # Head must be supplied for a balloon of this kind
    material: LEATHER_HORSE_ARMOR # The material of the head
    color: '#FF0000' # The color of the head item, this is optional
    custom-model-data: 10280 # The custom model data of the head, this is not required but is recommended for use of models
  body: # Body must be supplied for a balloon of this kind
    material: LEATHER_HORSE_ARMOR # The material of the body
    color: '#ffffff' # The color of the body, this is optional
    custom-model-data: 10281 # The custom model data of the body, this is not required but is recommended for use of models
  tail: # Tail must be supplied for a balloon of this kind
    material: LEATHER_HORSE_ARMOR # The material of the tail
    color: '#ffffff' # The color of the tail, this is optional
    custom-model-data: 10282 # The custom model data of the tail, this is not required but is recommended for use of models
```
{% endcode %}

Along with the automatically generated files packed within the plugin, many other translations/locales come included with Bloons Premium, these include but are not limited to:

* es\_US&#x20;
* de\_DE
* fr\_FR
* ja\_JP
* ko\_KR
* pt\_PT
* ru\_RU
* zh\_CN
