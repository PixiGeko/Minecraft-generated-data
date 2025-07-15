## Comparison with [1.19.3-rc2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19.3-rc2)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.19.3-rc2</th><th>1.19.3-rc3</th></tr><tr><td>World version</td><td><pre>3216</pre></td><td><pre>3217</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741937</pre></td><td><pre>1073741938</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
- com.mojang:text2speech (natives-linux) V1.13.9
- com.mojang:text2speech (natives-windows) V1.13.9
+ org.lwjgl:lwjgl (natives-windows-arm64) V3.3.1
+ org.lwjgl:lwjgl-glfw (natives-windows-arm64) V3.3.1
+ org.lwjgl:lwjgl-jemalloc (natives-windows-arm64) V3.3.1
+ org.lwjgl:lwjgl-openal (natives-windows-arm64) V3.3.1
+ org.lwjgl:lwjgl-opengl (natives-windows-arm64) V3.3.1
+ org.lwjgl:lwjgl-stb (natives-windows-arm64) V3.3.1
+ org.lwjgl:lwjgl-tinyfd (natives-windows-arm64) V3.3.1
```

</details>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.19.3-rc2</th><th>1.19.3-rc3</th></tr><tr><td>com.mojang:text2speech</td><td><pre>1.13.9</pre></td><td><pre>1.16.7</pre></td></tr></table>
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
XXX.protocol.game.ClientboundRespawnPacket +2M -2M | +4P -1P
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRespawnPacket
</summary>

```diff
- boolean shouldKeep(byte)
+ boolean shouldKeepAllPlayerData()
+ void <init>(ResourceKey,ResourceKey,long,GameType,GameType,boolean,boolean,boolean,Optional)
- void <init>(ResourceKey,ResourceKey,long,GameType,GameType,boolean,boolean,byte,Optional)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
</details>
<hr/>