[[Complejos de cadena y cocadena]], [[Grupos de (co)homología]]

- Una aplicación cadena $f$ entre complejos $A_{*}$, $B_{*}$ es una familia de homomorfismos/aplicaciones lineales $f_{p}:A_{p}\longrightarrow B_{p}$ de forma que $d_{B,p}\circ f_{p} = f_{p-1} \circ d_{A,p}$, es decir, el siguiente diagrama conmuta:
```tikz
\usepackage{tikz-cd} 
\begin{document} 
\begin{tikzcd}
\cdots \arrow[r] & A_{p+1} \arrow[d, "f_{p+1}"] \arrow[r, "{d_{A,p+1}}"] & A_p \arrow[d, "f_p"] \arrow[r, "{d_{A,p}}"] & A_{p-1} \arrow[r] \arrow[d, "f_{p-1}"] & \cdots \\
\cdots \arrow[r] & B_{p+1} \arrow[r, "{d_{B,p+1}}"]                      & B_p \arrow[r, "{d_{B,p}}"]                  & B_{p-1} \arrow[r]                      & \cdots
\end{tikzcd}
\end{document} 
```
