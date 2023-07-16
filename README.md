cadastro de Usuarios.

Este é um projeto feito com Python e Django de um cadastro de usuários. Ele permite que os usuários se registrem, façam login e vejam seus dados.

Como usar
Para usar este projeto, você precisa ter Python e Django instalados no seu computador. Depois, siga estes passos:

Clone este repositório para a sua máquina local.
Navegue até a pasta do projeto e crie um ambiente virtual com o comando python -m venv venv.
Ative o ambiente virtual com o comando source venv/bin/activate (Linux) ou venv\Scripts\activate (Windows).
Instale as dependências do projeto com o comando pip install -r requirements.txt.
Execute as migrações do banco de dados com o comando python manage.py migrate.
Inicie o servidor de desenvolvimento com o comando python manage.py runserver.
Acesse a aplicação no seu navegador pelo endereço http://localhost:8000.

Funcionalidades
Este projeto tem as seguintes funcionalidades:

Registro de usuários: os usuários podem se cadastrar fornecendo um nome e idade.
Login de usuários: os usuários podem fazer login na aplicação usando seu email e senha.
Visualização de dados: os usuários podem ver seus dados cadastrados na página inicial após fazerem login.

Tecnologias
Este projeto usa as seguintes tecnologias:

Python: a linguagem de programação usada para desenvolver a lógica da aplicação.
Django: o framework web usado para criar a interface e a interação com o banco de dados.
Bootstrap: o framework CSS usado para estilizar a página web.
