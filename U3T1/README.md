# Descrição

Este trabalho foi desenvolvido em dupla com os discentes Rafael Ribeiro Franco (20230093741) [@rafael2673](https://github.com/rafael2673) 
e Matheus Carvalho da Silva (20230093670) [@matheuscs123](https://github.com/matheuscs123).

Link do artigo [medium](https://medium.com/@rafael.franco.123/an%C3%A1lise-dos-livros-de-sherlock-holmes-com-python-gera%C3%A7%C3%A3o-de-grafos-2610492ee084)
Ouça o podcast [aqui](https://notebooklm.google.com/notebook/b839ba07-c450-40b5-9f24-8272fd81f738)

O trabalho consiste na realização de uma análise de redes baseada em processamento de linguagem natural (NLP) e ferramentas de grafos. O objetivo é explorar relações linguísticas e criar uma solução completa, indo da análise de texto até a colocação em produção de um grafo interativo, com documentação detalhada em um artigo no Medium.

## Requisitos

### Requisito 1: Seleção e Preparação dos Textos

- Escolher um ou mais textos de diferentes fontes (por exemplo, jornais, livros, ou artigos online).
- Caso opte por fontes jornalísticas, comparar grafos gerados de uma mesma notícia veiculada por diferentes meios (Globo, UOL, Carta Capital, etc.).
- Realizar limpeza dos dados (remover linhas desnecessárias, corrigir pontuação, normalizar textos).

### Requisito 2: Análise de PoS Tagging e NER

- Usar a biblioteca NLTK ou spaCy para identificar categorias gramaticais (PoS) e entidades nomeadas (NER).
- Para as categorias gramaticais trabalhar com NNP.
- Trabalhar com entidades como PERSON, ORG, e GPE.
- Documentar o processo de análise e salvar os resultados intermediários para inclusão da nota técnica final.

### Requisito 3: Geração de Redes

- Criar uma rede com base nas relações entre as entidades extraídas.
- Utilizar a biblioteca NetworkX para construir e manipular a estrutura do grafo.
- Comparar os grafos gerados a partir de diferentes textos ou fontes.

### Requisito 4: Análise da Rede

- Calcular métricas como grau, centralidade e densidade.
- Identificar padrões e características, como clusters, hubs ou comunidades relevantes.
- Incorporar visualizações intermediárias (ego network, k-core, etc) para análise qualitativa.

### Requisito 5: Visualização e Produção do Grafo

- Utilizar NetworkX e Gephi para criar uma visualização interativa.
- Colocar o grafo em produção e disponibilizá-lo online, seguindo os métodos apresentados em sala.

### Requisito 6: Documentação e Divulgação

- Criar um artigo no Medium descrevendo detalhadamente todas as etapas realizadas, desde a escolha dos textos até a análise e produção do grafo. Considere [este link](https://blog.devops.dev/learn-how-to-easily-improve-your-neural-network-in-practice-419e5402b4fa) como referência.
- O artigo deverá conter:
  - Descrição do processo: objetivos, ferramentas utilizadas e desafios enfrentados.
  - Resultados obtidos: insights sobre os grafos gerados e as análises realizadas.
  - Links relevantes:
    - Link para o repositório GitHub do projeto com o código e os dados utilizados.
    - Link para um podcast, criado com o Notebooklm, explicando os principais conceitos abordados no trabalho.
    - Link para o grafo em produção.
- Submissão no SIGAA: enviar o link do artigo no Medium.

## Critérios de Avaliação

1. Qualidade do Código (30%):
   - Estrutura, funcionalidade e documentação do código no GitHub.
2. Análise e Produção do Grafo (30%):
   - Relevância das métricas calculadas e insights gerados.
   - Colocação em produção do grafo interativo.
3. Artigo no Medium (20%):
   - Clareza, detalhamento e inclusão dos links necessários.
   - Condição necessária para a nota. Ou seja, sem o artigo a nota do trabalho será zero.
4. Podcast (10%):
   - Explicação clara e coerente dos conceitos, com linguagem dinâmica e acessível.
5. Originalidade e Rigor (10%):
   - Escolha criativa dos textos e rigor na análise realizada.
