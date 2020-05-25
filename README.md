####Backend - (nodejs)

- **`POST /repositories`**: A rota recebe `title`, `url` e `techs` dentro do corpo da requisição, sendo a URL o link para o github desse repositório.

- **`GET /repositories`**: Rota que lista todos os repositórios;

- **`PUT /repositories/:id`**: Rota que altera apenas o `título`, a `url` e as `techs` do repositório que possua o `id` igual ao `id` presente nos parâmetros da rota;

- **`DELETE /repositories/:id`**: Rota que deleta o repositório com o `id` presente nos parâmetros da rota;

- **`POST /repositories/:id/like`**: Rota que aumenta o número de likes do repositório específico escolhido através do `id` presente nos parâmetros da rota.

####Frontend - (reactjs)

- **`Listar os repositórios da sua API`**: Lista os repositórios com o campo **title** de todos os repositórios que estão cadastrados na API.

- **`Adicionar um repositório a sua API`**: Adiciona um novo item na sua API através de um botão com o texto **Adicionar** e, após a criação, é exibido em tela.

- **`Remover um repositório da sua API`**: Para cada item da lista, possui um botão com o texto **Remover** que, ao clicar, irá remover o repositório da lista.

####Mobile - (react-native)

- **`Listar os repositórios da sua API`**: Lista de todos os repositórios que estão cadastrados na API com os campos **title**, **techs** e número de curtidas.

- **`Curtir um repositório listado da API`**: Capaz de curtir um item na API através do botão **Curtir** que atualiza o número de likes do repositório.



