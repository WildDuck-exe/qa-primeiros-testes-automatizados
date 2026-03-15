# Primeiros Testes Automatizados com CodeceptJS

Este repositório contém meus primeiros testes automatizados, desenvolvidos como prática inicial em automação de testes.

Os testes foram realizados na plataforma de estudo:

https://automationpratice.com.br/

---

## Objetivo

Praticar conceitos iniciais de automação de testes Web, entendendo a criação de cenários automatizados, execução de testes e validação de comportamentos do sistema.

---

## Cenários automatizados

Os testes implementados neste projeto incluem:

- Login com sucesso
- Tentativa de login apenas com e-mail
- Tentativa de login apenas com senha
- Tentativa de login sem credenciais

---

## Tecnologias utilizadas

- JavaScript
- CodeceptJS
- Node.js
- Visual Studio Code

---

## Execução dos testes

Para executar os testes:

```bash
npx codeceptjs run --steps
ou
npx codeceptjs run --grep 'tag'
