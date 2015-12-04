---
layout: page
title: Community Members
description: Project Community Page
group: nav-right
---
<!--
{% comment %}
Licensed to the Apache Software Foundation (ASF) under one or more
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership.
The ASF licenses this file to you under the Apache License, Version 2.0
(the "License"); you may not use this file except in compliance with
the License.  You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
{% endcomment %}
-->

{% include JB/setup %}

<br/><br/><br/>

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

