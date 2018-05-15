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
theme: jekyll-theme-dinky
show_downloads: false
---

The `x-twitter` extension is used to hold a reference to the API provider's Twitter account. It can appear as a property of the `contact` object.

```yaml
openapi: 3.0.0
info:
  title: My API
  version: 1.0.0
  contact:
    x-twitter: APIs-guru
```

Used by:

* APIs.guru

