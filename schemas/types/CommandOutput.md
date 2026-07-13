# CommandOutput

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["CommandOutput"])
  ROOT -->|"Output Type"| CommandOutputType["CommandOutputType"]
  ROOT -->|"Success Count"| uint32["uint32"]
  ROOT -->|"Output Messages"| CommandOutputMessage["CommandOutputMessage[]"]
  ROOT -->|"Data Set"| string["string"]
```

