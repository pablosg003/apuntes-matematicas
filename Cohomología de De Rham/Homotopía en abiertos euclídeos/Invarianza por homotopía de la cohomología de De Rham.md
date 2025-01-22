[[Homotopía y homotopía de cadena]], [[El functor de la cohomología de De Rham]], [[Homotopía]]

- **Teorema:** Sean $U\subseteq \mathbb{R}^{n}$, $V\subseteq \mathbb{R}^{m}$ abiertos, $p \in \mathbb{Z}$:
	- Si $\varphi_{0},\varphi_{1}:U\longrightarrow V$ son homotópicas, entonces:$$
\varphi_{0}^{*}=\varphi_{1}^{*}:H_{dR}^{p}(V)\longrightarrow H_{dR}^{p}(U)
$$
	- Si $\varphi:U\longrightarrow V$ y $\psi:V \longrightarrow W$ son continuas, entonces $(\psi \circ \varphi)^{*}=\varphi^{*}\circ \psi^{*}:H_{dR}^{p}(W)\longrightarrow H_{dR}^{p}(U)$.
	- Dada una equivalencia por homotopía $\varphi:U\longrightarrow V$, su homomorfismo inducido:$$
\varphi^{*}:H_{dR}^{p}(V)\longrightarrow H_{dR}^{p}(U)
$$Es un isomorfismo.
	Demostración: Homomorfismo inducido por una aplicación continua?? el resto trivial.
- **Corolario:** Los grupos de cohomología de De Rham son invariantes por homotopía y por homomorfismo en particular.
- **Corolario:** La cohomología de De Rham define functores contravariantes entre $\mathbf{Top}_{\mathbb{R}}$ (la categoría de abiertos euclídeos con topología inducida y aplicaciones continuas) y $\mathbf{Vec}_{\mathbb{R}}$, mediante la asignación $U \mapsto H_{dR}^{p}(U)$ y $\varphi \mapsto H^{p}(\varphi) = \varphi^{*}$.
- **Corolario:** (Lema de Poincaré, versión 2): Sea $U$ un abierto contractible de $\mathbb{R}^{n}$, entonces $H_{dR}^{0}(U) \cong \mathbb{R}$ y $H_{dR}^{p}(U)\cong 0$ si $p \neq 0$. 
	Demostración: (con $p \equiv \mathbb{R}^{0}$) trivial. (6 que añadirlo como nota al definir todo)