# BiomeOverworldGenRulesData

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["BiomeOverworldGenRulesData"])
  ROOT -->|"hills transformations"| BiomeWeightedData["BiomeWeightedData[]"]
  ROOT -->|"mutate transformations"| BiomeWeightedData["BiomeWeightedData[]"]
  ROOT -->|"river transformations"| BiomeWeightedData["BiomeWeightedData[]"]
  ROOT -->|"shore transformations"| BiomeWeightedData["BiomeWeightedData[]"]
  ROOT -->|"pre hills edge"| BiomeConditionalTransformationData["BiomeConditionalTransformationData[]"]
  ROOT -->|"post shore edge"| BiomeConditionalTransformationData["BiomeConditionalTransformationData[]"]
  ROOT -->|"climate"| BiomeWeightedTemperatureData["BiomeWeightedTemperatureData[]"]
```

