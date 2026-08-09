# BiomeConditionalTransformationData

`struct`

```mermaid
flowchart LR
  ROOT(["BiomeConditionalTransformationData"])
  ROOT -->|"transforms into"| BiomeWeightedData["BiomeWeightedData[]"]
  ROOT -->|"condition json"| uint16["uint16"]
  ROOT -->|"min passing neighbors"| uint32["uint32"]
```

