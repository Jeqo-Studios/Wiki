---
description: >-
  Creating a balloon can seem like a bit task at first, but our streamlined and
  easy-to-use configuration system makes it easy to create a nearly infinite
  amount of balloons tailored to your needs.
---

# 🎈 Creating A Balloon

### Balloon Configuration Fields

Below you can find tables with information regarding the configurations used to create balloons. One is for multipart balloons, and the other is for single balloons.

#### Single Balloon Fields

Fields that can be used in the creation of a single-type balloon via a configuration file.

<table><thead><tr><th width="158">Field</th><th width="216">Description</th><th width="119">Value Type</th><th>Requirement</th></tr></thead><tbody><tr><td><code>type</code></td><td>The type of balloon that this is. The two options are <code>single</code> and <code>multipart</code> respectively.</td><td><code>String</code></td><td>Optional (defaults to single)</td></tr><tr><td><code>id</code></td><td>The unique ID of the balloon used for internal purposes.</td><td><code>String</code></td><td>Required</td></tr><tr><td><code>permission</code></td><td>The required permission that a player needs to utilize the balloon type.</td><td><code>String</code></td><td>Required</td></tr><tr><td><code>leash-height</code></td><td>The height of the leash attached from the player to the balloon. This is measured in blocks and is relative to the head of the player.</td><td><code>double</code></td><td>Optional (defaults to 1.2)</td></tr><tr><td><code>balloon-height</code></td><td>The height of the physical balloon model/armor stand. This is measured in blocks and is relative to the head of the player.</td><td><code>double</code></td><td>Optional (defaults to 2.0)</td></tr><tr><td><code>material</code></td><td>The name of the material to use for the model of the balloon. This appears on the head slot of the armor stand. It <strong>MUST</strong> be a valid Minecraft material.</td><td><code>String</code></td><td>Required</td></tr><tr><td><code>custom-model-data</code></td><td>The custom model data value of the item used as the model of the balloon. This is stored on the item meta of the GUI item and the armor stand model.</td><td><code>int</code></td><td>Required</td></tr><tr><td><code>name</code></td><td>The name of the balloon. This is both displayed in the GUI with the specified color coding and it also used for chat messages in relation to the balloon.</td><td><code>String</code></td><td>Required</td></tr><tr><td><code>lore</code></td><td>The lore of the item that appears within the Bloons main GUI menu. This is not used anywhere else and is not stored on the model of the physical balloon.</td><td><code>String[]</code></td><td>Required</td></tr></tbody></table>



