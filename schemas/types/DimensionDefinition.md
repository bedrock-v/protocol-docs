# DimensionDefinition

`struct`

```mermaid
flowchart LR
  ROOT(["DimensionDefinition"])
  ROOT -->|"Minimum Y"| int32["int32"]
  ROOT -->|"Height Range"| int32["int32"]
  ROOT -->|"Generator Type"| int32["int32"]
  ROOT -->|"Dimension Type"| DimensionType["DimensionType"]
  ROOT -->|"Pack Id"| mce__UUID["mce__UUID"]
  ROOT -->|"Default Biome"| string["string"]
```

