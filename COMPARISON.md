## Comparison with [25w09b](https://github.com/PixiGeko/Minecraft-generated-data/tree/25w09b)

> [!TIP]
> - [Version data](#version-data)
> - [Commands](#commands)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">25w09b</th><th>25w10a</th></tr><tr><td>DataPack version</td><td><pre>69</pre></td><td><pre>70</pre></td></tr><tr><td>ResourcePack version</td><td><pre>53</pre></td><td><pre>54</pre></td></tr><tr><td>World version</td><td><pre>4318</pre></td><td><pre>4319</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742061</pre></td><td><pre>1073742062</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
gamerule
</summary>

```diff
+ gamerule tntExplodes <value: bool>
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
+ block.minecraft.tnt.disabled: TNT explosions are disabled
+ gamerule.tntExplodes: Allow TNT to be activated and to explode
+ snbt.parser.expected_number_or_boolean: Expected a number or a boolean
+ snbt.parser.expected_string_uuid: Expected a string representing a valid UUID
+ snbt.parser.infinity_not_allowed: Non-finite numbers are not allowed
+ snbt.parser.invalid_codepoint: Invalid Unicode character value: %s
+ snbt.parser.no_such_operation: No such operation: %s
```

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
+ minecraft/tags/item/flowers.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/misc/enchanted_glint_armor.png
+ minecraft/textures/misc/enchanted_glint_armor.png.mcmeta
- minecraft/textures/misc/enchanted_glint_entity.png
- minecraft/textures/misc/enchanted_glint_entity.png.mcmeta
```

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
- XXX.advancements.critereon.DataComponentMatchers
- XXX.minecraft.nbt.SnbtOperations$1
- XXX.minecraft.nbt.SnbtOperations$3
- XXX.minecraft.nbt.SnbtOperations$BuiltinOperation
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.BlockPredicate +3M -1M | +1P
```
```
XXX.advancements.critereon.EntityPredicate +2M -2M | +1P -1P
```
```
XXX.advancements.critereon.ItemPredicate +2M -3M | +1P -2P
```
```
XXX.core.component.DataComponentExactPredicate +1M
```
```
XXX.component.predicates.DataComponentPredicate$Single +1M
```
```
XXX.advancements.packs.VanillaHusbandryAdvancements +6M -5M | +1P
```
```
XXX.server.level.ServerLevel +1M -1M
```
```
XXX.packrat.commands.GreedyPredicateParseRule +1M | +1P
```
```
XXX.world.item.ShearsItem +1M
```
```
XXX.world.level.GameRules +1P
```
```
XXX.gameevent.vibrations.VibrationSystem +1P -1P
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BlockPredicate
</summary>

```diff
- boolean matchesComponents(BlockEntity,DataComponentMatchers)
- DataComponentMatchers components()
- void <init>(Optional,Optional,Optional,DataComponentMatchers)
+ void <init>(Optional,Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityPredicate
</summary>

```diff
- DataComponentMatchers components()
+ Optional components()
- void <init>(Optional,Optional,Optional,EntityPredicate$LocationWrapper,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,DataComponentMatchers)
+ void <init>(Optional,Optional,Optional,EntityPredicate$LocationWrapper,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ItemPredicate
</summary>

```diff
+ DataComponentExactPredicate components()
- DataComponentMatchers components()
+ Map subPredicates()
+ void <init>(Optional,MinMaxBounds$Ints,DataComponentExactPredicate,Map)
- void <init>(Optional,MinMaxBounds$Ints,DataComponentMatchers)
```

</details>
<details>
<summary>
net.minecraft.core.component.DataComponentExactPredicate
</summary>

```diff
- boolean isEmpty()
```

</details>
<details>
<summary>
net.minecraft.core.component.predicates.DataComponentPredicate$Single
</summary>

```diff
- DataComponentPredicate$Single fromEntry(Map$Entry)
```

</details>
<details>
<summary>
net.minecraft.data.advancements.packs.VanillaHusbandryAdvancements
</summary>

```diff
- Advancement$Builder addTamedWolfVariants(Advancement$Builder,HolderLookup)
+ Advancement$Builder addTamedWolfVariants(Advancement$Builder,HolderLookup$Provider)
+ ResourceLocation lambda$addCatVariants$3(Holder$Reference)
- ResourceLocation lambda$static$0(Holder$Reference)
- Stream sortedVariants(HolderLookup)
+ void lambda$addBreedable$1(Advancement$Builder,HolderGetter,EntityType)
- void lambda$addBreedable$3(Advancement$Builder,HolderGetter,EntityType)
+ void lambda$addLeashedFrogVariants$0(Advancement$Builder,HolderGetter,HolderGetter,Holder$Reference)
- void lambda$addLeashedFrogVariants$1(Advancement$Builder,HolderGetter,HolderGetter,Holder$Reference)
- void lambda$addTamedWolfVariants$5(Advancement$Builder,Holder$Reference)
+ void lambda$addTamedWolfVariants$5(HolderLookup$RegistryLookup,Advancement$Builder,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
- boolean areEntitiesActuallyLoadedAndTicking(ChunkPos)
+ boolean areEntitiesActuallyTicking(ChunkPos)
```

</details>
<details>
<summary>
net.minecraft.util.parsing.packrat.commands.GreedyPredicateParseRule
</summary>

```diff
- void <init>(int,int,DelayedException)
```

</details>
<details>
<summary>
net.minecraft.world.item.ShearsItem
</summary>

```diff
- boolean mineBlock(ItemStack,Level,BlockState,BlockPos,LivingEntity)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.advancements.critereon.DataComponentMatchers$Builder
- XXX.minecraft.nbt.SnbtOperations
- XXX.minecraft.nbt.SnbtOperations$2
- XXX.minecraft.nbt.SnbtOperations$BuiltinKey
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.systems.RenderSystem +2M -1M
```
```
XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer +2M -1M
```
```
XXX.blaze3d.vertex.VertexFormat +3M -1M
```
```
XXX.advancements.critereon.BlockPredicate$Builder +1M | +1P
```
```
XXX.advancements.critereon.EntityPredicate$Builder +1M -1M | +1P -1P
```
```
XXX.advancements.critereon.ItemPredicate$Builder +1M -2M | +1P -2P
```
```
XXX.client.renderer.RenderStateShard +1M -2M | +1P
```
```
XXX.renderer.entity.ItemRenderer +1P -1P
```
```
XXX.component.predicates.DataComponentPredicate +2M | +2P
```
```
XXX.component.predicates.DataComponentPredicate$Type +2M | +1P
```
```
XXX.minecraft.nbt.CompoundTag +3M -2M
```
```
XXX.minecraft.nbt.SnbtGrammar +24M -19M | +3P
```
```
XXX.minecraft.tags.ItemTags +1P
```
```
XXX.world.entity.Entity +2P
```
```
XXX.world.entity.Marker -2P
```
```
XXX.item.component.CustomData +2M -5M | -2P
```
```
XXX.level.block.TntBlock +2M -2M
```

</details>
<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem
</summary>

```diff
- GpuBuffer getQuadVertexBuffer()
+ GpuBuffer getQuadVertexBuffer(Supplier)
- String lambda$getQuadVertexBuffer$2()
```

</details>
<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
</summary>

```diff
- String lambda$ensureStorage$1()
+ void lambda$intConsumer$1(ByteBuffer,int)
- void lambda$intConsumer$2(ByteBuffer,int)
```

</details>
<details>
<summary>
com.mojang.blaze3d.vertex.VertexFormat
</summary>

```diff
+ String lambda$uploadImmediateIndexBuffer$2()
- String lambda$uploadImmediateIndexBuffer$3()
- String lambda$uploadImmediateIndexBuffer$4()
- String lambda$uploadImmediateVertexBuffer$2()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BlockPredicate$Builder
</summary>

```diff
- BlockPredicate$Builder components(DataComponentMatchers)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityPredicate$Builder
</summary>

```diff
+ EntityPredicate$Builder components(DataComponentExactPredicate)
- EntityPredicate$Builder components(DataComponentMatchers)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ItemPredicate$Builder
</summary>

```diff
+ ItemPredicate$Builder hasComponents(DataComponentExactPredicate)
- ItemPredicate$Builder withComponents(DataComponentMatchers)
+ ItemPredicate$Builder withSubPredicate(DataComponentPredicate$Type,DataComponentPredicate)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.RenderStateShard
</summary>

```diff
- RenderTarget lambda$static$11()
+ RenderTarget lambda$static$17()
+ void lambda$static$11()
```

</details>
<details>
<summary>
net.minecraft.core.component.predicates.DataComponentPredicate
</summary>

```diff
- List lambda$static$1(Map)
- Map lambda$static$0(List)
```

</details>
<details>
<summary>
net.minecraft.core.component.predicates.DataComponentPredicate$Type
</summary>

```diff
- DataComponentPredicate$Single lambda$new$2(DataComponentPredicate)
- StreamCodec singleStreamCodec()
```

</details>
<details>
<summary>
net.minecraft.nbt.CompoundTag
</summary>

```diff
- void lambda$copy$3(HashMap,String,Tag)
+ void lambda$read$3(String,Tag,String)
- void lambda$read$4(String,Tag,String)
+ void lambda$read$4(String)
- void lambda$read$5(String)
```

</details>
<details>
<summary>
net.minecraft.nbt.SnbtGrammar
</summary>

```diff
- List lambda$createParser$16(Atom,Scope)
+ List lambda$createParser$17(Atom,Scope)
+ List lambda$createParser$19(Atom,Scope)
- List lambda$createParser$20(Atom,Scope)
+ List lambda$createParser$21(Atom,Scope)
- List lambda$createParser$22(Atom,Scope)
- List lambda$createParser$24(Atom,Scope)
+ Map$Entry lambda$createParser$16(Atom,Atom,ParseState)
- Map$Entry lambda$createParser$19(Atom,Atom,ParseState)
- Message lambda$static$2(Object)
- Message lambda$static$3(Object)
- Object convertDouble(DynamicOps,ParseState,String)
- Object convertFloat(DynamicOps,ParseState,String)
+ Object lambda$createParser$14(Atom,Object,Object,DynamicOps,ParseState)
- Object lambda$createParser$17(Atom,Atom,DynamicOps,Object,Object,ParseState)
+ Object lambda$createParser$18(Atom,Object,DynamicOps,Scope)
- Object lambda$createParser$21(Atom,Object,DynamicOps,Scope)
+ Object lambda$createParser$22(Atom,Atom,DynamicOps,Atom,Object,ParseState)
+ Object lambda$createParser$23(Atom,DynamicOps,Atom,Atom,ParseState)
- Object lambda$createParser$25(Atom,Atom,DynamicOps,Atom,Object,ParseState)
- Object lambda$createParser$26(Atom,DynamicOps,Atom,Atom,ParseState)
+ Object lambda$createParser$7(Atom,Atom,Atom,Atom,Atom,DynamicOps,ParseState)
- Object lambda$createParser$9(Atom,Atom,Atom,Atom,Atom,DynamicOps,ParseState)
+ SnbtGrammar$ArrayPrefix lambda$createParser$20(Atom,Scope)
- SnbtGrammar$ArrayPrefix lambda$createParser$23(Atom,Scope)
+ SnbtGrammar$IntegerLiteral lambda$createParser$4(Atom,Atom,Atom,Atom,Atom,Scope)
- SnbtGrammar$IntegerLiteral lambda$createParser$6(Atom,Atom,Atom,Atom,Atom,Scope)
+ SnbtGrammar$IntegerSuffix lambda$createParser$3(Atom,Scope)
- SnbtGrammar$IntegerSuffix lambda$createParser$5(Atom,Scope)
+ SnbtGrammar$Sign lambda$createParser$2(Atom,Scope)
- SnbtGrammar$Sign lambda$createParser$4(Atom,Scope)
+ SnbtGrammar$Signed lambda$createParser$6(Atom,Atom,Scope)
- SnbtGrammar$Signed lambda$createParser$8(Atom,Atom,Scope)
+ SnbtGrammar$TypeSuffix lambda$createParser$5(Atom,Scope)
- SnbtGrammar$TypeSuffix lambda$createParser$7(Atom,Scope)
- String lambda$createParser$10(Atom,Atom,Atom,Atom,Atom,ParseState)
+ String lambda$createParser$10(Atom,Scope)
- String lambda$createParser$14(Atom,Scope)
+ String lambda$createParser$15(Atom,Atom,Scope)
- String lambda$createParser$15(Atom,Scope)
- String lambda$createParser$18(Atom,Atom,Scope)
+ String lambda$createParser$8(Atom,Atom,Atom,Atom,Atom,ParseState)
+ String lambda$createParser$9(Atom,Scope)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.CustomData
</summary>

```diff
+ boolean lambda$itemMatcher$4(DataComponentType,CompoundTag,ItemStack)
- CustomData lambda$update$5(Tag)
+ CustomData lambda$update$6(Tag)
- Optional lambda$parseEntityType$4(ResourceKey,ResourceLocation,HolderLookup$RegistryLookup)
+ Optional lambda$parseEntityType$5(ResourceKey,ResourceLocation,HolderLookup$RegistryLookup)
+ Predicate itemMatcher(DataComponentType,CompoundTag)
+ void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,DataComponentGetter)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TntBlock
</summary>

```diff
- boolean prime(Level,BlockPos,LivingEntity)
- boolean prime(Level,BlockPos)
+ void prime(Level,BlockPos,LivingEntity)
+ void prime(Level,BlockPos)
```

</details>
</details>
<hr/>