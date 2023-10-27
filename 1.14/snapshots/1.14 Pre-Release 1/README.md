<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.14 Pre-Release 1 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.14 Pre-Release 1</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2019-04-10T14:24:16+00:00</td></tr>
<tr><th>SHA1</th><td>76dd36e6b4fb2db5e474dd3b44cd96f3f498433d</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/76dd36e6b4fb2db5e474dd3b44cd96f3f498433d/1.14%20Pre-Release%201.json">https://piston-meta.mojang.com/v1/packages/76dd36e6b4fb2db5e474dd3b44cd96f3f498433d/1.14%20Pre-Release%201.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/6f27430bcd9b06d3dcb5d2966c75d5e491915c9c/server.jar">https://piston-data.mojang.com/v1/objects/6f27430bcd9b06d3dcb5d2966c75d5e491915c9c/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/eb144c0dbc03116c832cdd20d28a8a686327905a/client.jar">https://piston-data.mojang.com/v1/objects/eb144c0dbc03116c832cdd20d28a8a686327905a/client.jar</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/19w14b">19w14b</a>

# Folder structure

<details><summary>data/</summary>

```diff
+ minecraft/structures/village/desert/villagers/baby.nbt
+ minecraft/structures/village/plains/villagers/baby.nbt
+ minecraft/structures/village/savanna/villagers/baby.nbt
- minecraft/structures/village/snowy/houses/snowy_butchers_shop.nbt
+ minecraft/structures/village/snowy/villagers/baby.nbt
- minecraft/structures/village/taiga/houses/taiga_decoration_1.nbt
- minecraft/structures/village/taiga/houses/taiga_lamp_post_1.nbt
- minecraft/structures/village/taiga/houses/taiga_meeting_point_1.nbt
- minecraft/structures/village/taiga/houses/taiga_sheperds_house_1.nbt
- minecraft/structures/village/taiga/houses/taiga_weapon_smith_1.nbt
+ minecraft/structures/village/taiga/villagers/baby.nbt
- minecraft/tags/blocks/armorer_poi.json
- minecraft/tags/blocks/butcher_poi.json
- minecraft/tags/blocks/cartographer_poi.json
- minecraft/tags/blocks/cleric_poi.json
- minecraft/tags/blocks/farmer_poi.json
- minecraft/tags/blocks/fisherman_poi.json
- minecraft/tags/blocks/fletcher_poi.json
- minecraft/tags/blocks/job_site_poi.json
- minecraft/tags/blocks/leatherworker_poi.json
- minecraft/tags/blocks/librarian_poi.json
- minecraft/tags/blocks/mason_poi.json
- minecraft/tags/blocks/meeting_site_poi.json
- minecraft/tags/blocks/points_of_interest.json
- minecraft/tags/blocks/shepherd_poi.json
- minecraft/tags/blocks/toolsmith_poi.json
- minecraft/tags/blocks/weaponsmith_poi.json
```

</details>


<details><summary>assets/</summary>

```diff
+ minecraft/textures/gui/checkbox.png
```

</details>


# Tags

<details><summary>List</summary>

```diff
- blocks/armorer_poi.json
- blocks/butcher_poi.json
- blocks/cartographer_poi.json
- blocks/cleric_poi.json
- blocks/farmer_poi.json
- blocks/fisherman_poi.json
- blocks/fletcher_poi.json
- blocks/job_site_poi.json
- blocks/leatherworker_poi.json
- blocks/librarian_poi.json
- blocks/mason_poi.json
- blocks/meeting_site_poi.json
- blocks/points_of_interest.json
- blocks/shepherd_poi.json
- blocks/toolsmith_poi.json
- blocks/weaponsmith_poi.json
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ selectWorld.backupEraseCache
```

</details>


# Misc

<details><summary>structures.txt</summary>

```diff
+ village/desert/villagers/baby.nbt
+ village/plains/villagers/baby.nbt
+ village/savanna/villagers/baby.nbt
- village/snowy/houses/snowy_butchers_shop.nbt
+ village/snowy/villagers/baby.nbt
- village/taiga/houses/taiga_decoration_1.nbt
- village/taiga/houses/taiga_lamp_post_1.nbt
- village/taiga/houses/taiga_meeting_point_1.nbt
- village/taiga/houses/taiga_sheperds_house_1.nbt
- village/taiga/houses/taiga_weapon_smith_1.nbt
+ village/taiga/villagers/baby.nbt
```

</details>


<details><summary>tags.txt</summary>

```diff
- blocks/armorer_poi.json
- blocks/butcher_poi.json
- blocks/cartographer_poi.json
- blocks/cleric_poi.json
- blocks/farmer_poi.json
- blocks/fisherman_poi.json
- blocks/fletcher_poi.json
- blocks/job_site_poi.json
- blocks/leatherworker_poi.json
- blocks/librarian_poi.json
- blocks/mason_poi.json
- blocks/meeting_site_poi.json
- blocks/points_of_interest.json
- blocks/shepherd_poi.json
- blocks/toolsmith_poi.json
- blocks/weaponsmith_poi.json
```

</details>


<details><summary>textures.txt</summary>

```diff
+ gui/checkbox.png
```

</details>


# Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:datafixerupper:2.0.23
+ com.mojang:datafixerupper:2.0.24
- com.mojang:realms:1.14.4
+ com.mojang:realms:1.14.6
- com.mojang:text2speech:1.11.2
- com.mojang:text2speech:1.11.2
+ com.mojang:text2speech:1.11.3
+ com.mojang:text2speech:1.11.3
```

</details>
