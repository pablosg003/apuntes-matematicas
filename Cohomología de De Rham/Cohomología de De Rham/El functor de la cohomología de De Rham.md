---
~
---
[[Functores]], [[Definición de los grupos de cohomología de De Rham]]

- Podemos considerar la asignación del complejo de cocadena como un functor contravariante entre $\mathbf{Dif}$ y $\mathbf{Vec}^{*}$, mediante la asignación:$$
U \longmapsto \{ \cdots \longrightarrow  \Omega^{p}(U) \xrightarrow{d} \Omega^{p+1}(U) \longrightarrow  \cdots \}
$$Y actuando sobre aplicaciones suaves $\varphi:U\longrightarrow V$ como:$$
\varphi \longmapsto \varphi^*
$$Tal y como la definimos en [[Formas diferenciales como categorías]] para cada $\Omega^p(U)$. Falta comprobar que es una aplicación de cocadena, es decir, que conmuta con la diferencial exterior:
- **Teorema:** Se tienen las siguientes relaciones, que además determinan únicamente $\varphi^{*}$:
	- $\varphi^{*}(\omega \wedge \tau)=\varphi^{*}(\omega) \wedge \varphi^{*}(\tau)$.
	- $\varphi^{*}(f) = f \circ \varphi$ para todo $f \in \Omega^{0}(V)$.
	- $d\varphi^{*}(\omega) = \varphi^{*} (d \omega)$.

- Componiéndolo con el functor covariante descrito en [[Complejos de cadena como categorías]], obtenemos para cada $p \geq 0$ el functor contravariante de la cohomología de De Rham, que asigna:$$
U \longmapsto H_{dR}^{p}(U)
$$Y a cada aplicación diferenciable $\varphi$, la aplicación lineal:$$
\begin{align*}
\varphi^{*}:H_{dR}^{p}(V) & \longrightarrow H_{dR}^{p}(U)\\
[\omega] & \longmapsto [\varphi^{*}\omega]
\end{align*}
$$