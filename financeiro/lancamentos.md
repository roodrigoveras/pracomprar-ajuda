---
title: "Financeiro: lançamentos"
description: "Como registrar contas a pagar e a receber, baixar pagamentos e criar recorrências"
---

**Lançamentos** é o livro das contas a pagar e a receber do estabelecimento. A receita das vendas entra sozinha; aqui você registra o que não vem de outro módulo, como aluguel, energia e salários.

## Os números no topo

Quatro cartões resumem o período e funcionam como filtro ao clicar: **A receber**, **A pagar**, **Recebido / pago** e **Saldo previsto**.

## Registrar um lançamento

<Steps>
  <Step title='Clique em "Novo lançamento"'>
    Escolha entre **Manual** e **Por NF-e**
  </Step>
  <Step title="Preencha os dados (modo Manual)">
    - **Natureza** — Despesa ou Receita
    - **Descrição** e **Valor (R$)**
    - **Vencimento** e **Competência** (o mês a que a conta pertence)
    - **Categoria** e **Conta**
    - **Já pago / recebido nesta data** — marque se a conta já foi quitada
    - **Observação**, se precisar
  </Step>
  <Step title='Clique em "Salvar"'>
    O lançamento aparece na lista com o status correspondente
  </Step>
</Steps>

### Por NF-e

Use para notas que **não passaram** pela importação do estoque. Bipe ou cole a **chave de acesso** (44 dígitos), ou digite o número da nota ou o fornecedor, e clique em **Buscar NF-e**. A compra entra em [Financeiro → Compras](/financeiro/compras) com o total da nota, e as parcelas são sugeridas pelas duplicatas do XML. O estoque **não** é movimentado.

## Filtrar a lista

Use **Busca** (pela descrição), **Natureza**, **Status** e **Categoria**. Os status são: *Previsto, Pendente, Parcial, Liquidado* e *Cancelado*. **Limpar** zera os filtros.

## Liquidar (dar baixa)

Ao pagar ou receber uma conta, abra **Liquidar** e informe a **Data**, a **Conta** (carteira) e o **Valor**. Deixe o valor igual ao da conta para quitar tudo; um valor menor registra o pagamento como **Parcial**.

## Recorrências

Na aba **Recorrências**, clique em **Nova recorrência** para despesas e receitas que se repetem (ex.: *Aluguel*). Informe a natureza, a descrição, o valor e a **Periodicidade**: *Mensal, Semanal, Quinzenal* ou *Bimestral*. O sistema cria os lançamentos automaticamente a cada ciclo.

<Tip>
  Cadastre as despesas fixas como recorrências uma única vez. Elas alimentam a [projeção do fluxo de caixa](/financeiro/fluxo-de-caixa) mesmo antes de o mês começar.
</Tip>

<Card title="Próximo passo" icon="arrow-right" href="/financeiro/vendas">
  Acompanhe a receita das vendas
</Card>
