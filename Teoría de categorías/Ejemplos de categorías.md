[[Definición de categoría]], [[Functores]]

- $\mathbf{Set}$, la categoría de conjuntos y las aplicaciones entre ellos.
- $\mathbf{Top}$, la categoría de espacios topológicos y aplicaciones continuas.
- $\mathbf{Vec}_{\mathbb{F}}$, la categoría de espacios vectoriales y aplicaciones lineales sobre un cuerpo $\mathbb{F}$.
- $\mathbf{Pos}$. la categoría de conjuntos parcialmente ordenados, donde $f:(A,\leq_{A})\longrightarrow (B,\leq_{B})$ son las aplicaciones monótonas, es decir, $a \leq_{A}b \implies f(a)\leq_{B} f(b)$.
- $\mathbf{Rel}$, la categoría de conjuntos y relaciones, es decir, escribimos $f:A\longrightarrow B$ para cualquier $f \subseteq A\times B$, y tomando la composición como:
$$
S \circ R = \{(a,c) : \exists b\in B \text{ t.q. } (a,b)\in R \wedge (b,c)\in S\}
$$
- Categorías finitas: para cada $n\in \mathbb{N}$, tenemos la categoría $\mathbf{n}$, que se construye como el vacío si $n=0$ e inductivamente añadiendo un objeto con flechas hacia todos los objetos en $\mathbf{n-1}$.
- La identidad de una categoría en sí misma es un functor, $1_{\mathcal{C}}$, y se comportan bien con la composición, así que tomando las categorías como objetos y los functores como morfismos, obtenemos la categoría $\mathbf{Cat}$. 