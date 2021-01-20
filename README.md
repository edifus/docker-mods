# autodl-irssi - autodl-irssi mod for ruTorrent

This mod adds [irssi](https://irssi.org/), [autodl-irssi](https://github.com/autodl-community/autodl-irssi) and [autodl-irssi ruTorrent plug-in](https://github.com/autodl-community/autodl-rutorrent) to [ruTorrent](https://github.com/linxuserver/docker-rutorrent) container

In rutorrent docker arguments, set an environment variable `DOCKER_MODS=edifus/mods:rutorrent-autodl-irssi` to enable.

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=edifus/mods:rutorrent-autodl-irssi|edifus/mods:rutorrent-mod2`


## Information
* Recommend using an IRC bouncer such as [ZNC](https://github.com/linuxserver/docker-znc)

### Access irssi inside container
* `docker exec -it rutorrent screen -r irssi`

### irssi scripts and themes
* Themes
  * Install in /config/.irssi
* Scripts 
  * Install in /config/.irssi/scripts

