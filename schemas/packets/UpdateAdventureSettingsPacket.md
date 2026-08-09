# UpdateAdventureSettingsPacket

`packet` - id **188**

Sent by the server to update the state of AdventureSettings. Replaces the AdventureSettingsPacket for updating AdventureSettings from server to client.

```mermaid
flowchart LR
  ROOT(["UpdateAdventureSettingsPacket"])
  ROOT -->|"Adventure Settings"| AdventureSettings["AdventureSettings"]
```

