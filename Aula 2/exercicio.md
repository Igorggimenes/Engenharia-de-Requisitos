--Historias de usuario requisitadas:--

==Como usuario, quero acompanhar o pedido pago e saber em qual parte está e uma estimativa de quando chegará para receber o pedido.

==Como CEO de restaurante, quero ter a opção de mudar o status de um item no cardapio à indisponivel para não receber pedidos que não posso cumprir.

==Como entregador, quero poder reportar um problema durante a entrega para quando eu precisar de suporte e de registrar estas informações do pedido.

--Criterios de aceitação requisiados:--

==Dado o pagamento do pedido, enquanto(quando) estiver sendo preparado e levado por um entregador, (então) aparece na tela do cliente em qual parte do processo está (Preparação/transporte), em tempo real, e se o processo foi interrompido por algum acidente.
==Dado o pagamento do pedido, enquanto(quando) estiver sendo preparado (primeira parte), (então) aparece na tela do cliente o horario de confirmação de compra e o horario esperado de termino de preparo.
==Dado o pagamento do pedido, enquanto(quando) estiver sendo transportado (segunda parte), (então) aparece na tela do cliente o horario de saída do pedido e o horario esperado de chegada.

==Dado um pedido que não posso cumprir, quando aperto para trocar os status do item, então fica registrado para mim que o item está indisponivel/disponivel.
==Dado um pedido que não posso cumprir, quando aperto para trocar os status do item, então fica registrado para os clientes que o item está indisponivel/disponivel.
== Dado um pedido registrado como indisponivel, quando um cliente tenta compra-lo, então o software bloqueia.

==Dado um pedido recebido por mim, se(quando) for roubado/perdido/danificado, então posso apertar um botão que registra meu problema e informa o cliente e o vendedor.
==Dado um pedido recebido por mim, se(quando) o cliente não receber o pedido, então quero um botão de registrar isso e concluir a entrega.
==Dado um pedido recebido por mim, se(quando) o endereço estiver errado (resultar em um lugar vazio ou outro estabelecimento), então quero poder notificar o restaurante e o cliente.

--Ordenação usando MoSCow requisiada:--

== Must == Como CEO de restaurante, quero ter a opção de mudar o status de um item no cardapio à indisponivel para não receber pedidos que não posso cumprir.

== Must == Como entregador, quero poder reportar um problema durante a entrega para quando eu precisar de suporte e de registrar estas informações do pedido.

== Should == Como usuario, quero acompanhar o pedido pago e saber em qual parte está e uma estimativa de quando chegará para receber o pedido.