---
title: "Adicionar item ao catálogo"
description: "Como cadastrar um novo produto no seu catálogo"
---

<Note>
  No menu, esse módulo aparece como **Gestão de Itens**. É onde ficam o catálogo de produtos, as categorias e os fornecedores.
</Note>

Assista ao [vídeo de Gestão de Itens](/catalogo/meus-itens) para conhecer o módulo.

O catálogo é a base de tudo no PraComprar. É a partir dele que você monta listas de compras, cotações e controla o estoque.

<Steps>
  <Step title='Clique em "Novo item"'>
    Em **Gestão de Itens**, use o botão **Novo item** no topo da tela
  </Step>
  <Step title="Preencha a identificação">
    - **Nome do item** (obrigatório) — ex: *Tomate Orgânico*. É por ele que o item aparece nas buscas
    - **Origem** — Sem classificação, Compra (matéria-prima), Produção interna ou Produto final
    - **Modelo de rendimento** (opcional) — associe um modelo de [Transformação e Rendimentos](/relatorios-e-rendimento/transformacao-e-rendimentos) para calcular o aproveitamento
    - **Observação** (opcional) — ex: *Fatiado fino, apenas da marca X*
  </Step>
  <Step title="Defina as unidades">
    O item pode usar até três unidades diferentes:
    - **Pedido** — como você compra do fornecedor (usada na lista de compras)
    - **Contagem** — como sua equipe conta nas listas de contagem
    - **Estoque** — como o saldo é guardado
    - **Estoque ideal** — a meta de reposição, na unidade de estoque
  </Step>
  <Step title="Vincule categorias e fornecedores">
    Na seção **Categorias e fornecedores**, adicione uma ou mais de cada. A estrela marca o principal
  </Step>
  <Step title="Salve o item">
    Clique em **Salvar item**. Ele já pode entrar em listas de compras e cotações
  </Step>
</Steps>

## Seções opcionais

Abaixo do formulário há quatro seções que abrem ao clicar. Você pode preencher agora ou depois, na edição:

- **Locais de estoque** — sem nenhum marcado, o item usa o local padrão
- **GTIN / EAN** — códigos de barras usados para reconciliar NF-e
- **PDV** — o código do item no CardápioWeb (as outras integrações ficam na edição do item)
- **Lojas** — com todas (ou nenhuma) marcadas, o item aparece em todas as lojas

<Info>
  **Fatores de conversão** (quando a unidade de pedido ou de contagem difere da de estoque) são preenchidos na edição do item, na aba **Geral**. Veja em [Editar item](/catalogo/editar-item).
</Info>

<Tip>
  Prefere importar vários produtos de uma vez? Veja [Importar e exportar catálogo](/conta-e-configuracoes/importar-exportar-catalogo).
</Tip>

<Card title="Próximo passo" icon="arrow-right" href="/catalogo/editar-item">
  Veja todos os detalhes de edição de um item
</Card>
