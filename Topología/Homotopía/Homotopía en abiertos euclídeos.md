[[Homotopía]]

- Sean $Y\subseteq \mathbb{R}^{n}$, $X$ un espacio topológico y $f_{0},f_{1}:X\longrightarrow Y$ continuas. Si para todo $x \in X$ el segmento $[f_{0}(x),f_{1}(x)]$ está contenido en $Y$, entonces $f_{0}\simeq f_{1}$, mediante la homotopía:$$
F(x,t)=(1-t)f_{0}(x) + tf_{1}(x)
$$En particular, los abiertos estrellados son contractibles.
- **Lema:** Sean $U \subseteq \mathbb{R}^{n}$, $V\subseteq \mathbb{R}^{m}$ abiertos, entonces:
	- Toda aplicación continua $h:U\longrightarrow V$ es homotópica a una aplicación suave.
	- Si dos aplicaciones suaves $f_{0},f_{1}:U\longrightarrow V$ son homotópicas, existe una homotopía suave que las relaciona. Es decir, $F:U\times \mathbb{R}\longrightarrow V$ diferenciable con $F(x,0)=f_{0}(x)$ y $F(x,1)=f_{1}(x)$.
	
	Demostración:
	- Por el [[Teorema de aproximación de Whitney para funciones]], tomando $\delta(x)=\frac{1}{2}d(h(x),\mathbb{R}^{m}\setminus V)$, existe $f:U\longrightarrow V$ suave con $\|h(x)-f(x)\|<\delta(x)$, y por la elección de $\delta$ está claro que el segmento $[h(x),f(x)]\subseteq V$, y podemos usar la homotopía del punto anterior.
	- Dada una homotopía $G:U\times[0,1]\longrightarrow V$, tomamos $\psi:\mathbb{R}\longrightarrow[0,1]$ continua con $\psi(t)=0$ si $t\leq \frac{1}{3}$ y $\psi(t)=1$ si $t\geq \frac{2}{3}$. Entonces, construimos:$$
\begin{align}
H(x,t):U\times \mathbb{R} & \longrightarrow V \\
(x,t) & \longmapsto G(x,\psi(t))
\end{align}
$$Y de nuevo por el teorema de aproximación de Whitney, podemos encontrar $F:U\times \mathbb{R}\longrightarrow V$ diferenciable que además coincida con $H$ sobre el cerrado $U\times \set{0,1}$, ya que es diferenciable en $U\times\left( -\infty, \frac{1}{3} \right)\cup U\times\left( \frac{2}{3},+\infty \right)$. Entonces, $F(x,0)=H(x,0)=f_{0}(x)$, $F(x,1)=H(x,1)=f_{1}(x)$ y efectivamente es una homotopía suave entre $f_{0}$ y $f_{1}$.