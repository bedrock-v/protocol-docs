# EducationLevelSettings

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["EducationLevelSettings"])
  ROOT -->|"Code Builder Default URI"| string["string"]
  ROOT -->|"Code Builder Title"| string["string"]
  ROOT -->|"Can resize Code Builder"| boolean["boolean"]
  ROOT -->|"Disable legacy title bar"| boolean["boolean"]
  ROOT -->|"Post Process Filter"| string["string"]
  ROOT -->|"Screenshot Border Resource Path"| string["string"]
  ROOT -->|"Agent Capabilities"| AgentCapabilities["AgentCapabilities"]
  ROOT -->|"Local Settings"| EducationLocalLevelSettings["EducationLocalLevelSettings"]
  ROOT -->|"(Deprecated) Always False"| boolean["boolean"]
  ROOT -->|"External Link Settings"| ExternalLinkSettings["ExternalLinkSettings"]
```

