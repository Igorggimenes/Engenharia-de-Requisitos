Registrar pedidos coletados

Ator principal: Coletor.
Descrição: Coleta de uma compra na shopee pela agência.
Gatilho: Um vendedor entrega uma venda shopee ao usuário.
Pre condição: Conta cadastrada como agência shopee, sem mais de 3 penalidades nos ultimos 30 dias, modo férias desativado, login na conta realizado.
Pós condição: Pedido registrado e armazenado para ser buscado pela logística shopee.

Fluxo principal:
1 O usuário abre a camera de identificação de QR-code de pedidos;
2 O usuário aponta para o QR-code da etiqueta do pedido;
3 O sistema identifica que o pedido;
4 O sistema verifica se ele não foi coletado previamente e se está apto para isso;
5 O sistema registra o pedido estando na agência em questão;
6 O sistema mostra ao usuário que o pedido foi coletado com sucesso;
7 O usuário avisa o vendedor que o pedido foi processado com sucesso, que ele está liberado;
8 O usuário armazena o pedido.

Fluxo alternativo - Pedido para retirada no local:
Quando: No passo 5, o sistema percebe que não é um pedido padrão de postagem.
Passos: 1 O sistema mostra ao usuário que o pedido foi coletado com sucesso;
2 O sistema avisa ao usuário que o pedido é de retirada no local, para guardar separadamente e pronto para a chegada do cliente que pode vir a qualquer momento;
Retorno: O fluxo volta ao passo 7

Exceção - Pedido já coletado:
Quando: No passo 4 o sistema detecta que o pedido já foi coletado.
Passos: 1 O sistema detecta que o pedido foi previamente coletado;
2 O sistema mostra ao usuário que não é possível prosseguir por este erro em questão;
3 O usuário avisa o vendedor que trouxe o pedido que não podera coletar o pedido em questão por este acontecimento.
Retorno: Não há retorno ao fluxo principal.