[[Homotopía]]

Sean $X,Y$ espacios topológicos, $A\subseteq X$ con la topología del subespacio y $f:X \longrightarrow Y$ continua.
- Una retracción es una aplicación continua $r:X\longrightarrow X$ tal que $r^{2}=r$. 
- Una retracción por deformación (deformation retraction) de $X$ en $A$ es una aplicación continua:$$
\begin{align}
F:X\times[0,1] & \longrightarrow X \\
(x,t) & \longmapsto f_{t}(x)
\end{align}
$$Tal que $f_{0}= \mathrm{id}_{X}$, $\mathop{\mathrm{im}}f_{1}=A$ y $f_{t}|_{A} = \mathrm{id}_{A}$ para todo $t\in[0,1]$.
- Es decir, una retracción por deformación es una homotopía relativa a $A$ entre la identidad y una retracción.
- El cilindro de aplicación (mapping cylinder) de $f:X \longrightarrow Y$ es el conjunto:$$
M_{f}=((X\times I) \amalg Y) /_{\sim}
$$Donde hacemos la identificación $(x,1)\sim f(x)$. 
- La aplicación $F:M_{f} \times I \longrightarrow M_{f}$, que lleva $((x,t),t') \mapsto (x,t+(1-t)t')$ y $y \mapsto y$ es una retracción por deformación de $M_{f}$ en $Y$.