## Comparison with [24w45a](https://github.com/PixiGeko/Minecraft-generated-data/tree/24w45a)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">24w45a</th><th>24w46a</th></tr><tr><td>DataPack version</td><td><pre>59</pre></td><td><pre>60</pre></td></tr><tr><td>ResourcePack version</td><td><pre>44</pre></td><td><pre>45</pre></td></tr><tr><td>World version</td><td><pre>4177</pre></td><td><pre>4178</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742045</pre></td><td><pre>1073742046</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
entity_type
</summary>

```diff
- minecraft:creaking_transient
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
- minecraft:block.resin.hit
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
- minecraft:creaking_transient
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
- minecraft:creaking_transient
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
- minecraft:creaking_transient
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
- minecraft:block.resin.hit
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
- minecraft/loot_table/entities/creaking_transient.json
- minecraft/tags/item/drowned_preferred_weapon.json
+ minecraft/tags/item/drowned_preferred_weapons.json
- minecraft/tags/item/piglin_preferred_weapon.json
+ minecraft/tags/item/piglin_preferred_weapons.json
- minecraft/tags/item/pillager_preferred_weapon.json
+ minecraft/tags/item/pillager_preferred_weapons.json
- minecraft/tags/item/skeleton_preferred_weapon.json
+ minecraft/tags/item/skeleton_preferred_weapons.json
- minecraft/tags/item/trim_templates.json
+ minecraft/tags/item/wither_skeleton_disliked_weapons.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/gui/sprites/container/bundle/slot_background.png.mcmeta
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
+ XXX.entity.monster.package-info
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.InventoryCarrier
+ XXX.entity.npc.Npc
- XXX.entity.npc.package-info
- XXX.entity.npc.Villager
+ XXX.entity.npc.VillagerData
- XXX.entity.npc.VillagerDataHolder
+ XXX.entity.npc.VillagerProfession
- XXX.entity.npc.VillagerTrades
+ XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
- XXX.entity.npc.VillagerTrades$EmeraldForItems
+ XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- XXX.entity.npc.VillagerTrades$FailureItemListing
+ XXX.entity.npc.VillagerTrades$ItemListing
- XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ XXX.entity.npc.VillagerTrades$ItemsForEmeralds
- XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ XXX.entity.npc.VillagerTrades$TypeSpecificTrade
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Input
+ XXX.entity.player.Input$1
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$2
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerModelPart
- XXX.entity.player.ProfileKeyPair
+ XXX.entity.player.ProfilePublicKey
- XXX.entity.player.ProfilePublicKey$Data
+ XXX.entity.player.ProfilePublicKey$ValidationException
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$IngredientInfo
- XXX.entity.player.StackedContents$Output
+ XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.player.StackedItemContents
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.Arrow
- XXX.entity.projectile.DragonFireball
+ XXX.entity.projectile.EvokerFangs
- XXX.entity.projectile.EyeOfEnder
+ XXX.entity.projectile.Fireball
- XXX.entity.projectile.FireworkRocketEntity
+ XXX.entity.projectile.FishingHook
- XXX.entity.projectile.FishingHook$FishHookState
+ XXX.entity.projectile.FishingHook$OpenWaterType
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.Projectile$ProjectileFactory
+ XXX.entity.projectile.ProjectileDeflection
- XXX.entity.projectile.ProjectileUtil
+ XXX.entity.projectile.ShulkerBullet
- XXX.entity.projectile.SmallFireball
+ XXX.entity.projectile.Snowball
- XXX.entity.projectile.SpectralArrow
+ XXX.entity.projectile.ThrowableItemProjectile
- XXX.entity.projectile.ThrowableProjectile
+ XXX.entity.projectile.ThrownEgg
- XXX.entity.projectile.ThrownEnderpearl
+ XXX.entity.projectile.ThrownExperienceBottle
- XXX.entity.projectile.ThrownPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
- XXX.entity.raid.package-info
- XXX.entity.raid.Raid
+ XXX.entity.raid.Raid$1
+ XXX.entity.raid.Raid$RaiderType
- XXX.entity.raid.Raid$RaidStatus
- XXX.entity.raid.Raider
+ XXX.entity.raid.Raider$HoldGroundAttackGoal
- XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ XXX.entity.raid.Raider$RaiderCelebration
- XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ XXX.entity.raid.Raids
+ XXX.entity.schedule.Activity
- XXX.entity.schedule.Keyframe
+ XXX.entity.schedule.package-info
+ XXX.entity.schedule.Schedule
- XXX.entity.schedule.ScheduleBuilder
+ XXX.entity.schedule.ScheduleBuilder$ActivityTransition
- XXX.entity.schedule.Timeline
- XXX.entity.vehicle.AbstractBoat
+ XXX.entity.vehicle.AbstractBoat$Status
- XXX.entity.vehicle.AbstractChestBoat
+ XXX.entity.vehicle.AbstractMinecart
- XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.ChestBoat
+ XXX.entity.vehicle.ChestRaft
- XXX.entity.vehicle.ContainerEntity
+ XXX.entity.vehicle.ContainerEntity$1
- XXX.entity.vehicle.DismountHelper
+ XXX.entity.vehicle.Minecart
- XXX.entity.vehicle.MinecartBehavior
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.NewMinecartBehavior
- XXX.entity.vehicle.NewMinecartBehavior$1
+ XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
- XXX.entity.vehicle.NewMinecartBehavior$StepPartialTicks
+ XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
- XXX.entity.vehicle.OldMinecartBehavior
+ XXX.entity.vehicle.OldMinecartBehavior$1
- XXX.entity.vehicle.package-info
- XXX.entity.vehicle.Raft
+ XXX.entity.vehicle.VehicleEntity
+ XXX.inventory.tooltip.BundleTooltip
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipComponent
+ XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Builder
- XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.PotionContents
- XXX.item.alchemy.Potions
- XXX.item.component.BlockItemStateProperties
+ XXX.item.component.BookContent
- XXX.item.component.BundleContents
+ XXX.item.component.BundleContents$Mutable
- XXX.item.component.ChargedProjectiles
+ XXX.item.component.Consumable
- XXX.item.component.Consumable$Builder
+ XXX.item.component.Consumable$OverrideConsumeSound
- XXX.item.component.ConsumableListener
+ XXX.item.component.Consumables
- XXX.item.component.CustomData
+ XXX.item.component.CustomModelData
- XXX.item.component.DamageResistant
+ XXX.item.component.DeathProtection
- XXX.item.component.DebugStickState
+ XXX.item.component.DyedItemColor
- XXX.item.component.FireworkExplosion
+ XXX.item.component.FireworkExplosion$Shape
- XXX.item.component.Fireworks
+ XXX.item.component.ItemAttributeModifiers
- XXX.item.component.ItemAttributeModifiers$1
+ XXX.item.component.ItemAttributeModifiers$Builder
- XXX.item.component.ItemAttributeModifiers$Entry
+ XXX.item.component.ItemContainerContents
- XXX.item.component.ItemContainerContents$Slot
+ XXX.item.component.ItemLore
- XXX.item.component.LodestoneTracker
+ XXX.item.component.MapDecorations
- XXX.item.component.MapDecorations$Entry
+ XXX.item.component.MapItemColor
- XXX.item.component.MapPostProcessing
+ XXX.item.component.OminousBottleAmplifier
+ XXX.item.component.package-info
- XXX.item.component.ResolvableProfile
+ XXX.item.component.SeededContainerLoot
- XXX.item.component.SuspiciousStewEffects
+ XXX.item.component.SuspiciousStewEffects$Entry
- XXX.item.component.Tool
+ XXX.item.component.Tool$Rule
- XXX.item.component.TooltipProvider
+ XXX.item.component.Unbreakable
- XXX.item.component.UseCooldown
+ XXX.item.component.UseRemainder
- XXX.item.component.UseRemainder$OnExtraCreatedRemainder
+ XXX.item.component.WritableBookContent
- XXX.item.component.WrittenBookContent
- XXX.item.consume_effects.ApplyStatusEffectsConsumeEffect
+ XXX.item.consume_effects.ClearAllStatusEffectsConsumeEffect
- XXX.item.consume_effects.ConsumeEffect
+ XXX.item.consume_effects.ConsumeEffect$Type
+ XXX.item.consume_effects.package-info
- XXX.item.consume_effects.PlaySoundConsumeEffect
+ XXX.item.consume_effects.RemoveStatusEffectsConsumeEffect
- XXX.item.consume_effects.TeleportRandomlyConsumeEffect
- XXX.item.context.BlockPlaceContext
+ XXX.item.context.DirectionalPlaceContext
- XXX.item.context.DirectionalPlaceContext$1
- XXX.item.context.package-info
+ XXX.item.context.UseOnContext
+ XXX.item.crafting.AbstractCookingRecipe
- XXX.item.crafting.AbstractCookingRecipe$Factory
+ XXX.item.crafting.AbstractCookingRecipe$Serializer
- XXX.item.crafting.ArmorDyeRecipe
+ XXX.item.crafting.BannerDuplicateRecipe
- XXX.item.crafting.BlastingRecipe
+ XXX.item.crafting.BlastingRecipe$1
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CookingBookCategory
+ XXX.item.crafting.CraftingBookCategory
- XXX.item.crafting.CraftingInput
+ XXX.item.crafting.CraftingInput$Positioned
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CraftingRecipe$1
- XXX.item.crafting.CustomRecipe
+ XXX.item.crafting.CustomRecipe$Serializer
- XXX.item.crafting.CustomRecipe$Serializer$Factory
+ XXX.item.crafting.DecoratedPotRecipe
- XXX.item.crafting.ExtendedRecipeBookCategory
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.PlacementInfo
- XXX.monster.creaking.Creaking$CreakingPathNavigation
+ XXX.monster.creaking.CreakingTransient
+ XXX.monster.creaking.CreakingTransient$HomeNodeEvaluator
- XXX.monster.creaking.package-info
+ XXX.monster.hoglin.Hoglin
- XXX.monster.hoglin.HoglinAi
+ XXX.monster.hoglin.HoglinBase
- XXX.monster.hoglin.package-info
- XXX.monster.piglin.AbstractPiglin
- XXX.monster.piglin.package-info
+ XXX.monster.piglin.Piglin
- XXX.monster.piglin.PiglinAi
+ XXX.monster.piglin.PiglinArmPose
- XXX.monster.piglin.PiglinBrute
+ XXX.monster.piglin.PiglinBruteAi
- XXX.monster.piglin.RememberIfHoglinWasKilled
+ XXX.monster.piglin.StartAdmiringItemIfSeen
- XXX.monster.piglin.StartHuntingHoglin
+ XXX.monster.piglin.StopAdmiringIfItemTooFarAway
- XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ XXX.monster.warden.AngerLevel
- XXX.monster.warden.AngerManagement
+ XXX.monster.warden.AngerManagement$1
- XXX.monster.warden.AngerManagement$Sorter
- XXX.monster.warden.package-info
+ XXX.monster.warden.Warden
- XXX.monster.warden.Warden$1
+ XXX.monster.warden.Warden$1$1
- XXX.monster.warden.Warden$2
+ XXX.monster.warden.Warden$VibrationUser
- XXX.monster.warden.WardenAi
+ XXX.monster.warden.WardenSpawnTracker
+ XXX.packs.metadata.MetadataSectionType
- XXX.projectile.windcharge.AbstractWindCharge
+ XXX.projectile.windcharge.BreezeWindCharge
+ XXX.projectile.windcharge.package-info
- XXX.projectile.windcharge.WindCharge
+ XXX.world.entity.package-info
+ XXX.world.flag.FeatureElement
- XXX.world.flag.FeatureFlag
+ XXX.world.flag.FeatureFlagRegistry
- XXX.world.flag.FeatureFlagRegistry$Builder
+ XXX.world.flag.FeatureFlags
+ XXX.world.flag.FeatureFlagSet
- XXX.world.flag.FeatureFlagUniverse
- XXX.world.flag.package-info
+ XXX.world.food.FoodConstants
- XXX.world.food.FoodData
+ XXX.world.food.FoodProperties
- XXX.world.food.FoodProperties$Builder
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractContainerMenu$1
+ XXX.world.inventory.AbstractCraftingMenu
- XXX.world.inventory.AbstractCraftingMenu$1
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AbstractFurnaceMenu$1
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.ArmorSlot
+ XXX.world.inventory.BeaconMenu
- XXX.world.inventory.BeaconMenu$1
+ XXX.world.inventory.BeaconMenu$PaymentSlot
- XXX.world.inventory.BlastFurnaceMenu
+ XXX.world.inventory.BrewingStandMenu
- XXX.world.inventory.BrewingStandMenu$FuelSlot
+ XXX.world.inventory.BrewingStandMenu$IngredientsSlot
- XXX.world.inventory.BrewingStandMenu$PotionSlot
+ XXX.world.inventory.CartographyTableMenu
- XXX.world.inventory.CartographyTableMenu$1
+ XXX.world.inventory.CartographyTableMenu$2
- XXX.world.inventory.CartographyTableMenu$3
+ XXX.world.inventory.CartographyTableMenu$4
- XXX.world.inventory.CartographyTableMenu$5
+ XXX.world.inventory.ChestMenu
- XXX.world.inventory.ClickAction
+ XXX.world.inventory.ClickType
- XXX.world.inventory.ContainerData
+ XXX.world.inventory.ContainerLevelAccess
- XXX.world.inventory.ContainerLevelAccess$1
+ XXX.world.inventory.ContainerLevelAccess$2
- XXX.world.inventory.ContainerListener
+ XXX.world.inventory.ContainerSynchronizer
- XXX.world.inventory.CrafterMenu
+ XXX.world.inventory.CrafterSlot
- XXX.world.inventory.CraftingContainer
+ XXX.world.inventory.CraftingMenu
- XXX.world.inventory.DataSlot
+ XXX.world.inventory.DataSlot$1
- XXX.world.inventory.DataSlot$2
+ XXX.world.inventory.DataSlot$3
- XXX.world.inventory.DispenserMenu
+ XXX.world.inventory.EnchantmentMenu
- XXX.world.inventory.EnchantmentMenu$1
+ XXX.world.inventory.EnchantmentMenu$2
- XXX.world.inventory.EnchantmentMenu$3
+ XXX.world.inventory.FurnaceFuelSlot
- XXX.world.inventory.FurnaceMenu
+ XXX.world.inventory.FurnaceResultSlot
- XXX.world.inventory.GrindstoneMenu
+ XXX.world.inventory.GrindstoneMenu$1
- XXX.world.inventory.GrindstoneMenu$2
+ XXX.world.inventory.GrindstoneMenu$3
- XXX.world.inventory.GrindstoneMenu$4
+ XXX.world.inventory.HopperMenu
- XXX.world.inventory.HorseInventoryMenu
+ XXX.world.inventory.HorseInventoryMenu$1
- XXX.world.inventory.HorseInventoryMenu$2
+ XXX.world.inventory.InventoryMenu
- XXX.world.inventory.InventoryMenu$1
+ XXX.world.inventory.ItemCombinerMenu
- XXX.world.inventory.ItemCombinerMenu$1
+ XXX.world.inventory.ItemCombinerMenu$2
- XXX.world.inventory.ItemCombinerMenu$3
+ XXX.world.inventory.ItemCombinerMenu$4
- XXX.world.inventory.ItemCombinerMenuSlotDefinition
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition$Builder
- XXX.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
+ XXX.world.inventory.LecternMenu
- XXX.world.inventory.LecternMenu$1
+ XXX.world.inventory.LoomMenu
- XXX.world.inventory.LoomMenu$1
+ XXX.world.inventory.LoomMenu$2
- XXX.world.inventory.LoomMenu$3
+ XXX.world.inventory.LoomMenu$4
- XXX.world.inventory.LoomMenu$5
+ XXX.world.inventory.LoomMenu$6
- XXX.world.inventory.MenuConstructor
+ XXX.world.inventory.MenuType
- XXX.world.inventory.MenuType$MenuSupplier
+ XXX.world.inventory.MerchantContainer
- XXX.world.inventory.MerchantMenu
+ XXX.world.inventory.MerchantResultSlot
- XXX.world.inventory.NonInteractiveResultSlot
- XXX.world.inventory.package-info
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeBookMenu$PostPlaceAction
- XXX.world.inventory.RecipeBookType
+ XXX.world.inventory.RecipeCraftingHolder
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SlotRange
+ XXX.world.inventory.SlotRange$1
- XXX.world.inventory.SlotRanges
+ XXX.world.inventory.SmithingMenu
- XXX.world.inventory.SmokerMenu
+ XXX.world.inventory.StackedContentsCompatible
- XXX.world.inventory.StonecutterMenu
+ XXX.world.inventory.StonecutterMenu$1
- XXX.world.inventory.StonecutterMenu$2
+ XXX.world.inventory.TransientCraftingContainer
- XXX.world.item.AdventureModePredicate
+ XXX.world.item.AirItem
- XXX.world.item.AnimalArmorItem
+ XXX.world.item.AnimalArmorItem$BodyType
- XXX.world.item.ArmorItem
+ XXX.world.item.ArmorStandItem
- XXX.world.item.ArrowItem
+ XXX.world.item.AxeItem
- XXX.world.item.BannerItem
+ XXX.world.item.BannerPatternItem
- XXX.world.item.BedItem
+ XXX.world.item.BlockItem
- XXX.world.item.BoatItem
+ XXX.world.item.BoneMealItem
- XXX.world.item.BoneMealItem$1
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BrushItem
- XXX.world.item.BrushItem$1
+ XXX.world.item.BrushItem$DustParticlesDelta
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
- XXX.world.item.BundleItem$1
+ XXX.world.item.CompassItem
- XXX.world.item.CreativeModeTab
+ XXX.world.item.CreativeModeTab$Builder
- XXX.world.item.CreativeModeTab$DisplayItemsGenerator
+ XXX.world.item.CreativeModeTab$ItemDisplayBuilder
- XXX.world.item.CreativeModeTab$ItemDisplayParameters
+ XXX.world.item.CreativeModeTab$Output
- XXX.world.item.CreativeModeTab$Row
+ XXX.world.item.CreativeModeTab$TabVisibility
- XXX.world.item.CreativeModeTab$Type
+ XXX.world.item.CreativeModeTabs
- XXX.world.item.CrossbowItem
+ XXX.world.item.CrossbowItem$ChargeType
- XXX.world.item.CrossbowItem$ChargingSounds
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiggerItem
+ XXX.world.item.DiscFragmentItem
- XXX.world.item.DispensibleContainerItem
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.EitherHolder
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkStarItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
- XXX.world.item.FoodOnAStickItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.GlowInkSacItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HangingSignItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.InkSacItem
- XXX.world.item.Instrument
+ XXX.world.item.InstrumentItem
- XXX.world.item.Instruments
+ XXX.world.item.Item
- XXX.world.item.Item$Properties
+ XXX.world.item.Item$TooltipContext
- XXX.world.item.Item$TooltipContext$1
+ XXX.world.item.Item$TooltipContext$2
- XXX.world.item.Item$TooltipContext$3
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemDisplayContext
- XXX.world.item.ItemFrameItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$1
+ XXX.world.item.ItemStack$2
- XXX.world.item.ItemStack$3
+ XXX.world.item.ItemStack$4
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUseAnimation
+ XXX.world.item.ItemUtils
+ XXX.world.item.JukeboxPlayable
- XXX.world.item.JukeboxSong
+ XXX.world.item.JukeboxSongPlayer
- XXX.world.item.JukeboxSongPlayer$OnSongChanged
+ XXX.world.item.JukeboxSongs
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MaceItem
- XXX.world.item.MapItem
+ XXX.world.item.MapItem$1
- XXX.world.item.MinecartItem
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
+ XXX.world.item.PickaxeItem
- XXX.world.item.PlaceOnWaterBlockItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileItem
- XXX.world.item.ProjectileItem$DispenseConfig
+ XXX.world.item.ProjectileItem$DispenseConfig$Builder
- XXX.world.item.ProjectileItem$PositionFunction
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.Rarity
+ XXX.world.item.SaddleItem
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignApplicator
- XXX.world.item.SignItem
+ XXX.world.item.SmithingTemplateItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SolidBucketItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.SpyglassItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.SwordItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.TippedArrowItem
- XXX.world.item.ToolMaterial
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.core.component.PatchedDataComponentMap +1M
```
```
XXX.data.tags.VanillaItemTagsProvider +1M
```
```
XXX.server.packs.BuiltInMetadata +3M -3M
```
```
XXX.packs.resources.ResourceMetadata$1 +1M -1M
```
```
XXX.packs.resources.ResourceMetadata$Builder +1M -1M
```
```
XXX.world.entity.EntityType -1P
```
```
XXX.entity.monster.WitherSkeleton +2M
```
```
XXX.level.block.AbstractFurnaceBlock -1M
```
```
XXX.level.block.BarrelBlock -1M
```
```
XXX.level.block.BaseEntityBlock -1M
```
```
XXX.level.block.BedBlock -1M
```
```
XXX.level.block.BeehiveBlock -1M
```
```
XXX.level.block.BellBlock -1M
```
```
XXX.level.block.BrushableBlock -1M
```
```
XXX.level.block.CampfireBlock -1M
```
```
XXX.level.block.CommandBlock -1M
```
```
XXX.level.block.CreakingHeartBlock -1M
```
```
XXX.level.block.EnchantingTableBlock -1M
```
```
XXX.level.block.EndPortalBlock +1M
```
```
XXX.level.block.EyeblossomBlock$Type -1M
```
```
XXX.level.block.HopperBlock -1M
```
```
XXX.level.block.LecternBlock -1M
```
```
XXX.level.block.MultifaceBlock +1M -1M | +1P
```
```
XXX.level.block.SculkSensorBlock -1M
```
```
XXX.level.block.SculkVeinBlock -4M | -1P
```
```
XXX.level.block.ShulkerBoxBlock -1M
```
```
XXX.level.block.SkullBlock -1M
```
```
XXX.level.block.SpawnerBlock -1M
```
```
XXX.level.block.StonecutterBlock -1M
```

