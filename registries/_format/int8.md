---
slug: int8
name: int8
title: int8
owner: MikeRalphson
issue: 845
description: signed 8-bit integer

layout: default
---

# {{ page.collection }}

## {{ page.title }} - {{ page.description }}

The `{{page.slug}}` format represents a signed 8-bit integer, with the range -128 to 127

### GitHub Issue

* [#{{ page.issue }}](https://github.com/OAI/OpenAPI-Specification/issues/{{ page.issue }})

### Raw data

```json
{{ page || jsonify }}
```
