## Comparison with [18w33a](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w33a)

> [!TIP]
> - [Commands](#commands)
> - [Translations](#translations)
> - [Misc](#misc)

<br/><br/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- chunk.txt
+ forceload.txt
```

</details>
<details>
<summary>
execute
</summary>

```diff
+ execute in <dimension: dimension>
- execute in <dimension>
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
- argument.pos.incomplete: Incomplete (expected 3 coordinates)
+ argument.pos2d.incomplete: Incomplete (expected 2 coordinates)
+ argument.pos3d.incomplete: Incomplete (expected 3 coordinates)
- argument.vec2.incomplete: Incomplete (expected 2 coordinates)
- commands.chunk.forced: Marked chunk (%s, %s) as force loaded
- commands.chunk.not.forced: Could not mark chunk (%s, %s) as force loaded, already so
- commands.chunk.not.unforced: Could not mark chunk (%s, %s) as not force loaded, already so
- commands.chunk.unforced: Marked chunk (%s, %s) as not force loaded
+ commands.forceload.added.failure: No chunks were marked for force loading
+ commands.forceload.added.multiple: Marked %s chunks in %s from %s to %s to be force loaded
+ commands.forceload.added.none: No force loaded chunks were found in %s
+ commands.forceload.added.single: Marked chunk %s in %s to be force loaded
+ commands.forceload.list.multiple: %s force loaded chunks were found in %s at: %s
+ commands.forceload.list.single: A force loaded chunk was found in %s at: %s
+ commands.forceload.query.failure: Chunk at %s in %s is not marked for force loading
+ commands.forceload.query.success: Chunk at %s in %s is marked for force loading
+ commands.forceload.removed.all: Unmarked all force loaded chunks in %s
+ commands.forceload.removed.failure: No chunks were removed from force loading
+ commands.forceload.removed.multiple: Unmarked %s chunks in %s from %s to %s for force loading
+ commands.forceload.removed.single: Unmarked chunk %s in %s for force loading
+ commands.forceload.toobig: Too many chunks in the specified area (maximum %s, specified %s)
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
+ minecraft:column_pos
+ minecraft:dimension
```

</details>
</details>
<hr/>