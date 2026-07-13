# DimensionDataPacket

`packet` - id **180**

- protocol: 2168
- minecraft: 1.26.40

Contains dimension definition data including height bounds and generator type for each dimension.

```mermaid
flowchart LR
  ROOT(["DimensionDataPacket"])
  ROOT -->|"Definitions"| object["object"]
```

