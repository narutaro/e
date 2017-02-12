# Posts

| Tables        | Are           |
| ------------- |:-------------:|
| col 3 is      | right-aligned very long tile here you go|
| col 2 is      | centered      |
| zebra stripes | are neat      |

{% for post in site.posts %}
  <li>&raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
