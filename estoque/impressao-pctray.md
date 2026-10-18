---
title: "Impressão com pctray"
description: "Como configurar a impressão automática em impressoras térmicas usando o pctray"
---

O **pctray** é o agente de impressão do PraComprar — um programa que roda no seu computador e permite imprimir fichas técnicas, receitas e pedidos direto numa impressora térmica, sem passar pela caixa de diálogo de impressão do navegador.

<Note>
  O pctray é instalado separadamente no computador do estabelecimento. O instalador atual é para **Windows**. Depois de instalado, ele roda em segundo plano (sem janela), abre junto com o Windows e mostra um ícone na bandeja com o status (*Conectado* ou *Sem sessão — faça login*), além de **Abrir log**, **Reiniciar agora** e **Sair**. O PraComprar se conecta a ele automaticamente.
</Note>

## Quais impressoras funcionam

- **Impressoras térmicas ESC/POS de rede** — pelo endereço IP, porta 9100, sem driver do Windows
- **Impressoras térmicas USB** — usando o compartilhamento da impressora no Windows

Se a impressora estiver desligada ou offline, o pedido de impressão **não se perde**: o pctray guarda na fila e tenta de novo automaticamente (até 5 tentativas). Se sua conta tem mais de um estabelecimento, o instalador pede para escolher a loja no primeiro login.

<Info>
  Para a **etiqueta de validade**, use a [impressora Niimbot](/estoque/etiquetas), que conecta direto pelo Bluetooth do navegador e não depende do pctray.
</Info>

## Como funciona

<Steps>
  <Step title="Instale e abra o pctray no computador">
    No primeiro início, o pctray pede login — use os mesmos dados de acesso da sua conta PraComprar
  </Step>
  <Step title="Dê um nome lógico para cada impressora dentro do pctray">
    Esse é o nome que você vai usar depois dentro do PraComprar para escolher qual impressora usar em cada função (ex: *"Cozinha"*, *"Balcão"*)
  </Step>
  <Step title="Deixe o pctray aberto">
    Enquanto estiver rodando, o PraComprar consegue enviar impressões diretamente para as impressoras conectadas
  </Step>
</Steps>

## Configurando a impressora dentro do PraComprar

Você pode cadastrar e escolher a impressora direto de onde for usá-la — por exemplo, na tela de **Fichas Técnicas**:

<Steps>
  <Step title="Abra uma ficha técnica">
    Acesse **Fichas Técnicas** e abra a receita desejada
  </Step>
  <Step title="Encontre o campo Impressora (pctray)">
    Perto do botão **Imprimir Receita**
  </Step>
  <Step title="Selecione uma impressora já cadastrada">
    Ou clique em **Nova impressora** para cadastrar uma agora
  </Step>
  <Step title="Preencha o cadastro rápido">
    - **Nome da impressora** — ex: *"Cozinha"* (precisa ser exatamente o mesmo nome configurado dentro do pctray)
    - **Colunas** — largura do papel: **48** para 80mm, **32** para 58mm (valores típicos)
  </Step>
  <Step title="Clique em Criar, depois em Salvar">
    A partir daí, **Imprimir Receita** envia direto pra impressora térmica escolhida
  </Step>
</Steps>

<Warning>
  Se o pctray não estiver aberto ou não for detectado nessa máquina, o botão de imprimir usa normalmente a caixa de diálogo de impressão do navegador — nada quebra, só não sai direto na térmica.
</Warning>

<Card title="Voltar ao início do Estoque" icon="arrow-right" href="/estoque/dashboard-de-estoque">
  Veja o resumo geral do seu estoque
</Card>
