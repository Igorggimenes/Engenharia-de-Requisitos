Sua vez de elicitar
Voce foi designado para elicitar os requisitos de um sistema do zero. A empresa vende produtos por telefone ou em
encontros presenciais. Vendedores devem acessar o sistema pra registrar pedidos, o administrador para cadastrar e
remover produtos, e o time de estoque para controlar a quantidade disponivel, dando baixa nas saidas e registrando
as entradas.
Para cada um dos tres processos, escreva tres requisitos do sistema e aponte as fontes de informacao que voce
usaria pra especifica-lo. Classifique cada fonte, dizendo o nivel se for humana (estrategico, tatico, operacional
[+classe do usuario] ou externo) ou a categoria se for nao humana (documentacao, sistema legado, concorrencia ou
norma).
Um exemplo de como o resultado deve ficar.

Requisito: O sistema deve registrar a forma de pagamento escolhida no momento da venda.
Fonte 1: Entrevista com o vendedor. Fonte humana, nivel operacional, classe de usuario vendedor.
Fonte 2: Politica comercial sobre formas de pagamento aceitas. Fonte nao humana, categoria documentação.

Minha resposta:

--Vendedores
O sistema deve registrar o usuário que fez cada alteração.
Fonte: LGPD (lei de averiguação), não humana.
Fonte: Sistema legado, não humana.

Na tela de registro deve ter metodo de pagamento, data, usuario e produto
Fonte: Norma escrita da empresa, não humana.

O sistema deve não aceitar se tiver informacoes erradas na publicação do registro.
Fonte: Concorrência e entrevista não estruturada, virou expectativa básica, humana e não humana.

--Administrador
O sistema deve permitir somente à este tipo de usuário a cadastrar produtos.
Fonte: Norma da empresa, não humana, categoria documentação.

Editar produtos deve ser uma das opções no menu deste usuario quando seleciona o botão de tres pontinhos do produto.
Fonte: Sistema legado, mão humana,  categoria de registros.
Fonte Concorrência, não humana, registro.

O sistema deve permitir a este usuário remover produtos cadastrados.
Fonte: Usuário final do tipo administrador em entrevista, ele disse que as vezes coloca errado, ou o chefe muda de ideia, operacional, pessoa.

--Estoquistas
Registrar saida/entrada/edição de estoque.
Fonte: Entrevista estruturada com stakeholder de nível tático, fonte humana.

Metodo de login que ao colocar um login deste tipo de usuário mostrar apenas a seção dele e não outras funções de outros tipos de usuário.
Fonte: Fonte não humana, concorrência, equisito não funcional de simplicidade.
Fonte: Fonte não humana, norma da empresa, categoria de documentação.

O sistema deve responder 99,9% do tempo com 500 usuários ativos, caso problemas tecnicos deve se recuperar em até 5 minutos.
Fonte: Entrevista estruturada com stakeholder de nível estratégico, fonte humana.
