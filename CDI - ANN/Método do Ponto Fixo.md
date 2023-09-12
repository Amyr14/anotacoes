---
tags: Metodo_Numerico
---
O ponto fixo de uma função $\large g$ é o ponto em que $\large g(x) = x$. Podemos usar isso para encontrar a raiz $\large x^{*} \in [a, b]$ da função $\large f$ se $f\large (x^{*}) = 0$ implicar em $\large g(x) = x$ e $\large g$ [[Convergência Para o Ponto Fixo |convergir]] para o fixo dentro do intervalo $\large [a, b]$. 

### Algoritmo
Sempre começar as questões de ponto fixo analisando a derivada da função no intervalo dado. 
*Passo 1* -> Identificar $\large g(x)$ tal que $\large g(x) = x$, tomar $\large x_{i}$ como um chute qualquer
*Passo 2* -> Tome $\large x_{i + 1} = g(x_{i})$ 
Passo 3 -> Se $\large | x_{i + 1} - x_{i} | < lim$, tome $\large x_{i + 1}$ como resposta. Se não, $\large x_{i} = x_{i + 1}$ e voltar ao passo 2. 



