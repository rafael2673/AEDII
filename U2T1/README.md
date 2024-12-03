# Descrição

Este trabalho foi desenvolvido em dupla com os discentes Rafael Ribeiro Franco (20230093741) [@rafael2673](https://github.com/rafael2673) 
e Matheus Carvalho da Silva (20230093670) [@matheuscs123](https://github.com/matheuscs123)
O vídeo gravado pode ser visto nesse [link](https://www.loom.com/share/beec74e5e9b84657abac8d63c571ca0a?sid=f5193f6c-0656-4cf8-8f86-026b0b3fe31b)

# Objetivo

- Utilizando o Gephi, aplicar os conhecimentos vistos no curso para analisar a rede
de co-autoria dos professores permanentes do Programa de Pós-Graduação em
Engenharia Elétrica e de Computação (PPgEEC)
- Base de dados: https://abre.ai/ltcE

## Requisito #01
- A partir da rede construída gerar
figuras similares utilizando o Gephi.
- O tamanho do vértice deverá ser
proporcional a quantidade de
vizinhos. Que outra métrica faria
sentido ser o tamanho do vértice?
- As cores devem ser relacionadas com
  - Closeness ou Betweenness ou
Eigenvector Centrality
- Adote um layout que seja razoável
perceber a diferença entre as cores
do vértices. As figuras devem ser
acompanhadas de
descrições/explicações.

As imagens abaixo foram geradas utilizando a propriedade Ranking da aba de Nodes do Appearence com as seguintes cores:
- azul - 1D138F
- azul claro - 88DAD7
- amarelo - E7F041
- vermelho - FF1A24

### Degree Centrality
A primeira métrica mostrada é a Degree Centrality, ela é usada para quantificação da importância de um nó com base no número de conexões diretas que ele possui. Foram filtrados os dados para que mostrasse o nome apenas dos que tivessem essa métrica maior que 165 conexões.
![Degree_Centrality](https://github.com/user-attachments/assets/86259c91-1b06-4063-8e8d-6e5a56e34da1)

### Closeness Centrality
A segunda métrica mostrada é a Closeness Centrality que mede a proximidade de um nó em relação a todos os outros na rede. Está sendo mostrado o nome dos autores com média maior ou igual a 0.45953 aproximadamente.
![Closeness_Centrality](https://github.com/user-attachments/assets/55330b18-7e4d-456b-b469-17df9431c8a9)

### Betweeness Centrality
A terceira métrica foi a Betweeness centrality que mede quantas vezes um nó aparece nos caminhos mínimos entre outros pares de nós. Está sendo mostrado o nome daqueles que tem a média maior ou igual a 0.06995 aproximadamente.
![Betweenness_Centrality](https://github.com/user-attachments/assets/0ae41216-e279-47c5-b9fe-c565fdfdfdda)

### Eigenvector Centrality
A quarta e última métrica foi a Eigenvector centrality que mede a influência de um nó na rede com base na importância dos nós a que está conectado. Um nó com alto índice está conectado a outros nós influentes. Está sendo mostrado o nome aqueles que tem a média maior ou igual a 0.56116 aproximadamente.
![Eigenvector_Centrality](https://github.com/user-attachments/assets/180772fe-f9de-4c05-8559-ebcaf9bf9a78)

## Requisito #02
- A partir da rede construída
gerar uma figura similar no
gephi destacando o k-core e
o k-shell da rede. O layout é
de livre escolha. Os vértices
devem ter um tamanho
proporcional a propriedade
degree. A figura deverá estar
acompanhada de
descrição/explicação.

### 10-Shell (vermelho), 11-Core (azul)
Foi feito uma exportação para o python cujo código utilizado está nesta pasta para calcular o K-core e o K-shell. O resultado de ambos foram 18. Está sendo colorido o grupo 10 e o grupo 11 como mostrado no título.
![k-core_k-shell](https://github.com/user-attachments/assets/d13c51be-8a02-4fe1-a2c6-6e71e2b4a50c)

## Requisito #03
- A rede deverá estar em
produção de forma análoga
ao explicado na Semana 6.
As cores deverão ser
relacionadas ao critério de
comunidade e o tamanho do
vértice a uma métrica de
livre escolha

[link direto](https://rafael2673.github.io/AEDII/U2T1/network)

# Requisitos
- Trabalho individual ou em dupla
- Entregável: link para o repositório do projeto no github e contendo: códigos
utilizados (notebooks ou scripts python), README identificando o grupo,
detalhes para reprodução do código e o link para um vídeo no Loom (ou
ferramenta similar) de até 10min descrevendo os resultados e como foi feito.
- A inexistência do vídeo de apresentação irá impactar nota zero no trabalho.
- Trabalho irá compor 3,00 pontos na Unidade 2.

