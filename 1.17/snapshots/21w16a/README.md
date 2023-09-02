<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 21w16a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>21w16a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2021-04-21T16:41:14+00:00</td></tr>
<tr><th>SHA1</th><td>f083b566dd515b5706ead9522c42b187b3f2f2f6</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/f083b566dd515b5706ead9522c42b187b3f2f2f6/21w16a.json">https://piston-meta.mojang.com/v1/packages/f083b566dd515b5706ead9522c42b187b3f2f2f6/21w16a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/f425401a00adf0112fde624ee80c66333530f8a1/1.17.json">https://piston-meta.mojang.com/v1/packages/f425401a00adf0112fde624ee80c66333530f8a1/1.17.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/b8bacc67a9db84db59e2f97e9a9fba3a242480a8/server.jar">https://piston-data.mojang.com/v1/objects/b8bacc67a9db84db59e2f97e9a9fba3a242480a8/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/63799f9f0f3738a0832cf3a3a9593b2f8adc97c6/server.txt">https://piston-data.mojang.com/v1/objects/63799f9f0f3738a0832cf3a3a9593b2f8adc97c6/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/f124f2aad604e88f27f010834d82c7af85506b6c/client.jar">https://piston-data.mojang.com/v1/objects/f124f2aad604e88f27f010834d82c7af85506b6c/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/7a8e3a33afdd6e6ab669852685e1b12ba338234a/client.txt">https://piston-data.mojang.com/v1/objects/7a8e3a33afdd6e6ab669852685e1b12ba338234a/client.txt</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/21w15a">21w15a</a>
## File structure

<details><summary>data/</summary>

```diff
-  minecraft/tags/blocks/lush_plants_replaceable.json
+  minecraft/tags/blocks/moss_replaceable.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/shaders/core/rendertype_text_intensity.fsh
+  minecraft/shaders/core/rendertype_text_intensity.json
+  minecraft/shaders/core/rendertype_text_intensity.vsh
+  minecraft/shaders/core/rendertype_text_intensity_see_through.fsh
+  minecraft/shaders/core/rendertype_text_intensity_see_through.json
+  minecraft/shaders/core/rendertype_text_intensity_see_through.vsh
-  minecraft/textures/block/root_vines_head.png
```

</details>

## Registries

<details><summary>custom_stat.txt</summary>

```diff
- minecraft:play_one_minute
+ minecraft:play_time
+ minecraft:total_world_time
```

</details>

<details><summary>worldgen/feature.txt</summary>

```diff
- minecraft:emerald_ore
+ minecraft:replace_single_block
```

</details>

## Tags

<details><summary>list</summary>

```diff
- blocks/lush_plants_replaceable.json
+ blocks/moss_replaceable.json
```

</details>

<details><summary>blocks/bamboo_plantable_on.json</summary>

```diff
- minecraft:grass_block
- minecraft:mycelium
```

</details>

<details><summary>blocks/dirt.json</summary>

```diff
+ minecraft:grass_block
+ minecraft:mycelium
+ minecraft:moss_block
```

</details>

<details><summary>blocks/enderman_holdable.json</summary>

```diff
- minecraft:grass_block
```

</details>

<details><summary>blocks/lush_ground_replaceable.json</summary>

```diff
- #minecraft:lush_plants_replaceable
+ #minecraft:moss_replaceable
+ minecraft:gravel
+ minecraft:sand
```

</details>

## Misc

<details><summary>tags.txt</summary>

```diff
- blocks/lush_plants_replaceable.json
+ blocks/moss_replaceable.json
```

</details>

<details><summary>textures.txt</summary>

```diff
- block/root_vines_head.png
```

</details>

## Mappings

















<details><summary>com.mojang.blaze3d.platform.GlConst</summary>

```diff
+ int GL_RED
+ int GL_RG
- int GL_INTENSITY
- int GL_LUMINANCE
- int GL_LUMINANCE_ALPHA
```

</details>
























































































































































<details><summary>net.minecraft.SharedConstants</summary>

