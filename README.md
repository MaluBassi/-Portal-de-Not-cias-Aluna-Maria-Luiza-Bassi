Portal de Notícias PBE
Maria Luiza Bassi - 31º
Este projeto é um Portal de Notícias Dinâmico desenvolvido com Node.js e Express. 
A aplicação consome dados em tempo real da NewsAPI utilizando Axios, transformando um layout estático em uma interface funcional. 
O sistema utiliza a template engine EJS para renderizar as notícias diretamente no servidor, garantindo que o conteúdo seja atualizado automaticamente conforme a fonte de dados externa.
## 🚀 Como rodar o projeto

1.  **Instale as dependências:**
    Abra o terminal na pasta do projeto e execute:
    ```bash
    npm install
    ```

2.  **Configure a API Key:**
    Como as chaves de segurança não são enviadas para o GitHub, você precisa criar um arquivo chamado `.env` na raiz do projeto e adicionar o seguinte conteúdo:
    ```env
    API_KEY=sua_chave_da_newsapi_aqui
    PORT=3000
    ```

3.  **Inicie o servidor:**
    No terminal, rode o comando:
    ```bash
    node app.js
    ```

4.  **Acesse:**
    Abra seu navegador em: [http://localhost:3000](http://localhost:3000)

    ## 🛠️ Tecnologias Usadas

* **Node.js:** Ambiente de execução JavaScript no servidor.
* **Express:** Framework para gerenciar rotas e o servidor.
* **EJS (Embedded JavaScript):** Motor de visualização para renderizar páginas HTML com dados dinâmicos.
* **Axios:** Biblioteca para fazer requisições HTTP (consumir a API de notícias).
* **Dotenv:** Gerenciamento de variáveis de ambiente (segurança da API Key).
* **CSS3:** Estilização responsiva utilizando CSS Grid e Flexbox.

## 📂 Estrutura do Projeto

A organização de pastas segue o padrão MVC (Model-View-Controller) simplificado:
portal-backend/ ├── 📁 public/ # Arquivos estáticos (acessíveis publicamente) │ ├── 📂 css/ # Folhas de estilo (style.css) │ └── 📂 img/ # Imagens do layout (ex: imagem padrão) ├── 📁 views/ # Templates HTML/EJS (Front-end dinâmico) │ └── 📄 index.ejs # Página principal com lógica de loop ├── 📄 .env # Variáveis de ambiente (Armazena a API Key - Não enviado ao GitHub) ├── 📄 .gitignore # Define arquivos ignorados pelo Git (node_modules, .env) ├── 📄 app.js # Arquivo principal (Configuração do servidor e rotas) └── 📄 package.json # Gerenciador de dependências do projeto
