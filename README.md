# Spotify Playlist Builder

![Status](https://img.shields.io/badge/status-desafio%20t%C3%A9cnico-2ea44f?style=for-the-badge)
![Next.js](https://img.shields.io/badge/Next.js-13%2B-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Spotify](https://img.shields.io/badge/Spotify-Web%20API-1DB954?style=for-the-badge&logo=spotify&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-deploy-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![Licença](https://img.shields.io/badge/licença-MIT-042570?style=for-the-badge)

> Desafio front-end para candidatos: construir uma aplicação que busca músicas na API do Spotify,
> cria playlists personalizadas e as gerencia. Este repositório traz o enunciado; o projeto de cada
> candidato roda no próprio deploy no Netlify.

## Sumário

- [Sobre o sistema](#-sobre-o-sistema)
- [O que ele faz](#-o-que-ele-faz)
- [Ajustes e melhorias](#-ajustes-e-melhorias)
- [Pré-requisitos](#-pré-requisitos)
- [Instalando o Spotify Playlist Builder](#-instalando-o-spotify-playlist-builder)
- [Usando o Spotify Playlist Builder](#-usando-o-spotify-playlist-builder)
- [Configuração](#-configuração)
- [Arquitetura](#-arquitetura)
- [Testes](#-testes)
- [CI e deploy](#-ci-e-deploy)
- [Contribuindo para o Spotify Playlist Builder](#-contribuindo-para-o-spotify-playlist-builder)
- [Colaboradores](#-colaboradores)
- [Documentação](#-documentação)
- [Licença](#-licença)

## 📌 Sobre o sistema

Bem-vindo ao desafio front-end da **GP Engenharia e Consultoria**! Neste desafio, você construirá
uma aplicação que utiliza a API do **Spotify** para buscar músicas, criar playlists personalizadas
e gerenciá-las usando **Next.js**.

### 🎯 Objetivo

Desenvolver uma aplicação web que:

- ✅ Busque músicas por gênero e outros filtros usando a **API do Spotify**
- ✅ Permita criar e gerenciar **playlists**
- ✅ Adicione e remova **músicas da playlist**
- ✅ Tenha um **design responsivo e intuitivo**

## 🧭 O que ele faz

### Funcionalidades Principais

#### **1. Autenticação com Spotify**

- Implementar **fluxo OAuth 2.0**
- Gerenciar **token de acesso e refresh token**
- Referência:
  [Spotify Authorization Guide](https://developer.spotify.com/documentation/general/guides/authorization-guide/)

#### **2. Sistema de Busca**

- Busca por **gênero** via endpoint `/recommendations`
- Busca avançada (**bônus**) via `/search` (artistas, músicas, álbuns)

#### **3. Gerenciamento de Playlists**

- Criar **playlists locais**
- Adicionar/remover músicas
- Salvar playlists no perfil do Spotify (**se autenticado**)
- Editar detalhes da playlist (**bônus**)

#### **4. Interface do Usuário**

- Layout moderno com referências do **Dribbble**
- Ilustrações do **unDraw**
- **Totalmente responsivo**
- **Feedback visual** para ações do usuário

## 🚧 Ajustes e melhorias

### Sugestões de Melhorias (Bônus)

- 🔹 **Sistema de favoritos** para músicas
- 🔹 **Compartilhamento de playlists** via URL
- 🔹 **Sincronização entre abas** usando localStorage
- 🔹 **Paginação** para resultados de busca
- 🔹 **Animações** com Framer Motion

## 💻 Pré-requisitos

Os requisitos técnicos do desafio estão em [Arquitetura](#-arquitetura). Você também precisa de uma
conta no GitHub para fazer o fork.

## 🚀 Instalando o Spotify Playlist Builder

Este repositório traz só o enunciado: não há código para instalar. As instruções de instalação do
seu projeto fazem parte da [entrega](#-contribuindo-para-o-spotify-playlist-builder).

## ☕ Usando o Spotify Playlist Builder

O uso da aplicação é o descrito em [O que ele faz](#-o-que-ele-faz).

## 🔧 Configuração

O enunciado não define variáveis de ambiente: documente as do seu projeto no README da entrega.

## 🧱 Arquitetura

### 📌 Requisitos Técnicos

#### **Obrigatórios**

- ✅ **Next.js** (versão 13 ou superior) ou **React.js**
- ✅ **Spotify Web API** (autenticação via OAuth)
- ✅ **Gerenciamento de estado** (Context API, Zustand ou Redux Toolkit)
- ✅ **Estilização** com CSS Modules, Styled Components ou TailwindCSS
- ✅ **Hospedagem** no Netlify (deploy contínuo)
- ✅ **Roteamento** com Next.js Router

#### **Desejáveis (Bônus)**

- 🧪 **Testes unitários e de integração** (Jest, React Testing Library)
- 📂 **Rotas dinâmicas** (ex: página dedicada para cada playlist)
- 🎤 **Busca avançada** (por artista, nome da música e álbum)
- 🎶 **Player de prévia das músicas** (embed do Spotify)
- ✨ **Dark/Light Mode** (tema alternativo)
- 📊 **Estatísticas da playlist** (duração total, popularidade média)

## 🧪 Testes

Testes unitários e de integração são bônus do desafio, como listado em [Arquitetura](#-arquitetura).

## 🔁 CI e deploy

O desafio pede hospedagem no Netlify, com deploy contínuo, e a URL do deploy faz parte da entrega.

## 📫 Contribuindo para o Spotify Playlist Builder

Este repositório não recebe contribuições de código: cada candidato trabalha no próprio fork,
seguindo as regras abaixo.

### 📌 Regras de Entrega

#### **1. Repositório no GitHub**

- Faça um **fork** deste repositório para sua conta pessoal
- Mantenha o repositório **público** durante o desenvolvimento
- Nome do repositório: `spotify-playlist-builder-[seu-nome]`

#### **2. Padrão de Commits**

- Use **commits atômicos** (1 feature por commit)
- Formato: `tipo: descrição` (ex: `feat: autenticação com Spotify`)
- Tipos válidos: `feat`, `fix`, `style`, `refactor`, `docs`, `test`

#### **3. Organização do Código**

- Mantenha uma **estrutura de pastas clara**
- **Documente** componentes complexos
- Siga boas práticas de **clean code**

#### **4. Prazo de Entrega**

- **7 dias corridos** a partir do recebimento
- **Entregas tardias serão desconsideradas**

#### **5. Itens Obrigatórios para Entrega**

- ✅ Link do **repositório GitHub** (com histórico de commits)
- ✅ URL do **deploy no Netlify**
- ✅ README completo com:
  - 📌 **Instruções de instalação**
  - 📌 **Dependências utilizadas**
  - 📌 **Dificuldades encontradas**

#### **6. Critérios de Avaliação**

- ✅ **Funcionalidades implementadas**
- ✅ **Qualidade do código**
- ✅ **Organização dos commits**
- ✅ **UI/UX e responsividade**
- ✅ **Documentação**

#### **7. Dicas Extras**

- ✅ **Priorize as funcionalidades obrigatórias**
- ✅ **Teste em diferentes dispositivos**
- ✅ **Mantenha o design consistente**
- ✅ **Trate possíveis erros da API**

⚠️ **Atenção**: Plágio ou cópia de outros projetos resultará em **desqualificação imediata**.

## 🤝 Colaboradores

Este desafio é mantido pela GpDevLab.

## 📚 Documentação

### 📎 Links Úteis

- 🎵 [Spotify Web API](https://developer.spotify.com/documentation/web-api/)
- 🎨 [Inspiração UI - Dribbble](https://dribbble.com/)
- 🚀 [Netlify Docs](https://docs.netlify.com/)
- 🖼️ [unDraw Illustrations](https://undraw.co/)

Boa sorte! 🚀 Use sua criatividade e divirta-se desenvolvendo! 🎧

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE).
