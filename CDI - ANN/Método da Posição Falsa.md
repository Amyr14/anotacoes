---
tags: Metodo_Numerico
---
Método para encontrar o zero de uma certa função $\large f: [a, b] \to R$ contínua, tal que $\large f(a)f(b) < 0$ (ver [[Teorema de Bolzano | teorema de Bolzano]]. Consiste em dividir o intervalo $\large [a, b]$ em subintervalos sucessivamente menores que contenham a raiz. Quando é encontrado um subintervalo suficientemente pequeno, o método encerra.

### Algoritmo
*Passo 1* -> Tome a reta $\large r$ formada pelos pontos $\large (a , f(a))$ e $\large (b, f(b))$. Tome $\large m = b - \frac{f(b)}{d}$, onde $\large d = \frac{f(b) - f(a)}{b - a}$ ($\large m$ é o valor de $\large x$ que faz com que $\large r$ intercepte o eixo). 
*Passo 2* ->  Se $\large f(a)f(m) < 0$ , $\large b = m$.  Se $\large f(b)f(m) < 0$ , $\large a = m$
*Passo 3* -> Se $\large | b - a | < 2lim$ , encerrar a iteração. Se não, voltar ao passo 1
