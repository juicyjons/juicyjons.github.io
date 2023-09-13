{% for project in site.data.projects %}
  <h3><a href="{{ project.link }}">{{ project.name }}</a></h3>
  <p>{{ project.description }}</p>
  
  **Organisation**:  {{ project.organisation }}

  **Tools**: {{ project.tools }}
{% endfor %}
