# UpdatePlayerGameTypePacket

`packet` - id **151**

- protocol: 2168
- minecraft: 1.26.40



```mermaid
flowchart LR
  ROOT(["UpdatePlayerGameTypePacket"])
  ROOT -->|"Player Game Type"| GameType["GameType"]
  ROOT -->|"Target player"| ActorUniqueID["ActorUniqueID"]
  ROOT -->|"Tick"| PlayerInputTick["PlayerInputTick"]
```

