# BlockEventPacket

`packet` - id **26**

- protocol: 2168
- minecraft: 1.26.40



```mermaid
flowchart LR
  ROOT(["BlockEventPacket"])
  ROOT -->|"Block Position"| BlockPos["BlockPos"]
  ROOT -->|"Event Type"| int32["int32"]
  ROOT -->|"Event Value"| int32["int32"]
```

