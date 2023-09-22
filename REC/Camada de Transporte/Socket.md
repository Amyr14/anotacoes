Um socket pode ser visto como uma abstração usada na camada de transporte para estabelecer uma conexão lógica entre dois processos.

### UDP
Um socket [[UDP]] é composto pela tupla $\large (IP; porta)$. Ele não estabelece nenhuma conexão, somente recebe informação.

### TCP
Um socket [[TCP]] é composto pela tupla $\large (IP_{dest}; porta_{dest}; IP_{origem}, porta_{origem})$ . Ele estabelece uma conexão duplex entre dois hosts. Dados podem ser enviados e recebidos por um socket TCP.
