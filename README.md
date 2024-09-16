# API Hello World

A **API Hello World** é uma aplicação base desenvolvida em Ruby, com o objetivo de fornecer um ponto de partida simples e eficiente para a criação de APIs. Utilizando o framework Sinatra, este projeto demonstra uma estrutura básica de resposta HTTP, ideal para desenvolvedores que desejam iniciar seus próprios projetos com Ruby e buscar uma base sólida e escalável.

## Tecnologias Utilizadas

- **Ruby:** Linguagem de programação dinâmica e open-source.
- **Sinatra:** Framework minimalista para desenvolvimento de aplicações web.
- **Rackup:** Utilitário para gerenciar o ambiente de execução do Sinatra.

## Funcionalidades

- **Personalizável**: Fácil adaptação para expandir a lógica de negócios e adicionar funcionalidades mais complexas.
- **Estrutura Simples:** Código clean e de fácil compreensão para iniciantes ou profissionais.
- **Resposta Básica:** Ao acessar a API, a resposta "Hello World" é retornada.

## Como Executar

1. Instale as dependências necessárias:

```bash
gem install sinatra rackup
```

2. Crie o arquivo `main.rb` com o seguinte conteúdo:

```ruby
require 'sinatra';

get '/' do;
  'Hello World'
end;
```

3. Execute o servidor:

```bash
ruby main.rb
```

4. Acesse a API em [http://localhost](http://localhost:4567).