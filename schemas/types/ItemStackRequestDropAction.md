# ItemStackRequestDropAction

`struct`

```mermaid
flowchart LR
  ROOT(["ItemStackRequestDropAction"])
  ROOT -->|"Action type"| ItemStackRequestActionType["ItemStackRequestActionType"]
  ROOT -->|"Amount"| uint8["uint8"]
  ROOT -->|"Source"| ItemStackRequestSlotInfo["ItemStackRequestSlotInfo"]
  ROOT -->|"Randomly"| boolean["boolean"]
```

