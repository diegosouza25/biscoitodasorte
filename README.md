🥠 Sorte do Dia - Biscoito da Sorte Digital

Bem-vindo ao repositório do Sorte do Dia! Este é um aplicativo web interativo que simula a experiência de abrir um biscoito da sorte chinês, oferecendo frases motivacionais baseadas no humor do usuário.

🎯 Objetivo do Projeto

Criar uma aplicação leve e divertida onde o usuário pode receber uma dose diária de motivação. O sistema garante que a mesma pessoa não receba frases repetidas e controla o acesso para apenas uma "jogada" a cada 12 horas.

🚀 Funcionalidades

Acesso Simplificado: Login apenas com o nome (usa Autenticação Anônima do Firebase).

Sorteio Inteligente: Baseado na emoção escolhida (Feliz, Triste, Motivado, Cansado, Ansioso).

Sem Repetições: O sistema memoriza quais frases o usuário já viu.

Cooldown de 12h: Controle de tempo para abrir um novo biscoito.

Modo Offline: Funciona com um banco de dados de backup caso a internet caia.

Painel Administrativo (Setup): Ferramenta segura para carga e atualização de frases no banco de dados.

🛠️ Tecnologias Utilizadas

Frontend: HTML5, CSS3 (via Tailwind CSS) e JavaScript (ES6 Modules).

Backend / Banco de Dados: Google Firebase (Firestore Database).

Autenticação: Firebase Authentication (Anônimo).

Hospedagem: GitHub Pages (compatível).

📂 Estrutura do Projeto

index.html: O aplicativo principal que o usuário acessa.

setup.html: Ferramenta administrativa para popular o banco de dados (protegido por senha).

⚙️ Como Configurar e Rodar

Pré-requisitos

Uma conta no Google Firebase.

Um projeto criado com Firestore Database e Authentication (Anônimo) ativados.

Passo a Passo

Clone o repositório:

git clone [https://github.com/seu-usuario/sorte-do-dia.git](https://github.com/seu-usuario/sorte-do-dia.git)


Configure o Firebase:

Substitua as chaves firebaseConfig no arquivo index.html e setup.html pelas do seu projeto.

Carga Inicial de Dados:

Abra o arquivo setup.html no navegador (localmente).

Digite a senha de administrador (Padrão: lsa142536).

Clique em "Enviar Frases".

Acesse o App:

Abra o index.html e comece a usar!

🔒 Segurança

O arquivo setup.html possui uma trava de segurança simples para evitar que o banco de dados seja zerado acidentalmente por usuários comuns.

Desenvolvido para fins de estudo em Gestão de TI.