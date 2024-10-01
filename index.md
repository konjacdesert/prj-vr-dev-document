# Test io pages

## Specifications

{{ site.collections.specification.docs }}

{% for doc in site.collections %}
<p>{{ doc.label }}</p>
{% endfor %}

{% for doc in site.specification %}
<p>{{ doc.relative_path }}</p>
{% endfor %}
