{%- for repository in site.github.public_repositories -%}
{% if repository.name contains "springboot" or repository.topics contains "springboot" %}
  * [{{ repository.name }}]({{ repository.html_url }})
{%- endif -%}
{%- endfor %}
