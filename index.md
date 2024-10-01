# Test io pages

## Specifications

{% for page in site.pages %}
<p>{{page.url}}</p>
{% endfor %}

{% for page in site.pages %}
    {% if page.layout == 'page' %}
        <a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.link_title }}</a>
    {% endif %}
{% endfor %}