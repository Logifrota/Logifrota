# Painel Administrativo LogiFrota

Este repositório contém o código-fonte do painel administrativo para o sistema de gestão de frotas LogiFrota.

## Funcionalidades

- Login para usuários administrativos (RH/Frota).
- Dashboard com visão geral do sistema.
- Listagem e visualização de motoristas.
- Listagem e visualização de jornadas.
- Listagem e visualização de veículos.

## Tecnologias Utilizadas

- HTML
- CSS (básico, pode ser estilizado posteriormente)
- JavaScript (Vanilla JS)
- Firebase (para autenticação e acesso ao Firestore Database)

## Configuração

1.  Clone este repositório.
2.  Certifique-se de que o arquivo `firebaseConfigWeb.js` está presente e configurado com as credenciais corretas do seu projeto Firebase.
3.  Abra o arquivo `index.html` em um navegador ou hospede os arquivos em um servidor web estático (como Firebase Hosting).

## Backend

Este painel se conecta a um backend Firebase que inclui:
- Firebase Authentication
- Firestore Database
- Cloud Functions (para lógicas de negócio específicas)
