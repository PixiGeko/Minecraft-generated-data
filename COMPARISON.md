## Comparison with [26.2-snapshot-3](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.2-snapshot-3)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.2-snapshot-3</th><th>26.2-snapshot-4</th></tr><tr><td>DataPack version</td><td><pre>102.0</pre></td><td><pre>103.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>86.0</pre></td><td><pre>86.1</pre></td></tr><tr><td>World version</td><td><pre>4886</pre></td><td><pre>4887</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742133</pre></td><td><pre>1073742134</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
attribute
</summary>

```diff
+ minecraft:below_name_distance
+ minecraft:nameplate_distance
```

</details>
<details>
<summary>
entity_sub_predicate_type
</summary>

```diff
+ minecraft:type_specific/cube_mob
- minecraft:type_specific/slime
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:item.bucket.empty_sulfur_cube
+ minecraft:item.bucket.fill_sulfur_cube
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/attribute.json
</summary>

```diff
+ minecraft:below_name_distance
+ minecraft:nameplate_distance
```

</details>
<details>
<summary>
universal_tags/entity_sub_predicate_type.json
</summary>

```diff
+ minecraft:type_specific/cube_mob
- minecraft:type_specific/slime
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:item.bucket.empty_sulfur_cube
+ minecraft:item.bucket.fill_sulfur_cube
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
+ attribute.name.below_name_distance: Nameplate Score Distance
+ attribute.name.nameplate_distance: Nameplate Distance
+ subtitles.item.bucket.fill_sulfur_cube: Sulfur Cube scooped
+ telemetry.event.graphics_capabilities.description: This event informs us of the capabilities of the graphics device used to play the game.
+ telemetry.event.graphics_capabilities.title: Graphics Capabilities
+ telemetry.property.backend_failure_message.title: Backend Creation Failure Message
+ telemetry.property.backend_failure_missing_capabilities.title: Backend Creation Failure Missing Capabilities
+ telemetry.property.backend_failure_reason.title: Backend Creation Failure Reason
+ telemetry.property.backend_name.title: Backend Name
```

</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
assets
</summary>

```diff
- minecraft/atlases/beds.json
```

</details>
</details>
<hr/>