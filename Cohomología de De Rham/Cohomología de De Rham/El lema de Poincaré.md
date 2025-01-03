---
~
---
[[Definición de los grupos de cohomología de De Rham]], [[Homotopía de cadena]], [[Caracterización de la diferencial exterior]]

- **Teorema:** Sea $U \subseteq \mathbb{R}^{n}$ un abierto estrellado, entonces $H_{dR}^{0}(U)\cong\mathbb{R}$ y $H^{p}_{dR}(U)=0$ para todo $p >0$.
	Demostración: Podemos asumir sin pérdida de generalidad que es estrellado en el 0. Además, es conexo y por tanto se cumple el caso $p=0$. Consideramos la aplicación $e:\Omega^{p}(U) \longrightarrow \Omega^{p}(U)$ que lleva $\omega \in \Omega^{0}(U) \mapsto \omega(0)$ y es cero para todo $p>0$. Vamos a comprobar que $\mathrm{id} \simeq e$. 
	Para $p>0$, definimos:$$
\begin{align*}
\hat{S}_{p}:\Omega^{p}(U \times \mathbb{R}) & \longrightarrow \Omega^{p-1}(U)\\
\sum_{I} f_{I}(x,t)dx_{I} + \sum_{J} g_{J}(x,t)dt \wedge dx_{J} & \longmapsto \sum \left( \int_{0}^{1}g_{J}(x,t) dt \right)dx_{J} 
\end{align*}
$$Tenemos entonces que, para todo $\omega \in \Omega^{p}(U \times \mathbb{R})$ escrito de la forma de arriba:$$
\begin{gather*}
d \omega = \sum_{I}df_{I}\wedge dx_{I} + \sum_{J}dg_{J} \wedge(dt \wedge dx_{J}) = \sum_{I}\left( \sum_{i} \frac{\partial f_{I}}{\partial x_{i}}dx_{i} + \frac{\partial f}{\partial t}dt \right) \wedge dx_{I} + \\ \sum_{J}\left( \sum_{j} \frac{\partial g_{J}}{\partial x_{j}}dx_{j} + \frac{\partial g}{\partial t}dt \right) \wedge dt \wedge dx_{J} = \sum_{I}\left( \sum_{i} \frac{\partial f_{I}}{\partial x_{i}}dx_{i}\wedge dx_{I} + \frac{\partial f}{\partial t}dt\wedge dx_{I} \right) \\ - \sum_{J} \sum_{j} \frac{\partial g_{J}}{\partial x_{j}} dt\wedge dx_{j} \wedge dx_{J}
\end{gather*}
$$Y aplicando 