# Comomandos SQL

### Criar database
```
create database NOME_DATABASE
```

### Definir a database de uso 
```
use NAME_DATABASE;
```

### Criar tabela de usuários 
```
create table users (
	id int not null auto_increment,
    nome varchar(120) not null,
    email varchar(120) not null,
    senha varchar (120) not null,
    dt_nascimento date,
    primary key(id)
);
```
### Insert Dados
```
INSERT INTO users(nome, email, senha, dt_nascimento)
VALUES ('Emily', 'Emily@gmail.com', 'secreta', '2004-08-01');
```

### Listar Dados da Tabela de users
```
elect* from users;
```

