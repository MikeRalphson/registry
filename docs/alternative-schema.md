---
layout: default
permalink: /registries/alternative-schema/index.html
---

# OpenAPI Initiative Alternative Schema Type Registry

## Contributing

Please raise a [Pull-Request]() or [issue]() to contribute or discuss a registry value.

## Values

|Value|Description|Issue|
|---|---|---|
{% for value in site.alternative-schema %}| <a href="/registry/alternative-schema/{{ value.slug }}.html">{{ value.slug }}</a> | {{ value.description }} | {% if value.issue %}<a href="https://github.com/OAI/OpenAPI-Specification/issues/{{ value.issue }}">{{ value.issue }}</a>{% endif %} |
{% endfor %}

