# JoaoEquer.github.io

Site pessoal no GitHub Pages. Hoje serve a versão web (PWA) do app Ovnifit (antes Pedalien), que reúne treino de bike, corrida, academia e alimentação.

Endereço: https://joaoequer.github.io

## O que há no repositório

É apenas o build estático do app (export web do Expo): `index.html`, `_expo/`, `assets/`, `manifest.json`, `sw.js` e ícones. O código-fonte do app não está aqui.

## Como atualizar

Não edite os arquivos à mão. Gere o build web no projeto do app (`npm run build:web`, conforme comentário no `index.html`) e copie o resultado para este repositório, na branch `main`. O histórico mostra commits no formato `deploy: Ovnifit PWA <versão>`. O Pages publica a raiz da `main`.

## Uso

Abra o endereço no navegador e use "Adicionar à Tela de Início" para instalar como app.
