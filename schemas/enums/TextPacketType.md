# TextPacketType

`enum` - wire `uint8`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart TB
  ROOT(["TextPacketType"])
  ROOT --> raw["raw"]
  ROOT --> chat["chat"]
  ROOT --> translate["translate"]
  ROOT --> popup["popup"]
  ROOT --> jukeboxPopup["jukeboxPopup"]
  ROOT --> tip["tip"]
  ROOT --> systemMessage["systemMessage"]
  ROOT --> whisper["whisper"]
  ROOT --> announcement["announcement"]
  ROOT --> textObjectWhisper["textObjectWhisper"]
  ROOT --> textObject["textObject"]
  ROOT --> textObjectAnnouncement["textObjectAnnouncement"]
```

