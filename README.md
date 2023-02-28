# Curso de PostegreSQL na Alura
## Índice
[Aula 01](https://github.com/Leticia-Souza94/Alura_PostgreSQL#aula-01)<br><br>
<br>
## Aula 01
### Criando uma tabela:

1) Criar um Banco de dados no PostgreSQL adicinando o comando CREATE DATABASE. Para esse curso,  foi utilizada a versão PostgreSQL 15.

'''

    CREATE DATABASE alura;

'''

2) Para verificar o Bancos de dados abertos podemos inserir contra-barra e a letra l:

'''

    \l
    
'''

3) Podemos excluir um Banco de dados inserindo o comando DROP DATABASE:

'''

    DROP DATABASE alura;

'''

4) Para criar uma tabela utilizamos o comando CREATE TABLE. No [site da Postgre](https://www.postgresql.org/docs/15/index.html), podemos buscar a lista de Data Types que podemos utilizar para caracteres numéricos (integer, real, serial, numeric), texto (varchar, char, text), boleanos (boolean), data e hora (date, time, timestamp), ente outros.

'''

    CREATE TABLE aluno(
          id SERIAL,
          nome VARCHAR(255),
          cpf CHAR(11),
          observação TEXT,
          idade INTEGER,
          dinheiro NUMERIC(10,2),
          altura REAL
          );

'''
<br>
<br>
<br>
<br>
