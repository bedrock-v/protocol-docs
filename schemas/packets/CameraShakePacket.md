# CameraShakePacket

`packet` - id **159**

- protocol: 2168
- minecraft: 1.26.40

It may be used to queue or stop a camera shake

```mermaid
flowchart LR
  ROOT(["CameraShakePacket"])
  ROOT -->|"Intensity"| float["float"]
  ROOT -->|"Seconds"| float["float"]
  ROOT -->|"Shake Type"| CameraShakeType["CameraShakeType"]
  ROOT -->|"Shake Action"| CameraShakeAction["CameraShakeAction"]
```

