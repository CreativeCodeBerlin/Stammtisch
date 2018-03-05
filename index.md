{% for post in site.posts %} {% assign currentdate = post.date | date: "%Y" %} {% if currentdate != date %}

# {{ currentdate }} 
{% assign date = currentdate %} {% endif %} [ ![](/Stammtisch/assets/img/small/{{post.img}}) ]({{ post.url | remove_first:'/'}}) {% endfor %}

<!-- {{ post.date | date: "%B" }} - {{post.title}} -->
