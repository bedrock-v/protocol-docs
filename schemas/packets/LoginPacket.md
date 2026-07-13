# LoginPacket

`packet` - id **1**

- protocol: 2168
- minecraft: 1.26.40



```mermaid
flowchart LR
  ROOT(["LoginPacket"])
  ROOT -->|"Client Network Version"| int32["int32"]
  ROOT -->|"Connection Request"| string["string"]
```

