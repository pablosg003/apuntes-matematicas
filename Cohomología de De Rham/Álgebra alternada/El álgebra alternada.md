- Sea $V$ un espacio vectorial sobre un cuerpo $\mathbb{F}$, una aplicación $\omega:V^{k}\longrightarrow \mathbb{F}$ se dice **$k$-lineal** o multilineal si es lineal en cada factor.
- Además, decimos que es **alternada** si $v_{i}=v_{j}\Rightarrow\omega(v_{1},\dots,v_{k}) = 0$. De hecho, basta exigir que $v_{i}=v_{i+1} \Rightarrow \omega(v_{1},\dots,v_{k}) = 0$ El espacio vectorial de formas multilineales alternadas se denota $\mathrm{Alt}^k(V)$.
- Si $k>n$, entonces $\mathrm{Alt}^k(V)=0$, y por convenio también se toma $\mathrm{Alt}^0(V)=0$.
- Si $\omega \in \mathrm{Alt}^k(V)$ y $\sigma \in S(k)$, entonces:
$$
\omega(v_{\sigma(1)},\dots ,v_{\sigma(n)}) = \mathrm{sgn}(\sigma)\omega(v_{1},\dots,v_{n})
$$

- El **producto exterior** de $\omega_{1}\in \mathrm{Alt}^p(V)$ y $\omega_{2}\in \mathrm{Alt}^q(V)$ es:
$$
(\omega_{1}\wedge \omega_{2})(v_{1},\dots,v_{p+q})=\sum_{\sigma \in S_{p,q}}\mathrm{sgn}(\sigma)\omega_{1}\left(v_{\sigma(1)},\dots,v_{\sigma(p)}\right)\omega_{2}\left(v_{\sigma(p+1)},\dots,v_{\sigma(p+q)}\right)
$$
	Donde tomamos $S_{p,q}=\{\sigma \in S_{p+q}: \sigma(1)<\cdots<\sigma(p),\sigma(p+1)<\cdots<\sigma(p+q)\}$
