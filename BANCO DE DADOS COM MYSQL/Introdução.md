# INTRODUÇÃO

## Já parou pra pensar onde todos os dados que estão no seu celular, e no seu computador estão armazenados?

## Aqui você vai encontrar um conteúdo muito especial sobre a origem dos bancos de dados.

## Vamo lá?



## Década de 50.

### Naquela época os primeiros computadores eram universitários e militares. Os dados eram guardados em fichas de papel, que eram preenchidas em pastas, que eram armazenadas em armários metálicos. Iguais aos filmes, lembra? Naquela época era a única forma. No começo da decade de 60, os americanos começaram a implementar armazenamentos digitais, mas era uma loucura. As fichas era armazenadas uma após a outra em um arquivo squencial. Fitas magnéticas, tem a mesma dinâmica, de rebobinação, e daí surgiu a inspiração para a criação das mesmas. Esses eram os arquivos sequenciais, gravados em sequência. Já viu um .PDF de um livro escaneado? A dinâmica era tipo assim.


### Após as fitas, chegaram os discos. Disquetes e HDs. O armazenamento passou a ser direto, e não sequencial. Haviam índices, chaves identificadoras de registros. Algo muito parecido com o que temos hoje em dia, mas eram índices, e não palavras chaves que possibilitaram o acesso aos arquivos. Arquivos de acesso direto. Ainda na década de 60, o departamento de defesa americano tinha uma tarefa de armazenar dados de forma mais segura e inteligente, e no CODASYL (consultar rodapé deste arquivo) algo começou a surgir.
 


Fichas são armazenadas em - Pastas que são armazenadas em - Armários de Arquivo

Registros são armazenadas em - Tabelas que são armazenadas em - Arquivos com a extensão .SQL 

Arquivos armazenam Tabelas que armazenam registros



Base de dados
Sistema gerenciador (SGBD - DMS)
Linguagem de exploração
Programas adicionais


A IBM, empresa de tecnologia americana vanguardista, que criou o computador pessoal (não foi a Apple nem a Microsoft), criou o conceito de dados hierárquicos. De forma simples, mas hierarquicamente. Foi criado o modelo hierárquico. E em seguida o modelo de rede. Mas ambos não facilitavam o relacionamento direto. Década de 70, e Edgar codd foi o primeiro a sugerir o modelo relacional, e é esse que nós utizaremos. Modelos orientados a objetos são mais atuais do que esse. Mas pra facilitar o nosso entendimento, vamos começar do modelo relacional A partir de um dado armazenado, eu consigo navegar por esses dados.

Structured English Query Language

(SEQUEL)

com o tempo esse English saiu da sigla, e hoje somente chamamos de SQL.

UMA QUERY É UMA SOLICITAÇÃO, OU UMA RESPOSTA.

O SQL é como iremos criar bancos de dados, acessar e manipular bancos de dados.


Or órgãos padronizadores ANSI e ISO começaram a padronizar banco de 

Oracle  é um exemplo de uma solução paga 


São exemplos de soluções pagas

PostgresSQL
Maria DB (um fork do MySQL, criados pelos mesmos Programadores)
MySQL 

São soluções gratuitas. 

MySQL é a que usaremos nesse curso.

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


## Curiosidade

### CODASYL foi um evento nos anos 60-70 entre empresas e os militares, para tratar de soluções tecnológicas. Lá nasceu o Cobol, linguagem antiga e verbosa, mas extremamente firme, concisa e eficiente. Muitas empresas ainda hoje em dia utilizam Cobol, e geralmente programadores de Cobol ganham bem, pois são recurso raro, escasso. Valioso. Maaaas, o foco de vocês é JAVASCRIPT e seus coleguinhas. 

# Sucesso, pessoal! 

#### #genBR
