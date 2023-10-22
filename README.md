# Processando e Transformando Dados com Power BI
Desafio de projeto do bootcamp DIO - Santander - Ciência de Dados com Python

Carreguei os scripts sql disponibilizados na plataforma azure e fiz a conexão com o MySQL Workbench e conexão com o Power BI.

Optei por fazer todas as transformações no Power Bi para consolidar meu aprendizado na ferramenta.

Transformei os dados da coluna "salary" em decimal fixo, conforme solicitado.
Exclui colunas e tabelas que não eram necesárias para a análise solicitada.
Fiz uma filtragem e percebi que somente o funcionário "James Borg" não possuia gerente, o que nos leva a concluir que ele é o gerente geral.
Através da análise do Ssn e Super_ssn podemos observar dois gerentes abaixo dele, que gerenciam o restante dos funcionários.
Verificado número de horas por projeto através da mescla entre projects e works_on, seguido da soma de horas agrupadas por projetos.
Mescladas tabelas employee e departament para criar uma tabela employee-department com o nome dos departamentos associados aos colaboradores.
Criada tabela de funcionários com seus respectivos gerentes. Mescladas colunas de nomes e sebrenomes.
Associação dos nomes dos departamentos e localizações.
Feito relatório para demonstrar resultados.

Questão: Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o
atribuir.
Mesclar funciona como join do sql e acrescenta colunas a uma tabela, de acordo com uma correspondência (chave). Acrescentar funciona como union do sql e acrescenta linhas a tabela.

