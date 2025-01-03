[[Definición de categoría]], [[Aplicaciones cadena]], [[Functores]], [[Grupos de (co)homología]]

- Definimos $\mathbf{Vec}_{*}$ ($\mathbf{Vec}^{*}$) como la categoría cuyos objetos son los complejos de (co)cadena sobre espacios vectoriales y los morfismos son las aplicaciones (co)cadena.
- La asignación de los grupos de homología es un functor covariante entre $\mathbf{Vec}_{*}$ y $\mathbf{Vec}$ para cualquier $p$, llevando $A_{*} \longmapsto H_{p}(A_{*})$ y a las aplicaciones de cadena $f:A_{*}\longrightarrow B_{*}$ a las aplicaciones lineales:$$
\begin{align*}
f_{*}=H_{*}(f):H_{p}(A_{*}) & \longrightarrow H_{p}(B_{*})\\
[\gamma] & \longmapsto [f_{p}(\gamma)]
\end{align*}
$$Y se puede ver que está bien definido usando que $d$ y $f$ conmutan. De forma análoga tenemos un functor covariante de $\mathbf{Vec}^{*}$ a $\mathbf{Vec}$, y lo mismo sustituyendo los espacios vectoriales por módulos y grupos.
