Tecnologias a serem utilizadas:
HTML
CSS
Javascript
PHP (Laravel, Lumen)
O que vamos avaliar:
Legibilidade do código
Modularização
Lógica para aplicar a regra de negócio
Utilização da API
O Desafio:
O usuário precisa informar 3 informações em tela, moeda de destino, valor para conversão e forma de pagamento. A nossa moeda nacional BRL será usada como moeda base na conversão.

As Regras de negócio:
Moeda de origem BRL;
Informar uma moeda de compra que não seja BRL (exibir no mínimo 2 opções);
Valor da Compra em BRL (deve ser maior que R$ 900,00 e menor que R$ 900.000,00)
Formas de pagamento (taxas aplicadas no valor da compra e aceitar apenas as opções abaixo)
Para pagamentos em boleto, taxa de 1,37%
Para pagamentos em cartão de crédito, taxa de 7,73%
Aplicar taxa de 2% pela conversão para valores abaixo de R$ 3.700,00 e 1% para valores maiores que R$ 3.700,01, essa taxa deve ser aplicada apenas no valor da compra e não sobre o valor já com a taxa de forma de pagamento.
Exemplos de entrada:
Moeda de origem: BRL (default)
Moeda de destino:
Exemplo: USD, BTC, ...
Valor para conversão:
Exemplo: 5.000,00, 1.000.00, 70.000,00, ...
Forma de pagamento:
Boleto ou Cartão de Crédito
Exemplo de funcionamento:
Parâmetros de entrada:
Moeda de origem: BRL (default)
Moeda de destino: USD
Valor para conversão: 5.000,00
Forma de pagamento: Boleto
Parâmetros de saída:
Moeda de origem: BRL
Moeda de destino: USD
Valor para conversão: R$ 5.000,00
Forma de pagamento: Boleto
Valor da "Moeda de destino" usado para conversão: $ 5,30
Valor comprado em "Moeda de destino": $ 921,03 (taxas aplicadas no valor de compra diminuindo no valor total de conversão)
Taxa de pagamento: R$ 68,50
Taxa de conversão: R$ 50,00
Valor utilizado para conversão descontando as taxas: R$ 4.881,50
Critério de aceitação:
Deve ser possível escolher uma moeda estrangeira entre pelo menos 2 opções sendo o seu valor de compra maior que R$ 1.000 e menor que R$ 100.000,00 e sua forma de pagamento em boleto ou cartão de crédito tendo como resultado o valor que será adquirido na moeda de destino e as taxas aplicadas;

Bônus:
Enviar cotação realizada por email;
Autenticação de usuário;
Histórico de cotações feita pelo usuário;
Uma opção no painel para configurar as taxas aplicadas na conversão;
Informações úteis da api:
Conversão BRL para USD
https://economia.awesomeapi.com.br/json/last/BRL-USD
Moedas para conversão
https://docs.awesomeapi.com.br/api-de-moedas#moedas-com-conversao-para
Tradução das moedas
https://economia.awesomeapi.com.br/json/available/uniq
Combinações possíveis
https://economia.awesomeapi.com.br/json/available
Legendas
https://docs.awesomeapi.com.br/api-de-moedas#legendas