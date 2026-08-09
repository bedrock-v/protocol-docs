# ItemStackResponseInfo

`struct`

```mermaid
flowchart LR
  ROOT(["ItemStackResponseInfo"])
  ROOT -->|"Result"| uint8["uint8"]
  ROOT -->|"Client Request Id"| ItemStackRequestId["ItemStackRequestId"]
  ROOT -->|"Containers"| ItemStackResponseContainerInfo["ItemStackResponseContainerInfo[]"]
```

