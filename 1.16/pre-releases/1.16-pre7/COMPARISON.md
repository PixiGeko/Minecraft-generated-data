## Comparison with [1.16-pre6](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16-pre6)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.16-pre6</th><th>1.16-pre7</th></tr><tr><td>World version</td><td><pre>2562</pre></td><td><pre>2563</pre></td></tr><tr><td>Protocol version</td><td><pre>730</pre></td><td><pre>732</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.16-pre6</th><th>1.16-pre7</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetEquippedItemPacket
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.entity.monster.ZombifiedPiglin -1M
```
```
XXX.entity.player.Player +1M
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.ZombifiedPiglin
</summary>

```diff
+ boolean isAlwaysExperienceDropper()
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- void setRemainingFireTicks(int)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.platform.Window +1M
```
```
XXX.minecraft.client.Minecraft +1M
```
```
XXX.minecraft.client.MouseHandler +1M
```
```
XXX.client.multiplayer.ClientPacketListener +11M -9M
```
```
XXX.protocol.game.ClientGamePacketListener +1P -1P
```
```
XXX.protocol.game.ClientboundLevelChunkPacket +2M -1M | +1P
```
```
XXX.server.level.ChunkHolder -1P
```
```
XXX.world.entity.LivingEntity +14M -4M
```
```
XXX.world.level.CollisionSpliterator +2M
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.Window
</summary>

```diff
- void onEnter(long,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
- void cursorEntered()
```

</details>
<details>
<summary>
net.minecraft.client.MouseHandler
</summary>

```diff
- void cursorEntered()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
- void handleSetEquipment(ClientboundSetEquipmentPacket)
+ void handleSetEquippedItem(ClientboundSetEquippedItemPacket)
+ void lambda$downloadCallback$5()
+ Void lambda$downloadCallback$6(Throwable)
- void lambda$downloadCallback$7()
- Void lambda$downloadCallback$8(Throwable)
+ void lambda$handleAddOrRemoveRecipes$1(ClientRecipeBook,Recipe)
+ void lambda$handleAddOrRemoveRecipes$2(ClientRecipeBook,RecipeCollection)
- void lambda$handleAddOrRemoveRecipes$3(ClientRecipeBook,Recipe)
- void lambda$handleAddOrRemoveRecipes$4(ClientRecipeBook,RecipeCollection)
+ void lambda$handleGameEvent$0()
- void lambda$handleGameEvent$2()
- void lambda$handleLevelChunk$0(LevelChunk,BlockPos)
+ void lambda$handlePlaceRecipe$7(AbstractContainerMenu,Recipe)
- void lambda$handlePlaceRecipe$9(AbstractContainerMenu,Recipe)
+ void lambda$handleResourcePack$4(String,String)
- void lambda$handleResourcePack$6(String,String)
- void lambda$handleSetEquipment$1(Entity,Pair)
+ void lambda$null$3(String,String,boolean)
- void lambda$null$5(String,String,boolean)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
</summary>

```diff
- boolean forgetOldData()
- void <init>(LevelChunk,int,boolean)
+ void <init>(LevelChunk,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ Boolean lambda$checkBedExists$7(BlockPos)
- Boolean lambda$checkBedExists$8(BlockPos)
- ItemStack getLastArmorItem(EquipmentSlot)
- ItemStack getLastHandItem(EquipmentSlot)
- Map collectEquipmentChanges()
+ Vec3 lambda$null$8(BlockPos)
- Vec3 lambda$null$9(BlockPos)
- void detectEquipmentUpdates()
- void handleEquipmentChanges(Map)
- void handleHandSwap(Map)
- void lambda$handleEquipmentChanges$6(List,EquipmentSlot,ItemStack)
- void lambda$stopSleeping$10(BlockPos)
+ void lambda$stopSleeping$9(BlockPos)
+ void lambda$updateFallFlying$6(LivingEntity)
- void lambda$updateFallFlying$7(LivingEntity)
- void setLastArmorItem(EquipmentSlot,ItemStack)
- void setLastHandItem(EquipmentSlot,ItemStack)
- void swapHandItems()
```

</details>
<details>
<summary>
net.minecraft.world.level.CollisionSpliterator
</summary>

```diff
- boolean isCloseToBorder(VoxelShape,AABB)
- boolean isOutsideBorder(VoxelShape,AABB)
```

</details>
</details>
<hr/>