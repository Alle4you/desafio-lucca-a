# Notas do Laboratorio

Este laboratorio e para aprender, passo a passo, como criar uma aplicacao simples de busca de filmes usando ajuda de IA.

A ideia nao e fazer tudo rapido. A ideia e entender cada parte.

## O que vamos construir

Vamos criar uma aplicacao para pesquisar filmes.

Ela vai usar uma base de dados do TMDB/Kaggle com informacoes sobre filmes.

No comeco, a busca pode ser bem simples:

- procurar filme pelo nome;
- mostrar o titulo;
- mostrar o ano;
- mostrar a nota;
- mostrar a sinopse.

## O que voce vai aprender

Durante o laboratorio, voce vai praticar:

- organizar arquivos de um projeto;
- usar Git para salvar seu progresso;
- usar GitHub para guardar o projeto online;
- ler dados de um arquivo CSV;
- criar um banco SQLite;
- fazer buscas simples no banco;
- criar uma tela web simples;
- usar IA para ajudar no desenvolvimento.

## Fase 0: clonar o projeto e preparar o ambiente

Nesta fase, o objetivo e baixar o projeto base e preparar o ambiente antes de comecar a codar.

O repositorio inicial ja vem com os arquivos do laboratorio.

Passos importantes:

- confirmar que o Git esta instalado;
- clonar o repositorio informado pelo professor;
- entrar na pasta do projeto;
- abrir o projeto no editor de codigo;
- ler o `README.md`;
- ler este arquivo `notas.md`;
- conferir se os arquivos do dataset estao na pasta do projeto;
- escolher qual IA sera usada como apoio: Codex, ChatGPT, Claude ou outra;
- se for usar Codex, iniciar uma sessao na pasta do projeto e usar `/init`;
- se for usar outra IA, pedir para ela ler o `README.md` e o `notas.md` antes de sugerir codigo;
- combinar uma regra simples: a IA deve explicar antes de alterar partes importantes;
- fazer commits apenas das mudancas feitas pelo aluno durante o laboratorio.

Exemplo:

```bash
git clone LINK_DO_REPOSITORIO
cd NOME_DA_PASTA_DO_PROJETO
```

Exemplo de pedido para a IA:

```txt
Leia o README.md e o notas.md deste projeto.
Antes de criar codigo, me explique o objetivo do laboratorio e proponha os proximos passos de forma simples.
Use o conceito KISS e evite complexidade desnecessaria.
```

Observacao: no Codex, `/init` e um comando usado dentro da conversa com a IA. Ele ajuda a IA a analisar o projeto e criar instrucoes iniciais para trabalhar naquele repositorio.

Voce vai aprender a:

- clonar um repositorio existente;
- abrir um projeto local no editor;
- entender a estrutura inicial de um projeto;
- usar README e notas como guia de trabalho;
- usar IA como apoio sem copiar codigo sem entender;
- continuar o desenvolvimento a partir de um projeto base;
- criar commits para registrar as suas proprias mudancas.


## Fase 1: dados e banco

Nesta fase, o objetivo e preparar os dados dos filmes.

descompact o arquivo zip, deve ficar apenas dois arquivos. CSV.
Crie o banco SQLite e import, entenda o conceito de tabelas de banco. 
quando o sqlite estiver populado ou seja com dados no banco, peça a AI listar as colunas diponiveis. e quantidade de linhas.

Voce vai aprender a:

- entender o que existe dentro de um arquivo CSV;
- criar um banco SQLite;
- importar os filmes para o banco;
- fazer uma busca simples pelo terminal.

No final desta fase, voce deve conseguir pesquisar um filme usando os dados salvos no banco.

## Fase 2: aplicacao web

Nesta fase, o objetivo e criar uma tela para pesquisar filmes, porem deve ser levado em consideração passos futuros. como publicação no vercel ou railway. definia isso antes de começar a codar.
Aqui entenda o conceito de arquitetura. 
pergunte a AI oque é conceito KISS "keep it simple stupid" 
defina a stack a ser usada entre 3 opção python, NEXTJS, vite. tente ender o impacto desta escolha antes de iniciar o codigo. perceba que quanto mais abstração mais dificil manter. KISS KISS KISS

Depois de cada parte importante funcionando, faca um commit para manter controle do codigo.

Um jeito simples de escrever commits e usar um padrao chamado Conventional Commits:

- `feat`: quando voce cria uma funcionalidade nova.
  Exemplo: `feat: adiciona tela de busca de filmes`
- `fix`: quando voce corrige um erro.
  Exemplo: `fix: corrige busca por titulo vazio`
- `docs`: quando voce altera apenas textos ou documentacao.
  Exemplo: `docs: explica escolha da stack`
- `chore`: quando voce faz ajustes de organizacao, configuracao ou manutencao.
  Exemplo: `chore: organiza arquivos iniciais do projeto`

Nao precisa decorar tudo agora. O importante e o commit explicar, em poucas palavras, o que mudou.

Voce vai aprender a:

- entender o que e arquitetura de uma aplicacao simples;
- comparar Python, Next.js e Vite antes de escolher a stack;
- aplicar o conceito KISS para evitar complexidade desnecessaria;
- criar uma tela web simples para busca de filmes;
- conectar a tela com os dados dos filmes;
- adicionar um campo de busca;
- mostrar os filmes encontrados de forma organizada;
- testar a aplicacao no navegador;
- pensar nos impactos da escolha da stack para publicacao no Vercel ou Railway.

No final desta fase, voce deve conseguir abrir a aplicacao e pesquisar filmes pela tela.

## Como usar IA neste laboratorio

Voce pode pedir ajuda para ferramentas como Codex, ChatGPT ou Claude.

Mas existe uma regra importante:


Sempre que a IA criar algo, pergunte:

```txt
Explique esse codigo de forma simples.
```

Ou:

```txt
Me mostre o que cada parte faz.
```

## Regra de trabalho

Para cada etapa:

1. Entenda o objetivo.
2. Peca ajuda para a IA.
3. Leia o codigo.
4. Teste.
5. Salve o progresso no Git.

O mais importante e aprender com calma.