```diff
+ boolean ALLOW_INCOMPATIBLE_WORLD_HEIGHT
+ boolean AQUIFER_ENABLED_CARVERS
+ boolean DEBUG_DISABLE_FLUID_GENERATION
+ boolean DEBUG_DISABLE_ORE_VEINS
+ boolean DEBUG_ORE_VEINS
- boolean DEBUG_DISABLE_WATER_GENERATION
```

</details>




















































































<details><summary>net.minecraft.client.Camera</summary>

```diff
+ Camera$NearPlane getNearPlane()
```

</details>





























































































































































































































































































































































































































<details><summary>net.minecraft.client.renderer.GameRenderer</summary>

```diff
+ ShaderInstance rendertypeTextIntensitySeeThroughShader
+ ShaderInstance rendertypeTextIntensityShader
+ ShaderInstance getRendertypeTextIntensitySeeThroughShader()
+ ShaderInstance getRendertypeTextIntensityShader()
```

</details>






















<details><summary>net.minecraft.client.renderer.RenderType</summary>

```diff
+ Function TEXT_INTENSITY
+ Function TEXT_INTENSITY_SEE_THROUGH
+ RenderType lambda$static$18(ResourceLocation)
+ RenderType lambda$static$19(ResourceLocation)
+ RenderType textIntensity(ResourceLocation)
+ RenderType textIntensitySeeThrough(ResourceLocation)
```

</details>






























































































<details><summary>net.minecraft.client.renderer.entity.FishingHookRenderer</summary>

```diff
+ double VIEW_BOBBING_SCALE
```

</details>















































































<details><summary>net.minecraft.client.resources.ClientPackSource</summary>

```diff
+ Component APPLYING_PACK_TEXT
+ CompletableFuture downloadAndSelectResourcePack(String,boolean)
+ CompletionStage lambda$downloadAndSelectResourcePack$3(Object)
+ PackResources lambda$createProgrammerArtPack$9(File)
+ PackResources lambda$setServerPack$7(File)
+ void lambda$downloadAndSelectResourcePack$6(Throwable)
+ void lambda$null$2(Minecraft)
+ void lambda$null$4(Minecraft,boolean)
+ void lambda$null$5(Minecraft)
- CompletableFuture downloadAndSelectResourcePack(String)
- CompletionStage lambda$downloadAndSelectResourcePack$2(Object)
- PackResources lambda$createProgrammerArtPack$7(File)
- PackResources lambda$setServerPack$6(File)
- void lambda$downloadAndSelectResourcePack$5(Throwable)
- void lambda$null$3(Minecraft,boolean)
- void lambda$null$4(Minecraft)
```

</details>

















































<details><summary>net.minecraft.client.server.IntegratedServer</summary>

```diff
+ void tickPaused()
```

</details>












































































































































































<details><summary>net.minecraft.data.recipes.RecipeBuilder</summary>

```diff
+ Item getResult()
+ void save(java.util.function.Consumer,net.minecraft.resources.ResourceLocation)
- void save(java.util.function.Consumer)
+ ResourceLocation getDefaultRecipeId(ItemLike)
+ void save(Consumer)
+ void save(String)
```

</details>

<details><summary>net.minecraft.data.recipes.ShapedRecipeBuilder</summary>

```diff
- Logger LOGGER
+ Item getResult()
- void <clinit>()
- void save(Consumer)
- void save(String)
```

</details>

<details><summary>net.minecraft.data.recipes.ShapelessRecipeBuilder</summary>

```diff
- Logger LOGGER
+ Item getResult()
- void <clinit>()
- void save(Consumer)
- void save(String)
```

</details>

<details><summary>net.minecraft.data.recipes.SimpleCookingRecipeBuilder</summary>

```diff
+ Item getResult()
+ RecipeBuilder group(String)
+ RecipeBuilder unlockedBy(CriterionTriggerInstance)
- void save(Consumer)
- void save(String)
```

</details>

<details><summary>net.minecraft.data.recipes.SingleItemRecipeBuilder</summary>

