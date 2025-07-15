## Comparison with [1.17.1-pre1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.17.1-pre1)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.17.1-pre1</th><th>1.17.1-pre2</th></tr><tr><td>World version</td><td><pre>2725</pre></td><td><pre>2726</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741860</pre></td><td><pre>1073741861</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.17.1-pre1</th><th>1.17.1-pre2</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
XXX.minecraft.network.FriendlyByteBuf +3M -1M
```
```
XXX.protocol.game.ServerboundEditBookPacket +1P
```

</details>
<details>
<summary>
net.minecraft.network.FriendlyByteBuf
</summary>

```diff
- IntFunction limitValue(IntFunction,int)
- Object lambda$limitValue$2(int,IntFunction,int)
+ void lambda$writeMap$2(BiConsumer,BiConsumer,Object,Object)
- void lambda$writeMap$3(BiConsumer,BiConsumer,Object,Object)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.client.gui.MapRenderer +1M -1M
```
```
XXX.protocol.game.ServerboundContainerClickPacket +1P
```

</details>
<details>
<summary>
net.minecraft.client.gui.MapRenderer
</summary>

```diff
+ MapRenderer$MapInstance lambda$getOrCreateMapInstance$0(MapItemSavedData,int)
- MapRenderer$MapInstance lambda$getOrCreateMapInstance$0(MapItemSavedData,Integer,MapRenderer$MapInstance)
```

</details>
</details>
<hr/>