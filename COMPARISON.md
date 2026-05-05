## Comparison with [26.2-snapshot-5](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.2-snapshot-5)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.2-snapshot-5</th><th>26.2-snapshot-6</th></tr><tr><td>DataPack version</td><td><pre>104.0</pre></td><td><pre>105.0</pre></td></tr><tr><td>World version</td><td><pre>4889</pre></td><td><pre>4890</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742135</pre></td><td><pre>1073742136</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.2-snapshot-5</th><th>26.2-snapshot-6</th></tr><tr><td>com.mojang:datafixerupper</td><td><pre>9.0.19</pre></td><td><pre>10.0.21</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
worldgen/feature
</summary>

```diff
+ minecraft:weighted_random_selector
```

</details>
<details>
<summary>
worldgen/material_rule
</summary>

```diff
- minecraft:noise_gradient
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
+ minecraft:weighted_random_selector
```

</details>
<details>
<summary>
universal_tags/worldgen/material_rule.json
</summary>

```diff
- minecraft:noise_gradient
```

</details>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
+ advancements.husbandry.uh_oh.description: Have a Sulfur Cube absorb a TNT block
+ advancements.husbandry.uh_oh.title: Uh Oh
```

</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/husbandry/uh_oh.json
+ minecraft/sulfur_cube_archetype/hot.json
+ minecraft/sulfur_cube_archetype/slow_bouncy.json
+ minecraft/tags/item/sulfur_cube_archetype/hot.json
+ minecraft/tags/item/sulfur_cube_archetype/slow_bouncy.json
```

</details>
</details>
<hr/>