```diff
+ Item getResult()
+ RecipeBuilder group(String)
+ RecipeBuilder unlockedBy(CriterionTriggerInstance)
+ SingleItemRecipeBuilder unlockedBy(CriterionTriggerInstance)
- SingleItemRecipeBuilder unlocks(CriterionTriggerInstance)
- void save(String)
```

</details>















<details><summary>net.minecraft.data.worldgen.Carvers</summary>

```diff
+ ConfiguredWorldCarver PROTOTYPE_CREVICE
- ConfiguredWorldCarver PROTOTYPE_CRACK
```

</details>

<details><summary>net.minecraft.data.worldgen.Features</summary>

```diff
+ ImmutableList ORE_COAL_TARGET_LIST
+ ImmutableList ORE_COPPER_TARGET_LIST
+ ImmutableList ORE_EMERALD_TARGET_LIST
```

</details>










































































































































































































































































































































































































<details><summary>net.minecraft.tags.BlockTags</summary>

```diff
+ Tag$Named MOSS_REPLACEABLE
- Tag$Named LUSH_PLANTS_REPLACEABLE
```

</details>





































<details><summary>net.minecraft.util.StringUtil</summary>

```diff
+ Pattern LINE_END_PATTERN
+ boolean endsWithNewLine(String)
```

</details>
























































































































































<details><summary>net.minecraft.world.InteractionResult</summary>

```diff
+ InteractionResult CONSUME_PARTIAL
+ boolean shouldAwardStats()
```

</details>

















<details><summary>net.minecraft.world.entity.Entity</summary>

```diff
+ boolean hasGlowingTag
- boolean glowing
+ boolean hasGlowingTag()
+ boolean isCurrentlyGlowing()
+ void setGlowingTag(boolean)
- boolean isGlowing()
- void setGlowing(boolean)
```

</details>











<details><summary>net.minecraft.world.entity.LivingEntity</summary>

```diff
+ boolean isCurrentlyGlowing()
+ void updateGlowingStatus()
```

</details>























































































































































































































































































































































































































































<details><summary>net.minecraft.world.item.DebugStickItem</summary>

```diff
+ boolean handleInteraction(ItemStack)
- void handleInteraction(ItemStack)
```

</details>


























































































































































































































































































<details><summary>net.minecraft.world.level.chunk.ChunkGenerator</summary>

```diff
+ Aquifer createAquifer(ChunkAccess)
```

</details>























































<details><summary>net.minecraft.world.level.levelgen.Aquifer</summary>

```diff
+ BlockState computeState(net.minecraft.world.level.levelgen.BaseStoneSource,int,int,int,double)
+ boolean shouldScheduleFluidUpdate()
+ int ALWAYS_LAVA_AT_OR_BELOW_Y_INDEX
- boolean shouldScheduleWaterUpdate
- double lastBarrierDensity
- int ALWAYS_LAVA_BELOW_Y_INDEX
- int gridSizeX
- int gridSizeZ
- int lastWaterLevel
- int minGridX
- int minGridY
- int minGridZ
- int X_RANGE
- int X_SEPARATION
- int X_SPACING
- int Y_RANGE
- int Y_SEPARATION
- int Y_SPACING
- int Z_RANGE
- int Z_SEPARATION
- int Z_SPACING
- int[] aquiferCache
- long[] aquiferLocationCache
- NoiseGeneratorSettings noiseGeneratorSettings
- NoiseSampler sampler
- NormalNoise barrierNoise
- NormalNoise waterLevelNoise
+ Aquifer create(NoiseSampler,int,int)
+ Aquifer createDisabled(BlockState)
- boolean isLavaLevel(int)
- boolean shouldScheduleWaterUpdate()
- double calculatePressure(int,double,int,int)
- double getLastBarrierDensity()
- double similarity(int,int)
- int computeAquifer(int,int,int)
- int getIndex(int,int,int)
- int getLastWaterLevel()
- int getWaterLevel(long)
- int gridX(int)
- int gridY(int)
- int gridZ(int)
- void <init>(NoiseSampler,int,int)
- void computeAt(int,int,int)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.NoiseInterpolator</summary>

```diff
+ void <init>(NoiseInterpolator$NoiseColumnFiller)
- void <init>(NoiseInterpolator$NoiseColumnFiller)
```

</details>





<details><summary>net.minecraft.world.level.levelgen.SingleBaseStoneSource</summary>

```diff
+ BlockState getBaseBlock(int,int,int)
- BlockState getBaseStone(int,int,int)
```

</details>






<details><summary>net.minecraft.world.level.levelgen.carver.CarverConfiguration</summary>

```diff
+ boolean aquifersEnabled
+ App lambda$static$6(RecordCodecBuilder$Instance)
+ Boolean lambda$null$4(CarverConfiguration)
+ CarverDebugSettings lambda$null$5(CarverConfiguration)
+ void <init>(CarverDebugSettings)
- App lambda$static$5(RecordCodecBuilder$Instance)
- CarverDebugSettings lambda$null$4(CarverConfiguration)
- void <init>(CarverDebugSettings)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.carver.CaveWorldCarver</summary>

