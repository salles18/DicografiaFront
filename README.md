# Projeto de Gerenciamento de Discografia

Este projeto é uma aplicação web para gerenciar a discografia da dupla caipira Tião Carreiro e Pardinho. A aplicação é dividida em duas partes: uma API REST construída com Laravel e um front-end desenvolvido com React e Bootstrap.

## Tecnologias Utilizadas

- **Backend:** Laravel (PHP)
- **Frontend:** React.js
- **Estilização:** Bootstrap
- **Banco de Dados:** Mysql 

## Funcionalidades

1. **Ver Lista de Álbuns e Faixas**
   - Visualize todos os álbuns e suas respectivas faixas.

2. **Pesquisar Álbuns e Faixas**
   - Pesquise álbuns e faixas por nome.

3. **Adicionar um Novo Álbum**
   - Permite adicionar um novo álbum à discografia.

4. **Adicionar uma Nova Faixa em um Álbum**
   - Adicione uma faixa a um álbum existente.

5. **Excluir uma Faixa**
   - Remova uma faixa específica de um álbum.

6. **Excluir um Álbum**
   - Remova um álbum da discografia.

## Instalação

### Backend (Laravel)

1. Clone o repositório:

   ```sh
   git clone https://github.com/seu-usuario/discografia-backend.git
   cd discografia-backend
Instale as dependências:

``sh
Copiar código
composer install
Configure o banco de dados no arquivo .env:

``env
Copiar código
DB_CONNECTION=sqlite
DB_DATABASE=/caminho/para/seu/database.sqlite
Execute as migrations:

``sh
Copiar código
php artisan migrate
Inicie o servidor:

```sh
Copiar código
php artisan serve
Frontend (React)
Clone o repositório:

```sh
Copiar código
git clone https://github.com/seu-usuario/discografia-frontend.git
cd discografia-frontend
Instale as dependências:

```sh
Copiar código
npm install
Inicie o servidor de desenvolvimento:

```sh
Copiar código
npm start
Configuração de CORS
Certifique-se de que o CORS está configurado corretamente no backend para permitir solicitações do frontend. O Laravel já inclui um middleware para CORS. Verifique o arquivo config/cors.php para ajustar as configurações conforme necessário.

##Estrutura do Projeto
Backend
app/Http/Controllers: Controladores da API
database/migrations: Migrations do banco de dados
routes/api.php: Rotas da API
##Frontend
src/App.js: Componente principal da aplicação React
src/components: Componentes reutilizáveis
src/assets: Imagens e outros arquivos estáticos
Contribuição
Contribuições são bem-vindas! Se você tiver sugestões, correções ou melhorias, sinta-se à vontade para abrir um issue ou enviar um pull request.

##Licença
Este projeto está licenciado sob a MIT License.

Contato
Para qualquer dúvida ou sugestão, entre em contato:

Seu Nome - jv.salles2015@gmail.com
GitHub - Salles18
