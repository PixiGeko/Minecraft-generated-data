## Comparison with [26.1-snapshot-9](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.1-snapshot-9)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.1-snapshot-9</th><th>26.1-snapshot-10</th></tr><tr><td>DataPack version</td><td><pre>99.2</pre></td><td><pre>99.3</pre></td></tr><tr><td>ResourcePack version</td><td><pre>81.1</pre></td><td><pre>82.0</pre></td></tr><tr><td>World version</td><td><pre>4777</pre></td><td><pre>4778</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742119</pre></td><td><pre>1073742120</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:pause_mob_growth
+ minecraft:reset_mob_growth
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:pause_mob_growth
+ minecraft:reset_mob_growth
```

</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
generated
</summary>

```diff
+ reports/minecraft/components/particle_type/pause_mob_growth.json
+ reports/minecraft/components/particle_type/reset_mob_growth.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/particles/pause_mob_growth.json
+ minecraft/particles/reset_mob_growth.json
+ minecraft/shaders/include/sample_lightmap.glsl
- minecraft/shaders/include/smooth_lighting.glsl
+ minecraft/textures/block/cactus_side.png.mcmeta
+ minecraft/textures/block/cactus_top.png.mcmeta
```

</details>
</details>
<hr/>