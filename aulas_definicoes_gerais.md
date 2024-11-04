---
title: Introdução ao projeto
layout: default
parent: Aulas
nav_order: 1
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
<br>
<h1><b>Definições gerais</b></h1>
<br><br><br>
<table border = 1>
  <tr style="text-align: center;">
    <th>
      <br>
      ONDE ESTAMOS ???
      <br>&nbsp;
    </th>
  </tr>
    <tr style = "text-align:left">
      <th>
        <p style="color: blue; text-align: center;">1 – CONCEITOS GERAIS SOBRE O PROJETO DE PONTES</p>
        2 – AÇÕES NA SUPERESTRUTURA<br><br>
        3 – ANÁLISE COMPUTACIONAL COM CARGA MÓVEL<br><br>
        4 – DIMENSIONAMENTO DA LONGARINA<br><br>
        5 – DIMENSIONAMENTO DO TABULEIRO<br><br>
        6 – DIMENSIONAMENTO DA TRANSVERSINA<br><br>
        7 – DIMENSIONAMENTO DA MESOESTRUTURA<br><br>
        8 – APARELHOS DE APOIO<br>
      </th>
    </tr>
</table>
<br><br>
<h2>1 – DEFINIÇÕES GERAIS</h2>
<br>
<p>
    De acordo com o item 3.1 da NBR 7188 [1], ponte é uma estrutura utilizada para transpor um determinado obstáculo natural, como rios, vales, córregos, entre outros.    Esse tipo de construção é submetida a ação de carga móvel, ou seja, ação de esforços com posicionamento variável. Já os viadutos são definidos no item 3.2 e se diferenciam das pontes no sentido de ser uma estrutura com finalidade de transpor algum obstáculo artificial, por exemplo: (a) avenida; (b) rodovia; e etc.<br>

Pontes e viadutos são enquadrados como Obras de Arte Especiais (OAE’s). E são assim denominadas devido a sua complexidade projetual, envolvimento de diversas áreas do conhecimento na elaboração dos projetos até a construção. Além disso OAE’s são obras de grande relevância no âmbito da infraestrutura de uma nação. <br>

Segundo o DNIT1a apud Mendes [2] afirma que os 73000 km de rodovias pavimentadas e não pavimentadas do modal rodoviário federal brasileiro possui 5600 pontes. Em 2011 um relatório do Tribunal de Contas da União (Relatório TC 003.134/2011-3) apontou em uma auditoria que o valor estimado das OAE's são da ordem 13 bilhões de reais e esses estão distribuídos em cerca de 4.500 pontes e viadutos na malha federal. Já em 2015 o Departamento Nacional de Infraestrutura de Transportes (DNIT) contabilizou somente sob sua responsabilidade um total de 5114 OAE’s.
</p><br><br><br>
<p>
    Uma ponte ou um viaduto podem ser classificados da seguinte forma:<br>
    <ol type = "a" >
        <li>Ponte: Quando o obstáculo é constituído de curso de água ou outra superfície líquida como por exemplo um lago ou braço de mar;</li>
        <li>Viaduto: Quando o obstáculo é um vale ou uma via;</li>
    </ol>
</p>
<br>

<table align = "center">
    <tr>
        <th>
        <img  src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiKMYQRtanBOrZakn1UaKT6iYFKnv5Ph7RUr1TQwaLnQZe4bkkkM3zHUCyafha71A7lKL2hQc-Hpqu8toSdJS4RYXKKDi1urGtSo_2jEGzqcQgnUReysUPCeQjAJKfAiya9Kv2FxPvirTBl/s1600/Captura+de+Tela+2015-10-04+a%25CC%2580s+21.39.13.png" alt="Exemplificações dos sistemas de pontes e viadutos">
            </th>
    </tr>
</table>
<br><br><br>
<p>
    Algumas nomenclaturas devem ser definidas para facilitar o prosseguimento. A primeira definição importante é baseada na organização do sistema estrutural, que nesse caso se subdivide em 3 classificações, são elas:<br><br>
 <ol type = "a" >
        <li>Superestrutura: Elementos de laje (tabuleiro) e viga;</li>
        <li>Mesoestrutura: Elementos de pilar e aparelhos de apoio;</li>
        <li>Infraestrutura: Obras de terra e elementos de fundação.</li>
    </ol>
    <br><br>
    <p>Vitório [4] define da segunda forma cada uma das partes do sistema:</p>
    <ol type = "a" >
        <li>Superestrutura: Vence o vão necessário a ser transposto pela ponte e recebe diretamente as cargas provenientes do tráfego dos veículos, transmitindo-as à mesoestrutura. É normalmente denominada de tabuleiro ou estrado, sendo composta de vigamento longitudinal (vigas principais ou longarinas), de vigamento transversal (transversinas) e das lajes superior, e inferior (no caso de estrado celular);</li><br>
        <li>Mesoestrutura: Tem função é conduzir as cargas da superestrutura para as fundações, é constituída pelos pilares, travessas e encontros;</li><br>
        <li>Infraestrutura: Também chamada de fundação, tem a finalidade de receber as cargas da estrutura, transmitindo-as para o solo. Pode ser direta (sapatas) ou profunda (estacas ou tubulões).</li><br>
    </ol>
</p>
<br><br>
<table align = "center">
    <tr>
        <th>
        <img  src="" alt="AQUI VAI A IMAGEM DO SLIDE 7 DA AULA 1 DE PONTES">
            </th>
    </tr>
</table>
<br><br><br>
<h2> 2 - CLASSIFICAÇÕES DE PROJETO</h2>


