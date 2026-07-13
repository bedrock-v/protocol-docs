# mce::UUID

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["mce::UUID"])
  ROOT -->|"Most Significant Bits"| uint64["uint64"]
  ROOT -->|"Least Significant Bits"| uint64["uint64"]
```

