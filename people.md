---
title: "People"
permalink: "/people/"
layout: page
--- 

<ul class="list-unstyled list-inline text-center">
        

{% for author in site.authors %}
<li>
        <figure class="figure">
                <img src='../assets/images/{{ author.short_name }}.jpg' alt='{{ author.short_name }}' height="200" width="200"/> 
                <figcaption><strong>{{ author.name }}</strong>
                <br> <strong>{{ author.studyrole }} </strong> <br> <strong>{{ author.position }}</strong> <br> {{ author.bio }} </figcaption>
        </figure> 
        
</li>
{% endfor %}
</ul>

