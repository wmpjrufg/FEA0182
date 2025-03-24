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
Considerando a área de aço de 139 cm², conforme o dimensionamento de viga de seção T, pode-se realizar a verificação da fadiga, inicialmente foi realizada as verificações em relação ao momento máximo.
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
Após isso, determina-se a posição da linha neutra.
</p>

<body>
    <table>
        <tr>
            <td style="width: 80%;">\[x_{II,pos} = \frac{-a_2 + \sqrt{a_2^2 - 4 \cdot a_1 \cdot a_3}}{2 \cdot a_1} = 0,3914 \, \text{m}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>x_{II,pos}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[x_{II,neg} = \frac{-a_2 - \sqrt{a_2^2 - 4 \cdot a_1 \cdot a_3}}{2 \cdot a_1} = -157,3665 \, \text{cm}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>x_{II,neg}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[x_{II} := x_{II,pos}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>x_{II}</b></font></td>
        </tr>
    </table>
</body>

<p align = "justify">
Em seguida, calcula-se o momento de inércia da seção no estádio II.
</p>

<body>
    <table>
        <tr>
            <td style="width: 80%;">\[I_{II} := \frac{b_r \cdot x_{II}}{3} + \alpha_g \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_g - 1) \cdot A_s \cdot (x_{II} - d)^2 = 0,0778 \, \text{m}^4\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>I_{II}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[I_{x_III} := \left( \frac{b_r - b_y}{12} \right) \cdot h_e^3 + \frac{b_y \cdot x_{II}}{3} + \left( \frac{b_z - b_y}{12} \right) \cdot \left( x_{II} - \frac{h_e}{2} \right)^2 + \alpha_g \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_g - 1) \cdot A'_s \cdot (x_{II} - d')^2 = 0,0559 \, \text{m}^4\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>I_{x_III}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[y_{N1} := d - x_{II} = 0,5086 \, \text{m}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>y_{N1}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[\alpha_{N1,Msdnax} := \frac{\alpha_g \cdot (M_{sd,nax}) \cdot y_{N1}}{I_{II}} = 1,5472 \cdot 10^5 \, \text{kPa} \quad \text{Tensão de tração}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>\alpha_{N1,Msdnax}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[y_{N2} := x_{II} - d' = 0,2914 \, \text{m}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>y_{N2}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[\alpha_{N2,Msdnax} := \frac{\alpha_g \cdot (M_{sd,nin}) \cdot y_{N2}}{I_{II}} = 37567,0922 \, \text{kPa} \quad \text{Tensão de compressão}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>\alpha_{N2,Msdnax}</b></font></td>
        </tr>
    </table>
</body>

<p align = "justify">
Por fim, foram realizados os cálculos novamente para o momento mínimo.
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
Após isso, determina-se a posição da linha neutra.
</p>

<body>
    <table>
        <tr>
            <td style="width: 80%;">\[x_{II,pos} = \frac{-a_2 + \sqrt{a_2^2 - 4 \cdot a_1 \cdot a_3}}{2 \cdot a_1} = 0,3914 \, \text{m}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>x_{II,pos}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[x_{II,neg} = \frac{-a_2 - \sqrt{a_2^2 - 4 \cdot a_1 \cdot a_3}}{2 \cdot a_1} = -157,3665 \, \text{cm}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>x_{II,neg}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[x_{II} := x_{II,pos}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>x_{II}</b></font></td>
        </tr>
    </table>
</body>

<p align = "justify">
Em seguida, calcula-se o momento de inércia da seção no estádio II.
</p>

<body>
    <table>
        <tr>
            <td style="width: 80%;">\[I_{II} := \frac{b_r \cdot x_{II}}{3} + \alpha_g \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_g - 1) \cdot A_s \cdot (x_{II} - d)^2 = 0,0778 \, \text{m}^4\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>I_{II}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[I_{x_III} := \left( \frac{b_r - b_y}{12} \right) \cdot h_e^3 + \frac{b_y \cdot x_{II}}{3} + \left( \frac{b_z - b_y}{12} \right) \cdot \left( x_{II} - \frac{h_e}{2} \right)^2 + \alpha_g \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_g - 1) \cdot A'_s \cdot (x_{II} - d')^2 = 0,0559 \, \text{m}^4\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>I_{x_III}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[y_{N1} := d - x_{II} = 0,5086 \, \text{m}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>y_{N1}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[\alpha_{N1,Msdnax} := \frac{\alpha_g \cdot (M_{sd,nax}) \cdot y_{N1}}{I_{II}} = 1,5472 \cdot 10^5 \, \text{kPa} \quad \text{Tensão de tração}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>\alpha_{N1,Msdnax}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[y_{N2} := x_{II} - d' = 0,2914 \, \text{m}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>y_{N2}</b></font></td>
        </tr>
        <tr>
            <td style="width: 80%;">\[\alpha_{N2,Msdnax} := \frac{\alpha_g \cdot (M_{sd,nin}) \cdot y_{N2}}{I_{II}} = 37567,0922 \, \text{kPa} \quad \text{Tensão de compressão}\]</td>
            <td style="width: 20%;"><font color="#D2691E"><b>\alpha_{N2,Msdnax}</b></font></td>
        </tr>
    </table>
</body>



