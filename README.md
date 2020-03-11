# simulated-anealing-otimization
Simulated Anealing Otimization

<b>A implementação aqui apresentada bem como os documentos citados foi resultado do estudo das estratégias de otimização combinatorial durante a disciplina de mesmo nome da especialização em Telemática (IFTO).</b>

A coloração de grafos tem sido estuda desde 1852 por <i>Frederick Guthrie</i>, da universidade de Londres, o qual apresentou na época uma conjectura que daria origem a um dos maiores problemas da teoria dos grafos, a teoria das quatro cores, na qual seria possível pintar com apenas quatro cores as regiões de um mapa, respeitando as adjacências <i>[Rego et al., 2001]</i>.

O <i>Simulated Annealing</i> é uma meta-heurística baseada no recozimento de metais que procura uma solução ótima dentro de um espaço de soluções não conhecido, onde a exploração de todas as possíveis soluções é tecnicamente inviável. Utiliza as técnicas para encontrar um vizinho ótimo, e uma taxa de pertubação. Partindo de uma temperatura inicial alta que vai se resfriando para fugir da melhor solução local e explorar outros espaços de solução.

Vários trabalhos procurando buscar uma solução ótima, utilizando coloração de grafos, foram apresentados na literatura, comparando os resultados obtidos com novas implementações nas soluções, tais como:

 <ul>
  <li>
  Heurísticas Baseadas no Algoritmo de Coloração de Grafos para o problema de alocação de salas em uma instituição de ensino superior. Nesta implementação utilizou-se dois métodos, sendo o método do Melhor Vizinho capaz de obter soluções de custos médios menores que o método Primeiro Melhora, embora, este último tenha obtido menor tempo computacional.   Realizado por \cite{daSilva2010}
  </li>
  <li>
  Algoritmos para o problema de coloração de grafos, por \cite{Rego2001}. Neste artigo, o autor utilizou um algoritmo para obter uma solução inicial e posteriormente comparou estas soluções utilizando a meta-heurística SA e obteve melhorias significativas em relação solução inicial.
  </li>
  <li>
  Meta-heurística Busca Tabu para a problema de coloração de grafos apresentada e publicada nos Anais do XXXVII SBPO 2005 em Gramado – RS. O artigo trouxe uma contribuição com três procedimentos para a busca local, e uma nova heurística Busca Tabu que demonstrou ser competitiva com outras encontradas na literatura \cite{deAguiar2015}
  </li>
  <li>
  <i>Simulated Annealing</i> aplicado a um problema de roteirização e programação de veículos, elaborado no Instituto Nacional de Pesquisas Espaciais, apresentou uma nova abordagem para o problema de roteirização de veículos, na qual comparada a dois resultados obtidos na literatura, foi capaz de melhorar a qualidade do serviço, ou seja, foi capaz de atender aos clientes mais rapidamente, porém apresentou um acréscimo na distância percorrida pelos veículos  \cite{Mauri2006}.
\end{itemize} 
  </li>
</ul> 

A implementação aqui apresentada deu origem à publicação do artigo "DESENVOLVIMENTO META-HEURÍSTICA BASEADA EM SIMULATED ANNEALING APLICADO A COLORAÇÃO DE GRAFOS PARA OTIMIZAÇÃO DE PROCESSOS", publicado em http://bit.ly/2IBNmnB. 

Este artigo está disposto da seguinte forma. A seção 2 apresenta a proposta deste trabalho com os objetivos. Na seção 3 foi demonstrada a metodologia usada para a implementação do algoritmo para a solução de coloração de grafos e o material utilizado. Na seção 4 os resultados encontrados com a implementação para os três grafos gerados são demonstrados. A seção 5 traz as conclusões sobre os resultados apresentados e, por fim, na seção 6 informa-se a linha para os trabalhos futuros.
