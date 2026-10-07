---
layout: splash
title: Projects
permalink: /projects/
author_profile: true
---
<br>
Main Project


<div class="">
    <dl>
        {% for project in site.data.projects %}
                <dt>
                    <a href="{{ project.github }}">{{ project.name }}</a>
                </dt>
                <dd>
                    <i>{{project.language}}</i>
                    {{ project.description | markdownify }}
                </dd>
            
        {% endfor %}
    </dl>


</div>
---


Smaller Project

<div class="">
    <dl>
        {% for project in site.data.miniprojects %}
                <dt>
                    <a href="{{ project.github }}">{{ project.name }}</a>
                </dt>
                <dd>
                    <i>{{project.language}}</i>
                    {{ project.description | markdownify }}
                </dd>
            
        {% endfor %}
    </dl>


</div>
---