# StructureSettings

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["StructureSettings"])
  ROOT -->|"Structure Palette Name"| string["string"]
  ROOT -->|"Should ignore entities?"| boolean["boolean"]
  ROOT -->|"Should ignore blocks?"| boolean["boolean"]
  ROOT -->|"Should Allow Non Ticking Player and Ticking Area Chunks"| boolean["boolean"]
  ROOT -->|"Structure Size"| BlockPos["BlockPos"]
  ROOT -->|"Structure Offset"| BlockPos["BlockPos"]
  ROOT -->|"Last Edit Player"| ActorUniqueID["ActorUniqueID"]
  ROOT -->|"Rotation"| Rotation["Rotation"]
  ROOT -->|"Mirror"| Mirror["Mirror"]
  ROOT -->|"Animation Mode"| AnimationMode["AnimationMode"]
  ROOT -->|"Animation Seconds"| float["float"]
  ROOT -->|"Integrity Value"| float["float"]
  ROOT -->|"Integrity Seed"| uint32["uint32"]
  ROOT -->|"Rotation Pivot"| Vec3["Vec3"]
```

