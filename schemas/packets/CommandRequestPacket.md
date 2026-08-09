# CommandRequestPacket

`packet` - id **77**



```mermaid
flowchart LR
  ROOT(["CommandRequestPacket"])
  ROOT -->|"Command"| string["string"]
  ROOT -->|"Origin"| CommandOriginData["CommandOriginData"]
  ROOT -->|"IsInternal"| boolean["boolean"]
  ROOT -->|"Version"| CurrentCmdVersion["CurrentCmdVersion"]
```

