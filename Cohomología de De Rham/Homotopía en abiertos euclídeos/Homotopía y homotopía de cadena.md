[[Homotopía en abiertos euclídeos]], [[Homotopía de cadena]], [[El functor de la cohomología de De Rham]]

- **Teorema:** Sean $f,g:U \longrightarrow V$ aplicaciones diferenciables con $f \simeq g$. Entonces, las aplicaciones de cocadena inducidas:$$f^{*},g^{*}:\Omega^{*}(V) \longrightarrow \Omega^{*}(U)$$Son homotópas, y por lo tanto inducen el mismo homomorfismo sobre los grupos de cohomología de De Rham:$$
f^{*}=g^{*}:H_{dR}^{p}(V)\longrightarrow H_{dR}^{p}(U)
$$
	Demostración: Sea $F:U\times \mathbb{R}\longrightarrow V$ una homotopía suave entre $f$ y $g$, y $\varphi_{0}(x)=(x,0)$, $\varphi_{1}(x)=(x,1)$ de forma que $f=F\circ\varphi_{0}$, $g=F\circ\varphi_{1}$. Recuperamos la aplicación que ya usamos en el [[Lema de Poincaré]]:$$
\begin{align*}
\hat{S}_{p}:\Omega^{p}(U \times \mathbb{R}) & \longrightarrow \Omega^{p-1}(U)\\
\sum_{I} f_{I}(x,t)dx_{I} + \sum_{J} g_{J}(x,t)dt \wedge dx_{J} & \longmapsto \sum_{J} \left( \int_{0}^{1}g_{J}(x,t) dt \right)dx_{J} 
\end{align*}
$$Que sabemos que cumple $d(\hat{S}_{p}(\omega)) + \hat{S}_{p+1}(d \omega) = \sum_{I}f_{I}(x,1)dx_{I} -\sum_{I} f_{I}(x,0) dx_{I}$. Además, dada $\omega \in \Omega^{p}(U\times \mathbb{R})$ en la misma forma, tenemos que $\varphi_{0}^{*}(\omega) =\sum_{I}f_{I}(x,0)dx_{I}$, ya que $\varphi_{0}$ es constante respecto a $t$ y la identidad en $x$; y análogamente $\varphi_{1}^{*}(\omega)=\sum_{I}f_{I}(x,1)dx_{I}$. Por lo tanto, tenemos de hecho que $d(\hat{S}_{p}(\omega)) + \hat{S}_{p+1}(d \omega)= \varphi_{1}^*(\omega)-\varphi_{0}^{*}(\omega)$.
	Considerando las composiciones $U \xrightarrow{\varphi_{i}}U\times \mathbb{R} \xrightarrow{F}V$, tenemos claramente que $F\circ \varphi_{0}=f$, $F\circ \varphi_{1}=g$. Consideramos ahora $S_{p}=\hat{S}_{p} \circ F^{*}:\Omega^{p}(V)\longrightarrow\Omega^p(U)$, y aplicando la relación del paso anterior a la forma diferencial $F^{*}\omega$ tenemos que:$$
\begin{gather*}
dS_{p}(\omega) + S_{p+1}(d \omega)= d\hat{S}_{p}(F^{*}\omega) + \hat{S}_{p+1}(F^{*}(d\omega))= d\hat{S}_{p}(F^{*}\omega) + \hat{S}_{p+1}(dF^{*}\omega)=\\ \varphi_{1}^{*}(F^{*}\omega) - \varphi_{0}^{*}(F^{*}\omega) =(F \circ \varphi_{1})^{*}\omega - (F \circ \varphi_{0})^{*}\omega = g^{*}\omega - f^{*}\omega
\end{gather*}
$$Utilizando que $F^{*}$ es una aplicación de cadena, por lo que conmuta con la diferencial exterior, y que la asignación de la aplicación de cocadena es un functor contravariante.