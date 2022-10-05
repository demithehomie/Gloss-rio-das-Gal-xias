
# 29/09/2022

# INTRODUÇÃO À BANCO DE DADOS COM MYSQL

## Já parou pra pensar onde todos os dados que estão no seu celular, e no seu computador estão armazenados?

## Aqui você vai encontrar um conteúdo muito especial sobre a origem dos bancos de dados.

## Vamo lá?



## Década de 50.

### Naquela época os primeiros computadores eram universitários e militares. Os dados eram guardados em fichas de papel, que eram preenchidas em pastas, que eram armazenadas em armários metálicos. Iguais aos filmes, lembra? Naquela época era a única forma. No começo da decade de 60, os americanos começaram a implementar armazenamentos digitais, mas era uma loucura. As fichas era armazenadas uma após a outra em um arquivo squencial. Fitas magnéticas, tem a mesma dinâmica, de rebobinação, e daí surgiu a inspiração para a criação das mesmas. Esses eram os arquivos sequenciais, gravados em sequência. Já viu um .PDF de um livro escaneado? A dinâmica era tipo assim.


### Após as fitas, chegaram os discos. Disquetes e HDs. O armazenamento passou a ser direto, e não sequencial. Haviam índices, chaves identificadoras de registros. Algo muito parecido com o que temos hoje em dia, mas eram índices, e não palavras chaves que possibilitaram o acesso aos arquivos. Arquivos de acesso direto. Ainda na década de 60, o departamento de defesa americano tinha uma tarefa de armazenar dados de forma mais segura e inteligente, e no CODASYL (consultar rodapé deste arquivo) algo começou a surgir.
 
### A IBM, empresa de tecnologia americana vanguardista, que criou o computador pessoal (não foi a Apple nem a Microsoft), criou o conceito de dados hierárquicos. De forma simples, mas hierarquicamente. Foi criado o modelo hierárquico. E em seguida o modelo de rede. Mas ambos não facilitavam o relacionamento direto. Década de 70, e Edgar codd foi o primeiro a sugerir o modelo relacional, e é esse que nós utizaremos. Modelos orientados a objetos são mais atuais do que esse. Mas pra facilitar o nosso entendimento, vamos começar do modelo relacional A partir de um dado armazenado, eu consigo navegar por esses dados.

## Analogias?

### Fichas são armazenadas em - Pastas que são armazenadas em - Armários de Arquivo

### Registros são armazenadas em - Tabelas que são armazenadas em - Arquivos com a extensão .SQL 

# Arquivos armazenam Tabelas que armazenam registros


# O que é MySQL? 

### SQL significa Structured English Query Language (SEQUEL), ou Linguagem estruturada de Query. Com o tempo esse English saiu da sigla, e hoje somente chamamos de SQL.

# UMA QUERY É UMA SOLICITAÇÃO, OU UMA RESPOSTA.

### O SQL é como iremos criar bancos de dados, acessar e manipular bancos de dados.

### Oracle é um exemplo de uma solução paga. MySQL é um exemplo de solução gratuita e é a que usaremos neste curso. 


## Pontos de atenção

### Um banco de dados relacional organiza dados em tabelas e estabelece relacionamentos entre eles. Os bancos de dados relacionais baseiam-se no Modelo Relacional, onde todos os dados são representados em termos de tuplas (linhas) e atributos (colunas), sendo agrupados em relacionamentos (tabelas), que também se relacionam com outras tabelas. 

### Uma chave primária é um identificador exclusivo que permite localizar uma linha dentro de uma tabela relacional, geralmente definida como ID integer ou, às vezes, com base em uma coluna existente.

### Uma chave estrangeira, por outro lado, consiste em uma referência a uma linha em outra tabela. Chaves estrangeiras costumam ser chaves primárias de outras tabelas, considerando que sempre precisam identificar uma linha exclusivamente.

### Um Modelo Entidade-Relacionamento é um diagrama utilizado para projetar e definir a estrutura de um banco de dados relacional. 

### Os objetivos do projeto de banco de dados relacional são:

### Eliminar redundância de dados: os dados não devem ser armazenados em mais de um local
### Garantir a integridade e precisão dos dados
### Os relacionamentos estabelecidos entre tabelas podem ser classificados entre os tipos a seguir:
###  1:1 - um para um
### 1:n - um para muitos
###  n:m - muitos para muitos
###  Embora os modelos relacionais existam há cerca de 50 anos, o aprendizado desses conceitos está fortemente vinculado à mentalidade de orientação ao futuro, pois ainda serão utilizados por muito tempo. 
###  A administração de bancos de dados e informações é uma competência essencial que qualquer desenvolvedor deve ter. O modelo relacional é um forte modelo mental, e sua compreensão altera a maneira como administramos e visualizamos os dados. A orientação ao detalhe é uma habilidade comportamental essencial para o aprendizado dessa competência.

## Alguns dos comandos mais importantes que utilizaremos com MySQL

