---
slug: commonmark
owner: MikeRalphson
description: commonmark-formatted text
layout: default
---

# {{ page.collection }}

## {{ page.slug }} - {{ page.description }}

Base type: `string`.

The `{{page.slug}}` format represents [CommonMark](https://commonmark.org/) formatted text.

{% if page.issue %}
### GitHub Issue

* [#{{ page.issue }}](https://github.com/OAI/OpenAPI-Specification/issues/{{ page.issue }})
{% endif %}
