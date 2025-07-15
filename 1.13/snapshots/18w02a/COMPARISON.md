## Comparison with [18w01a](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w01a)

> [!TIP]
> - [Commands](#commands)
> - [File structure](#file-structure)
> - [Misc](#misc)

<br/><br/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
execute
</summary>

```diff
+ execute anchored <anchor: entity_anchor>
+ execute facing <pos: vec3>
+ execute facing entity <targets: entity> <anchor: entity_anchor>
+ execute if score <target: score_holder> <targetObjective: objective> matches <range: range>
+ execute in overworld
+ execute in the_end
+ execute in the_nether
- execute offset <pos: vec3>
+ execute positioned <pos: vec3>
+ execute positioned as <entities: entity>
+ execute rotated <rot: rotation>
+ execute rotated as <entities: entity>
+ execute unless score <target: score_holder> <targetObjective: objective> matches <range: range>
```

</details>
<details>
<summary>
teleport
</summary>

```diff
+ teleport <destination: entity>
- teleport <destination: entity> facing <facingEntity: entity>
- teleport <destination: entity> facing <facingLocation: vec3>
+ teleport <location: vec3>
- teleport <location: vec3> <rotation: rotation>
- teleport <location: vec3> facing <facingEntity: entity>
- teleport <location: vec3> facing <facingLocation: vec3>
+ teleport <targets: entity> <destination: entity>
- teleport <targets: entity> <destination: entity> facing <facingEntity: entity>
- teleport <targets: entity> <destination: entity> facing <facingLocation: vec3>
- teleport <targets: entity> <location: vec3> facing <facingEntity: entity>
+ teleport <targets: entity> <location: vec3> facing entity <facingEntity: entity> <facingAnchor: entity_anchor>
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
+ minecraft/tags/blocks/enderman_holdable.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/lang/en_us.json
- minecraft/lang/en_us.lang
```

</details>
</details>
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
parsers
</summary>

```diff
+ minecraft:entity_anchor
+ minecraft:range
```

</details>
</details>
<hr/>