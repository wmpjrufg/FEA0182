---
title: Tabuleiro
layout: default
parent: Exemplo I - Pontes duas longarinas
nav_order: 10
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
        <td style="width: 20%;">Tabuleiro + longarina</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ A_{barreira} = 0,19 \; m² \]</td>
        <td style="width: 20%;">Barreira de concreto</td>        
    </tr>
    <tr>
        <td style="width: 80%;">\[ A_{pavto} = 8,24 \cdot 0,08 = 0,66 \; m² \]</td>
        <td style="width: 20%;">Pavimento flexível</td>
    </tr>
</table>

<p align = "justify">
O valor total do carregamento atuante na seção é dado a seguir:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ g_{pp} =  \frac{2,60}{2} \cdot 25 = 32,50 \; kN/m\]</td>
        <td style="width: 20%;">Longarina + tabuleiro</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ g_{barreira} = 0,19 \cdot 25 = 4,75 \; kN/m\]</td>
        <td style="width: 20%;">Barreira de concreto</td>        
    </tr>
    <tr>
        <td style="width: 80%;">\[ g_{pavto+recap} = \frac{0,66}{2} \cdot 24 + \frac{2 \cdot 8,24}{2} = 16,16 \; kN/m \]</td>
        <td style="width: 20%;">Pavimento flexível + recapeamento</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ g_{total} = g_{pp} + g_{barreira} + g_{pavto+recap} + g_{gcmetalico} = 32,50 + 4,75 + 16,16 + 1 = 54,41 \; kN/m\]</td>
        <td style="width: 20%;"><font color="#D2691E"><b>Carregamento total</b></font></td>
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

<p align = "justify">
Agora, para a determinação dos esforços variáveis, serão utilizadas as tabelas de Rüsch.
</p>

<p align = "justify">
Inicialmente, devemos analisar alguns fatores sobre estas tabelas: 
</p>

<ul>
  <li>O primeiro é a relação 𝑙𝑥/𝑎, este fator se diz respeito à distância adjacente entre as rodas de um mesmo eixo, no caso do TB-450, este valor é de 2 m;</li>
  <li>O segundo fator é a relação 𝑡/𝑎, onde 𝑡 é a largura de distribuição da pressão da roda</li>
</ul>

<p align = "justify">
A <a href="#fig2">Figura 2</a> apresenta os detalhes sobre os fatores mencionados. 
</p>

<p align = "left"><b><a href="#fig2">Figura 2</a>.</b> Representação das variáveis 𝑏 e 𝑡 na planta da laje.</p>
<center><img src="assets/images/aula_esforco_tabuleiro/FIG_11.png" width="100%"></center>
<br>

<p align = "justify">
A largura 𝑡 é calculada a partir da seguinte equação: 
</p>

<p align = "justify">
<td style="width: 80%;">\[ t_x \text{ ou } t_y = b + 2 \cdot h_{\text{pav}} + h_{\text{laje}} \]</td>
</p>

<p align = "justify">
Como a roda tem contato nas duas direções é necessário fazer o valor médio de 𝑡, dado pela equação abaixo:
</p>

<p align = "justify">
<td style="width: 80%;">\[ t_{\text{equivalente}} = \sqrt{t_x \cdot t_y} \]</td>
</p>
  
<p align = "justify">
Assim, substituindo pelos valores previamente calculados em outras seções do exemplo:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ t_x = 50 \, \text{cm} + 2 \cdot 8 \, \text{cm} + 21 \, \text{cm} = 87 \, \text{cm} \]</td>
        <td style="width: 20%;">Longitudinal (\( h_{\text{pav}} = 8 \, \text{cm}, h_{\text{laje}} = 21 \, \text{cm} \))</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ t_y = 20 \, \text{cm} + 2 \cdot 8 \, \text{cm} + 21 \, \text{cm} = 57 \, \text{cm} \]</td>
        <td style="width: 20%;">Transversal</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ t_{\text{equivalente}} = \sqrt{0,87 \cdot 0,57} = 0,70 \, \text{m} \]</td>
        <td style="width: 20%;">Largura equivalente</b></font></td>
    </tr>
