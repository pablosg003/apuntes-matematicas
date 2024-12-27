[[El álgebra alternada]], [[Ejemplos de categorías]], [[Functores]]

- $\wedge:\mathrm{Alt}^p(V)\times \mathrm{Alt}^q(V)\longrightarrow\mathrm{Alt}^{p+q}(V)$.
- $\omega_{1}\wedge \omega_{2} = (-1)^{pq}\omega_{2}\wedge \omega_{1}$.
- $(\omega_{1}\wedge \omega_{2})\wedge \omega_{3} = \omega_{1}\wedge(\omega_{2}\wedge \omega_{3})$.
- Si $\omega_{1},\dots,\omega_{p}\in \mathrm{Alt}^1(V)$, entonces: $$(\omega_{1}\wedge \omega_{2})(v_{1},\dots,v_{p+q})=\frac{1}{p!q!}\sum_{\sigma \in S(p+q)}\mathrm{sgn}(\sigma)\omega_{1}\left(v_{\sigma(1)},\dots,v_{\sigma(p)}\right)\omega_{2}\left(v_{\sigma(p+1)},\dots,v_{\sigma(p+q)}\right)$$
- $(\omega_{1}\wedge \cdots \wedge \omega_{p})(v_{1},\dots,v_{p}) = \det(\omega_{i}(v_{j}))$.
- $\omega_{1},\dots,\omega_{p}\in \mathrm{Alt}^{1}(V)=V^*$ son linealmente independientes $\iff \omega_{1}\wedge \cdots\wedge \omega_{p}\neq 0$.
- Si $\{e_{1},\dots,e_{n}\}$ es una base de $V$ y $\{\varepsilon_{1},\dots,\varepsilon_{n}\}$ es la base dual de $V^*$, entonces $\{\varepsilon_{\sigma(1)}\wedge\dots \wedge\varepsilon_{\sigma(p)}:\sigma \in S_{p,n-p}\}$ es una base de $\mathrm{Alt}^p(V)$. En particular, $\dim\mathrm{Alt}^{p}(V)={n\choose p}$.
- Una aplicación lineal $f:V \longrightarrow W$ induce otra aplicación lineal $\mathrm{Alt}^p(f):\mathrm{Alt}^p(W)\longrightarrow\mathrm{Alt}^p(V)$ de forma natural, fijando:$$
\mathrm{Alt}^p(f)(\omega)(v_{1},\dots,v_{p}) = \omega(f(v_{1}),\dots,f(v_{p}))
$$Claramente, $\mathrm{Alt}^p(g\circ f) = \mathrm{Alt}^p(f)\circ\mathrm{Alt}^p(g)$, así que es un functor contravariante:$$
\mathrm{Alt}^p:\mathbf{Vec}_{\mathbb{F}}\longrightarrow \mathbf{Vec}_{\mathbb{F}}
$$
- Si $\dim V  = n$ y $f:V\longrightarrow V$ es un endomorfismo, entonces $\mathrm{Alt}^n(f)$ es la multiplicación por $\det f$.