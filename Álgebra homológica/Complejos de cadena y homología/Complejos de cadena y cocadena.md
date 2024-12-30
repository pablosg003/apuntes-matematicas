[[Módulos]], [[Secuencias exactas cortas]]

- Una secuencia de $R$-módulos y homomorfismos conectores:$$
\cdots \longrightarrow  A_{i+1} \xrightarrow{d_{i+1}}A_{i} \xrightarrow{d_{i}}A_{i-1} \longrightarrow \cdots
$$Se dice un **complejo de cadena** si $\ker d_{i} \subseteq \mathop{\mathrm{im}} d_{i+1}$, y una **secuencia exacta** si $\ker d_{i}=\mathop{\mathrm{im}}d_{i+1}$.
- Una secuencia de $R$-módulos y homomorfismos conectores:$$
\cdots \longrightarrow  A^{i-1} \xrightarrow{d^{i-1}}A^{i} \xrightarrow{d^{i}}A^{i+1} \longrightarrow \cdots
$$Se dice un **complejo de cocadena** si $\ker d^{i} \subseteq \mathop{\mathrm{im}} d^{i-1}$, y una **secuencia exacta** si $\ker d^{i}=\mathop{\mathrm{im}}d^{i-1}$.

Todas las propiedades que enunciemos solo para una se cumplen inmediatamente para la otra por simetría, así que lo hacemos solo para la primera.
- Cada cadena exacta induce una exacta corta para cada $i$:$$
0\longrightarrow \mathop{\mathrm{im}} d_{i+1}\longrightarrow A_{i}\longrightarrow  \mathop{\mathrm{im}} d_{i}\longrightarrow  0
$$Tomando la inclusión $\mathop{\mathrm{im}}d_{i+1} \xhookrightarrow{\iota}A_{i}$ y la restricción de codominio en $d_{i}$, por lo que son inyectiva y suprayectiva respectivamente. Como hemos visto, induce isomorfismos:$$
A_{i} / \mathop{\mathrm{im}} d_{i+1} \cong A_{i} / \ker d_{i} \xrightarrow[d_{i}]{\sim} \mathop{\mathrm{im}} d_{i}
$$

