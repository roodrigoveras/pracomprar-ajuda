---
title: "Central de Integrações"
description: "Como conectar o CardápioWeb ao PraComprar e acompanhar a conexão do estabelecimento"
---

A **Central de Integrações** (menu lateral **Integrações**) é onde você conecta o PraComprar às plataformas de venda. Hoje a integração disponível é o **CardápioWeb**: cada venda recebida pode baixar o estoque automaticamente, usando as fichas técnicas dos pratos.

A central funciona **por estabelecimento** — confira a loja selecionada antes de mexer. Ela tem seis abas:

<CardGroup cols={2}>
  <Card title="Explorar integrações" icon="compass">
    Vitrine das integrações e pedido de ativação
  </Card>
  <Card title="Composições de combos" icon="layer-group" href="/integracoes/composicoes-de-combos">
    Combos fixos montados com fichas e itens
  </Card>
  <Card title="Produtos e vínculos" icon="link" href="/integracoes/produtos-e-vinculos">
    Liga cada produto vendido a uma ficha, composição ou item
  </Card>
  <Card title="Conexões" icon="plug">
    Credenciais, webhook e situação da conexão
  </Card>
  <Card title="Vendas e pendências" icon="receipt" href="/estoque/integracao-cardapioweb">
    Pedidos recebidos e o que ficou sem baixa
  </Card>
  <Card title="Recursos e regras" icon="gear" href="/integracoes/recursos-e-regras">
    Quando e como as vendas baixam o estoque
  </Card>
</CardGroup>

<Note>
  Só aparecem as abas de operação (Composições, Produtos e vínculos, Conexões, Vendas e pendências, Recursos e regras) quando a integração está **liberada** para o estabelecimento. Enquanto isso, você vê apenas **Explorar integrações**.
</Note>

## Solicitar a ativação

Na aba **Explorar integrações**, o cartão **Cardápio Web** mostra o que a integração entrega: pedidos em tempo real, baixa automática de estoque e fichas e combos vinculados. Clique em **Solicitar ativação** para pedir a liberação à equipe do PraComprar. Depois de ativa, o botão vira **Gerenciar conexão**.

Plataformas ainda não disponíveis aparecem em **Em breve**; use **Tenho interesse** ou **Sugerir** para nos dizer qual você usa.

## Conectar o CardápioWeb

Na aba **Conexões** você vê o cartão **Cardápio Web** com a situação da conexão e três números: **Último pedido**, **Pedidos hoje** e **Últimos 30 dias**.

### Pela CW App Store (recomendado)

Quando disponível, clique em **Conectar CardápioWeb**. A autorização acontece pela CW App Store, e as credenciais e o *secret* são gerenciados por ela — você não precisa copiar nada.

### Conexão manual

Se o seu estabelecimento usa a conexão por credenciais:

<Steps>
  <Step title="Informe as credenciais">
    No painel do Cardápio Web, copie o **Merchant ID** (ID da loja) e o **API Token** e cole nos campos correspondentes
  </Step>
  <Step title="Cadastre o webhook no Cardápio Web">
    Copie a **URL do webhook** gerada pelo PraComprar (botão **Copiar**) e cadastre no painel do Cardápio Web, para receber os pedidos em tempo real
  </Step>
  <Step title="Gere e guarde o Webhook Secret">
    Clique em **Gerar novo**. O valor aparece **uma única vez**: copie e cole no campo **Webhook Secret** do painel do Cardápio Web. Se perder, é só gerar outro
  </Step>
  <Step title="Ative e salve">
    Marque **Integração ativa** e clique em **Salvar**
  </Step>
  <Step title='Teste a conexão'>
    Use **Testar Webhook** para confirmar que o PraComprar está recebendo os eventos
  </Step>
</Steps>

<Warning>
  Gerar um novo secret invalida o anterior. Atualize o Webhook Secret no painel do Cardápio Web logo depois, ou os pedidos deixarão de chegar.
</Warning>

<Card title="Próximo passo" icon="arrow-right" href="/integracoes/produtos-e-vinculos">
  Ligue os produtos vendidos às fichas técnicas
</Card>
