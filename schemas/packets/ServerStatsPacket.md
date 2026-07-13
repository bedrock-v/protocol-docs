# ServerStatsPacket

`packet` - id **192**

- protocol: 2168
- minecraft: 1.26.40

Sent from server.

```mermaid
flowchart LR
  ROOT(["ServerStatsPacket"])
  ROOT -->|"ServerTime"| float["float"]
  ROOT -->|"NetworkTime"| float["float"]
```

