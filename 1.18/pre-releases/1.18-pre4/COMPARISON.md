## Comparison with [1.18-pre3](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18-pre3)

- [Version data](#version-data)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">1.18-pre3</th><th>1.18-pre4</th></tr><tr><td>World version</td><td><code>2849</code></td><td><code>2850</code></td></tr><tr><td>Protocol version</td><td><code>1073741875</code></td><td><code>1073741876</code></td></tr></table>
</details>
<details><summary>Mappings</summary>
<h2>Server</h2>

<details>
<summary>
Changes
</summary>

```
XXX.level.chunk.PalettedContainer +1M -1M
```

</details>
































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer
</summary>

```diff
+ void lambda$getAll$4(Consumer,GlobalPalette,int)
- void lambda$getAll$4(Consumer,Palette,int)
```

</details>



















































































































































































































































































































































































































































































































































<h2>Client</h2>

<details>
<summary>
Changes
</summary>

```
XXX.level.biome.BiomeSource +1M -1M | +1P -1P
```

</details>
































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.biome.BiomeSource
</summary>

```diff
+ List possibleBiomes()
- Set possibleBiomes()
```

</details>
</details>