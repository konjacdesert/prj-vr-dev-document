# Test io pages

{% for section in site.data.pages %}
  {% for page in section.pages %}
  {% capture path %}_{{ section.prefix }}/{{page}}.md{% endcapture %}
    <p>
    {% assign content = site.Jekyll | where:"path", path | first %}
    {{content.title}}
    </p>
    <p>
    {{content.url}}
    </p>
  {% endfor %}
{% endfor %}
