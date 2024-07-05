---
title: Carga variável e esforços
layout: default
parent: Exemplo I
nav_order: 4
has_children: false
has_toc: false
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Análise estrutural: carregamento variável</h1> 

<p align = "justify">
O carregamento variável que atua sobre a longarina é o carregamento do trem tipo brasileiro (TB-450) conforme descrito na NBR 7188. A carga móvel é constituida pelo veículo tipo de 450 kN e carga de multidão de 5 kN/m².
Considerando a seção da ponte exposta anteriormente e que a posição mais desfavorável é encostada na barreira de proteção em concreto armado temos a <a href="#fig1">Figura 1</a> que demarca a posição do veículo tipo na seção. 
</p>

<center><img src="assets/images/perfil.png" width="100%"></center>
<p align = "left"><b><a href="#fig1">Figura 1</a>.</b> Posição do veículo tipo na seção.</p>

<p align = "justify">
De forma a obter as reações provocadas por este veículo na seção transversal da longarina aplica-se o conceito de linha de influência de reação para determinar esse carregamento. Portanto aplicando esse conceito chega-se a seguinte linha de influência:
</p>

<center><img src="assets/images/perfil.png" width="100%"></center>
<p align = "center">(a) Linha para seção veículo + carga distribuída.</p>
<center><img src="assets/images/perfil.png" width="100%"></center>
<p align = "center">(b) Linha para seção somente carga distribuída.</p>
<p align = "left"><b><a href="#fig2">Figura 2</a>.</b> Linha de influência de reação de apoio na seção transversal da ponte.</p>

<p align = "justify">
Poranto é possível determinar as cargas (<i>P</i> pontual e <i>Q</i> distribuída) na seção conforme equações <a href="#eq1">(1)</a> e <a href="#eq2">(2)</a>.
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ P = p \cdot \delta \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ Q = q \cdot A_{dig}\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq2">(2)</p></td>
    </tr>
</table>

<p align = "justify">
Onde:
<ul>
    <li>\( p \) é a carga pontual que atua na seção;</li>
    <li>\( \delta \) é a ordenada da linha de influência no abscissa da carga \(p\);</li>
    <li>\( q \) é a carga distribuída que atua na seção;</li>
    <li>\( A_{dig} \) é a área do diagrama da linha de influência.</li>
</ul>

Aplicando as equações chega-se então nas seguintes cargas para a seção veículo + carga de multidão e somente multidão. A <a href="#fig3">Figura 3</a> apresenta a carga final que será inserida no <i>software</i> de análise estrutural para determinação dos valores dos esforçso de flexão.
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ ch_{a,k} = 0.50 \cdot p_{0,k}^{t} + 0.50 \cdot p_{1,k}^{t}\]</td>
        <td style="width: 10%;">carga pontual</td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ ch_{b,k} = 1.50 \cdot p_{0,k}^{t} - 0.50 \cdot p_{1,k}^{t}\]</td>
        <td style="width: 10%;">carga distribuída interna</td>        
    </tr>
    <tr>
        <td style="width: 90%;">\[ ch_{b,k} = 1.50 \cdot p_{0,k}^{t} - 0.50 \cdot p_{1,k}^{t}\]</td>
        <td style="width: 10%;">carga distribuída externa</td>        
    </tr>
</table>

<center><img src="assets/images/perfil.png" width="100%"></center>
<p align = "left"><b><a href="#fig3">Figura 3</a>.</b> Carga móvel que será aplicada na longarina.</p>

<p align = "justify">
Determinada a carga móvel que atuará na longarina utiliza-se o <i>software</i> Ftool para a determinação dos esforços de flexão. Aqui cabe a ressalva da aplicação dos coeficientes de amplicação dinâmica do carregamento. Portanto serão aplicados os coeficientes ponderação CIV, CNF e CIA conforme equações <a href="#eq1">(1)</a> a <a href="#eq4">(4)</a>:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ ch_{a,k} = 0.50 \cdot p_{0,k}^{t} + 0.50 \cdot p_{1,k}^{t}\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ ch_{a,k} = 0.50 \cdot p_{0,k}^{t} + 0.50 \cdot p_{1,k}^{t}\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ ch_{b,k} = 1.50 \cdot p_{0,k}^{t} - 0.50 \cdot p_{1,k}^{t}\]</td>  
        <td style="width: 10%;"><p align = "right" id = "eq2">(2)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ ch_{c,k} = -0.50 \cdot p_{0,k}^{t} + 1.50 \cdot p_{1,k}^{t}\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(4)</p></td>
    </tr>
</table>

