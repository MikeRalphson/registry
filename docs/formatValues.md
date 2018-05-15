---
layout: default
theme: jekyll-theme-cayman
show_downloads: false
title: OpenAPI Initiative Registry
---

{% assign slug = "format" %}

{% assign registry = false %}
{% for reg in site.data.registries %}{% if reg.slug == slug %}{% registry = reg %}{% endif %}
{% endfor %}

# OpenAPI Initiative {% registry.name %}

## Contributing

Please raise a [Pull-Request]() or [issue]() to contribute or discuss a registry value.

## Values

|Value|Description|Issue|
|---|---|---|
{% for value in site.data.values %}{% if value.registry == registry.slug %}| {{ value.slug }} | {{ value.description }} | {{ value.issue }} |{% endif %}
{% endfor %}

