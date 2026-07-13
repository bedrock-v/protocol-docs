# SpawnExperienceOrbPacket

`packet` - id **66**

- protocol: 2168
- minecraft: 1.26.40

Note: This can be seen as "ContainerWantSetSlotPacket" when sent from client to server. Currently, the client handles side-effects relating to it's own inventory, regardless of the success of the operation.

```mermaid
flowchart LR
  ROOT(["SpawnExperienceOrbPacket"])
  ROOT -->|"Position"| Vec3["Vec3"]
  ROOT -->|"XP Value"| int32["int32"]
```

