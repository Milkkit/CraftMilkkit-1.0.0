CraftMilkkit 1.0.0
===========

A Bukkit (Minecraft Server API) implementation.

CraftMilkkit is an server software that patches vulnerabilites and gives performance patches

Project is currently not ready for compiling

Bugs/Suggestions: [Discord](https://discord.gg/kt3Ap6gSU3)  

Regarding the DMCA of CraftBukkit in 2014
------------
The contributor Wolverness who first contributed on CraftBukkit in February 2012 issued a DMCA against CraftBukkit and other major forks of CraftBukkit. This project is based on the following commits:

CraftBukkit: [54bcd1c1f36691a714234e5ca2f30a20b3ad2816](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/craftbukkit/commits/54bcd1c1f36691a714234e5ca2f30a20b3ad2816) (SpigotMC)
Bukkit: [3524fde5ffc387ef9e39f6ee7dae83ff4dbf8229](https://github.com/Bukkit/Bukkit/commit/3524fde5ffc387ef9e39f6ee7dae83ff4dbf8229) (GitHub)
The Bukkit and CraftBukkit commits that CraftMilkkit is based on are before Wolverness started contributing.

If you were a contributor before these commits please feel free to contact me or open an issue asking for this repository to be taken down.

Compilation
-----------

We use maven to handle our dependencies.

* Install [Maven 3](http://maven.apache.org/download.html)
* Check out and install [Bukkit](http://github.com/Bukkit/Bukkit)
    * *Note*: this is not needed as the repository we use has Bukkit too, but you might have a newer one (with your own changes :D)
* Check out this repo and: `mvn clean package`
