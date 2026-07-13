# InventoryAction

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["InventoryAction"])
  ROOT -->|"Source"| InventorySource["InventorySource"]
  ROOT -->|"Slot"| uint32["uint32"]
  ROOT -->|"From Item"| NetworkItemStackDescriptor["NetworkItemStackDescriptor"]
  ROOT -->|"To Item"| NetworkItemStackDescriptor["NetworkItemStackDescriptor"]
```

