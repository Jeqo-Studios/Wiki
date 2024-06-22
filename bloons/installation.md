---
description: Learn how to quickly and easily install Bloons with this step-by-step guide.
---

# 🛠️ Installation

Installing Minecraft plugins can be a tricky start, especially with a plugin with such a large codebase and lots of configurations like Bloons. We'll walk through creating a Java Minecraft server that supports Bloons, adding Bloons, and ensuring the plugin works as expected.

## Technical Requirements

Bloons is a fairly lightweight plugin and doesn't use many resources server-wise, this means that it's light on memory, CPU usage, and IO. Overall, Bloons doesn't use much IO as it keeps configurations like balloons and translations inside of its memory throughout the duration that the plugin is enabled.

### Recommended Server Requirements

As per the [paper documentation](https://docs.papermc.io/paper/getting-started), the server requirements are the following:

* Java Version: Java 21 (for Minecraft 1.20.x)
* RAM/Memory: 4GB-6GB Minimum
* CPU: Intel i5, Intel i7, Xeon, or greater depending on the plugins the server is hosting
* Storage Space: 24GB or greater
* OS: Windows or a suitable Linux Distribution that can both install Java and run the official PaperMC server software or a PaperMC fork that contains the **Kyori Adventure Library**
* Network: 50MB/s or greater for download and 10MB/s or greater for upload

## Plugin Requirements

There are no plugin requirements for Bloons other than the base plugin itself at this point in time! You can go ahead and move forward throughout this guide.

## Creating a PaperMC Server

Although this is an important step in the process of hosting and utilizing the plugin, we will not be outlining the steps of creating and running a PaperMC server to use the plugin. We would like to kindly refer you to the [PaperMC getting started guide](https://docs.papermc.io/paper/getting-started) for detailed steps on installing the required dependencies of PaperMC and for details on downloading, installing, and running the PaperMC server.

## Installing Bloons

Now that you have created a PaperMC server, accepted the Minecraft EULA, and generated the files for your newly or currently existing server, you can now move on to installing the plugin and can get it up and running. Below you can find the steps detailed and laid out one by one:

1. If your server is currently running, please stop your server and ensure that it gracefully shuts down and saves all vital data from the previously run session.
2. Download Bloons by visiting the [official plugin page](https://jeqo.net/bloons). Save the plugin in an easy to remember location that you can easily access in the next few moments.
3. Open up the root directory of your server location, this is where your server JAR is currently located. Navigate to the `plugins` directory and place the Bloons plugin JAR that you downloaded in that directory.
4. Navigate back to the root of your server and start the PaperMC server via the script file you have created locally OR start your server the way you usually start your server. Whether it be a hosting panel or a command you tend to use regularly.&#x20;
5. View your console or your current server logs, if no errors have appeared in your console in regards to Bloons and a successful Bloons startup message has appeared then congrats, the plugin has now loaded Bloons! If there is an error or a warning of any importance in your console, please address it and reach out for support on our[ Discord server](https://jeqo.net/discord).
6. Ensure that all [default files](default-files/) generated properly by navigating to `/plugins/Bloons` and reviewing the language/locale files and various configurations by confirming that they are present and have the proper contents.

Congratulations on loading the Bloons plugin up and setting up your server if you haven't already done so! Our goal with Bloons was to make it as easy and seamless as possible to upload it to your server to ensure the best possible user experience as possible when utilizing your PaperMC server.

From all of Jeqo Studios, we hope you enjoy Bloons.

{% hint style="info" %}
Troubleshooting & Support

Having issues with Bloons? Join our [community Discord](https://jeqo.net/discord) server and leave a message!
{% endhint %}
