# EnvironmentAttributeData

`struct`

```mermaid
flowchart LR
  ROOT(["EnvironmentAttributeData"])
  ROOT -->|"AttributeName"| string["string"]
  ROOT -->|"FromAttribute"| unknown["unknown"]
  ROOT -->|"Attribute"| unknown["unknown"]
  ROOT -->|"ToAttribute"| unknown["unknown"]
  ROOT -->|"CurrentTransitionTicks"| uint32["uint32"]
  ROOT -->|"TotalTransitionTicks"| uint32["uint32"]
  ROOT -->|"Easing"| easing_function["easing_function"]
  ROOT -->|"LocalTransitionTicks"| uint32["uint32"]
  ROOT -->|"NoiseTransition"| boolean["boolean"]
```

