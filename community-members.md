---
layout: page
title: Community Members
description: Project Community Page
group: nav-right
---
{% include JB/setup %}

### {{ site.data.project.short_name }} Mentors

{% if site.data.mentors %}
<table class="table table-hover">
    <tr>
        <th><b>ID</b></th><th><b>Full Name</b></th>
    </tr>
    {% for mentor in site.data.mentors %}
        <tr>
        <td>{{mentor.apache_id}}</td>
        <td>{{mentor.name}}</td>
        </tr>
    {% endfor %}
</table>
{% endif %}


### {{ site.data.project.short_name }} Team Members

{% if site.data.members %}
<table class="table table-hover">
    <tr>
        <th><b>ID</b></th><th><b>Full Name</b></th><th><b>PMC</b></th><th><b>Affiliation</b></th>
    </tr>
    {% for member in site.data.members %}
        <tr>
        <td>{{member.apache_id}}</td>
        <td>{{member.name}}</td>
        <td>{{member.pmc}}</td>
        <td>{{member.affiliation}}</td>
        </tr>
    {% endfor %}
</table>
{% endif %}

