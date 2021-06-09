---
title: "TikZJax Test"
date: 2021-06-09T20:53:32+01:00
lastmod: 2021-06-09T20:53:32+01:00
draft: false
authors: ["PCloud"]
description: "TikzJax Test"
categories: [Tests]
tikz:
  enable: true
hiddenFromHomePage: true
---

<!--more-->

<script type="text/tikz">
  \begin{tikzpicture}
    \draw (0,0) circle (1in);
  \end{tikzpicture}
</script>
<script type="text/tikz">
\begin{tikzpicture}
\draw[gray, thick] (-1,2) -- (2,-4);
\draw[gray, thick] (-1,-1) -- (2,2);
\filldraw[black] (0,0) circle (2pt) node[anchor=west] {Intersection point};

\end{tikzpicture}
</script>
<script type="text/tikz">
\begin{tikzpicture}

\draw (-2,0) -- (2,0);
\filldraw [gray] (0,0) circle (2pt);
\draw (-2,-2) .. controls (0,0) .. (2,-2);
\draw (-2,2) .. controls (-1,0) and (1,0) .. (2,2);

\end{tikzpicture}
</script>
<script type="text/tikz">
\begin{tikzpicture}

\draw[blue, very thick] (0,0) rectangle (3,2);
\draw[orange, ultra thick] (4,0) -- (6,0) -- (5.7,2) -- cycle;

\end{tikzpicture}
</script>
