---
layout: default
theme: jekyll-theme-dinky
show_downloads: false
title: OpenAPI Initiative Registry
permalink: /format/index.html
---

# OpenAPI Initiative Formats Registry

## Contributing

Please raise a [Pull-Request]() or [issue]() to contribute or discuss a registry value.

## Values

|Value|Description|Issue|
|---|---|---|
{% for value in site.format %}| <a href="/registry/format/{{ value.slug }}.html">{{ value.slug }}</a> | {{ value.description }} | {{ value.issue }} |
{% endfor %}

