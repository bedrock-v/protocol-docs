# ContainerOpenPacket

`packet` - id **46**



```mermaid
flowchart LR
  ROOT(["ContainerOpenPacket"])
  ROOT -->|"Container Id"| uint8["uint8"]
  ROOT -->|"Container Type"| uint8["uint8"]
  ROOT -->|"Position"| BlockPos["BlockPos"]
  ROOT -->|"Target Actor ID"| ActorUniqueID["ActorUniqueID"]
```

