# InventorySource

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["InventorySource"])
  ROOT -->|"Source Type"| InventorySourceType["InventorySourceType"]
  ROOT -->|"Container ID"| int8["int8"]
  ROOT -->|"Bit Flags"| InventorySourceFlags["InventorySourceFlags"]
```

