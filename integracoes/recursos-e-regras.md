---
title: "Recursos e regras"
description: "Como escolher se e quando as vendas do CardápioWeb baixam o estoque"
---

A aba **Recursos e regras** da [Central de Integrações](/integracoes/central-de-integracoes) controla o que acontece com o estoque quando uma venda chega. O **recebimento** das vendas fica ativo enquanto a conexão estiver habilitada; aqui você decide o efeito no estoque.

<Steps>
  <Step title='Ative "Baixar estoque automaticamente"'>
    Cada venda recebida passa a consumir as fichas, itens e composições vinculados. Desligado, as vendas são apenas registradas
  </Step>
  <Step title="Escolha o momento da baixa">
    - **No despacho ou conclusão** — baixa quando o pedido sai ou é concluído. É a opção **recomendada**
    - **Na criação do pedido** — baixa assim que o pedido é recebido
  </Step>
  <Step title='Clique em "Salvar"'>
    A regra vale para os **eventos recebidos depois de salvar**. Os já recebidos, inclusive os pendentes, mantêm a regra anterior
  </Step>
</Steps>

## Histórico de alterações

Cada mudança fica registrada no **Histórico de alterações**, com quem alterou e quando. A primeira versão guarda a configuração que existia antes dessas regras.

<Tip>
  Prefira **No despacho ou conclusão**: pedidos cancelados antes de sair não baixam estoque indevidamente.
</Tip>

<Card title="Próximo passo" icon="arrow-right" href="/estoque/integracao-cardapioweb">
  Acompanhe as vendas recebidas e as pendências
</Card>
