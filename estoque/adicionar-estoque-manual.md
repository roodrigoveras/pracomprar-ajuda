---
title: "Adicionar ao estoque (manual)"
description: "Como lançar uma entrada, definir o saldo ou dar saída para produção sem passar por conferência ou NF-e"
---

Use **Adicionar ao estoque** quando precisar lançar um movimento que não veio de uma conferência de pedido ou de uma NF-e — por exemplo, o saldo inicial de um produto, uma compra feita fora do PraComprar ou uma saída para produção.

<Steps>
  <Step title='Clique em "Adicionar ao estoque"'>
    O botão fica no topo da aba **Estoque** (e também no **Dashboard** do estoque). Abre uma tela própria; use a seta para voltar quando terminar
  </Step>
  <Step title="Escolha o produto e o local">
    Em **Produto e local**, digite o nome do produto e selecione o **Local** que vai receber (ou perder) a quantidade
  </Step>
  <Step title="Escolha o tipo de operação">
    - **Adicionar** — soma ao saldo atual
    - **Definir quantidade** — substitui o saldo pelo valor informado
    - **Saída para produção** — desconta do saldo
  </Step>
  <Step title="Informe a quantidade e o custo">
    Digite a **Quantidade**. O **Custo unitário** é opcional e mantém o valor do estoque atualizado
  </Step>
  <Step title="Registre o motivo">
    Em **Observações**, anote o motivo do ajuste, o número da nota fiscal etc. Isso ajuda a rastrear a origem do lançamento depois
  </Step>
  <Step title='Clique em "Adicionar ao Estoque"'>
    O saldo é atualizado imediatamente e o lançamento aparece no histórico de [Movimentações](/estoque/movimentacoes). **Limpar** descarta o formulário
  </Step>
</Steps>

<Tip>
  Para dar entrada em várias notas de uma vez, use [Importar NF-e](/estoque/importar-nfe). Para corrigir o saldo depois de contar, prefira [fazer uma contagem](/estoque/fazer-uma-contagem), que deixa a trilha de aprovação.
</Tip>

<Card title="Próximo passo" icon="arrow-right" href="/estoque/importar-nfe">
  Importe notas fiscais para lançar entradas em lote
</Card>
