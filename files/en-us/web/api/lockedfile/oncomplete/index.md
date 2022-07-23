---
title: LockedFile.oncomplete
slug: Web/API/LockedFile/oncomplete
tags:
  - API
  - Files
  - Non Standard
  - Property
  - Reference
  - WebAPI
spec-urls: https://w3c.github.io/filesystem-api/
---
{{APIRef("File System API")}}{{ non-standard_header }}

## Summary

Specifies an event listener to receive {{event("complete")}} events. These events occur each time a read or write operation is successful.

## Syntax

```js
instanceOfLockedFile.oncomplete = funcRef;
```

Where `funcRef` is a function to be called when the {{event("complete")}} event occurs.

## Specifications

{{Specifications}}

## See also

- {{domxref("LockedFile")}}
