# PlayerLocationPacket

`packet` - id **326**

- protocol: 2168
- minecraft: 1.26.40

Sent by PlayerLocationSender when a player position changes beyond a certain angle.

```mermaid
flowchart LR
  ROOT(["PlayerLocationPacket"])
  ROOT -->|"Target Actor ID"| ActorUniqueID["ActorUniqueID"]
  ROOT -->|"Location"| unknown["unknown"]
```

