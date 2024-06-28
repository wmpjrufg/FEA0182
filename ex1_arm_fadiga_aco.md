---
title: Fadiga armaduras
layout: default
parent: Exemplo I
nav_order: 8
has_children: false
has_toc: false
---


<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Análise estrutural: carregamento permanente</h1> 

<p align = "justify">
O carregamento permanente advém da determinação da área da seção transversal dos elementos que compõem a seção da ponte. No caso do nosso exemplo a seção é composta pelos elementos da <a href="#fig1">Figura 1</a>.
</p>

<center><img src="assets/images/perfil.png" width="100%"></center>
<p align = "left"><b><a href="#fig1">Figura 1</a>.</b> Área dos elementos que compõem a seção transversal.</p>

<p align = "justify">
Portanto aplicando a equação de determinação do carregamento linear em vigas chega-se a carga total que ocorre na ponte. É válido salientar que determinamos o carregamento em apenas uma das duas longarinas. As densidades dos materiais empregados para essa análise são:

<ul>
<li><i>γ<sub>c</sub></i> = 25 kN/m³ para peças de concreto armado (Barreira + seção da ponte);</li>
<li><i>γ<sub>pavto</sub></i> = 22 kN/m³ para o pavimento flexível.</li>
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[g_{laje} =  \frac{A_c}{2} \cdot \gamma_{c} \therefore g_{laje} = \frac{2,37}{2} \cdot 25 = 29,625KN/m\]</td>
        <td style="width: 10%;">longarina + tabuleiro</td>
    </tr>
    <tr>
        <td style="width: 90%;">\[g_{barreira} = A_{barreira} \cdot \gamma_{c} \therefore g_{barreira} = 0,24345 \cdot 25 = 6,08625kN/m\]</td>
        <td style="width: 10%;">barreira de concreto</td>        
    </tr>
    <tr>
        <td style="width: 90%;">\[ g_{pavto} = \frac{L_{pavto}}{2} \cdot e_{pavto}\cdot \gamma_{pavto} \therefore g_{pavto} = \frac{8,24}{2} \cdot 0,08 \cdot 22 = 7,25 kN/m \]</td>
        <td style="width: 10%;">pavimento flexível</td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ g_{recap} = 2 \cdot \frac{L_{pavto}}{2} \therefore g_{recap} = 2 \cdot \frac{8,24}{2} = 8,24 kN/m \]</td>
        <td style="width: 10%;">recapeamento</td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ g_{total} = g_{laje} + g_{barreira} + g_{pavto} + g_{gcmetalico} + g_{recap} \therefore q_{total}=29,625+6,08625+7,2512+0,1=43,06245KN/m\]</td>
        <td style="width: 10%;"><font color="#D2691E"><b>carregamento total</b></font></td>
    </tr>
</table>

<p align = "justify">
Logo é possível definir o carregamento permanente que atuará na ponte de concreto. A <a href="#fig2">Figura 2</a> apresenta o lançamento da estrutura no <i>software</i> Ftool e seus respectivos esforços ao longo da longarina conforme <a href="#tab1">Tabela 1</a>.
<br><br>
Aqui salienta-se que para a seleção das seções de interesse o vão será divido em <i>L/10</i> e o balanço em <i>L/5</i>.
</p>

<center><img src="assets/images/perfil.png" width="100%"></center>
<p align = "left"><b><a href="#fig2">Figura 2</a>.</b> Lançamento da estrutura com o seu carregamento permanente.</p>

<p align = "justify">
Considerando o <i>f<sub>ck</i> de 25 MPa e um agregado de granito o módulo de elasticidade do concreto (<i>E<sub>c</i>) será de 24 GPa. Já a seção da longarina será de 0,25 m <i>x</i> 1,00 m. 
</p>

<p align = "left"><b><a href="#tab1">Tabela 1</a>.</b> Esforços de flexão nas seções de interesse para carga permanente.</p>

<table style="width: 100%"><thead>
  <tr>
    <th>Seção</th>
    <th>x (m)</th>
    <th>V (kN)</th>
    <th>M (kN)</th>
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
