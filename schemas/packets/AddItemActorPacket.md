# AddItemActorPacket

`packet` - id **15**

- protocol: 2168
- minecraft: 1.26.40



```mermaid
flowchart LR
  ROOT(["AddItemActorPacket"])
  ROOT -->|"Target Actor ID"| ActorUniqueID["ActorUniqueID"]
  ROOT -->|"Target Runtime ID"| ActorRuntimeID["ActorRuntimeID"]
  ROOT -->|"Item"| NetworkItemStackDescriptor["NetworkItemStackDescriptor"]
  ROOT -->|"Position"| Vec3["Vec3"]
  ROOT -->|"Velocity"| Vec3["Vec3"]
  ROOT -->|"Entity Data"| SynchedActorDataList["SynchedActorDataList"]
  ROOT -->|"Is From Fishing"| boolean["boolean"]
```

