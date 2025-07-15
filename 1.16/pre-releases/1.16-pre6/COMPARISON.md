## Comparison with [1.16-pre5](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16-pre5)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Translations](#translations)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.16-pre5</th><th>1.16-pre6</th></tr><tr><td>World version</td><td><pre>2561</pre></td><td><pre>2562</pre></td></tr><tr><td>Protocol version</td><td><pre>729</pre></td><td><pre>730</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.16-pre5</th><th>1.16-pre6</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
+ gui.recipebook.search_hint: Search...
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.16-pre5</th><th>1.16-pre6</th></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.zombified_piglin.angry</div></th><td>Zombified Piglin angers</td><td>Zombified Piglin grunts angrily</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.server.level.ServerPlayerGameMode +2M | +1P
```
```
XXX.datafix.fixes.BlockRenameFixWithJigsaw -1P
```
```
XXX.ai.goal.RangedCrossbowAttackGoal +1M | +2P
```
```
XXX.ai.sensing.PiglinSpecificSensor +1M
```
```
XXX.entity.monster.Strider +2M
```
```
XXX.entity.monster.ZombifiedPiglin +1M | +2P -2P
```
```
XXX.monster.hoglin.HoglinAi +4M -4M
```
```
XXX.monster.piglin.Piglin +1M -7M
```
```
XXX.monster.piglin.PiglinAi +5M -3M | +1P
```
```
XXX.entity.projectile.ThrownEnderpearl -1M
```
```
XXX.world.level.Level +2M -1M
```
```
XXX.level.block.Block +1M
```
```
XXX.level.block.RedStoneWireBlock +1M -1M | +1P -1P
```
```
XXX.level.block.RedstoneLampBlock -1M
```
```
XXX.block.state.BlockBehaviour +1M -1M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +2M
```
```
XXX.level.material.MaterialColor +7P
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayerGameMode
</summary>

