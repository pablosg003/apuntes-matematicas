[[Definición de categoría]]

- Dada una categoría $\mathcal{C}$, una flecha $f:A\longrightarrow B$ es un:
	- **Isomorfismo** si $\exists g:B \longrightarrow A$ tal que $g \circ f = 1_{A}$ y $f \circ g =1_{B}$. 
	- **Epimorfismo** si para todas $g,h:B\longrightarrow C$ con $g \circ f = h \circ f$, entonces $g=h$.
	- **Monomorfismo** si si para todas $g,h:C\longrightarrow A$ con $f \circ g = f \circ h$, entonces $g=h$.
- Todo isomorfismo es un monomorfismo y un epimorfismo.
- El inverso de un isomorfismo es único, ya que si $g,h:B\longrightarrow A$ lo son, entonces: $$h = h \circ 1_{B} = h \circ(f \circ g) = (h \circ f) \circ g = 1_{A} \circ g = g$$Así que podemos denotar el inverso como $g = f^{-1}$.