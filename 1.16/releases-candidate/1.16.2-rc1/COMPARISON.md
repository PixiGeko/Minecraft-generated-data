## Comparison with [1.16.2-pre3](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16.2-pre3)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.16.2-pre3</th><th>1.16.2-rc1</th></tr><tr><td>World version</td><td><pre>2575</pre></td><td><pre>2576</pre></td></tr><tr><td>Protocol version</td><td><pre>748</pre></td><td><pre>749</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.16.2-pre3</th><th>1.16.2-rc1</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
XXX.levelgen.carver.ConfiguredWorldCarver +1P
```
```
XXX.levelgen.feature.ConfiguredStructureFeature +1P
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.client.Minecraft +2M -1M
```
```
XXX.gui.screens.PresetFlatWorldScreen +5M -3M
```
```
XXX.levelgen.carver.ConfiguredWorldCarver +1P
```
```
XXX.levelgen.feature.ConfiguredStructureFeature +1P
```

</details>
<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
- void clearResourcePacksOnError(Throwable,Component)
- void lambda$clearResourcePacksOnError$3(Component)
+ void lambda$rollbackResourcePacks$3(Component)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.PresetFlatWorldScreen
</summary>

```diff
- Biome lambda$fromString$1(Registry,ResourceKey)
- Biome lambda$null$4(Registry,ResourceKey)
+ FlatLevelGeneratorSettings lambda$preset$3(List,boolean,boolean,boolean,FlatLayerInfo[],ResourceKey,Registry)
- FlatLevelGeneratorSettings lambda$preset$5(List,boolean,boolean,boolean,FlatLayerInfo[],ResourceKey,Registry)
+ void lambda$init$1(Registry,Button)
+ void lambda$init$2(Button)
- void lambda$init$2(Registry,Button)
- void lambda$init$3(Button)
```

</details>
</details>
<hr/>