---
title: "Conferir um recebimento"
description: "Como revisar a conferência, dar entrada no estoque e finalizar o recebimento da mercadoria"
---

Ao abrir uma conferência no [Painel de Conferências](/conferencias/painel-de-conferencias), você vê o cabeçalho **Conferência #número** com a situação, o estabelecimento, quem criou e quando.

## O que a tela mostra

- **Progresso** — quantos itens já foram recebidos, com barra de porcentagem
- **Colaboradores** ou **Responsável** — quem está conferindo
- **Enviada pela equipe** — quando o colaborador terminou
- **Fornecedores** — quantos fornecedores há na conferência
- **Observações gerais**, quando você tiver escrito alguma
- **Itens por fornecedor** — a lista de produtos, agrupada por fornecedor

## Passo a passo

<Steps>
  <Step title="Acompanhe ou preencha o recebimento">
    Para cada item, confira a **quantidade esperada** contra a **Qtd. Recebida**, o **Vl Unit.** e a **Validade**. O sistema sinaliza quando o recebido diverge do pedido. A **Nota do Staff** mostra o recado do colaborador sobre o item
  </Step>
  <Step title="Deixe um recado para a equipe (opcional)">
    No ícone de **Obs. do Admin**, escreva uma **Observação para a equipe** sobre o item (ex.: *conferir a validade com atenção*)
  </Step>
  <Step title="Registre a entrada no estoque">
    No item recebido, clique em **Registrar entrada no estoque** e informe:
    - **Quantidade recebida** (obrigatória) — o que realmente chegou
    - **Valor unitário** — pode ser preenchido depois
    - **Validade**
    - **Local de destino** — em qual local do estoque o item entra
    - **Salvar padrão** — guarda local e valor para a próxima vez
  </Step>
  <Step title="Escolha a variação recebida">
    Se o item tem mais de uma embalagem cadastrada (GTINs diferentes), o sistema pergunta **qual variação foi recebida**. O fator de conversão da variação define quantas unidades de estoque entram
  </Step>
  <Step title='Clique em "Finalizar conferência"'>
    Itens com quantidade zero precisam da quantidade recebida antes de finalizar. Quando você confirma, o **estoque é atualizado** com o que foi efetivamente recebido. Use **Não dar entrada agora** para os itens que não devem entrar
  </Step>
</Steps>

<Warning>
  Se precisar corrigir algo depois, use **Reabrir** (se você tem a permissão). A conferência volta a ficar editável.
</Warning>

## Ajustar a conferência durante o recebimento

Chegou um produto que não estava no pedido? Você pode mudar a conferência na hora:

- **Incluir item** — busque no catálogo ou digite um item que ainda não está cadastrado, informe o fornecedor e a **Quantidade esperada**. Itens digitados aparecem como **Não cadastrado**
- **Adicionar fornecedor** — cria o card de um fornecedor que não estava na conferência
- **Arrastar** — mova um item de um fornecedor para outro, arrastando para o card dele

## Ler código de barras

O leitor de código funciona no [celular da equipe](/conferencias/minhas-conferencias). Se o produto não tiver o código cadastrado, ele não é encontrado — cadastre o GTIN na aba **Fiscal** do item (veja [Editar item](/catalogo/editar-item)).

<Tip>
  Para lançar entradas de várias notas de uma vez, sem conferir item por item, use a [importação de NF-e](/estoque/importar-nfe).
</Tip>

<Card title="Próximo passo" icon="arrow-right" href="/conferencias/minhas-conferencias">
  Veja como a equipe confere pelo celular
</Card>
