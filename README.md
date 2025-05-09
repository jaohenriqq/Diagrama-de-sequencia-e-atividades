# Diagrama-de-sequencia-e-atividades
Ex: locadora online
//diagrama de sequência

USUÁRIO>INTERFACE: Escolhe o filme e informa dados do usuário.
INTERFACE>SERVIDOR: Envia dados.
SERVIDOR>BANCO DE DADOS: Verifica se existe em estoque.
BANCO DE DADOS>SERVIDOR: Resposta.
SERVIDOR>INTERFACE: Envia o resultado.
INTERFACE>USUÁRIO: Confirma ou exibe que a compra não foi realizada.


//DIAGRAMA DE ATIVIDADES

[INÍCIO]
↓
[CLIENTE ESCOLHE O FILME]
↓
[CLIENTE CONFIRMA SEU PEDIDO]
↓
[TEM PRODUTO EM ESTOQUE?]
→SIM: [FAZER DAS INFORMAÇÕES DO USUÁRIO]→ [FINALIZAR PEDIDO] →[FIM]
→NÃO: [MOSTRA MENSAGEM DIZENDO QUE O PEDIDO NÃO PODE SER REALIZADO] →[FIM]




