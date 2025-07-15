## Comparison with [24w03a](https://github.com/PixiGeko/Minecraft-generated-data/tree/24w03a)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">24w03a</th><th>24w03b</th></tr><tr><td>World version</td><td><pre>3804</pre></td><td><pre>3805</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741995</pre></td><td><pre>1073741996</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
particle_type
</summary>

```diff
- minecraft:gust_dust
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
- minecraft:gust_dust
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
- minecraft/particles/gust_dust.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.entity.item.ItemEntity +2P
```
```
XXX.level.block.CrafterBlock +1M -2M
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CrafterBlock
</summary>

```diff
- void lambda$dispenseFrom$0(ItemStack)
+ void lambda$dispenseFrom$0(ServerLevel,BlockPos,CrafterBlockEntity,BlockState,ItemStack)
+ void lambda$dispenseFrom$1(ItemStack)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ XXX.client.particle.GustDustParticle
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.core.particles.ParticleTypes -1P
```
```
XXX.gametest.framework.GameTestHelper -1M
```
```
XXX.entity.item.ItemEntity +2P
```
```
XXX.level.block.CrafterBlock +1M -2M
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
+ void assertValueEqual(Number,Number,String)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CrafterBlock
</summary>

```diff
- void lambda$dispenseFrom$0(ItemStack)
+ void lambda$dispenseFrom$0(ServerLevel,BlockPos,CrafterBlockEntity,BlockState,ItemStack)
+ void lambda$dispenseFrom$1(ItemStack)
```

</details>
</details>
<hr/>