</details>
<details>
<summary>
net.minecraft.core.component.PatchedDataComponentMap
</summary>

```diff
- boolean hasNonDefault(DataComponentType)
```

</details>
<details>
<summary>
net.minecraft.data.tags.VanillaItemTagsProvider
</summary>

```diff
- void lambda$addTags$0(Holder$Reference)
```

</details>
<details>
<summary>
net.minecraft.server.packs.BuiltInMetadata
</summary>

```diff
+ BuiltInMetadata of(MetadataSectionSerializer,Object,MetadataSectionSerializer,Object)
+ BuiltInMetadata of(MetadataSectionSerializer,Object)
- BuiltInMetadata of(MetadataSectionType,Object,MetadataSectionType,Object)
- BuiltInMetadata of(MetadataSectionType,Object)
+ Object get(MetadataSectionSerializer)
- Object get(MetadataSectionType)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.ResourceMetadata$1
</summary>

```diff
+ Optional getSection(MetadataSectionSerializer)
- Optional getSection(MetadataSectionType)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.ResourceMetadata$Builder
</summary>

```diff
+ ResourceMetadata$Builder put(MetadataSectionSerializer,Object)
- ResourceMetadata$Builder put(MetadataSectionType,Object)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.WitherSkeleton
</summary>

```diff
- boolean canHoldItem(ItemStack)
- TagKey getPreferredWeaponType()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractFurnaceBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BarrelBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseEntityBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BrushableBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CampfireBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CommandBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CreakingHeartBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnchantingTableBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndPortalBlock
</summary>

