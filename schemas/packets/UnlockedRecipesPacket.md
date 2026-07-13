# UnlockedRecipesPacket

`packet` - id **199**

- protocol: 2168
- minecraft: 1.26.40



```mermaid
flowchart LR
  ROOT(["UnlockedRecipesPacket"])
  ROOT -->|"Packet Type"| UnlockedRecipesPacketPayload__PacketType["UnlockedRecipesPacketPayload__PacketType"]
  ROOT -->|"Unlocked Recipes List"| string["string[]"]
```

