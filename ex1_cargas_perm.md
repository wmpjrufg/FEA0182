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
  <li><i>γ<sub>c</sub></i> = 25 kN/m³ para peças de concreto armado (aplica-se a barreira e seção da ponte);</li>
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
        <td style="width: 80%;">\[ g_{gcmetalico} = 1 \; kN/m \]</td>
        <td style="width: 20%;">Guarda corpo metálico</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ g_{total} = g_{pp} + g_{barreira} + g_{pavto+recap} + g_{gcmetalico} = 32,50 + 4,75 + 16,16 + 1 = 54,41 \; kN/m\]</td>
        <td style="width: 20%;"><font color="#D2691E"><b>carregamento total</b></font></td>
    </tr>
</table>

<p align = "justify">
Logo é possível definir o carregamento permanente que atuará na ponte de concreto é de 54,41 kN/m.
</p>

<h1>Esforços</h1> 

<p align = "justify">
Para determinação dos esforços será empregado o <i>software</i> Ftool. E neste lançamento estrutural serão definidas seções para determinação dos esforços. Será empregado uma divisão de <i>l/4</i> para os balanços e <i>l/10</i> para o meio do vão.
<br><br>
Considerando o <i>f<sub>ck</sub></i> de 30 MPa e um agregado de granito o módulo de elasticidade secante do concreto (<i>E<sub>c</sub></i>). Os esforços finais são apresentados na <a href="#tab1">Tabela 1</a>. A <a href="#fig1">Figura 1</a> apresenta a distribuição das seções.
</p>

<p align = "left"><b><a href="#fig1">Figura 1</a>.</b> Distribuição das seções da ponte.</p>
<center><img src="assets/images/exemplo_i/carga_perm/fig_01_secoes.png" width="100%"></center>
<br>
<p align = "left"><b><a href="#tab1">Tabela 1</a>.</b> Esforços de flexão simples para viga nas seções demarcadas.</p>
<table style="width: 100%"><thead>
  <tr>
    <th>Seção</th>
    <th>x (m)</th>
    <th>V<sub>g</sub> (kN)</th>
    <th>M<sub>g</sub> (kN.m)</th>
  </tr></thead>
<tbody>
  <tr>
    <td><center>A-0</center></td>
    <td><center>0</center></td>
    <td><center>0</center></td>
    <td><center>0</center></td>
  </tr>
  <tr>
    <td><center>A-1</center></td>
    <td><center>0,75</center></td>
    <td><center>-40,81</center></td>
    <td><center>-15,30</center></td>
  </tr>
  <tr>
    <td><center>A-2</center></td>
    <td><center>1,50</center></td>
    <td><center>-81,62</center></td>
    <td><center>-61,21</center></td>
  </tr>
  <tr>
    <td><center>A-3</center></td>
    <td><center>2,25</center></td>
    <td><center>-122,42</center></td>
    <td><center>-137,72</center></td>
  </tr>
  <tr>
    <td><center>A-4</center></td>
    <td><center>3,00</center></td>
    <td><center>-163,23</center></td>
    <td><center>-244,84</center></td>
  </tr>
  <tr>
    <td><center>L-0</center></td>
    <td><center>3,00</center></td>
    <td><center>380,87</center></td>
    <td><center>-244,84</center></td>
  </tr>
  <tr>
    <td><center>L-1</center></td>
    <td><center>4,40</center></td>
    <td><center>304,70</center></td>
    <td><center>235,05</center></td>
  </tr>
  <tr>
    <td><center>L-2</center></td>
    <td><center>5,80</center></td>
    <td><center>228,52</center></td>
    <td><center>608,30</center></td>
  </tr>
  <tr>
    <td><center>L-3</center></td>
    <td><center>7,20</center></td>
    <td><center>152,35</center></td>
    <td><center>874,91</center></td>
  </tr>
  <tr>
    <td><center>L-4</center></td>
    <td><center>8,60</center></td>
    <td><center>76,17</center></td>
    <td><center>1034,88</center></td>
  </tr>
  <tr>
    <td><center>L-5</center></td>
    <td><center>10,00</center></td>
    <td><center>0,00</center></td>
    <td><center>1088,20</center></td>
  </tr>
</tbody>
</table>
