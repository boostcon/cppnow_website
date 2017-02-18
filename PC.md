---
layout: default
permalink: /PC/
---

<style>

    img[alt="Boost C++ Libraries"]
    {
        display: block;
        margin-left: auto;
        margin-right: auto;
    }

    div.sponsor_name
    {
        text-align: center;
    }

    h2
    {
        text-align: center;
    }

    h3
    {
        text-align: center;
    }

    h4
    {
        font-weight: bold;
    }

    div.PC_member_name
    {
        text-align: left;
    }

</style>

## Program Committee Members

***

Bryce Adelstein Lelbach (Program Chair)
{% for member in site.data[site.current_year].PC.PC %}

<div class="PC_member_name">{{member.name}}{% if member.company %}, {{member.company}}{% endif %}


</div>

{% endfor %}
    
<br>

***
