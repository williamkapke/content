---
title: InstallEvent()
slug: Web/API/InstallEvent/InstallEvent
tags:
  - API
  - Constructor
  - Experimental
  - InstallEvent
  - Reference
  - Service Workers
  - ServiceWorker
browser-compat: api.InstallEvent.InstallEvent
---

{{APIRef("Service Workers API")}}

{{non-standard_header}}{{deprecated_header}}{{SeeCompatTable}}

The **`InstallEvent()`** constructor creates a new {{domxref("InstallEvent")}} object.

## Syntax

```js
new InstallEvent(type, options)
```

### Parameters

- `type`
  - : A string with the name of the event.
    It is case-sensitive and browsers always set it to `install`.
- `options`
  - : An object that, _in addition of the properties defined in {{domxref("Event/Event", "Event()")}}_, can have the following properties:
    - `activeWorker`
      - : The {{domxref("ServiceWorker")}} that is currently actively controlling the page.

## Return value

A new {{domxref("InstallEvent")}} object.

## Specifications

_This feature is no more on the standard track._

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("Promise")}}
- [Fetch API](/en-US/docs/Web/API/Fetch_API)
