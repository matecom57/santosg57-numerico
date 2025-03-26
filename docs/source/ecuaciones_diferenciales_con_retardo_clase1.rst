Ecuaciones diferenciales con retardo
====================================

Clase 1, versi´on preliminar (las cr´ıticas son bienvenidas)

1 Introducción
--------------

Con probabilidad 1, la primera clase de un primer curso sobre ecuaciones diferenciales comienza con el siguiente ejemplo

.. math::

   x'(t) = x(t).


Más allá de las bromas estudiantiles sobre la función exponencial, todo el
mundo acepta inmediatamente que :math:`x(t) = e^t` es una solución y, con un m´ınimo
esfuerzo adicional, que todas las soluciones son de la forma x(t) = Cet
, en donde
C es una constante arbitraria. Podemos suponer :math:`C \in \mathbb{C}`C y entonces es fácil ver
que la fórmula obtenida abarca todas las posibles soluciones complejas de la
ecuación. Muy pronto, esta idea elemental se transforma en un método general
para obtener soluciones de ecuaciones lineales con coeficientes constantes: “proponer” soluciones de la forma :math:`x(t) = e
^{λt}` y hallar los valores de λ que anulan el
polinomio característico asociado a la ecuación. Claro que en nuestro ejemplo,
todo se torna bastante trivial: como x
0
(t) = λx(t), al reemplazar en la ecuaci´on
resulta
λx(t) = x(t)
y el polinomio caracter´ıstico es P(λ) = λ − 1, que obviamente tiene al valor
λ = 1 como ´unica ra´ız.
Sin embargo, la situaci´on cambia de manera dr´astica si suponemos que la
ecuaci´on tiene un retardo τ > 0, vale decir
x
0
(t) = x(t − τ ).
En efecto, ahora al reemplazar x(t) = e
λt en la ecuaci´on resulta
λx(t) = x(t − τ ) = e
λ(t−τ) = e
−λτx(t).
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


