---
layout: default
theme: jekyll-theme-cayman
show_downloads: false
title: OpenAPI Initiative Registry
---

## Contributing

Please raise a [Pull-Request]() or [issue]() to contribute or discuss a registry value.

### Contents

{% for registry in site.data.registries %}{% unless registry.hidden %}* <a href="/registry/{{ registry.slug }}/index.html">{{ registry.name }}</a>{% endunless %}
{% endfor %}

#### API access

* [registries.json](/registry/api/registries.json)
{% for registry in site.data.registries %}{% unless registry.hidden %}* <a href="/registry/api/{{ registry.slug }}.json">{{ registry.name }}.json</a>{% endunless %}
{% endfor %}

#### RSS feed

* [values.rss](/rss/feed.xml)

