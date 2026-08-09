# SpawnParticleEffectPacket

`packet` - id **118**

This is not used for much anymore, only the Particle command (spawn particle by name at a location) and for ScriptServerSpawnParticleAttachedToActor and ScriptServerSpawnParticleInWorldEvent.

```mermaid
flowchart LR
  ROOT(["SpawnParticleEffectPacket"])
  ROOT -->|"Dimension Id"| uint8["uint8"]
  ROOT -->|"Actor Id"| ActorUniqueID["ActorUniqueID"]
  ROOT -->|"Position"| Vec3["Vec3"]
  ROOT -->|"Effect Name"| string["string"]
  ROOT -->|"Molang Variables"| MolangVariableMap["MolangVariableMap"]
```

