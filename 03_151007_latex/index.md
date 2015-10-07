# Lekce 3 (7. 10. 2015) - LaTeX

- kniha - <https://prints.os1.cz/4/data/drsny_uvod_do_latexu.pdf>
- tex pro windows - <http://miktex.org/download>
- texmaker (editor) - <http://www.xm1math.net/texmaker/download.html#windows>

Nase ukazka

``` latex
% Sika Gymansium Paper
% http://sgy.cz/sgy.pdf
% Author: Ondrej Sika <ondrej@ondrejsika.com>

\documentclass[12pt,a4paper]{article}
\usepackage[utf8]{inputenc}
\usepackage[margin=2cm]{geometry}
\usepackage[parfill]{parskip}
\usepackage{graphicx}
\pagestyle{empty}

\begin{document}

\tableofcontents

\newpage

\section{Poliklinika}

Pani doktorka je hodna.

\subsection{popravde je tlusta}

ok

\section{Litomysl}



\includegraphics[scale=0.3]{blockchain}


{\Huge Some text}

{\LARGE Some text}

{\Large Some text}

{\small \bf Some text}

{\tiny Some text}

\begin{tabular}{|l|cr||}
\hline
\hline
1 & 2 & \&\\
1dwdwdww & 2vdvvfevr & \& ffregegregre\\
\hline
\end{tabular}

wfjelkfew fewfwefewr ferwfwe $n^2$

wffrwefwe
fefrwefre
frefer

ferferfrwe

$$ \sqrt[5]{\frac{53}{x^{43}}}$$

\begin{Huge}
defrefgre
frefre
\end{Huge}

\end{document}

```

