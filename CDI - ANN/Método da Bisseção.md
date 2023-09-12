---
tags: Metodo_Numerico
---
Para uma função $\large f : [a, b] \to \mathbb{R}, f(a)f(b) < 0$  (ver [[Teorema de Bolzano | teorema de Bolzano]]) o método da bisseção encontra uma aproximação da raiz de $\large f$. Ele consiste em dividir sucessivamente o intervalo em intervalos progressivamente menores que contenham a raiz, até que se encontre um intervalo suficientemente pequeno.

## Algoritmo
*Passo 1* -> Tome $\large m = \frac{a + b}{2}$ (ponto médio do intervalo)
*Passo 2* -> Se $\large f(a)f(m) < 0, b \leftarrow m$ .  Se $\large f(b)f(m) < 0, a \leftarrow m$.
*Passo 3* -> Se $\large | b - a | < 2lim$, encerrar o algoritmo. Se não, voltar ao passo 1.
### Taxa de convergência

Descreve o quão rápido o método encontra a aproximação da raiz.