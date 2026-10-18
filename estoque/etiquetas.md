---
title: "Etiquetas"
description: "Como montar e imprimir etiquetas de produção com validade, lote e responsável em uma impressora Niimbot"
---

A tela **Etiquetas** monta etiquetas a partir das [fichas técnicas](/estoque/fichas-tecnicas) — nome, validade e temperatura vêm da própria ficha — e imprime numa **impressora Niimbot** via Bluetooth. Ideal para identificar o que foi produzido, com data de fabricação e validade corretas.

## Antes de começar: conecte a impressora

<Steps>
  <Step title="Feche o app da Niimbot">
    Com o aplicativo da Niimbot aberto, a impressora não aparece na lista de Bluetooth do navegador
  </Step>
  <Step title='Clique em "Conectar"'>
    No painel da impressora (que mostra *Niimbot desconectada*), clique em **Conectar** e escolha a impressora na lista do navegador
  </Step>
  <Step title="Confirme a conexão">
    O indicador muda para conectado e mostra o nome do aparelho. Use **Desconectar** quando terminar
  </Step>
</Steps>

<Note>
  A impressão usa Bluetooth do navegador. Funciona no Chrome e Edge, no computador e no Android. No iPhone, o navegador não oferece Bluetooth para o site.
</Note>

## Montar a etiqueta

<Steps>
  <Step title="1. Produto">
    Em **Ficha técnica**, busque a receita. **Nome na etiqueta** vem preenchido (edite se quiser) e **Responsável** indica quem produziu — o nome é abreviado para os dois primeiros nomes na etiqueta
  </Step>
  <Step title="2. Datas">
    Defina **Fabricação** e **Validade**. Os atalhos **1 dia, 3 dias, 7 dias, 15 dias** e **1 mês** calculam a validade a partir da fabricação
  </Step>
  <Step title="3. Detalhes">
    Conforme os campos do modelo escolhido: **Temperatura**, **Lote**, **Qtd. produzida**, **Ingredientes / alérgenos** e **Observação**
  </Step>
  <Step title="Escolha o modelo e a fonte">
    Em **Pré-visualização**, selecione o **Modelo de etiqueta** (o tamanho aparece, ex.: 60×40 mm) e o **Tamanho da fonte**: *Pequena* (cabem mais campos), *Média* ou *Grande* (mais legível)
  </Step>
  <Step title="Imprima">
    Defina o número de **Cópias** (1 a 500) e clique em **Imprimir via Niimbot**. O botão só habilita com a impressora conectada e uma ficha escolhida
  </Step>
</Steps>

## Criar um modelo personalizado

Clique em **+** ao lado de *Modelo de etiqueta* e informe:

- **Nome do modelo** (ex.: *Etiqueta delivery*)
- **Largura** e **Altura** em mm
- **Campos da etiqueta**: nome do produto (sempre presente), data e hora de fabricação, data de validade, temperatura, responsável, lote, quantidade produzida, nome do estabelecimento, código de barras, ingredientes/alérgenos e observação

Use o lápis para editar e a lixeira para excluir os modelos que você criou.

<Tip>
  Cadastre **validade em dias** e **armazenamento** na ficha técnica. Assim a etiqueta já nasce com a validade e a temperatura certas, só falta escolher a data de fabricação.
</Tip>

<Card title="Próximo passo" icon="arrow-right" href="/estoque/impressao-pctray">
  Configure também a impressão de receitas em impressora térmica
</Card>
