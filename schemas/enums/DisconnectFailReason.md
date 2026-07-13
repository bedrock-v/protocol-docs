# DisconnectFailReason

`enum` - wire `int32`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart TB
  ROOT(["DisconnectFailReason"])
  ROOT --> Unknown["Unknown"]
  ROOT --> CantConnectNoInternet["CantConnectNoInternet"]
  ROOT --> NoPermissions["NoPermissions"]
  ROOT --> UnrecoverableError["UnrecoverableError"]
  ROOT --> ThirdPartyBlocked["ThirdPartyBlocked"]
  ROOT --> ThirdPartyNoInternet["ThirdPartyNoInternet"]
  ROOT --> ThirdPartyBadIP["ThirdPartyBadIP"]
  ROOT --> ThirdPartyNoServerOrServerLocked["ThirdPartyNoServerOrServerLocked"]
  ROOT --> VersionMismatch["VersionMismatch"]
  ROOT --> SkinIssue["SkinIssue"]
  ROOT --> InviteSessionNotFound["InviteSessionNotFound"]
  ROOT --> EduLevelSettingsMissing["EduLevelSettingsMissing"]
  ROOT --> LocalServerNotFound["LocalServerNotFound"]
  ROOT --> LegacyDisconnect["LegacyDisconnect"]
  ROOT --> INTERNAL_UserLeaveGameAttempted["INTERNAL_UserLeaveGameAttempted"]
  ROOT --> PlatformLockedSkinsError["PlatformLockedSkinsError"]
  ROOT --> RealmsWorldUnassigned["RealmsWorldUnassigned"]
  ROOT --> RealmsServerCantConnect["RealmsServerCantConnect"]
  ROOT --> RealmsServerHidden["RealmsServerHidden"]
  ROOT --> RealmsServerDisabledBeta["RealmsServerDisabledBeta"]
  ROOT --> RealmsServerDisabled["RealmsServerDisabled"]
  ROOT --> CrossPlatformDisabled["CrossPlatformDisabled"]
  ROOT --> TESTONLY_CantConnect["TESTONLY_CantConnect"]
  ROOT --> SessionNotFound["SessionNotFound"]
  ROOT --> ClientSettingsIncompatibleWithServer["ClientSettingsIncompatibleWithServer"]
  ROOT --> ServerFull["ServerFull"]
  ROOT --> InvalidPlatformSkin["InvalidPlatformSkin"]
  ROOT --> EditionVersionMismatch["EditionVersionMismatch"]
  ROOT --> EditionMismatch["EditionMismatch"]
  ROOT --> LevelNewerThanExeVersion["LevelNewerThanExeVersion"]
  ROOT --> INTERNAL_NoFailOccurred["INTERNAL_NoFailOccurred"]
  ROOT --> BannedSkin["BannedSkin"]
  ROOT --> Timeout["Timeout"]
  ROOT --> ServerNotFound["ServerNotFound"]
  ROOT --> OutdatedServer["OutdatedServer"]
  ROOT --> OutdatedClient["OutdatedClient"]
  ROOT --> NoPremiumPlatform["NoPremiumPlatform"]
  ROOT --> MultiplayerDisabled["MultiplayerDisabled"]
  ROOT --> NoWiFi["NoWiFi"]
  ROOT --> WorldCorruption["WorldCorruption"]
  ROOT --> more["... 108 more"]
```

