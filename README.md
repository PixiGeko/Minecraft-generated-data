<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.16-pre6 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.16-pre6</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2020-06-15T16:57:57+00:00</td></tr>
<tr><th>SHA1</th><td>4c1ed3dcbbf22fe0a17eb05b3f1f1445f25508d6</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/4c1ed3dcbbf22fe0a17eb05b3f1f1445f25508d6/1.16-pre6.json">https://piston-meta.mojang.com/v1/packages/4c1ed3dcbbf22fe0a17eb05b3f1f1445f25508d6/1.16-pre6.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/f3c4aa96e12951cd2781b3e1c0e8ab82bf719cf2/1.16.json">https://piston-meta.mojang.com/v1/packages/f3c4aa96e12951cd2781b3e1c0e8ab82bf719cf2/1.16.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/8984939f42371a7e614fa48669e308c4cc9ba228/server.jar">https://piston-data.mojang.com/v1/objects/8984939f42371a7e614fa48669e308c4cc9ba228/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/94bb748272f25871dc31c3976f9f9583f857e030/server.txt">https://piston-data.mojang.com/v1/objects/94bb748272f25871dc31c3976f9f9583f857e030/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/44aa1f291392b002cb7096c71913306f57e318e0/client.jar">https://piston-data.mojang.com/v1/objects/44aa1f291392b002cb7096c71913306f57e318e0/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/55d69c6051182d71191f30779e97f3a3b88e2361/client.txt">https://piston-data.mojang.com/v1/objects/55d69c6051182d71191f30779e97f3a3b88e2361/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16-pre5">1.16-pre5</a>

# Mappings

### Client




<details><summary>Classes</summary>

```diff
- com.mojang.blaze3d.vertex.BreakingTextureGenerator
+ com.mojang.blaze3d.vertex.BufferBuilder
- com.mojang.blaze3d.vertex.BufferBuilder$1
+ com.mojang.blaze3d.vertex.BufferBuilder$DrawState
- com.mojang.blaze3d.vertex.BufferBuilder$State
+ com.mojang.blaze3d.vertex.BufferUploader
- com.mojang.blaze3d.vertex.BufferVertexConsumer
- com.mojang.blaze3d.vertex.DefaultedVertexConsumer
+ com.mojang.blaze3d.vertex.DefaultVertexFormat
+ com.mojang.blaze3d.vertex.PoseStack
- com.mojang.blaze3d.vertex.PoseStack$1
+ com.mojang.blaze3d.vertex.PoseStack$Pose
+ net.minecraft.advancements.critereon.PlayerInteractTrigger
```

</details>


<details><summary>com.mojang.blaze3d.platform.InputConstants$Key</summary>

```diff
+ OptionalInt getNumericKeyValue()
```

</details>


<details><summary>net.minecraft.advancements.critereon.EntityPredicate</summary>

```diff
+ void <init>(EntityTypePredicate,DistancePredicate,LocationPredicate,MobEffectsPredicate,NbtPredicate,EntityFlagsPredicate,EntityEquipmentPredicate,PlayerPredicate,FishingHookPredicate,String,ResourceLocation)
```

</details>


<details><summary>net.minecraft.client.gui.components.CommandSuggestions</summary>

```diff
+ List sortSuggestions(Suggestions)
```

</details>


<details><summary>net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList</summary>

```diff
+ void <init>(CommandSuggestions,int,int,int,List,boolean,CommandSuggestions$1)
+ void <init>(CommandSuggestions,int,int,int,List,boolean)
- void <init>(CommandSuggestions,int,int,int,Suggestions,boolean,CommandSuggestions$1)
- void <init>(CommandSuggestions,int,int,int,Suggestions,boolean)
```

</details>


<details><summary>net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen</summary>

```diff
+ GameType getDefaultSelected()
```

</details>


<details><summary>net.minecraft.client.gui.screens.inventory.AbstractContainerScreen</summary>

```diff
+ void checkHotbarMouseClicked(int)
```

</details>


<details><summary>net.minecraft.client.renderer.debug.BeeDebugRenderer</summary>

