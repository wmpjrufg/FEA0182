---
title: Fadiga
layout: default
parent: Exemplo I - Pontes duas longarinas
nav_order: 5
has_children: false
has_toc: false
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Fadiga</h1>

<p align = "justify">
A fadiga pode ser definida como a alteração mecânica dos materiais sob o efeito de solicitações repetidas. As ações que causam fadiga são aquelas que produzem variações de solicitações com frequência relativamente alta. Dentre elas podem ser citadas: cargas móveis, ondas do mar, sismos, vento, variações de temperatura, congelamentos, etc. 
</p>

<p align = "justify">
A fadiga é abordada pela NBR 6118 (ABNT, 2014) no item 23, com base nisso foram realizados os cálculos a seguir.
</p>

<ul>
  <li><i>M_{g}</sub></i> = 1081,2 kN.m (Momento no meio do vão devido a carga permanente);</li>
  <li><i>M_{q,max}</sub></i> = 2570,9 kN.m (Momento positivo no meio do vão devido a carga variável);</li>
  <li><i>M_{q,min}</sub></i> = -156,9 kN.m (Momento negativo no meio do vão devido a carga variável);</li>
</ul>

<p align = "justify">
Com base nesses momentos, foi realizada as combinações em serviço, adotando \psi_{1} = 0,5:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ M_{sd,max} = M_{g} + M_{q,max} \cdot \psi_{1} = 2366,65 kN.m \]</td>
        <td style="width: 20%;">Combinação 1</td>  
    </tr>
    <tr>
        <td style="width: 80%;">\[ M_{sd,min} = M_{g} + M_{q,min} \cdot \psi_{1} = 1002,75 kN.m \]</td>
        <td style="width: 20%;">Combinação 2</td>        
    </tr>
</table>

<p align = "justify">
Considerando a área de aço de 139 cm², conforme o dimensionamento de viga de seção T, pode-se realizar a verificação da fadiga.
</p>

<p align = "justify">
Inicialmente calcula-se os coeficientes a_1, a_2 e a_3.
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ a_1 =  \frac{b_w}{2}= 0,225 \; m\]</td>
        <td style="width: 20%;"><font color="#D2691E"><b>a_1</b></font></td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ a_2 = h_f \cdot (b_f - b_w) + \alpha_e - 1 \cdot \alpha_e \cdot A_s = 0,266 \; m²\]</td> 
        <td style="width: 20%;"><font color="#D2691E"><b>a_2</b></font></td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ a_{g}:= -d^{\prime}\cdot(a_{g}-1)\cdot A_{s}^{\prime}-d\cdot a_{g}\cdot A_{s}-\frac{b_{f}}{2}\cdot(b_{f} b_{v})=-0.1386\,\mathrm{m}^{3} \]</td>
        <td style="width: 20%;"><font color="#D2691E"><b>a_3</b></font></td>
    </tr>
</table>

<p align = "justify">
Logo é possível definir o carregamento permanente que atuará na ponte de concreto é de 54,41 kN/m.
</p>

<h1>Esforços</h1> 

<p align = "justify">
Para determinação dos esforços será empregado o <i>software</i> Ftool. E neste lançamento estrutural serão definidas seções para determinação dos esforços. Será empregado uma divisão de <i>l/4</i> para os balanços e  <i>L/10</i> para o meio do vão.
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
