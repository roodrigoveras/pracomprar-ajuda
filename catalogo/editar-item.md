---
title: "Editar item"
description: "Todas as abas da edição de um item: Geral, Categorias, Fornecedores, Locais, Fiscal, PDV e Lojas"
---

Ao abrir um item em [Meus Itens](/catalogo/meus-itens), você entra numa tela com abas. No topo ficam a seta para voltar à lista e o ícone de lixeira para **excluir o item**. No rodapé ficam **Cancelar** e **Salvar**.

## Geral

**Identificação:** Nome do item, **Origem**, **Modelo de rendimento** e Observação.

**Unidades:** as três unidades do item e o estoque ideal.

| Campo | Para que serve |
|---|---|
| **Pedido** | Lista de compras e cotações |
| **Contagem** | Listas de contagem de estoque |
| **Estoque** | Como o saldo é guardado |
| **Estoque ideal** | Meta de reposição (pode mudar por categoria) |

### Fatores de conversão

Quando a unidade de pedido ou de contagem é diferente da de estoque, aparece o bloco **Fatores de conversão**, com uma linha para cada unidade. Exemplo: *1 caixa (pedido) = 4,8 kg (estoque)*.

<Info>
  Conversões automáticas, como g para kg e ml para L, não pedem fator. Os fatores valem no recebimento, na contagem, no rendimento e nas cotações. Pedido e contagem se convertem entre si passando pela unidade de estoque.
</Info>

## Categorias

Mostra as categorias do item. Cada uma tem seu próprio **estoque ideal** e unidade. Se ficar vazio, vale o padrão do item.

<Steps>
  <Step title="Marque a principal">
    Clique na estrela ao lado da categoria. A principal ganha o selo **Principal**
  </Step>
  <Step title="Ajuste o ideal da categoria">
    Informe o valor só se for diferente do padrão
  </Step>
  <Step title="Adicione novas categorias">
    Em **Adicionar categorias**, busque, marque e clique em **Adicionar selecionados**
  </Step>
</Steps>

## Fornecedores

Mesma lógica: estrela para o **Principal** e **Adicionar selecionados** para vincular novos.

<Info>
  **Principal por loja** — com mais de um estabelecimento, aparece a seção **Principal por loja**. Use quando um fornecedor não atende todas as unidades. Em **Usar o padrão**, vale o fornecedor principal do item.
</Info>

## Locais

Em quais locais de estoque o item aparece. Sem nenhum marcado, usa o local padrão.

## Fiscal

A aba **GTIN / EAN e nome para pedido** guarda as **variações** do item. Cada GTIN é uma embalagem ou marca (ex: caixa de 18 kg e caixa de 12 kg).

Para cadastrar uma variação, informe:

- **GTIN / EAN** — PLU, EAN-8, UPC-A, EAN-13 ou DUN-14 (só números)
- **Descrição** (opcional)
- **Nome para pedido** (opcional) — vai ao fornecedor no lugar do nome interno. Em branco, usa a descrição
- **Fornecedor específico** (opcional) — restringe a variação a um fornecedor
- **Fator desta variação** (opcional) — só vale quando esse GTIN é reconhecido, como na [importação de NF-e](/estoque/importar-nfe). Fora disso, vale o fator da aba Geral
- **Composição** (opcional) — texto livre, só documentação (ex: *8 pacotes de 2,25kg*)
- **Marcar como principal**

Depois, clique em **Adicionar**. Para corrigir uma variação, edite-a na lista; para remover, use a lixeira.

## PDV

Em **Códigos PDV** você informa o código do item em cada sistema de vendas. Apenas integrações **ativas** (hoje o CardápioWeb) baixam estoque.

### Baixa na venda

O **Modo de baixa** vale **para esta loja**. Itens compartilhados podem ter modos diferentes em cada loja.

| Opção | O que faz |
|---|---|
| **Não definido** | A venda gera pendência, sem baixar estoque |
| **Baixa automática** | Desconta na venda, pela ficha técnica ou 1:1 |
| **Não controlado** | Não baixa. Use para matéria-prima ou componente de combo |
| **Produção** | Controlado via Rendimento ou Ficha Técnica |

<Note>
  Só importa para itens vendidos com código PDV. Veja como tratar as pendências em [Vendas e pendências do CardápioWeb](/estoque/integracao-cardapioweb).
</Note>

## Lojas

Aparece só para quem tem mais de um estabelecimento. Marque as lojas em que o item deve aparecer.

<Card title="Voltar" icon="arrow-right" href="/catalogo/meus-itens">
  Veja todos os itens já cadastrados
</Card>
