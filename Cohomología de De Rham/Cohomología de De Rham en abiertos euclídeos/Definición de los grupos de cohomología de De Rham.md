[[Caracterización de la diferencial exterior]], [[Complejos de cadena y cocadena]], [[Grupos de (co)homología]]

- Como hemos visto que $d \circ d=0$, tenemos un complejo de cocadena $\Omega^{*}(U) = \{\left( \Omega^{p}(U),d \right)\}$ entre espacios vectoriales. Por lo tanto, podemos definir los **grupos de cohomología de De Rham** como los espacios vectoriales de cohomología correspondientes al complejo $\Omega^{*}(U)$. Escribimos:
	- $Z^{p}(U)=\ker d^{p}$, las $p$-formas cerradas.
	- $B^p(U)=\mathop{\mathrm{im}}d^{p-1}$, las $p$-formas exactas
	- $H_{dR}^{p}(U)$ el $p$-ésimo grupo de cohomología de De Rham de $U$.
- Tenemos que $H_{dR}^{p}(U)=0$ si $p<0$ o $p>n$.
- $H_{dR}^{0}(U)=\{f\in \mathcal{C}^{\infty}(U,\mathbb{R}) : df=0\}= \{f\in \mathcal{C}^{\infty}(U,\mathbb{R}) : D_{x}f=0 \hspace{5pt} \forall x \in U\}=$ $\{f\in \mathcal{C}^{\infty}(U,\mathbb{R}) : f \text{ constante en cada componente conexa de } U\}$, así que  $\dim H_{dR}^0(U)$ es el número de componentes conexas por caminos de $U$.
- Podemos extender el producto exterior a estos grupos:$$
\begin{align*}
H^{p}(U)\times H^{q}(U)&\longrightarrow H^{p+q}(U)\\
([\omega_{1}], [\omega_{2}]) & \longmapsto [\omega_{1}][\omega_{2}]= [\omega_{1}\wedge \omega_{2}]
\end{align*}
$$Se comprueba fácilmente que está bien definido.