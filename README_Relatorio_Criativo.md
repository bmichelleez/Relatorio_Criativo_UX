# Relatório Criativo com Foco na Experiência do Usuário

Desafio de projeto da Formação Power BI Analyst (DIO). O relatório criativo, o primeiro desenvolvido na formação com a base *Financial Sample*, foi reformulado com foco na experiência do usuário, considerando **posicionamento**, **contraste**, **proporção áurea** e **segmentação dos dados**.

<!-- Adicione aqui os prints das três páginas -->

## Estrutura

| Página | Conteúdo |
| --- | --- |
| Vendas | Vendas por período, segmento ou produto, trimestre e mês e país |
| Lucro | Árvore de decomposição do lucro, lucro por produto, trimestre e segmento |
| Relatório | Vendas x vendas brutas, lucro por trimestre e ano, vendas e lucro no tempo, faixas de desconto |

## Decisões de design

### Posicionamento
- As três páginas seguem o mesmo esqueleto: cabeçalho com logo, título e menu; painel de filtros à esquerda; conteúdo à direita. Antes, cada página tinha uma disposição diferente (menu lateral em uma, cabeçalho em outra).
- Leitura em "Z": quatro cartões-resumo no topo, visual principal abaixo à esquerda, complementares à direita e embaixo.
- Elementos decorativos sem função analítica foram retirados, e o espaço foi redistribuído para os dados.

### Contraste
- Cabeçalho em roxo escuro (#36003E) com textos brancos, e área de conteúdo em lilás claro com visuais brancos de cantos arredondados.
- A cor lilás (#C499CA), que já fazia parte do relatório, destaca a página atual no menu.
- Cartões com o valor em roxo e destaque maior e o rótulo em cinza menor.

### Proporção áurea
- A área de conteúdo (996 px) é dividida na razão 1 : 0,618: 615 px para os visuais principais e 381 px para os complementares.
- Na vertical, a mesma lógica separa o bloco principal (324 px) do secundário (184 px).

### Segmentação dos dados
- Filtros de **Período**, **Segmento** e **País** em todas as páginas, sincronizados: uma seleção vale para o relatório inteiro.
- Botão **Limpar filtros** para remover todas as seleções de uma vez.

## Navegabilidade
- Menu com os botões Vendas, Lucro e Relatório no cabeçalho de cada página, substituindo o navegador lateral e os botões de voltar.
- A página atual fica destacada em lilás.
- Os botões mudam de cor ao **focalizar** (passar o mouse) e ao **selecionar** (clicar).
- Na página Vendas, os botões Segmento e Produto alternam o gráfico de barras por meio de indicadores.

## Visuais adicionados
- Cartões de indicadores nas três páginas (vendas, unidades, lucro, descontos, vendas brutas e custo).
- Vendas por país (página Vendas).
- Vendas por faixa de desconto (página Relatório).

## Ferramentas
Power BI Desktop: indicadores, botões com estados, segmentações sincronizadas, matriz, árvore de decomposição, cascata, gráfico de radar (visual personalizado) e treemap.
