# JGM Home Page

## Descrição

O JGM Home Page é uma aplicação web que apresenta uma página inicial para um site de loja de produtos, focada em videogames e acessórios que foi feita para um exercíccio do meu curso de React. A página inclui uma seção de cabeçalho, uma seção sobre a empresa, uma seção de produtos e um rodapé.

## Estrutura do Projeto

- **src/components**: Contém os componentes principais da aplicação.
  - **about**: Contém o componente `Abuot` (provavelmente um erro de digitação, deve ser `About`).
  - **button**: Contém componentes de botão reutilizáveis.
  - **cardProduct**: Contém o componente `Products` que exibe os produtos.
  - **footer**: Contém o componente `Footer`.
  - **header**: Contém o componente `Header`.

- **db.json**: Arquivo de dados simulado para produtos. Utilizado com uma ferramenta como json-server para servir como uma API fake.

- **App.jsx**: O componente principal da aplicação onde os componentes são renderizados.

- **index.css**: Arquivo de estilos CSS globais.

- **main.jsx**: O ponto de entrada da aplicação React.

## Instalação

Para instalar e executar o projeto localmente, siga os passos abaixo:

1. Clone o repositório:
    ```bash
    git clone https://github.com/jotaMch/m15_exercicio.git
    cd <DIRETORIO_DO_PROJETO>
    ```

2. Instale as dependências:
    ```bash
    npm install
    ```

3. Inicie o servidor de desenvolvimento:
    ```bash
    npm start
    ```

4. Se você ainda não tiver uma API simulada, instale e inicie o json-server para servir o arquivo `db.json`:
    ```bash
    npm install -g json-server
    json-server --watch db.json --port 3000
    ```

## Uso

- **Header**: Exibe o cabeçalho da página com opções de navegação e botões de ação.
- **Abuot**: Seção que descreve a empresa e exibe uma imagem representativa.
- **Products**: Seção que lista produtos obtidos da API fake configurada no `db.json`.
- **Footer**: Exibe o rodapé com uma mensagem de direitos autorais.

## Estrutura dos Componentes

### `Page.jsx`

Componente principal que organiza a estrutura da página incluindo `Header`, `Abuot`, `Products`, e `Footer`.

### `Abuot.jsx`

Componente que exibe uma descrição sobre a empresa e uma imagem ilustrativa.

### `Products.jsx`

Componente que realiza uma chamada à API para buscar produtos e exibi-los em cards.

### `Footer.jsx`

Componente que exibe informações de rodapé.

### `Header.jsx`

Componente que exibe o cabeçalho da página com opções de navegação e botões de ação.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.


## Contato

Se você tiver alguma dúvida, sinta-se à vontade para entrar em contato pelo e-mail: [seuemail@example.com](mailto:seuemail@example.com).
