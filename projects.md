---
Title: "Projects"

---

<ul>
  {% for project in site.projects %}
    <li>
      <h2>{{ project.title }}</h2>
    </li>
  {% endfor %}
</ul>