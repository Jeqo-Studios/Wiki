---
description: >-
  Creating a balloon can seem like a bit task at first, but our streamlined and
  easy-to-use configuration system makes it easy to create a nearly infinite
  amount of balloons tailored to your needs.
---

# 🎈 Creating A Balloon

### Balloon Types

There are two balloon types packaged within Bloons. These are `single` and `multipart`. You can find the [single balloon configuration fields](single-configuration-fields.md) and [multipart balloon configuration fields](multipart-configuration-fields.md) in the hyperlinks provided.

### Creating a Minimal Single Balloon

There are a **LOT** of configurations that you can use to create a single balloon. Below you can find an example of a minimal balloon with the minimum options along with an explanation of the configuration.

{% code title="minimal_single.yml" %}
```yaml
minimal:
  type: single
  id: minimal
  permission: balloon.minimal
  material: FLINT
  custom-model-data: 4
  name: '<white>Minimal Balloon'
  lore:
    - '&8Bloons Default Balloon'
    - ''
    - '&eᴄʟɪᴄᴋ ᴛᴏ ᴇǫᴜɪᴘ'
```
{% endcode %}

This is a minimal single balloon with the minimum requirements to create a balloon. Every field except the leash height, balloon height, and color are required.

### Creating a Maximized Single Balloon

Creating a single balloon configuration with all of the configurations is made easy. Below you can find an example configuration that utilizes all options available.

{% code title="maximized_single.yml" %}
```yaml
maximized:
  type: single
  id: maximized
  permission: balloon.maximized
  leash-height: 1.2
  balloon-height: 2.0
  material: LEATHER_HORSE_ARMOR
  color: '#FF0000'
  custom-model-data: 4
  name: '<white>Minimal Balloon'
  lore:
    - '&8Bloons Default Balloon'
    - ''
    - '&eᴄʟɪᴄᴋ ᴛᴏ ᴇǫᴜɪᴘ'
```
{% endcode %}

This is a maximized single balloon configuration. This utilizes options like leash height, balloon height, and color fields which offer a more configured experience when using the balloon. Be aware that the color field can only be used with leather items used in the material field.

### Creating a Minimal Multipart Balloon

Creating a multipart balloon in a short period of time is simple. With a minimalistic set of fields that are used, you can be up and running within less than a minute.

{% code title="minimal_multipart.yml" %}
```yaml
multipart_example:
  type: multipart
  id: minimal
  permission: balloon.minimal
  name: '<white>Minimal Multipart Balloon'
  lore:
    - '&8Bloons Default Balloon'
    - ''
    - '&eᴄʟɪᴄᴋ ᴛᴏ ᴇǫᴜɪᴘ'
  head:
    material: LEATHER_HORSE_ARMOR
    custom-model-data: 10280
  body:
    material: LEATHER_HORSE_ARMOR
    custom-model-data: 10281
  tail:
    material: LEATHER_HORSE_ARMOR
    custom-model-data: 10282
```
{% endcode %}

This is an example of a minimal multipart balloon. All configurations in regards to the sine waves, lengths, and various other offset settings can be stripped down to a simple and easy-to-use configuration that can be whipped up in less than a minute.

### Creating a Maximized Multipart Balloon

Although multipart balloons are made to be easy and minimalistic to create, there is a wide range of fields that can be used to tune multipart balloons exactly to your liking. Below you can find an example of a balloon that uses every field available to make a perfect starting balloon.

{% code title="maximized_multipart.yml" %}
```yaml
multipart_example:
  type: multipart
  id: multipart_example
  permission: balloon.multipart_example
  name: '<white>Multipart Balloon'
  lore:
    - '&8Bloons Default Balloon'
    - ''
    - '&eᴄʟɪᴄᴋ ᴛᴏ ᴇǫᴜɪᴘ'
  node-count: 5
  distance-between-nodes: 2.0
  leash-height: 1.2
  head-node-offset: 0.0
  body-node-offset: 0.0
  tail-node-offset: 0.0
  max-joint-angle: 35.0
  y-axis-interpolation: 0.2
  turning-spline-interpolation: 0.5
  passive-sine-wave-speed: 0.05
  passive-sine-wave-amplitude: 0.5
  passive-nose-sine-wave-amplitude: 0.5
  head:
    material: LEATHER_HORSE_ARMOR
    color: '#FF0000'
    custom-model-data: 10280
  body:
    material: LEATHER_HORSE_ARMOR
    color: '#ffffff'
    custom-model-data: 10281
  tail:
    material: LEATHER_HORSE_ARMOR
    color: '#ffffff'
    custom-model-data: 10282
```
{% endcode %}

This example uses a custom sine wave for the animation and tunes the interpolation values to give an elegant and free-feeling experience when using multipart balloons.
