# Projeto_OnlineShopers

## Projeto MongoDB - Ingestão de Dados

Este projeto consiste na ingestão de dados do dataset "Online Shoppers" para uma base de dados MongoDB, utilizando Docker e Python.

O objetivo é aplicar um pipeline simples com:
- limpeza de dados
- utilização de Docker para o serviço MongoDB
- ingestão CSV → MongoDB
- operações CRUD (insert, select, update, delete)


### Passos feitos durante o projeto

- Criação do repositório no GitHub
- Limpeza do dataset original (identificação de inconsistências nas colunas)
- Conversão de colunas para tipos numéricos quando necessário
- Tratamento de valores em falta (missing values) usando moda e média
- Remoção de registos duplicados
- Exportação do dataset limpo para um novo ficheiro CSV
- Criação de classes para gestão da base de dados (MongoDatabase e MongoExecutor)
- Criação do ambiente MongoDB com Docker Compose
- Ligação à base de dados com PyMongo
- Implementação da ingestão de dados (CSV → MongoDB)
- Implementação e testes de operações CRUD (insert, select, update, delete)