---
title: "Editar item"
description: "Todas as abas da edição de um item: Geral, Categorias, Fornecedores, Locais, Fiscal, PDV e Lojas"
---

Ao clicar em **Editar** num item em [Meus Itens](/catalogo/meus-itens), você abre uma tela com 7 abas — bem mais completa que o formulário inicial de [Adicionar Item](/catalogo/adicionar-item).

## Geral

Além dos campos básicos (Nome, Unidade de Pedido, Unidade de Estoque, Estoque Ideal Padrão, Observação, Modelo de Rendimento, Origem do Item), a edição libera um campo extra:

<Info>
  **Fator de Conversão** — só aparece quando a Unidade de Pedido é diferente da Unidade de Estoque. Ex: *1 un = 4,8 kg*. Usado para converter automaticamente no recebimento, no rendimento e na comparação de cotações.
</Info>

## Categorias

Mostra as categorias já vinculadas ao item, cada uma com sua própria **quantidade ideal** e **unidade** — ou seja, dá pra ter um estoque ideal diferente por categoria, sobrescrevendo o padrão definido na aba Geral.

<Steps>
  <Step title="Marque uma categoria como principal">
    Clique na estrela ao lado da categoria — a categoria principal aparece com o badge **Principal**
  </Step>
  <Step title="Ajuste a quantidade ideal daquela categoria">
    Informe o valor e a unidade específicos, se forem diferentes do padrão do item
  </Step>
  <Step title="Vincule novas categorias">
    Busque na lista abaixo, marque as desejadas e clique em **Adicionar selecionados**
  </Step>
</Steps>

## Fornecedores

Mostra os fornecedores vinculados, com o mesmo sistema de estrela pra marcar o **principal**.

<Info>
  **Principal por loja** — se você tem mais de um estabelecimento, dá pra definir um fornecedor principal diferente por loja (útil quando um fornecedor não atende todas as unidades). Deixe em **"Usar o padrão"** pra manter o mesmo fornecedor principal de sempre, ou clique em **"padrão do item"** pra reverter.
</Info>

Pra adicionar um novo fornecedor, busque na lista, marque e clique em **Adicionar selecionados**.

## Locais

Cada estabelecimento pode ter mais de um local de estoque (ex: *Estoque Fechado* e *Estoque Aberto*). Marque em quais locais esse item deve aparecer ao sincronizar com o estoque — o local marcado como **padrão** é usado quando nenhum é selecionado manualmente.

## Fiscal

Mesma lógica de cadastro dos [códigos GTIN/EAN](/catalogo/adicionar-item), mas aqui você também pode **excluir** um código já vinculado, clicando no ícone de lixeira ao lado dele.

## PDV

Configure o código PDV desse item em cada sistema de vendas integrado — CardápioWeb, iFood, 99Food, Keeta, Saipos, Consumer e SoftPlus (a maioria ainda marcada como **Em breve**; apenas integrações **ativas** baixam estoque automaticamente).

### Modo de Baixa na Venda

Esse campo controla como o estoque é abatido quando o item é vendido por uma integração, **especificamente nesta loja** (itens compartilhados entre lojas podem ter modo diferente em cada uma):

| Opção | O que faz |
|---|---|
| **Não definido** | Gera pendência se o item for vendido, sem baixar estoque automaticamente |
| **Baixa automática** | Desconta o estoque na hora da venda (ficha técnica ou 1:1) |
| **Não controlado** | Não baixa estoque — use pra matéria-prima ou item que compõe um combo |
| **Produção** | O controle é feito via Rendimento/Ficha Técnica, não pela venda direta |

<Note>Esse campo só importa pra itens vendidos com código PDV configurado.</Note>

## Lojas

Mesma tela de [Disponibilidade por Loja](/catalogo/adicionar-item) do cadastro — marque em quais estabelecimentos o item aparece.

---

Em qualquer aba, os botões no rodapé permanecem os mesmos: **Cancelar**, **Excluir Item** e **Salvar Alterações**.

<Card title="Voltar" icon="arrow-right" href="/catalogo/meus-itens">
  Veja todos os itens já cadastrados
</Card>
