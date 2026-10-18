---
title: "Lançar produção"
description: "Como registrar quanto foi produzido e baixar automaticamente os ingredientes do estoque"
---

Quando a cozinha prepara um molho, uma massa ou qualquer item de **produção interna**, o estoque precisa refletir: os ingredientes **saem** e o item produzido **entra**. A tela **Lançar Produção** faz isso em dois toques.

<Info>
  Antes de usar, a receita precisa existir como [ficha técnica](/estoque/fichas-tecnicas) do tipo **Produção**, **publicada** e com o **Item gerado** definido. Se não houver nenhuma, a tela avisa: *"Nenhuma ficha técnica de produção ativa encontrada para esta loja"*.
</Info>

<Steps>
  <Step title="Abra Lançar produção">
    Pelo botão **Lançar produção** no topo de [Fichas Técnicas](/estoque/fichas-tecnicas), ou pelo atalho em **Minhas Tarefas**
  </Step>
  <Step title="Escolha a receita">
    Selecione em **Receita**
  </Step>
  <Step title="Informe quanto foi produzido">
    Em **Quero produzir**, digite a quantidade e a unidade e clique em **Calcular**. A tela lista os **Ingredientes para** a quantidade escolhida, com o fator de multiplicação (ex.: ×2,0)
  </Step>
  <Step title='Clique em "Executar e Baixar Estoque"'>
    O estoque dos ingredientes é baixado e o item final recebe a quantidade produzida
  </Step>
</Steps>

<Note>
  Colaboradores só veem esta tela se estiverem marcados em **Quem pode executar produção**, nas fichas técnicas.
</Note>

## Como se relaciona com o resto

- A baixa aparece em [Movimentações](/estoque/movimentacoes) com a referência de produção
- O custo do item produzido vem do custo dos ingredientes
- Na [Contagem](/estoque/fazer-uma-contagem), uma sobra ou falta também pode ser tratada como **Saída de produção**

<Card title="Próximo passo" icon="arrow-right" href="/estoque/etiquetas">
  Imprima a etiqueta de validade do produto
</Card>
