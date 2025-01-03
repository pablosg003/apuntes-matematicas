[[El álgebra alternada]], [[Propiedades del álgebra alternada]]

- Sea $U$ un abierto de $\mathbb{R}^n$, $p \in \mathbb{N}$, una **$p$-forma diferencial** es una aplicación suave:$$
\omega:U\longrightarrow \mathrm{Alt}^p(\mathbb{R}^n)
$$ El conjunto de todas las $p$-formas diferenciales se denota $\Omega^p(U)$.
- El producto exterior en $p$-formas alternadas induce puntualmente el **producto exterior** en $p$-formas diferenciales como:$$
\begin{array}{rclcl}
\wedge:\Omega^{p}(U)\times \Omega^{q}(U) & \longrightarrow & \Omega^{p+q}(U)&&\\
(\omega_{1},\omega_{2}) & \longmapsto & \omega_{1}\wedge \omega_{2}:U & \longrightarrow & \mathrm{Alt}^{p+q}(\mathbb{R}^n)\\
&  & x & \longmapsto & \omega_{1}(x)\wedge \omega_{2}(x) \\
\end{array}
$$(Comprobar que respeta diferenciabilidad)
- Como $\varepsilon_{I} = \varepsilon_{i_{1}}\wedge \cdots \wedge \varepsilon_{i_{p}}$, con $I=\{i_{1}<\cdots<i_{p}\}$ forman una base de $\mathrm{Alt}^p(\mathbb{R}^n)$, podemos escribir:$$
\omega=\sum_{I}\omega_{I}\varepsilon_{I}
$$ Con $\omega_{I}\in \mathcal{C}^{\infty}(U,\mathbb{R})$ para todo $I$.

