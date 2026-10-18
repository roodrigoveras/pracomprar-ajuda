---
title: "Fichas técnicas"
description: "Como cadastrar receitas de venda e de produção, calcular custo e CMV e usar a matriz BCG"
---

A **ficha técnica** registra os ingredientes de uma receita, calcula o **custo** com base nos preços do seu estoque e compara com o preço de venda para mostrar o **CMV** (custo da mercadoria vendida). Também é a base da baixa automática de estoque nas vendas e na produção.

A tela **Fichas Técnicas** ("receitas, custos e CMV do estabelecimento") separa as fichas em duas abas:

- **Venda** — pratos e produtos que você vende (têm preço de venda e CMV meta)
- **Produção** — preparos internos (molhos, bases, massas) que viram um **item de estoque** quando produzidos

## Criar uma ficha

<Steps>
  <Step title='Clique em "Nova ficha"'>
    Abre a criação em três passos, com um **Resumo** que atualiza enquanto você preenche
  </Step>
  <Step title="Passo 1 — Dados da receita">
    - **Foto** da receita (JPG, PNG ou WebP, até 10 MB)
    - **Nome da receita** *(obrigatório)*
    - **Tipo**: *Venda* ou *Produção*
    - **Preço de venda** e **CMV meta** (%), para fichas de venda
    - **Popularidade**: *Alta* ou *Baixa* (alimenta a matriz BCG)
    - **Validade** em dias, **Validade extra** em horas (para ultraperecíveis) e **Armazenamento** em °C — usados nas [etiquetas](/estoque/etiquetas)
    - **Item gerado** — o item do catálogo que entra no estoque ao lançar a produção. É necessário para **publicar** fichas de produção
  </Step>
  <Step title="Passo 2 — Ingredientes">
    Busque o **ingrediente**, informe a **Qtd.** e a **Unidade na ficha** e clique em **+**. O custo aparece na hora. Se a unidade da ficha for diferente da do estoque, use **Configurar unidade e conversão**. Defina o **Rendimento da receita** (quantidade e unidade que a receita rende)
  </Step>
  <Step title="Passo 3 — Resumo">
    Confira **Preço de venda, Custo unitário, CMV meta** e **CMV atual**. A lista de verificação mostra o que falta: *nome, preço e CMV meta, ao menos um ingrediente*
  </Step>
  <Step title='Salve como rascunho ou publique'>
    Só o nome é obrigatório para **Salvar rascunho**. **Publicar ficha** deixa a receita ativa
  </Step>
</Steps>

<Warning>
  **Rascunhos não entram na baixa de estoque nem nas integrações.** Publique a ficha para ela valer. Salvar uma ficha também não altera o saldo nem o custo do estoque.
</Warning>

## Ler a lista

A aba **Venda** mostra a **matriz BCG**, que cruza lucro e popularidade. Clique em um cartão para filtrar:

| Cartão | O que significa |
|---|---|
| **Orgulho da casa** | Alto lucro · alta popularidade |
| **Carro-chefe** | Baixo lucro · alta popularidade |
| **Joia escondida** | Alto lucro · baixa popularidade |
| **Candidato ao corte** | Baixo lucro · baixa popularidade |

A tabela traz **Receita, Preço de venda, CMV meta, Ingredientes** e a **Matriz BCG** de cada ficha. Busque por receita ou ingrediente.

## Dentro de uma ficha

Ao abrir uma ficha, o resumo mostra **Preço de venda, Custo unitário, CMV atual, CMV meta** e o **Preço sugerido** (calculado pelo CMV meta). O selo de CMV indica se está *dentro* ou *acima da meta*.

- **Ingredientes** — adicione, remova e **Salvar ingredientes**
- **Modo de preparo** — escreva o passo a passo e salve
- **Editar dados** — muda nome, tipo, popularidade, preço, CMV meta, validade e item gerado
- **Baixar ficha técnica** e **Excluir ficha** (fichas em uso mostram os vínculos antes de excluir)

### Calcular receita

Em **Calcular receita**, informe **Quero produzir** (quantidade e unidade) e clique em **Calcular**. O PraComprar multiplica todos os ingredientes pelo fator (ex.: ×2,5) e mostra o custo estimado.

- **Imprimir receita** — na impressora térmica do módulo ([pctray](/estoque/impressao-pctray)) ou na impressão do navegador
- **Executar e baixar estoque** — para fichas de produção, lança a [produção](/estoque/lancar-producao)

### Criar uma rotina a partir da ficha

Depois de imprimir, o PraComprar pergunta se você quer criar uma **rotina de produção**: escolha uma rotina existente ou crie uma nova, o **colaborador**, o **dia** e o **início**. Veja [Rottinas](/marketplace-e-rotinas/checklists-e-rotinas).

## Quem pode lançar produção

O ícone de pessoas no topo abre **Quem pode executar produção**. Marque os colaboradores que podem usar receitas prontas em [Lançar produção](/estoque/lancar-producao) **sem** poder criar, editar ou apagar fichas. Donos, superusuários e gerentes com permissão de fichas técnicas sempre podem executar.

<Tip>
  Para conectar uma ficha de venda ao CardápioWeb, use [Produtos e vínculos](/integracoes/produtos-e-vinculos). Não precisa cadastrar o produto final na Gestão de Itens.
</Tip>

<Card title="Próximo passo" icon="arrow-right" href="/estoque/lancar-producao">
  Lance a produção e dê baixa nos ingredientes
</Card>
