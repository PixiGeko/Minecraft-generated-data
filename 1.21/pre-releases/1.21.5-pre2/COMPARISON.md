## Comparison with [1.21.5-pre1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.5-pre1)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21.5-pre1</th><th>1.21.5-pre2</th></tr><tr><td>DataPack version</td><td><pre>70</pre></td><td><pre>71</pre></td></tr><tr><td>World version</td><td><pre>4320</pre></td><td><pre>4321</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742063</pre></td><td><pre>1073742064</pre></td></tr></table>
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
XXX.blaze3d.systems.RenderSystem +1M -1M
```
```
XXX.client.renderer.SkyRenderer +1P
```

</details>
<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem
</summary>

```diff
+ String lambda$getQuadVertexBuffer$2()
- String lambda$initRenderer$2()
```

</details>
</details>
<hr/>