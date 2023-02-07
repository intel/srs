---
layout: default
---

Scaling Repo Scanner is a Github Actions framework to perform various code-analytics tasks on publicly available Github Repositories.

## Scan logs

{% assign scans_by_year = site.data.scans | group_by: "year" | sort_by: "name" %}
<ul>
{% for scan_year in scans_by_year %}
{% assign scans = scan_year.items %}
  <li><b>{{ scan_year.name }}</b>
    <ul>
    {% for scan in scans %}
    <li><a href="./{{ scan.id }}">{{ scan.date }}</a>: {{ scan.bugs }} bugs</li>
    {% endfor %}
    </ul>
  </li>
{% endfor %}
</ul>
