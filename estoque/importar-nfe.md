---
title: "Importar NF-e"
description: "Como lançar a nota fiscal do fornecedor no estoque lendo o DANFE pela câmera, pela chave ou pelo XML"
---

Em vez de lançar item por item, você importa a **nota fiscal (NF-e)** do fornecedor e o PraComprar faz as entradas de estoque, cruzando cada produto da nota com o seu catálogo. A tela fica na aba **NF-e** do Estoque.

## 1. Traga a nota

Há três formas de importar:

<Tabs>
  <Tab title="Câmera">
    Clique em **Ler DANFE** ("Está com o DANFE em mãos?"). Escolha o **Tipo de código** (**Código de barras do DANFE** ou **QR Code**), a **Câmera / lente** e use **Abrir câmera**, **Tirar foto** ou **Escolher foto**. Gire o celular na horizontal e alinhe o código inteiro. Quando a chave é válida, ela preenche o campo e a nota é buscada sozinha.
  </Tab>
  <Tab title="Chave de acesso">
    Digite ou cole os **44 dígitos** da chave e clique para buscar. O PraComprar consulta a nota na SEFAZ.
  </Tab>
  <Tab title="Arquivo XML">
    Selecione o arquivo `.xml` da nota (do emissor ou baixado da SEFAZ).
  </Tab>
</Tabs>

<Note>
  A leitura pela câmera exige conexão segura (HTTPS). A nota é sempre lançada na **loja destinatária** (pelo CNPJ). Se você trocar de loja no meio do processo, a conferência da nota é limpa.
</Note>

## 2. Confira os itens

O sistema mostra o **Emitente**, o **Nº/Série** e a **Emissão**. Em seguida, uma linha por produto:

| Coluna | Para que serve |
|---|---|
| **Produto na NF-e** | Nome como veio na nota |
| **GTIN** e **NCM** | Código de barras e classificação fiscal |
| **Qtd** | Quantidade lançada; ajuste se necessário |
| **Custo unit.** | Custo de cada unidade, usado para o valor do estoque |
| **Local de destino** | Sugerido conforme onde o produto costuma ficar |
| **Vínculo no catálogo** | Com qual item do seu catálogo a linha foi casada |

### Como o produto é reconhecido

O PraComprar tenta casar cada linha nesta ordem: **GTIN** → **código do produto no fornecedor** → **nome no mesmo fornecedor** → mesmo nome em outro fornecedor (só como **Sugestão**) → palpite pelas palavras do nome. O selo **Vinculado** ou **Sugestão** mostra de onde veio.

Ao confirmar, **cada linha ensina um apelido**: CNPJ do emitente + código do fornecedor → seu item, com a unidade e o fator usados. Na próxima nota do mesmo fornecedor, o produto já vem vinculado, mesmo sem GTIN. Produtos novos criados como rascunho na importação também deixam de ser duplicados.

### Unidade da nota diferente da do estoque

Quando a nota vem em caixa (`CX`) e o estoque é em unidade, use **Definir conversão** ou **Revisar unidade** na linha. O valor informado vale só para aquela nota. Para o sistema lembrar sempre, cadastre o fator no item (aba **Geral** ou, por embalagem/GTIN, aba **Fiscal**). Veja [Editar item](/catalogo/editar-item).

## 3. Defina os locais

Se vários itens ficaram sem destino, escolha um local em "Aplicar um local a todos os itens sem destino definido" e clique em **Aplicar a todos**.

## 4. Confirme

Clique para confirmar a importação. Cada linha entra no estoque com a quantidade e o custo conferidos. Uma nota parcialmente importada pode ser reprocessada: **só os itens pendentes** são lançados.

## Depois de importar

- **Baixar DANFE** e **Baixar XML** — baixam os arquivos da nota (o ícone de olho abre o DANFE em nova aba)
- **Desfazer importação** — enquanto a janela de desfazer estiver aberta, remove os movimentos de entrada, subtrai as quantidades do estoque e permite reimportar do zero. Não pode ser desfeito
- A nota importada alimenta o [Financeiro → Compras](/financeiro/compras), onde você define parcelas e vencimentos

<Tip>
  Cadastre o GTIN dos produtos na aba **Fiscal** do item. Com ele, a nota é reconhecida na hora e a conferência por código de barras no recebimento também funciona.
</Tip>

<Card title="Voltar ao início do Estoque" icon="arrow-right" href="/estoque/dashboard-de-estoque">
  Veja o resumo geral do seu estoque
</Card>
