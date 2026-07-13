# PlayerActionType

`enum` - wire `int32`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart TB
  ROOT(["PlayerActionType"])
  ROOT --> Unknown["Unknown"]
  ROOT --> StartDestroyBlock["StartDestroyBlock"]
  ROOT --> AbortDestroyBlock["AbortDestroyBlock"]
  ROOT --> StopDestroyBlock["StopDestroyBlock"]
  ROOT --> StartSleeping["StartSleeping"]
  ROOT --> StopSleeping["StopSleeping"]
  ROOT --> Respawn["Respawn"]
  ROOT --> StartJump["StartJump"]
  ROOT --> StartSprinting["StartSprinting"]
  ROOT --> StopSprinting["StopSprinting"]
  ROOT --> StartSneaking["StartSneaking"]
  ROOT --> StopSneaking["StopSneaking"]
  ROOT --> CreativeDestroyBlock["CreativeDestroyBlock"]
  ROOT --> ChangeDimensionAck["ChangeDimensionAck"]
  ROOT --> StartGliding["StartGliding"]
  ROOT --> StopGliding["StopGliding"]
  ROOT --> DenyDestroyBlock["DenyDestroyBlock"]
  ROOT --> CrackBlock["CrackBlock"]
  ROOT --> StartSwimming["StartSwimming"]
  ROOT --> StopSwimming["StopSwimming"]
  ROOT --> StartSpinAttack["StartSpinAttack"]
  ROOT --> StopSpinAttack["StopSpinAttack"]
  ROOT --> PredictDestroyBlock["PredictDestroyBlock"]
  ROOT --> ContinueDestroyBlock["ContinueDestroyBlock"]
  ROOT --> StartItemUseOn["StartItemUseOn"]
  ROOT --> StopItemUseOn["StopItemUseOn"]
  ROOT --> HandledTeleport["HandledTeleport"]
  ROOT --> MissedSwing["MissedSwing"]
  ROOT --> StartCrawling["StartCrawling"]
  ROOT --> StopCrawling["StopCrawling"]
  ROOT --> StartFlying["StartFlying"]
  ROOT --> StopFlying["StopFlying"]
  ROOT --> StartUsingItem["StartUsingItem"]
  ROOT --> InternalUpdate["InternalUpdate"]
  ROOT --> Count["Count"]
```

