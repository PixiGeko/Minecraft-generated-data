## Comparison with [1.20.2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.20.2)

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
<table><tr><th></th><th align="left">1.20.2</th><th>23w40a</th></tr><tr><td>DataPack version</td><td><code>18</code></td><td><code>19</code></td></tr><tr><td>World version</td><td><code>3578</code></td><td><code>3679</code></td></tr><tr><td>Protocol version</td><td><code>764</code></td><td><code>1073741978</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ block_type.txt
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
+ universal_tags/block_type.json
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ commands.kick.owner.failed: Cannot kick server owner in LAN game
+ gui.loadingMinecraft: Loading Minecraft
+ mco.snapshotRealmsPopup.message: Realms are now available in Snapshots starting with Snapshot 23w41a. Every Realms subscription comes with a free Snapshot Realm that is separate from your normal Java Realm!
+ mco.snapshotRealmsPopup.title: Realms now available in Snapshots
+ mco.snapshotRealmsPopup.urlText: Learn More
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/tags/damage_type/can_break_armor_stand.json
+ minecraft/tags/entity_types/can_breathe_under_water.json
+ minecraft/tags/entity_types/undead.json
+ minecraft/tags/entity_types/zombies.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/gui/realms/snapshot_realms.png
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
- net.minecraft.advancements.Advancement
+ net.minecraft.advancements.Advancement$Builder
- net.minecraft.advancements.AdvancementHolder
+ net.minecraft.advancements.AdvancementNode
- net.minecraft.advancements.AdvancementProgress
+ net.minecraft.advancements.AdvancementRequirements
- net.minecraft.advancements.AdvancementRequirements$Strategy
+ net.minecraft.advancements.AdvancementRewards
- net.minecraft.advancements.AdvancementRewards$Builder
+ net.minecraft.advancements.AdvancementTree
- net.minecraft.advancements.AdvancementTree$Listener
- net.minecraft.advancements.critereon.AbstractCriterionTriggerInstance
+ net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
- net.minecraft.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.BlockPredicate
- net.minecraft.advancements.critereon.BlockPredicate$Builder
+ net.minecraft.advancements.critereon.BredAnimalsTrigger
- net.minecraft.advancements.critereon.BredAnimalsTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.BrewedPotionTrigger
- net.minecraft.advancements.critereon.BrewedPotionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ChangeDimensionTrigger
- net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ChanneledLightningTrigger
- net.minecraft.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ConstructBeaconTrigger
- net.minecraft.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ConsumeItemTrigger
- net.minecraft.advancements.critereon.ConsumeItemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ContextAwarePredicate
- net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
+ net.minecraft.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
- net.minecraft.advancements.critereon.DamagePredicate
+ net.minecraft.advancements.critereon.DamagePredicate$Builder
- net.minecraft.advancements.critereon.DamageSourcePredicate
+ net.minecraft.advancements.critereon.DamageSourcePredicate$Builder
- net.minecraft.advancements.critereon.DeserializationContext
+ net.minecraft.advancements.critereon.DistancePredicate
- net.minecraft.advancements.critereon.DistanceTrigger
+ net.minecraft.advancements.critereon.DistanceTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EffectsChangedTrigger
+ net.minecraft.advancements.critereon.EffectsChangedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EnchantedItemTrigger
+ net.minecraft.advancements.critereon.EnchantedItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EnchantmentPredicate
+ net.minecraft.advancements.critereon.EnterBlockTrigger
- net.minecraft.advancements.critereon.EnterBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EntityEquipmentPredicate
- net.minecraft.advancements.critereon.EntityEquipmentPredicate$Builder
+ net.minecraft.advancements.critereon.EntityFlagsPredicate
- net.minecraft.advancements.critereon.EntityFlagsPredicate$Builder
+ net.minecraft.advancements.critereon.EntityHurtPlayerTrigger
- net.minecraft.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EntityPredicate
- net.minecraft.advancements.critereon.EntityPredicate$Builder
+ net.minecraft.advancements.critereon.EntitySubPredicate
- net.minecraft.advancements.critereon.EntitySubPredicate$Type
+ net.minecraft.advancements.critereon.EntitySubPredicate$Types
- net.minecraft.advancements.critereon.EntitySubPredicate$Types$1
+ net.minecraft.advancements.critereon.EntityTypePredicate
- net.minecraft.advancements.critereon.EntityVariantPredicate
+ net.minecraft.advancements.critereon.EntityVariantPredicate$SubPredicate
- net.minecraft.advancements.critereon.FilledBucketTrigger
+ net.minecraft.advancements.critereon.FilledBucketTrigger$TriggerInstance
- net.minecraft.advancements.critereon.FishingHookPredicate
+ net.minecraft.advancements.critereon.FishingRodHookedTrigger
- net.minecraft.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.FluidPredicate
- net.minecraft.advancements.critereon.FluidPredicate$Builder
+ net.minecraft.advancements.critereon.ImpossibleTrigger
- net.minecraft.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.InventoryChangeTrigger
- net.minecraft.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ItemDurabilityTrigger
- net.minecraft.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ItemPredicate
- net.minecraft.advancements.critereon.ItemPredicate$Builder
+ net.minecraft.advancements.critereon.ItemUsedOnLocationTrigger
- net.minecraft.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.KilledByCrossbowTrigger
- net.minecraft.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.KilledTrigger
- net.minecraft.advancements.critereon.KilledTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.LevitationTrigger
- net.minecraft.advancements.critereon.LevitationTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.LightningBoltPredicate
- net.minecraft.advancements.critereon.LightningStrikeTrigger
+ net.minecraft.advancements.critereon.LightningStrikeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.LightPredicate
- net.minecraft.advancements.critereon.LightPredicate$Builder
- net.minecraft.advancements.critereon.LocationPredicate
+ net.minecraft.advancements.critereon.LocationPredicate$Builder
- net.minecraft.advancements.critereon.LocationPredicate$PositionPredicate
+ net.minecraft.advancements.critereon.LootTableTrigger
- net.minecraft.advancements.critereon.LootTableTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.MinMaxBounds
- net.minecraft.advancements.critereon.MinMaxBounds$BoundsFactory
+ net.minecraft.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
- net.minecraft.advancements.critereon.MinMaxBounds$Doubles
+ net.minecraft.advancements.critereon.MinMaxBounds$Ints
- net.minecraft.advancements.critereon.MobEffectsPredicate
+ net.minecraft.advancements.critereon.MobEffectsPredicate$Builder
- net.minecraft.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
+ net.minecraft.advancements.critereon.NbtPredicate
+ net.minecraft.advancements.critereon.package-info
- net.minecraft.advancements.critereon.PickedUpItemTrigger
+ net.minecraft.advancements.critereon.PickedUpItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerHurtEntityTrigger
+ net.minecraft.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerInteractTrigger
+ net.minecraft.advancements.critereon.PlayerInteractTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementPredicate
- net.minecraft.advancements.critereon.PlayerPredicate$Builder
+ net.minecraft.advancements.critereon.PlayerPredicate$StatMatcher
- net.minecraft.advancements.critereon.PlayerTrigger
+ net.minecraft.advancements.critereon.PlayerTrigger$TriggerInstance
- net.minecraft.advancements.critereon.RecipeCraftedTrigger
+ net.minecraft.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.RecipeUnlockedTrigger
+ net.minecraft.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ShotCrossbowTrigger
+ net.minecraft.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
- net.minecraft.advancements.critereon.SimpleCriterionTrigger
+ net.minecraft.advancements.critereon.SimpleCriterionTrigger$SimpleInstance
- net.minecraft.advancements.critereon.SlideDownBlockTrigger
+ net.minecraft.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.SlimePredicate
+ net.minecraft.advancements.critereon.StartRidingTrigger
- net.minecraft.advancements.critereon.StartRidingTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.StatePropertiesPredicate
- net.minecraft.advancements.critereon.StatePropertiesPredicate$Builder
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$ExactMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$RangedMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$ValueMatcher
+ net.minecraft.advancements.critereon.SummonedEntityTrigger
- net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TagPredicate
- net.minecraft.advancements.critereon.TameAnimalTrigger
+ net.minecraft.advancements.critereon.TameAnimalTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TargetBlockTrigger
+ net.minecraft.advancements.critereon.TargetBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TradeTrigger
+ net.minecraft.advancements.critereon.TradeTrigger$TriggerInstance
- net.minecraft.advancements.critereon.UsedEnderEyeTrigger
+ net.minecraft.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
- net.minecraft.advancements.critereon.UsedTotemTrigger
+ net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.UsingItemTrigger
+ net.minecraft.advancements.critereon.UsingItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.WrappedMinMaxBounds
+ net.minecraft.advancements.CriteriaTriggers
- net.minecraft.advancements.Criterion
+ net.minecraft.advancements.CriterionProgress
- net.minecraft.advancements.CriterionTrigger
+ net.minecraft.advancements.CriterionTrigger$Listener
- net.minecraft.advancements.CriterionTriggerInstance
+ net.minecraft.advancements.DisplayInfo
- net.minecraft.advancements.FrameType
- net.minecraft.advancements.package-info
+ net.minecraft.advancements.TreeNodePosition
- net.minecraft.commands.arguments.AngleArgument
+ net.minecraft.commands.arguments.AngleArgument$SingleAngle
- net.minecraft.commands.arguments.ArgumentSignatures
+ net.minecraft.commands.arguments.ArgumentSignatures$Entry
- net.minecraft.commands.arguments.ArgumentSignatures$Signer
- net.minecraft.commands.arguments.blocks.BlockInput
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.blocks.BlockStateArgument
- net.minecraft.commands.arguments.blocks.BlockStateParser
+ net.minecraft.commands.arguments.blocks.BlockStateParser$BlockResult
- net.minecraft.commands.arguments.blocks.BlockStateParser$TagResult
+ net.minecraft.commands.arguments.blocks.package-info
+ net.minecraft.commands.arguments.ColorArgument
- net.minecraft.commands.arguments.ComponentArgument
+ net.minecraft.commands.arguments.CompoundTagArgument
- net.minecraft.commands.arguments.coordinates.BlockPosArgument
+ net.minecraft.commands.arguments.coordinates.ColumnPosArgument
- net.minecraft.commands.arguments.coordinates.Coordinates
+ net.minecraft.commands.arguments.coordinates.LocalCoordinates
- net.minecraft.commands.arguments.coordinates.package-info
- net.minecraft.commands.arguments.coordinates.RotationArgument
+ net.minecraft.commands.arguments.coordinates.SwizzleArgument
- net.minecraft.commands.arguments.coordinates.Vec2Argument
+ net.minecraft.commands.arguments.coordinates.Vec3Argument
- net.minecraft.commands.arguments.coordinates.WorldCoordinate
+ net.minecraft.commands.arguments.coordinates.WorldCoordinates
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
+ net.minecraft.commands.arguments.item.FunctionArgument
- net.minecraft.commands.arguments.item.FunctionArgument$1
+ net.minecraft.commands.arguments.item.FunctionArgument$2
- net.minecraft.commands.arguments.item.FunctionArgument$Result
+ net.minecraft.commands.arguments.item.ItemArgument
- net.minecraft.commands.arguments.item.ItemInput
+ net.minecraft.commands.arguments.item.ItemParser
- net.minecraft.commands.arguments.item.ItemParser$ItemResult
+ net.minecraft.commands.arguments.item.ItemParser$TagResult
- net.minecraft.commands.arguments.item.ItemPredicateArgument
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
- net.minecraft.commands.arguments.item.package-info
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
+ net.minecraft.commands.arguments.package-info
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
- net.minecraft.commands.arguments.selector.EntitySelector
+ net.minecraft.commands.arguments.selector.EntitySelector$1
- net.minecraft.commands.arguments.selector.EntitySelectorParser
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
- net.minecraft.commands.arguments.selector.options.package-info
+ net.minecraft.commands.arguments.selector.package-info
- net.minecraft.commands.arguments.SignedArgument
+ net.minecraft.commands.arguments.SlotArgument
- net.minecraft.commands.arguments.StringRepresentableArgument
+ net.minecraft.commands.arguments.TeamArgument
- net.minecraft.commands.arguments.TemplateMirrorArgument
+ net.minecraft.commands.arguments.TemplateRotationArgument
- net.minecraft.commands.arguments.TimeArgument
+ net.minecraft.commands.arguments.TimeArgument$Info
- net.minecraft.commands.arguments.TimeArgument$Info$Template
+ net.minecraft.commands.arguments.UuidArgument
+ net.minecraft.commands.BrigadierExceptions
- net.minecraft.commands.CommandBuildContext
+ net.minecraft.commands.CommandBuildContext$1
- net.minecraft.commands.CommandBuildContext$2
+ net.minecraft.commands.CommandBuildContext$2$1
- net.minecraft.commands.CommandBuildContext$3
+ net.minecraft.commands.CommandBuildContext$Configurable
- net.minecraft.commands.CommandBuildContext$MissingTagAccessPolicy
+ net.minecraft.commands.CommandFunction
- net.minecraft.commands.CommandFunction$CacheableFunction
+ net.minecraft.commands.CommandFunction$CommandEntry
- net.minecraft.commands.CommandFunction$CommandMacro
+ net.minecraft.commands.CommandFunction$Entry
- net.minecraft.commands.CommandFunction$FunctionEntry
+ net.minecraft.commands.CommandFunction$MacroEntry
- net.minecraft.commands.CommandRuntimeException
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
- net.minecraft.commands.FunctionInstantiationException
- net.minecraft.commands.package-info
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
+ net.minecraft.core.BlockPos$MutableBlockPos
+ net.minecraft.core.cauldron.CauldronInteraction
- net.minecraft.core.cauldron.CauldronInteraction$InteractionMap
- net.minecraft.core.Cursor3D
+ net.minecraft.core.DefaultedMappedRegistry
- net.minecraft.core.DefaultedRegistry
+ net.minecraft.core.Direction
- net.minecraft.core.Direction$1
+ net.minecraft.core.Direction$Axis
- net.minecraft.core.Direction$Axis$1
+ net.minecraft.core.Direction$Axis$2
- net.minecraft.core.Direction$Axis$3
+ net.minecraft.core.Direction$AxisDirection
- net.minecraft.core.Direction$Plane
+ net.minecraft.core.Direction8
- net.minecraft.core.FrontAndTop
+ net.minecraft.core.GlobalPos
- net.minecraft.core.Holder
+ net.minecraft.core.Holder$Direct
- net.minecraft.core.Holder$Kind
+ net.minecraft.core.Holder$Reference
- net.minecraft.core.Holder$Reference$Type
+ net.minecraft.core.HolderGetter
- net.minecraft.core.HolderGetter$Provider
+ net.minecraft.core.HolderLookup
- net.minecraft.core.HolderLookup$1
+ net.minecraft.core.HolderLookup$Delegate
- net.minecraft.core.HolderLookup$Provider
+ net.minecraft.core.HolderLookup$Provider$1
- net.minecraft.core.HolderLookup$Provider$2
+ net.minecraft.core.HolderLookup$RegistryLookup
- net.minecraft.core.HolderLookup$RegistryLookup$Delegate
+ net.minecraft.core.HolderOwner
- net.minecraft.core.HolderSet
+ net.minecraft.core.HolderSet$Direct
- net.minecraft.core.HolderSet$ListBacked
+ net.minecraft.core.HolderSet$Named
- net.minecraft.core.IdMap
+ net.minecraft.core.IdMapper
- net.minecraft.core.LayeredRegistryAccess
+ net.minecraft.core.MappedRegistry
- net.minecraft.core.MappedRegistry$1
+ net.minecraft.core.MappedRegistry$2
- net.minecraft.core.NonNullList
+ net.minecraft.core.Position
- net.minecraft.core.QuartPos
+ net.minecraft.core.Registry
- net.minecraft.core.Registry$1
+ net.minecraft.core.Registry$2
- net.minecraft.core.RegistryAccess
+ net.minecraft.core.RegistryAccess$1
- net.minecraft.core.RegistryAccess$1FrozenAccess
+ net.minecraft.core.RegistryAccess$Frozen
- net.minecraft.core.RegistryAccess$ImmutableRegistryAccess
+ net.minecraft.core.RegistryAccess$RegistryEntry
- net.minecraft.core.RegistryCodecs
+ net.minecraft.core.RegistryCodecs$RegistryEntry
- net.minecraft.core.RegistrySetBuilder
+ net.minecraft.core.RegistrySetBuilder$1
- net.minecraft.core.RegistrySetBuilder$BuildState
+ net.minecraft.core.RegistrySetBuilder$BuildState$1
- net.minecraft.core.RegistrySetBuilder$CompositeOwner
+ net.minecraft.core.RegistrySetBuilder$EmptyTagLookup
- net.minecraft.core.RegistrySetBuilder$RegisteredValue
+ net.minecraft.core.RegistrySetBuilder$RegistryBootstrap
- net.minecraft.core.RegistrySetBuilder$RegistryContents
+ net.minecraft.core.RegistrySetBuilder$RegistryContents$1
- net.minecraft.core.RegistrySetBuilder$RegistryStub
+ net.minecraft.core.RegistrySetBuilder$UniversalLookup
- net.minecraft.core.RegistrySetBuilder$ValueAndHolder
+ net.minecraft.core.RegistrySynchronization
- net.minecraft.core.RegistrySynchronization$NetworkedRegistryData
+ net.minecraft.core.Rotations
- net.minecraft.core.SectionPos
+ net.minecraft.core.SectionPos$1
- net.minecraft.core.UUIDUtil
+ net.minecraft.core.Vec3i
- net.minecraft.core.WritableRegistry
- net.minecraft.network.chat.Component$SerializerAdapter
+ net.minecraft.network.chat.ComponentContents
- net.minecraft.network.chat.ComponentContents$Type
- net.minecraft.network.chat.ComponentSerialization$FuzzyCodec
+ net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.contents.EntityDataSource
+ net.minecraft.network.chat.contents.KeybindContents
- net.minecraft.network.chat.contents.KeybindResolver
+ net.minecraft.network.chat.contents.LiteralContents
- net.minecraft.network.chat.contents.package-info
- net.minecraft.network.chat.contents.PlainTextContents
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
+ net.minecraft.network.chat.package-info
- net.minecraft.network.package-info
+ net.minecraft.network.protocol.BundleDelimiterPacket
- net.minecraft.network.protocol.BundlePacket
+ net.minecraft.network.protocol.BundlerInfo
- net.minecraft.network.protocol.BundlerInfo$1
+ net.minecraft.network.protocol.BundlerInfo$2
- net.minecraft.network.protocol.BundlerInfo$2$1
+ net.minecraft.network.protocol.BundlerInfo$Bundler
- net.minecraft.network.protocol.BundlerInfo$Provider
+ net.minecraft.network.protocol.common.ClientboundCustomPayloadPacket
- net.minecraft.network.protocol.common.ClientboundDisconnectPacket
+ net.minecraft.network.protocol.common.ClientboundKeepAlivePacket
- net.minecraft.network.protocol.common.ClientboundPingPacket
+ net.minecraft.network.protocol.common.ClientboundResourcePackPacket
- net.minecraft.network.protocol.common.ClientboundUpdateTagsPacket
- net.minecraft.network.protocol.common.ClientCommonPacketListener
- net.minecraft.network.protocol.common.custom.BeeDebugPayload
+ net.minecraft.network.protocol.common.custom.BeeDebugPayload$BeeInfo
- net.minecraft.network.protocol.common.custom.BrainDebugPayload
+ net.minecraft.network.protocol.common.custom.BrainDebugPayload$BrainDump
- net.minecraft.network.protocol.common.custom.BrandPayload
+ net.minecraft.network.protocol.common.custom.CustomPacketPayload
- net.minecraft.network.protocol.common.custom.DiscardedPayload
+ net.minecraft.network.protocol.common.custom.GameEventDebugPayload
- net.minecraft.network.protocol.common.custom.GameEventListenerDebugPayload
+ net.minecraft.network.protocol.common.custom.GameTestAddMarkerDebugPayload
- net.minecraft.network.protocol.common.custom.GameTestClearMarkersDebugPayload
+ net.minecraft.network.protocol.common.custom.GoalDebugPayload
- net.minecraft.network.protocol.common.custom.GoalDebugPayload$DebugGoal
+ net.minecraft.network.protocol.common.custom.HiveDebugPayload
- net.minecraft.network.protocol.common.custom.HiveDebugPayload$HiveInfo
+ net.minecraft.network.protocol.common.custom.NeighborUpdatesDebugPayload
+ net.minecraft.network.protocol.common.custom.package-info
- net.minecraft.network.protocol.common.custom.PathfindingDebugPayload
+ net.minecraft.network.protocol.common.custom.PoiAddedDebugPayload
- net.minecraft.network.protocol.common.custom.PoiRemovedDebugPayload
+ net.minecraft.network.protocol.common.custom.PoiTicketCountDebugPayload
- net.minecraft.network.protocol.common.custom.RaidsDebugPayload
+ net.minecraft.network.protocol.common.custom.StructuresDebugPayload
- net.minecraft.network.protocol.common.custom.StructuresDebugPayload$PieceInfo
+ net.minecraft.network.protocol.common.custom.VillageSectionsDebugPayload
- net.minecraft.network.protocol.common.custom.WorldGenAttemptDebugPayload
- net.minecraft.network.protocol.common.package-info
- net.minecraft.network.protocol.common.ServerboundClientInformationPacket
+ net.minecraft.network.protocol.common.ServerboundCustomPayloadPacket
- net.minecraft.network.protocol.common.ServerboundKeepAlivePacket
+ net.minecraft.network.protocol.common.ServerboundPongPacket
- net.minecraft.network.protocol.common.ServerboundResourcePackPacket
+ net.minecraft.network.protocol.common.ServerboundResourcePackPacket$Action
+ net.minecraft.network.protocol.common.ServerCommonPacketListener
- net.minecraft.network.protocol.configuration.ClientboundFinishConfigurationPacket
+ net.minecraft.network.protocol.configuration.ClientboundRegistryDataPacket
- net.minecraft.network.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
+ net.minecraft.network.protocol.configuration.ClientConfigurationPacketListener
+ net.minecraft.network.protocol.configuration.package-info
- net.minecraft.network.protocol.configuration.ServerboundFinishConfigurationPacket
+ net.minecraft.network.protocol.configuration.ServerConfigurationPacketListener
+ net.minecraft.network.protocol.game.ClientboundAddEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
+ net.minecraft.network.protocol.game.ClientboundAnimatePacket
- net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
+ net.minecraft.network.protocol.game.ClientboundBlockChangedAckPacket
- net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundBlockEventPacket
+ net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$OperationType
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
- net.minecraft.network.protocol.game.ClientboundBundlePacket
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundChunkBatchFinishedPacket
+ net.minecraft.network.protocol.game.ClientboundChunkBatchStartPacket
- net.minecraft.network.protocol.game.ClientboundChunksBiomesPacket
+ net.minecraft.network.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
- net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
- net.minecraft.network.protocol.game.ClientboundContainerClosePacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
- net.minecraft.network.protocol.game.ClientboundCooldownPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ net.minecraft.network.protocol.game.ClientboundDamageEventPacket
- net.minecraft.network.protocol.game.ClientboundDeleteChatPacket
+ net.minecraft.network.protocol.game.ClientboundDisguisedChatPacket
- net.minecraft.network.protocol.game.ClientboundEntityEventPacket
+ net.minecraft.network.protocol.game.ClientboundExplodePacket
- net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
+ net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
- net.minecraft.network.protocol.game.ClientboundHurtAnimationPacket
+ net.minecraft.network.protocol.game.ClientboundInitializeBorderPacket
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
+ net.minecraft.network.protocol.game.ClientboundLevelChunkWithLightPacket
- net.minecraft.network.protocol.game.ClientboundLevelEventPacket
+ net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundLightUpdatePacketData
- net.minecraft.network.protocol.game.ClientboundLoginPacket
+ net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
- net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
+ net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ClientboundOpenBookPacket
+ net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
- net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
+ net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
- net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerChatPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatEndPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatEnterPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatKillPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoRemovePacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
- net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
- net.minecraft.network.protocol.game.ClientboundRecipePacket
+ net.minecraft.network.protocol.game.ClientboundRecipePacket$State
- net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
+ net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundRespawnPacket
+ net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
- net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
- net.minecraft.network.protocol.game.ClientboundServerDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
- net.minecraft.network.protocol.game.ClientboundSetBorderSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDistancePacket
+ net.minecraft.network.protocol.game.ClientboundSetCameraPacket
- net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
- net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
+ net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
- net.minecraft.network.protocol.game.ClientboundSetHealthPacket
+ net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- net.minecraft.network.protocol.game.ClientboundSetScorePacket
+ net.minecraft.network.protocol.game.ClientboundSetSimulationDistancePacket
- net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetTimePacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
- net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
- net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
+ net.minecraft.network.protocol.game.ClientboundSoundPacket
- net.minecraft.network.protocol.game.ClientboundStartConfigurationPacket
+ net.minecraft.network.protocol.game.ClientboundStopSoundPacket
- net.minecraft.network.protocol.game.ClientboundSystemChatPacket
+ net.minecraft.network.protocol.game.ClientboundTabListPacket
- net.minecraft.network.protocol.game.ClientboundTagQueryPacket
+ net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
- net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
- net.minecraft.network.protocol.game.ClientGamePacketListener
- net.minecraft.network.protocol.game.CommonPlayerSpawnInfo
+ net.minecraft.network.protocol.game.DebugEntityNameGenerator
- net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.package-info
- net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
+ net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundChatAckPacket
- net.minecraft.network.protocol.game.ServerboundChatCommandPacket
+ net.minecraft.network.protocol.game.ServerboundChatPacket
- net.minecraft.network.protocol.game.ServerboundChatSessionUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundChunkBatchReceivedPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
+ net.minecraft.network.protocol.game.ServerboundConfigurationAcknowledgedPacket
- net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClosePacket
+ net.minecraft.network.protocol.game.ServerboundEditBookPacket
- net.minecraft.network.protocol.game.ServerboundEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundInteractPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$1
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$StatusOnly
+ net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
+ net.minecraft.network.protocol.game.ServerboundPickItemPacket
- net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
+ net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ net.minecraft.network.protocol.game.ServerboundRenameItemPacket
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
- net.minecraft.network.protocol.game.ServerboundSelectTradePacket
+ net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
- net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
+ net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
- net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
- net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundSwingPacket
- net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
- net.minecraft.network.protocol.game.ServerboundUseItemPacket
+ net.minecraft.network.protocol.game.ServerGamePacketListener
- net.minecraft.network.protocol.game.ServerPacketListener
+ net.minecraft.network.protocol.game.ServerPingPacketListener
+ net.minecraft.network.protocol.game.VecDeltaCodec
+ net.minecraft.network.protocol.handshake.ClientIntent
- net.minecraft.network.protocol.handshake.ClientIntent$1
+ net.minecraft.network.protocol.handshake.ClientIntentionPacket
+ net.minecraft.network.protocol.handshake.package-info
- net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
+ net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
- net.minecraft.network.protocol.login.ClientboundGameProfilePacket
+ net.minecraft.network.protocol.login.ClientboundHelloPacket
- net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
+ net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
- net.minecraft.network.protocol.login.ClientLoginPacketListener
+ net.minecraft.network.protocol.login.custom.CustomQueryAnswerPayload
- net.minecraft.network.protocol.login.custom.CustomQueryPayload
+ net.minecraft.network.protocol.login.custom.DiscardedQueryAnswerPayload
- net.minecraft.network.protocol.login.custom.DiscardedQueryPayload
+ net.minecraft.network.protocol.login.custom.package-info
- net.minecraft.network.protocol.login.package-info
+ net.minecraft.network.protocol.login.ServerboundCustomQueryAnswerPacket
- net.minecraft.network.protocol.login.ServerboundHelloPacket
+ net.minecraft.network.protocol.login.ServerboundKeyPacket
- net.minecraft.network.protocol.login.ServerboundLoginAcknowledgedPacket
- net.minecraft.network.protocol.login.ServerLoginPacketListener
+ net.minecraft.network.protocol.package-info
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketUtils
+ net.minecraft.network.protocol.status.ClientboundPongResponsePacket
- net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
- net.minecraft.network.protocol.status.ClientStatusPacketListener
- net.minecraft.network.protocol.status.package-info
- net.minecraft.network.protocol.status.ServerboundPingRequestPacket
+ net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
+ net.minecraft.network.protocol.status.ServerStatus
- net.minecraft.network.protocol.status.ServerStatus$Favicon
+ net.minecraft.network.protocol.status.ServerStatus$Players
- net.minecraft.network.protocol.status.ServerStatus$Version
+ net.minecraft.network.protocol.status.ServerStatusPacketListener
+ net.minecraft.network.syncher.EntityDataAccessor
- net.minecraft.network.syncher.EntityDataSerializer
+ net.minecraft.network.syncher.EntityDataSerializer$1
- net.minecraft.network.syncher.EntityDataSerializer$ForValueType
+ net.minecraft.network.syncher.EntityDataSerializers
- net.minecraft.network.syncher.EntityDataSerializers$1
+ net.minecraft.network.syncher.EntityDataSerializers$2
- net.minecraft.network.syncher.EntityDataSerializers$3
+ net.minecraft.network.syncher.EntityDataSerializers$4
- net.minecraft.network.syncher.EntityDataSerializers$5
+ net.minecraft.network.syncher.EntityDataSerializers$6
- net.minecraft.network.syncher.EntityDataSerializers$7
- net.minecraft.network.syncher.package-info
+ net.minecraft.network.syncher.SynchedEntityData
- net.minecraft.network.syncher.SynchedEntityData$DataItem
+ net.minecraft.network.syncher.SynchedEntityData$DataValue
+ net.minecraft.obfuscate.DontObfuscate
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.references.Items
+ net.minecraft.resources.DelegatingOps
- net.minecraft.resources.FileToIdConverter
+ net.minecraft.resources.HolderSetCodec
- net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataLoader
+ net.minecraft.resources.RegistryDataLoader$1
- net.minecraft.resources.RegistryDataLoader$Loader
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
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator$Output
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
- net.minecraft.server.advancements.package-info
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$Entry
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
+ net.minecraft.server.commands.DataPackCommand
- net.minecraft.server.commands.DataPackCommand$Inserter
- net.minecraft.server.commands.DebugCommand
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
+ net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
- net.minecraft.server.commands.ExecuteCommand$CommandPredicate
+ net.minecraft.server.commands.ExperienceCommand
- net.minecraft.server.commands.ExperienceCommand$Type
+ net.minecraft.server.commands.FillBiomeCommand
- net.minecraft.server.commands.FillCommand
+ net.minecraft.server.commands.FillCommand$Mode
- net.minecraft.server.commands.ForceLoadCommand
+ net.minecraft.server.commands.FunctionCommand
- net.minecraft.server.commands.FunctionCommand$FunctionResult
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
- net.minecraft.server.commands.package-info
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
+ net.minecraft.server.commands.RideCommand
- net.minecraft.server.commands.SaveAllCommand
+ net.minecraft.server.commands.SaveOffCommand
- net.minecraft.server.commands.SaveOnCommand
+ net.minecraft.server.commands.SayCommand
- net.minecraft.server.commands.ScheduleCommand
+ net.minecraft.server.commands.ScoreboardCommand
- net.minecraft.server.commands.SeedCommand
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
- net.minecraft.server.commands.TimeCommand
+ net.minecraft.server.commands.TitleCommand
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
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$ExecutionContext
- net.minecraft.server.ServerFunctionManager$ExecutionContext$AbortingReturnValueConsumer
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerFunctionManager$TraceCallbacks
+ net.minecraft.server.ServerInfo
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
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
- net.minecraft.util.datafix.ComponentDataFixUtils
- net.minecraft.util.ExtraCodecs$EitherCodec
+ net.minecraft.util.ExtraCodecs$RecursiveCodec
- net.minecraft.util.ExtraCodecs$StrictOptionalFieldCodec
+ net.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
- net.minecraft.util.ExtraCodecs$TagOrElementLocation
+ net.minecraft.util.ExtraCodecs$XorCodec
- net.minecraft.util.FastBufferedInputStream
+ net.minecraft.util.FastColor
- net.minecraft.util.FastColor$ABGR32
+ net.minecraft.util.FastColor$ARGB32
- net.minecraft.util.FileZipper
+ net.minecraft.util.FormattedCharSequence
- net.minecraft.util.FormattedCharSink
+ net.minecraft.util.FutureChain
- net.minecraft.util.Graph
+ net.minecraft.util.GsonHelper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.InclusiveRange
- net.minecraft.util.JavaOps
- net.minecraft.util.JavaOps$FixedMapBuilder
- net.minecraft.util.StringUtil
+ net.minecraft.util.TaskChainer
- net.minecraft.util.TaskChainer$DelayedTask
+ net.minecraft.util.ThreadingDetector
- net.minecraft.util.TimeSource
+ net.minecraft.util.TimeSource$NanoTimeSource
- net.minecraft.util.TimeUtil
+ net.minecraft.util.ToFloatFunction
- net.minecraft.util.ToFloatFunction$1
+ net.minecraft.util.ToFloatFunction$2
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.ZeroBitStorage
+ net.minecraft.Util$IdentityStrategy
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
- net.minecraft.world.level.block.BaseTorchBlock
+ net.minecraft.world.level.block.BeaconBeamBlock
- net.minecraft.world.level.block.BeaconBlock
+ net.minecraft.world.level.block.BedBlock
- net.minecraft.world.level.block.BedBlock$1
+ net.minecraft.world.level.block.BeehiveBlock
- net.minecraft.world.level.block.BeetrootBlock
+ net.minecraft.world.level.block.BellBlock
- net.minecraft.world.level.block.BellBlock$1
+ net.minecraft.world.level.block.BigDripleafBlock
- net.minecraft.world.level.block.BigDripleafStemBlock
+ net.minecraft.world.level.block.BigDripleafStemBlock$1
- net.minecraft.world.level.block.BlastFurnaceBlock
+ net.minecraft.world.level.block.Block
- net.minecraft.world.level.block.Block$1
+ net.minecraft.world.level.block.Block$2
- net.minecraft.world.level.block.Block$BlockStatePairKey
- net.minecraft.world.level.block.CommandBlock
+ net.minecraft.world.level.block.ComparatorBlock
- net.minecraft.world.level.block.ComposterBlock
+ net.minecraft.world.level.block.ComposterBlock$EmptyContainer
- net.minecraft.world.level.block.ComposterBlock$InputContainer
+ net.minecraft.world.level.block.ComposterBlock$OutputContainer
- net.minecraft.world.level.block.ConcretePowderBlock
+ net.minecraft.world.level.block.ConduitBlock
- net.minecraft.world.level.block.CoralBlock
+ net.minecraft.world.level.block.CoralFanBlock
- net.minecraft.world.level.block.CoralPlantBlock
+ net.minecraft.world.level.block.CoralWallFanBlock
- net.minecraft.world.level.block.CraftingTableBlock
+ net.minecraft.world.level.block.CropBlock
- net.minecraft.world.level.block.CrossCollisionBlock
+ net.minecraft.world.level.block.CrossCollisionBlock$1
- net.minecraft.world.level.block.CryingObsidianBlock
+ net.minecraft.world.level.block.DaylightDetectorBlock
- net.minecraft.world.level.block.DeadBushBlock
+ net.minecraft.world.level.block.DecoratedPotBlock
- net.minecraft.world.level.block.DetectorRailBlock
+ net.minecraft.world.level.block.DetectorRailBlock$1
- net.minecraft.world.level.block.DiodeBlock
+ net.minecraft.world.level.block.DirectionalBlock
- net.minecraft.world.level.block.DirtPathBlock
+ net.minecraft.world.level.block.DispenserBlock
- net.minecraft.world.level.block.DoorBlock
+ net.minecraft.world.level.block.DoorBlock$1
- net.minecraft.world.level.block.DoubleBlockCombiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
- net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- net.minecraft.world.level.block.DoublePlantBlock
+ net.minecraft.world.level.block.DragonEggBlock
- net.minecraft.world.level.block.DropExperienceBlock
+ net.minecraft.world.level.block.DropperBlock
- net.minecraft.world.level.block.EnchantmentTableBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
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
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DecoratedPotBlockEntity
- net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$Decorations
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
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.EquipableCarvedPumpkinBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
- net.minecraft.world.level.block.Fallable
+ net.minecraft.world.level.block.FallingBlock
- net.minecraft.world.level.block.FarmBlock
+ net.minecraft.world.level.block.FenceBlock
- net.minecraft.world.level.block.FenceGateBlock
+ net.minecraft.world.level.block.FenceGateBlock$1
- net.minecraft.world.level.block.FireBlock
+ net.minecraft.world.level.block.FletchingTableBlock
- net.minecraft.world.level.block.FlowerBlock
+ net.minecraft.world.level.block.FlowerPotBlock
- net.minecraft.world.level.block.FrogspawnBlock
+ net.minecraft.world.level.block.FrostedIceBlock
- net.minecraft.world.level.block.FungusBlock
+ net.minecraft.world.level.block.FurnaceBlock
- net.minecraft.world.level.block.GameMasterBlock
+ net.minecraft.world.level.block.GlassBlock
- net.minecraft.world.level.block.GlazedTerracottaBlock
+ net.minecraft.world.level.block.GlowLichenBlock
- net.minecraft.world.level.block.GrassBlock
+ net.minecraft.world.level.block.GravelBlock
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.MangroveTreeGrower
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.grower.TreeGrower
+ net.minecraft.world.level.block.MelonBlock
- net.minecraft.world.level.block.Mirror
+ net.minecraft.world.level.block.Mirror$1
- net.minecraft.world.level.block.MossBlock
+ net.minecraft.world.level.block.MudBlock
- net.minecraft.world.level.block.MultifaceBlock
+ net.minecraft.world.level.block.MultifaceSpreader
- net.minecraft.world.level.block.MultifaceSpreader$DefaultSpreaderConfig
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadConfig
- net.minecraft.world.level.block.MultifaceSpreader$SpreadPos
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadPredicate
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType$1
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$2
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType$3
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
+ net.minecraft.world.level.block.PiglinWallSkullBlock
- net.minecraft.world.level.block.PinkPetalsBlock
+ net.minecraft.world.level.block.PipeBlock
- net.minecraft.world.level.block.PitcherCropBlock
+ net.minecraft.world.level.block.PitcherCropBlock$PosAndState
- net.minecraft.world.level.block.PlayerHeadBlock
+ net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PointedDripstoneBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock$FluidInfo
- net.minecraft.world.level.block.PotatoBlock
+ net.minecraft.world.level.block.PowderSnowBlock
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
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
+ net.minecraft.world.level.block.SupportType$1
- net.minecraft.world.level.block.SupportType$2
+ net.minecraft.world.level.block.SupportType$3
- net.minecraft.world.level.block.SuspiciousEffectHolder
+ net.minecraft.world.level.block.SuspiciousEffectHolder$EffectEntry
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TintedGlassBlock
- net.minecraft.world.level.block.TntBlock
+ net.minecraft.world.level.block.TorchBlock
- net.minecraft.world.level.block.TorchflowerCropBlock
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
- net.minecraft.world.level.block.WallHangingSignBlock
+ net.minecraft.world.level.block.WallHangingSignBlock$1
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
+ net.minecraft.world.level.block.WoolCarpetBlock
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
- net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.SectionStorage
+ net.minecraft.world.level.chunk.StructureAccess
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
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
+ net.minecraft.world.level.gameevent.GameEventListener$Holder
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
- net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
- net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.package-info
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
- net.minecraft.world.level.levelgen.structure.StructureSet
+ net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- net.minecraft.world.level.levelgen.structure.StructureStart
+ net.minecraft.world.level.levelgen.structure.StructureType
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
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
- net.minecraft.world.level.levelgen.synth.BlendedNoise
+ net.minecraft.world.level.levelgen.synth.ImprovedNoise
- net.minecraft.world.level.levelgen.synth.NoiseUtils
+ net.minecraft.world.level.levelgen.synth.NormalNoise
- net.minecraft.world.level.levelgen.synth.NormalNoise$NoiseParameters
- net.minecraft.world.level.levelgen.synth.package-info
+ net.minecraft.world.level.levelgen.synth.PerlinNoise
- net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
+ net.minecraft.world.level.levelgen.synth.SimplexNoise
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
+ net.minecraft.world.level.pathfinder.package-info
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.Path$DebugData
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
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
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
+ net.minecraft.world.level.saveddata.maps.package-info
- net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.saveddata.SavedData$Factory
+ net.minecraft.world.level.storage.CommandStorage
- net.minecraft.world.level.storage.CommandStorage$Container
+ net.minecraft.world.level.storage.DataVersion
- net.minecraft.world.level.storage.DerivedLevelData
+ net.minecraft.world.level.storage.DimensionDataStorage
- net.minecraft.world.level.storage.LevelData
+ net.minecraft.world.level.storage.LevelResource
- net.minecraft.world.level.storage.LevelStorageException
+ net.minecraft.world.level.storage.LevelStorageSource
- net.minecraft.world.level.storage.LevelStorageSource$LevelCandidates
+ net.minecraft.world.level.storage.LevelStorageSource$LevelDirectory
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
+ net.minecraft.world.level.storage.LevelSummary
- net.minecraft.world.level.storage.LevelSummary$BackupStatus
+ net.minecraft.world.level.storage.LevelSummary$SymlinkLevelSummary
- net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.loot.BuiltInLootTables
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
- net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem
+ net.minecraft.world.level.storage.loot.entries.EntryGroup
- net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
+ net.minecraft.world.level.storage.loot.entries.LootItem
- net.minecraft.world.level.storage.loot.entries.LootPoolEntries
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntry
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ net.minecraft.world.level.storage.loot.entries.LootTableReference
- net.minecraft.world.level.storage.loot.entries.package-info
- net.minecraft.world.level.storage.loot.entries.SequentialEntry
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
- net.minecraft.world.level.storage.loot.entries.TagEntry
+ net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaType
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Path
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FunctionReference
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SequenceFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction
+ net.minecraft.world.level.storage.loot.functions.SetPotionFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$EffectEntry
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.IntRange
+ net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
+ net.minecraft.world.level.storage.loot.LootContext
- net.minecraft.world.level.storage.loot.LootContext$Builder
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget
- net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
+ net.minecraft.world.level.storage.loot.LootContextUser
- net.minecraft.world.level.storage.loot.LootDataId
+ net.minecraft.world.level.storage.loot.LootDataManager
- net.minecraft.world.level.storage.loot.LootDataManager$1
+ net.minecraft.world.level.storage.loot.LootDataResolver
- net.minecraft.world.level.storage.loot.LootDataType
+ net.minecraft.world.level.storage.loot.LootDataType$Validator
- net.minecraft.world.level.storage.loot.LootParams
+ net.minecraft.world.level.storage.loot.LootParams$Builder
- net.minecraft.world.level.storage.loot.LootParams$DynamicDrop
+ net.minecraft.world.level.storage.loot.LootPool
- net.minecraft.world.level.storage.loot.LootPool$Builder
+ net.minecraft.world.level.storage.loot.LootTable
- net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition
+ net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition
+ net.minecraft.world.level.storage.loot.predicates.AnyOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
- net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LocationCheck
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
+ net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
- net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue
+ net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
- net.minecraft.world.level.storage.loot.providers.number.NumberProvider
+ net.minecraft.world.level.storage.loot.providers.number.NumberProviders
- net.minecraft.world.level.storage.loot.providers.number.package-info
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
+ net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
+ net.minecraft.world.level.storage.PrimaryLevelData$SpecialWorldProperty
- net.minecraft.world.level.storage.ServerLevelData
+ net.minecraft.world.level.storage.WorldData
- net.minecraft.world.level.storage.WritableLevelData
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
+ net.minecraft.world.level.timers.package-info
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.level.timers.TimerQueue$Event
- net.minecraft.world.level.validation.ContentValidationException
+ net.minecraft.world.level.validation.DirectoryValidator
- net.minecraft.world.level.validation.DirectoryValidator$1
+ net.minecraft.world.level.validation.ForbiddenSymlinkInfo
+ net.minecraft.world.level.validation.package-info
- net.minecraft.world.level.validation.PathAllowList
+ net.minecraft.world.level.validation.PathAllowList$ConfigEntry
- net.minecraft.world.level.validation.PathAllowList$EntryType
- net.minecraft.world.package-info
+ net.minecraft.world.phys.AABB
- net.minecraft.world.phys.BlockHitResult
+ net.minecraft.world.phys.EntityHitResult
- net.minecraft.world.phys.HitResult
+ net.minecraft.world.phys.HitResult$Type
- net.minecraft.world.phys.package-info
+ net.minecraft.world.phys.shapes.ArrayVoxelShape
- net.minecraft.world.phys.shapes.ArrayVoxelShape$1
+ net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
- net.minecraft.world.phys.shapes.BooleanOp
+ net.minecraft.world.phys.shapes.CollisionContext
- net.minecraft.world.phys.shapes.CubePointRange
+ net.minecraft.world.phys.shapes.CubeVoxelShape
- net.minecraft.world.phys.shapes.DiscreteCubeMerger
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- net.minecraft.world.phys.shapes.EntityCollisionContext
+ net.minecraft.world.phys.shapes.EntityCollisionContext$1
- net.minecraft.world.phys.shapes.IdenticalMerger
+ net.minecraft.world.phys.shapes.IndexMerger
- net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
+ net.minecraft.world.phys.shapes.IndirectMerger
- net.minecraft.world.phys.shapes.NonOverlappingMerger
+ net.minecraft.world.phys.shapes.OffsetDoubleList
+ net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.shapes.Shapes
+ net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
- net.minecraft.world.phys.shapes.SliceShape
+ net.minecraft.world.phys.shapes.SubShape
- net.minecraft.world.phys.shapes.VoxelShape
- net.minecraft.world.phys.Vec2
+ net.minecraft.world.phys.Vec3
- net.minecraft.world.scores.criteria.ObjectiveCriteria
+ net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
- net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.DisplaySlot
+ net.minecraft.world.scores.DisplaySlot$1
- net.minecraft.world.scores.Objective
+ net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.Score
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.Team
- net.minecraft.world.scores.Team$CollisionRule
+ net.minecraft.world.scores.Team$Visibility
- net.minecraft.world.ticks.BlackholeTickAccess
+ net.minecraft.world.ticks.BlackholeTickAccess$1
- net.minecraft.world.ticks.BlackholeTickAccess$2
+ net.minecraft.world.ticks.ContainerSingleItem
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
+ net.minecraft.WorldVersion
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.Util +1M -2M | +1P
```
```
XXX.network.chat.ClickEvent$Action +3M -3M | +2P -1P
```
```
XXX.network.chat.Component +7M
```
```
XXX.network.chat.Style +2M -10M | -1P
```
```
XXX.chat.contents.DataSource +1M | +2P
```
```
XXX.minecraft.util.ExtraCodecs$4 +5M -3M | +2P -1P
```
```
XXX.minecraft.util.StringRepresentable +7M -4M
```
```
XXX.minecraft.util.StringRepresentable$EnumCodec +1M -6M | -1P
```
```
XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix -1M | -1P
```
```
XXX.datafix.fixes.DropInvalidSignDataFix -1P
```
```
XXX.datafix.fixes.TeamDisplayNameFix +3M -5M
```
```
XXX.util.worldupdate.WorldUpgrader +1P -1P
```
```
XXX.entity.animal.Turtle -1M
```
```
XXX.entity.animal.WaterAnimal -1M
```
```
XXX.animal.frog.Frog -1M
```
```
XXX.world.item.ArmorMaterials +1P -1P
```
```
XXX.level.biome.FeatureSorter$StepFeatureData -1M
```
```
XXX.level.block.AbstractBannerBlock +1M -1M | +1P
```
```
XXX.level.block.AbstractCauldronBlock +1M -1M | +2P -1P
```
```
XXX.level.block.AbstractFurnaceBlock +1P
```
```
XXX.level.block.AbstractSkullBlock +1P
```
```
XXX.level.block.AmethystBlock +2M | +1P
```
```
XXX.level.block.AttachedStemBlock +7M -2M | +4P -2P
```
```
XXX.level.block.BambooSaplingBlock +2M -1M | +1P
```
```
XXX.level.block.BannerBlock +2M | +1P
```
```
XXX.level.block.BarrierBlock +1M | +1P
```
```
XXX.level.block.BaseCoralPlantBlock +1M | +1P
```
```
XXX.level.block.BaseCoralWallFanBlock +1M | +1P
```
```
XXX.level.block.BaseFireBlock +1M -1M | +1P
```
```
XXX.level.block.BaseRailBlock +1P
```
```
XXX.level.block.Blocks +28M -31M | +1P
```
```
XXX.level.block.BrewingStandBlock +1M | +1P
```
```
XXX.level.block.BubbleColumnBlock +1M | +1P
```
```
XXX.level.block.BuddingAmethystBlock +1M | +1P
```
```
XXX.level.block.ButtonBlock +5M -1M | +1P -1P
```
```
XXX.level.block.CactusBlock +1M | +1P
```
```
XXX.level.block.CalibratedSculkSensorBlock +1M | +1P
```
```
XXX.level.block.CandleBlock +1M | +1P
```
```
XXX.level.block.CarpetBlock +1M | +1P
```
```
XXX.level.block.CartographyTableBlock +1M | +1P
```
```
XXX.level.block.CauldronBlock +2M | +1P
```
```
XXX.level.block.CaveVinesBlock +3M -1M | +1P
```
```
XXX.level.block.CeilingHangingSignBlock +3M -1M | +1P
```
```
XXX.level.block.CherryLeavesBlock +2M | +1P
```
```
XXX.level.block.ChorusPlantBlock +3M -1M | +1P
```
```
XXX.level.block.GrowingPlantBodyBlock +1M -1M | +1P
```
```
XXX.level.block.HalfTransparentBlock +2M | +1P
```
```
XXX.level.block.HayBlock +2M | +1P
```
```
XXX.level.block.HopperBlock +1M | +1P
```
```
XXX.level.block.HorizontalDirectionalBlock +1P
```
```
XXX.level.block.IceBlock +2M | +1P
```
```
XXX.level.block.InfestedRotatedPillarBlock +3M | +1P
```
```
XXX.level.block.JigsawBlock +1M | +1P
```
```
XXX.level.block.KelpBlock +1M | +1P
```
```
XXX.level.block.LadderBlock +1M | +1P
```
```
XXX.level.block.LanternBlock +1M | +1P
```
```
XXX.level.block.LayeredCauldronBlock +5M -3M | +2P -3P
```
```
XXX.level.block.LecternBlock +1M | +1P
```
```
XXX.level.block.LightningRodBlock +1M | +1P
```
```
XXX.level.block.MagmaBlock +2M | +1P
```
```
XXX.level.block.MangrovePropaguleBlock +4M -1M | +1P -1P
```
```
XXX.level.block.PoweredBlock +2M | +1P
```
```
XXX.level.block.PressurePlateBlock$1 +1P -1P
```
```
XXX.level.block.ScaffoldingBlock +1M | +1P
```
```
XXX.level.block.SculkCatalystBlock +1M | +1P
```
```
XXX.level.block.SculkShriekerBlock +1M | +1P
```
```
XXX.level.block.SeagrassBlock +1M | +1P
```
```
XXX.level.block.SkullBlock$Type +1M | +2P
```
```
XXX.level.block.SlabBlock +1M | +1P
```
```
XXX.level.block.SlimeBlock +2M | +1P
```
```
XXX.level.block.SmithingTableBlock +1M | +1P
```
```
XXX.level.block.SnifferEggBlock +1M | +1P
```
```
XXX.level.block.SoulFireBlock +2M | +1P
```
```
XXX.level.block.SpongeBlock +1M | +1P
```
```
XXX.level.block.SpreadingSnowyDirtBlock +1P
```
```
XXX.level.block.StainedGlassPaneBlock +3M | +1P
```
```
XXX.level.block.StemBlock +7M -3M | +4P -2P
```
```
XXX.block.piston.PistonBaseBlock +3M | +1P
```
```
XXX.block.piston.PistonHeadBlock +3M -2M | +1P
```
```
XXX.block.state.BlockBehaviour +4M | +1P
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +1M
```
```
XXX.block.state.BlockBehaviour$Properties +9M -7M | +1P
```

</details>
















<details>
<summary>
net.minecraft.Util
</summary>

```diff
+ Hash$Strategy identityStrategy()
- ToIntFunction createIndexIdentityLookup(List)
+ ToIntFunction createIndexLookup(List,IntFunction)
```

</details>





































































































































































































































<details>
<summary>
net.minecraft.network.chat.ClickEvent$Action
</summary>

```diff
+ ClickEvent$Action getByName(String)
+ ClickEvent$Action lambda$static$0(ClickEvent$Action)
- DataResult filterForSerialization(ClickEvent$Action)
+ String getName()
- String getSerializedName()
- String lambda$filterForSerialization$0(ClickEvent$Action)
```

</details>
<details>
<summary>
net.minecraft.network.chat.Component
</summary>

```diff
- Component translationArg(ChunkPos)
- Component translationArg(Date)
- Component translationArg(Message)
- Component translationArg(ResourceLocation)
- Component translationArg(UUID)
- MutableComponent translatableEscape(String,Object[])
- String tryCollapseToString()
```

</details>














<details>
<summary>
net.minecraft.network.chat.Style
</summary>

```diff
+ App lambda$static$8(RecordCodecBuilder$Instance)
+ Optional lambda$static$0(Style)
+ Optional lambda$static$1(Style)
+ Optional lambda$static$2(Style)
+ Optional lambda$static$3(Style)
+ Optional lambda$static$4(Style)
+ Optional lambda$static$5(Style)
+ Optional lambda$static$6(Style)
+ Optional lambda$static$7(Style)
- Style checkEmptyAfterChange(Style,Object,Object)
- Style create(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
+ Style create(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
```

</details>



<details>
<summary>
net.minecraft.network.chat.contents.DataSource
</summary>

```diff
- void <clinit>()
```

</details>














<details>
<summary>
net.minecraft.util.ExtraCodecs$4
</summary>

```diff
- DataResult apply(DynamicOps,Object,DataResult)
- DataResult coApply(DynamicOps,Object,DataResult)
+ DataResult decode(DynamicOps,Object)
- DataResult lambda$apply$0(DataResult,Function,Pair)
+ String lambda$decode$0(Object,Exception)
- String toString()
+ void <init>(Codec)
- void <init>(Function,Function)
```

</details>
















<details>
<summary>
net.minecraft.util.StringRepresentable
</summary>

```diff
- Codec fromValues(Supplier)
+ Enum lambda$fromEnumWithMapping$2(Enum)
+ Enum lambda$fromEnumWithMapping$3(Map,String)
+ Enum lambda$fromEnumWithMapping$4(Enum[],Function,String)
- Function createNameLookup(StringRepresentable[],Function)
- String lambda$createNameLookup$2(Function,StringRepresentable)
+ String lambda$fromEnumWithMapping$1(Function,Enum)
- String lambda$fromValues$1(String)
- StringRepresentable lambda$createNameLookup$3(StringRepresentable)
- StringRepresentable lambda$createNameLookup$4(Map,String)
- StringRepresentable lambda$createNameLookup$5(StringRepresentable[],Function,String)
```

</details>
<details>
<summary>
net.minecraft.util.StringRepresentable$EnumCodec
</summary>

```diff
+ DataResult decode(DynamicOps,Object)
+ DataResult encode(Enum,DynamicOps,Object)
+ DataResult encode(Object,DynamicOps,Object)
+ Enum lambda$new$2(Enum[],int)
- int lambda$new$0(Object)
+ int lambda$new$1(Object)
+ String lambda$new$0(Object)
```

</details>













<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
</summary>

```diff
+ void <clinit>()
```

</details>
















































































<details>
<summary>
net.minecraft.util.datafix.fixes.TeamDisplayNameFix
</summary>

```diff
- Dynamic lambda$makeRule$0(Dynamic)
+ Dynamic lambda$makeRule$1(Dynamic,Dynamic)
+ Dynamic lambda$makeRule$2(Dynamic)
- Function lambda$makeRule$2(DynamicOps)
+ Function lambda$makeRule$4(DynamicOps)
- Pair lambda$makeRule$1(Pair)
+ Pair lambda$makeRule$3(Pair)
+ String lambda$makeRule$0(String)
```

</details>



















































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.animal.Turtle
</summary>

```diff
+ boolean canBreatheUnderwater()
```

</details>




<details>
<summary>
net.minecraft.world.entity.animal.WaterAnimal
</summary>

```diff
+ boolean canBreatheUnderwater()
```

</details>












<details>
<summary>
net.minecraft.world.entity.animal.frog.Frog
</summary>

```diff
+ boolean canBreatheUnderwater()
```

</details>


































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.biome.FeatureSorter$StepFeatureData
</summary>

```diff
+ Object2IntMap lambda$new$0(int)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.AbstractBannerBlock
</summary>

```diff
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractCauldronBlock
</summary>

```diff
- void <init>(BlockBehaviour$Properties,CauldronInteraction$InteractionMap)
+ void <init>(BlockBehaviour$Properties,Map)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.AmethystBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.AttachedStemBlock
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
- MapCodec codec()
- ResourceKey lambda$static$0(AttachedStemBlock)
- ResourceKey lambda$static$1(AttachedStemBlock)
- ResourceKey lambda$static$2(AttachedStemBlock)
- void <init>(ResourceKey,ResourceKey,ResourceKey,BlockBehaviour$Properties)
+ void <init>(StemGrownBlock,Supplier,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BambooSaplingBlock
</summary>

```diff
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BannerBlock
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BarrierBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseCoralPlantBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseCoralWallFanBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseFireBlock
</summary>

```diff
- BlockState playerWillDestroy(Level,BlockPos,BlockState,Player)
+ void playerWillDestroy(Level,BlockPos,BlockState,Player)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
+ BedBlock bed(DyeColor)
- Block bed(DyeColor)
- Block candle(MapColor)
- Block flowerPot(Block)
- Block leaves(SoundType)
- Block log(MapColor,MapColor,SoundType)
- Block log(MapColor,MapColor)
- Block pistonBase(boolean)
- Block register(ResourceKey,Block)
+ Block register(ResourceLocation,Block)
- Block shulkerBox(DyeColor,MapColor)
- Block stainedGlass(DyeColor)
- Block stair(Block)
- Block stoneButton()
- Block woodenButton(BlockSetType)
+ boolean lambda$shulkerBox$5(BlockState,BlockGetter,BlockPos)
- boolean lambda$static$0(BlockState,BlockGetter,BlockPos)
- boolean lambda$static$32(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$34(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$static$36(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$static$38(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$47(BlockState,BlockGetter,BlockPos)
+ boolean lambda$static$51(BlockState,BlockGetter,BlockPos)
+ ButtonBlock stoneButton()
+ ButtonBlock woodenButton(BlockSetType,FeatureFlag[])
+ CandleBlock candle(MapColor)
+ FlowerPotBlock flowerPot(Block,FeatureFlag[])
+ int lambda$litBlockEmission$0(int,BlockState)
- int lambda$litBlockEmission$1(int,BlockState)
- int lambda$static$21(BlockState)
- int lambda$static$22(BlockState)
- int lambda$static$23(BlockState)
- int lambda$static$24(BlockState)
+ int lambda$static$32(BlockState)
+ int lambda$static$34(BlockState)
- int lambda$static$36(BlockState)
- int lambda$static$38(BlockState)
+ int lambda$static$47(BlockState)
- int lambda$static$51(BlockState)
+ int lambda$static$52(BlockState)
+ int lambda$static$53(BlockState)
+ int lambda$static$54(BlockState)
+ int lambda$static$55(BlockState)
+ Item lambda$static$21()
+ Item lambda$static$22()
+ Item lambda$static$23()
+ Item lambda$static$24()
+ LeavesBlock leaves(SoundType)
+ MapColor lambda$bed$1(DyeColor,BlockState)
- MapColor lambda$bed$2(DyeColor,BlockState)
+ MapColor lambda$log$2(MapColor,MapColor,BlockState)
- MapColor lambda$log$4(MapColor,MapColor,BlockState)
+ MapColor lambda$netherStem$4(MapColor,BlockState)
- MapColor lambda$netherStem$5(MapColor,BlockState)
+ PistonBaseBlock pistonBase(boolean)
+ RotatedPillarBlock log(MapColor,MapColor,SoundType)
+ RotatedPillarBlock log(MapColor,MapColor)
+ ShulkerBoxBlock shulkerBox(DyeColor,BlockBehaviour$Properties)
+ StainedGlassBlock stainedGlass(DyeColor)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BrewingStandBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BubbleColumnBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BuddingAmethystBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ButtonBlock
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- BlockSetType lambda$static$0(ButtonBlock)
- Integer lambda$static$1(ButtonBlock)
- MapCodec codec()
+ void <init>(BlockBehaviour$Properties,BlockSetType,int,boolean)
- void <init>(BlockSetType,int,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CactusBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CalibratedSculkSensorBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CandleBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CarpetBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CartographyTableBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CauldronBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CaveVinesBlock
</summary>

```diff
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CeilingHangingSignBlock
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- MapCodec codec()
+ void <init>(BlockBehaviour$Properties,WoodType)
- void <init>(WoodType,BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.CherryLeavesBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>




<details>
<summary>
net.minecraft.world.level.block.ChorusPlantBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockGetter,BlockPos)
- BlockState getStateWithConnections(BlockGetter,BlockPos,BlockState)
- MapCodec codec()
- void <clinit>()
```

</details>


<details>
<summary>
net.minecraft.world.level.block.GrowingPlantBodyBlock
</summary>

```diff
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HalfTransparentBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HayBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
- MapCodec codec()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.IceBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.InfestedRotatedPillarBlock
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.JigsawBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.KelpBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LadderBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LanternBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LayeredCauldronBlock
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- Biome$Precipitation lambda$static$0(LayeredCauldronBlock)
+ boolean lambda$static$0(Biome$Precipitation)
+ boolean lambda$static$1(Biome$Precipitation)
- CauldronInteraction$InteractionMap lambda$static$1(LayeredCauldronBlock)
- MapCodec codec()
- void <init>(Biome$Precipitation,CauldronInteraction$InteractionMap,BlockBehaviour$Properties)
+ void <init>(BlockBehaviour$Properties,Predicate,Map)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
- MapCodec codec()
```

</details>


<details>
<summary>
net.minecraft.world.level.block.LightningRodBlock
</summary>

```diff
- MapCodec codec()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.MagmaBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.MangrovePropaguleBlock
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
- MapCodec codec()
- TreeGrower lambda$static$0(MangrovePropaguleBlock)
+ void <init>(BlockBehaviour$Properties)
- void <init>(TreeGrower,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PoweredBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>


<details>
<summary>
net.minecraft.world.level.block.ScaffoldingBlock
</summary>

```diff
- MapCodec codec()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.SculkCatalystBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkShriekerBlock
</summary>

```diff
- MapCodec codec()
```

</details>


<details>
<summary>
net.minecraft.world.level.block.SeagrassBlock
</summary>

```diff
- MapCodec codec()
```

</details>


<details>
<summary>
net.minecraft.world.level.block.SkullBlock$Type
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SlabBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SlimeBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SmithingTableBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SnifferEggBlock
</summary>

```diff
- MapCodec codec()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.SoulFireBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.SpongeBlock
</summary>

```diff
- MapCodec codec()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.StainedGlassPaneBlock
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- MapCodec codec()
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.StemBlock
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
- MapCodec codec()
- ResourceKey lambda$static$0(StemBlock)
- ResourceKey lambda$static$1(StemBlock)
- ResourceKey lambda$static$2(StemBlock)
+ StemGrownBlock getFruit()
- void <init>(ResourceKey,ResourceKey,ResourceKey,BlockBehaviour$Properties)
+ void <init>(StemGrownBlock,Supplier,BlockBehaviour$Properties)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.piston.PistonBaseBlock
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
- Boolean lambda$static$0(PistonBaseBlock)
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.PistonHeadBlock
</summary>

```diff
- BlockState playerWillDestroy(Level,BlockPos,BlockState,Player)
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
- MapCodec codec()
+ void playerWillDestroy(Level,BlockPos,BlockState,Player)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
- App lambda$simpleCodec$0(Function,RecordCodecBuilder$Instance)
- BlockBehaviour$Properties properties()
- MapCodec simpleCodec(Function)
- RecordCodecBuilder propertiesCodec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
- boolean is(ResourceKey)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$Properties
</summary>

```diff
- BlockBehaviour$Properties lambda$static$0()
+ boolean lambda$new$2(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$new$3(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$new$3(BlockState,BlockGetter,BlockPos)
- boolean lambda$new$7(BlockState,BlockGetter,BlockPos)
+ int lambda$new$1(BlockState)
- int lambda$new$2(BlockState)
+ MapColor lambda$mapColor$7(DyeColor,BlockState)
- MapColor lambda$mapColor$8(DyeColor,BlockState)
+ MapColor lambda$mapColor$8(MapColor,BlockState)
- MapColor lambda$mapColor$9(MapColor,BlockState)
+ MapColor lambda$new$0(BlockState)
- MapColor lambda$new$1(BlockState)
- Vec3 lambda$offsetType$11(BlockState,BlockGetter,BlockPos)
+ Vec3 lambda$offsetType$9(BlockState,BlockGetter,BlockPos)
- void <clinit>()
```

</details>











<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- com.mojang.realmsclient.dto.RealmsNotification$InfoPopup
- net.minecraft.advancements.Advancement
+ net.minecraft.advancements.Advancement$Builder
- net.minecraft.advancements.AdvancementHolder
+ net.minecraft.advancements.AdvancementNode
- net.minecraft.advancements.AdvancementProgress
+ net.minecraft.advancements.AdvancementRequirements
- net.minecraft.advancements.AdvancementRequirements$Strategy
+ net.minecraft.advancements.AdvancementRewards
- net.minecraft.advancements.AdvancementRewards$Builder
+ net.minecraft.advancements.AdvancementTree
- net.minecraft.advancements.AdvancementTree$Listener
- net.minecraft.advancements.critereon.AbstractCriterionTriggerInstance
+ net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
- net.minecraft.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.BlockPredicate
- net.minecraft.advancements.critereon.BlockPredicate$Builder
+ net.minecraft.advancements.critereon.BredAnimalsTrigger
- net.minecraft.advancements.critereon.BredAnimalsTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.BrewedPotionTrigger
- net.minecraft.advancements.critereon.BrewedPotionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ChangeDimensionTrigger
- net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ChanneledLightningTrigger
- net.minecraft.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ConstructBeaconTrigger
- net.minecraft.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ConsumeItemTrigger
- net.minecraft.advancements.critereon.ConsumeItemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ContextAwarePredicate
- net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
+ net.minecraft.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
- net.minecraft.advancements.critereon.DamagePredicate
+ net.minecraft.advancements.critereon.DamagePredicate$Builder
- net.minecraft.advancements.critereon.DamageSourcePredicate
+ net.minecraft.advancements.critereon.DamageSourcePredicate$Builder
- net.minecraft.advancements.critereon.DeserializationContext
+ net.minecraft.advancements.critereon.DistancePredicate
- net.minecraft.advancements.critereon.DistanceTrigger
+ net.minecraft.advancements.critereon.DistanceTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EffectsChangedTrigger
+ net.minecraft.advancements.critereon.EffectsChangedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EnchantedItemTrigger
+ net.minecraft.advancements.critereon.EnchantedItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EnchantmentPredicate
+ net.minecraft.advancements.critereon.EnterBlockTrigger
- net.minecraft.advancements.critereon.EnterBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EntityEquipmentPredicate
- net.minecraft.advancements.critereon.EntityEquipmentPredicate$Builder
+ net.minecraft.advancements.critereon.EntityFlagsPredicate
- net.minecraft.advancements.critereon.EntityFlagsPredicate$Builder
+ net.minecraft.advancements.critereon.EntityHurtPlayerTrigger
- net.minecraft.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EntityPredicate
- net.minecraft.advancements.critereon.EntityPredicate$Builder
+ net.minecraft.advancements.critereon.EntitySubPredicate
- net.minecraft.advancements.critereon.EntitySubPredicate$Type
+ net.minecraft.advancements.critereon.EntitySubPredicate$Types
- net.minecraft.advancements.critereon.EntitySubPredicate$Types$1
+ net.minecraft.advancements.critereon.EntityTypePredicate
- net.minecraft.advancements.critereon.EntityVariantPredicate
+ net.minecraft.advancements.critereon.EntityVariantPredicate$SubPredicate
- net.minecraft.advancements.critereon.FilledBucketTrigger
+ net.minecraft.advancements.critereon.FilledBucketTrigger$TriggerInstance
- net.minecraft.advancements.critereon.FishingHookPredicate
+ net.minecraft.advancements.critereon.FishingRodHookedTrigger
- net.minecraft.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.FluidPredicate
- net.minecraft.advancements.critereon.FluidPredicate$Builder
+ net.minecraft.advancements.critereon.ImpossibleTrigger
- net.minecraft.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.InventoryChangeTrigger
- net.minecraft.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ItemDurabilityTrigger
- net.minecraft.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ItemPredicate
- net.minecraft.advancements.critereon.ItemPredicate$Builder
+ net.minecraft.advancements.critereon.ItemUsedOnLocationTrigger
- net.minecraft.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.KilledByCrossbowTrigger
- net.minecraft.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.KilledTrigger
- net.minecraft.advancements.critereon.KilledTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.LevitationTrigger
- net.minecraft.advancements.critereon.LevitationTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.LightningBoltPredicate
- net.minecraft.advancements.critereon.LightningStrikeTrigger
+ net.minecraft.advancements.critereon.LightningStrikeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.LightPredicate
- net.minecraft.advancements.critereon.LightPredicate$Builder
- net.minecraft.advancements.critereon.LocationPredicate
+ net.minecraft.advancements.critereon.LocationPredicate$Builder
- net.minecraft.advancements.critereon.LocationPredicate$PositionPredicate
+ net.minecraft.advancements.critereon.LootTableTrigger
- net.minecraft.advancements.critereon.LootTableTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.MinMaxBounds
- net.minecraft.advancements.critereon.MinMaxBounds$BoundsFactory
+ net.minecraft.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
- net.minecraft.advancements.critereon.MinMaxBounds$Doubles
+ net.minecraft.advancements.critereon.MinMaxBounds$Ints
- net.minecraft.advancements.critereon.MobEffectsPredicate
+ net.minecraft.advancements.critereon.MobEffectsPredicate$Builder
- net.minecraft.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
+ net.minecraft.advancements.critereon.NbtPredicate
+ net.minecraft.advancements.critereon.package-info
- net.minecraft.advancements.critereon.PickedUpItemTrigger
+ net.minecraft.advancements.critereon.PickedUpItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerHurtEntityTrigger
+ net.minecraft.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerInteractTrigger
+ net.minecraft.advancements.critereon.PlayerInteractTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementPredicate
- net.minecraft.advancements.critereon.PlayerPredicate$Builder
+ net.minecraft.advancements.critereon.PlayerPredicate$StatMatcher
- net.minecraft.advancements.critereon.PlayerTrigger
+ net.minecraft.advancements.critereon.PlayerTrigger$TriggerInstance
- net.minecraft.advancements.critereon.RecipeCraftedTrigger
+ net.minecraft.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.RecipeUnlockedTrigger
+ net.minecraft.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ShotCrossbowTrigger
+ net.minecraft.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
- net.minecraft.advancements.critereon.SimpleCriterionTrigger
+ net.minecraft.advancements.critereon.SimpleCriterionTrigger$SimpleInstance
- net.minecraft.advancements.critereon.SlideDownBlockTrigger
+ net.minecraft.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.SlimePredicate
+ net.minecraft.advancements.critereon.StartRidingTrigger
- net.minecraft.advancements.critereon.StartRidingTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.StatePropertiesPredicate
- net.minecraft.advancements.critereon.StatePropertiesPredicate$Builder
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$ExactMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$RangedMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$ValueMatcher
+ net.minecraft.advancements.critereon.SummonedEntityTrigger
- net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TagPredicate
- net.minecraft.advancements.critereon.TameAnimalTrigger
+ net.minecraft.advancements.critereon.TameAnimalTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TargetBlockTrigger
+ net.minecraft.advancements.critereon.TargetBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TradeTrigger
+ net.minecraft.advancements.critereon.TradeTrigger$TriggerInstance
- net.minecraft.advancements.critereon.UsedEnderEyeTrigger
+ net.minecraft.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
- net.minecraft.advancements.critereon.UsedTotemTrigger
+ net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.UsingItemTrigger
+ net.minecraft.advancements.critereon.UsingItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.WrappedMinMaxBounds
+ net.minecraft.advancements.CriteriaTriggers
- net.minecraft.advancements.Criterion
+ net.minecraft.advancements.CriterionProgress
- net.minecraft.advancements.CriterionTrigger
+ net.minecraft.advancements.CriterionTrigger$Listener
- net.minecraft.advancements.CriterionTriggerInstance
+ net.minecraft.advancements.DisplayInfo
- net.minecraft.advancements.FrameType
- net.minecraft.advancements.package-info
+ net.minecraft.advancements.TreeNodePosition
- net.minecraft.client.animation.AnimationChannel
+ net.minecraft.client.animation.AnimationChannel$Interpolation
- net.minecraft.client.animation.AnimationChannel$Interpolations
+ net.minecraft.client.animation.AnimationChannel$Target
- net.minecraft.client.animation.AnimationChannel$Targets
+ net.minecraft.client.animation.AnimationDefinition
- net.minecraft.client.animation.AnimationDefinition$Builder
+ net.minecraft.client.animation.definitions.CamelAnimation
- net.minecraft.client.animation.definitions.FrogAnimation
+ net.minecraft.client.animation.definitions.package-info
+ net.minecraft.client.animation.definitions.SnifferAnimation
- net.minecraft.client.animation.definitions.WardenAnimation
+ net.minecraft.client.animation.Keyframe
- net.minecraft.client.animation.KeyframeAnimations
- net.minecraft.client.animation.package-info
+ net.minecraft.client.AttackIndicatorStatus
- net.minecraft.client.Camera
+ net.minecraft.client.Camera$NearPlane
- net.minecraft.client.CameraType
+ net.minecraft.client.ClientBrandRetriever
- net.minecraft.client.ClientRecipeBook
+ net.minecraft.client.ClientRecipeBook$1
- net.minecraft.client.CloudStatus
+ net.minecraft.client.color.block.BlockColor
- net.minecraft.client.color.block.BlockColors
+ net.minecraft.client.color.block.BlockTintCache
- net.minecraft.client.color.block.BlockTintCache$CacheData
+ net.minecraft.client.color.block.BlockTintCache$LatestCacheInfo
- net.minecraft.client.color.block.package-info
+ net.minecraft.client.color.item.ItemColor
- net.minecraft.client.color.item.ItemColors
+ net.minecraft.client.color.item.package-info
+ net.minecraft.client.CommandHistory
- net.minecraft.client.ComponentCollector
+ net.minecraft.client.DebugQueryHandler
- net.minecraft.client.GameNarrator
+ net.minecraft.client.GameNarrator$NarratorInitException
- net.minecraft.client.GraphicsStatus
+ net.minecraft.client.GraphicsStatus$1
- net.minecraft.client.gui.ComponentPath
+ net.minecraft.client.gui.ComponentPath$Leaf
- net.minecraft.client.gui.ComponentPath$Path
+ net.minecraft.client.gui.components.AbstractButton
- net.minecraft.client.gui.components.AbstractOptionSliderButton
+ net.minecraft.client.gui.components.AbstractScrollWidget
- net.minecraft.client.gui.components.AbstractSelectionList
+ net.minecraft.client.gui.components.AbstractSelectionList$1
- net.minecraft.client.gui.components.AbstractSelectionList$Entry
+ net.minecraft.client.gui.components.AbstractSelectionList$TrackedList
- net.minecraft.client.gui.components.AbstractSliderButton
+ net.minecraft.client.gui.components.AbstractStringWidget
- net.minecraft.client.gui.components.AbstractWidget
+ net.minecraft.client.gui.components.BossHealthOverlay
- net.minecraft.client.gui.components.BossHealthOverlay$1
+ net.minecraft.client.gui.components.Button
- net.minecraft.client.gui.components.Button$Builder
+ net.minecraft.client.gui.components.Button$CreateNarration
- net.minecraft.client.gui.components.Button$OnPress
+ net.minecraft.client.gui.components.ChatComponent
- net.minecraft.client.gui.components.ChatComponent$DelayedMessageDeletion
+ net.minecraft.client.gui.components.Checkbox
- net.minecraft.client.gui.components.CommandSuggestions
+ net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
- net.minecraft.client.gui.components.CommonButtons
+ net.minecraft.client.gui.components.ComponentRenderUtils
- net.minecraft.client.gui.components.ContainerObjectSelectionList
+ net.minecraft.client.gui.components.ContainerObjectSelectionList$1
- net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
+ net.minecraft.client.gui.components.CycleButton
- net.minecraft.client.gui.components.CycleButton$Builder
+ net.minecraft.client.gui.components.CycleButton$OnValueChange
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
+ net.minecraft.client.gui.components.DebugScreenOverlay
- net.minecraft.client.gui.components.DebugScreenOverlay$1
+ net.minecraft.client.gui.components.DebugScreenOverlay$AllocationRateCalculator
- net.minecraft.client.gui.components.EditBox
+ net.minecraft.client.gui.components.FittingMultiLineTextWidget
- net.minecraft.client.gui.components.FocusableTextWidget
+ net.minecraft.client.gui.components.ImageButton
- net.minecraft.client.gui.components.ImageWidget
+ net.minecraft.client.gui.components.ImageWidget$Sprite
- net.minecraft.client.gui.components.ImageWidget$Texture
+ net.minecraft.client.gui.components.LerpingBossEvent
- net.minecraft.client.gui.components.LoadingDotsWidget
+ net.minecraft.client.gui.components.LockIconButton
- net.minecraft.client.gui.components.LockIconButton$Icon
+ net.minecraft.client.gui.components.LogoRenderer
- net.minecraft.client.gui.components.MultiLineEditBox
+ net.minecraft.client.gui.components.MultiLineLabel
- net.minecraft.client.gui.components.MultiLineLabel$1
+ net.minecraft.client.gui.components.MultiLineLabel$2
- net.minecraft.client.gui.components.MultiLineLabel$TextWithWidth
+ net.minecraft.client.gui.components.MultilineTextField
- net.minecraft.client.gui.components.MultilineTextField$1
+ net.minecraft.client.gui.components.MultilineTextField$StringView
+ net.minecraft.client.gui.components.MultiLineTextWidget
- net.minecraft.client.gui.components.MultiLineTextWidget$CacheKey
- net.minecraft.client.gui.components.ObjectSelectionList
+ net.minecraft.client.gui.components.ObjectSelectionList$Entry
- net.minecraft.client.gui.components.OptionsList
+ net.minecraft.client.gui.components.OptionsList$Entry
- net.minecraft.client.gui.components.PlainTextButton
+ net.minecraft.client.gui.components.PlayerFaceRenderer
- net.minecraft.client.gui.components.PlayerSkinWidget
+ net.minecraft.client.gui.components.PlayerSkinWidget$Model
- net.minecraft.client.gui.components.PlayerTabOverlay
+ net.minecraft.client.gui.components.PlayerTabOverlay$HealthState
- net.minecraft.client.gui.components.PopupScreen
- net.minecraft.client.gui.components.PopupScreen$ButtonOption
+ net.minecraft.client.gui.Font
- net.minecraft.client.gui.Font$DisplayMode
+ net.minecraft.client.gui.Font$StringRenderOutput
- net.minecraft.client.gui.Gui
+ net.minecraft.client.gui.Gui$HeartType
- net.minecraft.client.gui.GuiGraphics
+ net.minecraft.client.gui.GuiGraphics$ScissorStack
- net.minecraft.client.gui.GuiSpriteManager
+ net.minecraft.client.gui.MapRenderer
- net.minecraft.client.gui.MapRenderer$MapInstance
+ net.minecraft.client.gui.screens.PopupScreen
- net.minecraft.client.gui.screens.UnsupportedGraphicsWarningScreen
- net.minecraft.client.GuiMessage
+ net.minecraft.client.GuiMessage$Line
- net.minecraft.client.GuiMessageTag
+ net.minecraft.client.GuiMessageTag$Icon
- net.minecraft.client.HotbarManager
+ net.minecraft.client.InputType
+ net.minecraft.client.KeyboardHandler
- net.minecraft.client.KeyboardHandler$1
- net.minecraft.client.KeyMapping
+ net.minecraft.client.Minecraft
- net.minecraft.client.Minecraft$1
+ net.minecraft.client.Minecraft$ChatStatus
- net.minecraft.client.Minecraft$ChatStatus$1
+ net.minecraft.client.Minecraft$ChatStatus$2
- net.minecraft.client.Minecraft$ChatStatus$3
+ net.minecraft.client.Minecraft$ChatStatus$4
- net.minecraft.client.Minecraft$GameLoadCookie
+ net.minecraft.client.MouseHandler
- net.minecraft.client.multiplayer.chat.ChatListener
+ net.minecraft.client.multiplayer.chat.ChatListener$Message
- net.minecraft.client.multiplayer.chat.ChatLog
+ net.minecraft.client.multiplayer.chat.ChatTrustLevel
- net.minecraft.client.multiplayer.chat.ChatTrustLevel$1
+ net.minecraft.client.multiplayer.chat.LoggedChatEvent
- net.minecraft.client.multiplayer.chat.LoggedChatEvent$Type
+ net.minecraft.client.multiplayer.chat.LoggedChatMessage
- net.minecraft.client.multiplayer.chat.LoggedChatMessage$Player
+ net.minecraft.client.multiplayer.chat.LoggedChatMessage$System
- net.minecraft.client.multiplayer.chat.package-info
+ net.minecraft.client.multiplayer.chat.report.AbuseReportSender
- net.minecraft.client.multiplayer.chat.report.AbuseReportSender$1
+ net.minecraft.client.multiplayer.chat.report.AbuseReportSender$SendException
- net.minecraft.client.multiplayer.chat.report.AbuseReportSender$Services
+ net.minecraft.client.multiplayer.chat.report.BanReason
- net.minecraft.client.multiplayer.chat.report.ChatReport
+ net.minecraft.client.multiplayer.chat.report.ChatReport$Builder
- net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder
+ net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder$Collector
- net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder$Handler
+ net.minecraft.client.multiplayer.chat.report.NameReport
- net.minecraft.client.multiplayer.chat.report.NameReport$Builder
- net.minecraft.client.multiplayer.chat.report.package-info
+ net.minecraft.client.multiplayer.chat.report.Report
- net.minecraft.client.multiplayer.chat.report.Report$Builder
+ net.minecraft.client.multiplayer.chat.report.Report$CannotBuildReason
- net.minecraft.client.multiplayer.chat.report.Report$Result
+ net.minecraft.client.multiplayer.chat.report.ReportEnvironment
- net.minecraft.client.multiplayer.chat.report.ReportEnvironment$Server
+ net.minecraft.client.multiplayer.chat.report.ReportEnvironment$Server$Realm
- net.minecraft.client.multiplayer.chat.report.ReportEnvironment$Server$ThirdParty
+ net.minecraft.client.multiplayer.chat.report.ReportingContext
+ net.minecraft.client.multiplayer.chat.report.ReportReason
- net.minecraft.client.multiplayer.chat.report.ReportType
- net.minecraft.client.multiplayer.chat.report.SkinReport
+ net.minecraft.client.multiplayer.chat.report.SkinReport$Builder
- net.minecraft.client.multiplayer.LevelLoadStatusManager$1
- net.minecraft.client.multiplayer.MultiPlayerGameMode
+ net.minecraft.client.multiplayer.package-info
+ net.minecraft.client.multiplayer.PingDebugMonitor
- net.minecraft.client.multiplayer.PlayerInfo
- net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler
+ net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
+ net.minecraft.client.multiplayer.prediction.package-info
- net.minecraft.client.multiplayer.prediction.PredictiveAction
+ net.minecraft.client.multiplayer.ProfileKeyPairManager
- net.minecraft.client.multiplayer.ProfileKeyPairManager$1
- net.minecraft.client.multiplayer.resolver.AddressCheck
+ net.minecraft.client.multiplayer.resolver.AddressCheck$1
- net.minecraft.client.multiplayer.resolver.package-info
- net.minecraft.client.multiplayer.resolver.ResolvedServerAddress
+ net.minecraft.client.multiplayer.resolver.ResolvedServerAddress$1
- net.minecraft.client.multiplayer.resolver.ServerAddress
+ net.minecraft.client.multiplayer.resolver.ServerAddressResolver
- net.minecraft.client.multiplayer.resolver.ServerNameResolver
+ net.minecraft.client.multiplayer.resolver.ServerRedirectHandler
+ net.minecraft.client.multiplayer.ServerData
- net.minecraft.client.multiplayer.ServerData$ServerPackStatus
+ net.minecraft.client.multiplayer.ServerData$Type
- net.minecraft.client.multiplayer.ServerList
+ net.minecraft.client.multiplayer.ServerStatusPinger
- net.minecraft.client.multiplayer.ServerStatusPinger$1
+ net.minecraft.client.multiplayer.ServerStatusPinger$2
- net.minecraft.client.NarratorStatus
+ net.minecraft.client.OptionInstance
- net.minecraft.client.OptionInstance$AltEnum
+ net.minecraft.client.OptionInstance$CaptionBasedToString
- net.minecraft.client.OptionInstance$ClampingLazyMaxIntRange
+ net.minecraft.client.OptionInstance$CycleableValueSet
- net.minecraft.client.OptionInstance$CycleableValueSet$ValueSetter
+ net.minecraft.client.OptionInstance$Enum
- net.minecraft.client.OptionInstance$IntRange
+ net.minecraft.client.OptionInstance$IntRangeBase
- net.minecraft.client.OptionInstance$IntRangeBase$1
+ net.minecraft.client.OptionInstance$LazyEnum
- net.minecraft.client.OptionInstance$OptionInstanceSliderButton
+ net.minecraft.client.OptionInstance$SliderableOrCyclableValueSet
- net.minecraft.client.OptionInstance$SliderableValueSet
+ net.minecraft.client.OptionInstance$TooltipSupplier
- net.minecraft.client.OptionInstance$UnitDouble
+ net.minecraft.client.OptionInstance$UnitDouble$1
- net.minecraft.client.OptionInstance$ValueSet
+ net.minecraft.client.Options
- net.minecraft.client.Options$1
+ net.minecraft.client.Options$2
- net.minecraft.client.Options$3
+ net.minecraft.client.Options$4
- net.minecraft.client.Options$FieldAccess
+ net.minecraft.client.package-info
- net.minecraft.client.particle.AshParticle
+ net.minecraft.client.particle.AshParticle$Provider
- net.minecraft.client.particle.AttackSweepParticle
+ net.minecraft.client.particle.AttackSweepParticle$Provider
- net.minecraft.client.particle.BaseAshSmokeParticle
+ net.minecraft.client.particle.BlockMarker
- net.minecraft.client.particle.BlockMarker$Provider
+ net.minecraft.client.particle.BreakingItemParticle
- net.minecraft.client.particle.BreakingItemParticle$Provider
+ net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
- net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
+ net.minecraft.client.particle.BubbleColumnUpParticle
- net.minecraft.client.particle.BubbleColumnUpParticle$Provider
+ net.minecraft.client.particle.BubbleParticle
- net.minecraft.client.particle.BubbleParticle$Provider
+ net.minecraft.client.particle.BubblePopParticle
- net.minecraft.client.particle.BubblePopParticle$Provider
+ net.minecraft.client.particle.CampfireSmokeParticle
- net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
+ net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
- net.minecraft.client.particle.CherryParticle
+ net.minecraft.client.particle.CritParticle
- net.minecraft.client.particle.CritParticle$DamageIndicatorProvider
+ net.minecraft.client.particle.CritParticle$MagicProvider
- net.minecraft.client.particle.CritParticle$Provider
+ net.minecraft.client.particle.DragonBreathParticle
- net.minecraft.client.particle.DragonBreathParticle$Provider
+ net.minecraft.client.particle.DripParticle
- net.minecraft.client.particle.DripParticle$CoolingDripHangParticle
+ net.minecraft.client.particle.DripParticle$DripHangParticle
- net.minecraft.client.particle.DripParticle$DripLandParticle
+ net.minecraft.client.particle.DripParticle$DripstoneFallAndLandParticle
- net.minecraft.client.particle.DripParticle$FallAndLandParticle
+ net.minecraft.client.particle.DripParticle$FallingParticle
- net.minecraft.client.particle.DripParticle$HoneyFallAndLandParticle
+ net.minecraft.client.particle.DustColorTransitionParticle
- net.minecraft.client.particle.DustColorTransitionParticle$Provider
+ net.minecraft.client.particle.DustParticle
- net.minecraft.client.particle.DustParticle$Provider
+ net.minecraft.client.particle.DustParticleBase
- net.minecraft.client.particle.EnchantmentTableParticle
+ net.minecraft.client.particle.EnchantmentTableParticle$NautilusProvider
- net.minecraft.client.particle.EnchantmentTableParticle$Provider
+ net.minecraft.client.particle.EndRodParticle
- net.minecraft.client.particle.EndRodParticle$Provider
+ net.minecraft.client.particle.ExplodeParticle
- net.minecraft.client.particle.ExplodeParticle$Provider
+ net.minecraft.client.particle.FallingDustParticle
- net.minecraft.client.particle.FallingDustParticle$Provider
+ net.minecraft.client.particle.FireworkParticles
- net.minecraft.client.particle.FireworkParticles$1
+ net.minecraft.client.particle.FireworkParticles$FlashProvider
- net.minecraft.client.particle.FireworkParticles$OverlayParticle
+ net.minecraft.client.particle.FireworkParticles$SparkParticle
- net.minecraft.client.particle.FireworkParticles$SparkProvider
+ net.minecraft.client.particle.FireworkParticles$Starter
- net.minecraft.client.particle.FlameParticle
+ net.minecraft.client.particle.FlameParticle$Provider
- net.minecraft.client.particle.FlameParticle$SmallFlameProvider
+ net.minecraft.client.particle.GlowParticle
- net.minecraft.client.particle.GlowParticle$ElectricSparkProvider
+ net.minecraft.client.particle.GlowParticle$GlowSquidProvider
- net.minecraft.client.particle.GlowParticle$ScrapeProvider
+ net.minecraft.client.particle.GlowParticle$WaxOffProvider
- net.minecraft.client.particle.GlowParticle$WaxOnProvider
+ net.minecraft.client.particle.HeartParticle
- net.minecraft.client.particle.HeartParticle$AngryVillagerProvider
+ net.minecraft.client.particle.HeartParticle$Provider
- net.minecraft.client.particle.HugeExplosionParticle
+ net.minecraft.client.particle.HugeExplosionParticle$Provider
- net.minecraft.client.particle.HugeExplosionSeedParticle
+ net.minecraft.client.particle.HugeExplosionSeedParticle$Provider
- net.minecraft.client.particle.ItemPickupParticle
+ net.minecraft.client.particle.LargeSmokeParticle
- net.minecraft.client.particle.LargeSmokeParticle$Provider
+ net.minecraft.client.particle.LavaParticle
- net.minecraft.client.particle.LavaParticle$Provider
+ net.minecraft.client.particle.MobAppearanceParticle
- net.minecraft.client.particle.MobAppearanceParticle$Provider
+ net.minecraft.client.particle.NoRenderParticle
- net.minecraft.client.particle.NoteParticle
+ net.minecraft.client.particle.NoteParticle$Provider
- net.minecraft.client.particle.package-info
- net.minecraft.client.particle.Particle
+ net.minecraft.client.particle.ParticleDescription
- net.minecraft.client.particle.ParticleEngine
+ net.minecraft.client.particle.ParticleEngine$1ParticleDefinition
- net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
+ net.minecraft.client.particle.ParticleEngine$SpriteParticleRegistration
- net.minecraft.client.particle.ParticleProvider
+ net.minecraft.client.particle.ParticleProvider$Sprite
- net.minecraft.client.particle.ParticleRenderType
+ net.minecraft.client.particle.ParticleRenderType$1
- net.minecraft.client.particle.ParticleRenderType$2
+ net.minecraft.client.particle.ParticleRenderType$3
- net.minecraft.client.particle.ParticleRenderType$4
+ net.minecraft.client.particle.ParticleRenderType$5
- net.minecraft.client.particle.ParticleRenderType$6
+ net.minecraft.client.particle.PlayerCloudParticle
- net.minecraft.client.particle.PlayerCloudParticle$Provider
+ net.minecraft.client.particle.PlayerCloudParticle$SneezeProvider
- net.minecraft.client.particle.PortalParticle
+ net.minecraft.client.particle.PortalParticle$Provider
- net.minecraft.client.particle.ReversePortalParticle
+ net.minecraft.client.particle.ReversePortalParticle$ReversePortalProvider
- net.minecraft.client.particle.RisingParticle
+ net.minecraft.client.particle.SculkChargeParticle
- net.minecraft.client.particle.SculkChargeParticle$Provider
+ net.minecraft.client.particle.SculkChargePopParticle
- net.minecraft.client.particle.SculkChargePopParticle$Provider
+ net.minecraft.client.particle.ShriekParticle
- net.minecraft.client.particle.ShriekParticle$Provider
+ net.minecraft.client.particle.SimpleAnimatedParticle
- net.minecraft.client.particle.SingleQuadParticle
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
+ net.minecraft.client.ParticleStatus
- net.minecraft.client.PeriodicNotificationManager
+ net.minecraft.client.PeriodicNotificationManager$Notification
- net.minecraft.client.PeriodicNotificationManager$NotificationTask
+ net.minecraft.client.player.AbstractClientPlayer
- net.minecraft.client.player.Input
- net.minecraft.client.player.inventory.Hotbar
+ net.minecraft.client.player.inventory.package-info
+ net.minecraft.client.player.KeyboardInput
- net.minecraft.client.player.LocalPlayer
- net.minecraft.client.player.package-info
+ net.minecraft.client.player.RemotePlayer
+ net.minecraft.client.PrioritizeChunkUpdates
+ net.minecraft.client.profiling.ClientMetricsSamplersProvider
- net.minecraft.client.profiling.package-info
+ net.minecraft.client.quickplay.package-info
+ net.minecraft.client.quickplay.QuickPlay
- net.minecraft.client.quickplay.QuickPlayLog
+ net.minecraft.client.quickplay.QuickPlayLog$1
- net.minecraft.client.quickplay.QuickPlayLog$QuickPlayEntry
+ net.minecraft.client.quickplay.QuickPlayLog$QuickPlayWorld
- net.minecraft.client.quickplay.QuickPlayLog$Type
- net.minecraft.client.Realms32BitWarningStatus
+ net.minecraft.client.RecipeBookCategories
- net.minecraft.client.RecipeBookCategories$1
- net.minecraft.client.renderer.BiomeColors
- net.minecraft.client.renderer.block.BlockModelShaper
+ net.minecraft.client.renderer.block.BlockRenderDispatcher
- net.minecraft.client.renderer.block.BlockRenderDispatcher$1
+ net.minecraft.client.renderer.block.LiquidBlockRenderer
- net.minecraft.client.renderer.block.LiquidBlockRenderer$1
- net.minecraft.client.renderer.block.model.BakedQuad
+ net.minecraft.client.renderer.block.model.BlockElement
- net.minecraft.client.renderer.block.model.BlockElement$1
+ net.minecraft.client.renderer.block.model.BlockElement$Deserializer
- net.minecraft.client.renderer.block.model.BlockElementFace
+ net.minecraft.client.renderer.block.model.BlockElementFace$Deserializer
- net.minecraft.client.renderer.block.model.BlockElementRotation
+ net.minecraft.client.renderer.block.model.BlockFaceUV
- net.minecraft.client.renderer.block.model.BlockFaceUV$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModel
- net.minecraft.client.renderer.block.model.BlockModel$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModel$GuiLight
- net.minecraft.client.renderer.block.model.BlockModel$LoopException
+ net.minecraft.client.renderer.block.model.BlockModelDefinition
- net.minecraft.client.renderer.block.model.BlockModelDefinition$Context
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$Deserializer
- net.minecraft.client.renderer.block.model.BlockModelDefinition$MissingVariantException
+ net.minecraft.client.renderer.block.model.FaceBakery
- net.minecraft.client.renderer.block.model.FaceBakery$1
+ net.minecraft.client.renderer.block.model.ItemModelGenerator
- net.minecraft.client.renderer.block.model.ItemModelGenerator$1
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$Span
- net.minecraft.client.renderer.block.model.ItemModelGenerator$SpanFacing
+ net.minecraft.client.renderer.block.model.ItemOverride
- net.minecraft.client.renderer.block.model.ItemOverride$Deserializer
+ net.minecraft.client.renderer.block.model.ItemOverride$Predicate
- net.minecraft.client.renderer.block.model.ItemOverrides
+ net.minecraft.client.renderer.block.model.ItemOverrides$BakedOverride
- net.minecraft.client.renderer.block.model.ItemOverrides$PropertyMatcher
+ net.minecraft.client.renderer.block.model.ItemTransform
- net.minecraft.client.renderer.block.model.ItemTransform$Deserializer
+ net.minecraft.client.renderer.block.model.ItemTransforms
- net.minecraft.client.renderer.block.model.ItemTransforms$1
+ net.minecraft.client.renderer.block.model.ItemTransforms$Deserializer
- net.minecraft.client.renderer.block.model.multipart.AndCondition
+ net.minecraft.client.renderer.block.model.multipart.Condition
- net.minecraft.client.renderer.block.model.multipart.KeyValueCondition
+ net.minecraft.client.renderer.block.model.multipart.MultiPart
- net.minecraft.client.renderer.block.model.multipart.MultiPart$Deserializer
+ net.minecraft.client.renderer.block.model.multipart.OrCondition
- net.minecraft.client.renderer.block.model.multipart.package-info
- net.minecraft.client.renderer.block.model.multipart.Selector
+ net.minecraft.client.renderer.block.model.multipart.Selector$Deserializer
- net.minecraft.client.renderer.block.model.MultiVariant
+ net.minecraft.client.renderer.block.model.MultiVariant$Deserializer
+ net.minecraft.client.renderer.block.model.package-info
- net.minecraft.client.renderer.block.model.Variant
+ net.minecraft.client.renderer.block.model.Variant$Deserializer
+ net.minecraft.client.renderer.block.ModelBlockRenderer
- net.minecraft.client.renderer.block.ModelBlockRenderer$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
+ net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
- net.minecraft.client.renderer.block.package-info
+ net.minecraft.client.renderer.blockentity.BannerRenderer
- net.minecraft.client.renderer.blockentity.BeaconRenderer
+ net.minecraft.client.renderer.blockentity.BedRenderer
- net.minecraft.client.renderer.blockentity.BellRenderer
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
- net.minecraft.client.renderer.blockentity.BlockEntityRenderer
+ net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider
- net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider$Context
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderers
- net.minecraft.client.renderer.blockentity.BrightnessCombiner
+ net.minecraft.client.renderer.blockentity.BrushableBlockRenderer
- net.minecraft.client.renderer.blockentity.BrushableBlockRenderer$1
+ net.minecraft.client.renderer.blockentity.CampfireRenderer
- net.minecraft.client.renderer.blockentity.ChestRenderer
+ net.minecraft.client.renderer.blockentity.ConduitRenderer
- net.minecraft.client.renderer.blockentity.DecoratedPotRenderer
+ net.minecraft.client.renderer.blockentity.EnchantTableRenderer
- net.minecraft.client.renderer.blockentity.HangingSignRenderer
+ net.minecraft.client.renderer.blockentity.HangingSignRenderer$HangingSignModel
- net.minecraft.client.renderer.blockentity.LecternRenderer
+ net.minecraft.client.renderer.blockentity.package-info
+ net.minecraft.client.renderer.blockentity.PistonHeadRenderer
- net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer
+ net.minecraft.client.renderer.blockentity.SignRenderer
- net.minecraft.client.renderer.blockentity.SignRenderer$SignModel
+ net.minecraft.client.renderer.blockentity.SkullBlockRenderer
- net.minecraft.client.renderer.blockentity.SpawnerRenderer
+ net.minecraft.client.renderer.blockentity.StructureBlockRenderer
- net.minecraft.client.renderer.blockentity.StructureBlockRenderer$1
+ net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
- net.minecraft.client.renderer.blockentity.TheEndPortalRenderer
+ net.minecraft.client.renderer.BlockEntityWithoutLevelRenderer
- net.minecraft.client.renderer.chunk.package-info
- net.minecraft.client.renderer.chunk.RenderChunk
+ net.minecraft.client.renderer.chunk.RenderChunkRegion
- net.minecraft.client.renderer.chunk.RenderRegionCache
+ net.minecraft.client.renderer.chunk.RenderRegionCache$ChunkInfo
- net.minecraft.client.renderer.chunk.SectionRenderDispatcher
+ net.minecraft.client.renderer.chunk.SectionRenderDispatcher$CompiledSection
- net.minecraft.client.renderer.chunk.SectionRenderDispatcher$CompiledSection$1
+ net.minecraft.client.renderer.chunk.SectionRenderDispatcher$RenderSection
- net.minecraft.client.renderer.chunk.SectionRenderDispatcher$RenderSection$CompileTask
+ net.minecraft.client.renderer.chunk.SectionRenderDispatcher$RenderSection$RebuildTask
- net.minecraft.client.renderer.chunk.SectionRenderDispatcher$RenderSection$RebuildTask$CompileResults
+ net.minecraft.client.renderer.chunk.SectionRenderDispatcher$RenderSection$ResortTransparencyTask
- net.minecraft.client.renderer.chunk.SectionRenderDispatcher$SectionTaskResult
+ net.minecraft.client.renderer.chunk.VisGraph
- net.minecraft.client.renderer.chunk.VisGraph$1
+ net.minecraft.client.renderer.chunk.VisibilitySet
- net.minecraft.client.renderer.CubeMap
+ net.minecraft.client.renderer.culling.Frustum
- net.minecraft.client.renderer.culling.package-info
+ net.minecraft.client.renderer.debug.BeeDebugRenderer
- net.minecraft.client.renderer.debug.BeeDebugRenderer$HiveDebugInfo
+ net.minecraft.client.renderer.debug.BrainDebugRenderer
- net.minecraft.client.renderer.debug.BrainDebugRenderer$PoiInfo
+ net.minecraft.client.renderer.debug.ChunkBorderRenderer
- net.minecraft.client.renderer.debug.ChunkDebugRenderer
+ net.minecraft.client.renderer.debug.ChunkDebugRenderer$ChunkData
- net.minecraft.client.renderer.debug.CollisionBoxRenderer
+ net.minecraft.client.renderer.debug.DebugRenderer
- net.minecraft.client.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ net.minecraft.client.renderer.debug.GameEventListenerRenderer
- net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
+ net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedListener
- net.minecraft.client.renderer.debug.GameTestDebugRenderer
+ net.minecraft.client.renderer.debug.GameTestDebugRenderer$Marker
- net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer
+ net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer$EntityGoalInfo
- net.minecraft.client.renderer.debug.HeightMapRenderer
+ net.minecraft.client.renderer.debug.HeightMapRenderer$1
- net.minecraft.client.renderer.debug.LightDebugRenderer
+ net.minecraft.client.renderer.debug.LightSectionDebugRenderer
- net.minecraft.client.renderer.debug.LightSectionDebugRenderer$1
+ net.minecraft.client.renderer.debug.LightSectionDebugRenderer$SectionData
- net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
+ net.minecraft.client.renderer.debug.package-info
+ net.minecraft.client.renderer.debug.PathfindingRenderer
- net.minecraft.client.renderer.debug.RaidDebugRenderer
+ net.minecraft.client.renderer.debug.SolidFaceRenderer
- net.minecraft.client.renderer.debug.StructureRenderer
+ net.minecraft.client.renderer.debug.SupportBlockRenderer
- net.minecraft.client.renderer.debug.VillageSectionsDebugRenderer
+ net.minecraft.client.renderer.debug.WaterDebugRenderer
- net.minecraft.client.renderer.debug.WorldGenAttemptRenderer
+ net.minecraft.client.renderer.DimensionSpecialEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$EndEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$NetherEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$OverworldEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$SkyType
- net.minecraft.client.renderer.EffectInstance
- net.minecraft.client.renderer.entity.AbstractHorseRenderer
+ net.minecraft.client.renderer.entity.AbstractZombieRenderer
- net.minecraft.client.renderer.entity.AllayRenderer
+ net.minecraft.client.renderer.entity.ArmorStandRenderer
- net.minecraft.client.renderer.entity.ArrowRenderer
+ net.minecraft.client.renderer.entity.AxolotlRenderer
- net.minecraft.client.renderer.entity.BatRenderer
+ net.minecraft.client.renderer.entity.BeeRenderer
- net.minecraft.client.renderer.entity.BlazeRenderer
+ net.minecraft.client.renderer.entity.BoatRenderer
- net.minecraft.client.renderer.entity.CamelRenderer
+ net.minecraft.client.renderer.entity.CatRenderer
- net.minecraft.client.renderer.entity.CaveSpiderRenderer
+ net.minecraft.client.renderer.entity.ChestedHorseRenderer
- net.minecraft.client.renderer.entity.ChickenRenderer
+ net.minecraft.client.renderer.entity.CodRenderer
- net.minecraft.client.renderer.entity.CowRenderer
+ net.minecraft.client.renderer.entity.CreeperRenderer
- net.minecraft.client.renderer.entity.DisplayRenderer
+ net.minecraft.client.renderer.entity.DisplayRenderer$1
- net.minecraft.client.renderer.entity.DisplayRenderer$BlockDisplayRenderer
+ net.minecraft.client.renderer.entity.DisplayRenderer$ItemDisplayRenderer
- net.minecraft.client.renderer.entity.DisplayRenderer$TextDisplayRenderer
+ net.minecraft.client.renderer.entity.DolphinRenderer
- net.minecraft.client.renderer.entity.DragonFireballRenderer
+ net.minecraft.client.renderer.entity.DrownedRenderer
- net.minecraft.client.renderer.entity.ElderGuardianRenderer
+ net.minecraft.client.renderer.entity.EndCrystalRenderer
- net.minecraft.client.renderer.entity.EnderDragonRenderer
+ net.minecraft.client.renderer.entity.EnderDragonRenderer$DragonModel
- net.minecraft.client.renderer.entity.EndermanRenderer
+ net.minecraft.client.renderer.entity.EndermiteRenderer
- net.minecraft.client.renderer.entity.EntityRenderDispatcher
+ net.minecraft.client.renderer.entity.EntityRenderer
- net.minecraft.client.renderer.entity.EntityRendererProvider
+ net.minecraft.client.renderer.entity.EntityRendererProvider$Context
- net.minecraft.client.renderer.entity.EntityRenderers
+ net.minecraft.client.renderer.entity.EvokerFangsRenderer
- net.minecraft.client.renderer.entity.EvokerRenderer
+ net.minecraft.client.renderer.entity.EvokerRenderer$1
- net.minecraft.client.renderer.entity.ExperienceOrbRenderer
+ net.minecraft.client.renderer.entity.FallingBlockRenderer
- net.minecraft.client.renderer.entity.FireworkEntityRenderer
+ net.minecraft.client.renderer.entity.FishingHookRenderer
- net.minecraft.client.renderer.entity.FoxRenderer
+ net.minecraft.client.renderer.entity.FrogRenderer
- net.minecraft.client.renderer.entity.GhastRenderer
+ net.minecraft.client.renderer.entity.GiantMobRenderer
- net.minecraft.client.renderer.entity.GlowSquidRenderer
+ net.minecraft.client.renderer.entity.GoatRenderer
- net.minecraft.client.renderer.entity.GuardianRenderer
+ net.minecraft.client.renderer.entity.HoglinRenderer
- net.minecraft.client.renderer.entity.HorseRenderer
+ net.minecraft.client.renderer.entity.HumanoidMobRenderer
- net.minecraft.client.renderer.entity.HuskRenderer
+ net.minecraft.client.renderer.entity.IllagerRenderer
- net.minecraft.client.renderer.entity.IllusionerRenderer
+ net.minecraft.client.renderer.entity.IllusionerRenderer$1
- net.minecraft.client.renderer.entity.IronGolemRenderer
+ net.minecraft.client.renderer.entity.ItemEntityRenderer
- net.minecraft.client.renderer.entity.ItemFrameRenderer
+ net.minecraft.client.renderer.entity.ItemRenderer
+ net.minecraft.client.renderer.entity.layers.ArrowLayer
- net.minecraft.client.renderer.entity.layers.BeeStingerLayer
+ net.minecraft.client.renderer.entity.layers.CapeLayer
- net.minecraft.client.renderer.entity.layers.CarriedBlockLayer
+ net.minecraft.client.renderer.entity.layers.CatCollarLayer
- net.minecraft.client.renderer.entity.layers.CreeperPowerLayer
+ net.minecraft.client.renderer.entity.layers.CrossedArmsItemLayer
- net.minecraft.client.renderer.entity.layers.CustomHeadLayer
+ net.minecraft.client.renderer.entity.layers.Deadmau5EarsLayer
- net.minecraft.client.renderer.entity.layers.DolphinCarryingItemLayer
+ net.minecraft.client.renderer.entity.layers.DrownedOuterLayer
- net.minecraft.client.renderer.entity.layers.ElytraLayer
+ net.minecraft.client.renderer.entity.layers.EnderEyesLayer
- net.minecraft.client.renderer.entity.layers.EnergySwirlLayer
+ net.minecraft.client.renderer.entity.layers.EyesLayer
- net.minecraft.client.renderer.entity.layers.FoxHeldItemLayer
+ net.minecraft.client.renderer.entity.layers.HorseArmorLayer
- net.minecraft.client.renderer.entity.layers.HorseMarkingLayer
+ net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer
- net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer$1
+ net.minecraft.client.renderer.entity.layers.IronGolemCrackinessLayer
- net.minecraft.client.renderer.entity.layers.IronGolemFlowerLayer
+ net.minecraft.client.renderer.entity.layers.ItemInHandLayer
- net.minecraft.client.renderer.entity.layers.LlamaDecorLayer
+ net.minecraft.client.renderer.entity.layers.MushroomCowMushroomLayer
+ net.minecraft.client.renderer.entity.layers.package-info
- net.minecraft.client.renderer.entity.layers.PandaHoldsItemLayer
+ net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
- net.minecraft.client.renderer.entity.layers.PhantomEyesLayer
+ net.minecraft.client.renderer.entity.layers.PlayerItemInHandLayer
- net.minecraft.client.renderer.entity.layers.RenderLayer
+ net.minecraft.client.renderer.entity.layers.SaddleLayer
- net.minecraft.client.renderer.entity.layers.SheepFurLayer
+ net.minecraft.client.renderer.entity.layers.ShulkerHeadLayer
- net.minecraft.client.renderer.entity.layers.SlimeOuterLayer
+ net.minecraft.client.renderer.entity.layers.SnowGolemHeadLayer
- net.minecraft.client.renderer.entity.layers.SpiderEyesLayer
+ net.minecraft.client.renderer.entity.layers.SpinAttackEffectLayer
- net.minecraft.client.renderer.entity.layers.StrayClothingLayer
+ net.minecraft.client.renderer.entity.layers.StuckInBodyLayer
- net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer
+ net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer$1
- net.minecraft.client.renderer.entity.layers.VillagerProfessionLayer
+ net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer
- net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer$AlphaFunction
+ net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer$DrawSelector
- net.minecraft.client.renderer.entity.layers.WitchItemLayer
+ net.minecraft.client.renderer.entity.layers.WitherArmorLayer
- net.minecraft.client.renderer.entity.layers.WolfCollarLayer
- net.minecraft.client.renderer.entity.LeashKnotRenderer
+ net.minecraft.client.renderer.entity.LightningBoltRenderer
- net.minecraft.client.renderer.entity.LivingEntityRenderer
+ net.minecraft.client.renderer.entity.LivingEntityRenderer$1
- net.minecraft.client.renderer.entity.LlamaRenderer
+ net.minecraft.client.renderer.entity.LlamaRenderer$1
- net.minecraft.client.renderer.entity.LlamaSpitRenderer
+ net.minecraft.client.renderer.entity.MagmaCubeRenderer
- net.minecraft.client.renderer.entity.MinecartRenderer
+ net.minecraft.client.renderer.entity.MobRenderer
- net.minecraft.client.renderer.entity.MushroomCowRenderer
+ net.minecraft.client.renderer.entity.NoopRenderer
- net.minecraft.client.renderer.entity.OcelotRenderer
- net.minecraft.client.renderer.entity.package-info
+ net.minecraft.client.renderer.entity.PaintingRenderer
- net.minecraft.client.renderer.entity.PandaRenderer
+ net.minecraft.client.renderer.entity.ParrotRenderer
- net.minecraft.client.renderer.entity.ParrotRenderer$1
+ net.minecraft.client.renderer.entity.PhantomRenderer
+ net.minecraft.client.renderer.entity.PiglinRenderer
- net.minecraft.client.renderer.entity.PigRenderer
- net.minecraft.client.renderer.entity.PillagerRenderer
- net.minecraft.client.renderer.entity.player.package-info
+ net.minecraft.client.renderer.entity.player.PlayerRenderer
+ net.minecraft.client.renderer.entity.PolarBearRenderer
- net.minecraft.client.renderer.entity.PufferfishRenderer
+ net.minecraft.client.renderer.entity.RabbitRenderer
- net.minecraft.client.renderer.entity.RabbitRenderer$1
+ net.minecraft.client.renderer.entity.RavagerRenderer
- net.minecraft.client.renderer.entity.RenderLayerParent
+ net.minecraft.client.renderer.entity.SalmonRenderer
- net.minecraft.client.renderer.entity.SheepRenderer
+ net.minecraft.client.renderer.entity.ShulkerBulletRenderer
- net.minecraft.client.renderer.entity.ShulkerRenderer
+ net.minecraft.client.renderer.entity.SilverfishRenderer
- net.minecraft.client.renderer.entity.SkeletonRenderer
+ net.minecraft.client.renderer.entity.SlimeRenderer
- net.minecraft.client.renderer.entity.SnifferRenderer
+ net.minecraft.client.renderer.entity.SnowGolemRenderer
- net.minecraft.client.renderer.entity.SpectralArrowRenderer
+ net.minecraft.client.renderer.entity.SpiderRenderer
- net.minecraft.client.renderer.entity.SquidRenderer
+ net.minecraft.client.renderer.entity.StrayRenderer
- net.minecraft.client.renderer.entity.StriderRenderer
+ net.minecraft.client.renderer.entity.TadpoleRenderer
- net.minecraft.client.renderer.entity.ThrownItemRenderer
+ net.minecraft.client.renderer.entity.ThrownTridentRenderer
- net.minecraft.client.renderer.entity.TippableArrowRenderer
+ net.minecraft.client.renderer.entity.TntMinecartRenderer
- net.minecraft.client.renderer.entity.TntRenderer
+ net.minecraft.client.renderer.entity.TropicalFishRenderer
- net.minecraft.client.renderer.entity.TropicalFishRenderer$1
+ net.minecraft.client.renderer.entity.TurtleRenderer
- net.minecraft.client.renderer.entity.UndeadHorseRenderer
+ net.minecraft.client.renderer.entity.VexRenderer
- net.minecraft.client.renderer.entity.VillagerRenderer
+ net.minecraft.client.renderer.entity.VindicatorRenderer
- net.minecraft.client.renderer.entity.VindicatorRenderer$1
+ net.minecraft.client.renderer.entity.WanderingTraderRenderer
- net.minecraft.client.renderer.entity.WardenRenderer
+ net.minecraft.client.renderer.entity.WitchRenderer
- net.minecraft.client.renderer.entity.WitherBossRenderer
+ net.minecraft.client.renderer.entity.WitherSkeletonRenderer
- net.minecraft.client.renderer.entity.WitherSkullRenderer
+ net.minecraft.client.renderer.entity.WolfRenderer
- net.minecraft.client.renderer.entity.ZoglinRenderer
+ net.minecraft.client.renderer.entity.ZombieRenderer
- net.minecraft.client.renderer.entity.ZombieVillagerRenderer
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
+ net.minecraft.client.renderer.item.ClampedItemPropertyFunction
- net.minecraft.client.renderer.item.CompassItemPropertyFunction
+ net.minecraft.client.renderer.item.CompassItemPropertyFunction$CompassTarget
- net.minecraft.client.renderer.item.CompassItemPropertyFunction$CompassWobble
+ net.minecraft.client.renderer.item.ItemProperties
- net.minecraft.client.renderer.item.ItemProperties$1
+ net.minecraft.client.renderer.item.ItemPropertyFunction
- net.minecraft.client.renderer.item.package-info
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
+ net.minecraft.client.renderer.package-info
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
+ net.minecraft.client.renderer.SectionOcclusionGraph
- net.minecraft.client.renderer.SectionOcclusionGraph$GraphEvents
+ net.minecraft.client.renderer.SectionOcclusionGraph$GraphState
- net.minecraft.client.renderer.SectionOcclusionGraph$GraphStorage
+ net.minecraft.client.renderer.SectionOcclusionGraph$Node
- net.minecraft.client.renderer.SectionOcclusionGraph$SectionToNodeMap
+ net.minecraft.client.renderer.ShaderInstance
- net.minecraft.client.renderer.ShaderInstance$1
+ net.minecraft.client.renderer.Sheets
- net.minecraft.client.renderer.Sheets$1
+ net.minecraft.client.renderer.SpriteCoordinateExpander
- net.minecraft.client.renderer.texture.AbstractTexture
- net.minecraft.client.renderer.texture.atlas.package-info
+ net.minecraft.client.renderer.texture.atlas.sources.DirectoryLister
- net.minecraft.client.renderer.texture.atlas.sources.LazyLoadedImage
- net.minecraft.client.renderer.texture.atlas.sources.package-info
+ net.minecraft.client.renderer.texture.atlas.sources.PalettedPermutations
- net.minecraft.client.renderer.texture.atlas.sources.PalettedPermutations$PalettedSpriteSupplier
+ net.minecraft.client.renderer.texture.atlas.sources.SingleFile
- net.minecraft.client.renderer.texture.atlas.sources.SourceFilter
+ net.minecraft.client.renderer.texture.atlas.sources.Unstitcher
- net.minecraft.client.renderer.texture.atlas.sources.Unstitcher$Region
+ net.minecraft.client.renderer.texture.atlas.sources.Unstitcher$RegionInstance
- net.minecraft.client.renderer.texture.atlas.SpriteResourceLoader
+ net.minecraft.client.renderer.texture.atlas.SpriteSource
- net.minecraft.client.renderer.texture.atlas.SpriteSource$Output
+ net.minecraft.client.renderer.texture.atlas.SpriteSource$SpriteSupplier
- net.minecraft.client.renderer.texture.atlas.SpriteSourceList
+ net.minecraft.client.renderer.texture.atlas.SpriteSourceList$1
+ net.minecraft.client.renderer.texture.atlas.SpriteSources
- net.minecraft.client.renderer.texture.atlas.SpriteSourceType
+ net.minecraft.client.renderer.texture.Dumpable
- net.minecraft.client.renderer.texture.DynamicTexture
+ net.minecraft.client.renderer.texture.HttpTexture
- net.minecraft.client.renderer.texture.MipmapGenerator
+ net.minecraft.client.renderer.texture.MissingTextureAtlasSprite
- net.minecraft.client.renderer.texture.OverlayTexture
+ net.minecraft.client.renderer.texture.package-info
+ net.minecraft.client.renderer.texture.PreloadedTexture
- net.minecraft.client.renderer.texture.SimpleTexture
+ net.minecraft.client.renderer.texture.SimpleTexture$TextureImage
- net.minecraft.client.renderer.texture.SpriteContents
+ net.minecraft.client.renderer.texture.SpriteContents$AnimatedTexture
- net.minecraft.client.renderer.texture.SpriteContents$FrameInfo
+ net.minecraft.client.renderer.texture.SpriteContents$InterpolationData
- net.minecraft.client.renderer.texture.SpriteContents$Ticker
+ net.minecraft.client.renderer.texture.SpriteLoader
- net.minecraft.client.renderer.texture.SpriteLoader$Preparations
+ net.minecraft.client.renderer.texture.SpriteTicker
- net.minecraft.client.renderer.texture.Stitcher
+ net.minecraft.client.renderer.texture.Stitcher$Entry
- net.minecraft.client.renderer.texture.Stitcher$Holder
+ net.minecraft.client.renderer.texture.Stitcher$Region
- net.minecraft.client.renderer.texture.Stitcher$SpriteLoader
+ net.minecraft.client.renderer.texture.StitcherException
- net.minecraft.client.renderer.texture.TextureAtlas
+ net.minecraft.client.renderer.texture.TextureAtlasSprite
- net.minecraft.client.renderer.texture.TextureAtlasSprite$1
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$Ticker
- net.minecraft.client.renderer.texture.TextureManager
+ net.minecraft.client.renderer.texture.Tickable
- net.minecraft.client.renderer.ViewArea
+ net.minecraft.client.renderer.VirtualScreen
+ net.minecraft.client.ResourceLoadStateTracker
- net.minecraft.client.ResourceLoadStateTracker$RecoveryInfo
+ net.minecraft.client.ResourceLoadStateTracker$ReloadReason
- net.minecraft.client.ResourceLoadStateTracker$ReloadState
- net.minecraft.client.resources.ClientPackSource
+ net.minecraft.client.resources.DefaultPlayerSkin
- net.minecraft.client.resources.DownloadedPackSource
+ net.minecraft.client.resources.FoliageColorReloadListener
- net.minecraft.client.resources.GrassColorReloadListener
+ net.minecraft.client.resources.IndexedAssetSource
+ net.minecraft.client.resources.language.ClientLanguage
- net.minecraft.client.resources.language.FormattedBidiReorder
+ net.minecraft.client.resources.language.I18n
- net.minecraft.client.resources.language.LanguageInfo
+ net.minecraft.client.resources.language.LanguageManager
- net.minecraft.client.resources.language.package-info
- net.minecraft.client.resources.LegacyStuffWrapper
+ net.minecraft.client.resources.metadata.animation.AnimationFrame
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$1
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$FrameOutput
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSectionSerializer
- net.minecraft.client.resources.metadata.animation.FrameSize
- net.minecraft.client.resources.metadata.animation.package-info
+ net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection
- net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection$Hat
+ net.minecraft.client.resources.metadata.animation.VillagerMetadataSectionSerializer
+ net.minecraft.client.resources.metadata.gui.GuiMetadataSection
- net.minecraft.client.resources.metadata.gui.GuiSpriteScaling
+ net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$NineSlice
- net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$NineSlice$Border
+ net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$Stretch
- net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$Tile
+ net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$Type
- net.minecraft.client.resources.metadata.gui.package-info
+ net.minecraft.client.resources.metadata.language.LanguageMetadataSection
- net.minecraft.client.resources.metadata.language.package-info
+ net.minecraft.client.resources.metadata.package-info
- net.minecraft.client.resources.metadata.texture.package-info
- net.minecraft.client.resources.metadata.texture.TextureMetadataSection
+ net.minecraft.client.resources.metadata.texture.TextureMetadataSectionSerializer
+ net.minecraft.client.resources.MobEffectTextureManager
+ net.minecraft.client.resources.model.AtlasSet
- net.minecraft.client.resources.model.AtlasSet$AtlasEntry
+ net.minecraft.client.resources.model.AtlasSet$StitchResult
- net.minecraft.client.resources.model.BakedModel
+ net.minecraft.client.resources.model.BlockModelRotation
- net.minecraft.client.resources.model.BuiltInModel
+ net.minecraft.client.resources.model.Material
- net.minecraft.client.resources.model.ModelBaker
+ net.minecraft.client.resources.model.ModelBakery
- net.minecraft.client.resources.model.ModelBakery$BakedCacheKey
+ net.minecraft.client.resources.model.ModelBakery$BlockStateDefinitionException
- net.minecraft.client.resources.model.ModelBakery$LoadedJson
+ net.minecraft.client.resources.model.ModelBakery$ModelBakerImpl
- net.minecraft.client.resources.model.ModelBakery$ModelGroupKey
+ net.minecraft.client.resources.model.ModelManager
- net.minecraft.client.resources.model.ModelManager$ReloadState
+ net.minecraft.client.resources.model.ModelResourceLocation
- net.minecraft.client.resources.model.ModelState
+ net.minecraft.client.resources.model.MultiPartBakedModel
- net.minecraft.client.resources.model.MultiPartBakedModel$Builder
- net.minecraft.client.resources.model.package-info
+ net.minecraft.client.resources.model.SimpleBakedModel
- net.minecraft.client.resources.model.SimpleBakedModel$Builder
+ net.minecraft.client.resources.model.UnbakedModel
- net.minecraft.client.resources.model.WeightedBakedModel
+ net.minecraft.client.resources.model.WeightedBakedModel$Builder
+ net.minecraft.client.resources.package-info
- net.minecraft.client.resources.PaintingTextureManager
+ net.minecraft.client.resources.PlayerSkin
- net.minecraft.client.resources.PlayerSkin$Model
+ net.minecraft.client.resources.SkinManager
- net.minecraft.client.resources.SkinManager$1
+ net.minecraft.client.resources.SkinManager$2
- net.minecraft.client.resources.SkinManager$CacheKey
+ net.minecraft.client.resources.SkinManager$TextureCache
- net.minecraft.client.resources.SkinManager$TextureInfo
- net.minecraft.client.resources.sounds.AbstractSoundInstance
+ net.minecraft.client.resources.sounds.AbstractTickableSoundInstance
- net.minecraft.client.resources.sounds.AmbientSoundHandler
+ net.minecraft.client.resources.sounds.BeeAggressiveSoundInstance
- net.minecraft.client.resources.sounds.BeeFlyingSoundInstance
+ net.minecraft.client.resources.sounds.BeeSoundInstance
- net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler
+ net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
- net.minecraft.client.resources.sounds.BubbleColumnAmbientSoundHandler
+ net.minecraft.client.resources.sounds.ElytraOnPlayerSoundInstance
- net.minecraft.client.resources.sounds.EntityBoundSoundInstance
+ net.minecraft.client.resources.sounds.GuardianAttackSoundInstance
- net.minecraft.client.resources.sounds.MinecartSoundInstance
+ net.minecraft.client.resources.sounds.package-info
+ net.minecraft.client.resources.sounds.RidingMinecartSoundInstance
- net.minecraft.client.resources.sounds.SimpleSoundInstance
+ net.minecraft.client.resources.sounds.SnifferSoundInstance
- net.minecraft.client.resources.sounds.Sound
+ net.minecraft.client.resources.sounds.Sound$Type
- net.minecraft.client.resources.sounds.SoundEventRegistration
+ net.minecraft.client.resources.sounds.SoundEventRegistrationSerializer
- net.minecraft.client.resources.sounds.SoundInstance
+ net.minecraft.client.resources.sounds.SoundInstance$Attenuation
- net.minecraft.client.resources.sounds.TickableSoundInstance
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundHandler
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
+ net.minecraft.client.resources.SplashManager
- net.minecraft.client.resources.TextureAtlasHolder
+ net.minecraft.client.Screenshot
- net.minecraft.client.searchtree.FullTextSearchTree
+ net.minecraft.client.searchtree.IdSearchTree
- net.minecraft.client.searchtree.IntersectionIterator
+ net.minecraft.client.searchtree.MergingUniqueIterator
+ net.minecraft.client.searchtree.package-info
- net.minecraft.client.searchtree.PlainTextSearchTree
+ net.minecraft.client.searchtree.RefreshableSearchTree
- net.minecraft.client.searchtree.ResourceLocationSearchTree
+ net.minecraft.client.searchtree.ResourceLocationSearchTree$1
- net.minecraft.client.searchtree.ResourceLocationSearchTree$2
+ net.minecraft.client.searchtree.SearchRegistry
- net.minecraft.client.searchtree.SearchRegistry$Key
+ net.minecraft.client.searchtree.SearchRegistry$TreeBuilderSupplier
- net.minecraft.client.searchtree.SearchRegistry$TreeEntry
+ net.minecraft.client.searchtree.SearchTree
- net.minecraft.client.searchtree.SuffixArray
- net.minecraft.client.server.IntegratedPlayerList
+ net.minecraft.client.server.IntegratedServer
- net.minecraft.client.server.LanServer
+ net.minecraft.client.server.LanServerDetection
- net.minecraft.client.server.LanServerDetection$LanServerDetector
+ net.minecraft.client.server.LanServerDetection$LanServerList
- net.minecraft.client.server.LanServerPinger
+ net.minecraft.client.server.package-info
- net.minecraft.client.sounds.AudioStream
+ net.minecraft.client.sounds.ChannelAccess
- net.minecraft.client.sounds.ChannelAccess$ChannelHandle
+ net.minecraft.client.sounds.LoopingAudioStream
- net.minecraft.client.sounds.LoopingAudioStream$AudioStreamProvider
+ net.minecraft.client.sounds.LoopingAudioStream$NoCloseBuffer
- net.minecraft.client.sounds.MusicManager
+ net.minecraft.client.sounds.package-info
+ net.minecraft.client.sounds.SoundBufferLibrary
- net.minecraft.client.sounds.SoundEngine
+ net.minecraft.client.sounds.SoundEngine$DeviceCheckState
- net.minecraft.client.sounds.SoundEngineExecutor
+ net.minecraft.client.sounds.SoundEventListener
- net.minecraft.client.sounds.SoundManager
+ net.minecraft.client.sounds.SoundManager$1
- net.minecraft.client.sounds.SoundManager$2
+ net.minecraft.client.sounds.SoundManager$Preparations
- net.minecraft.client.sounds.SoundManager$Preparations$1
+ net.minecraft.client.sounds.WeighedSoundEvents
- net.minecraft.client.sounds.Weighted
- net.minecraft.client.StringSplitter
+ net.minecraft.client.StringSplitter$1
- net.minecraft.client.StringSplitter$FlatComponents
+ net.minecraft.client.StringSplitter$LineBreakFinder
- net.minecraft.client.StringSplitter$LineComponent
+ net.minecraft.client.StringSplitter$LinePosConsumer
- net.minecraft.client.StringSplitter$WidthLimitedCharSink
+ net.minecraft.client.StringSplitter$WidthProvider
- net.minecraft.client.telemetry.ClientTelemetryManager
- net.minecraft.client.telemetry.events.AggregatedTelemetryEvent
+ net.minecraft.client.telemetry.events.GameLoadTimesEvent
- net.minecraft.client.telemetry.events.GameLoadTimesEvent$Measurement
- net.minecraft.client.telemetry.events.package-info
+ net.minecraft.client.telemetry.events.PerformanceMetricsEvent
- net.minecraft.client.telemetry.events.WorldLoadEvent
+ net.minecraft.client.telemetry.events.WorldLoadEvent$1
- net.minecraft.client.telemetry.events.WorldLoadTimesEvent
+ net.minecraft.client.telemetry.events.WorldUnloadEvent
+ net.minecraft.client.telemetry.package-info
+ net.minecraft.client.telemetry.TelemetryEventInstance
- net.minecraft.client.telemetry.TelemetryEventLog
+ net.minecraft.client.telemetry.TelemetryEventLogger
- net.minecraft.client.telemetry.TelemetryEventSender
+ net.minecraft.client.telemetry.TelemetryEventType
- net.minecraft.client.telemetry.TelemetryEventType$Builder
+ net.minecraft.client.telemetry.TelemetryLogManager
- net.minecraft.client.telemetry.TelemetryProperty
+ net.minecraft.client.telemetry.TelemetryProperty$Exporter
- net.minecraft.client.telemetry.TelemetryProperty$GameMode
+ net.minecraft.client.telemetry.TelemetryProperty$ServerType
- net.minecraft.client.telemetry.TelemetryPropertyMap
+ net.minecraft.client.telemetry.TelemetryPropertyMap$1
- net.minecraft.client.telemetry.TelemetryPropertyMap$Builder
+ net.minecraft.client.telemetry.WorldSessionTelemetryManager
- net.minecraft.client.Timer
+ net.minecraft.client.ToggleKeyMapping
- net.minecraft.client.tutorial.BundleTutorial
+ net.minecraft.client.tutorial.CompletedTutorialStepInstance
- net.minecraft.client.tutorial.CraftPlanksTutorialStep
+ net.minecraft.client.tutorial.FindTreeTutorialStepInstance
- net.minecraft.client.tutorial.MovementTutorialStepInstance
+ net.minecraft.client.tutorial.OpenInventoryTutorialStep
+ net.minecraft.client.tutorial.package-info
- net.minecraft.client.tutorial.PunchTreeTutorialStepInstance
+ net.minecraft.client.tutorial.Tutorial
- net.minecraft.client.tutorial.Tutorial$TimedToast
+ net.minecraft.client.tutorial.TutorialStepInstance
- net.minecraft.client.tutorial.TutorialSteps
- net.minecraft.client.User
+ net.minecraft.client.User$Type
+ net.minecraft.commands.arguments.AngleArgument
- net.minecraft.commands.arguments.AngleArgument$SingleAngle
+ net.minecraft.commands.arguments.ArgumentSignatures
- net.minecraft.commands.arguments.ArgumentSignatures$Entry
+ net.minecraft.commands.arguments.ArgumentSignatures$Signer
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
- net.minecraft.commands.arguments.ColorArgument
+ net.minecraft.commands.arguments.ComponentArgument
- net.minecraft.commands.arguments.CompoundTagArgument
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
+ net.minecraft.commands.arguments.DimensionArgument
- net.minecraft.commands.arguments.EntityAnchorArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
- net.minecraft.commands.arguments.EntityArgument
+ net.minecraft.commands.arguments.EntityArgument$Info
- net.minecraft.commands.arguments.EntityArgument$Info$Template
+ net.minecraft.commands.arguments.GameModeArgument
- net.minecraft.commands.arguments.GameProfileArgument
+ net.minecraft.commands.arguments.GameProfileArgument$Result
- net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
+ net.minecraft.commands.arguments.HeightmapTypeArgument
- net.minecraft.commands.arguments.item.FunctionArgument
+ net.minecraft.commands.arguments.item.FunctionArgument$1
- net.minecraft.commands.arguments.item.FunctionArgument$2
+ net.minecraft.commands.arguments.item.FunctionArgument$Result
- net.minecraft.commands.arguments.item.ItemArgument
+ net.minecraft.commands.arguments.item.ItemInput
- net.minecraft.commands.arguments.item.ItemParser
+ net.minecraft.commands.arguments.item.ItemParser$ItemResult
- net.minecraft.commands.arguments.item.ItemParser$TagResult
+ net.minecraft.commands.arguments.item.ItemPredicateArgument
- net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
+ net.minecraft.commands.arguments.item.package-info
- net.minecraft.commands.arguments.MessageArgument
+ net.minecraft.commands.arguments.MessageArgument$Message
- net.minecraft.commands.arguments.MessageArgument$Part
+ net.minecraft.commands.arguments.NbtPathArgument
- net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
+ net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
- net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$NbtPath
+ net.minecraft.commands.arguments.NbtPathArgument$Node
- net.minecraft.commands.arguments.NbtTagArgument
+ net.minecraft.commands.arguments.ObjectiveArgument
- net.minecraft.commands.arguments.ObjectiveCriteriaArgument
+ net.minecraft.commands.arguments.OperationArgument
- net.minecraft.commands.arguments.OperationArgument$Operation
+ net.minecraft.commands.arguments.OperationArgument$SimpleOperation
- net.minecraft.commands.arguments.package-info
- net.minecraft.commands.arguments.ParticleArgument
+ net.minecraft.commands.arguments.RangeArgument
- net.minecraft.commands.arguments.RangeArgument$Floats
+ net.minecraft.commands.arguments.RangeArgument$Ints
- net.minecraft.commands.arguments.ResourceArgument
+ net.minecraft.commands.arguments.ResourceArgument$Info
- net.minecraft.commands.arguments.ResourceArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceKeyArgument
- net.minecraft.commands.arguments.ResourceKeyArgument$Info
+ net.minecraft.commands.arguments.ResourceKeyArgument$Info$Template
- net.minecraft.commands.arguments.ResourceLocationArgument
+ net.minecraft.commands.arguments.ResourceOrTagArgument
- net.minecraft.commands.arguments.ResourceOrTagArgument$Info
+ net.minecraft.commands.arguments.ResourceOrTagArgument$Info$Template
- net.minecraft.commands.arguments.ResourceOrTagArgument$ResourceResult
+ net.minecraft.commands.arguments.ResourceOrTagArgument$Result
- net.minecraft.commands.arguments.ResourceOrTagArgument$TagResult
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info$Template
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Result
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$TagResult
- net.minecraft.commands.arguments.ScoreboardSlotArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument
- net.minecraft.commands.arguments.ScoreHolderArgument$Info
+ net.minecraft.commands.arguments.ScoreHolderArgument$Info$Template
- net.minecraft.commands.arguments.ScoreHolderArgument$Result
+ net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
+ net.minecraft.commands.arguments.selector.EntitySelector
- net.minecraft.commands.arguments.selector.EntitySelector$1
+ net.minecraft.commands.arguments.selector.EntitySelectorParser
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
+ net.minecraft.commands.arguments.selector.options.package-info
- net.minecraft.commands.arguments.selector.package-info
+ net.minecraft.commands.arguments.SignedArgument
- net.minecraft.commands.arguments.SlotArgument
+ net.minecraft.commands.arguments.StringRepresentableArgument
- net.minecraft.commands.arguments.TeamArgument
+ net.minecraft.commands.arguments.TemplateMirrorArgument
- net.minecraft.commands.arguments.TemplateRotationArgument
+ net.minecraft.commands.arguments.TimeArgument
- net.minecraft.commands.arguments.TimeArgument$Info
+ net.minecraft.commands.arguments.TimeArgument$Info$Template
- net.minecraft.commands.arguments.UuidArgument
- net.minecraft.commands.BrigadierExceptions
+ net.minecraft.commands.CommandBuildContext
- net.minecraft.commands.CommandBuildContext$1
+ net.minecraft.commands.CommandBuildContext$2
- net.minecraft.commands.CommandBuildContext$2$1
+ net.minecraft.commands.CommandBuildContext$3
- net.minecraft.commands.CommandBuildContext$Configurable
+ net.minecraft.commands.CommandBuildContext$MissingTagAccessPolicy
- net.minecraft.commands.CommandFunction
+ net.minecraft.commands.CommandFunction$CacheableFunction
- net.minecraft.commands.CommandFunction$CommandEntry
+ net.minecraft.commands.CommandFunction$CommandMacro
- net.minecraft.commands.CommandFunction$Entry
+ net.minecraft.commands.CommandFunction$FunctionEntry
- net.minecraft.commands.CommandFunction$MacroEntry
+ net.minecraft.commands.CommandRuntimeException
- net.minecraft.commands.Commands
+ net.minecraft.commands.Commands$1
- net.minecraft.commands.Commands$1$1
+ net.minecraft.commands.Commands$CommandSelection
- net.minecraft.commands.Commands$ParseFunction
- net.minecraft.commands.CommandSigningContext
+ net.minecraft.commands.CommandSigningContext$1
- net.minecraft.commands.CommandSigningContext$SignedArguments
+ net.minecraft.commands.CommandSource
- net.minecraft.commands.CommandSource$1
+ net.minecraft.commands.CommandSourceStack
+ net.minecraft.commands.FunctionInstantiationException
+ net.minecraft.commands.package-info
- net.minecraft.commands.SharedSuggestionProvider
+ net.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
- net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- net.minecraft.commands.synchronization.ArgumentTypeInfo
+ net.minecraft.commands.synchronization.ArgumentTypeInfo$Template
- net.minecraft.commands.synchronization.ArgumentTypeInfos
+ net.minecraft.commands.synchronization.ArgumentUtils
- net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.LongArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.LongArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.package-info
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$1
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$Template
- net.minecraft.commands.synchronization.package-info
- net.minecraft.commands.synchronization.SingletonArgumentInfo
+ net.minecraft.commands.synchronization.SingletonArgumentInfo$Template
- net.minecraft.commands.synchronization.SuggestionProviders
+ net.minecraft.commands.synchronization.SuggestionProviders$Wrapper
+ net.minecraft.core.AxisCycle
- net.minecraft.core.AxisCycle$1
+ net.minecraft.core.AxisCycle$2
- net.minecraft.core.AxisCycle$3
+ net.minecraft.core.BlockMath
- net.minecraft.core.BlockPos
+ net.minecraft.core.BlockPos$1
- net.minecraft.core.BlockPos$2
+ net.minecraft.core.BlockPos$3
- net.minecraft.core.BlockPos$4
+ net.minecraft.core.BlockPos$5
- net.minecraft.core.BlockPos$MutableBlockPos
- net.minecraft.core.cauldron.CauldronInteraction
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
- net.minecraft.core.HolderLookup$Delegate
+ net.minecraft.core.HolderLookup$Provider
- net.minecraft.core.HolderLookup$Provider$1
+ net.minecraft.core.HolderLookup$Provider$2
- net.minecraft.core.HolderLookup$RegistryLookup
+ net.minecraft.core.HolderLookup$RegistryLookup$Delegate
- net.minecraft.core.HolderOwner
+ net.minecraft.core.HolderSet
- net.minecraft.core.HolderSet$Direct
+ net.minecraft.core.HolderSet$ListBacked
- net.minecraft.core.HolderSet$Named
+ net.minecraft.core.IdMap
- net.minecraft.core.IdMapper
+ net.minecraft.core.LayeredRegistryAccess
- net.minecraft.core.MappedRegistry
+ net.minecraft.core.MappedRegistry$1
- net.minecraft.core.MappedRegistry$2
+ net.minecraft.core.NonNullList
- net.minecraft.core.Position
+ net.minecraft.core.QuartPos
- net.minecraft.core.Registry
+ net.minecraft.core.Registry$1
- net.minecraft.core.Registry$2
+ net.minecraft.core.RegistryAccess
- net.minecraft.core.RegistryAccess$1
+ net.minecraft.core.RegistryAccess$1FrozenAccess
- net.minecraft.core.RegistryAccess$Frozen
+ net.minecraft.core.RegistryAccess$ImmutableRegistryAccess
- net.minecraft.core.RegistryAccess$RegistryEntry
+ net.minecraft.core.RegistryCodecs
- net.minecraft.core.RegistryCodecs$RegistryEntry
+ net.minecraft.core.RegistrySetBuilder
- net.minecraft.core.RegistrySetBuilder$1
+ net.minecraft.core.RegistrySetBuilder$BuildState
- net.minecraft.core.RegistrySetBuilder$BuildState$1
+ net.minecraft.core.RegistrySetBuilder$CompositeOwner
- net.minecraft.core.RegistrySetBuilder$EmptyTagLookup
+ net.minecraft.core.RegistrySetBuilder$RegisteredValue
- net.minecraft.core.RegistrySetBuilder$RegistryBootstrap
+ net.minecraft.core.RegistrySetBuilder$RegistryContents
- net.minecraft.core.RegistrySetBuilder$RegistryContents$1
+ net.minecraft.core.RegistrySetBuilder$RegistryStub
- net.minecraft.core.RegistrySetBuilder$UniversalLookup
+ net.minecraft.core.RegistrySetBuilder$ValueAndHolder
- net.minecraft.core.RegistrySynchronization
+ net.minecraft.core.RegistrySynchronization$NetworkedRegistryData
- net.minecraft.core.Rotations
+ net.minecraft.core.SectionPos
- net.minecraft.core.SectionPos$1
+ net.minecraft.core.UUIDUtil
- net.minecraft.core.Vec3i
+ net.minecraft.core.WritableRegistry
- net.minecraft.network.chat.ComponentContents
+ net.minecraft.network.chat.ComponentContents$1
- net.minecraft.network.chat.ComponentSerialization
- net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.contents.DataSource$Type
+ net.minecraft.network.chat.contents.EntityDataSource
- net.minecraft.network.chat.contents.KeybindContents
+ net.minecraft.network.chat.contents.KeybindResolver
+ net.minecraft.network.chat.contents.package-info
- net.minecraft.network.chat.contents.PlainTextContents$1
- net.minecraft.network.chat.contents.ScoreContents
+ net.minecraft.network.chat.contents.SelectorContents
- net.minecraft.network.chat.contents.StorageDataSource
+ net.minecraft.network.chat.contents.TranslatableContents
- net.minecraft.network.chat.contents.TranslatableFormatException
+ net.minecraft.network.chat.FilterMask
- net.minecraft.network.chat.FilterMask$1
+ net.minecraft.network.chat.FilterMask$Type
- net.minecraft.network.chat.FormattedText
+ net.minecraft.network.chat.FormattedText$1
- net.minecraft.network.chat.FormattedText$2
+ net.minecraft.network.chat.FormattedText$3
- net.minecraft.network.chat.FormattedText$4
+ net.minecraft.network.chat.FormattedText$ContentConsumer
- net.minecraft.network.chat.FormattedText$StyledContentConsumer
+ net.minecraft.network.chat.HoverEvent
- net.minecraft.network.chat.HoverEvent$Action
+ net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
- net.minecraft.network.chat.HoverEvent$ItemStackInfo
- net.minecraft.network.chat.package-info
+ net.minecraft.network.package-info
- net.minecraft.network.protocol.BundleDelimiterPacket
+ net.minecraft.network.protocol.BundlePacket
- net.minecraft.network.protocol.BundlerInfo
+ net.minecraft.network.protocol.BundlerInfo$1
- net.minecraft.network.protocol.BundlerInfo$2
+ net.minecraft.network.protocol.BundlerInfo$2$1
- net.minecraft.network.protocol.BundlerInfo$Bundler
+ net.minecraft.network.protocol.BundlerInfo$Provider
- net.minecraft.network.protocol.common.ClientboundCustomPayloadPacket
+ net.minecraft.network.protocol.common.ClientboundDisconnectPacket
- net.minecraft.network.protocol.common.ClientboundKeepAlivePacket
+ net.minecraft.network.protocol.common.ClientboundPingPacket
- net.minecraft.network.protocol.common.ClientboundResourcePackPacket
+ net.minecraft.network.protocol.common.ClientboundUpdateTagsPacket
+ net.minecraft.network.protocol.common.ClientCommonPacketListener
+ net.minecraft.network.protocol.common.custom.BeeDebugPayload
- net.minecraft.network.protocol.common.custom.BeeDebugPayload$BeeInfo
+ net.minecraft.network.protocol.common.custom.BrainDebugPayload
- net.minecraft.network.protocol.common.custom.BrainDebugPayload$BrainDump
+ net.minecraft.network.protocol.common.custom.BrandPayload
- net.minecraft.network.protocol.common.custom.CustomPacketPayload
+ net.minecraft.network.protocol.common.custom.DiscardedPayload
- net.minecraft.network.protocol.common.custom.GameEventDebugPayload
+ net.minecraft.network.protocol.common.custom.GameEventListenerDebugPayload
- net.minecraft.network.protocol.common.custom.GameTestAddMarkerDebugPayload
+ net.minecraft.network.protocol.common.custom.GameTestClearMarkersDebugPayload
- net.minecraft.network.protocol.common.custom.GoalDebugPayload
+ net.minecraft.network.protocol.common.custom.GoalDebugPayload$DebugGoal
- net.minecraft.network.protocol.common.custom.HiveDebugPayload
+ net.minecraft.network.protocol.common.custom.HiveDebugPayload$HiveInfo
- net.minecraft.network.protocol.common.custom.NeighborUpdatesDebugPayload
- net.minecraft.network.protocol.common.custom.package-info
+ net.minecraft.network.protocol.common.custom.PathfindingDebugPayload
- net.minecraft.network.protocol.common.custom.PoiAddedDebugPayload
+ net.minecraft.network.protocol.common.custom.PoiRemovedDebugPayload
- net.minecraft.network.protocol.common.custom.PoiTicketCountDebugPayload
+ net.minecraft.network.protocol.common.custom.RaidsDebugPayload
- net.minecraft.network.protocol.common.custom.StructuresDebugPayload
+ net.minecraft.network.protocol.common.custom.StructuresDebugPayload$PieceInfo
- net.minecraft.network.protocol.common.custom.VillageSectionsDebugPayload
+ net.minecraft.network.protocol.common.custom.WorldGenAttemptDebugPayload
+ net.minecraft.network.protocol.common.package-info
+ net.minecraft.network.protocol.common.ServerboundClientInformationPacket
- net.minecraft.network.protocol.common.ServerboundCustomPayloadPacket
+ net.minecraft.network.protocol.common.ServerboundKeepAlivePacket
- net.minecraft.network.protocol.common.ServerboundPongPacket
+ net.minecraft.network.protocol.common.ServerboundResourcePackPacket
- net.minecraft.network.protocol.common.ServerboundResourcePackPacket$Action
- net.minecraft.network.protocol.common.ServerCommonPacketListener
+ net.minecraft.network.protocol.configuration.ClientboundFinishConfigurationPacket
- net.minecraft.network.protocol.configuration.ClientboundRegistryDataPacket
+ net.minecraft.network.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
- net.minecraft.network.protocol.configuration.ClientConfigurationPacketListener
- net.minecraft.network.protocol.configuration.package-info
+ net.minecraft.network.protocol.configuration.ServerboundFinishConfigurationPacket
- net.minecraft.network.protocol.configuration.ServerConfigurationPacketListener
- net.minecraft.network.protocol.game.ClientboundAddEntityPacket
+ net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
- net.minecraft.network.protocol.game.ClientboundAnimatePacket
+ net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
- net.minecraft.network.protocol.game.ClientboundBlockChangedAckPacket
+ net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
- net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEventPacket
- net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$OperationType
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ net.minecraft.network.protocol.game.ClientboundBundlePacket
- net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ClientboundChunkBatchFinishedPacket
- net.minecraft.network.protocol.game.ClientboundChunkBatchStartPacket
+ net.minecraft.network.protocol.game.ClientboundChunksBiomesPacket
- net.minecraft.network.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
+ net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
+ net.minecraft.network.protocol.game.ClientboundContainerClosePacket
- net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
+ net.minecraft.network.protocol.game.ClientboundCooldownPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
- net.minecraft.network.protocol.game.ClientboundDamageEventPacket
+ net.minecraft.network.protocol.game.ClientboundDeleteChatPacket
- net.minecraft.network.protocol.game.ClientboundDisguisedChatPacket
+ net.minecraft.network.protocol.game.ClientboundEntityEventPacket
- net.minecraft.network.protocol.game.ClientboundExplodePacket
+ net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
- net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
+ net.minecraft.network.protocol.game.ClientboundHurtAnimationPacket
- net.minecraft.network.protocol.game.ClientboundInitializeBorderPacket
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
- net.minecraft.network.protocol.game.ClientboundLevelChunkWithLightPacket
+ net.minecraft.network.protocol.game.ClientboundLevelEventPacket
- net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
+ net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacketData
+ net.minecraft.network.protocol.game.ClientboundLoginPacket
- net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
+ net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
- net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ClientboundOpenBookPacket
- net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
+ net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
- net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ClientboundPlayerChatPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatEndPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatEnterPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatKillPacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoRemovePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
+ net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
+ net.minecraft.network.protocol.game.ClientboundRecipePacket
- net.minecraft.network.protocol.game.ClientboundRecipePacket$State
+ net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
- net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundRespawnPacket
- net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
+ net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
+ net.minecraft.network.protocol.game.ClientboundServerDataPacket
- net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderSizePacket
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderWarningDistancePacket
- net.minecraft.network.protocol.game.ClientboundSetCameraPacket
+ net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
- net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
+ net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
- net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
+ net.minecraft.network.protocol.game.ClientboundSetHealthPacket
- net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Action
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
+ net.minecraft.network.protocol.game.ClientboundSetScorePacket
- net.minecraft.network.protocol.game.ClientboundSetSimulationDistancePacket
+ net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
- net.minecraft.network.protocol.game.ClientboundSetTimePacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
- net.minecraft.network.protocol.game.ClientboundSoundPacket
+ net.minecraft.network.protocol.game.ClientboundStartConfigurationPacket
- net.minecraft.network.protocol.game.ClientboundStopSoundPacket
+ net.minecraft.network.protocol.game.ClientboundSystemChatPacket
- net.minecraft.network.protocol.game.ClientboundTabListPacket
+ net.minecraft.network.protocol.game.ClientboundTagQueryPacket
- net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
+ net.minecraft.network.protocol.game.ClientGamePacketListener
+ net.minecraft.network.protocol.game.CommonPlayerSpawnInfo
- net.minecraft.network.protocol.game.DebugEntityNameGenerator
+ net.minecraft.network.protocol.game.DebugPackets
+ net.minecraft.network.protocol.game.package-info
+ net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
- net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundChatAckPacket
+ net.minecraft.network.protocol.game.ServerboundChatCommandPacket
- net.minecraft.network.protocol.game.ServerboundChatPacket
+ net.minecraft.network.protocol.game.ServerboundChatSessionUpdatePacket
- net.minecraft.network.protocol.game.ServerboundChunkBatchReceivedPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
- net.minecraft.network.protocol.game.ServerboundConfigurationAcknowledgedPacket
+ net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClosePacket
- net.minecraft.network.protocol.game.ServerboundEditBookPacket
+ net.minecraft.network.protocol.game.ServerboundEntityTagQuery
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
- net.minecraft.network.protocol.game.ServerGamePacketListener
+ net.minecraft.network.protocol.game.ServerPacketListener
- net.minecraft.network.protocol.game.ServerPingPacketListener
- net.minecraft.network.protocol.game.VecDeltaCodec
- net.minecraft.network.protocol.handshake.ClientIntent
+ net.minecraft.network.protocol.handshake.ClientIntent$1
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
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
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryAnswerPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerboundLoginAcknowledgedPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
- net.minecraft.network.protocol.Packet
+ net.minecraft.network.protocol.PacketFlow
- net.minecraft.network.protocol.PacketUtils
- net.minecraft.network.protocol.status.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
+ net.minecraft.network.protocol.status.ServerboundPingRequestPacket
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
- net.minecraft.network.protocol.status.ServerStatus
+ net.minecraft.network.protocol.status.ServerStatus$Favicon
- net.minecraft.network.protocol.status.ServerStatus$Players
+ net.minecraft.network.protocol.status.ServerStatus$Version
- net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializer$1
+ net.minecraft.network.syncher.EntityDataSerializer$ForValueType
- net.minecraft.network.syncher.EntityDataSerializers
+ net.minecraft.network.syncher.EntityDataSerializers$1
- net.minecraft.network.syncher.EntityDataSerializers$2
+ net.minecraft.network.syncher.EntityDataSerializers$3
- net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.EntityDataSerializers$5
- net.minecraft.network.syncher.EntityDataSerializers$6
+ net.minecraft.network.syncher.EntityDataSerializers$7
+ net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.network.syncher.SynchedEntityData$DataValue
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
- net.minecraft.references.Items
+ net.minecraft.resources.DelegatingOps
- net.minecraft.resources.FileToIdConverter
+ net.minecraft.resources.HolderSetCodec
- net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataLoader
+ net.minecraft.resources.RegistryDataLoader$1
- net.minecraft.resources.RegistryDataLoader$Loader
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
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator$Output
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
- net.minecraft.server.advancements.package-info
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$Entry
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
+ net.minecraft.server.commands.DataPackCommand
- net.minecraft.server.commands.DataPackCommand$Inserter
- net.minecraft.server.commands.DebugCommand
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
+ net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
- net.minecraft.server.commands.ExecuteCommand$CommandPredicate
+ net.minecraft.server.commands.ExperienceCommand
- net.minecraft.server.commands.ExperienceCommand$Type
+ net.minecraft.server.commands.FillBiomeCommand
- net.minecraft.server.commands.FillCommand
+ net.minecraft.server.commands.FillCommand$Mode
- net.minecraft.server.commands.ForceLoadCommand
+ net.minecraft.server.commands.FunctionCommand
- net.minecraft.server.commands.FunctionCommand$FunctionResult
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
- net.minecraft.server.commands.package-info
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
+ net.minecraft.server.commands.RideCommand
- net.minecraft.server.commands.SaveAllCommand
+ net.minecraft.server.commands.SaveOffCommand
- net.minecraft.server.commands.SaveOnCommand
+ net.minecraft.server.commands.SayCommand
- net.minecraft.server.commands.ScheduleCommand
+ net.minecraft.server.commands.ScoreboardCommand
- net.minecraft.server.commands.SeedCommand
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
- net.minecraft.server.commands.TimeCommand
+ net.minecraft.server.commands.TitleCommand
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
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$ExecutionContext
- net.minecraft.server.ServerFunctionManager$ExecutionContext$AbortingReturnValueConsumer
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerFunctionManager$TraceCallbacks
+ net.minecraft.server.ServerInfo
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
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
- net.minecraft.util.datafix.ComponentDataFixUtils
- net.minecraft.util.ExtraCodecs$EitherCodec
+ net.minecraft.util.ExtraCodecs$RecursiveCodec
- net.minecraft.util.ExtraCodecs$StrictOptionalFieldCodec
+ net.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
- net.minecraft.util.ExtraCodecs$TagOrElementLocation
+ net.minecraft.util.ExtraCodecs$XorCodec
- net.minecraft.util.FastBufferedInputStream
+ net.minecraft.util.FastColor
- net.minecraft.util.FastColor$ABGR32
+ net.minecraft.util.FastColor$ARGB32
- net.minecraft.util.FileZipper
+ net.minecraft.util.FormattedCharSequence
- net.minecraft.util.FormattedCharSink
+ net.minecraft.util.FutureChain
- net.minecraft.util.Graph
+ net.minecraft.util.GsonHelper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.InclusiveRange
- net.minecraft.util.JavaOps
- net.minecraft.util.JavaOps$FixedMapBuilder
- net.minecraft.util.StringUtil
+ net.minecraft.util.TaskChainer
- net.minecraft.util.TaskChainer$DelayedTask
+ net.minecraft.util.ThreadingDetector
- net.minecraft.util.TimeSource
+ net.minecraft.util.TimeSource$NanoTimeSource
- net.minecraft.util.TimeUtil
+ net.minecraft.util.ToFloatFunction
- net.minecraft.util.ToFloatFunction$1
+ net.minecraft.util.ToFloatFunction$2
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.ZeroBitStorage
+ net.minecraft.Util$IdentityStrategy
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
- net.minecraft.world.level.block.BaseTorchBlock
+ net.minecraft.world.level.block.BeaconBeamBlock
- net.minecraft.world.level.block.BeaconBlock
+ net.minecraft.world.level.block.BedBlock
- net.minecraft.world.level.block.BedBlock$1
+ net.minecraft.world.level.block.BeehiveBlock
- net.minecraft.world.level.block.BeetrootBlock
+ net.minecraft.world.level.block.BellBlock
- net.minecraft.world.level.block.BellBlock$1
+ net.minecraft.world.level.block.BigDripleafBlock
- net.minecraft.world.level.block.BigDripleafStemBlock
+ net.minecraft.world.level.block.BigDripleafStemBlock$1
- net.minecraft.world.level.block.BlastFurnaceBlock
+ net.minecraft.world.level.block.Block
- net.minecraft.world.level.block.Block$1
+ net.minecraft.world.level.block.Block$2
- net.minecraft.world.level.block.Block$BlockStatePairKey
- net.minecraft.world.level.block.CommandBlock
+ net.minecraft.world.level.block.ComparatorBlock
- net.minecraft.world.level.block.ComposterBlock
+ net.minecraft.world.level.block.ComposterBlock$EmptyContainer
- net.minecraft.world.level.block.ComposterBlock$InputContainer
+ net.minecraft.world.level.block.ComposterBlock$OutputContainer
- net.minecraft.world.level.block.ConcretePowderBlock
+ net.minecraft.world.level.block.ConduitBlock
- net.minecraft.world.level.block.CoralBlock
+ net.minecraft.world.level.block.CoralFanBlock
- net.minecraft.world.level.block.CoralPlantBlock
+ net.minecraft.world.level.block.CoralWallFanBlock
- net.minecraft.world.level.block.CraftingTableBlock
+ net.minecraft.world.level.block.CropBlock
- net.minecraft.world.level.block.CrossCollisionBlock
+ net.minecraft.world.level.block.CrossCollisionBlock$1
- net.minecraft.world.level.block.CryingObsidianBlock
+ net.minecraft.world.level.block.DaylightDetectorBlock
- net.minecraft.world.level.block.DeadBushBlock
+ net.minecraft.world.level.block.DecoratedPotBlock
- net.minecraft.world.level.block.DetectorRailBlock
+ net.minecraft.world.level.block.DetectorRailBlock$1
- net.minecraft.world.level.block.DiodeBlock
+ net.minecraft.world.level.block.DirectionalBlock
- net.minecraft.world.level.block.DirtPathBlock
+ net.minecraft.world.level.block.DispenserBlock
- net.minecraft.world.level.block.DoorBlock
+ net.minecraft.world.level.block.DoorBlock$1
- net.minecraft.world.level.block.DoubleBlockCombiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
- net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- net.minecraft.world.level.block.DoublePlantBlock
+ net.minecraft.world.level.block.DragonEggBlock
- net.minecraft.world.level.block.DropExperienceBlock
+ net.minecraft.world.level.block.DropperBlock
- net.minecraft.world.level.block.EnchantmentTableBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
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
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DecoratedPotBlockEntity
- net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$Decorations
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
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.EquipableCarvedPumpkinBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
- net.minecraft.world.level.block.Fallable
+ net.minecraft.world.level.block.FallingBlock
- net.minecraft.world.level.block.FarmBlock
+ net.minecraft.world.level.block.FenceBlock
- net.minecraft.world.level.block.FenceGateBlock
+ net.minecraft.world.level.block.FenceGateBlock$1
- net.minecraft.world.level.block.FireBlock
+ net.minecraft.world.level.block.FletchingTableBlock
- net.minecraft.world.level.block.FlowerBlock
+ net.minecraft.world.level.block.FlowerPotBlock
- net.minecraft.world.level.block.FrogspawnBlock
+ net.minecraft.world.level.block.FrostedIceBlock
- net.minecraft.world.level.block.FungusBlock
+ net.minecraft.world.level.block.FurnaceBlock
- net.minecraft.world.level.block.GameMasterBlock
+ net.minecraft.world.level.block.GlassBlock
- net.minecraft.world.level.block.GlazedTerracottaBlock
+ net.minecraft.world.level.block.GlowLichenBlock
- net.minecraft.world.level.block.GrassBlock
+ net.minecraft.world.level.block.GravelBlock
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.MangroveTreeGrower
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.grower.TreeGrower
+ net.minecraft.world.level.block.MelonBlock
- net.minecraft.world.level.block.Mirror
+ net.minecraft.world.level.block.Mirror$1
- net.minecraft.world.level.block.MossBlock
+ net.minecraft.world.level.block.MudBlock
- net.minecraft.world.level.block.MultifaceBlock
+ net.minecraft.world.level.block.MultifaceSpreader
- net.minecraft.world.level.block.MultifaceSpreader$DefaultSpreaderConfig
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadConfig
- net.minecraft.world.level.block.MultifaceSpreader$SpreadPos
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadPredicate
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType$1
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$2
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType$3
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
+ net.minecraft.world.level.block.PiglinWallSkullBlock
- net.minecraft.world.level.block.PinkPetalsBlock
+ net.minecraft.world.level.block.PipeBlock
- net.minecraft.world.level.block.PitcherCropBlock
+ net.minecraft.world.level.block.PitcherCropBlock$PosAndState
- net.minecraft.world.level.block.PlayerHeadBlock
+ net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PointedDripstoneBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock$FluidInfo
- net.minecraft.world.level.block.PotatoBlock
+ net.minecraft.world.level.block.PowderSnowBlock
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
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
+ net.minecraft.world.level.block.SupportType$1
- net.minecraft.world.level.block.SupportType$2
+ net.minecraft.world.level.block.SupportType$3
- net.minecraft.world.level.block.SuspiciousEffectHolder
+ net.minecraft.world.level.block.SuspiciousEffectHolder$EffectEntry
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TintedGlassBlock
- net.minecraft.world.level.block.TntBlock
+ net.minecraft.world.level.block.TorchBlock
- net.minecraft.world.level.block.TorchflowerCropBlock
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
- net.minecraft.world.level.block.WallHangingSignBlock
+ net.minecraft.world.level.block.WallHangingSignBlock$1
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
+ net.minecraft.world.level.block.WoolCarpetBlock
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
- net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.SectionStorage
+ net.minecraft.world.level.chunk.StructureAccess
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
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
+ net.minecraft.world.level.gameevent.GameEventListener$Holder
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
- net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
- net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.package-info
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
- net.minecraft.world.level.levelgen.structure.StructureSet
+ net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- net.minecraft.world.level.levelgen.structure.StructureStart
+ net.minecraft.world.level.levelgen.structure.StructureType
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
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
- net.minecraft.world.level.levelgen.synth.BlendedNoise
+ net.minecraft.world.level.levelgen.synth.ImprovedNoise
- net.minecraft.world.level.levelgen.synth.NoiseUtils
+ net.minecraft.world.level.levelgen.synth.NormalNoise
- net.minecraft.world.level.levelgen.synth.NormalNoise$NoiseParameters
- net.minecraft.world.level.levelgen.synth.package-info
+ net.minecraft.world.level.levelgen.synth.PerlinNoise
- net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
+ net.minecraft.world.level.levelgen.synth.SimplexNoise
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
+ net.minecraft.world.level.pathfinder.package-info
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.Path$DebugData
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
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
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
+ net.minecraft.world.level.saveddata.maps.package-info
- net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.saveddata.SavedData$Factory
+ net.minecraft.world.level.storage.CommandStorage
- net.minecraft.world.level.storage.CommandStorage$Container
+ net.minecraft.world.level.storage.DataVersion
- net.minecraft.world.level.storage.DerivedLevelData
+ net.minecraft.world.level.storage.DimensionDataStorage
- net.minecraft.world.level.storage.LevelData
+ net.minecraft.world.level.storage.LevelResource
- net.minecraft.world.level.storage.LevelStorageException
+ net.minecraft.world.level.storage.LevelStorageSource
- net.minecraft.world.level.storage.LevelStorageSource$LevelCandidates
+ net.minecraft.world.level.storage.LevelStorageSource$LevelDirectory
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
+ net.minecraft.world.level.storage.LevelSummary
- net.minecraft.world.level.storage.LevelSummary$BackupStatus
+ net.minecraft.world.level.storage.LevelSummary$SymlinkLevelSummary
- net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.loot.BuiltInLootTables
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
- net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem
+ net.minecraft.world.level.storage.loot.entries.EntryGroup
- net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
+ net.minecraft.world.level.storage.loot.entries.LootItem
- net.minecraft.world.level.storage.loot.entries.LootPoolEntries
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntry
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ net.minecraft.world.level.storage.loot.entries.LootTableReference
- net.minecraft.world.level.storage.loot.entries.package-info
- net.minecraft.world.level.storage.loot.entries.SequentialEntry
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
- net.minecraft.world.level.storage.loot.entries.TagEntry
+ net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaType
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Path
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FunctionReference
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SequenceFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction
+ net.minecraft.world.level.storage.loot.functions.SetPotionFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$EffectEntry
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.IntRange
+ net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
+ net.minecraft.world.level.storage.loot.LootContext
- net.minecraft.world.level.storage.loot.LootContext$Builder
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget
- net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
+ net.minecraft.world.level.storage.loot.LootContextUser
- net.minecraft.world.level.storage.loot.LootDataId
+ net.minecraft.world.level.storage.loot.LootDataManager
- net.minecraft.world.level.storage.loot.LootDataManager$1
+ net.minecraft.world.level.storage.loot.LootDataResolver
- net.minecraft.world.level.storage.loot.LootDataType
+ net.minecraft.world.level.storage.loot.LootDataType$Validator
- net.minecraft.world.level.storage.loot.LootParams
+ net.minecraft.world.level.storage.loot.LootParams$Builder
- net.minecraft.world.level.storage.loot.LootParams$DynamicDrop
+ net.minecraft.world.level.storage.loot.LootPool
- net.minecraft.world.level.storage.loot.LootPool$Builder
+ net.minecraft.world.level.storage.loot.LootTable
- net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition
+ net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition
+ net.minecraft.world.level.storage.loot.predicates.AnyOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
- net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LocationCheck
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
+ net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
- net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue
+ net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
- net.minecraft.world.level.storage.loot.providers.number.NumberProvider
+ net.minecraft.world.level.storage.loot.providers.number.NumberProviders
- net.minecraft.world.level.storage.loot.providers.number.package-info
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
+ net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
+ net.minecraft.world.level.storage.PrimaryLevelData$SpecialWorldProperty
- net.minecraft.world.level.storage.ServerLevelData
+ net.minecraft.world.level.storage.WorldData
- net.minecraft.world.level.storage.WritableLevelData
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
+ net.minecraft.world.level.timers.package-info
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.level.timers.TimerQueue$Event
- net.minecraft.world.level.validation.ContentValidationException
+ net.minecraft.world.level.validation.DirectoryValidator
- net.minecraft.world.level.validation.DirectoryValidator$1
+ net.minecraft.world.level.validation.ForbiddenSymlinkInfo
+ net.minecraft.world.level.validation.package-info
- net.minecraft.world.level.validation.PathAllowList
+ net.minecraft.world.level.validation.PathAllowList$ConfigEntry
- net.minecraft.world.level.validation.PathAllowList$EntryType
- net.minecraft.world.package-info
+ net.minecraft.world.phys.AABB
- net.minecraft.world.phys.BlockHitResult
+ net.minecraft.world.phys.EntityHitResult
- net.minecraft.world.phys.HitResult
+ net.minecraft.world.phys.HitResult$Type
- net.minecraft.world.phys.package-info
+ net.minecraft.world.phys.shapes.ArrayVoxelShape
- net.minecraft.world.phys.shapes.ArrayVoxelShape$1
+ net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
- net.minecraft.world.phys.shapes.BooleanOp
+ net.minecraft.world.phys.shapes.CollisionContext
- net.minecraft.world.phys.shapes.CubePointRange
+ net.minecraft.world.phys.shapes.CubeVoxelShape
- net.minecraft.world.phys.shapes.DiscreteCubeMerger
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- net.minecraft.world.phys.shapes.EntityCollisionContext
+ net.minecraft.world.phys.shapes.EntityCollisionContext$1
- net.minecraft.world.phys.shapes.IdenticalMerger
+ net.minecraft.world.phys.shapes.IndexMerger
- net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
+ net.minecraft.world.phys.shapes.IndirectMerger
- net.minecraft.world.phys.shapes.NonOverlappingMerger
+ net.minecraft.world.phys.shapes.OffsetDoubleList
+ net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.shapes.Shapes
+ net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
- net.minecraft.world.phys.shapes.SliceShape
+ net.minecraft.world.phys.shapes.SubShape
- net.minecraft.world.phys.shapes.VoxelShape
- net.minecraft.world.phys.Vec2
+ net.minecraft.world.phys.Vec3
- net.minecraft.world.scores.criteria.ObjectiveCriteria
+ net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
- net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.DisplaySlot
+ net.minecraft.world.scores.DisplaySlot$1
- net.minecraft.world.scores.Objective
+ net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.Score
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.Team
- net.minecraft.world.scores.Team$CollisionRule
+ net.minecraft.world.scores.Team$Visibility
- net.minecraft.world.ticks.BlackholeTickAccess
+ net.minecraft.world.ticks.BlackholeTickAccess$1
- net.minecraft.world.ticks.BlackholeTickAccess$2
+ net.minecraft.world.ticks.ContainerSingleItem
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
+ net.minecraft.WorldVersion
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.platform.MacosUtil +6M -3M | +1P
```
```
XXX.realmsclient.dto.RealmsText +3M -1M | +1P -1P
```
```
XXX.realmsclient.util.WorldGenerationInfo +6M -3M
```
```
net.minecraft.Util +1M -2M | +1P
```
```
XXX.gui.screens.GenericDirtMessageScreen +1M
```
```
XXX.gui.screens.ReceivingLevelScreen +1M -2M | +1P -2P
```
```
XXX.screens.worldselection.OptimizeWorldScreen +1M -1M | +1P -1P
```
```
XXX.client.model.HumanoidModel +1M | +2P
```
```
XXX.core.registries.BuiltInRegistries +1P
```
```
XXX.core.registries.Registries +1P
```
```
XXX.gametest.framework.GameTestHelper +2M
```
```
XXX.gametest.framework.GameTestInfo +2M | +1P
```
```
XXX.gametest.framework.TestCommand +10M -9M
```
```
XXX.minecraft.network.FriendlyByteBuf +1M
```
```
XXX.network.chat.ClickEvent +4M | +1P
```
```
XXX.network.chat.Component$Serializer +3M -12M
```
```
XXX.network.chat.Style$Serializer +12M -10M | +2P
```
```
XXX.network.chat.TextColor +6M -5M
```
```
XXX.chat.contents.BlockDataSource +3M | +2P
```
```
XXX.chat.contents.NbtContents +8M -6M | +2P
```
```
XXX.minecraft.util.ExtraCodecs$4 +5M -3M | +2P -1P
```
```
XXX.minecraft.util.StringRepresentable +7M -4M
```
```
XXX.minecraft.util.StringRepresentable$EnumCodec +1M -6M | -1P
```
```
XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix -1M | -1P
```
```
XXX.datafix.fixes.DropInvalidSignDataFix -1P
```
```
XXX.datafix.fixes.TeamDisplayNameFix +3M -5M
```
```
XXX.util.worldupdate.WorldUpgrader +1P -1P
```
```
XXX.entity.animal.Turtle -1M
```
```
XXX.entity.animal.WaterAnimal -1M
```
```
XXX.animal.frog.Frog -1M
```
```
XXX.world.item.ArmorMaterials +1P -1P
```
```
XXX.level.biome.FeatureSorter$StepFeatureData -1M
```
```
XXX.level.block.AbstractBannerBlock +1M -1M | +1P
```
```
XXX.level.block.AbstractCauldronBlock +1M -1M | +2P -1P
```
```
XXX.level.block.AbstractFurnaceBlock +1P
```
```
XXX.level.block.AbstractSkullBlock +1P
```
```
XXX.level.block.AmethystBlock +2M | +1P
```
```
XXX.level.block.AttachedStemBlock +7M -2M | +4P -2P
```
```
XXX.level.block.BambooSaplingBlock +2M -1M | +1P
```
```
XXX.level.block.BannerBlock +2M | +1P
```
```
XXX.level.block.BarrierBlock +1M | +1P
```
```
XXX.level.block.BaseCoralPlantBlock +1M | +1P
```
```
XXX.level.block.BaseCoralWallFanBlock +1M | +1P
```
```
XXX.level.block.BaseFireBlock +1M -1M | +1P
```
```
XXX.level.block.BaseRailBlock +1P
```
```
XXX.level.block.Blocks +28M -31M | +1P
```
```
XXX.level.block.BrewingStandBlock +1M | +1P
```
```
XXX.level.block.BubbleColumnBlock +1M | +1P
```
```
XXX.level.block.BuddingAmethystBlock +1M | +1P
```
```
XXX.level.block.ButtonBlock +5M -1M | +1P -1P
```
```
XXX.level.block.CactusBlock +1M | +1P
```
```
XXX.level.block.CalibratedSculkSensorBlock +1M | +1P
```
```
XXX.level.block.CandleBlock +1M | +1P
```
```
XXX.level.block.CarpetBlock +1M | +1P
```
```
XXX.level.block.CartographyTableBlock +1M | +1P
```
```
XXX.level.block.CauldronBlock +2M | +1P
```
```
XXX.level.block.CaveVinesBlock +3M -1M | +1P
```
```
XXX.level.block.CeilingHangingSignBlock +3M -1M | +1P
```
```
XXX.level.block.CherryLeavesBlock +2M | +1P
```
```
XXX.level.block.ChorusPlantBlock +3M -1M | +1P
```
```
XXX.level.block.GrowingPlantBodyBlock +1M -1M | +1P
```
```
XXX.level.block.HalfTransparentBlock +2M | +1P
```
```
XXX.level.block.HayBlock +2M | +1P
```
```
XXX.level.block.HopperBlock +1M | +1P
```
```
XXX.level.block.HorizontalDirectionalBlock +1P
```
```
XXX.level.block.IceBlock +2M | +1P
```
```
XXX.level.block.InfestedRotatedPillarBlock +3M | +1P
```
```
XXX.level.block.JigsawBlock +1M | +1P
```
```
XXX.level.block.KelpBlock +1M | +1P
```
```
XXX.level.block.LadderBlock +1M | +1P
```
```
XXX.level.block.LanternBlock +1M | +1P
```
```
XXX.level.block.LayeredCauldronBlock +5M -3M | +2P -3P
```
```
XXX.level.block.LecternBlock +1M | +1P
```
```
XXX.level.block.LightningRodBlock +1M | +1P
```
```
XXX.level.block.MagmaBlock +2M | +1P
```
```
XXX.level.block.MangrovePropaguleBlock +4M -1M | +1P -1P
```
```
XXX.level.block.PoweredBlock +2M | +1P
```
```
XXX.level.block.PressurePlateBlock$1 +1P -1P
```
```
XXX.level.block.ScaffoldingBlock +1M | +1P
```
```
XXX.level.block.SculkCatalystBlock +1M | +1P
```
```
XXX.level.block.SculkShriekerBlock +1M | +1P
```
```
XXX.level.block.SeagrassBlock +1M | +1P
```
```
XXX.level.block.SkullBlock$Type +1M | +2P
```
```
XXX.level.block.SlabBlock +1M | +1P
```
```
XXX.level.block.SlimeBlock +2M | +1P
```
```
XXX.level.block.SmithingTableBlock +1M | +1P
```
```
XXX.level.block.SnifferEggBlock +1M | +1P
```
```
XXX.level.block.SoulFireBlock +2M | +1P
```
```
XXX.level.block.SpongeBlock +1M | +1P
```
```
XXX.level.block.SpreadingSnowyDirtBlock +1P
```
```
XXX.level.block.StainedGlassPaneBlock +3M | +1P
```
```
XXX.level.block.StemBlock +7M -3M | +4P -2P
```
```
XXX.block.piston.PistonBaseBlock +3M | +1P
```
```
XXX.block.piston.PistonHeadBlock +3M -2M | +1P
```
```
XXX.block.state.BlockBehaviour +4M | +1P
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +1M
```
```
XXX.block.state.BlockBehaviour$Properties +9M -7M | +1P
```

</details>
































<details>
<summary>
com.mojang.blaze3d.platform.MacosUtil
</summary>

```diff
+ boolean isInKioskMode(NSObject)
- boolean isInNativeFullscreen(NSObject)
- long getStyleMask(NSObject)
- void clearResizableBit(long)
- void exitNativeFullscreen(long)
- void lambda$clearResizableBit$0(NSObject)
+ void toggleFullscreen(long)
+ void toggleFullscreen(NSObject)
- void toggleNativeFullscreen(NSObject)
```

</details>







































































<details>
<summary>
com.mojang.realmsclient.dto.RealmsText
</summary>

```diff
- Component createComponent()
- String toString()
+ void <init>(String,Object[])
- void <init>(String,String[])
```

</details>





















































<details>
<summary>
com.mojang.realmsclient.util.WorldGenerationInfo
</summary>

```diff
- boolean equals(Object)
- boolean generateStructures()
+ boolean shouldGenerateStructures()
- int hashCode()
+ LevelType getLevelType()
- LevelType levelType()
+ String getSeed()
- String seed()
- String toString()
```

</details>

















<details>
<summary>
net.minecraft.Util
</summary>

```diff
+ Hash$Strategy identityStrategy()
- ToIntFunction createIndexIdentityLookup(List)
+ ToIntFunction createIndexLookup(List,IntFunction)
```

</details>

























































































<details>
<summary>
net.minecraft.client.gui.screens.GenericDirtMessageScreen
</summary>

```diff
- boolean shouldNarrateNavigation()
```

</details>











<details>
<summary>
net.minecraft.client.gui.screens.ReceivingLevelScreen
</summary>

```diff
+ void <init>()
- void <init>(BooleanSupplier)
+ void loadingPacketsReceived()
```

</details>














































































































<details>
<summary>
net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen
</summary>

```diff
+ void lambda$static$0(Object2IntOpenCustomHashMap)
- void lambda$static$0(Reference2IntOpenHashMap)
```

</details>












































<details>
<summary>
net.minecraft.client.model.HumanoidModel
</summary>

```diff
- void poseBlockingArm(ModelPart,boolean)
```

</details>











































































































































































































<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- void assertItemEntityNotPresent(Item)
- void assertItemEntityPresent(Item)
```

</details>

<details>
<summary>
net.minecraft.gametest.framework.GameTestInfo
</summary>

```diff
- boolean rerunUntilFailed()
- void setRerunUntilFailed(boolean)
```

</details>









<details>
<summary>
net.minecraft.gametest.framework.TestCommand
</summary>

```diff
+ boolean lambda$say$29(ServerPlayer)
- boolean lambda$say$30(ServerPlayer)
+ Component lambda$say$28(String)
- Component lambda$say$29(String)
+ Component lambda$showPos$25(String,Component)
- Component lambda$showPos$26(String,Component)
- int lambda$register$25(CommandContext)
- int runAllNearbyTests(CommandSourceStack,boolean)
+ int runAllNearbyTests(CommandSourceStack)
- int runNearbyTest(CommandSourceStack,boolean)
+ int runNearbyTest(CommandSourceStack)
+ void lambda$runAllNearbyTests$26(ServerLevel,MultipleTestTracker,BlockPos)
- void lambda$runAllNearbyTests$27(ServerLevel,MultipleTestTracker,boolean,BlockPos)
+ void lambda$runTests$27(GameTestInfo)
- void lambda$runTests$28(GameTestInfo)
+ void lambda$say$30(ChatFormatting,String,ServerPlayer)
- void lambda$say$31(ChatFormatting,String,ServerPlayer)
- void runTest(ServerLevel,BlockPos,MultipleTestTracker,boolean)
+ void runTest(ServerLevel,BlockPos,MultipleTestTracker)
```

</details>
















































<details>
<summary>
net.minecraft.network.FriendlyByteBuf
</summary>

```diff
- Component readComponentTrusted()
```

</details>














<details>
<summary>
net.minecraft.network.chat.ClickEvent
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- ClickEvent$Action lambda$static$0(ClickEvent)
- String lambda$static$1(ClickEvent)
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.network.chat.Component$Serializer
</summary>

```diff
- Field lambda$static$0()
+ Field lambda$static$2()
+ Gson lambda$static$0()
+ JsonElement serialize(Component,Type,JsonSerializationContext)
- JsonElement serialize(Component)
+ JsonElement serialize(Object,Type,JsonSerializationContext)
+ MutableComponent deserialize(JsonElement,Type,JsonDeserializationContext)
- MutableComponent deserialize(JsonElement)
+ Object deserialize(JsonElement,Type,JsonDeserializationContext)
+ Object unwrapTextArgument(Object)
+ Optional parseSeparator(Type,JsonDeserializationContext,JsonObject)
+ String toStableJson(Component)
+ void lambda$serializeSeparator$3(JsonObject,JsonSerializationContext,Component)
+ void serializeSeparator(JsonSerializationContext,JsonObject,Optional)
+ void serializeStyle(Style,JsonObject,JsonSerializationContext)
```

</details>
















<details>
<summary>
net.minecraft.network.chat.Style$Serializer
</summary>

```diff
- App lambda$static$10(RecordCodecBuilder$Instance)
+ Boolean getOptionalFlag(JsonObject,String)
+ ClickEvent getClickEvent(JsonObject)
+ HoverEvent getHoverEvent(JsonObject)
+ JsonElement serialize(Object,Type,JsonSerializationContext)
+ JsonElement serialize(Style,Type,JsonSerializationContext)
+ Object deserialize(JsonElement,Type,JsonDeserializationContext)
- Optional lambda$static$0(Style)
- Optional lambda$static$1(Style)
- Optional lambda$static$2(Style)
- Optional lambda$static$3(Style)
- Optional lambda$static$4(Style)
- Optional lambda$static$5(Style)
- Optional lambda$static$6(Style)
- Optional lambda$static$7(Style)
- Optional lambda$static$8(Style)
- Optional lambda$static$9(Style)
+ ResourceLocation getFont(JsonObject)
+ String getInsertion(JsonObject)
+ Style deserialize(JsonElement,Type,JsonDeserializationContext)
+ TextColor getTextColor(JsonObject)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.network.chat.TextColor
</summary>

```diff
+ DataResult lambda$static$1(String)
- DataResult parseColor(String)
- String lambda$parseColor$2(String)
- String lambda$parseColor$3(String)
- String lambda$parseColor$4(String)
+ String lambda$static$0()
- String lambda$static$1(TextColor)
+ String lambda$static$3(TextColor)
- TextColor lambda$static$0(ChatFormatting)
+ TextColor lambda$static$2(ChatFormatting)
+ TextColor parseColor(String)
```

</details>
<details>
<summary>
net.minecraft.network.chat.contents.BlockDataSource
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- DataSource$Type type()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.network.chat.contents.NbtContents
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- ComponentContents$Type type()
+ MutableComponent lambda$resolve$2(Component,MutableComponent,MutableComponent)
- MutableComponent lambda$resolve$3(Component,MutableComponent,MutableComponent)
+ MutableComponent lambda$resolve$3(MutableComponent,MutableComponent,MutableComponent)
- MutableComponent lambda$resolve$4(MutableComponent,MutableComponent,MutableComponent)
+ MutableComponent lambda$resolve$4(Stream,MutableComponent)
- MutableComponent lambda$resolve$5(Stream,MutableComponent)
+ MutableComponent lambda$resolve$5(Stream)
- MutableComponent lambda$resolve$6(Stream)
+ Stream lambda$resolve$0(CompoundTag)
+ Stream lambda$resolve$1(CommandSourceStack,Entity,int,String)
- Stream lambda$resolve$1(CompoundTag)
- Stream lambda$resolve$2(CommandSourceStack,Entity,int,String)
```

</details>














<details>
<summary>
net.minecraft.util.ExtraCodecs$4
</summary>

```diff
- DataResult apply(DynamicOps,Object,DataResult)
- DataResult coApply(DynamicOps,Object,DataResult)
+ DataResult decode(DynamicOps,Object)
- DataResult lambda$apply$0(DataResult,Function,Pair)
+ String lambda$decode$0(Object,Exception)
- String toString()
+ void <init>(Codec)
- void <init>(Function,Function)
```

</details>
















<details>
<summary>
net.minecraft.util.StringRepresentable
</summary>

```diff
- Codec fromValues(Supplier)
+ Enum lambda$fromEnumWithMapping$2(Enum)
+ Enum lambda$fromEnumWithMapping$3(Map,String)
+ Enum lambda$fromEnumWithMapping$4(Enum[],Function,String)
- Function createNameLookup(StringRepresentable[],Function)
- String lambda$createNameLookup$2(Function,StringRepresentable)
+ String lambda$fromEnumWithMapping$1(Function,Enum)
- String lambda$fromValues$1(String)
- StringRepresentable lambda$createNameLookup$3(StringRepresentable)
- StringRepresentable lambda$createNameLookup$4(Map,String)
- StringRepresentable lambda$createNameLookup$5(StringRepresentable[],Function,String)
```

</details>
<details>
<summary>
net.minecraft.util.StringRepresentable$EnumCodec
</summary>

```diff
+ DataResult decode(DynamicOps,Object)
+ DataResult encode(Enum,DynamicOps,Object)
+ DataResult encode(Object,DynamicOps,Object)
+ Enum lambda$new$2(Enum[],int)
- int lambda$new$0(Object)
+ int lambda$new$1(Object)
+ String lambda$new$0(Object)
```

</details>













<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
</summary>

```diff
+ void <clinit>()
```

</details>
















































































<details>
<summary>
net.minecraft.util.datafix.fixes.TeamDisplayNameFix
</summary>

```diff
- Dynamic lambda$makeRule$0(Dynamic)
+ Dynamic lambda$makeRule$1(Dynamic,Dynamic)
+ Dynamic lambda$makeRule$2(Dynamic)
- Function lambda$makeRule$2(DynamicOps)
+ Function lambda$makeRule$4(DynamicOps)
- Pair lambda$makeRule$1(Pair)
+ Pair lambda$makeRule$3(Pair)
+ String lambda$makeRule$0(String)
```

</details>



















































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.animal.Turtle
</summary>

```diff
+ boolean canBreatheUnderwater()
```

</details>




<details>
<summary>
net.minecraft.world.entity.animal.WaterAnimal
</summary>

```diff
+ boolean canBreatheUnderwater()
```

</details>












<details>
<summary>
net.minecraft.world.entity.animal.frog.Frog
</summary>

```diff
+ boolean canBreatheUnderwater()
```

</details>


































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.biome.FeatureSorter$StepFeatureData
</summary>

```diff
+ Object2IntMap lambda$new$0(int)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.AbstractBannerBlock
</summary>

```diff
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractCauldronBlock
</summary>

```diff
- void <init>(BlockBehaviour$Properties,CauldronInteraction$InteractionMap)
+ void <init>(BlockBehaviour$Properties,Map)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.AmethystBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.AttachedStemBlock
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
- MapCodec codec()
- ResourceKey lambda$static$0(AttachedStemBlock)
- ResourceKey lambda$static$1(AttachedStemBlock)
- ResourceKey lambda$static$2(AttachedStemBlock)
- void <init>(ResourceKey,ResourceKey,ResourceKey,BlockBehaviour$Properties)
+ void <init>(StemGrownBlock,Supplier,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BambooSaplingBlock
</summary>

```diff
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BannerBlock
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BarrierBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseCoralPlantBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseCoralWallFanBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseFireBlock
</summary>

```diff
- BlockState playerWillDestroy(Level,BlockPos,BlockState,Player)
+ void playerWillDestroy(Level,BlockPos,BlockState,Player)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
+ BedBlock bed(DyeColor)
- Block bed(DyeColor)
- Block candle(MapColor)
- Block flowerPot(Block)
- Block leaves(SoundType)
- Block log(MapColor,MapColor,SoundType)
- Block log(MapColor,MapColor)
- Block pistonBase(boolean)
- Block register(ResourceKey,Block)
+ Block register(ResourceLocation,Block)
- Block shulkerBox(DyeColor,MapColor)
- Block stainedGlass(DyeColor)
- Block stair(Block)
- Block stoneButton()
- Block woodenButton(BlockSetType)
+ boolean lambda$shulkerBox$5(BlockState,BlockGetter,BlockPos)
- boolean lambda$static$0(BlockState,BlockGetter,BlockPos)
- boolean lambda$static$32(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$34(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$static$36(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$static$38(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$47(BlockState,BlockGetter,BlockPos)
+ boolean lambda$static$51(BlockState,BlockGetter,BlockPos)
+ ButtonBlock stoneButton()
+ ButtonBlock woodenButton(BlockSetType,FeatureFlag[])
+ CandleBlock candle(MapColor)
+ FlowerPotBlock flowerPot(Block,FeatureFlag[])
+ int lambda$litBlockEmission$0(int,BlockState)
- int lambda$litBlockEmission$1(int,BlockState)
- int lambda$static$21(BlockState)
- int lambda$static$22(BlockState)
- int lambda$static$23(BlockState)
- int lambda$static$24(BlockState)
+ int lambda$static$32(BlockState)
+ int lambda$static$34(BlockState)
- int lambda$static$36(BlockState)
- int lambda$static$38(BlockState)
+ int lambda$static$47(BlockState)
- int lambda$static$51(BlockState)
+ int lambda$static$52(BlockState)
+ int lambda$static$53(BlockState)
+ int lambda$static$54(BlockState)
+ int lambda$static$55(BlockState)
+ Item lambda$static$21()
+ Item lambda$static$22()
+ Item lambda$static$23()
+ Item lambda$static$24()
+ LeavesBlock leaves(SoundType)
+ MapColor lambda$bed$1(DyeColor,BlockState)
- MapColor lambda$bed$2(DyeColor,BlockState)
+ MapColor lambda$log$2(MapColor,MapColor,BlockState)
- MapColor lambda$log$4(MapColor,MapColor,BlockState)
+ MapColor lambda$netherStem$4(MapColor,BlockState)
- MapColor lambda$netherStem$5(MapColor,BlockState)
+ PistonBaseBlock pistonBase(boolean)
+ RotatedPillarBlock log(MapColor,MapColor,SoundType)
+ RotatedPillarBlock log(MapColor,MapColor)
+ ShulkerBoxBlock shulkerBox(DyeColor,BlockBehaviour$Properties)
+ StainedGlassBlock stainedGlass(DyeColor)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BrewingStandBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BubbleColumnBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BuddingAmethystBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ButtonBlock
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- BlockSetType lambda$static$0(ButtonBlock)
- Integer lambda$static$1(ButtonBlock)
- MapCodec codec()
+ void <init>(BlockBehaviour$Properties,BlockSetType,int,boolean)
- void <init>(BlockSetType,int,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CactusBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CalibratedSculkSensorBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CandleBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CarpetBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CartographyTableBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CauldronBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CaveVinesBlock
</summary>

```diff
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CeilingHangingSignBlock
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- MapCodec codec()
+ void <init>(BlockBehaviour$Properties,WoodType)
- void <init>(WoodType,BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.CherryLeavesBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>




<details>
<summary>
net.minecraft.world.level.block.ChorusPlantBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockGetter,BlockPos)
- BlockState getStateWithConnections(BlockGetter,BlockPos,BlockState)
- MapCodec codec()
- void <clinit>()
```

</details>


<details>
<summary>
net.minecraft.world.level.block.GrowingPlantBodyBlock
</summary>

```diff
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HalfTransparentBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HayBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
- MapCodec codec()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.IceBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.InfestedRotatedPillarBlock
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.JigsawBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.KelpBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LadderBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LanternBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LayeredCauldronBlock
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- Biome$Precipitation lambda$static$0(LayeredCauldronBlock)
+ boolean lambda$static$0(Biome$Precipitation)
+ boolean lambda$static$1(Biome$Precipitation)
- CauldronInteraction$InteractionMap lambda$static$1(LayeredCauldronBlock)
- MapCodec codec()
- void <init>(Biome$Precipitation,CauldronInteraction$InteractionMap,BlockBehaviour$Properties)
+ void <init>(BlockBehaviour$Properties,Predicate,Map)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
- MapCodec codec()
```

</details>


<details>
<summary>
net.minecraft.world.level.block.LightningRodBlock
</summary>

```diff
- MapCodec codec()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.MagmaBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.MangrovePropaguleBlock
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
- MapCodec codec()
- TreeGrower lambda$static$0(MangrovePropaguleBlock)
+ void <init>(BlockBehaviour$Properties)
- void <init>(TreeGrower,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PoweredBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>


<details>
<summary>
net.minecraft.world.level.block.ScaffoldingBlock
</summary>

```diff
- MapCodec codec()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.SculkCatalystBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkShriekerBlock
</summary>

```diff
- MapCodec codec()
```

</details>


<details>
<summary>
net.minecraft.world.level.block.SeagrassBlock
</summary>

```diff
- MapCodec codec()
```

</details>


<details>
<summary>
net.minecraft.world.level.block.SkullBlock$Type
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SlabBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SlimeBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SmithingTableBlock
</summary>

```diff
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SnifferEggBlock
</summary>

```diff
- MapCodec codec()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.SoulFireBlock
</summary>

```diff
- MapCodec codec()
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.SpongeBlock
</summary>

```diff
- MapCodec codec()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.StainedGlassPaneBlock
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- MapCodec codec()
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.StemBlock
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
- MapCodec codec()
- ResourceKey lambda$static$0(StemBlock)
- ResourceKey lambda$static$1(StemBlock)
- ResourceKey lambda$static$2(StemBlock)
+ StemGrownBlock getFruit()
- void <init>(ResourceKey,ResourceKey,ResourceKey,BlockBehaviour$Properties)
+ void <init>(StemGrownBlock,Supplier,BlockBehaviour$Properties)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.piston.PistonBaseBlock
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
- Boolean lambda$static$0(PistonBaseBlock)
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.PistonHeadBlock
</summary>

```diff
- BlockState playerWillDestroy(Level,BlockPos,BlockState,Player)
+ ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState)
- MapCodec codec()
+ void playerWillDestroy(Level,BlockPos,BlockState,Player)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
- App lambda$simpleCodec$0(Function,RecordCodecBuilder$Instance)
- BlockBehaviour$Properties properties()
- MapCodec simpleCodec(Function)
- RecordCodecBuilder propertiesCodec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
- boolean is(ResourceKey)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$Properties
</summary>

```diff
- BlockBehaviour$Properties lambda$static$0()
+ boolean lambda$new$2(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$new$3(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$new$3(BlockState,BlockGetter,BlockPos)
- boolean lambda$new$7(BlockState,BlockGetter,BlockPos)
+ int lambda$new$1(BlockState)
- int lambda$new$2(BlockState)
+ MapColor lambda$mapColor$7(DyeColor,BlockState)
- MapColor lambda$mapColor$8(DyeColor,BlockState)
+ MapColor lambda$mapColor$8(MapColor,BlockState)
- MapColor lambda$mapColor$9(MapColor,BlockState)
+ MapColor lambda$new$0(BlockState)
- MapColor lambda$new$1(BlockState)
- Vec3 lambda$offsetType$11(BlockState,BlockGetter,BlockPos)
+ Vec3 lambda$offsetType$9(BlockState,BlockGetter,BlockPos)
- void <clinit>()
```

</details>
</details>