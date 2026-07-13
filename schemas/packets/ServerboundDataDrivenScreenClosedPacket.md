# ServerboundDataDrivenScreenClosedPacket

`packet` - id **343**

- protocol: 2168
- minecraft: 1.26.40



```mermaid
flowchart LR
  ROOT(["ServerboundDataDrivenScreenClosedPacket"])
  ROOT -->|"FormId"| uint32["uint32"]
  ROOT -->|"CloseReason"| DataDrivenScreenClosedReason["DataDrivenScreenClosedReason"]
```

