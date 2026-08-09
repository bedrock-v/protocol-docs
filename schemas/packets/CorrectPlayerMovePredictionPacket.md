# CorrectPlayerMovePredictionPacket

`packet` - id **161**

Used only in server authoritative movement mode, see ServerAuthMovementMode documentation.<br>
	Since it is sent to the specified client the target player is implied to be the receiver.<br>
	It is an optional part of the server authoritative protocol. A server could choose to never send this or do all corrections
	through MovePlayerPacket, although doing so would likely provide less smooth results.

```mermaid
flowchart LR
  ROOT(["CorrectPlayerMovePredictionPacket"])
  ROOT -->|"PredictionType"| RewindType["RewindType"]
  ROOT -->|"Pos"| Vec3["Vec3"]
  ROOT -->|"Pos Delta"| Vec3["Vec3"]
  ROOT -->|"Rotation"| Vec2["Vec2"]
  ROOT -->|"VehicleAngularVelocity"| float["float"]
  ROOT -->|"On Ground"| boolean["boolean"]
  ROOT -->|"Tick"| PlayerInputTick["PlayerInputTick"]
```

