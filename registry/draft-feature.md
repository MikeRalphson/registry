---
layout: default
permalink: /registries/draft-feature/index.html
---

# Draft Features Registry

## Master Issue

* [#1531](https://github.com/OAI/OpenAPI-Specification/pull/1531)

## Contributing

Please raise a [Pull-Request]() or [issue]() to contribute or discuss a registry value.

## Values

|Value|Description|Issue|
|---|---|---|
{% for value in site.draft-feature %}| <a href="/draft-feature/{{ value.slug }}.html">{{ value.slug }}</a> | {{ value.description }} | {% if value.issue %}<a href="https://github.com/OAI/OpenAPI-Specification/issues/{{ value.issue }}">#{{ value.issue }}</a>{% endif %} |
{% endfor %}

