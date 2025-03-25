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
        <td style="width: 20%;">(1)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ a_2 = h_f \cdot (b_f - b_w) + \alpha_e - 1 \cdot \alpha_e \cdot A_s = 0,2641 \; m²\]</td> 
        <td style="width: 20%;">(2)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ a_{3} = -d^{\prime}\cdot(\alpha_{e}-1)\cdot A_{s}^{\prime}-d\cdot \alpha_{e} \cdot A_{s}-\frac{h_{f}^2}{2}\cdot(b_{f} b_{w})=-0.1386\,\mathrm{m}^{3} \]</td>
        <td style="width: 20%;">(3)</td>
    </tr>
</table>

<p align = "justify">
Após isso, determina-se a posição da linha neutra.
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[x_{II,pos} = \frac{-a_2 + \sqrt{a_2^2 - 4 \cdot a_1 \cdot a_3}}{2 \cdot a_1} = 0,3914 \, \text{m}\]</td>
        <td style="width: 20%;">(4)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[x_{II,neg} = \frac{-a_2 - \sqrt{a_2^2 - 4 \cdot a_1 \cdot a_3}}{2 \cdot a_1} = -157,3665 \, \text{cm}\]</td>
        <td style="width: 20%;">(5)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[x_{II} = x_{II,pos}\]</td>
        <td style="width: 20%;">(6)</td>
    </tr>
</table>

<p align = "justify">
Em seguida, calcula-se o momento de inércia da seção no estádio II.
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[I_{II} = \frac{b_f \cdot x_{II}^3}{3} + \alpha_e \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_e - 1) \cdot A_s \cdot (x_{II} - d)^2 = 0,0774 \, \text{m}^4\]</td>
        <td style="width: 20%;">(7)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[I_{II} =  \frac{b_f - b_w}{12} \cdot h_f^3 + \frac{b_w \cdot x_{II}}{3} + (b_f - b_w) \cdot ( x_{II} - \frac{h_f}{2}^2 + \alpha_e \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_e - 1) \cdot A'_s \cdot (x_{II} - d')^2 = 0,0556 \, \text{m}^4\]</td>
          <td style="width: 20%;">(8)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[y_{N1} := d - x_{II} = 0,5091 \, \text{m}\]</td>
        <td style="width: 20%;">(9)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[\alpha_{N1,Msdmax} = \frac{\alpha_e \cdot (M_{sd,max}) \cdot y_{N1}}{I_{II}} = 1,5565 \cdot 10^5 \, \text{kPa} \quad \text{Tensão de tração}\]</td>
        <td style="width: 20%;">(10)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[y_{N2} := x_{II} - d' = 0,2909 \, \text{m}\]</td>
        <td style="width: 20%;">(11)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[\alpha_{N2,Msdmax} := \frac{\alpha_e \cdot (M_{sd,max}) \cdot y_{N2}}{I_{II}} = 88927,9809 \, \text{kPa} \quad \text{Tensão de compressão}\]</td>
        <td style="width: 20%;">(12)</td>
    </tr>
    <tr>
        <td>\( \delta\sigma = \sigma_{N1,Msdmin} - (-\sigma_{N1,Msdmin}) = 1,9332 \times 10^5 \) kPa</td>
        <td style="width: 20%;">(13)</td>
    </tr>
    <tr>
        <td>\( \delta\sigma = \sigma_{N2,Msdmin} - (-\sigma_{N2,Msdmin}) = 1,5488 \times 10^5 \) kPa</td>
        <td style="width: 20%;">(14)</td>
    </tr>
    <tr>
        <td>\( k = \frac{1,5 \cdot \delta\sigma}{17,5} = 1,3275 \)</td>
        <td style="width: 20%;">(15)</td>
    </tr>
</table>
</body>

<p align = "justify">
Quando o valor da fadiga for menor que 1, não é necessário acrescentar armadura multiplicando pelo valor de \( k \).
</p>

<p align = "justify">
Por fim, foram realizados os cálculos novamente para o momento mínimo.
</p>

<p align = "justify">
Inicialmente calcula-se os coeficientes a_1, a_2 e a_3.
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ a_1 =  \frac{b_w}{2}= 0,225 \; m\]</td>
        <td style="width: 20%;">(16)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ a_2 = h_f \cdot (b_f - b_w) + \alpha_e - 1 \cdot \alpha_e \cdot A_s = 0,2641 \; m²\]</td> 
        <td style="width: 20%;">(17)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[ a_{3} = -d^{\prime}\cdot(\alpha_{e}-1)\cdot A_{s}^{\prime}-d\cdot \alpha_{e} \cdot A_{s}-\frac{h_{f}^2}{2}\cdot(b_{f} b_{w})=-0.1386\,\mathrm{m}^{3} \]</td>
        <td style="width: 20%;">(18)</td>
    </tr>