<p align = "justify">
Determinando os coeficientes de ponderação chegamos aos seguintes valores:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ ch_{a,k} = 0.50 \cdot p_{0,k}^{t} + 0.50 \cdot p_{1,k}^{t}\]</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ ch_{a,k} = 0.50 \cdot p_{0,k}^{t} + 0.50 \cdot p_{1,k}^{t}\]</td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ ch_{b,k} = 1.50 \cdot p_{0,k}^{t} - 0.50 \cdot p_{1,k}^{t}\]</td>  
    </tr>
    <tr>
        <td style="width: 90%;">\[ ch_{b,k} = 1.50 \cdot p_{0,k}^{t} - 0.50 \cdot p_{1,k}^{t}\]</td>  
    </tr>
</table>

<p align = "justify">
Com o valor o total do coeficiente de ponderação e das cargas determinadas chegamos aos esforços da <a href="#tab">Tabela 1</a>. Aqui ressaltamos que a carga móvel produzirá uma envoltórias de esforços máximos e mínimos.
</p>

<p align = "left"><b><a href="#tab1">Tabela 1</a>.</b> Esforços de flexão nas seções de interesse considerando carga móvel.</p>

<table style="width: 100%"><thead>
  <tr>
    <th>Seção</th>
    <th>x (m)</th>
    <th>V<sub>min</sub> (kN)</th>
    <th>V<sub>max</sub> (kN)</th>
    <th>M<sub>min</sub> (kN)</th>
    <th>M<sub>max</sub> (kN)</th>
  </tr></thead>
<tbody>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
</tbody>
</table>

<p align = "justify">
As seguintes fórmulas serão necessárias:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ CIV = 1,0 +  1,06 \cdot ((20)/(20+50)) = 1,3029 m </td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ CNF = 1 - 0,05 \cdot (n-2) = 1 - 0,05 \cdot (2-2) = 1</td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ CIA = 1,25 para obras em concreto ou mistas.</td>  
    </tr>
    <tr>
        <td style="width: 90%;">\[ Coeficiente = CIV \cdot CNF \cdot CIA = 1,3029 \cdot 1 \cdot 1,25 = 1,6286</td>  
    </tr>
</table>

    <p align = "justify">
Para calcular o trem tipo da ponte em questão, tem-se:
</p>
<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ 	φ (fí) = 1,4 \cdot 0,7% \cdot 20 = 1,26</td>
    </tr>
</table>
    <p align = "justify">
Logo, para o cálculo das coordenadas, fez-se:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ \frac{1}{5} = \frac{a}{6,37} \therefore a = 1,274 </td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ \frac{1}{5} = \frac{b}{(6,37-2} \therefore b = 0,8740 </td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ \frac{1}{5} = \frac{c}{(6,37+0,5)} \therefore c = 1,3740 </td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ \frac{1}{5} = \frac{d}{(6,37-2-0,5)} \therefore d = 0,7740 </td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ \frac{1}{5} = \frac{e}{(5+1,37+0,63)} \therefore e = 1,4000 </td>  
    </tr>
    <tr>
        <td style="width: 90%;">\[  \frac{1}{5} = \frac{f}{(5+1,37+0,63-(0,15+0,38))} \therefore f = 1,2900  </td>  
    </tr>
</table>

    <p align = "justify">
Com os resultados apresentados acima, em seguida serão calculadas as respectivas áreas.
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ A1 = (1,4 + 1,3740) \cdot 0,55) /2 \therefore A1 = 0,7629 m </td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ A2 = (3,87 \cdot (\frac{0,774}{(2)) \therefore A2 = = 1,4977 m </td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ A3 = (1,4 + 1,29) \cdot \frac{0,38}{(2) \therefore A3 = = 0,511 m </td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ A4 = 6,47 \cdot \frac{1,29}{2} \therefore A4 = 4,1732 m  </td>
    </tr>
    </table>

<p align = "justify">
Com isso, pode-se calcular o PR (peso por roda):
</p>
<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ PR = P \cdot φ \cdot (a + b) </td>
    </tr>
        <tr>
        <td style="width: 80%;">\[ PR = 75 \cdot 1,26 \cdot (1,274 + 0,874) \therefore PR = 202,986 kN </td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ m' = p' \cdot + p \cdot φ \cdot A2  </td>
    </tr>
        <tr>
        <td style="width: 80%;">\[ m' = 3,0 \cdot 0,7629 + 5 \cdot 1,26 \cdot 1,4977 \therefore m' = 11,7242 kN/m </td>
    </tr>
        <td style="width: 80%;">\[ m = A3 \cdot p' + A4 \cdot φ \cdot p</td>
    </tr>
        <tr>
        <td style="width: 80%;">\[ m = 0,511 \cdot 3,0 + 4,1732 \cdot 1,26 \cdot 5 \therefore m = 27,8242 kN/m </td>
    </tr>

</table>

<p align = "justify">
Com isso,  pode-se calcular o PRsimp:
</p>
<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ PRsimp = PR - (((m-m') \cdot 6) / 3) </td>
    </tr>
        <tr>
        <td style="width: 80%;">\[ PRsimp = 202,99 - (((27,8242-11,7242) \cdot 6) /3 </td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ PRsimp = 170,79 kN </td>
    </tr>


</table>
