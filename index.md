# This is the Markdown Homepage

## Here are the articles

{% for post in site.posts %}
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}

## Here are my projects
{% for project in site.data.projects %}
  <h3><a href="{{ project.link }}">{{ project.name }}</a></h3>
  <p>{{ project.description }}</p>
{% endfor %}
