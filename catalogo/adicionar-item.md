---
title: "Adicionar item ao catálogo"
description: "Como cadastrar um novo produto no seu catálogo"
---

<Note>
  No menu, esse módulo aparece como **Gestão de Itens** — é onde fica todo o catálogo de produtos, categorias e fornecedores.
</Note>

O catálogo é a base de tudo no PraComprar — é a partir dele que você monta listas de compras, cotações e controla o estoque.

<Steps>
  <Step title="Acesse Gestão de Itens">
    No menu, entre em **Gestão de Itens** e clique na aba **Adicionar Item**
  </Step>
  <Step title="Preencha o nome do item">
    Ex: *"Tomate Orgânico"* — use um nome claro, é por ele que o item aparece nas buscas
  </Step>
  <Step title="Defina as unidades">
    - **Unidade de Pedido** — como você compra do fornecedor (usada na lista de compras)
    - **Unidade de Estoque** — como você controla no estoque; deixe em branco pra herdar a unidade de pedido
  </Step>
  <Step title="Informe o Estoque Ideal">
    A quantidade que você quer sempre ter disponível — usada como meta de reposição. Pode ser sobrescrita por categoria
  </Step>
  <Step title="Classifique a Origem do Item">
    Define onde esse item aparece nos filtros de **Meus Itens**:
    - **Não classificado** — padrão, sem classificação
    - **Compra (matéria-prima)** — item que você compra pronto de um fornecedor
    - **Produção Interna (subproduto)** — item gerado a partir de outro (ex: filé depois de processar um peixe inteiro)
    - **Produto Final** — item pronto pra venda ou uso final
  </Step>
  <Step title="Vincule um Modelo de Rendimento (opcional)">
    Se esse item passa por algum processamento, associe um modelo já cadastrado em [Transformação e Rendimentos](/relatorios-e-rendimento/transformacao-e-rendimentos) — isso conecta o item ao cálculo de aproveitamento
  </Step>
  <Step title="Adicione uma observação (opcional)">
    Ex: *"Fatiado fino, apenas da marca X, orgânico certificado..."*
  </Step>
  <Step title="Vincule categorias e fornecedores">
    Adicione uma ou mais categorias e um ou mais fornecedores direto nessa mesma tela
  </Step>
  <Step title="Salve o item">
    Clique em **Salvar Novo Item** — ele já está disponível pra entrar em listas de compras e cotações
  </Step>
</Steps>

<Tip>
  O formulário tem mais 4 seções opcionais (Locais de Estoque, Fiscal, PDV e Disponibilidade por Loja) que você pode configurar na mesma tela antes de salvar. Depois de criado, esses mesmos detalhes — e mais alguns — ficam disponíveis a qualquer momento em [Editar Item](/catalogo/editar-item).
</Tip>

<Tip>
  Prefere importar vários produtos de uma vez em vez de cadastrar um por um? Veja [Importar e exportar catálogo](/conta-e-configuracoes/importar-exportar-catalogo).
</Tip>

<Card title="Próximo passo" icon="arrow-right" href="/catalogo/editar-item">
  Veja todos os detalhes de edição de um item
</Card>
