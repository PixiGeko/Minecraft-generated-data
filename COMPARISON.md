## Comparison with [19w14a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w14a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Recipes](#recipes)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">19w14a</th><th>19w14b</th></tr><tr><td>World version</td><td><code>1944</code></td><td><code>1945</code></td></tr><tr><td>Protocol version</td><td><code>470</code></td><td><code>471</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
feature.txt
</summary>

```diff
+ minecraft:fill_layer
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
universal_tags/feature.json
</summary>

```diff
+ minecraft:fill_layer
```

</details>
</details>
<details><summary>Recipes</summary>
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