# GameRulesChangedPacket

`packet` - id **72**

- protocol: 2168
- minecraft: 1.26.40

Informs client about any changes to the game rules.

```mermaid
flowchart LR
  ROOT(["GameRulesChangedPacket"])
  ROOT -->|"Rule Data"| GameRulesChangedPacketData["GameRulesChangedPacketData"]
```

