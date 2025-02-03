---
title: Carga permanente e esforços
layout: default
parent: Exemplo I - Pontes duas longarinas
nav_order: 3
has_children: false
has_toc: false
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Determinação carregamento permanente</h1> 

<p align = "justify">
O carregamento permanente advém da determinação da área da seção transversal dos elementos que compõem a seção da ponte. O carregamento permanente advém da determinação da área da seção transversal dos elementos que compõem a seção da ponte. 
</p>

<p align = "justify">
As densidades dos materiais empregados para essa análise são:
</p>

<ul>
  <li><i>γ<sub>c</sub></i> = 25 kN/m³ para peças de concreto armado (Barreira + seção da ponte);</li>
  <li><i>γ<sub>pavto</sub></i> = 24 kN/m³ para o pavimento flexível.</li>
</ul>

<p align = "justify">
Áreas que compõem a seção:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ A_c = 2 \cdot \left(1 \cdot 0,45\right) + 2 \cdot \left(1,78 \cdot 0,21\right) + 4,54 \cdot 0,21 = 2,60 m² \]</td>
        <td style="width: 20%;">tabuleiro + longarina</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ A_{barreira} = 0,19 \; m² \]</td>
        <td style="width: 20%;">barreira de concreto</td>        
    </tr>
    <tr>
        <td style="width: 80%;">\[ A_{pavto} = 8,24 \cdot 0,08 = 0,66 \; m² \]</td>
        <td style="width: 20%;">pavimento flexível</td>
    </tr>
</table>

<p align = "justify">
O valor total do carregamento atuante na seção é dado a seguir:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ g_{pp} =  \frac{2,60}{2} \cdot 25 = 32,50 \; kN/m\]</td>
        <td style="width: 20%;">longarina + tabuleiro</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ g_{barreira} = 0,19 \cdot 25 = 4,75 \; kN/m\]</td>
        <td style="width: 20%;">barreira de concreto</td>        
    </tr>
    <tr>
        <td style="width: 80%;">\[ g_{pavto+recap} = \frac{0,66}{2} \cdot 24 + \frac{2 \cdot 8,24}{2} = 16,16 \; kN/m \]</td>
        <td style="width: 20%;">pavimento flexível + recapeamento</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ g_{total} = g_{pp} + g_{barreira} + g_{pavto+recap} + g_{gcmetalico} = 32,50 + 4,75 + 16,16 + 1 = 54,41 \; kN/m\]</td>
        <td style="width: 20%;"><font color="#D2691E"><b>carregamento total</b></font></td>
    </tr>
</table>

<p align = "justify">
Logo é possível definir o carregamento permanente que atuará na ponte de concreto é de 53,51 kN/m.
</p>

<h1>Esforços</h1> 

<p align = "justify">
Para determinação dos esforços será empregado o <i>software</i> Ftool. E neste lançamento estrutural serão definidas seções para determinação dos esforços. Será empregado uma divisão de <i>l/4</i> para os balanços e  <i>L/10</i> para o meio do vão.
<br><br>
Considerando o <i>f<sub>ck</sub></i> de 30 MPa e um agregado de granito o módulo de elasticidade do concreto (<i>E<sub>c</sub></i>) será de 27 GPa (Módulo secante).
<br><br>
A <a href="#tab1">Tabela 1</a> apresenta os esforços de momento e cisalhamento.
</p>

<p align = "left"><b><a href="#tab1">Tabela 1</a>.</b> Esforços por seção delimitada.</p>
<table style="width: 100%"><thead>
  <tr>
    <th>Seção</th>
    <th>x (m)</th>
    <th>V<sub>g</sub> (kN)</th>
    <th>M<sub>g</sub> (kN.m)</th>
  </tr></thead>
<tbody>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>B-0</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
</tbody>
</table>
