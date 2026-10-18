---
title: "Financeiro: vendas"
description: "Receita por canal, venda manual, importação de planilhas, mapeamento de produtos e regras de taxa"
---

A tela **Vendas** consolida a receita de todos os canais no mês escolhido. As vendas do CardápioWeb chegam sozinhas, e o PraComprar **sincroniza a cada 15 minutos**. Se quiser forçar, clique em **Sincronizar**.

A tela tem quatro abas.

## Vendas

Mostra a receita do mês em cartões e gráficos:

- **Receita bruta** e demais totais do período
- **Vendas por dia**, alternando entre *Receita* e *Pedidos*
- **Formas de pagamento**, **Vendas por canal**, **Cartões e vouchers por bandeira** e **Canal × pagamento**

Filtre por **Canal de venda**, **Tipo de pedido** (Entrega, Retirada, Consumo no local), **Pagamento**, **Bandeira**, **Integração** (CardápioWeb, Importação, Manual) e **Status** (Confirmada ou Cancelada).

Para lançar uma venda que não veio de nenhum canal, clique em **Venda manual** e preencha **Descrição**, **Valor (R$)**, **Data** e **Forma de pagamento**. Ao abrir uma venda, você pode **Recalcular taxas** ou **Cancelar venda**.

## Importar CSV/XLS

Para quem usa outro PDV ou ERP:

<Steps>
  <Step title="Escolha o arquivo">
    Envie uma planilha exportada do seu sistema (CSV, XLS ou XLSX)
  </Step>
  <Step title="Faça o De/Para de colunas">
    Indique quais colunas correspondem à data, à descrição e ao valor
  </Step>
  <Step title='Clique em "Pré-visualizar"'>
    Confira as linhas antes de gravar
  </Step>
  <Step title='Clique em "Importar"'>
    As vendas entram no mês. Cada importação aparece no **Histórico de importações** e pode ser **revertida por inteiro**
  </Step>
</Steps>

## Mapeamento de produtos

Para o **CMV** (custo da mercadoria vendida) ser calculado, cada produto vendido precisa estar ligado a um item do catálogo. A aba separa os **Pendentes** dos **Mapeamentos ativos**, ordenados pela receita. Comece pelos de cima.

Clique em um produto pendente, escolha o **Item do catálogo** (e opcionalmente uma ficha técnica) e, se quiser, informe um **Custo manual**, usado quando não há ficha nem estoque. Use **Remover mapeamento** para desfazer.

## Regras de taxa

Cadastre os percentuais descontados da venda bruta. Clique em **Nova regra** e escolha o **Tipo**:

- **Taxa de pagamento** — maquininha ou gateway
- **Comissão de canal** — marketplaces como o iFood

Informe o canal, a forma de pagamento e a bandeira. A regra **mais específica** (canal + forma + bandeira) vence a mais genérica.

<Card title="Próximo passo" icon="arrow-right" href="/financeiro/compras">
  Transforme compras recebidas em contas a pagar
</Card>
