---
title: "Vendas e pendências do CardápioWeb"
description: "Como acompanhar os pedidos recebidos do CardápioWeb e resolver o que ficou sem baixa de estoque"
---

<Note>
  Essa tela fica disponível apenas para estabelecimentos com a integração do CardápioWeb habilitada. Para conectar e configurar, veja a [Central de Integrações](/integracoes/central-de-integracoes).
</Note>

A tela de **Vendas e pendências** lista os pedidos que o CardápioWeb enviou ao PraComprar e mostra o que aconteceu com o estoque de cada um. Você a encontra no menu **Integrações → Vendas e pendências**.

<Steps>
  <Step title="Escolha o período">
    Use **Hoje**, **7 dias**, **30 dias** ou o ícone de período personalizado. Para achar um pedido específico, busque pelo ID
  </Step>
  <Step title="Veja os números por situação">
    Os cartões **Todos, Recebidos, Processados, Capturados, Agendados, Sem baixa, Atenção** e **Erros** funcionam como filtro
  </Step>
  <Step title="Resolva o que precisa de atenção">
    Abra os pedidos em **Sem baixa**, **Atenção** ou **Erro** e siga a causa indicada
  </Step>
  <Step title="Confira a tendência e os mais vendidos">
    Os painéis **Tendência** e **Mais vendidos** resumem o período. **Ver todos** abre o relatório completo de itens vendidos, filtrável por período e por nome ou código PDV
  </Step>
</Steps>

## O que cada situação significa

| Situação | O que quer dizer |
|---|---|
| **Processado** | O estoque foi baixado automaticamente |
| **Capturado** | Os itens foram registrados, mas o estoque não foi movimentado (modo diagnóstico) |
| **Agendado** | Pré-venda: a baixa acontece quando o CardápioWeb confirmar o envio |
| **Sem baixa** | O produto não tem ficha de venda nem modo de baixa. Vincule em [Produtos e vínculos](/integracoes/produtos-e-vinculos) para abater o estoque |
| **Atenção** | Há códigos PDV sem vínculo ou cancelamentos que precisam de decisão |
| **Erro** | O pedido falhou ao processar |

## Ações em pedidos com problema

- **Repetir em lote** — tenta reprocessar pedidos que falharam
- **Ignorar em lote** — marca como ignorados, sem afetar o estoque

## Comparar com a API

O painel lateral da API compara os pedidos do CardápioWeb com os recebidos pelo webhook, em janelas de 30 minutos até 24 horas. Use para descobrir se algum pedido se perdeu no caminho.

<Card title="Voltar ao início do Estoque" icon="arrow-right" href="/estoque/dashboard-de-estoque">
  Veja o resumo geral do seu estoque
</Card>
