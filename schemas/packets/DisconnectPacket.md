# DisconnectPacket

`packet` - id **5**

- protocol: 2168
- minecraft: 1.26.40



```mermaid
flowchart LR
  ROOT(["DisconnectPacket"])
  ROOT -->|"Reason"| DisconnectFailReason["DisconnectFailReason"]
  ROOT -->|"Messages"| unknown["unknown"]
```

