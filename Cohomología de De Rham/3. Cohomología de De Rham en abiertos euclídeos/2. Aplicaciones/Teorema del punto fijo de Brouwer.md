[[1. Homotopía]], [[7. Invarianza por homotopía de la cohomología de De Rham]], [[10. Cálculos de cohomología de De Rham (III)]]

- **Lema:** No existen aplicaciones continuas $g:\mathbb{D}^{n} \longrightarrow \mathbb{S}^{n-1}$ con $g|_{\partial \mathbb{D}^{n}} = \mathop{\mathrm{id}}_{\mathbb{S}^{n-1}}$.
	Demostración: Si $n=1$, es trivial porque $\mathbb{D}^{1}=[-1,1]$ es conexo pero $\mathbb{S}^{0}=\{ -1,1 \}$ no, así que asumimos $n\geq 2$. Consideramos la retracción:$$
\begin{align*}
r:\mathbb{R}^{n}\setminus \{ 0 \} & \longrightarrow \mathbb{R}^{n}\setminus \{ 0 \}\\
x & \longmapsto \frac{x}{\left\| x \right\| }
\end{align*}
$$Y tenemos claramente que $r \simeq \mathop{\mathrm{id}}_{\mathbb{R}^{n}\setminus \{ 0 \}}$, ya que siempre contiene el segmento que une $x$ con $r(x)$. Ahora, si existe dicha $g$, tenemos que $H(t,x)=g(t\cdot r(x))$ es una homotopía entre una aplicación constante y $r$, por lo que $\mathbb{R}^{n} \setminus \{ 0 \}$ es contractible y entonces $H_{dR}^{n-1}(\mathbb{R}^{n}\setminus \{ 0 \})\cong 0$, lo que es una contradicción.

- **Teorema:** Toda aplicación continua $f:\mathbb{D}^{n} \longrightarrow \mathbb{D}^{n}$ tiene un punto fijo.
	Demostración: Supongamos que $f(x)\neq x$ para todo $x \in \mathbb{D}^{n}$, entonces podemos considerar $g(x)\in \mathbb{S}^{n-1}$ como el punto de intersección con la semirrecta con extremo en $f(x)$ que pasa por $x$. Es decir:$$
g(x) = x + tu, \text{ con } u= \frac{x-f(x)}{\|x-f(x)\|} \text{ y } t=\sqrt{ 1- \|x\|^{2} + \left< x,u \right>^{2}    } - \left< x,u \right> 
$$Donde $u$ fija la dirección y $t$ es el valor que hace cumplir que $\|g(x)\|=1$ en el punto de intersección adecuado. Como es una aplicación continua, esto contradice el lema anterior.