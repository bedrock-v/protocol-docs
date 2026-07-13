# BiomeNoiseGradientSurfaceData

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["BiomeNoiseGradientSurfaceData"])
  ROOT -->|"non-replaceable blocks"| uint32["uint32[]"]
  ROOT -->|"gradient blocks"| SerializedNoiseBlockSpecifier["SerializedNoiseBlockSpecifier[]"]
  ROOT -->|"noise"| NoiseDescriptor["NoiseDescriptor"]
```

