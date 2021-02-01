# test_extends
Created for testing github pages issue with extends keyword in markup.
1. First, lets change README.md and check if [github page](https://nikovrdoljak.github.io/test_extends/) is updated after commit and push.
2. As expected, page is built. Now I will add some HTML code:

```jinja
<!-- {% raw %} -->
{% extends 'admin/master.html' %}
<!-- {% endraw %} -->
<h3>Header</h3>
<p>Paragraph</p>
```

3. Will add "_extends_" keyword in code above between _block_start_string_ and _block_end_string_.
