---
slug: x-twitter
name: x-twitter
title: x-twitter
owner: mike_ralphson
issue:
description: Used to hold a reference to the API provider's Twitter account.
schema:
  type: string
objects: [ "contactObject" ]

layout: default
---

The `x-twitter` extension is used to hold a reference to the API provider's Twitter account. It can appear as a property of the `contact` object.

### Schema

```yaml
{{schema}}
```

### Example

```yaml
openapi: 3.0.0
info:
  title: My API
  version: 1.0.0
  contact:
    x-twitter: APIs-guru
```

Used by: (informational)

* APIs.guru

