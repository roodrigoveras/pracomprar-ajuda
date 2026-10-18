---
title: "Meus itens"
description: "Como visualizar, filtrar, editar, classificar e excluir os itens do seu catálogo"
---

A aba **Meus Itens**, dentro de **Gestão de Itens**, é onde ficam todos os produtos cadastrados no seu catálogo. É a primeira aba que abre quando você entra no módulo.

## Vídeo: conheça a Gestão de Itens

Assista ao vídeo para conhecer o módulo antes de seguir o passo a passo.

<video controls preload="metadata" src="/videos/gestao-de-itens.mp4"></video>

<Note>
  Alguns recursos podem variar conforme o perfil de acesso e os módulos habilitados na sua conta.
</Note>

<Steps>
  <Step title="Acesse Gestão de Itens">
    No menu, entre em **Gestão de Itens** — a aba **Meus Itens** já abre selecionada
  </Step>
  <Step title="Escolha a classificação">
    Os botões no topo separam os itens por origem, cada um com a contagem ao lado:
    - **Todos**
    - **Compra** — matéria-prima comprada de fornecedores
    - **Produção interna** — itens gerados dentro da casa (ex: filé de peixe)
    - **Produto final** — itens prontos para venda
    - **Sem classificação** — itens que ainda não têm origem definida
  </Step>
  <Step title="Busque e filtre">
    Digite no campo **Buscar item...** e combine com os filtros:
    - **Categoria** e **Fornecedor** — menus que permitem marcar uma ou mais opções (incluindo **Sem categoria** e **Sem fornecedor**)
    - **Sem fator** — itens com unidade de compra diferente da unidade de estoque e sem fator de conversão (bloqueiam a entrada de estoque)
    - **Sem modo de venda** — itens com código PDV mas sem modo de baixa definido (as vendas geram pendência)
    - **Limpar** — remove todos os filtros de uma vez
  </Step>
  <Step title='Abra o item'>
    Clique no item para abrir a tela de edição, com 6 ou 7 abas — veja o detalhe em [Editar item](/catalogo/editar-item)
  </Step>
</Steps>

<Info>
  Os filtros **Sem fator** e **Sem modo de venda** só aparecem quando existe pelo menos um item nessa situação. São o caminho mais rápido para corrigir pendências que travam o [estoque](/estoque/visualizacao-de-estoque) e as [vendas do CardápioWeb](/estoque/integracao-cardapioweb).
</Info>

## Seleção em massa

Clique em **Classificar em massa** para marcar vários itens de uma vez. Uma barra aparece na parte de baixo da tela com o total selecionado e estas ações:

| Botão | O que faz |
|---|---|
| **Todos visíveis** | Marca todos os itens que estão aparecendo com o filtro atual |
| **Classificar (n)** | Abre a janela para aplicar uma origem a todos: Sem classificação, Compra (matéria-prima), Produção interna ou Produto final |
| **Excluir (n)** | Exclui os itens selecionados |
| **Cancelar** | Sai do modo de seleção |

<Warning>
  Excluir é definitivo. Confira a seleção antes de confirmar.
</Warning>

<Tip>
  Cada item na lista mostra suas categorias e fornecedores (ou os avisos **Sem categoria** e **Sem fornecedor**). Dá para ver o essencial sem abrir a edição.
</Tip>

<Card title="Próximo passo" icon="arrow-right" href="/catalogo/categorias">
  Organize seus itens por categoria
</Card>
