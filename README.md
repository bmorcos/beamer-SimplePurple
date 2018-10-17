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
