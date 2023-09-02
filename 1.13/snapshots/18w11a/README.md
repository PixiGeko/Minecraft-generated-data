<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w11a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w11a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-03-13T15:10:59+00:00</td></tr>
<tr><th>SHA1</th><td>d07fefcabe464b19876597340187732ffd59be5f</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/d07fefcabe464b19876597340187732ffd59be5f/18w11a.json">https://piston-meta.mojang.com/v1/packages/d07fefcabe464b19876597340187732ffd59be5f/18w11a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/4286b7cbc4709c8f61c93a77b42c70918376cac3/server.jar">https://piston-data.mojang.com/v1/objects/4286b7cbc4709c8f61c93a77b42c70918376cac3/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/e4abfe0c5e7f490a1071e7c99cb1cef81ffd89dc/client.jar">https://piston-data.mojang.com/v1/objects/e4abfe0c5e7f490a1071e7c99cb1cef81ffd89dc/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w10d">18w10d</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/loot_tables/chests/shipwreck_map.json
+  minecraft/loot_tables/chests/shipwreck_supply.json
+  minecraft/loot_tables/chests/shipwreck_treasure.json
+  minecraft/loot_tables/entities/drowned.json
+  minecraft/structures/shipwreck
+  minecraft/structures/shipwreck/rightsideup_backhalf.nbt
+  minecraft/structures/shipwreck/rightsideup_backhalf_degraded.nbt
+  minecraft/structures/shipwreck/rightsideup_fronthalf.nbt
+  minecraft/structures/shipwreck/rightsideup_fronthalf_degraded.nbt
+  minecraft/structures/shipwreck/rightsideup_full.nbt
+  minecraft/structures/shipwreck/rightsideup_full_degraded.nbt
+  minecraft/structures/shipwreck/sideways_backhalf.nbt
+  minecraft/structures/shipwreck/sideways_backhalf_degraded.nbt
+  minecraft/structures/shipwreck/sideways_fronthalf.nbt
+  minecraft/structures/shipwreck/sideways_fronthalf_degraded.nbt
+  minecraft/structures/shipwreck/sideways_full.nbt
+  minecraft/structures/shipwreck/sideways_full_degraded.nbt
+  minecraft/structures/shipwreck/upsidedown_backhalf.nbt
+  minecraft/structures/shipwreck/upsidedown_backhalf_degraded.nbt
+  minecraft/structures/shipwreck/upsidedown_fronthalf.nbt
+  minecraft/structures/shipwreck/upsidedown_fronthalf_degraded.nbt
+  minecraft/structures/shipwreck/upsidedown_full.nbt
+  minecraft/structures/shipwreck/upsidedown_full_degraded.nbt
+  minecraft/structures/shipwreck/with_mast.nbt
+  minecraft/structures/shipwreck/with_mast_degraded.nbt
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/blockstates/blue_coral_fan.json
+  minecraft/blockstates/pink_coral_fan.json
+  minecraft/blockstates/purple_coral_fan.json
+  minecraft/blockstates/red_coral_fan.json
+  minecraft/blockstates/yellow_coral_fan.json
+  minecraft/models/block/blue_coral_fan.json
+  minecraft/models/block/coral_fan.json
+  minecraft/models/block/pink_coral_fan.json
+  minecraft/models/block/purple_coral_fan.json
+  minecraft/models/block/red_coral_fan.json
+  minecraft/models/block/yellow_coral_fan.json
+  minecraft/models/item/blue_coral_fan.json
+  minecraft/models/item/drowned_spawn_egg.json
+  minecraft/models/item/pink_coral_fan.json
+  minecraft/models/item/purple_coral_fan.json
+  minecraft/models/item/red_coral_fan.json
+  minecraft/models/item/yellow_coral_fan.json
+  minecraft/textures/blocks/blue_coral_fan.png
+  minecraft/textures/blocks/pink_coral_fan.png
+  minecraft/textures/blocks/purple_coral_fan.png
+  minecraft/textures/blocks/red_coral_fan.png
+  minecraft/textures/blocks/yellow_coral_fan.png
+  minecraft/textures/entity/zombie/drowned.png
+  minecraft/textures/entity/zombie/drowned_outer_layer.png
```

</details>

## Commands

<details><summary>locate.txt</summary>

```diff
+ locate Shipwreck
```

</details>

## Misc

<details><summary>loot_tables.txt</summary>

```diff
+ chests/shipwreck_map.json
+ chests/shipwreck_supply.json
+ chests/shipwreck_treasure.json
+ entities/drowned.json
```

</details>

<details><summary>structures.txt</summary>

```diff
+ shipwreck/rightsideup_backhalf.nbt
+ shipwreck/rightsideup_backhalf_degraded.nbt
+ shipwreck/rightsideup_fronthalf.nbt
+ shipwreck/rightsideup_fronthalf_degraded.nbt
+ shipwreck/rightsideup_full.nbt
+ shipwreck/rightsideup_full_degraded.nbt
+ shipwreck/sideways_backhalf.nbt
+ shipwreck/sideways_backhalf_degraded.nbt
+ shipwreck/sideways_fronthalf.nbt
+ shipwreck/sideways_fronthalf_degraded.nbt
+ shipwreck/sideways_full.nbt
+ shipwreck/sideways_full_degraded.nbt
+ shipwreck/upsidedown_backhalf.nbt
+ shipwreck/upsidedown_backhalf_degraded.nbt
+ shipwreck/upsidedown_fronthalf.nbt
+ shipwreck/upsidedown_fronthalf_degraded.nbt
+ shipwreck/upsidedown_full.nbt
+ shipwreck/upsidedown_full_degraded.nbt
+ shipwreck/with_mast.nbt
+ shipwreck/with_mast_degraded.nbt
```

</details>

<details><summary>textures.txt</summary>

```diff
+ blocks/blue_coral_fan.png
+ blocks/pink_coral_fan.png
+ blocks/purple_coral_fan.png
+ blocks/red_coral_fan.png
+ blocks/yellow_coral_fan.png
+ entity/zombie/drowned.png
+ entity/zombie/drowned_outer_layer.png
```

</details>

<br/>
<html><table>
<tr><td colspan="2" align="center"><img width="5000" height="0"><br/>
<a href="https://github.com/PixiGeko/Minecraft-generated-data">Minecraft-generated-data</a>
<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="5000" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
</table></html>
<br/>