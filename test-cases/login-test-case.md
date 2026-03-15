# Casos de Teste - Funcionalidade de Login

Sistema testado: https://automationpratice.com.br/

---

## TC_LOGIN_001 - Login com sucesso

### Pré-condições
Usuário cadastrado no sistema.

### Passos

1. Acessar a página inicial
2. Clicar em "Login"
3. Inserir e-mail válido
4. Inserir senha válida
5. Clicar no botão de login

### Resultado esperado
O sistema deve autenticar o usuário e exibir a mensagem de login realizado com sucesso.

---

## TC_LOGIN_002 - Tentativa de login apenas com e-mail

### Passos

1. Acessar a página inicial
2. Clicar em "Login"
3. Inserir e-mail válido
4. Deixar o campo senha vazio
5. Clicar em login

### Resultado esperado
O sistema deve exibir mensagem de senha inválida.

---

## TC_LOGIN_003 - Tentativa de login apenas com senha

### Passos

1. Acessar a página inicial
2. Clicar em "Login"
3. Inserir senha
4. Deixar o campo e-mail vazio
5. Clicar em login

### Resultado esperado
O sistema deve exibir mensagem de e-mail inválido.

---

## TC_LOGIN_004 - Tentativa de login sem e-mail e senha

### Passos

1. Acessar a página inicial
2. Clicar em "Login"
3. Não preencher os campos
4. Clicar em login

### Resultado esperado
O sistema deve exibir mensagem de erro informando e-mail inválido.
