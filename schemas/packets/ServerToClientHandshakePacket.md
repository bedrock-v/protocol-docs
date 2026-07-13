# ServerToClientHandshakePacket

`packet` - id **3**

- protocol: 2168
- minecraft: 1.26.40

Sent from the server at the end of the login packet

```mermaid
flowchart LR
  ROOT(["ServerToClientHandshakePacket"])
  ROOT -->|"Handshake WebToken"| WebToken["WebToken"]
```

