## Comparison with [26.2-snapshot-8](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.2-snapshot-8)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Commands](#commands)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.2-snapshot-8</th><th>26.2-pre-1</th></tr><tr><td>DataPack version</td><td><pre>106.0</pre></td><td><pre>106.1</pre></td></tr><tr><td>ResourcePack version</td><td><pre>87.0</pre></td><td><pre>88.0</pre></td></tr><tr><td>World version</td><td><pre>4893</pre></td><td><pre>4894</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742138</pre></td><td><pre>1073742139</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
- dev.onvoid.webrtc:webrtc-java (linux-aarch32) V0.14.0
- dev.onvoid.webrtc:webrtc-java (linux-aarch64) V0.14.0
- dev.onvoid.webrtc:webrtc-java (linux-x86_64) V0.14.0
- dev.onvoid.webrtc:webrtc-java (macos-aarch64) V0.14.0
- dev.onvoid.webrtc:webrtc-java (macos-x86_64) V0.14.0
- dev.onvoid.webrtc:webrtc-java (windows-x86_64) V0.14.0
- dev.onvoid.webrtc:webrtc-java V0.14.0
+ org.lwjgl:lwjgl (unsafe) V3.4.1
- org.lwjgl:lwjgl V3.4.1
```

</details>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.2-snapshot-8</th><th>26.2-pre-1</th></tr><tr><td>com.mojang:authlib</td><td><pre>7.0.72</pre></td><td><pre>8.0.73</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:entity.small_sulfur_cube.eat
+ minecraft:entity.sulfur_cube.bouncy.hit
+ minecraft:entity.sulfur_cube.bouncy.push
+ minecraft:entity.sulfur_cube.explosive.hit
+ minecraft:entity.sulfur_cube.explosive.push
+ minecraft:entity.sulfur_cube.fast_flat.hit
+ minecraft:entity.sulfur_cube.fast_flat.push
+ minecraft:entity.sulfur_cube.fast_sliding.hit
+ minecraft:entity.sulfur_cube.fast_sliding.push
+ minecraft:entity.sulfur_cube.high_resistance.hit
+ minecraft:entity.sulfur_cube.high_resistance.push
- minecraft:entity.sulfur_cube.hit
+ minecraft:entity.sulfur_cube.hot.hit
+ minecraft:entity.sulfur_cube.hot.push
+ minecraft:entity.sulfur_cube.light.hit
+ minecraft:entity.sulfur_cube.light.push
- minecraft:entity.sulfur_cube.push
+ minecraft:entity.sulfur_cube.regular.hit
+ minecraft:entity.sulfur_cube.regular.push
+ minecraft:entity.sulfur_cube.slow_bouncy.hit
+ minecraft:entity.sulfur_cube.slow_bouncy.push
+ minecraft:entity.sulfur_cube.slow_flat.hit
+ minecraft:entity.sulfur_cube.slow_flat.push
+ minecraft:entity.sulfur_cube.slow_sliding.hit
+ minecraft:entity.sulfur_cube.slow_sliding.push
+ minecraft:entity.sulfur_cube.sticky.hit
+ minecraft:entity.sulfur_cube.sticky.push
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.small_sulfur_cube.eat
+ minecraft:entity.sulfur_cube.bouncy.hit
+ minecraft:entity.sulfur_cube.bouncy.push
+ minecraft:entity.sulfur_cube.explosive.hit
+ minecraft:entity.sulfur_cube.explosive.push
+ minecraft:entity.sulfur_cube.fast_flat.hit
+ minecraft:entity.sulfur_cube.fast_flat.push
+ minecraft:entity.sulfur_cube.fast_sliding.hit
+ minecraft:entity.sulfur_cube.fast_sliding.push
+ minecraft:entity.sulfur_cube.high_resistance.hit
+ minecraft:entity.sulfur_cube.high_resistance.push
- minecraft:entity.sulfur_cube.hit
+ minecraft:entity.sulfur_cube.hot.hit
+ minecraft:entity.sulfur_cube.hot.push
+ minecraft:entity.sulfur_cube.light.hit
+ minecraft:entity.sulfur_cube.light.push
- minecraft:entity.sulfur_cube.push
+ minecraft:entity.sulfur_cube.regular.hit
+ minecraft:entity.sulfur_cube.regular.push
+ minecraft:entity.sulfur_cube.slow_bouncy.hit
+ minecraft:entity.sulfur_cube.slow_bouncy.push
+ minecraft:entity.sulfur_cube.slow_flat.hit
+ minecraft:entity.sulfur_cube.slow_flat.push
+ minecraft:entity.sulfur_cube.slow_sliding.hit
+ minecraft:entity.sulfur_cube.slow_sliding.push
+ minecraft:entity.sulfur_cube.sticky.hit
+ minecraft:entity.sulfur_cube.sticky.push
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
publish
</summary>

```diff
+ publish <allowCommands: bool> <gamemode: gamemode> <port: integer>
- publish <online: bool> <allowCommands: bool> <gamemode: gamemode> <port: integer>
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
+ generator.minecraft.flat_all_dimensions: Flat All Dimensions
+ subtitles.entity.small_sulfur_cube.death: Small Sulfur Cube dies
+ subtitles.entity.small_sulfur_cube.eat: Small Sulfur Cube puts on mass
+ subtitles.entity.small_sulfur_cube.hurt: Small Sulfur Cube hurts
+ subtitles.entity.small_sulfur_cube.jump: Small Sulfur Cube bounces
+ subtitles.entity.sulfur_cube.jump: Sulfur Cube bounces
+ telemetry.property.server_session_id.title: Server Session ID
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.2-snapshot-8</th><th>26.2-pre-1</th></tr>
<tr><th align="left"><div style="width:290px">options.sharePresence.limited.tooltip</div></th><td>Sharing limited presence. Appearing as online, but not sharing what you are doing. You can still invite friends to your game.</td><td>Sharing limited presence. Appearing as online, but not sharing what you are doing.</td></tr>
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
+ minecraft/worldgen/world_preset/flat_all_dimensions.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/models/block/attached_hanging_sign_rot_0.json
- minecraft/models/block/attached_hanging_sign_rot_1.json
- minecraft/models/block/attached_hanging_sign_rot_2.json
- minecraft/models/block/attached_hanging_sign_rot_3.json
- minecraft/models/block/bed_foot.json
- minecraft/models/block/bed_head.json
- minecraft/models/block/hanging_sign_rot_0.json
- minecraft/models/block/hanging_sign_rot_1.json
- minecraft/models/block/hanging_sign_rot_2.json
- minecraft/models/block/hanging_sign_rot_3.json
- minecraft/models/block/sign_rot_0.json
- minecraft/models/block/sign_rot_1.json
- minecraft/models/block/sign_rot_2.json
- minecraft/models/block/sign_rot_3.json
+ minecraft/models/block/template_attached_hanging_sign_rot_0.json
+ minecraft/models/block/template_attached_hanging_sign_rot_1.json
+ minecraft/models/block/template_attached_hanging_sign_rot_2.json
+ minecraft/models/block/template_attached_hanging_sign_rot_3.json
+ minecraft/models/block/template_bed_foot.json
+ minecraft/models/block/template_bed_head.json
+ minecraft/models/block/template_hanging_sign_rot_0.json
+ minecraft/models/block/template_hanging_sign_rot_1.json
+ minecraft/models/block/template_hanging_sign_rot_2.json
+ minecraft/models/block/template_hanging_sign_rot_3.json
+ minecraft/models/block/template_sign_rot_0.json
+ minecraft/models/block/template_sign_rot_1.json
+ minecraft/models/block/template_sign_rot_2.json
+ minecraft/models/block/template_sign_rot_3.json
+ minecraft/models/block/template_wall_hanging_sign.json
+ minecraft/models/block/template_wall_sign.json
- minecraft/models/block/wall_hanging_sign.json
- minecraft/models/block/wall_sign.json
+ minecraft/textures/block/purpur_pillar_side.png
- minecraft/textures/block/purpur_pillar.png
+ minecraft/textures/block/quartz_pillar_side.png
- minecraft/textures/block/quartz_pillar.png
+ minecraft/textures/entity/sulfur_cube/sulfur_cube_inner_small.png
+ minecraft/textures/entity/sulfur_cube/sulfur_cube_outer_small.png
- minecraft/textures/gui/sprites/friends/multiplayer/invite.png
- minecraft/textures/gui/sprites/friends/multiplayer/join_request.png
+ minecraft/textures/gui/sprites/friends/send_request.png
```

</details>
</details>
<hr/>