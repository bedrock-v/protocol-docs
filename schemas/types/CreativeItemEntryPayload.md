# CreativeItemEntryPayload

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["CreativeItemEntryPayload"])
  ROOT -->|"Creative Net Id"| CreativeItemNetId["CreativeItemNetId"]
  ROOT -->|"Item Instance"| NetworkItemInstanceDescriptor["NetworkItemInstanceDescriptor"]
  ROOT -->|"Group Index"| uint32["uint32"]
```

