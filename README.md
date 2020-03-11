# simulated-anealing-otimization
Simulated Anealing Otimization

<b>A implementação aqui apresentada bem como os documentos citados foi resultado do estudo das estratégias de otimização combinatorial durante a disciplina de mesmo nome da especialização em Telemática (IFTO).</b>

A coloração de grafos tem sido estuda desde 1852 por <i>Frederick Guthrie</i>, da universidade de Londres, o qual apresentou na época uma conjectura que daria origem a um dos maiores problemas da teoria dos grafos, a teoria das quatro cores, na qual seria possível pintar com apenas quatro cores as regiões de um mapa, respeitando as adjacências <i>[Rego et al., 2001]</i>.

O <i>Simulated Annealing</i> é uma meta-heurística baseada no recozimento de metais que procura uma solução ótima dentro de um espaço de soluções não conhecido, onde a exploração de todas as possíveis soluções é tecnicamente inviável. Utiliza as técnicas para encontrar um vizinho ótimo, e uma taxa de pertubação. Partindo de uma temperatura inicial alta que vai se resfriando para fugir da melhor solução local e explorar outros espaços de solução.

Vários trabalhos procurando buscar uma solução ótima, utilizando coloração de grafos, foram apresentados na literatura, comparando os resultados obtidos com novas implementações nas soluções, tais como:

 <ul>
  <li>
  Heurísticas Baseadas no Algoritmo de Coloração de Grafos para o problema de alocação de salas em uma instituição de ensino superior. Nesta implementação utilizou-se dois métodos, sendo o método do Melhor Vizinho capaz de obter soluções de custos médios menores que o método Primeiro Melhora, embora, este último tenha obtido menor tempo computacional.   Realizado por <i>[da Silva et al., 2010].</i>
  </li>
  <li>
  Algoritmos para o problema de coloração de grafos, por <i>[Regoetal.,2001]</i>. Neste artigo, o autor utilizou um algoritmo para obter uma solução inicial e posteriormente comparou estas soluções utilizando a meta-heurística SA e obteve melhorias significativas em relação solução inicial.
  </li>
  <li>
  Meta-heurística Busca Tabu para a problema de coloração de grafos apresentada e publicada nos Anais do XXXVII SBPO 2005 em Gramado – RS. O artigo trouxe uma contribuição com três procedimentos para a busca local, e uma nova heurística Busca Tabu que demonstrou ser competitiva com outras encontradas na literatura <i>[de Aguiar et al., 2005]</i>
  </li>
  <li>
  <i>Simulated Annealing</i> aplicado a um problema de roteirização e programação de veículos, elaborado no Instituto Nacional de Pesquisas Espaciais, apresentou uma nova abordagem para o problema de roteirização de veículos, na qual comparada a dois resultados obtidos na literatura, foi capaz de melhorar a qualidade do serviço, ou seja, foi capaz de atender aos clientes mais rapidamente, porém apresentou um acréscimo na distância percorrida pelos veículos  <i>[Mauri et al., 2006]</i>.
\end{itemize} 
  </li>
</ul> 

A implementação aqui apresentada deu origem à publicação do artigo "DESENVOLVIMENTO META-HEURÍSTICA BASEADA EM SIMULATED ANNEALING APLICADO A COLORAÇÃO DE GRAFOS PARA OTIMIZAÇÃO DE PROCESSOS", publicado em http://bit.ly/2IBNmnB. 

Este artigo está disposto da seguinte forma. A seção 2 apresenta a proposta deste trabalho com os objetivos. Na seção 3 foi demonstrada a metodologia usada para a implementação do algoritmo para a solução de coloração de grafos e o material utilizado. Na seção 4 os resultados encontrados com a implementação para os três grafos gerados são demonstrados. A seção 5 traz as conclusões sobre os resultados apresentados e, por fim, na seção 6 informa-se a linha para os trabalhos futuros.


<b> Referências </b>

<i> Irkpatrick, Scott, C. Daniel Gelatt, and Mario P. Vecchi. Optimization by simulated annealing In science 220.4598 (1983): 671680. </i>

<i>Mauri,Geraldo Regis and Lorena,Luiz Antonio Nogueira. SIMULATED ANNEALING APLICADO A UM PROBLEMA DE ROTEIRIZÇÃO E PROGRAMAÇÃO DE VEÍCULOS (2006). </i>

<i>daSilva,Douglas José and da Silva, Geiza Cristina. Heurísticas baseadas no algoritmo de coloração de grafos para o problema de alocação de salas em uma instituição de ensino superior. In Anais do XLII SBPO, Pages: 2839–2849 (2010)</i>

<i>Rego, Marcelo Ferreira and Santos, Haroldo Gambini. Algoritmos para o Problema de Coloração de Grafos. In Computational optimization and applications. Vol19,Number 2, Pages 165–178 (2001) </i>

<i>de Aguiar, Felipe Neves and Honorato, Gustavo de Sá Carvalho and Santos, Haroldo Gambini and Ochi, Luiz Satoru. Metaheurística busca tabu para o problema de coloração de grafos. In Anais do XXXVII SBPO. Pages 2497–2504 (2005) </i>
