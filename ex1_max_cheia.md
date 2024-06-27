---
title: Máxima cheia e posição super estrutura
layout: default
parent: Exemplo I
nav_order: 1
has_children: false
has_toc: false
---


<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Determinação da máxima cheia e gabarito da ponte</h1> 

<p align = "justify">
O primeiro passo na determinação do modelo estrutural é a confecção de um desenho geométrico em perfil longitudinal que contemple o estaqueamento e as suas cotas verticais. Isso permitirá que o projetista visualize o obstáculo a ser vencido e comece a efetuar o lançamento da ponte.
<br><br>
Para o caso deste projeto o perfil topográfico é dado conforme <a href="#fig1">Figura 1</a>.
</p>

<center><img src="assets/images/perfil.png" width="100%"></center>
<p align = "left"><b><a href="#fig1">Figura 1</a>.</b> Perfil topográfico da estrada.</p>

<p align = "justify">
Considerando que a meta de vazão a ser alcançada é de 12,57 m²/s e o canal tem formato trapezoidal pode-se usar a formulação proposta na <a href="#tab1">Tabela 1</a> para determinação da vazão a cada nível do canal.
</p>

<p align = "left"><b><a href="#tab1">Tabela 1</a>.</b> Equacionamento para conduto livre.</p>
<table style="width: 100%"><thead>
  <tr>
    <th>Forma da seção</th>
    <th>Área (m²) [<i>A</i>]</th>
    <th>Perímetro molhado (m) [<i>P</i>]</th>
    <th>Raio hidráulico (m)</th>
    <th>Velocidade (m/s)</th>
    <th>Vazão (m³/s)</th>
  </tr></thead>
<tbody>
  <tr>
    <td><center><img src="assets/images/secao_canal.png" width="200%"></center></td>
    <td><center>\[ b \cdot h + m \cdot h^2 \]</center></td>
    <td><center>\[ b + 2\cdot h  \cdot \sqrt{l+m^2} \]</center></td>
    <td><center>\[\ frac{A}{P} \]</center></td>
    <td><center>\[ \frac{1}{n} \cdot R^{2/3} \cdot J^{1/2}\]</center></td>
    <td><center>\[A \cdot V\]</center></td>
  </tr>
</tbody>
</table>

<p align = "justify">
Onde:
  <ul>
    <li><i>m</i> é a inclinação do talude do canal;</li>
    <li><i>n</i> é o coeficiente de rugosidade do canal;</li>
    <li><i>R</i> é o raio hidraúlico;</li>
    <li><i>J</i> é a declividade do fundo do canal (m/m).</li>
  </ul>
</p>


<p align = "justify">
Aplicando a equação de Manning é possível obter a <a href="#tab2">Tabela 2</a> com algumas vazões em função da cota. No caso a declividade do talude do canal é de <i>m = </i> 2 metros.
</p>

<p align = "left"><b><a href="#tab2">Tabela 2</a>.</b> Vazão no canal do exemplo.</p>
<table style="width: 100%"><thead>
  <tr>
    <th>Cota (m)</th>
    <th>b (m)</th>
    <th>h (m)</th>
    <th>Área (m)</th>
    <th>Perímetro molhado (m)</th>
    <th>Raio hidráulico (m)</th>
    <th>Velocidade (m/s)</th>
    <th>Vazão (m³/s)</th>
  </tr></thead>
<tbody>
  <tr>
    <td><center>197,40</center></td>
    <td><center>8,00</center></td>
    <td><center>0,10</center></td>
    <td><center>0,82</center></td>
    <td><center>8,45</center></td>
    <td><center>0,1</center></td>
    <td><center>0,22</center></td>
    <td><center>0,18</center></td>
  </tr>
  <tr>
    <td><center>198,20</center></td>
    <td><center>8,00</center></td>
    <td><center>0,90</center></td>
    <td><center>8,82</center></td>
    <td><center>12,02</center></td>
    <td><center>0,73</center></td>
    <td><center>0,86</center></td>
    <td><center>7,56</center></td>
  </tr>
  <tr>
    <td><center><font color="##008000"><b>198,50</b></font></center></font></td>
    <td><center><font color="##008000"><b>8,00</b></font></center></td>
    <td><center><font color="##008000"><b>1,20</b></font></center></td>
    <td><center><font color="##008000"><b>12,48</b></font></center></td>
    <td><center><font color="##008000"><b>13,37</b></font></center></td>
    <td><center><font color="##008000"><b>0,93</b></font></center></td>
    <td><center><font color="##008000"><b>1,01</b></font></center></td>
    <td><center><font color="##008000"><b>12,57</b></font></center></td>
  </tr>
  <tr>
    <td><center>199,10</center></td>
    <td><center>8,00</center></td>
    <td><center>1,80</center></td>
    <td><center>20,88</center></td>
    <td><center>16,05</center></td>
    <td><center>1,3</center></td>
    <td><center>1,26</center></td>
    <td><center>26,23</center></td>
  </tr>
</tbody>
</table>

<p align = "justify">
Considerando o cálculo efetuado na 
<a href="#tab2">Tabela 2</a> é possível determinar as posições da cota do nível d'água para a máxima cheia e também determinar a altura mínima que respeitará o gabarito imposto pela concessionária que é de 2 metros. Com isso é possível construir a <a href="#fig2">Figura 2</a>.
</p>

<center><img src="assets/images/perfil.png" width="100%"></center>
<p align = "left"><b><a href="#fig2">Figura 2</a>.</b> Perfil topográfico da estrada com a demarcação da posição da estrutura e nível d'água na máxima cheia calculada.</p>

<p align = "justify">
Após a verificação da máxima cheia calculada e então detalhamento do posicionamento da ponte é possível estabelecer que a ponte precisará vencer um vão de 20 metros.
</p>