```diff
- RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EyeblossomBlock$Type
</summary>

```diff
+ BlockState oppositeState()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.MultifaceBlock
</summary>

```diff
+ boolean isWaterloggable()
- FluidState getFluidState(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkSensorBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkVeinBlock
</summary>

```diff
+ BlockState updateShape(BlockState,LevelReader,ScheduledTickAccess,BlockPos,Direction,BlockPos,BlockState,RandomSource)
+ boolean canBeReplaced(BlockState,BlockPlaceContext)
+ FluidState getFluidState(BlockState)
+ void createBlockStateDefinition(StateDefinition$Builder)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SkullBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SpawnerBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StonecutterBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.atlas.sources.DirectoryLister
+ XXX.atlas.sources.LazyLoadedImage
+ XXX.atlas.sources.package-info
- XXX.atlas.sources.PalettedPermutations
+ XXX.atlas.sources.PalettedPermutations$PalettedSpriteSupplier
- XXX.atlas.sources.SingleFile
+ XXX.atlas.sources.SourceFilter
- XXX.atlas.sources.Unstitcher
+ XXX.atlas.sources.Unstitcher$Region
- XXX.atlas.sources.Unstitcher$RegionInstance
+ XXX.block.model.BakedQuad
- XXX.block.model.BlockElement
+ XXX.block.model.BlockElement$1
- XXX.block.model.BlockElement$Deserializer
+ XXX.block.model.BlockElementFace
- XXX.block.model.BlockElementFace$Deserializer
+ XXX.block.model.BlockElementRotation
- XXX.block.model.BlockFaceUV
+ XXX.block.model.BlockFaceUV$Deserializer
- XXX.block.model.BlockModel
+ XXX.block.model.BlockModel$Deserializer
- XXX.block.model.BlockModelDefinition
+ XXX.block.model.BlockModelDefinition$Deserializer
- XXX.block.model.BlockModelDefinition$MissingVariantException
+ XXX.block.model.FaceBakery
- XXX.block.model.FaceBakery$1
+ XXX.block.model.ItemModelGenerator
- XXX.block.model.ItemModelGenerator$Span
+ XXX.block.model.ItemModelGenerator$SpanFacing
- XXX.block.model.ItemTransform
+ XXX.block.model.ItemTransform$Deserializer
- XXX.block.model.ItemTransforms
+ XXX.block.model.ItemTransforms$1
- XXX.block.model.ItemTransforms$Deserializer
+ XXX.block.model.MultiVariant
- XXX.block.model.MultiVariant$Deserializer
- XXX.block.model.package-info
+ XXX.block.model.TextureSlots
- XXX.block.model.TextureSlots$Data
+ XXX.block.model.TextureSlots$Data$Builder
- XXX.block.model.TextureSlots$Reference
+ XXX.block.model.TextureSlots$Resolver
- XXX.block.model.TextureSlots$SlotContents
+ XXX.block.model.TextureSlots$Value
- XXX.block.model.UnbakedBlockStateModel
+ XXX.block.model.Variant
- XXX.block.model.Variant$Deserializer
+ XXX.block.model.VariantSelector
+ XXX.client.resources.ClientPackSource
- XXX.client.resources.DefaultPlayerSkin
+ XXX.client.resources.FoliageColorReloadListener
- XXX.client.resources.GrassColorReloadListener
+ XXX.client.resources.IndexedAssetSource
- XXX.client.resources.LegacyStuffWrapper
+ XXX.client.resources.MapDecorationTextureManager
- XXX.client.resources.MapTextureManager
+ XXX.client.resources.MapTextureManager$MapInstance
- XXX.client.resources.MobEffectTextureManager
+ XXX.client.resources.PaintingTextureManager
- XXX.client.resources.PlayerSkin
+ XXX.client.resources.PlayerSkin$Model
- XXX.client.resources.SkinManager
+ XXX.client.resources.SkinManager$1
- XXX.client.resources.SkinManager$2
+ XXX.client.resources.SkinManager$CacheKey
- XXX.client.resources.SkinManager$TextureCache
+ XXX.client.resources.SplashManager
- XXX.client.resources.TextureAtlasHolder
- XXX.entity.monster.package-info
- XXX.entity.npc.AbstractVillager
+ XXX.entity.npc.CatSpawner
- XXX.entity.npc.ClientSideMerchant
+ XXX.entity.npc.InventoryCarrier
- XXX.entity.npc.Npc
+ XXX.entity.npc.package-info
+ XXX.entity.npc.Villager
- XXX.entity.npc.VillagerData
+ XXX.entity.npc.VillagerDataHolder
- XXX.entity.npc.VillagerProfession
+ XXX.entity.npc.VillagerTrades
- XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ XXX.entity.npc.VillagerTrades$EmeraldForItems
- XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
- XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ XXX.entity.npc.VillagerTrades$FailureItemListing
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerTrades$TypeSpecificTrade
+ XXX.entity.npc.VillagerType
- XXX.entity.npc.WanderingTrader
+ XXX.entity.npc.WanderingTrader$WanderToPositionGoal
- XXX.entity.npc.WanderingTraderSpawner
+ XXX.entity.player.Abilities
- XXX.entity.player.ChatVisiblity
+ XXX.entity.player.Input
- XXX.entity.player.Input$1
+ XXX.entity.player.Inventory
- XXX.entity.player.package-info
- XXX.entity.player.Player
+ XXX.entity.player.Player$1
- XXX.entity.player.Player$2
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerModelPart
+ XXX.entity.player.ProfileKeyPair
- XXX.entity.player.ProfilePublicKey
+ XXX.entity.player.ProfilePublicKey$Data
- XXX.entity.player.ProfilePublicKey$ValidationException
+ XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$IngredientInfo
+ XXX.entity.player.StackedContents$Output
- XXX.entity.player.StackedContents$RecipePicker
+ XXX.entity.player.StackedItemContents
+ XXX.entity.projectile.AbstractArrow
- XXX.entity.projectile.AbstractArrow$Pickup
+ XXX.entity.projectile.AbstractHurtingProjectile
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$FishHookState
- XXX.entity.projectile.FishingHook$OpenWaterType
+ XXX.entity.projectile.ItemSupplier
- XXX.entity.projectile.LargeFireball
+ XXX.entity.projectile.LlamaSpit
- XXX.entity.projectile.package-info
- XXX.entity.projectile.Projectile
+ XXX.entity.projectile.Projectile$ProjectileFactory
- XXX.entity.projectile.ProjectileDeflection
+ XXX.entity.projectile.ProjectileUtil
- XXX.entity.projectile.ShulkerBullet
+ XXX.entity.projectile.SmallFireball
- XXX.entity.projectile.Snowball
+ XXX.entity.projectile.SpectralArrow
- XXX.entity.projectile.ThrowableItemProjectile
+ XXX.entity.projectile.ThrowableProjectile
- XXX.entity.projectile.ThrownEgg
+ XXX.entity.projectile.ThrownEnderpearl
- XXX.entity.projectile.ThrownExperienceBottle
+ XXX.entity.projectile.ThrownPotion
- XXX.entity.projectile.ThrownTrident
+ XXX.entity.projectile.WitherSkull
+ XXX.entity.raid.package-info
+ XXX.entity.raid.Raid
- XXX.entity.raid.Raid$1
- XXX.entity.raid.Raid$RaiderType
+ XXX.entity.raid.Raid$RaidStatus
+ XXX.entity.raid.Raider
- XXX.entity.raid.Raider$HoldGroundAttackGoal
+ XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- XXX.entity.raid.Raider$RaiderCelebration
+ XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
- XXX.entity.raid.Raids
- XXX.entity.schedule.Activity
+ XXX.entity.schedule.Keyframe
- XXX.entity.schedule.package-info
- XXX.entity.schedule.Schedule
+ XXX.entity.schedule.ScheduleBuilder
- XXX.entity.schedule.ScheduleBuilder$ActivityTransition
+ XXX.entity.schedule.Timeline
+ XXX.entity.vehicle.AbstractBoat
- XXX.entity.vehicle.AbstractBoat$Status
+ XXX.entity.vehicle.AbstractChestBoat
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.Boat
+ XXX.entity.vehicle.ChestBoat
- XXX.entity.vehicle.ChestRaft
+ XXX.entity.vehicle.ContainerEntity
- XXX.entity.vehicle.ContainerEntity$1
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartBehavior
- XXX.entity.vehicle.MinecartChest
+ XXX.entity.vehicle.MinecartCommandBlock
- XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ XXX.entity.vehicle.MinecartFurnace
- XXX.entity.vehicle.MinecartHopper
+ XXX.entity.vehicle.MinecartSpawner
- XXX.entity.vehicle.MinecartSpawner$1
+ XXX.entity.vehicle.MinecartTNT
- XXX.entity.vehicle.NewMinecartBehavior
+ XXX.entity.vehicle.NewMinecartBehavior$1
- XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
+ XXX.entity.vehicle.NewMinecartBehavior$StepPartialTicks
- XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
+ XXX.entity.vehicle.OldMinecartBehavior
- XXX.entity.vehicle.OldMinecartBehavior$1
+ XXX.entity.vehicle.package-info
+ XXX.entity.vehicle.Raft
- XXX.entity.vehicle.VehicleEntity
- XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipComponent
- XXX.item.alchemy.package-info
- XXX.item.alchemy.Potion
+ XXX.item.alchemy.PotionBrewing
- XXX.item.alchemy.PotionBrewing$Builder
+ XXX.item.alchemy.PotionBrewing$Mix
- XXX.item.alchemy.PotionContents
+ XXX.item.alchemy.Potions
+ XXX.item.component.BlockItemStateProperties
- XXX.item.component.BookContent
+ XXX.item.component.BundleContents
- XXX.item.component.BundleContents$Mutable
+ XXX.item.component.ChargedProjectiles
- XXX.item.component.Consumable
+ XXX.item.component.Consumable$Builder
- XXX.item.component.Consumable$OverrideConsumeSound
+ XXX.item.component.ConsumableListener
- XXX.item.component.Consumables
+ XXX.item.component.CustomData
- XXX.item.component.CustomModelData
+ XXX.item.component.DamageResistant
- XXX.item.component.DeathProtection
+ XXX.item.component.DebugStickState
- XXX.item.component.DyedItemColor
+ XXX.item.component.FireworkExplosion
- XXX.item.component.FireworkExplosion$Shape
+ XXX.item.component.Fireworks
- XXX.item.component.ItemAttributeModifiers
+ XXX.item.component.ItemAttributeModifiers$1
- XXX.item.component.ItemAttributeModifiers$Builder
+ XXX.item.component.ItemAttributeModifiers$Entry
- XXX.item.component.ItemContainerContents
+ XXX.item.component.ItemContainerContents$Slot
- XXX.item.component.ItemLore
+ XXX.item.component.LodestoneTracker
- XXX.item.component.MapDecorations
+ XXX.item.component.MapDecorations$Entry
- XXX.item.component.MapItemColor
+ XXX.item.component.MapPostProcessing
- XXX.item.component.OminousBottleAmplifier
- XXX.item.component.package-info
+ XXX.item.component.ResolvableProfile
- XXX.item.component.SeededContainerLoot
+ XXX.item.component.SuspiciousStewEffects
- XXX.item.component.SuspiciousStewEffects$Entry
+ XXX.item.component.Tool
- XXX.item.component.Tool$Rule
+ XXX.item.component.TooltipProvider
- XXX.item.component.Unbreakable
+ XXX.item.component.UseCooldown
- XXX.item.component.UseRemainder
+ XXX.item.component.UseRemainder$OnExtraCreatedRemainder
- XXX.item.component.WritableBookContent
+ XXX.item.component.WrittenBookContent
+ XXX.item.consume_effects.ApplyStatusEffectsConsumeEffect
- XXX.item.consume_effects.ClearAllStatusEffectsConsumeEffect
+ XXX.item.consume_effects.ConsumeEffect
- XXX.item.consume_effects.ConsumeEffect$Type
- XXX.item.consume_effects.package-info
+ XXX.item.consume_effects.PlaySoundConsumeEffect
- XXX.item.consume_effects.RemoveStatusEffectsConsumeEffect
+ XXX.item.consume_effects.TeleportRandomlyConsumeEffect
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.AbstractCookingRecipe$Factory
- XXX.item.crafting.AbstractCookingRecipe$Serializer
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BlastingRecipe$1
+ XXX.item.crafting.BookCloningRecipe
- XXX.item.crafting.CampfireCookingRecipe
+ XXX.item.crafting.CookingBookCategory
- XXX.item.crafting.CraftingBookCategory
+ XXX.item.crafting.CraftingInput
- XXX.item.crafting.CraftingInput$Positioned
+ XXX.item.crafting.CraftingRecipe
- XXX.item.crafting.CraftingRecipe$1
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.CustomRecipe$Serializer
+ XXX.item.crafting.CustomRecipe$Serializer$Factory
- XXX.item.crafting.DecoratedPotRecipe
+ XXX.item.crafting.ExtendedRecipeBookCategory
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
- XXX.item.crafting.PlacementInfo
+ XXX.item.crafting.PlacementInfo$SlotInfo
+ XXX.metadata.animation.AnimationFrame
- XXX.metadata.animation.AnimationMetadataSection
+ XXX.metadata.animation.AnimationMetadataSection$1
+ XXX.metadata.animation.AnimationMetadataSectionSerializer
- XXX.metadata.animation.package-info
- XXX.metadata.animation.VillagerMetadataSection
+ XXX.metadata.animation.VillagerMetaDataSection
+ XXX.metadata.animation.VillagerMetadataSectionSerializer
+ XXX.metadata.gui.GuiMetadataSection
- XXX.metadata.gui.GuiSpriteScaling
+ XXX.metadata.gui.GuiSpriteScaling$NineSlice
- XXX.metadata.gui.GuiSpriteScaling$NineSlice$Border
+ XXX.metadata.gui.GuiSpriteScaling$Stretch
- XXX.metadata.gui.GuiSpriteScaling$Tile
+ XXX.metadata.gui.GuiSpriteScaling$Type
- XXX.metadata.gui.package-info
+ XXX.metadata.language.LanguageMetadataSection
- XXX.metadata.language.package-info
- XXX.metadata.texture.TextureMetadataSection
+ XXX.metadata.texture.TextureMetadataSectionSerializer
- XXX.model.multipart.AndCondition
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.MultiPart
- XXX.model.multipart.MultiPart$1Key
+ XXX.model.multipart.MultiPart$Definition
- XXX.model.multipart.MultiPart$Deserializer
+ XXX.model.multipart.MultiPart$InstantiatedSelector
- XXX.model.multipart.OrCondition
+ XXX.model.multipart.package-info
+ XXX.model.multipart.Selector
- XXX.model.multipart.Selector$Deserializer
- XXX.monster.creaking.Creaking$HomeNodeEvaluator
+ XXX.monster.creaking.CreakingTransient$CreakingPathNavigation
+ XXX.monster.creaking.package-info
- XXX.monster.hoglin.Hoglin
+ XXX.monster.hoglin.HoglinAi
- XXX.monster.hoglin.HoglinBase
+ XXX.monster.hoglin.package-info
+ XXX.monster.piglin.AbstractPiglin
+ XXX.monster.piglin.package-info
- XXX.monster.piglin.Piglin
+ XXX.monster.piglin.PiglinAi
- XXX.monster.piglin.PiglinArmPose
+ XXX.monster.piglin.PiglinBrute
- XXX.monster.piglin.PiglinBruteAi
+ XXX.monster.piglin.RememberIfHoglinWasKilled
- XXX.monster.piglin.StartAdmiringItemIfSeen
+ XXX.monster.piglin.StartHuntingHoglin
- XXX.monster.piglin.StopAdmiringIfItemTooFarAway
+ XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- XXX.monster.warden.AngerLevel
+ XXX.monster.warden.AngerManagement
- XXX.monster.warden.AngerManagement$1
+ XXX.monster.warden.AngerManagement$Sorter
+ XXX.monster.warden.package-info
- XXX.monster.warden.Warden
+ XXX.monster.warden.Warden$1
- XXX.monster.warden.Warden$1$1
+ XXX.monster.warden.Warden$2
- XXX.monster.warden.Warden$VibrationUser
+ XXX.monster.warden.WardenAi
- XXX.monster.warden.WardenSpawnTracker
+ XXX.packs.metadata.MetadataSectionSerializer
- XXX.packs.metadata.MetadataSectionType
+ XXX.packs.metadata.MetadataSectionType$1
+ XXX.projectile.windcharge.AbstractWindCharge
- XXX.projectile.windcharge.BreezeWindCharge
- XXX.projectile.windcharge.package-info
+ XXX.projectile.windcharge.WindCharge
- XXX.properties.conditional.ExtendedView
+ XXX.properties.conditional.FishingRodCast
- XXX.properties.conditional.HasComponent
+ XXX.properties.conditional.IsCarried
- XXX.properties.conditional.IsKeybindDown
+ XXX.properties.conditional.IsShiftDown
- XXX.properties.conditional.IsUsingItem
+ XXX.properties.conditional.IsXmas
- XXX.properties.select.HolderType
+ XXX.properties.select.ItemBlockState
- XXX.properties.select.LocalTime
+ XXX.renderer.block.BlockRenderDispatcher$1
- XXX.renderer.block.LiquidBlockRenderer
+ XXX.renderer.block.LiquidBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer
+ XXX.renderer.block.ModelBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
- XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ XXX.renderer.block.ModelBlockRenderer$Cache
- XXX.renderer.block.ModelBlockRenderer$Cache$1
+ XXX.renderer.block.ModelBlockRenderer$Cache$2
- XXX.renderer.block.ModelBlockRenderer$SizeInfo
+ XXX.renderer.block.package-info
- XXX.renderer.blockentity.AbstractSignRenderer
- XXX.renderer.special.HangingSignSpecialRenderer
- XXX.renderer.special.StandingSignSpecialRenderer
+ XXX.renderer.texture.MipmapGenerator
- XXX.renderer.texture.MissingTextureAtlasSprite
+ XXX.renderer.texture.OverlayTexture
- XXX.renderer.texture.package-info
- XXX.renderer.texture.ReloadableTexture
+ XXX.renderer.texture.SimpleTexture
- XXX.renderer.texture.SkinTextureDownloader
+ XXX.renderer.texture.SpriteContents
- XXX.renderer.texture.SpriteContents$AnimatedTexture
+ XXX.renderer.texture.SpriteContents$FrameInfo
- XXX.renderer.texture.SpriteContents$InterpolationData
+ XXX.renderer.texture.SpriteContents$Ticker
- XXX.renderer.texture.SpriteLoader
+ XXX.renderer.texture.SpriteLoader$Preparations
- XXX.renderer.texture.SpriteTicker
+ XXX.renderer.texture.Stitcher
- XXX.renderer.texture.Stitcher$Entry
+ XXX.renderer.texture.Stitcher$Holder
- XXX.renderer.texture.Stitcher$Region
+ XXX.renderer.texture.Stitcher$SpriteLoader
- XXX.renderer.texture.StitcherException
+ XXX.renderer.texture.TextureAtlas
- XXX.renderer.texture.TextureAtlasSprite
+ XXX.renderer.texture.TextureAtlasSprite$1
- XXX.renderer.texture.TextureAtlasSprite$Ticker
- XXX.renderer.texture.Tickable
+ XXX.resources.language.ClientLanguage
- XXX.resources.language.FormattedBidiReorder
+ XXX.resources.language.I18n
- XXX.resources.language.LanguageInfo
+ XXX.resources.language.LanguageManager
- XXX.resources.language.package-info
+ XXX.resources.metadata.package-info
+ XXX.texture.atlas.package-info
+ XXX.texture.atlas.SpriteResourceLoader
- XXX.texture.atlas.SpriteSource
+ XXX.texture.atlas.SpriteSource$Output
- XXX.texture.atlas.SpriteSource$SpriteSupplier
+ XXX.texture.atlas.SpriteSourceList
- XXX.texture.atlas.SpriteSourceList$1
- XXX.texture.atlas.SpriteSources
+ XXX.texture.atlas.SpriteSourceType
- XXX.world.entity.package-info
- XXX.world.flag.FeatureElement
+ XXX.world.flag.FeatureFlag
- XXX.world.flag.FeatureFlagRegistry
+ XXX.world.flag.FeatureFlagRegistry$Builder
- XXX.world.flag.FeatureFlags
- XXX.world.flag.FeatureFlagSet
+ XXX.world.flag.FeatureFlagUniverse
+ XXX.world.flag.package-info
- XXX.world.food.FoodConstants
+ XXX.world.food.FoodData
- XXX.world.food.FoodProperties
+ XXX.world.food.FoodProperties$Builder
- XXX.world.food.Foods
+ XXX.world.food.package-info
- XXX.world.inventory.AbstractContainerMenu
+ XXX.world.inventory.AbstractContainerMenu$1
- XXX.world.inventory.AbstractCraftingMenu
+ XXX.world.inventory.AbstractCraftingMenu$1
- XXX.world.inventory.AbstractFurnaceMenu
+ XXX.world.inventory.AbstractFurnaceMenu$1
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.ArmorSlot
- XXX.world.inventory.BeaconMenu
+ XXX.world.inventory.BeaconMenu$1
- XXX.world.inventory.BeaconMenu$PaymentSlot
+ XXX.world.inventory.BlastFurnaceMenu
- XXX.world.inventory.BrewingStandMenu
+ XXX.world.inventory.BrewingStandMenu$FuelSlot
- XXX.world.inventory.BrewingStandMenu$IngredientsSlot
+ XXX.world.inventory.BrewingStandMenu$PotionSlot
- XXX.world.inventory.CartographyTableMenu
+ XXX.world.inventory.CartographyTableMenu$1
- XXX.world.inventory.CartographyTableMenu$2
+ XXX.world.inventory.CartographyTableMenu$3
- XXX.world.inventory.CartographyTableMenu$4
+ XXX.world.inventory.CartographyTableMenu$5
- XXX.world.inventory.ChestMenu
+ XXX.world.inventory.ClickAction
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
- XXX.world.inventory.ContainerSynchronizer
+ XXX.world.inventory.CrafterMenu
- XXX.world.inventory.CrafterSlot
+ XXX.world.inventory.CraftingContainer
- XXX.world.inventory.CraftingMenu
+ XXX.world.inventory.DataSlot
- XXX.world.inventory.DataSlot$1
+ XXX.world.inventory.DataSlot$2
- XXX.world.inventory.DataSlot$3
+ XXX.world.inventory.DispenserMenu
- XXX.world.inventory.EnchantmentMenu
+ XXX.world.inventory.EnchantmentMenu$1
- XXX.world.inventory.EnchantmentMenu$2
+ XXX.world.inventory.EnchantmentMenu$3
- XXX.world.inventory.FurnaceFuelSlot
+ XXX.world.inventory.FurnaceMenu
- XXX.world.inventory.FurnaceResultSlot
+ XXX.world.inventory.GrindstoneMenu
- XXX.world.inventory.GrindstoneMenu$1
+ XXX.world.inventory.GrindstoneMenu$2
- XXX.world.inventory.GrindstoneMenu$3
+ XXX.world.inventory.GrindstoneMenu$4
- XXX.world.inventory.HopperMenu
+ XXX.world.inventory.HorseInventoryMenu
- XXX.world.inventory.HorseInventoryMenu$1
+ XXX.world.inventory.HorseInventoryMenu$2
- XXX.world.inventory.InventoryMenu
+ XXX.world.inventory.InventoryMenu$1
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
+ XXX.world.inventory.ItemCombinerMenu$3
- XXX.world.inventory.ItemCombinerMenu$4
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition
- XXX.world.inventory.ItemCombinerMenuSlotDefinition$Builder
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
- XXX.world.inventory.LecternMenu
+ XXX.world.inventory.LecternMenu$1
- XXX.world.inventory.LoomMenu
+ XXX.world.inventory.LoomMenu$1
- XXX.world.inventory.LoomMenu$2
+ XXX.world.inventory.LoomMenu$3
- XXX.world.inventory.LoomMenu$4
+ XXX.world.inventory.LoomMenu$5
- XXX.world.inventory.LoomMenu$6
+ XXX.world.inventory.MenuConstructor
- XXX.world.inventory.MenuType
+ XXX.world.inventory.MenuType$MenuSupplier
- XXX.world.inventory.MerchantContainer
+ XXX.world.inventory.MerchantMenu
- XXX.world.inventory.MerchantResultSlot
+ XXX.world.inventory.NonInteractiveResultSlot
+ XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeBookMenu$PostPlaceAction
+ XXX.world.inventory.RecipeBookType
- XXX.world.inventory.RecipeCraftingHolder
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SlotRange
- XXX.world.inventory.SlotRange$1
+ XXX.world.inventory.SlotRanges
- XXX.world.inventory.SmithingMenu
+ XXX.world.inventory.SmokerMenu
- XXX.world.inventory.StackedContentsCompatible
+ XXX.world.inventory.StonecutterMenu
- XXX.world.inventory.StonecutterMenu$1
+ XXX.world.inventory.StonecutterMenu$2
- XXX.world.inventory.TransientCraftingContainer
+ XXX.world.item.AdventureModePredicate
- XXX.world.item.AirItem
+ XXX.world.item.AnimalArmorItem
- XXX.world.item.AnimalArmorItem$BodyType
+ XXX.world.item.ArmorItem
- XXX.world.item.ArmorStandItem
+ XXX.world.item.ArrowItem
- XXX.world.item.AxeItem
+ XXX.world.item.BannerItem
- XXX.world.item.BannerPatternItem
+ XXX.world.item.BedItem
- XXX.world.item.BlockItem
+ XXX.world.item.BoatItem
- XXX.world.item.BoneMealItem
+ XXX.world.item.BoneMealItem$1
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BrushItem
+ XXX.world.item.BrushItem$1
- XXX.world.item.BrushItem$DustParticlesDelta
+ XXX.world.item.BucketItem
- XXX.world.item.BundleItem
+ XXX.world.item.BundleItem$1
- XXX.world.item.CompassItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$Builder
+ XXX.world.item.CreativeModeTab$DisplayItemsGenerator
- XXX.world.item.CreativeModeTab$ItemDisplayBuilder
+ XXX.world.item.CreativeModeTab$ItemDisplayParameters
- XXX.world.item.CreativeModeTab$Output
+ XXX.world.item.CreativeModeTab$Row
- XXX.world.item.CreativeModeTab$TabVisibility
+ XXX.world.item.CreativeModeTab$Type
- XXX.world.item.CreativeModeTabs
+ XXX.world.item.CrossbowItem
- XXX.world.item.CrossbowItem$ChargeType
+ XXX.world.item.CrossbowItem$ChargingSounds
- XXX.world.item.DebugStickItem
+ XXX.world.item.DiggerItem
- XXX.world.item.DiscFragmentItem
+ XXX.world.item.DispensibleContainerItem
- XXX.world.item.DoubleHighBlockItem
+ XXX.world.item.DyeColor
- XXX.world.item.DyeItem
+ XXX.world.item.EggItem
- XXX.world.item.EitherHolder
+ XXX.world.item.EmptyMapItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.ExperienceBottleItem
- XXX.world.item.FireChargeItem
+ XXX.world.item.FireworkRocketItem
- XXX.world.item.FireworkStarItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.GlowInkSacItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HangingSignItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneycombItem
- XXX.world.item.InkSacItem
+ XXX.world.item.Instrument
- XXX.world.item.InstrumentItem
+ XXX.world.item.Instruments
- XXX.world.item.Item
+ XXX.world.item.Item$Properties
- XXX.world.item.Item$TooltipContext
+ XXX.world.item.Item$TooltipContext$1
- XXX.world.item.Item$TooltipContext$2
+ XXX.world.item.Item$TooltipContext$3
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemDisplayContext
+ XXX.world.item.ItemFrameItem
+ XXX.world.item.Items
- XXX.world.item.ItemStack
+ XXX.world.item.ItemStack$1
- XXX.world.item.ItemStack$2
+ XXX.world.item.ItemStack$3
- XXX.world.item.ItemStack$4
+ XXX.world.item.ItemStackLinkedSet
- XXX.world.item.ItemStackLinkedSet$1
+ XXX.world.item.ItemUseAnimation
- XXX.world.item.ItemUtils
- XXX.world.item.JukeboxPlayable
+ XXX.world.item.JukeboxSong
- XXX.world.item.JukeboxSongPlayer
+ XXX.world.item.JukeboxSongPlayer$OnSongChanged
- XXX.world.item.JukeboxSongs
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MaceItem
+ XXX.world.item.MapItem
- XXX.world.item.MapItem$1
+ XXX.world.item.MinecartItem
- XXX.world.item.MobBucketItem
+ XXX.world.item.NameTagItem
- XXX.world.item.PickaxeItem
+ XXX.world.item.PlaceOnWaterBlockItem
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileItem
+ XXX.world.item.ProjectileItem$DispenseConfig
- XXX.world.item.ProjectileItem$DispenseConfig$Builder
+ XXX.world.item.ProjectileItem$PositionFunction
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.Rarity
- XXX.world.item.SaddleItem
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignApplicator
+ XXX.world.item.SignItem
- XXX.world.item.SmithingTemplateItem
+ XXX.world.item.SnowballItem
- XXX.world.item.SolidBucketItem
+ XXX.world.item.SpawnEggItem
- XXX.world.item.SpectralArrowItem
+ XXX.world.item.SplashPotionItem
- XXX.world.item.SpyglassItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.SwordItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.TippedArrowItem
+ XXX.world.item.ToolMaterial
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.WindChargeItem
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.client.KeyMapping +1M
```
```
XXX.models.model.ItemModelUtils +1M
```
```
XXX.gui.font.FontTexture -1M
```
```
XXX.gui.screens.LoadingOverlay +1M -1M
```
```
XXX.gui.screens.TitleScreen +1M -1M
```
```
XXX.screens.recipebook.RecipeButton +2M | +1P
```
```
XXX.screens.recipebook.RecipeCollection +1M -2M | +1P -1P
```
```
XXX.client.renderer.Sheets +2M
```
```
XXX.renderer.blockentity.HangingSignRenderer +4M -2M
```
```
XXX.renderer.entity.AbstractSkeletonRenderer +2M
```
```
XXX.properties.conditional.Broken +1M -1M
```
```
XXX.properties.conditional.CustomModelDataProperty +1M -1M
```
```
XXX.renderer.special.SkullSpecialRenderer$Unbaked +4M | +1P
```
```
XXX.renderer.texture.AbstractTexture -1M | -1P
```
```
XXX.renderer.texture.DynamicTexture -1M
```
```
XXX.renderer.texture.TextureManager +10M -13M | -1P
```
```
XXX.minecraft.recipebook.ServerPlaceRecipe +2M -2M
```
```
XXX.server.packs.AbstractPackResources +3M -2M
```
```
XXX.server.packs.CompositePackResources +1M -1M
```
```
XXX.server.packs.PackResources +1P -1P
```
```
XXX.server.packs.VanillaPackResources +1M -1M
```
```
XXX.packs.resources.ResourceMetadata +2M -2M | +1P -1P
```
```
XXX.packs.resources.ResourceMetadata$2 +1M -1M
```
```
XXX.packs.resources.ResourceMetadata$Builder$1 +1M -1M
```
```
XXX.minecraft.sounds.SoundEvents -1P
```
```
XXX.minecraft.tags.ItemTags +5P -5P
```
```
XXX.monster.creaking.Creaking +20M | +9P
```
```
XXX.item.crafting.RecipePropertySet -1M
```
```
XXX.level.block.BannerBlock -1M
```
```
XXX.level.block.BeaconBlock -1M
```
```
XXX.level.block.BrewingStandBlock -1M
```
```
XXX.level.block.ChestBlock -1M
```
```
XXX.level.block.ChiseledBookShelfBlock -1M
```
```
XXX.level.block.ConduitBlock -1M
```
```
XXX.level.block.CrafterBlock -1M
```
```
XXX.level.block.DaylightDetectorBlock -1M
```
```
XXX.level.block.DecoratedPotBlock -1M
```
```
XXX.level.block.DispenserBlock -1M
```
```
XXX.level.block.EndGatewayBlock +1M
```
```
XXX.level.block.EnderChestBlock -1M
```
```
XXX.level.block.GlowLichenBlock -4M | -1P
```
```
XXX.level.block.GrindstoneBlock -1M
```
```
XXX.level.block.JukeboxBlock -1M
```
```
XXX.level.block.RenderShape -1P
```
```
XXX.level.block.SculkCatalystBlock -1M
```
```
XXX.level.block.SculkShriekerBlock -1M
```
```
XXX.level.block.StructureBlock -1M
```
```
XXX.level.block.TrialSpawnerBlock -1M
```
```
XXX.level.block.VaultBlock -1M
```
```
XXX.block.entity.BeehiveBlockEntity +1M -1M
```
```
XXX.block.entity.CreakingHeartBlockEntity +12M -4M | +5P -1P
```
```
XXX.block.piston.MovingPistonBlock +1M
```

</details>
<details>
<summary>
net.minecraft.client.KeyMapping
</summary>

```diff
- KeyMapping get(String)
```

</details>
<details>
<summary>
net.minecraft.client.data.models.model.ItemModelUtils
</summary>

```diff
- ItemModel$Unbaked isXmas(ItemModel$Unbaked,ItemModel$Unbaked)
```

</details>
<details>
<summary>
net.minecraft.client.gui.font.FontTexture
</summary>

```diff
+ void load(ResourceManager)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LoadingOverlay
</summary>

