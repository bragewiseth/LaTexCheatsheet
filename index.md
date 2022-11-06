---
layout: post
---

Brøker:

~~~ tex
  $$\frac{1}{2}$$
~~~

<div align="center">
  <img src="g19.svg" width="30"/>
</div>

Align:

> lingningene blir linet opp etter `&` symbolet
> `\\` indikerer ny linje
> `\quad` og `\qquad` genererer mellomrom i mathmode

~~~ tex
\begin{align*}
    \oint\limits_C \vb{F} \cdot d\vb{r} = \qquad\qquad& \\
   -\oint\limits_C P dx + Q dy &= -\iint\limits_R \left(\pdv{Q}{x}-\pdv{P}{y}\right)dxdy\\
   -\iint\limits_R \left(\pdv{Q}{x}-\pdv{P}{y}\right)dxdy 
   &=-\iint\limits_R \left(\pdv{\frac{x}{2}}{x} + \pdv{\frac{y}{2}}{y}\right)dxdy   \\
    &=-\iint\limits_R 1 \; \text dx \text dy\\
\end{align*}
~~~

Minipage:

~~~ tex
\begin{minipage}[t]{.48\linewidth}
  % likningen over
\end{minipage}
\hspace{4mm}
\begin{minipage}[t]{.48\linewidth}
  % masse masse tekst
\end{minipage}
~~~

<div align="center">
  <img src="g3586.svg" width="800"/>
</div>

