# ItemStackNetResult

`enum` - wire `uint8`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart TB
  ROOT(["ItemStackNetResult"])
  ROOT --> Success["Success"]
  ROOT --> Error["Error"]
  ROOT --> InvalidRequestActionType["InvalidRequestActionType"]
  ROOT --> ActionRequestNotAllowed["ActionRequestNotAllowed"]
  ROOT --> ScreenHandlerEndRequestFailed["ScreenHandlerEndRequestFailed"]
  ROOT --> ItemRequestActionHandlerCommitFailed["ItemRequestActionHandlerCommitFailed"]
  ROOT --> InvalidRequestCraftActionType["InvalidRequestCraftActionType"]
  ROOT --> InvalidCraftRequest["InvalidCraftRequest"]
  ROOT --> InvalidCraftRequestScreen["InvalidCraftRequestScreen"]
  ROOT --> InvalidCraftResult["InvalidCraftResult"]
  ROOT --> InvalidCraftResultIndex["InvalidCraftResultIndex"]
  ROOT --> InvalidCraftResultItem["InvalidCraftResultItem"]
  ROOT --> InvalidItemNetId["InvalidItemNetId"]
  ROOT --> MissingCreatedOutputContainer["MissingCreatedOutputContainer"]
  ROOT --> FailedToSetCreatedItemOutputSlot["FailedToSetCreatedItemOutputSlot"]
  ROOT --> RequestAlreadyInProgress["RequestAlreadyInProgress"]
  ROOT --> FailedToInitSparseContainer["FailedToInitSparseContainer"]
  ROOT --> ResultTransferFailed["ResultTransferFailed"]
  ROOT --> ExpectedItemSlotNotFullyConsumed["ExpectedItemSlotNotFullyConsumed"]
  ROOT --> ExpectedAnywhereItemNotFullyConsumed["ExpectedAnywhereItemNotFullyConsumed"]
  ROOT --> ItemAlreadyConsumedFromSlot["ItemAlreadyConsumedFromSlot"]
  ROOT --> ConsumedTooMuchFromSlot["ConsumedTooMuchFromSlot"]
  ROOT --> MismatchSlotExpectedConsumedItem["MismatchSlotExpectedConsumedItem"]
  ROOT --> MismatchSlotExpectedConsumedItemNetIdVariant["MismatchSlotExpectedConsumedItemNetIdVariant"]
  ROOT --> FailedToMatchExpectedSlotConsumedItem["FailedToMatchExpectedSlotConsumedItem"]
  ROOT --> FailedToMatchExpectedAllowedAnywhereConsumedItem["FailedToMatchExpectedAllowedAnywhereConsumedItem"]
  ROOT --> ConsumedItemOutOfAllowedSlotRange["ConsumedItemOutOfAllowedSlotRange"]
  ROOT --> ConsumedItemNotAllowed["ConsumedItemNotAllowed"]
  ROOT --> PlayerNotInCreativeMode["PlayerNotInCreativeMode"]
  ROOT --> InvalidExperimentalRecipeRequest["InvalidExperimentalRecipeRequest"]
  ROOT --> FailedToCraftCreative["FailedToCraftCreative"]
  ROOT --> FailedToGetLevelRecipe["FailedToGetLevelRecipe"]
  ROOT --> FailedToFindRecipeByNetId["FailedToFindRecipeByNetId"]
  ROOT --> MismatchedCraftingSize["MismatchedCraftingSize"]
  ROOT --> MissingInputSparseContainer["MissingInputSparseContainer"]
  ROOT --> MismatchedRecipeForInputGridItems["MismatchedRecipeForInputGridItems"]
  ROOT --> EmptyCraftResults["EmptyCraftResults"]
  ROOT --> FailedToEnchant["FailedToEnchant"]
  ROOT --> MissingInputItem["MissingInputItem"]
  ROOT --> InsufficientPlayerLevelToEnchant["InsufficientPlayerLevelToEnchant"]
  ROOT --> more["... 28 more"]
```

