# Filebot - Filebot mod for deluge

This mods adds support for [Deluge FileBotTool plug-in](https://github.com/Laharah/deluge-FileBotTool) for deluge.
* Adds Filebot / MediaInfo / ZenLib / Java

**FileBotTool plug-in has not been updated for Deluge 2.0 yet and still requires Deluge 1.3.x. This mod will not work with the official linuxserver.io Deluge container without running an older version with Deluge 1.3.x**

In deluge docker arguments, set an environment variable `DOCKER_MODS=edifus/mods:deluge-filebot` to enable.

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=edifus/mods:deluge-filebot|edifus/mods:deluge-mod2`
