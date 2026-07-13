# BiomeDefinitionData

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["BiomeDefinitionData"])
  ROOT -->|"id"| uint16["uint16"]
  ROOT -->|"temperature"| float["float"]
  ROOT -->|"downfall"| float["float"]
  ROOT -->|"foliage snow"| float["float"]
  ROOT -->|"depth"| float["float"]
  ROOT -->|"scale"| float["float"]
  ROOT -->|"map water color ARGB"| int32["int32"]
  ROOT -->|"rain"| boolean["boolean"]
  ROOT -->|"tags"| BiomeTagsData["BiomeTagsData"]
  ROOT -->|"chunk gen data"| BiomeDefinitionChunkGenData["BiomeDefinitionChunkGenData"]
```

