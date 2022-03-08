# Banco de Dados

SQL = **S**tructured **Q**uery **L**anguage

>Linguagem de consulta, possível de dar comandos ao meio ambiente do banco de dados e o mesmo te retorna uma query, uma resposta a uma solicitação.

### Principios de uma solicitação feita ao BD<br>
#### DICA<br>
- **D**urabilidade: todo dado alterado deve permanecer dessa maneira até segunda ordem<br>
- **I**solamento: se 2 transações forem feitas ao mesmo tempo, elas não podem sofrer interferencia uma na outra<br>
- **C**onsistência: toda transação deve levar o bd a um estado de consistencia (como era antes)<br>
- **A**tomicidade: toda transação deve ser atomica, ou toda ela acontece ou nada dela acontece<br>
_______________________________

Bancos de dados são conjuntos de tabelas, e tabelas são conjuntos de registros, e registros são compostos por campos.

### Conceitos

Chave primária:  campo que não se repete, indicador único de um registro na tabela. Não pode existir duas tuplas (registro) com a mesma chave primária.

ex na vida real: matrícula e cpf

### Tipos primitivos:

Tem pra caralho.
exemplo:

        TinyInt, SmallInt, Int, BigInt
        Decimal, Float
        Date, DateTime, Time, Year
        Char, VarChar
        

### Comandos

Criando um banco de dados (com codificação de caracteres especiais e collation voltados ao utf8):

        create database cadastro
        default character set utf8
        default collate utf8_general_ci;


Criando uma tabela:

not null: não pode ser vazio

decimal(5,2): campo decimal com 5 espaços sendo 2 deles após a virgula. ex: 102,75

        create table pessoas(
            id int not null auto_increment,
            nome varchar(30) not null,
            nascimento date,
            sexo enum('M','F'),
            peso decimal(5,2),
            altura decimal(3,2),
            nacionalidade varchar(20) default 'Brasil'
            primary key (id)

        ) default charset = utf8;
ou
        
        create table `pessoas`(
            `id` int not null auto_increment,
            `nome` varchar(30) not null,
            `nascimento` date,
            `sexo` enum('M','F'),
            `peso` decimal(5,2),
            `altura` decimal(3,2),
            `nacionalidade` varchar(20) default 'Brasil'
            primary key (id)

        ) default charset = utf8;



Selecionar a tabela;
        
        use cadastro;


Mostrar a tabela

        describe pessoas;


    



