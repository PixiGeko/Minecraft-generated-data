## Comparison with [1.15](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.15)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.15</th><th>1.15.1-pre1</th></tr><tr><td>World version</td><td><pre>2225</pre></td><td><pre>2226</pre></td></tr><tr><td>Protocol version</td><td><pre>573</pre></td><td><pre>574</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.15</th><th>1.15.1-pre1</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
XXX.level.block.Block$2 +1M -1M
```
```
XXX.block.state.AbstractStateHolder -2M | -1P
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Block$2
</summary>

```diff
- void <init>(int,float)
+ void <init>(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.AbstractStateHolder
</summary>

```diff
+ boolean equals(Object)
+ int hashCode()
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.realmsclient.RealmsMainScreen +5M -5M
```
```
XXX.mojang.realmsclient.RealmsMainScreen$12 +1M
```
```
XXX.level.chunk.ChunkBiomeContainer +1P
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen
</summary>

```diff
+ int access$1900(RealmsMainScreen)
+ int access$1902(RealmsMainScreen,int)
- int access$2000(RealmsMainScreen)
- int access$2002(RealmsMainScreen,int)
+ RealmsButton access$1700(RealmsMainScreen)
- RealmsButton access$1900(RealmsMainScreen)
- RealmsMainScreen$RealmSelectionList access$1700(RealmsMainScreen)
+ RealmsMainScreen$RealmSelectionList access$1800(RealmsMainScreen)
- void access$1800(RealmsMainScreen,RealmsServer)
+ void access$2000(RealmsMainScreen,RealmsServer)
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$12
</summary>

```diff
- boolean lambda$run$0(RealmListEntry)
```

</details>
</details>
<hr/>