### SELECT - extrai dados de um banco de dados
### UPDATE - atualiza dados em um banco de dados
### DELETE - deleta dados em um banco de dados
### INSERT INTO - insere  dados em um banco de dados
### CREATE DATABASE - cria um banco de dados
### ALTER DATABASE - modifica um banco de dados
### CREATE TABLE - cria uma nova tabela
### ALTER TABLE - modifica uma tabela
### DROP TABLE - deleta uma tabela
### CREATE INDEX - cria um indice (search key)
### DROP INDEX - deleta um indice

# Para relembrar!!! 
## Pontos de Atenção:
### A Linguagem de Consulta Estruturada (SQL) é uma linguagem de banco de dados padrão utilizada para criar, manter e recuperar bancos de dados relacionais.
### O MySQL é um poderoso sistema de código aberto cuja função é gerenciar bancos de dados relacionais.
### O MySQL Workbench é uma ferramenta utilizada para projetar e estabelecer conexão com bancos de dados baseados no mecanismo do MySQL.
### O modelo entidade-relacionamento (ER) representa uma forma de projetar bancos de dados graficamente.
### Os relacionamentos entre tabelas podem ser obrigatórios (linha contínua) ou opcionais (linha tracejada).
### Os bancos de dados do MySQL podem armazenar valores dos tipos a seguir:
### String (CHAR, VARCHAR, BINARY, BLOB, LONGTEXT)
### Numérico (BIT; BOOLEAN; INTEGER, FLOAT, DOUBLE)
### Data e hora (DATE; DATETIME, TIMESTAMP, TIME, YEAR)
### Declaração INSERT permite adicionar registros a um banco de dados SQL.
### Um schema é uma definição de banco de dados que consiste em um conjunto de TABLES e regras (restrições) para proteger a integridade dos dados Abordar DDL: Alter Table, Alter Collumn.

# Alerta de BSMs - Conexão com o mundo real

### Carlos desempenha a função de administrador de banco de dados em um banco e utiliza bancos de dados relacionais como ferramenta de trabalho. O departamento de TI solicita que Carlos aumente a redundância devido a uma nova lei que estabelece a obrigatoriedade de haver um advogado de segurança adicional nos bancos, visando garantir a proteção de dados dos clientes. 

## De que forma Carlos está adotando a orientação ao futuro quando opta por utilizar um banco de dados relacional?

### Carlos sabe que bases de dados relacionais são antigas, mas também muito seguras e com alta probabilidade de permanecerem no mercado por um longo período. As bases de dados relacionais protegem a integridade e viabilizam a condução de backups durante o processo migratório caso algum erro ocorra. Com a orientação ao futuro, Carlos é capaz de adquirir conhecimentos sobre novas tecnologias baseadas na nuvem que auxiliam sua equipe a atingir a qualidade dos padrões requeridos pelo banco.

## De que forma orientação ao detalhe pode ser útil?

### Estando atento aos detalhes, Carlos é capaz de avaliar rigorosamente o processo de migração e a estrutura do banco de dados. Uma pessoa orientada ao detalhe não admite um cenário suscetível a falhas, mas verifica e testa antes de realizar operações arriscadas!

# Para relembrar!!! 
## Pontos de Atenção:
### A maioria das bases de dados relacionais utiliza a definição de dados SQL e a linguagem de query de dados; esses sistemas implementam o que pode ser considerado uma aproximação de engenharia ao modelo relacional.
### O SQL baseia-se em instruções chamadas de queries. Uma query consiste em uma solicitação de dados ou informações de uma tabela de base de dados ou combinação de tabelas. As queries em SQL padrão que interagem com bases de dados relacionais são CREATE, SELECT, INSERT, UPDATE, DELETE e ALTER TABLE. 
### O SQL fornece a capacidade de filtrar, calcular, adicionar, agrupar e combinar queries. O SQL é capaz de executar matemática básica, funções de subtotais e transformações lógicas. Os analistas conseguem ordenar os resultados por data, nome ou qualquer coluna.
### As queries SELECT recuperam determinados registros de uma ou mais tabelas. Em uma query SELECT, o usuário pode escolher quais campos recuperar, de quais tabelas e quais filtros aplicar. 
### A cláusula WHERE, uma parte opcional das queries SELECT, filtra os dados recuperados, removendo as filas que não seguem as condições especificadas na cláusula.




## Curiosidade

### CODASYL foi um evento nos anos 60-70 entre empresas e os militares, para tratar de soluções tecnológicas. Lá nasceu o Cobol, linguagem antiga e verbosa, mas extremamente firme, concisa e eficiente. Muitas empresas ainda hoje em dia utilizam Cobol, e geralmente programadores de Cobol ganham bem, pois são recurso raro, escasso. Valioso. Maaaas, o foco de vocês é JAVASCRIPT e seus coleguinhas. 


# Sucesso, pessoal! 

#### #genBR
