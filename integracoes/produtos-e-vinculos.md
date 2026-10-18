---
title: "Produtos e vínculos"
description: "Como ligar cada produto vendido no CardápioWeb a uma ficha técnica, composição ou item de estoque"
---

Para o estoque baixar sozinho a cada venda, o PraComprar precisa saber **o que cada produto vendido consome**. Isso é feito ligando o produto do CardápioWeb a uma **ficha de venda**, a uma **composição** ou a um **item de estoque**. Fica na aba **Produtos e vínculos** da [Central de Integrações](/integracoes/central-de-integracoes).

<Info>
  Você **não precisa** cadastrar o produto final na Gestão de Itens. Basta ter a ficha técnica de venda (ou o item que será baixado).
</Info>

## Ver o que falta vincular

Três cartões no topo funcionam como filtro: **Produtos**, **Vinculados** e **Sem vínculo**. Use a busca por nome ou ID do produto, e **Atualizar catálogo** para importar o catálogo atual do Cardápio Web.

Se o catálogo ainda não foi importado, a lista mostra os produtos capturados nas vendas recebidas.

## Criar um vínculo

<Steps>
  <Step title="Toque no produto">
    Escolha um produto **Sem vínculo** da lista
  </Step>
  <Step title="Selecione o destino">
    Busque e escolha entre:
    - **Ficha de venda** — consome os ingredientes da receita
    - **Composição** — para combos fixos (veja [Composições de combos](/integracoes/composicoes-de-combos))
    - **Item de estoque** — baixa o saldo do próprio item, **sem** executar a ficha de produção dele
  </Step>
  <Step title="Revise o consumo por venda">
    O painel mostra **Consumo por venda**, ou seja, o que vai sair do estoque a cada unidade vendida
  </Step>
  <Step title='Clique em "Salvar vínculo"'>
    O produto passa para **Vinculado**
  </Step>
</Steps>

Se não encontrar a ficha, crie-a em [Fichas Técnicas](/estoque/fichas-tecnicas) — o painel tem o atalho **Criar ficha técnica**.

### Produto que não deve baixar estoque

Há produtos que não consomem nada (um brinde, uma taxa). Para eles, escolha **Sem movimentação de estoque**. É uma decisão explícita: o produto deixa de aparecer como pendente.

## Regras importantes

- O **vínculo direto** prevalece sobre o código PDV; sem vínculo, o código PDV continua valendo
- Salvar um vínculo **não reprocessa** vendas já recebidas nem baixa estoque retroativo
- **Combos fixos** usam composições. Escolhas variáveis e complementos têm tratamento próprio (veja abaixo)

## Escolhas e complementos

Quando um pedido traz opções escolhidas pelo cliente (ex.: "troque a bebida"), é possível **configurar o vínculo da escolha**: definir se ela entra como **Acrescentar consumo à base**, se substitui a ficha principal ou se é **Sem movimentação de estoque**, e qual a **Quantidade por unidade da escolha**. O botão **Simular consumo físico** mostra o **Consumo total previsto** antes de você salvar.

<Tip>
  Comece pelos produtos mais vendidos. Os que não têm ficha de venda aparecem em **Sem baixa** na tela de [Vendas e pendências](/estoque/integracao-cardapioweb).
</Tip>

<Card title="Próximo passo" icon="arrow-right" href="/integracoes/recursos-e-regras">
  Defina quando as vendas baixam o estoque
</Card>
