# BiomeConsolidatedFeatureData

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["BiomeConsolidatedFeatureData"])
  ROOT -->|"scatter"| BiomeScatterParamData["BiomeScatterParamData"]
  ROOT -->|"feature"| uint16["uint16"]
  ROOT -->|"identifier"| uint16["uint16"]
  ROOT -->|"pass"| uint16["uint16"]
  ROOT -->|"can use internal feature"| boolean["boolean"]
```

