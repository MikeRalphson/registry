---
layout: default
title: OpenAPI Initiative Registry
permalink: /registries/extension/index.html
---

# OpenAPI Initiative Extensions Registry

## Contributing

Please raise a [Pull-Request]() or [issue]() to contribute or discuss a registry value.

## Values

|Value|Description|Issue|
|---|---|---|
{% for value in site.extension %}| <a href="/registry/extension/{{ value.slug }}.html">{{ value.slug }}</a> | {{ value.description }} | {% if value.issue %}<a href="https://github.com/OAI/OpenAPI-Specification/issues/{{ value.issue }}">{{ value.issue }}</a>{% endif %} |
{% endfor %}

