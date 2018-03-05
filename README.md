# Creative Code Stammtisch

The Creative Code Stammtisch is a monthly open conversation between artists, makers, designers, coders, performers, learners and anyone interested in the use of computing skills for artistic expression.

We use Paper to document our meetups collaboratively in real time.
We have 5 years of meetups in one looooong page, which has become unusably slow.

What we are testing here is if we can use Paper to document only the current meetup, then move the content to GitHub, when the real time aspect is no longer necessary, but still anyone can submit pull requests to make changes.

How to update this page:

1. Go to [paper](https://paper.dropbox.com/doc/Creative-Code-Stammtisch-8CQK2xebLjA6RJHGbuHoX) and export it as markdown, replacing Creative-Code-Stammtisch.md found in this repo.
2. Open the downloaded file, cut the content that matches one month, and paste
   it as a new file with this name format: `_posts/YYYY-MM-DD-ccsNNN.md`.
3. At the top of that file, add a header like this:
```
---
img: "NNN.jpg"
---
```
4. Save a poster jpg image (max 600x600) to `assets/img/large/NNN.jpg`
5. Save a thumbnail (160x160 85% quality) to `assets/img/small/NNN.jpg`
6. Git: `commit` those 3 files then `push`.

The page will be built automatically using Jekyll and visible at

[https://creativecodeberlin.github.io/Stammtisch/](https://creativecodeberlin.github.io/Stammtisch/)

