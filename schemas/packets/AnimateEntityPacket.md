# AnimateEntityPacket

`packet` - id **158**

- protocol: 2168
- minecraft: 1.26.40

Several properties can be specified in the following order:</br>
	- The name of the animation (a string) that the specified entities are to play.</br>
	- The next state to transition to (a string) once the specified animation is finished playing.</br>
	- The stop expression (a string), the condition that determines when to transition to the next state.</br>
	- The name of an animation controller (a string) that you would like to use.</br>
	- The blend out time (a float), the amount of time to blend out of this animation.</br>
	- A vector of ActorRuntimeIds of the entities that will play the specified animation.

```mermaid
flowchart LR
  ROOT(["AnimateEntityPacket"])
  ROOT -->|"mAnimation"| string["string"]
  ROOT -->|"mNextState"| string["string"]
  ROOT -->|"mStopExpression"| string["string"]
  ROOT -->|"mStopExpressionVersion"| int32["int32"]
  ROOT -->|"mController"| string["string"]
  ROOT -->|"mBlendOutTime"| float["float"]
  ROOT -->|"mRuntimeIds"| ActorRuntimeID["ActorRuntimeID[]"]
```

