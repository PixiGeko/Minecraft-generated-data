## Comparison with [1.21.5-pre2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.5-pre2)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21.5-pre2</th><th>1.21.5-pre3</th></tr><tr><td>World version</td><td><pre>4321</pre></td><td><pre>4322</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742064</pre></td><td><pre>1073742065</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
net.minecraft.SharedConstants +1P
```
```
XXX.selector.options.EntitySelectorOptions +1M -1M
```
```
XXX.gametest.framework.GameTestHelper$1 +1M -2M
```
```
XXX.server.level.ServerPlayer +1M -2M
```
```
XXX.entity.player.Player +3M | +1P -2P
```
```
XXX.world.inventory.CraftingMenu -1M
```
```
XXX.world.item.MapItem +4M -4M
```
```
XXX.world.level.Level -2P
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
</summary>

```diff
+ boolean lambda$bootStrap$34(boolean,GameType,Entity)
- boolean lambda$bootStrap$34(GameType,boolean,Entity)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper$1
</summary>

```diff
+ boolean isCreative()
+ boolean isSpectator()
- GameType gameMode()
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
+ boolean isCreative()
+ boolean isSpectator()
- GameType gameMode()
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- boolean isCreative()
- boolean isSpectator()
- String debugInfo()
```

</details>
<details>
<summary>
net.minecraft.world.inventory.CraftingMenu
</summary>

```diff
+ void lambda$quickMoveStack$2(ItemStack,Player,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.item.MapItem
</summary>

```diff
+ ItemStack create(Level,int,int,byte,boolean,boolean)
- ItemStack create(ServerLevel,int,int,byte,boolean,boolean)
+ MapId createNewSavedData(Level,int,int,int,boolean,boolean,ResourceKey)
- MapId createNewSavedData(ServerLevel,int,int,int,boolean,boolean,ResourceKey)
- void lockMap(ItemStack,ServerLevel)
+ void lockMap(Level,ItemStack)
+ void scaleMap(ItemStack,Level)
- void scaleMap(ItemStack,ServerLevel)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.client.player.AbstractClientPlayer +1M -2M
```
```
XXX.selector.options.EntitySelectorOptions +1M -1M
```
```
XXX.gametest.framework.GameTestHelper$1 +1M -2M
```
```
XXX.server.level.ServerPlayer +1M -2M
```
```
XXX.entity.player.Player +3M | +1P -2P
```
```
XXX.world.inventory.CraftingMenu -1M
```
```
XXX.world.item.MapItem +4M -4M
```
```
XXX.world.level.Level -2P
```

</details>
<details>
<summary>
net.minecraft.client.player.AbstractClientPlayer
</summary>

```diff
+ boolean isCreative()
+ boolean isSpectator()
- GameType gameMode()
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
</summary>

```diff
+ boolean lambda$bootStrap$34(boolean,GameType,Entity)
- boolean lambda$bootStrap$34(GameType,boolean,Entity)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper$1
</summary>

```diff
+ boolean isCreative()
+ boolean isSpectator()
- GameType gameMode()
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
+ boolean isCreative()
+ boolean isSpectator()
- GameType gameMode()
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- boolean isCreative()
- boolean isSpectator()
- String debugInfo()
```

</details>
<details>
<summary>
net.minecraft.world.inventory.CraftingMenu
</summary>

```diff
+ void lambda$quickMoveStack$2(ItemStack,Player,Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.item.MapItem
</summary>

```diff
+ ItemStack create(Level,int,int,byte,boolean,boolean)
- ItemStack create(ServerLevel,int,int,byte,boolean,boolean)
+ MapId createNewSavedData(Level,int,int,int,boolean,boolean,ResourceKey)
- MapId createNewSavedData(ServerLevel,int,int,int,boolean,boolean,ResourceKey)
- void lockMap(ItemStack,ServerLevel)
+ void lockMap(Level,ItemStack)
+ void scaleMap(ItemStack,Level)
- void scaleMap(ItemStack,ServerLevel)
```

</details>
</details>
<hr/>