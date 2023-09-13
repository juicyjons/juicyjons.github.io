{% for project in site.data.projects %}
  ### <a href="{{ project.link }}">{{ project.name }}</a>

  {{ project.description }}

  **Organisation**:  *{{ project.organisation }}*

  **Tools**: *{{ project.tools }}*

{% endfor %}
