# The Forest
### From Endnight Games [Website](https://endnightgames.com/)
The egg uses the [SteamCMD](https://developer.valvesoftware.com/wiki/SteamCMD) technology to download [The Forest](https://store.steampowered.com/app/242760/The_Forest/) from the Steam Service.  

## Description From Steam Store Page
As the lone survivor of a passenger jet crash, you find yourself in a mysterious forest battling to stay alive against a society of cannibalistic mutants.

Build, explore, survive in this terrifying first person survival horror simulator.

### Install notes
Based on egg available from [NGLoader](https://gist.github.com/NgLoader/496b33e360d531826976a5a1e932b57d), attempted to add features and get egg to run consistently. 
Uses `xvfb`,`wine`, and `winetricks` 

Uses `steamcmd` to download the server files and then uses `xvfb` and `wine` to launch the server files.

Due to the requirements in getting The Forest to run `winetricks` is used to assist with the process.

### Minimum RAM warning
4096 MB Minimum required memory to run the server. [Recommended System Requirements](https://store.steampowered.com/app/242760/The_Forest/)


### Server Ports
The Forest uses the Steam Community Server Browser to populate Dedicated Servers requiring one port for itself, one for the game, and one for query.

| Port    | default |
|---------|---------|
| Steam    | 8766   |
| Game    | 27015   |
| Query    | 27016   |

These can be changed using the Pterodactyl Panel; however, will need allocation via Server Allocation

#### Mods/Plugins may require ports to be added to the server.
