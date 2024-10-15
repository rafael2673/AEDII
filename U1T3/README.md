# Descrição

Este trabalho foi desenvolvido em dupla com os discentes Rafael Ribeiro Franco (20230093741) [@rafael2673](https://github.com/rafael2673) 
e Matheus Carvalho da Silva (20230093670) [@matheuscs123](https://github.com/matheuscs123)
O vídeo gravado pode ser visto nesse [link](https://www.youtube.com/watch?v=BRLuaIO3vHA)

## Objetivo Geral

O trabalho proposto tem como objetivo analisar e identificar informações baseado nos dados de medicamentos cadastrados na base do governo [ANVISA](https://dados.gov.br/dados/conjuntos-dados/medicamentos-registrados-no-brasil)
e testar hipóteses que guiam o desenvolvimento dos grafos e a análise de assortatividade.

## Hipóteses a serem testadas:
1. Hipótese da Categoria Regulatória:
   - Medicamentos da mesma categoria regulatória tendem a compartilhar mais princípios ativos?
2. Hipótese da Empresa:
   - Medicamentos da mesma empresa tendem a compartilhar mais princípios ativos?
3. Hipótese da Complexidade:
   - Medicamentos com mais princípios ativos tendem a se conectar com medicamentos de similar complexidade?
  
## Rede #01

<b>Co-ocorrência de Princípios Ativos entre Medicamentos</b>
- Nós (vértices): Cada medicamento é um nó.
- Arestas (Edges): Existe uma aresta entre dois medicamentos se eles
compartilham ao menos um princípio ativo.
- Assortatividade: Calcular a assortatividade com base na categoria
regulatória dos medicamentos.
- Pergunta a ser respondida:
  - Medicamentos da mesma categoria regulatória tendem a compartilhar princípios ativos?
## Rede #02
<b>Grafo Bipartido de Medicamentos e Princípios Ativos</b>
- Nós (vértices): Medicamentos e princípios ativos são nós distintos.
- Arestas (Edges): Uma aresta conecta um medicamento aos seus
respectivos princípios ativos.
- Assortatividade: Calcular a assortatividade por grau dentro do grafo
bipartido para determinar se os princípios ativos que se conectam a
medicamentos complexos (com muitos princípios ativos) tendem a se
conectar também a medicamentos com perfis de complexidade
semelhante.
- Pergunta a ser respondida:
  - Princípios ativos compartilhados por medicamentos complexos tendem a se conectar a medicamentos com perfis de complexidade similar?
## Rede #03
<b>Co-ocorrência por Empresa ou Classe Terapêutica</b>
- Nós (Nodes): Cada medicamento é um nó.
- Arestas (Edges): Existe uma aresta entre dois medicamentos se eles
compartilham ao menos um princípio ativo.
- Assortatividade: Calcular a assortatividade com base na empresa ou classe
terapêutica dos medicamentos.
- Pergunta a ser respondida:
  - Medicamentos da mesma empresa ou classe terapêutica tendem a compartilhar mais princípios ativos?
 
## Instruções para o trabalho
- Desenvolver as 3 redes propostas usando Python e Networkx.
- Organizar o projeto em um repositório no GitHub com o código estruturado.
- Incluir um README com os resultados, as figuras geradas, a identificação do
grupo e o link para um vídeo de até 10 minutos explicando a abordagem, os
resultados e conclusões.
- Utilizar as técnicas de visualização de redes descritas no notebook "The Art of
Seeing Networks" ao gerar as figuras.
- Trabalho poderá ser realizado individualmente, dupla ou trio.
- Na submissão da tarefa informar apenas o link do repositório. 
- O trabalho irá compor 1,5 pontos na Unidade 1.
- Prazo para entrada: 15 de outubro de 2024 (terça-feira) até as 23h59.
