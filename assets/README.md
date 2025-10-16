# Calculadora de IMC

Projeto web simples para calcular o Índice de Massa Corporal (IMC) com interface em HTML/CSS/JS.

## Funcionalidades
- Cálculo de IMC (peso / altura²)
- Aceita decimais com vírgula ou ponto (JS faz a conversão)
- Exibe classificação conforme intervalo de IMC
- Layout responsivo: calculadora centralizada no mobile e tabela abaixo

## Estrutura
- assets/src/index.html — página principal
- assets/src/styles/style.css — estilos
- assets/src/scripts/script.js — lógica JS

## Como rodar localmente
Opção 1 — Live Server (recomendado, VS Code)
1. Instale extensão Live Server
2. Clique em "Go Live"

Opção 2 — servidor simples com npx
```powershell
npx serve assets/src
```
(Se PowerShell bloquear npx, use Live Server ou ajuste `Set-ExecutionPolicy`.)

Abra `http://localhost:5000` (ou a porta mostrada).

## Deploy no Firebase Hosting
1. Instale Firebase CLI:
```powershell
npm install -g firebase-tools
```
2. Login e inicialização (na pasta do projeto):
```powershell
firebase login
firebase init
# quando perguntado, defina "public" como: assets/src
# responda "No" para sobrescrever index.html se for o caso
```
3. Deploy:
```powershell
firebase deploy --only hosting
```

## Contribuição
- Faça fork, crie branch, commit e PR.
- Mantenha HTML/CSS/JS organizados em `assets/src`.

## Licença
Projeto sem licença especificada — adicione uma licença se desejar.