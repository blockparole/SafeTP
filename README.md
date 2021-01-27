# SafeTP
[![Download](https://img.shields.io/github/downloads/nothub/SafeTP/latest/total.svg?label=download%20latest&style=popout-square)](https://github.com/nothub/SafeTP/releases/latest)
[![RepoSize](https://img.shields.io/github/languages/code-size/nothub/SafeTP.svg?label=repo%20size&style=popout-square)](https://github.com/nothub/SafeTP)
[![HitCount](http://hits.dwyl.com/nothub/SafeTP.svg)](https://github.com/nothub/SafeTP)

A simple Teleport Plugin for Minecraft that uses [vanish](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/entity/Player.html#hidePlayer-org.bukkit.plugin.Plugin-org.bukkit.entity.Player-) to mitigate [Coordinate Exploitation](https://2b2t.miraheze.org/wiki/Coordinate_Exploits#Debug_Exploit/).  

Usage:
`/tpa <NAME>` `/tpy <NAME>` `/tpn <NAME>` `/tpt`

Default Config:
```
allow-multi-target-request: true
request-timeout-seconds: 60
unvanish-delay-ticks: 20
spawn-tp-deny: true
spawn-tp-deny-radius: 1500
```

This Project uses [PaperLib](https://github.com/PaperMC/PaperLib) and was tested on [Paper](https://papermc.io/) [1.12.2](https://papermc.io/api/v1/paper/1.12.2/1618).
