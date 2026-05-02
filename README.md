# Projeto de Teste Manual - E-commerce
Projeto de testes manuais em e-commerce com documentação de bugs e casos de teste.
# Teste da funcionalidade do Carrinho de Compras - Americanas
- Data: 14/04/2026
- Sistema testado: https://www.americanas.com.br/
- Tipo de teste: Teste funcional manual
## Descrição 
Projeto de teste manual, com foco na funcionalidade de carrinho de compras em um site de e-commerce e identificação de bugs em diferentes navegadores.
## Objetivo
Verificar se as funcionalidades ofertadas como: adicionar, remover, editar ou atualizar itens ao carrinho estão funcionando corretamente. 
## Ambiente de teste
- Navegadores:
    - Google Chrome
    - Mozilla Firefox
    - Microsoft Edge
- Dispositivo: Desktop
- Login utilizado: Mesmo em todos os testes
- CEP configurado
- Cookies e permissões do site aceitos
- Cada cenário foi testado 10 vezes por navegador
## Cenários testados
- Adicionar itens ao carrinho
- Aumentar ou diminuir a quantidade de itens já selecionados
- Remover itens do carrinho
- Verificar atualização dos preços ao remover itens
## Resultados
### Google Chrome
- Comportamento inconsistente, em todos os testes realizados não era possível a remoção de itens após adicioná-los por meio da aba destinada ao carrinho, a remoção só era possível após dar continuidade a compra, pouco antes do pagamento.
- Em alguns casos, ao adicionar certa quantidade de itens o site impossibilita o usuário de adicionar outros, excluindo automáticamente aqueles selecionados após o primeiro item.
- As falhas apresentadas foram intermitentes, tendo se repetido todas as vezes que o teste foi rodado.
### Mozilla Firefox
- Funcionamento estável, dentro do esperado permitindo uso de todas as funcionalidades oferecidas sem intercorrências ou erros.
### Microsoft Edge
- Funcionamento estável ao adicionar e remover itens, operando dentro do esperado.
- Apresentou delay ao exibir a atualização dos preços após remoção de itens do carrinho, sendo por vezes necessária uma ação na página como interagir com a interface ou até recarregar a página. 
## Problemas identificados
- Bug crítico no funcionamento com o uso do Google Chrome
- Delay na atualização dos valores com o uso do Microsoft Edge
## Conclusão
A funcionalidade apresenta bugs e inconsistências críticas a depender do navegador, sendo o Google Chrome o mais afetado, o que além de impactar a experiência do usuário pode vir a ser uma desvantagem para a empresa, pois o Chrome é o navegador mais utilizado em todo o mundo. 
## Sugestões de melhorias
- Corrigir comportamento apresentado no Google Chrome
- Garantir a atualização imediata ou menos demorada dos preços no Microsoft Edge.
