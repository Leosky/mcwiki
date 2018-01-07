<!-- TITLE: Forge -->

# Forge

## Configuration
### Default files
* [r126 actuallyadditions.cfg](https://gist.githubusercontent.com/Leosky/9e9f0e3c752f3e886f5789b138489ba3/raw/ec165a242f314d8184481bcafd64c1e949734db3/actuallyadditions.cfg)
​
### Important values
Each entry is a regex search value.
* ```machine values/S:Item Repairer Extra Whitelist``` : to add item to repairable item in the Item Repairer.
* ```"tool control" {``` : This section containe all added tool, AIOT tools are a bit overpowered and others are useless ore too powerfull (Emeralds ones).
* ```AIOT"= ``` : To search AIOT tools specificaly.
​
## packdev
### forge.cfg
*  ```B:disableVersionCheck=true```
*  ```I:dimensionUnloadQueueDelay=120```
*  ```B:alwaysSetupTerrainOffThread=true```
*  version_checking {
    # Enable the entire mod update check system. This only applies to mods using the Forge system.
    B:Global=false
	}