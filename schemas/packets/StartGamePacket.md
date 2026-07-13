# StartGamePacket

`packet` - id **11**

- protocol: 2168
- minecraft: 1.26.40

The player movement mode is also specified here, see ServerAuthMovementMode enum documentation for details on the modes.

```mermaid
flowchart LR
  ROOT(["StartGamePacket"])
  ROOT -->|"Entity ID"| ActorUniqueID["ActorUniqueID"]
  ROOT -->|"Runtime ID"| ActorRuntimeID["ActorRuntimeID"]
  ROOT -->|"Game Type"| int32["int32"]
  ROOT -->|"Position"| Vec3["Vec3"]
  ROOT -->|"Rotation"| Vec2["Vec2"]
  ROOT -->|"Settings"| LevelSettings["LevelSettings"]
  ROOT -->|"Level ID"| string["string"]
  ROOT -->|"Level Name"| string["string"]
  ROOT -->|"Template Content Identity"| string["string"]
  ROOT -->|"Is Trial"| boolean["boolean"]
  ROOT -->|"Movement Settings"| SyncedPlayerMovementSettings["SyncedPlayerMovementSettings"]
  ROOT -->|"Level Current Time"| uint64["uint64"]
  ROOT -->|"Enchantment Seed"| int32["int32"]
  ROOT -->|"Block Properties"| ServerBlockProperty["ServerBlockProperty[]"]
  ROOT -->|"Multiplayer Correlation Id"| string["string"]
  ROOT -->|"Enable Item Stack Net Manager"| boolean["boolean"]
  ROOT -->|"Server Version"| string["string"]
  ROOT -->|"Player Property Data"| unknown["unknown"]
  ROOT -->|"Server Block Type Registry Checksum"| uint64["uint64"]
  ROOT -->|"World Template ID"| mce__UUID["mce__UUID"]
  ROOT -->|"Server Enabled ClientSide Generation"| boolean["boolean"]
  ROOT -->|"BlockNetworkIds Are Hashes"| boolean["boolean"]
  ROOT -->|"NetworkPermissions"| NetworkPermissions["NetworkPermissions"]
  ROOT -->|"Server Configuration Join Info"| server_config["server_config"]
  ROOT -->|"Server Telemetry Data"| ServerTelemetryData["ServerTelemetryData"]
```

