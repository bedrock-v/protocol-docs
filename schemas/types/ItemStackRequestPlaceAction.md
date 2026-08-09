# ItemStackRequestPlaceAction

`struct`

```mermaid
flowchart LR
  ROOT(["ItemStackRequestPlaceAction"])
  ROOT -->|"Action type"| ItemStackRequestActionType["ItemStackRequestActionType"]
  ROOT -->|"Amount"| uint8["uint8"]
  ROOT -->|"Source"| ItemStackRequestSlotInfo["ItemStackRequestSlotInfo"]
  ROOT -->|"Destination"| ItemStackRequestSlotInfo["ItemStackRequestSlotInfo"]
```

