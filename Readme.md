# Minecraft-Cinematographer-AI

### Dependencies
 Python3.7
 
 Windos 10
```bash
pip install -r requirement.txt
```
### Install Minecraft Mod and Maps

Overwrite ".minecraft" to "%AppData%/.minecraft" to install Minecraft mod and maps.

#### Mod's Information:

player movement handler mod for [MC 1.12.2 jave ver.](https://www.minecraft.net/ja-jp/store/minecraft-java-edition)

using [forge-1.12.2-14.23.5.2855](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.12.2.html)

source code in "/.minecraft/mods/src/".

### Experimental Data

The experimental data of 3 players is stored in the data folder in the form of excel files, which are read and processed by script files. 

Each player uses different map order.

### Experimental Data Acquisition 

With the MC(Minecraft 1.12.2 720x480 resolution) open, run [DataCollector.py](https://github.com/Moss-J/Minecraft-Cinematographer-AI/blob/main/DataCollector.py). 