# ContainerClosePacket

`packet` - id **47**



```mermaid
flowchart LR
  ROOT(["ContainerClosePacket"])
  ROOT -->|"Container Id"| uint8["uint8"]
  ROOT -->|"Container Type"| uint8["uint8"]
  ROOT -->|"Server Initiated Close"| boolean["boolean"]
```

