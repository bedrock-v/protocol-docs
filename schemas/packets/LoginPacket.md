# LoginPacket

`packet` - id **1**



```mermaid
flowchart LR
  ROOT(["LoginPacket"])
  ROOT -->|"Client Network Version"| int32["int32"]
  ROOT -->|"Connection Request"| string["string"]
```

