# Laboratório: Busca de Filmes

Este repositório será usado como laboratório para criar uma aplicação simples de busca de filmes.

A ideia é usar uma base do TMDb/Kaggle em CSV, importar os dados para um banco SQLite e construir uma interface para pesquisar filmes.

## Objetivo

O objetivo principal é praticar:

- organização de um projeto local
- uso de Git e GitHub
- leitura de arquivos CSV
- criação de um banco SQLite
- consultas simples em SQL
- criação de uma busca de filmes
- publicação inicial na Vercel
- uso de IA como apoio ao desenvolvimento

## Base de dados

A base usada vem do dataset:

**TMDB 5000 Movie Dataset**  
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

Arquivos esperados:

```txt
tmdb_5000_movies.csv
tmdb_5000_credits.csv
```

A primeira etapa pode usar apenas o arquivo de filmes. O arquivo de créditos pode ser usado depois para buscar por elenco ou equipe.

## Por que SQLite?

SQLite é simples, leve e não exige servidor separado. Ele é uma boa escolha para aprender os conceitos básicos de banco de dados antes de migrar para soluções como Supabase ou PostgreSQL.

## Ideia inicial

A primeira versão da aplicação deve permitir:

- importar os filmes do CSV para SQLite
- pesquisar filmes pelo título
- exibir uma lista com os resultados
- mostrar informações básicas como nome, ano, nota e sinopse

## Uso de IA

O aluno pode usar ferramentas como Codex, Claude ou ChatGPT para ajudar no desenvolvimento, mas deve revisar o código gerado, entender as mudanças e manter o projeto organizado.

## Próximo passo

Criar a estrutura inicial do projeto e o script de importação do CSV para o banco SQLite.
