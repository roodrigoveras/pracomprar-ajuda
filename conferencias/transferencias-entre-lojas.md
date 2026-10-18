---
title: "Transferências entre lojas"
description: "Como enviar estoque para outra loja, conferir o recebimento e tratar divergências"
---

Quando você tem mais de um estabelecimento, pode mandar produtos de um para outro direto pelo PraComprar. A transferência **entre estabelecimentos diferentes** sempre sai **em trânsito** e só entra no estoque do destino depois que alguém **confere o recebimento**.

<Info>
  Transferências **entre locais da mesma loja** (do depósito para a cozinha, por exemplo) são imediatas. Veja [Movimentações entre locais](/estoque/movimentacoes).
</Info>

## Enviar

<Steps>
  <Step title="Abra a Movimentação de estoque">
    Em **Estoque → Movimentações**, clique em movimentar
  </Step>
  <Step title="Defina origem e destino">
    Escolha o **Estabelecimento** e o **Local de estoque** de origem. No destino, selecione **Outro estabelecimento** e informe o estabelecimento, o local e **Quem vai receber no destino**
  </Step>
  <Step title="Adicione os produtos">
    Busque o produto — a tela mostra o **Disponível** na origem — e informe a **Quantidade**
  </Step>
  <Step title="Complete o lote">
    Em **Lote de transferência**, confira os itens. Se quiser, preencha **Observação** e **Solicitado por** (um colaborador ou "Outro / pessoa externa")
  </Step>
  <Step title="Envie">
    A saída é registrada na origem, e o recebimento fica pendente no destino
  </Step>
</Steps>

## Receber

Quem foi indicado como recebedor vê um aviso na tela inicial (**Minhas Tarefas**).

<Steps>
  <Step title="Abra a transferência">
    A tela **Transferência #número** mostra de qual loja e local ela veio
  </Step>
  <Step title="Confira o que chegou">
    Para cada item, o campo **Recebido** já vem com a quantidade enviada. Corrija se chegou diferente
  </Step>
  <Step title='Clique em "Confirmar recebimento"'>
    O estoque do destino é atualizado com o que foi recebido
  </Step>
</Steps>

## Divergências

Se chegou **menos** do que foi enviado, o sistema abre uma divergência em **Divergências de Transferência** ("Recebimentos com quantidade menor que a enviada"). Para cada uma, escolha:

- **Devolver à origem** — a diferença volta ao estoque de quem enviou
- **Baixar como perda** — registra a diferença como perda, com auditoria
- **Aceitar diferença** — dá o assunto por encerrado

Você pode escrever uma **Observação** antes de decidir.

<Card title="Próximo passo" icon="arrow-right" href="/estoque/movimentacoes">
  Veja a movimentação de estoque em detalhes
</Card>
