---
layout: default
theme: jekyll-theme-dinky
show_downloads: false
title: OpenAPI Initiative Registry
permalink: /extension/index.html
---

# OpenAPI Initiative Extensions Registry

## Contributing

Please raise a [Pull-Request]() or [issue]() to contribute or discuss a registry value.

## Values

|Value|Description|Issue|
|---|---|---|
{% for value in site.extension %}| <a href="/registry/extension/{{ value.slug }}.html">{{ value.slug }}</a> | {{ value.description }} | {{ value.issue }} |
{% endfor %}

