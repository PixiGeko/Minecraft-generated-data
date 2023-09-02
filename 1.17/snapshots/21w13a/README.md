<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 21w13a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>21w13a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2021-03-31T16:17:46+00:00</td></tr>
<tr><th>SHA1</th><td>c20df75b956c2eb982a9028ceff965e1aae40345</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/c20df75b956c2eb982a9028ceff965e1aae40345/21w13a.json">https://piston-meta.mojang.com/v1/packages/c20df75b956c2eb982a9028ceff965e1aae40345/21w13a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/f425401a00adf0112fde624ee80c66333530f8a1/1.17.json">https://piston-meta.mojang.com/v1/packages/f425401a00adf0112fde624ee80c66333530f8a1/1.17.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/36d49b1a6d05f1deac293d477bfa2b4a1babb71c/server.jar">https://piston-data.mojang.com/v1/objects/36d49b1a6d05f1deac293d477bfa2b4a1babb71c/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/13ef5a693f7437b18c322654749db3ec895ba97e/server.txt">https://piston-data.mojang.com/v1/objects/13ef5a693f7437b18c322654749db3ec895ba97e/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/507be109a1902b7c3b30c1e900299344c7c0bee6/client.jar">https://piston-data.mojang.com/v1/objects/507be109a1902b7c3b30c1e900299344c7c0bee6/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/be3ba1ca24543ecd73f240c36a3aa61916fa4d0c/client.txt">https://piston-data.mojang.com/v1/objects/be3ba1ca24543ecd73f240c36a3aa61916fa4d0c/client.txt</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/21w11a">21w11a</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/loot_tables/entities/goat.json
+  minecraft/tags/blocks/dirt.json
+  minecraft/tags/blocks/snow.json
+  minecraft/tags/entity_types/axolotl_hunt_targets.json
-  minecraft/tags/entity_types/axolotl_tempted_hostiles.json
+  minecraft/tags/entity_types/freeze_hurts_extra_types.json
+  minecraft/tags/entity_types/freeze_immune_entity_types.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/blockstates/light.json
+  minecraft/models/block/light.json
+  minecraft/models/item/goat_spawn_egg.json
+  minecraft/models/item/light.json
+  minecraft/models/item/light_00.json
+  minecraft/models/item/light_01.json
+  minecraft/models/item/light_02.json
+  minecraft/models/item/light_03.json
+  minecraft/models/item/light_04.json
+  minecraft/models/item/light_05.json
+  minecraft/models/item/light_06.json
+  minecraft/models/item/light_07.json
+  minecraft/models/item/light_08.json
+  minecraft/models/item/light_09.json
+  minecraft/models/item/light_10.json
+  minecraft/models/item/light_11.json
+  minecraft/models/item/light_12.json
+  minecraft/models/item/light_13.json
+  minecraft/models/item/light_14.json
+  minecraft/models/item/light_15.json
+  minecraft/particles/light.json
-  minecraft/textures/block/calibrated_sculk_sensor_side.png
-  minecraft/textures/block/calibrated_sculk_sensor_top.png
+  minecraft/textures/entity/goat
+  minecraft/textures/entity/goat/goat.png
-  minecraft/textures/entity/zombie/zombie_villager.png
-  minecraft/textures/entity/arrow.png
+  minecraft/textures/item/light.png
+  minecraft/textures/item/light_00.png
+  minecraft/textures/item/light_01.png
+  minecraft/textures/item/light_02.png
+  minecraft/textures/item/light_03.png
+  minecraft/textures/item/light_04.png
+  minecraft/textures/item/light_05.png
+  minecraft/textures/item/light_06.png
+  minecraft/textures/item/light_07.png
+  minecraft/textures/item/light_08.png
+  minecraft/textures/item/light_09.png
+  minecraft/textures/item/light_10.png
+  minecraft/textures/item/light_11.png
+  minecraft/textures/item/light_12.png
+  minecraft/textures/item/light_13.png
+  minecraft/textures/item/light_14.png
+  minecraft/textures/item/light_15.png
-  minecraft/textures/item/ruby.png
-  minecraft/textures/models/armor/piglin_leather_layer_1.png
-  minecraft/textures/models/armor/piglin_leather_layer_1_overlay.png
-  minecraft/textures/particle/footprint.png
```

</details>

## Registries

<details><summary>list</summary>

```diff
- worldgen/float_provider_type.txt
+ float_provider_type.txt
+ height_provider_type.txt
+ int_provider_type.txt
```

</details>

<details><summary>activity.txt</summary>

```diff
+ minecraft:long_jump
```

</details>

<details><summary>block.txt</summary>

```diff
+ minecraft:light
```

</details>

<details><summary>entity_type.txt</summary>

```diff
+ minecraft:goat
```

</details>

<details><summary>item.txt</summary>

```diff
+ minecraft:light
+ minecraft:goat_spawn_egg
```

</details>

<details><summary>memory_module_type.txt</summary>

```diff
+ minecraft:nearest_attackable
+ minecraft:long_jump_cooling_down
+ minecraft:long_jump_mid_jump
+ minecraft:has_hunting_cooldown
```

</details>

<details><summary>particle_type.txt</summary>

```diff
+ minecraft:light
```

</details>

<details><summary>sensor_type.txt</summary>

```diff
- minecraft:axolotl_hostiles
+ minecraft:axolotl_attackables
+ minecraft:goat_temptations
```

</details>

<details><summary>sound_event.txt</summary>

```diff
+ minecraft:entity.goat.ambient
+ minecraft:entity.goat.death
+ minecraft:entity.goat.hurt
+ minecraft:entity.goat.milk
+ minecraft:entity.goat.prepare_ram
+ minecraft:entity.goat.screaming.ambient
+ minecraft:entity.goat.screaming.death
+ minecraft:entity.goat.screaming.hurt
+ minecraft:entity.goat.screaming.milk
+ minecraft:entity.goat.screaming.ram
+ minecraft:entity.goat.step
```

</details>

## Tags

<details><summary>list</summary>

```diff
- entity_types/axolotl_tempted_hostiles.json
+ blocks/dirt.json
+ blocks/snow.json
+ entity_types/axolotl_hunt_targets.json
+ entity_types/freeze_hurts_extra_types.json
+ entity_types/freeze_immune_entity_types.json
```

</details>

<details><summary>blocks/bamboo_plantable_on.json</summary>

```diff
- minecraft:dirt
- minecraft:podzol
- minecraft:coarse_dirt
+ #minecraft:dirt
```

</details>

<details><summary>blocks/enderman_holdable.json</summary>

```diff
- minecraft:dirt
- minecraft:coarse_dirt
- minecraft:podzol
+ #minecraft:dirt
```

</details>

<details><summary>blocks/slabs.json</summary>

```diff
+ minecraft:waxed_weathered_cut_copper_slab
+ minecraft:waxed_exposed_cut_copper_slab
+ minecraft:waxed_cut_copper_slab
+ minecraft:oxidized_cut_copper_slab
+ minecraft:weathered_cut_copper_slab
+ minecraft:exposed_cut_copper_slab
+ minecraft:cut_copper_slab
```

</details>

<details><summary>blocks/small_flowers.json</summary>

```diff
+ minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea
```

</details>

<details><summary>blocks/stairs.json</summary>

```diff
+ minecraft:oxidized_cut_copper_stairs
+ minecraft:weathered_cut_copper_stairs
+ minecraft:exposed_cut_copper_stairs
+ minecraft:cut_copper_stairs
+ minecraft:waxed_weathered_cut_copper_stairs
+ minecraft:waxed_exposed_cut_copper_stairs
+ minecraft:waxed_cut_copper_stairs
```

</details>

<details><summary>entity_types/axolotl_always_hostiles.json</summary>

```diff
- minecraft:tropical_fish
- minecraft:pufferfish
- minecraft:salmon
- minecraft:cod
- minecraft:squid
- minecraft:glow_squid
+ minecraft:drowned
+ minecraft:guardian
+ minecraft:elder_guardian
```

</details>

<details><summary>items/freeze_immune_wearables.json</summary>

```diff
+ minecraft:leather_horse_armor
```

</details>

<details><summary>items/slabs.json</summary>

```diff
+ minecraft:waxed_weathered_cut_copper_slab
+ minecraft:waxed_exposed_cut_copper_slab
+ minecraft:waxed_cut_copper_slab
+ minecraft:oxidized_cut_copper_slab
+ minecraft:weathered_cut_copper_slab
+ minecraft:exposed_cut_copper_slab
+ minecraft:cut_copper_slab
```

</details>

<details><summary>items/small_flowers.json</summary>

```diff
+ minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea
```

</details>

<details><summary>items/stairs.json</summary>

```diff
+ minecraft:oxidized_cut_copper_stairs
+ minecraft:weathered_cut_copper_stairs
+ minecraft:exposed_cut_copper_stairs
+ minecraft:cut_copper_stairs
+ minecraft:waxed_weathered_cut_copper_stairs
+ minecraft:waxed_exposed_cut_copper_stairs
+ minecraft:waxed_cut_copper_stairs
```

</details>

## Misc

<details><summary>loot_tables.txt</summary>

```diff
+ entities/goat.json
```

</details>

<details><summary>particles.txt</summary>

```diff
+ light.json
```

</details>

<details><summary>tags.txt</summary>

```diff
- entity_types/axolotl_tempted_hostiles.json
+ blocks/dirt.json
+ blocks/snow.json
+ entity_types/axolotl_hunt_targets.json
+ entity_types/freeze_hurts_extra_types.json
+ entity_types/freeze_immune_entity_types.json
```

</details>

<details><summary>textures.txt</summary>

```diff
- block/calibrated_sculk_sensor_side.png
- block/calibrated_sculk_sensor_top.png
- entity/arrow.png
- entity/zombie/zombie_villager.png
- item/ruby.png
- models/armor/piglin_leather_layer_1.png
- models/armor/piglin_leather_layer_1_overlay.png
- particle/footprint.png
+ entity/goat/goat.png
+ item/light.png
+ item/light_00.png
+ item/light_01.png
+ item/light_02.png
+ item/light_03.png
+ item/light_04.png
+ item/light_05.png
+ item/light_06.png
+ item/light_07.png
+ item/light_08.png
+ item/light_09.png
+ item/light_10.png
+ item/light_11.png
+ item/light_12.png
+ item/light_13.png
+ item/light_14.png
+ item/light_15.png
```

</details>

## Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:brigadier:1.0.17
+ com.mojang:brigadier:1.0.18
```

</details>

## Mappings

<details><summary>com.mojang.blaze3d.Blaze3D</summary>

```diff
+ void <init>()
+ void process(RenderPipeline,float)
+ void render(RenderPipeline,float)
```

</details>

<details><summary>com.mojang.blaze3d.font.GlyphInfo</summary>

```diff
+ float getBearingY()
```

</details>




<details><summary>com.mojang.blaze3d.pipeline.RenderTarget</summary>

```diff
+ int ALPHA_CHANNEL
+ int BLUE_CHANNEL
+ int GREEN_CHANNEL
+ int RED_CHANNEL
+ void bindRead()
```

</details>

<details><summary>com.mojang.blaze3d.platform.GlStateManager</summary>

```diff
+ int TEXTURE_COUNT
+ int getBoundFramebuffer()
+ int glGenRenderbuffers()
+ void _glBindRenderbuffer(int,int)
+ void _glCopyTexSubImage2D(int,int,int,int,int,int,int,int)
+ void _glDeleteRenderbuffers(int)
+ void _glDrawPixels(int,int,int,int,long)
+ void _glFramebufferRenderbuffer(int,int,int,int)
+ void _glRenderbufferStorage(int,int,int,int)
+ void _readPixels(int,int,int,int,int,int,long)
+ void <init>()
```

</details>








<details><summary>com.mojang.blaze3d.platform.GlStateManager$Viewport</summary>

```diff
+ int height()
+ int width()
+ int x()
+ int y()
```

</details>

<details><summary>com.mojang.blaze3d.platform.InputConstants</summary>

```diff
+ int CURSOR
+ int CURSOR_DISABLED
+ int CURSOR_NORMAL
+ int KEY_0
+ int KEY_1
+ int KEY_2
+ int KEY_3
+ int KEY_4
+ int KEY_5
+ int KEY_6
+ int KEY_7
+ int KEY_8
+ int KEY_9
+ int KEY_A
+ int KEY_ADD
+ int KEY_APOSTROPHE
+ int KEY_B
+ int KEY_BACKSLASH
+ int KEY_BACKSPACE
+ int KEY_C
+ int KEY_CAPSLOCK
+ int KEY_COMMA
+ int KEY_D
+ int KEY_DELETE
+ int KEY_DOWN
+ int KEY_E
+ int KEY_END
+ int KEY_EQUALS
+ int KEY_ESCAPE
+ int KEY_F
+ int KEY_F1
+ int KEY_F10
+ int KEY_F11
+ int KEY_F12
+ int KEY_F13
+ int KEY_F14
+ int KEY_F15
+ int KEY_F16
+ int KEY_F17
+ int KEY_F18
+ int KEY_F19
+ int KEY_F2
+ int KEY_F20
+ int KEY_F21
+ int KEY_F22
+ int KEY_F23
+ int KEY_F24
+ int KEY_F25
+ int KEY_F3
+ int KEY_F4
+ int KEY_F5
+ int KEY_F6
+ int KEY_F7
+ int KEY_F8
+ int KEY_F9
+ int KEY_G
+ int KEY_GRAVE
+ int KEY_H
+ int KEY_HOME
+ int KEY_I
+ int KEY_INSERT
+ int KEY_J
+ int KEY_K
+ int KEY_L
+ int KEY_LALT
+ int KEY_LBRACKET
+ int KEY_LCONTROL
+ int KEY_LEFT
+ int KEY_LSHIFT
+ int KEY_LWIN
+ int KEY_M
+ int KEY_MINUS
+ int KEY_MULTIPLY
+ int KEY_N
+ int KEY_NUMLOCK
+ int KEY_NUMPAD0
+ int KEY_NUMPAD1
+ int KEY_NUMPAD2
+ int KEY_NUMPAD3
+ int KEY_NUMPAD4
+ int KEY_NUMPAD5
+ int KEY_NUMPAD6
+ int KEY_NUMPAD7
+ int KEY_NUMPAD8
+ int KEY_NUMPAD9
+ int KEY_NUMPADCOMMA
+ int KEY_NUMPADENTER
+ int KEY_NUMPADEQUALS
+ int KEY_O
+ int KEY_P
+ int KEY_PAGEDOWN
+ int KEY_PAGEUP
+ int KEY_PAUSE
+ int KEY_PERIOD
+ int KEY_PRINTSCREEN
+ int KEY_Q
+ int KEY_R
+ int KEY_RALT
+ int KEY_RBRACKET
+ int KEY_RCONTROL
+ int KEY_RETURN
+ int KEY_RIGHT
+ int KEY_RSHIFT
+ int KEY_RWIN
+ int KEY_S
+ int KEY_SCROLLLOCK
+ int KEY_SEMICOLON
+ int KEY_SLASH
+ int KEY_SPACE
+ int KEY_T
+ int KEY_TAB
+ int KEY_U
+ int KEY_UP
+ int KEY_V
+ int KEY_W
+ int KEY_X
+ int KEY_Y
+ int KEY_Z
+ int MOD_CONTROL
+ int MOUSE_BUTTON_LEFT
+ int MOUSE_BUTTON_MIDDLE
+ int MOUSE_BUTTON_RIGHT
+ int PRESS
+ int RELEASE
+ int REPEAT
+ void <init>()
```

</details>


<details><summary>com.mojang.blaze3d.platform.Lighting</summary>

```diff
+ void <init>()
```

</details>


<details><summary>com.mojang.blaze3d.platform.NativeImage</summary>

```diff
+ int OFFSET_A
+ int OFFSET_B
+ int OFFSET_G
+ int OFFSET_R
+ byte getBlueOrLuminance(int,int)
+ byte getGreenOrLuminance(int,int)
+ byte getRedOrLuminance(int,int)
+ void blendPixel(int,int,int)
+ void downloadDepthBuffer(float)
+ void drawPixels()
+ void setPixelLuminance(int,int,byte)
+ void writeToFile(String)
```

</details>

<details><summary>com.mojang.blaze3d.platform.NativeImage$Format</summary>

```diff
+ boolean hasBlue()
+ boolean hasGreen()
+ boolean hasLuminance()
+ boolean hasLuminanceOrBlue()
+ boolean hasLuminanceOrGreen()
+ boolean hasLuminanceOrRed()
+ boolean hasRed()
+ int blueOffset()
+ int greenOffset()
+ int luminanceOffset()
+ int luminanceOrBlueOffset()
+ int luminanceOrGreenOffset()
+ int luminanceOrRedOffset()
+ int redOffset()
```

</details>



<details><summary>com.mojang.blaze3d.platform.PngInfo$StbReaderBufferedChannel</summary>

```diff
+ int START_BUFFER_SIZE
```

</details>


<details><summary>com.mojang.blaze3d.platform.TextureUtil</summary>

```diff
+ int DEFAULT_IMAGE_BUFFER_SIZE
+ int MIN_MIPMAP_LEVEL
+ void <init>()
+ void writeAsPNG(String,int,int,int,int)
```

</details>





<details><summary>com.mojang.math.OctahedralGroup</summary>

```diff
+ Matrix3f transformation()
+ OctahedralGroup inverse()
```

</details>

<details><summary>com.mojang.math.Quaternion</summary>

```diff
+ Quaternion fromXYZ(float,float,float)
+ Quaternion fromXYZ(Vector3f)
+ Quaternion fromXYZDegrees(Vector3f)
+ Quaternion fromYXZ(float,float,float)
+ Vector3f toXYZ()
+ Vector3f toXYZDegrees()
+ Vector3f toYXZ()
+ Vector3f toYXZDegrees()
+ void slerp(Quaternion,float)
```

</details>

<details><summary>com.mojang.math.Transformation</summary>

```diff
+ Quaternion getRightRotation()
+ Transformation slerp(Transformation,float)
+ Vector3f getScale()
+ Vector3f getTranslation()
```

</details>

<details><summary>com.mojang.math.Vector3f</summary>

```diff
+ DataResult lambda$static$1(List)
+ List lambda$static$2(Vector3f)
+ Vector3f lambda$null$0(List)
+ void clamp(Vector3f)
+ void load(Vector3f)
- DataResult lambda$static$1(DoubleStream)
- DoubleStream lambda$static$2(Vector3f)
- Vector3f lambda$null$0(double[])
```

</details>










<details><summary>com.mojang.realmsclient.dto.RealmsWorldOptions</summary>

```diff
+ boolean DEFAULT_COMMAND_BLOCKS
+ boolean DEFAULT_FORCE_GAME_MODE
+ boolean DEFAULT_PVP
+ boolean DEFAULT_SPAWN_ANIMALS
+ boolean DEFAULT_SPAWN_MONSTERS
+ boolean DEFAULT_SPAWN_NPCS
+ int DEFAULT_DIFFICULTY
+ int DEFAULT_GAME_MODE
+ int DEFAULT_SPAWN_PROTECTION
+ long DEFAULT_TEMPLATE_ID
+ String DEFAULT_SLOT_NAME
```

</details>



<details><summary>com.mojang.realmsclient.dto.UploadInfo</summary>

```diff
+ int DEFAULT_PORT
+ String DEFAULT_SCHEMA
```

</details>












<details><summary>com.mojang.realmsclient.util.RealmsUtil</summary>

```diff
+ int DAYS
+ int HOURS
+ int MINUTES
+ void <init>()
```

</details>


<details><summary>com.mojang.realmsclient.util.TextRenderingUtils$Line</summary>

```diff
+ void <init>(TextRenderingUtils$LineSegment[])
```

</details>

<details><summary>com.mojang.realmsclient.util.UploadTokenCache</summary>

```diff
+ void <init>()
```

</details>







<details><summary>net.minecraft.FileUtil</summary>

```diff
+ int MAX_FILE_NAME
```

</details>


<details><summary>net.minecraft.SharedConstants</summary>

```diff
+ boolean COMMAND_STACK_TRACES
+ boolean DEBUG_BEES
+ boolean DEBUG_BLOCK_BREAK
+ boolean DEBUG_BRAIN
+ boolean DEBUG_CARVERS
+ boolean DEBUG_CHUNKS
+ boolean DEBUG_COLLISION
+ boolean DEBUG_DISABLE_AQUIFERS
+ boolean DEBUG_DISABLE_CARVERS
+ boolean DEBUG_DISABLE_FEATURES
+ boolean DEBUG_DISABLE_LIQUID_SPREADING
+ boolean DEBUG_DISABLE_NOISE_CAVES
+ boolean DEBUG_DISABLE_STRUCTURES
+ boolean DEBUG_DISABLE_SURFACE
+ boolean DEBUG_DISABLE_WATER_GENERATION
+ boolean DEBUG_DONT_SAVE_WORLD
+ boolean DEBUG_DUMP_INTERPOLATED_TEXTURE_FRAMES
+ boolean DEBUG_DUMP_TEXTURE_ATLAS
+ boolean DEBUG_GAME_EVENT_LISTENERS
+ boolean DEBUG_GOAL_SELECTOR
+ boolean DEBUG_HEIGHTMAP
+ boolean DEBUG_HOTKEYS
+ boolean DEBUG_KEEP_JIGSAW_BLOCKS_DURING_STRUCTURE_GEN
+ boolean DEBUG_LARGE_DRIPSTONE
+ boolean DEBUG_LIGHT
+ boolean DEBUG_MONITOR_TICK_TIMES
+ boolean DEBUG_NAMED_RUNNABLES
+ boolean DEBUG_NEIGHBORSUPDATE
+ boolean DEBUG_ONLY_GENERATE_HALF_THE_WORLD
+ boolean DEBUG_PACKET_SERIALIZATION
+ boolean DEBUG_PATHFINDING
+ boolean DEBUG_RAIDS
+ boolean DEBUG_RENDER
+ boolean DEBUG_RESOURCE_LOAD_TIMES
+ boolean DEBUG_SAVE_STRUCTURES_AS_SNBT
+ boolean DEBUG_SHAPES
+ boolean DEBUG_SHOW_SERVER_DEBUG_VALUES
+ boolean DEBUG_SMALL_SPAWN
+ boolean DEBUG_SOLID_FACE
+ boolean DEBUG_STORE_CHUNK_STACKTRACES
+ boolean DEBUG_STRUCTURE_EDIT_MODE
+ boolean DEBUG_STRUCTURES
+ boolean DEBUG_SUBTITLES
+ boolean DEBUG_SYNCHRONOUS_GL_LOGS
+ boolean DEBUG_VERBOSE_SERVER_EVENTS
+ boolean DEBUG_VILLAGE_SECTIONS
+ boolean DEBUG_WATER
+ boolean DEBUG_WORLD_RECREATE
+ boolean DEBUG_WORLDGENATTEMPT
+ boolean ENABLE_SNOOPER
+ boolean EXTENDED_WORLD_HEIGHT
+ boolean FIX_TNT_DUPE
+ boolean INGAME_DEBUG_OUTPUT
+ boolean MULTITHREADED_RENDERING
+ boolean NEW_WORLD_GENERATION
+ boolean SNAPSHOT
+ boolean USE_DEBUG_FEATURES
+ boolean USE_NEW_RENDERSYSTEM
+ float AVERAGE_GAME_TICKS_PER_RANDOM_TICK_PER_BLOCK
+ float AVERAGE_RANDOM_TICKS_PER_BLOCK_PER_GAME_DAY
+ float AVERAGE_RANDOM_TICKS_PER_BLOCK_PER_MINUTE
+ float RAIN_THRESHOLD
+ int DATA_PACK_FORMAT
+ int DEFAULT_MINECRAFT_PORT
+ int FAKE_MS_JITTER
+ int FAKE_MS_LATENCY
+ int MAX_CHAT_LENGTH
+ int MAX_COMMAND_LENGTH
+ int RELEASE_NETWORK_PROTOCOL_VERSION
+ int RESOURCE_PACK_FORMAT
+ int SNAPSHOT_NETWORK_PROTOCOL_VERSION
+ int SNAPSHOT_PROTOCOL_BIT
+ int SNBT_NAG_VERSION
+ int TICKS_PER_GAME_DAY
+ int TICKS_PER_MINUTE
+ int TICKS_PER_SECOND
+ int WORLD_RESOLUTION
+ int WORLD_VERSION
+ String DATA_VERSION_TAG
+ String RELEASE_TARGET
+ String VERSION_STRING
```

</details>




















































































<details><summary>net.minecraft.client.Camera</summary>

```diff
+ float FOG_DISTANCE_SCALE
```

</details>

<details><summary>net.minecraft.client.ClientBrandRetriever</summary>

```diff
+ String VANILLA_NAME
```

</details>







<details><summary>net.minecraft.client.KeyMapping</summary>

```diff
+ String CATEGORY_CREATIVE
+ String CATEGORY_GAMEPLAY
+ String CATEGORY_INTERFACE
+ String CATEGORY_INVENTORY
+ String CATEGORY_MISC
+ String CATEGORY_MOVEMENT
+ String CATEGORY_MULTIPLAYER
```

</details>


<details><summary>net.minecraft.client.Minecraft</summary>

```diff
+ int MAX_TICKS_PER_UPDATE
```

</details>



















<details><summary>net.minecraft.client.color.block.BlockColors</summary>

```diff
+ int DEFAULT
```

</details>



<details><summary>net.minecraft.client.color.item.ItemColors</summary>

```diff
+ int DEFAULT
```

</details>

<details><summary>net.minecraft.client.gui.Font</summary>

```diff
+ float EFFECT_DEPTH
```

</details>

<details><summary>net.minecraft.client.gui.Gui</summary>

```diff
+ float MIN_CROSSHAIR_ATTACK_SPEED
+ float PORTAL_OVERLAY_ALPHA_MIN
+ int COLOR_WHITE
+ int LINE_HEIGHT
+ int NUM_HEARTS_PER_ROW
+ String SPACER
```

</details>

<details><summary>net.minecraft.client.gui.MapRenderer</summary>

```diff
+ int HEIGHT
+ int WIDTH
+ RenderType access$300()
+ TextureManager access$200(MapRenderer)
- MapItemSavedData retrieveMapFromRenderer(int)
- RenderType access$400()
- TextureManager access$300(MapRenderer)
```

</details>

<details><summary>net.minecraft.client.gui.MapRenderer$MapInstance</summary>

```diff
- MapItemSavedData access$200(MapRenderer$MapInstance)
```

</details>







<details><summary>net.minecraft.client.gui.components.AbstractWidget</summary>

```diff
+ int NARRATE_DELAY_FOCUS
+ int NARRATE_DELAY_MOUSE
```

</details>



<details><summary>net.minecraft.client.gui.components.ChatComponent</summary>

```diff
+ int MAX_CHAT_HISTORY
```

</details>








<details><summary>net.minecraft.client.gui.components.DebugScreenOverlay</summary>

```diff
+ int COLOR_GREY
+ int GREEN
+ int MARGIN_LEFT
+ int MARGIN_RIGHT
+ int MARGIN_TOP
+ int RED
+ int YELLOW
```

</details>

<details><summary>net.minecraft.client.gui.components.EditBox</summary>

```diff
+ int BACKGROUND_COLOR
+ int BACKWARDS
+ int BORDER_COLOR
+ int BORDER_COLOR_FOCUSED
+ int CURSOR_INSERT_COLOR
+ int CURSOR_INSERT_WIDTH
+ int DEFAULT_TEXT_COLOR
+ int FORWARDS
+ long NARRATE_DELAY_TYPING_MS
+ String CURSOR_APPEND_CHARACTER
```

</details>

<details><summary>net.minecraft.client.gui.components.LerpingBossEvent</summary>

```diff
+ long LERP_MILLISECONDS
```

</details>








<details><summary>net.minecraft.client.gui.components.SubtitleOverlay</summary>

```diff
+ long DISPLAY_TIME
```

</details>







<details><summary>net.minecraft.client.gui.components.toasts.RecipeToast</summary>

```diff
+ long DISPLAY_TIME
```

</details>




<details><summary>net.minecraft.client.gui.components.toasts.TutorialToast</summary>

```diff
+ int PROGRESS_BAR_HEIGHT
+ int PROGRESS_BAR_WIDTH
+ int PROGRESS_BAR_X
+ int PROGRESS_BAR_Y
```

</details>


<details><summary>net.minecraft.client.gui.font.FontManager</summary>

```diff
+ String FONTS_PATH
```

</details>





<details><summary>net.minecraft.client.gui.font.glyphs.MissingGlyph</summary>

```diff
+ int MISSING_IMAGE_HEIGHT
+ int MISSING_IMAGE_WIDTH
```

</details>





<details><summary>net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider</summary>

```diff
+ int CHARS_PER_SHEET
+ int TEXTURE_SIZE
+ int UNICODE_SHEETS
```

</details>






<details><summary>net.minecraft.client.gui.screens.ChatScreen</summary>

```diff
+ int MOUSE_SCROLL_SPEED
```

</details>


<details><summary>net.minecraft.client.gui.screens.ConnectScreen</summary>

```diff
+ long NARRATION_DELAY_MS
```

</details>



<details><summary>net.minecraft.client.gui.screens.CreateFlatWorldScreen</summary>

```diff
+ int SLOT_BG_SIZE
+ int SLOT_BG_X
+ int SLOT_BG_Y
+ int SLOT_FG_X
+ int SLOT_FG_Y
+ int SLOT_STAT_HEIGHT
+ int SLOT_TEX_SIZE
```

</details>








<details><summary>net.minecraft.client.gui.screens.LevelLoadingScreen</summary>

```diff
+ long NARRATION_DELAY_MS
```

</details>





<details><summary>net.minecraft.client.gui.screens.PauseScreen</summary>

```diff
+ String URL_BUGS
+ String URL_FEEDBACK_RELEASE
+ String URL_FEEDBACK_SNAPSHOT
```

</details>







<details><summary>net.minecraft.client.gui.screens.TitleScreen</summary>

```diff
+ String COPYRIGHT_TEXT
+ String DEMO_LEVEL_ID
```

</details>

<details><summary>net.minecraft.client.gui.screens.WinScreen</summary>

```diff
+ String CENTERED_PREFIX
```

</details>














<details><summary>net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen</summary>

```diff
+ int HELP_TIPS_OFFSET_Y
+ int SLOT_AREA
+ int SLOT_AREA_PADDED
+ int SLOT_PADDING
+ int SPRITE_SHEET_HEIGHT
+ int SPRITE_SHEET_WIDTH
```

</details>

<details><summary>net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon</summary>

```diff
+ int ICON_AREA
+ int ICON_TOP_LEFT
```

</details>


<details><summary>net.minecraft.client.gui.screens.inventory.AbstractContainerScreen</summary>

```diff
+ float SNAPBACK_SPEED
+ int DOUBLECLICK_SPEED
+ int HOVER_ITEM_BLIT_OFFSET
+ int QUICKDROP_DELAY
+ int SLOT_ITEM_BLIT_OFFSET
```

</details>






























<details><summary>net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip</summary>

```diff
+ int BORDER_WIDTH
+ int MARGIN_Y
+ int SLOT_SIZE_X
+ int SLOT_SIZE_Y
+ int TEX_SIZE
```

</details>





















<details><summary>net.minecraft.client.gui.spectator.categories.SpectatorPage</summary>

```diff
+ int NO_SELECTION
```

</details>









<details><summary>net.minecraft.client.model.GuardianModel</summary>

```diff
+ String EYE
+ String TAIL_0
+ String TAIL_1
+ String TAIL_2
```

</details>


<details><summary>net.minecraft.client.model.HorseModel</summary>

```diff
+ float DEG_125
+ float DEG_15
+ float DEG_30
+ float DEG_45
+ float DEG_60
+ String HEAD_PARTS
+ String HEAD_SADDLE
+ String LEFT_FRONT_BABY_LEG
+ String LEFT_HIND_BABY_LEG
+ String LEFT_SADDLE_LINE
+ String LEFT_SADDLE_MOUTH
+ String MOUTH_SADDLE_WRAP
+ String RIGHT_FRONT_BABY_LEG
+ String RIGHT_HIND_BABY_LEG
+ String RIGHT_SADDLE_LINE
+ String RIGHT_SADDLE_MOUTH
+ String SADDLE
```

</details>



<details><summary>net.minecraft.client.model.LavaSlimeModel</summary>

```diff
+ int SEGMENT_COUNT
```

</details>


<details><summary>net.minecraft.client.model.LlamaSpitModel</summary>

```diff
+ String MAIN
```

</details>


<details><summary>net.minecraft.client.model.OcelotModel</summary>

```diff
+ float BACK_LEG_Y
+ float BACK_LEG_Z
+ float BODY_WALK_Y
+ float BODY_WALK_Z
+ float FRONT_LEG_Y
+ float FRONT_LEG_Z
+ float HEAD_WALK_Y
+ float HEAD_WALK_Z
+ float TAIL_1_WALK_Y
+ float TAIL_1_WALK_Z
+ float TAIL_2_WALK_Y
+ float TAIL_2_WALK_Z
+ float XO
+ float YO
+ float ZO
+ int CROUCH_STATE
+ int SITTING_STATE
+ int SPRINT_STATE
+ int WALK_STATE
+ String TAIL_1
+ String TAIL_2
```

</details>

<details><summary>net.minecraft.client.model.ParrotModel</summary>

```diff
+ String FEATHER
```

</details>



<details><summary>net.minecraft.client.model.PlayerModel</summary>

```diff
+ String CLOAK
+ String EAR
+ String LEFT_PANTS
+ String LEFT_SLEEVE
+ String RIGHT_PANTS
+ String RIGHT_SLEEVE
```

</details>



<details><summary>net.minecraft.client.model.RabbitModel</summary>

```diff
+ float FRONT_JUMP_ANGLE
+ float NEW_SCALE
+ float REAR_JUMP_ANGLE
+ String LEFT_HAUNCH
+ String RIGHT_HAUNCH
```

</details>

<details><summary>net.minecraft.client.model.SalmonModel</summary>

```diff
+ String BODY_BACK
+ String BODY_FRONT
```

</details>


<details><summary>net.minecraft.client.model.ShulkerBulletModel</summary>

```diff
+ String MAIN
```

</details>

<details><summary>net.minecraft.client.model.SilverfishModel</summary>

```diff
+ int BODY_COUNT
```

</details>



<details><summary>net.minecraft.client.model.SpiderModel</summary>

```diff
+ String BODY_0
+ String BODY_1
+ String LEFT_MIDDLE_FRONT_LEG
+ String LEFT_MIDDLE_HIND_LEG
+ String RIGHT_MIDDLE_FRONT_LEG
+ String RIGHT_MIDDLE_HIND_LEG
```

</details>

<details><summary>net.minecraft.client.model.StriderModel</summary>

```diff
+ String LEFT_BOTTOM_BRISTLE
+ String LEFT_MIDDLE_BRISTLE
+ String LEFT_TOP_BRISTLE
+ String RIGHT_BOTTOM_BRISTLE
+ String RIGHT_MIDDLE_BRISTLE
+ String RIGHT_TOP_BRISTLE
```

</details>


<details><summary>net.minecraft.client.model.TurtleModel</summary>

```diff
+ String EGG_BELLY
```

</details>



<details><summary>net.minecraft.client.model.WolfModel</summary>

```diff
+ int LEG_SIZE
+ String REAL_HEAD
+ String REAL_TAIL
+ String UPPER_BODY
```

</details>




<details><summary>net.minecraft.client.model.geom.ModelLayers</summary>

```diff
+ ModelLayerLocation GOAT
+ String DEFAULT_LAYER
```

</details>



<details><summary>net.minecraft.client.model.geom.PartNames</summary>

```diff
+ String ARMS
+ String BACK_FIN
+ String BEAK
+ String BODY
+ String BOTTOM_FIN
+ String CUBE
+ String HAT
+ String HAT_RIM
+ String HEAD
+ String JACKET
+ String JAW
+ String LEFT_ARM
+ String LEFT_BLUE_FIN
+ String LEFT_CHEST
+ String LEFT_EAR
+ String LEFT_EYE
+ String LEFT_FIN
+ String LEFT_FRONT_FOOT
+ String LEFT_FRONT_LEG
+ String LEFT_FRONT_LEG_TIP
+ String LEFT_GILLS
+ String LEFT_HIND_FOOT
+ String LEFT_HIND_LEG
+ String LEFT_HIND_LEG_TIP
+ String LEFT_HORN
+ String LEFT_LEG
+ String LEFT_LID
+ String LEFT_WING
+ String LEFT_WING_BASE
+ String LEFT_WING_TIP
+ String MANE
+ String MOUTH
+ String NECK
+ String NOSE
+ String RIGHT_ARM
+ String RIGHT_BLUE_FIN
+ String RIGHT_CHEST
+ String RIGHT_EAR
+ String RIGHT_EYE
+ String RIGHT_FIN
+ String RIGHT_FRONT_FOOT
+ String RIGHT_FRONT_LEG
+ String RIGHT_FRONT_LEG_TIP
+ String RIGHT_GILLS
+ String RIGHT_HIND_FOOT
+ String RIGHT_HIND_LEG
+ String RIGHT_HIND_LEG_TIP
+ String RIGHT_HORN
+ String RIGHT_LEG
+ String RIGHT_LID
+ String RIGHT_WING
+ String RIGHT_WING_BASE
+ String RIGHT_WING_TIP
+ String TAIL
+ String TAIL_FIN
+ String TOP_FIN
+ String TOP_GILLS
```

</details>
























<details><summary>net.minecraft.client.particle.DragonBreathParticle</summary>

```diff
+ float COLOR_MAX_BLUE
+ float COLOR_MAX_GREEN
+ float COLOR_MAX_RED
+ float COLOR_MIN_BLUE
+ float COLOR_MIN_GREEN
+ float COLOR_MIN_RED
+ int COLOR_MAX
+ int COLOR_MIN
```

</details>





































<details><summary>net.minecraft.client.particle.ItemPickupParticle</summary>

```diff
+ int LIFE_TIME
```

</details>

















































<details><summary>net.minecraft.client.player.AbstractClientPlayer</summary>

```diff
+ int SKIN_HAT_HEIGHT
+ int SKIN_HAT_U
+ int SKIN_HAT_V
+ int SKIN_HAT_WIDTH
+ int SKIN_HEAD_HEIGHT
+ int SKIN_HEAD_U
+ int SKIN_HEAD_V
+ int SKIN_HEAD_WIDTH
+ int SKIN_TEX_HEIGHT
+ int SKIN_TEX_WIDTH
+ String SKIN_URL_TEMPLATE
```

</details>

<details><summary>net.minecraft.client.player.KeyboardInput</summary>

```diff
+ double MOVING_SLOW_FACTOR
```

</details>



<details><summary>net.minecraft.client.profiling.ActiveClientMetricsLogger</summary>

```diff
+ int PROFILING_MAX_DURATION_SECONDS
```

</details>







<details><summary>net.minecraft.client.profiling.storage.MetricsPersister</summary>

```diff
+ String DEVIATIONS_DIR_NAME
+ String METRICS_DIR_NAME
+ String PROFILING_RESULT_FILENAME
```

</details>








<details><summary>net.minecraft.client.renderer.FogRenderer</summary>

```diff
+ float BIOME_FOG_TRANSITION_TIME
+ int WATER_FOG_DISTANCE
```

</details>

<details><summary>net.minecraft.client.renderer.GameRenderer</summary>

```diff
+ boolean DEPTH_BUFFER_DEBUG
+ float PROJECTION_Z_NEAR
+ int ITEM_ACTIVATION_ANIMATION_LENGTH
+ boolean isPanoramicMode()
```

</details>







<details><summary>net.minecraft.client.renderer.LightTexture</summary>

```diff
+ int FULL_BLOCK
+ int FULL_BRIGHT
+ int FULL_SKY
```

</details>















<details><summary>net.minecraft.client.renderer.RenderType</summary>

```diff
+ int BIG_BUFFER_SIZE
+ int BYTES_IN_INT
+ int MEDIUM_BUFFER_SIZE
+ int MEGABYTE
+ int SMALL_BUFFER_SIZE
+ int TRANSIENT_BUFFER_SIZE
```

</details>




<details><summary>net.minecraft.client.renderer.ShaderInstance</summary>

```diff
+ boolean ALWAYS_REAPPLY
+ String SHADER_INCLUDE_PATH
+ String SHADER_PATH
```

</details>




<details><summary>net.minecraft.client.renderer.blockentity.BeaconRenderer</summary>

```diff
+ int MAX_RENDER_Y
```

</details>

<details><summary>net.minecraft.client.renderer.blockentity.BellRenderer</summary>

```diff
+ String BELL_BODY
```

</details>




<details><summary>net.minecraft.client.renderer.blockentity.ChestRenderer</summary>

```diff
+ String BOTTOM
+ String LID
+ String LOCK
```

</details>



<details><summary>net.minecraft.client.renderer.blockentity.SignRenderer</summary>

```diff
+ int LINE_HEIGHT
+ int MAX_LINE_WIDTH
+ String STICK
```

</details>



<details><summary>net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer</summary>

```diff
+ float getOffsetDown()
+ float getOffsetUp()
- float getOffset()
```

</details>






<details><summary>net.minecraft.client.renderer.chunk.VisGraph</summary>

```diff
+ int INVALID_INDEX
+ int LEN
+ int MASK
+ int SIZE
+ int SIZE_IN_BITS
+ int X_SHIFT
+ int Y_SHIFT
+ int Z_SHIFT
```

</details>



<details><summary>net.minecraft.client.renderer.debug.BeeDebugRenderer</summary>

```diff
+ boolean SHOW_BLACKLISTS
+ boolean SHOW_FLOWER_POS_FOR_ALL_BEES
+ boolean SHOW_FLOWER_POS_FOR_SELECTED_BEE
+ boolean SHOW_GOAL_FOR_ALL_BEES
+ boolean SHOW_GOAL_FOR_SELECTED_BEE
+ boolean SHOW_HIVE_FOR_ALL_BEES
+ boolean SHOW_HIVE_FOR_SELECTED_BEE
+ boolean SHOW_HIVE_MEMBERS
+ boolean SHOW_NAME_FOR_ALL_BEES
+ boolean SHOW_NAME_FOR_SELECTED_BEE
+ boolean SHOW_PATH_FOR_ALL_BEES
+ boolean SHOW_PATH_FOR_SELECTED_BEE
+ boolean SHOW_TRAVEL_TICKS_FOR_ALL_BEES
+ boolean SHOW_TRAVEL_TICKS_FOR_SELECTED_BEE
+ float TEXT_SCALE
+ int GRAY
+ int GREEN
+ int HIVE_TIMEOUT
+ int MAX_RENDER_DIST_FOR_BEE_OVERLAY
+ int MAX_RENDER_DIST_FOR_HIVE_OVERLAY
+ int MAX_TARGETING_DIST
+ int ORANGE
+ int PINK
+ int RED
+ int WHITE
+ int YELLOW
```

</details>








<details><summary>net.minecraft.client.renderer.debug.GameTestDebugRenderer</summary>

```diff
+ float PADDING
```

</details>

<details><summary>net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer</summary>

```diff
+ int MAX_RENDER_DIST
```

</details>

<details><summary>net.minecraft.client.renderer.debug.HeightMapRenderer</summary>

```diff
+ float BOX_HEIGHT
+ int CHUNK_DIST
```

</details>

<details><summary>net.minecraft.client.renderer.debug.LightDebugRenderer</summary>

```diff
+ int MAX_RENDER_DIST
```

</details>

<details><summary>net.minecraft.client.renderer.debug.PathfindingRenderer</summary>

```diff
+ boolean SHOW_GROUND_LABELS
+ boolean SHOW_OPEN_CLOSED
+ boolean SHOW_OPEN_CLOSED_COST_MALUS
+ boolean SHOW_OPEN_CLOSED_NODE_TYPE_WITH_BOX
+ boolean SHOW_OPEN_CLOSED_NODE_TYPE_WITH_TEXT
+ float MAX_RENDER_DIST
+ float TEXT_SCALE
+ long TIMEOUT
```

</details>


<details><summary>net.minecraft.client.renderer.debug.VillageSectionsDebugRenderer</summary>

```diff
+ int MAX_RENDER_DIST_FOR_VILLAGE_SECTIONS
```

</details>

















<details><summary>net.minecraft.client.renderer.entity.EntityRenderers</summary>

```diff
+ String DEFAULT_PLAYER_MODEL
```

</details>









<details><summary>net.minecraft.client.resources.sounds.BeeSoundInstance</summary>

```diff
+ float PITCH_MIN
+ float VOLUME_MAX
+ float VOLUME_MIN
```

</details>


<details><summary>net.minecraft.client.resources.sounds.ElytraOnPlayerSoundInstance</summary>

```diff
+ int DELAY
```

</details>

<details><summary>net.minecraft.client.resources.sounds.GuardianAttackSoundInstance</summary>

```diff
+ float PITCH_MIN
+ float PITCH_SCALE
+ float VOLUME_MIN
+ float VOLUME_SCALE
```

</details>

<details><summary>net.minecraft.client.resources.sounds.RidingMinecartSoundInstance</summary>

```diff
+ float VOLUME_MAX
+ float VOLUME_MIN
```

</details>






<details><summary>net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance</summary>

```diff
+ int FADE_DURATION
```

</details>





<details><summary>net.minecraft.client.searchtree.SuffixArray</summary>

```diff
+ int END_OF_DATA
+ int END_OF_TEXT_MARKER
```

</details>


<details><summary>net.minecraft.client.server.IntegratedServer</summary>

```diff
+ int CLIENT_VIEW_DISTANCE_OFFSET
```

</details>








<details><summary>net.minecraft.commands.synchronization.brigadier.BrigadierArgumentSerializers</summary>

```diff
+ byte NUMBER_FLAG_MAX
+ byte NUMBER_FLAG_MIN
```

</details>







<details><summary>net.minecraft.core.BlockPos</summary>

```diff
+ int Y_OFFSET
```

</details>










<details><summary>net.minecraft.core.FrontAndTop</summary>

```diff
+ void lambda$static$0(Int2ObjectOpenHashMap)
```

</details>





<details><summary>net.minecraft.core.Registry</summary>

```diff
+ Registry HEIGHT_PROVIDER_TYPES
+ Registry INT_PROVIDER_TYPES
+ ResourceKey HEIGHT_PROVIDER_TYPE_REGISTRY
+ ResourceKey INT_PROVIDER_TYPE_REGISTRY
+ BlockPlacerType lambda$static$45()
+ BlockStateProviderType lambda$static$44()
+ Codec lambda$static$50()
+ Codec lambda$static$51()
+ DataResult lambda$decode$56(Number)
+ DataResult lambda$decode$58(Pair)
+ Feature lambda$static$40()
+ FeatureDecorator lambda$static$43()
+ FeatureSizeType lambda$static$49()
+ FloatProviderType lambda$static$35()
+ FoliagePlacerType lambda$static$46()
+ HeightProviderType lambda$static$37()
+ IntProviderType lambda$static$36()
+ Object lambda$keys$59(ResourceLocation)
+ Pair lambda$decode$57(Object)
+ StructureFeature lambda$static$41()
+ StructurePieceType lambda$static$42()
+ StructurePoolElementType lambda$static$53()
+ StructureProcessorType lambda$static$52()
+ SurfaceBuilder lambda$static$38()
+ TreeDecoratorType lambda$static$48()
+ TrunkPlacerType lambda$static$47()
+ void lambda$checkRegistry$55(WritableRegistry)
+ void lambda$static$54(Supplier)
+ WorldCarver lambda$static$39()
- BlockPlacerType lambda$static$43()
- BlockStateProviderType lambda$static$42()
- Codec lambda$static$48()
- Codec lambda$static$49()
- DataResult lambda$decode$54(Number)
- DataResult lambda$decode$56(Pair)
- Feature lambda$static$38()
- FeatureDecorator lambda$static$41()
- FeatureSizeType lambda$static$47()
- FloatProviderType lambda$static$36()
- FoliagePlacerType lambda$static$44()
- Object lambda$keys$57(ResourceLocation)
- Pair lambda$decode$55(Object)
- StructureFeature lambda$static$39()
- StructurePieceType lambda$static$40()
- StructurePoolElementType lambda$static$51()
- StructureProcessorType lambda$static$50()
- SurfaceBuilder lambda$static$35()
- TreeDecoratorType lambda$static$46()
- TrunkPlacerType lambda$static$45()
- void lambda$checkRegistry$53(WritableRegistry)
- void lambda$static$52(Supplier)
- WorldCarver lambda$static$37()
```

</details>



























<details><summary>net.minecraft.core.particles.DustParticleOptionsBase</summary>

```diff
+ float MAX_SCALE
+ float MIN_SCALE
```

</details>







<details><summary>net.minecraft.data.BlockFamilies</summary>

```diff
+ String RECIPE_GROUP_PREFIX_WOODEN
+ String RECIPE_UNLOCKED_BY_HAS_PLANKS
```

</details>


























































<details><summary>net.minecraft.data.worldgen.Carvers</summary>

```diff
+ ConfiguredWorldCarver OLD_CANYON
+ ConfiguredWorldCarver OLD_CAVE
+ ConfiguredWorldCarver OLD_OCEAN_CAVE
```

</details>

<details><summary>net.minecraft.data.worldgen.Features</summary>

```diff
+ ConfiguredFeature OLD_FOSSIL
+ ConfiguredFeature OLD_GLOW_LICHEN
+ ConfiguredFeature OLD_ORE_ANDESITE
+ ConfiguredFeature OLD_ORE_COAL
+ ConfiguredFeature OLD_ORE_COPPER
+ ConfiguredFeature OLD_ORE_DIAMOND
+ ConfiguredFeature OLD_ORE_DIORITE
+ ConfiguredFeature OLD_ORE_DIRT
+ ConfiguredFeature OLD_ORE_EMERALD
+ ConfiguredFeature OLD_ORE_GOLD
+ ConfiguredFeature OLD_ORE_GRANITE
+ ConfiguredFeature OLD_ORE_GRAVEL
+ ConfiguredFeature OLD_ORE_INFESTED
+ ConfiguredFeature OLD_ORE_IRON
+ ConfiguredFeature OLD_ORE_LAPIS
+ ConfiguredFeature OLD_ORE_REDSTONE
+ ConfiguredFeature OLD_SPRING_WATER
+ ConfiguredFeature OLD_VINES
+ ConfiguredFeature ORE_DEEPSLATE
+ ConfiguredFeature ORE_DIAMOND_LARGE
+ ConfiguredFeature RARE_DRIPSTONE_CLUSTER_FEATURE
+ ConfiguredFeature RARE_SMALL_DRIPSTONE_FEATURE
+ SimpleWeightedRandomList$Builder access$000()
+ SimpleWeightedRandomList$Builder weightedBlockStateBuilder()
```

</details>












<details><summary>net.minecraft.gametest.framework.GameTestBatch</summary>

```diff
+ String DEFAULT_BATCH_NAME
```

</details>





<details><summary>net.minecraft.gametest.framework.GameTestRunner</summary>

```diff
+ int DEFAULT_TESTS_PER_ROW
+ int MAX_TESTS_PER_BATCH
+ int PADDING_AROUND_EACH_STRUCTURE
+ int SPACE_BETWEEN_COLUMNS
+ int SPACE_BETWEEN_ROWS
```

</details>

<details><summary>net.minecraft.gametest.framework.GameTestSequence$Condition</summary>

```diff
+ long NOT_TRIGGERED
```

</details>




<details><summary>net.minecraft.gametest.framework.MultipleTestTracker</summary>

```diff
+ char FAILED_OPTIONAL_TEST_CHAR
+ char FAILED_REQUIRED_TEST_CHAR
+ char NOT_STARTED_TEST_CHAR
+ char ONGOING_TEST_CHAR
+ char SUCCESSFUL_TEST_CHAR
```

</details>








<details><summary>net.minecraft.nbt.ByteArrayTag</summary>

```diff
+ int SELF_SIZE_IN_BITS
```

</details>

<details><summary>net.minecraft.nbt.ByteTag</summary>

```diff
+ int SELF_SIZE_IN_BITS
```

</details>


<details><summary>net.minecraft.nbt.CompoundTag</summary>

```diff
+ int MAP_ENTRY_SIZE_IN_BITS
+ int SELF_SIZE_IN_BITS
```

</details>

<details><summary>net.minecraft.nbt.DoubleTag</summary>

```diff
+ int SELF_SIZE_IN_BITS
```

</details>

<details><summary>net.minecraft.nbt.EndTag</summary>

```diff
+ int SELF_SIZE_IN_BITS
```

</details>

<details><summary>net.minecraft.nbt.FloatTag</summary>

```diff
+ int SELF_SIZE_IN_BITS
```

</details>

<details><summary>net.minecraft.nbt.IntArrayTag</summary>

```diff
+ int SELF_SIZE_IN_BITS
```

</details>

<details><summary>net.minecraft.nbt.IntTag</summary>

```diff
+ int SELF_SIZE_IN_BITS
```

</details>

<details><summary>net.minecraft.nbt.IntTag$Cache</summary>

```diff
+ int HIGH
+ int LOW
```

</details>







<details><summary>net.minecraft.nbt.NbtUtils</summary>

```diff
+ char KEY_VALUE_SEPARATOR
+ char PROPERTIES_END
+ char PROPERTIES_START
+ int INDENT
+ int NOT_FOUND
+ String ELEMENT_SEPARATOR
+ String SNBT_DATA_TAG
```

</details>

<details><summary>net.minecraft.nbt.ShortTag</summary>

```diff
+ int SELF_SIZE_IN_BITS
```

</details>

<details><summary>net.minecraft.nbt.ShortTag$Cache</summary>

```diff
+ int HIGH
+ int LOW
```

</details>

<details><summary>net.minecraft.nbt.StringTag</summary>

```diff
+ char DOUBLE_QUOTE
+ char ESCAPE
+ char NOT_SET
+ char SINGLE_QUOTE
+ int SELF_SIZE_IN_BITS
```

</details>


<details><summary>net.minecraft.nbt.TagParser</summary>

```diff
+ char ELEMENT_SEPARATOR
+ char LIST_CLOSE
+ char LIST_OPEN
+ char NAME_VALUE_SEPARATOR
+ char STRUCT_CLOSE
+ char STRUCT_OPEN
```

</details>





<details><summary>net.minecraft.network.CompressionDecoder</summary>

```diff
+ int MAXIMUM_DECOMPRESSED_LENGTH
```

</details>

<details><summary>net.minecraft.network.Connection</summary>

```diff
+ float AVERAGE_PACKETS_SMOOTHING
```

</details>


<details><summary>net.minecraft.network.ConnectionProtocol</summary>

```diff
+ int MAX_PROTOCOL_ID
+ int MIN_PROTOCOL_ID
```

</details>


<details><summary>net.minecraft.network.FriendlyByteBuf</summary>

```diff
+ int DEFAULT_NBT_QUOTA
+ int MAX_COMPONENT_STRING_LENGTH
+ int MAX_VARINT_SIZE
+ int MAX_VARLONG_SIZE
+ short MAX_STRING_LENGTH
```

</details>















<details><summary>net.minecraft.network.chat.NbtComponent</summary>

```diff
+ String SEPARATOR
```

</details>


<details><summary>net.minecraft.network.chat.ScoreComponent</summary>

```diff
+ String SCORER_PLACEHOLDER
```

</details>



<details><summary>net.minecraft.network.chat.TextColor</summary>

```diff
+ String CUSTOM_COLOR_PREFIX
```

</details>





<details><summary>net.minecraft.network.protocol.game.ClientboundAddEntityPacket</summary>

```diff
+ double LIMIT
+ double MAGICAL_QUANTIZATION
```

</details>



<details><summary>net.minecraft.network.protocol.game.ClientboundAnimatePacket</summary>

```diff
+ int CRITICAL_HIT
+ int HURT
+ int MAGIC_CRITICAL_HIT
+ int SWING_MAIN_HAND
+ int SWING_OFF_HAND
+ int WAKE_UP
```

</details>


<details><summary>net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket</summary>

```diff
+ int TYPE_ADV_COMMAND
+ int TYPE_BANNER
+ int TYPE_BEACON
+ int TYPE_BED
+ int TYPE_BEEHIVE
+ int TYPE_CAMPFIRE
+ int TYPE_CONDUIT
+ int TYPE_END_GATEWAY
+ int TYPE_JIGSAW
+ int TYPE_MOB_SPAWNER
+ int TYPE_SIGN
+ int TYPE_SKULL
+ int TYPE_STRUCT_COMMAND
```

</details>













<details><summary>net.minecraft.network.protocol.game.ClientboundCustomSoundPacket</summary>

```diff
+ float LOCATION_ACCURACY
```

</details>





<details><summary>net.minecraft.network.protocol.game.ClientboundLevelChunkPacket</summary>

```diff
+ int TWO_MEGABYTES
```

</details>


<details><summary>net.minecraft.network.protocol.game.ClientboundLoginPacket</summary>

```diff
+ int HARDCORE_FLAG
```

</details>






<details><summary>net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket</summary>

```diff
+ int FLAG_CAN_FLY
+ int FLAG_FLYING
+ int FLAG_INSTABUILD
+ int FLAG_INVULNERABLE
```

</details>










<details><summary>net.minecraft.network.protocol.game.ClientboundResourcePackPacket</summary>

```diff
+ int MAX_HASH_LENGTH
```

</details>










<details><summary>net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket</summary>

```diff
+ byte CONTINUE_MASK
```

</details>







<details><summary>net.minecraft.network.protocol.game.ClientboundSoundPacket</summary>

```diff
+ float LOCATION_ACCURACY
```

</details>









<details><summary>net.minecraft.network.protocol.game.ServerboundChatPacket</summary>

```diff
+ int MAX_MESSAGE_LENGTH
```

</details>




<details><summary>net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket</summary>

```diff
+ int MAX_PAYLOAD_SIZE
```

</details>











<details><summary>net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket</summary>

```diff
+ int FLAG_FLYING
```

</details>








<details><summary>net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket</summary>

```diff
+ int FLAG_AUTOMATIC
+ int FLAG_CONDITIONAL
+ int FLAG_TRACK_OUTPUT
```

</details>


<details><summary>net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket</summary>

```diff
+ int FLAG_IGNORE_ENTITIES
+ int FLAG_SHOW_AIR
+ int FLAG_SHOW_BOUNDING_BOX
```

</details>
































<details><summary>net.minecraft.util.FrameTimer</summary>

```diff
+ int LOGGING_LENGTH
```

</details>



<details><summary>net.minecraft.util.Mth</summary>

```diff
+ double ONE_SIXTH
+ float BIG_ENOUGH_FLOAT
+ float DEG_TO_RAD
+ float EPSILON
+ float HALF_PI
+ float PI
+ float RAD_TO_DEG
+ float SIN_SCALE
+ float TWO_PI
+ int BIG_ENOUGH_INT
+ int FRAC_EXP
+ int LUT_SIZE
+ long UUID_VARIANT
+ long UUID_VARIANT_2
+ long UUID_VERSION
+ long UUID_VERSION_TYPE_4
```

</details>



<details><summary>net.minecraft.util.SortedArraySet</summary>

```diff
+ int DEFAULT_INITIAL_CAPACITY
```

</details>












<details><summary>net.minecraft.world.DifficultyInstance</summary>

```diff
+ float DIFFICULTY_TIME_GLOBAL_OFFSET
+ float MAX_DIFFICULTY_TIME_GLOBAL
+ float MAX_DIFFICULTY_TIME_LOCAL
```

</details>


<details><summary>net.minecraft.world.LockCode</summary>

```diff
+ String TAG_LOCK
```

</details>






<details><summary>net.minecraft.world.damagesource.CombatRules</summary>

```diff
+ float ARMOR_PROTECTION_DIVIDER
+ float BASE_ARMOR_TOUGHNESS
+ float MAX_ARMOR
+ float MIN_ARMOR_RATIO
+ int NUM_ARMOR_ITEMS
```

</details>










<details><summary>net.minecraft.world.entity.Entity</summary>

```diff
+ double DELTA_AFFECTED_BY_BLOCKS_BELOW
+ double LAVA_FAST_FLOW_SCALE
+ double LAVA_SLOW_FLOW_SCALE
+ double WATER_FLOW_SCALE
+ float BREATHING_DISTANCE_BELOW_EYES
+ float DEFAULT_BB_HEIGHT
+ float DEFAULT_BB_WIDTH
+ int BASE_TICKS_REQUIRED_TO_FREEZE
+ int BOARDING_COOLDOWN
+ int FLAG_FALL_FLYING
+ int FLAG_GLOWING
+ int FLAG_INVISIBLE
+ int FLAG_ONFIRE
+ int FLAG_SHIFT_KEY_DOWN
+ int FLAG_SPRINTING
+ int FLAG_SWIMMING
+ int FREEZE_HURT_FREQUENCY
+ int MAX_ENTITY_TAG_COUNT
+ int TOTAL_AIR_SUPPLY
+ String ID_TAG
+ String PASSENGERS_TAG
+ String UUID_TAG
```

</details>



<details><summary>net.minecraft.world.entity.EntityEvent</summary>

```diff
+ byte ARMORSTAND_WOBBLE
+ byte ATTACK_BLOCKED
+ byte BAD_OMEN_TRIGGERED
+ byte BURNED
+ byte CANCEL_SHAKE_WETNESS
+ byte CHEST_BREAK
+ byte DEATH
+ byte DOLPHIN_LOOKING_FOR_TREASURE
+ byte DROWNED
+ byte EAT_GRASS
+ byte FEET_BREAK
+ byte FIREWORKS_EXPLODE
+ byte FISHING_ROD_REEL_IN
+ byte FOX_EAT
+ byte FROZEN
+ byte FULL_DEBUG_INFO
+ byte GUARDIAN_ATTACK_SOUND
+ byte HEAD_BREAK
+ byte HONEY_JUMP
+ byte HONEY_SLIDE
+ byte HURT
+ byte IN_LOVE_HEARTS
+ byte JUMP
+ byte LEGS_BREAK
+ byte LOVE_HEARTS
+ byte MAINHAND_BREAK
+ byte OFFER_FLOWER
+ byte OFFHAND_BREAK
+ byte PERMISSION_LEVEL_ADMINS
+ byte PERMISSION_LEVEL_ALL
+ byte PERMISSION_LEVEL_GAMEMASTERS
+ byte PERMISSION_LEVEL_MODERATORS
+ byte PERMISSION_LEVEL_OWNERS
+ byte POKED
+ byte RAVAGER_STUNNED
+ byte REDUCED_DEBUG_INFO
+ byte SHAKE_WETNESS
+ byte SHIELD_DISABLED
+ byte SILVERFISH_MERGE_ANIM
+ byte SQUID_ANIM_SYNCH
+ byte START_ATTACKING
+ byte STOP_ATTACKING
+ byte STOP_OFFER_FLOWER
+ byte SWAP_HANDS
+ byte TALISMAN_ACTIVATE
+ byte TAMING_FAILED
+ byte TAMING_SUCCEEDED
+ byte TELEPORT
+ byte THORNED
+ byte TRUSTING_FAILED
+ byte TRUSTING_SUCCEEDED
+ byte USE_ITEM_COMPLETE
+ byte VILLAGER_ANGRY
+ byte VILLAGER_HAPPY
+ byte VILLAGER_SWEAT
+ byte WITCH_HAT_MAGIC
+ byte ZOMBIE_CONVERTING
```

</details>








<details><summary>net.minecraft.world.entity.LivingEntity</summary>

```diff
+ boolean discardFriction
+ double DEFAULT_BASE_GRAVITY
+ double MIN_MOVEMENT_DISTANCE
+ float DEFAULT_EYE_HEIGHT
+ float EXTRA_RENDER_CULLING_SIZE_WITH_BIG_HAT
+ int ARMOR_SLOT_OFFSET
+ int ARMOR_SLOTS
+ int DAMAGE_SOURCE_TIMEOUT
+ int DEATH_DURATION
+ int EQUIPMENT_SLOT_OFFSET
+ int FREE_FALL_EVENTS_PER_ELYTRA_BREAK
+ int HAND_SLOTS
+ int LIVING_ENTITY_FLAG_IS_USING
+ int LIVING_ENTITY_FLAG_OFF_HAND
+ int LIVING_ENTITY_FLAG_SPIN_ATTACK
+ int PLAYER_HURT_EXPERIENCE_TIME
+ int SWING_DURATION
+ int TICKS_PER_ELYTRA_FREE_FALL_EVENT
+ int USE_ITEM_INTERVAL
+ int WAIT_TICKS_BEFORE_ITEM_USE_EFFECTS
+ boolean shouldDiscardFriction()
+ void setDiscardFriction(boolean)
```

</details>

<details><summary>net.minecraft.world.entity.Mob</summary>

```diff
+ float MAX_ENCHANTED_ARMOR_CHANCE
+ float MAX_ENCHANTED_WEAPON_CHANCE
+ float MAX_PICKUP_LOOT_CHANCE
+ float MAX_WEARING_ARMOR_CHANCE
+ int MOB_FLAG_AGGRESSIVE
+ int MOB_FLAG_LEFTHANDED
+ int MOB_FLAG_NO_AI
+ int PICKUP_REACH
+ String LEASH_TAG
```

</details>

<details><summary>net.minecraft.world.entity.MobCategory</summary>

```diff
+ MobCategory UNDERGROUND_WATER_CREATURE
```

</details>


<details><summary>net.minecraft.world.entity.NeutralMob</summary>

```diff
+ String TAG_ANGER_TIME
+ String TAG_ANGRY_AT
```

</details>










<details><summary>net.minecraft.world.entity.ai.Brain</summary>

```diff
+ int SCHEDULE_UPDATE_DELAY
```

</details>


<details><summary>net.minecraft.world.entity.ai.attributes.Attribute</summary>

```diff
+ int MAX_NAME_LENGTH
```

</details>






<details><summary>net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry</summary>

```diff
+ int MAX_INTERVAL_INCREASE
+ int MAX_RETRY_PATHFINDING_INTERVAL
+ int MIN_INTERVAL_INCREASE
```

</details>


<details><summary>net.minecraft.world.entity.ai.behavior.Mount</summary>

```diff
+ int CLOSE_ENOUGH_TO_START_RIDING_DIST
```

</details>

<details><summary>net.minecraft.world.entity.ai.behavior.MoveToTargetSink</summary>

```diff
+ int MAX_COOLDOWN_BEFORE_RETRYING
```

</details>


<details><summary>net.minecraft.world.entity.ai.behavior.RandomStroll</summary>

```diff
+ int MAX_XZ_DIST
+ int MAX_Y_DIST
```

</details>




<details><summary>net.minecraft.world.entity.ai.behavior.RunSometimes</summary>

```diff
+ UniformInt interval
- IntRange interval
+ void <init>(UniformInt)
+ void <init>(UniformInt)
- void <init>(IntRange)
- void <init>(IntRange)
```

</details>





<details><summary>net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer</summary>

```diff
+ int MAX_LOOK_TIME
+ int STARTING_LOOK_TIME
```

</details>

<details><summary>net.minecraft.world.entity.ai.behavior.SocializeAtBell</summary>

```diff
+ float SPEED_MODIFIER
```

</details>






<details><summary>net.minecraft.world.entity.ai.behavior.UseBonemeal</summary>

```diff
+ int BONEMEALING_DURATION
```

</details>


<details><summary>net.minecraft.world.entity.ai.behavior.VillagerCalmDown</summary>

```diff
+ int SAFE_DISTANCE_FROM_DANGER
```

</details>

<details><summary>net.minecraft.world.entity.ai.behavior.VillagerMakeLove</summary>

```diff
+ float SPEED_MODIFIER
+ int INTERACT_DIST_SQR
```

</details>


<details><summary>net.minecraft.world.entity.ai.behavior.WorkAtPoi</summary>

```diff
+ double DISTANCE
+ int CHECK_COOLDOWN
```

</details>




<details><summary>net.minecraft.world.entity.ai.control.MoveControl</summary>

```diff
+ float MIN_SPEED
+ float MIN_SPEED_SQR
+ int MAX_TURN
```

</details>

<details><summary>net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl</summary>

```diff
+ int HEAD_TILT_X
+ int HEAD_TILT_Y
```

</details>



<details><summary>net.minecraft.world.entity.ai.goal.BreakDoorGoal</summary>

```diff
+ int DEFAULT_DOOR_BREAK_TIME
```

</details>







<details><summary>net.minecraft.world.entity.ai.goal.FollowParentGoal</summary>

```diff
+ int DONT_FOLLOW_IF_CLOSER_THAN
+ int HORIZONTAL_SCAN_RANGE
+ int VERTICAL_SCAN_RANGE
```

</details>



<details><summary>net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal</summary>

```diff
+ int POI_SECTION_SCAN_RADIUS
+ int RANDOM_POS_XY_DISTANCE
+ int RANDOM_POS_Y_DISTANCE
+ int VILLAGER_SCAN_RADIUS
```

</details>




<details><summary>net.minecraft.world.entity.ai.goal.MeleeAttackGoal</summary>

```diff
+ long COOLDOWN_BETWEEN_CAN_USE_CHECKS
```

</details>

<details><summary>net.minecraft.world.entity.ai.goal.RandomStrollGoal</summary>

```diff
+ int DEFAULT_INTERVAL
```

</details>


<details><summary>net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal</summary>

```diff
+ UniformInt PATHFINDING_DELAY_RANGE
- IntRange PATHFINDING_DELAY_RANGE
```

</details>

<details><summary>net.minecraft.world.entity.ai.goal.RemoveBlockGoal</summary>

```diff
+ int WAIT_AFTER_BLOCK_FOUND
```

</details>


<details><summary>net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal</summary>

```diff
+ int DISTANCE_THRESHOLD
```

</details>

<details><summary>net.minecraft.world.entity.ai.sensing.NearestBedSensor</summary>

```diff
+ int BATCH_SIZE
+ int CACHE_TIMEOUT
+ int RATE
```

</details>


<details><summary>net.minecraft.world.entity.animal.horse.AbstractChestedHorse</summary>

```diff
+ int INV_CHEST_COUNT
```

</details>

<details><summary>net.minecraft.world.entity.animal.horse.AbstractHorse</summary>

```diff
+ int CHEST_SLOT_OFFSET
+ int EQUIPMENT_SLOT_OFFSET
+ int FLAG_BRED
+ int FLAG_EATING
+ int FLAG_OPEN_MOUTH
+ int FLAG_SADDLE
+ int FLAG_STANDING
+ int FLAG_TAME
+ int INV_BASE_COUNT
+ int INV_SLOT_ARMOR
+ int INV_SLOT_SADDLE
+ int INVENTORY_SLOT_OFFSET
```

</details>






<details><summary>net.minecraft.world.entity.animal.horse.SkeletonHorse</summary>

```diff
+ int TRAP_MAX_LIFE
```

</details>





<details><summary>net.minecraft.world.entity.boss.enderdragon.EnderDragon</summary>

```diff
+ float SITTING_ALLOWED_DAMAGE_PERCENTAGE
+ int GROWL_INTERVAL_MAX
+ int GROWL_INTERVAL_MIN
```

</details>


<details><summary>net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase</summary>

```diff
+ int CHARGE_RECOVERY_TIME
```

</details>




<details><summary>net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase</summary>

```diff
+ int FLAME_DURATION
+ int SITTING_FLAME_ATTACKS_COUNT
+ int WARMUP_TIME
```

</details>

<details><summary>net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase</summary>

```diff
+ int FIREBALL_CHARGE_AMOUNT
```

</details>



<details><summary>net.minecraft.world.entity.boss.wither.WitherBoss</summary>

```diff
+ int INVULNERABLE_TICKS
```

</details>




<details><summary>net.minecraft.world.entity.decoration.ItemFrame</summary>

```diff
+ int NUM_ROTATIONS
```

</details>




<details><summary>net.minecraft.world.entity.item.ItemEntity</summary>

```diff
+ int INFINITE_LIFETIME
+ int INFINITE_PICKUP_DELAY
+ int LIFETIME
```

</details>



<details><summary>net.minecraft.world.entity.monster.AbstractSkeleton</summary>

```diff
+ boolean isShaking()
```

</details>










<details><summary>net.minecraft.world.entity.monster.Endermite</summary>

```diff
+ int MAX_LIFE
```

</details>







<details><summary>net.minecraft.world.entity.monster.Guardian</summary>

```diff
+ int ATTACK_TIME
```

</details>






<details><summary>net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal</summary>

```diff
+ int NAVIGATION_FAILED_COOLDOWN
```

</details>






<details><summary>net.minecraft.world.entity.monster.Pillager</summary>

```diff
+ float CROSSBOW_POWER
+ int INVENTORY_SIZE
+ int SLOT_OFFSET
```

</details>

<details><summary>net.minecraft.world.entity.monster.Ravager</summary>

```diff
+ double ATTACK_MOVEMENT_SPEED
+ double BASE_MOVEMENT_SPEED
+ double STUNNED_COLOR_BLUE
+ double STUNNED_COLOR_GREEN
+ double STUNNED_COLOR_RED
+ int ATTACK_DURATION
+ int STUN_DURATION
+ int STUNNED_COLOR
```

</details>








<details><summary>net.minecraft.world.entity.monster.Slime</summary>

```diff
+ int MAX_SIZE
+ int MIN_SIZE
```

</details>





<details><summary>net.minecraft.world.entity.monster.Spider</summary>

```diff
+ float SPIDER_SPECIAL_EFFECT_CHANCE
```

</details>







<details><summary>net.minecraft.world.entity.monster.Vindicator</summary>

```diff
+ String TAG_JOHNNY
```

</details>



<details><summary>net.minecraft.world.entity.monster.Zoglin</summary>

```diff
+ float BABY_ATTACK_DAMAGE
+ float KNOCKBACK_RESISTANCE
+ float MOVEMENT_SPEED_WHEN_FIGHTING
+ float SPEED_MULTIPLIER_WHEN_IDLING
+ int ATTACK_DAMAGE
+ int ATTACK_DURATION
+ int ATTACK_INTERVAL
+ int ATTACK_KNOCKBACK
+ int BABY_ATTACK_INTERVAL
+ int MAX_HEALTH
```

</details>


<details><summary>net.minecraft.world.entity.monster.ZombieVillager</summary>

```diff
+ int MAX_SPECIAL_BLOCKS_COUNT
+ int SPECIAL_BLOCK_RADIUS
+ int VILLAGER_CONVERSION_WAIT_MAX
+ int VILLAGER_CONVERSION_WAIT_MIN
```

</details>

<details><summary>net.minecraft.world.entity.monster.hoglin.Hoglin</summary>

```diff
+ float BABY_ATTACK_DAMAGE
+ float KNOCKBACK_RESISTANCE
+ float MOVEMENT_SPEED_WHEN_FIGHTING
+ float PROBABILITY_OF_SPAWNING_AS_BABY
+ int ATTACK_DAMAGE
+ int ATTACK_KNOCKBACK
+ int CONVERSION_TIME
+ int MAX_HEALTH
```

</details>

<details><summary>net.minecraft.world.entity.monster.hoglin.HoglinBase</summary>

```diff
+ int ATTACK_ANIMATION_DURATION
```

</details>


<details><summary>net.minecraft.world.entity.monster.piglin.Piglin</summary>

```diff
+ double PROBABILITY_OF_SPAWNING_WITH_CROSSBOW_INSTEAD_OF_SWORD
+ float BABY_EYE_HEIGHT_ADJUSTMENT
+ float CHANCE_OF_WEARING_EACH_ARMOUR_ITEM
+ float CROSSBOW_POWER
+ float MOVEMENT_SPEED_WHEN_FIGHTING
+ float PROBABILITY_OF_SPAWNING_AS_BABY
+ int ATTACK_DAMAGE
+ int MAX_HEALTH
+ int MAX_PASSENGERS_ON_ONE_HOGLIN
```

</details>


<details><summary>net.minecraft.world.entity.monster.piglin.PiglinBruteAi</summary>

```diff
+ double ACTIVITY_SOUND_LIKELIHOOD_PER_TICK
+ double TARGETING_RANGE
+ float SPEED_MULTIPLIER_WHEN_IDLING
+ int ANGER_DURATION
+ int HOME_CLOSE_ENOUGH_DISTANCE
+ int HOME_STROLL_AROUND_DISTANCE
+ int HOME_TOO_FAR_DISTANCE
+ int INTERACTION_RANGE
+ int MAX_LOOK_DIST
+ int MELEE_ATTACK_COOLDOWN
```

</details>




<details><summary>net.minecraft.world.entity.npc.AbstractVillager</summary>

```diff
+ int VILLAGER_INVENTORY_SIZE
+ int VILLAGER_SLOT_OFFSET
```

</details>



<details><summary>net.minecraft.world.entity.npc.VillagerData</summary>

```diff
+ int MAX_VILLAGER_LEVEL
+ int MIN_VILLAGER_LEVEL
```

</details>








<details><summary>net.minecraft.world.entity.npc.WanderingTrader</summary>

```diff
+ int NUMBER_OF_TRADE_OFFERS
```

</details>

<details><summary>net.minecraft.world.entity.npc.WanderingTraderSpawner</summary>

```diff
+ int DEFAULT_SPAWN_DELAY
+ int DEFAULT_TICK_DELAY
+ int MAX_SPAWN_CHANCE
+ int MIN_SPAWN_CHANCE
+ int NUMBER_OF_SPAWN_ATTEMPTS
+ int SPAWN_CHANCE_INCREASE
+ int SPAWN_ONE_IN_X_CHANCE
```

</details>



<details><summary>net.minecraft.world.entity.player.Player</summary>

```diff
+ float CROUCH_BB_HEIGHT
+ float DEFAULT_EYE_HEIGHT
+ float SWIMMING_BB_HEIGHT
+ float SWIMMING_BB_WIDTH
+ int ENDER_SLOT_OFFSET
+ int FLY_ACHIEVEMENT_SPEED
+ int MAX_HEALTH
+ int MAX_NAME_LENGTH
+ int SLEEP_DURATION
+ int WAKE_UP_DURATION
+ String UUID_PREFIX_OFFLINE_PLAYER
```

</details>


<details><summary>net.minecraft.world.entity.player.StackedContents</summary>

```diff
+ int EMPTY
```

</details>




<details><summary>net.minecraft.world.entity.projectile.DragonFireball</summary>

```diff
+ float SPLASH_RANGE
```

</details>







<details><summary>net.minecraft.world.entity.projectile.ShulkerBullet</summary>

```diff
+ double SPEED
```

</details>











<details><summary>net.minecraft.world.entity.raid.Raids</summary>

```diff
+ String RAID_FILE_ID
```

</details>

<details><summary>net.minecraft.world.entity.schedule.Activity</summary>

```diff
+ Activity LONG_JUMP
```

</details>

<details><summary>net.minecraft.world.entity.schedule.Schedule</summary>

```diff
+ int TOTAL_WORK_TIME
+ int WORK_START_TIME
```

</details>





<details><summary>net.minecraft.world.entity.vehicle.Boat</summary>

```diff
+ double PADDLE_SOUND_TIME
+ double PADDLE_SPEED
+ int BUBBLE_TIME
+ int PADDLE_LEFT
+ int PADDLE_RIGHT
+ int TIME_TO_EJECT
```

</details>





<details><summary>net.minecraft.world.entity.vehicle.MinecartHopper</summary>

```diff
+ int MOVE_ITEM_SPEED
```

</details>





<details><summary>net.minecraft.world.food.Foods</summary>

```diff
+ FoodProperties$Builder stew(int)
- FoodProperties stew(int)
```

</details>

<details><summary>net.minecraft.world.inventory.AbstractContainerMenu</summary>

```diff
+ int CARRIED_SLOT_SIZE
+ int QUICKCRAFT_HEADER_CONTINUE
+ int QUICKCRAFT_HEADER_END
+ int QUICKCRAFT_HEADER_START
+ int QUICKCRAFT_TYPE_CHARITABLE
+ int QUICKCRAFT_TYPE_CLONE
+ int QUICKCRAFT_TYPE_GREEDY
+ int SLOT_CLICKED_OUTSIDE
```

</details>

<details><summary>net.minecraft.world.inventory.AbstractFurnaceMenu</summary>

```diff
+ int DATA_COUNT
+ int FUEL_SLOT
+ int INGREDIENT_SLOT
+ int INV_SLOT_END
+ int INV_SLOT_START
+ int RESULT_SLOT
+ int SLOT_COUNT
+ int USE_ROW_SLOT_END
+ int USE_ROW_SLOT_START
```

</details>
















<details><summary>net.minecraft.world.inventory.DispenserMenu</summary>

```diff
+ int INV_SLOT_END
+ int INV_SLOT_START
+ int SLOT_COUNT
+ int USE_ROW_SLOT_END
+ int USE_ROW_SLOT_START
```

</details>




<details><summary>net.minecraft.world.inventory.GrindstoneMenu</summary>

```diff
+ int ADDITIONAL_SLOT
+ int INPUT_SLOT
+ int INV_SLOT_END
+ int INV_SLOT_START
+ int MAX_NAME_LENGTH
+ int RESULT_SLOT
+ int USE_ROW_SLOT_END
+ int USE_ROW_SLOT_START
```

</details>






<details><summary>net.minecraft.world.inventory.ItemCombinerMenu</summary>

```diff
+ int ADDITIONAL_SLOT
+ int INPUT_SLOT
+ int INV_SLOT_END
+ int INV_SLOT_START
+ int RESULT_SLOT
+ int USE_ROW_SLOT_END
+ int USE_ROW_SLOT_START
```

</details>








<details><summary>net.minecraft.world.inventory.MerchantMenu</summary>

```diff
+ int BUYSLOT_X
+ int INV_SLOT_END
+ int INV_SLOT_START
+ int PAYMENT1_SLOT
+ int PAYMENT2_SLOT
+ int RESULT_SLOT
+ int ROW_Y
+ int SELLSLOT1_X
+ int SELLSLOT2_X
+ int USE_ROW_SLOT_END
+ int USE_ROW_SLOT_START
```

</details>




<details><summary>net.minecraft.world.inventory.ShulkerBoxMenu</summary>

```diff
+ int CONTAINER_SIZE
```

</details>











<details><summary>net.minecraft.world.item.BannerItem</summary>

```diff
+ String PATTERN_PREFIX
```

</details>




<details><summary>net.minecraft.world.item.BowItem</summary>

```diff
+ int DEFAULT_RANGE
+ int MAX_DRAW_DURATION
```

</details>










<details><summary>net.minecraft.world.item.CrossbowItem</summary>

```diff
+ float ARROW_POWER
+ float FIREWORK_POWER
+ float MID_SOUND_PERCENT
+ float START_SOUND_PERCENT
+ int DEFAULT_RANGE
+ int MAX_CHARGE_DURATION
+ String TAG_CHARGED
+ String TAG_CHARGED_PROJECTILES
```

</details>










<details><summary>net.minecraft.world.item.FireworkRocketItem</summary>

```diff
+ double ROCKET_PLACEMENT_OFFSET
+ String TAG_EXPLOSION
+ String TAG_EXPLOSION_COLORS
+ String TAG_EXPLOSION_FADECOLORS
+ String TAG_EXPLOSION_FLICKER
+ String TAG_EXPLOSION_TRAIL
+ String TAG_EXPLOSION_TYPE
+ String TAG_EXPLOSIONS
+ String TAG_FIREWORKS
+ String TAG_FLIGHT
```

</details>






<details><summary>net.minecraft.world.item.Item</summary>

```diff
+ int EAT_DURATION
+ int MAX_BAR_WIDTH
+ int MAX_STACK_SIZE
```

</details>




<details><summary>net.minecraft.world.item.ItemStack</summary>

```diff
+ int DONT_HIDE_TOOLTIP
+ String TAG_CAN_DESTROY_BLOCK_LIST
+ String TAG_CAN_PLACE_ON_BLOCK_LIST
+ String TAG_COLOR
+ String TAG_DAMAGE
+ String TAG_DISPLAY
+ String TAG_DISPLAY_NAME
+ String TAG_ENCH
+ String TAG_ENCH_ID
+ String TAG_ENCH_LEVEL
+ String TAG_HIDE_FLAGS
+ String TAG_LORE
+ String TAG_REPAIR_COST
+ String TAG_UNBREAKABLE
```

</details>

<details><summary>net.minecraft.world.item.ItemUtils</summary>

```diff
- Optional bucketMobPickup(Supplier)
```

</details>

<details><summary>net.minecraft.world.item.KnowledgeBookItem</summary>

```diff
+ String RECIPE_TAG
```

</details>


<details><summary>net.minecraft.world.item.MilkBucketItem</summary>

```diff
+ int DRINK_DURATION
```

</details>



<details><summary>net.minecraft.world.item.PlayerHeadItem</summary>

```diff
+ String TAG_SKULL_OWNER
```

</details>









<details><summary>net.minecraft.world.item.SpyglassItem</summary>

```diff
+ float ZOOM_FOV_MODIFIER
+ int USE_DURATION
```

</details>

<details><summary>net.minecraft.world.item.SuspiciousStewItem</summary>

```diff
+ String EFFECT_DURATION_TAG
+ String EFFECT_ID_TAG
+ String EFFECTS_TAG
```

</details>



















<details><summary>net.minecraft.world.item.crafting.Ingredient</summary>

```diff
- JsonSyntaxException lambda$valueFromJson$8(ResourceLocation)
```

</details>






































<details><summary>net.minecraft.world.item.enchantment.ThornsEnchantment</summary>

```diff
+ float CHANCE_PER_LEVEL
```

</details>








<details><summary>net.minecraft.world.level.BaseSpawner</summary>

```diff
+ int EVENT_SPAWN
+ WeightedRandomList EMPTY_POTENTIALS
+ WeightedRandomList spawnPotentials
- List spawnPotentials
```

</details>


<details><summary>net.minecraft.world.level.ChunkPos</summary>

```diff
+ int HASH_A
+ int HASH_C
+ int HASH_Z_XOR
+ int REGION_BITS
+ int REGION_MASK
+ long COORD_BITS
+ long COORD_MASK
```

</details>










<details><summary>net.minecraft.world.level.Explosion</summary>

```diff
+ int MAX_DROPS_PER_COMBINED_STACK
```

</details>


<details><summary>net.minecraft.world.level.ForcedChunksSavedData</summary>

```diff
+ String FILE_ID
+ String TAG_FORCED
```

</details>







<details><summary>net.minecraft.world.level.Level</summary>

```diff
+ int LONG_PARTICLE_CLIP_RANGE
+ int MAX_BRIGHTNESS
+ int MAX_ENTITY_SPAWN_Y
+ int MAX_LEVEL_SIZE
+ int MIN_ENTITY_SPAWN_Y
+ int SHORT_PARTICLE_CLIP_RANGE
+ int TICKS_PER_DAY
```

</details>











<details><summary>net.minecraft.world.level.ServerTickList</summary>

```diff
+ int MAX_TICK_BLOCKS_PER_TICK
```

</details>

<details><summary>net.minecraft.world.level.StructureFeatureManager</summary>

```diff
+ boolean lambda$getStructureAt$4(StructureStart)
+ boolean lambda$null$3(StructurePiece)
- boolean lambda$getStructureAt$3(StructureStart)
- boolean lambda$getStructureAt$5(StructureStart)
- boolean lambda$null$4(StructurePiece)
```

</details>




<details><summary>net.minecraft.world.level.biome.Biome</summary>

```diff
+ int TEMPERATURE_CACHE_SIZE
```

</details>






















<details><summary>net.minecraft.world.level.block.AbstractCandleBlock</summary>

```diff
+ int LIGHT_PER_CANDLE
+ boolean canBeLit(BlockState)
+ boolean isLit(BlockState)
+ void lambda$extinguish$1(Vec3)
```

</details>





<details><summary>net.minecraft.world.level.block.AnvilBlock</summary>

```diff
+ float FALL_DAMAGE_PER_DISTANCE
+ int FALL_DAMAGE_MAX
```

</details>

<details><summary>net.minecraft.world.level.block.AzaleaBlock</summary>

```diff
+ VoxelShape SUPPORT_SHAPE
+ void <clinit>()
+ VoxelShape getBlockSupportShape(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.block.BambooSaplingBlock</summary>

```diff
+ float SAPLING_AABB_OFFSET
```

</details>









<details><summary>net.minecraft.world.level.block.BeetrootBlock</summary>

```diff
+ int MAX_AGE
```

</details>


<details><summary>net.minecraft.world.level.block.BigDripleafStemBlock</summary>

```diff
+ int STEM_WIDTH
+ ItemStack getCloneItemStack(BlockState)
```

</details>





<details><summary>net.minecraft.world.level.block.BubbleColumnBlock</summary>

```diff
+ int CHECK_PERIOD
```

</details>

<details><summary>net.minecraft.world.level.block.BuddingAmethystBlock</summary>

```diff
+ int GROWTH_CHANCE
```

</details>

<details><summary>net.minecraft.world.level.block.ButtonBlock</summary>

```diff
+ int HALF_AABB_HEIGHT
+ int HALF_AABB_WIDTH
+ int PRESSED_DEPTH
+ int UNPRESSED_DEPTH
```

</details>

<details><summary>net.minecraft.world.level.block.CactusBlock</summary>

```diff
+ int AABB_OFFSET
+ int MAX_AGE
```

</details>

<details><summary>net.minecraft.world.level.block.CampfireBlock</summary>

```diff
+ int SMOKE_DISTANCE
```

</details>

<details><summary>net.minecraft.world.level.block.CandleCakeBlock</summary>

```diff
+ float AABB_OFFSET
```

</details>






<details><summary>net.minecraft.world.level.block.ChestBlock</summary>

```diff
+ int AABB_HEIGHT
+ int AABB_OFFSET
+ int EVENT_SET_OPEN_COUNT
```

</details>



<details><summary>net.minecraft.world.level.block.ChorusFlowerBlock</summary>

```diff
+ int DEAD_AGE
```

</details>

<details><summary>net.minecraft.world.level.block.CocoaBlock</summary>

```diff
+ int AGE_0_HALFWIDTH
+ int AGE_0_HEIGHT
+ int AGE_0_WIDTH
+ int AGE_1_HALFWIDTH
+ int AGE_1_HEIGHT
+ int AGE_1_WIDTH
+ int AGE_2_HALFWIDTH
+ int AGE_2_HEIGHT
+ int AGE_2_WIDTH
+ int MAX_AGE
```

</details>


<details><summary>net.minecraft.world.level.block.ComposterBlock</summary>

```diff
+ int AABB_SIDE_THICKNESS
+ int MAX_LEVEL
+ int MIN_LEVEL
+ int READY
```

</details>




<details><summary>net.minecraft.world.level.block.CoralPlantBlock</summary>

```diff
+ float AABB_OFFSET
```

</details>




<details><summary>net.minecraft.world.level.block.DeadBushBlock</summary>

```diff
+ float AABB_OFFSET
```

</details>



<details><summary>net.minecraft.world.level.block.DispenserBlock</summary>

```diff
+ int TRIGGER_DURATION
```

</details>















<details><summary>net.minecraft.world.level.block.FlowerPotBlock</summary>

```diff
+ float AABB_SIZE
```

</details>

<details><summary>net.minecraft.world.level.block.FungusBlock</summary>

```diff
+ double BONEMEAL_SUCCESS_PROBABILITY
```

</details>






<details><summary>net.minecraft.world.level.block.GrowingPlantHeadBlock</summary>

```diff
+ int MAX_AGE
```

</details>


<details><summary>net.minecraft.world.level.block.HoneyBlock</summary>

```diff
+ double MIN_FALL_SPEED_TO_BE_CONSIDERED_SLIDING
+ double SLIDE_STARTS_WHEN_VERTICAL_SPEED_IS_AT_LEAST
+ double THROTTLE_SLIDE_SPEED_TO
+ int SLIDE_ADVANCEMENT_CHECK_INTERVAL
```

</details>





<details><summary>net.minecraft.world.level.block.KelpBlock</summary>

```diff
+ double GROW_PER_TICK_PROBABILITY
```

</details>

<details><summary>net.minecraft.world.level.block.LadderBlock</summary>

```diff
+ float AABB_OFFSET
```

</details>


<details><summary>net.minecraft.world.level.block.LayeredCauldronBlock</summary>

```diff
+ double HEIGHT_PER_LEVEL
+ int BASE_CONTENT_HEIGHT
+ int MAX_FILL_LEVEL
+ int MIN_FILL_LEVEL
```

</details>

<details><summary>net.minecraft.world.level.block.LecternBlock</summary>

```diff
+ int PAGE_CHANGE_IMPULSE_TICKS
```

</details>

<details><summary>net.minecraft.world.level.block.LevelEvent</summary>

```diff
+ int ANIMATION_DRAGON_SUMMON_ROAR
+ int ANIMATION_END_GATEWAY_SPAWN
+ int COMPOSTER_FILL
+ int DRIPSTONE_DRIP
+ int END_PORTAL_FRAME_FILL
+ int LAVA_FIZZ
+ int PARTICLES_AND_SOUND_WAX_ON
+ int PARTICLES_DESTROY_BLOCK
+ int PARTICLES_DRAGON_BLOCK_BREAK
+ int PARTICLES_DRAGON_FIREBALL_SPLASH
+ int PARTICLES_ELECTRIC_SPARK
+ int PARTICLES_EYE_OF_ENDER_DEATH
+ int PARTICLES_INSTANT_POTION_SPLASH
+ int PARTICLES_MOBBLOCK_SPAWN
+ int PARTICLES_PLANT_GROWTH
+ int PARTICLES_SCRAPE
+ int PARTICLES_SHOOT
+ int PARTICLES_SPELL_POTION_SPLASH
+ int PARTICLES_WATER_EVAPORATING
+ int PARTICLES_WAX_OFF
+ int REDSTONE_TORCH_BURNOUT
+ int SOUND_ANVIL_BROKEN
+ int SOUND_ANVIL_LAND
+ int SOUND_ANVIL_USED
+ int SOUND_BAT_LIFTOFF
+ int SOUND_BLAZE_FIREBALL
+ int SOUND_BREWING_STAND_BREW
+ int SOUND_CHORUS_DEATH
+ int SOUND_CHORUS_GROW
+ int SOUND_CLOSE_FENCE_GATE
+ int SOUND_CLOSE_IRON_DOOR
+ int SOUND_CLOSE_IRON_TRAP_DOOR
+ int SOUND_CLOSE_WOODEN_DOOR
+ int SOUND_CLOSE_WOODEN_TRAP_DOOR
+ int SOUND_DISPENSER_DISPENSE
+ int SOUND_DISPENSER_FAIL
+ int SOUND_DISPENSER_PROJECTILE_LAUNCH
+ int SOUND_DRAGON_DEATH
+ int SOUND_DRAGON_FIREBALL
+ int SOUND_DRIP_LAVA_INTO_CAULDRON
+ int SOUND_DRIP_WATER_INTO_CAULDRON
+ int SOUND_END_PORTAL_SPAWN
+ int SOUND_ENDER_EYE_LAUNCH
+ int SOUND_EXTINGUISH_FIRE
+ int SOUND_FIREWORK_SHOOT
+ int SOUND_GHAST_FIREBALL
+ int SOUND_GHAST_WARNING
+ int SOUND_GRINDSTONE_USED
+ int SOUND_HUSK_TO_ZOMBIE
+ int SOUND_OPEN_FENCE_GATE
+ int SOUND_OPEN_IRON_DOOR
+ int SOUND_OPEN_IRON_TRAP_DOOR
+ int SOUND_OPEN_WOODEN_DOOR
+ int SOUND_OPEN_WOODEN_TRAP_DOOR
+ int SOUND_PAGE_TURN
+ int SOUND_PHANTOM_BITE
+ int SOUND_PLAY_RECORDING
+ int SOUND_POINTED_DRIPSTONE_LAND
+ int SOUND_PORTAL_TRAVEL
+ int SOUND_SKELETON_TO_STRAY
+ int SOUND_SMITHING_TABLE_USED
+ int SOUND_WITHER_BLOCK_BREAK
+ int SOUND_WITHER_BOSS_SHOOT
+ int SOUND_WITHER_BOSS_SPAWN
+ int SOUND_ZOMBIE_CONVERTED
+ int SOUND_ZOMBIE_DOOR_CRASH
+ int SOUND_ZOMBIE_INFECTED
+ int SOUND_ZOMBIE_IRON_DOOR
+ int SOUND_ZOMBIE_TO_DROWNED
+ int SOUND_ZOMBIE_WOODEN_DOOR
```

</details>





























<details><summary>net.minecraft.world.level.levelgen.Cavifier</summary>

```diff
+ int CHEESE_NOISE_RANGE
+ int SURFACE_DENSITY_THRESHOLD
```

</details>



<details><summary>net.minecraft.world.level.levelgen.DebugLevelSource</summary>

```diff
+ int BARRIER_HEIGHT
+ int BLOCK_MARGIN
+ int HEIGHT
```

</details>

<details><summary>net.minecraft.world.level.levelgen.DepthBasedReplacingBaseStoneSource</summary>

```diff
+ int ALWAYS_REPLACE_BELOW_Y
+ int NEVER_REPLACE_ABOVE_Y
```

</details>











<details><summary>net.minecraft.world.level.levelgen.SimpleRandomSource</summary>

```diff
+ double DOUBLE_MULTIPLIER
+ float FLOAT_MULTIPLIER
+ int MODULUS_BITS
+ long INCREMENT
+ long MODULUS_MASK
+ long MULTIPLIER
```

</details>


<details><summary>net.minecraft.world.level.levelgen.VerticalAnchor$Absolute</summary>

```diff
+ String toString()
```

</details>



<details><summary>net.minecraft.world.level.levelgen.carver.CaveWorldCarver</summary>

```diff
+ boolean carve(BitSet)
+ boolean isStartChunk(Random)
+ void createRoom(WorldCarver$CarveSkipChecker)
+ void createTunnel(WorldCarver$CarveSkipChecker)
- int getCaveY(Random)
- void createRoom(WorldCarver$CarveSkipChecker)
- void createTunnel(WorldCarver$CarveSkipChecker)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.carver.NetherWorldCarver</summary>

```diff
+ boolean carveBlock(MutableBoolean)
- int getCaveY(Random)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.feature.BastionFeature</summary>

```diff
+ int BASTION_SPAWN_HEIGHT
```

</details>



<details><summary>net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.feature.DeltaFeature</summary>

```diff
+ double RIM_SPAWN_CHANCE
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>











<details><summary>net.minecraft.world.level.levelgen.feature.JigsawFeature</summary>

```diff
+ StructureStart lambda$getStartFactory$0(ChunkPos,int,long)
- StructureStart lambda$getStartFactory$0(BoundingBox,int,long)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature</summary>

```diff
+ LargeDripstoneFeature$LargeDripstone makeDripstone(FloatProvider)
- LargeDripstoneFeature$LargeDripstone makeDripstone(FloatProvider)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart</summary>

```diff
- boolean isCreated
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
- void generatePieces(ChunkPos)
- void placeInChunk(ChunkPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature</summary>

```diff
+ WeightedRandomList OUTPOST_ENEMIES
- List OUTPOST_ENEMIES
+ WeightedRandomList getSpecialEnemies()
- List getSpecialEnemies()
```

</details>




<details><summary>net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.ScatteredOreFeature</summary>

```diff
+ int MAX_DIST_FROM_ORIGIN
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>






<details><summary>net.minecraft.world.level.levelgen.feature.StructureFeature</summary>

```diff
+ int MAX_STRUCTURE_RANGE
+ StructureStart createStart(ChunkPos,int,long)
+ WeightedRandomList getSpecialAnimals()
+ WeightedRandomList getSpecialEnemies()
- List getSpecialAnimals()
- List getSpecialEnemies()
- StructureStart createStart(BoundingBox,int,long)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>






<details><summary>net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration</summary>

```diff
+ IntProvider height
+ IntProvider reach
- UniformInt height
- UniformInt reach
+ IntProvider height()
+ IntProvider lambda$null$0(ColumnFeatureConfiguration)
+ IntProvider lambda$null$1(ColumnFeatureConfiguration)
+ IntProvider reach()
+ void <init>(IntProvider)
- UniformInt height()
- UniformInt lambda$null$0(ColumnFeatureConfiguration)
- UniformInt lambda$null$1(ColumnFeatureConfiguration)
- UniformInt reach()
- void <init>(UniformInt)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration</summary>

```diff
+ IntProvider rimSize
+ IntProvider size
- UniformInt rimSize
- UniformInt size
+ IntProvider lambda$null$2(DeltaFeatureConfiguration)
+ IntProvider lambda$null$3(DeltaFeatureConfiguration)
+ IntProvider rimSize()
+ IntProvider size()
+ void <init>(IntProvider)
- UniformInt lambda$null$2(DeltaFeatureConfiguration)
- UniformInt lambda$null$3(DeltaFeatureConfiguration)
- UniformInt rimSize()
- UniformInt size()
- void <init>(UniformInt)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration</summary>

```diff
+ FloatProvider density
+ FloatProvider wetness
+ IntProvider dripstoneBlockLayerThickness
+ IntProvider height
+ IntProvider radius
- FloatProvider density
- FloatProvider wetness
- UniformInt dripstoneBlockLayerThickness
- UniformInt height
- UniformInt radius
+ FloatProvider lambda$null$6(DripstoneClusterConfiguration)
+ FloatProvider lambda$null$7(DripstoneClusterConfiguration)
+ IntProvider lambda$null$1(DripstoneClusterConfiguration)
+ IntProvider lambda$null$2(DripstoneClusterConfiguration)
+ IntProvider lambda$null$5(DripstoneClusterConfiguration)
+ void <init>(FloatProvider,float,int,int)
- FloatProvider lambda$null$6(DripstoneClusterConfiguration)
- FloatProvider lambda$null$7(DripstoneClusterConfiguration)
- UniformInt lambda$null$1(DripstoneClusterConfiguration)
- UniformInt lambda$null$2(DripstoneClusterConfiguration)
- UniformInt lambda$null$5(DripstoneClusterConfiguration)
- void <init>(FloatProvider,float,int,int)
```

</details>














<details><summary>net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration</summary>

```diff
+ IntProvider radius
- UniformInt radius
+ IntProvider lambda$null$2(ReplaceSphereConfiguration)
+ IntProvider radius()
+ void <init>(IntProvider)
- UniformInt lambda$null$2(ReplaceSphereConfiguration)
- UniformInt radius()
- void <init>(UniformInt)
```

</details>







<details><summary>net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration</summary>

```diff
+ IntProvider depth
+ IntProvider xzRadius
- UniformInt depth
- UniformInt xzRadius
+ IntProvider lambda$null$4(VegetationPatchConfiguration)
+ IntProvider lambda$null$8(VegetationPatchConfiguration)
+ void <init>(IntProvider,float)
- UniformInt lambda$null$4(VegetationPatchConfiguration)
- UniformInt lambda$null$8(VegetationPatchConfiguration)
- void <init>(UniformInt,float)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize</summary>

```diff
+ int MAX_WIDTH
```

</details>



<details><summary>net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer</summary>

```diff
+ void <init>(IntProvider,int)
+ void createFoliage(FoliagePlacer$FoliageAttachment,int,int,int)
- void <init>(UniformInt,int)
- void createFoliage(BoundingBox)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer</summary>

```diff
+ void <init>(IntProvider)
+ void createFoliage(FoliagePlacer$FoliageAttachment,int,int,int)
- void <init>(UniformInt)
- void createFoliage(BoundingBox)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer</summary>

```diff
+ IntProvider offset
+ IntProvider radius
+ void createFoliage(net.minecraft.world.level.LevelSimulatedReader,java.util.function.BiConsumer,java.util.Random,net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration,int,net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment,int,int,int)
- UniformInt offset
- UniformInt radius
- void createFoliage(net.minecraft.world.level.LevelSimulatedRW,java.util.Random,net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration,int,net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment,int,int,java.util.Set,int,net.minecraft.world.level.levelgen.structure.BoundingBox)
+ IntProvider lambda$foliagePlacerParts$0(FoliagePlacer)
+ IntProvider lambda$foliagePlacerParts$1(FoliagePlacer)
+ void <init>(IntProvider)
+ void createFoliage(FoliagePlacer$FoliageAttachment,int,int)
+ void placeLeavesRow(BlockPos,int,int,boolean)
+ void tryPlaceLeaf(BlockPos)
- UniformInt lambda$foliagePlacerParts$0(FoliagePlacer)
- UniformInt lambda$foliagePlacerParts$1(FoliagePlacer)
- void <init>(UniformInt)
- void createFoliage(BoundingBox)
- void placeLeavesRow(BoundingBox)
- void tryPlaceLeaf(BlockPos$MutableBlockPos)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer</summary>

```diff
+ IntProvider crownHeight
- UniformInt crownHeight
+ IntProvider lambda$null$0(MegaPineFoliagePlacer)
+ void <init>(IntProvider)
+ void createFoliage(FoliagePlacer$FoliageAttachment,int,int,int)
- UniformInt lambda$null$0(MegaPineFoliagePlacer)
- void <init>(UniformInt)
- void createFoliage(BoundingBox)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer</summary>

```diff
+ IntProvider foliageHeight
- UniformInt foliageHeight
+ IntProvider lambda$null$0(RandomSpreadFoliagePlacer)
+ void <init>(IntProvider,int)
+ void createFoliage(FoliagePlacer$FoliageAttachment,int,int,int)
- UniformInt lambda$null$0(RandomSpreadFoliagePlacer)
- void <init>(UniformInt,int)
- void createFoliage(BoundingBox)
```

</details>




<details><summary>net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider</summary>

```diff
+ IntProvider values
- UniformInt values
+ IntProvider lambda$null$2(RandomizedIntStateProvider)
+ void <init>(IntProvider)
+ void <init>(IntProvider)
- UniformInt lambda$null$2(RandomizedIntStateProvider)
- void <init>(UniformInt)
- void <init>(UniformInt)
```

</details>




<details><summary>net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement</summary>

```diff
+ void addPieces(LevelHeightAccessor)
- void addPieces(LevelHeightAccessor)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.feature.structures.ListPoolElement</summary>

```diff
+ boolean lambda$getBoundingBox$2(StructurePoolElement)
+ BoundingBox lambda$getBoundingBox$3(StructurePoolElement)
+ IllegalStateException lambda$getBoundingBox$4()
+ void lambda$setProjectionOnEachElement$5(StructurePoolElement)
- void lambda$setProjectionOnEachElement$2(StructurePoolElement)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool</summary>

```diff
+ int SIZE_UNSET
+ boolean lambda$getMaxSize$2(StructurePoolElement)
+ int lambda$getMaxSize$3(StructurePoolElement)
- int lambda$getMaxSize$2(StructurePoolElement)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator</summary>

```diff
+ void lambda$place$2(BeehiveBlockEntity)
+ void place(List)
- void place(BoundingBox)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator</summary>

```diff
+ void addHangingVine(BiConsumer)
+ void lambda$place$1(BlockPos)
+ void place(List)
- void addHangingVine(BoundingBox)
- void lambda$place$1(BlockPos)
- void place(BoundingBox)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer</summary>

```diff
+ List placeTrunk(TreeConfiguration)
- List placeTrunk(TreeConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer</summary>

```diff
+ List placeTrunk(TreeConfiguration)
+ void placeLogIfFreeWithOffset(BlockPos,int,int,int)
- List placeTrunk(TreeConfiguration)
- void placeLogIfFreeWithOffset(BlockPos,int,int,int)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer</summary>

```diff
+ List placeTrunk(TreeConfiguration)
- List placeTrunk(TreeConfiguration)
```

</details>

























<details><summary>net.minecraft.world.level.levelgen.structure.BoundingBox</summary>

```diff
+ int maxX
+ int maxY
+ int maxZ
+ int minX
+ int minY
+ int minZ
+ Logger LOGGER
- int x0
- int x1
- int y0
- int y1
- int z0
- int z1
+ BoundingBox encapsulate(BoundingBox)
+ BoundingBox fromCorners(Vec3i)
+ BoundingBox inflate(int)
+ int maxX()
+ int maxY()
+ int maxZ()
+ int minX()
+ int minY()
+ int minZ()
+ Optional encapsulatingBoxes(Iterable)
+ Optional encapsulatingPositions(Iterable)
- BoundingBox createProper(int,int,int,int,int,int)
- BoundingBox createProper(Vec3i)
- BoundingBox getUnknownBox()
- void expand(BoundingBox)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece</summary>

```diff
- boolean overwrite
- Rotation rotation
- String templateName
+ ResourceLocation makeResourceLocation(String)
+ ResourceLocation makeTemplateLocation()
+ StructurePlaceSettings lambda$new$0(ResourceLocation)
+ StructurePlaceSettings makeSettings(Rotation)
- void loadTemplate(StructureManager)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.IglooPieces</summary>

```diff
+ int GENERATION_HEIGHT
+ void addPieces(Random)
- void addPieces(Random)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.structure.MineShaftPieces</summary>

```diff
+ int DEFAULT_SHAFT_HEIGHT
+ int DEFAULT_SHAFT_LENGTH
+ int DEFAULT_SHAFT_WIDTH
+ int MAX_CHAIN_HEIGHT
+ int MAX_DEPTH
+ int MAX_PILLAR_HEIGHT
+ MineShaftPieces$MineShaftPiece access$100(Direction,int)
+ MineShaftPieces$MineShaftPiece createRandomShaftPiece(MineshaftFeature$Type)
+ MineShaftPieces$MineShaftPiece generateAndAddPiece(Direction,int)
- MineShaftPieces$MineShaftPiece access$100(Direction,int)
- MineShaftPieces$MineShaftPiece createRandomShaftPiece(MineshaftFeature$Type)
- MineShaftPieces$MineShaftPiece generateAndAddPiece(Direction,int)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor</summary>

```diff
+ BoundingBox findCorridorSize(Direction)
+ void addChildren(Random)
- BoundingBox findCorridorSize(Direction)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece</summary>

```diff
+ void <init>(BoundingBox)
- void <init>(MineshaftFeature$Type)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs</summary>

```diff
+ BoundingBox findStairs(Direction)
+ void addChildren(Random)
- BoundingBox findStairs(Direction)
- void addChildren(Random)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$BridgeEndFiller createPiece(Direction,int)
- NetherBridgePieces$BridgeEndFiller createPiece(Direction,int)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$CastleCorridorStairsPiece createPiece(Direction,int)
+ void addChildren(Random)
- NetherBridgePieces$CastleCorridorStairsPiece createPiece(Direction,int)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$CastleEntrance createPiece(Direction,int)
+ void addChildren(Random)
- NetherBridgePieces$CastleEntrance createPiece(Direction,int)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$CastleSmallCorridorLeftTurnPiece createPiece(Direction,int)
+ void addChildren(Random)
- NetherBridgePieces$CastleSmallCorridorLeftTurnPiece createPiece(Direction,int)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$CastleSmallCorridorRightTurnPiece createPiece(Direction,int)
+ void addChildren(Random)
- NetherBridgePieces$CastleSmallCorridorRightTurnPiece createPiece(Direction,int)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$MonsterThrone createPiece(Direction)
- NetherBridgePieces$MonsterThrone createPiece(Direction)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$StairsRoom createPiece(Direction)
+ void addChildren(Random)
- NetherBridgePieces$StairsRoom createPiece(Direction)
- void addChildren(Random)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.NetherFossilPieces</summary>

```diff
+ void addPieces(BlockPos)
- void addPieces(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NoiseAffectingStructureStart</summary>

```diff
+ BoundingBox getBoundingBox()
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
- void calculateBoundingBox()
```

</details>





<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding</summary>

```diff
+ int BIOME_RANGE_CHECK
+ int DEPTH
+ int HEIGHT
+ int TOP_POSITION
+ int WIDTH
```

</details>





<details><summary>net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece</summary>

```diff
+ boolean DO_FILL
+ int GRID_DEPTH
+ int GRID_FLOOR_COUNT
+ int GRID_HEIGHT
+ int GRID_SIZE
+ int GRID_WIDTH
+ int GRIDROOM_DEPTH
+ int GRIDROOM_HEIGHT
+ int GRIDROOM_WIDTH
+ int LEFTWING_INDEX
+ int PENTHOUSE_INDEX
+ int RIGHTWING_INDEX
+ BoundingBox makeBoundingBox(OceanMonumentPieces$RoomDefinition,int,int,int)
+ void <init>(BoundingBox)
- void <init>(BoundingBox)
- void <init>(StructurePieceType,int)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.OceanRuinPieces</summary>

```diff
+ List allPositions(BlockPos)
+ void addClusterRuins(StructurePieceAccessor)
+ void addPiece(OceanRuinConfiguration,boolean,float)
+ void addPieces(OceanRuinConfiguration)
- List allPositions(Random,int,int)
- void addClusterRuins(List)
- void addPiece(OceanRuinConfiguration,boolean,float)
- void addPieces(OceanRuinConfiguration)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.StructureStart$1</summary>

```diff
+ boolean isValid()
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.TemplateStructurePiece</summary>

```diff
+ String templateName
+ ResourceLocation makeTemplateLocation()
+ void <init>(BlockPos)
+ void <init>(Function)
- void <init>(CompoundTag)
- void <init>(StructurePieceType,int)
- void setup(StructurePlaceSettings)
```

</details>








<details><summary>net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor</summary>

```diff
+ float PROBABILITY_OF_REPLACING_FULL_BLOCK
+ float PROBABILITY_OF_REPLACING_OBSIDIAN
+ float PROBABILITY_OF_REPLACING_STAIRS
```

</details>












<details><summary>net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate</summary>

```diff
+ int CHUNK_SIZE
+ String BLOCK_TAG_NBT
+ String BLOCK_TAG_POS
+ String BLOCK_TAG_STATE
+ String BLOCKS_TAG
+ String ENTITIES_TAG
+ String ENTITY_TAG_BLOCKPOS
+ String ENTITY_TAG_NBT
+ String ENTITY_TAG_POS
+ String PALETTE_LIST_TAG
+ String PALETTE_TAG
+ String SIZE_TAG
```

</details>




<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder</summary>

```diff
+ int MAX_CLAY_DEPTH
```

</details>











<details><summary>net.minecraft.world.level.levelgen.synth.ImprovedNoise</summary>

```diff
+ float SHIFT_UP_EPSILON
```

</details>

<details><summary>net.minecraft.world.level.levelgen.synth.NormalNoise</summary>

```diff
+ double INPUT_FACTOR
+ double TARGET_DEVIATION
```

</details>





<details><summary>net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint</summary>

```diff
+ int NO_COMPUTED_LEVEL
```

</details>


<details><summary>net.minecraft.world.level.lighting.LayerLightEngine</summary>

```diff
+ int CACHE_SIZE
+ long SELF_SOURCE
```

</details>






<details><summary>net.minecraft.world.level.lighting.SpatialLongSet$InternalMap</summary>

```diff
+ int Y_OFFSET
```

</details>



<details><summary>net.minecraft.world.level.material.FluidState</summary>

```diff
+ int AMOUNT_FULL
+ int AMOUNT_MAX
```

</details>



<details><summary>net.minecraft.world.level.material.Material</summary>

```diff
+ Material MOSS
- Material CORAL
```

</details>







<details><summary>net.minecraft.world.level.newbiome.context.LazyAreaContext</summary>

```diff
+ int MAX_CACHE
```

</details>







<details><summary>net.minecraft.world.level.newbiome.layer.LayerBiomes</summary>

```diff
+ int BADLANDS
+ int BADLANDS_PLATEAU
+ int BAMBOO_JUNGLE
+ int BAMBOO_JUNGLE_HILLS
+ int BEACH
+ int BIRCH_FOREST
+ int BIRCH_FOREST_HILLS
+ int COLD_OCEAN
+ int DARK_FOREST
+ int DARK_FOREST_HILLS
+ int DEEP_COLD_OCEAN
+ int DEEP_FROZEN_OCEAN
+ int DEEP_LUKEWARM_OCEAN
+ int DEEP_OCEAN
+ int DEEP_WARM_OCEAN
+ int DESERT
+ int DESERT_HILLS
+ int DESERT_LAKES
+ int ERODED_BADLANDS
+ int FLOWER_FOREST
+ int FOREST
+ int FROZEN_OCEAN
+ int FROZEN_RIVER
+ int GIANT_SPRUCE_TAIGA
+ int GIANT_SPRUCE_TAIGA_HILLS
+ int GIANT_TREE_TAIGA
+ int GIANT_TREE_TAIGA_HILLS
+ int GRAVELLY_MOUNTAINS
+ int ICE_SPIKES
+ int JUNGLE
+ int JUNGLE_EDGE
+ int JUNGLE_HILLS
+ int LUKEWARM_OCEAN
+ int MODIFIED_BADLANDS_PLATEAU
+ int MODIFIED_GRAVELLY_MOUNTAINS
+ int MODIFIED_JUNGLE
+ int MODIFIED_JUNGLE_EDGE
+ int MODIFIED_WOODED_BADLANDS_PLATEAU
+ int MOUNTAIN_EDGE
+ int MOUNTAINS
+ int MUSHROOM_FIELD_SHORE
+ int MUSHROOM_FIELDS
+ int OCEAN
+ int PLAINS
+ int RIVER
+ int SAVANNA
+ int SAVANNA_PLATEAU
+ int SHATTERED_SAVANNA
+ int SHATTERED_SAVANNA_PLATEAU
+ int SNOWY_BEACH
+ int SNOWY_MOUNTAINS
+ int SNOWY_TAIGA
+ int SNOWY_TAIGA_HILLS
+ int SNOWY_TAIGA_MOUNTAINS
+ int SNOWY_TUNDRA
+ int STONE_SHORE
+ int SUNFLOWER_PLAINS
+ int SWAMP
+ int SWAMP_HILLS
+ int TAIGA
+ int TAIGA_HILLS
+ int TAIGA_MOUNTAINS
+ int TALL_BIRCH_FOREST
+ int TALL_BIRCH_HILLS
+ int WARM_OCEAN
+ int WOODED_BADLANDS_PLATEAU
+ int WOODED_HILLS
+ int WOODED_MOUNTAINS
```

</details>







<details><summary>net.minecraft.world.level.newbiome.layer.ZoomLayer</summary>

```diff
+ int ZOOM_BITS
+ int ZOOM_MASK
```

</details>












<details><summary>net.minecraft.world.level.pathfinder.PathFinder</summary>

```diff
+ boolean DEBUG
+ float FUDGING
```

</details>









<details><summary>net.minecraft.world.level.saveddata.maps.MapItemSavedData</summary>

```diff
+ int HALF_MAP_SIZE
+ int MAP_SIZE
+ int MAX_SCALE
```

</details>



<details><summary>net.minecraft.world.level.storage.CommandStorage</summary>

```diff
+ String ID_PREFIX
```

</details>

<details><summary>net.minecraft.world.level.storage.CommandStorage$Container</summary>

```diff
+ String TAG_CONTENTS
```

</details>



<details><summary>net.minecraft.world.level.storage.LevelStorageSource</summary>

```diff
+ String ICON_FILENAME
```

</details>




































<details><summary>net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer</summary>

```diff
+ int DEFAULT_QUALITY
+ int DEFAULT_WEIGHT
```

</details>


























<details><summary>net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction</summary>

```diff
+ boolean DEFAULT_SKIP_EXISTING
+ byte DEFAULT_ZOOM
+ int DEFAULT_SEARCH_RADIUS
+ String DEFAULT_DECORATION_NAME
```

</details>









<details><summary>net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction</summary>

```diff
+ int NO_LIMIT
```

</details>















































































<details><summary>Added and removed classes</summary>

```diff
+ com.mojang.blaze3d.audio.Channel
- com.mojang.blaze3d.audio.Library
+ com.mojang.blaze3d.audio.Library$1
- com.mojang.blaze3d.audio.Library$ChannelPool
+ com.mojang.blaze3d.audio.Library$CountingChannelPool
- com.mojang.blaze3d.audio.Library$Pool
+ com.mojang.blaze3d.audio.Listener
- com.mojang.blaze3d.audio.OggAudioStream
+ com.mojang.blaze3d.audio.OggAudioStream$OutputConcat
- com.mojang.blaze3d.audio.OpenAlUtil
+ com.mojang.blaze3d.audio.SoundBuffer
+ com.mojang.blaze3d.FieldsAreNonnullByDefault
+ com.mojang.blaze3d.font.package-info
+ com.mojang.blaze3d.platform.ClipboardManager
- com.mojang.blaze3d.platform.DebugMemoryUntracker
+ com.mojang.blaze3d.platform.DisplayData
+ com.mojang.blaze3d.platform.GlConst
- com.mojang.blaze3d.platform.GLX
+ com.mojang.blaze3d.platform.package-info
+ com.mojang.blaze3d.preprocessor.GlslPreprocessor$1
+ com.mojang.blaze3d.preprocessor.package-info
- com.mojang.blaze3d.shaders.AbstractUniform
+ com.mojang.blaze3d.shaders.BlendMode
- com.mojang.blaze3d.shaders.Effect
+ com.mojang.blaze3d.shaders.EffectProgram
- com.mojang.blaze3d.shaders.EffectProgram$1
+ com.mojang.blaze3d.shaders.Program
- com.mojang.blaze3d.shaders.Program$Type
+ com.mojang.blaze3d.shaders.ProgramManager
- com.mojang.blaze3d.shaders.Shader
+ com.mojang.blaze3d.shaders.Uniform
+ com.mojang.blaze3d.systems.package-info
- com.mojang.blaze3d.vertex.BufferBuilder
+ com.mojang.blaze3d.vertex.BufferBuilder$1
- com.mojang.blaze3d.vertex.BufferBuilder$DrawState
+ com.mojang.blaze3d.vertex.BufferBuilder$SortState
- com.mojang.blaze3d.vertex.BufferUploader
+ com.mojang.blaze3d.vertex.BufferVertexConsumer
+ com.mojang.blaze3d.vertex.DefaultedVertexConsumer
- com.mojang.blaze3d.vertex.DefaultVertexFormat
+ com.mojang.blaze3d.vertex.package-info
- com.mojang.blaze3d.vertex.PoseStack
+ com.mojang.blaze3d.vertex.PoseStack$1
- com.mojang.blaze3d.vertex.PoseStack$Pose
+ com.mojang.blaze3d.vertex.SheetedDecalTextureGenerator
- com.mojang.blaze3d.vertex.Tesselator
+ com.mojang.blaze3d.vertex.VertexBuffer
- com.mojang.blaze3d.vertex.VertexConsumer
+ com.mojang.blaze3d.vertex.VertexFormat
- com.mojang.blaze3d.vertex.VertexFormat$1
+ com.mojang.blaze3d.vertex.VertexFormat$IndexType
- com.mojang.blaze3d.vertex.VertexFormat$Mode
+ com.mojang.blaze3d.vertex.VertexFormatElement
- com.mojang.blaze3d.vertex.VertexFormatElement$Type
+ com.mojang.blaze3d.vertex.VertexFormatElement$Usage
- com.mojang.blaze3d.vertex.VertexFormatElement$Usage$ClearState
+ com.mojang.blaze3d.vertex.VertexFormatElement$Usage$SetupState
- com.mojang.blaze3d.vertex.VertexMultiConsumer
+ com.mojang.blaze3d.vertex.VertexMultiConsumer$Double
+ com.mojang.math.FieldsAreNonnullByDefault
- com.mojang.math.Matrix3f
+ com.mojang.math.Matrix4f
+ com.mojang.math.package-info
+ com.mojang.realmsclient.client.FileDownload
- com.mojang.realmsclient.client.FileDownload$1
+ com.mojang.realmsclient.client.FileDownload$DownloadCountingOutputStream
- com.mojang.realmsclient.client.FileDownload$ProgressListener
+ com.mojang.realmsclient.client.FileDownload$ResourcePackProgressListener
- com.mojang.realmsclient.client.FileUpload
+ com.mojang.realmsclient.client.FileUpload$CustomInputStreamEntity
+ com.mojang.realmsclient.client.package-info
- com.mojang.realmsclient.client.Ping
+ com.mojang.realmsclient.client.Ping$Region
- com.mojang.realmsclient.client.RealmsClient
+ com.mojang.realmsclient.client.RealmsClient$CompatibleVersionResponse
- com.mojang.realmsclient.client.RealmsClient$Environment
+ com.mojang.realmsclient.client.RealmsClientConfig
- com.mojang.realmsclient.client.RealmsError
+ com.mojang.realmsclient.client.Request
- com.mojang.realmsclient.client.Request$Delete
+ com.mojang.realmsclient.client.Request$Get
- com.mojang.realmsclient.client.Request$Post
+ com.mojang.realmsclient.client.Request$Put
- com.mojang.realmsclient.client.UploadStatus
+ com.mojang.realmsclient.dto.package-info
+ com.mojang.realmsclient.dto.ServerActivity
- com.mojang.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
+ com.mojang.realmsclient.exception.RealmsHttpException
- com.mojang.realmsclient.exception.RealmsServiceException
+ com.mojang.realmsclient.exception.RetryCallException
+ com.mojang.realmsclient.gui.screens.package-info
+ com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen
- com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen$BackupInfoList
+ com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen$BackupInfoListEntry
- com.mojang.realmsclient.gui.screens.RealmsBackupScreen
+ com.mojang.realmsclient.gui.screens.RealmsBackupScreen$1
- com.mojang.realmsclient.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
+ com.mojang.realmsclient.gui.screens.RealmsBackupScreen$Entry
- com.mojang.realmsclient.gui.screens.RealmsBrokenWorldScreen
+ com.mojang.realmsclient.gui.screens.RealmsClientOutdatedScreen
- com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen
+ com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$1
- com.mojang.realmsclient.gui.screens.RealmsConfirmScreen
+ com.mojang.realmsclient.gui.screens.RealmsCreateRealmScreen
- com.mojang.realmsclient.gui.screens.RealmsDownloadLatestWorldScreen
+ com.mojang.realmsclient.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
- com.mojang.realmsclient.gui.screens.RealmsGenericErrorScreen
+ com.mojang.realmsclient.gui.screens.RealmsInviteScreen
- com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen
+ com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen$Type
- com.mojang.realmsclient.gui.screens.RealmsLongRunningMcoTaskScreen
+ com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen
- com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsParentalConsentScreen
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$1
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$3
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry$RejectRowButton
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
- com.mojang.realmsclient.gui.screens.RealmsPlayerScreen
+ com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$Entry
- com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
+ com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$UserAction
- com.mojang.realmsclient.gui.screens.RealmsResetNormalWorldScreen
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$FrameButton
- com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen
+ com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$Entry
- com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
+ com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen
- com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$Entry
- com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
+ com.mojang.realmsclient.gui.screens.RealmsSettingsScreen
- com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen
+ com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
- com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen
+ com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen$1
- com.mojang.realmsclient.gui.screens.RealmsTermsScreen
+ com.mojang.realmsclient.gui.screens.RealmsUploadScreen
- com.mojang.realmsclient.gui.screens.UploadResult
+ com.mojang.realmsclient.gui.screens.UploadResult$1
- com.mojang.realmsclient.gui.screens.UploadResult$Builder
- com.mojang.realmsclient.KeyCombo
+ com.mojang.realmsclient.package-info
+ com.mojang.realmsclient.RealmsMainScreen
- com.mojang.realmsclient.RealmsMainScreen$1
+ com.mojang.realmsclient.RealmsMainScreen$2
- com.mojang.realmsclient.RealmsMainScreen$3
+ com.mojang.realmsclient.RealmsMainScreen$4
- com.mojang.realmsclient.RealmsMainScreen$5
+ com.mojang.realmsclient.RealmsMainScreen$CloseButton
- com.mojang.realmsclient.RealmsMainScreen$Entry
+ com.mojang.realmsclient.RealmsMainScreen$HoveredElement
- com.mojang.realmsclient.RealmsMainScreen$NewsButton
+ com.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
- com.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
+ com.mojang.realmsclient.RealmsMainScreen$ServerEntry
- com.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
+ com.mojang.realmsclient.RealmsMainScreen$TrialEntry
- com.mojang.realmsclient.Unit
+ com.mojang.realmsclient.util.package-info
- com.mojang.realmsclient.util.task.CloseServerTask
+ com.mojang.realmsclient.util.task.ConnectTask
- com.mojang.realmsclient.util.task.DownloadTask
+ com.mojang.realmsclient.util.task.GetServerDetailsTask
- com.mojang.realmsclient.util.task.LongRunningTask
+ com.mojang.realmsclient.util.task.OpenServerTask
+ com.mojang.realmsclient.util.task.package-info
- com.mojang.realmsclient.util.task.ResettingGeneratedWorldTask
+ com.mojang.realmsclient.util.task.ResettingTemplateWorldTask
- com.mojang.realmsclient.util.task.ResettingWorldTask
+ com.mojang.realmsclient.util.task.RestoreTask
- com.mojang.realmsclient.util.task.SwitchMinigameTask
+ com.mojang.realmsclient.util.task.SwitchSlotTask
- com.mojang.realmsclient.util.task.WorldCreationTask
- net.minecraft.client.gui.screens.mco.package-info
+ net.minecraft.client.gui.screens.multiplayer.JoinMultiplayerScreen
- net.minecraft.client.gui.screens.multiplayer.package-info
- net.minecraft.client.gui.screens.multiplayer.SafetyScreen
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$Entry
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$LANHeader
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$NetworkServerEntry
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
+ net.minecraft.client.gui.screens.package-info
+ net.minecraft.client.gui.screens.packs.package-info
- net.minecraft.client.gui.screens.packs.PackSelectionModel
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$Entry
- net.minecraft.client.gui.screens.packs.PackSelectionModel$EntryBase
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$SelectedPackEntry
- net.minecraft.client.gui.screens.packs.PackSelectionModel$UnselectedPackEntry
+ net.minecraft.client.gui.screens.packs.PackSelectionScreen
- net.minecraft.client.gui.screens.packs.PackSelectionScreen$Watcher
+ net.minecraft.client.gui.screens.packs.TransferableSelectionList
- net.minecraft.client.gui.screens.packs.TransferableSelectionList$PackEntry
- net.minecraft.client.gui.screens.recipebook.AbstractFurnaceRecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.BlastingRecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.GhostRecipe
+ net.minecraft.client.gui.screens.recipebook.GhostRecipe$GhostIngredient
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
+ net.minecraft.client.gui.screens.recipebook.package-info
- net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.RecipeBookPage
- net.minecraft.client.gui.screens.recipebook.RecipeBookTabButton
+ net.minecraft.client.gui.screens.recipebook.RecipeButton
- net.minecraft.client.gui.screens.recipebook.RecipeCollection
+ net.minecraft.client.gui.screens.recipebook.RecipeShownListener
- net.minecraft.client.gui.screens.recipebook.RecipeUpdateListener
+ net.minecraft.client.gui.screens.recipebook.SmeltingRecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.SmokingRecipeBookComponent
+ net.minecraft.client.gui.screens.social.package-info
- net.minecraft.client.gui.screens.social.PlayerEntry
+ net.minecraft.client.gui.screens.social.PlayerEntry$1
- net.minecraft.client.gui.screens.social.PlayerEntry$2
+ net.minecraft.client.gui.screens.social.PlayerSocialManager
- net.minecraft.client.gui.screens.social.SocialInteractionsPlayerList
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$1
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen$2
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$Page
- net.minecraft.client.gui.screens.stream.package-info
- net.minecraft.client.map.Map$1
- net.minecraft.client.map.Map$3
- net.minecraft.client.model.AbstractZombieModel
+ net.minecraft.client.model.AgeableListModel
- net.minecraft.client.model.AnimationUtils
+ net.minecraft.client.model.ArmedModel
- net.minecraft.client.model.ArmorStandArmorModel
+ net.minecraft.client.model.ArmorStandModel
- net.minecraft.client.model.AxolotlModel
+ net.minecraft.client.model.BatModel
- net.minecraft.client.model.BeeModel
+ net.minecraft.client.model.BlazeModel
- net.minecraft.client.model.BoatModel
+ net.minecraft.client.model.BookModel
- net.minecraft.client.model.CatModel
+ net.minecraft.client.model.ChestedHorseModel
- net.minecraft.client.model.ChickenModel
+ net.minecraft.client.model.CodModel
- net.minecraft.client.model.ColorableAgeableListModel
+ net.minecraft.client.model.ColorableHierarchicalModel
- net.minecraft.client.model.CowModel
+ net.minecraft.client.model.CreeperModel
- net.minecraft.client.model.DolphinModel
+ net.minecraft.client.model.DrownedModel
- net.minecraft.client.model.ElytraModel
+ net.minecraft.client.model.EndermanModel
- net.minecraft.client.model.EndermiteModel
+ net.minecraft.client.model.EntityModel
- net.minecraft.client.model.EvokerFangsModel
+ net.minecraft.client.model.FoxModel
- net.minecraft.client.model.GhastModel
+ net.minecraft.client.model.GiantZombieModel
+ net.minecraft.client.multiplayer.ClientPacketListener
- net.minecraft.client.multiplayer.ClientPacketListener$1
+ net.minecraft.client.multiplayer.ClientSuggestionProvider
- net.minecraft.client.multiplayer.MultiPlayerGameMode
- net.minecraft.client.multiplayer.package-info
+ net.minecraft.client.multiplayer.PlayerInfo
- net.minecraft.client.multiplayer.ServerAddress
+ net.minecraft.client.multiplayer.ServerData
- net.minecraft.client.multiplayer.ServerData$ServerPackStatus
+ net.minecraft.client.multiplayer.ServerList
- net.minecraft.client.multiplayer.ServerStatusPinger
+ net.minecraft.client.multiplayer.ServerStatusPinger$1
- net.minecraft.client.multiplayer.ServerStatusPinger$2
+ net.minecraft.client.multiplayer.ServerStatusPinger$2$1
+ net.minecraft.client.package-info
- net.minecraft.client.particle.AshParticle
+ net.minecraft.client.particle.AshParticle$Provider
- net.minecraft.client.particle.AttackSweepParticle
+ net.minecraft.client.particle.AttackSweepParticle$1
- net.minecraft.client.particle.AttackSweepParticle$Provider
- net.minecraft.client.particle.BarrierParticle$1
+ net.minecraft.client.particle.StationaryItemParticle
+ net.minecraft.client.particle.StationaryItemParticle$BarrierProvider
- net.minecraft.client.renderer.block.BlockModelShaper
+ net.minecraft.client.renderer.block.BlockRenderDispatcher
- net.minecraft.client.renderer.block.BlockRenderDispatcher$1
+ net.minecraft.client.renderer.block.LiquidBlockRenderer
+ net.minecraft.client.renderer.block.model.BakedQuad
- net.minecraft.client.renderer.block.model.BlockElement
+ net.minecraft.client.renderer.block.model.BlockElement$1
- net.minecraft.client.renderer.block.model.BlockElement$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementFace
- net.minecraft.client.renderer.block.model.BlockElementFace$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementRotation
- net.minecraft.client.renderer.block.model.BlockFaceUV
+ net.minecraft.client.renderer.block.model.BlockFaceUV$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel
+ net.minecraft.client.renderer.block.model.BlockModel$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel$GuiLight
+ net.minecraft.client.renderer.block.model.BlockModel$LoopException
- net.minecraft.client.renderer.block.model.BlockModelDefinition
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$Context
- net.minecraft.client.renderer.block.model.BlockModelDefinition$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$MissingVariantException
- net.minecraft.client.renderer.block.model.FaceBakery
+ net.minecraft.client.renderer.block.model.FaceBakery$1
- net.minecraft.client.renderer.block.model.ItemModelGenerator
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$1
- net.minecraft.client.renderer.block.model.ItemModelGenerator$Span
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$SpanFacing
- net.minecraft.client.renderer.block.model.ItemOverride
+ net.minecraft.client.renderer.block.model.ItemOverride$Deserializer
- net.minecraft.client.renderer.block.model.ItemOverride$Predicate
+ net.minecraft.client.renderer.block.model.ItemOverrides
- net.minecraft.client.renderer.block.model.ItemOverrides$1
+ net.minecraft.client.renderer.block.model.ItemOverrides$BakedOverride
- net.minecraft.client.renderer.block.model.ItemOverrides$PropertyMatcher
+ net.minecraft.client.renderer.block.model.ItemTransform
- net.minecraft.client.renderer.block.model.ItemTransform$Deserializer
+ net.minecraft.client.renderer.block.model.ItemTransforms
- net.minecraft.client.renderer.block.model.ItemTransforms$1
+ net.minecraft.client.renderer.block.model.ItemTransforms$Deserializer
- net.minecraft.client.renderer.block.model.ItemTransforms$TransformType
+ net.minecraft.client.renderer.block.model.multipart.AndCondition
- net.minecraft.client.renderer.block.model.multipart.Condition
+ net.minecraft.client.renderer.block.model.multipart.KeyValueCondition
- net.minecraft.client.renderer.block.model.multipart.MultiPart
+ net.minecraft.client.renderer.block.model.multipart.MultiPart$Deserializer
- net.minecraft.client.renderer.block.model.multipart.OrCondition
+ net.minecraft.client.renderer.block.model.multipart.package-info
+ net.minecraft.client.renderer.block.model.multipart.Selector
- net.minecraft.client.renderer.block.model.multipart.Selector$Deserializer
+ net.minecraft.client.renderer.block.model.MultiVariant
- net.minecraft.client.renderer.block.model.MultiVariant$Deserializer
- net.minecraft.client.renderer.block.model.package-info
+ net.minecraft.client.renderer.block.model.Variant
- net.minecraft.client.renderer.block.model.Variant$Deserializer
- net.minecraft.client.renderer.block.ModelBlockRenderer
+ net.minecraft.client.renderer.block.ModelBlockRenderer$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
- net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
+ net.minecraft.client.renderer.block.package-info
- net.minecraft.client.renderer.block.statemap.package-info
+ net.minecraft.client.renderer.entity.GoatRenderer
- net.minecraft.client.renderer.entity.GuardianRenderer
+ net.minecraft.client.renderer.entity.HoglinRenderer
- net.minecraft.client.renderer.entity.HorseRenderer
+ net.minecraft.client.renderer.entity.HumanoidMobRenderer
- net.minecraft.client.renderer.entity.HuskRenderer
+ net.minecraft.client.renderer.entity.IllagerRenderer
- net.minecraft.client.renderer.entity.IllusionerRenderer
+ net.minecraft.client.renderer.entity.IllusionerRenderer$1
- net.minecraft.client.renderer.entity.IronGolemRenderer
+ net.minecraft.client.renderer.entity.ItemEntityRenderer
- net.minecraft.client.renderer.entity.ItemFrameRenderer
+ net.minecraft.client.renderer.entity.ItemRenderer
+ net.minecraft.client.renderer.entity.layers.ArrowLayer
- net.minecraft.client.renderer.entity.layers.BeeStingerLayer
+ net.minecraft.client.renderer.entity.layers.CapeLayer
- net.minecraft.client.renderer.entity.layers.CarriedBlockLayer
+ net.minecraft.client.renderer.entity.layers.CatCollarLayer
- net.minecraft.client.renderer.entity.layers.CreeperPowerLayer
+ net.minecraft.client.renderer.entity.layers.CrossedArmsItemLayer
- net.minecraft.client.renderer.entity.layers.CustomHeadLayer
+ net.minecraft.client.renderer.entity.layers.Deadmau5EarsLayer
- net.minecraft.client.renderer.entity.layers.DolphinCarryingItemLayer
+ net.minecraft.client.renderer.entity.layers.DrownedOuterLayer
- net.minecraft.client.renderer.entity.layers.ElytraLayer
+ net.minecraft.client.renderer.entity.layers.EnderEyesLayer
- net.minecraft.client.renderer.entity.layers.EnergySwirlLayer
+ net.minecraft.client.renderer.entity.layers.EyesLayer
- net.minecraft.client.renderer.entity.layers.FoxHeldItemLayer
+ net.minecraft.client.renderer.entity.layers.HorseArmorLayer
- net.minecraft.client.renderer.entity.layers.HorseMarkingLayer
+ net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer
- net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer$1
+ net.minecraft.client.renderer.entity.layers.IronGolemCrackinessLayer
- net.minecraft.client.renderer.entity.layers.IronGolemFlowerLayer
+ net.minecraft.client.renderer.entity.layers.ItemInHandLayer
- net.minecraft.client.renderer.entity.layers.LlamaDecorLayer
+ net.minecraft.client.renderer.entity.layers.MushroomCowMushroomLayer
+ net.minecraft.client.renderer.entity.layers.package-info
- net.minecraft.client.renderer.entity.layers.PandaHoldsItemLayer
+ net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
- net.minecraft.client.renderer.entity.layers.PhantomEyesLayer
+ net.minecraft.client.renderer.entity.layers.PlayerItemInHandLayer
- net.minecraft.client.renderer.entity.layers.RenderLayer
+ net.minecraft.client.renderer.entity.layers.SaddleLayer
- net.minecraft.client.renderer.entity.layers.SheepFurLayer
+ net.minecraft.client.renderer.entity.layers.ShulkerHeadLayer
- net.minecraft.client.renderer.entity.layers.SlimeOuterLayer
+ net.minecraft.client.renderer.entity.layers.SnowGolemHeadLayer
- net.minecraft.client.renderer.entity.layers.SpiderEyesLayer
+ net.minecraft.client.renderer.entity.layers.SpinAttackEffectLayer
- net.minecraft.client.renderer.entity.layers.StrayClothingLayer
+ net.minecraft.client.renderer.entity.layers.StuckInBodyLayer
- net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer
+ net.minecraft.client.renderer.entity.layers.VillagerProfessionLayer
- net.minecraft.client.renderer.entity.layers.WitchItemLayer
+ net.minecraft.client.renderer.entity.layers.WitherArmorLayer
- net.minecraft.client.renderer.entity.layers.WolfCollarLayer
- net.minecraft.client.renderer.entity.LeashKnotRenderer
+ net.minecraft.client.renderer.entity.LightningBoltRenderer
- net.minecraft.client.renderer.entity.LivingEntityRenderer
+ net.minecraft.client.renderer.entity.LivingEntityRenderer$1
- net.minecraft.client.renderer.entity.LlamaRenderer
+ net.minecraft.client.renderer.entity.LlamaSpitRenderer
- net.minecraft.client.renderer.entity.MagmaCubeRenderer
+ net.minecraft.client.renderer.entity.MinecartRenderer
- net.minecraft.client.renderer.entity.MobRenderer
+ net.minecraft.client.renderer.entity.MushroomCowRenderer
- net.minecraft.client.renderer.entity.OcelotRenderer
- net.minecraft.client.renderer.entity.package-info
+ net.minecraft.client.renderer.entity.PaintingRenderer
- net.minecraft.client.renderer.entity.PandaRenderer
+ net.minecraft.client.renderer.entity.ParrotRenderer
- net.minecraft.client.renderer.entity.PhantomRenderer
- net.minecraft.client.renderer.entity.PiglinRenderer
+ net.minecraft.client.renderer.entity.PigRenderer
+ net.minecraft.client.renderer.entity.PillagerRenderer
- net.minecraft.client.renderer.entity.player.package-info
+ net.minecraft.client.renderer.entity.player.PlayerRenderer
- net.minecraft.client.renderer.entity.PolarBearRenderer
+ net.minecraft.client.renderer.entity.PufferfishRenderer
- net.minecraft.client.renderer.entity.RabbitRenderer
+ net.minecraft.client.renderer.entity.RavagerRenderer
- net.minecraft.client.renderer.entity.RenderLayerParent
+ net.minecraft.client.renderer.entity.SalmonRenderer
- net.minecraft.client.renderer.entity.SheepRenderer
+ net.minecraft.client.renderer.entity.ShulkerBulletRenderer
- net.minecraft.client.renderer.entity.ShulkerRenderer
+ net.minecraft.client.renderer.entity.SilverfishRenderer
- net.minecraft.client.renderer.entity.SkeletonRenderer
+ net.minecraft.client.renderer.entity.SlimeRenderer
- net.minecraft.client.renderer.entity.SnowGolemRenderer
+ net.minecraft.client.renderer.entity.SpectralArrowRenderer
- net.minecraft.client.renderer.entity.SpiderRenderer
+ net.minecraft.client.renderer.entity.SquidRenderer
- net.minecraft.client.renderer.entity.StrayRenderer
+ net.minecraft.client.renderer.entity.StriderRenderer
- net.minecraft.client.renderer.entity.ThrownItemRenderer
+ net.minecraft.client.renderer.entity.ThrownTridentRenderer
- net.minecraft.client.renderer.entity.TippableArrowRenderer
+ net.minecraft.client.renderer.entity.TntMinecartRenderer
- net.minecraft.client.renderer.entity.TntRenderer
+ net.minecraft.client.renderer.entity.TropicalFishRenderer
- net.minecraft.client.renderer.entity.TurtleRenderer
+ net.minecraft.client.renderer.entity.UndeadHorseRenderer
- net.minecraft.client.renderer.entity.VexRenderer
+ net.minecraft.client.renderer.entity.VillagerRenderer
- net.minecraft.client.renderer.entity.VindicatorRenderer
+ net.minecraft.client.renderer.entity.VindicatorRenderer$1
- net.minecraft.client.renderer.entity.WanderingTraderRenderer
+ net.minecraft.client.renderer.entity.WitchRenderer
- net.minecraft.client.renderer.entity.WitherBossRenderer
+ net.minecraft.client.renderer.entity.WitherSkeletonRenderer
- net.minecraft.client.renderer.entity.WitherSkullRenderer
+ net.minecraft.client.renderer.entity.WolfRenderer
- net.minecraft.client.renderer.entity.ZoglinRenderer
+ net.minecraft.client.renderer.entity.ZombieRenderer
- net.minecraft.client.renderer.entity.ZombieVillagerRenderer
+ net.minecraft.client.renderer.item.ItemProperties
- net.minecraft.client.renderer.item.ItemProperties$1
+ net.minecraft.client.renderer.item.ItemProperties$2
- net.minecraft.client.renderer.item.ItemProperties$CompassWobble
+ net.minecraft.client.renderer.item.ItemPropertyFunction
- net.minecraft.client.renderer.item.package-info
+ net.minecraft.client.renderer.package-info
- net.minecraft.client.renderer.texture.AbstractTexture
+ net.minecraft.client.renderer.texture.AtlasSet
- net.minecraft.client.renderer.texture.DynamicTexture
+ net.minecraft.client.renderer.texture.HttpTexture
- net.minecraft.client.renderer.texture.MipmapGenerator
+ net.minecraft.client.renderer.texture.MissingTextureAtlasSprite
- net.minecraft.client.renderer.texture.OverlayTexture
+ net.minecraft.client.renderer.texture.package-info
+ net.minecraft.client.renderer.texture.PreloadedTexture
- net.minecraft.client.renderer.texture.SimpleTexture
+ net.minecraft.client.renderer.texture.SimpleTexture$TextureImage
- net.minecraft.client.renderer.texture.Stitcher
+ net.minecraft.client.renderer.texture.Stitcher$Holder
- net.minecraft.client.renderer.texture.Stitcher$Region
+ net.minecraft.client.renderer.texture.Stitcher$SpriteLoader
- net.minecraft.client.renderer.texture.StitcherException
+ net.minecraft.client.renderer.texture.TextureAtlas
- net.minecraft.client.renderer.texture.TextureAtlas$Preparations
+ net.minecraft.client.renderer.texture.TextureAtlasSprite
- net.minecraft.client.renderer.texture.TextureAtlasSprite$1
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$AnimatedTexture
- net.minecraft.client.renderer.texture.TextureAtlasSprite$FrameInfo
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$Info
- net.minecraft.client.renderer.texture.TextureAtlasSprite$InterpolationData
+ net.minecraft.client.renderer.texture.TextureManager
- net.minecraft.client.renderer.texture.Tickable
- net.minecraft.client.resources.AssetIndex
+ net.minecraft.client.resources.ClientPackSource
- net.minecraft.client.resources.ClientPackSource$1
+ net.minecraft.client.resources.ClientPackSource$2
- net.minecraft.client.resources.DefaultClientPackResources
+ net.minecraft.client.resources.DefaultPlayerSkin
- net.minecraft.client.resources.DirectAssetIndex
+ net.minecraft.client.resources.FoliageColorReloadListener
- net.minecraft.client.resources.GrassColorReloadListener
+ net.minecraft.client.resources.language.ClientLanguage
- net.minecraft.client.resources.language.FormattedBidiReorder
+ net.minecraft.client.resources.language.I18n
- net.minecraft.client.resources.language.LanguageInfo
+ net.minecraft.client.resources.language.LanguageManager
- net.minecraft.client.resources.language.package-info
+ net.minecraft.client.resources.LegacyPackResourcesAdapter
- net.minecraft.client.resources.LegacyStuffWrapper
+ net.minecraft.client.resources.metadata.animation.AnimationFrame
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$1
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$FrameOutput
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSectionSerializer
+ net.minecraft.client.resources.metadata.animation.package-info
- net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection
+ net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection$Hat
- net.minecraft.client.resources.metadata.animation.VillagerMetadataSectionSerializer
- net.minecraft.client.resources.metadata.language.LanguageMetadataSection
+ net.minecraft.client.resources.metadata.language.LanguageMetadataSectionSerializer
- net.minecraft.client.resources.metadata.language.package-info
+ net.minecraft.client.resources.metadata.package-info
- net.minecraft.client.resources.metadata.texture.package-info
- net.minecraft.client.resources.metadata.texture.TextureMetadataSection
+ net.minecraft.client.resources.metadata.texture.TextureMetadataSectionSerializer
+ net.minecraft.client.resources.MobEffectTextureManager
+ net.minecraft.client.resources.model.BakedModel
- net.minecraft.client.resources.model.BlockModelRotation
+ net.minecraft.client.resources.model.BuiltInModel
- net.minecraft.client.resources.model.Material
+ net.minecraft.client.resources.model.ModelBakery
- net.minecraft.client.resources.model.ModelBakery$BlockStateDefinitionException
+ net.minecraft.client.resources.model.ModelBakery$ModelGroupKey
- net.minecraft.client.resources.model.ModelManager
+ net.minecraft.client.resources.model.ModelResourceLocation
- net.minecraft.client.resources.model.ModelState
+ net.minecraft.client.resources.model.MultiPartBakedModel
- net.minecraft.client.resources.model.MultiPartBakedModel$Builder
+ net.minecraft.client.resources.model.SimpleBakedModel
- net.minecraft.client.resources.model.SimpleBakedModel$Builder
+ net.minecraft.client.resources.model.UnbakedModel
- net.minecraft.client.resources.model.WeightedBakedModel
+ net.minecraft.client.resources.model.WeightedBakedModel$Builder
- net.minecraft.client.resources.model.WeightedBakedModel$WeightedModel
- net.minecraft.client.resources.PackResourcesAdapterV4
+ net.minecraft.client.resources.PaintingTextureManager
- net.minecraft.client.resources.SkinManager
+ net.minecraft.client.resources.SkinManager$1
- net.minecraft.client.resources.SkinManager$SkinTextureCallback
+ net.minecraft.client.resources.SplashManager
- net.minecraft.client.resources.TextureAtlasHolder
- net.minecraft.client.sounds.AudioStream
+ net.minecraft.client.sounds.ChannelAccess
- net.minecraft.client.sounds.ChannelAccess$ChannelHandle
+ net.minecraft.client.sounds.LoopingAudioStream
- net.minecraft.client.sounds.LoopingAudioStream$1
+ net.minecraft.client.sounds.LoopingAudioStream$AudioStreamProvider
- net.minecraft.client.sounds.LoopingAudioStream$NoCloseBuffer
+ net.minecraft.client.sounds.MusicManager
+ net.minecraft.client.sounds.package-info
- net.minecraft.client.sounds.SoundBufferLibrary
+ net.minecraft.client.sounds.SoundEngine
- net.minecraft.client.sounds.SoundEngineExecutor
+ net.minecraft.client.sounds.SoundEventListener
- net.minecraft.client.sounds.SoundManager
+ net.minecraft.client.sounds.SoundManager$1
- net.minecraft.client.sounds.SoundManager$2
+ net.minecraft.client.sounds.SoundManager$Preparations
- net.minecraft.client.sounds.SoundManager$Preparations$1
+ net.minecraft.client.sounds.WeighedSoundEvents
- net.minecraft.client.sounds.Weighted
- net.minecraft.client.tutorial.BundleTutorial
+ net.minecraft.client.tutorial.CompletedTutorialStepInstance
- net.minecraft.client.tutorial.CraftPlanksTutorialStep
+ net.minecraft.client.tutorial.FindTreeTutorialStepInstance
- net.minecraft.client.tutorial.MovementTutorialStepInstance
+ net.minecraft.client.tutorial.OpenInventoryTutorialStep
- net.minecraft.client.tutorial.package-info
- net.minecraft.client.tutorial.PunchTreeTutorialStepInstance
+ net.minecraft.client.tutorial.Tutorial
- net.minecraft.client.tutorial.Tutorial$1
+ net.minecraft.client.tutorial.Tutorial$TimedToast
- net.minecraft.client.tutorial.TutorialStepInstance
+ net.minecraft.client.tutorial.TutorialSteps
- net.minecraft.commands.arguments.AngleArgument
+ net.minecraft.commands.arguments.AngleArgument$1
- net.minecraft.commands.arguments.AngleArgument$SingleAngle
+ net.minecraft.commands.arguments.blocks.BlockInput
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.blocks.BlockStateArgument
- net.minecraft.commands.arguments.blocks.BlockStateParser
+ net.minecraft.commands.arguments.blocks.package-info
+ net.minecraft.commands.arguments.ColorArgument
- net.minecraft.commands.arguments.ComponentArgument
+ net.minecraft.commands.arguments.CompoundTagArgument
- net.minecraft.commands.arguments.coordinates.BlockPosArgument
+ net.minecraft.commands.arguments.coordinates.ColumnPosArgument
- net.minecraft.commands.arguments.coordinates.Coordinates
+ net.minecraft.commands.arguments.coordinates.LocalCoordinates
- net.minecraft.commands.arguments.coordinates.package-info
- net.minecraft.commands.arguments.coordinates.RotationArgument
+ net.minecraft.commands.arguments.coordinates.SwizzleArgument
- net.minecraft.commands.arguments.coordinates.Vec2Argument
+ net.minecraft.commands.arguments.coordinates.Vec3Argument
- net.minecraft.commands.arguments.coordinates.WorldCoordinate
+ net.minecraft.commands.arguments.coordinates.WorldCoordinates
- net.minecraft.commands.arguments.DimensionArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument
- net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
+ net.minecraft.commands.arguments.EntityArgument
- net.minecraft.commands.arguments.EntityArgument$Serializer
+ net.minecraft.commands.arguments.EntitySummonArgument
- net.minecraft.commands.arguments.GameProfileArgument
+ net.minecraft.commands.arguments.GameProfileArgument$Result
- net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
+ net.minecraft.commands.arguments.item.FunctionArgument
- net.minecraft.commands.arguments.item.FunctionArgument$1
+ net.minecraft.commands.arguments.item.FunctionArgument$2
- net.minecraft.commands.arguments.item.FunctionArgument$Result
+ net.minecraft.commands.arguments.item.ItemArgument
- net.minecraft.commands.arguments.item.ItemInput
+ net.minecraft.commands.arguments.item.ItemParser
- net.minecraft.commands.arguments.item.ItemPredicateArgument
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$ItemPredicate
- net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$TagPredicate
- net.minecraft.commands.arguments.item.package-info
+ net.minecraft.commands.arguments.ItemEnchantmentArgument
- net.minecraft.commands.arguments.MessageArgument
+ net.minecraft.commands.arguments.MessageArgument$Message
- net.minecraft.commands.arguments.MessageArgument$Part
+ net.minecraft.commands.arguments.MobEffectArgument
- net.minecraft.commands.arguments.NbtPathArgument
+ net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
- net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
+ net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$NbtPath
- net.minecraft.commands.arguments.NbtPathArgument$Node
+ net.minecraft.commands.arguments.NbtTagArgument
- net.minecraft.commands.arguments.ObjectiveArgument
+ net.minecraft.commands.arguments.ObjectiveCriteriaArgument
- net.minecraft.commands.arguments.OperationArgument
+ net.minecraft.commands.arguments.OperationArgument$Operation
- net.minecraft.commands.arguments.OperationArgument$SimpleOperation
+ net.minecraft.commands.arguments.package-info
+ net.minecraft.commands.arguments.ParticleArgument
- net.minecraft.commands.arguments.RangeArgument
+ net.minecraft.commands.arguments.RangeArgument$Floats
- net.minecraft.commands.arguments.RangeArgument$Ints
+ net.minecraft.commands.arguments.ResourceLocationArgument
- net.minecraft.commands.arguments.ScoreboardSlotArgument
- net.minecraft.commands.arguments.ScoreHolderArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument$Result
- net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
+ net.minecraft.commands.arguments.ScoreHolderArgument$Serializer
- net.minecraft.commands.arguments.selector.EntitySelector
+ net.minecraft.commands.arguments.selector.EntitySelector$1
- net.minecraft.commands.arguments.selector.EntitySelectorParser
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$1
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
+ net.minecraft.commands.arguments.selector.options.package-info
- net.minecraft.commands.arguments.selector.package-info
+ net.minecraft.commands.arguments.SlotArgument
- net.minecraft.commands.arguments.TeamArgument
+ net.minecraft.commands.arguments.TimeArgument
- net.minecraft.commands.arguments.UuidArgument
+ net.minecraft.commands.BrigadierExceptions
- net.minecraft.commands.CommandFunction
+ net.minecraft.commands.CommandFunction$CacheableFunction
- net.minecraft.commands.CommandFunction$CommandEntry
+ net.minecraft.commands.CommandFunction$Entry
- net.minecraft.commands.CommandFunction$FunctionEntry
+ net.minecraft.commands.CommandRuntimeException
+ net.minecraft.commands.Commands
- net.minecraft.commands.Commands$CommandSelection
+ net.minecraft.commands.Commands$ParseFunction
- net.minecraft.commands.CommandSource
+ net.minecraft.commands.CommandSource$1
- net.minecraft.commands.CommandSourceStack
- net.minecraft.commands.SharedSuggestionProvider
+ net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ net.minecraft.obfuscate.DontObfuscate
- net.minecraft.obfuscate.DontObfuscateOrShrink
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.realms.DisconnectedRealmsScreen
+ net.minecraft.realms.NarrationHelper
+ net.minecraft.realms.package-info
- net.minecraft.realms.RealmsBridge
+ net.minecraft.realms.RealmsConnect
- net.minecraft.realms.RealmsConnect$1
+ net.minecraft.realms.RealmsLabel
- net.minecraft.realms.RealmsObjectSelectionList
+ net.minecraft.realms.RealmsScreen
- net.minecraft.realms.RealmsServerAddress
+ net.minecraft.realms.RepeatedNarrator
- net.minecraft.realms.RepeatedNarrator$Params
- net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataPackCodec
+ net.minecraft.resources.RegistryFileCodec
- net.minecraft.resources.RegistryLookupCodec
+ net.minecraft.resources.RegistryReadOps
- net.minecraft.resources.RegistryReadOps$1
+ net.minecraft.resources.RegistryReadOps$ReadCache
- net.minecraft.resources.RegistryReadOps$ResourceAccess
+ net.minecraft.resources.RegistryReadOps$ResourceAccess$1
- net.minecraft.resources.RegistryReadOps$ResourceAccess$MemoryMap
+ net.minecraft.resources.RegistryWriteOps
- net.minecraft.resources.ResourceKey
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.Bootstrap
+ net.minecraft.server.Bootstrap$1
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
- net.minecraft.server.ChainedJsonException
+ net.minecraft.server.ChainedJsonException$1
- net.minecraft.server.ChainedJsonException$Entry
+ net.minecraft.server.commands.AdvancementCommands
- net.minecraft.server.commands.AdvancementCommands$1
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.AttributeCommand
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ClearInventoryCommands
+ net.minecraft.server.commands.CloneCommands
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$Mode
+ net.minecraft.server.commands.data.BlockDataAccessor
- net.minecraft.server.commands.data.BlockDataAccessor$1
+ net.minecraft.server.commands.data.DataAccessor
- net.minecraft.server.commands.data.DataCommands
+ net.minecraft.server.commands.data.DataCommands$DataManipulator
- net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
+ net.minecraft.server.commands.data.DataCommands$DataProvider
- net.minecraft.server.commands.data.EntityDataAccessor
+ net.minecraft.server.commands.data.EntityDataAccessor$1
- net.minecraft.server.commands.data.package-info
- net.minecraft.server.commands.data.StorageDataAccessor
+ net.minecraft.server.commands.data.StorageDataAccessor$1
- net.minecraft.server.commands.DataPackCommand
+ net.minecraft.server.commands.DataPackCommand$Inserter
+ net.minecraft.server.commands.DebugCommand
- net.minecraft.server.commands.DebugMobSpawningCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.DifficultyCommand
- net.minecraft.server.commands.EffectCommands
+ net.minecraft.server.commands.EmoteCommands
- net.minecraft.server.commands.EnchantCommand
+ net.minecraft.server.commands.ExecuteCommand
- net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
+ net.minecraft.server.commands.ExecuteCommand$CommandPredicate
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillCommand
+ net.minecraft.server.commands.FillCommand$Mode
- net.minecraft.server.commands.ForceLoadCommand
+ net.minecraft.server.commands.FunctionCommand
- net.minecraft.server.commands.GameModeCommand
+ net.minecraft.server.commands.GameRuleCommand
- net.minecraft.server.commands.GameRuleCommand$1
+ net.minecraft.server.commands.GiveCommand
- net.minecraft.server.commands.HelpCommand
+ net.minecraft.server.commands.ItemCommands
- net.minecraft.server.commands.KickCommand
+ net.minecraft.server.commands.KillCommand
- net.minecraft.server.commands.ListPlayersCommand
+ net.minecraft.server.commands.LocateBiomeCommand
- net.minecraft.server.commands.LocateCommand
+ net.minecraft.server.commands.LootCommand
- net.minecraft.server.commands.LootCommand$Callback
+ net.minecraft.server.commands.LootCommand$DropConsumer
- net.minecraft.server.commands.LootCommand$TailProvider
+ net.minecraft.server.commands.MsgCommand
- net.minecraft.server.commands.OpCommand
+ net.minecraft.server.commands.package-info
+ net.minecraft.server.commands.PardonCommand
- net.minecraft.server.commands.PardonIpCommand
+ net.minecraft.server.commands.ParticleCommand
- net.minecraft.server.commands.PlaySoundCommand
+ net.minecraft.server.commands.PublishCommand
- net.minecraft.server.commands.RaidCommand
+ net.minecraft.server.commands.RecipeCommand
- net.minecraft.server.commands.ReloadCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.SeedCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpectateCommand
+ net.minecraft.server.commands.SpreadPlayersCommand
- net.minecraft.server.commands.SpreadPlayersCommand$1
+ net.minecraft.server.commands.SpreadPlayersCommand$Position
- net.minecraft.server.commands.StopCommand
+ net.minecraft.server.commands.StopSoundCommand
- net.minecraft.server.commands.SummonCommand
+ net.minecraft.server.commands.TagCommand
- net.minecraft.server.commands.TeamCommand
+ net.minecraft.server.commands.TeamMsgCommand
- net.minecraft.server.commands.TeleportCommand
+ net.minecraft.server.commands.TeleportCommand$LookAt
- net.minecraft.server.commands.TellRawCommand
+ net.minecraft.server.commands.TimeCommand
- net.minecraft.server.commands.TitleCommand
+ net.minecraft.server.commands.TriggerCommand
- net.minecraft.server.commands.WeatherCommand
+ net.minecraft.server.commands.WhitelistCommand
- net.minecraft.server.commands.WorldBorderCommand
+ net.minecraft.server.ConsoleInput
- net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerSettings
- net.minecraft.server.dedicated.package-info
+ net.minecraft.server.dedicated.ServerWatchdog
- net.minecraft.server.dedicated.ServerWatchdog$1
+ net.minecraft.server.dedicated.Settings
- net.minecraft.server.dedicated.Settings$1
+ net.minecraft.server.dedicated.Settings$MutableValue
+ net.minecraft.server.Eula
+ net.minecraft.server.gui.MinecraftServerGui
- net.minecraft.server.gui.MinecraftServerGui$1
+ net.minecraft.server.gui.MinecraftServerGui$2
- net.minecraft.server.gui.package-info
- net.minecraft.server.gui.PlayerListComponent
+ net.minecraft.server.gui.StatsComponent
+ net.minecraft.server.level.BlockDestructionProgress
- net.minecraft.server.level.ChunkHolder
+ net.minecraft.server.level.ChunkHolder$1
- net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure
+ net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure$1
- net.minecraft.server.level.ChunkHolder$ChunkSaveDebug
+ net.minecraft.server.level.ChunkHolder$FullChunkStatus
- net.minecraft.server.level.ChunkHolder$LevelChangeListener
+ net.minecraft.server.level.ChunkHolder$PlayerProvider
- net.minecraft.server.level.ChunkMap
+ net.minecraft.server.level.ChunkMap$1
- net.minecraft.server.level.ChunkMap$2
+ net.minecraft.server.level.ChunkMap$DistanceManager
- net.minecraft.server.level.ChunkMap$TrackedEntity
+ net.minecraft.server.level.ChunkTaskPriorityQueue
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$1
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
- net.minecraft.server.level.ChunkTracker
+ net.minecraft.server.level.ColumnPos
- net.minecraft.server.level.DemoMode
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.package-info
+ net.minecraft.server.level.PlayerMap
- net.minecraft.server.level.PlayerRespawnLogic
- net.minecraft.server.level.progress.ChunkProgressListener
+ net.minecraft.server.level.progress.ChunkProgressListenerFactory
- net.minecraft.server.level.progress.LoggerChunkProgressListener
+ net.minecraft.server.level.progress.package-info
+ net.minecraft.server.level.progress.ProcessorChunkProgressListener
- net.minecraft.server.level.progress.StoringChunkProgressListener
+ net.minecraft.server.level.SectionTracker
- net.minecraft.server.level.ServerBossEvent
+ net.minecraft.server.level.ServerChunkCache
- net.minecraft.server.level.ServerChunkCache$1
+ net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
- net.minecraft.server.level.ServerEntity
+ net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerLevel$1
+ net.minecraft.server.level.ServerLevel$EntityCallbacks
- net.minecraft.server.level.ServerPlayer
+ net.minecraft.server.level.ServerPlayer$1
- net.minecraft.server.level.ServerPlayer$2
+ net.minecraft.server.level.ServerPlayer$3
- net.minecraft.server.level.ServerPlayerGameMode
+ net.minecraft.server.level.ThreadedLevelLightEngine
- net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
+ net.minecraft.server.level.Ticket
- net.minecraft.server.level.TicketType
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.level.WorldGenTickList
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.Main
- net.minecraft.server.Main$1
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$2
- net.minecraft.server.network.LegacyQueryHandler
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
- net.minecraft.server.network.package-info
- net.minecraft.server.network.ServerConnectionListener
+ net.minecraft.server.network.ServerConnectionListener$1
- net.minecraft.server.network.ServerConnectionListener$2
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ net.minecraft.server.network.ServerGamePacketListenerImpl
- net.minecraft.server.network.ServerGamePacketListenerImpl$1
+ net.minecraft.server.network.ServerGamePacketListenerImpl$2
- net.minecraft.server.network.ServerGamePacketListenerImpl$EntityInteraction
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl
- net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl
- net.minecraft.server.network.ServerLoginPacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$State
- net.minecraft.server.network.ServerPlayerConnection
+ net.minecraft.server.network.ServerStatusPacketListenerImpl
- net.minecraft.server.network.TextFilter
+ net.minecraft.server.network.TextFilter$1
- net.minecraft.server.network.TextFilter$FilteredText
+ net.minecraft.server.network.TextFilterClient
- net.minecraft.server.network.TextFilterClient$1
+ net.minecraft.server.network.TextFilterClient$IgnoreStrategy
- net.minecraft.server.network.TextFilterClient$PlayerContext
+ net.minecraft.server.network.TextFilterClient$RequestFailedException
+ net.minecraft.server.package-info
- net.minecraft.server.packs.AbstractPackResources
+ net.minecraft.server.packs.FilePackResources
- net.minecraft.server.packs.FolderPackResources
- net.minecraft.server.packs.metadata.MetadataSectionSerializer
+ net.minecraft.server.packs.metadata.pack.package-info
+ net.minecraft.server.packs.metadata.pack.PackMetadataSection
- net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
- net.minecraft.server.packs.metadata.package-info
+ net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackResources
- net.minecraft.server.packs.PackType
- net.minecraft.server.packs.repository.FolderRepositorySource
+ net.minecraft.server.packs.repository.Pack
- net.minecraft.server.packs.repository.Pack$PackConstructor
+ net.minecraft.server.packs.repository.Pack$Position
+ net.minecraft.server.packs.repository.package-info
- net.minecraft.server.packs.repository.PackCompatibility
+ net.minecraft.server.packs.repository.PackRepository
- net.minecraft.server.packs.repository.PackSource
+ net.minecraft.server.packs.repository.RepositorySource
- net.minecraft.server.packs.repository.ServerPacksSource
+ net.minecraft.server.packs.ResourcePackFileNotFoundException
- net.minecraft.server.packs.resources.FallbackResourceManager
+ net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.package-info
- net.minecraft.server.packs.resources.PreparableReloadListener
+ net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
- net.minecraft.server.packs.resources.ProfiledReloadInstance
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$1
- net.minecraft.server.packs.resources.ProfiledReloadInstance$State
- net.minecraft.server.packs.resources.ReloadableResourceManager
+ net.minecraft.server.packs.resources.ReloadInstance
+ net.minecraft.server.packs.resources.Resource
- net.minecraft.server.packs.resources.ResourceManager
+ net.minecraft.server.packs.resources.ResourceManager$Empty
- net.minecraft.server.packs.resources.ResourceManagerReloadListener
+ net.minecraft.server.packs.resources.ResourceProvider
- net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
+ net.minecraft.server.packs.resources.SimplePreparableReloadListener
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
- net.minecraft.server.packs.resources.SimpleReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadInstance$1
- net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
- net.minecraft.server.packs.resources.SimpleResource
- net.minecraft.server.packs.VanillaPackResources
+ net.minecraft.server.packs.VanillaPackResources$1
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.players.BanListEntry
+ net.minecraft.server.players.GameProfileCache
- net.minecraft.server.players.GameProfileCache$1
+ net.minecraft.server.players.GameProfileCache$GameProfileInfo
- net.minecraft.server.players.IpBanList
+ net.minecraft.server.players.IpBanListEntry
- net.minecraft.server.players.OldUsersConverter
+ net.minecraft.server.players.OldUsersConverter$1
- net.minecraft.server.players.OldUsersConverter$2
+ net.minecraft.server.players.OldUsersConverter$3
- net.minecraft.server.players.OldUsersConverter$4
+ net.minecraft.server.players.OldUsersConverter$5
- net.minecraft.server.players.OldUsersConverter$ConversionError
- net.minecraft.server.players.package-info
+ net.minecraft.server.players.PlayerList
- net.minecraft.server.players.PlayerList$1
+ net.minecraft.server.players.ServerOpList
- net.minecraft.server.players.ServerOpListEntry
+ net.minecraft.server.players.SleepStatus
- net.minecraft.server.players.StoredUserEntry
+ net.minecraft.server.players.StoredUserList
- net.minecraft.server.players.UserBanList
+ net.minecraft.server.players.UserBanListEntry
- net.minecraft.server.players.UserWhiteList
+ net.minecraft.server.players.UserWhiteListEntry
+ net.minecraft.server.rcon.NetworkDataOutputStream
- net.minecraft.server.rcon.package-info
- net.minecraft.server.rcon.PktUtils
+ net.minecraft.server.rcon.RconConsoleSource
+ net.minecraft.server.rcon.thread.GenericThread
- net.minecraft.server.rcon.thread.package-info
- net.minecraft.server.rcon.thread.QueryThreadGs4
+ net.minecraft.server.rcon.thread.QueryThreadGs4$RequestChallenge
- net.minecraft.server.rcon.thread.RconClient
+ net.minecraft.server.rcon.thread.RconThread
- net.minecraft.server.RunningOnDifferentThreadException
+ net.minecraft.server.ServerAdvancementManager
- net.minecraft.server.ServerFunctionLibrary
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerFunctionManager$QueuedCommand
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerResources
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.TickTask
+ net.minecraft.sounds.Music
- net.minecraft.sounds.Musics
- net.minecraft.sounds.package-info
+ net.minecraft.sounds.SoundEvent
- net.minecraft.sounds.SoundEvents
+ net.minecraft.sounds.SoundSource
+ net.minecraft.stats.package-info
+ net.minecraft.stats.RecipeBook
- net.minecraft.stats.RecipeBookSettings
+ net.minecraft.stats.RecipeBookSettings$TypeSettings
- net.minecraft.stats.ServerRecipeBook
+ net.minecraft.stats.ServerStatsCounter
- net.minecraft.stats.Stat
+ net.minecraft.stats.StatFormatter
+ net.minecraft.stats.Stats
- net.minecraft.stats.StatsCounter
- net.minecraft.stats.StatType
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.FluidTags
+ net.minecraft.tags.GameEventTags
- net.minecraft.tags.ItemTags
- net.minecraft.tags.package-info
+ net.minecraft.tags.SerializationTags
- net.minecraft.tags.SetTag
+ net.minecraft.tags.StaticTagHelper
- net.minecraft.tags.StaticTagHelper$1
+ net.minecraft.tags.StaticTagHelper$Wrapper
- net.minecraft.tags.StaticTags
+ net.minecraft.tags.Tag
- net.minecraft.tags.Tag$1
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$BuilderEntry
+ net.minecraft.tags.Tag$ElementEntry
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$Named
- net.minecraft.tags.Tag$OptionalElementEntry
+ net.minecraft.tags.Tag$OptionalTagEntry
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.TagCollection
- net.minecraft.tags.TagCollection$1
+ net.minecraft.tags.TagCollection$NetworkPayload
- net.minecraft.tags.TagContainer
+ net.minecraft.tags.TagContainer$1
- net.minecraft.tags.TagContainer$Builder
+ net.minecraft.tags.TagContainer$CollectionConsumer
- net.minecraft.tags.TagLoader
+ net.minecraft.tags.TagManager
- net.minecraft.tags.TagManager$1
+ net.minecraft.tags.TagManager$LoaderInfo
+ net.minecraft.util.BitStorage
- net.minecraft.util.ClampedNormalFloat
- net.minecraft.util.ConstantFloat
+ net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- net.minecraft.util.Crypt
+ net.minecraft.util.CryptException
- net.minecraft.util.CsvOutput
+ net.minecraft.util.CsvOutput$1
- net.minecraft.util.CsvOutput$Builder
+ net.minecraft.util.CubicSampler
- net.minecraft.util.CubicSampler$Vec3Fetcher
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
+ net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
- net.minecraft.util.datafix.fixes.BedItemColorFix
+ net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
- net.minecraft.util.datafix.fixes.BiomeFix
+ net.minecraft.util.datafix.fixes.BitStorageAlignFix
- net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
+ net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
- net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.BlockEntityIdFix
- net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
+ net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.fixes.CauldronRenameFix
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ net.minecraft.util.datafix.fixes.ChunkStatusFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix2
+ net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
- net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
+ net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
- net.minecraft.util.datafix.fixes.DyeItemRenameFix
+ net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
- net.minecraft.util.datafix.fixes.EntityBlockStateFix
+ net.minecraft.util.datafix.fixes.EntityCatSplitFix
- net.minecraft.util.datafix.fixes.EntityCodSalmonFix
+ net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
+ net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
- net.minecraft.util.datafix.fixes.EntityHealthFix
+ net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
- net.minecraft.util.datafix.fixes.EntityHorseSplitFix
+ net.minecraft.util.datafix.fixes.EntityIdFix
- net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
- net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
- net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
+ net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
- net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
+ net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
- net.minecraft.util.datafix.fixes.EntityRenameFix
+ net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
- net.minecraft.util.datafix.fixes.EntityShulkerColorFix
+ net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
- net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
+ net.minecraft.util.datafix.fixes.EntityStringUuidFix
- net.minecraft.util.datafix.fixes.EntityTheRenameningFix
+ net.minecraft.util.datafix.fixes.EntityTippedArrowFix
- net.minecraft.util.datafix.fixes.EntityUUIDFix
+ net.minecraft.util.datafix.fixes.EntityWolfColorFix
- net.minecraft.util.datafix.fixes.EntityZombieSplitFix
+ net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
- net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
+ net.minecraft.util.datafix.fixes.ForcePoiRebuild
- net.minecraft.util.datafix.fixes.FurnaceRecipeFix
+ net.minecraft.util.datafix.fixes.GossipUUIDFix
- net.minecraft.util.datafix.fixes.HeightmapRenamingFix
+ net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
- net.minecraft.util.datafix.fixes.ItemBannerColorFix
+ net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.ItemIdFix
+ net.minecraft.util.datafix.fixes.ItemLoreFix
- net.minecraft.util.datafix.fixes.ItemPotionFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix
- net.minecraft.util.datafix.fixes.ItemRenameFix$1
+ net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.ItemSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
+ net.minecraft.util.datafix.fixes.ItemStackUUIDFix
- net.minecraft.util.datafix.fixes.ItemWaterPotionFix
+ net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- net.minecraft.util.datafix.fixes.JigsawPropertiesFix
+ net.minecraft.util.datafix.fixes.JigsawRotationFix
- net.minecraft.util.datafix.fixes.LeavesFix
+ net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
- net.minecraft.util.datafix.fixes.LeavesFix$Section
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.LevelUUIDFix
- net.minecraft.util.datafix.fixes.MapIdFix
+ net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
- net.minecraft.util.datafix.fixes.MissingDimensionFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRename
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
- net.minecraft.util.datafix.fixes.RenameBiomesFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
+ net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.SwimStatsRenameFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WriteAndReadFix
- net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
- net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.PackedBitStorage
+ net.minecraft.util.datafix.schemas.NamespacedSchema
- net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.package-info
+ net.minecraft.util.datafix.schemas.V100
- net.minecraft.util.datafix.schemas.V102
+ net.minecraft.util.datafix.schemas.V1022
- net.minecraft.util.datafix.schemas.V106
+ net.minecraft.util.datafix.schemas.V107
- net.minecraft.util.datafix.schemas.V1125
+ net.minecraft.util.datafix.schemas.V135
- net.minecraft.util.datafix.schemas.V143
+ net.minecraft.util.datafix.schemas.V1451
- net.minecraft.util.datafix.schemas.V1451_1
+ net.minecraft.util.datafix.schemas.V1451_2
- net.minecraft.util.datafix.schemas.V1451_3
+ net.minecraft.util.datafix.schemas.V1451_4
- net.minecraft.util.datafix.schemas.V1451_5
+ net.minecraft.util.datafix.schemas.V1451_6
- net.minecraft.util.datafix.schemas.V1451_7
+ net.minecraft.util.datafix.schemas.V1460
- net.minecraft.util.datafix.schemas.V1460$1
+ net.minecraft.util.datafix.schemas.V1466
- net.minecraft.util.datafix.schemas.V1470
+ net.minecraft.util.datafix.schemas.V1481
- net.minecraft.util.datafix.schemas.V1483
+ net.minecraft.util.datafix.schemas.V1486
- net.minecraft.util.datafix.schemas.V1510
+ net.minecraft.util.datafix.schemas.V1800
- net.minecraft.util.datafix.schemas.V1801
+ net.minecraft.util.datafix.schemas.V1904
- net.minecraft.util.datafix.schemas.V1906
+ net.minecraft.util.datafix.schemas.V1909
- net.minecraft.util.datafix.schemas.V1920
+ net.minecraft.util.datafix.schemas.V1928
- net.minecraft.util.datafix.schemas.V1929
+ net.minecraft.util.datafix.schemas.V1931
- net.minecraft.util.datafix.schemas.V2100
+ net.minecraft.util.datafix.schemas.V2501
- net.minecraft.util.datafix.schemas.V2502
+ net.minecraft.util.datafix.schemas.V2505
- net.minecraft.util.datafix.schemas.V2509
+ net.minecraft.util.datafix.schemas.V2519
- net.minecraft.util.datafix.schemas.V2522
+ net.minecraft.util.datafix.schemas.V2551
- net.minecraft.util.datafix.schemas.V2568
+ net.minecraft.util.datafix.schemas.V2571
+ net.minecraft.util.datafix.schemas.V2704
- net.minecraft.util.datafix.schemas.V501
+ net.minecraft.util.datafix.schemas.V700
- net.minecraft.util.datafix.schemas.V701
+ net.minecraft.util.datafix.schemas.V702
- net.minecraft.util.datafix.schemas.V703
+ net.minecraft.util.datafix.schemas.V704
- net.minecraft.util.datafix.schemas.V704$1
+ net.minecraft.util.datafix.schemas.V705
- net.minecraft.util.datafix.schemas.V705$1
+ net.minecraft.util.datafix.schemas.V808
- net.minecraft.util.datafix.schemas.V99
+ net.minecraft.util.datafix.schemas.V99$1
+ net.minecraft.util.DebugBuffer
- net.minecraft.util.DirectoryLock
+ net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.ExceptionCollector
+ net.minecraft.util.ExtraCodecs
- net.minecraft.util.ExtraCodecs$1
- net.minecraft.util.FloatProvider
- net.minecraft.util.GlslPreprocessor$1
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HeapDumper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$1
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$PathEntry
+ net.minecraft.util.profiling.ContinuousProfiler
- net.minecraft.util.profiling.EmptyProfileResults
+ net.minecraft.util.profiling.FilledProfileResults
- net.minecraft.util.profiling.FilledProfileResults$1
+ net.minecraft.util.profiling.FilledProfileResults$CounterCollector
- net.minecraft.util.profiling.InactiveProfiler
- net.minecraft.util.profiling.package-info
+ net.minecraft.util.profiling.ProfileCollector
- net.minecraft.util.profiling.ProfileResults
+ net.minecraft.util.profiling.ProfilerFiller
- net.minecraft.util.profiling.ProfilerFiller$1
+ net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.registry.MeasuredMetric
- net.minecraft.util.profiling.registry.MeasurementCategory
+ net.minecraft.util.profiling.registry.MeasurementRegistry
- net.minecraft.util.profiling.registry.Metric
- net.minecraft.util.profiling.registry.package-info
+ net.minecraft.util.profiling.registry.ProfilerMeasured
- net.minecraft.util.profiling.ResultField
+ net.minecraft.util.profiling.SingleTickProfiler
+ net.minecraft.util.random.SimpleWeightedRandomList
+ net.minecraft.util.random.Weight
+ net.minecraft.util.random.WeightedEntry$1
+ net.minecraft.util.random.WeightedEntry$Wrapper
+ net.minecraft.util.random.WeightedRandomList
+ net.minecraft.util.thread.BlockableEventLoop
- net.minecraft.util.thread.NamedThreadFactory
+ net.minecraft.util.thread.package-info
+ net.minecraft.util.thread.ProcessorHandle
- net.minecraft.util.thread.ProcessorHandle$1
+ net.minecraft.util.thread.ProcessorMailbox
- net.minecraft.util.thread.ReentrantBlockableEventLoop
+ net.minecraft.util.thread.StrictQueue
- net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
+ net.minecraft.util.thread.StrictQueue$IntRunnable
- net.minecraft.util.thread.StrictQueue$QueueStrictQueue
- net.minecraft.util.TrapezoidFloat
+ net.minecraft.util.Tuple
- net.minecraft.util.UniformFloat
- net.minecraft.util.Unit
+ net.minecraft.util.valueproviders.ConstantFloat
+ net.minecraft.util.valueproviders.FloatProvider
+ net.minecraft.util.valueproviders.IntProvider
+ net.minecraft.util.valueproviders.TrapezoidFloat
+ net.minecraft.util.valueproviders.UniformInt
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
+ net.minecraft.world.entity.ai.behavior.AnimalPanic
- net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
+ net.minecraft.world.entity.ai.behavior.BabyFollowAdult
- net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
+ net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
- net.minecraft.world.entity.ai.behavior.Behavior
+ net.minecraft.world.entity.ai.behavior.Behavior$Status
- net.minecraft.world.entity.ai.behavior.BehaviorUtils
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
+ net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
- net.minecraft.world.entity.ai.behavior.CountDownTemptationTicks
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
+ net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
- net.minecraft.world.entity.ai.behavior.DoNothing
+ net.minecraft.world.entity.ai.behavior.EntityTracker
- net.minecraft.world.entity.ai.behavior.EraseMemoryIf
+ net.minecraft.world.entity.ai.behavior.FollowTemptation
- net.minecraft.world.entity.ai.behavior.GateBehavior
+ net.minecraft.world.entity.ai.behavior.GateBehavior$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
- net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
+ net.minecraft.world.entity.ai.behavior.GoToWantedItem
- net.minecraft.world.entity.ai.behavior.HarvestFarmland
+ net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
- net.minecraft.world.entity.ai.behavior.InteractWith
+ net.minecraft.world.entity.ai.behavior.InteractWithDoor
- net.minecraft.world.entity.ai.behavior.JumpOnBed
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlace
- net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
+ net.minecraft.world.entity.ai.behavior.LongJumpMidJump
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
+ net.minecraft.world.entity.ai.behavior.ShufflingList$1
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.WeightedList$1
- net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry$1
- net.minecraft.world.entity.ai.goal.MoveIndoorsGoal
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
+ net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.PlayGoal
- net.minecraft.world.entity.ai.goal.TakeFlowerGoal
- net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
+ net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
- net.minecraft.world.entity.ai.goal.target.package-info
- net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
+ net.minecraft.world.entity.ai.goal.target.TargetGoal
+ net.minecraft.world.entity.ai.goal.TemptGoal
- net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
+ net.minecraft.world.entity.ai.goal.TryFindWaterGoal
- net.minecraft.world.entity.ai.goal.UseItemGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
+ net.minecraft.world.entity.ai.goal.WrappedGoal
- net.minecraft.world.entity.ai.goal.ZombieAttackGoal
+ net.minecraft.world.entity.ai.gossip.GossipContainer
- net.minecraft.world.entity.ai.gossip.GossipContainer$1
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
+ net.minecraft.world.entity.ai.memory.package-info
- net.minecraft.world.entity.ai.memory.WalkTarget
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.AxolotlHostileSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HostilesSensor
+ net.minecraft.world.entity.ai.sensing.package-info
+ net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
- net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.TemptingSensor
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
+ net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.ai.util.LandRandomPos
+ net.minecraft.world.entity.ai.util.package-info
- net.minecraft.world.entity.ai.util.RandomPos
- net.minecraft.world.entity.ai.village.package-info
+ net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.axolotl.Axolotl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
+ net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
- net.minecraft.world.entity.animal.axolotl.AxolotlAi
+ net.minecraft.world.entity.animal.axolotl.package-info
+ net.minecraft.world.entity.animal.axolotl.PlayDead
- net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Bucketable
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$1
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
+ net.minecraft.world.entity.animal.FlyingAnimal
- net.minecraft.world.entity.animal.Fox
+ net.minecraft.world.entity.animal.Fox$1
- net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
+ net.minecraft.world.entity.animal.Fox$FaceplantGoal
- net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
+ net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
- net.minecraft.world.entity.animal.Fox$FoxBreedGoal
+ net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
- net.minecraft.world.entity.animal.Fox$FoxFloatGoal
+ net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
- net.minecraft.world.entity.animal.Fox$FoxGroupData
+ net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
- net.minecraft.world.entity.animal.Fox$FoxLookControl
+ net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
- net.minecraft.world.entity.animal.Fox$FoxMoveControl
+ net.minecraft.world.entity.animal.Fox$FoxPanicGoal
- net.minecraft.world.entity.animal.Fox$FoxPounceGoal
+ net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
- net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
+ net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
- net.minecraft.world.entity.animal.Fox$SeekShelterGoal
+ net.minecraft.world.entity.animal.Fox$SleepGoal
- net.minecraft.world.entity.animal.Fox$StalkPreyGoal
+ net.minecraft.world.entity.animal.Fox$Type
+ net.minecraft.world.entity.animal.goat.GoatAi
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
+ net.minecraft.world.entity.animal.Panda
- net.minecraft.world.entity.animal.Panda$Gene
+ net.minecraft.world.entity.animal.Panda$PandaAttackGoal
- net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
+ net.minecraft.world.entity.animal.Panda$PandaBreedGoal
- net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
+ net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
- net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Panda$PandaMoveControl
- net.minecraft.world.entity.animal.Panda$PandaPanicGoal
+ net.minecraft.world.entity.animal.Panda$PandaRollGoal
- net.minecraft.world.entity.animal.Panda$PandaSitGoal
+ net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
- net.minecraft.world.entity.animal.Parrot
+ net.minecraft.world.entity.animal.Parrot$1
- net.minecraft.world.entity.animal.Pig
+ net.minecraft.world.entity.animal.PolarBear
- net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
- net.minecraft.world.entity.animal.Pufferfish
+ net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
- net.minecraft.world.entity.animal.Rabbit
+ net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
- net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
- net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
+ net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
- net.minecraft.world.entity.animal.Salmon
+ net.minecraft.world.entity.animal.Sheep
- net.minecraft.world.entity.animal.Sheep$1
+ net.minecraft.world.entity.animal.Sheep$2
- net.minecraft.world.entity.animal.ShoulderRidingEntity
+ net.minecraft.world.entity.animal.SnowGolem
- net.minecraft.world.entity.animal.Squid
+ net.minecraft.world.entity.animal.Squid$1
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$1
- net.minecraft.world.entity.animal.TropicalFish$Pattern
+ net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
- net.minecraft.world.entity.animal.Turtle
+ net.minecraft.world.entity.animal.Turtle$1
- net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
- net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
+ net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
- net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
+ net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BarrelBlockEntity
+ net.minecraft.world.level.block.entity.BarrelBlockEntity$1
- net.minecraft.world.level.block.entity.BaseContainerBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity$1
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
- net.minecraft.world.level.block.entity.BedBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ net.minecraft.world.level.block.entity.BellBlockEntity
- net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
+ net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
- net.minecraft.world.level.block.entity.BlockEntity
+ net.minecraft.world.level.block.entity.BlockEntityTicker
- net.minecraft.world.level.block.entity.BlockEntityType
+ net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
- net.minecraft.world.level.block.entity.BlockEntityType$Builder
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.ChestLidController
+ net.minecraft.world.level.block.entity.CommandBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity$1
+ net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
- net.minecraft.world.level.block.entity.ComparatorBlockEntity
+ net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.ContainerOpenersCounter
+ net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
- net.minecraft.world.level.block.entity.DispenserBlockEntity
+ net.minecraft.world.level.block.entity.DropperBlockEntity
- net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
+ net.minecraft.world.level.block.entity.FurnaceBlockEntity
- net.minecraft.world.level.block.entity.Hopper
+ net.minecraft.world.level.block.entity.HopperBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
- net.minecraft.world.level.block.entity.JukeboxBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity$1
+ net.minecraft.world.level.block.entity.LecternBlockEntity$2
- net.minecraft.world.level.block.entity.LidBlockEntity
+ net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
- net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.JungleTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
+ net.minecraft.world.level.block.LightningRodBlock
- net.minecraft.world.level.block.LiquidBlock
+ net.minecraft.world.level.block.LiquidBlockContainer
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MultifaceBlock
+ net.minecraft.world.level.block.MushroomBlock
- net.minecraft.world.level.block.MyceliumBlock
+ net.minecraft.world.level.block.NetherPortalBlock
- net.minecraft.world.level.block.NetherPortalBlock$1
- net.minecraft.world.level.block.NetherrackBlock
+ net.minecraft.world.level.block.NetherSproutsBlock
- net.minecraft.world.level.block.NetherVines
+ net.minecraft.world.level.block.NetherWartBlock
+ net.minecraft.world.level.block.NoteBlock
- net.minecraft.world.level.block.NyliumBlock
+ net.minecraft.world.level.block.ObserverBlock
- net.minecraft.world.level.block.OreBlock
+ net.minecraft.world.level.block.package-info
+ net.minecraft.world.level.block.PipeBlock
- net.minecraft.world.level.block.piston.MovingPistonBlock
- net.minecraft.world.level.block.piston.package-info
+ net.minecraft.world.level.block.piston.PistonBaseBlock
- net.minecraft.world.level.block.piston.PistonBaseBlock$1
+ net.minecraft.world.level.block.piston.PistonHeadBlock
- net.minecraft.world.level.block.piston.PistonHeadBlock$1
+ net.minecraft.world.level.block.piston.PistonMath
- net.minecraft.world.level.block.piston.PistonMath$1
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
+ net.minecraft.world.level.block.piston.PistonStructureResolver
- net.minecraft.world.level.block.PlayerHeadBlock
+ net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PointedDripstoneBlock
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PoweredBlock
- net.minecraft.world.level.block.PoweredRailBlock
+ net.minecraft.world.level.block.PoweredRailBlock$1
- net.minecraft.world.level.block.PressurePlateBlock
+ net.minecraft.world.level.block.PressurePlateBlock$1
- net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
+ net.minecraft.world.level.block.PumpkinBlock
- net.minecraft.world.level.block.RailBlock
+ net.minecraft.world.level.block.RailBlock$1
- net.minecraft.world.level.block.RailState
+ net.minecraft.world.level.block.RailState$1
+ net.minecraft.world.level.block.RedstoneLampBlock
- net.minecraft.world.level.block.RedStoneOreBlock
- net.minecraft.world.level.block.RedstoneTorchBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
- net.minecraft.world.level.block.RedstoneWallTorchBlock
+ net.minecraft.world.level.block.RedStoneWireBlock
- net.minecraft.world.level.block.RedStoneWireBlock$1
+ net.minecraft.world.level.block.RenderShape
- net.minecraft.world.level.block.RepeaterBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock
- net.minecraft.world.level.block.RespawnAnchorBlock$1
+ net.minecraft.world.level.block.RodBlock
- net.minecraft.world.level.block.RodBlock$1
+ net.minecraft.world.level.block.RootedDirtBlock
- net.minecraft.world.level.block.RootsBlock
+ net.minecraft.world.level.block.RotatedPillarBlock
- net.minecraft.world.level.block.RotatedPillarBlock$1
+ net.minecraft.world.level.block.Rotation
- net.minecraft.world.level.block.Rotation$1
+ net.minecraft.world.level.block.SandBlock
- net.minecraft.world.level.block.SaplingBlock
+ net.minecraft.world.level.block.ScaffoldingBlock
- net.minecraft.world.level.block.SculkSensorBlock
- net.minecraft.world.level.block.SeagrassBlock
+ net.minecraft.world.level.block.SeaPickleBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock
- net.minecraft.world.level.block.ShulkerBoxBlock$1
+ net.minecraft.world.level.block.SignBlock
- net.minecraft.world.level.block.SimpleWaterloggedBlock
+ net.minecraft.world.level.block.SkullBlock
- net.minecraft.world.level.block.SkullBlock$Type
+ net.minecraft.world.level.block.SkullBlock$Types
- net.minecraft.world.level.block.SlabBlock
+ net.minecraft.world.level.block.SlabBlock$1
- net.minecraft.world.level.block.SlimeBlock
+ net.minecraft.world.level.block.SmallDripleafBlock
- net.minecraft.world.level.block.SmithingTableBlock
+ net.minecraft.world.level.block.SmokerBlock
- net.minecraft.world.level.block.SnowLayerBlock
+ net.minecraft.world.level.block.SnowLayerBlock$1
- net.minecraft.world.level.block.SnowyDirtBlock
+ net.minecraft.world.level.block.SoulFireBlock
- net.minecraft.world.level.block.SoulSandBlock
+ net.minecraft.world.level.block.SoundType
- net.minecraft.world.level.block.SpawnerBlock
+ net.minecraft.world.level.block.SpongeBlock
- net.minecraft.world.level.block.SporeBlossomBlock
+ net.minecraft.world.level.block.SpreadingSnowyDirtBlock
- net.minecraft.world.level.block.StainedGlassBlock
+ net.minecraft.world.level.block.StainedGlassPaneBlock
- net.minecraft.world.level.block.StairBlock
+ net.minecraft.world.level.block.StairBlock$1
- net.minecraft.world.level.block.StandingSignBlock
+ net.minecraft.world.level.block.state.BlockBehaviour
- net.minecraft.world.level.block.state.BlockBehaviour$1
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
- net.minecraft.world.level.block.state.BlockBehaviour$Properties
+ net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
- net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
+ net.minecraft.world.level.block.state.BlockState
+ net.minecraft.world.level.block.state.package-info
- net.minecraft.world.level.block.state.pattern.BlockInWorld
+ net.minecraft.world.level.block.state.pattern.BlockPattern
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
- net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
+ net.minecraft.world.level.block.state.pattern.package-info
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
- net.minecraft.world.level.block.state.predicate.BlockPredicate
+ net.minecraft.world.level.block.state.predicate.BlockStatePredicate
- net.minecraft.world.level.block.state.predicate.package-info
+ net.minecraft.world.level.block.state.properties.AttachFace
- net.minecraft.world.level.block.state.properties.BambooLeaves
+ net.minecraft.world.level.block.state.properties.BedPart
- net.minecraft.world.level.block.state.properties.BellAttachType
+ net.minecraft.world.level.block.state.properties.BlockStateProperties
- net.minecraft.world.level.block.state.properties.BooleanProperty
+ net.minecraft.world.level.block.state.properties.ChestType
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.DripstoneThickness
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
- net.minecraft.world.level.block.state.properties.package-info
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$1
- net.minecraft.world.level.block.state.properties.Property$Value
+ net.minecraft.world.level.block.state.properties.RailShape
- net.minecraft.world.level.block.state.properties.RedstoneSide
+ net.minecraft.world.level.block.state.properties.SculkSensorPhase
- net.minecraft.world.level.block.state.properties.SlabType
+ net.minecraft.world.level.block.state.properties.StairsShape
- net.minecraft.world.level.block.state.properties.StructureMode
+ net.minecraft.world.level.block.state.properties.Tilt
- net.minecraft.world.level.block.state.properties.WallSide
+ net.minecraft.world.level.block.state.properties.WoodType
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
- net.minecraft.world.level.block.state.StateHolder$1
+ net.minecraft.world.level.block.StemBlock
- net.minecraft.world.level.block.StemGrownBlock
+ net.minecraft.world.level.block.StoneButtonBlock
- net.minecraft.world.level.block.StonecutterBlock
+ net.minecraft.world.level.block.StructureBlock
- net.minecraft.world.level.block.StructureBlock$1
+ net.minecraft.world.level.block.StructureVoidBlock
- net.minecraft.world.level.block.SugarCaneBlock
+ net.minecraft.world.level.block.SupportType
- net.minecraft.world.level.block.SupportType$1
+ net.minecraft.world.level.block.SupportType$2
- net.minecraft.world.level.block.SupportType$3
+ net.minecraft.world.level.block.SweetBerryBushBlock
- net.minecraft.world.level.block.TallFlowerBlock
+ net.minecraft.world.level.block.TallGrassBlock
- net.minecraft.world.level.block.TallSeagrassBlock
+ net.minecraft.world.level.block.TargetBlock
- net.minecraft.world.level.block.TintedGlassBlock
+ net.minecraft.world.level.block.TntBlock
- net.minecraft.world.level.block.TorchBlock
+ net.minecraft.world.level.block.TrapDoorBlock
- net.minecraft.world.level.block.TrapDoorBlock$1
+ net.minecraft.world.level.block.TrappedChestBlock
- net.minecraft.world.level.block.TripWireBlock
+ net.minecraft.world.level.block.TripWireBlock$1
- net.minecraft.world.level.block.TripWireHookBlock
+ net.minecraft.world.level.block.TripWireHookBlock$1
- net.minecraft.world.level.block.TurtleEggBlock
+ net.minecraft.world.level.block.TwistingVinesBlock
- net.minecraft.world.level.block.TwistingVinesPlantBlock
+ net.minecraft.world.level.block.VineBlock
- net.minecraft.world.level.block.VineBlock$1
+ net.minecraft.world.level.block.WallBannerBlock
- net.minecraft.world.level.block.WallBlock
+ net.minecraft.world.level.block.WallBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WeatheringCopper
+ net.minecraft.world.level.block.WeatheringCopper$WeatherState
- net.minecraft.world.level.block.WeatheringCopperFullBlock
+ net.minecraft.world.level.block.WeatheringCopperSlabBlock
- net.minecraft.world.level.block.WeatheringCopperStairBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeepingVinesBlock
+ net.minecraft.world.level.block.WeepingVinesPlantBlock
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoodButtonBlock
- net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
- net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$1
- net.minecraft.world.level.border.WorldBorder$BorderExtent
+ net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
- net.minecraft.world.level.border.WorldBorder$Settings
+ net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
+ net.minecraft.world.level.chunk.BulkSectionAccess
- net.minecraft.world.level.chunk.ChunkAccess
+ net.minecraft.world.level.chunk.ChunkBiomeContainer
- net.minecraft.world.level.chunk.ChunkGenerator
+ net.minecraft.world.level.chunk.ChunkSource
- net.minecraft.world.level.chunk.ChunkStatus
+ net.minecraft.world.level.chunk.ChunkStatus$ChunkType
- net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
+ net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
- net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
+ net.minecraft.world.level.chunk.DataLayer
- net.minecraft.world.level.chunk.EmptyLevelChunk
+ net.minecraft.world.level.chunk.EmptyLevelChunk$EmptyChunkBiomeContainer
- net.minecraft.world.level.chunk.FeatureAccess
+ net.minecraft.world.level.chunk.GlobalPalette
- net.minecraft.world.level.chunk.HashMapPalette
+ net.minecraft.world.level.chunk.ImposterProtoChunk
- net.minecraft.world.level.chunk.LevelChunk
+ net.minecraft.world.level.chunk.LevelChunk$1
- net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
+ net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
- net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ net.minecraft.world.level.chunk.LevelChunkSection
- net.minecraft.world.level.chunk.LightChunkGetter
+ net.minecraft.world.level.chunk.LinearPalette
- net.minecraft.world.level.chunk.OldDataLayer
- net.minecraft.world.level.chunk.package-info
+ net.minecraft.world.level.chunk.Palette
+ net.minecraft.world.level.chunk.PalettedContainer
- net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
- net.minecraft.world.level.chunk.PaletteResize
+ net.minecraft.world.level.chunk.ProtoChunk
- net.minecraft.world.level.chunk.ProtoTickList
+ net.minecraft.world.level.chunk.storage.ChunkSerializer
- net.minecraft.world.level.chunk.storage.ChunkStorage
+ net.minecraft.world.level.chunk.storage.EntityStorage
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.IOWorker$Priority
+ net.minecraft.world.level.chunk.storage.OldChunkStorage
- net.minecraft.world.level.chunk.storage.OldChunkStorage$1
+ net.minecraft.world.level.chunk.storage.OldChunkStorage$OldLevelChunk
- net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.SectionStorage
+ net.minecraft.world.level.chunk.UpgradeData
- net.minecraft.world.level.chunk.UpgradeData$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.dimension.DimensionDefaults
+ net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
- net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.CarverConfiguration
- net.minecraft.world.level.levelgen.carver.CarverDebugSettings
+ net.minecraft.world.level.levelgen.carver.CarvingContext
+ net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
+ net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
+ net.minecraft.world.level.levelgen.heightproviders.package-info
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$Properties
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
- net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
- net.minecraft.world.level.timers.package-info
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.level.timers.TimerQueue$1
+ net.minecraft.world.level.timers.TimerQueue$Event
+ net.minecraft.world.package-info
- net.minecraft.world.phys.AABB
+ net.minecraft.world.phys.BlockHitResult
- net.minecraft.world.phys.EntityHitResult
+ net.minecraft.world.phys.HitResult
- net.minecraft.world.phys.HitResult$Type
+ net.minecraft.world.phys.package-info
- net.minecraft.world.phys.shapes.ArrayVoxelShape
+ net.minecraft.world.phys.shapes.ArrayVoxelShape$1
- net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
+ net.minecraft.world.phys.shapes.BooleanOp
- net.minecraft.world.phys.shapes.CollisionContext
+ net.minecraft.world.phys.shapes.CubePointRange
- net.minecraft.world.phys.shapes.CubeVoxelShape
+ net.minecraft.world.phys.shapes.DiscreteCubeMerger
- net.minecraft.world.phys.shapes.DiscreteVoxelShape
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ net.minecraft.world.phys.shapes.EntityCollisionContext
- net.minecraft.world.phys.shapes.EntityCollisionContext$1
+ net.minecraft.world.phys.shapes.IdenticalMerger
- net.minecraft.world.phys.shapes.IndexMerger
+ net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
- net.minecraft.world.phys.shapes.IndirectMerger
+ net.minecraft.world.phys.shapes.NonOverlappingMerger
- net.minecraft.world.phys.shapes.OffsetDoubleList
- net.minecraft.world.phys.shapes.package-info
+ net.minecraft.world.phys.shapes.Shapes
- net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
+ net.minecraft.world.phys.shapes.SliceShape
- net.minecraft.world.phys.shapes.SubShape
+ net.minecraft.world.phys.shapes.VoxelShape
+ net.minecraft.world.phys.Vec2
- net.minecraft.world.phys.Vec3
+ net.minecraft.world.scores.criteria.ObjectiveCriteria
- net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
+ net.minecraft.world.scores.criteria.package-info
+ net.minecraft.world.scores.Objective
- net.minecraft.world.scores.package-info
- net.minecraft.world.scores.PlayerTeam
+ net.minecraft.world.scores.Score
- net.minecraft.world.scores.Scoreboard
+ net.minecraft.world.scores.ScoreboardSaveData
- net.minecraft.world.scores.Team
+ net.minecraft.world.scores.Team$CollisionRule
- net.minecraft.world.scores.Team$Visibility
```

</details>

<details><summary>com.mojang.math.Matrix3f</summary>

```diff
+ int ORDER
+ boolean invert()
+ float adjugateAndDet()
+ float determinant()
+ float trace()
+ int bufferIndex(int,int)
+ Matrix3f createScaleMatrix(float,float,float)
+ void add(Matrix3f)
+ void load(FloatBuffer,boolean)
+ void load(FloatBuffer)
+ void loadTransposed(FloatBuffer)
+ void mul(float)
+ void mul(Quaternion)
+ void sortSingularValues(Quaternion)
+ void store(FloatBuffer,boolean)
+ void store(FloatBuffer)
+ void storeTransposed(FloatBuffer)
+ void sub(Matrix3f)
```

</details>

<details><summary>com.mojang.math.Vector4f</summary>

```diff
+ boolean normalize()
+ float dot(Vector4f)
+ float w()
+ void <init>(Vector3f)
+ void add(float,float,float,float)
+ void lerp(Vector4f,float)
+ void mul(float)
+ void mul(Vector3f)
+ void perspectiveDivide()
+ void set(float,float,float,float)
+ void transform(Quaternion)
```

</details>
















<details><summary>net.minecraft.core.Cursor3D</summary>

```diff
+ int TYPE_CORNER
+ int TYPE_EDGE
+ int TYPE_FACE
+ int TYPE_INSIDE
```

</details>







<details><summary>net.minecraft.core.IdMapper</summary>

```diff
+ int DEFAULT
```

</details>



<details><summary>net.minecraft.core.QuartPos</summary>

```diff
+ int BITS
+ int SECTION_TO_QUARTS_BITS
+ int SIZE
```

</details>



<details><summary>net.minecraft.core.SectionPos</summary>

```diff
+ int PACKED_X_LENGTH
+ int PACKED_Y_LENGTH
+ int PACKED_Z_LENGTH
+ int RELATIVE_X_SHIFT
+ int RELATIVE_Y_SHIFT
+ int RELATIVE_Z_SHIFT
+ int SECTION_BITS
+ int SECTION_HALF_SIZE
+ int SECTION_MASK
+ int SECTION_MAX_INDEX
+ int SECTION_SIZE
+ int X_OFFSET
+ int Y_OFFSET
+ int Z_OFFSET
+ long PACKED_X_MASK
+ long PACKED_Y_MASK
+ long PACKED_Z_MASK
```

</details>




























<details><summary>net.minecraft.core.particles.ParticleTypes</summary>

```diff
+ SimpleParticleType LIGHT
```

</details>


















<details><summary>net.minecraft.data.models.BlockModelGenerators</summary>

```diff
+ void createLightBlockItems()
```

</details>











































<details><summary>net.minecraft.data.worldgen.BiomeDefaultFeatures</summary>

```diff
+ void caveSpawns(MobSpawnSettings$Builder)
+ void caveWaterSpawns(MobSpawnSettings$Builder)
- void ambientSpawns(MobSpawnSettings$Builder)
```

</details>



<details><summary>net.minecraft.data.worldgen.Features$States</summary>

```diff
+ BlockState DEEPSLATE
```

</details>

















<details><summary>net.minecraft.gametest.framework.GameTestServer</summary>

```diff
+ int PROGRESS_REPORT_INTERVAL
```

</details>





<details><summary>net.minecraft.gametest.framework.StructureUtils</summary>

```diff
+ int HOW_MANY_CHUNKS_TO_LOAD_IN_EACH_DIRECTION_OF_STRUCTURE
+ String DEFAULT_TEST_STRUCTURES_DIR
```

</details>


<details><summary>net.minecraft.gametest.framework.TestCommand</summary>

```diff
+ int DEFAULT_CLEAR_RADIUS
+ int DEFAULT_X_SIZE
+ int DEFAULT_Y_SIZE
+ int DEFAULT_Z_SIZE
+ int MAX_CLEAR_RADIUS
+ int SHOW_POS_DURATION_MS
+ int STRUCTURE_BLOCK_FULL_SEARCH_RADIUS
+ int STRUCTURE_BLOCK_NEARBY_SEARCH_RADIUS
+ int TEST_POS_Z_OFFSET_FROM_PLAYER
```

</details>



<details><summary>net.minecraft.locale.Language</summary>

```diff
+ String DEFAULT
```

</details>











<details><summary>net.minecraft.nbt.ListTag</summary>

```diff
+ int SELF_SIZE_IN_BITS
```

</details>

<details><summary>net.minecraft.nbt.LongArrayTag</summary>

```diff
+ int SELF_SIZE_IN_BITS
```

</details>

<details><summary>net.minecraft.nbt.LongTag</summary>

```diff
+ int SELF_SIZE_IN_BITS
```

</details>

<details><summary>net.minecraft.nbt.LongTag$Cache</summary>

```diff
+ int HIGH
+ int LOW
```

</details>






<details><summary>net.minecraft.nbt.SnbtPrinterTagVisitor</summary>

```diff
+ String ELEMENT_SPACING
+ String LIST_CLOSE
+ String LIST_OPEN
+ String LIST_TYPE_SEPARATOR
+ String NEWLINE
+ String STRUCT_CLOSE
+ String STRUCT_OPEN
```

</details>


<details><summary>net.minecraft.nbt.Tag</summary>

```diff
+ byte TAG_ANY_NUMERIC
+ byte TAG_BYTE
+ byte TAG_BYTE_ARRAY
+ byte TAG_COMPOUND
+ byte TAG_DOUBLE
+ byte TAG_END
+ byte TAG_FLOAT
+ byte TAG_INT
+ byte TAG_INT_ARRAY
+ byte TAG_LIST
+ byte TAG_LONG
+ byte TAG_LONG_ARRAY
+ byte TAG_SHORT
+ byte TAG_STRING
+ int ARRAY_HEADER
+ int MAX_DEPTH
+ int OBJECT_HEADER
+ int OBJECT_REFERENCE
+ int STRING_SIZE
```

</details>



<details><summary>net.minecraft.nbt.TextComponentTagVisitor</summary>

```diff
+ int INLINE_LIST_THRESHOLD
+ String ELEMENT_SPACING
+ String LIST_CLOSE
+ String LIST_OPEN
+ String LIST_TYPE_SEPARATOR
+ String NEWLINE
+ String STRUCT_CLOSE
+ String STRUCT_OPEN
```

</details>











<details><summary>net.minecraft.network.Varint21LengthFieldPrepender</summary>

```diff
+ int MAX_BYTES
```

</details>




























<details><summary>net.minecraft.network.protocol.game.ClientboundBossEventPacket</summary>

```diff
+ int FLAG_DARKEN
+ int FLAG_FOG
+ int FLAG_MUSIC
```

</details>







<details><summary>net.minecraft.network.protocol.game.ClientboundCommandsPacket</summary>

```diff
+ byte FLAG_CUSTOM_SUGGESTIONS
+ byte FLAG_EXECUTABLE
+ byte FLAG_REDIRECT
+ byte MASK_TYPE
+ byte TYPE_ARGUMENT
+ byte TYPE_LITERAL
+ byte TYPE_ROOT
```

</details>



<details><summary>net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket</summary>

```diff
+ int CARRIED_ITEM
+ int PLAYER_INVENTORY
```

</details>

<details><summary>net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket</summary>

```diff
+ int MAX_PAYLOAD_SIZE
```

</details>



<details><summary>net.minecraft.network.protocol.game.ClientboundGameEventPacket</summary>

```diff
+ int DEMO_PARAM_HINT_1
+ int DEMO_PARAM_HINT_2
+ int DEMO_PARAM_HINT_3
+ int DEMO_PARAM_HINT_4
+ int DEMO_PARAM_INTRO
```

</details>






<details><summary>net.minecraft.network.protocol.game.ClientboundMoveEntityPacket</summary>

```diff
+ double TRUNCATION_STEPS
```

</details>
















<details><summary>net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket</summary>

```diff
+ int POS_IN_SECTION_BITS
```

</details>










<details><summary>net.minecraft.network.protocol.game.ClientboundSetObjectivePacket</summary>

```diff
+ int METHOD_ADD
+ int METHOD_CHANGE
+ int METHOD_REMOVE
```

</details>

<details><summary>net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket</summary>

```diff
+ int MAX_COLLISION_LENGTH
+ int MAX_VISIBILITY_LENGTH
+ int METHOD_ADD
+ int METHOD_CHANGE
+ int METHOD_JOIN
+ int METHOD_LEAVE
+ int METHOD_REMOVE
```

</details>





<details><summary>net.minecraft.network.protocol.game.ClientboundStopSoundPacket</summary>

```diff
+ int HAS_SOUND
+ int HAS_SOURCE
```

</details>




<details><summary>net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket</summary>

```diff
+ int FLAG_AMBIENT
+ int FLAG_SHOW_ICON
+ int FLAG_VISIBLE
```

</details>






<details><summary>net.minecraft.network.protocol.game.ServerboundClientInformationPacket</summary>

```diff
+ int MAX_LANGUAGE_LENGTH
```

</details>
















<details><summary>net.minecraft.network.protocol.game.ServerboundPlayerInputPacket</summary>

```diff
+ int FLAG_JUMPING
+ int FLAG_SHIFT_KEY_DOWN
```

</details>








<details><summary>net.minecraft.network.protocol.game.ServerboundSignUpdatePacket</summary>

```diff
+ int MAX_STRING_LENGTH
```

</details>



<details><summary>net.minecraft.network.protocol.handshake.ClientIntentionPacket</summary>

```diff
+ int MAX_HOST_LENGTH
```

</details>


<details><summary>net.minecraft.network.protocol.login.ClientboundCustomQueryPacket</summary>

```diff
+ int MAX_PAYLOAD_SIZE
```

</details>



<details><summary>net.minecraft.network.protocol.login.ServerboundCustomQueryPacket</summary>

```diff
+ int MAX_PAYLOAD_SIZE
```

</details>




<details><summary>net.minecraft.network.protocol.status.ServerStatus</summary>

```diff
+ int FAVICON_HEIGHT
+ int FAVICON_WIDTH
```

</details>
















<details><summary>net.minecraft.network.syncher.SynchedEntityData</summary>

```diff
+ int EOF_MARKER
+ int MAX_ID_VALUE
```

</details>






<details><summary>net.minecraft.util.LinearCongruentialGenerator</summary>

```diff
+ long INCREMENT
+ long MULTIPLIER
```

</details>


<details><summary>net.minecraft.util.ParticleUtils</summary>

```diff
+ void spawnParticlesAlongAxis(UniformInt)
+ void spawnParticlesOnBlockFaces(UniformInt)
- void spawnParticlesAlongAxis(IntRange)
- void spawnParticlesOnBlockFaces(IntRange)
```

</details>




<details><summary>net.minecraft.util.StringDecomposer</summary>

```diff
+ char REPLACEMENT_CHAR
```

</details>



<details><summary>net.minecraft.util.TimeUtil</summary>

```diff
+ UniformInt rangeOfSeconds(int,int)
- IntRange rangeOfSeconds(int,int)
```

</details>






<details><summary>net.minecraft.world.Container</summary>

```diff
+ int LARGE_MAX_STACK_SIZE
```

</details>







<details><summary>net.minecraft.world.Snooper</summary>

```diff
+ int SNOOPER_VERSION
+ long DATA_SEND_FREQUENCY
+ String POLL_HOST
```

</details>




<details><summary>net.minecraft.world.damagesource.CombatTracker</summary>

```diff
+ int RESET_COMBAT_STATUS_TIME
+ int RESET_DAMAGE_STATUS_TIME
```

</details>








<details><summary>net.minecraft.world.entity.AgeableMob</summary>

```diff
+ int BABY_START_AGE
+ int FORCED_AGE_PARTICLE_TICKS
```

</details>

<details><summary>net.minecraft.world.entity.AreaEffectCloud</summary>

```diff
+ float MAX_RADIUS
+ int TIME_BETWEEN_APPLICATIONS
```

</details>





<details><summary>net.minecraft.world.entity.EntityType</summary>

```diff
+ EntityType GOAT
+ float MAGIC_HORSE_WIDTH
+ String ENTITY_TAG
```

</details>



<details><summary>net.minecraft.world.entity.ExperienceOrb</summary>

```diff
+ double ORB_MERGE_DISTANCE
+ int ENTITY_SCAN_PERIOD
+ int LIFETIME
+ int MAX_FOLLOW_DIST
+ int ORB_GROUPS_PER_AREA
+ int repairPlayerItems(Player,int)
```

</details>


<details><summary>net.minecraft.world.entity.ItemBasedSteering</summary>

```diff
+ int MAX_BOOST_TIME
+ int MIN_BOOST_TIME
```

</details>

<details><summary>net.minecraft.world.entity.LightningBolt</summary>

```diff
+ int START_LIFE
```

</details>







<details><summary>net.minecraft.world.entity.Pose</summary>

```diff
+ Pose LONG_JUMPING
```

</details>















<details><summary>net.minecraft.world.entity.ai.behavior.AcquirePoi</summary>

```diff
+ int BATCH_SIZE
+ int RATE
+ int SCAN_RANGE
```

</details>

<details><summary>net.minecraft.world.entity.ai.behavior.AnimalMakeLove</summary>

```diff
+ int BREED_RANGE
+ int MAX_DURATION
+ int MIN_DURATION
```

</details>




<details><summary>net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids</summary>

```diff
+ float CHASE_SPEED_MODIFIER
+ float FLEE_SPEED_MODIFIER
+ int AVERAGE_WAIT_TIME_BETWEEN_RUNS
+ int MAX_CHASERS_PER_TARGET
+ int MAX_FLEE_XZ_DIST
+ int MAX_FLEE_Y_DIST
```

</details>




<details><summary>net.minecraft.world.entity.ai.behavior.RingBell</summary>

```diff
+ float BELL_RING_CHANCE
+ int RING_BELL_FROM_DISTANCE
```

</details>


<details><summary>net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget</summary>

```diff
+ int BATCH_SIZE
+ int CACHE_TIMEOUT
+ int OK_DISTANCE_SQR
+ int RATE
```

</details>

<details><summary>net.minecraft.world.entity.ai.behavior.SetHiddenState</summary>

```diff
+ int HIDE_TIMEOUT
```

</details>


<details><summary>net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach</summary>

```diff
+ int PROJECTILE_ATTACK_RANGE_BUFFER
```

</details>


<details><summary>net.minecraft.world.entity.ai.behavior.SleepInBed</summary>

```diff
+ int COOLDOWN_AFTER_BEING_WOKEN
```

</details>


<details><summary>net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid</summary>

```diff
+ Consumer onTargetErased
+ int TIMEOUT_TO_GET_WITHIN_ATTACK_RANGE
+ boolean lambda$new$1(LivingEntity)
+ boolean lambda$new$2(LivingEntity)
+ void <init>(Consumer)
+ void <init>(Consumer)
+ void lambda$new$0(Mob)
+ void lambda$new$3(Mob)
- boolean lambda$new$0(LivingEntity)
```

</details>

<details><summary>net.minecraft.world.entity.ai.behavior.StrollAroundPoi</summary>

```diff
+ int MIN_TIME_BETWEEN_STROLLS
+ int STROLL_MAX_XZ_DIST
+ int STROLL_MAX_Y_DIST
```

</details>


<details><summary>net.minecraft.world.entity.ai.behavior.TradeWithVillager</summary>

```diff
+ float SPEED_MODIFIER
+ int INTERACT_DIST_SQR
```

</details>


<details><summary>net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi</summary>

```diff
+ int MAX_DISTANCE
```

</details>

<details><summary>net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll</summary>

```diff
+ int MAX_XZ_DIST
+ int MAX_Y_DIST
```

</details>

<details><summary>net.minecraft.world.entity.ai.behavior.VillagerGoalPackages</summary>

```diff
+ float STROLL_SPEED_MODIFIER
```

</details>




<details><summary>net.minecraft.world.entity.ai.control.BodyRotationControl</summary>

```diff
+ int DELAY_UNTIL_STARTING_TO_FACE_FORWARD
+ int HEAD_STABLE_ANGLE
+ int HOW_LONG_IT_TAKES_TO_FACE_FORWARD
```

</details>










<details><summary>net.minecraft.world.entity.ai.goal.EatBlockGoal</summary>

```diff
+ int EAT_ANIMATION_TICKS
```

</details>


<details><summary>net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal</summary>

```diff
+ int INTERVAL_TICKS
```

</details>

<details><summary>net.minecraft.world.entity.ai.goal.FollowOwnerGoal</summary>

```diff
+ int MAX_HORIZONTAL_DISTANCE_FROM_PLAYER_WHEN_TELEPORTING
+ int MAX_VERTICAL_DISTANCE_FROM_PLAYER_WHEN_TELEPORTING
+ int MIN_HORIZONTAL_DISTANCE_FROM_PLAYER_WHEN_TELEPORTING
+ int TELEPORT_WHEN_DISTANCE_IS
```

</details>


<details><summary>net.minecraft.world.entity.ai.goal.GoalSelector</summary>

```diff
+ int tickCount
```

</details>




<details><summary>net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal</summary>

```diff
+ int CARAVAN_LIMIT
```

</details>


<details><summary>net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal</summary>

```diff
+ int MAX_XZ_DIST
+ int MAX_Y_DIST
```

</details>









<details><summary>net.minecraft.world.entity.ai.sensing.NearestItemSensor</summary>

```diff
+ int MAX_DISTANCE_TO_WANTED_ITEM
+ long XZ_RANGE
+ long Y_RANGE
```

</details>




<details><summary>net.minecraft.world.entity.animal.horse.Llama</summary>

```diff
+ int MAX_STRENGTH
+ int VARIANTS
```

</details>














<details><summary>net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase</summary>

```diff
+ int ROAR_DURATION
```

</details>

<details><summary>net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase</summary>

```diff
+ int SITTING_ATTACK_VIEW_RANGE
+ int SITTING_ATTACK_Y_VIEW_RANGE
+ int SITTING_CHARGE_VIEW_RANGE
+ int SITTING_SCANNING_IDLE_TICKS
```

</details>





<details><summary>net.minecraft.world.entity.decoration.ArmorStand</summary>

```diff
+ boolean ENABLE_ARMS
+ double CHEST_OFFSET
+ double FEET_OFFSET
+ double HEAD_OFFSET
+ double LEGS_OFFSET
+ int CLIENT_FLAG_MARKER
+ int CLIENT_FLAG_NO_BASEPLATE
+ int CLIENT_FLAG_SHOW_ARMS
+ int CLIENT_FLAG_SMALL
+ int DISABLE_PUTTING_OFFSET
+ int DISABLE_TAKING_OFFSET
+ int WOBBLE_TIME
```

</details>




<details><summary>net.minecraft.world.entity.decoration.LeashFenceKnotEntity</summary>

```diff
+ double OFFSET_Y
```

</details>



<details><summary>net.minecraft.world.entity.item.PrimedTnt</summary>

```diff
+ int DEFAULT_FUSE_TIME
```

</details>






<details><summary>net.minecraft.world.entity.monster.Drowned</summary>

```diff
+ float NAUTILUS_SHELL_CHANCE
```

</details>




<details><summary>net.minecraft.world.entity.monster.EnderMan</summary>

```diff
+ int DELAY_BETWEEN_CREEPY_STARE_SOUND
+ int MIN_DEAGGRESSION_TIME
+ UniformInt PERSISTENT_ANGER_TIME
- IntRange PERSISTENT_ANGER_TIME
```

</details>



<details><summary>net.minecraft.world.entity.monster.Enemy</summary>

```diff
+ int XP_REWARD_BOSS
+ int XP_REWARD_HUGE
+ int XP_REWARD_LARGE
+ int XP_REWARD_MEDIUM
+ int XP_REWARD_NONE
+ int XP_REWARD_SMALL
```

</details>









<details><summary>net.minecraft.world.entity.monster.Illusioner</summary>

```diff
+ int ILLUSION_SPREAD
+ int ILLUSION_TRANSITION_TICKS
+ int NUM_ILLUSIONS
```

</details>




<details><summary>net.minecraft.world.entity.monster.Phantom</summary>

```diff
+ float FLAP_DEGREES_PER_TICK
```

</details>









<details><summary>net.minecraft.world.entity.monster.Shulker</summary>

```diff
+ byte DEFAULT_COLOR
+ byte NO_COLOR
+ float MAX_LID_OPEN
+ float PEEK_PER_TICK
+ int MAX_TELEPORT_DISTANCE
+ int OTHER_SHULKER_LIMIT
+ int OTHER_SHULKER_SCAN_RADIUS
+ int TELEPORT_STEPS
+ void onSyncedDataUpdated(EntityDataAccessor)
+ void setAttachFace(Direction)
```

</details>





<details><summary>net.minecraft.world.entity.monster.Skeleton</summary>

```diff
+ String CONVERSION_TAG
+ boolean isShaking()
```

</details>








<details><summary>net.minecraft.world.entity.monster.Strider</summary>

```diff
+ float STEERING_MODIFIER
+ float SUFFOCATE_SPEED_MODIFIER
+ float SUFFOCATE_STEERING_MODIFIER
```

</details>


<details><summary>net.minecraft.world.entity.monster.Vex</summary>

```diff
+ float FLAP_DEGREES_PER_TICK
+ int FLAG_IS_CHARGING
```

</details>






<details><summary>net.minecraft.world.entity.monster.Zombie</summary>

```diff
+ float BREAK_DOOR_CHANCE
+ float ZOMBIE_LEADER_CHANCE
+ int REINFORCEMENT_ATTEMPTS
+ int REINFORCEMENT_RANGE_MAX
+ int REINFORCEMENT_RANGE_MIN
```

</details>


<details><summary>net.minecraft.world.entity.monster.ZombifiedPiglin</summary>

```diff
+ int ALERT_RANGE_Y
+ UniformInt ALERT_INTERVAL
+ UniformInt FIRST_ANGER_SOUND_DELAY
+ UniformInt PERSISTENT_ANGER_TIME
- IntRange ALERT_INTERVAL
- IntRange FIRST_ANGER_SOUND_DELAY
- IntRange PERSISTENT_ANGER_TIME
```

</details>

<details><summary>net.minecraft.world.entity.monster.hoglin.HoglinAi</summary>

```diff
+ float SPEED_MULTIPLIER_WHEN_AVOIDING_REPELLENT
+ float SPEED_MULTIPLIER_WHEN_FOLLOWING_ADULT
+ float SPEED_MULTIPLIER_WHEN_IDLING
+ float SPEED_MULTIPLIER_WHEN_MAKING_LOVE
+ float SPEED_MULTIPLIER_WHEN_RETREATING
+ int ATTACK_DURATION
+ int ATTACK_INTERVAL
+ int BABY_ATTACK_INTERVAL
+ int DESIRED_DISTANCE_FROM_PIGLIN_WHEN_IDLING
+ int DESIRED_DISTANCE_FROM_PIGLIN_WHEN_RETREATING
+ int REPELLENT_DETECTION_RANGE_HORIZONTAL
+ int REPELLENT_DETECTION_RANGE_VERTICAL
+ int REPELLENT_PACIFY_TIME
+ UniformInt ADULT_FOLLOW_RANGE
+ UniformInt RETREAT_DURATION
- IntRange ADULT_FOLLOW_RANGE
- IntRange RETREAT_DURATION
```

</details>


<details><summary>net.minecraft.world.entity.monster.piglin.AbstractPiglin</summary>

```diff
+ int CONVERSION_TIME
```

</details>

<details><summary>net.minecraft.world.entity.monster.piglin.PiglinAi</summary>

```diff
+ float PROBABILITY_OF_CELEBRATION_DANCE
+ float SPEED_MULTIPLIER_WHEN_AVOIDING
+ float SPEED_MULTIPLIER_WHEN_DANCING
+ float SPEED_MULTIPLIER_WHEN_GOING_TO_CELEBRATE_LOCATION
+ float SPEED_MULTIPLIER_WHEN_GOING_TO_WANTED_ITEM
+ float SPEED_MULTIPLIER_WHEN_IDLING
+ float SPEED_MULTIPLIER_WHEN_MOUNTING
+ float SPEED_MULTIPLIER_WHEN_RETREATING
+ float SPEED_WHEN_STRAFING_BACK_FROM_TARGET
+ int ADMIRE_DURATION
+ int ANGER_DURATION
+ int BABY_FLEE_DURATION_AFTER_GETTING_HIT
+ int CELEBRATION_TIME
+ int DESIRED_DISTANCE_FROM_ENTITY_WHEN_AVOIDING
+ int DESIRED_DISTANCE_FROM_ZOMBIFIED
+ int EAT_COOLDOWN
+ int HIT_BY_PLAYER_MEMORY_TIMEOUT
+ int HOW_LONG_TIME_TO_DISABLE_ADMIRE_WALKING_IF_CANT_REACH_ITEM
+ int INTERACTION_RANGE
+ int MAX_DISTANCE_TO_WALK_TO_ITEM
+ int MAX_LOOK_DIST
+ int MAX_LOOK_DIST_FOR_PLAYER_HOLDING_LOVED_ITEM
+ int MAX_TIME_TO_WALK_TO_ITEM
+ int MAX_WALK_DISTANCE_TO_START_RIDING
+ int MELEE_ATTACK_COOLDOWN
+ int MIN_DESIRED_DIST_FROM_TARGET_WHEN_HOLDING_CROSSBOW
+ int PLAYER_ANGER_RANGE
+ int REPELLENT_DETECTION_RANGE_HORIZONTAL
+ int REPELLENT_DETECTION_RANGE_VERTICAL
+ UniformInt AVOID_ZOMBIFIED_DURATION
+ UniformInt BABY_AVOID_NEMESIS_DURATION
+ UniformInt RETREAT_DURATION
+ UniformInt RIDE_DURATION
+ UniformInt RIDE_START_INTERVAL
+ UniformInt TIME_BETWEEN_HUNTS
- IntRange AVOID_ZOMBIFIED_DURATION
- IntRange BABY_AVOID_NEMESIS_DURATION
- IntRange RETREAT_DURATION
- IntRange RIDE_DURATION
- IntRange RIDE_START_INTERVAL
- IntRange TIME_BETWEEN_HUNTS
```

</details>

<details><summary>net.minecraft.world.entity.monster.piglin.PiglinBrute</summary>

```diff
+ float MOVEMENT_SPEED_WHEN_FIGHTING
+ int ATTACK_DAMAGE
+ int MAX_HEALTH
```

</details>





<details><summary>net.minecraft.world.entity.npc.CatSpawner</summary>

```diff
+ int TICK_DELAY
```

</details>


<details><summary>net.minecraft.world.entity.npc.Villager</summary>

```diff
+ float SPEED_MODIFIER
+ int BREEDING_FOOD_THRESHOLD
+ int GOSSIP_COOLDOWN
+ int GOSSIP_DECAY_INTERVAL
+ int HOW_FAR_AWAY_TO_TALK_TO_OTHER_VILLAGERS_ABOUT_GOLEMS
+ int HOW_MANY_VILLAGERS_NEED_TO_AGREE_TO_SPAWN_A_GOLEM
+ int MAX_GOSSIP_TOPICS
+ int REPUTATION_CHANGE_PER_EVENT
+ int TRADES_PER_LEVEL
+ long TIME_SINCE_SLEEPING_FOR_GOLEM_SPAWNING
```

</details>


<details><summary>net.minecraft.world.entity.npc.VillagerTrades</summary>

```diff
+ float HIGH_TIER_PRICE_MULTIPLIER
+ float LOW_TIER_PRICE_MULTIPLIER
+ int COMMON_ITEMS_SUPPLY
+ int DEFAULT_SUPPLY
+ int UNCOMMON_ITEMS_SUPPLY
+ int XP_LEVEL_1_BUY
+ int XP_LEVEL_1_SELL
+ int XP_LEVEL_2_BUY
+ int XP_LEVEL_2_SELL
+ int XP_LEVEL_3_BUY
+ int XP_LEVEL_3_SELL
+ int XP_LEVEL_4_BUY
+ int XP_LEVEL_4_SELL
+ int XP_LEVEL_5_TRADE
```

</details>










<details><summary>net.minecraft.world.entity.player.Inventory</summary>

```diff
+ int INVENTORY_SIZE
+ int NOT_FOUND_INDEX
+ int POP_TIME_DURATION
+ int SELECTION_SIZE
+ int SLOT_OFFHAND
```

</details>




<details><summary>net.minecraft.world.entity.projectile.AbstractArrow</summary>

```diff
+ double ARROW_BASE_DAMAGE
+ int FLAG_CRIT
+ int FLAG_CROSSBOW
+ int FLAG_NOPHYSICS
```

</details>


<details><summary>net.minecraft.world.entity.projectile.Arrow</summary>

```diff
+ byte EVENT_POTION_PUFF
+ int EXPOSED_POTION_DECAY_TIME
+ int NO_EFFECT_COLOR
```

</details>

<details><summary>net.minecraft.world.entity.projectile.EvokerFangs</summary>

```diff
+ int ATTACK_DURATION
+ int ATTACK_TRIGGER_TICKS
+ int LIFE_OFFSET
```

</details>


<details><summary>net.minecraft.world.entity.projectile.FishingHook</summary>

```diff
+ int MAX_OUT_OF_WATER_TIME
```

</details>









<details><summary>net.minecraft.world.entity.projectile.ThrownPotion</summary>

```diff
+ double SPLASH_RANGE
+ double SPLASH_RANGE_SQ
```

</details>


<details><summary>net.minecraft.world.entity.raid.Raid</summary>

```diff
+ int ATTEMPT_RAID_CLOSE
+ int ATTEMPT_RAID_FARTHEST
+ int ATTEMPT_RAID_INSIDE
+ int DEFAULT_MAX_BAD_OMEN_LEVEL
+ int DEFAULT_PRE_RAID_TICKS
+ int HERO_OF_THE_VILLAGE_DURATION
+ int LOW_MOB_THRESHOLD
+ int MAX_CELEBRATION_TICKS
+ int MAX_NO_ACTION_TIME
+ int NUM_SPAWN_ATTEMPTS
+ int OUTSIDE_RAID_BOUNDS_TIMEOUT
+ int POST_RAID_TICK_LIMIT
+ int RAID_REMOVAL_THRESHOLD_SQR
+ int RAID_TIMEOUT_TICKS
+ int SECTION_RADIUS_FOR_FINDING_NEW_VILLAGE_CENTER
+ int TICKS_PER_DAY
+ int VALID_RAID_RADIUS_SQR
+ int VILLAGE_RADIUS_BUFFER
+ int VILLAGE_SEARCH_RADIUS
+ String OMINOUS_BANNER_PATTERN_NAME
+ String RAIDERS_REMAINING
```

</details>









<details><summary>net.minecraft.world.entity.vehicle.AbstractMinecart</summary>

```diff
+ float WATER_SLOWDOWN_FACTOR
```

</details>






<details><summary>net.minecraft.world.entity.vehicle.MinecartCommandBlock</summary>

```diff
+ int ACTIVATION_DELAY
```

</details>



<details><summary>net.minecraft.world.entity.vehicle.MinecartTNT</summary>

```diff
+ byte EVENT_PRIME
```

</details>

<details><summary>net.minecraft.world.food.FoodConstants</summary>

```diff
+ float EXHAUSTION_ATTACK
+ float EXHAUSTION_CROUCH
+ float EXHAUSTION_DAMAGE
+ float EXHAUSTION_DROP
+ float EXHAUSTION_HEAL
+ float EXHAUSTION_JUMP
+ float EXHAUSTION_MINE
+ float EXHAUSTION_SPRINT
+ float EXHAUSTION_SPRINT_JUMP
+ float EXHAUSTION_SWIM
+ float EXHAUSTION_WALK
+ float FOOD_SATURATION_GOOD
+ float FOOD_SATURATION_LOW
+ float FOOD_SATURATION_MAX
+ float FOOD_SATURATION_NORMAL
+ float FOOD_SATURATION_POOR
+ float FOOD_SATURATION_SUPERNATURAL
+ float MAX_SATURATION
+ float SATURATION_FLOOR
+ float START_SATURATION
+ int HEAL_LEVEL
+ int HEALTH_TICK_COUNT
+ int HEALTH_TICK_COUNT_SATURATED
+ int MAX_FOOD
+ int SPRINT_LEVEL
+ int STARVE_LEVEL
```

</details>





<details><summary>net.minecraft.world.inventory.AnvilMenu</summary>

```diff
+ boolean DEBUG_COST
+ int COST_ADDED_BASE
+ int COST_BASE
+ int COST_FAIL
+ int COST_INCOMPATIBLE_PENALTY
+ int COST_RENAME
+ int COST_REPAIR_MATERIAL
+ int COST_REPAIR_SACRIFICE
+ int MAX_NAME_LENGTH
```

</details>

<details><summary>net.minecraft.world.inventory.BeaconMenu</summary>

```diff
+ int DATA_COUNT
+ int INV_SLOT_END
+ int INV_SLOT_START
+ int PAYMENT_SLOT
+ int SLOT_COUNT
+ int USE_ROW_SLOT_END
+ int USE_ROW_SLOT_START
```

</details>


<details><summary>net.minecraft.world.inventory.BrewingStandMenu</summary>

```diff
+ int BOTTLE_SLOT_END
+ int BOTTLE_SLOT_START
+ int DATA_COUNT
+ int FUEL_SLOT
+ int INGREDIENT_SLOT
+ int INV_SLOT_END
+ int INV_SLOT_START
+ int SLOT_COUNT
+ int USE_ROW_SLOT_END
+ int USE_ROW_SLOT_START
```

</details>


<details><summary>net.minecraft.world.inventory.CartographyTableMenu</summary>

```diff
+ int ADDITIONAL_SLOT
+ int INV_SLOT_END
+ int INV_SLOT_START
+ int MAP_SLOT
+ int RESULT_SLOT
+ int USE_ROW_SLOT_END
+ int USE_ROW_SLOT_START
```

</details>



<details><summary>net.minecraft.world.inventory.ChestMenu</summary>

```diff
+ int SLOTS_PER_ROW
```

</details>





<details><summary>net.minecraft.world.inventory.CraftingMenu</summary>

```diff
+ int CRAFT_SLOT_END
+ int CRAFT_SLOT_START
+ int INV_SLOT_END
+ int INV_SLOT_START
+ int RESULT_SLOT
+ int USE_ROW_SLOT_END
+ int USE_ROW_SLOT_START
```

</details>









<details><summary>net.minecraft.world.inventory.HopperMenu</summary>

```diff
+ int CONTAINER_SIZE
```

</details>


<details><summary>net.minecraft.world.inventory.InventoryMenu</summary>

```diff
+ int ARMOR_SLOT_END
+ int ARMOR_SLOT_START
+ int CONTAINER_ID
+ int CRAFT_SLOT_END
+ int CRAFT_SLOT_START
+ int INV_SLOT_END
+ int INV_SLOT_START
+ int RESULT_SLOT
+ int SHIELD_SLOT
+ int USE_ROW_SLOT_END
+ int USE_ROW_SLOT_START
```

</details>



<details><summary>net.minecraft.world.inventory.LecternMenu</summary>

```diff
+ int BUTTON_NEXT_PAGE
+ int BUTTON_PAGE_JUMP_RANGE_START
+ int BUTTON_PREV_PAGE
+ int BUTTON_TAKE_BOOK
+ int DATA_COUNT
+ int SLOT_COUNT
```

</details>

<details><summary>net.minecraft.world.inventory.LoomMenu</summary>

```diff
+ int INV_SLOT_END
+ int INV_SLOT_START
+ int USE_ROW_SLOT_END
+ int USE_ROW_SLOT_START
```

</details>













<details><summary>net.minecraft.world.inventory.StonecutterMenu</summary>

```diff
+ int INPUT_SLOT
+ int INV_SLOT_END
+ int INV_SLOT_START
+ int RESULT_SLOT
+ int USE_ROW_SLOT_END
+ int USE_ROW_SLOT_START
```

</details>









<details><summary>net.minecraft.world.item.BlockItem</summary>

```diff
+ String BLOCK_ENTITY_TAG
+ String BLOCK_STATE_TAG
```

</details>

<details><summary>net.minecraft.world.item.BoneMealItem</summary>

```diff
+ int GRASS_COUNT_MULTIPLIER
+ int GRASS_SPREAD_HEIGHT
+ int GRASS_SPREAD_WIDTH
```

</details>



<details><summary>net.minecraft.world.item.BundleItem</summary>

```diff
+ int BUNDLE_IN_BUNDLE_WEIGHT
+ int MAX_WEIGHT
+ String TAG_ITEMS
```

</details>

<details><summary>net.minecraft.world.item.CompassItem</summary>

```diff
+ String TAG_LODESTONE_DIMENSION
+ String TAG_LODESTONE_POS
+ String TAG_LODESTONE_TRACKED
```

</details>












<details><summary>net.minecraft.world.item.DyeableLeatherItem</summary>

```diff
+ int DEFAULT_LEATHER_COLOR
+ String TAG_COLOR
+ String TAG_DISPLAY
```

</details>


<details><summary>net.minecraft.world.item.EnchantedBookItem</summary>

```diff
+ String TAG_STORED_ENCHANTMENTS
```

</details>








<details><summary>net.minecraft.world.item.HoneyBottleItem</summary>

```diff
+ int DRINK_DURATION
```

</details>

<details><summary>net.minecraft.world.item.HorseArmorItem</summary>

```diff
+ String TEX_FOLDER
```

</details>






<details><summary>net.minecraft.world.item.Items</summary>

```diff
+ Item GOAT_SPAWN_EGG
+ Item LIGHT
+ Item registerBlock(Block[])
```

</details>


<details><summary>net.minecraft.world.item.MapItem</summary>

```diff
+ int DEFAULT_MAP_COLOR
+ int IMAGE_HEIGHT
+ int IMAGE_WIDTH
+ String TAG_MAP
```

</details>



<details><summary>net.minecraft.world.item.PickaxeItem</summary>

```diff
+ int MISSING_LEVEL
```

</details>

<details><summary>net.minecraft.world.item.PotionItem</summary>

```diff
+ int DRINK_DURATION
```

</details>




<details><summary>net.minecraft.world.item.ShieldItem</summary>

```diff
+ float MINIMUM_DURABILITY_DAMAGE
+ int EFFECTIVE_BLOCK_DELAY
+ String TAG_BASE_COLOR
```

</details>










<details><summary>net.minecraft.world.item.TridentItem</summary>

```diff
+ float BASE_DAMAGE
+ float SHOOT_POWER
+ int THROW_THRESHOLD_TIME
```

</details>



<details><summary>net.minecraft.world.item.WrittenBookItem</summary>

```diff
+ int MAX_GENERATION
+ int MAX_PAGES
+ int PAGE_EDIT_LENGTH
+ int PAGE_LENGTH
+ int TITLE_LENGTH
+ int TITLE_MAX_LENGTH
+ String TAG_AUTHOR
+ String TAG_FILTERED_PAGES
+ String TAG_FILTERED_TITLE
+ String TAG_GENERATION
+ String TAG_PAGES
+ String TAG_RESOLVED
+ String TAG_TITLE
```

</details>

<details><summary>net.minecraft.world.item.alchemy.PotionBrewing</summary>

```diff
+ int BREWING_TIME_SECONDS
```

</details>

<details><summary>net.minecraft.world.item.alchemy.PotionUtils</summary>

```diff
+ int EMPTY_COLOR
+ String TAG_CUSTOM_POTION_COLOR
+ String TAG_CUSTOM_POTION_EFFECTS
+ String TAG_POTION
```

</details>
















<details><summary>net.minecraft.world.item.crafting.ShapedRecipe</summary>

```diff
+ Item itemFromJson(JsonObject)
+ ItemStack itemStackFromJson(JsonObject)
- ItemStack itemFromJson(JsonObject)
```

</details>













<details><summary>net.minecraft.world.item.enchantment.DamageEnchantment</summary>

```diff
+ int ALL
+ int ARTHROPODS
+ int UNDEAD
```

</details>




























<details><summary>net.minecraft.world.level.BlockGetter</summary>

```diff
+ Optional getBlockEntity(BlockEntityType)
```

</details>







<details><summary>net.minecraft.world.level.CommonLevelAccessor</summary>

```diff
+ Optional getBlockEntity(BlockEntityType)
```

</details>






<details><summary>net.minecraft.world.level.GameRules</summary>

```diff
+ int DEFAULT_RANDOM_TICK_SPEED
```

</details>





<details><summary>net.minecraft.world.level.GameType</summary>

```diff
+ int NOT_SET
```

</details>





<details><summary>net.minecraft.world.level.LevelSimulatedReader</summary>

```diff
+ Optional getBlockEntity(net.minecraft.core.BlockPos,net.minecraft.world.level.block.entity.BlockEntityType)
```

</details>


<details><summary>net.minecraft.world.level.NaturalSpawner</summary>

```diff
+ int MIN_SPAWN_DISTANCE
+ int SPAWN_DISTANCE_BLOCK
+ int SPAWN_DISTANCE_CHUNK
+ WeightedRandomList mobsAt(Biome)
- List mobsAt(Biome)
```

</details>






<details><summary>net.minecraft.world.level.SpawnData</summary>

```diff
+ int DEFAULT_WEIGHT
+ String DEFAULT_TYPE
```

</details>


















<details><summary>net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer</summary>

```diff
+ int ZOOM
+ int ZOOM_BITS
+ int ZOOM_MASK
```

</details>

<details><summary>net.minecraft.world.level.biome.MobSpawnSettings</summary>

```diff
+ float DEFAULT_CREATURE_SPAWN_PROBABILITY
+ WeightedRandomList EMPTY_MOB_LIST
+ WeightedRandomList getMobs(MobCategory)
+ WeightedRandomList lambda$static$1(MobCategory)
- List getMobs(MobCategory)
- List lambda$static$1(MobCategory)
```

</details>

<details><summary>net.minecraft.world.level.biome.MobSpawnSettings$Builder</summary>

```diff
+ WeightedRandomList lambda$build$2(Map$Entry)
- List lambda$build$2(Map$Entry)
```

</details>

<details><summary>net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData</summary>

```diff
+ App lambda$static$3(RecordCodecBuilder$Instance)
+ void <init>(Weight,int,int)
- App lambda$static$4(RecordCodecBuilder$Instance)
- Integer lambda$null$3(MobSpawnSettings$SpawnerData)
```

</details>




<details><summary>net.minecraft.world.level.biome.TheEndBiomeSource</summary>

```diff
+ float ISLAND_THRESHOLD
+ int ISLAND_CHUNK_DISTANCE
+ long ISLAND_CHUNK_DISTANCE_SQR
```

</details>


<details><summary>net.minecraft.world.level.block.AbstractCauldronBlock</summary>

```diff
+ int FLOOR_LEVEL
+ int LEG_DEPTH
+ int LEG_HEIGHT
+ int LEG_WIDTH
+ int SIDE_THICKNESS
```

</details>





<details><summary>net.minecraft.world.level.block.AttachedStemBlock</summary>

```diff
+ float AABB_OFFSET
```

</details>

<details><summary>net.minecraft.world.level.block.BambooBlock</summary>

```diff
+ float COLLISION_AABB_OFFSET
+ float LARGE_LEAVES_AABB_OFFSET
+ float SMALL_LEAVES_AABB_OFFSET
+ int AGE_THICK_BAMBOO
+ int AGE_THIN_BAMBOO
+ int MAX_HEIGHT
+ int STAGE_DONE_GROWING
+ int STAGE_GROWING
```

</details>



<details><summary>net.minecraft.world.level.block.BaseCoralPlantBlock</summary>

```diff
+ float AABB_OFFSET
```

</details>


<details><summary>net.minecraft.world.level.block.BaseFireBlock</summary>

```diff
+ float AABB_OFFSET
+ int SECONDS_ON_FIRE
```

</details>



<details><summary>net.minecraft.world.level.block.BedBlock</summary>

```diff
+ int HEIGHT
+ int LEG_WIDTH
```

</details>

<details><summary>net.minecraft.world.level.block.BeehiveBlock</summary>

```diff
+ int MAX_HONEY_LEVELS
+ int SHEARED_HONEYCOMB_COUNT
```

</details>

<details><summary>net.minecraft.world.level.block.BellBlock</summary>

```diff
+ int EVENT_BELL_RING
```

</details>

<details><summary>net.minecraft.world.level.block.BigDripleafBlock</summary>

```diff
+ int ENTITY_DETECTION_MIN_Y
+ int LOWEST_LEAF_TOP
+ int MAX_GEN_HEIGHT
+ int NO_TICK
+ int STEM_WIDTH
+ VoxelShape STEM_SLICER
- VoxelShape getLeafShape(BlockState)
- VoxelShape getStemShape(BlockState)
```

</details>


<details><summary>net.minecraft.world.level.block.Block</summary>

```diff
+ float INDESTRUCTIBLE
+ float INSTANT
+ int CACHE_SIZE
+ int UPDATE_ALL
+ int UPDATE_ALL_IMMEDIATE
+ int UPDATE_CLIENTS
+ int UPDATE_IMMEDIATE
+ int UPDATE_INVISIBLE
+ int UPDATE_KNOWN_SHAPE
+ int UPDATE_LIMIT
+ int UPDATE_MOVE_BY_PISTON
+ int UPDATE_NEIGHBORS
+ int UPDATE_NONE
+ int UPDATE_SUPPRESS_DROPS
+ int UPDATE_SUPPRESS_LIGHT
```

</details>


<details><summary>net.minecraft.world.level.block.Blocks</summary>

```diff
+ Block LIGHT
```

</details>





<details><summary>net.minecraft.world.level.block.CakeBlock</summary>

```diff
+ float AABB_OFFSET
+ float AABB_SIZE_PER_BITE
+ int MAX_BITES
```

</details>

<details><summary>net.minecraft.world.level.block.CandleBlock</summary>

```diff
+ int MAX_CANDLES
+ int MIN_CANDLES
+ boolean canBeLit(BlockState)
```

</details>




<details><summary>net.minecraft.world.level.block.CaveVinesBlock</summary>

```diff
+ float CHANCE_OF_BERRIES_ON_GROWTH
```

</details>

<details><summary>net.minecraft.world.level.block.ChainBlock</summary>

```diff
+ float AABB_MAX
+ float AABB_MIN
```

</details>

<details><summary>net.minecraft.world.level.block.ChangeOverTimeBlock</summary>

```diff
+ int SCAN_DISTANCE
```

</details>









<details><summary>net.minecraft.world.level.block.ConduitBlock</summary>

```diff
+ int SIZE
```

</details>



<details><summary>net.minecraft.world.level.block.CropBlock</summary>

```diff
+ int MAX_AGE
```

</details>



<details><summary>net.minecraft.world.level.block.DetectorRailBlock</summary>

```diff
+ int PRESSED_CHECK_PERIOD
```

</details>



<details><summary>net.minecraft.world.level.block.DoorBlock</summary>

```diff
+ float AABB_DOOR_THICKNESS
```

</details>











<details><summary>net.minecraft.world.level.block.FarmBlock</summary>

```diff
+ int MAX_MOISTURE
```

</details>


<details><summary>net.minecraft.world.level.block.FireBlock</summary>

```diff
+ int BURN_EASY
+ int BURN_HARD
+ int BURN_INSTANT
+ int BURN_MEDIUM
+ int FLAME_EASY
+ int FLAME_HARD
+ int FLAME_INSTANT
+ int FLAME_MEDIUM
+ int MAX_AGE
```

</details>

<details><summary>net.minecraft.world.level.block.FlowerBlock</summary>

```diff
+ float AABB_OFFSET
```

</details>

<details><summary>net.minecraft.world.level.block.FrostedIceBlock</summary>

```diff
+ int MAX_AGE
+ int NEIGHBORS_TO_AGE
+ int NEIGHBORS_TO_MELT
```

</details>

















<details><summary>net.minecraft.world.level.block.LeavesBlock</summary>

```diff
+ int DECAY_DISTANCE
+ int TICK_DELAY
```

</details>


<details><summary>net.minecraft.world.level.block.LeverBlock</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
```

</details>

<details><summary>net.minecraft.world.level.dimension.DimensionType</summary>

```diff
+ int MOON_PHASES
```

</details>




<details><summary>net.minecraft.world.level.dimension.end.EndDragonFight</summary>

```diff
+ int ARENA_SIZE_CHUNKS
+ int ARENA_TICKET_LEVEL
+ int DRAGON_SPAWN_Y
+ int GATEWAY_COUNT
+ int GATEWAY_DISTANCE
+ int MAX_TICKS_BEFORE_DRAGON_RESPAWN
+ int TIME_BETWEEN_CRYSTAL_SCANS
+ int TIME_BETWEEN_PLAYER_SCANS
```

</details>
















<details><summary>net.minecraft.world.level.gameevent.GameEvent</summary>

```diff
+ int DEFAULT_NOTIFICATION_RADIUS
```

</details>






<details><summary>net.minecraft.world.level.levelgen.Aquifer</summary>

```diff
+ int ALWAYS_LAVA_BELOW_Y_INDEX
+ int ALWAYS_USE_SEA_LEVEL_WHEN_ABOVE
+ int X_RANGE
+ int X_SEPARATION
+ int X_SPACING
+ int Y_RANGE
+ int Y_SEPARATION
+ int Y_SPACING
+ int Z_RANGE
+ int Z_SEPARATION
+ int Z_SPACING
+ boolean isLavaLevel(int)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.Beardifier</summary>

```diff
+ int BEARD_KERNEL_RADIUS
+ int BEARD_KERNEL_SIZE
```

</details>




<details><summary>net.minecraft.world.level.levelgen.Decoratable</summary>

```diff
+ Object count(IntProvider)
- Object count(UniformInt)
```

</details>






<details><summary>net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator</summary>

```diff
+ WeightedRandomList getMobsAt(BlockPos)
- List getMobsAt(BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.NoiseSampler</summary>

```diff
+ int OLD_CELL_COUNT_Y
```

</details>





<details><summary>net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom</summary>

```diff
+ String toString()
```

</details>

<details><summary>net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop</summary>

```diff
+ String toString()
```

</details>


<details><summary>net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration</summary>

```diff
+ CanyonCarverConfiguration$CanyonShapeConfiguration shape
+ FloatProvider verticalRotation
- float verticalRadiusCenterFactor
- float verticalRadiusDefaultFactor
- FloatProvider distanceFactor
- FloatProvider horizontalRadiusFactor
- FloatProvider thickness
- FloatProvider verticalRotation
- int widthSmoothness
- UniformInt yScale
- VerticalAnchor bottomInclusive
- VerticalAnchor topInclusive
+ App lambda$static$3(RecordCodecBuilder$Instance)
+ CanyonCarverConfiguration$CanyonShapeConfiguration lambda$null$2(CanyonCarverConfiguration)
+ CarverConfiguration lambda$null$0(CanyonCarverConfiguration)
+ FloatProvider lambda$null$1(CanyonCarverConfiguration)
+ void <init>(CanyonCarverConfiguration$CanyonShapeConfiguration)
+ void <init>(CanyonCarverConfiguration$CanyonShapeConfiguration)
- App lambda$static$1(RecordCodecBuilder$Instance)
- float getVerticalRadiusCenterFactor()
- float getVerticalRadiusDefaultFactor()
- Float lambda$null$0(CanyonCarverConfiguration)
- FloatProvider getDistanceFactor()
- FloatProvider getHorizontalRadiusFactor()
- FloatProvider getThickness()
- FloatProvider getVerticalRotation()
- int getWidthSmoothness()
- UniformInt getYScale()
- VerticalAnchor getBottomInclusive()
- VerticalAnchor getTopInclusive()
- void <init>(FloatProvider,float,float)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature</summary>

```diff
+ int CLUSTERED_REACH
+ int CLUSTERED_SIZE
+ int UNCLUSTERED_REACH
+ int UNCLUSTERED_SIZE
```

</details>




<details><summary>net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature</summary>

```diff
+ int RANDOM_SALT
```

</details>









<details><summary>net.minecraft.world.level.levelgen.feature.EndCityFeature</summary>

```diff
+ int RANDOM_SALT
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.EndPodiumFeature</summary>

```diff
+ float CORNER_ROUNDING
+ int PODIUM_PILLAR_HEIGHT
+ int PODIUM_RADIUS
+ int RIM_RADIUS
```

</details>






<details><summary>net.minecraft.world.level.levelgen.feature.HugeFungusFeature</summary>

```diff
+ float HUGE_PROBABILITY
```

</details>



<details><summary>net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.JigsawFeature$FeatureStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter</summary>

```diff
+ void <init>(FloatProvider)
+ void <init>(LargeDripstoneFeature$1)
- void <init>(FloatProvider)
- void <init>(LargeDripstoneFeature$1)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.NetherFortressFeature</summary>

```diff
+ WeightedRandomList FORTRESS_ENEMIES
- List FORTRESS_ENEMIES
+ WeightedRandomList getSpecialEnemies()
- List getSpecialEnemies()
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.OceanMonumentFeature</summary>

```diff
+ WeightedRandomList MONUMENT_ENEMIES
- List MONUMENT_ENEMIES
+ WeightedRandomList getSpecialEnemies()
- List getSpecialEnemies()
```

</details>





<details><summary>net.minecraft.world.level.levelgen.feature.RuinedPortalFeature</summary>

```diff
+ float JUNGLE_MOSSINESS
+ float PROBABILITY_OF_AIR_POCKET
+ float PROBABILITY_OF_GIANT_PORTAL
+ float PROBABILITY_OF_UNDERGROUND
+ float SWAMP_MOSSINESS
+ float UNDERWATER_MOSSINESS
+ int MIN_Y
```

</details>






<details><summary>net.minecraft.world.level.levelgen.feature.SpikeFeature</summary>

```diff
+ int NUMBER_OF_SPIKES
+ int SPIKE_DISTANCE
```

</details>



<details><summary>net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory</summary>

```diff
+ StructureStart create(net.minecraft.world.level.levelgen.feature.StructureFeature,net.minecraft.world.level.ChunkPos,int,long)
- StructureStart create(net.minecraft.world.level.levelgen.feature.StructureFeature,net.minecraft.world.level.ChunkPos,net.minecraft.world.level.levelgen.structure.BoundingBox,int,long)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.SwamplandHutFeature</summary>

```diff
+ WeightedRandomList SWAMPHUT_ANIMALS
+ WeightedRandomList SWAMPHUT_ENEMIES
- List SWAMPHUT_ANIMALS
- List SWAMPHUT_ENEMIES
+ WeightedRandomList getSpecialAnimals()
+ WeightedRandomList getSpecialEnemies()
- List getSpecialAnimals()
- List getSpecialEnemies()
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.TreeFeature</summary>

```diff
+ int BLOCK_UPDATE_FLAGS
+ boolean doPlace(TreeConfiguration)
+ Boolean lambda$place$11(BoundingBox)
+ void lambda$doPlace$6(FoliagePlacer$FoliageAttachment)
+ void lambda$place$10(TreeDecorator)
+ void lambda$place$7(BlockState)
+ void lambda$place$8(BlockState)
+ void lambda$place$9(BlockState)
- boolean doPlace(TreeConfiguration)
- void lambda$doPlace$6(FoliagePlacer$FoliageAttachment)
- void lambda$place$7(TreeDecorator)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature</summary>

```diff
+ int PLATFORM_RADIUS
+ int PLATFORM_RADIUS_CHUNKS
```

</details>








<details><summary>net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration</summary>

```diff
+ IntProvider count
- UniformInt count
+ IntProvider count()
+ void <init>(IntProvider)
- UniformInt count()
- void <init>(UniformInt)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration</summary>

```diff
+ IntProvider radius
- UniformInt radius
+ IntProvider lambda$null$1(DiskConfiguration)
+ void <init>(List)
- UniformInt lambda$null$1(DiskConfiguration)
- void <init>(List)
```

</details>



<details><summary>net.minecraft.world.level.levelgen.feature.configurations.GrowingPlantConfiguration</summary>

```diff
+ SimpleWeightedRandomList heightDistribution
- WeightedList heightDistribution
+ SimpleWeightedRandomList lambda$null$0(GrowingPlantConfiguration)
+ void <init>(BlockStateProvider,boolean)
- void <init>(BlockStateProvider,boolean)
- void <init>(BlockStateProvider,boolean)
- WeightedList lambda$null$0(GrowingPlantConfiguration)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration</summary>

```diff
+ FloatProvider heightScale
+ FloatProvider stalactiteBluntness
+ FloatProvider stalagmiteBluntness
+ FloatProvider windSpeed
+ IntProvider columnRadius
- FloatProvider heightScale
- FloatProvider stalactiteBluntness
- FloatProvider stalagmiteBluntness
- FloatProvider windSpeed
- UniformInt columnRadius
+ FloatProvider lambda$null$2(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$4(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$5(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$6(LargeDripstoneConfiguration)
+ IntProvider lambda$null$1(LargeDripstoneConfiguration)
+ void <init>(FloatProvider,int,float)
- FloatProvider lambda$null$2(LargeDripstoneConfiguration)
- FloatProvider lambda$null$4(LargeDripstoneConfiguration)
- FloatProvider lambda$null$5(LargeDripstoneConfiguration)
- FloatProvider lambda$null$6(LargeDripstoneConfiguration)
- UniformInt lambda$null$1(LargeDripstoneConfiguration)
- void <init>(FloatProvider,int,float)
```

</details>




















<details><summary>net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer</summary>

```diff
+ void <init>(IntProvider)
+ void createFoliage(FoliagePlacer$FoliageAttachment,int,int,int)
- void <init>(UniformInt)
- void createFoliage(BoundingBox)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer</summary>

```diff
+ void <init>(IntProvider,int)
+ void createFoliage(FoliagePlacer$FoliageAttachment,int,int,int)
- void <init>(UniformInt,int)
- void createFoliage(BoundingBox)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer</summary>

```diff
+ void <init>(IntProvider,int)
+ void createFoliage(FoliagePlacer$FoliageAttachment,int,int,int)
- void <init>(UniformInt,int)
- void createFoliage(BoundingBox)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment</summary>

```diff
+ BlockPos pos
- BlockPos foliagePos
+ BlockPos pos()
- BlockPos foliagePos()
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer</summary>

```diff
+ void <init>(IntProvider,int)
+ void createFoliage(FoliagePlacer$FoliageAttachment,int,int,int)
- void <init>(UniformInt,int)
- void createFoliage(BoundingBox)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer</summary>

```diff
+ IntProvider height
- UniformInt height
+ IntProvider lambda$null$0(PineFoliagePlacer)
+ void <init>(IntProvider)
+ void createFoliage(FoliagePlacer$FoliageAttachment,int,int,int)
- UniformInt lambda$null$0(PineFoliagePlacer)
- void <init>(UniformInt)
- void createFoliage(BoundingBox)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer</summary>

```diff
+ IntProvider trunkHeight
- UniformInt trunkHeight
+ IntProvider lambda$null$0(SpruceFoliagePlacer)
+ void <init>(IntProvider)
+ void createFoliage(FoliagePlacer$FoliageAttachment,int,int,int)
- UniformInt lambda$null$0(SpruceFoliagePlacer)
- void <init>(UniformInt)
- void createFoliage(BoundingBox)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider</summary>

```diff
+ SimpleWeightedRandomList weightedList
- WeightedList weightedList
+ DataResult create(SimpleWeightedRandomList)
+ SimpleWeightedRandomList lambda$static$0(WeightedStateProvider)
+ void <init>(SimpleWeightedRandomList)
+ void <init>(SimpleWeightedRandomList$Builder)
- DataResult create(WeightedList)
- void <init>()
- void <init>(WeightedList)
- WeightedList lambda$static$0(WeightedStateProvider)
- WeightedStateProvider add(BlockState,int)
```

</details>









<details><summary>net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator</summary>

```diff
+ void lambda$place$2(BlockPos)
+ void place(List)
+ void placeBlockAt(BlockPos)
+ void placeCircle(BlockPos)
- void lambda$place$2(BlockPos)
- void place(BoundingBox)
- void placeBlockAt(BlockPos)
- void placeCircle(BlockPos)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator</summary>

```diff
+ void lambda$place$2(BlockPos)
+ void place(List)
- void lambda$place$2(BlockPos)
- void place(BoundingBox)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator</summary>

```diff
+ void place(net.minecraft.world.level.LevelSimulatedReader,java.util.function.BiConsumer,java.util.Random,java.util.List,java.util.List)
- void place(net.minecraft.world.level.WorldGenLevel,java.util.Random,java.util.List,java.util.List,java.util.Set,net.minecraft.world.level.levelgen.structure.BoundingBox)
+ void placeVine(BooleanProperty)
- void placeVine(BoundingBox)
- void setBlock(BoundingBox)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator</summary>

```diff
+ void lambda$place$1(BlockPos)
+ void place(List)
- void lambda$place$1(BlockPos)
- void place(BoundingBox)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer</summary>

```diff
+ IntProvider bendLength
- UniformInt bendLength
+ IntProvider lambda$null$1(BendingTrunkPlacer)
+ List placeTrunk(TreeConfiguration)
+ void <init>(IntProvider)
- List placeTrunk(TreeConfiguration)
- UniformInt lambda$null$1(BendingTrunkPlacer)
- void <init>(UniformInt)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer</summary>

```diff
+ double BRANCH_LENGTH_MAGIC
+ double BRANCH_SLOPE
+ double CLUSTER_DENSITY_MAGIC
+ double TRUNK_HEIGHT_SCALE
+ BlockState lambda$makeLimb$1(BlockState)
+ boolean makeLimb(TreeConfiguration)
+ List placeTrunk(TreeConfiguration)
+ void makeBranches(TreeConfiguration)
- boolean makeLimb(TreeConfiguration)
- List placeTrunk(TreeConfiguration)
- void makeBranches(TreeConfiguration)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer</summary>

```diff
+ List placeTrunk(TreeConfiguration)
- List placeTrunk(TreeConfiguration)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer</summary>

```diff
+ List placeTrunk(TreeConfiguration)
- List placeTrunk(TreeConfiguration)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer</summary>

```diff
+ int MAX_BASE_HEIGHT
+ int MAX_HEIGHT
+ int MAX_RAND
+ List placeTrunk(net.minecraft.world.level.LevelSimulatedReader,java.util.function.BiConsumer,java.util.Random,int,net.minecraft.core.BlockPos,net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration)
- List placeTrunk(net.minecraft.world.level.LevelSimulatedRW,java.util.Random,int,net.minecraft.core.BlockPos,java.util.Set,net.minecraft.world.level.levelgen.structure.BoundingBox,net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration)
+ boolean placeLog(Function)
+ boolean placeLog(TreeConfiguration)
+ void placeLogIfFree(TreeConfiguration)
+ void setDirtAt(TreeConfiguration)
- boolean placeLog(TreeConfiguration)
- void placeLogIfFree(TreeConfiguration)
- void setBlock(BoundingBox)
- void setDirtAt(TreeConfiguration)
```

</details>



























<details><summary>net.minecraft.world.level.levelgen.structure.EndCityPieces</summary>

```diff
+ int MAX_GEN_DEPTH
- StructurePlaceSettings INSERT
- StructurePlaceSettings OVERWRITE
+ boolean access$300(Random)
+ EndCityPieces$EndCityPiece access$000(Rotation,boolean)
+ EndCityPieces$EndCityPiece access$100(EndCityPieces$EndCityPiece)
+ EndCityPieces$SectionGenerator access$200()
+ EndCityPieces$SectionGenerator access$500()
+ EndCityPieces$SectionGenerator access$600()
+ List access$400()
+ List access$800()
- boolean access$500(Random)
- EndCityPieces$EndCityPiece access$200(Rotation,boolean)
- EndCityPieces$EndCityPiece access$300(EndCityPieces$EndCityPiece)
- EndCityPieces$SectionGenerator access$400()
- EndCityPieces$SectionGenerator access$800()
- EndCityPieces$SectionGenerator access$900()
- List access$1000()
- List access$600()
- StructurePlaceSettings access$000()
- StructurePlaceSettings access$100()
```

</details>




<details><summary>net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece</summary>

```diff
- ResourceLocation templateLocation
- Rotation rotation
+ BlockPos makePosition(BlockPos,int)
+ StructurePlaceSettings lambda$new$0(ResourceLocation)
+ StructurePlaceSettings makeSettings(ResourceLocation)
- void loadTemplate(StructureManager)
```

</details>




<details><summary>net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing</summary>

```diff
+ BoundingBox findCrossing(Direction)
+ void addChildren(Random)
- BoundingBox findCrossing(Direction)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom</summary>

```diff
+ void addChildren(Random)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces</summary>

```diff
+ int LOWEST_Y_POSITION
+ int MAX_DEPTH
+ NetherBridgePieces$NetherBridgePiece access$000(Direction,int)
+ NetherBridgePieces$NetherBridgePiece findAndCreateBridgePieceFactory(Direction,int)
- NetherBridgePieces$NetherBridgePiece access$000(Direction,int)
- NetherBridgePieces$NetherBridgePiece findAndCreateBridgePieceFactory(Direction,int)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$BridgeCrossing createPiece(Direction,int)
+ void <init>(Direction)
+ void addChildren(Random)
- NetherBridgePieces$BridgeCrossing createPiece(Direction,int)
- void <init>(Random,int,int)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$BridgeStraight createPiece(Direction,int)
+ void addChildren(Random)
- NetherBridgePieces$BridgeStraight createPiece(Direction,int)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$CastleCorridorTBalconyPiece createPiece(Direction,int)
+ void addChildren(Random)
- NetherBridgePieces$CastleCorridorTBalconyPiece createPiece(Direction,int)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$CastleSmallCorridorCrossingPiece createPiece(Direction,int)
+ void addChildren(Random)
- NetherBridgePieces$CastleSmallCorridorCrossingPiece createPiece(Direction,int)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$CastleSmallCorridorPiece createPiece(Direction,int)
+ void addChildren(Random)
- NetherBridgePieces$CastleSmallCorridorPiece createPiece(Direction,int)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$CastleStalkRoom createPiece(Direction,int)
+ void addChildren(Random)
- NetherBridgePieces$CastleStalkRoom createPiece(Direction,int)
- void addChildren(Random)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece</summary>

```diff
+ NetherBridgePieces$NetherBridgePiece generatePiece(Direction,int)
+ StructurePiece generateAndAddPiece(Direction,int,boolean)
+ StructurePiece generateChildForward(Random,int,int,boolean)
+ StructurePiece generateChildLeft(Random,int,int,boolean)
+ StructurePiece generateChildRight(Random,int,int,boolean)
+ void <init>(BoundingBox)
- NetherBridgePieces$NetherBridgePiece generatePiece(Direction,int)
- StructurePiece generateAndAddPiece(Direction,int,boolean)
- StructurePiece generateChildForward(Random,int,int,boolean)
- StructurePiece generateChildLeft(Random,int,int,boolean)
- StructurePiece generateChildRight(Random,int,int,boolean)
- void <init>(StructurePieceType,int)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing</summary>

```diff
+ int DEPTH
+ int HEIGHT
+ int WIDTH
+ NetherBridgePieces$RoomCrossing createPiece(Direction,int)
+ void addChildren(Random)
- NetherBridgePieces$RoomCrossing createPiece(Direction,int)
- void addChildren(Random)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart</summary>

```diff
+ void <init>(ChunkPos,int,long)
- void <init>(BoundingBox,int,long)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece</summary>

```diff
- ResourceLocation templateLocation
- Rotation rotation
+ StructurePlaceSettings lambda$new$0(ResourceLocation)
+ StructurePlaceSettings makeSettings(Rotation)
- void loadTemplate(StructureManager)
```

</details>















<details><summary>net.minecraft.world.level.levelgen.structure.StructureStart</summary>

```diff
+ BoundingBox cachedBoundingBox
+ String INVALID_START_ID
- BoundingBox boundingBox
+ boolean hasNoPieces()
+ boolean isInsidePiece(BlockPos)
+ IllegalStateException lambda$getBoundingBox$0()
+ StructurePiece findCollisionPiece(BoundingBox)
+ StructurePiece findCollisionPiece(BoundingBox)
+ void <init>(ChunkPos,int,long)
+ void addPiece(StructurePiece)
+ void clearPieces()
+ void invalidateCache()
+ void offsetPiecesVertically(int)
- void <init>(BoundingBox,int,long)
- void calculateBoundingBox()
- void lambda$createTag$0(Tag)
```

</details>




<details><summary>net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid</summary>

```diff
+ int BLOCKED
+ int CLEAR
+ int CORRIDOR
+ int DEFAULT_SIZE
+ int ROOM
+ int ROOM_1x1
+ int ROOM_1x2
+ int ROOM_2x2
+ int ROOM_CORRIDOR_FLAG
+ int ROOM_DOOR_FLAG
+ int ROOM_ID_MASK
+ int ROOM_ORIGIN_FLAG
+ int ROOM_STAIRS_FLAG
+ int ROOM_TYPE_MASK
+ int START_ROOM
+ int TEST_ROOM
```

</details>



<details><summary>net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece</summary>

```diff
- Mirror mirror
- Rotation rotation
- String templateName
+ ResourceLocation makeLocation(String)
+ ResourceLocation makeTemplateLocation()
+ StructurePlaceSettings lambda$new$0(ResourceLocation)
+ StructurePlaceSettings makeSettings(Rotation)
- void loadTemplate(StructureManager)
```

</details>












<details><summary>net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager</summary>

```diff
+ String STRUCTURE_DIRECTORY_NAME
+ String STRUCTURE_FILE_EXTENSION
+ String STRUCTURE_TEXT_FILE_EXTENSION
```

</details>








<details><summary>net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder</summary>

```diff
+ int LOWEST_Y_TO_BUILD_SURFACE_ON
```

</details>











<details><summary>net.minecraft.world.level.levelgen.synth.PerlinNoise</summary>

```diff
+ int ROUND_OFF
```

</details>




<details><summary>net.minecraft.world.level.lighting.DataLayerStorageMap</summary>

```diff
+ int CACHE_SIZE
```

</details>


<details><summary>net.minecraft.world.level.lighting.FlatDataLayer</summary>

```diff
+ int SIZE
```

</details>


<details><summary>net.minecraft.world.level.lighting.LayerLightSectionStorage</summary>

```diff
+ int EMPTY
+ int LIGHT_AND_DATA
+ int LIGHT_ONLY
```

</details>

<details><summary>net.minecraft.world.level.lighting.LevelLightEngine</summary>

```diff
+ int LIGHT_SECTION_PADDING
+ int MAX_SOURCE_LEVEL
```

</details>





<details><summary>net.minecraft.world.level.material.FlowingFluid</summary>

```diff
+ int CACHE_SIZE
```

</details>



<details><summary>net.minecraft.world.level.material.LavaFluid</summary>

```diff
+ float MIN_LEVEL_CUTOFF
```

</details>
















<details><summary>net.minecraft.world.level.newbiome.layer.Layers</summary>

```diff
+ int COLD_ID
+ int ICE_ID
+ int MEDIUM_ID
+ int SPECIAL_MASK
+ int SPECIAL_SHIFT
+ int WARM_ID
```

</details>




















<details><summary>net.minecraft.world.level.pathfinder.WalkNodeEvaluator</summary>

```diff
+ double SPACE_BETWEEN_WALL_POSTS
```

</details>

<details><summary>net.minecraft.world.level.portal.PortalForcer</summary>

```diff
+ int CREATE_RADIUS
+ int FRAME_BOX
+ int FRAME_BOX_END
+ int FRAME_BOX_START
+ int FRAME_HEIGHT
+ int FRAME_HEIGHT_END
+ int FRAME_HEIGHT_START
+ int FRAME_WIDTH
+ int FRAME_WIDTH_END
+ int FRAME_WIDTH_START
+ int NOTHING_FOUND
+ int SEARCH_RADIUS
+ int TICKET_RADIUS
```

</details>

<details><summary>net.minecraft.world.level.portal.PortalShape</summary>

```diff
+ int MAX_HEIGHT
+ int MAX_WIDTH
+ int MIN_HEIGHT
+ int MIN_WIDTH
```

</details>

<details><summary>net.minecraft.world.level.redstone.Redstone</summary>

```diff
+ int SIGNAL_MAX
+ int SIGNAL_MIN
+ int SIGNAL_NONE
```

</details>




<details><summary>net.minecraft.world.level.saveddata.maps.MapIndex</summary>

```diff
+ String FILE_NAME
```

</details>











<details><summary>net.minecraft.world.level.storage.McRegionUpgrader</summary>

```diff
+ String MCREGION_EXTENSION
```

</details>

<details><summary>net.minecraft.world.level.storage.PrimaryLevelData</summary>

```diff
+ String WORLD_GEN_SETTINGS
```

</details>

<details><summary>net.minecraft.world.level.storage.WorldData</summary>

```diff
+ int ANVIL_VERSION_ID
+ int MCREGION_VERSION_ID
```

</details>



























































































































<details><summary>net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider</summary>

```diff
+ String BLOCK_ENTITY_ID
```

</details>





















<details><summary>Added and removed classes</summary>

```diff
+ com.mojang.math.Constants
+ com.mojang.math.MethodsReturnNonnullByDefault
- com.mojang.math.OctahedralGroup
+ com.mojang.math.OctahedralGroup$1
- com.mojang.math.Quaternion
+ com.mojang.math.SymmetricGroup3
- com.mojang.math.Transformation
+ com.mojang.math.Vector3d
- net.minecraft.advancements.Advancement
+ net.minecraft.advancements.Advancement$1
- net.minecraft.advancements.Advancement$Builder
+ net.minecraft.advancements.AdvancementList
- net.minecraft.advancements.AdvancementList$Listener
+ net.minecraft.advancements.AdvancementProgress
- net.minecraft.advancements.AdvancementProgress$Serializer
+ net.minecraft.advancements.AdvancementRewards
- net.minecraft.advancements.AdvancementRewards$Builder
+ net.minecraft.advancements.critereon.AbstractCriterionTriggerInstance
- net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
+ net.minecraft.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.BlockPredicate
+ net.minecraft.advancements.critereon.BlockPredicate$Builder
- net.minecraft.advancements.critereon.BredAnimalsTrigger
+ net.minecraft.advancements.critereon.BredAnimalsTrigger$TriggerInstance
- net.minecraft.advancements.critereon.BrewedPotionTrigger
+ net.minecraft.advancements.critereon.BrewedPotionTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ChangeDimensionTrigger
+ net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ChanneledLightningTrigger
+ net.minecraft.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ConstructBeaconTrigger
+ net.minecraft.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ConsumeItemTrigger
+ net.minecraft.advancements.critereon.ConsumeItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
+ net.minecraft.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
- net.minecraft.advancements.critereon.DamagePredicate
+ net.minecraft.advancements.critereon.DamagePredicate$Builder
- net.minecraft.advancements.critereon.DamageSourcePredicate
+ net.minecraft.advancements.critereon.DamageSourcePredicate$Builder
- net.minecraft.advancements.critereon.DeserializationContext
+ net.minecraft.advancements.critereon.DistancePredicate
- net.minecraft.advancements.critereon.EffectsChangedTrigger
+ net.minecraft.advancements.critereon.EffectsChangedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EnchantedItemTrigger
+ net.minecraft.advancements.critereon.EnchantedItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EnchantmentPredicate
+ net.minecraft.advancements.critereon.EnterBlockTrigger
- net.minecraft.advancements.critereon.EnterBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EntityEquipmentPredicate
- net.minecraft.advancements.critereon.EntityEquipmentPredicate$Builder
+ net.minecraft.advancements.critereon.EntityFlagsPredicate
- net.minecraft.advancements.critereon.EntityFlagsPredicate$Builder
+ net.minecraft.advancements.critereon.EntityHurtPlayerTrigger
- net.minecraft.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EntityPredicate
- net.minecraft.advancements.critereon.EntityPredicate$1
+ net.minecraft.advancements.critereon.EntityPredicate$Builder
- net.minecraft.advancements.critereon.EntityPredicate$Composite
+ net.minecraft.advancements.critereon.EntityTypePredicate
- net.minecraft.advancements.critereon.EntityTypePredicate$1
+ net.minecraft.advancements.critereon.EntityTypePredicate$TagPredicate
- net.minecraft.advancements.critereon.EntityTypePredicate$TypePredicate
+ net.minecraft.advancements.critereon.FilledBucketTrigger
- net.minecraft.advancements.critereon.FilledBucketTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.FishingHookPredicate
- net.minecraft.advancements.critereon.FishingRodHookedTrigger
+ net.minecraft.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.FluidPredicate
+ net.minecraft.advancements.critereon.FluidPredicate$Builder
- net.minecraft.advancements.critereon.ImpossibleTrigger
+ net.minecraft.advancements.critereon.ImpossibleTrigger$TriggerInstance
- net.minecraft.advancements.critereon.InventoryChangeTrigger
+ net.minecraft.advancements.critereon.InventoryChangeTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ItemDurabilityTrigger
+ net.minecraft.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ItemPickedUpByEntityTrigger
+ net.minecraft.advancements.critereon.ItemPickedUpByEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ItemPredicate
+ net.minecraft.advancements.critereon.ItemPredicate$Builder
- net.minecraft.advancements.critereon.ItemUsedOnBlockTrigger
+ net.minecraft.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.KilledByCrossbowTrigger
+ net.minecraft.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
- net.minecraft.advancements.critereon.KilledTrigger
+ net.minecraft.advancements.critereon.KilledTrigger$TriggerInstance
- net.minecraft.advancements.critereon.LevitationTrigger
+ net.minecraft.advancements.critereon.LevitationTrigger$TriggerInstance
- net.minecraft.advancements.critereon.LightPredicate
+ net.minecraft.advancements.critereon.LightPredicate$1
- net.minecraft.advancements.critereon.LightPredicate$Builder
+ net.minecraft.advancements.critereon.LocationPredicate
- net.minecraft.advancements.critereon.LocationPredicate$Builder
+ net.minecraft.advancements.critereon.LocationTrigger
- net.minecraft.advancements.critereon.LocationTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.LootTableTrigger
- net.minecraft.advancements.critereon.LootTableTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.MinMaxBounds
- net.minecraft.advancements.critereon.MinMaxBounds$BoundsFactory
+ net.minecraft.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
- net.minecraft.advancements.critereon.MinMaxBounds$Floats
+ net.minecraft.advancements.critereon.MinMaxBounds$Ints
- net.minecraft.advancements.critereon.MobEffectsPredicate
+ net.minecraft.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
- net.minecraft.advancements.critereon.NbtPredicate
+ net.minecraft.advancements.critereon.NetherTravelTrigger
- net.minecraft.advancements.critereon.NetherTravelTrigger$TriggerInstance
- net.minecraft.advancements.critereon.package-info
+ net.minecraft.advancements.critereon.PlacedBlockTrigger
- net.minecraft.advancements.critereon.PlacedBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.PlayerHurtEntityTrigger
- net.minecraft.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.PlayerInteractTrigger
- net.minecraft.advancements.critereon.PlayerInteractTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.PlayerPredicate
- net.minecraft.advancements.critereon.PlayerPredicate$1
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementPredicate
- net.minecraft.advancements.critereon.PlayerPredicate$Builder
+ net.minecraft.advancements.critereon.RecipeUnlockedTrigger
- net.minecraft.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.SerializationContext
- net.minecraft.advancements.critereon.ShotCrossbowTrigger
+ net.minecraft.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
- net.minecraft.advancements.critereon.SimpleCriterionTrigger
+ net.minecraft.advancements.critereon.SlideDownBlockTrigger
- net.minecraft.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.StatePropertiesPredicate
- net.minecraft.advancements.critereon.StatePropertiesPredicate$1
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$Builder
- net.minecraft.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
+ net.minecraft.advancements.critereon.SummonedEntityTrigger
- net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TameAnimalTrigger
- net.minecraft.advancements.critereon.TameAnimalTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TargetBlockTrigger
- net.minecraft.advancements.critereon.TargetBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TickTrigger
- net.minecraft.advancements.critereon.TickTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TradeTrigger
- net.minecraft.advancements.critereon.TradeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedEnderEyeTrigger
- net.minecraft.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedTotemTrigger
- net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.WrappedMinMaxBounds
+ net.minecraft.advancements.CriteriaTriggers
- net.minecraft.advancements.Criterion
+ net.minecraft.advancements.CriterionProgress
- net.minecraft.advancements.CriterionTrigger
+ net.minecraft.advancements.CriterionTrigger$Listener
- net.minecraft.advancements.CriterionTriggerInstance
+ net.minecraft.advancements.DisplayInfo
- net.minecraft.advancements.FrameType
+ net.minecraft.advancements.package-info
+ net.minecraft.advancements.RequirementsStrategy
- net.minecraft.advancements.TreeNodePosition
+ net.minecraft.BlockUtil
- net.minecraft.BlockUtil$FoundRectangle
+ net.minecraft.BlockUtil$IntBounds
- net.minecraft.CharPredicate
+ net.minecraft.ChatFormatting
+ net.minecraft.commands.arguments.AngleArgument
- net.minecraft.commands.arguments.AngleArgument$1
+ net.minecraft.commands.arguments.AngleArgument$SingleAngle
- net.minecraft.commands.arguments.blocks.BlockInput
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
- net.minecraft.commands.arguments.blocks.BlockStateArgument
+ net.minecraft.commands.arguments.blocks.BlockStateParser
- net.minecraft.commands.arguments.blocks.package-info
- net.minecraft.commands.arguments.ColorArgument
+ net.minecraft.commands.arguments.ComponentArgument
- net.minecraft.commands.arguments.CompoundTagArgument
+ net.minecraft.commands.arguments.coordinates.BlockPosArgument
- net.minecraft.commands.arguments.coordinates.ColumnPosArgument
+ net.minecraft.commands.arguments.coordinates.Coordinates
- net.minecraft.commands.arguments.coordinates.LocalCoordinates
+ net.minecraft.commands.arguments.coordinates.package-info
+ net.minecraft.commands.arguments.coordinates.RotationArgument
- net.minecraft.commands.arguments.coordinates.SwizzleArgument
+ net.minecraft.commands.arguments.coordinates.Vec2Argument
- net.minecraft.commands.arguments.coordinates.Vec3Argument
+ net.minecraft.commands.arguments.coordinates.WorldCoordinate
- net.minecraft.commands.arguments.coordinates.WorldCoordinates
+ net.minecraft.commands.arguments.DimensionArgument
- net.minecraft.commands.arguments.EntityAnchorArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
- net.minecraft.commands.arguments.EntityArgument
+ net.minecraft.commands.arguments.EntityArgument$Serializer
- net.minecraft.commands.arguments.EntitySummonArgument
+ net.minecraft.commands.arguments.GameProfileArgument
- net.minecraft.commands.arguments.GameProfileArgument$Result
+ net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
- net.minecraft.commands.arguments.item.FunctionArgument
+ net.minecraft.commands.arguments.item.FunctionArgument$1
- net.minecraft.commands.arguments.item.FunctionArgument$2
+ net.minecraft.commands.arguments.item.FunctionArgument$Result
- net.minecraft.commands.arguments.item.ItemArgument
+ net.minecraft.commands.arguments.item.ItemInput
- net.minecraft.commands.arguments.item.ItemParser
+ net.minecraft.commands.arguments.item.ItemPredicateArgument
- net.minecraft.commands.arguments.item.ItemPredicateArgument$ItemPredicate
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
- net.minecraft.commands.arguments.item.ItemPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.item.package-info
- net.minecraft.commands.arguments.ItemEnchantmentArgument
+ net.minecraft.commands.arguments.MessageArgument
- net.minecraft.commands.arguments.MessageArgument$Message
+ net.minecraft.commands.arguments.MessageArgument$Part
- net.minecraft.commands.arguments.MobEffectArgument
+ net.minecraft.commands.arguments.NbtPathArgument
- net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
+ net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
- net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$NbtPath
+ net.minecraft.commands.arguments.NbtPathArgument$Node
- net.minecraft.commands.arguments.NbtTagArgument
+ net.minecraft.commands.arguments.ObjectiveArgument
- net.minecraft.commands.arguments.ObjectiveCriteriaArgument
+ net.minecraft.commands.arguments.OperationArgument
- net.minecraft.commands.arguments.OperationArgument$Operation
+ net.minecraft.commands.arguments.OperationArgument$SimpleOperation
- net.minecraft.commands.arguments.package-info
- net.minecraft.commands.arguments.ParticleArgument
+ net.minecraft.commands.arguments.RangeArgument
- net.minecraft.commands.arguments.RangeArgument$Floats
+ net.minecraft.commands.arguments.RangeArgument$Ints
- net.minecraft.commands.arguments.ResourceLocationArgument
+ net.minecraft.commands.arguments.ScoreboardSlotArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument
- net.minecraft.commands.arguments.ScoreHolderArgument$Result
+ net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
- net.minecraft.commands.arguments.ScoreHolderArgument$Serializer
+ net.minecraft.commands.arguments.selector.EntitySelector
- net.minecraft.commands.arguments.selector.EntitySelector$1
+ net.minecraft.commands.arguments.selector.EntitySelectorParser
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$1
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
- net.minecraft.commands.arguments.selector.options.package-info
+ net.minecraft.commands.arguments.selector.package-info
- net.minecraft.commands.arguments.SlotArgument
+ net.minecraft.commands.arguments.TeamArgument
- net.minecraft.commands.arguments.TimeArgument
+ net.minecraft.commands.arguments.UuidArgument
- net.minecraft.commands.BrigadierExceptions
+ net.minecraft.commands.CommandFunction
- net.minecraft.commands.CommandFunction$CacheableFunction
+ net.minecraft.commands.CommandFunction$CommandEntry
- net.minecraft.commands.CommandFunction$Entry
+ net.minecraft.commands.CommandFunction$FunctionEntry
- net.minecraft.commands.CommandRuntimeException
- net.minecraft.commands.Commands
+ net.minecraft.commands.Commands$CommandSelection
- net.minecraft.commands.Commands$ParseFunction
+ net.minecraft.commands.CommandSource
- net.minecraft.commands.CommandSource$1
+ net.minecraft.commands.CommandSourceStack
- net.minecraft.commands.exceptions.package-info
+ net.minecraft.commands.SharedSuggestionProvider
- net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- net.minecraft.CrashReport
+ net.minecraft.CrashReportCategory
- net.minecraft.CrashReportCategory$Entry
+ net.minecraft.CrashReportDetail
- net.minecraft.DefaultUncaughtExceptionHandler
+ net.minecraft.DefaultUncaughtExceptionHandlerWithName
- net.minecraft.DetectedVersion
+ net.minecraft.FieldsAreNonnullByDefault
- net.minecraft.FileUtil
+ net.minecraft.MethodsReturnNonnullByDefault
- net.minecraft.obfuscate.KeepAfterObfuscation
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.ReportedException
+ net.minecraft.ResourceLocationException
- net.minecraft.resources.DelegatingOps
- net.minecraft.resources.package-info
+ net.minecraft.resources.RegistryDataPackCodec
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryLookupCodec
- net.minecraft.resources.RegistryReadOps
+ net.minecraft.resources.RegistryReadOps$1
- net.minecraft.resources.RegistryReadOps$ReadCache
+ net.minecraft.resources.RegistryReadOps$ResourceAccess
- net.minecraft.resources.RegistryReadOps$ResourceAccess$1
+ net.minecraft.resources.RegistryReadOps$ResourceAccess$MemoryMap
- net.minecraft.resources.RegistryWriteOps
+ net.minecraft.resources.ResourceKey
- net.minecraft.resources.ResourceLocation
+ net.minecraft.resources.ResourceLocation$Serializer
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$1
+ net.minecraft.server.ChainedJsonException$Entry
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$1
- net.minecraft.server.commands.AdvancementCommands$Action
+ net.minecraft.server.commands.AdvancementCommands$Action$1
- net.minecraft.server.commands.AdvancementCommands$Action$2
+ net.minecraft.server.commands.AdvancementCommands$Mode
- net.minecraft.server.commands.AttributeCommand
+ net.minecraft.server.commands.BanIpCommands
- net.minecraft.server.commands.BanListCommands
+ net.minecraft.server.commands.BanPlayerCommands
- net.minecraft.server.commands.BossBarCommands
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockInfo
- net.minecraft.server.commands.CloneCommands$Mode
- net.minecraft.server.commands.data.BlockDataAccessor
+ net.minecraft.server.commands.data.BlockDataAccessor$1
- net.minecraft.server.commands.data.DataAccessor
+ net.minecraft.server.commands.data.DataCommands
- net.minecraft.server.commands.data.DataCommands$DataManipulator
+ net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
- net.minecraft.server.commands.data.DataCommands$DataProvider
+ net.minecraft.server.commands.data.EntityDataAccessor
- net.minecraft.server.commands.data.EntityDataAccessor$1
+ net.minecraft.server.commands.data.package-info
+ net.minecraft.server.commands.data.StorageDataAccessor
- net.minecraft.server.commands.data.StorageDataAccessor$1
+ net.minecraft.server.commands.DataPackCommand
- net.minecraft.server.commands.DataPackCommand$Inserter
- net.minecraft.server.commands.DebugCommand
+ net.minecraft.server.commands.DebugMobSpawningCommand
- net.minecraft.server.commands.DebugPathCommand
+ net.minecraft.server.commands.DefaultGameModeCommands
+ net.minecraft.server.commands.DeOpCommands
- net.minecraft.server.commands.DifficultyCommand
+ net.minecraft.server.commands.EffectCommands
- net.minecraft.server.commands.EmoteCommands
+ net.minecraft.server.commands.EnchantCommand
- net.minecraft.server.commands.ExecuteCommand
+ net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
- net.minecraft.server.commands.ExecuteCommand$CommandPredicate
+ net.minecraft.server.commands.ExperienceCommand
- net.minecraft.server.commands.ExperienceCommand$Type
+ net.minecraft.server.commands.FillCommand
- net.minecraft.server.commands.FillCommand$Mode
+ net.minecraft.server.commands.ForceLoadCommand
- net.minecraft.server.commands.FunctionCommand
+ net.minecraft.server.commands.GameModeCommand
- net.minecraft.server.commands.GameRuleCommand
+ net.minecraft.server.commands.GameRuleCommand$1
- net.minecraft.server.commands.GiveCommand
+ net.minecraft.server.commands.HelpCommand
- net.minecraft.server.commands.ItemCommands
+ net.minecraft.server.commands.KickCommand
- net.minecraft.server.commands.KillCommand
+ net.minecraft.server.commands.ListPlayersCommand
- net.minecraft.server.commands.LocateBiomeCommand
+ net.minecraft.server.commands.LocateCommand
- net.minecraft.server.commands.LootCommand
+ net.minecraft.server.commands.LootCommand$Callback
- net.minecraft.server.commands.LootCommand$DropConsumer
+ net.minecraft.server.commands.LootCommand$TailProvider
- net.minecraft.server.commands.MsgCommand
+ net.minecraft.server.commands.OpCommand
- net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PlaySoundCommand
- net.minecraft.server.commands.PublishCommand
+ net.minecraft.server.commands.RaidCommand
- net.minecraft.server.commands.RecipeCommand
+ net.minecraft.server.commands.ReloadCommand
- net.minecraft.server.commands.SaveAllCommand
+ net.minecraft.server.commands.SaveOffCommand
- net.minecraft.server.commands.SaveOnCommand
+ net.minecraft.server.commands.SayCommand
- net.minecraft.server.commands.ScheduleCommand
+ net.minecraft.server.commands.ScoreboardCommand
- net.minecraft.server.commands.SeedCommand
+ net.minecraft.server.commands.SetBlockCommand
- net.minecraft.server.commands.SetBlockCommand$Filter
+ net.minecraft.server.commands.SetBlockCommand$Mode
- net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
+ net.minecraft.server.commands.SetSpawnCommand
- net.minecraft.server.commands.SetWorldSpawnCommand
+ net.minecraft.server.commands.SpectateCommand
- net.minecraft.server.commands.SpreadPlayersCommand
+ net.minecraft.server.commands.SpreadPlayersCommand$1
- net.minecraft.server.commands.SpreadPlayersCommand$Position
+ net.minecraft.server.commands.StopCommand
- net.minecraft.server.commands.StopSoundCommand
+ net.minecraft.server.commands.SummonCommand
- net.minecraft.server.commands.TagCommand
+ net.minecraft.server.commands.TeamCommand
- net.minecraft.server.commands.TeamMsgCommand
+ net.minecraft.server.commands.TeleportCommand
- net.minecraft.server.commands.TeleportCommand$LookAt
+ net.minecraft.server.commands.TellRawCommand
- net.minecraft.server.commands.TimeCommand
+ net.minecraft.server.commands.TitleCommand
- net.minecraft.server.commands.TriggerCommand
+ net.minecraft.server.commands.WeatherCommand
- net.minecraft.server.commands.WhitelistCommand
+ net.minecraft.server.commands.WorldBorderCommand
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.DebugLoggedPrintStream
+ net.minecraft.server.dedicated.DedicatedPlayerList
- net.minecraft.server.dedicated.DedicatedServer
+ net.minecraft.server.dedicated.DedicatedServer$1
- net.minecraft.server.dedicated.DedicatedServerProperties
+ net.minecraft.server.dedicated.DedicatedServerSettings
+ net.minecraft.server.dedicated.package-info
- net.minecraft.server.dedicated.ServerWatchdog
+ net.minecraft.server.dedicated.ServerWatchdog$1
- net.minecraft.server.dedicated.Settings
+ net.minecraft.server.dedicated.Settings$1
- net.minecraft.server.dedicated.Settings$MutableValue
- net.minecraft.server.Eula
- net.minecraft.server.gui.MinecraftServerGui
+ net.minecraft.server.gui.MinecraftServerGui$1
- net.minecraft.server.gui.MinecraftServerGui$2
+ net.minecraft.server.gui.package-info
+ net.minecraft.server.gui.PlayerListComponent
- net.minecraft.server.gui.StatsComponent
- net.minecraft.server.level.BlockDestructionProgress
+ net.minecraft.server.level.ChunkHolder
- net.minecraft.server.level.ChunkHolder$1
+ net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure
- net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure$1
+ net.minecraft.server.level.ChunkHolder$ChunkSaveDebug
- net.minecraft.server.level.ChunkHolder$FullChunkStatus
+ net.minecraft.server.level.ChunkHolder$LevelChangeListener
- net.minecraft.server.level.ChunkHolder$PlayerProvider
+ net.minecraft.server.level.ChunkMap
- net.minecraft.server.level.ChunkMap$1
+ net.minecraft.server.level.ChunkMap$2
- net.minecraft.server.level.ChunkMap$DistanceManager
+ net.minecraft.server.level.ChunkMap$TrackedEntity
- net.minecraft.server.level.ChunkTaskPriorityQueue
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$1
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
+ net.minecraft.server.level.ChunkTracker
- net.minecraft.server.level.ColumnPos
+ net.minecraft.server.level.DemoMode
- net.minecraft.server.level.DistanceManager
+ net.minecraft.server.level.DistanceManager$ChunkTicketTracker
- net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ net.minecraft.server.level.DistanceManager$PlayerTicketTracker
- net.minecraft.server.level.package-info
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.PlayerRespawnLogic
+ net.minecraft.server.level.progress.ChunkProgressListener
- net.minecraft.server.level.progress.ChunkProgressListenerFactory
+ net.minecraft.server.level.progress.LoggerChunkProgressListener
- net.minecraft.server.level.progress.package-info
- net.minecraft.server.level.progress.ProcessorChunkProgressListener
+ net.minecraft.server.level.progress.StoringChunkProgressListener
- net.minecraft.server.level.SectionTracker
+ net.minecraft.server.level.ServerBossEvent
- net.minecraft.server.level.ServerChunkCache
+ net.minecraft.server.level.ServerChunkCache$1
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
+ net.minecraft.server.level.ServerLevel$1
- net.minecraft.server.level.ServerLevel$EntityCallbacks
+ net.minecraft.server.level.ServerPlayer
- net.minecraft.server.level.ServerPlayer$1
+ net.minecraft.server.level.ServerPlayer$2
- net.minecraft.server.level.ServerPlayer$3
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.WorldGenRegion
+ net.minecraft.server.level.WorldGenTickList
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.Main
+ net.minecraft.server.Main$1
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$2
+ net.minecraft.server.network.LegacyQueryHandler
- net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
+ net.minecraft.server.network.package-info
+ net.minecraft.server.network.ServerConnectionListener
- net.minecraft.server.network.ServerConnectionListener$1
+ net.minecraft.server.network.ServerConnectionListener$2
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
- net.minecraft.server.network.ServerGamePacketListenerImpl
+ net.minecraft.server.network.ServerGamePacketListenerImpl$1
- net.minecraft.server.network.ServerGamePacketListenerImpl$2
+ net.minecraft.server.network.ServerGamePacketListenerImpl$EntityInteraction
- net.minecraft.server.network.ServerHandshakePacketListenerImpl
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl$State
+ net.minecraft.server.network.ServerPlayerConnection
- net.minecraft.server.network.ServerStatusPacketListenerImpl
+ net.minecraft.server.network.TextFilter
- net.minecraft.server.network.TextFilter$1
+ net.minecraft.server.network.TextFilter$FilteredText
- net.minecraft.server.network.TextFilterClient
+ net.minecraft.server.network.TextFilterClient$1
- net.minecraft.server.network.TextFilterClient$IgnoreStrategy
+ net.minecraft.server.network.TextFilterClient$PlayerContext
- net.minecraft.server.network.TextFilterClient$RequestFailedException
- net.minecraft.server.package-info
+ net.minecraft.server.packs.AbstractPackResources
- net.minecraft.server.packs.FilePackResources
+ net.minecraft.server.packs.FolderPackResources
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
+ net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.package-info
- net.minecraft.server.packs.PackResources
+ net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.Pack
+ net.minecraft.server.packs.repository.Pack$PackConstructor
- net.minecraft.server.packs.repository.Pack$Position
- net.minecraft.server.packs.repository.package-info
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.PackSource
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
- net.minecraft.server.packs.ResourcePackFileNotFoundException
+ net.minecraft.server.packs.resources.FallbackResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- net.minecraft.server.packs.resources.package-info
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$1
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$State
+ net.minecraft.server.packs.resources.ReloadableResourceManager
- net.minecraft.server.packs.resources.ReloadInstance
- net.minecraft.server.packs.resources.Resource
+ net.minecraft.server.packs.resources.ResourceManager
- net.minecraft.server.packs.resources.ResourceManager$Empty
+ net.minecraft.server.packs.resources.ResourceManagerReloadListener
- net.minecraft.server.packs.resources.ResourceProvider
+ net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
- net.minecraft.server.packs.resources.SimplePreparableReloadListener
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
+ net.minecraft.server.packs.resources.SimpleReloadInstance
- net.minecraft.server.packs.resources.SimpleReloadInstance$1
+ net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
+ net.minecraft.server.packs.resources.SimpleResource
+ net.minecraft.server.packs.VanillaPackResources
- net.minecraft.server.packs.VanillaPackResources$1
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$1
+ net.minecraft.server.players.BanListEntry
- net.minecraft.server.players.GameProfileCache
+ net.minecraft.server.players.GameProfileCache$1
- net.minecraft.server.players.GameProfileCache$GameProfileInfo
+ net.minecraft.server.players.IpBanList
- net.minecraft.server.players.IpBanListEntry
+ net.minecraft.server.players.OldUsersConverter
- net.minecraft.server.players.OldUsersConverter$1
+ net.minecraft.server.players.OldUsersConverter$2
- net.minecraft.server.players.OldUsersConverter$3
+ net.minecraft.server.players.OldUsersConverter$4
- net.minecraft.server.players.OldUsersConverter$5
+ net.minecraft.server.players.OldUsersConverter$ConversionError
+ net.minecraft.server.players.package-info
- net.minecraft.server.players.PlayerList
+ net.minecraft.server.players.PlayerList$1
- net.minecraft.server.players.ServerOpList
+ net.minecraft.server.players.ServerOpListEntry
- net.minecraft.server.players.SleepStatus
+ net.minecraft.server.players.StoredUserEntry
- net.minecraft.server.players.StoredUserList
+ net.minecraft.server.players.UserBanList
- net.minecraft.server.players.UserBanListEntry
+ net.minecraft.server.players.UserWhiteList
- net.minecraft.server.players.UserWhiteListEntry
- net.minecraft.server.rcon.NetworkDataOutputStream
+ net.minecraft.server.rcon.package-info
+ net.minecraft.server.rcon.PktUtils
- net.minecraft.server.rcon.RconConsoleSource
- net.minecraft.server.rcon.thread.GenericThread
+ net.minecraft.server.rcon.thread.package-info
+ net.minecraft.server.rcon.thread.QueryThreadGs4
- net.minecraft.server.rcon.thread.QueryThreadGs4$RequestChallenge
+ net.minecraft.server.rcon.thread.RconClient
- net.minecraft.server.rcon.thread.RconThread
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerResources
- net.minecraft.server.ServerScoreboard
+ net.minecraft.server.ServerScoreboard$Method
- net.minecraft.server.TickTask
- net.minecraft.SharedConstants
- net.minecraft.sounds.Music
+ net.minecraft.sounds.Musics
+ net.minecraft.sounds.package-info
- net.minecraft.sounds.SoundEvent
+ net.minecraft.sounds.SoundEvents
- net.minecraft.sounds.SoundSource
- net.minecraft.stats.package-info
- net.minecraft.stats.RecipeBook
+ net.minecraft.stats.RecipeBookSettings
- net.minecraft.stats.RecipeBookSettings$TypeSettings
+ net.minecraft.stats.ServerRecipeBook
- net.minecraft.stats.ServerStatsCounter
+ net.minecraft.stats.Stat
- net.minecraft.stats.StatFormatter
- net.minecraft.stats.Stats
+ net.minecraft.stats.StatsCounter
+ net.minecraft.stats.StatType
+ net.minecraft.tags.BlockTags
- net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.FluidTags
- net.minecraft.tags.GameEventTags
+ net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
- net.minecraft.tags.SerializationTags
+ net.minecraft.tags.SetTag
- net.minecraft.tags.StaticTagHelper
+ net.minecraft.tags.StaticTagHelper$1
- net.minecraft.tags.StaticTagHelper$Wrapper
+ net.minecraft.tags.StaticTags
- net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$1
- net.minecraft.tags.Tag$Builder
+ net.minecraft.tags.Tag$BuilderEntry
- net.minecraft.tags.Tag$ElementEntry
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.Tag$Named
+ net.minecraft.tags.Tag$OptionalElementEntry
- net.minecraft.tags.Tag$OptionalTagEntry
+ net.minecraft.tags.Tag$TagEntry
- net.minecraft.tags.TagCollection
+ net.minecraft.tags.TagCollection$1
- net.minecraft.tags.TagCollection$NetworkPayload
+ net.minecraft.tags.TagContainer
- net.minecraft.tags.TagContainer$1
+ net.minecraft.tags.TagContainer$Builder
- net.minecraft.tags.TagContainer$CollectionConsumer
+ net.minecraft.tags.TagLoader
- net.minecraft.tags.TagManager
+ net.minecraft.tags.TagManager$1
- net.minecraft.tags.TagManager$LoaderInfo
+ net.minecraft.Util
- net.minecraft.util.BitStorage
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.CryptException
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$1
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
+ net.minecraft.util.datafix.fixes.BedItemColorFix
- net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
+ net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.fixes.BitStorageAlignFix
+ net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
- net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
+ net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.BlockEntityIdFix
+ net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
- net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
+ net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
+ net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
- net.minecraft.util.datafix.fixes.BlockRenameFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix$1
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
- net.minecraft.util.datafix.fixes.BlockStateData
+ net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
- net.minecraft.util.datafix.fixes.CatTypeFix
+ net.minecraft.util.datafix.fixes.CauldronRenameFix
- net.minecraft.util.datafix.fixes.ChunkBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- net.minecraft.util.datafix.fixes.ChunkStatusFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix2
- net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
+ net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
- net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
+ net.minecraft.util.datafix.fixes.DyeItemRenameFix
- net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
+ net.minecraft.util.datafix.fixes.EntityBlockStateFix
- net.minecraft.util.datafix.fixes.EntityCatSplitFix
+ net.minecraft.util.datafix.fixes.EntityCodSalmonFix
- net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
- net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ net.minecraft.util.datafix.fixes.EntityHealthFix
- net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
+ net.minecraft.util.datafix.fixes.EntityHorseSplitFix
- net.minecraft.util.datafix.fixes.EntityIdFix
+ net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
+ net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
+ net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
- net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
+ net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
- net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
+ net.minecraft.util.datafix.fixes.EntityRenameFix
- net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
+ net.minecraft.util.datafix.fixes.EntityShulkerColorFix
- net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
+ net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
- net.minecraft.util.datafix.fixes.EntityStringUuidFix
+ net.minecraft.util.datafix.fixes.EntityTheRenameningFix
- net.minecraft.util.datafix.fixes.EntityTippedArrowFix
+ net.minecraft.util.datafix.fixes.EntityUUIDFix
- net.minecraft.util.datafix.fixes.EntityWolfColorFix
+ net.minecraft.util.datafix.fixes.EntityZombieSplitFix
- net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
+ net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
- net.minecraft.util.datafix.fixes.ForcePoiRebuild
+ net.minecraft.util.datafix.fixes.FurnaceRecipeFix
- net.minecraft.util.datafix.fixes.GossipUUIDFix
+ net.minecraft.util.datafix.fixes.HeightmapRenamingFix
- net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
+ net.minecraft.util.datafix.fixes.ItemBannerColorFix
- net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.ItemIdFix
- net.minecraft.util.datafix.fixes.ItemLoreFix
+ net.minecraft.util.datafix.fixes.ItemPotionFix
- net.minecraft.util.datafix.fixes.ItemRenameFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix$1
- net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.ItemSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
+ net.minecraft.util.datafix.fixes.ItemStackMapIdFix
- net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.JigsawPropertiesFix
- net.minecraft.util.datafix.fixes.JigsawRotationFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
+ net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
+ net.minecraft.util.datafix.fixes.MissingDimensionFix
- net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ net.minecraft.util.datafix.fixes.NamedEntityFix
- net.minecraft.util.datafix.fixes.NewVillageFix
+ net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
- net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
+ net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
- net.minecraft.util.datafix.fixes.OminousBannerRenameFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsForceVBOFix
+ net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
- net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
+ net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
- net.minecraft.util.datafix.fixes.package-info
+ net.minecraft.util.datafix.fixes.PlayerUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRename
+ net.minecraft.util.datafix.fixes.RecipesFix
- net.minecraft.util.datafix.fixes.RecipesRenameFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
+ net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
+ net.minecraft.util.datafix.fixes.RenameBiomesFix
- net.minecraft.util.datafix.fixes.RenamedCoralFansFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFix
- net.minecraft.util.datafix.fixes.ReorganizePoi
+ net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
- net.minecraft.util.datafix.fixes.SavedDataUUIDFix
+ net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
- net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
+ net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.util.datafix.fixes.SwimStatsRenameFix
- net.minecraft.util.datafix.fixes.TeamDisplayNameFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ net.minecraft.util.datafix.fixes.VillagerDataFix
- net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
+ net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
- net.minecraft.util.datafix.fixes.VillagerTradeFix
+ net.minecraft.util.datafix.fixes.WallPropertyFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- net.minecraft.util.datafix.fixes.WriteAndReadFix
+ net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.package-info
+ net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
+ net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V100
+ net.minecraft.util.datafix.schemas.V102
- net.minecraft.util.datafix.schemas.V1022
+ net.minecraft.util.datafix.schemas.V106
- net.minecraft.util.datafix.schemas.V107
+ net.minecraft.util.datafix.schemas.V1125
- net.minecraft.util.datafix.schemas.V135
+ net.minecraft.util.datafix.schemas.V143
- net.minecraft.util.datafix.schemas.V1451
+ net.minecraft.util.datafix.schemas.V1451_1
- net.minecraft.util.datafix.schemas.V1451_2
+ net.minecraft.util.datafix.schemas.V1451_3
- net.minecraft.util.datafix.schemas.V1451_4
+ net.minecraft.util.datafix.schemas.V1451_5
- net.minecraft.util.datafix.schemas.V1451_6
+ net.minecraft.util.datafix.schemas.V1451_7
- net.minecraft.util.datafix.schemas.V1460
+ net.minecraft.util.datafix.schemas.V1460$1
- net.minecraft.util.datafix.schemas.V1466
+ net.minecraft.util.datafix.schemas.V1470
- net.minecraft.util.datafix.schemas.V1481
+ net.minecraft.util.datafix.schemas.V1483
- net.minecraft.util.datafix.schemas.V1486
+ net.minecraft.util.datafix.schemas.V1510
- net.minecraft.util.datafix.schemas.V1800
+ net.minecraft.util.datafix.schemas.V1801
- net.minecraft.util.datafix.schemas.V1904
+ net.minecraft.util.datafix.schemas.V1906
- net.minecraft.util.datafix.schemas.V1909
+ net.minecraft.util.datafix.schemas.V1920
- net.minecraft.util.datafix.schemas.V1928
+ net.minecraft.util.datafix.schemas.V1929
- net.minecraft.util.datafix.schemas.V1931
+ net.minecraft.util.datafix.schemas.V2100
- net.minecraft.util.datafix.schemas.V2501
+ net.minecraft.util.datafix.schemas.V2502
- net.minecraft.util.datafix.schemas.V2505
+ net.minecraft.util.datafix.schemas.V2509
- net.minecraft.util.datafix.schemas.V2519
+ net.minecraft.util.datafix.schemas.V2522
- net.minecraft.util.datafix.schemas.V2551
+ net.minecraft.util.datafix.schemas.V2568
+ net.minecraft.util.datafix.schemas.V501
- net.minecraft.util.datafix.schemas.V700
+ net.minecraft.util.datafix.schemas.V701
- net.minecraft.util.datafix.schemas.V702
+ net.minecraft.util.datafix.schemas.V703
- net.minecraft.util.datafix.schemas.V704
+ net.minecraft.util.datafix.schemas.V704$1
- net.minecraft.util.datafix.schemas.V705
+ net.minecraft.util.datafix.schemas.V705$1
- net.minecraft.util.datafix.schemas.V808
+ net.minecraft.util.datafix.schemas.V99
- net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.DebugBuffer
+ net.minecraft.util.DirectoryLock
- net.minecraft.util.DirectoryLock$LockException
+ net.minecraft.util.ExceptionCollector
- net.minecraft.util.ExtraCodecs
- net.minecraft.util.FloatProviderType
- net.minecraft.util.GlslPreprocessor
- net.minecraft.util.GlslPreprocessor$Context
+ net.minecraft.util.GsonHelper
- net.minecraft.util.HeapDumper
+ net.minecraft.util.HttpUtil
- net.minecraft.util.IntRange
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$1
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.package-info
- net.minecraft.util.profiling.ActiveProfiler
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
- net.minecraft.util.profiling.registry.MeasuredMetric
+ net.minecraft.util.profiling.registry.MeasurementCategory
- net.minecraft.util.profiling.registry.MeasurementRegistry
+ net.minecraft.util.profiling.registry.Metric
+ net.minecraft.util.profiling.registry.package-info
- net.minecraft.util.profiling.registry.ProfilerMeasured
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
+ net.minecraft.util.random.package-info
+ net.minecraft.util.random.SimpleWeightedRandomList$Builder
+ net.minecraft.util.random.WeightedEntry
+ net.minecraft.util.random.WeightedEntry$IntrusiveBase
+ net.minecraft.util.random.WeightedRandom
- net.minecraft.util.thread.BlockableEventLoop
+ net.minecraft.util.thread.NamedThreadFactory
- net.minecraft.util.thread.package-info
- net.minecraft.util.thread.ProcessorHandle
+ net.minecraft.util.thread.ProcessorHandle$1
- net.minecraft.util.thread.ProcessorMailbox
+ net.minecraft.util.thread.ReentrantBlockableEventLoop
- net.minecraft.util.thread.StrictQueue
+ net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
- net.minecraft.util.thread.StrictQueue$IntRunnable
+ net.minecraft.util.thread.StrictQueue$QueueStrictQueue
- net.minecraft.util.Tuple
- net.minecraft.util.UniformInt
+ net.minecraft.util.Unit
+ net.minecraft.util.valueproviders.ClampedNormalFloat
+ net.minecraft.util.valueproviders.ConstantInt
+ net.minecraft.util.valueproviders.FloatProviderType
+ net.minecraft.util.valueproviders.IntProviderType
+ net.minecraft.util.valueproviders.package-info
+ net.minecraft.util.valueproviders.UniformFloat
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.WeighedRandom
- net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.Util$1
+ net.minecraft.Util$3
- net.minecraft.Util$4
+ net.minecraft.Util$5
- net.minecraft.Util$6
+ net.minecraft.Util$7
- net.minecraft.Util$8
+ net.minecraft.Util$9
- net.minecraft.Util$IdentityStrategy
+ net.minecraft.Util$OS
- net.minecraft.Util$OS$1
+ net.minecraft.Util$OS$2
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BabyFollowAdult
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
+ net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
- net.minecraft.world.entity.ai.behavior.GoToClosestVillage
+ net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.ShufflingList
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.WeightedList
- net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
- net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
- net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
+ net.minecraft.world.entity.ai.goal.target.package-info
+ net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
- net.minecraft.world.entity.ai.goal.target.TargetGoal
- net.minecraft.world.entity.ai.goal.TemptGoal
+ net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
- net.minecraft.world.entity.ai.goal.TryFindWaterGoal
+ net.minecraft.world.entity.ai.goal.UseItemGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
- net.minecraft.world.entity.ai.goal.WrappedGoal
+ net.minecraft.world.entity.ai.goal.ZombieAttackGoal
- net.minecraft.world.entity.ai.gossip.GossipContainer
+ net.minecraft.world.entity.ai.gossip.GossipContainer$1
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.PlayerSensor
+ net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
- net.minecraft.world.entity.ai.sensing.Sensing
+ net.minecraft.world.entity.ai.sensing.Sensor
- net.minecraft.world.entity.ai.sensing.SensorType
+ net.minecraft.world.entity.ai.sensing.TemptingSensor
- net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
+ net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
- net.minecraft.world.entity.ai.targeting.package-info
+ net.minecraft.world.entity.ai.targeting.TargetingConditions
+ net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
- net.minecraft.world.entity.ai.util.AirRandomPos
+ net.minecraft.world.entity.ai.util.DefaultRandomPos
- net.minecraft.world.entity.ai.util.GoalUtils
+ net.minecraft.world.entity.ai.util.HoverRandomPos
- net.minecraft.world.entity.ai.util.LandRandomPos
- net.minecraft.world.entity.ai.util.package-info
+ net.minecraft.world.entity.ai.util.RandomPos
+ net.minecraft.world.entity.ai.village.package-info
- net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiSection
+ net.minecraft.world.entity.ai.village.poi.PoiType
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
+ net.minecraft.world.entity.ambient.AmbientCreature
- net.minecraft.world.entity.ambient.Bat
+ net.minecraft.world.entity.ambient.package-info
- net.minecraft.world.entity.animal.AbstractFish
+ net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
- net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
+ net.minecraft.world.entity.animal.AbstractGolem
- net.minecraft.world.entity.animal.AbstractSchoolingFish
+ net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.Animal
+ net.minecraft.world.entity.animal.axolotl.Axolotl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
- net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
+ net.minecraft.world.entity.animal.axolotl.AxolotlAi
- net.minecraft.world.entity.animal.axolotl.package-info
- net.minecraft.world.entity.animal.axolotl.PlayDead
+ net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
+ net.minecraft.world.entity.animal.Bee
- net.minecraft.world.entity.animal.Bee$1
+ net.minecraft.world.entity.animal.Bee$BaseBeeGoal
- net.minecraft.world.entity.animal.Bee$BeeAttackGoal
+ net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
- net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
- net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
+ net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeLookControl
+ net.minecraft.world.entity.animal.Bee$BeePollinateGoal
- net.minecraft.world.entity.animal.Bee$BeeWanderGoal
+ net.minecraft.world.entity.animal.Bucketable
- net.minecraft.world.entity.animal.Cat
+ net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
- net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
+ net.minecraft.world.entity.animal.Cat$CatTemptGoal
- net.minecraft.world.entity.animal.Chicken
+ net.minecraft.world.entity.animal.Cod
- net.minecraft.world.entity.animal.Cow
+ net.minecraft.world.entity.animal.Dolphin
- net.minecraft.world.entity.animal.Dolphin$1
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
- net.minecraft.world.entity.animal.Fox$1
+ net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
- net.minecraft.world.entity.animal.Fox$FaceplantGoal
+ net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
- net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
+ net.minecraft.world.entity.animal.Fox$FoxBreedGoal
- net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
+ net.minecraft.world.entity.animal.Fox$FoxFloatGoal
- net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
+ net.minecraft.world.entity.animal.Fox$FoxGroupData
- net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Fox$FoxLookControl
- net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
+ net.minecraft.world.entity.animal.Fox$FoxMoveControl
- net.minecraft.world.entity.animal.Fox$FoxPanicGoal
+ net.minecraft.world.entity.animal.Fox$FoxPounceGoal
- net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
+ net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
- net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
+ net.minecraft.world.entity.animal.Fox$SeekShelterGoal
- net.minecraft.world.entity.animal.Fox$SleepGoal
+ net.minecraft.world.entity.animal.Fox$StalkPreyGoal
- net.minecraft.world.entity.animal.Fox$Type
+ net.minecraft.world.entity.animal.goat.Goat
+ net.minecraft.world.entity.animal.goat.package-info
+ net.minecraft.world.entity.animal.IronGolem
- net.minecraft.world.entity.animal.IronGolem$Crackiness
+ net.minecraft.world.entity.animal.MushroomCow
- net.minecraft.world.entity.animal.MushroomCow$MushroomType
+ net.minecraft.world.entity.animal.Ocelot
- net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
- net.minecraft.world.entity.animal.Panda
+ net.minecraft.world.entity.animal.Panda$Gene
- net.minecraft.world.entity.animal.Panda$PandaAttackGoal
+ net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
- net.minecraft.world.entity.animal.Panda$PandaBreedGoal
+ net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
- net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
+ net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
- net.minecraft.world.entity.animal.Panda$PandaMoveControl
+ net.minecraft.world.entity.animal.Panda$PandaPanicGoal
- net.minecraft.world.entity.animal.Panda$PandaRollGoal
+ net.minecraft.world.entity.animal.Panda$PandaSitGoal
- net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
+ net.minecraft.world.entity.animal.Parrot
- net.minecraft.world.entity.animal.Parrot$1
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$1
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
- net.minecraft.world.entity.animal.TropicalFish$1
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$1
+ net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
- net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
- net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
+ net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
- net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
- net.minecraft.world.entity.animal.WaterAnimal
+ net.minecraft.world.entity.animal.Wolf
- net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- net.minecraft.world.level.block.entity.BellBlockEntity
+ net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
- net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityTicker
+ net.minecraft.world.level.block.entity.BlockEntityType
- net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
+ net.minecraft.world.level.block.entity.BlockEntityType$Builder
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
+ net.minecraft.world.level.block.entity.ChestLidController
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JukeboxBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity$1
- net.minecraft.world.level.block.entity.LecternBlockEntity$2
+ net.minecraft.world.level.block.entity.LidBlockEntity
- net.minecraft.world.level.block.entity.package-info
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ net.minecraft.world.level.block.entity.SignBlockEntity
- net.minecraft.world.level.block.entity.SkullBlockEntity
+ net.minecraft.world.level.block.entity.SmokerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
- net.minecraft.world.level.block.grower.AbstractTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.OakTreeGrower
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.SpruceTreeGrower
+ net.minecraft.world.level.block.LightBlock
- net.minecraft.world.level.block.LightningRodBlock
+ net.minecraft.world.level.block.LiquidBlock
- net.minecraft.world.level.block.LiquidBlockContainer
+ net.minecraft.world.level.block.LoomBlock
- net.minecraft.world.level.block.MagmaBlock
+ net.minecraft.world.level.block.MelonBlock
- net.minecraft.world.level.block.Mirror
+ net.minecraft.world.level.block.Mirror$1
- net.minecraft.world.level.block.MossBlock
+ net.minecraft.world.level.block.MultifaceBlock
- net.minecraft.world.level.block.MushroomBlock
+ net.minecraft.world.level.block.MyceliumBlock
- net.minecraft.world.level.block.NetherPortalBlock
+ net.minecraft.world.level.block.NetherPortalBlock$1
+ net.minecraft.world.level.block.NetherrackBlock
- net.minecraft.world.level.block.NetherSproutsBlock
+ net.minecraft.world.level.block.NetherVines
- net.minecraft.world.level.block.NetherWartBlock
- net.minecraft.world.level.block.NoteBlock
+ net.minecraft.world.level.block.NyliumBlock
- net.minecraft.world.level.block.ObserverBlock
+ net.minecraft.world.level.block.OreBlock
- net.minecraft.world.level.block.package-info
- net.minecraft.world.level.block.PipeBlock
+ net.minecraft.world.level.block.piston.MovingPistonBlock
+ net.minecraft.world.level.block.piston.package-info
- net.minecraft.world.level.block.piston.PistonBaseBlock
+ net.minecraft.world.level.block.piston.PistonBaseBlock$1
- net.minecraft.world.level.block.piston.PistonHeadBlock
+ net.minecraft.world.level.block.piston.PistonHeadBlock$1
- net.minecraft.world.level.block.piston.PistonMath
+ net.minecraft.world.level.block.piston.PistonMath$1
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
- net.minecraft.world.level.block.piston.PistonStructureResolver
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PotatoBlock
+ net.minecraft.world.level.block.PowderSnowBlock
- net.minecraft.world.level.block.PoweredBlock
+ net.minecraft.world.level.block.PoweredRailBlock
- net.minecraft.world.level.block.PoweredRailBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock
- net.minecraft.world.level.block.PressurePlateBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
- net.minecraft.world.level.block.PumpkinBlock
+ net.minecraft.world.level.block.RailBlock
- net.minecraft.world.level.block.RailBlock$1
+ net.minecraft.world.level.block.RailState
- net.minecraft.world.level.block.RailState$1
- net.minecraft.world.level.block.RedstoneLampBlock
+ net.minecraft.world.level.block.RedStoneOreBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock
- net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
+ net.minecraft.world.level.block.RedstoneWallTorchBlock
- net.minecraft.world.level.block.RedStoneWireBlock
+ net.minecraft.world.level.block.RedStoneWireBlock$1
- net.minecraft.world.level.block.RenderShape
+ net.minecraft.world.level.block.RepeaterBlock
- net.minecraft.world.level.block.RespawnAnchorBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock$1
- net.minecraft.world.level.block.RodBlock
+ net.minecraft.world.level.block.RodBlock$1
- net.minecraft.world.level.block.RootedDirtBlock
+ net.minecraft.world.level.block.RootsBlock
- net.minecraft.world.level.block.RotatedPillarBlock
+ net.minecraft.world.level.block.RotatedPillarBlock$1
- net.minecraft.world.level.block.Rotation
+ net.minecraft.world.level.block.Rotation$1
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.SculkSensorBlock
+ net.minecraft.world.level.block.SeagrassBlock
- net.minecraft.world.level.block.SeaPickleBlock
- net.minecraft.world.level.block.ShulkerBoxBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock$1
- net.minecraft.world.level.block.SignBlock
+ net.minecraft.world.level.block.SimpleWaterloggedBlock
- net.minecraft.world.level.block.SkullBlock
+ net.minecraft.world.level.block.SkullBlock$Type
- net.minecraft.world.level.block.SkullBlock$Types
+ net.minecraft.world.level.block.SlabBlock
- net.minecraft.world.level.block.SlabBlock$1
+ net.minecraft.world.level.block.SlimeBlock
- net.minecraft.world.level.block.SmallDripleafBlock
+ net.minecraft.world.level.block.SmithingTableBlock
- net.minecraft.world.level.block.SmokerBlock
+ net.minecraft.world.level.block.SnowLayerBlock
- net.minecraft.world.level.block.SnowLayerBlock$1
+ net.minecraft.world.level.block.SnowyDirtBlock
- net.minecraft.world.level.block.SoulFireBlock
+ net.minecraft.world.level.block.SoulSandBlock
- net.minecraft.world.level.block.SoundType
+ net.minecraft.world.level.block.SpawnerBlock
- net.minecraft.world.level.block.SpongeBlock
+ net.minecraft.world.level.block.SporeBlossomBlock
- net.minecraft.world.level.block.SpreadingSnowyDirtBlock
+ net.minecraft.world.level.block.StainedGlassBlock
- net.minecraft.world.level.block.StainedGlassPaneBlock
+ net.minecraft.world.level.block.StairBlock
- net.minecraft.world.level.block.StairBlock$1
+ net.minecraft.world.level.block.StandingSignBlock
- net.minecraft.world.level.block.state.BlockBehaviour
+ net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
- net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
+ net.minecraft.world.level.block.state.BlockBehaviour$Properties
- net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
+ net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
- net.minecraft.world.level.block.state.BlockState
- net.minecraft.world.level.block.state.package-info
+ net.minecraft.world.level.block.state.pattern.BlockInWorld
- net.minecraft.world.level.block.state.pattern.BlockPattern
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
+ net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
- net.minecraft.world.level.block.state.pattern.package-info
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ComparatorMode
- net.minecraft.world.level.block.state.properties.DirectionProperty
+ net.minecraft.world.level.block.state.properties.DoorHingeSide
- net.minecraft.world.level.block.state.properties.DoubleBlockHalf
+ net.minecraft.world.level.block.state.properties.DripstoneThickness
- net.minecraft.world.level.block.state.properties.EnumProperty
+ net.minecraft.world.level.block.state.properties.Half
- net.minecraft.world.level.block.state.properties.IntegerProperty
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.PistonType
+ net.minecraft.world.level.block.state.properties.Property
- net.minecraft.world.level.block.state.properties.Property$1
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.SculkSensorPhase
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.Tilt
+ net.minecraft.world.level.block.state.properties.WallSide
- net.minecraft.world.level.block.state.properties.WoodType
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
+ net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StemGrownBlock
- net.minecraft.world.level.block.StoneButtonBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
+ net.minecraft.world.level.block.SupportType$1
- net.minecraft.world.level.block.SupportType$2
+ net.minecraft.world.level.block.SupportType$3
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TintedGlassBlock
- net.minecraft.world.level.block.TntBlock
+ net.minecraft.world.level.block.TorchBlock
- net.minecraft.world.level.block.TrapDoorBlock
+ net.minecraft.world.level.block.TrapDoorBlock$1
- net.minecraft.world.level.block.TrappedChestBlock
+ net.minecraft.world.level.block.TripWireBlock
- net.minecraft.world.level.block.TripWireBlock$1
+ net.minecraft.world.level.block.TripWireHookBlock
- net.minecraft.world.level.block.TripWireHookBlock$1
+ net.minecraft.world.level.block.TurtleEggBlock
- net.minecraft.world.level.block.TwistingVinesBlock
+ net.minecraft.world.level.block.TwistingVinesPlantBlock
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WeatheringCopper
- net.minecraft.world.level.block.WeatheringCopper$WeatherState
+ net.minecraft.world.level.block.WeatheringCopperFullBlock
- net.minecraft.world.level.block.WeatheringCopperSlabBlock
+ net.minecraft.world.level.block.WeatheringCopperStairBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVinesBlock
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.border.BorderChangeListener
+ net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
- net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
+ net.minecraft.world.level.border.WorldBorder
- net.minecraft.world.level.border.WorldBorder$1
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.BulkSectionAccess
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkBiomeContainer
+ net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.EmptyLevelChunk$EmptyChunkBiomeContainer
+ net.minecraft.world.level.chunk.FeatureAccess
- net.minecraft.world.level.chunk.GlobalPalette
+ net.minecraft.world.level.chunk.HashMapPalette
- net.minecraft.world.level.chunk.ImposterProtoChunk
+ net.minecraft.world.level.chunk.LevelChunk
- net.minecraft.world.level.chunk.LevelChunk$1
+ net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
- net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
+ net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- net.minecraft.world.level.chunk.LevelChunkSection
+ net.minecraft.world.level.chunk.LightChunkGetter
- net.minecraft.world.level.chunk.LinearPalette
+ net.minecraft.world.level.chunk.OldDataLayer
+ net.minecraft.world.level.chunk.package-info
- net.minecraft.world.level.chunk.Palette
- net.minecraft.world.level.chunk.PalettedContainer
+ net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
+ net.minecraft.world.level.chunk.PaletteResize
- net.minecraft.world.level.chunk.ProtoChunk
+ net.minecraft.world.level.chunk.ProtoTickList
- net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.EntityStorage
+ net.minecraft.world.level.chunk.storage.IOWorker
- net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
+ net.minecraft.world.level.chunk.storage.IOWorker$Priority
- net.minecraft.world.level.chunk.storage.OldChunkStorage
+ net.minecraft.world.level.chunk.storage.OldChunkStorage$1
- net.minecraft.world.level.chunk.storage.OldChunkStorage$OldLevelChunk
+ net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixer
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.CarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CarverDebugSettings
- net.minecraft.world.level.levelgen.carver.CarvingContext
+ net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration
+ net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.HeightProvider
+ net.minecraft.world.level.levelgen.heightproviders.UniformHeight
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces$1
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$Properties
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
- net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
+ net.minecraft.world.level.levelgen.structure.StructurePiece
- net.minecraft.world.level.levelgen.structure.StructurePiece$1
+ net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
- net.minecraft.world.level.storage.threaded.package-info
+ net.minecraft.world.level.timers.FunctionCallback
- net.minecraft.world.level.timers.FunctionCallback$Serializer
+ net.minecraft.world.level.timers.FunctionTagCallback
- net.minecraft.world.level.timers.FunctionTagCallback$Serializer
+ net.minecraft.world.level.timers.package-info
+ net.minecraft.world.level.timers.TimerCallback
- net.minecraft.world.level.timers.TimerCallback$Serializer
+ net.minecraft.world.level.timers.TimerCallbacks
- net.minecraft.world.level.timers.TimerQueue
+ net.minecraft.world.level.timers.TimerQueue$1
- net.minecraft.world.level.timers.TimerQueue$Event
- net.minecraft.world.package-info
+ net.minecraft.world.phys.AABB
- net.minecraft.world.phys.BlockHitResult
+ net.minecraft.world.phys.EntityHitResult
- net.minecraft.world.phys.HitResult
+ net.minecraft.world.phys.HitResult$Type
- net.minecraft.world.phys.package-info
+ net.minecraft.world.phys.shapes.ArrayVoxelShape
- net.minecraft.world.phys.shapes.ArrayVoxelShape$1
+ net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
- net.minecraft.world.phys.shapes.BooleanOp
+ net.minecraft.world.phys.shapes.CollisionContext
- net.minecraft.world.phys.shapes.CubePointRange
+ net.minecraft.world.phys.shapes.CubeVoxelShape
- net.minecraft.world.phys.shapes.DiscreteCubeMerger
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- net.minecraft.world.phys.shapes.EntityCollisionContext
+ net.minecraft.world.phys.shapes.EntityCollisionContext$1
- net.minecraft.world.phys.shapes.IdenticalMerger
+ net.minecraft.world.phys.shapes.IndexMerger
- net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
+ net.minecraft.world.phys.shapes.IndirectMerger
- net.minecraft.world.phys.shapes.NonOverlappingMerger
+ net.minecraft.world.phys.shapes.OffsetDoubleList
+ net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.shapes.Shapes
+ net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
- net.minecraft.world.phys.shapes.SliceShape
+ net.minecraft.world.phys.shapes.SubShape
- net.minecraft.world.phys.shapes.VoxelShape
- net.minecraft.world.phys.Vec2
+ net.minecraft.world.phys.Vec3
- net.minecraft.world.scores.criteria.ObjectiveCriteria
+ net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
- net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.Objective
+ net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.Score
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.Team
- net.minecraft.world.scores.Team$CollisionRule
+ net.minecraft.world.scores.Team$Visibility
```

</details>

<br/>
<html><table>
<tr><td colspan="2" align="center"><img width="5000" height="0"><br/>
<a href="https://github.com/PixiGeko/Minecraft-generated-data">Minecraft-generated-data</a>
<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="5000" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
</table></html>
<br/>