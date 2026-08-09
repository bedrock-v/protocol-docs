# PacketViolationWarningPacket

`packet` - id **156**



```mermaid
flowchart LR
  ROOT(["PacketViolationWarningPacket"])
  ROOT -->|"Violation Type"| PacketViolationType["PacketViolationType"]
  ROOT -->|"Violation Severity"| PacketViolationSeverity["PacketViolationSeverity"]
  ROOT -->|"Violation PacketId"| int32["int32"]
  ROOT -->|"Violation Context"| string["string"]
```

