﻿# projetopinterest
# FakePinterest

FakePinterest é uma plataforma de rede social inspirada no Pinterest, onde os usuários podem compartilhar imagens, criar perfis e interagir com o conteúdo. O projeto foi desenvolvido como uma aplicação web utilizando **Python** com **Flask** e **HTML/CSS** para a interface do usuário.

## Funcionalidades

- **Cadastro de Usuário:** Usuários podem criar uma conta com e-mail, nome de usuário e senha.
- **Login e Logout:** Usuários podem realizar login em sua conta e fazer logout quando desejarem.
- **Página Inicial:** A página inicial exibe uma galeria de imagens postadas por outros usuários.
- **Perfil de Usuário:** Cada usuário tem um perfil próprio, onde pode visualizar suas imagens e editar informações pessoais.
- **Envio de Imagens:** Os usuários podem adicionar imagens ao seu perfil, as quais são exibidas na página inicial.

## Como Funciona

1. **Cadastro e Login:**
   - Usuários podem criar uma conta fornecendo um e-mail, nome de usuário e senha.
   - Após o cadastro, o usuário pode fazer login para acessar o conteúdo exclusivo de sua conta.
   - O sistema valida as credenciais e redireciona o usuário para sua página de perfil após o login bem-sucedido.

2. **Página de Galeria:**
   - A página inicial exibe uma galeria de imagens postadas pelos usuários.
   - Cada imagem está ligada ao perfil do usuário que a postou. Ao clicar na imagem, o usuário é redirecionado para o perfil do dono da foto.

3. **Perfil de Usuário:**
   - Cada usuário possui uma página de perfil, onde é possível visualizar suas imagens postadas.
   - O perfil também oferece um botão para adicionar novas imagens e editar informações pessoais.

4. **Funcionalidade de Adicionar Imagens:**
   - Usuários podem adicionar novas imagens ao seu perfil clicando no botão de envio de imagem e escolhendo um arquivo do computador.

5. **CSS e Design Responsivo:**
   - O design foi feito para ser simples, funcional e responsivo, utilizando **CSS Grid** e **Flexbox** para a estrutura da página.

## Tecnologias e Bibliotecas Utilizadas

- **Backend:**
  - **Flask**: Framework web Python para desenvolvimento rápido de aplicações.
  - **Flask-WTF**: Extensão de Flask para fácil manipulação de formulários e validação.
  - **Flask-Login**: Extensão de Flask para gerenciamento de sessões de login.

- **Frontend:**
  - **HTML5**: Para a estruturação da página.
  - **CSS3**: Estilos e layout responsivo para a interface de usuário.
  - **JavaScript**: Para interações e comportamentos dinâmicos da página.
  
- **Banco de Dados:**
  - **SQLite**: Banco de dados leve utilizado para armazenar as informações de usuários e suas imagens.
  
- **Outras Bibliotecas:**
  - **Bootstrap**: Framework CSS utilizado para facilitar a criação de layouts responsivos e interativos.

## Como Rodar o Projeto

### Requisitos

Antes de rodar o projeto, você precisará instalar as dependências listadas no `requirements.txt`:

1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/fakepinterest.git
   cd fakepinterest
