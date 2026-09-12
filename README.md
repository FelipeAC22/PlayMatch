# PlayMatch

O PlayMatch foi desenvolvido para conectar jogadores de forma rápida e eficiente por meio de um sistema inteligente de matchmaking. As preferências dos usuários são analisadas antes que as partidas sejam sugeridas.

## Equipe

* Felipe Antunes
* João Borba

## Tecnologias Utilizadas

* **React** – Será utilizado para construir a interface front-end, proporcionando uma experiência de usuário dinâmica e responsiva.
* **Node.js + TypeScript** – Serão utilizados no desenvolvimento do back-end, garantindo uma lógica de servidor escalável e segurança de tipos.
* **PostgreSQL** – Será utilizado como banco de dados para armazenar perfis de usuários, partidas e pontuações de reputação.
* **Git + GitHub** – Serão utilizados para controle de versão e desenvolvimento colaborativo.
* **Expo Go** – Será utilizado para testagem do app ainda em desenvolvimento.

## Funcionalidades

* Os perfis dos usuários serão sincronizados com a API da Steam para exibir automaticamente os jogos que possuem e o tempo de jogo.
* As partidas serão geradas com base nas preferências, disponibilidade e estilo de jogo dos usuários.
* Pontuações de reputação serão atribuídas após cada interação para garantir confiança e confiabilidade entre os usuários.
* Filtros serão aplicados para ajudar os usuários a encontrar companheiros de equipe por gênero de jogo, nível de habilidade ou plataforma.

## Instalação

1. Clone o repositório para sua máquina local.

```bash
git clone https://github.com/FelipeAC22/PlayMatch.git
npm install
```

## Como Executar

```bash
npm run start
```

## Histórico de Alterações

O projeto do repositório foi criado.
O slide de introdução foi criado.
A seção de objetivos foi adicionada.

## Regras e Requisitos

Entradas inválidas devem ser rejeitadas pelo sistema.

As senhas dos usuários devem ser criptografadas antes de serem armazenadas.

As pontuações de reputação devem ser atualizadas após cada partida para manter a justiça e o equilíbrio do sistema.
