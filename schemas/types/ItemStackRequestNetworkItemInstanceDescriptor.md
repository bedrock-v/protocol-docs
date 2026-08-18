# ItemStackRequestNetworkItemInstanceDescriptor

`struct`

```mermaid
flowchart LR
  ROOT(["ItemStackRequestNetworkItemInstanceDescriptor"])
  ROOT -->|"Item Descriptor"| EmptyItemDescriptor___ItemNameDescriptor___MolangItemDescriptor___ItemTagDescriptor["EmptyItemDescriptor | ItemNameDescriptor | MolangItemDescriptor | ItemTagDescriptor"]
  ROOT -->|"Stack size"| uint16["uint16"]
  ROOT -->|"Block Runtime Id"| uint32["uint32"]
  ROOT -->|"User Data Buffer"| string["string"]
```

