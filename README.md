# autodl-irssi - autodl-irssi mod for ruTorrent

This mod adds [irssi](https://irssi.org/), [autodl-irssi](https://github.com/autodl-community/autodl-irssi) and [autodl-irssi ruTorrent plug-in](https://github.com/autodl-community/autodl-rutorrent) to [ruTorrent](https://github.com/linuxserver/docker-rutorrent) container

In rutorrent docker arguments, set an environment variable `DOCKER_MODS=edifus/mods:rutorrent-autodl-irssi` to enable.

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=edifus/mods:rutorrent-autodl-irssi|edifus/mods:rutorrent-mod2`


## Information
* Recommended to use an IRC bouncer such as [ZNC](https://github.com/linuxserver/docker-znc)

### Access irssi inside container
* `docker exec -it rutorrent screen -r irssi`

To disconnect from irssi session, use the normal gnu screen command (Ctrl+a d)
* `/config/.screenrc` can be customized to change screen configuration for irssi. These settings will not apply to screen running rtorrent.

###
* `/config/.irssi/` this directory contains the configuration for irssi and can be used to install additional scripts and themes
