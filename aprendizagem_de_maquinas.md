# Quais os tipos de aprendizagem de máquina e suas definições.

Aprendizagem supervisionada: São feitas entradas de rótulos e exemplos atuais a respectiva saída desejada e isso permite ao algoritmo aprender as regras que mapeiam entradas e saídas.  

Aprendizagem não supervisionada: Os rótulos não são fornecidos e, portanto, o algoritmo pode encontrar sua própria estrutura de processamento das entradas (por exemplo, encontrando padrões ocultos nos dados).

Aprendizagem por reforço: O algoritmo interage repetidamente com um ambiente dinâmico com um objetivo específico como, por exemplo, ganhar um jogo ou dirigir um carro. O algoritmo chega à solução mais otimizada para o problema por meio de repetidos erros e tentativas.

# Para cada tipo de aprendizagem de máquina apresente um exemplo que se encaixa com a sua definição.

Algoritmo de aprendizado supervisionado: Árvores de decisão: uma das estruturas de dados utilizadas na computação é a árvore. Ela possui elementos (nodos) raiz e nodos folha. As árvores de decisão utilizam essa estrutura como base para o seu funcionamento. Na árvore de decisão, uma decisão é tomada através do caminhamento a partir do nó raiz até o nó folha. Em outras palavras, é como se, ao fazermos uma pergunta, a resposta é encontrada ao se percorrer os nodos da árvore de decisão até que cheguemos a um nodo terminal.

Algoritmo de aprendizado não supervisionado: O K-means é um método de clusterização que particiona objetos de dados em k-grupos.
O agrupamento é feito por meio do cálculo da distância entre os objetos, de forma que cada elemento pertence ao grupo mais próximo da média da sua centroide, ou seja, mais similar a ele. O resultado é a divisão dos dados de forma similar a um Diagrama de Voronoi, ou seja, dividido em áreas. Mas como esse algoritmo funciona?
Inicialmente, são criadas k-centroides (aleatórias), que serão os grupos de dados resultantes.
A separação dos dados ocorre a partir do cálculo da distância entre os centros de todos os elementos da base de dados. 
Cada elemento é atribuído ao k mais próximo dele. A partir de então, as centroides são reposicionadas de acordo com a média das centroides dos elementos do grupo k (daí o nome k-means). O reposicionamento se repete até que os elementos estejam adequadamente no seu grupo k. Há ainda métodos que podem ser utilizados para auxiliar a definir qual é a quantidade ideal de k-centroides: Elbow Method e Silhouette Method.

Algoritmo de aprendizagem por reforço: Controle de Semáforo
No artigo “Sistema multiagente baseado em aprendizado por reforço para controle de sinais de tráfego de rede”, os pesquisadores tentaram projetar um controlador de semáforo para resolver o problema de congestionamento. Testados apenas em ambiente simulado, seus métodos mostraram resultados superiores aos métodos tradicionais e lançaram uma luz sobre os possíveis usos da RL de múltiplos agentes no projeto de sistemas de tráfego. Cinco agentes foram colocados na rede de tráfego de cinco cruzamentos, com um agente RL no cruzamento central para controlar a sinalização de tráfego. O estado foi definido como um vetor de oito dimensões, com cada elemento representando o fluxo de tráfego relativo de cada faixa. Oito opções estavam disponíveis para o agente, cada uma representando uma combinação de fases, e a função de recompensa foi definida como redução no atraso em comparação com o passo anterior. Os autores usaram o DQN para aprender o valor Q dos pares {state, action}.