```diff
+ boolean carve(BitSet)
+ boolean carve(BitSet)
+ void createRoom(WorldCarver$CarveSkipChecker)
+ void createTunnel(WorldCarver$CarveSkipChecker)
- boolean carve(BitSet)
- boolean carve(BitSet)
- void createRoom(WorldCarver$CarveSkipChecker)
- void createTunnel(WorldCarver$CarveSkipChecker)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.carver.NetherWorldCarver</summary>

```diff
+ boolean carveBlock(MutableBoolean)
+ boolean carveBlock(MutableBoolean)
- boolean carveBlock(MutableBoolean)
- boolean carveBlock(MutableBoolean)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver</summary>

```diff
+ boolean carveBlock(Aquifer)
+ boolean carveBlock(MutableBoolean)
+ boolean carveBlock(MutableBoolean)
- boolean carveBlock(BlockPos$MutableBlockPos,int)
- boolean carveBlock(MutableBoolean)
- boolean carveBlock(MutableBoolean)
```

</details>



















<details><summary>net.minecraft.world.level.levelgen.feature.Feature</summary>

```diff
+ Feature REPLACE_SINGLE_BLOCK
- Feature EMERALD_ORE
```

</details>























<details><summary>net.minecraft.world.level.levelgen.feature.RootSystemFeature</summary>

```diff
+ boolean isAllowedTreeSpace(BlockState,int,int)
```

</details>










<details><summary>net.minecraft.world.level.levelgen.feature.StructureFeature</summary>

```diff
+ WeightedRandomList getSpecialUndergroundWaterAnimals()
```

</details>





























<details><summary>net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration</summary>

