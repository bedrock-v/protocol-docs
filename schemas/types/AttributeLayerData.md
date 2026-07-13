# AttributeLayerData

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["AttributeLayerData"])
  ROOT -->|"Name"| string["string"]
  ROOT -->|"NoiseName"| string["string"]
  ROOT -->|"Dimension"| DimensionType["DimensionType"]
  ROOT -->|"Settings"| AttributeLayerSettings["AttributeLayerSettings"]
  ROOT -->|"Attributes"| EnvironmentAttributeData["EnvironmentAttributeData[]"]
```

