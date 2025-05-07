/*comando para criar um banco de dados*/
CREATE DATABASE editora;

/*
comando para colocar o banco em uso
*/

USE autor;
CREATE TABLE autor(
id_autor INTEGER PRIMARY KEY AUTO_INCREMENT,
nome_autor varchar (100),
titulo varchar (100),
ano_publicacao int
);

INSERT INTO autor
VALUES(null,
"Ali Hazelwood",
"A Hipótese do Amor",
"2022"
);

INSERT INTO autor
VALUES(null,
"Sarah J. Mass",
"Trono de Vidro",
"2012",
"Cidade de Céu e Sopro",
"2022"
);

SELECT * FROM autor;

SELECT *FROM autor WHERE id_autor =1;

SELECT nome_autor
FROM autor WHERE autor =1;

SELECT nome_autor FROM autor WHERE nome_autor = "AliHazelwood";

SELECT COUNT(*) FROM cliente

