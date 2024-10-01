# Test io pages

## Specifications

{% for page in site.pages %}
<p>{{page.url}}</p>
{% endfor %}
