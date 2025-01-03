[[Complejos de cadena y cocadena]], [[Grupos de (co)homología]], [[Secuencias exactas cortas]]

(Se toman todas las definiciones análogas para las aplicaciones cocadena)
- Una **aplicación cadena** $f$ entre complejos $A_{*}$, $B_{*}$ es una familia de homomorfismos/aplicaciones lineales $f_{p}:A_{p}\longrightarrow B_{p}$ de forma que $d_{B,p}\circ f_{p} = f_{p-1} \circ d_{A,p}$, es decir, el siguiente diagrama conmuta:
```tikz
\usepackage{tikz-cd} 
\begin{document} 
\begin{tikzcd}
\cdots \arrow[r] & A_{p+1} \arrow[d, "f_{p+1}"] \arrow[r, "{d_{A,p+1}}"] & A_p \arrow[d, "f_p"] \arrow[r, "{d_{A,p}}"] & A_{p-1} \arrow[r] \arrow[d, "f_{p-1}"] & \cdots \\
\cdots \arrow[r] & B_{p+1} \arrow[r, "{d_{B,p+1}}"]                      & B_p \arrow[r, "{d_{B,p}}"]                  & B_{p-1} \arrow[r]                      & \cdots
\end{tikzcd}
\end{document} 
```
- Cualquier aplicación cadena $f$ induce un homomorfismo/aplicación lineal entre los grupos de homología para todo $p$:$$
\begin{align*}
f_{*}=H_{*}(f):H_{p}(A_{*})& \longrightarrow H_{p}(B_{*})\\
[\gamma]&\longmapsto [f_{p}(\gamma)]
\end{align*}
$$Donde se puede comprobar fácilmente que está bien definida como consecuencia de que las aplicaciones cadena conmuten con $d$.
- Una secuencia exacta corta de complejos de cadena es:
```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}
0 \arrow[r] & A_* \arrow[r,"f"] & B_* \arrow[r,"g"] & C_* \arrow[r] & 0
\end{tikzcd}
\end{document}
```
Donde $f$ y $g$ son aplicaciones cadena y para todo $p$, la siguiente cadena es exacta corta:
```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}
0 \arrow[r] & A_p \arrow[r,"f_p"] & B_p \arrow[r,"g_p"] & C_p \arrow[r] & 0
\end{tikzcd}
\end{document}
```
- Dada una secuencia exacta corta de complejos de cadena como la anterior, entonces la siguiente cadena es exacta:
```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}
H_p(A_*) \arrow[r,"f_*"] & H_p(B_*) \arrow[r,"g_*"] & H_p(C_*)
\end{tikzcd}
\end{document}
```