# PlaySoundPacket

`packet` - id **86**

- protocol: 2168
- minecraft: 1.26.40



```mermaid
flowchart LR
  ROOT(["PlaySoundPacket"])
  ROOT -->|"Name"| string["string"]
  ROOT -->|"Position"| BlockPos["BlockPos"]
  ROOT -->|"Volume"| float["float"]
  ROOT -->|"Pitch"| float["float"]
  ROOT -->|"Loop Count"| int32["int32"]
  ROOT -->|"Server Sound Handle"| ServerSoundHandle["ServerSoundHandle"]
```

