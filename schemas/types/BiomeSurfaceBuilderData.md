# BiomeSurfaceBuilderData

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["BiomeSurfaceBuilderData"])
  ROOT -->|"surface materials"| BiomeSurfaceMaterialData["BiomeSurfaceMaterialData"]
  ROOT -->|"has default overworld surface"| boolean["boolean"]
  ROOT -->|"has swamp surface"| boolean["boolean"]
  ROOT -->|"has frozen ocean surface"| boolean["boolean"]
  ROOT -->|"has the end surface"| boolean["boolean"]
  ROOT -->|"mesa surface"| BiomeMesaSurfaceData["BiomeMesaSurfaceData"]
  ROOT -->|"capped surface"| BiomeCappedSurfaceData["BiomeCappedSurfaceData"]
  ROOT -->|"noise gradient surface"| BiomeNoiseGradientSurfaceData["BiomeNoiseGradientSurfaceData"]
```

