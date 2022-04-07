Critérios de aceitação

1. A aplicação front-end deve permitir o usuário realizar consultas dos indicadores de pobreza do banco mundial de
determinado país através da sigla do país.

2. O resultado da consulta na aplicação front-end deve exibir apenas o ano e o indicador de pobreza mundial em uma tabela de forma paginada e ordenada.
O valor padrão para ordenação será através do ano de forma decrescente e poderá ser alterado pelo usuário optando ordenar pelo ano ou pelo indicador 
de pobreza mundial de forma crescente ou decrescente.
O valor padrão para a paginação será de 5 itens por página e poderá ser alterado entre os valores 5, 10, 15, 30 e 50 pelo usuário.

3. A aplicação front-end não deve consultar o banco mundial diretamente, devendo fazer a consulta através da aplicação back- end.

4. A aplicação back-end deve ser agnóstica e retornar todo resultado da consulta sem nenhum tratamento específico, permitindo que a aplicação 
front-end decida qual informação deverá ser exibida ao usuário final.

5. Caso algum erro aconteça, seja entre a comunicação entre o front-end e o back-end ou algum erro por parte do back-end, a aplicação front-end 
deve exibir uma mensagem de erro genérica em uma página específica de erro.
