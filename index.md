## Welcome to my portfolio site.
Not sure what's going to be here. Right now its just another cookie-cutter GitHub page using the [hacker theme](https://github.com/pages-themes/hacker).

### Recent Posts
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

### Contact Me

Send me an [email](mailto:tyler@ionise.org) or have a look at my [github](https://github.com/tjbh) profile.
