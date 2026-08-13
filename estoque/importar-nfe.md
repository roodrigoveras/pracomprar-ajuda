---
title: "Importar NF-e"
description: "Como lançar entradas de estoque em lote importando o XML de uma Nota Fiscal Eletrônica"
---

Em vez de lançar item por item manualmente, você pode importar o XML da nota fiscal do fornecedor e o PraComprar lança as entradas de estoque automaticamente, cruzando os produtos pelo código de barras (GTIN).

<Steps>
  <Step title="Envie o XML da NF-e">
    Acesse **Estoque → NF-e** e selecione o arquivo `.xml` — pode ser o arquivo do emissor ou baixado da SEFAZ
  </Step>
  <Step title="Confira os dados da nota">
    O sistema mostra emitente, número/série, data de emissão e valor total
  </Step>
  <Step title="Revise os itens da nota">
    Para cada item, edite se necessário:
    - **Quantidade**
    - **Custo unitário**
    - **Local de destino** — já sugerido automaticamente com base em onde o produto costuma ficar
    - **Vínculo no catálogo** — o item da nota é cruzado com o produto correspondente no seu catálogo pelo GTIN
  </Step>
  <Step title="Aplique um local padrão (opcional)">
    Se vários itens ficarem sem local definido, use **Aplicar a todos** para definir um local padrão de uma vez
  </Step>
  <Step title="Confirme a importação">
    O estoque é atualizado com todos os itens selecionados
  </Step>
</Steps>

<Tip>
  Se uma nota já foi parcialmente importada antes, você pode reprocessar o mesmo XML — apenas os itens ainda pendentes serão lançados novamente.
</Tip>

<Card title="Voltar ao início do Estoque" icon="arrow-right" href="/estoque/dashboard-de-estoque">
  Veja o resumo geral do seu estoque
</Card>
