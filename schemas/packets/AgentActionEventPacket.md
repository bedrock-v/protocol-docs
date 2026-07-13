# AgentActionEventPacket

`packet` - id **181**

- protocol: 2168
- minecraft: 1.26.40



```mermaid
flowchart LR
  ROOT(["AgentActionEventPacket"])
  ROOT -->|"Request Id"| string["string"]
  ROOT -->|"Action"| AgentActionType["AgentActionType"]
  ROOT -->|"Response"| Json__Value["Json__Value"]
```

