---
title: Research Group Members
nav_title: People
layout: default
order: 3
---

# {{ page.title }}

## Lab Director
<table>
{% tablerow p in site.data.people.current.Director %}
{% if p.url %}<a href="{{ p.url }}">{% endif %}
<img src="{{ p.pic }}" alt="{{ p.name }}" title="{{ p.name }}" width="150" /><br />
{{ p.name }}<br />
{% if p.url %}</a>{% endif %}
{{ p.degree }}
{% endtablerow %}
</table>


## Current Students

### PhD Students
<table>
{% tablerow p in site.data.people.current.PhD %}
{% if p.url %}<a href="{{ p.url }}">{% endif %}
<img src="{{ p.pic }}" alt="{{ p.name }}" title="{{ p.name }}" width="150" /><br />
{{ p.name }}<br />
{% if p.url %}</a>{% endif %}
{{ p.degree }}
{% endtablerow %}
</table>

### MS Students
<table>
{% tablerow p in site.data.people.current.MS %}
{% if p.url %}<a href="{{ p.url }}">{% endif %}
<img src="{{ p.pic }}" alt="{{ p.name }}" title="{{ p.name }}" width="150" /><br />
{{ p.name }}<br />
{% if p.url %}</a>{% endif %}
{{ p.degree }}
{% endtablerow %}
</table>

### Undergraduate Students

<table>

{% tablerow p in site.data.people.current.Undergraduate %}
{% if p.url %}<a href="{{ p.url }}">{% endif %}
<img src="{{ p.pic }}" alt="{{ p.name }}" title="{{ p.name }}" width="150" /><br />
{{ p.name }}<br />
{% if p.url %}</a>{% endif %}
{{ p.degree }}
{% endtablerow %}
</table>

## Alumni

### PhD Students
<table>
{% tablerow p in site.data.people.past.PhD %}
{% if p.url %}<a href="{{ p.url }}">{% endif %}
<img src="{{ p.pic }}" alt="{{ p.name }}" title="{{ p.name }}" width="150" /><br />
{{ p.name }}<br />
{% if p.url %}</a>{% endif %}
{{ p.degree }}
{% endtablerow %}
</table>

### MS Students
<table>
{% tablerow p in site.data.people.past.MS %}
{% if p.url %}<a href="{{ p.url }}">{% endif %}
<img src="{{ p.pic }}" alt="{{ p.name }}" title="{{ p.name }}" width="150" /><br />
{{ p.name }}<br />
{% if p.url %}</a>{% endif %}
{{ p.degree }}
{% endtablerow %}
</table>

### Undergraduate Students

<table>

{% tablerow p in site.data.people.past.Undergraduate %}
{% if p.url %}<a href="{{ p.url }}">{% endif %}
<img src="{{ p.pic }}" alt="{{ p.name }}" title="{{ p.name }}" width="150" /><br />
{{ p.name }}<br />
{% if p.url %}</a>{% endif %}
{{ p.degree }}
{% endtablerow %}

</table>

