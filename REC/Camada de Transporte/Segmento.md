Um segmento é uma parte de um bloco de dados enviados pela [[Camada de Aplicação |camada de aplicação]].  Quando a camada de aplicação manda um bloco de dados para a camada de transporte, ele é dividido em pedaços menores chamados *segmentos* pela [[Camada de Transporte |camada de transporte]]. O seu tamanho é limitado pelo MSS (maximum segment size), que por si é definido pela placa de rede. Um segmento é composto de header e payload.

### Header
Contém a porta de origem, porta de destino, bits de flag e etc.

### Payload
Contém os dados que devem ser destinados ao processo destinatário.