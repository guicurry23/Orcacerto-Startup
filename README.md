OrçaCerto-Startup
Sobre o Projeto
OrçaCerto é um aplicativo de planejamento financeiro pessoal que ajuda os usuários a controlar seus gastos, definir metas e gerenciar orçamentos de forma eficaz. Focado em facilitar o entendimento e o uso de boas práticas financeiras, o OrçaCerto é ideal para jovens que buscam construir um futuro financeiro mais sólido.

Funcionalidades
Controle de Gastos: Adicione e categorize suas despesas, visualizando o total de gastos acumulados.
Planejamento Orçamentário: Defina um orçamento mensal e acompanhe o saldo restante.
Cadastro de Usuários: Crie uma conta para gerenciar seu perfil e dados financeiros.
Conexão com Instagram: Faça login e se conecte ao aplicativo via Instagram.
Notícias Financeiras: Fique atualizado com as últimas notícias do mundo financeiro.
Explicações sobre Finanças: Saiba mais sobre a importância da educação financeira com conteúdos explicativos.
Tecnologias Utilizadas
Frontend:

HTML5
CSS3
Bootstrap 4
JavaScript
Backend:

Node.js
Express.js
Banco de Dados:

MongoDB
Autenticação:

OAuth 2.0 via Instagram
Como Executar o Projeto
Clone o repositório:

bash
Copiar código
git clone https://github.com/guicurry23/Orcacerto-Startup.git
Instale as dependências:

bash
Copiar código
cd Orcacerto-Startup
npm install
Configure as variáveis de ambiente:
Crie um arquivo .env na raiz do projeto e adicione as seguintes variáveis:

env
Copiar código
INSTAGRAM_CLIENT_ID=seu_client_id
INSTAGRAM_CLIENT_SECRET=seu_client_secret
INSTAGRAM_REDIRECT_URI=http://localhost:3000/auth/instagram/callback
Inicie o servidor:

bash
Copiar código
npm start
Acesse a aplicação no navegador:

arduino
Copiar código
http://localhost:3000
Estrutura do Projeto
bash
Copiar código
OrcaCerto-Startup/
│
├── public/                 # Arquivos estáticos (HTML, CSS, JS)
├── src/                    # Código fonte do backend (Node.js)
│   ├── controllers/        # Controladores de rotas
│   ├── models/             # Modelos de banco de dados
│   ├── routes/             # Definições de rotas
│   └── views/              # Views e templates
├── .env                    # Variáveis de ambiente
├── README.md               # Documentação do projeto
└── package.json            # Configurações do Node.js e dependências
Contribuindo
Contribuições são bem-vindas! Se você deseja melhorar este projeto, sinta-se à vontade para abrir um pull request ou relatar problemas.

Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

Contato
Instagram: @orçacertooficial
