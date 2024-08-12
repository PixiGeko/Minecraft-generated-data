## Comparison with [24w04a](https://github.com/PixiGeko/Minecraft-generated-data/tree/24w04a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">24w04a</th><th>24w05a</th></tr><tr><td>DataPack version</td><td><code>29</code></td><td><code>30</code></td></tr><tr><td>ResourcePack version</td><td><code>24</code></td><td><code>25</code></td></tr><tr><td>World version</td><td><code>3806</code></td><td><code>3809</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ armor_material.txt
```

</details>



<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:vault
```

</details>
<details>
<summary>
block_entity_type.txt
</summary>

```diff
+ minecraft:vault
```

</details>

<details>
<summary>
block_type.txt
</summary>

```diff
+ minecraft:vault
```

</details>















<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:vault
```

</details>











<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:vault_connection
```

</details>










<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.vault.activate
+ minecraft:block.vault.ambient
+ minecraft:block.vault.break
+ minecraft:block.vault.close_shutter
+ minecraft:block.vault.deactivate
+ minecraft:block.vault.eject_item
+ minecraft:block.vault.fall
+ minecraft:block.vault.hit
+ minecraft:block.vault.insert_item
+ minecraft:block.vault.insert_item_fail
+ minecraft:block.vault.open_shutter
+ minecraft:block.vault.place
+ minecraft:block.vault.step
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
+ universal_tags/armor_material.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:vault
```

</details>




<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:vault
```

</details>



<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:vault
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
+ minecraft:vault
```

</details>

<details>
<summary>
universal_tags/block_type.json
</summary>

```diff
+ minecraft:vault
```

</details>















<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:vault
```

</details>











<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:vault_connection
```

</details>










<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.vault.activate
+ minecraft:block.vault.ambient
+ minecraft:block.vault.break
+ minecraft:block.vault.close_shutter
+ minecraft:block.vault.deactivate
+ minecraft:block.vault.eject_item
+ minecraft:block.vault.fall
+ minecraft:block.vault.hit
+ minecraft:block.vault.insert_item
+ minecraft:block.vault.insert_item_fail
+ minecraft:block.vault.open_shutter
+ minecraft:block.vault.place
+ minecraft:block.vault.step
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ block.minecraft.vault: Vault
+ item.modifiers.body: When equipped:
+ optimizeWorld.stage.finished: Finishing up...
+ optimizeWorld.stage.upgrading: Upgrading all chunks...
+ subtitles.block.vault.activate: Vault ignites
+ subtitles.block.vault.ambient: Vault crackles
+ subtitles.block.vault.close_shutter: Vault closes
+ subtitles.block.vault.deactivate: Vault extinguishes
+ subtitles.block.vault.eject_item: Vault ejects item
+ subtitles.block.vault.insert_item_fail: Vault fails unlocking
+ subtitles.block.vault.insert_item: Vault unlocks
+ subtitles.block.vault.open_shutter: Vault opens
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
- minecraft/damage_type/wind_charge.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/vault.json
+ minecraft/loot_tables/blocks/vault.json
+ minecraft/tags/items/dyeable.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/vault.json
+ minecraft/models/block/template_vault.json
+ minecraft/models/block/vault_active.json
+ minecraft/models/block/vault_ejecting_reward.json
+ minecraft/models/block/vault_unlocking.json
+ minecraft/models/block/vault.json
+ minecraft/models/item/vault.json
+ minecraft/particles/vault_connection.json
- minecraft/shaders/core/position_color_normal.fsh
- minecraft/shaders/core/position_color_normal.json
- minecraft/shaders/core/position_color_normal.vsh
- minecraft/shaders/core/position_tex_color_normal.fsh
- minecraft/shaders/core/position_tex_color_normal.json
- minecraft/shaders/core/position_tex_color_normal.vsh
- minecraft/shaders/core/position_tex_lightmap_color.fsh
- minecraft/shaders/core/position_tex_lightmap_color.json
- minecraft/shaders/core/position_tex_lightmap_color.vsh
+ minecraft/shaders/core/rendertype_clouds.fsh
+ minecraft/shaders/core/rendertype_clouds.json
+ minecraft/shaders/core/rendertype_clouds.vsh
+ minecraft/textures/block/vault_bottom.png
+ minecraft/textures/block/vault_front_ejecting.png
+ minecraft/textures/block/vault_front_off.png
+ minecraft/textures/block/vault_front_on.png
+ minecraft/textures/block/vault_side_off.png
+ minecraft/textures/block/vault_side_on.png
+ minecraft/textures/block/vault_top_ejecting.png
+ minecraft/textures/block/vault_top_off.png
+ minecraft/textures/block/vault_top_on.png
+ minecraft/textures/particle/vault_connection.png
```

