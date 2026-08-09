# TextPacket

`packet` - id **9**

Used for commands, messages, and other info printed to the screen. Most of which are server->client or server broadcasted to all clients, but some cases have a client to other client via the server

```mermaid
flowchart LR
  ROOT(["TextPacket"])
  ROOT -->|"Localize?"| boolean["boolean"]
  ROOT -->|"Body"| unknown["unknown"]
  ROOT -->|"Sender's XUID"| string["string"]
  ROOT -->|"Platform Id"| string["string"]
  ROOT -->|"Filtered Message"| string["string"]
```

