---
title: Dimensões longarinas e tabuleiro
layout: default
parent: Exemplo I
nav_order: 2
has_children: false
has_toc: false
---


<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Longarina</h1> 

<p align = "justify">
Determinado o vão da ponte é necessário estabelecer o sistema estrutura que será utilizado nesta ponte. Conforme estabelecido nas diretrizes do projeto o modelo será de uma ponte moldada no local e com uma estrutura isostática conforme <a href="#fig1">Figura 1b</a>.
</p>

<center><img src="assets/images/perfil.png" width="100%"></center>
<p align = "center">(a) Solução isostática sem balanço</p>
<center><img src="assets/images/perfil.png" width="100%"></center>
<p align = "center">(b) Solução isostática com balanço</p>
<p align = "left"><b><a href="#fig1">Figura 1</a>.</b> Possíveis soluções estruturais para a longarina no projeto exmeplo.</p>

<p align = "justify">
Para determinação das dimensões da superestrutura será empregada as recomendações do professor Areas Neto e da normativa do DNIT. As equações <a href="#eq1">(1)</a> a <a href="#eq3">(3)</a> apresentam estes limites para determinação das dimensões do elemento de longarina.
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ ch_{a,k} = 0.50 \cdot p_{0,k}^{t} + 0.50 \cdot p_{1,k}^{t}\]</td>
        <td style="width: 10%;">vão do elemento de balanço</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ ch_{b,k} = 1.50 \cdot p_{0,k}^{t} - 0.50 \cdot p_{1,k}^{t}\]</td>
        <td style="width: 10%;">altura da longarina</td>        
        <td style="width: 10%;"><p align = "right" id = "eq2">(2)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ ch_{c,k} = -0.50 \cdot p_{0,k}^{t} + 1.50 \cdot p_{1,k}^{t}\]</td>
        <td style="width: 10%;">largura da longarina</td>
        <td style="width: 10%;"><p align = "right" id = "eq3">(3)</p></td>
    </tr>
</table>

<p align = "justify">
Aplicando as equações <a href="#eq1">(1)</a> a <a href="#eq3">(3)</a> obtém-se as dimensões da longarina. No caso para o comprimento <i>a</i> do balanço será adotado um processo iterativo:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 80%;">\[ ch_{a,k} = 0.50 \cdot p_{0,k}^{t} + 0.50 \cdot p_{1,k}^{t}\]</td>
        <td style="width: 10%;">tentativa 1</td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ ch_{b,k} = 1.50 \cdot p_{0,k}^{t} - 0.50 \cdot p_{1,k}^{t}\]</td>
        <td style="width: 10%;">tentativa 2</td>        
    </tr>
    <tr>
        <td style="width: 90%;">\[ ch_{c,k} = -0.50 \cdot p_{0,k}^{t} + 1.50 \cdot p_{1,k}^{t}\]</td>
        <td style="width: 10%;">tentativa 3</td>
    </tr>
</table>

<p align = "justify">
A largura adotada será a mínima de 0,25 m e e então a altura será de 1,0 m \( \left( h=14/14 = 1 m \right) \).
</p>

<h1>Tabuleiro</h1> 

<p align = "justify">
Agora para definir a seção da ponte será utilziada a solução de duas longarinas apoiadas em pórticos de pilares de concreto. A normativa do DNIT definie que a largura máxima entre vigas é de 7 m. Para este projeto utilziaremos a proporção de 40% da largura da seção para balanços e 60% para o vão principal do tabuleiro. O formato deste tabuleiro é apresentado na Figura <a href="#fig2">2</a>.
</p>

<center><img src="assets/images/secao_ponte.png" width="90%"></center>
<p align = "left"><b><a href="#fig2">Figura 2</a>.</b> Solução para seção transversal da ponte.</p>

<p align = "justify">
Empregando as porporções citadas anteriormente temos um vão de 5,40 m (60% de 9 m) entre vigas e balanços de 1,80 m. Com isso chegamos a seguinte seção transversal que considera uma largura de tabuleiro de 0,22 m. A Figura <a href="#fig3">3</a> detalha esta seção.
</p>

<center><img src="assets/images/secao_ponte.png" width="90%"></center>
<p align = "left"><b><a href="#fig3">Figura 3</a>.</b> Detalhe com as dimensões da seção.</p>