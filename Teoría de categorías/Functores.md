[[Categoría opuesta]]

- Dadas categorías $\mathcal{C}$ y $\mathcal{D}$, un **functor covariante** $F:\mathcal{C}\longrightarrow \mathcal{D}$ es una aplicación que lleva $\mathbf{Ob}(\mathcal{C})$ a $\mathbf{Ob}(\mathcal{D})$ y $\mathbf{Mor}(\mathcal{C})$ a $\mathbf{Mor}(\mathcal{D})$, de forma que $\forall f,g\in \mathbf{Mor}(\mathcal{C})$ con $\mathrm{dom}(f)=\mathrm{cod}(g)$:
	- $F(f:A\longrightarrow B) = F(f):F(A)\longrightarrow F(B)$.
	- $F(1_{A}) = 1_{F(A)}$.
	- $F(g \circ f) = F(g)\circ F(f)$.
- Un functor covariante $F:\mathcal{C}^{op} \longrightarrow \mathcal{D}$ se dice **functor contravariante** en $\mathcal{C}$. Es decir, cumple las siguientes propiedades:
	- $F(f:A\longrightarrow B) = F(f):F(A)\longrightarrow F(B)$.
	- $F(1_{A}) = 1_{F(A)}$.
	- $F(g \circ f) = F(f)\circ F(g)$.