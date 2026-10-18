---
title: "Transformação e Rendimentos"
description: "Listas, campos de medição, modelos com meta, lançamentos, integração com estoque e ranking da equipe"
---

O módulo **Transformação e Rendimentos** mede o aproveitamento real de um produto que passa por processamento. Exemplo: quanto de filé você obtém de um peixe inteiro, descontando aparas e pele. Ele tem quatro abas: **Listas**, **Modelos**, **Relatórios** e **Pesagem com tara**.

## Modelos de rendimento

Um modelo define a **meta mínima de aproveitamento** de um processo (ex: *58,50%*).

<Steps>
  <Step title="Abra a aba Modelos">
    Em **Transformação e Rendimentos**, clique em **Modelos**
  </Step>
  <Step title='Clique em "Novo modelo"'>
    Dê um nome (ex: *Processamento de salmão*) e informe a **Meta mínima de aproveitamento**
  </Step>
  <Step title="Associe aos itens">
    No cadastro do item, o campo **Modelo de rendimento** liga o item ao modelo (veja [Editar item](/catalogo/editar-item))
  </Step>
</Steps>

## Listas de rendimento

Uma lista agrupa os itens que a equipe vai pesar (ex: o setor de peixaria).

<Steps>
  <Step title='Crie a lista'>
    Na aba **Listas**, clique em **Nova lista** e dê um nome
  </Step>
  <Step title="Abra a gestão da lista">
    Na lista, use o ícone de gerir itens, campos e permissões
  </Step>
  <Step title='Adicione itens'>
    Em **Adicionar item**, escolha o produto do catálogo. A coluna **Modelo** mostra a meta associada
  </Step>
  <Step title="Defina os campos de medição">
    No botão **Campos** do item, crie o que a equipe vai pesar. Cada campo tem nome, tipo e unidade
  </Step>
  <Step title="Escolha quem pode lançar">
    Em **Quem pode lançar**, marque os colaboradores com acesso à lista e salve
  </Step>
</Steps>

### Tipos de campo

| Tipo | Para que serve | Exemplo |
|---|---|---|
| **Entrada (peso total)** | Peso antes de processar | Peixe inteiro |
| **Aproveitamento** | O que vira produto utilizável | Filé |
| **Perda** | O que é descartado | Aparas, pele |

O rendimento é calculado como **aproveitamento ÷ entrada**. As perdas ajudam a explicar a diferença.

## Integração com estoque

No botão **Estoque** do item, você diz qual item do estoque corresponde a cada campo e o **local padrão**. Com a opção **Sugerir** ligada, ao lançar o rendimento o sistema propõe as movimentações: a entrada sai do estoque e o aproveitamento entra.

<Note>
  Se algum campo ficar sem local configurado, o sistema avisa que ele não será movimentado. Configure em **Gerir lista → Estoque**.
</Note>

## Lançando o rendimento

<Steps>
  <Step title="Abra a lista e o item">
    Quem tem permissão escolhe a lista no menu e abre o item processado
  </Step>
  <Step title="Informe a data e os pesos">
    Preencha a **Data de produção** e cada campo de medição
  </Step>
  <Step title="Lance em nome de outra pessoa (opcional)">
    Em **Lançar em nome de**, escolha um funcionário. O padrão é **Eu mesmo**
  </Step>
  <Step title="Clique em Lançar pesagem">
    Se houver mapeamento de estoque, abre a janela **Movimentações de estoque**, com entradas e saídas sugeridas. Use **Confirmar** para aplicar ou **Ignorar** para não movimentar
  </Step>
</Steps>

<Tip>
  Depois de confirmar, o link **Ver no Estoque** leva às [movimentações](/estoque/movimentacoes) geradas.
</Tip>

## Relatórios

Na aba **Relatórios**, escolha um **item** e um **período** (Últimos 7 dias, Últimos 15 dias, Este mês, Mês passado ou Todo o período). A tela mostra:

- **Meta**, **Média da equipe**, **Lançamentos** e quantos ficaram **Na meta**
- **Ranking da equipe** — rendimento médio por pessoa, com a marca da meta na barra
- **Tendência ao longo do tempo** — gráfico do rendimento no período

<Tip>
  Quanto mais lançamentos de um produto, mais confiável fica o rendimento médio. Use-o para precificar pratos e porções.
</Tip>

<Card title="Próximo passo" icon="arrow-right" href="/relatorios-e-rendimento/pesagem-com-tara">
  Use a pesagem com tara para estimar o que resta em estoque
</Card>
