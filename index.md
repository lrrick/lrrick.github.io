# Hello World!

# My Interests

I'm interested in front end development as well as java. Currently learning Github!

Enjoy learning new things and overcoming problems. Enjoy roles that include working as part of a team as well as on individual projects. Especially enjoy the increasing role technology and data analysis plays in the world of health and fitness allowing people to easily monitor their health and improve their fitness

#blog

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }} "> {{ post.title}}</a>
  <li>
  {% endfor %}
</ul>
