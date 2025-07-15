## Comparison with [19w14a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w14a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Recipes](#recipes)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">19w14a</th><th>19w14b</th></tr><tr><td>World version</td><td><pre>1944</pre></td><td><pre>1945</pre></td></tr><tr><td>Protocol version</td><td><pre>470</pre></td><td><pre>471</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">19w14a</th><th>19w14b</th></tr><tr><td>com.mojang:realms</td><td><pre>1.14.2</pre></td><td><pre>1.14.4</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
feature
</summary>

```diff
+ minecraft:fill_layer
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/feature.json
</summary>

```diff
+ minecraft:fill_layer
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
stone_brick_slab.json
</summary>

```
A: #stone_bricks
B: stone_bricks

Previous pattern:
[A | A | A]

New pattern:
[B | B | B]
```

</details>
<details>
<summary>
stone_brick_stairs.json
</summary>

```
A: #stone_bricks
B: stone_bricks

Previous pattern:
[A |   |  ]
[A | A |  ]
[A | A | A]

New pattern:
[B |   |  ]
[B | B |  ]
[B | B | B]
```

</details>
</details>
<hr/>