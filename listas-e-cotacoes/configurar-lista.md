---
title: "Configurar lista"
description: "Tipo, método de envio, exibição, ordem dos itens, local de estoque e estabelecimento"
---

O ícone de engrenagem (**Configurar**) em **Minhas Listas** abre um painel em seções com as regras daquela lista. Clique em **Salvar** ao terminar.

## Tipo e envio

<Steps>
  <Step title="Escolha o tipo da lista">
    **Pedido**, **Contagem** ou **Contagem + pedido** (veja [Criar uma lista](/listas-e-cotacoes/criar-lista-de-compras))
  </Step>
  <Step title="Escolha como a lista é enviada">
    - **WhatsApp** — abre o WhatsApp de quem gerou a lista, com a listagem completa
    - **Bot PraComprar** — o bot envia a listagem completa aos destinatários que você marcar
    - **Só avisar** — o bot avisa apenas que a lista foi gerada (loja, lista, quem gerou, quando e quantidade de itens) e manda um **link curto** para abrir a lista no sistema. A lista continua salva no histórico
  </Step>
  <Step title="Marque os destinatários">
    Nos métodos **Bot PraComprar** e **Só avisar**, selecione quem recebe a mensagem
  </Step>
</Steps>

<Info>
  Em listas **Contagem + pedido** com **Só avisar**, sai um aviso único com os dois totais (contagem e pedido).
</Info>

## Exibição

- **Quantidade ideal** — mostra a quantidade-alvo de cada item
- **Estoque atual** — mostra o saldo do estoque ao lado do ideal (requer o módulo de Estoque)
- **Escolher categorias visíveis** — por padrão o item aparece em todas as suas categorias. Ao ativar, marque quais aparecem; os itens que ficarem fora vão para **Outros**
- **Ordem dos itens** — **Manual** (você arrasta) ou **Alfabética**. Em alfabética o arrastar fica desligado, mas a ordem manual continua salva e volta ao escolher Manual

<Tip>
  "Ideal" e "Estoque" aparecem convertidos para a unidade em que a linha é preenchida (pedido ou contagem), então ninguém precisa fazer conta de caixa para unidade.
</Tip>

## Estoque

Aparece em listas de **Contagem**, **Contagem + pedido** ou com **Estoque atual** ligado. Escolha o **Local de estoque**:

- **Todos os locais (somado)** — o estoque atual soma todos os locais
- Um local específico — o estoque atual mostra só ele, e esse local também é o usado para [ajustar o estoque a partir da contagem](/relatorios-e-rendimento/comparar-contagens)

## Estabelecimento

Mostra a loja da lista e oferece **Duplicar lista** e **Mover para outra loja**.

<Card title="Veja também" icon="arrow-right" href="/listas-e-cotacoes/usuarios-da-lista">
  Defina quem da equipe acessa essa lista
</Card>
