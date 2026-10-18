---
title: "Integração com Consumer e PraConnect"
description: "Como solicitar e configurar a conexão do PDV Consumer com o PraComprar"
---

A integração **Consumer · PraConnect** conecta o PDV Consumer ao PraComprar por meio do aplicativo PraConnect. Ela permite acompanhar vendas e pagamentos e, quando configurada, movimentar o estoque conforme os vínculos dos produtos.

<Note>O recurso depende de ativação para o estabelecimento e da instalação do PraConnect no computador que utiliza o Consumer.</Note>

## Solicitar a integração

Acesse **Integrações > Explorar integrações**, localize **Consumer** e clique em **Solicitar ativação**. Quando estiver liberada, use **Gerenciar conexão**.

## Conectar o Consumer

<Steps>
  <Step title="Prepare o computador">
    Instale o **PraConnect** no computador com acesso ao Consumer, seguindo as instruções fornecidas pela equipe do PraComprar.
  </Step>
  <Step title="Teste a conexão no PraConnect">
    Abra o aplicativo e confirme que ele consegue acessar os dados do Consumer.
  </Step>
  <Step title="Gere o código de conexão">
    No PraComprar, abra **Integrações > Consumer > Conexão** e clique em **Gerar código de conexão**.
  </Step>
  <Step title="Vincule o aplicativo">
    Informe o código no PraConnect para concluir a associação. O código tem validade limitada; se expirar, gere outro.
  </Step>
  <Step title="Confira os produtos">
    Em **Produtos e vínculos**, associe os produtos e complementos às fichas técnicas ou itens de estoque correspondentes.
  </Step>
  <Step title="Configure a movimentação do estoque">
    Revise a opção **Baixar estoque de novas vendas confirmadas**. Com ela desligada, as vendas podem ser usadas para acompanhamento sem baixa automática.
  </Step>
</Steps>

## Conferir os resultados

Use **Vendas e pendências** para acompanhar os pedidos recebidos e identificar registros que precisem de revisão. Se não houver dados, confira a conexão do PraConnect, a loja selecionada e os vínculos cadastrados.

<Warning>Não compartilhe códigos de conexão com pessoas que não estejam autorizadas a configurar a integração do estabelecimento.</Warning>

<Card title="Voltar à Central de Integrações" icon="arrow-left" href="/integracoes/central-de-integracoes">Veja as outras plataformas.</Card>
