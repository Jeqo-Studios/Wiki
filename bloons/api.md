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
