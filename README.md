# LaTeX Beamer Slides Theme for the [University of Santiago](http://www.usach.cl/) (USACH)
LaTeX beamer template for presentations of the University of Santiago.


Not convinced? Have a look at the [demo slides][].

![Sample](https://github.com/gmartinezramirez/Beamer-Template-USACH/blob/master/beamer-usach-theme-collage.png)


## Usage

The following code shows a minimal example of a Beamer presentation using
Metropolis.

```latex
\documentclass{beamer}
\usetheme{metropolis}           % Use metropolis theme
\title{A minimal example}
\date{\today}
\author{Matthias Vogelgesang}
\institute{Centre for Modern Beamer Themes}
\begin{document}
  \maketitle
  \section{First Section}
  \begin{frame}{First Frame}
    Hello, world!
  \end{frame}
\end{document}
```
Detailed information on using Metropolis can be found in the [manual][].

## License

The theme itself is licensed under a [Creative Commons Attribution-ShareAlike
4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/). This
means that if you change the theme and re-distribute it, you *must* retain the
copyright notice header and license it under the same CC-BY-SA license. This
does not affect the presentation that you create with the theme.


[demo slides]: http://mirrors.ctan.org/macros/latex/contrib/beamer-contrib/themes/metropolis/demo/demo.pdf
[manual]: http://mirrors.ctan.org/macros/latex/contrib/beamer-contrib/themes/metropolis/doc/metropolistheme.pdf
[CTAN]: http://ctan.org/pkg/beamertheme-metropolis