```diff
+ List targetStates
- BlockState state
- BlockState target
+ App lambda$static$1(RecordCodecBuilder$Instance)
+ List lambda$null$0(ReplaceBlockConfiguration)
+ void <init>(List)
- App lambda$static$2(RecordCodecBuilder$Instance)
- BlockState lambda$null$0(ReplaceBlockConfiguration)
- BlockState lambda$null$1(ReplaceBlockConfiguration)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration</summary>

```diff
+ int allowedVerticalWaterForTree
+ App lambda$static$12(RecordCodecBuilder$Instance)
+ Integer lambda$null$11(RootSystemConfiguration)
+ void <init>(BlockStateProvider,int,int)
- App lambda$static$11(RecordCodecBuilder$Instance)
- void <init>(BlockStateProvider,int)
```

</details>









































































<details><summary>net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor</summary>

```diff
+ boolean hasSturdyNeighbours(BoundingBox,int,int,int,int)
+ void maybePlaceCobWeb(Random,float,int,int,int)
- void placeCobWeb(Random,float,int,int,int)
```

</details>








































































































<details><summary>net.minecraft.world.level.material.MaterialColor</summary>

```diff
+ MaterialColor GLOW_LICHEN
```

</details>


































































































































































































































<details><summary>Added and removed classes</summary>

```diff
+ net.minecraft.client.Camera$NearPlane
+ net.minecraft.util.datafix.fixes.StatsRenameFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.SwimStatsRenameFix
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
+ net.minecraft.world.level.block.grower.AzaleaTreeGrower
+ net.minecraft.world.level.block.InfestedRotatedPillarBlock
- net.minecraft.world.level.block.IronBarsBlock
+ net.minecraft.world.level.block.JigsawBlock
- net.minecraft.world.level.block.JukeboxBlock
+ net.minecraft.world.level.block.KelpBlock
- net.minecraft.world.level.block.KelpPlantBlock
+ net.minecraft.world.level.block.LadderBlock
- net.minecraft.world.level.block.LadderBlock$1
+ net.minecraft.world.level.block.LanternBlock
- net.minecraft.world.level.block.LavaCauldronBlock
+ net.minecraft.world.level.block.LayeredCauldronBlock
- net.minecraft.world.level.block.LeavesBlock
+ net.minecraft.world.level.block.LecternBlock
- net.minecraft.world.level.block.LecternBlock$1
+ net.minecraft.world.level.block.LevelEvent
- net.minecraft.world.level.block.LeverBlock
+ net.minecraft.world.level.block.LeverBlock$1
- net.minecraft.world.level.block.LightBlock
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
+ net.minecraft.world.level.block.PipeBlock
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
+ net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
+ net.minecraft.world.level.levelgen.BaseStoneSource
- net.minecraft.world.level.levelgen.Beardifier
+ net.minecraft.world.level.levelgen.Cavifier
- net.minecraft.world.level.levelgen.Cavifier$QuantizedSpaghettiRarity
+ net.minecraft.world.level.levelgen.Column
- net.minecraft.world.level.levelgen.Column$Line
+ net.minecraft.world.level.levelgen.Column$Range
- net.minecraft.world.level.levelgen.Column$Ray
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.Decoratable
+ net.minecraft.world.level.levelgen.DepthBasedReplacingBaseStoneSource
- net.minecraft.world.level.levelgen.FlatLevelSource
+ net.minecraft.world.level.levelgen.GenerationStep
- net.minecraft.world.level.levelgen.GenerationStep$Carving
+ net.minecraft.world.level.levelgen.GenerationStep$Decoration
- net.minecraft.world.level.levelgen.GeodeBlockSettings
+ net.minecraft.world.level.levelgen.GeodeCrackSettings
- net.minecraft.world.level.levelgen.GeodeLayerSettings
+ net.minecraft.world.level.levelgen.Heightmap
- net.minecraft.world.level.levelgen.Heightmap$Types
+ net.minecraft.world.level.levelgen.Heightmap$Usage
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator$OreVeinNoiseSource
+ net.minecraft.world.level.levelgen.OreVeinifier
```

</details>



































































































































































































































<details><summary>net.minecraft.data.models.BlockModelGenerators</summary>

```diff
+ void createInfestedDeepslate()
```

</details>

























<details><summary>net.minecraft.data.recipes.RecipeProvider</summary>

```diff
+ String getBlastingRecipeName(ItemLike)
+ String getConversionRecipeName(ItemLike)
+ String getItemName(ItemLike)
+ String getSimpleRecipeName(ItemLike)
+ String getSmeltingRecipeName(ItemLike)
+ void nineBlockStorageRecipes(ItemLike)
+ void nineBlockStorageRecipes(String)
+ void nineBlockStorageRecipesRecipesWithCustomUnpacking(String)
+ void nineBlockStorageRecipesWithCustomPacking(String)
+ void oneToOneConversionRecipe(String,int)
+ void oneToOneConversionRecipe(String)
+ void simpleCookingRecipe(ItemLike,float)
- String getBlockName(ItemLike)
- String getFromName(ItemLike)
- void compactMaterialRecipes(ItemLike)
```

</details>

<details><summary>net.minecraft.data.recipes.ShapedRecipeBuilder$Result</summary>

```diff
- ShapedRecipeBuilder this$0
+ void <init>(ResourceLocation)
- void <init>(ResourceLocation)
```

</details>

















<details><summary>net.minecraft.data.worldgen.BiomeDefaultFeatures</summary>

```diff
+ void addDefaultUndergroundVariety(BiomeGenerationSettings$Builder,boolean)
```

</details>



<details><summary>net.minecraft.data.worldgen.Features$States</summary>

```diff
+ BlockState DEEPSLATE_COAL_ORE
+ BlockState DEEPSLATE_COPPER_ORE
+ BlockState DEEPSLATE_EMERALD_ORE
```

</details>































































































































































































































































































































































































<details><summary>net.minecraft.stats.ServerStatsCounter</summary>

```diff
- int lastStatRequest
- int STAT_REQUEST_COOLDOWN
```

</details>


<details><summary>net.minecraft.stats.Stats</summary>

```diff
+ ResourceLocation PLAY_TIME
+ ResourceLocation TOTAL_WORLD_TIME
- ResourceLocation PLAY_ONE_MINUTE
```

</details>

























































































































































































































































































































































































































































































































































































































































































































































































































































<details><summary>net.minecraft.world.level.block.AzaleaBlock</summary>

```diff
+ AzaleaTreeGrower TREE_GROWER
+ VoxelShape SHAPE
- VoxelShape SUPPORT_SHAPE
+ boolean isBonemealSuccess(BlockState)
+ boolean isValidBonemealTarget(BlockState,boolean)
+ void performBonemeal(BlockState)
+ VoxelShape getShape(CollisionContext)
- VoxelShape getBlockSupportShape(BlockPos)
```

</details>








































































<details><summary>net.minecraft.world.level.block.InfestedBlock</summary>

```diff
+ Map HOST_TO_INFESTED_STATES
+ Map INFESTED_TO_HOST_STATES
+ BlockState getNewStateWithProperties(Supplier)
+ BlockState hostStateByInfested(BlockState)
+ BlockState infestedStateByHost(BlockState)
+ BlockState lambda$getNewStateWithProperties$2(BlockState)
+ BlockState lambda$hostStateByInfested$1()
+ BlockState lambda$infestedStateByHost$0(BlockState)
- BlockState stateByHostBlock(Block)
```

</details>




































































































<details><summary>net.minecraft.world.level.levelgen.NoiseGeneratorSettings</summary>

```diff
+ boolean oreVeinsEnabled
+ boolean isOreVeinsEnabled()
+ void <init>(BlockState,int,int,int,int,boolean,boolean,boolean,boolean,boolean)
- void <init>(BlockState,int,int,int,int,boolean,boolean,boolean,boolean)
```

</details>










<details><summary>net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration</summary>

```diff
+ void <init>(CanyonCarverConfiguration$CanyonShapeConfiguration)
- void <init>(CanyonCarverConfiguration$CanyonShapeConfiguration)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.carver.CanyonWorldCarver</summary>

