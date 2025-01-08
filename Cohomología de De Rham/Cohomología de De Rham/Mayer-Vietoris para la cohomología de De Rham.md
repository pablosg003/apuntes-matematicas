[[La cadena corta exacta de la cohomología de De Rham]], [[Lema del zig-zag]]

- **Teorema:** (Mayer-Vietoris) Bajo las condiciones del teorema anterior, tomando los homomorfismos inducidos, existe un homomorfismo conector $\partial^{*}:H_{dR}^{p}(U_{1} \cap U_{2}) \longrightarrow H_{dR}^{p+1}(U)$ para todo $p \geq 0$, de tal forma que la siguiente sucesión es exacta:$$
\cdots \xrightarrow{\partial^{*}} H_{dR}^{p}(U) \xrightarrow{I^{*}}H_{dR}^{p}(U_{1})\oplus H_{dR}^{p}(U_{2}) \xrightarrow{J^{*}}H_{dR}^{p}(U_{1}\cap U_{2}) \xrightarrow{\partial^{*}}H_{dR}^{p+1}(U) \xrightarrow{I^{*}}\cdots
$$
	Demostración: Es una consecuencia inmediata del lema anterior y el lema del zig-zag.

- Como observación, es consecuencia del primer lema que si $U_{1}$ y $U_{2}$ son abiertos disjuntos, entonces tenemos isomorfismos:$$
\Omega^{p}(U_{1}\cup U_{2}) \cong \Omega^{p}(U_{1})\oplus \Omega^{p}(U_{2}) \text{ y } H_{dR}^{p}(U_{1}\cup U_{2}) \cong H_{dR}^{p}(U_{1})\oplus H_{dR}^{p}(U_{2})
$$A través de $I^{p}$.
- **Corolario:** Si $U = U_{1}\cup \cdots \cup U_{r}$, donde $U_{i}$ son abiertos convexos de $\mathbb{R}^n$, entonces $\dim H_{dR}^{p}(U) < +\infty$.
	Demostración: Lo hacemos por inducción sobre $r$. Para $r=1$, podemos usar el [[Lema de Poincaré]]. Asumimos que es cierto hasta $r$, y para $r+1$, escribimos $V=U_{1}\cup \cdots \cup U_{r}$. Entonces, por Mayer-Vietoris:$$
H_{dR}^p-1
$$