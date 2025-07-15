## Comparison with [1.20.5-rc1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.20.5-rc1)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.20.5-rc1</th><th>1.20.5-rc2</th></tr><tr><td>World version</td><td><pre>3834</pre></td><td><pre>3835</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742013</pre></td><td><pre>1073742014</pre></td></tr></table>
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
XXX.minecraft.util.EncoderCache$2 +1M
```

</details>
<details>
<summary>
net.minecraft.util.EncoderCache$2
</summary>

```diff
- Object lambda$encode$0(Object)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds +2M
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
</summary>

```diff
- boolean lambda$getEnchantment$1(FeatureFlagSet,Enchantment)
- Enchantment getEnchantment(RandomSource,FeatureFlagSet)
```

</details>
</details>
<hr/>