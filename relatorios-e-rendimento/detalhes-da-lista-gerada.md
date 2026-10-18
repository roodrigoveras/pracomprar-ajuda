---
title: "Detalhes da lista gerada"
description: "Como visualizar, editar e decidir o que fazer com uma lista depois de enviada"
---

Depois que uma lista é enviada (seja como pedido ou contagem), ela vira uma **lista gerada** — um registro histórico que você pode revisitar, editar e usar como base pra novas ações.

<Steps>
  <Step title="Acesse Listas Geradas">
    No menu, entre em **Listas Geradas**
  </Step>
  <Step title="Clique numa lista">
    Abre a tela de **Detalhes da Lista Gerada**
  </Step>
  <Step title="Confira o resumo">
    - **Criado por** — quem gerou a lista
    - **Data** — quando foi gerada
    - **Itens** — quantidade total
    - **Fornecedores** — quantos fornecedores estão envolvidos
  </Step>
  <Step title="Navegue pelos itens">
    Os itens ficam agrupados por **fornecedor**, com categoria e quantidade de cada um — clique no cabeçalho de um grupo pra expandir ou recolher
  </Step>
</Steps>

## O que fazer a partir daqui

<CardGroup cols={2}>
  <Card title="Editar" icon="pen">
    Renomeia itens, ajusta quantidade e unidade, adiciona ou remove itens — depois de enviada, a lista continua editável
  </Card>
  <Card title="WhatsApp" icon="whatsapp">
    Reenvia a lista formatada por WhatsApp
  </Card>
  <Card title="Enviar pedido" icon="paper-plane" href="/listas-e-cotacoes/preencher-e-enviar-pedido">
    Envia o pedido direto para o fornecedor principal de cada item, sem passar por cotação
  </Card>
  <Card title="Solicitar cotação" icon="file-invoice-dollar" href="/listas-e-cotacoes/gerar-cotacao">
    Pede cotação a um ou mais fornecedores pra comparar preços antes de decidir
  </Card>
</CardGroup>

## Editando uma lista já gerada

<Steps>
  <Step title='Clique em "Editar"'>
    A tela entra em **Modo de Edição**
  </Step>
  <Step title="Ajuste o que precisar">
    Altere o nome do item, a quantidade ou a unidade diretamente na linha — ou clique no ícone de lixeira pra remover um item
  </Step>
  <Step title='Adicione um item novo, se precisar'>
    Clique em **Adicionar item** e busque no catálogo ou digite um nome livre (informe quantidade, unidade e, se quiser, categoria e fornecedor)
  </Step>
  <Step title='Salve'>
    Clique em **Salvar**, ou **Cancelar** para descartar
  </Step>
</Steps>

## Listas de contagem: comparar com o estoque

Em listas de **Contagem** (e na parte de contagem de **Contagem + pedido**), a tela compara o que foi contado com o **estoque atual do local** configurado na lista:

- Cada item mostra o estoque atual, a quantidade contada e a diferença, com indicadores de **falta**, **sobra**, **conferido** e **sem vínculo com estoque**
- A data da contagem e o local aparecem no topo, com o aviso de que movimentações posteriores podem alterar o saldo
- **Só divergências** filtra os itens que não batem
- Itens já ajustados por esta lista ficam identificados

<Note>
  Se a lista de origem não tem local de estoque configurado, a contagem não é comparada. Configure em **Configurar lista → Estoque** ([veja como](/listas-e-cotacoes/configurar-lista)).
</Note>

### Ajustar o estoque a partir da contagem

Quem tem permissão de movimentar estoque (proprietário ou gerente — nunca colaborador) pode corrigir o saldo sem abrir uma contagem formal:

<Steps>
  <Step title="Em um item com diferença, clique em Ajustar estoque">
    Escolha o motivo: **Ajuste** (vale para falta e sobra), **Venda** ou **Desperdício** (só quando faltou — desperdício exige justificativa), **Saída de produção** ou **Transferir estoque** (informe o local de destino)
  </Step>
  <Step title="Ou ajuste vários de uma vez">
    Marque **Selecionar ajustáveis**, escolha o motivo de cada item (ou aplique um motivo a todas as faltas) e clique em **Ajustar selecionados**. Sobras sempre usam *Ajuste*
  </Step>
  <Step title="Revise e confirme">
    O sistema recalcula os saldos e recusa se o valor mudou desde que você abriu a tela. Cada item só pode ser resolvido **uma vez** por lista
  </Step>
</Steps>

<Warning>
  O ajuste em lote não é uma transação única: se um item falhar, os que já deram certo continuam registrados. A tela informa o resultado de cada item.
</Warning>

## Contagem + pedido

Quando a lista foi do tipo **Contagem + pedido**, o envio gerou duas listas ligadas. No topo, o link **Ver a contagem deste envio** (ou **o pedido deste envio**) leva para a outra.

<Card title="Veja também" icon="arrow-right" href="/relatorios-e-rendimento/historico-de-listas">
  Volte ao histórico completo de listas geradas
</Card>
