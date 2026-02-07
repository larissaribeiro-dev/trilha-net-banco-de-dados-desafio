# 🎬 Banco de Dados Filmes - Consultas SQL e Modelagem

Este projeto foi desenvolvido como parte do módulo de Banco de Dados da trilha .NET da **DIO**. O objetivo principal foi consolidar conhecimentos em **SQL Server**, aplicando consultas complexas, junções (Joins), agrupamentos e filtros avançados.

## 🎯 O Desafio
O cenário consiste em um sistema de um site de filmes. O desafio exigiu a criação de 12 scripts SQL para extrair métricas e relatórios específicos baseados em um modelo de dados relacional.



## 🧠 Conceitos e Comandos SQL Aplicados
Durante a resolução das 12 consultas, foram aplicados conceitos essenciais de engenharia de dados:
* **Consultas Básicas:** Seleção e projeção de dados (`SELECT`, `WHERE`).
* **Ordenação e Filtros:** Uso de `ORDER BY`, `ASC/DESC` e operadores lógicos.
* **Agrupamento e Agregação:** Uso de `GROUP BY` e `COUNT` para análise estatística de dados por ano.
* **Relacionamentos (Joins):** Implementação de `INNER JOIN` para conectar tabelas de muitos para muitos (*Many-to-Many*), como Filmes, Gêneros e Atores.

## 🛠️ Tecnologias Utilizadas
* **SGBD:** SQL Server (ou compatível)
* **Linguagem:** T-SQL (Transact-SQL)
* **Ferramenta de Gerenciamento:** SQL Server Management Studio (SSMS)

## 📊 Estrutura das Consultas Realizadas
O repositório contém as soluções para extração de:
1. Listagem cronológica de filmes.
2. Filtros de duração específica (Intervalos entre 100 e 150 min).
3. Contagem de lançamentos por ano.
4. Relatórios de elenco e papéis desempenhados por atores.
5. Mapeamento de gêneros por título.

## 🚀 Como Executar
### 1. Pré-requisitos
Você precisará de um gerenciador de banco de dados compatível com **SQL Server**, como:
* [SQL Server Management Studio (SSMS)](https://learn.microsoft.com/pt-br/sql/ssms/download-sql-server-management-studio-ssms)

* Ou um compilador online que suporte T-SQL (como o [OneCompiler](https://onecompiler.com/sqlserver)).

### 2. Clonar o Repositório
Abra o terminal e execute o comando abaixo para baixar os arquivos:
```bash
git clone https://github.com/SEU_USUARIO/trilha-net-banco-de-dados-desafio.git
```
### 3. Preparação do Banco de Dados
1. Abra o arquivo Script Filmes.sql no seu editor de SQL.  
2. Execute o script completo (pressione F5 ou clique em Executar).  

### 3. Executando as Consultas (Desafio)  
As soluções para as 12 perguntas do desafio estão localizadas ao final do arquivo ```Script Filmes.sql.```

Para visualizar o resultado de uma consulta específica:

1. Selecione com o mouse o bloco de código da consulta desejada (Ex: Consulta 12).  
2. Clique em Executar.  
3. O resultado aparecerá na aba de resultados logo abaixo do editor.

---
**Destaque Técnico:** Este projeto demonstra minha capacidade de navegar em esquemas relacionais e transformar requisitos de negócio em queries eficientes.