```diff
- GameType getPreviousGameModeForPlayer()
- void setGameModeForPlayer(GameType,GameType)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
</summary>

```diff
- boolean isValidRepellent(ServerLevel,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Strider
</summary>

```diff
- boolean isBeingTempted()
- boolean isPanicking()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.ZombifiedPiglin
</summary>

```diff
- void maybePlayFirstAngerSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.hoglin.HoglinAi
</summary>

```diff
+ boolean isIdle(Hoglin)
- boolean isNearRepellent(Hoglin)
- Optional getSoundForCurrentActivity(Hoglin)
- SoundEvent getSoundForActivity(Hoglin,Activity)
- SoundEvent lambda$getSoundForCurrentActivity$2(Hoglin,Activity)
+ void lambda$playActivitySound$2(Hoglin,Activity)
+ void maybePlayActivitySound(Hoglin)
+ void playActivitySound(Hoglin)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.piglin.Piglin
</summary>

```diff
+ void playAdmiringSound()
+ void playAmbientSound()
+ void playAngrySound()
+ void playCelebrateSound()
+ void playConvertedSound()
+ void playJealousSound()
+ void playRetreatSound()
- void playSound(SoundEvent)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.piglin.PiglinAi
</summary>

```diff
- CopyMemoryWithExpiry babyAvoidNemesis()
- Optional getSoundForCurrentActivity(Piglin)
- SoundEvent getSoundForActivity(Piglin,Activity)
- SoundEvent lambda$getSoundForCurrentActivity$6(Piglin,Activity)
- void holdInOffhand(Piglin,ItemStack)
+ void lambda$playActivitySound$6(Piglin,Activity)
+ void maybePlayActivitySound(Piglin)
+ void playActivitySound(Piglin)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownEnderpearl
</summary>

```diff
+ void onHitBlock(BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
- boolean destroyBlock(BlockPos,boolean,Entity,int)
+ boolean destroyBlock(BlockPos,boolean,Entity)
- boolean setBlock(BlockPos,BlockState,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
- void updateOrDestroy(BlockState,BlockState,LevelAccessor,BlockPos,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RedStoneWireBlock
</summary>

```diff
- void updateIndirectNeighbourShapes(BlockState,LevelAccessor,BlockPos,int,int)
+ void updateIndirectNeighbourShapes(BlockState,LevelAccessor,BlockPos,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RedstoneLampBlock
</summary>

```diff
+ void onPlace(BlockState,Level,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
- void updateIndirectNeighbourShapes(BlockState,LevelAccessor,BlockPos,int,int)
+ void updateIndirectNeighbourShapes(BlockState,LevelAccessor,BlockPos,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
- void updateIndirectNeighbourShapes(LevelAccessor,BlockPos,int,int)
- void updateNeighbourShapes(LevelAccessor,BlockPos,int,int)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.advancements.critereon.PlayerInteractTrigger
+ XXX.blaze3d.vertex.BreakingTextureGenerator
- XXX.blaze3d.vertex.BufferBuilder
+ XXX.blaze3d.vertex.BufferBuilder$1
- XXX.blaze3d.vertex.BufferBuilder$DrawState
+ XXX.blaze3d.vertex.BufferBuilder$State
- XXX.blaze3d.vertex.BufferUploader
+ XXX.blaze3d.vertex.BufferVertexConsumer
+ XXX.blaze3d.vertex.DefaultedVertexConsumer
- XXX.blaze3d.vertex.DefaultVertexFormat
- XXX.blaze3d.vertex.PoseStack
+ XXX.blaze3d.vertex.PoseStack$1
- XXX.blaze3d.vertex.PoseStack$Pose
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.platform.InputConstants$Key +1M
```
```
XXX.minecraft.advancements.CriteriaTriggers +1P
```
```
XXX.advancements.critereon.EntityPredicate +1M
```
```
XXX.gui.components.CommandSuggestions +1M
```
```
XXX.gui.components.CommandSuggestions$SuggestionsList +2M -2M | +1P -1P
```
```
XXX.screens.debug.GameModeSwitcherScreen +1M
```
```
XXX.screens.inventory.AbstractContainerScreen +1M
```
```
XXX.screens.recipebook.RecipeBookComponent +1P
```
```
XXX.renderer.debug.BeeDebugRenderer +9M -7M
```
```
XXX.renderer.entity.ItemRenderer +2M
```
```
XXX.resources.sounds.AbstractSoundInstance +1M
```
```
XXX.data.advancements.NetherAdvancements +1P
```
```
XXX.protocol.game.ClientboundLoginPacket +2M -1M | +1P
```
```
XXX.protocol.game.ClientboundRespawnPacket +2M -1M | +1P
```
```
XXX.server.level.FeatureSimulator +2M -2M
```
```
XXX.server.level.WorldGenRegion +2M -2M
```
```
XXX.util.datafix.DataFixers +4M -30M
```
```
XXX.datafix.fixes.EntityRedundantChanceTagsFix +5M -3M | +1P
```
```
XXX.datafix.fixes.WorldGenSettingsFix +9M -8M
```
```
XXX.world.entity.Entity +1M
```
```
XXX.world.entity.Mob +1M
```
```
XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal -1M
```
```
XXX.entity.monster.Zoglin -3M
```
```
XXX.monster.hoglin.Hoglin +1M -4M
```
```
XXX.world.level.LevelWriter +2M | +2P -2P
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.InputConstants$Key
</summary>

```diff
- OptionalInt getNumericKeyValue()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityPredicate
</summary>

```diff
- void <init>(EntityTypePredicate,DistancePredicate,LocationPredicate,MobEffectsPredicate,NbtPredicate,EntityFlagsPredicate,EntityEquipmentPredicate,PlayerPredicate,FishingHookPredicate,String,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.CommandSuggestions
</summary>

```diff
- List sortSuggestions(Suggestions)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
</summary>

```diff
- void <init>(CommandSuggestions,int,int,int,List,boolean,CommandSuggestions$1)
- void <init>(CommandSuggestions,int,int,int,List,boolean)
+ void <init>(CommandSuggestions,int,int,int,Suggestions,boolean,CommandSuggestions$1)
+ void <init>(CommandSuggestions,int,int,int,Suggestions,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
</summary>

```diff
- GameType getDefaultSelected()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
</summary>

```diff
- void checkHotbarMouseClicked(int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.debug.BeeDebugRenderer
</summary>

```diff
+ boolean lambda$getHiveMembers$10(BlockPos,BeeDebugRenderer$BeeInfo)
- boolean lambda$getHiveMembers$12(BlockPos,BeeDebugRenderer$BeeInfo)
- List lambda$getGhostHives$13(BlockPos)
- Set lambda$null$6(BlockPos)
- Set lambda$null$9(BlockPos)
+ void addBeeToSetInMap(Map,BeeDebugRenderer$BeeInfo,BlockPos)
+ void lambda$createHiveBlacklistMap$7(Map,BeeDebugRenderer$BeeInfo)
- void lambda$createHiveBlacklistMap$8(Map,BeeDebugRenderer$BeeInfo)
+ void lambda$null$6(Map,BeeDebugRenderer$BeeInfo,BlockPos)
- void lambda$null$7(Map,BeeDebugRenderer$BeeInfo,BlockPos)
- void lambda$renderFlowerInfos$10(Map,BeeDebugRenderer$BeeInfo)
- void lambda$renderFlowerInfos$11(Map$Entry)
+ void lambda$renderFlowerInfos$8(Map,BeeDebugRenderer$BeeInfo)
+ void lambda$renderFlowerInfos$9(Map$Entry)
+ void lambda$updateLastLookedAtUuid$11(Entity)
- void lambda$updateLastLookedAtUuid$14(Entity)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ItemRenderer
</summary>

```diff
- VertexConsumer getCompassFoilBuffer(MultiBufferSource,RenderType,PoseStack$Pose)
- VertexConsumer getCompassFoilBufferDirect(MultiBufferSource,RenderType,PoseStack$Pose)
```

</details>
<details>
<summary>
net.minecraft.client.resources.sounds.AbstractSoundInstance
</summary>

```diff
- String toString()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundLoginPacket
</summary>

```diff
- GameType getPreviousGameType()
- void <init>(int,GameType,GameType,long,boolean,Set,RegistryAccess$RegistryHolder,ResourceKey,ResourceKey,int,int,boolean,boolean,boolean,boolean)
+ void <init>(int,GameType,long,boolean,Set,RegistryAccess$RegistryHolder,ResourceKey,ResourceKey,int,int,boolean,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundRespawnPacket
</summary>

```diff
- GameType getPreviousPlayerGameType()
+ void <init>(ResourceKey,ResourceKey,long,GameType,boolean,boolean,boolean)
- void <init>(ResourceKey,ResourceKey,long,GameType,GameType,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.level.FeatureSimulator
</summary>

```diff
- boolean destroyBlock(BlockPos,boolean,Entity,int)
+ boolean destroyBlock(BlockPos,boolean,Entity)
- boolean setBlock(BlockPos,BlockState,int,int)
+ boolean setBlock(BlockPos,BlockState,int)
```

</details>
<details>
<summary>
net.minecraft.server.level.WorldGenRegion
</summary>

```diff
- boolean destroyBlock(BlockPos,boolean,Entity,int)
+ boolean destroyBlock(BlockPos,boolean,Entity)
- boolean setBlock(BlockPos,BlockState,int,int)
+ boolean setBlock(BlockPos,BlockState,int)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.DataFixers
</summary>

```diff
+ String lambda$addFixers$10(String)
+ String lambda$addFixers$11(String)
+ String lambda$addFixers$12(String)
+ String lambda$addFixers$13(String)
+ String lambda$addFixers$14(String)
+ String lambda$addFixers$15(String)
+ String lambda$addFixers$16(String)
+ String lambda$addFixers$17(String)
+ String lambda$addFixers$18(String)
+ String lambda$addFixers$19(String)
+ String lambda$addFixers$20(String)
+ String lambda$addFixers$21(String)
+ String lambda$addFixers$22(String)
+ String lambda$addFixers$23(String)
+ String lambda$addFixers$24(String)
+ String lambda$addFixers$25(String)
+ String lambda$addFixers$26(String)
+ String lambda$addFixers$27(String)
+ String lambda$addFixers$28(String)
+ String lambda$addFixers$29(String)
+ String lambda$addFixers$3(String)
+ String lambda$addFixers$30(String)
+ String lambda$addFixers$31(String)
+ String lambda$addFixers$32(String)
+ String lambda$addFixers$4(String)
+ String lambda$addFixers$5(String)
+ String lambda$addFixers$6(String)
+ String lambda$addFixers$7(String)
+ String lambda$addFixers$8(String)
+ String lambda$addFixers$9(String)
- String lambda$createRenamer$3(Map,String)
- String lambda$createRenamer$4(String,String,String)
- UnaryOperator createRenamer(Map)
- UnaryOperator createRenamer(String,String)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
</summary>

```diff
- boolean isZeroList(OptionalDynamic,int)
- Boolean lambda$isZeroList$3(int,List)
- boolean lambda$null$2(Float)
+ Dynamic lambda$null$1(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Typed lambda$makeRule$1(Typed)
+ Typed lambda$makeRule$3(Typed)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.WorldGenSettingsFix
</summary>

```diff
- Dynamic lambda$fix$4(Dynamic)
+ Dynamic lambda$fixFlatStructures$10(OptionalDynamic,Map$Entry)
+ Dynamic lambda$fixFlatStructures$11(DynamicOps,Map$Entry)
- Dynamic lambda$fixFlatStructures$11(OptionalDynamic,Map$Entry)
- Dynamic lambda$fixFlatStructures$12(DynamicOps,Map$Entry)
+ Optional lambda$fix$4(Dynamic)
- Optional lambda$fix$5(Dynamic)
+ void lambda$fix$5(ImmutableMap$Builder,DynamicOps,String)
- void lambda$fix$6(ImmutableMap$Builder,DynamicOps,String)
- void lambda$fixFlatStructures$10(MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Map)
+ void lambda$fixFlatStructures$9(MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Map)
+ void lambda$null$6(Dynamic,MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Dynamic,Dynamic)
- void lambda$null$7(Dynamic,MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Dynamic,Dynamic)
+ void lambda$null$7(Dynamic,MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Map)
- void lambda$null$8(Dynamic,MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Map)
+ void lambda$null$8(MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Dynamic,Dynamic)
- void lambda$null$9(MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Dynamic,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- void removeAfterChangingDimensions()
```

</details>
<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
- void removeAfterChangingDimensions()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
</summary>

```diff
+ int lambda$canUse$0(Player,Player)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zoglin
</summary>

```diff
+ float getMovementSpeed()
+ void maybePlayActivitySound()
+ void playActivitySound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.hoglin.Hoglin
</summary>

```diff
+ void playAmbientSound()
+ void playAngrySound()
+ void playConvertedSound()
+ void playRetreatSound()
- void playSound(SoundEvent)
```

</details>
<details>
<summary>
net.minecraft.world.level.LevelWriter
</summary>

```diff
- boolean destroyBlock(BlockPos,boolean,Entity)
- boolean setBlock(BlockPos,BlockState,int)
```

</details>
</details>
<hr/>