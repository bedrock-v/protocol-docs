# ItemRegistryPacket

`packet` - id **162**

This packet needs to be sent immediately after the StartGamePacket for primary clients.

```mermaid
flowchart LR
  ROOT(["ItemRegistryPacket"])
  ROOT -->|"Item Data"| ItemData["ItemData[]"]
```

