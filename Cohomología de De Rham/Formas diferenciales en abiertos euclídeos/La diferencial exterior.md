[[Formas diferenciales en abiertos]]

- Dada $\omega\in \Omega^p(U)$, denotamos su diferencial como $D\omega$, y en cada punto $x \in U$ se puede escribir como la aplicación lineal:$$
\begin{align*}
D_{x}\omega:\mathbb{R}^{n}&\longrightarrow \mathrm{Alt}^p(\mathbb{R}^n)\\
v & \longmapsto \left.\frac{d}{dt}\right|_{t=0}\omega(x+tv)
\end{align*}
$$Así que en particular cumple:$$
(D_{x}\omega)(e_{i})=\frac{\partial \omega}{\partial x_{i}}(x) = \sum_{I}\frac{\partial \omega_{I}}{\partial x_{i}}(x)\varepsilon_{i}
$$
- La diferencial exterior es el operador lineal:$$
\begin{array}{rclclcl}
d:\Omega^{p}(U) & \longrightarrow & \Omega^{p+1}(U)&&\\
\omega & \longmapsto & d \omega:U & \longrightarrow & \mathrm{Alt}^{p+1}(\mathbb{R}^n)\\
&  & x & \longmapsto & d_{x}\omega
\end{array}
$$Donde $$
\begin{align*}
d_{x}\omega :\mathbb{R}^{n}\times \cdots\times \mathbb{R}^{n} & \longrightarrow \mathbb{R}\\
(v_{1},\dots,v_{p+1}) & \longmapsto \sum_{i=1}^{p+1}(-1)^{i-1}D_{x}\omega (v_{i})(v_{1},\dots,\hat{v_{i}},\dots,v_{p+1})
\end{align*}
$$Es inmediato que está bien definida.