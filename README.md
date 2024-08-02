![](https://raw.githubusercontent.com/samcarter/tikzbricks/main/ICON.png)

# TikZbricks

[![License](https://img.shields.io/github/license/samcarter/tikzbricks.svg?color=blue)](https://www.latex-project.org/lppl.txt)
[![GitHub tag](https://img.shields.io/github/tag/samcarter/tikzbricks.svg?label=current%20version&color=blue)](https://github.com/samcarter/tikzbricks/releases/latest)
[![CTAN](https://img.shields.io/ctan/v/tikzbricks.svg?color=blue)](https://ctan.org/pkg/tikzbricks)

A small LaTeX package to draw bricks with TikZ. The user can modify the colour, shape and  viewpoint.

This project is licensed under the LaTeX Project Public License v1.3c or later, see https://www.latex-project.org/lppl.txt . 

The project repository, including a bug tracker, can be found at https://github.com/samcarter/tikzbricks .

### Usage

```latex
\documentclass{standalone}
\usepackage{tikzbricks}

\begin{document}

\begin{tikzpicture}
  \brick[color=blue]{4}{2}
\end{tikzpicture}

\end{document}
```

For more details, please consult the [package documentation](https://github.com/samcarter/tikzbricks/blob/main/DOCUMENTATION.pdf).
