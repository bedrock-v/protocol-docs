# BiomeReplacementData

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["BiomeReplacementData"])
  ROOT -->|"replacement biome"| uint16["uint16"]
  ROOT -->|"dimension"| uint16["uint16"]
  ROOT -->|"target biomes"| uint16["uint16[]"]
  ROOT -->|"amount"| float["float"]
  ROOT -->|"noise frequency scale"| float["float"]
  ROOT -->|"replacement index"| uint32["uint32"]
```

