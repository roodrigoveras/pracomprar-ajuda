---
title: "Integração com CardápioWeb"
description: "Como conectar o CardápioWeb para sincronizar pedidos e baixar o estoque automaticamente"
---

<Note>
  Essa aba fica disponível apenas para estabelecimentos com a integração de vendas habilitada.
</Note>

O Integrador de Vendas conecta o PraComprar ao CardápioWeb, sincronizando os pedidos de venda e dando baixa automática no estoque conforme os produtos são vendidos.

<Steps>
  <Step title="Acesse o Integrador de Vendas">
    Em **Estoque → Integrador**, a aba **CardápioWeb** já aparece ativa
  </Step>
  <Step title="Configure a conexão com a API">
    Abra o painel de configuração e informe a chave de API do CardápioWeb para conectar sua conta
  </Step>
  <Step title="Sincronize os pedidos">
    Use **Sincronizar pedidos faltantes agora** para trazer pedidos que ainda não foram processados
  </Step>
  <Step title="Acompanhe a lista de pedidos">
    Filtre por período (Hoje, 7 dias, 30 dias ou período customizado) ou busque por ID do pedido
  </Step>
</Steps>

## Relatório de Itens Vendidos

Além da lista de pedidos, essa tela mostra um relatório com o total vendido por produto, filtrando por período (hoje, 7/30 dias, este mês, mês passado) e buscando por nome ou código PDV.

## Ações em pedidos com problema

- **Repetir em lote** — tenta reprocessar pedidos que falharam
- **Ignorar em lote** — marca pedidos com problema como ignorados, sem afetar o estoque

<Card title="Voltar ao início do Estoque" icon="arrow-right" href="/estoque/dashboard-de-estoque">
  Veja o resumo geral do seu estoque
</Card>
