---
layout: post
---

Brøker:

~~~ LaTex
  $$\frac{1}{2}$$
~~~

<div align="center">
  <img src="g19.svg" width="30"/>
</div>

Align:

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


\end{minipage}
\hspace{4mm}
\begin{minipage}[t]{.48\linewidth}
    Hvis vi tar linjestykket $C_1$ mellom $(a_1,b_1)$ og $(a_{2},b_{2})$ er $\Delta a = a_{2} - a_1$ og $\Delta b = b_{2} - b_1$.
    Linjen starter i  $(a_1,b_1)$ og går en distanse $\Delta a$ og $\Delta b$ mot henholdsvis $(a_2,b_2)$. Punktet $(a_2,b_2)$ kan da
    skrives som $(a_1 + (a_2-a_1))\vb*i + (b_1 + (b_2 -b_1))\vb*j$.\\\\
    Vi kan generalisere dette til $C_k$: $(a_k + (a_{k+1}-a_k))\vb*i + (b_k + (b_{k+1} - b_k))\vb*j$.
    Parameteriseringen av denne linjen kan gis som
    \begin{align*}
         \vb{r}_k(t) = (a_k + t(a_{k+1}-a_k))\vb*i + (b_k + t(b_{k+1} - b_k))\vb*j
    \end{align*}
    Der $0 \le t \le 1$ bestemmer lengden på $\Delta a$ og $\Delta b$
\end{minipage}
~~~

<!-- <div align="center">
  <img src="g3586.svg" width="30"/>
</div> -->
![](g3586.svg)
