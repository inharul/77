Let's set you up quickly
```latex
\documentclass{article}
\title{Title}
\author{author}
\date{29 February}

\begin{document}
\section {section}
your paragraph goes here...
% comment goes here...
\end{document}
```

The next thing will be to review and analyze it.

```tex
\documentclass{type} % replace "type" with any type you require
```
this is where you specify what kind of document you are working on.
Available options are
- article
- beamer
- book
- letter
- report
We don't use beamer or letter that much but still there are options. Article, Report and Book is probably the go-to types.

```latex
\title{Title}
\author{author}
\date{29 February}
```

Depending upon your type, these above information will be formatted. `title` is given to the document name and it can be shown in different pages or mainly in your cover/first page. Same goes for `\author` but `\date` can be for your publishing date or for as I use it for my own reports, could be "version control" commit dates.

### `\begin` and `\end`
