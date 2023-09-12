Analisando a convergência do [[Método da Bisseção | método da bisseção]], podemos obter as $\large k$ iterações necessárias para obter um resultado dentro de uma certa tolerância.

### Desenvolvimento
Como dividimos o intervalo por dois a cada iteração, observamos que o critério de parada é dado por $$\large \frac{a + b}{2^{k}} \le 2tol$$ Isolando $\large k$, temos $$\large \frac{a + b}{tol} \le 2^{k + 1}$$
$$\large log_{2}(\frac{a + b}{tol}) - 1 \le k$$


Logo, o número de iterações é o primeiro $\large k$ inteiro que satisfaz a expressão