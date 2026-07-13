# Data Store Change

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["Data Store Change"])
  ROOT -->|"Data Store Name"| string["string"]
  ROOT -->|"Property"| string["string"]
  ROOT -->|"Update Count"| uint32["uint32"]
  ROOT -->|"The New Property Value"| unknown["unknown"]
```

