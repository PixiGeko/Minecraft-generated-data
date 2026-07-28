## Comparison with [26.3-snapshot-4](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.3-snapshot-4)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.3-snapshot-4</th><th>26.3-snapshot-5</th></tr><tr><td>DataPack version</td><td><pre>111.0</pre></td><td><pre>112.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>92.0</pre></td><td><pre>93.0</pre></td></tr><tr><td>World version</td><td><pre>5003</pre></td><td><pre>5004</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742150</pre></td><td><pre>1073742151</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
- org.lwjgl:lwjgl (unsafe) V3.4.1
+ org.lwjgl:lwjgl V3.4.2
```

</details>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.3-snapshot-4</th><th>26.3-snapshot-5</th></tr><tr><td>com.mojang:brigadier</td><td><pre>1.3.10</pre></td><td><pre>1.3.11</pre></td></tr><tr><td>org.joml:joml</td><td><pre>1.10.8</pre></td><td><pre>1.10.9</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-linux)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-macos)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-macos-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-windows)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-windows-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-windows-x86)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-linux)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-macos)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-macos-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-windows)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-windows-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-windows-x86)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-linux)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-macos)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-macos-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-windows)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-windows-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-windows-x86)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-linux)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-macos)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-macos-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-windows)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-windows-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-windows-x86)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-sdl</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-sdl (natives-linux)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-sdl (natives-macos)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-sdl (natives-macos-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-sdl (natives-windows)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-sdl (natives-windows-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-sdl (natives-windows-x86)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-shaderc</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-shaderc (natives-linux)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-shaderc (natives-macos)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-shaderc (natives-macos-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-shaderc (natives-windows)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-shaderc (natives-windows-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-shaderc (natives-windows-x86)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-spvc</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-spvc (natives-linux)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-spvc (natives-macos)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-spvc (natives-macos-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-spvc (natives-windows)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-spvc (natives-windows-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-spvc (natives-windows-x86)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-linux)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-macos)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-macos-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-windows)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-windows-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-windows-x86)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-linux)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-macos)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-macos-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-windows)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-windows-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-windows-x86)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-vma</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-vma (natives-linux)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-vma (natives-macos)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-vma (natives-macos-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-vma (natives-windows)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-vma (natives-windows-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-vma (natives-windows-x86)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-vulkan</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-vulkan (natives-macos)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-vulkan (natives-macos-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-linux)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-macos)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-macos-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-windows)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-windows-arm64)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-windows-x86)</td><td><pre>3.4.1</pre></td><td><pre>3.4.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
+ item.minecraft.firework_rocket.flight_duration: Flight Duration: %s
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.3-snapshot-4</th><th>26.3-snapshot-5</th></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.firework_rocket.flight</div></th><td>Flight Duration: %s</td><td>Flight Duration:</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
data
</summary>

```diff
+ minecraft/worldgen/density_function/overworld_amplified/final_density.json
+ minecraft/worldgen/density_function/overworld_large_biomes/final_density.json
+ minecraft/worldgen/density_function/overworld/final_density.json
```

</details>
</details>
<hr/>