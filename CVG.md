# Cálculo Vectorial Sobre Grafos
## Introducción
## Notación
A lo largo de este texto $\Gamma = (V,E)$ denotará un grafo simple, conexo, sin lazos y finito con conjunto de vértices $V$ y conjunto de aristas $E$.
**Definición 1:** Decimos que dos vértices $x,y \in V$ son *adyacentes*, denotado por $x \sim y$, si $\{x,y \} \in E$.  En este caso denotaremos a la arista $\{ x,y\}$ por $e_{xy}$ y decimos que $x$ y $y$ son incidentes con $e_{xy}$.

**Definición 2:** Para todo $x \in V$ definimos el *grado* de $x$, denotado por $deg(x)$, como el número de vértices adyacentes a $x$. 

**Definición 3** Si $deg(x) = k$ para todo $x \in V$ decimos que $\Gamma$ es un grafo *$k$-regular*.

Denotaremos por $\mathcal{C}(V)$ al espacio vectorial de funciones $f: V \to \mathbb{R}$  y  análogamente para $\mathcal{C}(V \times V)$.
Si $u \in \mathcal{C}(V)$ y $f \in \mathcal{C}(V \times V)$ entonces $uf$ denotará la función definida por
$$(uf)(x,y) =u(x)f(x,y)$$

**Definición 4:** Sea $u \in \mathcal{C}(V)$. El *soporte* de $u$, denotado por $supp(u)$, es el conjunto $supp(u)=\{ x \in V : u(x) \neq 0\}$.

**Definición 5:** Una función $v \in \mathcal{C}( V)$ es llamada una *ponderación* en $V$ si $v(x)>0$ para todo $x \in V$ .

**Definición 6:** Para cada ponderación $v$ en $V$ y para cualquier $u \in \mathcal{C}(V)$ definimos $\displaystyle\int_V u \; dv$ como el valor
$$\displaystyle\int_V u \; dv = \sum_{x \in V} u(x) v(x)$$
En particular cuando $v(x) = 1$ para todo $x \in V$ lo denotaremos por $\displaystyle \int_V u  dx$.

Con $\langle u,v \rangle_{\mathcal{C}(V)} = \displaystyle \int_V u \; d v$ el espacio $\mathcal{C}(V)$ se vuelve un espacio vectorial con producto interior.
**Definición 7:** Definimos el subespacio$\mathcal{C}(\Gamma) \subset \mathcal{C}(V \times V)$ como  
$$\mathcal{C}(\Gamma) = \{ f \in \mathcal{C}(V \times V): f(x,y)= 0 \text{ si } x \not \sim y\}$$

**Definición 8:** Una función $c \in \mathcal{C}(\Gamma)$ es llamada una *conductancia en $\Gamma$* si $c(x,y) >0)$ si y solo si $x \sim y$.

**Definición 9:**  Una *red* una tercia $(\Gamma, c,v)$ donde $v$ es una ponderación y  $c$ es una conductancia en $\Gamma$.

En lo que resta de este trabajo denotaremos simplemente por $\Gamma$ a una red $(\Gamma, c,v)$.

**Definición 10:**  La función $k(x) \in \mathcal{C}(V)$ definida por $$k(x) = \int_{V}c(x,y)dy$$
Es llamada el *grado generalizado* de la red $\Gamma$.

**Definición 11:** La función $r \in C(\Gamma)$ definida por $$r(x,y) = \dfrac{1}{c(x,y)}$$
cuando $d(x,y) =1$ es llamada *resistencia*

**Definición 12:** Dado $x \in V$, el  *espacio tangente en $x$*, denotado por $T_x(\Gamma)$ es el espacio vectorial real de combinaciones lineales formales de aristas incidentes a $x$.

**Definición 13:** Al conjunto de vectores incidentes a $x$ es una base de $T_x(\Gamma)$  a la cual llamamos una *base coordenada de $T_x(\Gamma)$.

Notemos que  $dim_{\mathbb{R}}(T_x(\Gamma)) = deg(x)$ y, a menos que la gráfica sea $k$-regular, la dimensión del espacio tangente varía con cada vértice.

**Definición 14:** A cualquier aplicación $$F: V \to \bigcup_{x \in V}T_x(\Gamma)$$
tal que $F(x) \in T_x(\Gamma)$ para todo $x \in V$ la llamamos un *campo vectorial en $\Gamma$*. 

**Definición 15:** El *soporte de $F$*, denotado por $supp(F)$ está definido como el conjunto
$$supp(F) = \{x \in V : F(x) \neq 0 \}.$$

Al espacio de todos los campos vectoriales en $\Gamma$ lo denotaremos por $\mathcal{X}(\Gamma)$.

Si $F \in \mathcal{X}(\Gamma)$, entonces $F$ está únicamente determinado por sus componentes en la base coordenada. Por tanto, podemos asociar con $F$ la función $f \in \mathcal{C}(\Gamma)$ tal que para cada $x \in V$,
$$f(x) =  $$

**Ejemplo 1:**
Consideremos  la red $\Gamma$ con $v(x) = 7-x$ y $v(x) =   \begin{cases} x+y &\text{ si } x \sim y \\0 &\text{ de otra manera}\end{cases}$


## Aplicaciones

### Sistemas de resortes

## Referencias

