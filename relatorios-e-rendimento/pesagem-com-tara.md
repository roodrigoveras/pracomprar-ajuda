---
title: "Pesagem com Tara"
description: "Como estimar o que resta de um produto pesando a embalagem, com tolerância e aprovação do gestor"
---

A Pesagem com Tara descobre quanto ainda resta de um produto a granel ou em sachês sem contar unidade por unidade. Basta pesar a embalagem na balança.

Ela está na aba **Pesagem com tara** de [Transformação e Rendimentos](/relatorios-e-rendimento/transformacao-e-rendimentos) e também numa página própria, com o título **Pesagem com tara** (escolha o modelo, informe o peso da embalagem e registre o que sobrou).

## Cadastrando um modelo de tara

<Steps>
  <Step title='Clique em "Novo Modelo de Tara"'>
    Na seção **Modelos de tara**
  </Step>
  <Step title="Preencha os dados">
    - **Nome do modelo** — ex: *Sachê — Ketchup*
    - **Item do catálogo** (opcional) — vincula o resultado ao item do estoque
    - **Peso total lacrado** — embalagem cheia, ex: *1.350 g*
    - **Tara da embalagem** — embalagem vazia, ex: *205 g*
    - **Qtd. na embalagem cheia** — quantas unidades ela contém
    - **Unidade do resultado**
    - **Tolerância para auto-aprovação** — variação máxima aceita sem precisar do gestor
  </Step>
  <Step title="Salve">
    O sistema mostra o **peso por unidade** calculado
  </Step>
</Steps>

## Usando a calculadora

<Steps>
  <Step title="Selecione o estabelecimento e o modelo">
    A tela mostra **Peso cheio**, **Tara** e **Por unidade**
  </Step>
  <Step title="Informe o peso atual da embalagem">
    Pese a embalagem com o produto restante e digite o valor
  </Step>
  <Step title="Clique em Calcular">
    O sistema desconta a tara, divide pelo peso por unidade e mostra a **Quantidade estimada restante**, junto com o **Estoque atual** e a **Variação**
  </Step>
  <Step title="Observação (opcional)">
    Ex: *Caixa aberta, gaveta 3*
  </Step>
  <Step title="Clique em Registrar no estoque">
    O resultado entra como uma contagem de estoque
  </Step>
</Steps>

## Auto-aprovação

| Situação | O que acontece |
|---|---|
| Variação **dentro da tolerância** | O estoque é atualizado na hora |
| Variação **acima da tolerância** | O registro fica **aguardando aprovação do gestor** |
| Modelo **sem tolerância** | Sempre vai para aprovação |

<Info>
  Na lista de modelos, o selo mostra a tolerância de cada um (por exemplo, ±5 un) ou **Sem auto-aprovação**.
</Info>

<Card title="Voltar" icon="arrow-right" href="/relatorios-e-rendimento/transformacao-e-rendimentos">
  Veja como lançar produção e rendimento
</Card>
