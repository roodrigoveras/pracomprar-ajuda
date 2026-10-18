---
title: "Integração com Saipos"
description: "Como solicitar, conectar e conferir vendas da Saipos no PraComprar"
---

A integração com a **Saipos** permite consultar vendas e relacionar os produtos vendidos às fichas técnicas, itens e combos do PraComprar. A sincronização é periódica, e algumas vendas podem aparecer com atraso.

<Note>A integração precisa estar liberada para o estabelecimento. A configuração é feita para cada loja.</Note>

## Solicitar a integração

Acesse **Integrações > Explorar integrações**, localize **Saipos** e clique em **Solicitar ativação**. Se já estiver liberada, escolha **Gerenciar conexão**.

## Configurar a conexão

<Steps>
  <Step title="Obtenha os dados da Saipos">
    Solicite à Saipos o acesso à **API de Dados** da loja e identifique o **código da loja** correspondente.
  </Step>
  <Step title="Abra Conexão">
    Na área **Saipos** do PraComprar, entre na aba **Conexão**.
  </Step>
  <Step title="Preencha os campos">
    Informe o **Token** e o **Código da loja** e clique em **Conectar**.
  </Step>
  <Step title="Confira a sincronização">
    Verifique a situação da conexão e utilize **Sincronizar agora**, quando necessário.
  </Step>
  <Step title="Revise os vínculos e as regras">
    Acesse **Produtos e vínculos** para associar os produtos vendidos. Confira a aba **Regras** antes de ativar a movimentação automática do estoque.
  </Step>
</Steps>

## Consultar vendas e pendências

Na aba **Vendas**, acompanhe os registros importados. Na aba **Pendências**, verifique situações que exigem revisão. Alguns produtos só aparecerão para vinculação depois que houver vendas registradas na Saipos.

<Warning>Antes de habilitar a baixa automática, confira se o estoque já não está sendo movimentado por outra integração ou configuração.</Warning>

<Card title="Voltar à Central de Integrações" icon="arrow-left" href="/integracoes/central-de-integracoes">Veja as outras plataformas.</Card>
