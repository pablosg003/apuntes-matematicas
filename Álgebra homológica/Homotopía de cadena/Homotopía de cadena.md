[[Aplicaciones cadena]], [[Complejos de cadena como categorías]]

- Decimos que dos aplicaciones cadena $f,g:A_{*}\longrightarrow B_{*}$ son homótopas si existen aplicaciones lineales $s_{p}:A_{p} \longrightarrow B_{p-1}$ tales que:$$
d_{B}s_{p} + s_{p}d_{A} = f_{p}-g_{p}
$$Para todo $p$. Escribimos $f \simeq g$. En forma de diagrama, tenemos lo siguiente:
```tikz
\usepackage{tikz-cd} 
\begin{document} 
\begin{tikzcd}
\cdots \arrow[r] & A_{p-1} \arrow[r] \arrow[d, "f-g"'] & A_p \arrow[r] \arrow[d, "f-g"'] \arrow[ld, "s"'] & A_{p+1} \arrow[r] \arrow[d, "f-g"'] \arrow[ld, "s"'] & \cdots \\
\cdots \arrow[r] & B_{p-1} \arrow[r]                   & B_p \arrow[r]                                    & B_{p+1} \arrow[r]                                    & \cdots
\end{tikzcd}
\end{document} 
```
- Dos aplicaciones cadena homótopas inducen el mismo homomorfismo sobre los grupos de homología, es decir:$$
f_{*}=g_{*}:H_{p}(A_{*}) \longrightarrow  H_{p}(B_{*})
$$
- Dados dos complejos de cadena $A_{*}$ y $B_{*}$:$$
H_{p}(A_{*} \oplus B_{*}) = H_{p}(A_{*}) \oplus H_{p}(B_{*})
$$