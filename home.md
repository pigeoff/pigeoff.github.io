# Benvenue !

Valkommen hit ! Je m'appelle César, je suis étudiant en sociologie et militant *pédé*. Vous vous trouvez sur mon blog, j'y parle pouvoir et sexualité. Enjoy !

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
