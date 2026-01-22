# Registro de Bugs – SauceDemo

## BUG-01 – Mensagem de erro genérica no login inválido
**ID:** BUG-01  
**Título:** Mensagem de erro pouco clara no login  
**Ambiente:** Web – Google Chrome  
**Severidade:** Média  
**Prioridade:** Média  

**Passos para reproduzir:**
1. Acessar https://www.saucedemo.com/
2. Informar usuário válido
3. Informar senha inválida
4. Clicar em Login  

**Resultado esperado:** Mensagem clara informando que usuário ou senha estão incorretos.  
**Resultado obtido:** Mensagem genérica sem indicar o campo incorreto.

---

## BUG-02 – Carrinho não atualiza quantidade
**ID:** BUG-02  
**Título:** Quantidade do carrinho não atualiza corretamente  
**Ambiente:** Web – Google Chrome  
**Severidade:** Baixa  
**Prioridade:** Baixa  

**Passos para reproduzir:**
1. Logar no sistema
2. Adicionar dois produtos diferentes ao carrinho
3. Acessar o carrinho  

**Resultado esperado:** Carrinho exibe dois produtos.  
**Resultado obtido:** Carrinho exibe apenas um produto.