```diff
+ void registerTextures(Minecraft)
- void registerTextures(TextureManager)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.TitleScreen
</summary>

```diff
+ CompletableFuture preloadResources(TextureManager,Executor)
- void registerTextures(TextureManager)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeButton
</summary>

```diff
- boolean allRecipesHaveSameResultDisplay(List)
- Stream lambda$allRecipesHaveSameResultDisplay$1(RecipeButton$ResolvedEntry)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeCollection
</summary>

```diff
+ boolean allRecipesHaveSameResult(List)
+ boolean hasSingleResultItem()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.Sheets
</summary>

```diff
- Material createHangingSignMaterial(ResourceLocation)
- Material createSignMaterial(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.HangingSignRenderer
</summary>

```diff
- Model createSignModel(EntityModelSet,WoodType,HangingSignRenderer$AttachmentType)
- Model getSignModel(BlockState,WoodType)
+ void render(BlockEntity,float,PoseStack,MultiBufferSource,int,int)
+ void render(SignBlockEntity,float,PoseStack,MultiBufferSource,int,int)
- void renderInHand(PoseStack,MultiBufferSource,int,int,Model,Material)
- void translateBase(PoseStack,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.AbstractSkeletonRenderer
</summary>

```diff
- HumanoidModel$ArmPose getArmPose(AbstractSkeleton,HumanoidArm)
- HumanoidModel$ArmPose getArmPose(Mob,HumanoidArm)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.properties.conditional.Broken
</summary>

```diff
- boolean get(ItemStack,ClientLevel,LivingEntity,int,ItemDisplayContext)
+ boolean get(ItemStack,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.properties.conditional.CustomModelDataProperty
</summary>

```diff
- boolean get(ItemStack,ClientLevel,LivingEntity,int,ItemDisplayContext)
+ boolean get(ItemStack,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.SkullSpecialRenderer$Unbaked
</summary>

```diff
- Optional textureOverride()
- ResourceLocation lambda$bake$2(ResourceLocation)
- String lambda$bake$1(String)
- void <init>(SkullBlock$Type,Optional)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.AbstractTexture
</summary>

```diff
+ void reset(TextureManager,ResourceManager,ResourceLocation,Executor)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.DynamicTexture
</summary>

```diff
+ void load(ResourceManager)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.TextureManager
</summary>

```diff
+ AbstractTexture getTexture(ResourceLocation,AbstractTexture)
+ AbstractTexture loadTexture(ResourceLocation,AbstractTexture)
+ CompletableFuture preload(ResourceLocation,Executor)
- CompletableFuture[] lambda$reload$1(int)
+ ResourceLocation register(String,DynamicTexture)
+ String lambda$loadTexture$0(AbstractTexture)
- TextureContents lambda$scheduleLoad$5(ResourceManager,ResourceLocation,ReloadableTexture)
- TextureContents loadContents(ResourceManager,ResourceLocation,ReloadableTexture)
- TextureManager$PendingReload scheduleLoad(ResourceManager,ResourceLocation,ReloadableTexture,Executor)
+ void execute(Runnable)
- void lambda$_dumpAllSheets$4(Path,ResourceLocation,AbstractTexture)
+ void lambda$_dumpAllSheets$7(Path,ResourceLocation,AbstractTexture)
- void lambda$dumpAllSheets$3(Path)
+ void lambda$dumpAllSheets$6(Path)
+ void lambda$execute$2(Runnable)
+ void lambda$preload$1(ResourceLocation,PreloadedTexture)
- void lambda$reload$0(List,ResourceManager,Executor,ResourceLocation,AbstractTexture)
- void lambda$reload$2(List,Void)
+ void lambda$reload$3(CompletableFuture)
+ void lambda$reload$4(ResourceManager,Executor,CompletableFuture,Void)
+ void lambda$reload$5(Runnable)
- void registerAndLoad(ResourceLocation,ReloadableTexture)
- void registerForNextReload(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.recipebook.ServerPlaceRecipe
</summary>

```diff
- int clampToMaxStackSize(int,List)
+ int lambda$placeRecipe$0(Holder)
- void lambda$placeRecipe$0(List,int,Integer,int,int,int)
+ void lambda$placeRecipe$1(int,List,Optional,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.server.packs.AbstractPackResources
</summary>

```diff
+ Object getMetadataFromStream(MetadataSectionSerializer,InputStream)
- Object getMetadataFromStream(MetadataSectionType,InputStream)
+ Object getMetadataSection(MetadataSectionSerializer)
- Object getMetadataSection(MetadataSectionType)
- void lambda$getMetadataFromStream$0(MetadataSectionType,DataResult$Error)
```

</details>
<details>
<summary>
net.minecraft.server.packs.CompositePackResources
</summary>

```diff
+ Object getMetadataSection(MetadataSectionSerializer)
- Object getMetadataSection(MetadataSectionType)
```

</details>
<details>
<summary>
net.minecraft.server.packs.VanillaPackResources
</summary>

```diff
+ Object getMetadataSection(MetadataSectionSerializer)
- Object getMetadataSection(MetadataSectionType)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.ResourceMetadata
</summary>

```diff
+ void copySection(ResourceMetadata$Builder,MetadataSectionSerializer)
- void copySection(ResourceMetadata$Builder,MetadataSectionType)
+ void lambda$copySection$1(ResourceMetadata$Builder,MetadataSectionSerializer,Object)
- void lambda$copySection$1(ResourceMetadata$Builder,MetadataSectionType,Object)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.ResourceMetadata$2
</summary>

```diff
+ Optional getSection(MetadataSectionSerializer)
- Optional getSection(MetadataSectionType)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.ResourceMetadata$Builder$1
</summary>

```diff
+ Optional getSection(MetadataSectionSerializer)
- Optional getSection(MetadataSectionType)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.creaking.Creaking
</summary>

```diff
- boolean canAddPassenger(Entity)
- boolean canUsePortal(boolean)
- boolean couldAcceptPassenger()
- boolean fireImmune()
- boolean hasGlowingEyes()
- boolean hurtServer(ServerLevel,DamageSource,float)
- boolean isTearingDown()
- boolean isTransient()
- boolean playerIsStuckInYou()
- PathNavigation createNavigation(Level)
- Player blameSourceForDamage(DamageSource)
- void addAdditionalSaveData(CompoundTag)
- void addPassenger(Entity)
- void checkEyeBlink()
- void creakingDeathEffects(DamageSource)
- void readAdditionalSaveData(CompoundTag)
- void setTearingDown()
- void setTransient(BlockPos)
- void tearDown()
- void tickDeath()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.RecipePropertySet
</summary>

```diff
+ Stream lambda$create$2(Ingredient)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BannerBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeaconBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BrewingStandBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChestBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChiseledBookShelfBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ConduitBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CrafterBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DaylightDetectorBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DecoratedPotBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndGatewayBlock
</summary>

```diff
- RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnderChestBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GlowLichenBlock
</summary>

```diff
+ BlockState updateShape(BlockState,LevelReader,ScheduledTickAccess,BlockPos,Direction,BlockPos,BlockState,RandomSource)
+ boolean canBeReplaced(BlockState,BlockPlaceContext)
+ FluidState getFluidState(BlockState)
+ void createBlockStateDefinition(StateDefinition$Builder)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrindstoneBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.JukeboxBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkCatalystBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkShriekerBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StructureBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TrialSpawnerBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.VaultBlock
</summary>

```diff
+ RenderShape getRenderShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BeehiveBlockEntity
</summary>

```diff
- void addOccupant(Bee)
+ void addOccupant(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.CreakingHeartBlockEntity
</summary>

```diff
+ BlockPos$TraversalNodeStatus lambda$spreadResin$2(Mutable,BlockPos)
- BlockPos$TraversalNodeStatus lambda$spreadResin$4(Mutable,BlockPos)
- Boolean lambda$isProtector$5(Creaking,Creaking)
- Creaking spawnProtector(ServerLevel,CreakingHeartBlockEntity)
+ CreakingTransient spawnProtector(ServerLevel,CreakingHeartBlockEntity)
- Double lambda$distanceToCreaking$1(Creaking)
- Optional getCreakingProtector()
- UUID lambda$saveAdditional$6(UUID)
- void <clinit>()
+ void lambda$creakingHurt$0(BlockPos)
- void lambda$creakingHurt$2(BlockPos)
- void lambda$serverTick$0(CreakingHeartBlockEntity,Creaking)
+ void lambda$spreadResin$1(BlockPos,Consumer)
- void lambda$spreadResin$3(BlockPos,Consumer)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
- void saveAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.MovingPistonBlock
</summary>

```diff
- RenderShape getRenderShape(BlockState)
```

</details>
</details>
<hr/>