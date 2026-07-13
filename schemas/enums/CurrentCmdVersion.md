# CurrentCmdVersion

`enum` - wire `int32`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart TB
  ROOT(["CurrentCmdVersion"])
  ROOT --> Invalid["Invalid"]
  ROOT --> Initial["Initial"]
  ROOT --> TpRotationClamping["TpRotationClamping"]
  ROOT --> NewBedrockCmdSystem["NewBedrockCmdSystem"]
  ROOT --> ExecuteUsesVec3["ExecuteUsesVec3"]
  ROOT --> CloneFixes["CloneFixes"]
  ROOT --> UpdateAquatic["UpdateAquatic"]
  ROOT --> EntitySelectorUsesVec3["EntitySelectorUsesVec3"]
  ROOT --> ContainersDontDropItemsAnymore["ContainersDontDropItemsAnymore"]
  ROOT --> FiltersObeyDimensions["FiltersObeyDimensions"]
  ROOT --> ExecuteAndBlockCommandAndSelfSelectorFixes["ExecuteAndBlockCommandAndSelfSelectorFixes"]
  ROOT --> InstantEffectsUseTicks["InstantEffectsUseTicks"]
  ROOT --> DontRegisterBrokenFunctionCommands["DontRegisterBrokenFunctionCommands"]
  ROOT --> ClearSpawnPointCommand["ClearSpawnPointCommand"]
  ROOT --> CloneAndTeleportRotationFixes["CloneAndTeleportRotationFixes"]
  ROOT --> TeleportDimensionFixes["TeleportDimensionFixes"]
  ROOT --> CloneUpdateBlockAndTimeFixes["CloneUpdateBlockAndTimeFixes"]
  ROOT --> CloneIntersectFix["CloneIntersectFix"]
  ROOT --> FunctionExecuteOrderAndChestSlotFix["FunctionExecuteOrderAndChestSlotFix"]
  ROOT --> NonTickingAreasNoLongerConsideredLoaded["NonTickingAreasNoLongerConsideredLoaded"]
  ROOT --> SpreadplayersHazardAndResolvePlayerByNameFix["SpreadplayersHazardAndResolvePlayerByNameFix"]
  ROOT --> NewExecuteCommandSyntaxExperimentAndChestLootTableFixAndTeleportFacingVerticalUnclampedAndLocateBiomeAndFeatureMerged["NewExecuteCommandSyntaxExperimentAndChestLootTableFixAndTeleportFacingVerticalUnclampedAndLocateBiomeAndFeatureMerged"]
  ROOT --> WaterloggingAddedToStructureCommand["WaterloggingAddedToStructureCommand"]
  ROOT --> SelectorDistanceFilteredAndRelativeRotationFix["SelectorDistanceFilteredAndRelativeRotationFix"]
  ROOT --> NewSummonCommandAddedRotationOptionsAndBubbleColumnCloneFixAndExecuteInDimensionTeleportFixAndNewExecuteRotationFix["NewSummonCommandAddedRotationOptionsAndBubbleColumnCloneFixAndExecuteInDimensionTeleportFixAndNewExecuteRotationFix"]
  ROOT --> NewExecuteCommandReleaseEnchantCommandLevelFixAndHasItemDataFixAndCommandDeferral["NewExecuteCommandReleaseEnchantCommandLevelFixAndHasItemDataFixAndCommandDeferral"]
  ROOT --> ExecuteIfScoreFixes["ExecuteIfScoreFixes"]
  ROOT --> ReplaceItemAndLootReplaceBlockCommandsDoNotPlaceItemsIntoCauldronsFix["ReplaceItemAndLootReplaceBlockCommandsDoNotPlaceItemsIntoCauldronsFix"]
  ROOT --> ChangesToCommandOriginRotation["ChangesToCommandOriginRotation"]
  ROOT --> RemoveAuxValueParameterFromBlockCommands["RemoveAuxValueParameterFromBlockCommands"]
  ROOT --> VolumeSelectorFixes["VolumeSelectorFixes"]
  ROOT --> EnableSummonRotation["EnableSummonRotation"]
  ROOT --> SummonCommandDefaultRotation["SummonCommandDefaultRotation"]
  ROOT --> PositionalDimensionFiltering["PositionalDimensionFiltering"]
  ROOT --> CommandSelectorHasItemFilterNoLongerCallsSameItemFunction["CommandSelectorHasItemFilterNoLongerCallsSameItemFunction"]
  ROOT --> AgentSweepingBlockTest["AgentSweepingBlockTest"]
  ROOT --> BlockStateEquals["BlockStateEquals"]
  ROOT --> CommandPositionFix["CommandPositionFix"]
  ROOT --> CommandSelectorHasItemFilterUsesDataAsDamageForSelectingDamageableItems["CommandSelectorHasItemFilterUsesDataAsDamageForSelectingDamageableItems"]
  ROOT --> ExecuteDetectConditionSubcommandNotAllowNonLoadedBlocks["ExecuteDetectConditionSubcommandNotAllowNonLoadedBlocks"]
  ROOT --> more["... 9 more"]
```

