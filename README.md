## Welcome to Scooby-IO's Github Page 

{% for repository in site.github.public_repositories %}
  {% if repository.name != "scooby-io.github.io" %}
  * [{{ repository.name }}]({{ repository.html_url }}) {{ repository.description }}
  {% endif %}
{% endfor %}
