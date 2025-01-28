[[Mayer-Vietoris para la cohomología de De Rham]]

- **Proposición:** Sea $A \subsetneq \mathbb{R}^n$ cerrado, entonces:$$
\begin{gather*}
H_{dR}^{p+1}(\mathbb{R}^{n+1} \setminus A) \cong H_{dR}^{p}(\mathbb{R}^{n} \setminus A)\\
H_{dR}^{1}(\mathbb{R}^{n+1} \setminus A) \cong H_{dR}^{0}(\mathbb{R}^{n} \setminus A) / (\mathbb{R}\cdot1)\\
H_{dR}^{0}(\mathbb{R}^{n+1} \setminus A) \cong \mathbb{R}
\end{gather*}
$$Donde identificamos $A$ con $A \times \{ 0 \}$ y $\mathbb{R} \cdot 1$ el espacio de funciones constantes.
	Demostración: Definimos los siguientes abiertos de $\mathbb{R}^{n+1}$:$$
\begin{gather*}
U_{1}=[\mathbb{R}^{n}\times(0,+\infty)] \cup [(\mathbb{R}^{n} \setminus A) \times(-1,+\infty)]\\
U_{2}=[\mathbb{R}^{n}\times(-\infty,0)] \cup [(\mathbb{R}^{n} \setminus A) \times(-\infty, 1)]
\end{gather*}
$$De forma que $U_{1} \cup U_{2} = \mathbb{R}^{n+1}\setminus A$ y $U_{1} \cap U_{2}=(\mathbb{R}^{n} \setminus A) \times (-1,1)$. Tomando $\varphi(x^{1},\dots,x^{n+1})=\varphi(x^{1},\dots,x^{n+1}+1)$, está claro que $U_{1}$ contiene los segmentos que unen $x \in U_{1}$ con $\varphi (x)$ y este último con un punto fijo, por ejemplo $(0,\dots,0,1)$, por lo que $U_{1}$ es contractible (y análogamente $U_{2}$), por lo que:$$
H_{dR}^{p}(U_{1})\cong H_{dR}^{p}(U_{2}) \cong \left\{\begin{align*}
0, \text{ si } p \neq 0\\
\mathbb{R}, \text{ si } p=0
\end{align*}\right.
$$