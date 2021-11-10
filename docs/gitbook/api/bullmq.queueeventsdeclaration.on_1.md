<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [QueueEventsDeclaration](./bullmq.queueeventsdeclaration.md) &gt; [on](./bullmq.queueeventsdeclaration.on_1.md)

## QueueEventsDeclaration.on() method

Listen to 'added' event.

This event is triggered when a job is created.

<b>Signature:</b>

```typescript
on(event: 'added', listener: (args: {
        jobId: string;
        name: string;
        data: string;
        opts: string;
    }, id: string) => void): this;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  event | 'added' |  listener |
|  listener | (args: { jobId: string; name: string; data: string; opts: string; }, id: string) =&gt; void |  |

<b>Returns:</b>

this
