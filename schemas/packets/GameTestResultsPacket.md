# GameTestResultsPacket

`packet` - id **195**

- protocol: 2168
- minecraft: 1.26.40

Internal Text Packet

```mermaid
flowchart LR
  ROOT(["GameTestResultsPacket"])
  ROOT -->|"Succeeded"| boolean["boolean"]
  ROOT -->|"Error"| string["string"]
  ROOT -->|"TestName"| string["string"]
```

