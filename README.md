
# 🎬 CineHome - Plataforma de Locação de Streaming

**CineHome** é uma aplicação web para locação de filmes, séries, novelas e desenhos. O sistema foi desenvolvido por alunos do Curso Técnico em Desenvolvimento de Sistemas do SENAI, com foco em proporcionar uma experiência personalizada de entretenimento digital sem a necessidade de assinatura mensal.

## 📌 Sobre o Projeto

Inspirado em plataformas como Netflix e Prime Video, o CineHome oferece:
- Navegação por catálogo interativo
- Locação por título ou pacotes
- Interfaces exclusivas para administradores e usuários
- Cálculo de aluguel por tipo de mídia e número de dias
- Autenticação com diferentes perfis (admin e usuário)

> O sistema é uma solução escalável e moderna, com backend em PHP, frontend responsivo e armazenamento em arquivos JSON.

## 🛠️ Tecnologias Utilizadas

- **PHP (com POO e Namespaces)**
- **HTML5 / CSS3 / Bootstrap**
- **JavaScript**
- **JSON** (para persistência de dados)
- **Figma** (para prototipação)
- **Kanban (Trello)** e **Scrum** (metodologia ágil)

## ⚙️ Funcionalidades

### Usuário comum:
- Login e cadastro
- Explorar e alugar mídias
- Visualizar catálogo com filtros
- Ver histórico de locações
- Calcular valor de aluguel

### Administrador:
- Acesso restrito com login
- Cadastrar, editar, deletar e alugar/devolver mídias
- Gerenciar catálogo de filmes, séries, novelas e desenhos

## 📁 Estrutura de Pastas

```
├── config/               # Arquivo de configuração
├── data/                 # JSONs de usuários e itens
├── img/uploads/          # Imagens das mídias
├── models/               # Classes de domínio (Filme, Serie, etc.)
├── public/               # Arquivos públicos como login.php e cadastro.php
├── services/             # Lógica de negócio (Auth, Locadora)
├── views/                # Templates e layout
└── index.php             # Arquivo principal
```

## 🚀 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/SeuUsuario/CineHome.git
   ```

2. Coloque os arquivos em um servidor local (como o [XAMPP](https://www.apachefriends.org/) ou [Laragon](https://laragon.org/)).

3. Inicie o Apache e acesse no navegador:
   ```
   http://localhost/CineHome/public/login.php
   ```

4. Use os usuários padrão (armazenados em `usuarios.json`):
   - Admin: `admin` / `admin123`
   - Usuário: `usuario` / `user123`

## 🔐 Segurança

- Senhas criptografadas (usando `password_hash`)
- Autenticação baseada em sessão
- Validações de entrada e controle de acesso por perfil

## 📅 Metodologia

Projeto desenvolvido em três Sprints:
1. Planejamento e protótipo (Figma)
2. Frontend e lógica de aluguel
3. Backend completo e integração

## 👥 Equipe

- Ana Lauren Dourado Pereira  
- Isabela Paiola  
- Laura Araujo Dutra dos Santos  
- Maria Eduarda dos Santos Rosa  
- Pedro Henrique da Silva Rodrigues  
- Yasmin Lopes Borba  

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais no SENAI e não possui fins comerciais.
