
{% for file in site.static_files %}
  {% if file.extname == ".png" or file.extname == ".PNG" %}
* [{{ file.path }}]({{ site.baseurl }}{{ file.path }})
  {% endif %}
{% endfor %}

