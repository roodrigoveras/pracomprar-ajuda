---
title: "Visualização de estoque"
description: "Como consultar o saldo por produto e local e fazer ajustes, saídas e transferências rápidas"
---

A aba **Estoque** mostra o saldo de cada produto por local, com ações rápidas em cada linha — sem precisar abrir uma contagem completa.

## Os números no topo

Quatro cartões resumem o recorte atual: **Itens**, **Valor total**, **Abaixo do mínimo** e **Locais ativos**.

<Steps>
  <Step title="Acesse a aba Estoque">
    No menu, entre em **Estoque** e clique na aba **Estoque**
  </Step>
  <Step title="Busque e filtre">
    Use **Buscar produto…**, o filtro **Todas as categorias**, o filtro de **local** (**Todos os locais** soma tudo) e a chave **Zerados** para esconder ou mostrar os itens sem saldo
  </Step>
  <Step title="Leia a tabela">
    Cada linha traz **Produto, Quantidade, Custo un., Total, Validade** e **Nível** (situação em relação ao estoque mínimo). Com *Todos os locais* ligado, aparece também a coluna **Local**
  </Step>
  <Step title="Exporte, se precisar">
    No botão de exportar, escolha **Exportar CSV** ou **Exportar PDF**
  </Step>
</Steps>

## Ações em cada produto

<CardGroup cols={2}>
  <Card title="Histórico" icon="clock-rotate-left">
    Painel com todas as movimentações daquele item ao longo do tempo
  </Card>
  <Card title="Transferir" icon="right-left">
    Move quantidade para outro local ou estabelecimento (**De (Origem)**, **Para (Destino)**, **Quantidade**, **Observações**)
  </Card>
  <Card title="Saída" icon="arrow-up-from-bracket">
    Registra uma saída manual do tipo **Venda, Produção, Consumo** ou **Perda**, com quantidade e observação
  </Card>
  <Card title="Ajustar estoque" icon="sliders">
    Corrige a quantidade registrada quando ela não bate com a realidade
  </Card>
</CardGroup>

O menu **⋯** da linha também permite **Remover deste local**.

## Ações da aba

- **Adicionar ao estoque** — abre o [lançamento manual](/estoque/adicionar-estoque-manual)
- **Movimentações** — abre o [histórico de movimentações](/estoque/movimentacoes)
- **⋯ → Sincronizar catálogo** — coloca no estoque (com quantidade zero) os itens do catálogo que ainda não estão nele, como os cadastrados recentemente ou importados em lote
- **⋯ → Zerar estoque da loja** — limpa saldos, movimentações e contagens da loja. Só aparece para quem tem permissão e **não pode ser desfeito**

<Warning>
  Use "Zerar estoque da loja" apenas para recomeçar do zero, como depois de testes. Ele apaga o histórico de movimentações e contagens do estabelecimento.
</Warning>

<Card title="Próximo passo" icon="arrow-right" href="/estoque/locais-de-estoque">
  Configure seus locais de estoque
</Card>
