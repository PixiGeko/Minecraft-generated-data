## Comparison with [1.19-pre5](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19-pre5)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.19-pre5</th><th>1.19-rc1</th></tr><tr><td>World version</td><td><pre>3102</pre></td><td><pre>3103</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741913</pre></td><td><pre>1073741914</pre></td></tr></table>
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
XXX.world.effect.MobEffectInstance$FactorData +1M -1M
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffectInstance$FactorData
</summary>

```diff
+ float getFactor(float)
- float getFactor(LivingEntity,float)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.world.effect.MobEffectInstance$FactorData +1M -1M
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffectInstance$FactorData
</summary>

```diff
+ float getFactor(float)
- float getFactor(LivingEntity,float)
```

</details>
</details>
<hr/>