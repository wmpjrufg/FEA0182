---
title: Máxima cheia e posição da superestrutura
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

<center><img src="assets/images/perfil_topo.png" width="100%"></center>
<p align = "left"><b><a href="#fig1">Figura 1</a>.</b> Perfil topográfico da estrada.</p>

<p align = "justify">
Considerando que a vazão de projeto é de 12,57 m²/s e o canal tem formato trapezoidal (conforme <a href="#fig2">Figura 2</a>) pode-se usar a formulação proposta nas equações <a href="#eq1">(1)</a> a <a href="#eq5">(5)</a>.
</p>

<center><img src="assets/images/secao_canal.png" width="50%"></center>
<p align = "left"><b><a href="#fig2">Figura 2</a>.</b> Formato do canal em seção trapezoidal.</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ A = b \cdot h + m \cdot h^2 \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ P = b + 2\cdot h  \cdot \sqrt{1+m^2} \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq2">(2)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ R = \frac{A}{P} \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq3">(3)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ V = \frac{1}{n} \cdot R^{2/3} \cdot J^{1/2} \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq4">(4)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ Q = V \cdot A \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq5">(5)</p></td>
    </tr>
</table>

<p align = "justify">
Onde:
  <ul>
    <li><i>A</i> é a área da seção transversal (m²);</li>
    <li><i>P</i> é o perímetro molhado (m);</li>
    <li><i>R</i> é o raio hidráulico (m);</li>
    <li><i>m</i> é a inclinação do talude do canal;</li>
    <li><i>n</i> é o coeficiente de rugosidade do canal;</li>
    <li><i>J</i> é a declividade do fundo do canal (m/m);</li>
    <li><i>V</i> é a velocidade no canal pelo modelo de Manning (m/s);</li>
    <li><i>Q</i> é a vazão no canal pelo modelo de Manning (m³/s).</li>
  </ul>
</p>


<p align = "justify">
Aplicando a equação de Manning é possível obter a <a href="#tab1">Tabela 1</a> com algumas vazões em função da cota. No caso a declividade do talude do canal é de <i>m</i> = 2 m e a largura do canal é de <i>b</i> = 8 m.
</p>

<p align = "left"><b><a href="#tab1">Tabela 1</a>.</b> Vazão no canal do exemplo.</p>
<table style="width: 100%"><thead>
  <tr>
    <th>Cota (m)</th>
    <th>b (m)</th>
    <th>h (m)</th>
    <th>Área (m²)</th>
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
    <td><center>\[ A = b \cdot h + m \cdot h^2 \;=\; 8 \cdot 0,10 + 2 \cdot 0,10^2 \;=\; 0,82 \]</center></td>
    <td><center>\[ P = b + 2 \cdot h  \cdot \sqrt{1+m^2} \;=\; 8 + 2 \cdot 0,10  \cdot \sqrt{1+2^2} \;=\;8,45 \]</center></td>
    <td><center>\[ R = \frac{A}{P} \;=\; \frac{0,82}{8,45} \;=\;0,097 \]</center></td>
    <td><center>\[ V = \frac{1}{n} \cdot R^{2/3} \cdot J^{1/2} \;=\; \frac{1}{0,03} \cdot 0,097^{2/3} \cdot 0,001^{1/2} \;=\; 0,22\]</center></td>
    <td><center>\[ Q = V \cdot A \;=\; 0,22 \cdot 0,82 \;=\; 0,18\]</center></td>
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
    <td><center><font color="##008000"><b>198,50</b></font></center></td>
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
Considerando o cálculo efetuado na <a href="#tab1">Tabela 1</a> é possível determinar as posições da cota do nível d'água para a Máxima Cheia Calculada (M.C.C.) e também determinar a altura mínima que respeitará o gabarito imposto pela concessionária que é de 2 metros. Com isso é possível construir a <a href="#fig2">Figura 2</a>.
</p>

<center><img src="assets/images/perfil_topo_com_longarina.png" width="100%"></center>
<p align = "left"><b><a href="#fig2">Figura 2</a>.</b> Perfil topográfico da estrada com a demarcação da posição da estrutura e nível d'água na Máxima Cheia Calculada.</p>

<p align = "justify">
Após a verificação da Máxima Cheia Calculada e então detalhamento do posicionamento da ponte é possível estabelecer que a ponte precisará vencer um vão de 20 metros.
</p>
