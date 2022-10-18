# From CSV to SQL


## Contexto

 Um desenhista freelancer anota seus pedidos em arquivos CSV, onde cada pedido tem uma data de entrega, data de entrega e o tipo de desenho que ele terá que fazer.
O programa pega os dados deste arquivo CSV determinado e os tranforma em uma tabela de banco de dados do SQLite3, além de permitir a manipulação dos dados guardados. Assim ele teria uma melhor organização de seus pedidos, acesso mais rápido além de abrir a possibilidade para ele implementar novas funções de manipulação, como por exemplo, ver todos os pedidos de um tipo específico.


## Intenções de Aprendizado

 Tenho em mente que muitas das funções e ideias que tive poderiam ser bem mais fáceis com alguma biblioteca, como o pandas por exemplo, mas decidi fazer tudo na mão para praticar e aprender novos conceitos de:

- Lógica
- Organização de Notebooks
- Manuseio no Github
- Boas praticas de programação
- Noções basicas manipulação com CSV e banco de dados relacional


## Ideias

 A ideia que tinha para o codigo era fazer com que cada função fosse o mais abrangente possível para que não ficasse precisando escrever tanto do mesmo, o que parece bom mas exige um pouco mais de cuidado com as informações que estão entrando e saindo das funções. Nem todas as ideias que tive acabei aplicando no código de primeira para não deixar tudo muito complicado, então foquei primeiro no mais simples e depois vou implementando algumas melhorias como:
 
 - Tratamento de erros e exceções
 - Tratamento de dados de entrada e saída
 - Conseguir criar uma tabela no banco de dados mediante aos dados existentes no CSV, usando o cabeçalho para criar os campos e então popular cada um com seus respectivos dados.


## Desafios

 Meu primeiro desafio foi com o arquivo CSV que iria criar para fazer os testes. De inicio me preocupei com os espaços vazios que ele estava apresentando e sinceramente ainda não entendi de onde ele veio, porém acabei notando que não precisava me preocupar com isso já que era só preencher ele com o restante dos dados que eu iria usar.
 O outro desafio que tive foi com a logica na hora de executar as funções mediante as opções escolhidas, precisando pensar em como as funções iriam receber os dados do teclado do jeito que deveriam. Fora estes, tive apenas que quebrar um pouco mais para pensar em como implementar cada função de forma que ela tivesse a abragencia. Não consegui em todas, mas acredito ter aprendido bastante em cada etapa.
 

## Desculpas

 Peço desculpas pelos possíveis erros quanto a organização do código, erros de inglês e até de português se tiver. Inglês é algo que tenho um conhecimento básico mas estou desenvolvendo mais esse ano e decidi que iria tentar o máximo possível no código.
