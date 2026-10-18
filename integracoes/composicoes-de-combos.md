---
title: "Composições de combos"
description: "Como montar combos fixos com fichas de venda e itens de estoque"
---

Uma **composição** é um combo que sempre leva os mesmos componentes — por exemplo, *1 poke + 2 guiozas*. Ao vincular o produto do CardápioWeb a uma composição, cada venda baixa tudo de uma vez.

<Steps>
  <Step title="Abra a aba Composições de combos">
    Na [Central de Integrações](/integracoes/central-de-integracoes), clique em **Composições de combos** e depois em **Nova composição**
  </Step>
  <Step title="Dê um nome">
    Ex.: *Combo poke + guioza*
  </Step>
  <Step title='Clique em "Adicionar componente"'>
    Busque a **ficha ou item** e informe a **Quantidade** para **1 combo** vendido. Repita para cada componente. As abas de busca separam **Fichas de venda** e **Itens de estoque**
  </Step>
  <Step title='Clique em "Salvar composição"'>
    Salvar **não movimenta estoque**
  </Step>
  <Step title="Vincule o produto">
    Em [Produtos e vínculos](/integracoes/produtos-e-vinculos), ligue o produto do Cardápio Web à composição criada
  </Step>
</Steps>

## Como cada componente baixa o estoque

- Uma **ficha** consome os ingredientes dela, proporcionalmente ao rendimento
- Um **item** baixa o próprio saldo, sem usar a ficha de produção dele

<Note>
  Para usar um item de estoque como componente, ele precisa ter o **Modo de baixa na venda** definido na Gestão de Itens. Itens esmaecidos na busca ainda não têm essa configuração.
</Note>

<Warning>
  Cadastre só componentes **fixos**. Escolhas variáveis do cliente não entram como ingrediente da composição; elas têm vínculo próprio. Componentes repetidos não são aceitos: some as quantidades na mesma linha.
</Warning>

<Card title="Próximo passo" icon="arrow-right" href="/integracoes/produtos-e-vinculos">
  Ligue o combo ao produto vendido
</Card>
