---
title: "Impressão com pctray"
description: "Como configurar a impressão automática em impressoras térmicas usando o pctray"
---

O **pctray** é o agente de impressão do PraComprar — um programa que roda no seu computador e permite imprimir fichas técnicas, receitas e pedidos direto numa impressora térmica, sem passar pela caixa de diálogo de impressão do navegador.

<Note>
  O pctray é instalado separadamente no computador (Windows, macOS ou Linux). Depois de instalado, ele fica rodando em segundo plano e o PraComprar se conecta a ele automaticamente.
</Note>

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
