---
title: Ação nos pilares
layout: default
parent: Exemplo I - Pontes duas longarinas
nav_order: 14
has_children: false
has_toc: false
---

<h1>CÁLCULO DAS CARGAS DE FRENAGEM E ACELERAÇÃO, EMPUXO E VENTO </h1> 

<h1>Aceleração e frenagem </h1> 

<p align = "justify">
De acordo com a NBR 7186 – Projeto de pontes de concreto armado e de concreto protendido – Procedimento, nas pontes rodoviárias, a força longitudinal resultante da frenagem ou aceleração dos veículos deve ser considerada aplicada na superfície de rolamento. O valor dessa força deve corresponder ao maior entre: 5% do peso do carregamento do tabuleiro, considerando as cargas móveis distribuídas e excluindo os passeios, ou 30% do peso do veículo tipo.
</p>

<p align = "justify">
O veículo-tipo utilizado foi o TB 450, que possui as seguintes características:
</p>
<ul>
  <li><i> Peso 450 kN
  <li><i> Comprimento 6 m 
  <li><i> Largura 3 m 
  <li><i> O que é q = 5 kN/m²????
</ul>

<p align = "justify">

</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;"> \[ 30% \cdot P_{veiculo} = 0,30 \cdot 450 = 135 \; kN \]</td>
        <td style="width: 20%;">30% do valor do peso do veículo-tipo</td>        
    </tr>
    <tr>
        <td style="width: 80%;">\[ A_{pista} = 8,24 \; m \cdot 20 \; m = 164,8 \; m^2\]</td>
        <td style="width: 20%;">Área do tabuleiro</td>
    </tr>
       <tr>
        <td style="width: 80%;">\[  5\% \cdot A_{pista} \cdot q = 0,05 \cdot 164.8 \;m² \cdot 5 \; kN/m² =  41,2\; kN\]</td>
        <td style="width: 20%;">5% do caregamento do tabuleiro</td>
    </tr>
</table>

<p align = "justify">
Assim, a força de frenagem ou aceleração adotada seria de 135 kN, pois é a maior entre elas.
</p>

<h1>Empuxo</h1> 

<p align = "justify">
O empuxo de terra nas estruturas é determinado com base nos princípios da mecânica dos solos, considerando sua natureza (ativo, passivo ou de repouso), as características do terreno e as inclinações dos taludes e paramentos. Para simplificação, pode-se assumir que o solo é isento de coesão e que não há atrito entre o terreno e a estrutura, desde que as solicitações resultantes garantam a segurança da obra (Associação Brasileira de Normas Técnicas, 2003, p. 4).

O peso específico do solo úmido deve ser considerado no mínimo igual a 18 kN/m³ e o ângulo de atrito interno no máximo igual a 30º. Os empuxos ativo e de repouso devem ser considerados nas situações mais desfavoráveis. A atuação do empuxo passivo só pode ser levada em conta quando sua ocorrência puder ser garantida ao longo de toda a vida útil da obra(Associação Brasileira de Normas Técnicas, 2003, p. 4).
</p>

<ul>
  <li><i> Peso específico: \[ \gamma_{solo} = 18 \; \text{kN/m}^3 \]
  <li><i> .....: \[ K_a = \frac{1}{3} \]
  <li><i> Área do veículo: \[ A_{veiculo} = 3 \; m \cdot 6 \; m = 18 \; m^2 \]
  <li><i> Carregamento do veículo: \[ Q_{veiculo} = P_{veiculo} \cdot A_{veiculo} = 450 \; kN \cdot 18 \; m^2 = 8100\; kN/m² \]
  <li><i>\[q_{med} = \frac{Q_{veiculo} \cdot 3 \; m + q \cdot (b - 3 \; m)}{b} = 11.6667 \; kN/m^2 \]
</ul>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;"> \[frac{1}{2} \times K_a \times \gamma_{solo} \times b \times h^2 = 27 \; \text{kN} \]</td>
        <td style="width: 20%;">Empuxo devio ao solo</td>        
    </tr>
    <tr>
        <td style="width: 80%;">\[ 30% \cdot P_{veiculo} = 0,30 \cdot 450 = 135 \; kN \]</td>
        <td style="width: 20%;">Empuxo devio a movimentação dos veículos</td>
    </tr>
