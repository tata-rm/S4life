Banco de dados:

create database s4life;

use s4life;
 
create table contato(
	id int primary key auto_increment,
	nome varchar(255),
    email varchar(255),
    mensagem varchar(255)
);
 
select * from contato;