# ActorPickRequestPacket

`packet` - id **35**

- protocol: 2168
- minecraft: 1.26.40



```mermaid
flowchart LR
  ROOT(["ActorPickRequestPacket"])
  ROOT -->|"Actor ID"| int64["int64"]
  ROOT -->|"Max Slots"| uint8["uint8"]
  ROOT -->|"With Data"| boolean["boolean"]
```

