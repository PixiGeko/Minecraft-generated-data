<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.19-pre3 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.19-pre3</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2022-05-25T09:56:47+00:00</td></tr>
<tr><th>SHA1</th><td>bf1ebc7ae0dbef7b92307a11eb0cbbfeaa3359e2</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/bf1ebc7ae0dbef7b92307a11eb0cbbfeaa3359e2/1.19-pre3.json">https://piston-meta.mojang.com/v1/packages/bf1ebc7ae0dbef7b92307a11eb0cbbfeaa3359e2/1.19-pre3.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/a9c8b05a8082a65678beda6dfa2b8f21fa627bce/1.19.json">https://piston-meta.mojang.com/v1/packages/a9c8b05a8082a65678beda6dfa2b8f21fa627bce/1.19.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/0702387c3519cc23a5184893275d00c05abf056d/server.jar">https://piston-data.mojang.com/v1/objects/0702387c3519cc23a5184893275d00c05abf056d/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/3151a5cf8b4489876325973837302390c2352902/server.txt">https://piston-data.mojang.com/v1/objects/3151a5cf8b4489876325973837302390c2352902/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/6dbfb4ceafd85dd01297c4d39fd26fe6c8452ba8/client.jar">https://piston-data.mojang.com/v1/objects/6dbfb4ceafd85dd01297c4d39fd26fe6c8452ba8/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/b7b683287ea5a4f0b7d3a33365f6cb9c216a71eb/client.txt">https://piston-data.mojang.com/v1/objects/b7b683287ea5a4f0b7d3a33365f6cb9c216a71eb/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19-pre2">1.19-pre2</a>

# Mappings

### Client




<details><summary>net.minecraft.client.multiplayer.ClientPacketListener</summary>

```diff
+ boolean hasValidSignature(PlayerChatMessage,PlayerInfo)
- boolean hasValidSignature(PlayerChatMessage)
```

</details>


<details><summary>net.minecraft.client.renderer.block.ModelBlockRenderer</summary>

```diff
- boolean isInteriorOccluded(BlockAndTintGetter,BlockState,BlockPos)
```

</details>


<details><summary>net.minecraft.commands.arguments.MessageArgument$Message</summary>

```diff
- CompletableFuture resolveComponent(CommandSourceStack)
+ CompletableFuture resolveDecoratedComponent(CommandSourceStack)
+ Component resolveComponent(CommandSourceStack)
- Component resolvePlainChat(CommandSourceStack)
```

</details>


<details><summary>net.minecraft.network.chat.MessageSignature</summary>

```diff
+ boolean isValid(UUID)
```

</details>


<details><summary>net.minecraft.world.entity.animal.allay.Allay</summary>

```diff
+ Iterable iteratePathfindingStartNodeCandidatePositions()
```

</details>


<details><summary>net.minecraft.world.entity.item.ItemEntity</summary>

```diff
+ Entity getResponsibleEntity()
```

</details>


### Server




<details><summary>net.minecraft.commands.arguments.MessageArgument$ChatMessage</summary>

```diff
+ Component formatted()
- Component plain()
- FilteredText verify(CommandSourceStack,FilteredText)
+ PlayerChatMessage getSignedMessage(FilteredText)
+ String plain()
- void <init>(Component,MessageSignature,boolean)
+ void <init>(String,Component,MessageSignature,boolean)
+ void verify(CommandSourceStack,PlayerChatMessage)
```

</details>


<details><summary>net.minecraft.gametest.framework.GameTestHelper</summary>

```diff
+ List getEntities(EntityType,BlockPos,double)
```

</details>


<details><summary>net.minecraft.world.entity.animal.allay.Allay</summary>

```diff
+ Iterable iteratePathfindingStartNodeCandidatePositions()
```

</details>


<details><summary>net.minecraft.world.entity.item.ItemEntity</summary>

```diff
+ Entity getResponsibleEntity()
```

</details>


# Registries

<details><summary>memory_module_type.txt</summary>

```diff
+ minecraft:unreachable_tongue_targets
```

</details>


# Tags

<details><summary>blocks/frogs_spawnable_on.json</summary>

```diff
- minecraft:moss_carpet
```

</details>


<details><summary>game_events/vibrations.json</summary>

```diff
- minecraft:item_interact_start
```

</details>


<details><summary>game_events/warden_can_listen.json</summary>

```diff
- minecraft:item_interact_start
```

</details>
