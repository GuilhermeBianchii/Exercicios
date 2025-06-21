/* Exercício 3: Prazo de entrega com base no valor do pedido
📋 Regras:
Se o pedido for maior ou igual a R$ 300, o prazo de entrega é 1 dia útil.

Se o pedido for entre R$ 100 e R$ 299.99, o prazo é de 3 dias úteis.

Se o pedido for menor que R$ 100, o prazo é de 7 dias úteis.

💡 Exemplos:
Pedido: R$ 350 → Prazo de entrega: 1 dia útil

Pedido: R$ 180 → Prazo de entrega: 3 dias úteis

Pedido: R$ 80 → Prazo de entrega: 7 dias úteis

📦 Entradas esperadas:
valorDoPedido (número)

DECOMPOSIÇÃO:
-Verificar Valor Do Pedido
-Se for <= 300, 1 dia util
-Se for  <=100 e <300 ,3 dia util
-Se for menor  que 100,7 dias uteis
-Declarar valor com o prazo de entrega

SEQUENCIA DE PASSOS:
1-Verificar Valor Do Pedido- OK
2-Se for MAIOR OU IGUAL 300, PRAZO 1 DIA UTIL - OK
3-Se for  MAIOR OU IGUAL 100 ATÉ 299.99, PRAZO 3 DIAS UTEIS - OK
4-Se for MENOR  que 100,7 dias uteis - OK
5-Declarar valor com o prazo de entrega */


function definirPrazoDeEntrega(valorDoPedido){
    let diasUteis
    if(valorDoPedido >= 300){
        diasUteis = 1
        return diasUteis  +  ' Dia Útil'
    } else if (valorDoPedido >= 100){
        diasUteis = 3
    } else {
        diasUteis = 7
    }
    return diasUteis  +  ' Dias Úteis'
}
const prazoDaEntregaTrezentosReais = definirPrazoDeEntrega(300)
console.log(prazoDaEntregaTrezentosReais)
const prazoDaEntregaCemReais = definirPrazoDeEntrega(100)
console.log(prazoDaEntregaCemReais)
const prazoDaEntregaVinteReais = definirPrazoDeEntrega(20)
console.log (prazoDaEntregaVinteReais)
