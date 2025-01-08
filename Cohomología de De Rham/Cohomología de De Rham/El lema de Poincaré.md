---
~
---
[[Definición de los grupos de cohomología de De Rham]], [[Homotopía de cadena]], [[Caracterización de la diferencial exterior]]

- **Teorema:** Sea $U \subseteq \mathbb{R}^{n}$ un abierto estrellado, entonces $H_{dR}^{0}(U)\cong\mathbb{R}$ y $H^{p}_{dR}(U)=0$ para todo $p >0$.
	Demostración: Podemos asumir sin pérdida de generalidad que es estrellado en el 0. Además, es conexo y por tanto se cumple el caso $p=0$. Consideramos la aplicación $e:\Omega^{p}(U) \longrightarrow \Omega^{p}(U)$ que lleva $\omega \in \Omega^{0}(U) \mapsto \omega(0)$ y es cero para todo $p>0$, que trivialmente es una aplicación de cadena. Vamos a comprobar que $\mathrm{id} \simeq e$. 
	Para $p>0$, definimos:$$
\begin{align*}
\hat{S}_{p}:\Omega^{p}(U \times \mathbb{R}) & \longrightarrow \Omega^{p-1}(U)\\
\sum_{I} f_{I}(x,t)dx_{I} + \sum_{J} g_{J}(x,t)dt \wedge dx_{J} & \longmapsto \sum_{J} \left( \int_{0}^{1}g_{J}(x,t) dt \right)dx_{J} 
\end{align*}
$$Tenemos entonces que, para todo $\omega \in \Omega^{p}(U \times \mathbb{R})$ escrito de la forma de arriba:$$
\begin{gather*}
d \omega = \sum_{I}df_{I}\wedge dx_{I} + \sum_{J}dg_{J} \wedge(dt \wedge dx_{J}) = \sum_{I}\left( \sum_{i} \frac{\partial f_{I}}{\partial x_{i}}dx_{i} + \frac{\partial f}{\partial t}dt \right) \wedge dx_{I} + \\ \sum_{J}\left( \sum_{j} \frac{\partial g_{J}}{\partial x_{j}}dx_{j} + \frac{\partial g}{\partial t}dt \right) \wedge dt \wedge dx_{J} = \sum_{I}\left( \sum_{i} \frac{\partial f_{I}}{\partial x_{i}}dx_{i}\wedge dx_{I} + \frac{\partial f}{\partial t}dt\wedge dx_{I} \right) \\ - \sum_{J} \sum_{j} \frac{\partial g_{J}}{\partial x_{j}} dt\wedge dx_{j} \wedge dx_{J}
\end{gather*}
$$Echando más cuentas, tenemos que:$$
\begin{gather*}
d(\hat{S}_{p}(\omega)) + \hat{S}_{p+1}(d \omega) = \sum_{J} d\left( \int_{0}^{1}g_{J} dt \right)\wedge dx_{J} + \\ \sum_{I}\left( \int_{0}^{1} \frac{\partial f_{I}}{\partial t}dt \right)dx_{I} -
\sum_{J,j}\left( \int_{0}^{1} \frac{\partial g_{J}}{\partial x_{j}}dt \right) dx_{j}\wedge dx_{J} 
\end{gather*}
$$OJO CON ESTE PASO; PREGUNTAR: es "Leibniz" pero no cuadra mucho con las referencias exactamente [[Regla de Leibniz]] $$
\begin{gather*}
= \sum_{J,j} \left( \int_{0}^{1} \frac{\partial g_{J}}{\partial x_{j}}dt \right) dx_{j}\wedge dx_{J} + \sum_{I}\left(f_{I}(x,1) - f_{I}(x,0) \right)dx_{I} - \\ \sum_{J,j} \left( \int_{0}^{1} \frac{\partial g_{J}}{\partial x_{j}}dt \right) dx_{j}\wedge dx_{J} = \sum_{I}\left(f_{I}(x,1) - f_{I}(x,0) \right)dx_{I}
\end{gather*}
$$Tomamos la función $\varphi:U\times \mathbb{R} \longrightarrow U$ como $\varphi(x,t)=\psi(t)x$, donde $\psi:\mathbb{R}\longrightarrow [0,1]$ es $\mathcal{C}^{\infty}$ y $\psi(t)=0$ si $t \leq 0$, $\psi(t)=1$ si $t \geq 1$. (Tiene codominio $U$ por ser estrellado). Definimos entonces $\forall \omega \in \Omega^{p}(U)$, $S_{p}(\omega) = \hat{S}_{p}(\varphi^{*}\omega)$, tal y como hicimos en [[El functor de la cohomología de De Rham]], es decir: si $\omega=\sum h_{I}(x)dx_{I}$, entonces $$
\begin{gather*}
\varphi^{*}\omega = \sum_{I} (\varphi^{*}h_{I})(\varphi^{*}(dx_{i_{1}}\wedge \cdots \wedge dx_{i_{p}})) = \sum_{I}h_{I}(\psi(t)x) d(x_{i_{1}}\psi(t))\wedge \cdots \wedge d(x_{i_{p}} \psi(t)) = \\
\sum_{I}h_{I}(\psi(t)x) (x_{i_{1}}d\psi(t) + \psi(t)dx_{i_{1}})\wedge \cdots\wedge (x_{i_{p}}d\psi(t) + \psi(t)dx_{i_{p}}) = \\
\sum_{I}h_{I}(\psi(t)x)\psi(t)^{p} dx_{I} + \sum_{J}*dt \wedge dx_{J}
\end{gather*}
$$Por lo tanto, tenemos que: $$
\begin{gather*}
d(S_{p}(\omega)) + S_{p+1}(d \omega) = d(\hat S_{p}(\varphi^{*}\omega)) + \hat{S}_{p+1}(\varphi^{*}(d \omega))= d(\hat S_{p}(\varphi^{*}\omega)) + \hat{S}_{p+1}(d(\varphi^{*}\omega))=\\
\sum_{I}h_{I} dx_{I} = \omega \hspace{5pt} \text{ si $p >0$ y } \hspace{5pt} \omega(x)-\omega(0) \hspace{5pt} \text{ si $p = 0$} 
\end{gather*}
$$Así que efectivamente $\mathrm{id}\simeq e$, y entonces para $p>0$, $\mathrm{id}_{H_{dR}^{p}(U)} = \mathrm{id}^{*}= e^{*} = 0$, por lo que necesariamente $H_{dR}^{p}(U)=0$.