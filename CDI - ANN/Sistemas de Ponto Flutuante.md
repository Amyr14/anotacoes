Um sistema de ponto flutuante contém uma base $\large \beta$, $\large t$ números na mantissa e expoente $\large m \le e \le M$, formando a 4-upla
$$\large F(\beta, t, m, M)$$
Quando formos converter um número para o sistema $\large F$, identificar a necessidade de arredondamento primeiro. Se o exercício somente exigir truncamento, basta apenas identificar os $\large t$ primeiros dígitos e converter para o sistema $\large F$. Obs: o primeiro digito da mantissa não pode ser zero.

### Epsilon da Máquina
É a distância entre 1 e o menor número estritamente maior que um que pode ser representado em um sistema $\large F$. É dado por
$$\large  \epsilon =  \beta^{ 1- t}$$

### Exemplo
Dado o sistema $\large F(10, 3, -5, 5)$, converta os números