# Casos de Teste – SauceDemo

## CT-01 – Login com usuário válido
**Pré-condição:** Usuário cadastrado  
**Passos:**
1. Acessar o site https://www.saucedemo.com/
2. Informar usuário "standard_user"
3. Informar senha "secret_sauce"
4. Clicar em Login  

**Resultado esperado:** Usuário autenticado e redirecionado para a página de produtos.

---

## CT-02 – Login com senha inválida
**Pré-condição:** Usuário cadastrado  
**Passos:**
1. Acessar o site
2. Informar usuário "standard_user"
3. Informar senha inválida
4. Clicar em Login  

**Resultado esperado:** Exibição de mensagem de erro de login.

---

## CT-03 – Adicionar produto ao carrinho
**Pré-condição:** Usuário logado  
**Passos:**
1. Selecionar um produto
2. Clicar em "Add to cart"
3. Acessar o carrinho  

**Resultado esperado:** Produto adicionado corretamente ao carrinho.

---

## CT-04 – Finalizar compra com sucesso
**Pré-condição:** Produto no carrinho  
**Passos:**
1. Acessar o carrinho
2. Clicar em Checkout
3. Preencher dados obrigatórios
4. Finalizar compra  

**Resultado esperado:** Compra finalizada com sucesso.

---

## CT-05 – Logout do sistema
**Pré-condição:** Usuário logado  
**Passos:**
1. Abrir menu lateral
2. Clicar em Logout  

**Resultado esperado:** Usuário deslogado e redirecionado para tela de login.
