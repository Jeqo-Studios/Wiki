---
description: >-
  Learn how to set up and modify the config.yml file to tailor Bloons to your
  specific needs.
---

# 📜 Main Configuration

The main configuration file for Bloons is generated as `config.yml` in the root of the Bloons directory.

{% code title="config.yml" %}
```yaml
# --------------------------------------------------#
#
# Bloons [version]
# Made by Jeqo Studios
#
# Wiki:     https://jeqo.net/wiki
# Discord:     https://jeqo.net/discord
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