```diff
- boolean lambda$getHiveMembers$10(BlockPos,BeeDebugRenderer$BeeInfo)
+ boolean lambda$getHiveMembers$12(BlockPos,BeeDebugRenderer$BeeInfo)
+ List lambda$getGhostHives$13(BlockPos)
+ Set lambda$null$6(BlockPos)
+ Set lambda$null$9(BlockPos)
- void addBeeToSetInMap(Map,BeeDebugRenderer$BeeInfo,BlockPos)
- void lambda$createHiveBlacklistMap$7(Map,BeeDebugRenderer$BeeInfo)
+ void lambda$createHiveBlacklistMap$8(Map,BeeDebugRenderer$BeeInfo)
- void lambda$null$6(Map,BeeDebugRenderer$BeeInfo,BlockPos)
+ void lambda$null$7(Map,BeeDebugRenderer$BeeInfo,BlockPos)
+ void lambda$renderFlowerInfos$10(Map,BeeDebugRenderer$BeeInfo)
+ void lambda$renderFlowerInfos$11(Map$Entry)
- void lambda$renderFlowerInfos$8(Map,BeeDebugRenderer$BeeInfo)
- void lambda$renderFlowerInfos$9(Map$Entry)
- void lambda$updateLastLookedAtUuid$11(Entity)
+ void lambda$updateLastLookedAtUuid$14(Entity)
```

</details>


<details><summary>net.minecraft.client.renderer.entity.ItemRenderer</summary>

```diff
+ VertexConsumer getCompassFoilBuffer(MultiBufferSource,RenderType,PoseStack$Pose)
+ VertexConsumer getCompassFoilBufferDirect(MultiBufferSource,RenderType,PoseStack$Pose)
```

</details>


<details><summary>net.minecraft.client.resources.sounds.AbstractSoundInstance</summary>

```diff
+ String toString()
```

</details>


<details><summary>net.minecraft.network.protocol.game.ClientboundLoginPacket</summary>

```diff
+ GameType getPreviousGameType()
+ void <init>(int,GameType,GameType,long,boolean,Set,RegistryAccess$RegistryHolder,ResourceKey,ResourceKey,int,int,boolean,boolean,boolean,boolean)
- void <init>(int,GameType,long,boolean,Set,RegistryAccess$RegistryHolder,ResourceKey,ResourceKey,int,int,boolean,boolean,boolean,boolean)
```

</details>


<details><summary>net.minecraft.network.protocol.game.ClientboundRespawnPacket</summary>

```diff
+ GameType getPreviousPlayerGameType()
- void <init>(ResourceKey,ResourceKey,long,GameType,boolean,boolean,boolean)
+ void <init>(ResourceKey,ResourceKey,long,GameType,GameType,boolean,boolean,boolean)
```

</details>


<details><summary>net.minecraft.server.level.FeatureSimulator</summary>

```diff
+ boolean destroyBlock(BlockPos,boolean,Entity,int)
- boolean destroyBlock(BlockPos,boolean,Entity)
+ boolean setBlock(BlockPos,BlockState,int,int)
- boolean setBlock(BlockPos,BlockState,int)
```

</details>


<details><summary>net.minecraft.server.level.WorldGenRegion</summary>

```diff
+ boolean destroyBlock(BlockPos,boolean,Entity,int)
- boolean destroyBlock(BlockPos,boolean,Entity)
+ boolean setBlock(BlockPos,BlockState,int,int)
- boolean setBlock(BlockPos,BlockState,int)
```

</details>


<details><summary>net.minecraft.util.datafix.DataFixers</summary>

