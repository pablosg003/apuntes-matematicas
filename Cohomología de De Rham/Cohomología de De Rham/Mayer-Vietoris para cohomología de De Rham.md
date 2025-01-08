[[Lema del zig-zag]]

- **Lema:** Sean $U_{1},U_{2} \subseteq \mathbb{R}^n$ abiertos, $U=U_{1}\cup U_{2}$, denotamos las inclusiones $\iota_{i}:U_{i} \hookrightarrow U$, $\gamma_{i}:U_{1}\cap U_{2}\hookrightarrow U_{i}$, y tomamos $I^{p}(\omega) = (\iota_{1}^{*}(\omega), \iota_{2}^{*}(\omega))$, $J^{p}(\omega) = \gamma_{1}^{*}(\omega) - \gamma_{2}^{*}(\omega)$. Entonces, la siguiente sucesión es exacta $\forall p \geq 0$:$$
0 \longrightarrow  \Omega^{p}(U) \xrightarrow{I^{p}} \Omega^{p}(U_{1})\oplus \Omega^{p}(U_{2}) \xrightarrow{J^{p}}\Omega^{p}(U_{1}\cap U_{2}) \longrightarrow  0
$$
	Demostración:8/
- **Teorema:** (Mayer-Vietoris) Bajo las condiciones del teorema anterior, $\forall p \geq 0$, existe un homomorfismo conector $\partial^{*}:H_{dR}^{p}(U_{1} \cap U_{2}) \longrightarrow H_{dR}^{p+1}(U)$ de tal forma que la siguiente sucesión es exacta:$$
\cdots \xrightarrow{\partial^{*}} H_{dR}^{p}(U) \xrightarrow{I^{*}}H_{dR}^{p}(U_{1})\oplus H_{dR}^{p}(U_{2}) \xrightarrow{J^{*}}H_{dR}^{p}(U_{1}\cap U_{2}) \xrightarrow{\partial^{*}}H_{dR}^{p+1}(U) \xrightarrow{I^{*}}\cdots
$$