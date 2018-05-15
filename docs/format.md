---
layout: default
title: OpenAPI Initiative Registry
permalink: /registries/format/index.html
---

# Formats Registry

## Contributing

Please raise a [Pull-Request]() or [issue]() to contribute or discuss a registry value.

## Values

|Value|Description|Issue|
|---|---|---|
{% for value in site.format %}| <a href="/registry/format/{{ value.slug }}.html">{{ value.slug }}</a> | {{ value.description }} | {% if value.issue %}<a href="https://github.com/OAI/OpenAPI-Specification/issues/{{ value.issue }}">{{ value.issue }}</a>{% endif %} |
{% endfor %}

