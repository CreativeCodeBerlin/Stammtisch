## Creative Code Stammtisch

The Creative Code Stammtisch is a monthly open conversation between artists, makers, designers, coders, performers, learners and anyone interested in the use of computing skills for artistic expression. There is usually a time for people to present something if they want to, followed by informal discussions. The event is free and open to all, regardless of age, gender or experience. Beginners and first-timers should feel especially welcome.

Follow us on Twitter: [@CreativeCodeBLN](https://twitter.com/creativecodebln)

Subscribe to our [Mailing list / forum](https://groups.google.com/forum/#!forum/creativecodeberlin)

Read the [list of previous events](https://docs.google.com/spreadsheets/d/1KOs798BIPlr1qzsn9HFky52wuW7PgzUaV9NM79Guk3o)

### Short links

* to the latest Stammtisch document: [http://tinyurl.com/creativecodeberlin](http://tinyurl.com/creativecodeberlin)
* to the jam document: [http://tinyurl.com/creativecodejam](http://tinyurl.com/creativecodejam)

## Meta

Why this page? We are using Paper to document our meetups collaboratively in real time.
The issue is that we have 4 years of meetups in one looooong page, which has become unusably slow.
What we are testing here is, if we can use Paper to document only the current meetup, and then move the content to GitHub, when the real time aspect is no longer necessary, but still anyone can make changes to it.

How to update this page:

1. Go to [paper](https://paper.dropbox.com/doc/Creative-Code-Stammtisch-8CQK2xebLjA6RJHGbuHoX) and export it as markdown, replacing Creative-Code-Stammtisch.md found in this repo.
2. Open the downloaded file, cut the content that matches one month, and paste
   it as a new file with this name format: `_posts/YYYY-MM-DD-ccsNNN.md`.
3. Commit and push in git.

View this page at [https://creativecodeberlin.github.io/Stammtisch/](https://creativecodeberlin.github.io/Stammtisch/) so the following links are correct.

{% for post in site.posts %} {% assign currentdate = post.date | date: "%Y" %} {% if currentdate != date %}

# {{ currentdate }} 
{% assign date = currentdate %} {% endif %}
* [{{ post.date | date: "%B" }} - {{post.title}} ]({{ post.url | remove_first:'/'}}) {% endfor %}

