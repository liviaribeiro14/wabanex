# Wabanex

API em GraphQL em Elixir - Para aprendizado.



## Criação do projeto em Elixir
Para criar o projeto do zero sem HTML e sem webpack
  `mix phx.new wabanex --no-html --no-webpack`

Para testar o banco de dados 
* Em `config/dev.exs` configurar conexão com o Postgres
* Executar `mix ecto.setup`

## Iniciar o projeto 
Iniciar um projeto Phoenix:

  * Instalar as dependências com `mix deps.get`
  * Criar e migrar o banco de dados com `mix ecto.setup`
  * Iniciar endpoint Phoenix com `mix phx.server`

Após, acesse pelo navegador [`localhost:4000`](http://localhost:4000). Para ver o dashboard [`localhost:4000/dashboard/home`]

Pronto para rodar em produção?  [Cheque os guias](https://hexdocs.pm/phoenix/deployment.html).

## Aprenda mais

  * Site oficial: https://www.phoenixframework.org/
  * Guias: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Fontes: https://github.com/phoenixframework/phoenix
