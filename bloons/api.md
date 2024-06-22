---
description: >-
  An API is the perfect addition to any Minecraft plugin, this will provide a
  detailed outline on using our custom Bloons API!
---

# 💻 API

## Maven Dependency Installation

Before using our Bloons API we need to first install the Maven GitHub package dependency. Before using the dependency in your project, please be sure to first [authenticate with your personal access token](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-apache-maven-registry#authenticating-to-github-packages) in your project.

Next, you can use the Bloons API in your project by adding the following to your `pom.xml` file:

```xml
<dependencies>
  <dependency>
    <groupId>net.jeqo</groupId>
    <artifactId>bloons</artifactId>
    <version>[version]</version>
  </dependency>
<dependencies/>
```

Replace `[version]` with the latest version of the API. At this point in time, the latest version is 2.0.0

## Examples

Below, you can find examples of some code to do a multitude of tasks with the Bloons plugin. This ranges from equipping balloons to players to unequipping balloons from players.

### Reloading Bloons

This will reload the main `config.yml` file and all balloon configurations. All language files are automatically refreshed upon the retrieval of values.

```java
// Trigger a custom event upon the reload of the config
BloonsConfigReloadEvent bloonsConfigReloadEvent = new BloonsConfigReloadEvent();
bloonsConfigReloadEvent.callEvent();

// If the event is cancelled, return out of the reload
if (bloonsConfigReloadEvent.isCancelled()) return;

// Reload the main config.yml and its defaults
Bloons.getInstance().reloadConfig();
Bloons.getInstance().getConfig().options().copyDefaults();
Bloons.getInstance().saveDefaultConfig();

// Refresh balloons and their configurations from their respective files
Bloons.getBalloonCore().initialize();
```

### Equipping a Single Balloon

Equipping a single balloon is a simple task to accomplish and can be an effective way to interact with the plugin. Please be sure to handle the removal of previous balloons and the removal of the player from the active balloons map properly.

```java
// Remove the previous balloon(s) here and remove the player from the map...

// Create a player object to direct the creation of a balloon at a player
Player player = ...;
// The ID of a registered balloon should appear here
String balloonID = "...";

// Call the equip event and check if it's cancelled, if it is, don't spawn the balloon or do anything
SingleBalloonEquipEvent singleBalloonEquipEvent = new SingleBalloonEquipEvent(player, balloonID);
singleBalloonEquipEvent.callEvent();

// If the called event is cancelled, do not continue to equip the balloon
if (singleBalloonEquipEvent.isCancelled()) return;

// Check if a balloon needs to be added or removed
SingleBalloonManagement.removeBalloon(player, Bloons.getPlayerSingleBalloons().get(player.getUniqueId()));
SingleBalloon.checkBalloonRemovalOrAdd(player, balloonID);
```

### Unequipping a Single Balloon

Unequipping balloons is a vital part when it comes to the balloon ecosystem. Please be sure to check the validity of the to be unequipped balloon before moving forward with the removal of it.

<pre class="language-java"><code class="lang-java">// Create a player object based on the player you want to unequip a balloon from
Player player = ...;

// Get the single balloon attached to the player in the active balloons map
SingleBalloon singleBalloon = Bloons.getPlayerSingleBalloons().get(player.getUniqueId());
<strong>
</strong><strong>// Check if the balloon is present and if they have one equipped here...
</strong><strong>
</strong><strong>// Call the balloon unequip event 
</strong><strong>SingleBalloonUnequipEvent singleBalloonUnequipEvent = new SingleBalloonUnequipEvent(player, singleBalloon);
</strong>singleBalloonUnequipEvent.callEvent();

// If the unequip balloon event is cancelled, return out of the unequipping
if (singleBalloonUnequipEvent.isCancelled()) return;

// Remove the balloon from the player
SingleBalloonManagement.removeBalloon(player, singleBalloon);
</code></pre>
