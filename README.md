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
