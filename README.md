# Desafio-DIO-M5
Objetivo:  Criar o diagrama dimensional – Star Schema – com base no diagrama relacional disponibilizado. E assim montar o esquema em estrela com o foco na análise dos dados dos professores. Sendo assim, a tabela fato deve refletir diversos dados sobre professor, cursos ministrados, departamento ao qual faz parte.

Através da aplicação MySQL Workbench eu realizei a construção de um banco de dados próprio para o desafio, utilizando o comando CREATE DATABASE, logo após criei as tabelas utilizando o comando CREATE TABLE IF NOT EXISTS, e para preencher as tabelas com dados fictícios utilizei o comando INSERT INTO nome_tabela VALUES(). 
Comandos utilizados para correção de erros durante o desafio: 
1. ALTER TABLE nome_tabela MODIFY nome_coluna (Alteração de tamanho usado);
2. DROP TABLE (Exclusão de tabelas erradas);
3. SELECT * FROM (Visualização das tabelas).

Diagrama relacional disponibilizado:

![Img Modelo](https://github.com/user-attachments/assets/57973d5e-ed36-4304-b380-5ddcdbef90c6)

