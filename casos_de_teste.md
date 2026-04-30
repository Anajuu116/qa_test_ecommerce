# Casos de teste
## TC_CART_01 - Adicionar item ao carrinho de compras
### Cenário: Adicionar produdo ao carrinho

**Pré-condição:** Usuário logado com produto disponível.

**Passos:** 
1. Buscar por um produto;
2. Acessar o produto;
3. Selecionar o ícone "Adicionar ao Carrinho".

**Resultado esperado:**

O item deve ser incorporado a aba "Carrinho de compras" da maneira correta.

**Resultado obtido:**

Os itens selecionados não eram adicionados de maneira correta ao carrinho de compras 100% das vezes, apresentando comportamento inconsistente observado durante os testes. Com resultados variando com o tipo de navegador utilizado.

--- 

## TC_CART_02 - Remover itens do carrinho
### Cenário: Tirar os produtos adicionados anteriormente

**Pré-condição:** Usuário logado com produto disponível.

**Passos:**
1. Abrir a aba "Carrinho de compras";
2. Identificar o produto desejado;
3. Clicar no "X" correspondente ao produto para removê-lo.

**Resultado esperado:**

O item deve ser removido do carrinho de compras de forma integral.

**Resultado obtido:**

O item selecionado, continuou retornando ao carrinho mesmo após sua remoção de forma repetida, com resultados variando com o tipo de navegador utilizado.

---

## TC_CART_03 - Atualizar o valor final
### Cenário: Conferir valor final do carrinho de compras

**Pré-condição:** Usuário logado com produto disponível.

**Passos:**
1. Remover ou adicionar um produto no carrinho de compras;
2. Identificar se houve alguma mudança no valor final.

**Resultado esperado:**

O valor deve atualizar automáticamente, de forma rápida e precisa.

**Resultado Obtido:**

O valor final apresenta demora para atualizar, com erros na página de acordo com o navegador utilizado. Em alguns casos, foi necessário recarregar a página ou interagir com a interface para que a funcionalidade fosse executada.