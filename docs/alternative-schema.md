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
{% for value in site.alternative-schema %}| <a href="/registry/registries/alternative-schema/{{ value.slug }}.html">{{ value.slug }}</a> | {{ value.description }} | {{ value.issue }} |
{% endfor %}