</table>

<p align = "justify">
Após isso, determina-se a posição da linha neutra.
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[x_{II,pos} = \frac{-a_2 + \sqrt{a_2^2 - 4 \cdot a_1 \cdot a_3}}{2 \cdot a_1} = 0,3914 \, \text{m}\]</td>
        <td style="width: 20%;">(19)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[x_{II,neg} = \frac{-a_2 - \sqrt{a_2^2 - 4 \cdot a_1 \cdot a_3}}{2 \cdot a_1} = -157,3665 \, \text{cm}\]</td>
        <td style="width: 20%;">(20)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[x_{II} = x_{II,pos}\]</td>
        <td style="width: 20%;">(21)</td>
    </tr>
</table>

<p align = "justify">
Em seguida, calcula-se o momento de inércia da seção no estádio II.
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[I_{II} = \frac{b_f \cdot x_{II}^3}{3} + \alpha_e \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_e - 1) \cdot A_s \cdot (x_{II} - d)^2 = 0,0774 \, \text{m}^4\]</td>
        <td style="width: 20%;">(22)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[I_{II} =  \frac{b_f - b_w}{12} \cdot h_f^3 + \frac{b_w \cdot x_{II}}{3} + (b_f - b_w) \cdot ( x_{II} - \frac{h_f}{2}^2 + \alpha_e \cdot A_s \cdot (x_{II} - d)^2 + (\alpha_e - 1) \cdot A'_s \cdot (x_{II} - d')^2 = 0,0556 \, \text{m}^4\]</td>
        <td style="width: 20%;">(23)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[y_{N1} := d - x_{II} = 0,5091 \, \text{m}\]</td>
        <td style="width: 20%;">(24)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[\alpha_{N1,Msdmin} = \frac{\alpha_e \cdot (M_{sd,min}) \cdot y_{N1}}{I_{II}} = 37678,8003 \, \text{kPa} \quad \text{Tensão de tração}\]</td>
        <td style="width: 20%;">(25)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[y_{N2} := x_{II} - d' = 0,2909 \, \text{m}\]</td>
        <td style="width: 20%;">(26)</td>
    </tr>
    <tr>
        <td style="width: 80%;">\[\alpha_{N2,Msdmin} := \frac{\alpha_e \cdot (M_{sd,min}) \cdot y_{N2}}{I_{II}} = 65947,0668 \, \text{kPa} \quad \text{Tensão de compressão}\]</td>
        <td style="width: 20%;">(27)</td>
    <tr>
        <td>\( \delta\sigma = \sigma_{N1,Msdmin} - (-\sigma_{N1,Msdmin}) = 1,9332 \times 10^5 \) kPa</td>
        <td style="width: 20%;">(28)</td>
    </tr>
    <tr>
        <td>\( \delta\sigma = \sigma_{N2,Msdmin} - (-\sigma_{N2,Msdmin}) = 1,5488 \times 10^5 \) kPa</td>
        <td style="width: 20%;">(28)</td>
    </tr>
    <tr>
        <td>\( k = \frac{1,5 \cdot \delta\sigma}{17,5} = 1,3275 \)</td>
        <td style="width: 20%;">(29)</td>
    </tr>
</table>

<p align = "justify">
Quando o valor da fadiga for menor que 1, não é necessário acrescentar armadura multiplicando pelo valor de \( k \).
</p>
