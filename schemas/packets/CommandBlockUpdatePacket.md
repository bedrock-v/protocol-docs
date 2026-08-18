# CommandBlockUpdatePacket

`packet` - id **78**

Sent when you close the command block screen on the client.

```mermaid
flowchart LR
  ROOT(["CommandBlockUpdatePacket"])
  ROOT -->|"Target"| EntityCommandTarget___BlockCommandData["EntityCommandTarget | BlockCommandData"]
  ROOT -->|"Command"| string["string"]
  ROOT -->|"Last Output"| string["string"]
  ROOT -->|"Name"| string["string"]
  ROOT -->|"FilteredName"| string["string"]
  ROOT -->|"Track Output"| boolean["boolean"]
  ROOT -->|"Tick Delay"| int32["int32"]
  ROOT -->|"Execute On First Tick"| boolean["boolean"]
```

