📌 BJJ Connect
👨‍💻 Integrantes / Matrículas

Guilherme Ferreira - 22402810

João Lucas - 22302450

Tiago Henrique - 22302522

Victor Marçal - 22301377

Vitor Vogel - 22302212


🚀 Funcionalidades

O sistema BJJ Connect possui as seguintes funcionalidades principais:


1 Cadastro de usuário/atleta

Cadastro de atleta com dados pessoais

Validação de senha e CPF

Login automático após cadastro


2 Cadastro de colaborador

Cadastro com CPF e telefone

Validação de senha e CPF

Login automático após cadastro


3 Login

Login para atleta e colaborador

Redirecionamento conforme tipo de usuário


4 Logout

Botão de sair em todas as páginas

Limpa dados do usuário e retorna ao login

5 Divulgação de campeonatos

Formulário para colaborador divulgar campeonatos

Salva no banco: nome, local, data, premiação, descrição, imagem, colaborador_id

Mensagem de sucesso após envio

6 Divulgação de arenas

Formulário para colaborador divulgar arenas com modalidade

Salva no banco: nome, endereço, cidade/estado, descrição, modalidade, colaborador_id

Mensagem de sucesso após envio

7 Listagem de campeonatos

Exibe campeonatos cadastrados com layout padronizado

Botão "Fazer inscrição" disponível

8 Inscrição em campeonatos

Modal de confirmação de inscrição

Inscrição automática com dados do usuário logado

Salva no banco: usuario_id, campeonato_id

Mensagem de sucesso após inscrição

9 Painel do colaborador

Exibe campeonatos divulgados pelo colaborador logado

Mostra quantidade de inscritos e informações dos atletas

10 Listagem de arenas

Exibe arenas cadastradas no banco

Organizadas por modalidade

11 Visualização dos dados do usuário

Página "Minha Conta" para atletas (nome, email, CPF, campeonatos inscritos)

Página "Meus Dados" para colaborador (ID, nome, email, telefone, tipo)

Página "Meus Dados Participante" para atletas

12 Envio de mensagens para organização

Formulário de contato no site

Salva mensagem no banco (mensagens_site)

Mensagem de sucesso após envio

13 Avaliação do site

Modal de avaliação com estrelas e comentário

Salva avaliação no banco (avaliacoes_site)

Mensagem de sucesso após envio

14 Menu lateral dinâmico

Exibe nome do usuário logado e botão de logout

Links exclusivos para colaborador ou atleta



📂 Estrutura de Diretórios

BJJ-Connect/
├── backend/                # Código do servidor (API, rotas, banco de dados)
│   ├── controllers/        # Lógica de controle
│   ├── models/             # Modelos e entidades do banco
│   ├── routes/             # Rotas da API
│   ├── config/             # Configurações (banco, autenticação, etc.)
│   └── server.js           # Arquivo principal do backend
│
├── frontend/               # Aplicação cliente (interface do usuário)
│   ├── public/             # Arquivos estáticos
│   ├── src/
│   │   ├── components/     # Componentes reutilizáveis
│   │   ├── pages/          # Páginas do sistema
│   │   ├── services/       # Comunicação com API
│   │   └── App.js          # Componente principal
│   └── package.json        # Dependências do frontend
│
├── database/               # Scripts do banco de dados
│   └── schema.sql
│
├── README.md               # Documentação do projeto
└── .gitignore              # Arquivos ignorados no Git



⚙️ Como Executar o Projeto
1. Pré-requisitos

Node.js (versão recomendada LTS)

NPM ou Yarn

Banco de dados MySQL ou PostgreSQL



2. InstalaçãoClone o repositório
git clone https://github.com/usuario/repositorio.git

# Acesse a pasta do projeto
cd BJJ-Connect

# Backend - instale as dependências
cd backend
npm install

# Frontend - instale as dependências
cd ../frontend
npm install


3. Execução

# Iniciar o backend
cd backend
npm start

# Iniciar o frontend
cd ../frontend
npm start


4. Acesso

    URL local: http://localhost:3000

    Usuário padrão: admin

    Senha padrão: admin123


📌 Observações

    Todas as funcionalidades listadas estão implementadas e funcionando.

    Melhorias futuras podem incluir:

        Integração com sistemas de pagamento online para inscrições.

        Painel administrativo avançado para gestão de eventos e arenas.

        Notificações em tempo real para atletas e colaboradores.
