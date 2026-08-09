# DeathInfoPacket

`packet` - id **189**

mDeathCauseMessage: is untranslated cause of death string vector returned from ActorDamageSource

```mermaid
flowchart LR
  ROOT(["DeathInfoPacket"])
  ROOT -->|"Death Cause Message"| DeathCauseMessageType["DeathCauseMessageType"]
```

