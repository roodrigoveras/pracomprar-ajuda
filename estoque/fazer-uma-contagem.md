---
title: "Contagem de estoque"
description: "Como criar, executar, revisar e aprovar uma contagem física, inclusive recorrente e com modelo salvo"
---

A **contagem física** é o que mantém o estoque do PraComprar batendo com a realidade do depósito. O fluxo tem três papéis: o gestor **cria** a contagem, a equipe **executa** e o gestor **revisa e aprova**, o que ajusta o estoque.

Na aba **Contagens** do Estoque você encontra a tela **Contagens físicas** ("contagens de estoque, revisão e reconciliação"), com quatro números no topo: **Total**, **Em andamento**, **Em revisão** e **Aprovadas · 30 d**. Ela tem as abas **Contagens**, **Templates** e **Recorrências**.

## 1. Criar a contagem

<Steps>
  <Step title='Clique em "Nova contagem"'>
    Abre a tela **Nova Contagem Física**, em três blocos
  </Step>
  <Step title="Bloco 1 — O que contar">
    - **Título da contagem** — ex.: *Contagem mensal — janeiro*
    - **Tipo de contagem**: **Normal** (mostra a quantidade esperada) ou **Cego** (oculta a quantidade esperada, para a equipe não "adivinhar")
    - **Local** — um local específico ou **Todas as localizações**
    - **Categorias** — toque para selecionar quais entram na contagem
  </Step>
  <Step title="Bloco 2 — Quem conta">
    Em **Atribuir a**, selecione uma ou mais pessoas. Todos os atribuídos veem a contagem em **Minhas contagens**
  </Step>
  <Step title="Bloco 3 — Opções">
    - **Permitir envio via WhatsApp** — os colaboradores podem compartilhar o resultado
    - **Contagem recorrente** — a próxima contagem é criada automaticamente. Escolha a **Frequência** (*Diária, Semanal, Quinzenal, Mensal, Trimestral* ou *Personalizado*, com "a cada quantos dias") e a **Próxima execução**
    - **Observações**
  </Step>
  <Step title='Clique em "Criar Contagem"'>
    Se algum usuário atribuído tiver permissões limitadas, o sistema avisa que ele verá só parte das categorias
  </Step>
</Steps>

## 2. Executar (equipe)

<Steps>
  <Step title="Abra Minhas contagens">
    O colaborador entra em **Minhas contagens** (também aparece na tela inicial) e abre a contagem pendente
  </Step>
  <Step title="Busque e filtre os itens">
    Busque por nome ou código, filtre por categoria e por **Pendentes** ou **Contados**. Os itens ficam agrupados por local, com o andamento de cada grupo (ex.: *21/30 contados*)
  </Step>
  <Step title="Informe a quantidade contada">
    Para cada item, digite a **Quantidade Contada**. Em contagem *Normal*, a tela mostra a **Quantidade Esperada** e a variação. Use **Observações** para registrar problemas (ex.: *embalagem violada*)
  </Step>
  <Step title="Salve e finalize">
    O progresso é salvo conforme você conta. Ao terminar, o botão de finalizar mostra o **Resumo da Contagem** (itens contados e pendentes) e pede **Observações Finais**
  </Step>
</Steps>

<Info>
  A contagem é feita na **unidade de contagem** do item. Se ela for diferente da unidade de estoque, o sistema converte ao gravar e mostra, na revisão, o valor original digitado (ex.: *digitado: 1 cx*).
</Info>

## 3. Finalizar e revisar (gestor)

Quando a equipe envia, a contagem fica **Aguardando Revisão**. O gestor também pode **finalizar direto** pela tela de detalhes. Se ainda existem itens pendentes, aparece o aviso **Existem itens não contados!** e é preciso **digitar "finalizar"** para confirmar — a contagem fica marcada como parcial e registra quem a finalizou.

<Steps>
  <Step title="Abra a revisão">
    A tela mostra **Itens**, **Com variância**, **Críticas >20%** e **Impacto** (o efeito financeiro)
  </Step>
  <Step title="Filtre as variâncias">
    Filtre por local e por nível (*Crítica >20%, Alta 10–20%, Média 5–10%, Baixa <5%, Sem variância*), ordene por maior variância, nome ou categoria, e exporte para Excel
  </Step>
  <Step title="Decida">
    - **Aprovar** — o estoque é ajustado para a quantidade contada. Confirme a caixa de ciência e, se quiser, escreva observações
    - **Rejeitar** — informe o **Motivo da Rejeição**; a equipe é avisada
    - **Reabrir** — volta para *Em andamento*, preservando o que já foi contado
  </Step>
</Steps>

O relatório pode ser compartilhado por WhatsApp pelo botão correspondente.

## Templates e recorrências

- **Templates** — salve uma contagem como modelo para reaproveitar escopo e categorias
- **Recorrências** — veja as **Contagens recorrentes ativas** e atualize a lista

<Tip>
  Para conferir só o que importa no dia a dia, use contagens por **local** ou por **categoria**, programadas como recorrentes (ex.: freezer toda semana).
</Tip>

<Card title="Próximo passo" icon="arrow-right" href="/estoque/alertas-de-reposicao">
  Veja os alertas de reposição
</Card>
