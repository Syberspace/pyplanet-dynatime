# Dynatime
A [PyPlanet](https://pypla.net) plugin to dynamically set the time limit for each map based on the map's bronze time.

## Installation
1. download the latest release as zip and unpack it into `apps/dynatime` in your PyPlanet installation
    1. alternatively clone this repository into `apps/dynatime` in your PyPlanet installation
2. add `'apps.dynatime'` in your `settings/apps.py` file
3. restart PyPlanet


## Settings


#### Dynatime Active  
Lets you comfortably activate/deactivate the plugin without having to restart PyPlanet from within the admin interface in the game.  
_Default_: True
      
#### Dynatime Announce
Acitvates/Deactivates the announcement of the current map's bronze time and the resulting time limit at the start of each map.  
_Default_: True

#### Dynatime Multiplier
Used to calculate the time limit. The map's bronze time will be multiplied by this number to get the time limit.  
**Example**:   
Multiplier = 4; Map Bronze Time = 1:12; → Time Limit = 4:48  
Multiplier = 5; Map Bronze Time = 1:12; → Time Limit = 6:00  
Multiplier = 6; Map Bronze Time = 1:12; → Time Limit = 7:12  
_Default_: 5


## Compatibility

The plugin has been tested with PyPlanet 0.7.1 and 0.7.4. It is possible that the plugin does work with other versions of PyPlanet as well.

## Bugs
If you find a bug please feel free to open an issue here on GitHub.

