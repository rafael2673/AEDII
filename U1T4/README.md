# Descrição

Este trabalho foi desenvolvido  pelo discente Rafael Ribeiro Franco (20230093741) [@rafael2673](https://github.com/rafael2673) 
O vídeo gravado pode ser visto nesse [link](https://youtu.be/_XC9x6LtuQc)

# Objetivo Geral

O objetivo geral é por em prática as métricas estudadas em aula, sendo estas:
Cycles, Average Shortest Path Length, Diameter of
Network, Shortest Path Length, Connected
Components, Giant Connected Components, number
connected components, BFS, DFS, SCC, WCC,
Clustering Coefficient.

# Perguntas Elaboradas

Quão conectada é a rede viária de Natal?
Podemos responder essa pergunta analisando o número de componentes conectados. Uma cidade altamente conectada terá poucos componentes desconectados.

Qual é o tamanho do maior componente conectado na rede viária?
O tamanho do Giant Connected Component indica a parte mais significativa da rede em termos de conectividade.

Qual é o comprimento médio dos caminhos mais curtos na rede?
O comprimento médio dos caminhos mais curtos oferece uma ideia de quão fácil é atravessar a cidade usando a rede viária.

Qual o diâmetro da rede viária de Natal?
O diâmetro indica a maior distância possível entre dois pontos na rede, refletindo os pontos mais distantes no maior componente conectado.

Qual o coeficiente de aglomeração da rede viária?
Um alto coeficiente de aglomeração pode indicar que a rede tem uma estrutura altamente interconectada, característica importante em redes com redundância de caminhos.

A rede viária de Natal possui clusters ou comunidades bem definidas?
Com base no coeficiente de aglomeração e na análise de componentes fortemente conectados (SCC) e componentes fracamente conectados (WCC), podemos inferir a presença de comunidades ou áreas com alta densidade de conexões.

Qual é a distribuição das distâncias entre pontos na rede?
Usando a métrica de comprimento médio dos caminhos mais curtos, podemos identificar se a cidade tem uma estrutura compacta ou se possui distâncias grandes entre algumas regiões.

# Requisitos do Trabalho
- Usando como fonte de estudo os notebooks do OSMnx e a documentação da
biblioteca, criar um exemplo que use de alguma forma a rede, ou parte dela,
referente a cidade de Natal-RN.
- Elaborar perguntas cujas as respostas podem ser respondidas com as
métricas estudadas na aula de segunda-feira (14/10/2024).
- Implementar um notebook com o código gerado, arquivo README com a
descrição do que foi feito e os principais resultados (figuras + explicação).
- Fazer a gravação de um vídeo de até 10min explicando tudo o que foi feito. O
link do vídeo deverá estar no arquivo README.
- Todo o trabalho deverá estar em um repositório do Github
