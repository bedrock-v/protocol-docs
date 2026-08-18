# MoveActorDeltaData

`struct`

```mermaid
flowchart LR
  ROOT(["MoveActorDeltaData"])
  ROOT -->|"Actor Runtime ID"| ActorRuntimeID["ActorRuntimeID"]
  ROOT -->|"New Position X"| float["float"]
  ROOT -->|"New Position Y"| float["float"]
  ROOT -->|"New Position Z"| float["float"]
  ROOT -->|"Rotation X"| int8["int8"]
  ROOT -->|"Rotation Y"| int8["int8"]
  ROOT -->|"Rotation Y Head"| int8["int8"]
  ROOT -->|"Is On Ground"| boolean["boolean"]
  ROOT -->|"Force Move"| boolean["boolean"]
  ROOT -->|"Force Move Local Entity"| boolean["boolean"]
  ROOT -->|"Force Completion"| boolean["boolean"]
  ROOT -->|"Ticks"| uint64["uint64"]
```

