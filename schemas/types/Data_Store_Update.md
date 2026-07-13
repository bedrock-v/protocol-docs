# Data Store Update

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["Data Store Update"])
  ROOT -->|"Data Store Name"| string["string"]
  ROOT -->|"Property"| string["string"]
  ROOT -->|"Path"| string["string"]
  ROOT -->|"Data"| unknown["unknown"]
  ROOT -->|"Property Update Count"| uint32["uint32"]
  ROOT -->|"Path Update Count"| uint32["uint32"]
```

