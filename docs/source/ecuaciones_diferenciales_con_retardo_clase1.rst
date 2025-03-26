Ecuaciones diferenciales con retardo
====================================

Clase 1, versi´on preliminar (las cr´ıticas son bienvenidas)

1 Introducción
--------------

La primera clase de un primer curso sobre ecuaciones diferenciales comienza con el siguiente ejemplo

.. math::

   x'(t) = x(t).


Todo el
mundo acepta inmediatamente que :math:`x(t) = e^t` es una solución y, con un mínimo de
esfuerzo adicional, que todas las soluciones son de la forma :math:`x(t) = Ce^t`, en donde
C es una constante arbitraria. 

Como :math:`x(t) = λx(t)`, al reemplazar en la ecuación resulta

.. math::

   λx(t) = x(t)

y el polinomio característico es P(λ) = λ − 1, que obviamente tiene al valor
λ = 1 como ´unica raíz.


Sin embargo, la situación cambia de manera drástica si suponemos que la
ecuación tiene un retardo τ > 0, vale decir

.. math::

   x'(t) = x(t − τ )
.
En efecto, ahora al reemplazar :math:`x(t) = e^´{λt} en la ecuación resulta

.. math::

   λx(t) = x(t − τ ) = ^{λ(t−τ}) = ^{−λ}τx(t)
.
En consecuencia λ debe ser soluci´on de la ecuaci´on caracter´ıstica P(λ) = 0,
donde P ya no es un polinomio sino una funci´on trascendente: P(λ) = λ−e
−λτ
.
Como λ = 0 no es ra´ız, podemos reemplazar z =
1
λ
y escribir la ecuaci´on anterior
como
ze−τ/z = 1.


