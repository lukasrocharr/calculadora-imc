# Calculadora de IMC

Aplicação web simples que calcula o Índice de Massa Corporal (IMC) a partir do peso e da altura.

## Como funciona a aplicação
- O usuário informa peso (kg) e altura (m).
- O JavaScript converte vírgula para ponto automaticamente e calcula: IMC = peso / (altura²).
- O resultado é formatado com duas casas decimais e exibido junto com a classificação (abaixo do peso, normal, sobrepeso, obesidade).
- Layout responsivo: na versão mobile a calculadora fica centralizada e a tabela de classificações aparece abaixo.

## Funcionalidades
- Cálculo do IMC com formatação (2 casas decimais).
- Aceita decimais com vírgula ou ponto.
- Exibe mensagem de classificação conforme faixas da OMS.
- Layout responsivo e acessível.

## Estrutura do projeto
- assets/src/index.html — página principal
- assets/src/styles/style.css — estilos
- assets/src/scripts/script.js — lógica JavaScript

## Como rodar localmente
Opção 1 — Live Server (VS Code)
1. Instale a extensão Live Server.
2. Abra `assets/src` no VS Code e clique em "Go Live".

Opção 2 — servidor simples com npx
```powershell
npx serve assets/src
```
Abra a URL mostrada no terminal (ex.: `http://localhost:5000`).

## Contribuição
- Fork -> branch -> pull request.  
- Mantenha HTML/CSS/JS organizados em `assets/src`.

## Licença
Sem licença especificada — adicione uma se desejar.