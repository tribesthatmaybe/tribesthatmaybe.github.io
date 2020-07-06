---
layout: page
title: How To Play
author: gadget
categories: pages
---

Tribes That May Be is currently in a pre-release state. You can find the latest development artifacts on our modpack [actions page](https://github.com/tribesthatmaybe/modpack/actions?query=workflow%3Amake-modpack). For single player usage, you can probably download the most recent artifact that has been succesfully build. Make sure the build you are selecting has a green checkbox next to it although please note that is no guarantee the version is completely bug free.

Due to the variety of mods included in this pack you do need a very fresh version of Java installed. This involves going to the sketchy-looking-but-totally-legit [java dot com](https://www.java.com/) website and installing the latest for your platform.

If you find anything that either doesn't work, or does not work as expected, please open an [issue on Github](https://github.com/tribesthatmaybe/modpack/issues).

# Client Installation

The Tribes That May Be crew would not recommend trying to use this modpack without a launcher to a friend. The Twitch Launcher is more popular and generally easier to use than MultiMC. Developers tend to prefer MultiMC as it makes juggling packs much easier. It does not support easy upgrades like Twitch does. Given that the modpack is not (yet) up on [Curseforge](https://www.curseforge.com/), either launcher is probably fine. Note that this is a bit of a beefy modpack and we recommend a minimum of 6Gb of memory being allocated.

## Twitch Launcher

Download and install the [Twitch App](https://www.twitch.tv/downloads). You will need to have a Twitch account to use this app. Once it has loaded, click on the `Mods` tab and select `Minecraft`. It may take a few moments to load. Click through and then select `Create Custom Profile`. Click on the `import` button, and select the zip file you downloaded earlier. You will probably need to bump up the memory used in the [Minecraft settings[(https://help.twitch.tv/s/article/How-to-Play-Minecraft-with-Twitch-App#Settings).

## MultiMC Launcher

The [MultiMC](https://multimc.org/) launcher is much lighter weight than the more common Twitch launcher. It works on Windows, Mac, and Linux. After you have downloaded the MultiMC launcher and started it up, click on the `Add Instance` button in the upper right. From there, select `Import from zip` from the list on the left. Unfortunately you cannot just paste the artifact URL in the text field even though it implies you can. Click `Browse` and select the zip file of the `ttmb-client` artifact you downloaded previously.

Things will happen for a bit as the modpack dependencies are downloaded. Once that has completed, you can select the new icon and click `Launch`.

# Servers

## Dev Server

The Tribes That May Be crew runs a development server. It is currently open to anyone with a registered Minecraft account. You can connect to it at `ttmb-dev.spmc.co`. Nothing here should be considered more than temporal, we do a lot of explosives based testing. We make use of [stickypiston](https://stickypiston.co/) for hosting and they are pretty great.

## Your Own Server

You can download and run a server on your own if you desire. Make sure to use the same build for both client and server. You must also make sure that commandblocks are enabled.

More guidance on running your own server will be provided once we are up on Curseforge.

# Notable Versions

| Version | Use |
| ------- | --- |
| [`0.0.1-07092f3c`](https://github.com/tribesthatmaybe/modpack/actions/runs/154559356) | dev server version |
| [`0.0.1-099b4a21`](https://github.com/tribesthatmaybe/modpack/actions/runs/159692991) | latest "stable" dev release |
