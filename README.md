Jekyll If File Exists
=====================

Installation
------------

Copy `file_exists.rb` into the `/_plugins/` directory of your Jekyll project.

Usage
-----

The plugin adds a new custom liquid tag, which can be used as follows: 
 
```
{% iffileexists dir/{{ page.var }}/page.html %}
  {% include dir/{{ page.var }}/page.html %}
{% else %}
  {% include dir/default_page.html %}
{% endiffileexists %}
```
