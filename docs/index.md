---
layout: default
theme: jekyll-theme-cayman
show_downloads: false
title: OpenAPI Initiative Registry
---

## Contributing

Please raise a [Pull-Request]() or [issue]() to contribute or discuss a registry value.

### Contents

{% for registry in site.data.registries %}{% unless registry.hidden %}* <a href="/{{ registry.slug }}values.html">{{ registry.name }}</a>{% endunless %}
{% endfor %}

#### API access

* [registries.json](/api/registries.json)
* [values.json](/api/values.json)

#### RSS feed

* [values.rss](/rss/feed.xml)

