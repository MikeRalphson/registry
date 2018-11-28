---
owner: MikeRalphson
description: commonmark-formatted text
layout: default
---

# {{ page.collection }}

## {{ page.name }} - {{ page.description }}

Base type: `string`.

The `{{page.name}}` format represents [CommonMark](https://commonmark.org/) formatted text.

{% if page.issue %}
### GitHub Issue

* [#{{ page.issue }}](https://github.com/OAI/OpenAPI-Specification/issues/{{ page.issue }})
{% endif %}
