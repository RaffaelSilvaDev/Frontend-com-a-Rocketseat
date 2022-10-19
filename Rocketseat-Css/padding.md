# Padding

Descrição
O padding é o preenchimento interno da caixa.

A propriedade padding pode ser escrita como nos formatos apresentados abaixo:

/_ padding-top | padding-right | padding-bottom | padding-left _/
values: <length> | <percentage>

padding-top | padding-right | padding-bottom | padding-left
Geralmente usamos uma forma abreviada (shorthand) para escrever o padding.
Esse formato segue o sentido horário iniciando
pelo top,
seguindo para right,
bottom
e left.

padding: 12px 16px 10px 4px; /_ TOP = 12px | RIGHT = 16px | BOTTOM = 10px | LEFT = 4px _/
padding: 12px 16px 0; /_ TOP = 12px | RIGHT = 16px | BOTTOM = 0px | LEFT = 16px _/
padding: 8px 16px; /_ TOP = 8px | RIGHT = 16px | BOTTOM = 8px | LEFT = 16px _/
padding: 8px; /_ TOP = 8px | RIGHT = 8px | BOTTOM = 8px | LEFT = 8px _/
O padding pode ter valores (values) de comprimento (px, em, rem) ou de porcentagem (%)

O padding poderá causar diferença na largura de um elemento
obs.: Na aula sobre box-xizing aprendemos como resolver essa diferença na largura do elemento

https://app.rocketseat.com.br/node/uma-caixa-dentro-da-outra/lesson/box-sizing
