# Test io pages

## Specifications

{% for page in site.pages %}
<p>{{page.url}}</p>
{% endfor %}

{{ site.collections.specifications.docs }}

{% for doc in site.collections %}
<p>{{ doc.label }}</p>
<p>{{ doc.docs }}</p>
{% endfor %}

{% for doc in site.specifications %}
<p>{{ doc.relative_path }}</p>
{% endfor %}
