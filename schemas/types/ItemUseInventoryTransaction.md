# ItemUseInventoryTransaction

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["ItemUseInventoryTransaction"])
  ROOT -->|"Actions"| InventoryTransaction["InventoryTransaction"]
  ROOT -->|"Action Type"| ItemUseActionType["ItemUseActionType"]
  ROOT -->|"Trigger Type"| ItemUseTriggerType["ItemUseTriggerType"]
  ROOT -->|"Position"| BlockPos["BlockPos"]
  ROOT -->|"Face"| uint8["uint8"]
  ROOT -->|"Slot"| int32["int32"]
  ROOT -->|"Item"| NetworkItemStackDescriptor["NetworkItemStackDescriptor"]
  ROOT -->|"From Position"| Vec3["Vec3"]
  ROOT -->|"Click Position"| Vec3["Vec3"]
  ROOT -->|"Target Block Id"| uint32["uint32"]
  ROOT -->|"Client Interact Prediction"| ItemUsePredictedResult["ItemUsePredictedResult"]
  ROOT -->|"Client Cooldown State"| ItemUseClientCooldownState["ItemUseClientCooldownState"]
```