```diff
- String lambda$addFixers$10(String)
- String lambda$addFixers$11(String)
- String lambda$addFixers$12(String)
- String lambda$addFixers$13(String)
- String lambda$addFixers$14(String)
- String lambda$addFixers$15(String)
- String lambda$addFixers$16(String)
- String lambda$addFixers$17(String)
- String lambda$addFixers$18(String)
- String lambda$addFixers$19(String)
- String lambda$addFixers$20(String)
- String lambda$addFixers$21(String)
- String lambda$addFixers$22(String)
- String lambda$addFixers$23(String)
- String lambda$addFixers$24(String)
- String lambda$addFixers$25(String)
- String lambda$addFixers$26(String)
- String lambda$addFixers$27(String)
- String lambda$addFixers$28(String)
- String lambda$addFixers$29(String)
- String lambda$addFixers$3(String)
- String lambda$addFixers$30(String)
- String lambda$addFixers$31(String)
- String lambda$addFixers$32(String)
- String lambda$addFixers$4(String)
- String lambda$addFixers$5(String)
- String lambda$addFixers$6(String)
- String lambda$addFixers$7(String)
- String lambda$addFixers$8(String)
- String lambda$addFixers$9(String)
+ String lambda$createRenamer$3(Map,String)
+ String lambda$createRenamer$4(String,String,String)
+ UnaryOperator createRenamer(Map)
+ UnaryOperator createRenamer(String,String)
```

</details>


<details><summary>net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix</summary>

```diff
+ boolean isZeroList(OptionalDynamic,int)
+ Boolean lambda$isZeroList$3(int,List)
+ boolean lambda$null$2(Float)
- Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Typed lambda$makeRule$1(Typed)
- Typed lambda$makeRule$3(Typed)
+ void <clinit>()
```

</details>


<details><summary>net.minecraft.util.datafix.fixes.WorldGenSettingsFix</summary>

```diff
+ Dynamic lambda$fix$4(Dynamic)
- Dynamic lambda$fixFlatStructures$10(OptionalDynamic,Map$Entry)
- Dynamic lambda$fixFlatStructures$11(DynamicOps,Map$Entry)
+ Dynamic lambda$fixFlatStructures$11(OptionalDynamic,Map$Entry)
+ Dynamic lambda$fixFlatStructures$12(DynamicOps,Map$Entry)
- Optional lambda$fix$4(Dynamic)
+ Optional lambda$fix$5(Dynamic)
- void lambda$fix$5(ImmutableMap$Builder,DynamicOps,String)
+ void lambda$fix$6(ImmutableMap$Builder,DynamicOps,String)
+ void lambda$fixFlatStructures$10(MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Map)
- void lambda$fixFlatStructures$9(MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Map)
- void lambda$null$6(Dynamic,MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Dynamic,Dynamic)
+ void lambda$null$7(Dynamic,MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Dynamic,Dynamic)
- void lambda$null$7(Dynamic,MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Map)
+ void lambda$null$8(Dynamic,MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Map)
- void lambda$null$8(MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Dynamic,Dynamic)
+ void lambda$null$9(MutableBoolean,MutableInt,MutableInt,MutableInt,Map,Dynamic,Dynamic)
```

</details>


<details><summary>net.minecraft.world.entity.Entity</summary>

```diff
+ void removeAfterChangingDimensions()
```

</details>


<details><summary>net.minecraft.world.entity.Mob</summary>

```diff
+ void removeAfterChangingDimensions()
```

</details>


<details><summary>net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal</summary>

```diff
- int lambda$canUse$0(Player,Player)
```

</details>


<details><summary>net.minecraft.world.entity.monster.Zoglin</summary>

```diff
- float getMovementSpeed()
- void maybePlayActivitySound()
- void playActivitySound()
```

</details>


<details><summary>net.minecraft.world.entity.monster.hoglin.Hoglin</summary>

```diff
- void playAmbientSound()
- void playAngrySound()
- void playConvertedSound()
- void playRetreatSound()
+ void playSound(SoundEvent)
```

</details>


<details><summary>net.minecraft.world.level.LevelWriter</summary>

```diff
+ boolean destroyBlock(BlockPos,boolean,Entity)
+ boolean setBlock(BlockPos,BlockState,int)
```

</details>


### Server




<details><summary>Classes</summary>

```diff
+ net.minecraft.advancements.critereon.PlayerInteractTrigger$TriggerInstance
```

</details>


