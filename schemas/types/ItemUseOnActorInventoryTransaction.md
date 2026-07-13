# ItemUseOnActorInventoryTransaction

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["ItemUseOnActorInventoryTransaction"])
  ROOT -->|"Actions"| InventoryTransaction["InventoryTransaction"]
  ROOT -->|"Runtime Id"| ActorRuntimeID["ActorRuntimeID"]
  ROOT -->|"Action Type"| ItemUseOnActorActionType["ItemUseOnActorActionType"]
  ROOT -->|"Slot"| int32["int32"]
  ROOT -->|"Item"| NetworkItemStackDescriptor["NetworkItemStackDescriptor"]
  ROOT -->|"From Position"| Vec3["Vec3"]
  ROOT -->|"Hit Position"| Vec3["Vec3"]
```

