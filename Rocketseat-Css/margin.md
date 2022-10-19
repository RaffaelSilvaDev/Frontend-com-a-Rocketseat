# Margin

Descrição
Margin, é o espaço (margem) entre os elementos

Podemos dividir o margin em 4 valores:

/_ margin-top | margin-right | margin-bottom | margin-left _/
values: <length> | <percentage> | auto

Geralmente usamos uma forma abreviada
(shorthand) para escrever o margin.
Esse formato segue o sentido horário
iniciando pelo top,
seguindo para right,
bottom
left.

margin: 12px 16px 10px 4px; /_ TOP = 12px | RIGHT = 16px | BOTTOM = 10px | LEFT = 4px _/
margin: 12px 16px 0; /_ TOP = 12px | RIGHT = 16px | BOTTOM = 0px | LEFT = 16px _/
margin: 8px 16px; /_ TOP = 8px | RIGHT = 16px | BOTTOM = 8px | LEFT = 16px _/
margin: 8px; /_ TOP = 8px | RIGHT = 8px | BOTTOM = 8px | LEFT = 8px _/
O margin é aplicado em elementos com display block
Cuidado com o margin collapsing que é quando o top se junta ao bottom
