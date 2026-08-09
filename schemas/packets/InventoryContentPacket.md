# InventoryContentPacket

`packet` - id **49**



```mermaid
flowchart LR
  ROOT(["InventoryContentPacket"])
  ROOT -->|"Container Id"| uint32["uint32"]
  ROOT -->|"Slots"| NetworkItemStackDescriptor["NetworkItemStackDescriptor[]"]
  ROOT -->|"Full Container Name"| FullContainerName["FullContainerName"]
  ROOT -->|"Storage Item"| NetworkItemStackDescriptor["NetworkItemStackDescriptor"]
```

