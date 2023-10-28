<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w31a ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w31a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-08-01T12:54:44+00:00</td></tr>
<tr><th>SHA1</th><td>5f20fbe733b3db3758045626e9ffff050029daf6</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/5f20fbe733b3db3758045626e9ffff050029daf6/18w31a.json">https://piston-meta.mojang.com/v1/packages/5f20fbe733b3db3758045626e9ffff050029daf6/18w31a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/a8ef90d58d4a170f85e3439470c99c25aa8e988b/1.13.1.json">https://piston-meta.mojang.com/v1/packages/a8ef90d58d4a170f85e3439470c99c25aa8e988b/1.13.1.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/4646084899fb62a7b9afa6f453fae4e6e786e5a5/server.jar">https://piston-data.mojang.com/v1/objects/4646084899fb62a7b9afa6f453fae4e6e786e5a5/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/0a343ef39365d70908a3c59fbbf2d9c0ddd2ad75/client.jar">https://piston-data.mojang.com/v1/objects/0a343ef39365d70908a3c59fbbf2d9c0ddd2ad75/client.jar</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w30b">18w30b</a>

# Folder structure

<details><summary>data/</summary>

```diff
+ minecraft/tags/blocks/coral_plants.json
+ minecraft/tags/blocks/underwater_bonemeals.json
```

</details>


# Commands

<details><summary>List</summary>

```diff
+ chunk.txt
```

</details>


<details><summary>execute.txt</summary>

```diff
+ execute in <dimension>
- execute in overworld
- execute in the_end
- execute in the_nether
```

</details>


<details><summary>worldborder.txt</summary>

```diff
+ worldborder add <distance: float> <time: integer>
- worldborder add <distance: integer> <time: integer>
+ worldborder set <distance: float> <time: integer>
- worldborder set <distance: integer> <time: integer>
```

</details>


# Tags

<details><summary>List</summary>

```diff
+ blocks/coral_plants.json
+ blocks/underwater_bonemeals.json
```

</details>


<details><summary>blocks/corals.json</summary>

```diff
+ #minecraft:coral_plants
- minecraft:brain_coral
- minecraft:bubble_coral
- minecraft:fire_coral
- minecraft:horn_coral
- minecraft:tube_coral
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ argument.dimension.invalid
+ commands.chunk.forced
+ commands.chunk.not.forced
+ commands.chunk.not.unforced
+ commands.chunk.unforced
+ death.attack.even_more_magic
+ death.attack.message_too_long
+ menu.loadingForcedChunks
```

</details>


# Misc

<details><summary>tags.txt</summary>

```diff
+ blocks/coral_plants.json
+ blocks/underwater_bonemeals.json
```

</details>


# Version data

<details><summary>libraries.txt</summary>

```diff
- it.unimi.dsi:fastutil:7.1.0
+ it.unimi.dsi:fastutil:8.2.1
```

</details>
