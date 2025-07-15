## Comparison with [1.17-pre3](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.17-pre3)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Translations](#translations)
> - [Credits](#credits)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.17-pre3</th><th>1.17-pre4</th></tr><tr><td>World version</td><td><pre>2719</pre></td><td><pre>2720</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741855</pre></td><td><pre>1073741856</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.17-pre3</th><th>1.17-pre4</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.17-pre3</th><th>1.17-pre4</th></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.candle_cake</div></th><td>Candle Cake</td><td>Cake with Candle</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>CREDITS</ins></b><a name="credits"></a></summary>
<br/>
<details>
<summary>
🗒️ Sections
</summary>

```diff
- Development Partner: Lionbridge
Quality - Poland Team
+ Development Partner: Lionbridge Quality - Poland Team
```

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
XXX.animal.goat.Goat -1M
```
```
XXX.world.level.WorldGenLevel +1M
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.goat.Goat
</summary>

```diff
+ boolean canAttack(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.WorldGenLevel
</summary>

```diff
- boolean ensureCanWrite(BlockPos)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.animal.goat.Goat -1M
```
```
XXX.world.level.WorldGenLevel +1M
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.goat.Goat
</summary>

```diff
+ boolean canAttack(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.WorldGenLevel
</summary>

```diff
- boolean ensureCanWrite(BlockPos)
```

</details>
</details>
<hr/>