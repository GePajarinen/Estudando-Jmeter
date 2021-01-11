JMeter – testes de performance (UDEMY)
Projeto 1 – Realizando testes de performance em umeCommerce
Baseado em u projeto aplicado no mundo real.

Objetivo
Simulação de carga gradativa buscando alcançar o momento de degradação da infraestrutura, possibilitando a identificação de gargalos.

Estratégias de performance
Usuários simultâneos: Muitos usuários acessando em curto período de tempo.

Duração do teste
Bateria de teste: aproximadamente 30 minutos.

Cenário de teste 1
Usuário navegador: abrir home, acessar categorias diferentes, acessar produtos diferentes.

Cenário de teste 2
Usuário buscador/pesquisador: abrir home, realizar busca, abrir produtos da busca.
Palavras de busca: shirt, dress

Cenário de teste 3
Usuário comprador: Abrir produto, adicionar na cesta, realizar login, confirmar endereço, forma de entrega, forma de pagamento, abrir página do pedido.

Cenário de teste 4
Usuário acessando outras páginas: páginas diversas. Promoções entre outras.

Configurações iniciais
Entre um passo e outro iremos adicionar um think time de 10 a 30 segundos.



curso_teste_1@gmail.com
curso_teste_2@gmail.com
curso_teste_3@gmail.com
curso_teste_4@gmail.com
curso_teste_5@gmail.com
abc.123

Aula 52
Nome de Referência: codigoOrdem

Expressão Regular: controller=(.+?)&id_cart=(.+?)&id_module=(.+?)&id_order=(.+?)&key=(.+?)

Modelo: $4$

Número para combinação: 1