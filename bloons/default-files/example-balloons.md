---
description: >-
  Want to have a taste of the capabilities of Bloons? The example balloons that
  come packaged are an easy way to experiment and to see what Bloons cando.
---

# 🎈 Example Balloons

### Where Can I Find These?

All of the below configuration files are stored in `Bloons/balloons` and are created upon the first initialization of the plugin.

### Color Pack

This example pack of balloons shows how you can easily create collections of balloons with custom properties like colors and custom model data.

{% code title="color_pack_example.yml" %}
```yaml
# A configuration like this is expressed as a balloon "pack" internally
# It can contain all the way from one balloon to technically an infinite
# amount of balloons, as long as the server can handle it.
blue:
  type: single
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

### Dyeable

An example of how easy it can be to create single balloons with custom hex code color values with custom properties like balloon height above the player and a custom leash height.

{% code title="dyeable_example.yml" %}
```yaml
# This is an example of a singular balloon config, this is a dyeable balloon that
# can be dyed to any color in the game. This is a very simple example of a balloon
# that contains just one segment.
dyeable_example:
  type: single
  id: dyeable_example
  permission: balloon.dyeable
  leash-height: 1.2
  balloon-height: 2.0
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

### MEG (ModelEngine)

(MEG) ModelEngine is now a part of our Jeqo Studios family and is especially useful when creating complex models for our single-node balloons. There is no current plan for implementing MEG into our multipart balloon systems.

{% code title="meg_example.yml" %}
```yaml
# An example of a MEG balloon which utilizes custom models from ModelEngine
meg_example:
  id: meg_example
  permission: balloon.meg_example
  meg-model-id: meg_example
  icon:
    material: FLINT
    custom-model-data: 7
    name: '<white>MEG Balloon'
    lore:
      - '&8Bloons Default Balloon'
      - ''
      - '&eᴄʟɪᴄᴋ ᴛᴏ ᴇǫᴜɪᴘ'
```
{% endcode %}

### Multipart

This is an awesome balloon to show you how easy it can be to create a chain or multipart balloon. These can be stored the same as single balloons in packs and take advantage of inverse kinematics physics.

{% code title="multipart_example.yml" %}
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

{% hint style="info" %}
Troubleshooting and Support

Having issues with Bloons? Join our [community Discord](https://jeqo.net/discord) server and leave a message!
{% endhint %}
