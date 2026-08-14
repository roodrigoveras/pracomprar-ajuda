---
title: "Importar e exportar catálogo"
description: "Como importar seu catálogo em massa via CSV ou Excel, com mapeamento de colunas e pré-visualização"
---

Se você já tem uma planilha com seus produtos, não precisa cadastrar item por item — o PraComprar importa tudo de uma vez, mapeando as colunas do seu jeito.

<Info>
  Aceita **CSV** ou **Excel (XLSX/XLS)**, em qualquer formato de coluna — você mapeia os campos depois do upload.
</Info>

## Modelos de referência

Antes de montar sua planilha, use um desses modelos como ponto de partida — copie o conteúdo abaixo e salve como `.csv`:

<CodeGroup>

```csv modelo-simples.csv
nome,categoria,fornecedor,estoque_ideal,unidade
Arroz Branco,Graos,Fornecedor ABC,10,kg
Feijao Preto,Leguminosas,Fornecedor ABC,5,kg
Leite Integral,Laticinios,Fornecedor DEF,12,l
Detergente,Limpeza,Casa da Limpeza,2,un
```

```csv modelo-avancado.csv
Nome,Cat1,Cat2,Cat3,Cat4,Cat5,Forn1,Forn2,Forn3,Forn4,Forn5,Estoque Ideal,Unidade de Medida
"ACUCAR MASCAVO KG","Estoque Seco","Despensa Externa",,,,"Atacado Central","Distribuidora Boa Safra",,,,3,kg
"AGUA C/ GAS 500ML PCT C/12","Geladeira Bebidas",,,,,"Distribuidora de Bebidas Sul",,,,,48,pack
"ALFACE AMERICANO KG","Balcao Refrigerado",,,,,"Hortifruti Verde",,,,,3,kg
"BACON FATIADO KG","Freezer",,,,,"Frigorifico Bom Corte","Distribuidora Boa Safra",,,,10,kg
"DETERGENTE NEUTRO 500ML UN","Limpeza",,,,,"Casa da Limpeza",,,,,2,un
```

</CodeGroup>

- O **modelo simples** cobre a maioria dos catálogos: nome, categoria, fornecedor, estoque ideal e unidade
- O **modelo avançado** segue a mesma estrutura usada pelo botão **Baixar modelo avançado** dentro do PraComprar, com até 5 categorias e 5 fornecedores por item

<Tip>
  Dentro do PraComprar, os botões equivalentes são **Baixar modelo CSV** e **Baixar modelo avançado** — prefira sempre baixar direto pela tela de Importar/Exportar, já que o arquivo vem pronto pra editar.
</Tip>

## Importando

<Steps>
  <Step title="Acesse Importar/Exportar">
    Em **Configurações → Importar/Exportar**
  </Step>
  <Step title="Selecione o arquivo">
    Clique em **Escolher Arquivo** e selecione seu CSV ou Excel
  </Step>
  <Step title='Ative o "Modo avançado", se seu arquivo tiver múltiplas categorias/fornecedores'>
    Libera o mapeamento de até 5 colunas de categoria e 5 de fornecedor, além de observação, unidade de estoque e tipo do item
  </Step>
  <Step title="Mapeie as colunas">
    Pra cada campo do PraComprar (**Nome** — obrigatório —, Unidade, Categoria, Fornecedor, Estoque Ideal), escolha no dropdown qual coluna do seu arquivo corresponde a ele
  </Step>
  <Step title="Configure os campos avançados (opcional)">
    - **Categorias e Fornecedores adicionais** — até 5 no total cada
    - **Definir estoque ideal específico por categoria** — sem isso, cada categoria usa o Estoque Ideal geral do item
    - **Observação** e **Unidade de Estoque** — mapeadas por coluna, se seu arquivo tiver
    - **Tipo do Item** e **Modo de Controle de Estoque** — aplicados a todos os itens **novos** dessa importação, não aos já existentes
  </Step>
  <Step title="Confira a pré-visualização">
    A tabela mostra até 10 linhas de exemplo com o mapeamento aplicado, e um status **OK** por linha confirmando que os dados estão prontos pra importar
  </Step>
  <Step title='Clique em "Importar Catálogo"'>
    Itens com o mesmo **Nome** de um item já existente são **atualizados**; os demais são **criados** como novos
  </Step>
</Steps>

## Exportar

Na mesma tela, clique em **Exportar Catálogo** para baixar todos os seus itens já cadastrados em CSV — útil pra backup ou pra editar em massa fora do sistema e reimportar depois.

<Card title="Próximo passo" icon="arrow-right" href="/conta-e-configuracoes/notificacoes">
  Configure suas notificações
</Card>