```diff
+ boolean carve(BitSet)
+ boolean carve(BitSet)
+ void doCarve(BitSet)
- boolean carve(BitSet)
- boolean carve(BitSet)
- void doCarve(BitSet)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.carver.CarverDebugSettings</summary>

```diff
+ BlockState barrierState
+ BlockState lavaState
+ BlockState waterState
+ BlockState getBarrierState()
+ BlockState getLavaState()
+ BlockState getWaterState()
+ CarverDebugSettings of(BlockState)
+ CarverDebugSettings of(BlockState)
+ void <init>(BlockState)
- void <init>(BlockState)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration</summary>

```diff
+ void <init>(FloatProvider)
+ void <init>(FloatProvider)
- void <init>(FloatProvider)
- void <init>(FloatProvider)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver</summary>

```diff
+ boolean carve(BitSet)
- boolean carve(BitSet)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver</summary>

```diff
+ boolean carveBlock(MutableBoolean)
+ boolean carveBlock(MutableBoolean)
- boolean carveBlock(MutableBoolean)
- boolean carveBlock(MutableBoolean)
```

</details>

<details><summary>net.minecraft.world.level.levelgen.carver.WorldCarver</summary>

```diff
+ BaseStoneSource STONE_SOURCE
+ boolean carve(net.minecraft.world.level.levelgen.carver.CarvingContext,net.minecraft.world.level.levelgen.carver.CarverConfiguration,net.minecraft.world.level.chunk.ChunkAccess,java.util.function.Function,java.util.Random,net.minecraft.world.level.levelgen.Aquifer,net.minecraft.world.level.ChunkPos,java.util.BitSet)
- boolean carve(net.minecraft.world.level.levelgen.carver.CarvingContext,net.minecraft.world.level.levelgen.carver.CarverConfiguration,net.minecraft.world.level.chunk.ChunkAccess,java.util.function.Function,java.util.Random,int,net.minecraft.world.level.ChunkPos,java.util.BitSet)
+ BlockState getCarveState(Aquifer)
+ BlockState getDebugState(BlockState)
+ boolean carveBlock(MutableBoolean)
+ boolean carveEllipsoid(WorldCarver$CarveSkipChecker)
- BlockState getCaveAirState(CarverConfiguration)
- boolean carveBlock(MutableBoolean)
- boolean carveEllipsoid(WorldCarver$CarveSkipChecker)
```

