# GameTestRequestPacket

`packet` - id **194**

- protocol: 2168
- minecraft: 1.26.40



```mermaid
flowchart LR
  ROOT(["GameTestRequestPacket"])
  ROOT -->|"MaxTestsPerBatch"| int32["int32"]
  ROOT -->|"RepeatCount"| int32["int32"]
  ROOT -->|"Rotation"| Rotation["Rotation"]
  ROOT -->|"StopOnFailure"| boolean["boolean"]
  ROOT -->|"TestPos"| BlockPos["BlockPos"]
  ROOT -->|"TestsPerRow"| int32["int32"]
  ROOT -->|"TestName"| string["string"]
```

