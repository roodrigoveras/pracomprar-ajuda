---
title: "Preencher e enviar um pedido"
description: "Como ajustar as quantidades da sua lista antes de enviar o pedido para os fornecedores"
---

Depois de [criar a lista](/listas-e-cotacoes/criar-lista-de-compras), esse é o passo em que você define quanto pedir de cada item, categoria por categoria.

<Steps>
  <Step title="Abra a lista">
    Em **Minhas Listas** (ou pela tela **Minhas Tarefas**), clique na lista que você quer preencher
  </Step>
  <Step title="Navegue pelas categorias">
    Os itens ficam agrupados por categoria (ex: Bebida, Cozinha, Embalagem, Freezer) — cada uma mostra quantos itens ela tem e pode ser expandida ou recolhida
  </Step>
  <Step title="Ajuste a quantidade de cada item">
    Use os botões **−** e **+**, ou digite direto, pra definir quanto pedir. Ao lado de cada item aparece o **Ideal** cadastrado no catálogo (a referência de quanto você normalmente mantém em estoque), pra te ajudar a decidir a quantidade
  </Step>
  <Step title="Salve como rascunho, se precisar continuar depois">
    Clique em **Salvar rascunho** — a lista fica salva com o que você já preencheu, sem enviar nada ainda
  </Step>
  <Step title='Envie quando terminar'>
    O botão muda conforme o tipo da lista: **Enviar pedido**, **Enviar contagem** ou **Enviar contagem e pedido**
  </Step>
</Steps>

## Confirmando o envio

Depois de clicar em Enviar Pedido, você entra numa tela de confirmação antes do envio de fato sair:

<Steps>
  <Step title="Confira o resumo">
    No topo aparecem 4 números: **Fornecedores**, **Itens para enviar**, **Sem WhatsApp** e **Sem fornecedor** — esses dois últimos avisam se algum item ficaria de fora do envio
  </Step>
  <Step title="Revise os fornecedores agrupados">
    Os itens aparecem agrupados por **fornecedor principal** de cada um, com a quantidade definida na etapa anterior
  </Step>
  <Step title="Desmarque o que não quiser enviar agora (opcional)">
    Cada fornecedor e cada item têm checkbox próprio — desmarque o que não for enviar nessa rodada
  </Step>
  <Step title='Clique em "Enviar Pedido"'>
    O PraComprar dispara o pedido direto pelo WhatsApp de cada fornecedor principal, sem passar por cotação — ideal quando você já sabe de quem vai comprar
  </Step>
</Steps>

<Tip>
  Se você quer comparar preços entre fornecedores antes de decidir, use [Gerar uma cotação](/listas-e-cotacoes/gerar-cotacao) em vez do envio direto.
</Tip>

## Lista Contagem + pedido

Cada item tem **dois contadores independentes**, lado a lado: um de **Contagem** (o que há no estoque) e um de **Pedido** (o que comprar), cada um na sua unidade (ex.: `cx / un`). Ao enviar, o PraComprar gera duas listas ligadas: uma de contagem e uma de pedido.

## Como a lista chega ao destinatário

Depende do **método de envio** configurado (veja [Configurar lista](/listas-e-cotacoes/configurar-lista)): **WhatsApp** abre a conversa com a listagem completa, **Bot PraComprar** envia a listagem aos destinatários e **Só avisar** manda apenas um aviso com o link para abrir a lista gerada.

<Note>
  Se a lista for do tipo **Contagem** (em vez de Pedido), o botão muda para **Enviar Contagem** — mesma tela, mas usada pra registrar quantidades contadas em vez de quantidades a comprar.
</Note>

<Card title="Próximo passo" icon="arrow-right" href="/relatorios-e-rendimento/detalhes-da-lista-gerada">
  Veja e edite a lista depois de enviada
</Card>
