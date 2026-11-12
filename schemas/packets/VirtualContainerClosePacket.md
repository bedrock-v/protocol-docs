# VirtualContainerClosePacket

`packet` - id **367**

Request is server-to-client. Closed is client-to-server for opening failure, user close, or acknowledgement of a server request. Confirmed is server-to-client after inventory work drains. Successful opening sends no acknowledgement.

```mermaid
flowchart LR
  ROOT(["VirtualContainerClosePacket"])
  ROOT -->|"Session Id"| uint64["uint64"]
  ROOT -->|"Kind"| uint8["uint8"]
  ROOT -->|"Cause"| uint8["uint8"]
```

