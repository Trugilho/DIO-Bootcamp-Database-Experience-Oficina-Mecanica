O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados

Desafio 
Neste desafio, você terá a missão de compreender o papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados. Para isso, anote todos os conceitos, definições e insights que julgar relevantes em um novo repositório Git, aumentando assim seu portfolio de conhecimentos.

Dados - Informações úteis que necessitamos guardar e acessar.

Banco de dados - Repositórios onde são guardadas/armazenados informações úteis(dados), um conjunto de dados que tem contexto, coerência e propósito. São coleções organizadas de informações estruturadas(dados) relacionadas entre sí, normalmente armazenadas eletronicamente em um sistema de computação(SGBD).

SGBDs - São sistemas informatizados, um conjunto de softwares  responsáveis por administrar e gerenciar os repositórios de dados, a base de dados, os bancos de dados. Os sistemas SGBDs são responsáveis por disponibilizar e administrar inclusões, alterações e consultas aos dados armazenados nos bancos de dados.

SQL - Significa “Structured Query Language”, o SQL é uma linguagem declarativa de sintaxe relativamente simples, voltada a bancos de dados relacionais, que pode ser aprendida por profissionais que não são necessariamente desenvolvedores, mas trabalham com bancos de dados com frequência. Linguagem usada para - Manipulação de dados e Execução de operações criada em 1970.
Objetivo do SQL - Modificação de dados e estrutura de dados, adicionar, remover ou atualizar linhas do BD, Recuperação de um subconjunto de informações do BD.
A linguagem SQL é utilizada de maneira relativamente parecida entre os principais bancos de dados relacionais do mercado: Oracle, MySQL, MariaDB, PostgreSQL, Microsoft SQL Server, entre muitos outros. Cada um tem suas características, sendo o MySQL e o PostgreSQL extremamente populares por possuírem versões gratuitas e de código aberto. A linguagem SQL é utilizada de maneira relativamente parecida entre os principais bancos de dados relacionais do mercado: Oracle, MySQL, MariaDB, PostgreSQL, Microsoft SQL Server, entre muitos outros. Cada um tem suas características, sendo o MySQL e o PostgreSQL extremamente populares por possuírem versões gratuitas e de código aberto. É também uma linguagem que muitos profissionais acabam precisando aprender: seja quem usa Excel de forma pesada e acaba migrando as informações para um banco de dados, seja um cientista de dados que usa Python para agregar os dados das diferentes fontes de informações. 

NoSQL - Significa "No Only SQL". O termo 'NoSQL' se refere a tipos não relacionais de bancos de dados, e esses bancos de dados armazenam dados em um formato diferente das tabelas relacionais. No entanto, os bancos de dados NoSQL podem ser consultados usando APIs de linguagem idiomática, linguagens de consulta estruturadas declarativas e linguagens de consulta por exemplo, razão pela qual também são chamados de bancos de dados "não apenas SQL". Para que é usado um banco de dados NoSQL? Os bancos de dados NoSQL são amplamente usados em aplicativos da web em tempo real e big data, porque suas principais vantagens são alta escalabilidade e alta disponibilidade. Os bancos de dados NoSQL também são a escolha preferida dos desenvolvedores, pois eles naturalmente aceitam um paradigma de desenvolvimento ágil, adaptando-se rapidamente aos requisitos em constante mudança. Os bancos de dados NoSQL permitem que os dados sejam armazenados de maneiras mais intuitivas e fáceis de entender, ou mais próximas da maneira como os dados são usados pelos aplicativos - com menos transformações necessárias ao armazenar ou recuperar usando APIs no estilo NoSQL. Além disso, os bancos de dados NoSQL podem aproveitar ao máximo a nuvem para oferecer tempo de inatividade zero.

No mundo da ciência de dados, são usadas várias ferramentas para trabalho/auxílio, uma delas e talvez a maior são os bancos de dados. É quase imprescindível o uso de banco de dados nessa área, pois precisamos de um repositório para alem de armazenar os dados, fazer isso de forme coerente pois quando for necessário a recuperação desses dados, eles precisam estar de forma organizados . Neste contexto existem dois tipos de bancos de dados, os relacionais e os não relacionais, ou melhor dizendo, não somente SQL,(NoSQL).

A estrutura dos bancos relacionais ou SQL são formadas de entidades e relacionamentos, onde um dado pode estar relacionado a outro através de chaves relacionais( chaves primárias e chaves estrangeiras). Seu schema é baseado em forma de tabelas e colunas, onde alguma tabela pode se relacionar com outra, fazendo uma recuperação de dados mais sólida e complexa através de querys de ligação de tabelas.

Ja os bancos NoSQL não possuem entidades e relacionamentos, e os seus dados só se relacionam através de querys usando algum atributo específico. Existem vários modelos de bancos NoSQL no mercado, e o modelo mais usado é baseado em documentos, como o MongoDB que utiliza JSON e BSON como tipo de linguagem para armazenar os dados.

Cada banco tem sua utilização específica para cada tipo de trabalho, por isso para um engenheiro de dados, é preciso traçar qual o objetivo na hora de escolher um banco de dados, pensar de que forma será recuperado os dados e se necessita de relacionamento entre eles. Um banco de dados SQL tem mais solidez e integridade dos dados utilizando seus relacionamentos, porém ele não é tão agil e robusto quando se busca agilidade e poder de armazenamento no processo, o que um banco orientado a documentos do tipo NoSQL ja desenpenha bem essa função.

No meu ponto de vista, um engenheiro de dados deve trabalhar simultaneamente com os dois tipos de bancos, pois cada um vai ser especifico para cada tarefa e está cada vez mais comum a utilizacao simultanea de vários tipos de banco de dados pelas empresas, ficando assim mais facil a compreensão e entendimento dos dados armazenados, de forma que consiga extrair o máximo de informação que ele pode te oferecer.

Os engenheiros de software que irão trabalhar com o sistema para o Big Data ou com  sistemas  que  demandem  o  uso  de  um  SGBD  NoSQL,  precisam  conhecer  essa tecnologia para terem condições de modelar o sistema seguindo esse novo paradigma e saberem  também,  quando  um  projeto irá demandar  uma  solução flexível e  escalável, evitando  assim  que  projetos  fracassem  ou  ultrapassem  o  orçamento  por  conta  de reengenharia.   
Já os engenheiros de dados são os responsáveis por manter essa estrutura de dados, garantindo a escalabilidade, consistência dos  dados  e  fornecendo  mecanismos  para  os analistas de dados extraírem informações úteis das bases, o que não é uma tarefa trivial frente ao Big Data.   Para que soluções envolvendo o uso de SGBDs NoSQL deem certo, é necessário além da comunicação entre os engenheiros de dados e de software, que ambos estejam alinhados  com  essa  tecnologia,  buscando  extrair  o melhor  de cada  SGBD  para  cada solução  provida.  Profissionais  que  não  se  atualizarem,  ficarão  limitados  a  sistemas triviais.


Referências:
Tutoriais e comandos SQL:
https://www.w3schools.com/sql/default.asp
https://www.1keydata.com/pt/sql/sql-alter-table.php

Artigos:
https://sites.google.com/site/uniplibancodedados1/aulas/normalizacao
https://www.cienciaedados.com/cientista-de-dados-x-engenheiro-de-dados/