</table>

<p align = "justify">
O próximo passo é determinar os fatores de momento 𝑘, estes são obtidos a partir da tabela, tendo como base apenas a direção de tráfego. No caso deste exemplo, o tráfego está na direção 𝑦, assim, os valores de 𝑘 utilizados devem ser deduzidos conforme a <a href="#fig3">Figura 3:</a>
</p>

<p align = "left"><b><a href="#fig3">Figura 3</a>.</b> Fator k conforme direção de tráfego.</p>
<center><img src="assets/images/aula_esforco_tabuleiro/DIR_XY.png" width="100%"></center>
<br>

<p align = "justify">
Assim, os valores de 𝑘 utilizados no exemplo são de 0,125 para 𝑥 e 0,0208 para 𝑦.</a>
</p>



<p align = "justify">
Agora, o último dado a ser determinado para de fato podermos aplicar a tabela é o 𝑙𝑥, para facilitar, utilizaremos a <a href="#fig4">Figura 4</a> que apresenta as dimensões previamente calculadas em outras seções deste exemplo.
</p>
  
<p align = "left"><b><a href="#fig4">Figura 4</a>.</b> Seções na transversal.</p>
<center><img src="assets/images/aula_esforco_tabuleiro/fig_02_secao_sem_trans.png" width="100%"></center>
<br>  

<p align = "justify">
Portanto, a partir da imagem podemos retirar os seguintes dados:
</p>

<ul>
  <li>Vão adotado: 4,54 m; </li>
  <li>Largura mínima da longarina: 45 cm.</li>
</ul>

<p align = "justify">
Com isto em mãos, o valor de 𝑙𝑥 é facilmente calculado:
</p>

<p align = "justify">
<td style="width: 80%;">\[ l_x = Vão_{\text{adot}} + L_{\text{min,long}} \]</td>
</p>

<p align = "justify">
<td style="width: 80%;">\[ l_x = 4{,}99\,\mathrm{m} \cong 5\,\mathrm{m} \]</td>
</p>

<p align = "justify">
Portanto, as relações calculadas são:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ \frac{t}{a} = \frac{0,70}{2,0} = 0,35 \]</td>
        <td style="width: 20%;">Relação de espalhamento</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ \frac{l_x}{a} = \frac{5,0}{2,0} = 2,5 \]</td>
        <td style="width: 20%;">Relação estrutural</td>
    </tr>
</table>

<p align = "justify">
Com estes dados, devemos observar na tabela selecionada os valores obtidos e, em seguida, interpolar linearmente para a obtenção dos valores necessários. A tabela utilizada é ilustrada na <a href="#fig5">Figura 5</a>.
</p>

<p align = "left"><b><a href="#fig5">Figura 5</a>.</b> Tabela de Rüsch adotada.</p>
<center><img src="assets/images/aula_esforco_tabuleiro/TAB_1.png" width="100%"></center>
<br>  

<p align = "justify">
Para nossas relações calculadas, os valores obtidos na tabela foram os seguintes
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ M_{\text{xm}} = 0,384 {\text{ e }} 0,315 \]</td>
        <td style="width: 20%;">Colunas a serem interpoladas</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ M_{\text{ym}} = 0,346 {\text{ e }} 0,303 \]</td>
        <td style="width: 20%;">Colunas a serem interpoladas</td>
    </tr>
</table>

<p align = "justify">
Após a interpolação, os valores obtidos foram os seguintes:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ M_{\text{xm}} = 0,356 \]</td>
        <td style="width: 20%;">M<sub>xm</sub> adotado</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ M_{\text{ym}} = 0,329 \]</td>
        <td style="width: 20%;">M<sub>ym</sub> adotado</td>
    </tr>
</table>
