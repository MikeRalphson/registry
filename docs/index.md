---
layout: default
theme: jekyll-theme-cayman
show_downloads: false
title: OpenAPI Initiative Registry
---

## Contributing

Please raise a [Pull-Request] or [issue] to contribute or discuss a registry value.

### Contents

{% for registry in site.data.registries %}{% if !registry.hidden %}* <a href="/values.html?registry={{ registry.slug }}">{{ registry.name }}</a>{% endif %}
{% endfor %}

#### API access

* [registries.json](/api/registries.json)
* [values.json](/api/values.json)

