# NoiseTransitionAttributeData

`struct`

```mermaid
flowchart LR
  ROOT(["NoiseTransitionAttributeData"])
  ROOT -->|"FromAttribute"| BoolAttributeData___FloatAttributeData___ColorAttributeData___StringAttributeData["BoolAttributeData | FloatAttributeData | ColorAttributeData | StringAttributeData"]
  ROOT -->|"ToAttribute"| BoolAttributeData___FloatAttributeData___ColorAttributeData___StringAttributeData["BoolAttributeData | FloatAttributeData | ColorAttributeData | StringAttributeData"]
  ROOT -->|"Settings"| NoiseTransitionSettingsData["NoiseTransitionSettingsData"]
```

