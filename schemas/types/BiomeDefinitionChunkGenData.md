# BiomeDefinitionChunkGenData

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["BiomeDefinitionChunkGenData"])
  ROOT -->|"climate"| BiomeClimateData["BiomeClimateData"]
  ROOT -->|"consolidated features"| BiomeConsolidatedFeaturesData["BiomeConsolidatedFeaturesData"]
  ROOT -->|"mountain params"| BiomeMountainParamsData["BiomeMountainParamsData"]
  ROOT -->|"surface material adjustments"| BiomeSurfaceMaterialAdjustmentData["BiomeSurfaceMaterialAdjustmentData"]
  ROOT -->|"overworld gen rules"| BiomeOverworldGenRulesData["BiomeOverworldGenRulesData"]
  ROOT -->|"multinoise gen rules"| BiomeMultinoiseGenRulesData["BiomeMultinoiseGenRulesData"]
  ROOT -->|"legacy world gen rules"| BiomeLegacyWorldGenRulesData["BiomeLegacyWorldGenRulesData"]
  ROOT -->|"replacement biomes"| BiomeReplacementsData["BiomeReplacementsData"]
  ROOT -->|"Village Type"| VillageType["VillageType"]
  ROOT -->|"surface builder data"| BiomeSurfaceBuilderData["BiomeSurfaceBuilderData"]
  ROOT -->|"subsurface builder data"| BiomeSurfaceBuilderData["BiomeSurfaceBuilderData"]
```

