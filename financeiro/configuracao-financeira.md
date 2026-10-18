---
title: "Financeiro: configuração"
description: "Preferências, plano de contas, carteiras e prazos de recebimento"
---

A tela **Financeiro → Configuração** é o ponto de partida: é aqui que você define como o módulo calcula o custo, organiza as categorias e prevê o dinheiro das vendas. Ela tem quatro abas.

## Preferências

<Steps>
  <Step title="Escolha o método de custeio (CMV)">
    - **Custo médio móvel** (padrão) — o custo de cada item é a média das compras
    - **Última compra** — usa sempre o preço da compra mais recente
  </Step>
  <Step title="Escolha o regime do DRE">
    - **Competência** (padrão) — o resultado considera o mês em que a venda ou a despesa aconteceu
    - **Caixa** — considera o mês em que o dinheiro entrou ou saiu
  </Step>
  <Step title="Defina a conta padrão de recebimento">
    A carteira que recebe o dinheiro das vendas quando você não escolhe outra
  </Step>
  <Step title='Clique em "Salvar preferências"'>
    A mudança vale para os próximos cálculos
  </Step>
</Steps>

## Plano de Contas

São as categorias que classificam receitas e despesas. O PraComprar cria um plano padrão no primeiro acesso, e você pode ajustar:

- **Nova categoria** — informe **Nome**, **Natureza** (Despesa ou Receita), **Comportamento** (Variável ou Fixo) e o **Grupo no DRE**
- **Restaurar padrão** — recria as categorias originais
- **Ativa** — desative categorias que você não usa mais

O **Grupo no DRE** define em qual linha do resultado a categoria aparece: *Receita bruta, Deduções, CMV, Pessoal, Operacional, Perdas, Financeiro* ou *Não operacional*.

## Contas / Carteiras

Cadastre onde o dinheiro fica: **Nova conta** com **Nome** (ex.: "Caixa da loja", "Conta do banco"), **Tipo** (Caixa, Banco, Cartão, Aplicação ou Outro) e **Saldo inicial**. A opção **Considerar no fluxo de caixa consolidado** inclui ou exclui a carteira da projeção.

## Prazos de recebimento

Define **quando** o dinheiro de cada venda cai na conta. Clique em **Nova regra** e informe:

- **Nome** da regra e a **Forma de pagamento** (Dinheiro, Crédito, Pix, pago pelo iFood etc.)
- **Canal da venda**, **Integração de origem** e **Quem processa o pagamento** (online pela plataforma, ou presencial)
- **Bandeira**, quando fizer diferença
- **Calendário**: *Dias após a venda* (D+N, em dias corridos) ou *Janela semanal* (fecha numa semana e paga em outro dia)
- **Vigência inicial** e **final**, e se a regra está ativa

Depois de criar ou mudar regras, use **Atualizar previsões existentes** para recalcular as vendas já registradas.

<Note>
  O prazo preenche a **previsão** do recebimento. As taxas da maquininha ou da plataforma são cadastradas em [Vendas → Regras de taxa](/financeiro/vendas).
</Note>

<Card title="Próximo passo" icon="arrow-right" href="/financeiro/lancamentos">
  Registre contas a pagar e a receber
</Card>
