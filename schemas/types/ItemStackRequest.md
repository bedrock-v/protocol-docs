# ItemStackRequest

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["ItemStackRequest"])
  ROOT -->|"Client Request Id"| ItemStackRequestId["ItemStackRequestId"]
  ROOT -->|"Actions"| unknown["unknown[]"]
  ROOT -->|"Strings To Filter"| string["string[]"]
  ROOT -->|"StringsToFilterOrigin"| TextProcessingEventOrigin["TextProcessingEventOrigin"]
```

