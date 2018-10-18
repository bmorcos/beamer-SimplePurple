# SimplePurple
A simple Beamer theme I use.

I got tired of fighting with the tools, so I just manually surpress the footer on the title frame:

```
    { %explicitly remove footer from title
    \setbeamertemplate{footline}{}
    \frame {
        \titlepage
    }}
```


Main references were:

- https://tex.stackexchange.com/questions/146529/design-a-custom-beamer-theme-from-scratch
- https://blog.hamaluik.ca/posts/better-beamer-themes/
- https://www.lucidchart.com/techblog/2016/12/07/how-to-make-a-presentation-in-latex/