</table>

<h1>Vento</h1>

<p align="justify">
    De acordo com a NBR 7187, o vento é considerado uma força horizontal agindo normalmente ao eixo da estrutura e uniformemente distribuído ao longo desse eixo. O valor dessa força é o seguinte:
</p>

<ul>
    <li><strong>Ponte descarregada</strong> — <em>pv</em> = 1,5 kN/m² — agindo sobre uma superfície representada pela projeção da estrutura sobre um plano vertical normal à direção do vento.</li>
    <li><strong>Ponte carregada</strong> — para pontes rodoviárias: <em>pv</em> = 1 kN/m²; para passarelas: <em>pv</em> = 0,7 kN/m².</li>
</ul>
<p align="justify">
A componente longitudinal das forças de vento podem ser determinadas, sendo 
<ul>
  <li><strong>25% da carga da superestrutura:</strong> Refere-se à parcela da força de vento incidente sobre os elementos fixos da ponte, como vigas e tabuleiros.
  <li><strong>40% da carga móvel:</strong>Corresponde à parcela da força de vento incidente sobre as cargas móveis, como veículos que transitam pela ponte.
</ul>

<p align = "left"><b><a href="#fig1">Figura 1</a>.</b> Carga de vento para ponte descarregada.</p>
<center><img src="assets\images\Ponte descarregada.png" width="100%"></center>

<p align = "left"><b><a href="#fig1">Figura 2</a>.</b> Carga de vento para ponte carregada.</p>
<center><img src="assets\images\Ponte carregada.png" width="100%"></center>

<h1>Vento transversal</h1>

<table style = "width:100%">
 <tr>
        <td style="width: 80%;"> \[  w_{descarregado} = 1 \; kN/m^2 \cdot (1 \; m + 0.81 \; m) \cdot 20 \; m = 36.2 \; kN \] </td>
        <td style="width: 20%;">Força de vento com estrutura descarregada</td>
    </tr>
    <tr>
        <td style="width: 80%;"> [ w_{carregado} = 1.5 \; kN/m^2 \cdot (1 \; m + 2.08 \; m) \cdot 20 \; m = 92.4 \; kN\] </td>
        <td style="width: 20%;">Força de vento com estrutura caregado</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ W_{adotado} = 92,4 \; kN \]</td>
        <td style="width: 20%;">Força de vento adotado</td>
    </tr>
</table>

<h1>Vento longitudinal</h1>

<table style = "width:100%">
    <tr>
        <td style=width:80%;>\[ FV_{descarregada} = 25\% \cdot w_{descarregado} = 9,05 \; kN\]</td>
        <td style=width:20%;>Força de vento com estrutura descarregada</td>
    <tr>
    <tr>
        <td style=width:80%;>\[ FV_{carregada} = 25\% \cdot 1.5 \; kN/m^2 \cdot (1 \; m + 0.08 \; m) \cdot 20 \; m + 40\% \cdot 1.5 \; kN/m^2 \cdot (2 \; m \cdot 20 \; m) = 32.1 \; kN\]</td>
        <td style=width:20%;>Força de vento com estrutura carregada</td>
    <tr>
    <tr>
        <td style=width:80%;>FV_{adotado} = 32,1 \; kN</td>
        <td style=width:20%;>Força de vento adotado</td>
    <tr>
</table>

<h1>Cargas total</h1>

<table style = "width:100%">
    <tr>
        <td style=width:80%;>\[F_{total, lomgitudinal}= FA_{adot} + E_{solo} + E_{tremtipo} + Vento_{adotado}\]</td>
        <td style=width:20%;>Carga total longitudinal</td>
    <tr>
    <tr>
        <td style=width:80%;>\[CF_{total, transversal} = w_{adotado} = 92.4 \; kN\]</td>
        <td style=width:20%;>Carga total transversal</td>
    <tr>
</table>
