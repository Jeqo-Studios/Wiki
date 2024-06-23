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
  color: "#FF0000"
  custom-model-data: 4
  name: '<white>Minimal Balloon'
  lore:
    - '&8Bloons Default Balloon'
    - ''
    - '&eᴄʟɪᴄᴋ ᴛᴏ ᴇǫᴜɪᴘ'
```
{% endcode %}

This is a maximized single balloon configuration. This utilizes options like leash height, balloon height, and color fields which offer a more configured experience when using the balloon. Be aware that the color field can only be used with leather items used in the material field.
