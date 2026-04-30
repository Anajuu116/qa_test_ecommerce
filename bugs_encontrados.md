# Bugs Encontrados
## Bug_CART_01 - Não é possível adicionar todos os itens desejados no carrinho

**Severidade:** Alta

**Prioridade:** Alta

**Tipo:** Funcional

**Ambiente:**
- Navegador: Google Chrome
- Dispositivo: Desktop

### Passos para reproduzir:
1. Acessar o site;
2. Adicionar itens no carrinho;
3. Abrir o carrinho;
4. Tentar adicionar mais itens.

**Resultado esperado:** Adicionar quantos e quaisquer itens o usuário desejar.

**Resultado obtido:** Não é possível adicionar todos os produtos desejados, pois a aba "carrinho" não os mantém na lista de compras, ela os exclui automáticamente e de maneira aleatória.

**Frequência:** Ocorreu em 100% dos testes realizados.

**Observações:** O bug ocorre de forma aleatória, não sendo possível prever ou predizer quando ele irá se manifestar.

## Bug_CART_02 - Não é possível a remoção de itens do carrinho

**Severidade:** Alta

**Prioridade:** Alta

**Tipo:** Funcional

**Ambiente:**
- Navegador: Google Chrome
- Dispositivo: Desktop

### Passos para reproduzir:
1. Acessar o site;
2. Adicionar item 
3. Abrir o carrinho de compras;
4. Tentar remover o item.

**Resultado esperado:** O item deve ser removido do carrinho de forma imediata.

**Resultado obtido:** O item sai do carrinho, porém, retorna ao mesmo sem o comando do usuário de forma praticamente instantânea. Impossibilitando assim a alteração da lista de compras.

**Frequência:** Ocorreu em 100% dos testes realizados.

**Observações:** O erro se mostrou consistente, se apresentando em praticamente todos os itens adicionados e em todos os testes realizados. 

## Bug_CART_03 - Delay na atualização de preços
**Severidade:** Média

**Prioridade:** Média

**Tipo:** Funcional

**Ambiente:**
- Navegador: Microsoft Edge
- Dispositivo: Desktop

### Passos para reproduzir:
1. Acessar o site;
2. Adicionar ou remover item;
3. Observar o somatório total.

**Resultado esperado:** O total deve ser atualizado automáticamente após uma modificação no carrinho de compras.

**Resultado obtido:** O somatório total muitas vezes apresentou significativo delay ao atualizar, muitas vezes sendo necessária nova interação com a interface para que o mesmo mostrasse a alteração.

**Frequência:** Ocorreu em 100% dos testes realizados.

**Observações:** Muitas vezes além da interação, era necessário recarregar a página.

---

**TODOS OS BUGS IMPEDEM A UTILIZAÇÃO CORRETA DA FUNCIONALIDADE**
