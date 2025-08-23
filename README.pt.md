# Hashflix

## Sobre o Projeto
Este é um projeto web completo, desenvolvido com o framework Django, que simula uma plataforma de streaming de filmes e séries. O aplicativo permite que os usuários criem uma conta, façam login e acessem um catálogo de filmes com informações detalhadas, sistema de visualizações e um histórico de filmes assistidos.

## Funcionalidades
- **Autenticação de Usuário:** Sistema robusto de login, registro de conta e edição de perfil.
- **Catálogo de Filmes:** Exibe uma lista de filmes e um destaque para o mais popular, com opção de pesquisa.
- **Páginas Detalhadas:** Cada filme possui uma página própria com informações, visualizações e a opção de assistir aos episódios.
- **Sistema de Histórico:** O aplicativo registra quais filmes o usuário assistiu.

## Tecnologias
Foram utilizadas as seguintes tecnologias: Python, Django, HTML, CSS, Tailwind, Bootstrap, SQLite, SQLAlchemy

## Como Executar
Para rodar este projeto, é necessário ter o Python e o `pip` instalados. Após clonar o repositório, instale as dependências listadas no arquivo `requirements.txt`.

**Lembre-se de aplicar as migrações para criar o banco de dados antes de executar a aplicação:**
```bash
python manage.py makemigrations
python manage.py migrate
