# 7-days-for-code-Alura

Hoje iniciei meu primeiro dia do #7DaysOfCode da Alura com a orientação de Francisco Tadeu Foz sobre Python e Pandas 🐍🐼

Descobri diversas coisas legais que o Pandas pode fazer, como ler arquivos CSV a partir de um link para repositórios públicos do Github, além disso aprendi na prática a concatenação de DataFrames através do .Concat, pois são muitos dados importados, praticamente todo o registo de empréstimos de uma biblioteca em 10 anos, então tínhamos todos os dados de empréstimos separados dos exemplares para que possamos unir os dados e limparmos as repetições, usando o drop_duplicates()
Após realizar a limpeza no DataFrame com o método citado acima, fizemos a inclusão dos exemplares e utilizamos o Merge para mesclar todos os exemplares com seus respectivos empréstimos, foi demais!

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SEGUNDO DIA DE #7DaysOfCode na Alura 🐼🐍

Hoje realizei algumas modificações importantes no DataFrame fornecido pela Universidade Federal do Rio Grande do Norte onde pude mesclar todos os exemplares disponíveis pela instituição com todos os registros de empréstimos feitos desde o 1º semestre de 2010 até o 1º semestre de 2020.

1 - Inicialmente obtivemos a informação sobre o DCU, que seria uma classificação de categorias para todos os exemplares baseado no código, então adicionei esta coluna dentro do nosso DataFrame e através do for, mapeei todas as condições e defini todas as categorias possíveis de acordo com a numeração pré-determinada

2 - Para melhorarmos a visualização do nosso DataFrame, foi sugerido no desafio a exclusão de algumas colunas que não seriam úteis para a análise de dados e a finalidade determinada, então usei o método drop collumns para retirar a coluna registro_sistema

3 - Para melhorar ainda mais nosso processo de leitura e compreensão dos dados importados, converti o tipo de dado demonstrado na coluna matricula_ou_siape para String, que facilitava a leitura, pois o tipo de dado trazia uma notação matemática nada prática de ser lida

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
