****************************************INSTRUÇÕES FRONT-END*************************************************************************

Desafio 🚀

Este projeto foi desenvolvido com as seguintes tecnologias:

.NET 8.0 (backend/API)

Angular 20.3 (frontend)

SQL Server (banco de dados)

Entity Framework (ORM)

📌 Configuração do Projeto
API

A API está configurada para rodar em:

http://localhost:5000


Se estiver rodando em outra porta, lembre-se de alterar a URL no projeto Angular dentro do arquivo env.ts.

Dependências

Antes de rodar o projeto Angular, instale as dependências:

npm install

🧩 Arquitetura e Padrões

Aplicação dos princípios S.O.L.I.D

Boas práticas de Clean Code

Separação de funcionalidades em camadas, models, arquivos reutilizaveis e pastas de componentes(Cujo simbolizam as telas), garantindo organização, manutenção e evolução do código

▶️ Executar o projeto use: 
npm start

📂 Estrutura de Telas

As telas do sistema estão disponíveis na pasta:

/Images-Telas

📄 Documentação

O enunciado do desafio está disponível em:

/Desafio.pdf



****************************************INSTRUÇÕES BACK-END*************************************************************************



Desafio 🚀

Este projeto foi desenvolvido com .NET 8.0, Angular 20.3 e SQL Server, utilizando Entity Framework como ORM.

📌 Configuração do Projeto

Banco de Dados

Altere as configurações de conexão no arquivo appsettings.json e no docker-compose.yml de acordo com o seu ambiente de banco de dados e Docker.

Arquivo create-database.sql presente em Desafio/init-db/create-database.sql é utilizado para auxiliar na criação do banco de dados e usuario, verifique a necessidade do mesmo.

Migrações

Caso necessário, execute os comandos de migration antes de rodar o projeto.

🧩 Arquitetura e Padrões

Utilização dos princípios S.O.L.I.D, MVC e Clean Code

Separação das funcionalidades em camadas e pastas para melhor organização, manutenção e evolução (services, controller, models, mappings, repositorios, arquivos compartilhados...)

Conteinerização com Dockerfile e docker-compose

🧪 Testes

Os testes unitários estão localizados no projeto, em Desafio.Tests, incluindo:

Desafio.Tests/ControllersTeste/TituloControllerTeste.cs

▶️ Como rodar o projeto (tenha instalado o docker na maquina): 
docker-compose up -d --build

📂 Estrutura de Telas

As telas do sistema preenchidas estão disponíveis em:

Desafio/Desafio/Images-Telas/

Desafio esta em anexo em:

Desafio/Desafio/Desafio.pdf
