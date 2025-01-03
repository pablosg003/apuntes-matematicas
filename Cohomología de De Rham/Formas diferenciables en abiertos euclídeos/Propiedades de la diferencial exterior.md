[[La diferencial exterior]]

- Si $x_{i}:U\longrightarrow\mathbb{R}$ es la proyección $i$-ésima, entonces $dx_{i}\in \Omega^1(U)$ es la aplicación constante $dx_{i} = \varepsilon_{i}$. Por lo tanto, podemos escribir $\omega \in \Omega^{p}(U)$ como:$$
\omega=\sum_{I}\omega_{I}dx_{i_{1}}\wedge \cdots\wedge dx_{i_{p}} = \sum_{I}\omega_{I}dx_{I}
$$En particular, si $f\in \Omega^{0}(U)=\mathcal{C}^{\infty}(U,\mathbb{R})$, entonces:$$
df=\sum_{i=1}^{n} \frac{\partial f}{\partial x_{i}}dx_{i}
$$
- Dada $fdx_{I}\in \Omega^{p}(U)$, con $f\in \mathcal{C}^{\infty}(U,\mathbb{R})$, se tiene que:$$
d(fdx_{I})=df \wedge dx_{I}
$$
- Dadas $\omega_{1}\in \Omega^{p}(U)$, $\omega_{2}\in \Omega^{q}(U)$, tenemos:$$
d(\omega_{1}\wedge \omega_{2})=(d \omega_{1})\wedge \omega_{2} + (-1)^{p}\omega_{1}\wedge(d \omega_{2})
$$