</details>







































































































































































































<details><summary>net.minecraft.world.level.levelgen.structure.StructurePiece</summary>

```diff
+ void maybeGenerateBlock(BlockState)
- void maybeGenerateBlock(BlockState,boolean)
```

</details>






























































































































































































































































































<details><summary>Added and removed classes</summary>

```diff
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
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
+ net.minecraft.world.level.block.IronBarsBlock
- net.minecraft.world.level.block.JigsawBlock
+ net.minecraft.world.level.block.JukeboxBlock
- net.minecraft.world.level.block.KelpBlock
+ net.minecraft.world.level.block.KelpPlantBlock
- net.minecraft.world.level.block.LadderBlock
+ net.minecraft.world.level.block.LadderBlock$1
- net.minecraft.world.level.block.LanternBlock
+ net.minecraft.world.level.block.LavaCauldronBlock
- net.minecraft.world.level.block.LayeredCauldronBlock
+ net.minecraft.world.level.block.LeavesBlock
- net.minecraft.world.level.block.LecternBlock
+ net.minecraft.world.level.block.LecternBlock$1
- net.minecraft.world.level.block.LevelEvent
+ net.minecraft.world.level.block.LeverBlock
- net.minecraft.world.level.block.LeverBlock$1
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
- net.minecraft.world.level.block.PipeBlock
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
+ net.minecraft.world.level.levelgen.Aquifer$1
+ net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer$AquiferStatus
- net.minecraft.world.level.levelgen.BaseStoneSource
+ net.minecraft.world.level.levelgen.Beardifier
- net.minecraft.world.level.levelgen.Cavifier
+ net.minecraft.world.level.levelgen.Cavifier$QuantizedSpaghettiRarity
- net.minecraft.world.level.levelgen.Column
+ net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Range
+ net.minecraft.world.level.levelgen.Column$Ray
- net.minecraft.world.level.levelgen.DebugLevelSource
+ net.minecraft.world.level.levelgen.Decoratable
- net.minecraft.world.level.levelgen.DepthBasedReplacingBaseStoneSource
+ net.minecraft.world.level.levelgen.FlatLevelSource
- net.minecraft.world.level.levelgen.GenerationStep
+ net.minecraft.world.level.levelgen.GenerationStep$Carving
- net.minecraft.world.level.levelgen.GenerationStep$Decoration
+ net.minecraft.world.level.levelgen.GeodeBlockSettings
- net.minecraft.world.level.levelgen.GeodeCrackSettings
+ net.minecraft.world.level.levelgen.GeodeLayerSettings
- net.minecraft.world.level.levelgen.Heightmap
+ net.minecraft.world.level.levelgen.Heightmap$Types
- net.minecraft.world.level.levelgen.Heightmap$Usage
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.OreVeinifier$VeinType
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