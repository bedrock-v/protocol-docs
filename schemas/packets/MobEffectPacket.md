# MobEffectPacket

`packet` - id **28**

At the start of the game the server sends any mob effects with _sendAdditionalLevelData() if the joining player saved out with them,
and then anytime a mob effect is added, removed, or updated this packet is sent.<br>
It is important for player movement simulation to ensure that the following effects are sent for the player or any client predicted vehicle they are in control of:<br>
- levitation<br>
- slow_falling<br>
- jump<br>
- movement_speed<br>
- movement_slowdown<br>
- weaving

```mermaid
flowchart LR
  ROOT(["MobEffectPacket"])
  ROOT -->|"Target Runtime ID"| ActorRuntimeID["ActorRuntimeID"]
  ROOT -->|"Event ID"| MobEffectPacketPayload__Event["MobEffectPacketPayload__Event"]
  ROOT -->|"Effect ID"| int32["int32"]
  ROOT -->|"Effect Amplifier"| int32["int32"]
  ROOT -->|"Show Particles"| boolean["boolean"]
  ROOT -->|"Effect Duration Ticks"| int32["int32"]
  ROOT -->|"Tick"| PlayerInputTick["PlayerInputTick"]
  ROOT -->|"Ambient"| boolean["boolean"]
```

