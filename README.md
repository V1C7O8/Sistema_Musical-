# 🎵 Sistema de Gestão de Artistas e Músicas

Este projeto é uma aplicação web desenvolvida para o gerenciamento, cadastro e listagem de artistas e suas respetivas músicas. O sistema conta com controle de acesso através de autenticação (login/logout), validação de sessão e armazenamento de dados em banco MySQL.

## 🚀 Funcionalidades

- **Autenticação de Usuários:**
  - Login seguro com validação de sessão (`login.html`, `valida.sessao.php`).
  - Geração automática de senhas/hash (`geraSenha.php`).
  - Encerramento de sessão (`logout.php`).

- **Gestão de Artistas e Músicas:**
  - Cadastro de novos artistas (`cadastro_artista.html`).
  - Cadastro de músicas com associação aos artistas (`cadastro_musica.html`).
  - Listagem e consulta de músicas cadastradas (`listagem_musicas.html`).

- **Interface e Estilização:**
  - Layout responsivo estilizado via CSS (`styles.css`).
  - Suporte a capas de álbuns e imagens de referência dos artistas (`img - Ref/`).

---

## 📁 Estrutura de Arquivos

```text
artistas-musicas/
├── bd.sql                   # Script de criação das tabelas e banco de dados MySQL
├── conexao.php              # Configuração da conexão com o banco de dados
├── login.html               # Tela de login
├── logout.php               # Script de encerramento da sessão
├── valida.sessao.php        # Verificação e proteção de rotas privadas
├── geraSenha.php            # Script auxiliar para criptografia/geração de senhas
├── index.html               # Página inicial / Dashboard
├── cadastro_artista.html    # Formulário de cadastro de artista
├── cadastro_musica.html     # Formulário de cadastro de música
├── listagem_musicas.html    # Exibição das músicas e artistas
├── styles.css               # Estilização visual da aplicação
└── img - Ref/               # Imagens de capas de álbuns e referências visuais
