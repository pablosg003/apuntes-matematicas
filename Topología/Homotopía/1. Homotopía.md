Sean $X,Y$ espacios topológicos:
- Decimos que dos aplicaciones continuas $f_{0},f_{1}:X \longrightarrow Y$ son **homotópicas** si existe una homotopía entre ellas, es decir, una aplicación continua:$$
\begin{align}
F:X\times[0,1] & \longrightarrow X \\
(x,t) & \longmapsto f_{t}(x)
\end{align}
$$Tal que $f_{0}(x)=F(0,x)$ y $f_{1}(x)=F(1,x)$. Escribimos $f_{0}\simeq f_{1}$.
- **Lema:** Ser homotópicas es una relación de equivalencia en el conjunto de aplicaciones continuas $\mathcal{C}(X,Y)$.
	$f\simeq f$ tomando $F(x,t)=f(x)$, y si $f \simeq g$ mediante $F$, basta considerar $G(x,t)=F(x,1-t)$. Si $f\simeq g \simeq h$ mediante $F$ y $G$, basta tomar:$$
H(x,t)=\left\{ \begin{align}
F(x,2t) \text{ si } 0 \leq t \leq \frac{1}{2} \\
G(x,2t-1) \text{ si } \frac{1}{2}<t \leq 1
\end{align} \right.
$$
- **Lema:** Si $f_{0},f_{1}:X\longrightarrow Y$ y $g_{0},g_{1}:Y \longrightarrow Z$ son aplicaciones continuas con $f_{0}\simeq f_{1}$ y $g_{0}\simeq g_{1}$, entonces $g_{0}\circ f_{0} \simeq g_{1} \circ f_{1}$.
	Basta tomar $H(x,t)=G(F(x,t),t)$.
- Decimos que una homotopía es relativa a $A$ si $f_{t}|_{A} = f_{t'}|_{A}$ para todo $t,t'\in I$.
- Una aplicación continua $f:X\longrightarrow Y$ se dice una **equivalencia por homotopía** si $\exists g:Y\longrightarrow X$ tal que $g \circ f \simeq \mathop{\mathrm{id}}_{X}$ $f\circ g \simeq \mathop{\mathrm{id}}_{Y}$. En tal caso, decimos que $X$ e $Y$ son equivalentes por homotopía, o que tienen el mismo tipo de homotopía, y escribimos $X \simeq Y$.
- **Lema:** Ser equivalente por homotopía es una relación de equivalencia.
- Decimos que un espacio topológico es contractible si tiene el tipo de homotopía de un punto.