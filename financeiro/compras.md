---
title: "Financeiro: compras e contas a pagar"
description: "Como transformar notas fiscais e conferências em contas a pagar com parcelas e vencimentos"
---

Quando você recebe mercadoria, o PraComprar já sabe **o que** chegou e **quanto** custou. A tela **Financeiro → Compras** pergunta só o que falta: **quando** você vai pagar.

## De onde vêm as compras

Duas origens alimentam a lista (filtro **Origem**):

- **NF-es de entrada** — notas já recebidas no estoque, inclusive as antigas, entram automaticamente no mês da entrada
- **Conferência** — conferências finalizadas que ainda não viraram compra. O contador mostra quantas estão esperando, e **Sincronizar todas** traz todas de uma vez

Conferências que batem exatamente com uma NF-e são mescladas à nota; diferenças ficam para você revisar.

## Gerar as contas a pagar

<Steps>
  <Step title="Abra o documento de compra">
    Clique na compra da lista. O painel mostra os dados da nota ou da conferência
  </Step>
  <Step title="Escolha o fornecedor, a conta e o tratamento">
    - **Fornecedor** e **Conta prevista para pagamento**
    - **Tratamento da compra**: *Estoque* (o consumo compõe o CMV) ou *Despesa operacional* (escolha também a **Categoria operacional**)
  </Step>
  <Step title="Defina as parcelas">
    Use **Adicionar parcela** e informe vencimentos e valores conforme o boleto, a NF-e ou o combinado com o fornecedor. A soma das parcelas precisa bater com o valor da compra
  </Step>
  <Step title='Clique em "Gerar contas a pagar"'>
    As parcelas aparecem em [Lançamentos](/financeiro/lancamentos). Gerar as contas **não** registra pagamento
  </Step>
</Steps>

### Várias compras de uma vez

Marque as compras completas na lista e preencha **Primeiro vencimento**, **Parcelas**, **Intervalo em dias**, **Tratamento** e **Conta prevista**. Clique em **Revisar lote** e, depois de conferir, **Gerar lote revisado**.

### Buscar NF-es já importadas

O botão **Buscar NF-es já importadas** lista as notas recebidas no estoque. Pesquise por fornecedor, número ou chave e, se quiser, limite pelo mês da entrada. Se uma conferência ainda não tem nota, use **Vincular** informando a chave de 44 dígitos.

## Desfazer

No documento da compra:

- **Cancelar parcelas não pagas** — cancela o que ainda está em aberto
- **Estornar pagamentos registrados** — desfaz baixas já feitas

<Warning>
  Itens sem quantidade efetivamente recebida ou sem preço aparecem como pendência, e o valor da compra pode ficar parcial. Revise a conferência antes de gerar as contas.
</Warning>

<Card title="Próximo passo" icon="arrow-right" href="/financeiro/recebimentos">
  Concilie o dinheiro que entra
</Card>
