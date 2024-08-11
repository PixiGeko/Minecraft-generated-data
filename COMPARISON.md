## Comparison with [19w35a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w35a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Commands](#commands)
- [File structure](#file-structure)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">19w35a</th><th>19w36a</th></tr><tr><td>World version</td><td><code>2201</code></td><td><code>2203</code></td></tr><tr><td>Protocol version</td><td><code>551</code></td><td><code>552</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
point_of_interest_type.txt
</summary>

```diff
+ minecraft:nether_portal
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
universal_tags/point_of_interest_type.json
</summary>

```diff
+ minecraft:nether_portal
```

</details>
</details>
<details><summary>Commands</summary>
<details>
<summary>
gamerule
</summary>

```diff
+ gamerule doImmediateRespawn <value: bool>
+ gamerule doInsomnia <value: bool>
+ gamerule drowningDamage <value: bool>
+ gamerule fallDamage <value: bool>
+ gamerule fireDamage <value: bool>
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/tags/entity_types/beehive_inhabitors.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/textures/block/bee_hive_bottom.png
+ minecraft/textures/block/bee_hive_end.png
- minecraft/textures/block/bee_hive_top.png
```

</details>
</details>