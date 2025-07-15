## Comparison with [1.20.3-pre4](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.20.3-pre4)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.20.3-pre4</th><th>1.20.3-rc1</th></tr><tr><td>World version</td><td><pre>3696</pre></td><td><pre>3697</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741991</pre></td><td><pre>1073741992</pre></td></tr></table>
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
XXX.protocol.game.ClientboundExplodePacket +1M
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundExplodePacket
</summary>

```diff
- void writeParticle(FriendlyByteBuf,ParticleOptions)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.protocol.game.ClientboundExplodePacket +1M
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundExplodePacket
</summary>

```diff
- void writeParticle(FriendlyByteBuf,ParticleOptions)
```

</details>
</details>
<hr/>