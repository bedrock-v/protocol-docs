# cerealizer<NetworkItemStackDescriptor>::SerializedData

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["cerealizer<NetworkItemStackDescriptor>::SerializedData"])
  ROOT -->|"Id"| int16["int16"]
  ROOT -->|"Stack size"| uint16["uint16"]
  ROOT -->|"Aux value"| uint32["uint32"]
  ROOT -->|"Net Id Variant"| ItemStackNetIdVariant["ItemStackNetIdVariant"]
  ROOT -->|"Block Runtime Id"| uint32["uint32"]
  ROOT -->|"User Data Buffer"| string["string"]
```

