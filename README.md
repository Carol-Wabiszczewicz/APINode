API CRUD Simples com Node.js, Express, Prisma e MongoDB

• Índice
• Visão Geral
• Funcionalidades
• Tecnologias Utilizadas
• Instalação
• Uso
• Endpoints da API
• Licença
• Visão Geral

Esta é uma API CRUD simples construída usando Node.js, Express, Prisma e MongoDB. A API permite criar, ler, atualizar e excluir dados de um banco de dados MongoDB.

• Funcionalidades
• Criar novos registros
• Ler registros existentes
• Atualizar registros
• Excluir registros

Tecnologias Utilizadas

• Node.js: Um ambiente de execução JavaScript baseado no motor V8 do Chrome.
• Express: Um framework web rápido, não opinativo e minimalista para Node.js.
• Prisma: Um ORM de próxima geração para Node.js e TypeScript.
•MongoDB: Um banco de dados de documentos, que armazena dados em documentos flexíveis semelhantes a JSON.

Instalação
Para rodar este projeto localmente, siga os seguintes passos:

Clone o repositório:
[git clone https://github.com/seu-usuario/seu-repo-nome.git](https://github.com/Carol-Wabiszczewicz/APINode.git)

Navegue até o diretório do projeto:
cd seu-repo-nome

Instale as dependências:
npm install

Configure as variáveis de ambiente:
Crie um arquivo .env na raiz do seu projeto e adicione as seguintes variáveis:
DATABASE_URL=DATABASE_URL="mongodb+srv://carolwabiszczewicz:Teste123$$@usersapi.sjgvh9r.mongodb.net/?retryWrites=true&w=majority&appName=UsersAPI"

Execute os comandos do Prisma:
npx prisma generate

Inicie o servidor:
npm start

Seu servidor agora deve estar rodando em http://localhost:3000.
