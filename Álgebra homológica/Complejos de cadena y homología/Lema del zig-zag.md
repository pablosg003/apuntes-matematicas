- Partiendo de la construcción de [[Aplicaciones cadena]], definimos la siguiente aplicación conectora:$$
\begin{align*}
\partial_{*}:H_{p}(C_{*}) & \longrightarrow  H_{p-1}(A_{*})\\
[c] & \longmapsto \left[ f_{p-1}^{-1}\left( d_{B,p}\left( g_{p}^{-1}(c) \right)  \right)  \right] 
\end{align*}
$$De forma que obtenemos el siguiente diagrama:
```tikz
\usepackage{tikz-cd} 
\begin{document} 
\begin{tikzcd}
& \vdots \arrow[d] & \vdots \arrow[d] & \vdots \arrow[d] & \\
0 \arrow[r] & A_p \arrow[r, "f_p"] \arrow[d, "{d_{A,p}}"'] & B_p \arrow[r, "g_p"] \arrow[d, "{d_{B,p}}"'] & C_p \arrow[r] \arrow[d, "{d_{C,p}}"'] \arrow[lld, "\partial_*"] & 0 \\
0 \arrow[r] & A_{p-1} \arrow[d] \arrow[r, "f_{p-1}"'] & B_{p-1} \arrow[d] \arrow[r, "g_{p-1}"'] & C_{p-1} \arrow[d] \arrow[r] & 0 \\
& \vdots & \vdots & \vdots &  
\end{tikzcd}
\end{document} 
```
- Hay que comprobar que está bien definida, tanto por elección de las preimágenes como la del representante, demostrando que:
	- Si $g_{p}(b)=c$ y $d_{C, p}(c)=0$, entonces $d_{B,p}(b)\in \mathop{\mathrm{im}}f_{p-1}$.
	- Si $f_{p-1}(a)=d_{B,p}(b)$, entonces $d_{A,p-1}(a)=0$.
	- Si $g_{p}(b_{1})=g_{p}(b_{2})=c$ y $f_{p-1}(a_{i})=d_{B,p}(b_{i})$, entonces $[a_{1}]=[a_{2}]\in H_{p-1}(A_{*})$.
- **Teorema:** La siguiente secuencia es exacta:
```tikz
\usepackage{tikz-cd} 
\begin{document} 
\begin{tikzcd}
                          &                           & \cdots \arrow[lld]             \\
A_p \arrow[r, "f_*"']     & B_p \arrow[r, "g_*"']     & C_p \arrow[lld, "\partial_*"'] \\
A_{p-1} \arrow[r, "f_*"'] & B_{p-1} \arrow[r, "g_*"'] & C_{p-1} \arrow[lld]            \\
\cdots                    &                           &                               
\end{tikzcd}
\end{document} 
```