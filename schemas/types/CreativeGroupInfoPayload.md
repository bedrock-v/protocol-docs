# CreativeGroupInfoPayload

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["CreativeGroupInfoPayload"])
  ROOT -->|"Creative Category"| uint8["uint8"]
  ROOT -->|"Name"| string["string"]
  ROOT -->|"Group Icon Item"| NetworkItemInstanceDescriptor["NetworkItemInstanceDescriptor"]
```

