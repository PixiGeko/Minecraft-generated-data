<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.16-pre7 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.16-pre7</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2020-06-16T15:31:35+00:00</td></tr>
<tr><th>SHA1</th><td>ec4dc4530869505923e1ebf6fc80ea08eda831e1</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/ec4dc4530869505923e1ebf6fc80ea08eda831e1/1.16-pre7.json">https://piston-meta.mojang.com/v1/packages/ec4dc4530869505923e1ebf6fc80ea08eda831e1/1.16-pre7.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/f3c4aa96e12951cd2781b3e1c0e8ab82bf719cf2/1.16.json">https://piston-meta.mojang.com/v1/packages/f3c4aa96e12951cd2781b3e1c0e8ab82bf719cf2/1.16.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/577f7287642309a2a32e80be395329118dfddb3f/server.jar">https://piston-data.mojang.com/v1/objects/577f7287642309a2a32e80be395329118dfddb3f/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/6da8e27122ba2731f6b9f935a91ffa47a8af2a14/server.txt">https://piston-data.mojang.com/v1/objects/6da8e27122ba2731f6b9f935a91ffa47a8af2a14/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/62473fe623906a01b2f7cf4f7c1396ab23697e5f/client.jar">https://piston-data.mojang.com/v1/objects/62473fe623906a01b2f7cf4f7c1396ab23697e5f/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/346d0cee6a2539c9edfb8dbc817f157cfb8627e5/client.txt">https://piston-data.mojang.com/v1/objects/346d0cee6a2539c9edfb8dbc817f157cfb8627e5/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16-pre6">1.16-pre6</a>

# Mappings

### Client




<details><summary>com.mojang.blaze3d.platform.Window</summary>

```diff
+ void onEnter(long,boolean)
```

</details>


<details><summary>net.minecraft.client.Minecraft</summary>

```diff
+ void cursorEntered()
```

</details>


<details><summary>net.minecraft.client.MouseHandler</summary>

```diff
+ void cursorEntered()
```

</details>


<details><summary>net.minecraft.client.multiplayer.ClientPacketListener</summary>

```diff
+ void handleSetEquipment(ClientboundSetEquipmentPacket)
- void handleSetEquippedItem(ClientboundSetEquippedItemPacket)
- void lambda$downloadCallback$5()
- Void lambda$downloadCallback$6(Throwable)
+ void lambda$downloadCallback$7()
+ Void lambda$downloadCallback$8(Throwable)
- void lambda$handleAddOrRemoveRecipes$1(ClientRecipeBook,Recipe)
- void lambda$handleAddOrRemoveRecipes$2(ClientRecipeBook,RecipeCollection)
+ void lambda$handleAddOrRemoveRecipes$3(ClientRecipeBook,Recipe)
+ void lambda$handleAddOrRemoveRecipes$4(ClientRecipeBook,RecipeCollection)
- void lambda$handleGameEvent$0()
+ void lambda$handleGameEvent$2()
+ void lambda$handleLevelChunk$0(LevelChunk,BlockPos)
- void lambda$handlePlaceRecipe$7(AbstractContainerMenu,Recipe)
+ void lambda$handlePlaceRecipe$9(AbstractContainerMenu,Recipe)
- void lambda$handleResourcePack$4(String,String)
+ void lambda$handleResourcePack$6(String,String)
+ void lambda$handleSetEquipment$1(Entity,Pair)
- void lambda$null$3(String,String,boolean)
+ void lambda$null$5(String,String,boolean)
```

</details>


<details><summary>net.minecraft.network.protocol.game.ClientboundLevelChunkPacket</summary>

```diff
+ boolean forgetOldData()
+ void <init>(LevelChunk,int,boolean)
- void <init>(LevelChunk,int)
```

</details>


<details><summary>net.minecraft.world.entity.LivingEntity</summary>

```diff
- Boolean lambda$checkBedExists$7(BlockPos)
+ Boolean lambda$checkBedExists$8(BlockPos)
+ ItemStack getLastArmorItem(EquipmentSlot)
+ ItemStack getLastHandItem(EquipmentSlot)
+ Map collectEquipmentChanges()
- Vec3 lambda$null$8(BlockPos)
+ Vec3 lambda$null$9(BlockPos)
+ void detectEquipmentUpdates()
+ void handleEquipmentChanges(Map)
+ void handleHandSwap(Map)
+ void lambda$handleEquipmentChanges$6(List,EquipmentSlot,ItemStack)
+ void lambda$stopSleeping$10(BlockPos)
- void lambda$stopSleeping$9(BlockPos)
- void lambda$updateFallFlying$6(LivingEntity)
+ void lambda$updateFallFlying$7(LivingEntity)
+ void setLastArmorItem(EquipmentSlot,ItemStack)
+ void setLastHandItem(EquipmentSlot,ItemStack)
+ void swapHandItems()
```

</details>


<details><summary>net.minecraft.world.level.CollisionSpliterator</summary>

```diff
+ boolean isCloseToBorder(VoxelShape,AABB)
+ boolean isOutsideBorder(VoxelShape,AABB)
```

</details>


### Server




<details><summary>Classes</summary>

```diff
+ net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
- net.minecraft.network.protocol.game.ClientboundSetEquippedItemPacket
```

</details>


<details><summary>net.minecraft.world.entity.monster.ZombifiedPiglin</summary>

```diff
- boolean isAlwaysExperienceDropper()
```

</details>


<details><summary>net.minecraft.world.entity.player.Player</summary>

```diff
+ void setRemainingFireTicks(int)
```

</details>
