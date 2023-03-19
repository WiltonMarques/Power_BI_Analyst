1) na conexão ao banco de dados foi usada a linha de comando:

mysql -h desafio-project-dio.mysql.database.azure.com -u powerbimasteradmin -p


2) na conexão com o workbench foi usado os seguintes parâmetros:
Nome do servidor: xxxxxxxxxxxxxxxxxxx; Azure opção Visao Geral;
User name: Nome logon do Admi: aaaaaaaaaaaaaaa; Azure opção Visao Geral;


3) na criação das tabelas foi alterado a ordem em que os comandos foram executados, primeiro foi realizado a criação das tabelas, em seguida a carga do dado, aí as alterações.

4) no momento de execução da alteração da tabela department " ... alter table departament drop  departament_ibfk_1;" 
departament_ibfk_1 não tinha sido criado!!! -         foi resolvido comentando essa parte!  
alter table departament #drop  departament_ibfk_1#;


14. Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir.
Por que estão nas colunas individualizados;






