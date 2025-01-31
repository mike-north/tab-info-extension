<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [tab-info](./tab-info.md) &gt; [ContentScriptReadyMessage](./tab-info.contentscriptreadymessage.md)

## ContentScriptReadyMessage interface

A message sent from the content script to the background thread to (1) indicate that the content script has loaded and (2) pass the current page info along

<b>Signature:</b>

```typescript
export interface ContentScriptReadyMessage extends MessageBase<'content_script_ready'> 
```
<b>Extends:</b> [MessageBase](./tab-info.messagebase.md)<!-- -->&lt;'content\_script\_ready'&gt;

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [pageInfo](./tab-info.contentscriptreadymessage.pageinfo.md) | PageInfo |  |

