# GO - Gamified Org
## 🚀 Sobre o Projeto
O GO - Gamified Org é um aplicativo de gestão de tarefas que transforma a organização pessoal em uma experiência motivadora e divertida. Ele tem como objetivo combater a procrastinação e o desânimo, usando a mecânica dos jogos para incentivar a consistência e aumentar a produtividade. O app busca quebrar a barreira do "tenho que fazer", transformando tarefas em missões com recompensas, onde o usuário pode subir de nível, desbloquear conquistas e visualizar seu progresso em tempo real.

## ✨ Funcionalidades Principais
O aplicativo é projetado para um público amplo, incluindo estudantes, profissionais liberais e qualquer pessoa que busque mais motivação e eficácia em sua rotina diária.

Sistema de Gamificação Central: Inclui um painel de progresso do jogador, um sistema de pontos por tarefa e nivelamento. O usuário acumula pontos para subir de nível e desbloquear novas funcionalidades, como avatares e temas. O app também oferece uma galeria de conquistas virtuais que o usuário pode ganhar ao completar marcos específicos.

Gestão de Tarefas: Permite a criação de tarefas simples e complexas, com a definição de prioridades e prazos. O usuário pode revisar todas as tarefas concluídas e visualizar estatísticas de produtividade em tempo real.

Personalização e Engajamento: O usuário pode personalizar um avatar que o representará no jogo, com novos itens desbloqueados ao subir de nível. A interface também pode ser personalizada com diferentes temas visuais. O sistema gera desafios diários e missões de longo prazo, dando pontos extras ou recompensas especiais.



## 💻 Tecnologias
Este projeto está sendo desenvolvido utilizando uma arquitetura moderna e escalável, com React no frontend e Django no backend.

### Frontend:
React: Biblioteca JavaScript para a construção da interface do usuário (UI) dinâmica e interativa.

### Backend:
Django: Framework web Python para o gerenciamento da lógica de negócio e da API.

### API:
Django Rest Framework (DRF): Para a criação de uma API RESTful.

### Autenticação:
JSON Web Tokens (JWT): Para autenticação e segurança das requisições.

## 🎨 Wireframes
A seguir, apresentamos os wireframes do projeto que definem o fluxo de navegação e o design das telas principais:

1. Fluxo de Autenticação
Fluxo de entrada e criação de conta do usuário.
2. Painel Principal e de Metas
Dashboard que mostra o progresso do jogador e as tarefas diárias.
3. Calendário de Tarefas
Visualização e organização de tarefas em formato de calendário.

## 🛠️ Como Executar o Projeto
Siga as instruções abaixo para clonar o repositório e rodar o projeto em sua máquina local.

Pré-requisitos
Certifique-se de ter o Node.js e o Python 3 instalados.

1. Configurar o Backend (Django)

```
Bash

# Clone o repositório
git clone https://github.com/seu-usuario/go-gamified-org.git
cd go-gamified-org

# Crie um ambiente virtual e ative-o
python -m venv venv
source venv/bin/activate  # No Windows use `venv\Scripts\activate`

# Instale as dependências
pip install -r requirements.txt

# Execute as migrações do banco de dados
python manage.py migrate

# Crie um superusuário (opcional)
python manage.py createsuperuser

# Inicie o servidor Django
python manage.py runserver
O servidor do backend estará rodando em http://localhost:8000.
```

2. Configurar o Frontend (React)
```
Bash

# Navegue para o diretório do frontend
cd frontend

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento do React
npm start
O aplicativo estará disponível em http://localhost:3000.
```

## 🧑‍🤝‍🧑 Equipe
Este projeto foi desenvolvido como um Trabalho de Conclusão de Curso (TCC) para a ETEC de Praia Grande.

Álvaro Manuel Morgado Chiari 

Caio dos Santos 

Isabella de Lira Gomes 

Rodrigo Jun Tangi Finotti 

Yghor Soares Oliveira Santos 

## 📅 Cronograma
O projeto segue o seguinte cronograma de desenvolvimento, com previsão de conclusão em outubro de 2025.

Fase 1: Monografia e Finalização (07/10/2025 - 29/10/2025) 

Fase 2: Planejamento e Design Essencial (30/10/2025 - 10/11/2025) 

Fase 3: Desenvolvimento Frontend (MVP) (11/11/2025 - 02/12/2025) 
