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