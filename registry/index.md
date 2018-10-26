---
layout: default
title: OpenAPI Initiative Registry
---

## Contributing

Please raise a [Pull-Request]() or [issue]() to contribute or discuss a registry value.

### Contents

{% for registry in site.data.registries %}{% unless registry.hidden %}* <a href="/registries/{{ registry.slug }}/index.html">{{ registry.name }}</a>{% endunless %}
{% endfor %}

#### API access

{% for registry in site.data.registries %}{% unless registry.hidden %}* <a href="/api/{{ registry.slug }}.json">{{ registry.slug }}.json</a>{% endunless %}
{% endfor %}* [registries.json](/api/registries.json)

#### RSS feed

* [values.rss](/rss/feed.xml)

