# JoaoEquer.github.io

Site pessoal de João Equer no GitHub Pages, que hoje serve a versão web do app Ovnifit.

![Expo](https://img.shields.io/badge/-Expo-000020?logo=expo&logoColor=white)
![React](https://img.shields.io/badge/-React%20Native%20Web-61DAFB?logo=react&logoColor=black)
![PWA](https://img.shields.io/badge/-PWA-5A0FC8?logo=pwa&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/-GitHub%20Pages-222222?logo=githubpages&logoColor=white)

## Sobre

Este repositório guarda só o build estático (export web do Expo) do Ovnifit, antes Pedalien: app de treino de bike, corrida, academia e alimentação. O código-fonte do app não está aqui.

Demo: https://joaoequer.github.io

## Funcionalidades

- PWA instalável (manifest e service worker com Workbox).
- Página 404 própria.
- Publicação direta da raiz da branch `main`.

## Stack

| Tecnologia | Para que serve aqui |
|---|---|
| Expo (export web) / React Native Web | Gera o build servido |
| Workbox + `sw.js` | Cache e uso offline |
| MapLibre GL | Mapa (worker incluído no build) |
| GitHub Pages | Hospedagem |

## Como rodar

Não há o que rodar aqui. Para atualizar, gere o build no projeto do app (`npm run build:web`, conforme comentário no `index.html`) e copie o resultado para a raiz da `main`. Os commits seguem o formato `deploy: Ovnifit PWA <versão>`.

## Estrutura

```
index.html, 404.html   páginas
_expo/, assets/        JS, CSS e imagens do build
manifest.json, sw.js   PWA
```

## Status

Ativo, com deploys frequentes do Ovnifit.
