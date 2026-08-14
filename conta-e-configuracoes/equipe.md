---
title: "Equipe"
description: "Como cadastrar proprietários, gerentes e colaboradores, e configurar permissões granulares"
---

A aba **Equipe** é onde você gerencia todo mundo que tem acesso à sua conta — proprietários, gerentes e colaboradores — e o que cada um pode fazer.

<Steps>
  <Step title="Acesse Equipe">
    Em **Configurações**, clique na aba **Equipe**
  </Step>
  <Step title="Veja o resumo">
    No topo: **Total**, **Proprietários**, **Gerentes** e **Colaboradores**
  </Step>
  <Step title="Filtre a lista">
    Use as abas **Todos / Proprietários / Gerentes / Colaboradores**, ou busque por nome, e-mail ou usuário
  </Step>
  <Step title='Adicione um novo usuário'>
    Clique em **+ Novo usuário**
  </Step>
</Steps>

## Cadastrando ou editando um usuário

<Steps>
  <Step title="Preencha os dados">
    - **Nome**
    - **Usuário** — o login dele no sistema
    - **WhatsApp / Telefone**
    - **E-mail** (opcional)
    - **Tipo de usuário** — Gerente ou Colaborador
    - **Nova senha** (opcional — deixe em branco pra manter)
  </Step>
  <Step title="Defina o estabelecimento principal">
    Escolha em qual loja esse usuário atua por padrão — esse campo é **obrigatório**
  </Step>
  <Step title="Salve">
    Clique em **Salvar**
  </Step>
</Steps>

<Warning>
  Um usuário sem estabelecimento definido não pode ter permissões configuradas — o sistema avisa: *"Este usuário ainda não tem um estabelecimento definido. Edite o usuário e selecione o estabelecimento antes de configurar permissões."*
</Warning>

## Configurando permissões

Clique no ícone de permissões (sliders) ao lado de um gerente ou colaborador pra abrir o painel completo, organizado por estabelecimento e por área do sistema:

<CardGroup cols={2}>
  <Card title="Listas de Compras" icon="cart-shopping">
    Criar Listas · Editar Listas · Excluir Listas · Editar Lista Gerada (editar itens e quantidades em listas de pedido já geradas)
  </Card>
  <Card title="Catálogo & Fornecedores" icon="box">
    Gerenciar Catálogo · Gerenciar Categorias · Gerenciar Fornecedores
  </Card>
  <Card title="Estoque & Recebimento" icon="boxes-stacked">
    Conferências e Recebimento (criar, editar, finalizar conferências) · Registrar Recebimento — Staff (informar quantidade e valor recebido) · Visualizar Estoque · Movimentar Estoque (entradas, saídas e ajustes)
  </Card>
  <Card title="Cotações" icon="file-invoice-dollar">
    Visualizar Cotações (histórico e detalhes) · Gerenciar Cotações (enviar, cancelar, reenviar e aprovar)
  </Card>
  <Card title="Transformação e Rendimentos & Fichas Técnicas" icon="scale-balanced">
    Módulo de Transformação e Rendimentos · Fichas Técnicas (criar, editar, executar) · Pesagem com Tara
  </Card>
  <Card title="Gerencial" icon="chart-line">
    Visualizar Relatórios · Gerenciar Colaboradores
  </Card>
</CardGroup>

Cada permissão é um toggle independente. Depois de ajustar, clique em **Salvar Permissões**.

<Tip>
  Como as permissões são configuradas por estabelecimento, um gerente pode ter acesso total numa loja e acesso bem restrito em outra — útil quando cada unidade tem uma equipe diferente.
</Tip>

## Ações rápidas na lista

Além de editar e configurar permissões, cada usuário tem ícones pra **pausar o acesso** (sem excluir o cadastro) e **excluir** o usuário definitivamente.

<Card title="Próximo passo" icon="arrow-right" href="/conta-e-configuracoes/importar-exportar-catalogo">
  Importe ou exporte seu catálogo em massa
</Card>
