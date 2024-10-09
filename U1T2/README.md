# Descrição

Este trabalho foi desenvolvido em dupla com os discentes Rafael Ribeiro Franco (20230093741) [@rafael2673](https://github.com/rafael2673) e Matheus Carvalho da Silva (20230093670) [@matheuscs123](https://github.com/matheuscs123)

O vídeo gravado pode ser visto nesse [link](https://drive.google.com/file/d/1UfIMHfSjVUEQKW3lh8-vhzHa26FQwmD5/view?usp=sharing)

## Objetivo Geral
O trabalho proposto tem como objetivo reforçar
conceitos de grafos utilizando a biblioteca
NetworkX no Python. A ideia central é que vocês,
individualmente ou em duplas, criem e manipulem
uma rede de co-autoria a partir de dados reais
extraídos da plataforma Scopus.

## Passo #01

<b>Exportação de Dados:</b>

- A partir da plataforma Scopus, vocês deverão extrair um arquivo .csv
que contenha informações de artigos publicados por autores da UFRN.
Esse conjunto pode ser filtrado por uma área específica (como saúde,
engenharia, computação, etc.), por múltiplas áreas ou ainda por temas
de interesse, como "machine learning", "inteligência artificial", "redes
complexas", etc.
- O arquivo .csv deve conter, no mínimo, as seguintes colunas:
  - Nome dos autores
  - Identificadores únicos dos autores
  - Título do artigo
  - Ano de publicação

## Passo #02

<b>Criação da Rede de Co-Autoria:</b>
- Utilizando os dados extraídos, vocês deverão criar uma rede de
co-autoria. Neste grafo, os vértices serão os autores e as arestas
representarão a colaboração entre eles. Por exemplo, se um artigo foi
escrito por três autores (A1, A2, A3), as arestas (A1, A2), (A1, A3), e (A2, A3)
serão criadas no grafo.

## Passo #03
<b>Análises na Rede:</b>

- Com a rede criada, vocês deverão realizar as seguintes análises
utilizando o NetworkX (use as funções já implementadas na ferramenta):
  - Densidade da Rede: Calcular a densidade, que mede o quão
conectados estão os autores em relação ao número máximo
possível de conexões.
  - Sub-Grafo: Gerar um sub-grafo contendo apenas os vértices que
possuem pelo menos X vizinhos (X será um valor a ser definido por
vocês). Calcular a densidade desse sub-grafo.
  - Histograma dos Graus: Criar um gráfico de histograma mostrando
a distribuição do grau dos vértices da rede. O grau de um vértice
representa o número de co-autores com os quais ele colaborou.

## Passo #04
<b>Entrega e Avaliação:</b>
- O trabalho deve ser entregue em formato de repositório no GitHub,
onde vocês deverão incluir todos os códigos utilizados, dados
processados e um arquivo README explicando o processo.
- Na submissão mencionar o link do repositório e inserir os códigos
desenvolvidos em um .zip no anexo.
- Além disso, cada grupo deverá gravar um vídeo explicativo de até 10
minutos na plataforma Loom ou software similar, descrevendo o que foi
feito e justificando as escolhas feitas durante o desenvolvimento.
- O trabalho vale 1,5 pontos na Unidade 1.

## Regras:
- O trabalho pode ser realizado individualmente ou em duplas.
- Vocês devem seguir boas práticas de programação, incluindo
comentários explicativos no código.
- O repositório deverá estar bem organizado, com o arquivo README
explicando o que foi feito, descrevendo resultados, mostrando imagens
geradas, link da gravação do vídeo, e outras informações que acharem
pertinentes.
- Indicar ainda no início do arquivo README os nomes completos dos
componentes do grupo.
- Prazo: 08 de outubro, terça-feira até às 23h59.
- Os grupos estão livres para uso de ferramentas de inteligência artificial
que auxilie na solução do trabalho.