<details><summary>net.minecraft.server.level.ServerPlayerGameMode</summary>

```diff
+ GameType getPreviousGameModeForPlayer()
+ void setGameModeForPlayer(GameType,GameType)
```

</details>


<details><summary>net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal</summary>

```diff
+ void <clinit>()
```

</details>


<details><summary>net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor</summary>

```diff
+ boolean isValidRepellent(ServerLevel,BlockPos)
```

</details>


<details><summary>net.minecraft.world.entity.monster.Strider</summary>

```diff
+ boolean isBeingTempted()
+ boolean isPanicking()
```

</details>


<details><summary>net.minecraft.world.entity.monster.ZombifiedPiglin</summary>

```diff
+ void maybePlayFirstAngerSound()
```

</details>


<details><summary>net.minecraft.world.entity.monster.hoglin.HoglinAi</summary>

```diff
- boolean isIdle(Hoglin)
+ boolean isNearRepellent(Hoglin)
+ Optional getSoundForCurrentActivity(Hoglin)
+ SoundEvent getSoundForActivity(Hoglin,Activity)
+ SoundEvent lambda$getSoundForCurrentActivity$2(Hoglin,Activity)
- void lambda$playActivitySound$2(Hoglin,Activity)
- void maybePlayActivitySound(Hoglin)
- void playActivitySound(Hoglin)
```

</details>


<details><summary>net.minecraft.world.entity.monster.piglin.Piglin</summary>

```diff
- void playAdmiringSound()
- void playAmbientSound()
- void playAngrySound()
- void playCelebrateSound()
- void playConvertedSound()
- void playJealousSound()
- void playRetreatSound()
+ void playSound(SoundEvent)
```

</details>


<details><summary>net.minecraft.world.entity.monster.piglin.PiglinAi</summary>

```diff
+ CopyMemoryWithExpiry babyAvoidNemesis()
+ Optional getSoundForCurrentActivity(Piglin)
+ SoundEvent getSoundForActivity(Piglin,Activity)
+ SoundEvent lambda$getSoundForCurrentActivity$6(Piglin,Activity)
+ void holdInOffhand(Piglin,ItemStack)
- void lambda$playActivitySound$6(Piglin,Activity)
- void maybePlayActivitySound(Piglin)
- void playActivitySound(Piglin)
```

</details>


<details><summary>net.minecraft.world.entity.projectile.ThrownEnderpearl</summary>

```diff
- void onHitBlock(BlockHitResult)
```

</details>


<details><summary>net.minecraft.world.level.Level</summary>

```diff
+ boolean destroyBlock(BlockPos,boolean,Entity,int)
- boolean destroyBlock(BlockPos,boolean,Entity)
+ boolean setBlock(BlockPos,BlockState,int,int)
```

</details>


<details><summary>net.minecraft.world.level.block.Block</summary>

```diff
+ void updateOrDestroy(BlockState,BlockState,LevelAccessor,BlockPos,int,int)
```

</details>


<details><summary>net.minecraft.world.level.block.RedStoneWireBlock</summary>

```diff
+ void updateIndirectNeighbourShapes(BlockState,LevelAccessor,BlockPos,int,int)
- void updateIndirectNeighbourShapes(BlockState,LevelAccessor,BlockPos,int)
```

</details>


<details><summary>net.minecraft.world.level.block.RedstoneLampBlock</summary>

```diff
- void onPlace(BlockState,Level,BlockPos,BlockState,boolean)
```

</details>


<details><summary>net.minecraft.world.level.block.state.BlockBehaviour</summary>

```diff
+ void updateIndirectNeighbourShapes(BlockState,LevelAccessor,BlockPos,int,int)
- void updateIndirectNeighbourShapes(BlockState,LevelAccessor,BlockPos,int)
```

</details>


<details><summary>net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase</summary>

```diff
+ void updateIndirectNeighbourShapes(LevelAccessor,BlockPos,int,int)
+ void updateNeighbourShapes(LevelAccessor,BlockPos,int,int)
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ gui.recipebook.search_hint
```

</details>
