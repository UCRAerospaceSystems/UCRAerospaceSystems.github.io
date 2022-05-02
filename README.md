# UCRAerospaceSystems.github.io

Do not try to directly edit the files in this repo. Edit the Hugo project and compile. Push the deploy code here

Helpful Links when working with Hugo:
1. https://gohugo.io/
2. https://mcshelby.github.io/hugo-theme-relearn/
3. https://www.oreilly.com/library/view/working-with-static/9781491960936/ch04.html
4. https://www.youtube.com/watch?v=qtIqKaDlqXo&list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3

### Way to separate dev dirs and deployment dirs:
House the development and deploy directories under one project directory so that the tree looks like:
```
docs_project
 -- development
 -- public
```

To compile, run the command from the project directory:
```
cd development ; hugo -D --destination ../public
```
