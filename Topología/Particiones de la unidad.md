- Sean $X$ un espacio topológico $V$ un espacio vectorial y $f:X \longrightarrow V$. El soporte de $f$ es:$$
\mathop{\mathrm{sop}}(f) = \overline{\{x \in X : f(x)\neq 0\}}
$$
- Sea $\mathcal{X} =\left\{ X_{\lambda} \right\}_{\lambda \in \Lambda}$ un cubrimiento abierto de $X$, una partición de la unidad subordinada a $\mathcal{X}$ es una colección de funciones continuas $\psi_{\lambda}:X \longrightarrow [0,1]$ tales que:
	- $\mathop{\mathrm{sop}}(\psi_{\lambda})\subseteq X_{\lambda}$ $\forall \lambda \in \Lambda$.
	- $\left\{ \mathop{\mathrm{sop}}\psi_{\lambda} \right\}_{\lambda \in \Lambda}$ es localmente finita, es decir, todo punto tiene un entorno que solo interseca a una cantidad finita de soportes.
	- $\sum_{\lambda \in \Lambda}\psi_{\lambda}(x) = 1$ para todo $x \in X$.
