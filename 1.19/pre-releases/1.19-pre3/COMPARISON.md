## Comparison with [1.19-pre2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19-pre2)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.19-pre2</th><th>1.19-pre3</th></tr><tr><td>World version</td><td><pre>3099</pre></td><td><pre>3100</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741910</pre></td><td><pre>1073741911</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
memory_module_type
</summary>

```diff
+ minecraft:unreachable_tongue_targets
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:unreachable_tongue_targets
```

</details>
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
XXX.commands.arguments.MessageArgument$ChatMessage +5M -3M | +2P -1P
```
```
XXX.gametest.framework.GameTestHelper +1M
```
```
XXX.animal.allay.Allay +1M | +1P
```
```
XXX.entity.item.ItemEntity +1M
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.MessageArgument$ChatMessage
</summary>

```diff
- Component formatted()
+ Component plain()
+ FilteredText verify(CommandSourceStack,FilteredText)
- PlayerChatMessage getSignedMessage(FilteredText)
- String plain()
+ void <init>(Component,MessageSignature,boolean)
- void <init>(String,Component,MessageSignature,boolean)
- void verify(CommandSourceStack,PlayerChatMessage)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- List getEntities(EntityType,BlockPos,double)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.allay.Allay
</summary>

```diff
- Iterable iteratePathfindingStartNodeCandidatePositions()
```

</details>
<details>
<summary>
net.minecraft.world.entity.item.ItemEntity
</summary>

```diff
- Entity getResponsibleEntity()
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.client.multiplayer.ClientPacketListener +1M -1M
```
```
XXX.renderer.block.ModelBlockRenderer -1M
```
```
XXX.commands.arguments.MessageArgument$Message +2M -2M
```
```
XXX.network.chat.MessageSignature +1M
```
```
XXX.animal.allay.Allay +1M | +1P
```
```
XXX.entity.item.ItemEntity +1M
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
- boolean hasValidSignature(PlayerChatMessage,PlayerInfo)
+ boolean hasValidSignature(PlayerChatMessage)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.ModelBlockRenderer
</summary>

```diff
+ boolean isInteriorOccluded(BlockAndTintGetter,BlockState,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.MessageArgument$Message
</summary>

```diff
+ CompletableFuture resolveComponent(CommandSourceStack)
- CompletableFuture resolveDecoratedComponent(CommandSourceStack)
- Component resolveComponent(CommandSourceStack)
+ Component resolvePlainChat(CommandSourceStack)
```

</details>
<details>
<summary>
net.minecraft.network.chat.MessageSignature
</summary>

```diff
- boolean isValid(UUID)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.allay.Allay
</summary>

```diff
- Iterable iteratePathfindingStartNodeCandidatePositions()
```

</details>
<details>
<summary>
net.minecraft.world.entity.item.ItemEntity
</summary>

```diff
- Entity getResponsibleEntity()
```

</details>
</details>
<hr/>