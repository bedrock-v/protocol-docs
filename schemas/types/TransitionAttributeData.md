# TransitionAttributeData

`struct`

```mermaid
flowchart LR
  ROOT(["TransitionAttributeData"])
  ROOT -->|"FromAttribute"| BoolAttributeData___FloatAttributeData___ColorAttributeData___StringAttributeData["BoolAttributeData | FloatAttributeData | ColorAttributeData | StringAttributeData"]
  ROOT -->|"ToAttribute"| BoolAttributeData___FloatAttributeData___ColorAttributeData___StringAttributeData["BoolAttributeData | FloatAttributeData | ColorAttributeData | StringAttributeData"]
  ROOT -->|"Settings"| TransitionSettingsData["TransitionSettingsData"]
```

