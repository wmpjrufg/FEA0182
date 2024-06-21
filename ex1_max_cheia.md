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
    <th>Área (m²)</th>
    <th>Perímetro molhado (m)</th>
    <th>Raio hidráulico (m)</th>
    <th>Velocidade (m/s)</th>
    <th>Vazão (m³/s)</th>
  </tr></thead>
<tbody>
  <tr>
    <td><center><img src="assets/images/logo.png" width="30%"></center></td>
    <td><center>\[(b+m\cdot h)\cdot h\]</center></td>
    <td><center>\[b+(2\cdot h \cdot \sqrt{1+m^2})\]</center></td>
    <td><center>\[\frac{A}{B}\]</center></td>
    <td><center>\[b+(2\cdot m\cdot h)\]</center></td>
    <td><center>\[(A\cdot V)\]</center></td>
  </tr>
</tbody>
</table>


<p align = "justify">
Aplicando a equação de Manning é possível obter a <a href="#tab2">Tabela 2</a> com todas as vazões considerando uma variação de altura de 0,10 m.
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
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
  </tr>
  <tr>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
    <td><center>200,3</center></td>
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
Após a verificação da máxima cheia calculada e então detalhamento do posicionamento da ponte é verificado que a mesma precisará vencer um vão de 20 metros.
</p>
