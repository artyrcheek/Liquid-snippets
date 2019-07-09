## To Use
```
{% for tab in split_tabs %}
  <h1>{{tab | split: ":" | first}}</h1>
  <div>
    {{tab | split: ":" | last}}
  </div>
{% endfor %}
```
