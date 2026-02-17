## Comparison with [26.1-snapshot-7](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.1-snapshot-7)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.1-snapshot-7</th><th>26.1-snapshot-8</th></tr><tr><td>DataPack version</td><td><pre>99.1</pre></td><td><pre>99.2</pre></td></tr><tr><td>ResourcePack version</td><td><pre>81.0</pre></td><td><pre>81.1</pre></td></tr><tr><td>World version</td><td><pre>4775</pre></td><td><pre>4776</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742117</pre></td><td><pre>1073742118</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
- org.lwjgl:lwjgl-freetype (natives-macos-patch) V3.3.3
+ org.lwjgl:lwjgl-freetype (natives-macos) V3.4.1
```

</details>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.1-snapshot-7</th><th>26.1-snapshot-8</th></tr><tr><td>org.lwjgl:lwjgl-freetype</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-linux)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-macos-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-windows)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-windows-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-windows-x86)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw (natives-linux)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw (natives-macos)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw (natives-macos-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw (natives-windows)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw (natives-windows-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw (natives-windows-x86)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-linux)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-macos)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-macos-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-windows)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-windows-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-windows-x86)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-linux)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-macos)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-macos-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-windows)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-windows-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-windows-x86)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-linux)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-macos)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-macos-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-windows)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-windows-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-windows-x86)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-linux)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-macos)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-macos-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-windows)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-windows-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-windows-x86)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-linux)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-macos)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-macos-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-windows)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-windows-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-windows-x86)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-linux)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-macos)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-macos-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-windows)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-windows-arm64)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-windows-x86)</td><td><pre>3.3.3</pre></td><td><pre>3.4.1</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
fetchprofile
</summary>

```diff
+ fetchprofile entity <entity: entity>
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ chiseled_deepslate_from_deepslate_stonecutting.json
+ cobbled_deepslate_from_deepslate_stonecutting.json
+ cobbled_deepslate_slab_from_deepslate_stonecutting.json
+ cobbled_deepslate_stairs_from_deepslate_stonecutting.json
+ cobbled_deepslate_wall_from_deepslate_stonecutting.json
+ cobblestone_from_stone_stonecutting.json
+ cobblestone_slab_from_stone_stonecutting.json
+ cobblestone_stairs_from_stone_stonecutting.json
+ cobblestone_wall_from_stone_stonecutting.json
+ deepslate_brick_slab_from_deepslate_stonecutting.json
+ deepslate_brick_stairs_from_deepslate_stonecutting.json
+ deepslate_brick_wall_from_deepslate_stonecutting.json
+ deepslate_bricks_from_deepslate_stonecutting.json
+ deepslate_tile_slab_from_deepslate_stonecutting.json
+ deepslate_tile_stairs_from_deepslate_stonecutting.json
+ deepslate_tile_wall_from_deepslate_stonecutting.json
+ deepslate_tiles_from_deepslate_stonecutting.json
+ polished_deepslate_from_deepslate_stonecutting.json
+ polished_deepslate_slab_from_deepslate_stonecutting.json
+ polished_deepslate_stairs_from_deepslate_stonecutting.json
+ polished_deepslate_wall_from_deepslate_stonecutting.json
```

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
+ build.tooLow: Minimum height for building is %s
+ command.trailing_data: Trailing data found: %s
+ commands.fetchprofile.entity.success: Resolved profile for entity %s: %s
+ commands.fetchprofile.no_profile: Entity %s has no profile
+ upgradeWorld.canceled.message: Your world remains as it was before.
+ upgradeWorld.canceled.title: World upgrade canceled
```

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
+ minecraft/advancement/recipes/building_blocks/chiseled_deepslate_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cobbled_deepslate_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cobbled_deepslate_slab_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cobbled_deepslate_stairs_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cobblestone_from_stone_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cobblestone_slab_from_stone_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cobblestone_stairs_from_stone_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/deepslate_brick_slab_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/deepslate_brick_stairs_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/deepslate_bricks_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/deepslate_tile_slab_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/deepslate_tile_stairs_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/deepslate_tiles_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_deepslate_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_deepslate_slab_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_deepslate_stairs_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/decorations/cobbled_deepslate_wall_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/decorations/cobblestone_wall_from_stone_stonecutting.json
+ minecraft/advancement/recipes/decorations/deepslate_brick_wall_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/decorations/deepslate_tile_wall_from_deepslate_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_deepslate_wall_from_deepslate_stonecutting.json
+ minecraft/recipe/chiseled_deepslate_from_deepslate_stonecutting.json
+ minecraft/recipe/cobbled_deepslate_from_deepslate_stonecutting.json
+ minecraft/recipe/cobbled_deepslate_slab_from_deepslate_stonecutting.json
+ minecraft/recipe/cobbled_deepslate_stairs_from_deepslate_stonecutting.json
+ minecraft/recipe/cobbled_deepslate_wall_from_deepslate_stonecutting.json
+ minecraft/recipe/cobblestone_from_stone_stonecutting.json
+ minecraft/recipe/cobblestone_slab_from_stone_stonecutting.json
+ minecraft/recipe/cobblestone_stairs_from_stone_stonecutting.json
+ minecraft/recipe/cobblestone_wall_from_stone_stonecutting.json
+ minecraft/recipe/deepslate_brick_slab_from_deepslate_stonecutting.json
+ minecraft/recipe/deepslate_brick_stairs_from_deepslate_stonecutting.json
+ minecraft/recipe/deepslate_brick_wall_from_deepslate_stonecutting.json
+ minecraft/recipe/deepslate_bricks_from_deepslate_stonecutting.json
+ minecraft/recipe/deepslate_tile_slab_from_deepslate_stonecutting.json
+ minecraft/recipe/deepslate_tile_stairs_from_deepslate_stonecutting.json
+ minecraft/recipe/deepslate_tile_wall_from_deepslate_stonecutting.json
+ minecraft/recipe/deepslate_tiles_from_deepslate_stonecutting.json
+ minecraft/recipe/polished_deepslate_from_deepslate_stonecutting.json
+ minecraft/recipe/polished_deepslate_slab_from_deepslate_stonecutting.json
+ minecraft/recipe/polished_deepslate_stairs_from_deepslate_stonecutting.json
+ minecraft/recipe/polished_deepslate_wall_from_deepslate_stonecutting.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/entity/hoglin/hoglin_baby.png
+ minecraft/textures/entity/hoglin/zoglin_baby.png
+ minecraft/textures/entity/panda/aggressive_panda_baby.png
+ minecraft/textures/entity/panda/brown_panda_baby.png
+ minecraft/textures/entity/panda/lazy_panda_baby.png
+ minecraft/textures/entity/panda/panda_baby.png
+ minecraft/textures/entity/panda/playful_panda_baby.png
+ minecraft/textures/entity/panda/weak_panda_baby.png
+ minecraft/textures/entity/panda/worried_panda_baby.png
+ minecraft/textures/entity/sniffer/snifflet.png
+ minecraft/textures/entity/strider/strider_baby.png
+ minecraft/textures/entity/strider/strider_cold_baby.png
+ minecraft/textures/gui/sprites/widget/preedit.png
+ minecraft/textures/gui/sprites/widget/preedit.png.mcmeta
```

</details>
</details>
<hr/>