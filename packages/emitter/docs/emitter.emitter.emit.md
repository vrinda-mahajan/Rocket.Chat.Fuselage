<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rocket.chat/emitter](./emitter.md) &gt; [Emitter](./emitter.emitter.md) &gt; [emit](./emitter.emitter.emit.md)

## Emitter.emit() method

Calls each of the handlers registered for the event of `type` type, in the order they were registered, passing the supplied argument `e` to each.

<b>Signature:</b>

```typescript
emit<T = any>(type: EventType, e?: T): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  type | [EventType](./emitter.eventtype.md) |  |
|  e | T |  |

<b>Returns:</b>

void