</details>
</details>
<details><summary>Mappings</summary>
<h2>Server</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.commands.arguments.AngleArgument
+ net.minecraft.commands.arguments.AngleArgument$SingleAngle
- net.minecraft.commands.arguments.ArgumentSignatures
+ net.minecraft.commands.arguments.ArgumentSignatures$Entry
- net.minecraft.commands.arguments.ArgumentSignatures$Signer
+ net.minecraft.commands.arguments.blocks.BlockInput
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
- net.minecraft.commands.arguments.blocks.BlockStateArgument
+ net.minecraft.commands.arguments.blocks.BlockStateParser
- net.minecraft.commands.arguments.blocks.BlockStateParser$BlockResult
+ net.minecraft.commands.arguments.blocks.BlockStateParser$TagResult
- net.minecraft.commands.arguments.blocks.package-info
+ net.minecraft.commands.arguments.ColorArgument
- net.minecraft.commands.arguments.ComponentArgument
+ net.minecraft.commands.arguments.CompoundTagArgument
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
- net.minecraft.commands.arguments.DimensionArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument
- net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
+ net.minecraft.commands.arguments.EntityArgument
- net.minecraft.commands.arguments.EntityArgument$Info
+ net.minecraft.commands.arguments.EntityArgument$Info$Template
- net.minecraft.commands.arguments.GameModeArgument
+ net.minecraft.commands.arguments.GameProfileArgument
- net.minecraft.commands.arguments.GameProfileArgument$Result
+ net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
- net.minecraft.commands.arguments.HeightmapTypeArgument
- net.minecraft.commands.arguments.item.FunctionArgument
+ net.minecraft.commands.arguments.item.FunctionArgument$1
- net.minecraft.commands.arguments.item.FunctionArgument$2
+ net.minecraft.commands.arguments.item.FunctionArgument$Result
- net.minecraft.commands.arguments.item.ItemArgument
+ net.minecraft.commands.arguments.item.ItemInput
- net.minecraft.commands.arguments.item.ItemParser
+ net.minecraft.commands.arguments.item.ItemPredicateArgument
- net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
- net.minecraft.commands.arguments.item.ItemPredicateParser$1
- net.minecraft.commands.arguments.item.ItemSyntaxParser$State
- net.minecraft.commands.arguments.item.ItemSyntaxParser$Visitor
+ net.minecraft.commands.arguments.item.package-info
+ net.minecraft.commands.arguments.MessageArgument
- net.minecraft.commands.arguments.MessageArgument$Message
+ net.minecraft.commands.arguments.MessageArgument$Part
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
- net.minecraft.commands.arguments.package-info
+ net.minecraft.commands.arguments.ParticleArgument
- net.minecraft.commands.arguments.RangeArgument
+ net.minecraft.commands.arguments.RangeArgument$Floats
- net.minecraft.commands.arguments.RangeArgument$Ints
+ net.minecraft.commands.arguments.ResourceArgument
- net.minecraft.commands.arguments.ResourceArgument$Info
+ net.minecraft.commands.arguments.ResourceArgument$Info$Template
- net.minecraft.commands.arguments.ResourceKeyArgument
+ net.minecraft.commands.arguments.ResourceKeyArgument$Info
- net.minecraft.commands.arguments.ResourceKeyArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceLocationArgument
- net.minecraft.commands.arguments.ResourceOrTagArgument
+ net.minecraft.commands.arguments.ResourceOrTagArgument$Info
- net.minecraft.commands.arguments.ResourceOrTagArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceOrTagArgument$ResourceResult
- net.minecraft.commands.arguments.ResourceOrTagArgument$Result
+ net.minecraft.commands.arguments.ResourceOrTagArgument$TagResult
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Result
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$TagResult
+ net.minecraft.commands.arguments.ScoreboardSlotArgument
- net.minecraft.commands.arguments.ScoreHolderArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument$Info
- net.minecraft.commands.arguments.ScoreHolderArgument$Info$Template
+ net.minecraft.commands.arguments.ScoreHolderArgument$Result
- net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
+ net.minecraft.commands.arguments.selector.EntitySelector
- net.minecraft.commands.arguments.selector.EntitySelector$1
+ net.minecraft.commands.arguments.selector.EntitySelectorParser
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
+ net.minecraft.commands.arguments.selector.options.package-info
- net.minecraft.commands.arguments.selector.package-info
- net.minecraft.commands.arguments.SignedArgument
+ net.minecraft.commands.arguments.SlotArgument
- net.minecraft.commands.arguments.StringRepresentableArgument
+ net.minecraft.commands.arguments.StyleArgument
- net.minecraft.commands.arguments.TeamArgument
+ net.minecraft.commands.arguments.TemplateMirrorArgument
- net.minecraft.commands.arguments.TemplateRotationArgument
+ net.minecraft.commands.arguments.TimeArgument
- net.minecraft.commands.arguments.TimeArgument$Info
+ net.minecraft.commands.arguments.TimeArgument$Info$Template
- net.minecraft.commands.arguments.UuidArgument
+ net.minecraft.commands.CommandBuildContext$2$1
+ net.minecraft.commands.CommandBuildContext$Configurable
+ net.minecraft.commands.CommandResultCallback
- net.minecraft.commands.CommandResultCallback$1
+ net.minecraft.commands.Commands
- net.minecraft.commands.Commands$1
+ net.minecraft.commands.Commands$1$1
- net.minecraft.commands.Commands$CommandSelection
+ net.minecraft.commands.Commands$ParseFunction
+ net.minecraft.commands.CommandSigningContext
- net.minecraft.commands.CommandSigningContext$1
+ net.minecraft.commands.CommandSigningContext$SignedArguments
- net.minecraft.commands.CommandSource
+ net.minecraft.commands.CommandSource$1
- net.minecraft.commands.CommandSourceStack
+ net.minecraft.commands.execution.ChainModifiers
- net.minecraft.commands.execution.CommandQueueEntry
+ net.minecraft.commands.execution.CustomCommandExecutor
- net.minecraft.commands.execution.CustomCommandExecutor$CommandAdapter
+ net.minecraft.commands.execution.CustomCommandExecutor$WithErrorHandling
- net.minecraft.commands.execution.CustomModifierExecutor
+ net.minecraft.commands.execution.CustomModifierExecutor$ModifierAdapter
- net.minecraft.commands.execution.EntryAction
+ net.minecraft.commands.execution.ExecutionContext
- net.minecraft.commands.execution.ExecutionControl
+ net.minecraft.commands.execution.ExecutionControl$1
- net.minecraft.commands.execution.Frame
+ net.minecraft.commands.execution.Frame$FrameControl
- net.minecraft.commands.execution.package-info
+ net.minecraft.commands.execution.tasks.BuildContexts
- net.minecraft.commands.execution.tasks.BuildContexts$Continuation
+ net.minecraft.commands.execution.tasks.BuildContexts$TopLevel
- net.minecraft.commands.execution.tasks.BuildContexts$Unbound
+ net.minecraft.commands.execution.tasks.CallFunction
- net.minecraft.commands.execution.tasks.ContinuationTask
+ net.minecraft.commands.execution.tasks.ContinuationTask$TaskProvider
- net.minecraft.commands.execution.tasks.ExecuteCommand
+ net.minecraft.commands.execution.tasks.FallthroughTask
- net.minecraft.commands.execution.tasks.IsolatedCall
+ net.minecraft.commands.execution.tasks.package-info
- net.minecraft.commands.execution.TraceCallbacks
+ net.minecraft.commands.execution.UnboundEntryAction
- net.minecraft.commands.ExecutionCommandSource
+ net.minecraft.commands.FunctionInstantiationException
- net.minecraft.commands.functions.CommandFunction
+ net.minecraft.commands.functions.FunctionBuilder
- net.minecraft.commands.functions.InstantiatedFunction
+ net.minecraft.commands.functions.MacroFunction
- net.minecraft.commands.functions.MacroFunction$Entry
+ net.minecraft.commands.functions.MacroFunction$MacroEntry
- net.minecraft.commands.functions.MacroFunction$PlainTextEntry
+ net.minecraft.commands.functions.package-info
+ net.minecraft.commands.functions.PlainTextFunction
- net.minecraft.commands.functions.StringTemplate
- net.minecraft.commands.package-info
- net.minecraft.commands.ParserUtils
+ net.minecraft.commands.SharedSuggestionProvider
- net.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ net.minecraft.commands.synchronization.ArgumentTypeInfo
- net.minecraft.commands.synchronization.ArgumentTypeInfo$Template
+ net.minecraft.commands.synchronization.ArgumentTypeInfos
- net.minecraft.commands.synchronization.ArgumentUtils
+ net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo
- net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo
- net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo
- net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.LongArgumentInfo
- net.minecraft.commands.synchronization.brigadier.LongArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.package-info
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$1
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$Template
+ net.minecraft.commands.synchronization.package-info
+ net.minecraft.commands.synchronization.SingletonArgumentInfo
- net.minecraft.commands.synchronization.SingletonArgumentInfo$Template
+ net.minecraft.commands.synchronization.SuggestionProviders
- net.minecraft.commands.synchronization.SuggestionProviders$Wrapper
- net.minecraft.core.AxisCycle
+ net.minecraft.core.AxisCycle$1
- net.minecraft.core.AxisCycle$2
+ net.minecraft.core.AxisCycle$3
- net.minecraft.core.BlockMath
+ net.minecraft.core.BlockPos
- net.minecraft.core.BlockPos$1
+ net.minecraft.core.BlockPos$2
- net.minecraft.core.BlockPos$3
+ net.minecraft.core.BlockPos$4
- net.minecraft.core.BlockPos$5
+ net.minecraft.core.BlockPos$6
- net.minecraft.core.BlockPos$MutableBlockPos
+ net.minecraft.core.Cloner
- net.minecraft.core.Cloner$Factory
+ net.minecraft.core.Cursor3D
- net.minecraft.core.DefaultedMappedRegistry
+ net.minecraft.core.DefaultedRegistry
- net.minecraft.core.Direction
+ net.minecraft.core.Direction$1
- net.minecraft.core.Direction$Axis
+ net.minecraft.core.Direction$Axis$1
- net.minecraft.core.Direction$Axis$2
+ net.minecraft.core.Direction$Axis$3
- net.minecraft.core.Direction$AxisDirection
+ net.minecraft.core.Direction$Plane
- net.minecraft.core.Direction8
+ net.minecraft.core.FrontAndTop
- net.minecraft.core.GlobalPos
+ net.minecraft.core.Holder
- net.minecraft.core.Holder$Direct
+ net.minecraft.core.Holder$Kind
- net.minecraft.core.Holder$Reference
+ net.minecraft.core.Holder$Reference$Type
- net.minecraft.core.HolderGetter
+ net.minecraft.core.HolderGetter$Provider
- net.minecraft.core.HolderLookup
+ net.minecraft.core.HolderLookup$1
+ net.minecraft.core.HolderLookup$Provider
- net.minecraft.core.HolderLookup$Provider$1
+ net.minecraft.core.HolderLookup$Provider$2
- net.minecraft.core.HolderLookup$RegistryLookup
+ net.minecraft.gametest.framework.GameTestInfo
- net.minecraft.gametest.framework.GameTestListener
+ net.minecraft.gametest.framework.GameTestRegistry
- net.minecraft.gametest.framework.GameTestRunner
+ net.minecraft.gametest.framework.GameTestRunner$1
- net.minecraft.gametest.framework.GameTestRunner$Builder
+ net.minecraft.gametest.framework.GameTestRunner$GameTestBatcher
- net.minecraft.gametest.framework.GameTestRunner$StructureSpawner
+ net.minecraft.gametest.framework.GameTestSequence
- net.minecraft.gametest.framework.GameTestSequence$Condition
+ net.minecraft.gametest.framework.GameTestServer
- net.minecraft.gametest.framework.GameTestServer$1
+ net.minecraft.gametest.framework.GameTestTicker
- net.minecraft.gametest.framework.GameTestTimeoutException
+ net.minecraft.gametest.framework.GlobalTestReporter
- net.minecraft.gametest.framework.JUnitLikeTestReporter
+ net.minecraft.gametest.framework.LogTestReporter
- net.minecraft.gametest.framework.MultipleTestTracker
+ net.minecraft.gametest.framework.MultipleTestTracker$1
+ net.minecraft.gametest.framework.package-info
- net.minecraft.gametest.framework.ReportGameListener
+ net.minecraft.gametest.framework.RetryOptions
- net.minecraft.gametest.framework.StructureBlockPosFinder
+ net.minecraft.gametest.framework.StructureGridSpawner
- net.minecraft.gametest.framework.StructureUtils
+ net.minecraft.gametest.framework.StructureUtils$1
- net.minecraft.gametest.framework.TestClassNameArgument
+ net.minecraft.gametest.framework.TestCommand
- net.minecraft.gametest.framework.TestCommand$Runner
+ net.minecraft.gametest.framework.TestCommand$TestBatchSummaryDisplayer
- net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
+ net.minecraft.gametest.framework.TestFinder
- net.minecraft.gametest.framework.TestFinder$Builder
+ net.minecraft.gametest.framework.TestFunction
- net.minecraft.gametest.framework.TestFunctionArgument
+ net.minecraft.gametest.framework.TestFunctionFinder
- net.minecraft.gametest.framework.TestReporter
- net.minecraft.locale.Language
+ net.minecraft.locale.Language$1
- net.minecraft.locale.package-info
+ net.minecraft.nbt.ByteArrayTag
- net.minecraft.nbt.ByteArrayTag$1
+ net.minecraft.nbt.ByteTag
- net.minecraft.nbt.ByteTag$1
+ net.minecraft.nbt.ByteTag$Cache
- net.minecraft.nbt.CollectionTag
+ net.minecraft.nbt.CompoundTag
- net.minecraft.nbt.CompoundTag$1
+ net.minecraft.nbt.CompoundTag$2
- net.minecraft.nbt.DoubleTag
+ net.minecraft.nbt.DoubleTag$1
- net.minecraft.nbt.EndTag
+ net.minecraft.nbt.EndTag$1
- net.minecraft.nbt.FloatTag
+ net.minecraft.nbt.FloatTag$1
- net.minecraft.nbt.IntArrayTag
+ net.minecraft.nbt.IntArrayTag$1
- net.minecraft.nbt.IntTag
+ net.minecraft.nbt.IntTag$1
- net.minecraft.nbt.IntTag$Cache
+ net.minecraft.nbt.ListTag
- net.minecraft.nbt.ListTag$1
+ net.minecraft.nbt.ListTag$2
- net.minecraft.nbt.LongArrayTag
+ net.minecraft.nbt.LongArrayTag$1
- net.minecraft.nbt.LongTag
+ net.minecraft.nbt.LongTag$1
- net.minecraft.nbt.LongTag$Cache
+ net.minecraft.nbt.NbtAccounter
- net.minecraft.nbt.NbtAccounterException
+ net.minecraft.nbt.NbtException
- net.minecraft.nbt.NbtFormatException
+ net.minecraft.nbt.NbtIo
- net.minecraft.nbt.NbtIo$1
+ net.minecraft.nbt.NbtIo$StringFallbackDataOutput
- net.minecraft.nbt.NbtOps
+ net.minecraft.nbt.NbtOps$1
- net.minecraft.nbt.NbtOps$ByteListCollector
+ net.minecraft.nbt.NbtOps$HeterogenousListCollector
- net.minecraft.nbt.NbtOps$HomogenousListCollector
+ net.minecraft.nbt.NbtOps$InitialListCollector
- net.minecraft.nbt.NbtOps$IntListCollector
+ net.minecraft.nbt.NbtOps$ListCollector
- net.minecraft.nbt.NbtOps$LongListCollector
+ net.minecraft.nbt.NbtOps$NbtRecordBuilder
- net.minecraft.nbt.NbtUtils
+ net.minecraft.nbt.NumericTag
+ net.minecraft.nbt.package-info
- net.minecraft.nbt.ReportedNbtException
+ net.minecraft.nbt.ShortTag
- net.minecraft.nbt.ShortTag$1
+ net.minecraft.nbt.ShortTag$Cache
- net.minecraft.nbt.SnbtPrinterTagVisitor
+ net.minecraft.nbt.StreamTagVisitor
- net.minecraft.nbt.StreamTagVisitor$EntryResult
+ net.minecraft.nbt.StreamTagVisitor$ValueResult
- net.minecraft.nbt.StringTag
+ net.minecraft.nbt.StringTag$1
- net.minecraft.nbt.StringTagVisitor
+ net.minecraft.nbt.Tag
- net.minecraft.nbt.TagParser
+ net.minecraft.nbt.TagType
- net.minecraft.nbt.TagType$1
+ net.minecraft.nbt.TagType$2
- net.minecraft.nbt.TagType$StaticSize
+ net.minecraft.nbt.TagType$VariableSize
- net.minecraft.nbt.TagTypes
+ net.minecraft.nbt.TagVisitor
- net.minecraft.nbt.TextComponentTagVisitor
- net.minecraft.nbt.visitors.CollectFields
+ net.minecraft.nbt.visitors.CollectToTag
- net.minecraft.nbt.visitors.FieldSelector
+ net.minecraft.nbt.visitors.FieldTree
+ net.minecraft.nbt.visitors.package-info
- net.minecraft.nbt.visitors.SkipAll
+ net.minecraft.nbt.visitors.SkipAll$1
- net.minecraft.nbt.visitors.SkipFields
- net.minecraft.network.BandwidthDebugMonitor
- net.minecraft.network.chat.ChatDecorator
+ net.minecraft.network.chat.ChatType
- net.minecraft.network.chat.ChatType$Bound
+ net.minecraft.network.chat.ChatTypeDecoration
- net.minecraft.network.chat.ChatTypeDecoration$Parameter
+ net.minecraft.network.chat.ChatTypeDecoration$Parameter$Selector
- net.minecraft.network.chat.ClickEvent
+ net.minecraft.network.chat.ClickEvent$Action
- net.minecraft.network.chat.CommonComponents
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.Component$SerializerAdapter
- net.minecraft.network.chat.ComponentContents
+ net.minecraft.network.chat.ComponentContents$Type
- net.minecraft.network.chat.ComponentSerialization
+ net.minecraft.network.chat.ComponentSerialization$FuzzyCodec
- net.minecraft.network.chat.ComponentSerialization$StrictEither
+ net.minecraft.network.chat.ComponentUtils
+ net.minecraft.network.chat.contents.BlockDataSource
- net.minecraft.network.chat.contents.DataSource
+ net.minecraft.network.chat.contents.DataSource$Type
- net.minecraft.network.chat.contents.EntityDataSource
+ net.minecraft.network.chat.contents.KeybindContents
- net.minecraft.network.chat.contents.KeybindResolver
+ net.minecraft.network.chat.contents.NbtContents
- net.minecraft.network.chat.contents.package-info
- net.minecraft.network.chat.contents.PlainTextContents
+ net.minecraft.network.chat.contents.PlainTextContents$1
- net.minecraft.network.chat.contents.PlainTextContents$LiteralContents
+ net.minecraft.network.chat.contents.ScoreContents
- net.minecraft.network.chat.contents.SelectorContents
+ net.minecraft.network.chat.contents.StorageDataSource
- net.minecraft.network.chat.contents.TranslatableContents
+ net.minecraft.network.chat.contents.TranslatableFormatException
- net.minecraft.network.chat.FilterMask
+ net.minecraft.network.chat.FilterMask$1
- net.minecraft.network.chat.FilterMask$Type
+ net.minecraft.network.chat.FormattedText
- net.minecraft.network.chat.FormattedText$1
+ net.minecraft.network.chat.FormattedText$2
- net.minecraft.network.chat.FormattedText$3
+ net.minecraft.network.chat.FormattedText$4
- net.minecraft.network.chat.FormattedText$ContentConsumer
+ net.minecraft.network.chat.FormattedText$StyledContentConsumer
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
+ net.minecraft.network.chat.HoverEvent$ItemStackInfo
- net.minecraft.network.chat.HoverEvent$TypedHoverEvent
+ net.minecraft.network.chat.LastSeenMessages
- net.minecraft.network.chat.LastSeenMessages$Packed
+ net.minecraft.network.chat.LastSeenMessages$Update
- net.minecraft.network.chat.LastSeenMessagesTracker
+ net.minecraft.network.chat.LastSeenMessagesTracker$Update
- net.minecraft.network.chat.LastSeenMessagesValidator
+ net.minecraft.network.chat.LastSeenTrackedEntry
- net.minecraft.network.chat.LocalChatSession
+ net.minecraft.network.chat.MessageSignature
- net.minecraft.network.chat.MessageSignature$Packed
+ net.minecraft.network.chat.MessageSignatureCache
- net.minecraft.network.chat.MutableComponent
+ net.minecraft.network.chat.numbers.BlankFormat
- net.minecraft.network.chat.numbers.BlankFormat$1
+ net.minecraft.network.chat.numbers.FixedFormat
- net.minecraft.network.chat.numbers.FixedFormat$1
+ net.minecraft.network.chat.numbers.NumberFormat
- net.minecraft.network.chat.numbers.NumberFormatType
+ net.minecraft.network.chat.numbers.NumberFormatTypes
- net.minecraft.network.chat.numbers.package-info
- net.minecraft.network.chat.numbers.StyledFormat
+ net.minecraft.network.chat.numbers.StyledFormat$1
+ net.minecraft.network.chat.OutgoingChatMessage
- net.minecraft.network.chat.OutgoingChatMessage$Disguised
+ net.minecraft.network.chat.OutgoingChatMessage$Player
+ net.minecraft.network.chat.package-info
- net.minecraft.network.chat.PlayerChatMessage
+ net.minecraft.network.chat.RemoteChatSession
- net.minecraft.network.chat.RemoteChatSession$Data
+ net.minecraft.network.chat.SignableCommand
- net.minecraft.network.chat.SignableCommand$Argument
+ net.minecraft.network.chat.SignedMessageBody
- net.minecraft.network.chat.SignedMessageBody$Packed
+ net.minecraft.network.chat.SignedMessageChain
- net.minecraft.network.chat.SignedMessageChain$DecodeException
+ net.minecraft.network.chat.SignedMessageChain$Decoder
- net.minecraft.network.chat.SignedMessageChain$Encoder
+ net.minecraft.network.chat.SignedMessageLink
- net.minecraft.network.chat.SignedMessageValidator
+ net.minecraft.network.chat.SignedMessageValidator$KeyBased
- net.minecraft.network.chat.Style
+ net.minecraft.network.chat.Style$1
- net.minecraft.network.chat.Style$1Collector
+ net.minecraft.network.chat.Style$Serializer
- net.minecraft.network.chat.SubStringSource
+ net.minecraft.network.chat.TextColor
- net.minecraft.network.chat.ThrowingComponent
+ net.minecraft.network.CipherBase
- net.minecraft.network.CipherDecoder
+ net.minecraft.network.CipherEncoder
- net.minecraft.network.ClientboundPacketListener
- net.minecraft.network.codec.ByteBufCodecs
+ net.minecraft.network.codec.ByteBufCodecs$1
- net.minecraft.network.codec.ByteBufCodecs$10
+ net.minecraft.network.codec.ByteBufCodecs$11
- net.minecraft.network.codec.ByteBufCodecs$12
+ net.minecraft.network.codec.ByteBufCodecs$13
- net.minecraft.network.codec.ByteBufCodecs$14
+ net.minecraft.network.codec.ByteBufCodecs$15
- net.minecraft.network.codec.ByteBufCodecs$16
+ net.minecraft.network.codec.ByteBufCodecs$17
- net.minecraft.network.codec.ByteBufCodecs$18
+ net.minecraft.network.codec.ByteBufCodecs$19
- net.minecraft.network.codec.ByteBufCodecs$2
- net.minecraft.network.codec.ByteBufCodecs$21
- net.minecraft.network.codec.StreamCodec$10
+ net.minecraft.network.CompressionDecoder
- net.minecraft.network.CompressionEncoder
+ net.minecraft.network.Connection
- net.minecraft.network.Connection$1
+ net.minecraft.network.Connection$2
- net.minecraft.network.Connection$3
+ net.minecraft.network.ConnectionProtocol
- net.minecraft.network.FriendlyByteBuf
+ net.minecraft.network.HandlerNames
- net.minecraft.network.PacketBundlePacker
+ net.minecraft.network.PacketBundleUnpacker
- net.minecraft.network.PacketDecoder
+ net.minecraft.network.PacketEncoder
- net.minecraft.network.PacketListener
+ net.minecraft.network.PacketSendListener
- net.minecraft.network.PacketSendListener$1
+ net.minecraft.network.PacketSendListener$2
- net.minecraft.network.protocol.game.ClientboundCommandsPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
- net.minecraft.network.protocol.game.ClientboundContainerClosePacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
- net.minecraft.network.protocol.game.ClientboundCooldownPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ net.minecraft.network.protocol.game.ClientboundDamageEventPacket
- net.minecraft.network.protocol.game.ClientboundDebugSamplePacket
+ net.minecraft.network.protocol.game.package-info
- net.minecraft.network.protocol.game.ServerboundEditBookPacket
+ net.minecraft.network.protocol.game.ServerboundEntityTagQueryPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$1
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
- net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$StatusOnly
- net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
- net.minecraft.network.protocol.game.ServerboundPickItemPacket
+ net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
- net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
- net.minecraft.network.protocol.game.ServerboundRenameItemPacket
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSelectTradePacket
- net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
+ net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
- net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
+ net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
- net.minecraft.network.protocol.game.ServerboundSwingPacket
+ net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
- net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemPacket
- net.minecraft.network.protocol.game.VecDeltaCodec
- net.minecraft.network.protocol.handshake.ClientIntent
+ net.minecraft.network.protocol.handshake.ClientIntent$1
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
+ net.minecraft.network.protocol.handshake.HandshakePacketTypes
- net.minecraft.network.protocol.handshake.HandshakeProtocols
- net.minecraft.network.protocol.handshake.package-info
+ net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
- net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ClientboundGameProfilePacket
- net.minecraft.network.protocol.login.ClientboundHelloPacket
+ net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
- net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
+ net.minecraft.network.protocol.login.ClientLoginPacketListener
- net.minecraft.network.protocol.login.custom.CustomQueryAnswerPayload
+ net.minecraft.network.protocol.login.custom.CustomQueryPayload
- net.minecraft.network.protocol.login.custom.DiscardedQueryAnswerPayload
+ net.minecraft.network.protocol.login.custom.DiscardedQueryPayload
- net.minecraft.network.protocol.login.custom.package-info
+ net.minecraft.network.protocol.login.LoginPacketTypes
- net.minecraft.network.protocol.login.LoginProtocols
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryAnswerPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerboundLoginAcknowledgedPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
- net.minecraft.network.protocol.ping.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.ping.ClientPongPacketListener
- net.minecraft.network.protocol.ping.package-info
+ net.minecraft.network.protocol.ping.PingPacketTypes
+ net.minecraft.network.protocol.ping.ServerboundPingRequestPacket
- net.minecraft.network.protocol.ping.ServerPingPacketListener
- net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
+ net.minecraft.network.protocol.status.ServerStatus
- net.minecraft.network.protocol.status.ServerStatus$Favicon
+ net.minecraft.network.protocol.status.ServerStatus$Players
- net.minecraft.network.protocol.status.ServerStatus$Version
+ net.minecraft.network.protocol.status.ServerStatusPacketListener
+ net.minecraft.network.protocol.status.StatusPacketTypes
- net.minecraft.network.protocol.status.StatusProtocols
- net.minecraft.network.ProtocolInfo
+ net.minecraft.network.ProtocolInfo$Unbound
- net.minecraft.network.ProtocolSwapHandler
+ net.minecraft.network.RateKickingConnection
- net.minecraft.network.RegistryFriendlyByteBuf
+ net.minecraft.network.ServerboundPacketListener
- net.minecraft.network.SkipPacketException
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializer$ForValueType
+ net.minecraft.network.syncher.EntityDataSerializers
- net.minecraft.network.syncher.EntityDataSerializers$1
+ net.minecraft.network.syncher.EntityDataSerializers$2
- net.minecraft.network.syncher.EntityDataSerializers$3
+ net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.network.syncher.SynchedEntityData$DataValue
+ net.minecraft.network.TickablePacketListener
- net.minecraft.network.UnconfiguredPipelineHandler
+ net.minecraft.network.UnconfiguredPipelineHandler$Inbound
- net.minecraft.network.UnconfiguredPipelineHandler$InboundConfigurationTask
+ net.minecraft.network.UnconfiguredPipelineHandler$Outbound
- net.minecraft.network.UnconfiguredPipelineHandler$OutboundConfigurationTask
+ net.minecraft.network.Utf8String
- net.minecraft.network.VarInt
- net.minecraft.network.Varint21FrameDecoder
+ net.minecraft.network.Varint21LengthFieldPrepender
+ net.minecraft.network.VarLong
- net.minecraft.obfuscate.DontObfuscate
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.references.Blocks
+ net.minecraft.references.Items
- net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.FileToIdConverter
- net.minecraft.resources.HolderSetCodec
- net.minecraft.resources.package-info
+ net.minecraft.resources.RegistryDataLoader
- net.minecraft.resources.RegistryDataLoader$1
+ net.minecraft.resources.RegistryDataLoader$Loader
- net.minecraft.resources.RegistryDataLoader$LoadingFunction
+ net.minecraft.resources.RegistryDataLoader$RegistryData
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryFixedCodec
- net.minecraft.resources.RegistryOps
+ net.minecraft.resources.RegistryOps$1
- net.minecraft.resources.RegistryOps$2
+ net.minecraft.resources.RegistryOps$RegistryInfo
- net.minecraft.resources.RegistryOps$RegistryInfoLookup
+ net.minecraft.resources.ResourceKey
- net.minecraft.resources.ResourceKey$InternKey
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Dummy
+ net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator$Output
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ net.minecraft.server.advancements.package-info
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$Entry
+ net.minecraft.server.chase.ChaseClient
- net.minecraft.server.chase.ChaseClient$TeleportTarget
+ net.minecraft.server.chase.ChaseServer
- net.minecraft.server.chase.ChaseServer$PlayerPosition
+ net.minecraft.server.chase.package-info
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.AttributeCommand
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ChaseCommand
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockInfo
- net.minecraft.server.commands.CloneCommands$CommandFunction
+ net.minecraft.server.commands.CloneCommands$DimensionAndPosition
- net.minecraft.server.commands.CloneCommands$Mode
+ net.minecraft.server.commands.DamageCommand
+ net.minecraft.server.commands.data.BlockDataAccessor
- net.minecraft.server.commands.data.BlockDataAccessor$1
+ net.minecraft.server.commands.data.DataAccessor
- net.minecraft.server.commands.data.DataCommands
+ net.minecraft.server.commands.data.DataCommands$DataManipulator
- net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
+ net.minecraft.server.commands.data.DataCommands$DataProvider
- net.minecraft.server.commands.data.DataCommands$StringProcessor
+ net.minecraft.server.commands.data.EntityDataAccessor
- net.minecraft.server.commands.data.EntityDataAccessor$1
+ net.minecraft.server.commands.data.package-info
+ net.minecraft.server.commands.data.StorageDataAccessor
- net.minecraft.server.commands.data.StorageDataAccessor$1
- net.minecraft.server.commands.DataPackCommand
+ net.minecraft.server.commands.DataPackCommand$Inserter
+ net.minecraft.server.commands.DebugCommand
- net.minecraft.server.commands.DebugCommand$TraceCustomExecutor
+ net.minecraft.server.commands.DebugCommand$TraceCustomExecutor$1
- net.minecraft.server.commands.DebugCommand$Tracer
+ net.minecraft.server.commands.DebugConfigCommand
- net.minecraft.server.commands.DebugMobSpawningCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.DifficultyCommand
- net.minecraft.server.commands.EffectCommands
+ net.minecraft.server.commands.EmoteCommands
- net.minecraft.server.commands.EnchantCommand
+ net.minecraft.server.commands.ExecuteCommand
- net.minecraft.server.commands.ExecuteCommand$CommandGetter
+ net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
- net.minecraft.server.commands.ExecuteCommand$CommandPredicate
+ net.minecraft.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
- net.minecraft.server.commands.ExecuteCommand$IntBiPredicate
+ net.minecraft.server.commands.ExperienceCommand
- net.minecraft.server.commands.ExperienceCommand$Type
+ net.minecraft.server.commands.FillBiomeCommand
- net.minecraft.server.commands.FillCommand
+ net.minecraft.server.commands.FillCommand$Mode
- net.minecraft.server.commands.ForceLoadCommand
+ net.minecraft.server.commands.FunctionCommand
- net.minecraft.server.commands.FunctionCommand$1
+ net.minecraft.server.commands.FunctionCommand$1Accumulator
- net.minecraft.server.commands.FunctionCommand$2
+ net.minecraft.server.commands.FunctionCommand$3
- net.minecraft.server.commands.FunctionCommand$4
+ net.minecraft.server.commands.FunctionCommand$5
- net.minecraft.server.commands.FunctionCommand$Callbacks
+ net.minecraft.server.commands.FunctionCommand$FunctionCustomExecutor
- net.minecraft.server.commands.GameModeCommand
+ net.minecraft.server.commands.GameRuleCommand
- net.minecraft.server.commands.GameRuleCommand$1
+ net.minecraft.server.commands.GiveCommand
- net.minecraft.server.commands.HelpCommand
+ net.minecraft.server.commands.ItemCommands
- net.minecraft.server.commands.JfrCommand
+ net.minecraft.server.commands.KickCommand
- net.minecraft.server.commands.KillCommand
+ net.minecraft.server.commands.ListPlayersCommand
- net.minecraft.server.commands.LocateCommand
+ net.minecraft.server.commands.LootCommand
- net.minecraft.server.commands.LootCommand$Callback
+ net.minecraft.server.commands.LootCommand$DropConsumer
- net.minecraft.server.commands.LootCommand$TailProvider
+ net.minecraft.server.commands.MsgCommand
- net.minecraft.server.commands.OpCommand
- net.minecraft.server.commands.package-info
+ net.minecraft.server.commands.PardonCommand
- net.minecraft.server.commands.PardonIpCommand
+ net.minecraft.server.commands.ParticleCommand
- net.minecraft.server.commands.PerfCommand
+ net.minecraft.server.commands.PlaceCommand
- net.minecraft.server.commands.PlaySoundCommand
+ net.minecraft.server.commands.PublishCommand
- net.minecraft.server.commands.RaidCommand
+ net.minecraft.server.commands.RandomCommand
- net.minecraft.server.commands.RecipeCommand
+ net.minecraft.server.commands.ReloadCommand
- net.minecraft.server.commands.ResetChunksCommand
+ net.minecraft.server.commands.ReturnCommand
- net.minecraft.server.commands.ReturnCommand$ReturnFailCustomExecutor
+ net.minecraft.server.commands.ReturnCommand$ReturnFromCommandCustomModifier
- net.minecraft.server.commands.ReturnCommand$ReturnValueCustomExecutor
+ net.minecraft.server.commands.RideCommand
- net.minecraft.server.commands.SaveAllCommand
+ net.minecraft.server.commands.SaveOffCommand
- net.minecraft.server.commands.SaveOnCommand
+ net.minecraft.server.commands.SayCommand
- net.minecraft.server.commands.ScheduleCommand
+ net.minecraft.server.commands.ScoreboardCommand
- net.minecraft.server.commands.ScoreboardCommand$NumberFormatCommandExecutor
+ net.minecraft.server.commands.SeedCommand
- net.minecraft.server.commands.ServerPackCommand
+ net.minecraft.server.commands.SetBlockCommand
- net.minecraft.server.commands.SetBlockCommand$Filter
+ net.minecraft.server.commands.SetBlockCommand$Mode
- net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
+ net.minecraft.server.commands.SetSpawnCommand
- net.minecraft.server.commands.SetWorldSpawnCommand
+ net.minecraft.server.commands.SpawnArmorTrimsCommand
- net.minecraft.server.commands.SpectateCommand
+ net.minecraft.server.commands.SpreadPlayersCommand
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
- net.minecraft.server.commands.TickCommand
+ net.minecraft.server.commands.TimeCommand
- net.minecraft.server.commands.TitleCommand
+ net.minecraft.server.commands.TransferCommand
- net.minecraft.server.commands.TriggerCommand
+ net.minecraft.server.commands.WardenSpawnTrackerCommand
- net.minecraft.server.commands.WeatherCommand
+ net.minecraft.server.commands.WhitelistCommand
- net.minecraft.server.commands.WorldBorderCommand
+ net.minecraft.server.ConsoleInput
- net.minecraft.server.DebugLoggedPrintStream
+ net.minecraft.server.dedicated.DedicatedPlayerList
- net.minecraft.server.dedicated.DedicatedServer
+ net.minecraft.server.dedicated.DedicatedServer$1
- net.minecraft.server.dedicated.DedicatedServerProperties
+ net.minecraft.server.dedicated.DedicatedServerProperties$WorldDimensionData
- net.minecraft.server.dedicated.DedicatedServerSettings
+ net.minecraft.server.dedicated.package-info
+ net.minecraft.server.dedicated.ServerWatchdog
- net.minecraft.server.dedicated.ServerWatchdog$1
+ net.minecraft.server.dedicated.Settings
- net.minecraft.server.dedicated.Settings$MutableValue
+ net.minecraft.server.Eula
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
- net.minecraft.server.level.ChunkHolder$LevelChangeListener
+ net.minecraft.server.level.ChunkHolder$PlayerProvider
- net.minecraft.server.level.ChunkLevel
+ net.minecraft.server.level.ChunkLevel$1
- net.minecraft.server.level.ChunkMap
+ net.minecraft.server.level.ChunkMap$1
- net.minecraft.server.level.ChunkMap$2
+ net.minecraft.server.level.ChunkMap$DistanceManager
- net.minecraft.server.level.ChunkMap$TrackedEntity
+ net.minecraft.server.level.ChunkTaskPriorityQueue
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
+ net.minecraft.server.level.ChunkTracker
- net.minecraft.server.level.ChunkTrackingView
+ net.minecraft.server.level.ChunkTrackingView$1
- net.minecraft.server.level.ChunkTrackingView$Positioned
+ net.minecraft.server.level.ClientInformation
- net.minecraft.server.level.ColumnPos
+ net.minecraft.server.level.DemoMode
- net.minecraft.server.level.DistanceManager
+ net.minecraft.server.level.DistanceManager$ChunkTicketTracker
- net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ net.minecraft.server.level.DistanceManager$PlayerTicketTracker
- net.minecraft.server.level.FullChunkStatus
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
- net.minecraft.server.level.ServerChunkCache$ChunkAndHolder
+ net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
- net.minecraft.server.level.ServerEntity
+ net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerLevel$EntityCallbacks
+ net.minecraft.server.level.ServerPlayer
- net.minecraft.server.level.ServerPlayer$1
+ net.minecraft.server.level.ServerPlayer$2
- net.minecraft.server.level.ServerPlayerGameMode
+ net.minecraft.server.level.ThreadedLevelLightEngine
- net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
+ net.minecraft.server.level.Ticket
- net.minecraft.server.level.TicketType
+ net.minecraft.server.level.TickingTracker
- net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.Main
- net.minecraft.server.Main$1
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$ReloadableResources
- net.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ net.minecraft.server.MinecraftServer$TimeProfiler
- net.minecraft.server.MinecraftServer$TimeProfiler$1
- net.minecraft.server.network.CommonListenerCookie
- net.minecraft.server.network.config.JoinWorldTask
- net.minecraft.server.network.config.package-info
+ net.minecraft.server.network.config.ServerResourcePackConfigurationTask
+ net.minecraft.server.network.ConfigurationTask
- net.minecraft.server.network.ConfigurationTask$Type
+ net.minecraft.server.network.FilteredText
- net.minecraft.server.network.LegacyProtocolUtils
+ net.minecraft.server.network.LegacyQueryHandler
- net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
+ net.minecraft.server.network.package-info
+ net.minecraft.server.network.PlayerChunkSender
- net.minecraft.server.network.ServerCommonPacketListenerImpl
+ net.minecraft.server.network.ServerConfigurationPacketListenerImpl
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
- net.minecraft.server.network.TextFilterClient
+ net.minecraft.server.network.TextFilterClient$IgnoreStrategy
- net.minecraft.server.network.TextFilterClient$JoinOrLeaveEncoder
+ net.minecraft.server.network.TextFilterClient$MessageEncoder
- net.minecraft.server.network.TextFilterClient$PlayerContext
+ net.minecraft.server.network.TextFilterClient$RequestFailedException
- net.minecraft.server.package-info
+ net.minecraft.server.packs.AbstractPackResources
- net.minecraft.server.packs.BuiltInMetadata
+ net.minecraft.server.packs.CompositePackResources
- net.minecraft.server.packs.DownloadCacheCleaner
+ net.minecraft.server.packs.DownloadCacheCleaner$1
- net.minecraft.server.packs.DownloadCacheCleaner$PathAndPriority
+ net.minecraft.server.packs.DownloadCacheCleaner$PathAndTime
- net.minecraft.server.packs.DownloadQueue
+ net.minecraft.server.packs.DownloadQueue$BatchConfig
- net.minecraft.server.packs.DownloadQueue$BatchResult
+ net.minecraft.server.packs.DownloadQueue$DownloadRequest
- net.minecraft.server.packs.DownloadQueue$FileInfoEntry
+ net.minecraft.server.packs.DownloadQueue$LogEntry
- net.minecraft.server.packs.FeatureFlagsMetadataSection
+ net.minecraft.server.packs.FilePackResources
- net.minecraft.server.packs.FilePackResources$FileResourcesSupplier
+ net.minecraft.server.packs.FilePackResources$SharedZipFileAccess
+ net.minecraft.server.packs.linkfs.DummyFileAttributes
- net.minecraft.server.packs.linkfs.LinkFileSystem
+ net.minecraft.server.packs.linkfs.LinkFileSystem$Builder
- net.minecraft.server.packs.linkfs.LinkFileSystem$DirectoryEntry
- net.minecraft.server.packs.linkfs.LinkFSFileStore
+ net.minecraft.server.packs.linkfs.LinkFSPath
- net.minecraft.server.packs.linkfs.LinkFSPath$1
+ net.minecraft.server.packs.linkfs.LinkFSPath$2
- net.minecraft.server.packs.linkfs.LinkFSPath$3
+ net.minecraft.server.packs.linkfs.LinkFSProvider
- net.minecraft.server.packs.linkfs.LinkFSProvider$1
+ net.minecraft.server.packs.linkfs.LinkFSProvider$2
- net.minecraft.server.packs.linkfs.package-info
+ net.minecraft.server.packs.linkfs.PathContents
- net.minecraft.server.packs.linkfs.PathContents$1
+ net.minecraft.server.packs.linkfs.PathContents$2
- net.minecraft.server.packs.linkfs.PathContents$DirectoryContents
+ net.minecraft.server.packs.linkfs.PathContents$FileContents
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.MetadataSectionType
+ net.minecraft.server.packs.metadata.MetadataSectionType$1
+ net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
- net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.OverlayMetadataSection
+ net.minecraft.server.packs.OverlayMetadataSection$OverlayEntry
+ net.minecraft.server.packs.package-info
- net.minecraft.server.packs.PackResources
+ net.minecraft.server.packs.PackResources$ResourceOutput
- net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.PathPackResources
- net.minecraft.server.packs.PathPackResources$PathResourcesSupplier
- net.minecraft.server.packs.repository.BuiltInPackSource
+ net.minecraft.server.packs.repository.BuiltInPackSource$1
- net.minecraft.server.packs.repository.FolderRepositorySource
+ net.minecraft.server.packs.repository.FolderRepositorySource$FolderPackDetector
- net.minecraft.server.packs.repository.Pack
+ net.minecraft.server.packs.repository.Pack$Info
- net.minecraft.server.packs.repository.Pack$Position
+ net.minecraft.server.packs.repository.Pack$ResourcesSupplier
+ net.minecraft.server.packs.repository.package-info
- net.minecraft.server.packs.repository.PackCompatibility
+ net.minecraft.server.packs.repository.PackDetector
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.PackSource
- net.minecraft.server.packs.repository.PackSource$1
+ net.minecraft.server.packs.repository.RepositorySource
- net.minecraft.server.packs.repository.ServerPacksSource
- net.minecraft.server.packs.resources.CloseableResourceManager
+ net.minecraft.server.packs.resources.FallbackResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ net.minecraft.server.packs.resources.FallbackResourceManager$EntryStack
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.FallbackResourceManager$PackEntry
- net.minecraft.server.packs.resources.FallbackResourceManager$ResourceWithSource
+ net.minecraft.server.packs.resources.IoSupplier
- net.minecraft.server.packs.resources.MultiPackResourceManager
+ net.minecraft.server.packs.resources.package-info
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$State
- net.minecraft.server.packs.resources.ReloadableResourceManager
+ net.minecraft.server.packs.resources.ReloadInstance
+ net.minecraft.server.packs.resources.Resource
- net.minecraft.server.packs.resources.ResourceFilterSection
+ net.minecraft.server.packs.resources.ResourceManager
- net.minecraft.server.packs.resources.ResourceManager$Empty
+ net.minecraft.server.packs.resources.ResourceManagerReloadListener
- net.minecraft.server.packs.resources.ResourceMetadata
+ net.minecraft.server.packs.resources.ResourceMetadata$1
- net.minecraft.server.packs.resources.ResourceMetadata$2
+ net.minecraft.server.packs.resources.ResourceMetadata$Builder
- net.minecraft.server.packs.resources.ResourceMetadata$Builder$1
+ net.minecraft.server.packs.resources.ResourceProvider
- net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
+ net.minecraft.server.packs.resources.SimplePreparableReloadListener
- net.minecraft.server.packs.resources.SimpleReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadInstance$1
- net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
+ net.minecraft.server.packs.VanillaPackResources
- net.minecraft.server.packs.VanillaPackResourcesBuilder
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$Data
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
+ net.minecraft.server.RegistryLayer
- net.minecraft.server.ReloadableServerResources
- net.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup
- net.minecraft.server.ReloadableServerResources$MissingTagAccessPolicy
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerInfo
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.ServerTickRateManager
- net.minecraft.server.Services
+ net.minecraft.server.TickTask
- net.minecraft.server.WorldLoader
+ net.minecraft.server.WorldLoader$DataLoadContext
- net.minecraft.server.WorldLoader$DataLoadOutput
+ net.minecraft.server.WorldLoader$InitConfig
- net.minecraft.server.WorldLoader$PackConfig
+ net.minecraft.server.WorldLoader$ResultFactory
- net.minecraft.server.WorldLoader$WorldDataSupplier
+ net.minecraft.server.WorldStem
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
- net.minecraft.tags.BannerPatternTags
+ net.minecraft.tags.BiomeTags
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.CatVariantTags
- net.minecraft.tags.DamageTypeTags
+ net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.FlatLevelGeneratorPresetTags
+ net.minecraft.tags.FluidTags
- net.minecraft.tags.GameEventTags
+ net.minecraft.tags.InstrumentTags
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
+ net.minecraft.tags.PaintingVariantTags
- net.minecraft.tags.PoiTypeTags
+ net.minecraft.tags.StructureTags
- net.minecraft.tags.TagBuilder
+ net.minecraft.tags.TagEntry
- net.minecraft.tags.TagEntry$Lookup
+ net.minecraft.tags.TagFile
- net.minecraft.tags.TagKey
+ net.minecraft.tags.TagLoader
- net.minecraft.tags.TagLoader$1
+ net.minecraft.tags.TagLoader$EntryWithSource
- net.minecraft.tags.TagLoader$SortingEntry
+ net.minecraft.tags.TagManager
- net.minecraft.tags.TagManager$LoadResult
+ net.minecraft.tags.TagNetworkSerialization
- net.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ net.minecraft.tags.TagNetworkSerialization$TagOutput
- net.minecraft.tags.WorldPresetTags
- net.minecraft.util.AbortableIterationConsumer
+ net.minecraft.util.AbortableIterationConsumer$Continuation
- net.minecraft.util.ArrayListDeque
+ net.minecraft.util.ArrayListDeque$DescendingIterator
- net.minecraft.util.BitStorage
+ net.minecraft.util.Brightness
- net.minecraft.util.ByIdMap
+ net.minecraft.util.ByIdMap$1
- net.minecraft.util.ByIdMap$OutOfBoundsStrategy
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.ColorRGBA
+ net.minecraft.util.CommonColors
- net.minecraft.util.CommonLinks
+ net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- net.minecraft.util.Crypt
+ net.minecraft.util.Crypt$ByteArrayToKeyFunction
- net.minecraft.util.Crypt$SaltSignaturePair
+ net.minecraft.util.Crypt$SaltSupplier
- net.minecraft.util.CryptException
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$Builder
+ net.minecraft.util.CubicSampler
- net.minecraft.util.CubicSampler$Vec3Fetcher
+ net.minecraft.util.CubicSpline
- net.minecraft.util.CubicSpline$1Point
+ net.minecraft.util.CubicSpline$Builder
- net.minecraft.util.CubicSpline$Constant
+ net.minecraft.util.CubicSpline$CoordinateVisitor
- net.minecraft.util.CubicSpline$Multipoint
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
+ net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
- net.minecraft.util.datafix.fixes.BlockRenameFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix$1
- net.minecraft.util.datafix.fixes.BlockStateData
+ net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
- net.minecraft.util.datafix.fixes.CatTypeFix
+ net.minecraft.util.datafix.fixes.CauldronRenameFix
- net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
- net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
+ net.minecraft.util.datafix.fixes.ItemBannerColorFix
- net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.ItemIdFix
- net.minecraft.util.datafix.fixes.ItemLoreFix
+ net.minecraft.util.datafix.fixes.ItemPotionFix
- net.minecraft.util.datafix.fixes.ItemRemoveBlockEntityTagFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix
- net.minecraft.util.datafix.fixes.ItemRenameFix$1
+ net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.ItemSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTagFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.JigsawPropertiesFix
- net.minecraft.util.datafix.fixes.JigsawRotationFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LegacyDragonFightFix
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.LevelLegacyWorldGenSettingsFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
+ net.minecraft.util.datafix.fixes.MissingDimensionFix
- net.minecraft.util.datafix.fixes.MobEffectIdFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NamedEntityWriteReadFix
- net.minecraft.util.datafix.fixes.NamespacedTypeRenameFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.OptionsAccessibilityOnboardFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsAmbientOcclusionFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.OverreachingTickFix
+ net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
- net.minecraft.util.datafix.fixes.PoiTypeRenameFix
+ net.minecraft.util.datafix.fixes.PrimedTntBlockStateFixer
- net.minecraft.util.datafix.fixes.RandomSequenceSettingsFix
+ net.minecraft.util.datafix.fixes.RecipesFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RemapChunkStatusFix
- net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
- net.minecraft.util.datafix.fixes.RenamedCoralFansFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFix
+ net.minecraft.util.datafix.fixes.RenameEnchantmentsFix
- net.minecraft.util.datafix.fixes.ReorganizePoi
+ net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
- net.minecraft.util.datafix.fixes.SavedDataUUIDFix
+ net.minecraft.util.datafix.fixes.ScoreboardDisplaySlotFix
- net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
+ net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
- net.minecraft.util.datafix.fixes.SpawnerDataFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
- net.minecraft.util.datafix.fixes.StatsCounterFix$StatType
+ net.minecraft.util.datafix.fixes.StatsRenameFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VariantRenameFix
+ net.minecraft.util.datafix.fixes.VillagerDataFix
- net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
+ net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
- net.minecraft.util.datafix.fixes.VillagerTradeFix
+ net.minecraft.util.datafix.fixes.WallPropertyFix
- net.minecraft.util.datafix.fixes.WeaponSmithChestLootTableFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
+ net.minecraft.util.datafix.fixes.WriteAndReadFix
- net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
- net.minecraft.util.datafix.package-info
+ net.minecraft.util.datafix.schemas.NamespacedSchema
- net.minecraft.util.datafix.schemas.NamespacedSchema$1
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
- net.minecraft.util.datafix.schemas.V1451_6$1
+ net.minecraft.util.datafix.schemas.V1451_6$2
- net.minecraft.util.datafix.schemas.V1460
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
- net.minecraft.util.datafix.schemas.V2684
+ net.minecraft.util.datafix.schemas.V2686
- net.minecraft.util.datafix.schemas.V2688
+ net.minecraft.util.datafix.schemas.V2704
- net.minecraft.util.datafix.schemas.V2707
+ net.minecraft.util.datafix.schemas.V2831
- net.minecraft.util.datafix.schemas.V2832
+ net.minecraft.util.datafix.schemas.V2842
- net.minecraft.util.datafix.schemas.V3076
+ net.minecraft.util.datafix.schemas.V3078
- net.minecraft.util.datafix.schemas.V3081
+ net.minecraft.util.datafix.schemas.V3082
- net.minecraft.util.datafix.schemas.V3083
+ net.minecraft.util.datafix.schemas.V3202
- net.minecraft.util.datafix.schemas.V3203
+ net.minecraft.util.datafix.schemas.V3204
- net.minecraft.util.datafix.schemas.V3325
+ net.minecraft.util.datafix.schemas.V3326
- net.minecraft.util.datafix.schemas.V3327
+ net.minecraft.util.datafix.schemas.V3328
- net.minecraft.util.datafix.schemas.V3438
+ net.minecraft.util.datafix.schemas.V3448
- net.minecraft.util.datafix.schemas.V3682
+ net.minecraft.util.datafix.schemas.V3683
- net.minecraft.util.datafix.schemas.V3685
+ net.minecraft.util.datafix.schemas.V3689
- net.minecraft.util.datafix.schemas.V3799
- net.minecraft.util.datafix.schemas.V3808
+ net.minecraft.util.DebugBuffer
- net.minecraft.util.debugchart.DebugSampleSubscriptionTracker
- net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
- net.minecraft.util.debugchart.RemoteDebugSampleType
- net.minecraft.util.debugchart.SampleLogger
- net.minecraft.util.DelegateDataOutput
+ net.minecraft.util.DependencySorter
- net.minecraft.util.DependencySorter$Entry
+ net.minecraft.util.DirectoryLock
- net.minecraft.util.DirectoryLock$LockException
+ net.minecraft.util.ExceptionCollector
- net.minecraft.util.ExtraCodecs
+ net.minecraft.util.ExtraCodecs$1
- net.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
+ net.minecraft.util.ExtraCodecs$2
- net.minecraft.util.ExtraCodecs$3
+ net.minecraft.util.ExtraCodecs$4
- net.minecraft.util.ExtraCodecs$5
+ net.minecraft.util.ExtraCodecs$6
- net.minecraft.util.ExtraCodecs$EitherCodec
+ net.minecraft.util.ExtraCodecs$RecursiveCodec
- net.minecraft.util.ExtraCodecs$RecursiveMapCodec
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffectUtil
- net.minecraft.world.effect.package-info
- net.minecraft.world.effect.PoisonMobEffect
+ net.minecraft.world.effect.RegenerationMobEffect
- net.minecraft.world.effect.SaturationMobEffect
+ net.minecraft.world.effect.WitherMobEffect
+ net.minecraft.world.entity.AgeableMob
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
+ net.minecraft.world.entity.ai.attributes.Attribute
- net.minecraft.world.entity.ai.attributes.AttributeInstance
+ net.minecraft.world.entity.ai.attributes.AttributeMap
- net.minecraft.world.entity.ai.attributes.AttributeModifier
+ net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
- net.minecraft.world.entity.ai.attributes.Attributes
- net.minecraft.world.entity.ai.attributes.AttributeSupplier
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
+ net.minecraft.world.entity.ai.attributes.DefaultAttributes
+ net.minecraft.world.entity.ai.attributes.package-info
- net.minecraft.world.entity.ai.attributes.RangedAttribute
- net.minecraft.world.entity.ai.behavior.AcquirePoi
+ net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
- net.minecraft.world.entity.ai.behavior.AnimalMakeLove
+ net.minecraft.world.entity.ai.behavior.AnimalPanic
- net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
+ net.minecraft.world.entity.ai.behavior.BabyFollowAdult
- net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
+ net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
- net.minecraft.world.entity.ai.behavior.Behavior
+ net.minecraft.world.entity.ai.behavior.Behavior$Status
- net.minecraft.world.entity.ai.behavior.BehaviorControl
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
- net.minecraft.world.entity.ai.behavior.Croak
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$2
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$3
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$4
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$5
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$Mu
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Mu
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWithResult
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryAccessor
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Absent
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Present
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Registered
+ net.minecraft.world.entity.ai.behavior.declarative.package-info
- net.minecraft.world.entity.ai.behavior.declarative.Trigger
+ net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
- net.minecraft.world.entity.ai.behavior.DoNothing
+ net.minecraft.world.entity.ai.behavior.EntityTracker
- net.minecraft.world.entity.ai.behavior.EraseMemoryIf
+ net.minecraft.world.entity.ai.behavior.FollowTemptation
- net.minecraft.world.entity.ai.behavior.GateBehavior
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
+ net.minecraft.world.entity.ai.behavior.GoToTargetLocation
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LongJumpMidJump
- net.minecraft.world.entity.ai.behavior.LongJumpToPreferredBlock
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
+ net.minecraft.world.entity.ai.behavior.LongJumpUtil
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.OneShot
- net.minecraft.world.entity.ai.behavior.package-info
+ net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
- net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
+ net.minecraft.world.entity.ai.behavior.PositionTracker
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
- net.minecraft.world.entity.ai.behavior.RamTarget
+ net.minecraft.world.entity.ai.behavior.RandomLookAround
- net.minecraft.world.entity.ai.behavior.RandomStroll
+ net.minecraft.world.entity.ai.behavior.ReactToBell
- net.minecraft.world.entity.ai.behavior.ResetProfession
+ net.minecraft.world.entity.ai.behavior.ResetRaidStatus
- net.minecraft.world.entity.ai.behavior.RingBell
+ net.minecraft.world.entity.ai.behavior.RunOne
- net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes$Ticker
- net.minecraft.world.entity.ai.behavior.SetHiddenState
+ net.minecraft.world.entity.ai.behavior.SetLookAndInteract
- net.minecraft.world.entity.ai.behavior.SetRaidStatus
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
+ net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
- net.minecraft.world.entity.ai.behavior.ShufflingList
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
+ net.minecraft.world.entity.ai.behavior.SleepInBed
- net.minecraft.world.entity.ai.behavior.SocializeAtBell
+ net.minecraft.world.entity.ai.behavior.StartAttacking
- net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StayCloseToTarget
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.TriggerGate
- net.minecraft.world.entity.ai.behavior.TryFindLand
+ net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
- net.minecraft.world.entity.ai.behavior.TryFindWater
+ net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
- net.minecraft.world.entity.ai.behavior.VillagerCalmDown
+ net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
- net.minecraft.world.entity.ai.behavior.VillagerMakeLove
+ net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
- net.minecraft.world.entity.ai.behavior.WakeUp
+ net.minecraft.world.entity.ai.behavior.warden.Digging
- net.minecraft.world.entity.ai.behavior.warden.Emerging
+ net.minecraft.world.entity.ai.behavior.warden.ForceUnmount
- net.minecraft.world.entity.ai.behavior.warden.package-info
- net.minecraft.world.entity.ai.behavior.warden.Roar
+ net.minecraft.world.entity.ai.behavior.warden.SetRoarTarget
- net.minecraft.world.entity.ai.behavior.warden.SetWardenLookTarget
+ net.minecraft.world.entity.ai.behavior.warden.Sniffing
- net.minecraft.world.entity.ai.behavior.warden.SonicBoom
+ net.minecraft.world.entity.ai.behavior.warden.TryToSniff
+ net.minecraft.world.entity.ai.behavior.WorkAtComposter
- net.minecraft.world.entity.ai.behavior.WorkAtPoi
+ net.minecraft.world.entity.ai.behavior.YieldJobSite
+ net.minecraft.world.entity.ai.Brain
- net.minecraft.world.entity.ai.Brain$1
+ net.minecraft.world.entity.ai.Brain$MemoryValue
- net.minecraft.world.entity.ai.Brain$Provider
+ net.minecraft.world.entity.ai.control.BodyRotationControl
- net.minecraft.world.entity.ai.control.Control
+ net.minecraft.world.entity.ai.control.FlyingMoveControl
- net.minecraft.world.entity.ai.control.JumpControl
+ net.minecraft.world.entity.ai.control.LookControl
- net.minecraft.world.entity.ai.control.MoveControl
+ net.minecraft.world.entity.ai.control.MoveControl$Operation
- net.minecraft.world.entity.ai.control.package-info
- net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
+ net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
+ net.minecraft.world.entity.ai.goal.AvoidEntityGoal
- net.minecraft.world.entity.ai.goal.BegGoal
+ net.minecraft.world.entity.ai.goal.BoatGoals
- net.minecraft.world.entity.ai.goal.BreakDoorGoal
+ net.minecraft.world.entity.ai.goal.BreathAirGoal
- net.minecraft.world.entity.ai.goal.BreedGoal
+ net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
- net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
+ net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
- net.minecraft.world.entity.ai.goal.DolphinJumpGoal
+ net.minecraft.world.entity.ai.goal.DoorInteractGoal
- net.minecraft.world.entity.ai.goal.EatBlockGoal
+ net.minecraft.world.entity.ai.goal.FleeSunGoal
- net.minecraft.world.entity.ai.goal.FloatGoal
+ net.minecraft.world.entity.ai.goal.FollowBoatGoal
- net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
+ net.minecraft.world.entity.ai.goal.FollowMobGoal
- net.minecraft.world.entity.ai.goal.FollowOwnerGoal
+ net.minecraft.world.entity.ai.goal.FollowParentGoal
- net.minecraft.world.entity.ai.goal.Goal
+ net.minecraft.world.entity.ai.goal.Goal$Flag
- net.minecraft.world.entity.ai.goal.GoalSelector
+ net.minecraft.world.entity.ai.goal.GoalSelector$1
- net.minecraft.world.entity.ai.goal.GoalSelector$2
+ net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
- net.minecraft.world.entity.ai.goal.InteractGoal
+ net.minecraft.world.entity.ai.goal.JumpGoal
- net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
+ net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
- net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
+ net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
- net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
+ net.minecraft.world.entity.ai.goal.MeleeAttackGoal
- net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStandGoal
- net.minecraft.world.entity.ai.goal.RandomStrollGoal
+ net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
- net.minecraft.world.entity.ai.goal.RangedAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- net.minecraft.world.entity.ai.goal.RemoveBlockGoal
+ net.minecraft.world.entity.ai.goal.RestrictSunGoal
- net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
+ net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
- net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.SwellGoal
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
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.AmphibiousPathNavigation
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.BreezeAttackEntitySensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.IsInWaterSensor
- net.minecraft.world.entity.ai.sensing.MobSensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.package-info
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
+ net.minecraft.world.entity.ai.sensing.WardenEntitySensor
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
+ net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiSection
+ net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.poi.PoiTypes
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.allay.Allay
+ net.minecraft.world.entity.animal.allay.Allay$JukeboxListener
- net.minecraft.world.entity.animal.allay.Allay$VibrationUser
+ net.minecraft.world.entity.animal.allay.AllayAi
- net.minecraft.world.entity.animal.allay.package-info
+ net.minecraft.world.entity.animal.Animal
+ net.minecraft.world.entity.animal.armadillo.Armadillo
- net.minecraft.world.entity.animal.armadillo.Armadillo$1
+ net.minecraft.world.entity.animal.armadillo.Armadillo$2
- net.minecraft.world.entity.animal.armadillo.Armadillo$ArmadilloState
+ net.minecraft.world.entity.animal.armadillo.ArmadilloAi
- net.minecraft.world.entity.animal.armadillo.ArmadilloAi$1
+ net.minecraft.world.entity.animal.armadillo.ArmadilloAi$ArmadilloBallUp
- net.minecraft.world.entity.animal.armadillo.ArmadilloAi$ArmadilloPanic
+ net.minecraft.world.entity.animal.armadillo.package-info
- net.minecraft.world.entity.animal.axolotl.Axolotl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
+ net.minecraft.world.entity.animal.axolotl.AxolotlAi
- net.minecraft.world.entity.animal.axolotl.package-info
- net.minecraft.world.entity.animal.axolotl.PlayDead
+ net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
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
+ net.minecraft.world.entity.animal.camel.Camel
- net.minecraft.world.entity.animal.camel.Camel$CamelBodyRotationControl
+ net.minecraft.world.entity.animal.camel.Camel$CamelLookControl
- net.minecraft.world.entity.animal.camel.Camel$CamelMoveControl
+ net.minecraft.world.entity.animal.camel.CamelAi
- net.minecraft.world.entity.animal.camel.CamelAi$CamelPanic
+ net.minecraft.world.entity.animal.camel.CamelAi$RandomSitting
- net.minecraft.world.entity.animal.camel.package-info
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.CatVariant
- net.minecraft.world.entity.animal.Chicken
+ net.minecraft.world.entity.animal.Cod
- net.minecraft.world.entity.animal.Cow
+ net.minecraft.world.entity.animal.Dolphin
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
+ net.minecraft.world.entity.animal.FlyingAnimal
- net.minecraft.world.entity.animal.Fox
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
+ net.minecraft.world.entity.animal.frog.Frog
- net.minecraft.world.entity.animal.frog.Frog$FrogLookControl
+ net.minecraft.world.entity.animal.frog.Frog$FrogNodeEvaluator
- net.minecraft.world.entity.animal.frog.Frog$FrogPathNavigation
+ net.minecraft.world.entity.animal.frog.FrogAi
+ net.minecraft.world.entity.animal.frog.package-info
- net.minecraft.world.entity.animal.frog.ShootTongue
+ net.minecraft.world.entity.animal.frog.ShootTongue$1
- net.minecraft.world.entity.animal.frog.ShootTongue$State
+ net.minecraft.world.entity.animal.frog.Tadpole
- net.minecraft.world.entity.animal.frog.TadpoleAi
+ net.minecraft.world.entity.animal.FrogVariant
- net.minecraft.world.entity.animal.goat.Goat
+ net.minecraft.world.entity.animal.goat.GoatAi
- net.minecraft.world.entity.animal.goat.package-info
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
+ net.minecraft.world.entity.animal.horse.AbstractHorse
- net.minecraft.world.entity.animal.horse.AbstractHorse$1
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
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
+ net.minecraft.world.entity.animal.Parrot$Variant
- net.minecraft.world.entity.animal.Pig
+ net.minecraft.world.entity.animal.PolarBear
- net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
- net.minecraft.world.entity.animal.Pufferfish
+ net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
- net.minecraft.world.entity.animal.Rabbit
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Rabbit$Variant
- net.minecraft.world.entity.animal.Salmon
+ net.minecraft.world.entity.animal.Sheep
- net.minecraft.world.entity.animal.Sheep$1
+ net.minecraft.world.entity.animal.Sheep$2
- net.minecraft.world.entity.animal.ShoulderRidingEntity
+ net.minecraft.world.entity.animal.SnowGolem
- net.minecraft.world.entity.animal.Squid
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
- net.minecraft.world.entity.animal.TropicalFish$Base
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.TropicalFish$Variant
- net.minecraft.world.entity.animal.Turtle
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
+ net.minecraft.world.entity.animal.Wolf$WolfPanicGoal
+ net.minecraft.world.entity.AnimationState
- net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.Attackable
- net.minecraft.world.entity.Display
+ net.minecraft.world.entity.Display$1
- net.minecraft.world.entity.Display$BillboardConstraints
+ net.minecraft.world.entity.Display$BlockDisplay
- net.minecraft.world.entity.Display$BlockDisplay$BlockRenderState
+ net.minecraft.world.entity.Display$ColorInterpolator
- net.minecraft.world.entity.Display$FloatInterpolator
+ net.minecraft.world.entity.Display$GenericInterpolator
- net.minecraft.world.entity.Display$IntInterpolator
+ net.minecraft.world.entity.Display$ItemDisplay
- net.minecraft.world.entity.Display$ItemDisplay$1
+ net.minecraft.world.entity.Display$ItemDisplay$ItemRenderState
- net.minecraft.world.entity.Display$LinearFloatInterpolator
+ net.minecraft.world.entity.Display$LinearIntInterpolator
- net.minecraft.world.entity.Display$PosRotInterpolationTarget
+ net.minecraft.world.entity.Display$RenderState
- net.minecraft.world.entity.Display$TextDisplay
+ net.minecraft.world.entity.Display$TextDisplay$Align
- net.minecraft.world.entity.Display$TextDisplay$CachedInfo
+ net.minecraft.world.entity.Display$TextDisplay$CachedLine
- net.minecraft.world.entity.Display$TextDisplay$LineSplitter
+ net.minecraft.world.entity.Display$TextDisplay$TextRenderState
- net.minecraft.world.entity.Display$TransformationInterpolator
+ net.minecraft.world.entity.Entity
- net.minecraft.world.entity.Entity$1
+ net.minecraft.world.entity.Entity$MoveFunction
- net.minecraft.world.entity.Entity$MovementEmission
+ net.minecraft.world.entity.Entity$RemovalReason
- net.minecraft.world.entity.EntityAttachment
+ net.minecraft.world.entity.EntityAttachment$Fallback
- net.minecraft.world.entity.EntityAttachments
+ net.minecraft.world.entity.EntityAttachments$Builder
- net.minecraft.world.entity.EntityDimensions
+ net.minecraft.world.entity.EntityEvent
- net.minecraft.world.entity.EntitySelector
+ net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- net.minecraft.world.entity.EntityType
+ net.minecraft.world.entity.EntityType$1
- net.minecraft.world.entity.EntityType$Builder
+ net.minecraft.world.entity.EntityType$EntityFactory
- net.minecraft.world.entity.EquipmentSlot
+ net.minecraft.world.entity.EquipmentSlot$Type
- net.minecraft.world.entity.ExperienceOrb
+ net.minecraft.world.entity.FlyingMob
- net.minecraft.world.entity.GlowSquid
+ net.minecraft.world.entity.HasCustomInventoryScreen
- net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.Interaction
- net.minecraft.world.entity.Interaction$PlayerAction
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.LerpingModel
- net.minecraft.world.entity.LightningBolt
+ net.minecraft.world.entity.LivingEntity
- net.minecraft.world.entity.LivingEntity$1
+ net.minecraft.world.entity.LivingEntity$Fallsounds
- net.minecraft.world.entity.Marker
+ net.minecraft.world.entity.Mob
- net.minecraft.world.entity.Mob$1
+ net.minecraft.world.entity.MobCategory
- net.minecraft.world.entity.MobSpawnType
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.RelativeMovement
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.Saddleable
- net.minecraft.world.entity.Shearable
+ net.minecraft.world.entity.SlotAccess
- net.minecraft.world.entity.SlotAccess$1
+ net.minecraft.world.entity.SlotAccess$2
- net.minecraft.world.entity.SlotAccess$3
+ net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacementType
+ net.minecraft.world.entity.SpawnPlacementTypes
- net.minecraft.world.entity.SpawnPlacementTypes$1
- net.minecraft.world.entity.TamableAnimal
+ net.minecraft.world.entity.Targeting
- net.minecraft.world.entity.TraceableEntity
+ net.minecraft.world.entity.VariantHolder
- net.minecraft.world.entity.WalkAnimationState
- net.minecraft.world.item.ArmorItem$2
+ net.minecraft.world.item.ArmorItem$Type
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.DyeableAnimalArmorItem
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BannerPatterns
- net.minecraft.world.level.block.entity.BarrelBlockEntity
+ net.minecraft.world.level.block.entity.BarrelBlockEntity$1
- net.minecraft.world.level.block.entity.BaseContainerBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity$1
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
- net.minecraft.world.level.block.entity.BedBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity
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
- net.minecraft.world.level.block.entity.BrushableBlockEntity
+ net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity
- net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.ChestLidController
+ net.minecraft.world.level.block.entity.ChiseledBookShelfBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.CrafterBlockEntity
+ net.minecraft.world.level.block.entity.CrafterBlockEntity$1
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DecoratedPotBlockEntity
- net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$Decorations
+ net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$WobbleStyle
- net.minecraft.world.level.block.entity.DecoratedPotPatterns
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.HangingSignBlockEntity
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
- net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
+ net.minecraft.world.level.block.entity.SculkCatalystBlockEntity$CatalystListener
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity$VibrationUser
- net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
+ net.minecraft.world.level.block.entity.SculkShriekerBlockEntity$VibrationUser
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ net.minecraft.world.level.block.entity.SignBlockEntity
- net.minecraft.world.level.block.entity.SignText
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SkullBlockEntity$1
+ net.minecraft.world.level.block.entity.SmokerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.entity.trialspawner.PlayerDetector
- net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector$1
- net.minecraft.world.level.block.entity.TrialSpawnerBlockEntity
- net.minecraft.world.level.block.entity.vault.package-info
- net.minecraft.world.level.block.entity.vault.VaultBlockEntity
- net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Server
- net.minecraft.world.level.block.entity.vault.VaultConfig
- net.minecraft.world.level.block.entity.vault.VaultSharedData
- net.minecraft.world.level.block.entity.vault.VaultState$1
- net.minecraft.world.level.block.entity.vault.VaultState$3
- net.minecraft.world.level.block.entity.vault.VaultState$5
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.TreeGrower
+ net.minecraft.world.level.block.package-info
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
+ net.minecraft.world.level.block.state.BlockBehaviour
- net.minecraft.world.level.block.state.BlockBehaviour$1
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetFunction
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
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockSetType
+ net.minecraft.world.level.block.state.properties.BlockSetType$PressurePlateSensitivity
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ChestType$1
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.DripstoneThickness
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument$Type
+ net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.PistonType
+ net.minecraft.world.level.block.state.properties.Property
- net.minecraft.world.level.block.state.properties.Property$Value
+ net.minecraft.world.level.block.state.properties.RailShape
- net.minecraft.world.level.block.state.properties.RedstoneSide
+ net.minecraft.world.level.block.state.properties.RotationSegment
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
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallHangingSignBlock
- net.minecraft.world.level.block.WallHangingSignBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WaterloggedTransparentBlock
- net.minecraft.world.level.block.WeatheringCopper
+ net.minecraft.world.level.block.WeatheringCopper$WeatherState
- net.minecraft.world.level.block.WeatheringCopperBulbBlock
+ net.minecraft.world.level.block.WeatheringCopperDoorBlock
- net.minecraft.world.level.block.WeatheringCopperFullBlock
+ net.minecraft.world.level.block.WeatheringCopperGrateBlock
- net.minecraft.world.level.block.WeatheringCopperSlabBlock
+ net.minecraft.world.level.block.WeatheringCopperStairBlock
- net.minecraft.world.level.block.WeatheringCopperTrapDoorBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeepingVinesBlock
+ net.minecraft.world.level.block.WeepingVinesPlantBlock
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.border.BorderChangeListener
+ net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
- net.minecraft.world.level.border.BorderStatus
- net.minecraft.world.level.border.package-info
+ net.minecraft.world.level.border.WorldBorder
- net.minecraft.world.level.border.WorldBorder$BorderExtent
+ net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
- net.minecraft.world.level.border.WorldBorder$Settings
+ net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
+ net.minecraft.world.level.chunk.BlockColumn
- net.minecraft.world.level.chunk.BulkSectionAccess
+ net.minecraft.world.level.chunk.CarvingMask
- net.minecraft.world.level.chunk.CarvingMask$Mask
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkAccess$TicksToSave
+ net.minecraft.world.level.chunk.ChunkGenerator
+ net.minecraft.world.level.chunk.ChunkGenerators
- net.minecraft.world.level.chunk.ChunkGeneratorStructureState
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.GlobalPalette
+ net.minecraft.world.level.chunk.HashMapPalette
- net.minecraft.world.level.chunk.ImposterProtoChunk
+ net.minecraft.world.level.chunk.LevelChunk
- net.minecraft.world.level.chunk.LevelChunk$1
+ net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
- net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
+ net.minecraft.world.level.chunk.LevelChunk$PostLoadProcessor
- net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ net.minecraft.world.level.chunk.LevelChunkSection
- net.minecraft.world.level.chunk.LevelChunkSection$1BlockCounter
+ net.minecraft.world.level.chunk.LightChunk
- net.minecraft.world.level.chunk.LightChunkGetter
+ net.minecraft.world.level.chunk.LinearPalette
- net.minecraft.world.level.chunk.MissingPaletteEntryException
+ net.minecraft.world.level.chunk.package-info
+ net.minecraft.world.level.chunk.Palette
- net.minecraft.world.level.chunk.Palette$Factory
- net.minecraft.world.level.chunk.PalettedContainer
+ net.minecraft.world.level.chunk.PalettedContainer$Configuration
- net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
+ net.minecraft.world.level.chunk.PalettedContainer$Data
- net.minecraft.world.level.chunk.PalettedContainer$Strategy
+ net.minecraft.world.level.chunk.PalettedContainer$Strategy$1
- net.minecraft.world.level.chunk.PalettedContainer$Strategy$2
+ net.minecraft.world.level.chunk.PalettedContainerRO
- net.minecraft.world.level.chunk.PalettedContainerRO$PackedData
+ net.minecraft.world.level.chunk.PalettedContainerRO$Unpacker
+ net.minecraft.world.level.chunk.PaletteResize
- net.minecraft.world.level.chunk.ProtoChunk
+ net.minecraft.world.level.chunk.SingleValuePalette
- net.minecraft.world.level.chunk.storage.ChunkScanAccess
+ net.minecraft.world.level.chunk.storage.ChunkSerializer
- net.minecraft.world.level.chunk.storage.ChunkStorage
+ net.minecraft.world.level.chunk.storage.EntityStorage
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.IOWorker$Priority
- net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RecreatingChunkStorage
- net.minecraft.world.level.chunk.storage.RecreatingSimpleRegionStorage
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.SectionStorage
+ net.minecraft.world.level.chunk.storage.SimpleRegionStorage
- net.minecraft.world.level.chunk.StructureAccess
+ net.minecraft.world.level.chunk.UpgradeData
- net.minecraft.world.level.chunk.UpgradeData$BlockFixer
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.dimension.BuiltinDimensionTypes
- net.minecraft.world.level.dimension.DimensionDefaults
+ net.minecraft.world.level.dimension.DimensionType
- net.minecraft.world.level.dimension.DimensionType$MonsterSettings
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
- net.minecraft.world.level.dimension.end.EndDragonFight
+ net.minecraft.world.level.dimension.end.EndDragonFight$Data
- net.minecraft.world.level.dimension.end.package-info
+ net.minecraft.world.level.dimension.LevelStem
+ net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.entity.ChunkEntities
+ net.minecraft.world.level.entity.ChunkStatusUpdateListener
- net.minecraft.world.level.entity.EntityAccess
+ net.minecraft.world.level.entity.EntityInLevelCallback
- net.minecraft.world.level.entity.EntityInLevelCallback$1
+ net.minecraft.world.level.entity.EntityLookup
- net.minecraft.world.level.entity.EntityPersistentStorage
+ net.minecraft.world.level.entity.EntitySection
- net.minecraft.world.level.entity.EntitySectionStorage
+ net.minecraft.world.level.entity.EntityTickList
- net.minecraft.world.level.entity.EntityTypeTest
+ net.minecraft.world.level.entity.EntityTypeTest$1
- net.minecraft.world.level.entity.EntityTypeTest$2
+ net.minecraft.world.level.entity.LevelCallback
- net.minecraft.world.level.entity.LevelEntityGetter
+ net.minecraft.world.level.entity.LevelEntityGetterAdapter
- net.minecraft.world.level.entity.package-info
- net.minecraft.world.level.entity.PersistentEntitySectionManager
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
- net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
+ net.minecraft.world.level.entity.TransientEntitySectionManager
- net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
+ net.minecraft.world.level.entity.Visibility
+ net.minecraft.world.level.gameevent.BlockPositionSource
- net.minecraft.world.level.gameevent.BlockPositionSource$Type
+ net.minecraft.world.level.gameevent.DynamicGameEventListener
- net.minecraft.world.level.gameevent.EntityPositionSource
+ net.minecraft.world.level.gameevent.EntityPositionSource$Type
- net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
+ net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
- net.minecraft.world.level.gameevent.GameEvent
+ net.minecraft.world.level.gameevent.GameEvent$Context
- net.minecraft.world.level.gameevent.GameEvent$ListenerInfo
+ net.minecraft.world.level.gameevent.GameEventDispatcher
- net.minecraft.world.level.gameevent.GameEventListener
+ net.minecraft.world.level.gameevent.GameEventListener$DeliveryMode
- net.minecraft.world.level.gameevent.GameEventListener$Provider
+ net.minecraft.world.level.gameevent.GameEventListenerRegistry
- net.minecraft.world.level.gameevent.GameEventListenerRegistry$1
+ net.minecraft.world.level.gameevent.GameEventListenerRegistry$ListenerVisitor
- net.minecraft.world.level.gameevent.package-info
- net.minecraft.world.level.gameevent.PositionSource
+ net.minecraft.world.level.gameevent.PositionSourceType
- net.minecraft.world.level.gameevent.vibrations.package-info
+ net.minecraft.world.level.gameevent.vibrations.VibrationInfo
- net.minecraft.world.level.gameevent.vibrations.VibrationSelector
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Data
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Listener
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Ticker
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$User
+ net.minecraft.world.level.levelgen.Aquifer
- net.minecraft.world.level.levelgen.Aquifer$1
+ net.minecraft.world.level.levelgen.Aquifer$FluidPicker
- net.minecraft.world.level.levelgen.Aquifer$FluidStatus
+ net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
- net.minecraft.world.level.levelgen.Beardifier
+ net.minecraft.world.level.levelgen.Beardifier$1
- net.minecraft.world.level.levelgen.Beardifier$Rigid
+ net.minecraft.world.level.levelgen.BelowZeroRetrogen
- net.minecraft.world.level.levelgen.BelowZeroRetrogen$1
+ net.minecraft.world.level.levelgen.BitRandomSource
- net.minecraft.world.level.levelgen.blending.Blender
+ net.minecraft.world.level.levelgen.blending.Blender$1
- net.minecraft.world.level.levelgen.blending.Blender$BlendingOutput
+ net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
- net.minecraft.world.level.levelgen.blending.Blender$DistanceGetter
+ net.minecraft.world.level.levelgen.blending.BlendingData
- net.minecraft.world.level.levelgen.blending.BlendingData$BiomeConsumer
+ net.minecraft.world.level.levelgen.blending.BlendingData$DensityConsumer
- net.minecraft.world.level.levelgen.blending.BlendingData$HeightConsumer
+ net.minecraft.world.level.levelgen.blending.package-info
- net.minecraft.world.level.levelgen.blockpredicates.AllOfPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.AnyOfPredicate
- net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.BlockPredicateType
- net.minecraft.world.level.levelgen.blockpredicates.CombiningPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.HasSturdyFacePredicate
- net.minecraft.world.level.levelgen.blockpredicates.InsideWorldBoundsPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingBlocksPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingBlockTagPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingFluidsPredicate
- net.minecraft.world.level.levelgen.blockpredicates.NotPredicate
- net.minecraft.world.level.levelgen.blockpredicates.package-info
+ net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
- net.minecraft.world.level.levelgen.blockpredicates.SolidPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.StateTestingPredicate
- net.minecraft.world.level.levelgen.blockpredicates.TrueBlockPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.WouldSurvivePredicate
+ net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
- net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.CarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CarverDebugSettings
- net.minecraft.world.level.levelgen.carver.CarvingContext
+ net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration
- net.minecraft.world.level.levelgen.carver.CaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
- net.minecraft.world.level.levelgen.carver.NetherWorldCarver
+ net.minecraft.world.level.levelgen.carver.package-info
+ net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.carver.WorldCarver$CarveSkipChecker
- net.minecraft.world.level.levelgen.Column
+ net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Range
+ net.minecraft.world.level.levelgen.Column$Ray
- net.minecraft.world.level.levelgen.DebugLevelSource
+ net.minecraft.world.level.levelgen.Density
- net.minecraft.world.level.levelgen.DensityFunction
+ net.minecraft.world.level.levelgen.DensityFunction$ContextProvider
- net.minecraft.world.level.levelgen.DensityFunction$FunctionContext
+ net.minecraft.world.level.levelgen.DensityFunction$NoiseHolder
- net.minecraft.world.level.levelgen.DensityFunction$SimpleFunction
+ net.minecraft.world.level.levelgen.DensityFunction$SinglePointContext
- net.minecraft.world.level.levelgen.DensityFunction$Visitor
+ net.minecraft.world.level.levelgen.DensityFunctions
- net.minecraft.world.level.levelgen.DensityFunctions$1
+ net.minecraft.world.level.levelgen.DensityFunctions$Ap2
- net.minecraft.world.level.levelgen.DensityFunctions$BeardifierMarker
+ net.minecraft.world.level.levelgen.DensityFunctions$BeardifierOrMarker
- net.minecraft.world.level.levelgen.DensityFunctions$BlendAlpha
+ net.minecraft.world.level.levelgen.DensityFunctions$BlendDensity
- net.minecraft.world.level.levelgen.DensityFunctions$BlendOffset
+ net.minecraft.world.level.levelgen.DensityFunctions$Clamp
- net.minecraft.world.level.levelgen.DensityFunctions$Constant
+ net.minecraft.world.level.levelgen.DensityFunctions$EndIslandDensityFunction
- net.minecraft.world.level.levelgen.DensityFunctions$HolderHolder
+ net.minecraft.world.level.levelgen.DensityFunctions$Mapped
- net.minecraft.world.level.levelgen.DensityFunctions$Mapped$Type
+ net.minecraft.world.level.levelgen.DensityFunctions$Marker
- net.minecraft.world.level.levelgen.DensityFunctions$Marker$Type
+ net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked
- net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd
+ net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd$Type
- net.minecraft.world.level.levelgen.DensityFunctions$Noise
+ net.minecraft.world.level.levelgen.DensityFunctions$PureTransformer
- net.minecraft.world.level.levelgen.DensityFunctions$RangeChoice
+ net.minecraft.world.level.levelgen.DensityFunctions$Shift
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftA
+ net.minecraft.world.level.levelgen.DensityFunctions$ShiftB
+ net.minecraft.world.level.levelgen.DensityFunctions$ShiftedNoise
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftNoise
- net.minecraft.world.level.levelgen.DensityFunctions$Spline
+ net.minecraft.world.level.levelgen.DensityFunctions$Spline$Coordinate
- net.minecraft.world.level.levelgen.DensityFunctions$Spline$Point
+ net.minecraft.world.level.levelgen.DensityFunctions$TransformerWithContext
- net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler
+ net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- net.minecraft.world.level.levelgen.DensityFunctions$YClampedGradient
- net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
- net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
+ net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
- net.minecraft.world.level.levelgen.feature.BlockBlobFeature
+ net.minecraft.world.level.levelgen.feature.BlockColumnFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
+ net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration$Layer
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MultifaceGrowthConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SculkPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DeltaFeature
- net.minecraft.world.level.levelgen.feature.DesertWellFeature
+ net.minecraft.world.level.levelgen.feature.DiskFeature
- net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
+ net.minecraft.world.level.levelgen.feature.DripstoneUtils
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPodiumFeature
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker$1
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$FeatureData
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker$LevelData
- net.minecraft.world.level.levelgen.feature.FeaturePlaceContext
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.CherryFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageSetter
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.FossilFeature
+ net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.GeodeFeature
+ net.minecraft.world.level.levelgen.feature.GlowstoneFeature
- net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
+ net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
- net.minecraft.world.level.levelgen.feature.HugeFungusFeature
+ net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
+ net.minecraft.world.level.levelgen.feature.IcebergFeature
- net.minecraft.world.level.levelgen.feature.IceSpikeFeature
- net.minecraft.world.level.levelgen.feature.KelpFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature$Configuration
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
- net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
+ net.minecraft.world.level.levelgen.feature.MultifaceGrowthFeature
- net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
+ net.minecraft.world.level.levelgen.feature.NoOpFeature
- net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.rootplacers.AboveRootPlacement
+ net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacement
- net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacer
+ net.minecraft.world.level.levelgen.feature.rootplacers.package-info
+ net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacer
- net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacerType
+ net.minecraft.world.level.levelgen.feature.RootSystemFeature
- net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
+ net.minecraft.world.level.levelgen.feature.SculkPatchFeature
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
- net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RuleBasedBlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RuleBasedBlockStateProvider$Rule
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.AttachedToLeavesDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator$Context
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.feature.TreeFeature$1
+ net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.CherryTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
- net.minecraft.world.level.levelgen.feature.trunkplacers.UpwardsBranchingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
+ net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPreset
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
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
- net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
- net.minecraft.world.level.levelgen.heightproviders.HeightProvider
+ net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
- net.minecraft.world.level.levelgen.heightproviders.package-info
- net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
+ net.minecraft.world.level.levelgen.heightproviders.UniformHeight
- net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.WeightedListHeight
+ net.minecraft.world.level.levelgen.LegacyRandomSource
- net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
+ net.minecraft.world.level.levelgen.material.MaterialRuleList
+ net.minecraft.world.level.levelgen.material.package-info
- net.minecraft.world.level.levelgen.material.WorldGenMaterialRule
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseChunk
- net.minecraft.world.level.levelgen.NoiseChunk$1
+ net.minecraft.world.level.levelgen.NoiseChunk$2
- net.minecraft.world.level.levelgen.NoiseChunk$BlendAlpha
+ net.minecraft.world.level.levelgen.NoiseChunk$BlendOffset
- net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
+ net.minecraft.world.level.levelgen.NoiseChunk$Cache2D
- net.minecraft.world.level.levelgen.NoiseChunk$CacheAllInCell
+ net.minecraft.world.level.levelgen.NoiseChunk$CacheOnce
- net.minecraft.world.level.levelgen.NoiseChunk$FlatCache
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
+ net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseRouter
+ net.minecraft.world.level.levelgen.NoiseRouterData
- net.minecraft.world.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
- net.minecraft.world.level.levelgen.Noises
+ net.minecraft.world.level.levelgen.NoiseSettings
+ net.minecraft.world.level.levelgen.OreVeinifier
- net.minecraft.world.level.levelgen.OreVeinifier$VeinType
- net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.placement.BiomeFilter
- net.minecraft.world.level.levelgen.placement.BlockPredicateFilter
+ net.minecraft.world.level.levelgen.placement.CarvingMaskPlacement
- net.minecraft.world.level.levelgen.placement.CaveSurface
+ net.minecraft.world.level.levelgen.placement.CountOnEveryLayerPlacement
- net.minecraft.world.level.levelgen.placement.CountPlacement
+ net.minecraft.world.level.levelgen.placement.EnvironmentScanPlacement
+ net.minecraft.world.level.levelgen.placement.HeightmapPlacement
- net.minecraft.world.level.levelgen.placement.HeightRangePlacement
- net.minecraft.world.level.levelgen.placement.InSquarePlacement
+ net.minecraft.world.level.levelgen.placement.NoiseBasedCountPlacement
- net.minecraft.world.level.levelgen.placement.NoiseThresholdCountPlacement
+ net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.PlacedFeature
- net.minecraft.world.level.levelgen.placement.PlacementContext
+ net.minecraft.world.level.levelgen.placement.PlacementFilter
- net.minecraft.world.level.levelgen.placement.PlacementModifier
+ net.minecraft.world.level.levelgen.placement.PlacementModifierType
- net.minecraft.world.level.levelgen.placement.RandomOffsetPlacement
+ net.minecraft.world.level.levelgen.placement.RarityFilter
- net.minecraft.world.level.levelgen.placement.RepeatingPlacement
+ net.minecraft.world.level.levelgen.placement.SurfaceRelativeThresholdFilter
- net.minecraft.world.level.levelgen.placement.SurfaceWaterDepthFilter
+ net.minecraft.world.level.levelgen.PositionalRandomFactory
+ net.minecraft.world.level.levelgen.presets.package-info
- net.minecraft.world.level.levelgen.presets.WorldPreset
+ net.minecraft.world.level.levelgen.presets.WorldPresets
- net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
- net.minecraft.world.level.levelgen.RandomState
+ net.minecraft.world.level.levelgen.RandomState$1
- net.minecraft.world.level.levelgen.RandomState$1NoiseWiringHelper
+ net.minecraft.world.level.levelgen.RandomSupport
- net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
+ net.minecraft.world.level.levelgen.SingleThreadedRandomSource
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuiltinStructures
- net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.pieces.package-info
- net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator$Context
- net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier$Context
- net.minecraft.world.level.levelgen.structure.pieces.PiecesContainer
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePiecesBuilder
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceSerializationContext
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$ContextlessType
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$StructureTemplateType
+ net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.package-info
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReducer
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
- net.minecraft.world.level.levelgen.structure.pools.alias.Direct
- net.minecraft.world.level.levelgen.structure.pools.alias.package-info
+ net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBinding
- net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBindings
+ net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasLookup
- net.minecraft.world.level.levelgen.structure.pools.alias.Random
+ net.minecraft.world.level.levelgen.structure.pools.alias.RandomGroup
+ net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
- net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
+ net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
- net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.package-info
+ net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.StructurePoolElementType
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
+ net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure
+ net.minecraft.world.level.levelgen.structure.SinglePieceStructure$PieceConstructor
- net.minecraft.world.level.levelgen.structure.Structure
+ net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
- net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
+ net.minecraft.world.level.levelgen.structure.Structure$StructureSettings
- net.minecraft.world.level.levelgen.structure.StructureCheck
+ net.minecraft.world.level.levelgen.structure.StructureCheckResult
- net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
+ net.minecraft.world.level.levelgen.structure.StructurePiece
- net.minecraft.world.level.levelgen.structure.StructurePiece$1
+ net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
- net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces
+ net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure
+ net.minecraft.world.level.levelgen.structure.structures.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.structures.DesertPyramidStructure
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$2
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$3
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$4
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$EndCityPiece
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$SectionGenerator
- net.minecraft.world.level.levelgen.structure.structures.EndCityStructure
+ net.minecraft.world.level.levelgen.structure.structures.IglooPieces
- net.minecraft.world.level.levelgen.structure.structures.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.structures.IglooStructure
- net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
+ net.minecraft.world.level.levelgen.structure.structures.JigsawStructure$1
- net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece
+ net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.structures.JungleTempleStructure
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCrossing
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftRoom
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure$Type
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$1
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeCrossing
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeStraight
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleStalkRoom
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$NetherBridgePiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressStructure
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces
+ net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces$NetherFossilPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilStructure
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$1
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$OceanRuinPiece
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure$Type
+ net.minecraft.world.level.levelgen.structure.structures.package-info
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$Properties
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$VerticalPlacement
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure$Setup
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces
+ net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckStructure
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$2
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$3
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$ChestCorridor
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FillerCorridor
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FiveCrossing
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$LeftTurn
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Library
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PortalRoom
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PrisonHall
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RightTurn
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$SmoothStoneSelector
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StairsDown
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Straight
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StraightStairsDown
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Turn
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdStructure
- net.minecraft.world.level.levelgen.structure.structures.SwampHutPiece
+ net.minecraft.world.level.levelgen.structure.structures.SwampHutStructure
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionStructure
+ net.minecraft.world.level.levelgen.structure.StructureSet
- net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureType
+ net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
- net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.CappedProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
- net.minecraft.world.level.levelgen.structure.templatesystem.ProtectedBlockProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendLoot
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendStatic
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.Clear
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.Passthrough
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.RuleBlockEntityModifier
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.RuleBlockEntityModifierType
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$InputStreamOpener
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$Source
+ net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
- net.minecraft.world.level.levelgen.structure.TerrainAdjustment
- net.minecraft.world.level.levelgen.SurfaceRules
+ net.minecraft.world.level.levelgen.SurfaceRules$AbovePreliminarySurface
- net.minecraft.world.level.levelgen.SurfaceRules$Bandlands
+ net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$BlockRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$Condition
+ net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$Context
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$HoleCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Hole
- net.minecraft.world.level.levelgen.SurfaceRules$LazyCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyXZCondition
- net.minecraft.world.level.levelgen.SurfaceRules$LazyYCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NotCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$SequenceRule
+ net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$StateRule
+ net.minecraft.world.level.levelgen.SurfaceRules$Steep
- net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck
+ net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
- net.minecraft.world.level.levelgen.SurfaceRules$SurfaceRule
+ net.minecraft.world.level.levelgen.SurfaceRules$Temperature
- net.minecraft.world.level.levelgen.SurfaceRules$TestRule
+ net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
- net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
- net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource$1YCondition
- net.minecraft.world.level.levelgen.SurfaceSystem
+ net.minecraft.world.level.levelgen.SurfaceSystem$1
- net.minecraft.world.level.levelgen.synth.BlendedNoise
+ net.minecraft.world.level.levelgen.synth.ImprovedNoise
- net.minecraft.world.level.levelgen.synth.NoiseUtils
+ net.minecraft.world.level.levelgen.synth.NormalNoise
- net.minecraft.world.level.levelgen.synth.NormalNoise$NoiseParameters
- net.minecraft.world.level.levelgen.synth.package-info
+ net.minecraft.world.level.levelgen.synth.PerlinNoise
- net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
+ net.minecraft.world.level.levelgen.synth.SimplexNoise
- net.minecraft.world.level.levelgen.ThreadSafeLegacyRandomSource
+ net.minecraft.world.level.levelgen.VerticalAnchor
- net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
+ net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
- net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
+ net.minecraft.world.level.levelgen.WorldDimensions
- net.minecraft.world.level.levelgen.WorldDimensions$1Entry
+ net.minecraft.world.level.levelgen.WorldDimensions$Complete
+ net.minecraft.world.level.levelgen.WorldGenerationContext
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
- net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.levelgen.WorldOptions
+ net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
- net.minecraft.world.level.levelgen.XoroshiroRandomSource
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ net.minecraft.world.level.lighting.BlockLightEngine
- net.minecraft.world.level.lighting.BlockLightSectionStorage
+ net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- net.minecraft.world.level.lighting.ChunkSkyLightSources
+ net.minecraft.world.level.lighting.DataLayerStorageMap
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
- net.minecraft.world.level.lighting.LayerLightEventListener
+ net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- net.minecraft.world.level.lighting.LayerLightSectionStorage
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$SectionState
- net.minecraft.world.level.lighting.LayerLightSectionStorage$SectionType
- net.minecraft.world.level.lighting.LeveledPriorityQueue
+ net.minecraft.world.level.lighting.LeveledPriorityQueue$1
+ net.minecraft.world.level.lighting.LevelLightEngine
- net.minecraft.world.level.lighting.LightEngine
+ net.minecraft.world.level.lighting.LightEngine$QueueEntry
- net.minecraft.world.level.lighting.LightEventListener
+ net.minecraft.world.level.lighting.package-info
+ net.minecraft.world.level.lighting.SkyLightEngine
- net.minecraft.world.level.lighting.SkyLightEngine$1
+ net.minecraft.world.level.lighting.SkyLightSectionStorage
- net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ net.minecraft.world.level.lighting.SpatialLongSet
- net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
- net.minecraft.world.level.material.EmptyFluid
+ net.minecraft.world.level.material.FlowingFluid
- net.minecraft.world.level.material.FlowingFluid$1
+ net.minecraft.world.level.material.Fluid
+ net.minecraft.world.level.material.Fluids
- net.minecraft.world.level.material.FluidState
- net.minecraft.world.level.material.FogType
+ net.minecraft.world.level.material.LavaFluid
- net.minecraft.world.level.material.LavaFluid$Flowing
+ net.minecraft.world.level.material.LavaFluid$Source
- net.minecraft.world.level.material.MapColor
+ net.minecraft.world.level.material.MapColor$Brightness
- net.minecraft.world.level.material.package-info
- net.minecraft.world.level.material.PushReaction
+ net.minecraft.world.level.material.WaterFluid
- net.minecraft.world.level.material.WaterFluid$Flowing
+ net.minecraft.world.level.material.WaterFluid$Source
+ net.minecraft.world.level.package-info
- net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
+ net.minecraft.world.level.pathfinder.BinaryHeap
- net.minecraft.world.level.pathfinder.BlockPathTypes
+ net.minecraft.world.level.pathfinder.FlyNodeEvaluator
- net.minecraft.world.level.pathfinder.Node
+ net.minecraft.world.level.pathfinder.NodeEvaluator
- net.minecraft.world.level.pathfinder.package-info
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.Path$DebugData
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
+ net.minecraft.world.level.pathfinder.WalkNodeEvaluator$1
- net.minecraft.world.level.portal.package-info
+ net.minecraft.world.level.portal.PortalForcer
- net.minecraft.world.level.portal.PortalInfo
+ net.minecraft.world.level.portal.PortalShape
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$NeighborUpdates
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$ShapeUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
+ net.minecraft.world.level.redstone.InstantNeighborUpdater
- net.minecraft.world.level.redstone.NeighborUpdater
- net.minecraft.world.level.redstone.package-info
+ net.minecraft.world.level.redstone.Redstone
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapId
+ net.minecraft.world.level.saveddata.SavedData
- net.minecraft.world.level.saveddata.SavedData$Factory
- net.minecraft.world.ticks.LevelChunkTicks
+ net.minecraft.world.ticks.LevelTickAccess
- net.minecraft.world.ticks.LevelTicks
+ net.minecraft.world.ticks.LevelTicks$PosAndContainerConsumer
- net.minecraft.world.ticks.package-info
- net.minecraft.world.ticks.ProtoChunkTicks
+ net.minecraft.world.ticks.SavedTick
- net.minecraft.world.ticks.SavedTick$1
+ net.minecraft.world.ticks.ScheduledTick
- net.minecraft.world.ticks.ScheduledTick$1
+ net.minecraft.world.ticks.SerializableTickContainer
- net.minecraft.world.ticks.TickAccess
+ net.minecraft.world.ticks.TickContainerAccess
- net.minecraft.world.ticks.TickPriority
+ net.minecraft.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.SharedConstants +1P
```
```
net.minecraft.Util +18M -12M
```
```
XXX.minecraft.commands.CommandBuildContext$1 +3M -1M
```
```
XXX.minecraft.core.UUIDUtil +1P
```
```
XXX.core.particles.BlockParticleOption$1 +2M -2M
```
```
XXX.core.particles.DustColorTransitionOptions$1 +2M -2M
```
```
XXX.core.particles.DustParticleOptions$1 +2M -2M
```
```
XXX.core.particles.ItemParticleOption +1M -1M
```
```
XXX.core.particles.ParticleOptions$Deserializer +1P -1P
```
```
XXX.core.particles.ParticleTypes +1P
```
```
XXX.core.particles.SculkChargeParticleOptions +1M -1M
```
```
XXX.core.particles.ShriekParticleOption +1M -1M
```
```
XXX.core.particles.SimpleParticleType +1M -1M
```
```
XXX.core.particles.VibrationParticleOption +1M -1M
```
```
XXX.minecraft.data.DataProvider +1M -1M
```
```
XXX.data.loot.LootTableProvider +9M -7M | +1P
```
```
XXX.loot.packs.TradeRebalanceLootTableProvider +1M -1M
```
```
XXX.loot.packs.VanillaLootTableProvider +1M -1M
```
```
XXX.data.models.BlockModelGenerators$1 +1P
```
```
XXX.data.models.ItemModelGenerators$TrimModelData +1M -1M
```
```
XXX.models.model.TextureMapping +1M
```
```
XXX.data.recipes.RecipeProvider$1 +1M -1M | +1P
```
```
XXX.recipes.packs.UpdateOneTwentyOneRecipeProvider +1M -1M
```
```
XXX.data.tags.TagsProvider +1M -1M
```
```
XXX.gametest.framework.GameTestHelper +2M -3M
```
```
XXX.gametest.framework.GameTestHelper$2 +1M -2M
```
```
XXX.network.codec.ByteBufCodecs$9 +3M -3M | -1P
```
```
XXX.network.codec.StreamCodec +2M
```
```
XXX.protocol.common.ClientboundDisconnectPacket +4M -3M
```
```
XXX.protocol.common.ClientboundResourcePackPushPacket +2M -4M | +1P -1P
```
```
XXX.protocol.cookie.ServerboundCookieResponsePacket -1M
```
```
XXX.protocol.game.ClientGamePacketListener +1P
```
```
XXX.protocol.game.ClientboundBossEventPacket +2M -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$AddOperation +2M -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$Operation +1P -1P
```
```
XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation +6M -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation +2M -2M
```
```
XXX.protocol.game.ClientboundCommandSuggestionsPacket +11M -7M | +3P -1P
```
```
XXX.protocol.game.ClientboundLightUpdatePacketData +1M -2M | +1P
```
```
XXX.protocol.game.ClientboundMapItemDataPacket +11M -10M | +3P -3P
```
```
XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action +12M -12M
```
```
XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer +1P -1P
```
```
XXX.protocol.game.ClientboundServerDataPacket +5M -4M
```
```
XXX.protocol.game.ClientboundSetScorePacket +2M -4M | +1P -1P
```
```
XXX.protocol.game.ClientboundSetSubtitleTextPacket +4M -3M
```
```
XXX.protocol.game.ClientboundSetTitleTextPacket +4M -3M
```
```
XXX.protocol.game.ClientboundSystemChatPacket -2M
```
```
XXX.minecraft.util.JavaOps -1M
```
```
XXX.util.datafix.ComponentDataFixUtils +1M
```
```
XXX.minecraft.world.RandomSequences +2M -2M
```
```
XXX.animal.horse.TraderLlama +1M -1M
```
```
XXX.entity.monster.AbstractSkeleton +1M -1M
```
```
XXX.entity.monster.CaveSpider +1M -1M
```
```
XXX.entity.monster.Illusioner +1M -1M
```
```
XXX.entity.monster.Shulker +1M -1M
```
```
XXX.entity.monster.Strider +1M -1M
```
```
XXX.entity.monster.Vindicator +1M -1M
```
```
XXX.entity.monster.WitherSkeleton +1M -1M
```
```
XXX.entity.monster.Zombie +1M -1M
```
```
XXX.monster.piglin.PiglinBrute +1M -1M
```
```
XXX.entity.npc.Villager +8M -7M
```
```
XXX.entity.projectile.EyeOfEnder +1M -1M
```
```
XXX.entity.raid.Raider +1M -1M
```
```
XXX.world.inventory.HorseInventoryMenu +3P
```
```
XXX.world.item.AnimalArmorItem +2M -3M | +1P -2P
```
```
XXX.world.item.ArmorItem +4M -3M | +2P -5P
```
```
XXX.world.item.ArmorMaterials +5M -13M | +8P -18P
```
```
XXX.world.item.ElytraItem +1M -1M
```
```
XXX.world.item.EnchantedBookItem -1M
```
```
XXX.item.armortrim.ArmorTrim +5M -5M
```
```
XXX.item.crafting.RecipeManager +2M -2M | +1P
```
```
XXX.item.crafting.RepairItemRecipe +1M -1M
```
```
XXX.item.trading.MerchantOffers +1M -2M | +1P
```
```
XXX.world.level.Level +3P -3P
```
```
XXX.level.block.Blocks +1M | +1P
```
```
XXX.level.block.DecoratedPotBlock +1M -1M
```
```
XXX.level.block.LevelEvent +3P
```
```
XXX.level.block.SoundType +1P
```
```
XXX.entity.trialspawner.TrialSpawner +3M -2M | +1P
```
```
XXX.saveddata.maps.MapItemSavedData +6M -5M
```
```
XXX.saveddata.maps.MapItemSavedData$MapPatch +11M | +1P
```
```
XXX.level.storage.CommandStorage$Container +1M -1M
```
```
XXX.storage.loot.LootDataManager +4M -4M | +1P
```
```
XXX.loot.functions.SetEnchantmentsFunction +1M -2M
```
```
XXX.loot.predicates.LootItemConditions -6M
```
```
XXX.world.ticks.ContainerSingleItem +1M -1M | -2P
```

</details>
















<details>
<summary>
net.minecraft.Util
</summary>

```diff
- boolean lambda$allOf$7(Object)
- boolean lambda$allOf$8(List,Object)
- boolean lambda$anyOf$10(List,Object)
- boolean lambda$anyOf$9(Object)
- boolean lambda$getVmArguments$11(String)
+ boolean lambda$getVmArguments$7(String)
+ List lambda$fallibleSequence$12(List,Void)
- List lambda$fallibleSequence$16(List,Void)
- List lambda$sequence$12(List,Void)
+ List lambda$sequence$8(List,Void)
- Predicate allOf(List)
- Predicate anyOf(List)
+ String lambda$fixedSize$14(int)
+ String lambda$fixedSize$15(int)
+ String lambda$fixedSize$16(int)
- String lambda$fixedSize$18(int)
- String lambda$fixedSize$19(int)
- String lambda$fixedSize$20(int)
+ String lambda$sanitizeName$17(CharPredicate,int)
- String lambda$sanitizeName$21(CharPredicate,int)
+ void lambda$fallibleSequence$10(Consumer,List,int,Object,Throwable)
+ void lambda$fallibleSequence$11(List,CompletableFuture[],Consumer,CompletableFuture)
- void lambda$fallibleSequence$14(Consumer,List,int,Object,Throwable)
- void lambda$fallibleSequence$15(List,CompletableFuture[],Consumer,CompletableFuture)
+ void lambda$getPartialOrThrow$18(String)
- void lambda$getPartialOrThrow$22(String)
+ void lambda$prefix$13(Consumer,String,String)
- void lambda$prefix$17(Consumer,String,String)
- void lambda$sequenceFailFastAndCancel$13(CompletableFuture,List,Throwable)
+ void lambda$sequenceFailFastAndCancel$9(CompletableFuture,List,Throwable)
```

</details>



























































































<details>
<summary>
net.minecraft.commands.CommandBuildContext$1
</summary>

```diff
+ HolderLookup holderLookup(ResourceKey)
- HolderLookup$RegistryLookup lambda$lookup$0(FeatureFlagSet,HolderLookup$RegistryLookup)
- Optional lookup(ResourceKey)
- Stream listRegistries()
```

</details>
















































<details>
<summary>
net.minecraft.core.particles.BlockParticleOption$1
</summary>

```diff
- BlockParticleOption fromCommand(ParticleType,StringReader,HolderLookup$Provider)
+ BlockParticleOption fromCommand(ParticleType,StringReader)
- ParticleOptions fromCommand(ParticleType,StringReader,HolderLookup$Provider)
+ ParticleOptions fromCommand(ParticleType,StringReader)
```

</details>
<details>
<summary>
net.minecraft.core.particles.DustColorTransitionOptions$1
</summary>

```diff
- DustColorTransitionOptions fromCommand(ParticleType,StringReader,HolderLookup$Provider)
+ DustColorTransitionOptions fromCommand(ParticleType,StringReader)
- ParticleOptions fromCommand(ParticleType,StringReader,HolderLookup$Provider)
+ ParticleOptions fromCommand(ParticleType,StringReader)
```

</details>
<details>
<summary>
net.minecraft.core.particles.DustParticleOptions$1
</summary>

```diff
- DustParticleOptions fromCommand(ParticleType,StringReader,HolderLookup$Provider)
+ DustParticleOptions fromCommand(ParticleType,StringReader)
- ParticleOptions fromCommand(ParticleType,StringReader,HolderLookup$Provider)
+ ParticleOptions fromCommand(ParticleType,StringReader)
```

</details>
<details>
<summary>
net.minecraft.core.particles.ItemParticleOption
</summary>

```diff
+ String writeToString()
- String writeToString(HolderLookup$Provider)
```

</details>



<details>
<summary>
net.minecraft.core.particles.SculkChargeParticleOptions
</summary>

```diff
+ String writeToString()
- String writeToString(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.core.particles.ShriekParticleOption
</summary>

```diff
+ String writeToString()
- String writeToString(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.core.particles.SimpleParticleType
</summary>

```diff
+ String writeToString()
- String writeToString(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.core.particles.VibrationParticleOption
</summary>

```diff
+ String writeToString()
- String writeToString(HolderLookup$Provider)
```

</details>






<details>
<summary>
net.minecraft.data.DataProvider
</summary>

```diff
+ CompletableFuture saveStable(CachedOutput,Codec,Object,Path)
- CompletableFuture saveStable(CachedOutput,HolderLookup$Provider,Codec,Object,Path)
```

</details>















<details>
<summary>
net.minecraft.data.loot.LootTableProvider
</summary>

```diff
+ CompletableFuture lambda$run$4(CachedOutput,Map$Entry)
- CompletableFuture lambda$run$5(CachedOutput,HolderLookup$Provider,Map$Entry)
- CompletableFuture run(CachedOutput,HolderLookup$Provider)
+ CompletableFuture[] lambda$run$5(int)
- CompletableFuture[] lambda$run$6(int)
- CompletionStage lambda$run$0(CachedOutput,HolderLookup$Provider)
- void <init>(PackOutput,Set,List,CompletableFuture)
+ void <init>(PackOutput,Set,List)
+ void lambda$run$0(Map,Map,LootTableProvider$SubProviderEntry,ResourceLocation,LootTable$Builder)
- void lambda$run$1(Map,Map,LootTableProvider$SubProviderEntry,ResourceLocation,LootTable$Builder)
+ void lambda$run$1(Map,Map,LootTableProvider$SubProviderEntry)
- void lambda$run$2(Map,Map,LootTableProvider$SubProviderEntry)
+ void lambda$run$2(ValidationContext,ResourceLocation,LootTable)
+ void lambda$run$3(String,String)
- void lambda$run$3(ValidationContext,ResourceLocation,LootTable)
- void lambda$run$4(String,String)
```

</details>


<details>
<summary>
net.minecraft.data.loot.packs.TradeRebalanceLootTableProvider
</summary>

```diff
- LootTableProvider create(PackOutput,CompletableFuture)
+ LootTableProvider create(PackOutput)
```

</details>




<details>
<summary>
net.minecraft.data.loot.packs.VanillaLootTableProvider
</summary>

```diff
- LootTableProvider create(PackOutput,CompletableFuture)
+ LootTableProvider create(PackOutput)
```

</details>






<details>
<summary>
net.minecraft.data.models.ItemModelGenerators$TrimModelData
</summary>

```diff
+ String name(ArmorMaterial)
- String name(Holder)
```

</details>















<details>
<summary>
net.minecraft.data.models.model.TextureMapping
</summary>

```diff
- TextureMapping vault(Block,String,String,String,String)
```

</details>





<details>
<summary>
net.minecraft.data.recipes.RecipeProvider$1
</summary>

```diff
- void <init>(RecipeProvider,Set,List,CachedOutput,HolderLookup$Provider)
+ void <init>(RecipeProvider,Set,List,CachedOutput)
```

</details>




<details>
<summary>
net.minecraft.data.recipes.packs.UpdateOneTwentyOneRecipeProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
```

</details>















<details>
<summary>
net.minecraft.data.tags.TagsProvider
</summary>

```diff
+ CompletableFuture lambda$run$5(Predicate,Predicate,CachedOutput,Map$Entry)
- CompletableFuture lambda$run$5(Predicate,Predicate,CachedOutput,TagsProvider$1CombinedData,Map$Entry)
```

</details>










































<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
+ Player makeMockPlayer()
- Player makeMockPlayer(GameType)
+ Player makeMockSurvivalPlayer()
+ void assertValueEqual(Number,Number,String)
- void assertValueEqual(Object,Object,String)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper$2
</summary>

```diff
+ boolean isLocalPlayer()
+ void <init>(GameTestHelper,Level,BlockPos,float,GameProfile)
- void <init>(GameTestHelper,MinecraftServer,ServerLevel,GameProfile,ClientInformation)
```

</details>



<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$9
</summary>

```diff
- byte[] decode(ByteBuf)
+ Tag decode(ByteBuf)
- void <init>()
+ void <init>(Supplier)
- void encode(ByteBuf,byte[])
+ void encode(ByteBuf,Tag)
```

</details>

<details>
<summary>
net.minecraft.network.codec.StreamCodec
</summary>

```diff
- StreamCodec composite(StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,Function4)
- StreamCodec composite(StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,Function5)
```

</details>















<details>
<summary>
net.minecraft.network.protocol.common.ClientboundDisconnectPacket
</summary>

```diff
- boolean equals(Object)
+ Component getReason()
- Component reason()
- int hashCode()
- String toString()
+ void <init>(FriendlyByteBuf)
+ void write(FriendlyByteBuf)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.common.ClientboundResourcePackPushPacket
</summary>

```diff
+ Component prompt()
- Optional prompt()
+ void <init>(FriendlyByteBuf)
+ void <init>(UUID,String,String,boolean,Component)
- void <init>(UUID,String,String,boolean,Optional)
+ void write(FriendlyByteBuf)
```

</details>




























<details>
<summary>
net.minecraft.network.protocol.cookie.ServerboundCookieResponsePacket
</summary>

```diff
+ byte[] lambda$new$0(FriendlyByteBuf)
```

</details>





<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket
</summary>

```diff
+ void <init>(FriendlyByteBuf)
- void <init>(RegistryFriendlyByteBuf)
+ void write(FriendlyByteBuf)
- void write(RegistryFriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
</summary>

```diff
+ void <init>(FriendlyByteBuf)
- void <init>(RegistryFriendlyByteBuf)
+ void write(FriendlyByteBuf)
- void write(RegistryFriendlyByteBuf)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
</summary>

```diff
- boolean equals(Object)
- Component name()
- int hashCode()
- String toString()
+ void <init>(FriendlyByteBuf)
- void <init>(RegistryFriendlyByteBuf)
+ void write(FriendlyByteBuf)
- void write(RegistryFriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
</summary>

```diff
+ void <init>(FriendlyByteBuf)
- void <init>(RegistryFriendlyByteBuf)
+ void write(FriendlyByteBuf)
- void write(RegistryFriendlyByteBuf)
```

</details>




<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
</summary>

```diff
- boolean equals(Object)
- ClientboundCommandSuggestionsPacket$Entry lambda$new$0(Suggestion)
+ int getId()
- int hashCode()
- int id()
- int length()
- int start()
- List suggestions()
- String toString()
+ Suggestion lambda$new$0(StringRange,FriendlyByteBuf)
- Suggestion lambda$toSuggestions$1(StringRange,ClientboundCommandSuggestionsPacket$Entry)
+ Suggestions getSuggestions()
- Suggestions toSuggestions()
+ void <init>(FriendlyByteBuf)
- void <init>(int,int,int,List)
+ void lambda$write$1(FriendlyByteBuf,Message)
+ void lambda$write$2(FriendlyByteBuf,Suggestion)
+ void write(FriendlyByteBuf)
```

</details>








<details>
<summary>
net.minecraft.network.protocol.game.ClientboundLightUpdatePacketData
</summary>

```diff
+ byte[] lambda$new$0(FriendlyByteBuf)
+ byte[] lambda$new$1(FriendlyByteBuf)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
</summary>

```diff
- boolean equals(Object)
+ boolean isLocked()
- boolean locked()
+ byte getScale()
- byte scale()
+ int getMapId()
- int hashCode()
+ List lambda$new$1(FriendlyByteBuf)
+ MapDecoration lambda$new$0(FriendlyByteBuf)
- MapId mapId()
- Optional colorPatch()
- Optional decorations()
- String toString()
+ void <init>(FriendlyByteBuf)
+ void <init>(int,byte,boolean,Collection,MapItemSavedData$MapPatch)
- void <init>(MapId,byte,boolean,Collection,MapItemSavedData$MapPatch)
- void <init>(MapId,byte,boolean,Optional,Optional)
- void lambda$applyToMap$0(MapItemSavedData,MapItemSavedData$MapPatch)
+ void lambda$write$2(FriendlyByteBuf,MapDecoration)
+ void lambda$write$3(FriendlyByteBuf,List)
+ void write(FriendlyByteBuf)
```

</details>








<details>
<summary>
net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
</summary>

```diff
+ void lambda$static$0(ClientboundPlayerInfoUpdatePacket$EntryBuilder,FriendlyByteBuf)
- void lambda$static$0(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
+ void lambda$static$1(FriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
- void lambda$static$1(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
+ void lambda$static$10(ClientboundPlayerInfoUpdatePacket$EntryBuilder,FriendlyByteBuf)
- void lambda$static$10(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
+ void lambda$static$11(FriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
- void lambda$static$11(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
+ void lambda$static$2(ClientboundPlayerInfoUpdatePacket$EntryBuilder,FriendlyByteBuf)
- void lambda$static$2(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
+ void lambda$static$3(FriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
- void lambda$static$3(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
+ void lambda$static$4(ClientboundPlayerInfoUpdatePacket$EntryBuilder,FriendlyByteBuf)
- void lambda$static$4(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
+ void lambda$static$5(FriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
- void lambda$static$5(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
+ void lambda$static$6(ClientboundPlayerInfoUpdatePacket$EntryBuilder,FriendlyByteBuf)
- void lambda$static$6(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
+ void lambda$static$7(FriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
- void lambda$static$7(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
+ void lambda$static$8(ClientboundPlayerInfoUpdatePacket$EntryBuilder,FriendlyByteBuf)
- void lambda$static$8(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
+ void lambda$static$9(FriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
- void lambda$static$9(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
```

</details>







<details>
<summary>
net.minecraft.network.protocol.game.ClientboundServerDataPacket
</summary>

```diff
- boolean equals(Object)
+ Component getMotd()
- Component motd()
- int hashCode()
+ Optional getIconBytes()
- Optional iconBytes()
- String toString()
+ void <init>(FriendlyByteBuf)
+ void write(FriendlyByteBuf)
```

</details>











<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSetScorePacket
</summary>

```diff
+ Component display()
- Optional display()
+ void <init>(RegistryFriendlyByteBuf)
+ void <init>(String,String,int,Component,Optional)
- void <init>(String,String,int,Optional,Optional)
+ void write(RegistryFriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
</summary>

```diff
- boolean equals(Object)
+ Component getText()
- Component text()
- int hashCode()
- String toString()
+ void <init>(FriendlyByteBuf)
+ void write(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
</summary>

```diff
- boolean equals(Object)
+ Component getText()
- Component text()
- int hashCode()
- String toString()
+ void <init>(FriendlyByteBuf)
+ void write(FriendlyByteBuf)
```

</details>


<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSystemChatPacket
</summary>

```diff
+ void <init>(FriendlyByteBuf)
+ void write(FriendlyByteBuf)
```

</details>

























<details>
<summary>
net.minecraft.util.JavaOps
</summary>

```diff
+ String lambda$remove$19(Object)
```

</details>



























<details>
<summary>
net.minecraft.util.datafix.ComponentDataFixUtils
</summary>

```diff
- Dynamic rewriteFromLenient(Dynamic)
```

</details>













































































































































<details>
<summary>
net.minecraft.world.RandomSequences
</summary>

```diff
- CompoundTag save(CompoundTag,HolderLookup$Provider)
+ CompoundTag save(CompoundTag)
- RandomSequences lambda$factory$1(long,CompoundTag,HolderLookup$Provider)
+ RandomSequences lambda$factory$1(long,CompoundTag)
```

</details>





















<details>
<summary>
net.minecraft.world.entity.animal.horse.TraderLlama
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>































<details>
<summary>
net.minecraft.world.entity.monster.AbstractSkeleton
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.CaveSpider
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>
















<details>
<summary>
net.minecraft.world.entity.monster.Illusioner
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>









<details>
<summary>
net.minecraft.world.entity.monster.Shulker
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>












<details>
<summary>
net.minecraft.world.entity.monster.Strider
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.Vindicator
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.WitherSkeleton
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zombie
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>











<details>
<summary>
net.minecraft.world.entity.monster.piglin.PiglinBrute
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>












<details>
<summary>
net.minecraft.world.entity.npc.Villager
</summary>

```diff
+ boolean lambda$getPlayerReputation$7(GossipType)
- boolean lambda$getPlayerReputation$8(GossipType)
- boolean lambda$hasFarmSeeds$10(ItemStack)
+ boolean lambda$hasFarmSeeds$9(ItemStack)
+ boolean lambda$spawnGolemIfNeeded$10(long,Villager)
- boolean lambda$spawnGolemIfNeeded$11(long,Villager)
+ int lambda$countFoodPointsInInventory$8(SimpleContainer,Map$Entry)
- int lambda$countFoodPointsInInventory$9(SimpleContainer,Map$Entry)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
- void lambda$readAdditionalSaveData$5(VillagerData)
+ void lambda$releasePoi$6(MinecraftServer,MemoryModuleType,GlobalPos)
- void lambda$releasePoi$7(MinecraftServer,MemoryModuleType,GlobalPos)
+ void lambda$tellWitnessesThatIWasMurdered$5(ServerLevel,Entity,LivingEntity)
- void lambda$tellWitnessesThatIWasMurdered$6(ServerLevel,Entity,LivingEntity)
```

</details>





















<details>
<summary>
net.minecraft.world.entity.projectile.EyeOfEnder
</summary>

```diff
- ItemStack getDefaultItem()
+ ItemStack getItemRaw()
```

</details>















<details>
<summary>
net.minecraft.world.entity.raid.Raider
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>












































































<details>
<summary>
net.minecraft.world.item.AnimalArmorItem
</summary>

```diff
- AnimalArmorItem$BodyType getBodyType()
+ AnimalArmorItem$Type getType()
+ int getProtection()
- void <init>(Holder,AnimalArmorItem$BodyType,Item$Properties)
+ void <init>(int,AnimalArmorItem$Type,String,Item$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.item.ArmorItem
</summary>

```diff
+ ArmorMaterial getMaterial()
- Holder getEquipSound()
- Holder getMaterial()
- Multimap lambda$new$1(Holder,ArmorItem$Type)
+ SoundEvent getEquipSound()
+ void <init>(ArmorMaterial,ArmorItem$Type,Item$Properties)
- void <init>(Holder,ArmorItem$Type,Item$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.item.ArmorMaterials
</summary>

```diff
+ ArmorMaterials valueOf(String)
+ ArmorMaterials[] $values()
+ ArmorMaterials[] values()
+ float getKnockbackResistance()
+ float getToughness()
- Holder bootstrap(Registry)
- Holder register(String,EnumMap,int,Holder,float,float,Supplier,List)
- Holder register(String,EnumMap,int,Holder,float,float,Supplier)
+ Ingredient getRepairIngredient()
- Ingredient lambda$static$15()
+ int getDefenseForType(ArmorItem$Type)
+ int getDurabilityForType(ArmorItem$Type)
+ int getEnchantmentValue()
+ SoundEvent getEquipSound()
+ String getName()
+ String getSerializedName()
- void <init>()
+ void <init>(String,int,String,int,EnumMap,int,SoundEvent,float,float,Supplier)
```

</details>





















<details>
<summary>
net.minecraft.world.item.ElytraItem
</summary>

```diff
- Holder getEquipSound()
+ SoundEvent getEquipSound()
```

</details>
<details>
<summary>
net.minecraft.world.item.EnchantedBookItem
</summary>

```diff
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>













































<details>
<summary>
net.minecraft.world.item.armortrim.ArmorTrim
</summary>

```diff
+ ResourceLocation innerTexture(ArmorMaterial)
- ResourceLocation innerTexture(Holder)
+ ResourceLocation lambda$new$2(Holder,ArmorMaterial)
- ResourceLocation lambda$new$2(Holder,Holder)
+ ResourceLocation lambda$new$4(Holder,ArmorMaterial)
- ResourceLocation lambda$new$4(Holder,Holder)
+ ResourceLocation outerTexture(ArmorMaterial)
- ResourceLocation outerTexture(Holder)
+ String getColorPaletteSuffix(ArmorMaterial)
- String getColorPaletteSuffix(Holder)
```

</details>

















<details>
<summary>
net.minecraft.world.item.crafting.RecipeManager
</summary>

```diff
- RecipeHolder fromJson(ResourceLocation,JsonObject,HolderLookup$Provider)
+ RecipeHolder fromJson(ResourceLocation,JsonObject)
+ void <init>()
- void <init>(HolderLookup$Provider)
```

</details>


<details>
<summary>
net.minecraft.world.item.crafting.RepairItemRecipe
</summary>

```diff
- void lambda$assemble$0(Map,Map,ItemStack,Enchantment)
+ void lambda$assemble$0(Map,Map,Map,Enchantment)
```

</details>

































<details>
<summary>
net.minecraft.world.item.trading.MerchantOffers
</summary>

```diff
+ CompoundTag createTag()
- void <init>(Collection)
+ void <init>(CompoundTag)
```

</details>























































































<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
- int lambda$static$53(BlockState)
```

</details>
































<details>
<summary>
net.minecraft.world.level.block.DecoratedPotBlock
</summary>

```diff
- void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag,RegistryAccess)
+ void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag)
```

</details>


















































































































<details>
<summary>
net.minecraft.world.level.block.entity.trialspawner.TrialSpawner
</summary>

```diff
- PlayerDetector$EntitySelector getEntitySelector()
- void <init>(TrialSpawner$StateAccessor,PlayerDetector,PlayerDetector$EntitySelector)
+ void <init>(TrialSpawner$StateAccessor,PlayerDetector)
- void <init>(TrialSpawnerConfig,TrialSpawnerData,TrialSpawner$StateAccessor,PlayerDetector,PlayerDetector$EntitySelector)
+ void <init>(TrialSpawnerConfig,TrialSpawnerData,TrialSpawner$StateAccessor,PlayerDetector)
```

</details>




<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData
</summary>

```diff
+ boolean lambda$mapMatcher$3(ItemStack,Integer,ItemStack)
- boolean lambda$mapMatcher$4(ItemStack,MapId,ItemStack)
- CompoundTag save(CompoundTag,HolderLookup$Provider)
+ CompoundTag save(CompoundTag)
- MapItemSavedData load(CompoundTag,HolderLookup$Provider)
+ MapItemSavedData load(CompoundTag)
+ Packet getUpdatePacket(int,Player)
- Packet getUpdatePacket(MapId,Player)
- void lambda$load$2(String)
+ void lambda$save$2(CompoundTag,Tag)
- void lambda$save$3(CompoundTag,Tag)
```

</details>
<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
</summary>

```diff
- boolean equals(Object)
- byte[] mapColors()
- int hashCode()
- int height()
- int startX()
- int startY()
- int width()
- Optional read(ByteBuf)
- String toString()
- void <clinit>()
- void write(ByteBuf,Optional)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.CommandStorage$Container
</summary>

```diff
- CompoundTag save(CompoundTag,HolderLookup$Provider)
+ CompoundTag save(CompoundTag)
```

</details>

















<details>
<summary>
net.minecraft.world.level.storage.loot.LootDataManager
</summary>

```diff
- CompletableFuture scheduleElementParse(LootDataType,HolderLookup$Provider,ResourceManager,Executor,Map)
+ CompletableFuture scheduleElementParse(LootDataType,ResourceManager,Executor,Map)
+ void <init>()
- void <init>(HolderLookup$Provider)
+ void lambda$scheduleElementParse$4(LootDataType,Map,ResourceLocation,JsonElement)
- void lambda$scheduleElementParse$4(LootDataType,RegistryOps,Map,ResourceLocation,JsonElement)
+ void lambda$scheduleElementParse$5(ResourceManager,LootDataType,Map)
- void lambda$scheduleElementParse$5(ResourceManager,LootDataType,RegistryOps,Map)
```

</details>











































<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
</summary>

```diff
+ void lambda$run$5(ItemStack,Enchantment,Integer)
- void lambda$run$5(Map,Enchantment,Integer)
+ void lambda$run$7(Map,Enchantment,Integer)
```

</details>




















<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemConditions
</summary>

```diff
+ boolean lambda$andConditions$1(Object)
+ boolean lambda$andConditions$2(List,Object)
+ boolean lambda$orConditions$3(Object)
+ boolean lambda$orConditions$4(List,Object)
+ Predicate andConditions(List)
+ Predicate orConditions(List)
```

</details>
























































<details>
<summary>
net.minecraft.world.ticks.ContainerSingleItem
</summary>

```diff
+ boolean stillValid(Player)
- ItemStack splitTheItem(int)
```

</details>
<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.client.multiplayer.chat.ChatListener
- net.minecraft.client.multiplayer.chat.ChatListener$Message
+ net.minecraft.client.multiplayer.chat.ChatLog
- net.minecraft.client.multiplayer.chat.ChatTrustLevel
+ net.minecraft.client.multiplayer.chat.ChatTrustLevel$1
- net.minecraft.client.multiplayer.chat.LoggedChatEvent
+ net.minecraft.client.multiplayer.chat.LoggedChatEvent$Type
- net.minecraft.client.multiplayer.chat.LoggedChatMessage
+ net.minecraft.client.multiplayer.chat.LoggedChatMessage$Player
- net.minecraft.client.multiplayer.chat.LoggedChatMessage$System
+ net.minecraft.client.multiplayer.chat.package-info
- net.minecraft.client.multiplayer.chat.report.AbuseReportSender
+ net.minecraft.client.multiplayer.chat.report.AbuseReportSender$1
- net.minecraft.client.multiplayer.chat.report.AbuseReportSender$SendException
+ net.minecraft.client.multiplayer.chat.report.AbuseReportSender$Services
- net.minecraft.client.multiplayer.chat.report.BanReason
+ net.minecraft.client.multiplayer.chat.report.ChatReport
- net.minecraft.client.multiplayer.chat.report.ChatReport$Builder
+ net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder
- net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder$Collector
+ net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder$Handler
- net.minecraft.client.multiplayer.chat.report.NameReport
+ net.minecraft.client.multiplayer.chat.report.NameReport$Builder
+ net.minecraft.client.multiplayer.chat.report.package-info
- net.minecraft.client.multiplayer.chat.report.Report
+ net.minecraft.client.multiplayer.chat.report.Report$Builder
- net.minecraft.client.multiplayer.chat.report.Report$CannotBuildReason
+ net.minecraft.client.multiplayer.chat.report.Report$Result
- net.minecraft.client.multiplayer.chat.report.ReportEnvironment
+ net.minecraft.client.multiplayer.chat.report.ReportEnvironment$Server
- net.minecraft.client.multiplayer.chat.report.ReportEnvironment$Server$Realm
+ net.minecraft.client.multiplayer.chat.report.ReportEnvironment$Server$ThirdParty
- net.minecraft.client.multiplayer.chat.report.ReportingContext
- net.minecraft.client.multiplayer.chat.report.ReportReason
+ net.minecraft.client.multiplayer.chat.report.ReportType
+ net.minecraft.client.multiplayer.chat.report.SkinReport
- net.minecraft.client.multiplayer.chat.report.SkinReport$Builder
- net.minecraft.client.multiplayer.DebugSampleSubscriber
+ net.minecraft.client.multiplayer.LegacyServerPinger
- net.minecraft.client.multiplayer.LegacyServerPinger$Output
+ net.minecraft.client.multiplayer.LevelLoadStatusManager
- net.minecraft.client.multiplayer.LevelLoadStatusManager$1
+ net.minecraft.client.multiplayer.LevelLoadStatusManager$Status
- net.minecraft.client.multiplayer.MultiPlayerGameMode
- net.minecraft.client.multiplayer.package-info
+ net.minecraft.client.multiplayer.PingDebugMonitor
- net.minecraft.client.multiplayer.PlayerInfo
+ net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler
- net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
- net.minecraft.client.multiplayer.prediction.package-info
+ net.minecraft.client.multiplayer.prediction.PredictiveAction
+ net.minecraft.client.multiplayer.ProfileKeyPairManager
- net.minecraft.client.multiplayer.ProfileKeyPairManager$1
+ net.minecraft.client.multiplayer.RegistryDataCollector
- net.minecraft.client.multiplayer.RegistryDataCollector$ContentsCollector
+ net.minecraft.client.multiplayer.RegistryDataCollector$TagCollector
+ net.minecraft.client.multiplayer.resolver.AddressCheck
- net.minecraft.client.multiplayer.resolver.AddressCheck$1
+ net.minecraft.client.multiplayer.resolver.package-info
+ net.minecraft.client.multiplayer.resolver.ResolvedServerAddress
- net.minecraft.client.multiplayer.resolver.ResolvedServerAddress$1
+ net.minecraft.client.multiplayer.resolver.ServerAddress
- net.minecraft.client.multiplayer.resolver.ServerAddressResolver
+ net.minecraft.client.multiplayer.resolver.ServerNameResolver
- net.minecraft.client.multiplayer.resolver.ServerRedirectHandler
- net.minecraft.client.multiplayer.ServerData
+ net.minecraft.client.multiplayer.ServerData$ServerPackStatus
- net.minecraft.client.multiplayer.ServerData$State
+ net.minecraft.client.multiplayer.ServerData$Type
- net.minecraft.client.multiplayer.ServerList
+ net.minecraft.client.multiplayer.ServerStatusPinger
- net.minecraft.client.multiplayer.ServerStatusPinger$1
+ net.minecraft.client.multiplayer.ServerStatusPinger$2
- net.minecraft.client.multiplayer.TransferState
- net.minecraft.client.package-info
+ net.minecraft.client.particle.AshParticle
- net.minecraft.client.particle.AshParticle$Provider
+ net.minecraft.client.particle.AttackSweepParticle
- net.minecraft.client.particle.AttackSweepParticle$Provider
+ net.minecraft.client.particle.BaseAshSmokeParticle
- net.minecraft.client.particle.BlockMarker
+ net.minecraft.client.particle.BlockMarker$Provider
- net.minecraft.client.particle.BreakingItemParticle
+ net.minecraft.client.particle.BreakingItemParticle$Provider
- net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
+ net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
- net.minecraft.client.particle.BubbleColumnUpParticle
+ net.minecraft.client.particle.BubbleColumnUpParticle$Provider
- net.minecraft.client.particle.BubbleParticle
+ net.minecraft.client.particle.BubbleParticle$Provider
- net.minecraft.client.particle.BubblePopParticle
+ net.minecraft.client.particle.BubblePopParticle$Provider
- net.minecraft.client.particle.CampfireSmokeParticle
+ net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
- net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
+ net.minecraft.client.particle.CherryParticle
- net.minecraft.client.particle.CritParticle
+ net.minecraft.client.particle.CritParticle$DamageIndicatorProvider
- net.minecraft.client.particle.CritParticle$MagicProvider
+ net.minecraft.client.particle.CritParticle$Provider
- net.minecraft.client.particle.DragonBreathParticle
+ net.minecraft.client.particle.DragonBreathParticle$Provider
- net.minecraft.client.particle.DripParticle
+ net.minecraft.client.particle.DripParticle$CoolingDripHangParticle
- net.minecraft.client.particle.DripParticle$DripHangParticle
+ net.minecraft.client.particle.DripParticle$DripLandParticle
- net.minecraft.client.particle.DripParticle$DripstoneFallAndLandParticle
+ net.minecraft.client.particle.DripParticle$FallAndLandParticle
- net.minecraft.client.particle.DripParticle$FallingParticle
+ net.minecraft.client.particle.DripParticle$HoneyFallAndLandParticle
- net.minecraft.client.particle.DustColorTransitionParticle
+ net.minecraft.client.particle.DustColorTransitionParticle$Provider
- net.minecraft.client.particle.DustParticle
+ net.minecraft.client.particle.DustParticle$Provider
- net.minecraft.client.particle.DustParticleBase
+ net.minecraft.client.particle.DustPlumeParticle
- net.minecraft.client.particle.DustPlumeParticle$Provider
+ net.minecraft.client.particle.EnchantmentTableParticle
+ net.minecraft.client.particle.EnchantmentTableParticle$Provider
- net.minecraft.client.particle.FlyTowardsPositionParticle$EnchantProvider
- net.minecraft.client.particle.FlyTowardsPositionParticle$VaultConnectionProvider
- net.minecraft.client.particle.package-info
- net.minecraft.client.particle.ParticleDescription
+ net.minecraft.client.particle.ParticleEngine
- net.minecraft.client.particle.ParticleEngine$1ParticleDefinition
+ net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
- net.minecraft.client.particle.ParticleEngine$SpriteParticleRegistration
+ net.minecraft.client.particle.ParticleProvider
- net.minecraft.client.particle.ParticleProvider$Sprite
+ net.minecraft.client.particle.ParticleRenderType
- net.minecraft.client.particle.ParticleRenderType$1
+ net.minecraft.client.particle.ParticleRenderType$2
- net.minecraft.client.particle.ParticleRenderType$3
+ net.minecraft.client.particle.ParticleRenderType$4
- net.minecraft.client.particle.ParticleRenderType$5
+ net.minecraft.client.particle.ParticleRenderType$6
- net.minecraft.client.particle.PlayerCloudParticle
+ net.minecraft.client.particle.PlayerCloudParticle$Provider
- net.minecraft.client.particle.PlayerCloudParticle$SneezeProvider
+ net.minecraft.client.particle.PortalParticle
- net.minecraft.client.particle.PortalParticle$Provider
+ net.minecraft.client.particle.ReversePortalParticle
- net.minecraft.client.particle.ReversePortalParticle$ReversePortalProvider
+ net.minecraft.client.particle.RisingParticle
- net.minecraft.client.particle.SculkChargeParticle
+ net.minecraft.client.particle.SculkChargeParticle$Provider
- net.minecraft.client.particle.SculkChargePopParticle
+ net.minecraft.client.particle.SculkChargePopParticle$Provider
- net.minecraft.client.particle.ShriekParticle
+ net.minecraft.client.particle.ShriekParticle$Provider
- net.minecraft.client.particle.SimpleAnimatedParticle
+ net.minecraft.client.particle.SingleQuadParticle
- net.minecraft.client.particle.SingleQuadParticle$FacingCameraMode
+ net.minecraft.client.particle.SmokeParticle
- net.minecraft.client.particle.SmokeParticle$Provider
+ net.minecraft.client.particle.SnowflakeParticle
- net.minecraft.client.particle.SnowflakeParticle$Provider
+ net.minecraft.client.particle.SonicBoomParticle
- net.minecraft.client.particle.SonicBoomParticle$Provider
+ net.minecraft.client.particle.SoulParticle
- net.minecraft.client.particle.SoulParticle$EmissiveProvider
+ net.minecraft.client.particle.SoulParticle$Provider
- net.minecraft.client.particle.SpellParticle
+ net.minecraft.client.particle.SpellParticle$AmbientMobProvider
- net.minecraft.client.particle.SpellParticle$InstantProvider
+ net.minecraft.client.particle.SpellParticle$MobProvider
- net.minecraft.client.particle.SpellParticle$Provider
+ net.minecraft.client.particle.SpellParticle$WitchProvider
- net.minecraft.client.particle.SpitParticle
+ net.minecraft.client.particle.SpitParticle$Provider
- net.minecraft.client.particle.SplashParticle
+ net.minecraft.client.particle.SplashParticle$Provider
- net.minecraft.client.particle.SpriteSet
+ net.minecraft.client.particle.SquidInkParticle
- net.minecraft.client.particle.SquidInkParticle$GlowInkProvider
+ net.minecraft.client.particle.SquidInkParticle$Provider
- net.minecraft.client.particle.SuspendedParticle
+ net.minecraft.client.particle.SuspendedParticle$CrimsonSporeProvider
- net.minecraft.client.particle.SuspendedParticle$SporeBlossomAirProvider
+ net.minecraft.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
- net.minecraft.client.particle.SuspendedParticle$UnderwaterProvider
+ net.minecraft.client.particle.SuspendedParticle$WarpedSporeProvider
- net.minecraft.client.particle.SuspendedTownParticle
+ net.minecraft.client.particle.SuspendedTownParticle$ComposterFillProvider
- net.minecraft.client.particle.SuspendedTownParticle$DolphinSpeedProvider
+ net.minecraft.client.particle.SuspendedTownParticle$EggCrackProvider
- net.minecraft.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ net.minecraft.client.particle.SuspendedTownParticle$Provider
- net.minecraft.client.particle.TerrainParticle
+ net.minecraft.client.particle.TerrainParticle$Provider
- net.minecraft.client.particle.TextureSheetParticle
+ net.minecraft.client.particle.TotemParticle
- net.minecraft.client.particle.TotemParticle$Provider
+ net.minecraft.client.particle.TrackingEmitter
- net.minecraft.client.particle.TrialSpawnerDetectionParticle
+ net.minecraft.client.particle.TrialSpawnerDetectionParticle$Provider
- net.minecraft.client.particle.VibrationSignalParticle
+ net.minecraft.client.particle.VibrationSignalParticle$Provider
- net.minecraft.client.particle.WakeParticle
+ net.minecraft.client.particle.WakeParticle$Provider
- net.minecraft.client.particle.WaterCurrentDownParticle
+ net.minecraft.client.particle.WaterCurrentDownParticle$Provider
- net.minecraft.client.particle.WaterDropParticle
+ net.minecraft.client.particle.WaterDropParticle$Provider
- net.minecraft.client.particle.WhiteAshParticle
+ net.minecraft.client.particle.WhiteAshParticle$Provider
- net.minecraft.client.particle.WhiteSmokeParticle
+ net.minecraft.client.particle.WhiteSmokeParticle$Provider
+ net.minecraft.client.player.AbstractClientPlayer
- net.minecraft.client.player.Input
- net.minecraft.client.player.inventory.Hotbar
+ net.minecraft.client.player.inventory.package-info
+ net.minecraft.client.player.KeyboardInput
- net.minecraft.client.player.LocalPlayer
- net.minecraft.client.player.package-info
+ net.minecraft.client.player.RemotePlayer
+ net.minecraft.client.profiling.ClientMetricsSamplersProvider
- net.minecraft.client.profiling.package-info
+ net.minecraft.client.quickplay.package-info
+ net.minecraft.client.quickplay.QuickPlay
- net.minecraft.client.quickplay.QuickPlayLog
+ net.minecraft.client.quickplay.QuickPlayLog$1
- net.minecraft.client.quickplay.QuickPlayLog$QuickPlayEntry
+ net.minecraft.client.quickplay.QuickPlayLog$QuickPlayWorld
- net.minecraft.client.quickplay.QuickPlayLog$Type
- net.minecraft.client.renderer.BiomeColors
+ net.minecraft.client.renderer.block.BlockModelShaper
- net.minecraft.client.renderer.block.BlockRenderDispatcher
+ net.minecraft.client.renderer.block.BlockRenderDispatcher$1
- net.minecraft.client.renderer.block.LiquidBlockRenderer
+ net.minecraft.client.renderer.block.LiquidBlockRenderer$1
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
- net.minecraft.client.renderer.block.model.ItemOverrides$BakedOverride
+ net.minecraft.client.renderer.block.model.ItemOverrides$PropertyMatcher
- net.minecraft.client.renderer.block.model.ItemTransform
+ net.minecraft.client.renderer.block.model.ItemTransform$Deserializer
- net.minecraft.client.renderer.block.model.ItemTransforms
+ net.minecraft.client.renderer.block.model.ItemTransforms$1
- net.minecraft.client.renderer.block.model.ItemTransforms$Deserializer
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
- net.minecraft.client.renderer.blockentity.BannerRenderer
+ net.minecraft.client.renderer.blockentity.BeaconRenderer
- net.minecraft.client.renderer.blockentity.BedRenderer
+ net.minecraft.client.renderer.blockentity.BellRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider
+ net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider$Context
- net.minecraft.client.renderer.blockentity.BlockEntityRenderers
+ net.minecraft.client.renderer.blockentity.BrightnessCombiner
- net.minecraft.client.renderer.blockentity.BrushableBlockRenderer
+ net.minecraft.client.renderer.blockentity.BrushableBlockRenderer$1
- net.minecraft.client.renderer.blockentity.CampfireRenderer
+ net.minecraft.client.renderer.blockentity.ChestRenderer
- net.minecraft.client.renderer.blockentity.ConduitRenderer
+ net.minecraft.client.renderer.blockentity.DecoratedPotRenderer
- net.minecraft.client.renderer.blockentity.EnchantTableRenderer
+ net.minecraft.client.renderer.blockentity.HangingSignRenderer
- net.minecraft.client.renderer.blockentity.HangingSignRenderer$HangingSignModel
+ net.minecraft.client.renderer.blockentity.LecternRenderer
- net.minecraft.client.renderer.blockentity.PistonHeadRenderer
+ net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer
- net.minecraft.client.renderer.blockentity.SignRenderer
+ net.minecraft.client.renderer.blockentity.SignRenderer$SignModel
- net.minecraft.client.renderer.blockentity.SkullBlockRenderer
+ net.minecraft.client.renderer.blockentity.SpawnerRenderer
- net.minecraft.client.renderer.blockentity.StructureBlockRenderer
+ net.minecraft.client.renderer.blockentity.StructureBlockRenderer$1
- net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
+ net.minecraft.client.renderer.blockentity.TheEndPortalRenderer
- net.minecraft.client.renderer.blockentity.TrialSpawnerRenderer
+ net.minecraft.client.renderer.BlockEntityWithoutLevelRenderer
- net.minecraft.client.renderer.CubeMap
+ net.minecraft.client.renderer.DimensionSpecialEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$EndEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$NetherEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$OverworldEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$SkyType
- net.minecraft.client.renderer.EffectInstance
+ net.minecraft.client.renderer.FaceInfo
- net.minecraft.client.renderer.FaceInfo$Constants
+ net.minecraft.client.renderer.FaceInfo$VertexInfo
- net.minecraft.client.renderer.FogRenderer
+ net.minecraft.client.renderer.FogRenderer$BlindnessFogFunction
- net.minecraft.client.renderer.FogRenderer$DarknessFogFunction
+ net.minecraft.client.renderer.FogRenderer$FogData
- net.minecraft.client.renderer.FogRenderer$FogMode
+ net.minecraft.client.renderer.FogRenderer$MobEffectFogFunction
- net.minecraft.client.renderer.GameRenderer
+ net.minecraft.client.renderer.GameRenderer$1
- net.minecraft.client.renderer.GameRenderer$ResourceCache
+ net.minecraft.client.renderer.GpuWarnlistManager
- net.minecraft.client.renderer.GpuWarnlistManager$Preparations
+ net.minecraft.client.renderer.ItemBlockRenderTypes
- net.minecraft.client.renderer.ItemInHandRenderer
+ net.minecraft.client.renderer.ItemInHandRenderer$1
- net.minecraft.client.renderer.ItemInHandRenderer$HandRenderSelection
+ net.minecraft.client.renderer.ItemModelShaper
- net.minecraft.client.renderer.LevelRenderer
+ net.minecraft.client.renderer.LevelRenderer$TransparencyShaderException
- net.minecraft.client.renderer.LightTexture
+ net.minecraft.client.renderer.MultiBufferSource
- net.minecraft.client.renderer.MultiBufferSource$BufferSource
+ net.minecraft.client.renderer.OutlineBufferSource
- net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
+ net.minecraft.client.renderer.PanoramaRenderer
- net.minecraft.client.renderer.PostChain
+ net.minecraft.client.renderer.PostPass
- net.minecraft.client.renderer.Rect2i
+ net.minecraft.client.renderer.RenderBuffers
- net.minecraft.client.renderer.RenderStateShard
+ net.minecraft.client.renderer.RenderStateShard$BooleanStateShard
- net.minecraft.client.renderer.RenderStateShard$ColorLogicStateShard
+ net.minecraft.client.renderer.RenderStateShard$CullStateShard
- net.minecraft.client.renderer.RenderStateShard$DepthTestStateShard
+ net.minecraft.client.renderer.RenderStateShard$EmptyTextureStateShard
- net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
+ net.minecraft.client.renderer.RenderStateShard$LightmapStateShard
- net.minecraft.client.renderer.RenderStateShard$LineStateShard
+ net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard
- net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
+ net.minecraft.client.renderer.RenderStateShard$OffsetTexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$OutputStateShard
+ net.minecraft.client.renderer.RenderStateShard$OverlayStateShard
- net.minecraft.client.renderer.RenderStateShard$ShaderStateShard
+ net.minecraft.client.renderer.RenderStateShard$TextureStateShard
- net.minecraft.client.renderer.RenderStateShard$TexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
- net.minecraft.client.renderer.RenderStateShard$WriteMaskStateShard
+ net.minecraft.client.renderer.RenderType
- net.minecraft.client.renderer.RenderType$CompositeRenderType
+ net.minecraft.client.renderer.RenderType$CompositeState
- net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ net.minecraft.client.renderer.RenderType$OutlineProperty
- net.minecraft.client.renderer.RunningTrimmedMean
+ net.minecraft.client.renderer.ScreenEffectRenderer
- net.minecraft.client.renderer.SectionBufferBuilderPack
+ net.minecraft.client.renderer.SectionBufferBuilderPool
- net.minecraft.client.renderer.SectionOcclusionGraph
+ net.minecraft.client.renderer.SectionOcclusionGraph$GraphEvents
- net.minecraft.client.renderer.SectionOcclusionGraph$GraphState
+ net.minecraft.client.renderer.SectionOcclusionGraph$GraphStorage
- net.minecraft.client.renderer.SectionOcclusionGraph$Node
+ net.minecraft.client.renderer.SectionOcclusionGraph$SectionToNodeMap
- net.minecraft.client.renderer.ShaderInstance
+ net.minecraft.client.renderer.ShaderInstance$1
- net.minecraft.client.renderer.Sheets
+ net.minecraft.client.renderer.Sheets$1
- net.minecraft.client.renderer.SpriteCoordinateExpander
+ net.minecraft.client.renderer.ViewArea
- net.minecraft.client.renderer.VirtualScreen
- net.minecraft.commands.arguments.AngleArgument
+ net.minecraft.commands.arguments.AngleArgument$SingleAngle
- net.minecraft.commands.arguments.ArgumentSignatures
+ net.minecraft.commands.arguments.ArgumentSignatures$Entry
- net.minecraft.commands.arguments.ArgumentSignatures$Signer
+ net.minecraft.commands.arguments.blocks.BlockInput
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
- net.minecraft.commands.arguments.blocks.BlockStateArgument
+ net.minecraft.commands.arguments.blocks.BlockStateParser
- net.minecraft.commands.arguments.blocks.BlockStateParser$BlockResult
+ net.minecraft.commands.arguments.blocks.BlockStateParser$TagResult
- net.minecraft.commands.arguments.blocks.package-info
+ net.minecraft.commands.arguments.ColorArgument
- net.minecraft.commands.arguments.ComponentArgument
+ net.minecraft.commands.arguments.CompoundTagArgument
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
- net.minecraft.commands.arguments.DimensionArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument
- net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
+ net.minecraft.commands.arguments.EntityArgument
- net.minecraft.commands.arguments.EntityArgument$Info
+ net.minecraft.commands.arguments.EntityArgument$Info$Template
- net.minecraft.commands.arguments.GameModeArgument
+ net.minecraft.commands.arguments.GameProfileArgument
- net.minecraft.commands.arguments.GameProfileArgument$Result
+ net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
- net.minecraft.commands.arguments.HeightmapTypeArgument
- net.minecraft.commands.arguments.item.FunctionArgument
+ net.minecraft.commands.arguments.item.FunctionArgument$1
- net.minecraft.commands.arguments.item.FunctionArgument$2
+ net.minecraft.commands.arguments.item.FunctionArgument$Result
- net.minecraft.commands.arguments.item.ItemArgument
+ net.minecraft.commands.arguments.item.ItemInput
- net.minecraft.commands.arguments.item.ItemParser
+ net.minecraft.commands.arguments.item.ItemPredicateArgument
- net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
- net.minecraft.commands.arguments.item.ItemPredicateParser$1
- net.minecraft.commands.arguments.item.ItemSyntaxParser$State
- net.minecraft.commands.arguments.item.ItemSyntaxParser$Visitor
+ net.minecraft.commands.arguments.item.package-info
+ net.minecraft.commands.arguments.MessageArgument
- net.minecraft.commands.arguments.MessageArgument$Message
+ net.minecraft.commands.arguments.MessageArgument$Part
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
- net.minecraft.commands.arguments.package-info
+ net.minecraft.commands.arguments.ParticleArgument
- net.minecraft.commands.arguments.RangeArgument
+ net.minecraft.commands.arguments.RangeArgument$Floats
- net.minecraft.commands.arguments.RangeArgument$Ints
+ net.minecraft.commands.arguments.ResourceArgument
- net.minecraft.commands.arguments.ResourceArgument$Info
+ net.minecraft.commands.arguments.ResourceArgument$Info$Template
- net.minecraft.commands.arguments.ResourceKeyArgument
+ net.minecraft.commands.arguments.ResourceKeyArgument$Info
- net.minecraft.commands.arguments.ResourceKeyArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceLocationArgument
- net.minecraft.commands.arguments.ResourceOrTagArgument
+ net.minecraft.commands.arguments.ResourceOrTagArgument$Info
- net.minecraft.commands.arguments.ResourceOrTagArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceOrTagArgument$ResourceResult
- net.minecraft.commands.arguments.ResourceOrTagArgument$Result
+ net.minecraft.commands.arguments.ResourceOrTagArgument$TagResult
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Result
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$TagResult
+ net.minecraft.commands.arguments.ScoreboardSlotArgument
- net.minecraft.commands.arguments.ScoreHolderArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument$Info
- net.minecraft.commands.arguments.ScoreHolderArgument$Info$Template
+ net.minecraft.commands.arguments.ScoreHolderArgument$Result
- net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
+ net.minecraft.commands.arguments.selector.EntitySelector
- net.minecraft.commands.arguments.selector.EntitySelector$1
+ net.minecraft.commands.arguments.selector.EntitySelectorParser
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
+ net.minecraft.commands.arguments.selector.options.package-info
- net.minecraft.commands.arguments.selector.package-info
- net.minecraft.commands.arguments.SignedArgument
+ net.minecraft.commands.arguments.SlotArgument
- net.minecraft.commands.arguments.StringRepresentableArgument
+ net.minecraft.commands.arguments.StyleArgument
- net.minecraft.commands.arguments.TeamArgument
+ net.minecraft.commands.arguments.TemplateMirrorArgument
- net.minecraft.commands.arguments.TemplateRotationArgument
+ net.minecraft.commands.arguments.TimeArgument
- net.minecraft.commands.arguments.TimeArgument$Info
+ net.minecraft.commands.arguments.TimeArgument$Info$Template
- net.minecraft.commands.arguments.UuidArgument
+ net.minecraft.commands.CommandBuildContext$2$1
+ net.minecraft.commands.CommandBuildContext$Configurable
+ net.minecraft.commands.CommandResultCallback
- net.minecraft.commands.CommandResultCallback$1
+ net.minecraft.commands.Commands
- net.minecraft.commands.Commands$1
+ net.minecraft.commands.Commands$1$1
- net.minecraft.commands.Commands$CommandSelection
+ net.minecraft.commands.Commands$ParseFunction
+ net.minecraft.commands.CommandSigningContext
- net.minecraft.commands.CommandSigningContext$1
+ net.minecraft.commands.CommandSigningContext$SignedArguments
- net.minecraft.commands.CommandSource
+ net.minecraft.commands.CommandSource$1
- net.minecraft.commands.CommandSourceStack
+ net.minecraft.commands.execution.ChainModifiers
- net.minecraft.commands.execution.CommandQueueEntry
+ net.minecraft.commands.execution.CustomCommandExecutor
- net.minecraft.commands.execution.CustomCommandExecutor$CommandAdapter
+ net.minecraft.commands.execution.CustomCommandExecutor$WithErrorHandling
- net.minecraft.commands.execution.CustomModifierExecutor
+ net.minecraft.commands.execution.CustomModifierExecutor$ModifierAdapter
- net.minecraft.commands.execution.EntryAction
+ net.minecraft.commands.execution.ExecutionContext
- net.minecraft.commands.execution.ExecutionControl
+ net.minecraft.commands.execution.ExecutionControl$1
- net.minecraft.commands.execution.Frame
+ net.minecraft.commands.execution.Frame$FrameControl
- net.minecraft.commands.execution.package-info
+ net.minecraft.commands.execution.tasks.BuildContexts
- net.minecraft.commands.execution.tasks.BuildContexts$Continuation
+ net.minecraft.commands.execution.tasks.BuildContexts$TopLevel
- net.minecraft.commands.execution.tasks.BuildContexts$Unbound
+ net.minecraft.commands.execution.tasks.CallFunction
- net.minecraft.commands.execution.tasks.ContinuationTask
+ net.minecraft.commands.execution.tasks.ContinuationTask$TaskProvider
- net.minecraft.commands.execution.tasks.ExecuteCommand
+ net.minecraft.commands.execution.tasks.FallthroughTask
- net.minecraft.commands.execution.tasks.IsolatedCall
+ net.minecraft.commands.execution.tasks.package-info
- net.minecraft.commands.execution.TraceCallbacks
+ net.minecraft.commands.execution.UnboundEntryAction
- net.minecraft.commands.ExecutionCommandSource
+ net.minecraft.commands.FunctionInstantiationException
- net.minecraft.commands.functions.CommandFunction
+ net.minecraft.commands.functions.FunctionBuilder
- net.minecraft.commands.functions.InstantiatedFunction
+ net.minecraft.commands.functions.MacroFunction
- net.minecraft.commands.functions.MacroFunction$Entry
+ net.minecraft.commands.functions.MacroFunction$MacroEntry
- net.minecraft.commands.functions.MacroFunction$PlainTextEntry
+ net.minecraft.commands.functions.package-info
+ net.minecraft.commands.functions.PlainTextFunction
- net.minecraft.commands.functions.StringTemplate
- net.minecraft.commands.package-info
- net.minecraft.commands.ParserUtils
+ net.minecraft.commands.SharedSuggestionProvider
- net.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ net.minecraft.commands.synchronization.ArgumentTypeInfo
- net.minecraft.commands.synchronization.ArgumentTypeInfo$Template
+ net.minecraft.commands.synchronization.ArgumentTypeInfos
- net.minecraft.commands.synchronization.ArgumentUtils
+ net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo
- net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo
- net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo
- net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.LongArgumentInfo
- net.minecraft.commands.synchronization.brigadier.LongArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.package-info
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$1
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$Template
+ net.minecraft.commands.synchronization.package-info
+ net.minecraft.commands.synchronization.SingletonArgumentInfo
- net.minecraft.commands.synchronization.SingletonArgumentInfo$Template
+ net.minecraft.commands.synchronization.SuggestionProviders
- net.minecraft.commands.synchronization.SuggestionProviders$Wrapper
- net.minecraft.core.AxisCycle
+ net.minecraft.core.AxisCycle$1
- net.minecraft.core.AxisCycle$2
+ net.minecraft.core.AxisCycle$3
- net.minecraft.core.BlockMath
+ net.minecraft.core.BlockPos
- net.minecraft.core.BlockPos$1
+ net.minecraft.core.BlockPos$2
- net.minecraft.core.BlockPos$3
+ net.minecraft.core.BlockPos$4
- net.minecraft.core.BlockPos$5
+ net.minecraft.core.BlockPos$6
- net.minecraft.core.BlockPos$MutableBlockPos
+ net.minecraft.core.Cloner
- net.minecraft.core.Cloner$Factory
+ net.minecraft.core.Cursor3D
- net.minecraft.core.DefaultedMappedRegistry
+ net.minecraft.core.DefaultedRegistry
- net.minecraft.core.Direction
+ net.minecraft.core.Direction$1
- net.minecraft.core.Direction$Axis
+ net.minecraft.core.Direction$Axis$1
- net.minecraft.core.Direction$Axis$2
+ net.minecraft.core.Direction$Axis$3
- net.minecraft.core.Direction$AxisDirection
+ net.minecraft.core.Direction$Plane
- net.minecraft.core.Direction8
+ net.minecraft.core.FrontAndTop
- net.minecraft.core.GlobalPos
+ net.minecraft.core.Holder
- net.minecraft.core.Holder$Direct
+ net.minecraft.core.Holder$Kind
- net.minecraft.core.Holder$Reference
+ net.minecraft.core.Holder$Reference$Type
- net.minecraft.core.HolderGetter
+ net.minecraft.core.HolderGetter$Provider
- net.minecraft.core.HolderLookup
+ net.minecraft.core.HolderLookup$1
+ net.minecraft.core.HolderLookup$Provider
- net.minecraft.core.HolderLookup$Provider$1
+ net.minecraft.core.HolderLookup$Provider$2
- net.minecraft.core.HolderLookup$RegistryLookup
+ net.minecraft.gametest.framework.GameTestInfo
- net.minecraft.gametest.framework.GameTestListener
+ net.minecraft.gametest.framework.GameTestRegistry
- net.minecraft.gametest.framework.GameTestRunner
+ net.minecraft.gametest.framework.GameTestRunner$1
- net.minecraft.gametest.framework.GameTestRunner$Builder
+ net.minecraft.gametest.framework.GameTestRunner$GameTestBatcher
- net.minecraft.gametest.framework.GameTestRunner$StructureSpawner
+ net.minecraft.gametest.framework.GameTestSequence
- net.minecraft.gametest.framework.GameTestSequence$Condition
+ net.minecraft.gametest.framework.GameTestServer
- net.minecraft.gametest.framework.GameTestServer$1
+ net.minecraft.gametest.framework.GameTestTicker
- net.minecraft.gametest.framework.GameTestTimeoutException
+ net.minecraft.gametest.framework.GlobalTestReporter
- net.minecraft.gametest.framework.JUnitLikeTestReporter
+ net.minecraft.gametest.framework.LogTestReporter
- net.minecraft.gametest.framework.MultipleTestTracker
+ net.minecraft.gametest.framework.MultipleTestTracker$1
+ net.minecraft.gametest.framework.package-info
- net.minecraft.gametest.framework.ReportGameListener
+ net.minecraft.gametest.framework.RetryOptions
- net.minecraft.gametest.framework.StructureBlockPosFinder
+ net.minecraft.gametest.framework.StructureGridSpawner
- net.minecraft.gametest.framework.StructureUtils
+ net.minecraft.gametest.framework.StructureUtils$1
- net.minecraft.gametest.framework.TestClassNameArgument
+ net.minecraft.gametest.framework.TestCommand
- net.minecraft.gametest.framework.TestCommand$Runner
+ net.minecraft.gametest.framework.TestCommand$TestBatchSummaryDisplayer
- net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
+ net.minecraft.gametest.framework.TestFinder
- net.minecraft.gametest.framework.TestFinder$Builder
+ net.minecraft.gametest.framework.TestFunction
- net.minecraft.gametest.framework.TestFunctionArgument
+ net.minecraft.gametest.framework.TestFunctionFinder
- net.minecraft.gametest.framework.TestReporter
- net.minecraft.locale.Language
+ net.minecraft.locale.Language$1
- net.minecraft.locale.package-info
+ net.minecraft.nbt.ByteArrayTag
- net.minecraft.nbt.ByteArrayTag$1
+ net.minecraft.nbt.ByteTag
- net.minecraft.nbt.ByteTag$1
+ net.minecraft.nbt.ByteTag$Cache
- net.minecraft.nbt.CollectionTag
+ net.minecraft.nbt.CompoundTag
- net.minecraft.nbt.CompoundTag$1
+ net.minecraft.nbt.CompoundTag$2
- net.minecraft.nbt.DoubleTag
+ net.minecraft.nbt.DoubleTag$1
- net.minecraft.nbt.EndTag
+ net.minecraft.nbt.EndTag$1
- net.minecraft.nbt.FloatTag
+ net.minecraft.nbt.FloatTag$1
- net.minecraft.nbt.IntArrayTag
+ net.minecraft.nbt.IntArrayTag$1
- net.minecraft.nbt.IntTag
+ net.minecraft.nbt.IntTag$1
- net.minecraft.nbt.IntTag$Cache
+ net.minecraft.nbt.ListTag
- net.minecraft.nbt.ListTag$1
+ net.minecraft.nbt.ListTag$2
- net.minecraft.nbt.LongArrayTag
+ net.minecraft.nbt.LongArrayTag$1
- net.minecraft.nbt.LongTag
+ net.minecraft.nbt.LongTag$1
- net.minecraft.nbt.LongTag$Cache
+ net.minecraft.nbt.NbtAccounter
- net.minecraft.nbt.NbtAccounterException
+ net.minecraft.nbt.NbtException
- net.minecraft.nbt.NbtFormatException
+ net.minecraft.nbt.NbtIo
- net.minecraft.nbt.NbtIo$1
+ net.minecraft.nbt.NbtIo$StringFallbackDataOutput
- net.minecraft.nbt.NbtOps
+ net.minecraft.nbt.NbtOps$1
- net.minecraft.nbt.NbtOps$ByteListCollector
+ net.minecraft.nbt.NbtOps$HeterogenousListCollector
- net.minecraft.nbt.NbtOps$HomogenousListCollector
+ net.minecraft.nbt.NbtOps$InitialListCollector
- net.minecraft.nbt.NbtOps$IntListCollector
+ net.minecraft.nbt.NbtOps$ListCollector
- net.minecraft.nbt.NbtOps$LongListCollector
+ net.minecraft.nbt.NbtOps$NbtRecordBuilder
- net.minecraft.nbt.NbtUtils
+ net.minecraft.nbt.NumericTag
+ net.minecraft.nbt.package-info
- net.minecraft.nbt.ReportedNbtException
+ net.minecraft.nbt.ShortTag
- net.minecraft.nbt.ShortTag$1
+ net.minecraft.nbt.ShortTag$Cache
- net.minecraft.nbt.SnbtPrinterTagVisitor
+ net.minecraft.nbt.StreamTagVisitor
- net.minecraft.nbt.StreamTagVisitor$EntryResult
+ net.minecraft.nbt.StreamTagVisitor$ValueResult
- net.minecraft.nbt.StringTag
+ net.minecraft.nbt.StringTag$1
- net.minecraft.nbt.StringTagVisitor
+ net.minecraft.nbt.Tag
- net.minecraft.nbt.TagParser
+ net.minecraft.nbt.TagType
- net.minecraft.nbt.TagType$1
+ net.minecraft.nbt.TagType$2
- net.minecraft.nbt.TagType$StaticSize
+ net.minecraft.nbt.TagType$VariableSize
- net.minecraft.nbt.TagTypes
+ net.minecraft.nbt.TagVisitor
- net.minecraft.nbt.TextComponentTagVisitor
- net.minecraft.nbt.visitors.CollectFields
+ net.minecraft.nbt.visitors.CollectToTag
- net.minecraft.nbt.visitors.FieldSelector
+ net.minecraft.nbt.visitors.FieldTree
+ net.minecraft.nbt.visitors.package-info
- net.minecraft.nbt.visitors.SkipAll
+ net.minecraft.nbt.visitors.SkipAll$1
- net.minecraft.nbt.visitors.SkipFields
- net.minecraft.network.BandwidthDebugMonitor
- net.minecraft.network.chat.ChatDecorator
+ net.minecraft.network.chat.ChatType
- net.minecraft.network.chat.ChatType$Bound
+ net.minecraft.network.chat.ChatTypeDecoration
- net.minecraft.network.chat.ChatTypeDecoration$Parameter
+ net.minecraft.network.chat.ChatTypeDecoration$Parameter$Selector
- net.minecraft.network.chat.ClickEvent
+ net.minecraft.network.chat.ClickEvent$Action
- net.minecraft.network.chat.CommonComponents
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.Component$SerializerAdapter
- net.minecraft.network.chat.ComponentContents
+ net.minecraft.network.chat.ComponentContents$Type
- net.minecraft.network.chat.ComponentSerialization
+ net.minecraft.network.chat.ComponentSerialization$FuzzyCodec
- net.minecraft.network.chat.ComponentSerialization$StrictEither
+ net.minecraft.network.chat.ComponentUtils
+ net.minecraft.network.chat.contents.BlockDataSource
- net.minecraft.network.chat.contents.DataSource
+ net.minecraft.network.chat.contents.DataSource$Type
- net.minecraft.network.chat.contents.EntityDataSource
+ net.minecraft.network.chat.contents.KeybindContents
- net.minecraft.network.chat.contents.KeybindResolver
+ net.minecraft.network.chat.contents.NbtContents
- net.minecraft.network.chat.contents.package-info
- net.minecraft.network.chat.contents.PlainTextContents
+ net.minecraft.network.chat.contents.PlainTextContents$1
- net.minecraft.network.chat.contents.PlainTextContents$LiteralContents
+ net.minecraft.network.chat.contents.ScoreContents
- net.minecraft.network.chat.contents.SelectorContents
+ net.minecraft.network.chat.contents.StorageDataSource
- net.minecraft.network.chat.contents.TranslatableContents
+ net.minecraft.network.chat.contents.TranslatableFormatException
- net.minecraft.network.chat.FilterMask
+ net.minecraft.network.chat.FilterMask$1
- net.minecraft.network.chat.FilterMask$Type
+ net.minecraft.network.chat.FormattedText
- net.minecraft.network.chat.FormattedText$1
+ net.minecraft.network.chat.FormattedText$2
- net.minecraft.network.chat.FormattedText$3
+ net.minecraft.network.chat.FormattedText$4
- net.minecraft.network.chat.FormattedText$ContentConsumer
+ net.minecraft.network.chat.FormattedText$StyledContentConsumer
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
+ net.minecraft.network.chat.HoverEvent$ItemStackInfo
- net.minecraft.network.chat.HoverEvent$TypedHoverEvent
+ net.minecraft.network.chat.LastSeenMessages
- net.minecraft.network.chat.LastSeenMessages$Packed
+ net.minecraft.network.chat.LastSeenMessages$Update
- net.minecraft.network.chat.LastSeenMessagesTracker
+ net.minecraft.network.chat.LastSeenMessagesTracker$Update
- net.minecraft.network.chat.LastSeenMessagesValidator
+ net.minecraft.network.chat.LastSeenTrackedEntry
- net.minecraft.network.chat.LocalChatSession
+ net.minecraft.network.chat.MessageSignature
- net.minecraft.network.chat.MessageSignature$Packed
+ net.minecraft.network.chat.MessageSignatureCache
- net.minecraft.network.chat.MutableComponent
+ net.minecraft.network.chat.numbers.BlankFormat
- net.minecraft.network.chat.numbers.BlankFormat$1
+ net.minecraft.network.chat.numbers.FixedFormat
- net.minecraft.network.chat.numbers.FixedFormat$1
+ net.minecraft.network.chat.numbers.NumberFormat
- net.minecraft.network.chat.numbers.NumberFormatType
+ net.minecraft.network.chat.numbers.NumberFormatTypes
- net.minecraft.network.chat.numbers.package-info
- net.minecraft.network.chat.numbers.StyledFormat
+ net.minecraft.network.chat.numbers.StyledFormat$1
+ net.minecraft.network.chat.OutgoingChatMessage
- net.minecraft.network.chat.OutgoingChatMessage$Disguised
+ net.minecraft.network.chat.OutgoingChatMessage$Player
+ net.minecraft.network.chat.package-info
- net.minecraft.network.chat.PlayerChatMessage
+ net.minecraft.network.chat.RemoteChatSession
- net.minecraft.network.chat.RemoteChatSession$Data
+ net.minecraft.network.chat.SignableCommand
- net.minecraft.network.chat.SignableCommand$Argument
+ net.minecraft.network.chat.SignedMessageBody
- net.minecraft.network.chat.SignedMessageBody$Packed
+ net.minecraft.network.chat.SignedMessageChain
- net.minecraft.network.chat.SignedMessageChain$DecodeException
+ net.minecraft.network.chat.SignedMessageChain$Decoder
- net.minecraft.network.chat.SignedMessageChain$Encoder
+ net.minecraft.network.chat.SignedMessageLink
- net.minecraft.network.chat.SignedMessageValidator
+ net.minecraft.network.chat.SignedMessageValidator$KeyBased
- net.minecraft.network.chat.Style
+ net.minecraft.network.chat.Style$1
- net.minecraft.network.chat.Style$1Collector
+ net.minecraft.network.chat.Style$Serializer
- net.minecraft.network.chat.SubStringSource
+ net.minecraft.network.chat.TextColor
- net.minecraft.network.chat.ThrowingComponent
+ net.minecraft.network.CipherBase
- net.minecraft.network.CipherDecoder
+ net.minecraft.network.CipherEncoder
- net.minecraft.network.ClientboundPacketListener
- net.minecraft.network.codec.ByteBufCodecs
+ net.minecraft.network.codec.ByteBufCodecs$1
- net.minecraft.network.codec.ByteBufCodecs$10
+ net.minecraft.network.codec.ByteBufCodecs$11
- net.minecraft.network.codec.ByteBufCodecs$12
+ net.minecraft.network.codec.ByteBufCodecs$13
- net.minecraft.network.codec.ByteBufCodecs$14
+ net.minecraft.network.codec.ByteBufCodecs$15
- net.minecraft.network.codec.ByteBufCodecs$16
+ net.minecraft.network.codec.ByteBufCodecs$17
- net.minecraft.network.codec.ByteBufCodecs$18
+ net.minecraft.network.codec.ByteBufCodecs$19
- net.minecraft.network.codec.ByteBufCodecs$2
- net.minecraft.network.codec.ByteBufCodecs$21
- net.minecraft.network.codec.StreamCodec$10
+ net.minecraft.network.CompressionDecoder
- net.minecraft.network.CompressionEncoder
+ net.minecraft.network.Connection
- net.minecraft.network.Connection$1
+ net.minecraft.network.Connection$2
- net.minecraft.network.Connection$3
+ net.minecraft.network.ConnectionProtocol
- net.minecraft.network.FriendlyByteBuf
+ net.minecraft.network.HandlerNames
- net.minecraft.network.PacketBundlePacker
+ net.minecraft.network.PacketBundleUnpacker
- net.minecraft.network.PacketDecoder
+ net.minecraft.network.PacketEncoder
- net.minecraft.network.PacketListener
+ net.minecraft.network.PacketSendListener
- net.minecraft.network.PacketSendListener$1
+ net.minecraft.network.PacketSendListener$2
- net.minecraft.network.protocol.game.ClientboundCommandsPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
- net.minecraft.network.protocol.game.ClientboundContainerClosePacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
- net.minecraft.network.protocol.game.ClientboundCooldownPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ net.minecraft.network.protocol.game.ClientboundDamageEventPacket
- net.minecraft.network.protocol.game.ClientboundDebugSamplePacket
+ net.minecraft.network.protocol.game.package-info
- net.minecraft.network.protocol.game.ServerboundEditBookPacket
+ net.minecraft.network.protocol.game.ServerboundEntityTagQueryPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$1
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
- net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$StatusOnly
- net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
- net.minecraft.network.protocol.game.ServerboundPickItemPacket
+ net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
- net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
- net.minecraft.network.protocol.game.ServerboundRenameItemPacket
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSelectTradePacket
- net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
+ net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
- net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
+ net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
- net.minecraft.network.protocol.game.ServerboundSwingPacket
+ net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
- net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemPacket
- net.minecraft.network.protocol.game.VecDeltaCodec
- net.minecraft.network.protocol.handshake.ClientIntent
+ net.minecraft.network.protocol.handshake.ClientIntent$1
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
+ net.minecraft.network.protocol.handshake.HandshakePacketTypes
- net.minecraft.network.protocol.handshake.HandshakeProtocols
- net.minecraft.network.protocol.handshake.package-info
+ net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
- net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ClientboundGameProfilePacket
- net.minecraft.network.protocol.login.ClientboundHelloPacket
+ net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
- net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
+ net.minecraft.network.protocol.login.ClientLoginPacketListener
- net.minecraft.network.protocol.login.custom.CustomQueryAnswerPayload
+ net.minecraft.network.protocol.login.custom.CustomQueryPayload
- net.minecraft.network.protocol.login.custom.DiscardedQueryAnswerPayload
+ net.minecraft.network.protocol.login.custom.DiscardedQueryPayload
- net.minecraft.network.protocol.login.custom.package-info
+ net.minecraft.network.protocol.login.LoginPacketTypes
- net.minecraft.network.protocol.login.LoginProtocols
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryAnswerPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerboundLoginAcknowledgedPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
- net.minecraft.network.protocol.ping.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.ping.ClientPongPacketListener
- net.minecraft.network.protocol.ping.package-info
+ net.minecraft.network.protocol.ping.PingPacketTypes
+ net.minecraft.network.protocol.ping.ServerboundPingRequestPacket
- net.minecraft.network.protocol.ping.ServerPingPacketListener
- net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
+ net.minecraft.network.protocol.status.ServerStatus
- net.minecraft.network.protocol.status.ServerStatus$Favicon
+ net.minecraft.network.protocol.status.ServerStatus$Players
- net.minecraft.network.protocol.status.ServerStatus$Version
+ net.minecraft.network.protocol.status.ServerStatusPacketListener
+ net.minecraft.network.protocol.status.StatusPacketTypes
- net.minecraft.network.protocol.status.StatusProtocols
- net.minecraft.network.ProtocolInfo
+ net.minecraft.network.ProtocolInfo$Unbound
- net.minecraft.network.ProtocolSwapHandler
+ net.minecraft.network.RateKickingConnection
- net.minecraft.network.RegistryFriendlyByteBuf
+ net.minecraft.network.ServerboundPacketListener
- net.minecraft.network.SkipPacketException
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializer$ForValueType
+ net.minecraft.network.syncher.EntityDataSerializers
- net.minecraft.network.syncher.EntityDataSerializers$1
+ net.minecraft.network.syncher.EntityDataSerializers$2
- net.minecraft.network.syncher.EntityDataSerializers$3
+ net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.network.syncher.SynchedEntityData$DataValue
+ net.minecraft.network.TickablePacketListener
- net.minecraft.network.UnconfiguredPipelineHandler
+ net.minecraft.network.UnconfiguredPipelineHandler$Inbound
- net.minecraft.network.UnconfiguredPipelineHandler$InboundConfigurationTask
+ net.minecraft.network.UnconfiguredPipelineHandler$Outbound
- net.minecraft.network.UnconfiguredPipelineHandler$OutboundConfigurationTask
+ net.minecraft.network.Utf8String
- net.minecraft.network.VarInt
- net.minecraft.network.Varint21FrameDecoder
+ net.minecraft.network.Varint21LengthFieldPrepender
+ net.minecraft.network.VarLong
- net.minecraft.obfuscate.DontObfuscate
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.realms.DisconnectedRealmsScreen
+ net.minecraft.realms.package-info
- net.minecraft.realms.RealmsConnect
+ net.minecraft.realms.RealmsConnect$1
- net.minecraft.realms.RealmsLabel
+ net.minecraft.realms.RealmsObjectSelectionList
- net.minecraft.realms.RealmsScreen
+ net.minecraft.realms.RepeatedNarrator
- net.minecraft.realms.RepeatedNarrator$Params
- net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.references.Blocks
- net.minecraft.references.Items
+ net.minecraft.resources.DelegatingOps
- net.minecraft.resources.FileToIdConverter
+ net.minecraft.resources.HolderSetCodec
+ net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataLoader
+ net.minecraft.resources.RegistryDataLoader$1
- net.minecraft.resources.RegistryDataLoader$Loader
+ net.minecraft.resources.RegistryDataLoader$LoadingFunction
- net.minecraft.resources.RegistryDataLoader$RegistryData
+ net.minecraft.resources.RegistryFileCodec
- net.minecraft.resources.RegistryFixedCodec
+ net.minecraft.resources.RegistryOps
- net.minecraft.resources.RegistryOps$1
+ net.minecraft.resources.RegistryOps$2
- net.minecraft.resources.RegistryOps$RegistryInfo
+ net.minecraft.resources.RegistryOps$RegistryInfoLookup
- net.minecraft.resources.ResourceKey
+ net.minecraft.resources.ResourceKey$InternKey
- net.minecraft.resources.ResourceLocation
+ net.minecraft.resources.ResourceLocation$Dummy
- net.minecraft.resources.ResourceLocation$Serializer
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator$Output
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
- net.minecraft.server.advancements.package-info
- net.minecraft.server.Bootstrap
+ net.minecraft.server.Bootstrap$1
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
- net.minecraft.server.ChainedJsonException
+ net.minecraft.server.ChainedJsonException$Entry
- net.minecraft.server.chase.ChaseClient
+ net.minecraft.server.chase.ChaseClient$TeleportTarget
- net.minecraft.server.chase.ChaseServer
+ net.minecraft.server.chase.ChaseServer$PlayerPosition
- net.minecraft.server.chase.package-info
+ net.minecraft.server.commands.AdvancementCommands
- net.minecraft.server.commands.AdvancementCommands$Action
+ net.minecraft.server.commands.AdvancementCommands$Action$1
- net.minecraft.server.commands.AdvancementCommands$Action$2
+ net.minecraft.server.commands.AdvancementCommands$Mode
- net.minecraft.server.commands.AttributeCommand
+ net.minecraft.server.commands.BanIpCommands
- net.minecraft.server.commands.BanListCommands
+ net.minecraft.server.commands.BanPlayerCommands
- net.minecraft.server.commands.BossBarCommands
+ net.minecraft.server.commands.ChaseCommand
- net.minecraft.server.commands.ClearInventoryCommands
+ net.minecraft.server.commands.CloneCommands
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$CommandFunction
- net.minecraft.server.commands.CloneCommands$DimensionAndPosition
+ net.minecraft.server.commands.CloneCommands$Mode
- net.minecraft.server.commands.DamageCommand
- net.minecraft.server.commands.data.BlockDataAccessor
+ net.minecraft.server.commands.data.BlockDataAccessor$1
- net.minecraft.server.commands.data.DataAccessor
+ net.minecraft.server.commands.data.DataCommands
- net.minecraft.server.commands.data.DataCommands$DataManipulator
+ net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
- net.minecraft.server.commands.data.DataCommands$DataProvider
+ net.minecraft.server.commands.data.DataCommands$StringProcessor
- net.minecraft.server.commands.data.EntityDataAccessor
+ net.minecraft.server.commands.data.EntityDataAccessor$1
- net.minecraft.server.commands.data.package-info
- net.minecraft.server.commands.data.StorageDataAccessor
+ net.minecraft.server.commands.data.StorageDataAccessor$1
+ net.minecraft.server.commands.DataPackCommand
- net.minecraft.server.commands.DataPackCommand$Inserter
- net.minecraft.server.commands.DebugCommand
+ net.minecraft.server.commands.DebugCommand$TraceCustomExecutor
- net.minecraft.server.commands.DebugCommand$TraceCustomExecutor$1
+ net.minecraft.server.commands.DebugCommand$Tracer
- net.minecraft.server.commands.DebugConfigCommand
+ net.minecraft.server.commands.DebugMobSpawningCommand
- net.minecraft.server.commands.DebugPathCommand
+ net.minecraft.server.commands.DefaultGameModeCommands
+ net.minecraft.server.commands.DeOpCommands
- net.minecraft.server.commands.DifficultyCommand
+ net.minecraft.server.commands.EffectCommands
- net.minecraft.server.commands.EmoteCommands
+ net.minecraft.server.commands.EnchantCommand
- net.minecraft.server.commands.ExecuteCommand
+ net.minecraft.server.commands.ExecuteCommand$CommandGetter
- net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
+ net.minecraft.server.commands.ExecuteCommand$CommandPredicate
- net.minecraft.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
+ net.minecraft.server.commands.ExecuteCommand$IntBiPredicate
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillBiomeCommand
+ net.minecraft.server.commands.FillCommand
- net.minecraft.server.commands.FillCommand$Mode
+ net.minecraft.server.commands.ForceLoadCommand
- net.minecraft.server.commands.FunctionCommand
+ net.minecraft.server.commands.FunctionCommand$1
- net.minecraft.server.commands.FunctionCommand$1Accumulator
+ net.minecraft.server.commands.FunctionCommand$2
- net.minecraft.server.commands.FunctionCommand$3
+ net.minecraft.server.commands.FunctionCommand$4
- net.minecraft.server.commands.FunctionCommand$5
+ net.minecraft.server.commands.FunctionCommand$Callbacks
- net.minecraft.server.commands.FunctionCommand$FunctionCustomExecutor
+ net.minecraft.server.commands.GameModeCommand
- net.minecraft.server.commands.GameRuleCommand
+ net.minecraft.server.commands.GameRuleCommand$1
- net.minecraft.server.commands.GiveCommand
+ net.minecraft.server.commands.HelpCommand
- net.minecraft.server.commands.ItemCommands
+ net.minecraft.server.commands.JfrCommand
- net.minecraft.server.commands.KickCommand
+ net.minecraft.server.commands.KillCommand
- net.minecraft.server.commands.ListPlayersCommand
+ net.minecraft.server.commands.LocateCommand
- net.minecraft.server.commands.LootCommand
+ net.minecraft.server.commands.LootCommand$Callback
- net.minecraft.server.commands.LootCommand$DropConsumer
+ net.minecraft.server.commands.LootCommand$TailProvider
- net.minecraft.server.commands.MsgCommand
+ net.minecraft.server.commands.OpCommand
+ net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PerfCommand
- net.minecraft.server.commands.PlaceCommand
+ net.minecraft.server.commands.PlaySoundCommand
- net.minecraft.server.commands.PublishCommand
+ net.minecraft.server.commands.RaidCommand
- net.minecraft.server.commands.RandomCommand
+ net.minecraft.server.commands.RecipeCommand
- net.minecraft.server.commands.ReloadCommand
+ net.minecraft.server.commands.ResetChunksCommand
- net.minecraft.server.commands.ReturnCommand
+ net.minecraft.server.commands.ReturnCommand$ReturnFailCustomExecutor
- net.minecraft.server.commands.ReturnCommand$ReturnFromCommandCustomModifier
+ net.minecraft.server.commands.ReturnCommand$ReturnValueCustomExecutor
- net.minecraft.server.commands.RideCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.ScoreboardCommand$NumberFormatCommandExecutor
- net.minecraft.server.commands.SeedCommand
+ net.minecraft.server.commands.ServerPackCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpawnArmorTrimsCommand
+ net.minecraft.server.commands.SpectateCommand
- net.minecraft.server.commands.SpreadPlayersCommand
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
+ net.minecraft.server.commands.TickCommand
- net.minecraft.server.commands.TimeCommand
+ net.minecraft.server.commands.TitleCommand
- net.minecraft.server.commands.TransferCommand
+ net.minecraft.server.commands.TriggerCommand
- net.minecraft.server.commands.WardenSpawnTrackerCommand
+ net.minecraft.server.commands.WeatherCommand
- net.minecraft.server.commands.WhitelistCommand
+ net.minecraft.server.commands.WorldBorderCommand
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerProperties$WorldDimensionData
+ net.minecraft.server.dedicated.DedicatedServerSettings
- net.minecraft.server.dedicated.package-info
- net.minecraft.server.dedicated.ServerWatchdog
+ net.minecraft.server.dedicated.ServerWatchdog$1
- net.minecraft.server.dedicated.Settings
+ net.minecraft.server.dedicated.Settings$MutableValue
- net.minecraft.server.Eula
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
+ net.minecraft.server.level.ChunkHolder$LevelChangeListener
- net.minecraft.server.level.ChunkHolder$PlayerProvider
+ net.minecraft.server.level.ChunkLevel
- net.minecraft.server.level.ChunkLevel$1
+ net.minecraft.server.level.ChunkMap
- net.minecraft.server.level.ChunkMap$1
+ net.minecraft.server.level.ChunkMap$2
- net.minecraft.server.level.ChunkMap$DistanceManager
+ net.minecraft.server.level.ChunkMap$TrackedEntity
- net.minecraft.server.level.ChunkTaskPriorityQueue
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
- net.minecraft.server.level.ChunkTracker
+ net.minecraft.server.level.ChunkTrackingView
- net.minecraft.server.level.ChunkTrackingView$1
+ net.minecraft.server.level.ChunkTrackingView$Positioned
- net.minecraft.server.level.ClientInformation
+ net.minecraft.server.level.ColumnPos
- net.minecraft.server.level.DemoMode
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.FullChunkStatus
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
+ net.minecraft.server.level.ServerChunkCache$ChunkAndHolder
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
+ net.minecraft.server.level.ServerLevel$EntityCallbacks
- net.minecraft.server.level.ServerPlayer
+ net.minecraft.server.level.ServerPlayer$1
- net.minecraft.server.level.ServerPlayer$2
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.TickingTracker
+ net.minecraft.server.level.WorldGenRegion
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.Main
+ net.minecraft.server.Main$1
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$ReloadableResources
+ net.minecraft.server.MinecraftServer$ServerResourcePackInfo
- net.minecraft.server.MinecraftServer$TimeProfiler
+ net.minecraft.server.MinecraftServer$TimeProfiler$1
+ net.minecraft.server.network.CommonListenerCookie
+ net.minecraft.server.network.config.JoinWorldTask
+ net.minecraft.server.network.config.package-info
- net.minecraft.server.network.config.ServerResourcePackConfigurationTask
- net.minecraft.server.network.ConfigurationTask
+ net.minecraft.server.network.ConfigurationTask$Type
- net.minecraft.server.network.FilteredText
+ net.minecraft.server.network.LegacyProtocolUtils
- net.minecraft.server.network.LegacyQueryHandler
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
- net.minecraft.server.network.package-info
- net.minecraft.server.network.PlayerChunkSender
+ net.minecraft.server.network.ServerCommonPacketListenerImpl
- net.minecraft.server.network.ServerConfigurationPacketListenerImpl
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
+ net.minecraft.server.network.TextFilterClient
- net.minecraft.server.network.TextFilterClient$IgnoreStrategy
+ net.minecraft.server.network.TextFilterClient$JoinOrLeaveEncoder
- net.minecraft.server.network.TextFilterClient$MessageEncoder
+ net.minecraft.server.network.TextFilterClient$PlayerContext
- net.minecraft.server.network.TextFilterClient$RequestFailedException
+ net.minecraft.server.package-info
- net.minecraft.server.packs.AbstractPackResources
+ net.minecraft.server.packs.BuiltInMetadata
- net.minecraft.server.packs.CompositePackResources
+ net.minecraft.server.packs.DownloadCacheCleaner
- net.minecraft.server.packs.DownloadCacheCleaner$1
+ net.minecraft.server.packs.DownloadCacheCleaner$PathAndPriority
- net.minecraft.server.packs.DownloadCacheCleaner$PathAndTime
+ net.minecraft.server.packs.DownloadQueue
- net.minecraft.server.packs.DownloadQueue$BatchConfig
+ net.minecraft.server.packs.DownloadQueue$BatchResult
- net.minecraft.server.packs.DownloadQueue$DownloadRequest
+ net.minecraft.server.packs.DownloadQueue$FileInfoEntry
- net.minecraft.server.packs.DownloadQueue$LogEntry
+ net.minecraft.server.packs.FeatureFlagsMetadataSection
- net.minecraft.server.packs.FilePackResources
+ net.minecraft.server.packs.FilePackResources$FileResourcesSupplier
- net.minecraft.server.packs.FilePackResources$SharedZipFileAccess
- net.minecraft.server.packs.linkfs.DummyFileAttributes
+ net.minecraft.server.packs.linkfs.LinkFileSystem
- net.minecraft.server.packs.linkfs.LinkFileSystem$Builder
+ net.minecraft.server.packs.linkfs.LinkFileSystem$DirectoryEntry
+ net.minecraft.server.packs.linkfs.LinkFSFileStore
- net.minecraft.server.packs.linkfs.LinkFSPath
+ net.minecraft.server.packs.linkfs.LinkFSPath$1
- net.minecraft.server.packs.linkfs.LinkFSPath$2
+ net.minecraft.server.packs.linkfs.LinkFSPath$3
- net.minecraft.server.packs.linkfs.LinkFSProvider
+ net.minecraft.server.packs.linkfs.LinkFSProvider$1
- net.minecraft.server.packs.linkfs.LinkFSProvider$2
+ net.minecraft.server.packs.linkfs.package-info
- net.minecraft.server.packs.linkfs.PathContents
+ net.minecraft.server.packs.linkfs.PathContents$1
- net.minecraft.server.packs.linkfs.PathContents$2
+ net.minecraft.server.packs.linkfs.PathContents$DirectoryContents
- net.minecraft.server.packs.linkfs.PathContents$FileContents
- net.minecraft.server.packs.metadata.MetadataSectionSerializer
+ net.minecraft.server.packs.metadata.MetadataSectionType
- net.minecraft.server.packs.metadata.MetadataSectionType$1
- net.minecraft.server.packs.metadata.pack.package-info
+ net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.package-info
+ net.minecraft.server.packs.OverlayMetadataSection
- net.minecraft.server.packs.OverlayMetadataSection$OverlayEntry
- net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackResources
- net.minecraft.server.packs.PackResources$ResourceOutput
+ net.minecraft.server.packs.PackType
- net.minecraft.server.packs.PathPackResources
+ net.minecraft.server.packs.PathPackResources$PathResourcesSupplier
+ net.minecraft.server.packs.repository.BuiltInPackSource
- net.minecraft.server.packs.repository.BuiltInPackSource$1
+ net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.FolderRepositorySource$FolderPackDetector
+ net.minecraft.server.packs.repository.Pack
- net.minecraft.server.packs.repository.Pack$Info
+ net.minecraft.server.packs.repository.Pack$Position
- net.minecraft.server.packs.repository.Pack$ResourcesSupplier
- net.minecraft.server.packs.repository.package-info
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackDetector
+ net.minecraft.server.packs.repository.PackRepository
- net.minecraft.server.packs.repository.PackSource
+ net.minecraft.server.packs.repository.PackSource$1
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
+ net.minecraft.server.packs.resources.CloseableResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager
+ net.minecraft.server.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
- net.minecraft.server.packs.resources.FallbackResourceManager$EntryStack
+ net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- net.minecraft.server.packs.resources.FallbackResourceManager$PackEntry
+ net.minecraft.server.packs.resources.FallbackResourceManager$ResourceWithSource
- net.minecraft.server.packs.resources.IoSupplier
+ net.minecraft.server.packs.resources.MultiPackResourceManager
- net.minecraft.server.packs.resources.package-info
- net.minecraft.server.packs.resources.PreparableReloadListener
+ net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
- net.minecraft.server.packs.resources.ProfiledReloadInstance
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$State
+ net.minecraft.server.packs.resources.ReloadableResourceManager
- net.minecraft.server.packs.resources.ReloadInstance
- net.minecraft.server.packs.resources.Resource
+ net.minecraft.server.packs.resources.ResourceFilterSection
- net.minecraft.server.packs.resources.ResourceManager
+ net.minecraft.server.packs.resources.ResourceManager$Empty
- net.minecraft.server.packs.resources.ResourceManagerReloadListener
+ net.minecraft.server.packs.resources.ResourceMetadata
- net.minecraft.server.packs.resources.ResourceMetadata$1
+ net.minecraft.server.packs.resources.ResourceMetadata$2
- net.minecraft.server.packs.resources.ResourceMetadata$Builder
+ net.minecraft.server.packs.resources.ResourceMetadata$Builder$1
- net.minecraft.server.packs.resources.ResourceProvider
+ net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
- net.minecraft.server.packs.resources.SimplePreparableReloadListener
+ net.minecraft.server.packs.resources.SimpleReloadInstance
- net.minecraft.server.packs.resources.SimpleReloadInstance$1
+ net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
- net.minecraft.server.packs.VanillaPackResources
+ net.minecraft.server.packs.VanillaPackResourcesBuilder
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$Data
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
- net.minecraft.server.RegistryLayer
+ net.minecraft.server.ReloadableServerResources
- net.minecraft.server.ReloadableServerResources$1
- net.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup$1
- net.minecraft.server.RunningOnDifferentThreadException
+ net.minecraft.server.ServerAdvancementManager
- net.minecraft.server.ServerFunctionLibrary
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerInfo
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerScoreboard
+ net.minecraft.server.ServerScoreboard$Method
- net.minecraft.server.ServerTickRateManager
+ net.minecraft.server.Services
- net.minecraft.server.TickTask
+ net.minecraft.server.WorldLoader
- net.minecraft.server.WorldLoader$DataLoadContext
+ net.minecraft.server.WorldLoader$DataLoadOutput
- net.minecraft.server.WorldLoader$InitConfig
+ net.minecraft.server.WorldLoader$PackConfig
- net.minecraft.server.WorldLoader$ResultFactory
+ net.minecraft.server.WorldLoader$WorldDataSupplier
- net.minecraft.server.WorldStem
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
+ net.minecraft.tags.BannerPatternTags
- net.minecraft.tags.BiomeTags
+ net.minecraft.tags.BlockTags
- net.minecraft.tags.CatVariantTags
+ net.minecraft.tags.DamageTypeTags
- net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.FlatLevelGeneratorPresetTags
- net.minecraft.tags.FluidTags
+ net.minecraft.tags.GameEventTags
- net.minecraft.tags.InstrumentTags
+ net.minecraft.tags.ItemTags
- net.minecraft.tags.package-info
- net.minecraft.tags.PaintingVariantTags
+ net.minecraft.tags.PoiTypeTags
- net.minecraft.tags.StructureTags
+ net.minecraft.tags.TagBuilder
- net.minecraft.tags.TagEntry
+ net.minecraft.tags.TagEntry$Lookup
- net.minecraft.tags.TagFile
+ net.minecraft.tags.TagKey
- net.minecraft.tags.TagLoader
+ net.minecraft.tags.TagLoader$1
- net.minecraft.tags.TagLoader$EntryWithSource
+ net.minecraft.tags.TagLoader$SortingEntry
- net.minecraft.tags.TagManager
+ net.minecraft.tags.TagManager$LoadResult
- net.minecraft.tags.TagNetworkSerialization
+ net.minecraft.tags.TagNetworkSerialization$NetworkPayload
- net.minecraft.tags.TagNetworkSerialization$TagOutput
+ net.minecraft.tags.WorldPresetTags
+ net.minecraft.util.AbortableIterationConsumer
- net.minecraft.util.AbortableIterationConsumer$Continuation
+ net.minecraft.util.ArrayListDeque
- net.minecraft.util.ArrayListDeque$DescendingIterator
+ net.minecraft.util.BitStorage
- net.minecraft.util.Brightness
+ net.minecraft.util.ByIdMap
- net.minecraft.util.ByIdMap$1
+ net.minecraft.util.ByIdMap$OutOfBoundsStrategy
- net.minecraft.util.ClassInstanceMultiMap
+ net.minecraft.util.ColorRGBA
- net.minecraft.util.CommonColors
+ net.minecraft.util.CommonLinks
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.Crypt$ByteArrayToKeyFunction
+ net.minecraft.util.Crypt$SaltSignaturePair
- net.minecraft.util.Crypt$SaltSupplier
+ net.minecraft.util.CryptException
- net.minecraft.util.CsvOutput
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
- net.minecraft.util.CubicSpline
+ net.minecraft.util.CubicSpline$1Point
- net.minecraft.util.CubicSpline$Builder
+ net.minecraft.util.CubicSpline$Constant
- net.minecraft.util.CubicSpline$CoordinateVisitor
+ net.minecraft.util.CubicSpline$Multipoint
+ net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.fixes.CauldronRenameFix
+ net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
- net.minecraft.util.datafix.fixes.ChestedHorsesInventoryZeroIndexingFix
- net.minecraft.util.datafix.fixes.HorseBodyArmorItemFix
+ net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
- net.minecraft.util.datafix.fixes.ItemBannerColorFix
+ net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.ItemIdFix
+ net.minecraft.util.datafix.fixes.ItemLoreFix
- net.minecraft.util.datafix.fixes.ItemPotionFix
+ net.minecraft.util.datafix.fixes.ItemRemoveBlockEntityTagFix
- net.minecraft.util.datafix.fixes.ItemRenameFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix$1
- net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.ItemSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
+ net.minecraft.util.datafix.fixes.ItemStackMapIdFix
- net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackTagFix
- net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
+ net.minecraft.util.datafix.fixes.ItemStackUUIDFix
- net.minecraft.util.datafix.fixes.ItemWaterPotionFix
+ net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- net.minecraft.util.datafix.fixes.JigsawPropertiesFix
+ net.minecraft.util.datafix.fixes.JigsawRotationFix
- net.minecraft.util.datafix.fixes.LeavesFix
+ net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
- net.minecraft.util.datafix.fixes.LeavesFix$Section
+ net.minecraft.util.datafix.fixes.LegacyDragonFightFix
- net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
+ net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
- net.minecraft.util.datafix.fixes.LevelLegacyWorldGenSettingsFix
+ net.minecraft.util.datafix.fixes.LevelUUIDFix
- net.minecraft.util.datafix.fixes.MapIdFix
+ net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
- net.minecraft.util.datafix.fixes.MissingDimensionFix
+ net.minecraft.util.datafix.fixes.MobEffectIdFix
- net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ net.minecraft.util.datafix.fixes.NamedEntityFix
- net.minecraft.util.datafix.fixes.NamedEntityWriteReadFix
+ net.minecraft.util.datafix.fixes.NamespacedTypeRenameFix
- net.minecraft.util.datafix.fixes.NewVillageFix
+ net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
- net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
+ net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
- net.minecraft.util.datafix.fixes.OminousBannerRenameFix
+ net.minecraft.util.datafix.fixes.OptionsAccessibilityOnboardFix
- net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
+ net.minecraft.util.datafix.fixes.OptionsAmbientOcclusionFix
- net.minecraft.util.datafix.fixes.OptionsForceVBOFix
+ net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
- net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
+ net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
- net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
+ net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
- net.minecraft.util.datafix.fixes.OverreachingTickFix
- net.minecraft.util.datafix.fixes.package-info
+ net.minecraft.util.datafix.fixes.PlayerUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
+ net.minecraft.util.datafix.fixes.PoiTypeRenameFix
- net.minecraft.util.datafix.fixes.PrimedTntBlockStateFixer
+ net.minecraft.util.datafix.fixes.RandomSequenceSettingsFix
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
+ net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.fixes.RemapChunkStatusFix
+ net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
- net.minecraft.util.datafix.fixes.RenameEnchantmentsFix
+ net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.ScoreboardDisplaySlotFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.SpawnerDataFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix$StatType
- net.minecraft.util.datafix.fixes.StatsRenameFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
- net.minecraft.util.datafix.fixes.TeamDisplayNameFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ net.minecraft.util.datafix.fixes.VariantRenameFix
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WeaponSmithChestLootTableFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.WriteAndReadFix
+ net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
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
+ net.minecraft.util.datafix.schemas.V1451_6$1
- net.minecraft.util.datafix.schemas.V1451_6$2
+ net.minecraft.util.datafix.schemas.V1460
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
- net.minecraft.util.datafix.schemas.V2571
+ net.minecraft.util.datafix.schemas.V2684
- net.minecraft.util.datafix.schemas.V2686
+ net.minecraft.util.datafix.schemas.V2688
- net.minecraft.util.datafix.schemas.V2704
+ net.minecraft.util.datafix.schemas.V2707
- net.minecraft.util.datafix.schemas.V2831
+ net.minecraft.util.datafix.schemas.V2832
- net.minecraft.util.datafix.schemas.V2842
+ net.minecraft.util.datafix.schemas.V3076
- net.minecraft.util.datafix.schemas.V3078
+ net.minecraft.util.datafix.schemas.V3081
- net.minecraft.util.datafix.schemas.V3082
+ net.minecraft.util.datafix.schemas.V3083
- net.minecraft.util.datafix.schemas.V3202
+ net.minecraft.util.datafix.schemas.V3203
- net.minecraft.util.datafix.schemas.V3204
+ net.minecraft.util.datafix.schemas.V3325
- net.minecraft.util.datafix.schemas.V3326
+ net.minecraft.util.datafix.schemas.V3327
- net.minecraft.util.datafix.schemas.V3328
+ net.minecraft.util.datafix.schemas.V3438
- net.minecraft.util.datafix.schemas.V3448
+ net.minecraft.util.datafix.schemas.V3682
- net.minecraft.util.datafix.schemas.V3683
+ net.minecraft.util.datafix.schemas.V3685
- net.minecraft.util.datafix.schemas.V3689
+ net.minecraft.util.datafix.schemas.V3799
- net.minecraft.util.datafix.schemas.V3807
- net.minecraft.util.datafix.schemas.V3808_1
- net.minecraft.util.DebugBuffer
- net.minecraft.util.debugchart.AbstractSampleLogger
- net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
- net.minecraft.util.debugchart.LocalSampleLogger
- net.minecraft.util.debugchart.RemoteSampleLogger
+ net.minecraft.util.debugchart.SampleLogger
- net.minecraft.util.debugchart.SampleStorage
+ net.minecraft.util.DelegateDataOutput
- net.minecraft.util.DependencySorter
+ net.minecraft.util.DependencySorter$Entry
- net.minecraft.util.DirectoryLock
+ net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.ExceptionCollector
+ net.minecraft.util.ExtraCodecs
- net.minecraft.util.ExtraCodecs$1
+ net.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- net.minecraft.util.ExtraCodecs$2
+ net.minecraft.util.ExtraCodecs$3
- net.minecraft.util.ExtraCodecs$4
+ net.minecraft.util.ExtraCodecs$5
- net.minecraft.util.ExtraCodecs$6
+ net.minecraft.util.ExtraCodecs$EitherCodec
- net.minecraft.util.ExtraCodecs$RecursiveCodec
- net.minecraft.world.effect.MobEffectInstance$Details
- net.minecraft.world.effect.MobEffects
+ net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.package-info
+ net.minecraft.world.effect.PoisonMobEffect
- net.minecraft.world.effect.RegenerationMobEffect
+ net.minecraft.world.effect.SaturationMobEffect
- net.minecraft.world.effect.WitherMobEffect
- net.minecraft.world.entity.AgeableMob
+ net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.AttributeInstance
- net.minecraft.world.entity.ai.attributes.AttributeMap
+ net.minecraft.world.entity.ai.attributes.AttributeModifier
- net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
+ net.minecraft.world.entity.ai.attributes.Attributes
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier
- net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
- net.minecraft.world.entity.ai.attributes.DefaultAttributes
- net.minecraft.world.entity.ai.attributes.package-info
+ net.minecraft.world.entity.ai.attributes.RangedAttribute
+ net.minecraft.world.entity.ai.behavior.AcquirePoi
- net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
+ net.minecraft.world.entity.ai.behavior.AnimalMakeLove
- net.minecraft.world.entity.ai.behavior.AnimalPanic
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BabyFollowAdult
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorControl
- net.minecraft.world.entity.ai.behavior.BehaviorUtils
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
+ net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
- net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
+ net.minecraft.world.entity.ai.behavior.Croak
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$2
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$3
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$4
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$5
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$Mu
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Mu
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWithResult
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
- net.minecraft.world.entity.ai.behavior.declarative.MemoryAccessor
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Absent
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Present
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Registered
- net.minecraft.world.entity.ai.behavior.declarative.package-info
+ net.minecraft.world.entity.ai.behavior.declarative.Trigger
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
- net.minecraft.world.entity.ai.behavior.GoToClosestVillage
+ net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
- net.minecraft.world.entity.ai.behavior.GoToTargetLocation
+ net.minecraft.world.entity.ai.behavior.GoToWantedItem
- net.minecraft.world.entity.ai.behavior.HarvestFarmland
+ net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
- net.minecraft.world.entity.ai.behavior.InteractWith
+ net.minecraft.world.entity.ai.behavior.InteractWithDoor
- net.minecraft.world.entity.ai.behavior.JumpOnBed
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlace
- net.minecraft.world.entity.ai.behavior.LongJumpMidJump
+ net.minecraft.world.entity.ai.behavior.LongJumpToPreferredBlock
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
- net.minecraft.world.entity.ai.behavior.LongJumpUtil
+ net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
- net.minecraft.world.entity.ai.behavior.LookAtTargetSink
+ net.minecraft.world.entity.ai.behavior.MeleeAttack
- net.minecraft.world.entity.ai.behavior.Mount
+ net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
- net.minecraft.world.entity.ai.behavior.MoveToTargetSink
+ net.minecraft.world.entity.ai.behavior.OneShot
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ net.minecraft.world.entity.ai.behavior.RamTarget
- net.minecraft.world.entity.ai.behavior.RandomLookAround
+ net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.ReactToBell
+ net.minecraft.world.entity.ai.behavior.ResetProfession
- net.minecraft.world.entity.ai.behavior.ResetRaidStatus
+ net.minecraft.world.entity.ai.behavior.RingBell
- net.minecraft.world.entity.ai.behavior.RunOne
+ net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes
- net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes$Ticker
+ net.minecraft.world.entity.ai.behavior.SetHiddenState
- net.minecraft.world.entity.ai.behavior.SetLookAndInteract
+ net.minecraft.world.entity.ai.behavior.SetRaidStatus
- net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
- net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
+ net.minecraft.world.entity.ai.behavior.ShufflingList
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.SleepInBed
+ net.minecraft.world.entity.ai.behavior.SocializeAtBell
- net.minecraft.world.entity.ai.behavior.StartAttacking
+ net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
- net.minecraft.world.entity.ai.behavior.StayCloseToTarget
+ net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
- net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StrollAroundPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoiList
- net.minecraft.world.entity.ai.behavior.Swim
+ net.minecraft.world.entity.ai.behavior.TradeWithVillager
- net.minecraft.world.entity.ai.behavior.TriggerGate
+ net.minecraft.world.entity.ai.behavior.TryFindLand
- net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
+ net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
- net.minecraft.world.entity.ai.behavior.UseBonemeal
+ net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.warden.Digging
+ net.minecraft.world.entity.ai.behavior.warden.Emerging
- net.minecraft.world.entity.ai.behavior.warden.ForceUnmount
+ net.minecraft.world.entity.ai.behavior.warden.package-info
+ net.minecraft.world.entity.ai.behavior.warden.Roar
- net.minecraft.world.entity.ai.behavior.warden.SetRoarTarget
+ net.minecraft.world.entity.ai.behavior.warden.SetWardenLookTarget
- net.minecraft.world.entity.ai.behavior.warden.Sniffing
+ net.minecraft.world.entity.ai.behavior.warden.SonicBoom
- net.minecraft.world.entity.ai.behavior.warden.TryToSniff
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
- net.minecraft.world.entity.ai.control.BodyRotationControl
+ net.minecraft.world.entity.ai.control.Control
- net.minecraft.world.entity.ai.control.FlyingMoveControl
+ net.minecraft.world.entity.ai.control.JumpControl
- net.minecraft.world.entity.ai.control.LookControl
+ net.minecraft.world.entity.ai.control.MoveControl
- net.minecraft.world.entity.ai.control.MoveControl$Operation
+ net.minecraft.world.entity.ai.control.package-info
+ net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
- net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
- net.minecraft.world.entity.ai.goal.AvoidEntityGoal
+ net.minecraft.world.entity.ai.goal.BegGoal
- net.minecraft.world.entity.ai.goal.BoatGoals
+ net.minecraft.world.entity.ai.goal.BreakDoorGoal
- net.minecraft.world.entity.ai.goal.BreathAirGoal
+ net.minecraft.world.entity.ai.goal.BreedGoal
- net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
+ net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
- net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
+ net.minecraft.world.entity.ai.goal.DolphinJumpGoal
- net.minecraft.world.entity.ai.goal.DoorInteractGoal
+ net.minecraft.world.entity.ai.goal.EatBlockGoal
- net.minecraft.world.entity.ai.goal.FleeSunGoal
+ net.minecraft.world.entity.ai.goal.FloatGoal
- net.minecraft.world.entity.ai.goal.FollowBoatGoal
+ net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
- net.minecraft.world.entity.ai.goal.FollowMobGoal
+ net.minecraft.world.entity.ai.goal.FollowOwnerGoal
- net.minecraft.world.entity.ai.goal.FollowParentGoal
+ net.minecraft.world.entity.ai.goal.Goal
- net.minecraft.world.entity.ai.goal.Goal$Flag
+ net.minecraft.world.entity.ai.goal.GoalSelector
- net.minecraft.world.entity.ai.goal.GoalSelector$1
+ net.minecraft.world.entity.ai.goal.GoalSelector$2
- net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
+ net.minecraft.world.entity.ai.goal.InteractGoal
- net.minecraft.world.entity.ai.goal.JumpGoal
+ net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
- net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
+ net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
- net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
+ net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
- net.minecraft.world.entity.ai.goal.MeleeAttackGoal
+ net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
+ net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
- net.minecraft.world.entity.ai.goal.RandomStandGoal
+ net.minecraft.world.entity.ai.goal.RandomStrollGoal
- net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
+ net.minecraft.world.entity.ai.goal.RangedAttackGoal
- net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ net.minecraft.world.entity.ai.goal.RemoveBlockGoal
- net.minecraft.world.entity.ai.goal.RestrictSunGoal
+ net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
- net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
+ net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
- net.minecraft.world.entity.ai.goal.SwellGoal
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
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
+ net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
+ net.minecraft.world.entity.ai.memory.package-info
- net.minecraft.world.entity.ai.memory.WalkTarget
- net.minecraft.world.entity.ai.navigation.AmphibiousPathNavigation
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
- net.minecraft.world.entity.ai.sensing.BreezeAttackEntitySensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.IsInWaterSensor
+ net.minecraft.world.entity.ai.sensing.MobSensor
- net.minecraft.world.entity.ai.sensing.NearestBedSensor
+ net.minecraft.world.entity.ai.sensing.NearestItemSensor
- net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
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
- net.minecraft.world.entity.ai.sensing.WardenEntitySensor
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
- net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
+ net.minecraft.world.entity.ai.village.poi.PoiTypes
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
+ net.minecraft.world.entity.ambient.AmbientCreature
- net.minecraft.world.entity.ambient.Bat
+ net.minecraft.world.entity.ambient.package-info
- net.minecraft.world.entity.animal.AbstractFish
+ net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
- net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
+ net.minecraft.world.entity.animal.AbstractGolem
- net.minecraft.world.entity.animal.AbstractSchoolingFish
+ net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ net.minecraft.world.entity.animal.allay.Allay
- net.minecraft.world.entity.animal.allay.Allay$JukeboxListener
+ net.minecraft.world.entity.animal.allay.Allay$VibrationUser
- net.minecraft.world.entity.animal.allay.AllayAi
+ net.minecraft.world.entity.animal.allay.package-info
- net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.armadillo.Armadillo
+ net.minecraft.world.entity.animal.armadillo.Armadillo$1
- net.minecraft.world.entity.animal.armadillo.Armadillo$2
+ net.minecraft.world.entity.animal.armadillo.Armadillo$ArmadilloState
- net.minecraft.world.entity.animal.armadillo.ArmadilloAi
+ net.minecraft.world.entity.animal.armadillo.ArmadilloAi$1
- net.minecraft.world.entity.animal.armadillo.ArmadilloAi$ArmadilloBallUp
+ net.minecraft.world.entity.animal.armadillo.ArmadilloAi$ArmadilloPanic
- net.minecraft.world.entity.animal.armadillo.package-info
+ net.minecraft.world.entity.animal.axolotl.Axolotl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
- net.minecraft.world.entity.animal.axolotl.AxolotlAi
+ net.minecraft.world.entity.animal.axolotl.package-info
+ net.minecraft.world.entity.animal.axolotl.PlayDead
- net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
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
- net.minecraft.world.entity.animal.camel.Camel
+ net.minecraft.world.entity.animal.camel.Camel$CamelBodyRotationControl
- net.minecraft.world.entity.animal.camel.Camel$CamelLookControl
+ net.minecraft.world.entity.animal.camel.Camel$CamelMoveControl
- net.minecraft.world.entity.animal.camel.CamelAi
+ net.minecraft.world.entity.animal.camel.CamelAi$CamelPanic
- net.minecraft.world.entity.animal.camel.CamelAi$RandomSitting
+ net.minecraft.world.entity.animal.camel.package-info
- net.minecraft.world.entity.animal.Cat
+ net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
- net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
+ net.minecraft.world.entity.animal.Cat$CatTemptGoal
- net.minecraft.world.entity.animal.CatVariant
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
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
- net.minecraft.world.entity.animal.frog.Frog
+ net.minecraft.world.entity.animal.frog.Frog$FrogLookControl
- net.minecraft.world.entity.animal.frog.Frog$FrogNodeEvaluator
+ net.minecraft.world.entity.animal.frog.Frog$FrogPathNavigation
- net.minecraft.world.entity.animal.frog.FrogAi
- net.minecraft.world.entity.animal.frog.package-info
+ net.minecraft.world.entity.animal.frog.ShootTongue
- net.minecraft.world.entity.animal.frog.ShootTongue$1
+ net.minecraft.world.entity.animal.frog.ShootTongue$State
- net.minecraft.world.entity.animal.frog.Tadpole
+ net.minecraft.world.entity.animal.frog.TadpoleAi
- net.minecraft.world.entity.animal.FrogVariant
+ net.minecraft.world.entity.animal.goat.Goat
- net.minecraft.world.entity.animal.goat.GoatAi
+ net.minecraft.world.entity.animal.goat.package-info
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse
+ net.minecraft.world.entity.animal.horse.AbstractHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse$2
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
+ net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
- net.minecraft.world.entity.animal.Parrot$Variant
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
- net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
- net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
+ net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
- net.minecraft.world.entity.animal.Rabbit$Variant
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$Base
- net.minecraft.world.entity.animal.TropicalFish$Pattern
+ net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
- net.minecraft.world.entity.animal.TropicalFish$Variant
+ net.minecraft.world.entity.animal.Turtle
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
- net.minecraft.world.entity.animal.Wolf$WolfPanicGoal
- net.minecraft.world.entity.AnimationState
+ net.minecraft.world.entity.AreaEffectCloud
- net.minecraft.world.entity.Attackable
+ net.minecraft.world.entity.Display
- net.minecraft.world.entity.Display$1
+ net.minecraft.world.entity.Display$BillboardConstraints
- net.minecraft.world.entity.Display$BlockDisplay
+ net.minecraft.world.entity.Display$BlockDisplay$BlockRenderState
- net.minecraft.world.entity.Display$ColorInterpolator
+ net.minecraft.world.entity.Display$FloatInterpolator
- net.minecraft.world.entity.Display$GenericInterpolator
+ net.minecraft.world.entity.Display$IntInterpolator
- net.minecraft.world.entity.Display$ItemDisplay
+ net.minecraft.world.entity.Display$ItemDisplay$1
- net.minecraft.world.entity.Display$ItemDisplay$ItemRenderState
+ net.minecraft.world.entity.Display$LinearFloatInterpolator
- net.minecraft.world.entity.Display$LinearIntInterpolator
+ net.minecraft.world.entity.Display$PosRotInterpolationTarget
- net.minecraft.world.entity.Display$RenderState
+ net.minecraft.world.entity.Display$TextDisplay
- net.minecraft.world.entity.Display$TextDisplay$Align
+ net.minecraft.world.entity.Display$TextDisplay$CachedInfo
- net.minecraft.world.entity.Display$TextDisplay$CachedLine
+ net.minecraft.world.entity.Display$TextDisplay$LineSplitter
- net.minecraft.world.entity.Display$TextDisplay$TextRenderState
+ net.minecraft.world.entity.Display$TransformationInterpolator
- net.minecraft.world.entity.Entity
+ net.minecraft.world.entity.Entity$1
- net.minecraft.world.entity.Entity$MoveFunction
+ net.minecraft.world.entity.Entity$MovementEmission
- net.minecraft.world.entity.Entity$RemovalReason
+ net.minecraft.world.entity.EntityAttachment
- net.minecraft.world.entity.EntityAttachment$Fallback
+ net.minecraft.world.entity.EntityAttachments
- net.minecraft.world.entity.EntityAttachments$Builder
+ net.minecraft.world.entity.EntityDimensions
- net.minecraft.world.entity.EntityEvent
+ net.minecraft.world.entity.EntitySelector
- net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ net.minecraft.world.entity.EntityType
- net.minecraft.world.entity.EntityType$1
+ net.minecraft.world.entity.EntityType$Builder
- net.minecraft.world.entity.EntityType$EntityFactory
+ net.minecraft.world.entity.EquipmentSlot
- net.minecraft.world.entity.EquipmentSlot$Type
+ net.minecraft.world.entity.ExperienceOrb
- net.minecraft.world.entity.FlyingMob
+ net.minecraft.world.entity.GlowSquid
- net.minecraft.world.entity.HasCustomInventoryScreen
+ net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.Interaction
+ net.minecraft.world.entity.Interaction$PlayerAction
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LerpingModel
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.LivingEntity$Fallsounds
+ net.minecraft.world.entity.Marker
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.RelativeMovement
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.Shearable
- net.minecraft.world.entity.SlotAccess
+ net.minecraft.world.entity.SlotAccess$1
- net.minecraft.world.entity.SlotAccess$2
+ net.minecraft.world.entity.SlotAccess$3
- net.minecraft.world.entity.SpawnGroupData
- net.minecraft.world.entity.SpawnPlacements
+ net.minecraft.world.entity.SpawnPlacements$Data
- net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
+ net.minecraft.world.entity.SpawnPlacementType
- net.minecraft.world.entity.SpawnPlacementTypes
+ net.minecraft.world.entity.SpawnPlacementTypes$1
+ net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.entity.Targeting
+ net.minecraft.world.entity.TraceableEntity
- net.minecraft.world.entity.VariantHolder
+ net.minecraft.world.entity.WalkAnimationState
- net.minecraft.world.item.AnimalArmorItem$BodyType
+ net.minecraft.world.item.AnimalArmorItem$Type
- net.minecraft.world.item.ArmorItem$Type
+ net.minecraft.world.item.ArmorMaterial
- net.minecraft.world.item.ArmorMaterial$Layer
+ net.minecraft.world.item.DyeableArmorItem
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BannerPatterns
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
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
+ net.minecraft.world.level.block.entity.BrushableBlockEntity
- net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
+ net.minecraft.world.level.block.entity.ChestLidController
- net.minecraft.world.level.block.entity.ChiseledBookShelfBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity$1
+ net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
- net.minecraft.world.level.block.entity.ComparatorBlockEntity
+ net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.ContainerOpenersCounter
+ net.minecraft.world.level.block.entity.CrafterBlockEntity
- net.minecraft.world.level.block.entity.CrafterBlockEntity$1
+ net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
- net.minecraft.world.level.block.entity.DecoratedPotBlockEntity
+ net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$Decorations
- net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$WobbleStyle
+ net.minecraft.world.level.block.entity.DecoratedPotPatterns
- net.minecraft.world.level.block.entity.DispenserBlockEntity
+ net.minecraft.world.level.block.entity.DropperBlockEntity
- net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
+ net.minecraft.world.level.block.entity.FurnaceBlockEntity
- net.minecraft.world.level.block.entity.HangingSignBlockEntity
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
+ net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
- net.minecraft.world.level.block.entity.SculkCatalystBlockEntity$CatalystListener
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity$VibrationUser
+ net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
- net.minecraft.world.level.block.entity.SculkShriekerBlockEntity$VibrationUser
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SignText
- net.minecraft.world.level.block.entity.SkullBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity$1
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
+ net.minecraft.world.level.block.entity.trialspawner.PlayerDetector
- net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector
- net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector$2
+ net.minecraft.world.level.block.entity.TrialSpawnerBlockEntity
- net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Client
- net.minecraft.world.level.block.entity.vault.VaultClientData
- net.minecraft.world.level.block.entity.vault.VaultServerData
- net.minecraft.world.level.block.entity.vault.VaultState
- net.minecraft.world.level.block.entity.vault.VaultState$2
- net.minecraft.world.level.block.entity.vault.VaultState$4
- net.minecraft.world.level.block.entity.vault.VaultState$LightLevel
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.TreeGrower
- net.minecraft.world.level.block.package-info
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
- net.minecraft.world.level.block.state.BlockBehaviour
+ net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
- net.minecraft.world.level.block.state.BlockBehaviour$OffsetFunction
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
- net.minecraft.world.level.block.state.predicate.BlockPredicate
+ net.minecraft.world.level.block.state.predicate.BlockStatePredicate
- net.minecraft.world.level.block.state.predicate.package-info
+ net.minecraft.world.level.block.state.properties.AttachFace
- net.minecraft.world.level.block.state.properties.BambooLeaves
+ net.minecraft.world.level.block.state.properties.BedPart
- net.minecraft.world.level.block.state.properties.BellAttachType
+ net.minecraft.world.level.block.state.properties.BlockSetType
- net.minecraft.world.level.block.state.properties.BlockSetType$PressurePlateSensitivity
+ net.minecraft.world.level.block.state.properties.BlockStateProperties
- net.minecraft.world.level.block.state.properties.BooleanProperty
+ net.minecraft.world.level.block.state.properties.ChestType
- net.minecraft.world.level.block.state.properties.ChestType$1
+ net.minecraft.world.level.block.state.properties.ComparatorMode
- net.minecraft.world.level.block.state.properties.DirectionProperty
+ net.minecraft.world.level.block.state.properties.DoorHingeSide
- net.minecraft.world.level.block.state.properties.DoubleBlockHalf
+ net.minecraft.world.level.block.state.properties.DripstoneThickness
- net.minecraft.world.level.block.state.properties.EnumProperty
+ net.minecraft.world.level.block.state.properties.Half
- net.minecraft.world.level.block.state.properties.IntegerProperty
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument$Type
- net.minecraft.world.level.block.state.properties.package-info
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.RotationSegment
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
- net.minecraft.world.level.block.VaultBlock
+ net.minecraft.world.level.block.VineBlock
- net.minecraft.world.level.block.VineBlock$1
+ net.minecraft.world.level.block.WallBannerBlock
- net.minecraft.world.level.block.WallBlock
+ net.minecraft.world.level.block.WallBlock$1
- net.minecraft.world.level.block.WallHangingSignBlock
+ net.minecraft.world.level.block.WallHangingSignBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WaterloggedTransparentBlock
+ net.minecraft.world.level.block.WeatheringCopper
- net.minecraft.world.level.block.WeatheringCopper$WeatherState
+ net.minecraft.world.level.block.WeatheringCopperBulbBlock
- net.minecraft.world.level.block.WeatheringCopperDoorBlock
+ net.minecraft.world.level.block.WeatheringCopperFullBlock
- net.minecraft.world.level.block.WeatheringCopperGrateBlock
+ net.minecraft.world.level.block.WeatheringCopperSlabBlock
- net.minecraft.world.level.block.WeatheringCopperStairBlock
+ net.minecraft.world.level.block.WeatheringCopperTrapDoorBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVinesBlock
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.BlockColumn
+ net.minecraft.world.level.chunk.BulkSectionAccess
- net.minecraft.world.level.chunk.CarvingMask
+ net.minecraft.world.level.chunk.CarvingMask$Mask
- net.minecraft.world.level.chunk.ChunkAccess
+ net.minecraft.world.level.chunk.ChunkAccess$TicksToSave
- net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkGenerators
+ net.minecraft.world.level.chunk.ChunkGeneratorStructureState
+ net.minecraft.world.level.chunk.ChunkSource
- net.minecraft.world.level.chunk.ChunkStatus
+ net.minecraft.world.level.chunk.ChunkStatus$ChunkType
- net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
+ net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
- net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
+ net.minecraft.world.level.chunk.DataLayer
- net.minecraft.world.level.chunk.EmptyLevelChunk
+ net.minecraft.world.level.chunk.GlobalPalette
- net.minecraft.world.level.chunk.HashMapPalette
+ net.minecraft.world.level.chunk.ImposterProtoChunk
- net.minecraft.world.level.chunk.LevelChunk
+ net.minecraft.world.level.chunk.LevelChunk$1
- net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
+ net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
- net.minecraft.world.level.chunk.LevelChunk$PostLoadProcessor
+ net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- net.minecraft.world.level.chunk.LevelChunkSection
+ net.minecraft.world.level.chunk.LevelChunkSection$1BlockCounter
- net.minecraft.world.level.chunk.LightChunk
+ net.minecraft.world.level.chunk.LightChunkGetter
- net.minecraft.world.level.chunk.LinearPalette
+ net.minecraft.world.level.chunk.MissingPaletteEntryException
- net.minecraft.world.level.chunk.package-info
- net.minecraft.world.level.chunk.Palette
+ net.minecraft.world.level.chunk.Palette$Factory
+ net.minecraft.world.level.chunk.PalettedContainer
- net.minecraft.world.level.chunk.PalettedContainer$Configuration
+ net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
- net.minecraft.world.level.chunk.PalettedContainer$Data
+ net.minecraft.world.level.chunk.PalettedContainer$Strategy
- net.minecraft.world.level.chunk.PalettedContainer$Strategy$1
+ net.minecraft.world.level.chunk.PalettedContainer$Strategy$2
- net.minecraft.world.level.chunk.PalettedContainerRO
+ net.minecraft.world.level.chunk.PalettedContainerRO$PackedData
- net.minecraft.world.level.chunk.PalettedContainerRO$Unpacker
- net.minecraft.world.level.chunk.PaletteResize
+ net.minecraft.world.level.chunk.ProtoChunk
- net.minecraft.world.level.chunk.SingleValuePalette
+ net.minecraft.world.level.chunk.storage.ChunkScanAccess
- net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.EntityStorage
+ net.minecraft.world.level.chunk.storage.IOWorker
- net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
+ net.minecraft.world.level.chunk.storage.IOWorker$Priority
+ net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RecreatingChunkStorage
+ net.minecraft.world.level.chunk.storage.RecreatingSimpleRegionStorage
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.storage.SimpleRegionStorage
+ net.minecraft.world.level.chunk.StructureAccess
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
- net.minecraft.world.level.dimension.BuiltinDimensionTypes
+ net.minecraft.world.level.dimension.DimensionDefaults
- net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.DimensionType$MonsterSettings
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
+ net.minecraft.world.level.dimension.end.EndDragonFight
- net.minecraft.world.level.dimension.end.EndDragonFight$Data
+ net.minecraft.world.level.dimension.end.package-info
- net.minecraft.world.level.dimension.LevelStem
- net.minecraft.world.level.dimension.package-info
+ net.minecraft.world.level.entity.ChunkEntities
- net.minecraft.world.level.entity.ChunkStatusUpdateListener
+ net.minecraft.world.level.entity.EntityAccess
- net.minecraft.world.level.entity.EntityInLevelCallback
+ net.minecraft.world.level.entity.EntityInLevelCallback$1
- net.minecraft.world.level.entity.EntityLookup
+ net.minecraft.world.level.entity.EntityPersistentStorage
- net.minecraft.world.level.entity.EntitySection
+ net.minecraft.world.level.entity.EntitySectionStorage
- net.minecraft.world.level.entity.EntityTickList
+ net.minecraft.world.level.entity.EntityTypeTest
- net.minecraft.world.level.entity.EntityTypeTest$1
+ net.minecraft.world.level.entity.EntityTypeTest$2
- net.minecraft.world.level.entity.LevelCallback
+ net.minecraft.world.level.entity.LevelEntityGetter
- net.minecraft.world.level.entity.LevelEntityGetterAdapter
+ net.minecraft.world.level.entity.package-info
+ net.minecraft.world.level.entity.PersistentEntitySectionManager
- net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- net.minecraft.world.level.entity.TransientEntitySectionManager
+ net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
- net.minecraft.world.level.entity.Visibility
- net.minecraft.world.level.gameevent.BlockPositionSource
+ net.minecraft.world.level.gameevent.BlockPositionSource$Type
- net.minecraft.world.level.gameevent.DynamicGameEventListener
+ net.minecraft.world.level.gameevent.EntityPositionSource
- net.minecraft.world.level.gameevent.EntityPositionSource$Type
+ net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
- net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
+ net.minecraft.world.level.gameevent.GameEvent
- net.minecraft.world.level.gameevent.GameEvent$Context
+ net.minecraft.world.level.gameevent.GameEvent$ListenerInfo
- net.minecraft.world.level.gameevent.GameEventDispatcher
+ net.minecraft.world.level.gameevent.GameEventListener
- net.minecraft.world.level.gameevent.GameEventListener$DeliveryMode
+ net.minecraft.world.level.gameevent.GameEventListener$Provider
- net.minecraft.world.level.gameevent.GameEventListenerRegistry
+ net.minecraft.world.level.gameevent.GameEventListenerRegistry$1
- net.minecraft.world.level.gameevent.GameEventListenerRegistry$ListenerVisitor
+ net.minecraft.world.level.gameevent.package-info
+ net.minecraft.world.level.gameevent.PositionSource
- net.minecraft.world.level.gameevent.PositionSourceType
+ net.minecraft.world.level.gameevent.vibrations.package-info
- net.minecraft.world.level.gameevent.vibrations.VibrationInfo
+ net.minecraft.world.level.gameevent.vibrations.VibrationSelector
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Data
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Listener
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Ticker
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$User
- net.minecraft.world.level.levelgen.Aquifer
+ net.minecraft.world.level.levelgen.Aquifer$1
- net.minecraft.world.level.levelgen.Aquifer$FluidPicker
+ net.minecraft.world.level.levelgen.Aquifer$FluidStatus
- net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
+ net.minecraft.world.level.levelgen.Beardifier
- net.minecraft.world.level.levelgen.Beardifier$1
+ net.minecraft.world.level.levelgen.Beardifier$Rigid
- net.minecraft.world.level.levelgen.BelowZeroRetrogen
+ net.minecraft.world.level.levelgen.BelowZeroRetrogen$1
- net.minecraft.world.level.levelgen.BitRandomSource
+ net.minecraft.world.level.levelgen.blending.Blender
- net.minecraft.world.level.levelgen.blending.Blender$1
+ net.minecraft.world.level.levelgen.blending.Blender$BlendingOutput
- net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
+ net.minecraft.world.level.levelgen.blending.Blender$DistanceGetter
- net.minecraft.world.level.levelgen.blending.BlendingData
+ net.minecraft.world.level.levelgen.blending.BlendingData$BiomeConsumer
- net.minecraft.world.level.levelgen.blending.BlendingData$DensityConsumer
+ net.minecraft.world.level.levelgen.blending.BlendingData$HeightConsumer
- net.minecraft.world.level.levelgen.blending.package-info
+ net.minecraft.world.level.levelgen.blockpredicates.AllOfPredicate
- net.minecraft.world.level.levelgen.blockpredicates.AnyOfPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
- net.minecraft.world.level.levelgen.blockpredicates.BlockPredicateType
+ net.minecraft.world.level.levelgen.blockpredicates.CombiningPredicate
- net.minecraft.world.level.levelgen.blockpredicates.HasSturdyFacePredicate
+ net.minecraft.world.level.levelgen.blockpredicates.InsideWorldBoundsPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingBlocksPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingBlockTagPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingFluidsPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.NotPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.package-info
- net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
+ net.minecraft.world.level.levelgen.blockpredicates.SolidPredicate
- net.minecraft.world.level.levelgen.blockpredicates.StateTestingPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.TrueBlockPredicate
- net.minecraft.world.level.levelgen.blockpredicates.WouldSurvivePredicate
- net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
- net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.CarverConfiguration
- net.minecraft.world.level.levelgen.carver.CarverDebugSettings
+ net.minecraft.world.level.levelgen.carver.CarvingContext
- net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CaveWorldCarver
- net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
+ net.minecraft.world.level.levelgen.carver.NetherWorldCarver
- net.minecraft.world.level.levelgen.carver.package-info
- net.minecraft.world.level.levelgen.carver.WorldCarver
+ net.minecraft.world.level.levelgen.carver.WorldCarver$CarveSkipChecker
+ net.minecraft.world.level.levelgen.Column
- net.minecraft.world.level.levelgen.Column$Line
+ net.minecraft.world.level.levelgen.Column$Range
- net.minecraft.world.level.levelgen.Column$Ray
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.Density
+ net.minecraft.world.level.levelgen.DensityFunction
- net.minecraft.world.level.levelgen.DensityFunction$ContextProvider
+ net.minecraft.world.level.levelgen.DensityFunction$FunctionContext
- net.minecraft.world.level.levelgen.DensityFunction$NoiseHolder
+ net.minecraft.world.level.levelgen.DensityFunction$SimpleFunction
- net.minecraft.world.level.levelgen.DensityFunction$SinglePointContext
+ net.minecraft.world.level.levelgen.DensityFunction$Visitor
- net.minecraft.world.level.levelgen.DensityFunctions
+ net.minecraft.world.level.levelgen.DensityFunctions$1
- net.minecraft.world.level.levelgen.DensityFunctions$Ap2
+ net.minecraft.world.level.levelgen.DensityFunctions$BeardifierMarker
- net.minecraft.world.level.levelgen.DensityFunctions$BeardifierOrMarker
+ net.minecraft.world.level.levelgen.DensityFunctions$BlendAlpha
- net.minecraft.world.level.levelgen.DensityFunctions$BlendDensity
+ net.minecraft.world.level.levelgen.DensityFunctions$BlendOffset
- net.minecraft.world.level.levelgen.DensityFunctions$Clamp
+ net.minecraft.world.level.levelgen.DensityFunctions$Constant
- net.minecraft.world.level.levelgen.DensityFunctions$EndIslandDensityFunction
+ net.minecraft.world.level.levelgen.DensityFunctions$HolderHolder
- net.minecraft.world.level.levelgen.DensityFunctions$Mapped
+ net.minecraft.world.level.levelgen.DensityFunctions$Mapped$Type
- net.minecraft.world.level.levelgen.DensityFunctions$Marker
+ net.minecraft.world.level.levelgen.DensityFunctions$Marker$Type
- net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked
+ net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd
- net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd$Type
+ net.minecraft.world.level.levelgen.DensityFunctions$Noise
- net.minecraft.world.level.levelgen.DensityFunctions$PureTransformer
+ net.minecraft.world.level.levelgen.DensityFunctions$RangeChoice
- net.minecraft.world.level.levelgen.DensityFunctions$Shift
+ net.minecraft.world.level.levelgen.DensityFunctions$ShiftA
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftB
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftedNoise
+ net.minecraft.world.level.levelgen.DensityFunctions$ShiftNoise
+ net.minecraft.world.level.levelgen.DensityFunctions$Spline
- net.minecraft.world.level.levelgen.DensityFunctions$Spline$Coordinate
+ net.minecraft.world.level.levelgen.DensityFunctions$Spline$Point
- net.minecraft.world.level.levelgen.DensityFunctions$TransformerWithContext
+ net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
- net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
+ net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler
- net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
+ net.minecraft.world.level.levelgen.DensityFunctions$YClampedGradient
+ net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
- net.minecraft.world.level.levelgen.feature.BambooFeature
+ net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockColumnFeature
+ net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.BlueIceFeature
+ net.minecraft.world.level.levelgen.feature.BonusChestFeature
- net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration$Layer
- net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MultifaceGrowthConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
+ net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
- net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SculkPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
- net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.ConfiguredFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.DeltaFeature
+ net.minecraft.world.level.levelgen.feature.DesertWellFeature
- net.minecraft.world.level.levelgen.feature.DiskFeature
+ net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
- net.minecraft.world.level.levelgen.feature.DripstoneUtils
+ net.minecraft.world.level.levelgen.feature.EndGatewayFeature
- net.minecraft.world.level.levelgen.feature.EndIslandFeature
+ net.minecraft.world.level.levelgen.feature.EndPodiumFeature
- net.minecraft.world.level.levelgen.feature.Feature
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$1
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker$FeatureData
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$LevelData
+ net.minecraft.world.level.levelgen.feature.FeaturePlaceContext
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
+ net.minecraft.world.level.levelgen.feature.featuresize.package-info
+ net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
- net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.CherryFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageSetter
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.GeodeFeature
- net.minecraft.world.level.levelgen.feature.GlowstoneFeature
+ net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
- net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
+ net.minecraft.world.level.levelgen.feature.HugeFungusFeature
- net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
- net.minecraft.world.level.levelgen.feature.IcebergFeature
+ net.minecraft.world.level.levelgen.feature.IceSpikeFeature
+ net.minecraft.world.level.levelgen.feature.KelpFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature$Configuration
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
- net.minecraft.world.level.levelgen.feature.MultifaceGrowthFeature
+ net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
- net.minecraft.world.level.levelgen.feature.NoOpFeature
+ net.minecraft.world.level.levelgen.feature.OreFeature
- net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.rootplacers.AboveRootPlacement
- net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacement
+ net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacer
- net.minecraft.world.level.levelgen.feature.rootplacers.package-info
- net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacer
+ net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacerType
- net.minecraft.world.level.levelgen.feature.RootSystemFeature
+ net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
- net.minecraft.world.level.levelgen.feature.SculkPatchFeature
- net.minecraft.world.level.levelgen.feature.SeagrassFeature
+ net.minecraft.world.level.levelgen.feature.SeaPickleFeature
+ net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
+ net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RuleBasedBlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RuleBasedBlockStateProvider$Rule
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.AttachedToLeavesDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator$Context
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.TreeFeature$1
- net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.CherryTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
- net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.trunkplacers.UpwardsBranchingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
+ net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
- net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.VinesFeature
- net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPreset
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
- net.minecraft.world.level.levelgen.flat.package-info
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
+ net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
- net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
+ net.minecraft.world.level.levelgen.heightproviders.HeightProvider
- net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
+ net.minecraft.world.level.levelgen.heightproviders.package-info
+ net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
- net.minecraft.world.level.levelgen.heightproviders.UniformHeight
+ net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
- net.minecraft.world.level.levelgen.heightproviders.WeightedListHeight
- net.minecraft.world.level.levelgen.LegacyRandomSource
+ net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
- net.minecraft.world.level.levelgen.material.MaterialRuleList
- net.minecraft.world.level.levelgen.material.package-info
+ net.minecraft.world.level.levelgen.material.WorldGenMaterialRule
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseChunk
+ net.minecraft.world.level.levelgen.NoiseChunk$1
- net.minecraft.world.level.levelgen.NoiseChunk$2
+ net.minecraft.world.level.levelgen.NoiseChunk$BlendAlpha
- net.minecraft.world.level.levelgen.NoiseChunk$BlendOffset
+ net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
- net.minecraft.world.level.levelgen.NoiseChunk$Cache2D
+ net.minecraft.world.level.levelgen.NoiseChunk$CacheAllInCell
- net.minecraft.world.level.levelgen.NoiseChunk$CacheOnce
+ net.minecraft.world.level.levelgen.NoiseChunk$FlatCache
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
+ net.minecraft.world.level.levelgen.NoiseRouter
- net.minecraft.world.level.levelgen.NoiseRouterData
+ net.minecraft.world.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
+ net.minecraft.world.level.levelgen.Noises
- net.minecraft.world.level.levelgen.NoiseSettings
- net.minecraft.world.level.levelgen.OreVeinifier
+ net.minecraft.world.level.levelgen.OreVeinifier$VeinType
+ net.minecraft.world.level.levelgen.package-info
- net.minecraft.world.level.levelgen.PatrolSpawner
+ net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.placement.BiomeFilter
+ net.minecraft.world.level.levelgen.placement.BlockPredicateFilter
- net.minecraft.world.level.levelgen.placement.CarvingMaskPlacement
+ net.minecraft.world.level.levelgen.placement.CaveSurface
- net.minecraft.world.level.levelgen.placement.CountOnEveryLayerPlacement
+ net.minecraft.world.level.levelgen.placement.CountPlacement
- net.minecraft.world.level.levelgen.placement.EnvironmentScanPlacement
- net.minecraft.world.level.levelgen.placement.HeightmapPlacement
+ net.minecraft.world.level.levelgen.placement.HeightRangePlacement
+ net.minecraft.world.level.levelgen.placement.InSquarePlacement
- net.minecraft.world.level.levelgen.placement.NoiseBasedCountPlacement
+ net.minecraft.world.level.levelgen.placement.NoiseThresholdCountPlacement
- net.minecraft.world.level.levelgen.placement.package-info
- net.minecraft.world.level.levelgen.placement.PlacedFeature
+ net.minecraft.world.level.levelgen.placement.PlacementContext
- net.minecraft.world.level.levelgen.placement.PlacementFilter
+ net.minecraft.world.level.levelgen.placement.PlacementModifier
- net.minecraft.world.level.levelgen.placement.PlacementModifierType
+ net.minecraft.world.level.levelgen.placement.RandomOffsetPlacement
- net.minecraft.world.level.levelgen.placement.RarityFilter
+ net.minecraft.world.level.levelgen.placement.RepeatingPlacement
- net.minecraft.world.level.levelgen.placement.SurfaceRelativeThresholdFilter
+ net.minecraft.world.level.levelgen.placement.SurfaceWaterDepthFilter
- net.minecraft.world.level.levelgen.PositionalRandomFactory
- net.minecraft.world.level.levelgen.presets.package-info
+ net.minecraft.world.level.levelgen.presets.WorldPreset
- net.minecraft.world.level.levelgen.presets.WorldPresets
+ net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
+ net.minecraft.world.level.levelgen.RandomState
- net.minecraft.world.level.levelgen.RandomState$1
+ net.minecraft.world.level.levelgen.RandomState$1NoiseWiringHelper
- net.minecraft.world.level.levelgen.RandomSupport
+ net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
- net.minecraft.world.level.levelgen.SingleThreadedRandomSource
+ net.minecraft.world.level.levelgen.structure.BoundingBox
- net.minecraft.world.level.levelgen.structure.BoundingBox$1
- net.minecraft.world.level.levelgen.structure.BuiltinStructures
+ net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
+ net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
- net.minecraft.world.level.levelgen.structure.package-info
+ net.minecraft.world.level.levelgen.structure.pieces.package-info
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator
- net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator$Context
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier
- net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier$Context
+ net.minecraft.world.level.levelgen.structure.pieces.PiecesContainer
- net.minecraft.world.level.levelgen.structure.pieces.StructurePiecesBuilder
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceSerializationContext
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$ContextlessType
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$StructureTemplateType
- net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.package-info
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReducer
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
- net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.pools.alias.Direct
+ net.minecraft.world.level.levelgen.structure.pools.alias.package-info
- net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBinding
+ net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBindings
- net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasLookup
+ net.minecraft.world.level.levelgen.structure.pools.alias.Random
- net.minecraft.world.level.levelgen.structure.pools.alias.RandomGroup
- net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
- net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
- net.minecraft.world.level.levelgen.structure.pools.package-info
- net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElementType
+ net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
- net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
+ net.minecraft.world.level.levelgen.structure.SinglePieceStructure
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure$PieceConstructor
+ net.minecraft.world.level.levelgen.structure.Structure
- net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
+ net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
- net.minecraft.world.level.levelgen.structure.Structure$StructureSettings
+ net.minecraft.world.level.levelgen.structure.StructureCheck
- net.minecraft.world.level.levelgen.structure.StructureCheckResult
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
+ net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
+ net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure
- net.minecraft.world.level.levelgen.structure.structures.DesertPyramidPiece
+ net.minecraft.world.level.levelgen.structure.structures.DesertPyramidStructure
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$1
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$2
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$3
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$4
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$EndCityPiece
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$SectionGenerator
+ net.minecraft.world.level.levelgen.structure.structures.EndCityStructure
- net.minecraft.world.level.levelgen.structure.structures.IglooPieces
+ net.minecraft.world.level.levelgen.structure.structures.IglooPieces$IglooPiece
- net.minecraft.world.level.levelgen.structure.structures.IglooStructure
+ net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
- net.minecraft.world.level.levelgen.structure.structures.JigsawStructure$1
+ net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece
- net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece$MossStoneSelector
+ net.minecraft.world.level.levelgen.structure.structures.JungleTempleStructure
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$1
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCorridor
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCrossing
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftPiece
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftRoom
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftStairs
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure
- net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure$Type
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeCrossing
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeEndFiller
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeStraight
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleEntrance
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleStalkRoom
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$MonsterThrone
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$NetherBridgePiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StairsRoom
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressStructure
+ net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces$NetherFossilPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFossilStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$1
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentBuilding
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentRoomFitter
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPiece
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$RoomDefinition
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentStructure
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$OceanRuinPiece
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure$Type
- net.minecraft.world.level.levelgen.structure.structures.package-info
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$Properties
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$VerticalPlacement
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure$Setup
+ net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces$ShipwreckPiece
+ net.minecraft.world.level.levelgen.structure.structures.ShipwreckStructure
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$1
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$3
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FillerCorridor
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$LeftTurn
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PrisonHall
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StairsDown
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Straight
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Turn
- net.minecraft.world.level.levelgen.structure.structures.StrongholdStructure
+ net.minecraft.world.level.levelgen.structure.structures.SwampHutPiece
- net.minecraft.world.level.levelgen.structure.structures.SwampHutStructure
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionGrid
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$PlacementData
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SimpleGrid
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionStructure
- net.minecraft.world.level.levelgen.structure.StructureSet
+ net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- net.minecraft.world.level.levelgen.structure.StructureStart
+ net.minecraft.world.level.levelgen.structure.StructureType
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.CappedProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.package-info
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProtectedBlockProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendLoot
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendStatic
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.Clear
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.package-info
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.Passthrough
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.RuleBlockEntityModifier
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.RuleBlockEntityModifierType
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$InputStreamOpener
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$Source
- net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
+ net.minecraft.world.level.levelgen.structure.TerrainAdjustment
+ net.minecraft.world.level.levelgen.SurfaceRules
- net.minecraft.world.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ net.minecraft.world.level.levelgen.SurfaceRules$Bandlands
- net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- net.minecraft.world.level.levelgen.SurfaceRules$BlockRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Condition
- net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Context
- net.minecraft.world.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$HoleCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Hole
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyCondition
- net.minecraft.world.level.levelgen.SurfaceRules$LazyXZCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyYCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NotCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$SequenceRule
- net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$StateRule
- net.minecraft.world.level.levelgen.SurfaceRules$Steep
+ net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck
- net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$SurfaceRule
- net.minecraft.world.level.levelgen.SurfaceRules$Temperature
+ net.minecraft.world.level.levelgen.SurfaceRules$TestRule
- net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ net.minecraft.world.level.levelgen.SurfaceSystem
- net.minecraft.world.level.levelgen.SurfaceSystem$1
+ net.minecraft.world.level.levelgen.synth.BlendedNoise
- net.minecraft.world.level.levelgen.synth.ImprovedNoise
+ net.minecraft.world.level.levelgen.synth.NoiseUtils
- net.minecraft.world.level.levelgen.synth.NormalNoise
+ net.minecraft.world.level.levelgen.synth.NormalNoise$NoiseParameters
+ net.minecraft.world.level.levelgen.synth.package-info
- net.minecraft.world.level.levelgen.synth.PerlinNoise
+ net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
- net.minecraft.world.level.levelgen.synth.SimplexNoise
+ net.minecraft.world.level.levelgen.ThreadSafeLegacyRandomSource
- net.minecraft.world.level.levelgen.VerticalAnchor
+ net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
- net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
+ net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
- net.minecraft.world.level.levelgen.WorldDimensions
+ net.minecraft.world.level.levelgen.WorldDimensions$1Entry
- net.minecraft.world.level.levelgen.WorldDimensions$Complete
- net.minecraft.world.level.levelgen.WorldGenerationContext
- net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
+ net.minecraft.world.level.levelgen.WorldGenSettings
+ net.minecraft.world.level.levelgen.WorldOptions
- net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource
- net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- net.minecraft.world.level.lighting.BlockLightEngine
+ net.minecraft.world.level.lighting.BlockLightSectionStorage
- net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ net.minecraft.world.level.lighting.ChunkSkyLightSources
- net.minecraft.world.level.lighting.DataLayerStorageMap
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
+ net.minecraft.world.level.lighting.LayerLightEventListener
- net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ net.minecraft.world.level.lighting.LayerLightSectionStorage
- net.minecraft.world.level.lighting.LayerLightSectionStorage$SectionState
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$SectionType
+ net.minecraft.world.level.lighting.LeveledPriorityQueue
- net.minecraft.world.level.lighting.LeveledPriorityQueue$1
- net.minecraft.world.level.lighting.LevelLightEngine
+ net.minecraft.world.level.lighting.LightEngine
- net.minecraft.world.level.lighting.LightEngine$QueueEntry
+ net.minecraft.world.level.lighting.LightEventListener
- net.minecraft.world.level.lighting.package-info
- net.minecraft.world.level.lighting.SkyLightEngine
+ net.minecraft.world.level.lighting.SkyLightEngine$1
- net.minecraft.world.level.lighting.SkyLightSectionStorage
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- net.minecraft.world.level.lighting.SpatialLongSet
+ net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
+ net.minecraft.world.level.material.EmptyFluid
- net.minecraft.world.level.material.FlowingFluid
+ net.minecraft.world.level.material.FlowingFluid$1
- net.minecraft.world.level.material.Fluid
- net.minecraft.world.level.material.Fluids
+ net.minecraft.world.level.material.FluidState
+ net.minecraft.world.level.material.FogType
- net.minecraft.world.level.material.LavaFluid
+ net.minecraft.world.level.material.LavaFluid$Flowing
- net.minecraft.world.level.material.LavaFluid$Source
+ net.minecraft.world.level.material.MapColor
- net.minecraft.world.level.material.MapColor$Brightness
+ net.minecraft.world.level.material.package-info
+ net.minecraft.world.level.material.PushReaction
- net.minecraft.world.level.material.WaterFluid
+ net.minecraft.world.level.material.WaterFluid$Flowing
- net.minecraft.world.level.material.WaterFluid$Source
- net.minecraft.world.level.package-info
+ net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
- net.minecraft.world.level.pathfinder.BinaryHeap
+ net.minecraft.world.level.pathfinder.BlockPathTypes
- net.minecraft.world.level.pathfinder.FlyNodeEvaluator
+ net.minecraft.world.level.pathfinder.Node
- net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
+ net.minecraft.world.level.pathfinder.Path
- net.minecraft.world.level.pathfinder.Path$DebugData
+ net.minecraft.world.level.pathfinder.PathComputationType
- net.minecraft.world.level.pathfinder.PathFinder
+ net.minecraft.world.level.pathfinder.SwimNodeEvaluator
- net.minecraft.world.level.pathfinder.Target
+ net.minecraft.world.level.pathfinder.WalkNodeEvaluator
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator$1
+ net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalForcer
+ net.minecraft.world.level.portal.PortalInfo
- net.minecraft.world.level.portal.PortalShape
- net.minecraft.world.level.redstone.CollectingNeighborUpdater
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- net.minecraft.world.level.redstone.InstantNeighborUpdater
+ net.minecraft.world.level.redstone.NeighborUpdater
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
- net.minecraft.world.level.saveddata.maps.MapBanner
+ net.minecraft.world.level.saveddata.maps.MapBanner$1
- net.minecraft.world.level.saveddata.maps.MapDecoration
+ net.minecraft.world.level.saveddata.maps.MapDecoration$Type
- net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.saveddata.SavedData$Factory
- net.minecraft.world.ticks.ContainerSingleItem$BlockContainerSingleItem
+ net.minecraft.world.ticks.LevelChunkTicks
- net.minecraft.world.ticks.LevelTickAccess
+ net.minecraft.world.ticks.LevelTicks
- net.minecraft.world.ticks.LevelTicks$PosAndContainerConsumer
+ net.minecraft.world.ticks.package-info
+ net.minecraft.world.ticks.ProtoChunkTicks
- net.minecraft.world.ticks.SavedTick
+ net.minecraft.world.ticks.SavedTick$1
- net.minecraft.world.ticks.ScheduledTick
+ net.minecraft.world.ticks.ScheduledTick$1
- net.minecraft.world.ticks.SerializableTickContainer
+ net.minecraft.world.ticks.TickAccess
- net.minecraft.world.ticks.TickContainerAccess
+ net.minecraft.world.ticks.TickPriority
- net.minecraft.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.platform.Lighting +3M -2M
```
```
XXX.blaze3d.vertex.PoseStack +1M -1M
```
```
XXX.blaze3d.vertex.SheetedDecalTextureGenerator +1M -1M
```
```
XXX.blaze3d.vertex.VertexConsumer +2M -1M
```
```
XXX.minecraft.client.Minecraft +1M -1M
```
```
XXX.client.gui.MapRenderer +3M -3M
```
```
XXX.components.debugchart.AbstractDebugChart +1M -1M | +1P -1P
```
```
XXX.components.debugchart.FpsDebugChart +1M -1M
```
```
XXX.components.debugchart.TpsDebugChart +1M -1M
```
```
XXX.screens.inventory.CartographyTableScreen +2M -2M
```
```
XXX.screens.worldselection.OptimizeWorldScreen +1M -1M
```
```
XXX.client.multiplayer.ClientLevel +4M -4M
```
```
XXX.client.multiplayer.ClientPacketListener +2M -1M | +1P
```
```
XXX.renderer.entity.DragonFireballRenderer +1M -1M
```
```
XXX.renderer.entity.ExperienceOrbRenderer +1M -1M
```
```
XXX.renderer.entity.GuardianRenderer +1M -1M
```
```
XXX.entity.layers.HumanoidArmorLayer +2M -3M
```
```
XXX.client.server.IntegratedServer +2M
```
```
XXX.minecraft.commands.CommandBuildContext$1 +3M -1M
```
```
XXX.minecraft.core.UUIDUtil +1P
```
```
XXX.core.particles.BlockParticleOption$1 +2M -2M
```
```
XXX.core.particles.DustColorTransitionOptions$1 +2M -2M
```
```
XXX.core.particles.DustParticleOptions$1 +2M -2M
```
```
XXX.core.particles.ItemParticleOption +1M -1M
```
```
XXX.core.particles.ParticleOptions$Deserializer +1P -1P
```
```
XXX.core.particles.ParticleTypes +1P
```
```
XXX.core.particles.SculkChargeParticleOptions +1M -1M
```
```
XXX.core.particles.ShriekParticleOption +1M -1M
```
```
XXX.core.particles.SimpleParticleType +1M -1M
```
```
XXX.core.particles.VibrationParticleOption +1M -1M
```
```
XXX.minecraft.data.DataProvider +1M -1M
```
```
XXX.data.loot.LootTableProvider +9M -7M | +1P
```
```
XXX.loot.packs.TradeRebalanceLootTableProvider +1M -1M
```
```
XXX.loot.packs.VanillaLootTableProvider +1M -1M
```
```
XXX.data.models.BlockModelGenerators$1 +1P
```
```
XXX.data.models.ItemModelGenerators$TrimModelData +1M -1M
```
```
XXX.models.model.TextureMapping +1M
```
```
XXX.data.recipes.RecipeProvider$1 +1M -1M | +1P
```
```
XXX.recipes.packs.UpdateOneTwentyOneRecipeProvider +1M -1M
```
```
XXX.data.tags.TagsProvider +1M -1M
```
```
XXX.gametest.framework.GameTestHelper +2M -3M
```
```
XXX.gametest.framework.GameTestHelper$2 +1M -2M
```
```
XXX.network.codec.ByteBufCodecs$9 +3M -3M | -1P
```
```
XXX.network.codec.StreamCodec +2M
```
```
XXX.protocol.common.ClientboundDisconnectPacket +4M -3M
```
```
XXX.protocol.common.ClientboundResourcePackPushPacket +2M -4M | +1P -1P
```
```
XXX.protocol.cookie.ServerboundCookieResponsePacket -1M
```
```
XXX.protocol.game.ClientGamePacketListener +1P
```
```
XXX.protocol.game.ClientboundBossEventPacket +2M -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$AddOperation +2M -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$Operation +1P -1P
```
```
XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation +6M -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation +2M -2M
```
```
XXX.protocol.game.ClientboundCommandSuggestionsPacket +11M -7M | +3P -1P
```
```
XXX.protocol.game.ClientboundLightUpdatePacketData +1M -2M | +1P
```
```
XXX.protocol.game.ClientboundMapItemDataPacket +11M -10M | +3P -3P
```
```
XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action +12M -12M
```
```
XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer +1P -1P
```
```
XXX.protocol.game.ClientboundServerDataPacket +5M -4M
```
```
XXX.protocol.game.ClientboundSetScorePacket +2M -4M | +1P -1P
```
```
XXX.protocol.game.ClientboundSetSubtitleTextPacket +4M -3M
```
```
XXX.protocol.game.ClientboundSetTitleTextPacket +4M -3M
```
```
XXX.protocol.game.ClientboundSystemChatPacket -2M
```
```
XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix -1M | -1P
```
```
XXX.util.worldupdate.WorldUpgrader +1M -1M
```
```
XXX.world.effect.MobEffectInstance +6M -5M | +1P -7P
```
```
XXX.animal.horse.Horse +3M -7M | -1P
```
```
XXX.animal.horse.Llama +3M -6M | -1P
```
```
XXX.entity.decoration.ItemFrame +1M -2M
```
```
XXX.entity.monster.Drowned +1M -1M
```
```
XXX.entity.monster.PatrollingMonster +1M -1M
```
```
XXX.entity.monster.Phantom +1M -1M
```
```
XXX.entity.monster.Pillager +1M -1M
```
```
XXX.entity.monster.Slime +1M -1M
```
```
XXX.entity.monster.Spider +1M -1M
```
```
XXX.entity.monster.Vex +1M -1M
```
```
XXX.entity.monster.ZombieVillager +3M -2M | +1P -1P
```
```
XXX.monster.hoglin.Hoglin +1M -1M
```
```
XXX.monster.piglin.Piglin +1M -1M
```
```
XXX.monster.warden.Warden +1M -1M
```
```
XXX.entity.npc.AbstractVillager +2M -1M | +1P
```
```
XXX.entity.projectile.Fireball +1M -1M
```
```
XXX.entity.projectile.ThrowableItemProjectile -1M
```
```
XXX.entity.raid.Raids +2M -2M
```
```
XXX.world.item.Equipable +1M -1M
```
```
XXX.world.item.ItemStack +11M -6M
```
```
XXX.world.item.Items +1P
```
```
XXX.world.item.MapItem +5M -6M
```
```
XXX.item.trading.MerchantOffer +13M -2M | +1P
```
```
XXX.world.level.ForcedChunksSavedData +2M -2M
```
```
XXX.level.block.Block +1M -1M
```
```
XXX.level.block.ShulkerBoxBlock +2M -2M
```
```
XXX.level.block.SpawnerBlock +1M -1M
```
```
XXX.level.block.TrialSpawnerBlock +1M -1M
```
```
XXX.entity.trialspawner.TrialSpawnerData +1M -1M
```
```
XXX.saveddata.maps.MapIndex +3M -3M
```
```
XXX.saveddata.maps.MapItemSavedData$HoldingPlayer +1M -1M
```
```
XXX.level.storage.CommandStorage +1M -1M
```
```
XXX.level.storage.DimensionDataStorage +2M -2M | +1P
```
```
XXX.level.storage.LevelStorageSource -1M
```
```
XXX.storage.loot.LootDataType +1M -1M
```
```
XXX.loot.parameters.LootContextParamSets +1M | +1P
```
```
XXX.world.scores.ScoreboardSaveData +1M -1M
```

</details>
































<details>
<summary>
com.mojang.blaze3d.platform.Lighting
</summary>

```diff
- void setupForEntityInInventory(Quaternionf)
- void setupLevel()
+ void setupLevel(Matrix4f)
- void setupNetherLevel()
+ void setupNetherLevel(Matrix4f)
```

</details>























<details>
<summary>
com.mojang.blaze3d.vertex.PoseStack
</summary>

```diff
- void mulPose(Matrix4f)
+ void mulPoseMatrix(Matrix4f)
```

</details>
<details>
<summary>
com.mojang.blaze3d.vertex.SheetedDecalTextureGenerator
</summary>

```diff
+ void <init>(VertexConsumer,Matrix4f,Matrix3f,float)
- void <init>(VertexConsumer,PoseStack$Pose,float)
```

</details>

<details>
<summary>
com.mojang.blaze3d.vertex.VertexConsumer
</summary>

```diff
+ VertexConsumer normal(Matrix3f,float,float,float)
- VertexConsumer normal(PoseStack$Pose,float,float,float)
- VertexConsumer vertex(PoseStack$Pose,float,float,float)
```

</details>































































































































































































































<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
- void addCustomNbtData(ItemStack,BlockEntity,RegistryAccess)
+ void addCustomNbtData(ItemStack,BlockEntity)
```

</details>

















































<details>
<summary>
net.minecraft.client.gui.MapRenderer
</summary>

```diff
+ MapRenderer$MapInstance getOrCreateMapInstance(int,MapItemSavedData)
- MapRenderer$MapInstance getOrCreateMapInstance(MapId,MapItemSavedData)
+ void render(PoseStack,MultiBufferSource,int,MapItemSavedData,boolean,int)
- void render(PoseStack,MultiBufferSource,MapId,MapItemSavedData,boolean,int)
+ void update(int,MapItemSavedData)
- void update(MapId,MapItemSavedData)
```

</details>













































<details>
<summary>
net.minecraft.client.gui.components.debugchart.AbstractDebugChart
</summary>

```diff
+ void <init>(Font,SampleLogger)
- void <init>(Font,SampleStorage)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.debugchart.FpsDebugChart
</summary>

```diff
+ void <init>(Font,SampleLogger)
- void <init>(Font,SampleStorage)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.debugchart.TpsDebugChart
</summary>

```diff
+ void <init>(Font,SampleLogger,Supplier)
- void <init>(Font,SampleStorage,Supplier)
```

</details>





























































































































<details>
<summary>
net.minecraft.client.gui.screens.inventory.CartographyTableScreen
</summary>

```diff
+ void renderMap(GuiGraphics,Integer,MapItemSavedData,int,int,float)
- void renderMap(GuiGraphics,MapId,MapItemSavedData,int,int,float)
+ void renderResultingMap(GuiGraphics,Integer,MapItemSavedData,boolean,boolean,boolean,boolean)
- void renderResultingMap(GuiGraphics,MapId,MapItemSavedData,boolean,boolean,boolean,boolean)
```

</details>












































































<details>
<summary>
net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen
</summary>

```diff
+ void <init>(BooleanConsumer,DataFixer,LevelStorageSource$LevelStorageAccess,LevelSettings,boolean,Registry)
- void <init>(BooleanConsumer,DataFixer,LevelStorageSource$LevelStorageAccess,LevelSettings,boolean,RegistryAccess)
```

</details>































































































<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
+ int getFreeMapId()
- MapId getFreeMapId()
- MapItemSavedData getMapData(MapId)
+ MapItemSavedData getMapData(String)
- void overrideMapData(MapId,MapItemSavedData)
+ void overrideMapData(String,MapItemSavedData)
- void setMapData(MapId,MapItemSavedData)
+ void setMapData(String,MapItemSavedData)
```

</details>

<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
- void handleDebugSample(ClientboundDebugSamplePacket)
+ void lambda$handleSetEquipment$6(Entity,Pair)
- void lambda$handleSetEquipment$6(LivingEntity,Pair)
```

</details>
































































<details>
<summary>
net.minecraft.client.renderer.entity.DragonFireballRenderer
</summary>

```diff
+ void vertex(VertexConsumer,Matrix4f,Matrix3f,int,float,int,int,int)
- void vertex(VertexConsumer,PoseStack$Pose,int,float,int,int,int)
```

</details>







<details>
<summary>
net.minecraft.client.renderer.entity.ExperienceOrbRenderer
</summary>

```diff
+ void vertex(VertexConsumer,Matrix4f,Matrix3f,float,float,int,int,int,float,float,int)
- void vertex(VertexConsumer,PoseStack$Pose,float,float,int,int,int,float,float,int)
```

</details>




<details>
<summary>
net.minecraft.client.renderer.entity.GuardianRenderer
</summary>

```diff
+ void vertex(VertexConsumer,Matrix4f,Matrix3f,float,float,float,int,int,int,float,float)
- void vertex(VertexConsumer,PoseStack$Pose,float,float,float,int,int,int,float,float)
```

</details>
















































<details>
<summary>
net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer
</summary>

```diff
+ ResourceLocation getArmorLocation(ArmorItem,boolean,String)
+ void renderModel(PoseStack,MultiBufferSource,int,ArmorItem,HumanoidModel,boolean,float,float,float,String)
- void renderModel(PoseStack,MultiBufferSource,int,HumanoidModel,float,float,float,ResourceLocation)
+ void renderTrim(ArmorMaterial,PoseStack,MultiBufferSource,int,ArmorTrim,HumanoidModel,boolean)
- void renderTrim(Holder,PoseStack,MultiBufferSource,int,ArmorTrim,HumanoidModel,boolean)
```

</details>






















































































































<details>
<summary>
net.minecraft.client.server.IntegratedServer
</summary>

```diff
- boolean isTickTimeLoggingEnabled()
- LocalSampleLogger getTickTimeLogger()
```

</details>

































<details>
<summary>
net.minecraft.commands.CommandBuildContext$1
</summary>

```diff
+ HolderLookup holderLookup(ResourceKey)
- HolderLookup$RegistryLookup lambda$lookup$0(FeatureFlagSet,HolderLookup$RegistryLookup)
- Optional lookup(ResourceKey)
- Stream listRegistries()
```

</details>
















































<details>
<summary>
net.minecraft.core.particles.BlockParticleOption$1
</summary>

```diff
- BlockParticleOption fromCommand(ParticleType,StringReader,HolderLookup$Provider)
+ BlockParticleOption fromCommand(ParticleType,StringReader)
- ParticleOptions fromCommand(ParticleType,StringReader,HolderLookup$Provider)
+ ParticleOptions fromCommand(ParticleType,StringReader)
```

</details>
<details>
<summary>
net.minecraft.core.particles.DustColorTransitionOptions$1
</summary>

```diff
- DustColorTransitionOptions fromCommand(ParticleType,StringReader,HolderLookup$Provider)
+ DustColorTransitionOptions fromCommand(ParticleType,StringReader)
- ParticleOptions fromCommand(ParticleType,StringReader,HolderLookup$Provider)
+ ParticleOptions fromCommand(ParticleType,StringReader)
```

</details>
<details>
<summary>
net.minecraft.core.particles.DustParticleOptions$1
</summary>

```diff
- DustParticleOptions fromCommand(ParticleType,StringReader,HolderLookup$Provider)
+ DustParticleOptions fromCommand(ParticleType,StringReader)
- ParticleOptions fromCommand(ParticleType,StringReader,HolderLookup$Provider)
+ ParticleOptions fromCommand(ParticleType,StringReader)
```

</details>
<details>
<summary>
net.minecraft.core.particles.ItemParticleOption
</summary>

```diff
+ String writeToString()
- String writeToString(HolderLookup$Provider)
```

</details>



<details>
<summary>
net.minecraft.core.particles.SculkChargeParticleOptions
</summary>

```diff
+ String writeToString()
- String writeToString(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.core.particles.ShriekParticleOption
</summary>

```diff
+ String writeToString()
- String writeToString(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.core.particles.SimpleParticleType
</summary>

```diff
+ String writeToString()
- String writeToString(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.core.particles.VibrationParticleOption
</summary>

```diff
+ String writeToString()
- String writeToString(HolderLookup$Provider)
```

</details>






<details>
<summary>
net.minecraft.data.DataProvider
</summary>

```diff
+ CompletableFuture saveStable(CachedOutput,Codec,Object,Path)
- CompletableFuture saveStable(CachedOutput,HolderLookup$Provider,Codec,Object,Path)
```

</details>















<details>
<summary>
net.minecraft.data.loot.LootTableProvider
</summary>

```diff
+ CompletableFuture lambda$run$4(CachedOutput,Map$Entry)
- CompletableFuture lambda$run$5(CachedOutput,HolderLookup$Provider,Map$Entry)
- CompletableFuture run(CachedOutput,HolderLookup$Provider)
+ CompletableFuture[] lambda$run$5(int)
- CompletableFuture[] lambda$run$6(int)
- CompletionStage lambda$run$0(CachedOutput,HolderLookup$Provider)
- void <init>(PackOutput,Set,List,CompletableFuture)
+ void <init>(PackOutput,Set,List)
+ void lambda$run$0(Map,Map,LootTableProvider$SubProviderEntry,ResourceLocation,LootTable$Builder)
- void lambda$run$1(Map,Map,LootTableProvider$SubProviderEntry,ResourceLocation,LootTable$Builder)
+ void lambda$run$1(Map,Map,LootTableProvider$SubProviderEntry)
- void lambda$run$2(Map,Map,LootTableProvider$SubProviderEntry)
+ void lambda$run$2(ValidationContext,ResourceLocation,LootTable)
+ void lambda$run$3(String,String)
- void lambda$run$3(ValidationContext,ResourceLocation,LootTable)
- void lambda$run$4(String,String)
```

</details>


<details>
<summary>
net.minecraft.data.loot.packs.TradeRebalanceLootTableProvider
</summary>

```diff
- LootTableProvider create(PackOutput,CompletableFuture)
+ LootTableProvider create(PackOutput)
```

</details>




<details>
<summary>
net.minecraft.data.loot.packs.VanillaLootTableProvider
</summary>

```diff
- LootTableProvider create(PackOutput,CompletableFuture)
+ LootTableProvider create(PackOutput)
```

</details>






<details>
<summary>
net.minecraft.data.models.ItemModelGenerators$TrimModelData
</summary>

```diff
+ String name(ArmorMaterial)
- String name(Holder)
```

</details>















<details>
<summary>
net.minecraft.data.models.model.TextureMapping
</summary>

```diff
- TextureMapping vault(Block,String,String,String,String)
```

</details>





<details>
<summary>
net.minecraft.data.recipes.RecipeProvider$1
</summary>

```diff
- void <init>(RecipeProvider,Set,List,CachedOutput,HolderLookup$Provider)
+ void <init>(RecipeProvider,Set,List,CachedOutput)
```

</details>




<details>
<summary>
net.minecraft.data.recipes.packs.UpdateOneTwentyOneRecipeProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture)
+ void <init>(PackOutput)
```

</details>















<details>
<summary>
net.minecraft.data.tags.TagsProvider
</summary>

```diff
+ CompletableFuture lambda$run$5(Predicate,Predicate,CachedOutput,Map$Entry)
- CompletableFuture lambda$run$5(Predicate,Predicate,CachedOutput,TagsProvider$1CombinedData,Map$Entry)
```

</details>










































<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
+ Player makeMockPlayer()
- Player makeMockPlayer(GameType)
+ Player makeMockSurvivalPlayer()
+ void assertValueEqual(Number,Number,String)
- void assertValueEqual(Object,Object,String)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper$2
</summary>

```diff
+ boolean isLocalPlayer()
+ void <init>(GameTestHelper,Level,BlockPos,float,GameProfile)
- void <init>(GameTestHelper,MinecraftServer,ServerLevel,GameProfile,ClientInformation)
```

</details>



<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$9
</summary>

```diff
- byte[] decode(ByteBuf)
+ Tag decode(ByteBuf)
- void <init>()
+ void <init>(Supplier)
- void encode(ByteBuf,byte[])
+ void encode(ByteBuf,Tag)
```

</details>

<details>
<summary>
net.minecraft.network.codec.StreamCodec
</summary>

```diff
- StreamCodec composite(StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,Function4)
- StreamCodec composite(StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,StreamCodec,Function,Function5)
```

</details>















<details>
<summary>
net.minecraft.network.protocol.common.ClientboundDisconnectPacket
</summary>

```diff
- boolean equals(Object)
+ Component getReason()
- Component reason()
- int hashCode()
- String toString()
+ void <init>(FriendlyByteBuf)
+ void write(FriendlyByteBuf)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.common.ClientboundResourcePackPushPacket
</summary>

```diff
+ Component prompt()
- Optional prompt()
+ void <init>(FriendlyByteBuf)
+ void <init>(UUID,String,String,boolean,Component)
- void <init>(UUID,String,String,boolean,Optional)
+ void write(FriendlyByteBuf)
```

</details>




























<details>
<summary>
net.minecraft.network.protocol.cookie.ServerboundCookieResponsePacket
</summary>

```diff
+ byte[] lambda$new$0(FriendlyByteBuf)
```

</details>





<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket
</summary>

```diff
+ void <init>(FriendlyByteBuf)
- void <init>(RegistryFriendlyByteBuf)
+ void write(FriendlyByteBuf)
- void write(RegistryFriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
</summary>

```diff
+ void <init>(FriendlyByteBuf)
- void <init>(RegistryFriendlyByteBuf)
+ void write(FriendlyByteBuf)
- void write(RegistryFriendlyByteBuf)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
</summary>

```diff
- boolean equals(Object)
- Component name()
- int hashCode()
- String toString()
+ void <init>(FriendlyByteBuf)
- void <init>(RegistryFriendlyByteBuf)
+ void write(FriendlyByteBuf)
- void write(RegistryFriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
</summary>

```diff
+ void <init>(FriendlyByteBuf)
- void <init>(RegistryFriendlyByteBuf)
+ void write(FriendlyByteBuf)
- void write(RegistryFriendlyByteBuf)
```

</details>




<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
</summary>

```diff
- boolean equals(Object)
- ClientboundCommandSuggestionsPacket$Entry lambda$new$0(Suggestion)
+ int getId()
- int hashCode()
- int id()
- int length()
- int start()
- List suggestions()
- String toString()
+ Suggestion lambda$new$0(StringRange,FriendlyByteBuf)
- Suggestion lambda$toSuggestions$1(StringRange,ClientboundCommandSuggestionsPacket$Entry)
+ Suggestions getSuggestions()
- Suggestions toSuggestions()
+ void <init>(FriendlyByteBuf)
- void <init>(int,int,int,List)
+ void lambda$write$1(FriendlyByteBuf,Message)
+ void lambda$write$2(FriendlyByteBuf,Suggestion)
+ void write(FriendlyByteBuf)
```

</details>








<details>
<summary>
net.minecraft.network.protocol.game.ClientboundLightUpdatePacketData
</summary>

```diff
+ byte[] lambda$new$0(FriendlyByteBuf)
+ byte[] lambda$new$1(FriendlyByteBuf)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
</summary>

```diff
- boolean equals(Object)
+ boolean isLocked()
- boolean locked()
+ byte getScale()
- byte scale()
+ int getMapId()
- int hashCode()
+ List lambda$new$1(FriendlyByteBuf)
+ MapDecoration lambda$new$0(FriendlyByteBuf)
- MapId mapId()
- Optional colorPatch()
- Optional decorations()
- String toString()
+ void <init>(FriendlyByteBuf)
+ void <init>(int,byte,boolean,Collection,MapItemSavedData$MapPatch)
- void <init>(MapId,byte,boolean,Collection,MapItemSavedData$MapPatch)
- void <init>(MapId,byte,boolean,Optional,Optional)
- void lambda$applyToMap$0(MapItemSavedData,MapItemSavedData$MapPatch)
+ void lambda$write$2(FriendlyByteBuf,MapDecoration)
+ void lambda$write$3(FriendlyByteBuf,List)
+ void write(FriendlyByteBuf)
```

</details>








<details>
<summary>
net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
</summary>

```diff
+ void lambda$static$0(ClientboundPlayerInfoUpdatePacket$EntryBuilder,FriendlyByteBuf)
- void lambda$static$0(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
+ void lambda$static$1(FriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
- void lambda$static$1(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
+ void lambda$static$10(ClientboundPlayerInfoUpdatePacket$EntryBuilder,FriendlyByteBuf)
- void lambda$static$10(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
+ void lambda$static$11(FriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
- void lambda$static$11(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
+ void lambda$static$2(ClientboundPlayerInfoUpdatePacket$EntryBuilder,FriendlyByteBuf)
- void lambda$static$2(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
+ void lambda$static$3(FriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
- void lambda$static$3(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
+ void lambda$static$4(ClientboundPlayerInfoUpdatePacket$EntryBuilder,FriendlyByteBuf)
- void lambda$static$4(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
+ void lambda$static$5(FriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
- void lambda$static$5(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
+ void lambda$static$6(ClientboundPlayerInfoUpdatePacket$EntryBuilder,FriendlyByteBuf)
- void lambda$static$6(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
+ void lambda$static$7(FriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
- void lambda$static$7(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
+ void lambda$static$8(ClientboundPlayerInfoUpdatePacket$EntryBuilder,FriendlyByteBuf)
- void lambda$static$8(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
+ void lambda$static$9(FriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
- void lambda$static$9(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
```

</details>







<details>
<summary>
net.minecraft.network.protocol.game.ClientboundServerDataPacket
</summary>

```diff
- boolean equals(Object)
+ Component getMotd()
- Component motd()
- int hashCode()
+ Optional getIconBytes()
- Optional iconBytes()
- String toString()
+ void <init>(FriendlyByteBuf)
+ void write(FriendlyByteBuf)
```

</details>











<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSetScorePacket
</summary>

```diff
+ Component display()
- Optional display()
+ void <init>(RegistryFriendlyByteBuf)
+ void <init>(String,String,int,Component,Optional)
- void <init>(String,String,int,Optional,Optional)
+ void write(RegistryFriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
</summary>

```diff
- boolean equals(Object)
+ Component getText()
- Component text()
- int hashCode()
- String toString()
+ void <init>(FriendlyByteBuf)
+ void write(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
</summary>

```diff
- boolean equals(Object)
+ Component getText()
- Component text()
- int hashCode()
- String toString()
+ void <init>(FriendlyByteBuf)
+ void write(FriendlyByteBuf)
```

</details>


<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSystemChatPacket
</summary>

```diff
+ void <init>(FriendlyByteBuf)
+ void write(FriendlyByteBuf)
```

</details>




































































<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
</summary>

```diff
+ void <clinit>()
```

</details>














































































































<details>
<summary>
net.minecraft.util.worldupdate.WorldUpgrader
</summary>

```diff
+ void <init>(LevelStorageSource$LevelStorageAccess,DataFixer,Registry,boolean,boolean)
- void <init>(LevelStorageSource$LevelStorageAccess,DataFixer,RegistryAccess,boolean,boolean)
```

</details>




























<details>
<summary>
net.minecraft.world.effect.MobEffectInstance
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
+ CompoundTag save(CompoundTag)
+ int lambda$tickDownDuration$0(int)
- int lambda$tickDownDuration$2(int)
+ MobEffectInstance lambda$load$1(CompoundTag,Holder$Reference)
- MobEffectInstance lambda$new$1(Holder,MobEffectInstance$Details)
+ MobEffectInstance loadSpecifiedEffect(Holder,CompoundTag)
- MobEffectInstance$Details asDetails()
- Tag save()
- void <init>(Holder,MobEffectInstance$Details)
+ void writeDetailsTo(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Horse
</summary>

```diff
+ boolean canWearArmor()
- boolean canWearBodyArmor()
+ boolean isArmor(ItemStack)
- boolean isBodyArmorItem(ItemStack)
+ ItemStack getArmor()
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
+ void setArmor(ItemStack)
+ void setArmorEquipment(ItemStack)
+ void updateContainerEquipment()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
+ boolean canWearArmor()
- boolean canWearBodyArmor()
+ boolean isArmor(ItemStack)
- boolean isBodyArmorItem(ItemStack)
+ boolean isWearingArmor()
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
+ void setSwag(DyeColor)
+ void updateContainerEquipment()
```

</details>




























<details>
<summary>
net.minecraft.world.entity.decoration.ItemFrame
</summary>

```diff
- MapId getFramedMapId()
+ OptionalInt getFramedMapId()
+ void lambda$removeFramedMap$0(int)
```

</details>










<details>
<summary>
net.minecraft.world.entity.monster.Drowned
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>

















<details>
<summary>
net.minecraft.world.entity.monster.PatrollingMonster
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Phantom
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.Pillager
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>






<details>
<summary>
net.minecraft.world.entity.monster.Slime
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.Spider
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.Vex
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>






<details>
<summary>
net.minecraft.world.entity.monster.ZombieVillager
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
- void lambda$readAdditionalSaveData$2(MerchantOffers)
+ void setTradeOffers(CompoundTag)
- void setTradeOffers(MerchantOffers)
```

</details>





<details>
<summary>
net.minecraft.world.entity.monster.hoglin.Hoglin
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>


<details>
<summary>
net.minecraft.world.entity.monster.piglin.Piglin
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>







<details>
<summary>
net.minecraft.world.entity.monster.warden.Warden
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>



<details>
<summary>
net.minecraft.world.entity.npc.AbstractVillager
</summary>

```diff
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
- void lambda$readAdditionalSaveData$0(MerchantOffers)
```

</details>
























<details>
<summary>
net.minecraft.world.entity.projectile.Fireball
</summary>

```diff
- ItemStack getDefaultItem()
+ ItemStack getItemRaw()
```

</details>







<details>
<summary>
net.minecraft.world.entity.projectile.ThrowableItemProjectile
</summary>

```diff
+ ItemStack getItemRaw()
```

</details>









<details>
<summary>
net.minecraft.world.entity.raid.Raids
</summary>

```diff
- CompoundTag save(CompoundTag,HolderLookup$Provider)
+ CompoundTag save(CompoundTag)
- Raids lambda$factory$1(ServerLevel,CompoundTag,HolderLookup$Provider)
+ Raids lambda$factory$1(ServerLevel,CompoundTag)
```

</details>




































































































<details>
<summary>
net.minecraft.world.item.Equipable
</summary>

```diff
- Holder getEquipSound()
+ SoundEvent getEquipSound()
```

</details>













<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
+ IllegalArgumentException lambda$addAttributeModifier$15()
- IllegalArgumentException lambda$addAttributeModifier$17()
- ItemStack lambda$optionalFieldOf$11(Optional)
- ItemStack transmuteCopy(ItemLike,int)
- ItemStack transmuteCopyIgnoreEmpty(ItemLike,int)
+ List lambda$expandBlockState$12(BlockStateParser$BlockResult)
- List lambda$expandBlockState$14(BlockStateParser$BlockResult)
+ List lambda$expandBlockState$14(BlockStateParser$TagResult)
- List lambda$expandBlockState$16(BlockStateParser$TagResult)
- MapCodec optionalFieldOf(String)
+ MutableComponent lambda$expandBlockState$13(Holder)
- MutableComponent lambda$expandBlockState$15(Holder)
- Optional lambda$optionalFieldOf$12(ItemStack)
+ Style lambda$getDisplayName$16(Style)
- Style lambda$getDisplayName$18(Style)
+ void lambda$appendEnchantmentNames$11(List,CompoundTag,Enchantment)
- void lambda$appendEnchantmentNames$13(List,CompoundTag,Enchantment)
```

</details>




<details>
<summary>
net.minecraft.world.item.MapItem
</summary>

```diff
+ Component getTooltipForId(int)
- Component getTooltipForId(MapId)
+ int createNewSavedData(Level,int,int,int,boolean,boolean,ResourceKey)
+ Integer getMapId(ItemStack)
- MapId createNewSavedData(Level,int,int,int,boolean,boolean,ResourceKey)
- MapId getMapId(ItemStack)
+ MapItemSavedData getSavedData(Integer,Level)
- MapItemSavedData getSavedData(MapId,Level)
+ String makeKey(int)
+ void storeMapData(ItemStack,int)
- void storeMapData(ItemStack,MapId)
```

</details>














































































<details>
<summary>
net.minecraft.world.item.trading.MerchantOffer
</summary>

```diff
- App lambda$static$11(RecordCodecBuilder$Instance)
- Boolean lambda$static$10(MerchantOffer)
- Boolean lambda$static$5(MerchantOffer)
+ CompoundTag createTag()
- Float lambda$static$8(MerchantOffer)
- Integer lambda$static$3(MerchantOffer)
- Integer lambda$static$4(MerchantOffer)
- Integer lambda$static$6(MerchantOffer)
- Integer lambda$static$7(MerchantOffer)
- Integer lambda$static$9(MerchantOffer)
- ItemStack lambda$static$0(MerchantOffer)
- ItemStack lambda$static$1(MerchantOffer)
- ItemStack lambda$static$2(MerchantOffer)
+ void <init>(CompoundTag)
- void <init>(ItemStack,ItemStack,ItemStack,int,int,boolean,int,int,float,int,boolean)
```

</details>













<details>
<summary>
net.minecraft.world.level.ForcedChunksSavedData
</summary>

```diff
- CompoundTag save(CompoundTag,HolderLookup$Provider)
+ CompoundTag save(CompoundTag)
- ForcedChunksSavedData load(CompoundTag,HolderLookup$Provider)
+ ForcedChunksSavedData load(CompoundTag)
```

</details>







































































<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
- void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag,RegistryAccess)
+ void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag)
```

</details>






















































































































<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
- void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag,RegistryAccess)
+ void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag)
- void lambda$getCloneItemStack$5(ItemStack,LevelReader,ShulkerBoxBlockEntity)
+ void lambda$getCloneItemStack$5(ItemStack,ShulkerBoxBlockEntity)
```

</details>









<details>
<summary>
net.minecraft.world.level.block.SpawnerBlock
</summary>

```diff
- void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag,RegistryAccess)
+ void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag)
```

</details>
















<details>
<summary>
net.minecraft.world.level.block.TrialSpawnerBlock
</summary>

```diff
- void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag,RegistryAccess)
+ void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerData
</summary>

```diff
+ void tryDetectPlayers(ServerLevel,BlockPos,PlayerDetector,int)
- void tryDetectPlayers(ServerLevel,BlockPos,PlayerDetector,PlayerDetector$EntitySelector,int)
```

</details>



<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapIndex
</summary>

```diff
- CompoundTag save(CompoundTag,HolderLookup$Provider)
+ CompoundTag save(CompoundTag)
+ int getFreeAuxValueForMap()
- MapId getFreeAuxValueForMap()
- MapIndex load(CompoundTag,HolderLookup$Provider)
+ MapIndex load(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
</summary>

```diff
+ Packet nextUpdatePacket(int)
- Packet nextUpdatePacket(MapId)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.CommandStorage
</summary>

```diff
- CommandStorage$Container lambda$factory$1(String,CompoundTag,HolderLookup$Provider)
+ CommandStorage$Container lambda$factory$1(String,CompoundTag)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.DimensionDataStorage
</summary>

```diff
- SavedData readSavedData(BiFunction,DataFixTypes,String)
+ SavedData readSavedData(Function,DataFixTypes,String)
- void <init>(File,DataFixer,HolderLookup$Provider)
+ void <init>(File,DataFixer)
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.LevelStorageSource
</summary>

```diff
+ Dynamic wrapWithRegistryOps(Dynamic,RegistryAccess$Frozen)
```

</details>














<details>
<summary>
net.minecraft.world.level.storage.loot.LootDataType
</summary>

```diff
- Optional deserialize(ResourceLocation,DynamicOps,Object)
+ Optional deserialize(ResourceLocation,JsonElement)
```

</details>



















































<details>
<summary>
net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
</summary>

```diff
- void lambda$static$18(LootContextParamSet$Builder)
```

</details>






























































<details>
<summary>
net.minecraft.world.scores.ScoreboardSaveData
</summary>

```diff
- CompoundTag save(CompoundTag,HolderLookup$Provider)
+ CompoundTag save(CompoundTag)
```

</details>
</details>