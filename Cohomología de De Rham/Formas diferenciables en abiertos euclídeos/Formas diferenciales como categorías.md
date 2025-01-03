[[Ejemplos de categorías]], [[Functores]], [[Formas diferenciales en abiertos]]

- La asignación de $p$-formas diferenciales define un functor contravariante entre la categoría de abiertos de $\mathbb{R}^n$ y aplicaciones suaves, $\mathbf{Dif}$, y la categoría de espacios vectoriales reales, $\mathbf{Vec}_{\mathbb{R}}$, para todo $p$. Actúa sobre los objetos como:$$
U \longmapsto \Omega^p(U)
$$Y sobre las aplicaciones suaves $\varphi:U \longrightarrow V$ como:$$
\begin{array}{rclcl}
\Omega^{p}(\varphi)=\varphi^{*}:\Omega^{p}(V)&\longrightarrow &\Omega^{p}(U) & & \\
\omega & \longmapsto & \varphi^{*}(\omega):U & \longrightarrow & \mathop{\mathrm{Alt}}^p(\mathbb{R}^{n}) \\
&& x & \longmapsto & \varphi^{*}(\omega)_{x}
\end{array}
$$Donde $\varphi^{*}(\omega)_{x}(v_{1},\dots,v_{p})=\omega_{\varphi(x)}(D_{x}\varphi(v_{1}),\dots,D_{x}\varphi(v_{p}))$.

 