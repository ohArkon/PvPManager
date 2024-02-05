PvPManager
===========
[![Discord](https://discordapp.com/api/guilds/622559860705198108/widget.png)](https://discord.gg/QFTjs3g)
[![Spiget Downloads](https://img.shields.io/spiget/downloads/845?label=spigot%20downloads)](https://www.spigotmc.org/resources/pvpmanager-lite.845/)
[![Build Status](https://github.com/ChanceSD/PvPManager/actions/workflows/maven.yml/badge.svg)](https://ci.codemc.io/job/ChanceSD/job/PvPManager/)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ChanceSD_PvPManager&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ChanceSD_PvPManager)
[![Crowdin](https://badges.crowdin.net/pvpmanager/localized.svg)](https://crowdin.com/project/pvpmanager)
[![GitHub commits since latest release](https://img.shields.io/github/commits-since/chancesd/pvpmanager/latest)](https://github.com/ChanceSD/PvPManager/commits/master)
![GitHub Releases](https://img.shields.io/github/downloads/chancesd/pvpmanager/latest/total)
***

If you have any ideas/bugfixes and have some experience programming, feel free to join the Discord and send me a PM  
Any help is always welcome, specially given the size of this project keeps growing, new contributions are very appreciated

Useful Links
------------
**Spigot:** https://www.spigotmc.org/resources/pvpmanager-lite.845/  
**Bukkit:** http://dev.bukkit.org/bukkit-plugins/pvpmanager/  
**Discord:** https://discord.gg/QFTjs3g  
**Dev Builds:** https://ci.codemc.io/job/ChanceSD/job/PvPManager/  
**Help translate PvPManager:** https://crowdin.com/project/pvpmanager

Developers
------
Maven Repo:
```xml
<repository>
    <id>CodeMC</id>
    <url>https://repo.codemc.org/repository/maven-public/</url>
</repository>
```
Artifact Information:
```xml
<dependency>
    <groupId>me.NoChance.PvPManager</groupId>
    <artifactId>pvpmanager</artifactId>
    <version>3.15.6</version>
    <scope>provided</scope>
</dependency>
 ```

Description
------------
PvPManager is an all in one PvP plugin.
There are certainly some features that are better covered by a dedicated separate plugin. Still, PvPManager will try to cover most of those even if in a more superficial way, always maintaining good performance in mind. 

**Some of the plugin's main features are:**
- Toggle PvP for each player  
- Stop combat logging by issuing punishments
- Disable several actions while in combat such as fly, gamemode, blocking commands, etc
- Stop what we named as "border hopping" which happens when a player enters combat and attempts to run away to a safezone
- Protect new players from being killed by other players
- Stop spawn killing or KDR abuse by issuing a kick or any other custom command
- Give money rewards, penalties, steal money or execute commands when a player kills another
- Keep/Drop player inventory depending whether they died in PvP or transfer drops directly to the killer

You can find a detailed description of all features on the plugin page and in the config.  

bStats
-----------

[![bStats](https://bstats.org/signatures/bukkit/PvPManager.svg "bStats")](https://bstats.org/plugin/bukkit/PvPManager/ "bStats")

![YourKit](https://www.yourkit.com/images/yklogo.png)

PvPManager uses YourKit to make sure everything runs smoothly in your server.  
YourKit supports open source projects with innovative and intelligent tools
for monitoring and profiling Java and .NET applications.
YourKit is the creator of <a href="https://www.yourkit.com/java/profiler/">YourKit Java Profiler</a>,
<a href="https://www.yourkit.com/.net/profiler/">YourKit .NET Profiler</a>,
and <a href="https://www.yourkit.com/youmonitor/">YourKit YouMonitor</a>.

