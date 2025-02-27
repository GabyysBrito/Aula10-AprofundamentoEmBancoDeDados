# 📌 Anotações de Banco de Dados

## 📚 Aprofundamento em Banco de dados parte 1 

<br> 

### 🔹 Tipos primitivos
---
- Os tipos primitivos no MySql definem o formato e a maneira como os dados são armazenados no banco de dados. 

- Eles garantem que as informações sejam organizadas.

    ### Tipos
    !['Tipos Primitivos'](imgs/tipoPrimitivos.png)

<br> 

### 🛠️ Principais Comandos DDL 
---

- São comandos usados para criar, modificar e excluir a estrutura do banco de dados, como tabelas e colunas

    - 📂 Comando para criar um Banco de dados
        > CREATE DATABASE nome_do_banco;

    - 📌 Comando para usar um Banco de Dados
        > USE nome_do_banco;

    - 🏗️ Comando para criar uma tabela 
        > CREATE TABLE nome_da_tabela(colunas);

    - 📋 Exibir tabelas do Banco de Dados
        > SHOW TABLE;

    - 🧐 Exibir estrutura de uma tabela 
        > DESC nome_da_tabela;

    - ❌ Excluir uma tabela
        > DROP TABLE nome_da_tabela;

    - 🗑️ Deletar dados de uma tabela `permanente`  
        > TRUNCATE TABLE nome_da_tabela;

<br> 

### 🔹 Principais Comandos DML
---

- São comandos responsáveis por inserir, atualizar, excluir e consultar dados dentro das tabelas.

    - ➕ Inserir Dados em uma tabela
        > INSERT INTO nome_da_tabela (coluna1, coluna2) VALUES (valor1, valor2)

    - 🔍 Selecionar todos os dados de uma tabela
        > SELECT * FROM 

    - 🗑️ Deletar dados de uma tabela 
        > TRUNCATE TABLE nome_da_tabela

    - ❌ Deletar uma informação específica 
        > DELETE FROM tabela WHERE id=1;

    - ✏️ Atualizar dados existentes na tabela 
        > UPDATE tabela SET idade = 30 WHERE id = 2;

<br> 

### 🔐 Constraints
---

- As constraints são regras aplicadas a colunas de uma tabela para garantir integridade, consistência, e confiabilidade dos dados.

✅ Servem para evitar erros e inconsistência nos dados.

✅ Ajudam a definir restrições como valores únicos, chaves primários e relações entre tabelas.

<br> 

!['Tipos de constraints'](imgs/constraints.png)

<br>

> id INT AUTO_INCREMENT PRIMARY KEY

> nome VARCHAR(50) NOT NULL