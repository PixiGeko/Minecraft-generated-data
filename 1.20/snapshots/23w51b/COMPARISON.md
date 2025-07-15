## Comparison with [23w51a](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w51a)

> [!TIP]
> - [Version data](#version-data)
> - [Translations](#translations)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">23w51a</th><th>23w51b</th></tr><tr><td>World version</td><td><pre>3801</pre></td><td><pre>3802</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741993</pre></td><td><pre>1073741994</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
+ item.minecraft.scute: Scute
```

</details>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.world.entity.EntityAttachments +1M -1M | -1P
```

</details>
<details>
<summary>
net.minecraft.world.entity.EntityAttachments
</summary>

```diff
- EntityAttachments createDefault(float,float)
+ void <clinit>()
```

</details>
</details>
<hr/>