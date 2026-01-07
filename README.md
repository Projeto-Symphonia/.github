# Perfil da Organização — Symphonia

Bem-vindos ao perfil da organização Symphonia — um time dedicado a construir uma plataforma para compartilhar e avaliar álbuns e músicas.

## Missão

Criar uma experiência social e colaborativa para fãs de música, permitindo que usuários publiquem avaliações com notas, comentem e descubram novos álbuns e artistas.

## Visão do projeto

-   Aplicação com backend em Node.js/Express e banco MongoDB.
-   Frontend moderno em React (Vite) para uma experiência interativa e responsiva.
-   Componentização pensada para facilitar reuso (ex.: componentes de posts, comentários, avaliações por estrelas).

Conteúdo principal do repositório base: [README.md](README.md)

## Tecnologias chave

-   Node.js, Express
-   MongoDB / Mongoose
-   React + Vite
-   Axios para comunicação API

## Organização dos repositórios / pastas

-   `server.js` / `src/` — backend (API, modelos, controllers, rotas)
-   `client/` — frontend legado (estático)
-   `symphonia-project/` — frontend moderno (React + Vite)

## Como contribuir

1. Abra uma issue descrevendo a proposta.
2. Crie um fork e uma branch `feature/<descrição>`.
3. Faça commits claros e abra um pull request com descrição do que foi alterado.

## Boas práticas

-   Autenticação e autorização em endpoints sensíveis.
-   Remoção em cascata no servidor para consistência (ex.: excluir comentários quando um post é removido).
-   Testes básicos para rotas essenciais (posts, comentários, usuários).

## Time — Integrantes

-   Ana Luiza
-   Pedro Henrique
-   Gustavo Fontenele
-   Riquelmy Ricarte
-   Matheus Cardoso

## Contato

Para mais informações, issues ou acesso a recursos (ex.: banco de dados de desenvolvimento), abra uma issue neste repositório ou contate o responsável pelo projeto.

---

Arquivo baseado em: [README.md](README.md)
