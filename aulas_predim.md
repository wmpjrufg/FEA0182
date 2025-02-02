---
title: Lançamento estrural e pré--dimensionamento
layout: default
parent: Aulas
nav_order: 4
has_children: false
has_toc: false
---


<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Sistema Estrutural e seu Pré-Dimensionamento</h1> 


<p align = "justify">
  Segundo O’Connor <a href="#ref1">[1]</a> a seleção do material e esquema estrutural é uma tarefa complexa e só pode ser determinado considerando-se todos os fatores que afetam o projeto de cada sistemas estrutural em particular. Para isso o mesmo apresenta a Figura. <a href="#fig1">1</a> algumas estruturas em função do seu material e tipologia do sistema, sendo o destaque dessa tabela o máximo vão em serviço utilizado em cada um dos sistemas.
</p>
<br>

<p id="fig1"></p>
<center><img src="./assets/images/aula4_predim/FIG_1.png" width="90%"></center>
<p align = "justify"><b>Figura 1.</b> Comprimento de vão para vários tipos de superestruturas <a href="#ref1">[1]</a>.</p>
<br>

<p align = "justify">
  De acordo com Areias Neto <a href="#ref2">[2]</a>, para a fixação do comprimento da ponte, deve-se levar em conta aspectos relacionados a seção de vazão necessária e ao projeto da estrada (perfil longitudinal).
	<br><br>
	Araújo <a href="#ref3">[3]</a> afirma que esse traçado de pontes em pequenos rios é definida pelo projetista da estrada quando da elaboração do traçado da via. Entretanto, quando a via cruza médios ou grandes rios a posição da ponte pode determinar o traçado da via. Nesse caso, segue alguns critérios para a posição da ponte:
	<br><br>
	<ul>
		<li>Transpor o canal principal ou vale no local mais estreito possível e mais próximo ao traçado original da via;</li>			<br>
		<li>O canal principal deve ser transposto, de preferência, perpendicularmente à direção do escoamento do rio;</li><br>
		<li>No caso de ponte esconsa deve-se evitar eixos de pilares no meio do rio onde a velocidade de escoamento d’água é maior, diminuindo a erosão localizada na base do pilar (Figura. <a href="#fig2">2</a> );</li><br>
		<li>Deve-se evitar transpor um rio logo após a região onde deságua um afluente (Figura. <a href="#fig3">3</a>). A melhor posição para transposição do rio é mais a jusante da região onde deságua seu afluente;</li><br>
    <li>Evitar transpor em locais onde possa haver, ao longo da vida útil da estrutura, mudanças na seção transversal do rio;</li><br>
    <li>Quando do cruzamento de rios de pequena vazão, é recomendável evitar curvas para transposição desses rio.</li>
	</ul>
</p>
<br>

<p id="fig2"></p>
<center><img src="./assets/images/aula4_predim/FIG_2.jpg" width="90%"></center>
<p align = "justify"><b>Figura 2.</b> Erosão localizada na base de um pilar e contato com a água <a href="#ref3">[3]</a>.</p>
<br>

<p id="fig3"></p>
<center><img src="./assets/images/aula4_predim/FIG_3.jpg" width="90%"></center>
<p align = "justify"><b>Figura 3.</b> Transposição de rio com afluente <a href="#ref3">[3]</a>.</p>
<br>

<h2>Algumas especificações para longarinas</h2>


<p align = "justify">
  Nesse texto iremos abordar os sistemas em Concreto Armado com solução de vigas de eixo reto. Para tanto será necessário algumas proposições de pré-dimensionamento do sistema estrutural. Aqui será apresentado o pré-dimensionamento para soluções em viga apoiada e viga contínua. 
	<br><br>
	Areias Neto <a href="#ref2">[2]</a> indica para sistemas simplesmente apoiados o seguinte valor de vão: 
	<br><br>
	𝑙 ≤ 25 𝑚 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Recomendação para pontes rodoviárias em concreto armado<br><br>
	ℎ<sub>𝑙𝑜𝑛𝑔</sub> > 𝑙/14 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Manual DNIT <a href="#ref4">[4]</a>
  <br><br>
 	𝑏<sub>𝑤,𝑙𝑜𝑛𝑔</sub> ≥ 25 𝑐𝑚 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Manual DNIT <a href="#ref4">[4]</a><br>
	<br>
 	No caso de soluções isostáticas com balanços (Figura. <a href="#fig4">4</a>) a recomendação de Areias Neto <a href="#ref2">[2]</a> é:
  <br><br>
  𝑙/5 ≤ 𝑎 ≤ 𝑙/2 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Valor similar ao apresentado por DNIT <a href="#ref4">[4]</a>
</p>
<br>


<p id="fig4"></p>
<center><img src="./assets/images/aula4_predim/FIG_4.png" width="90%"></center>
<p align = "justify"><b>Figura 4.</b> Viga isostática com balanço <a href="#ref2">[2]</a>.</p>
<br>

<p align = "jsutify">
  Araújo <a href="#ref3">[3]</a> replica algumas recomendações extras de DNIT <a href="#ref4">[4]</a> para o uso dos balanços:
 	<br><br>
    <ul>
      <li>Aterro com altura limitada a oito metros, ou menos;</li><br>
      <li>Aterro de acesso executado antes da obra de arte;</li><br>
      <li>Balanço (a) com comprimento máximo de 7,5 m e sua flecha deverá ser menor que 2 cm;</li><br>
      <li>Deve-se usar laje de transição de comprimento mínimo de 4 m.</li>
	</ul>
	<br>
 	Em sistema de viga contínua Areias Neto <a href="#ref3">[3]</a> faz as seguintes recomendações:
  <br><br>
  a) Vigas contínuas com dois vãos:
</p>
<br>


<p id="fig5"></p>
<center><img src="./assets/images/aula4_predim/FIG_5.jpg" width="90%"></center>
<p align = "justify"><b>Figura 5.</b> Viga contínua com dois vãos <a href="#ref2">[2]</a>.</p>
<p align = "justify">
  As mediidas da Figura. <a href="#fig5">5</a> são:<br>
  𝑙<sub>1</sub> = 𝑙<sub>2</sub> <br>
  𝑎 = 𝑙<sub>1</sub>/4
</p>
<br>

<p align = "justify"><b>
  b)  Vigas contínuas com três e quatro vãos:
</b></p>
<br>

<p id="fig6"></p>
<center><img src="./assets/images/aula4_predim/FIG_6.png" width="90%"></center>
<p align = "justify"><b>Figura 6.</b> Geometria da viga contínua <a href="#ref2">[2]</a>.</p>
<p align = "justify">
  As mediidas da Figura. <a href="#fig6">6</a> são:<br><br>
  0,60.𝑙<sub>2</sub>≤  𝑙<sub>1</sub> ≤ 0,80.𝑙<sub>2</sub><br>
  𝑎 = 𝑙<sub>1</sub>/4
</p>
<br>

<h2>Algumas especificações para tabuleiro e lajes em balanço</h2>

<p align = "justify">
  Quanto a seção transversal de lajes o manual do DNIT <a href="#ref4">[4]</a> de obras de arte apresenta a Tabela. <a href="#tab1">1</a>.
</p>
<br>


<p id="tab1"></p>
<center>
<table>
    <tr>
        <th colspan = "">
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Vão da Laje (m)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
         </th> 
         <th colspan = "">
           &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Espessura da Laje (cm)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
         </th> 
    </tr>  
     <tr>
        <th coslpan = "">
           2
         </th>  
         <th>
           15
         </th>
    </tr>  
     <tr>
        <th >
           3
         </th>       
         <th>
           18
         </th>
    </tr> 
     <tr>
        <th >
          4
         </th>    
         <th>
           20
         </th>
    </tr> 
    <tr>
        <th >
           5
         </th>    
         <th>
          22
         </th>
    </tr> 
    <tr>
        <th >
        6
         </th>    
         <th>
          25
         </th>
    </tr> 
</table>
</center>
<p align = "justify"><b>Tabela 1.</b> Espessura da laje [4].<a href="#ref2">[2]</a>.</p>
<br>

<p align = "jstify">
  DNIT <a href="#ref4">[4]</a> afirma que em concreto armado convencional as lajes são utilizadas para vãos até 15 metros, com relação altura/vão da ordem de 1/15, em vãos isostáticos, e 1/20 e 1/24, em vãos contínuos.
  <br><br>
  A norma regulamentadora NBR 7187 <a href="#ref5">[5]</a>, traz as seguintes exigências quanto as dimensões dos elementos estruturais nas pontes:
	<br><br>
	Nas lajes maciças as dimensões mínimas são:
	<br><br>
	<ul>
		<li>Lajes destinadas à passagem de tráfego ferroviário: h ≥20 cm;</li>
		<li>Lajes destinadas à passagem de tráfego rodoviário: h ≥15 cm;</li>
		<li>Demais casos: h ≥12 cm.</li>
	</ul>
</p>
<br>

<h2>O gabarito da pontes</h2>

<p align = "justify">
  De acordo com Pfeil <a href="#ref6">[6]</a>, os gabaritos são denominados os conjuntos de espaços livres que deve apresentar o projeto de uma ponte para atender o seu intuito. De uma forma geral, pode-se especificar os gabaritos quanto a finalidade de implantação da estrutura, tais como:
	<br><br>
	(a) Estruturas construídas sobre rodovias: Devem respeitar espaços livres, necessário para tráfego de caminhões (Figura. <a href="#fig7">7</a>).
</p>
<br>

<p id="fig7"></p>
<center><img src="./assets/images/aula4_predim/FIG_7.png" width="90%"></center>
<p align = "justify"><b>Figura 7.</b> Gabarito para obras de arte sobre rodovias – (a) rodovia de pista simples e (b) rodovia de pista dupla <a href="#ref6">[6]</a>.</p>
<br>

<p align = "justify">
  (a) Estruturas construídas sobre ferrovias: Devem respeitar espaços livres, necessário para tráfego de trens (Figura. <a href="#fig8">8</a> ).
</p>
<br>

<p id="fig8"></p>
<center><img src="./assets/images/aula4_predim/FIG_8.png" width="90%"></center>
<p align = "justify"><b>Figura 8.</b> Gabarito para obras de arte sobre ferrovias – (a) rodovia de pista simples e (b) rodovia de pista dupla <a href="#ref6">[6]</a>.</p>
<br>

<p align = "justify">
  (a) Estruturas construídas sobre vias navegáveis: Para vias navegáveis a chatas e rebocadores, é comum prever-se a altura livre de 3,50m a 5,0m acima do nível máximo de cheia. A largura deve atender no mínimo a largura máxima da embarcação mais 1,m (Figura. <a href="#fig9">9</a>).
 	<br><br>
  Para estruturas construídas sobre vias não navegáveis normalmente se estabelece uma altura livre de 2 m acima do nível de máxima cheia. 
	<br><br>
	Na Figura. <a href="#fig9">9</a> é apresentado o gabarito da ponte sobre o Rio Paraguai em Cáceres-MT, com gabarito de 30 m de largura por 12 m de altura sobre nível máximo de cheia das águas.
</p>
<br>

<p id="fig9"></p>
<center><img src="./assets/images/aula4_predim/FIG_9.jpg" width="90%"></center>
<p align = "justify"><b>Figura 9.</b> Exemplo de ponte com gabarito de navegação 35,00m x 12,00m <a href="#ref6">[6]</a>.</p>
<br>


<h2>Algumas especificações para os pilares e aparelhos de apoio</h2>

<p align = "justify">
  O desenvolvimento do pré-dimensionamento dos pilares e dos aparelhos de apoio para uma ponte é dependente da previsão de cargas nessas estruturas. Após isso as condições de pré-dimensionamento do pilar por exemplo segue as mesmas observações impostas para os elementos de estruturas prediais normalmente estudadas nas disciplinas de concreto armado.
	<br><br>
	<b>a) Pré-dimensionamento dos pilares:</b>
</p>

<table align = "center" border = "1">
       <tr>
        <th>
	        N*<sub>d</sub> = 𝛼 . N*<sub>k</sub>
        </th>
        <th rowspan = "2">
	        𝛼 = 1,8 – Pilares intermediários;<br><br>
          𝛼 = 2,2 – Pilares de extremidade;<br><br>
          𝛼 = 2,5 – Pilares de canto.<br><br>
        </th>
    </tr>
    <tr>
        <th >
         𝐴_𝑐=(1,50〖.𝑁〗_𝑑^∗)/(0,50.𝑓_𝑐𝑘+0,42)≥360 〖𝑐𝑚〗^2
         </th>            
    </tr>      
</table>
<br>

<p align = "justify">
  𝐴_𝑐: Área da seção de concreto do pilar ("cm²");
	<br><br>
	𝑁_𝑑: Força normal aproximada de cálculo (kN);
	<br><br>
	𝑓_𝑐𝑘: Resistência característica de cálculo ("kN/cm²").
	<br><br>
	É recomendável que a verificação das dimensões do pilares sejam verificadas após a previsão das dimensões dos aparelhos de apoio visto que estes devem se encaixar dentro dos pilares
	<br><br><br>
	<b>b) Pré-dimensionamento dos aparelhos de apoio em Neoprene:</b>
	<br><br>
	Para o pré-dimensionamento e dimensionamento dos aparelhos de apoio será utilizada a NBR 9062 <a href="#ref7">[7]</a> e descrições do tópico 7.2.1.6 e no Anexo A.
 	<ul>
		<li>Tensão limitante para aparelhos de apoios simples: 𝜎_𝑘=(𝑁_𝑘^∗)/(𝑎.𝑏)≤7 𝑀𝑃𝑎. Onde a (menor dimensão em planta) e b designam as dimensões em planta do aparelho;</li><br><br>
		<li>Tensão limitante para aparelhos de apoios fretados: 
		<br><br>
		𝑎 ≤ 15 𝑐𝑚 reflete 𝜎<sub>𝑘</sub> ≤ 8 𝑀𝑃𝑎
		<br><br>
		15 𝑐𝑚 < 𝑎 ≤2 0 𝑐𝑚 e 𝜎<sub>𝑘</sub> ≤ 11 𝑀𝑃𝑎
		<br><br>
		20 𝑐𝑚 <𝑎 ≤30 𝑐𝑚 e 𝜎<sub>𝑘</sub> ≤ 12,5 𝑀𝑃𝑎
		<br><br>
		𝑎 > 30 𝑐𝑚 e 𝜎<sub>𝑘</sub> ≤ 15 𝑀𝑃𝑎
		</li>
	</ul>
	<br>
 	Em relação a altura é necessário estabelecer diversos critérios relativos ao dimensionamento do aparelho, para uma verificação inicial vamos estabelecer a proposição da NBR 9062 <a href="#ref7">[7]</a> que promove a dispensa da verificação de estabilidade da almofada.
  <br><br>
  ℎ<sub>𝑎𝑙𝑚𝑜𝑓𝑎𝑑𝑎</sub> ≤ 𝑎 / 5
</p>
<br>

<h1>Lançamento Estrutural</h1>

<p align = "justify">
  Para o lançamento estrutural o primeiro dado que o engenheiro estrutural tem acesso é o levantamento topográfico (Figura. <a href="#fig10">10</a>) fornecido pela concessionária responsável pelo projeto. Após a visualização do estaqueamento e do eixo para colocação da ponte é necessário realizar um estudo hidrológico para determinação da Altura de Máxima Cheia.
</p>
<br>


<p id="fig10"></p>
<center><img src="./assets/images/aula4_predim/FIG_10.png" width="90%"></center>
<p align = "justify"><b>Figura 10.</b> Croqui da trajetória do leito do rio e também marcação do estaqueamento.</p>
<br>

<p id="tab2"></p>
<center><img src="./assets/images/aula4_predim/tab_2.jpg" width="90%"></center>
<p align = "justify"><b>Tabela 2.</b> Determinação da vazão de projeto e cota referente a máxima cheia <a href="#ref3">[3]</a>. 
<br><br>
Dados do projeto de Araújo <a href="#ref3">[3]</a>:
	<br><br>
	Q = 691,02 𝑚<sup>3</sup>/𝑠
	<br>
	Cota de fundo = 208,678 (m)
</p>
<br>


<center><img src="./assets/images/aula4_predim/FIG_10_1.png" width="90%"></center>
<p align = "justify">
 Onde:<br>
           <ul style = "text-align:left">
           		<li><p><b>Q</b> = Vazão (m<sup>3</sup> / s);</p></li>
                <li><p><b>A</b> = Área da seção molhada (m<sup>2</sup>;</p></li>
                <li><p><b>K</b> = Coeficiente de rugosidade de Strickler;</p></li>
                <li><p><b>n</b> = Coeficiente de rugosidade de Manning;</p></li>
                <li><p><b>V</b> = CoVelocidade de escoamento (m/s);</p></li>
                <li><p><b>R</b> = Raio hidráulico 9m) -> <b>R = A/P</b> (P = Perímetro molhado);</p></li>
                <li><p><b>J</b> = Declividade do fundo (m/m).</p></li>
           </ul>
</p>
<br>
<br>

<p id="fig11"></p>
<center><img src="./assets/images/aula4_predim/FIG_11.png" width="90%"></center>
<p align = "justify"><b>Figura 11.</b> Elevação longitudinal com a marcação do estaqueamento e MCC.</p>
<br>


<h3>Bibliografia</h3>

<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Referências</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><p align = "center" id = "ref1">[1]</p></td>
            <td><p align = "left">C. O’Connor, Pontes - Superestruturas, vol. 1, 2 vols. LTC, 1976.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref2">[2]</p></td>
            <td><p align = "left">A. C. de Areias Neto, Projeto e Cálculo de Pontes de Concreto Armado, vol. 1. Rio de Janeiro: IME, 1977.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref3">[3]</p></td>
            <td><p align = "left">D. de L. Araújo, Projeto de ponte em concreto armado com duas longarinas, 2o ed. Goiânia: UFG, 2018.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref4">[4]</p></td>
            <td><p align = "left">Departamento Nacional de Infraestrutura de Transportes (DNIT), Manual de Projeto de Obras de Arte Especiais. Brasília: Ministério da Infraestrutura, 1996.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref5">[5]</p></td>
            <td><p align = "left">Associação Brasileira de Normas Técnicas, NBR 7187: Projeto de pontes de concreto armado e de concreto protendido - Procedimento. Rio de Janeiro: ABNT, 2003.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref6">[6]</p></td>
            <td><p align = "left">W. Pfeil, Pontes Em Concreto Armado: elementos de Projeto, Solicitações e Superestrutura, vol. 1, 2 vols. Rio de Janeiro: LTC, 1990.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref7">[7]</p></td>
            <td><p align = "left">Associação Brasileira de Normas Técnicas, NBR 9062: Projeto e execução de estruturas de concreto pré-moldado. Rio de Janeiro: ABNT, 2017.</p></td>
        </tr>
    </tbody>
</table>


<p>--------------------------------------------------------------------------------------------------------------------------------</p>



<h1>Solicitações para o sistema de viga contínua</h1>

<h2>Esforços Horizontais</h2>

<p align = "justify">
  Como o sistema é monolítico os deslocamentos sofridos pelo tabuleiro serão repassados ao topo de cada pilar de concreto da mesoestrutura. Segundo Taguti (2002) os seguintes esforços atuam transversalmente ao pilares:
  <br><br>
  a) Esforços longitudinais atuantes no tabuleiro
  - Frenagem e aceleração de veículos
  - Empuxo de terra e sobrecarga na cortina
  - Componente longitudinal do vento, calculadas da seguinte forma:
  - vento na superestrutura = 25% do esforço de vento na direção transversal
  - vento no veículo = 40%
  <br><br>
  b) Esforços transversais atuantes no tabuleiro
  - Vento
  - Força centrífuga (pontes em curva horizontal)
  - Impacto lateral (pontes ferroviárias)
  - Empuxo de terra nas cortinas ( pontes esconsas)
  <br><br>
  c) Esforços devidos a deformações impostas
  - Efeito da temperatura nas vigas principais
  - Efeito da retração nas vigas principais
  <br><br>
  d) Esforços que atuam diretamente sobre os pilares
  - Empuxo de terra
  - Pressão do vento
  - Pressão d'água
</p>
<br><br><br>

<h1>Determinação das solicitações nos pilares</h1>

<h2>Solicitação para sistema em viga contínua</h2>

<p align = "justify">
  De acordo com Araújo (2010) o sistema formado por vigas contínuas, quando
  a superestrutura sofre um deslocamento horizontal o topo dos pilares sofre o
  mesmo deslocamento por estes estarem ligados à superestrutura. O esforço
  aplicado ao topo de cada pilar é igual ao produto do deslocamento pela
  rigidez do pilar (K). Portando faz-se a equação:
</p>





<p align = "justify">
  (a) Estruturas construídas sobre vias navegáveis: Para vias navegáveis a chatas e rebocadores, é comum prever-se a altura livre de 3,50m a 5,0m acima do nível máximo de cheia. A largura deve atender no mínimo a largura máxima da embarcação mais 1,m (Figura. <a href="#fig9">9</a>).
 	<br><br>
  Para estruturas construídas sobre vias não navegáveis normalmente se estabelece uma altura livre de 2 m acima do nível de máxima cheia. 
	<br><br>
	Na Figura. <a href="#fig9">9</a> é apresentado o gabarito da ponte sobre o Rio Paraguai em Cáceres-MT, com gabarito de 30 m de largura por 12 m de altura sobre nível máximo de cheia das águas.
</p>
<br>



<p id="fig1"></p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_1_1.png" width="90%"></center>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_1.png" width="90%"></center>
<p align = "justify"><b>Figura 1.</b> Distribuição das cargas variáveis sobre o tabuleiro da ponte.</p>
<br>

<h2>Rigidez de pilares Engastado-livre</h2>

<p align = "justify">
  Utilizando-se o modelo para as cargas horizontais, onde os pilares e seus
  respectivos aparelhos de apoio são considerados apoios elásticos, resulta que
  a superestrutura submetida a um esforço horizontal longitudinal F , sofre um
  deslocamento D e, consequentemente, todos os topos dos pilares
  também se deslocarão de D (Fig. <a href="#fig2">2</a>) . Com isso, a solução do
  problema se torna simples, bastando para tanto o cálculo das rigezas dos
  apoios elásticos (formado pelo conjunto: pilar e aparelho de apoio).
</p>
<br>


<p id="fig2"></p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_2.png" width="90%"></center>
<p align = "justify"><b>Figura 2.</b> Modelo de cálculo da distribuição de forças longitudinais entre os apoios elásticos.</p>
<br>

<p align = "justify">
Verificando o sistema pilar apoio como uma barra engastada livre (Figura. <a href="#fig3">3</a>)
têm-se então o valor da rigidez de cada pilar:
</p>
<br>

<p id="fig3"></p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_3.png" width="90%"></center>
<p align = "justify"><b>Figura 3.</b> Modelo do pilar de concreto armado engastado-livre.</p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_3_1.png" width="90%"></center>
<br>

<p align = "justify">
  Considerando agora a rigidez do aparelho de apoio têm-se então:
</p>
<br>

<p id="fig4"></p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_4.png" width="90%"></center>
<p align = "justify"><b>Figura 4.</b> Modelo do apoio em neoprene.</p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_4_1.png" width="90%"></center>
<br>

<p align = "justify">
  Considerando agora a rigidez do conjunto completo tem-se o
  comportamento completo da ligação. A associação do pilar engastado-livre
  e o apoio em neoprene resultará em um elemento de rigidez Ki.
</p>
<br>

<p id="fig5"></p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_5.png" width="90%"></center>
<p align = "justify"><b>Figura 5.</b> Modelo completo do apoio elástico.</p>
<left><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_5_1.png" width="90%"></left>
<br>


<h2>Rigidez de pilares biengastados</h2>

<p align = "justify">
  Araújo (2010) cita a rigidez de pilares biengastados. Segundo o mesmo
  quando o pilar é biengastado, o procedimento é análogo, podendo a rigidez
  ser calculada como o inverso da flexibilidade (processo dos esforços) ou
  obtida diretamente de tabelas. Para o caso particular de pilar biengastado
  de inércia constante sua rigidez vale:
</p>
<br>

<p id="fig6"></p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_6.png" width="90%"></center>
<p align = "justify"><b>Figura 6.</b> Modelo do pilar biengastado.</p>
<left><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_6_1.png" width="90%"></left>
<br>

<p align = "justify">
  O cálculo da distribuição do esforço longitudinal entre os pilares é geralmente
  feito admitindo que o esforço horizontal seja aplicado no eixo de simetria do
  tabuleiro. No caso de pontes rodoviárias, por exemplo, admite-se que o
  veículo tipo, ao freiar, esteja circulando no centro da pista de rolamento. Esta
  simplificação é admissível considerando que, em geral, a largura das pontes é
  muito menor que o seu comprimento (PFEIL, 1983).
</p>
<br>

<h2>Distribuição dos esforços transversais</h2>

<p align = "justify">
  Devido à grande rigidez que as lajes concedem, no plano horizontal, ao
  tabuleiro da ponte, este pode ser considerado, sob a ação de esforços
  transversais, como uma placa sobre apoios elásticos. Quando esses esforços
  incidem no tabuleiro, este se desloca horizontalmente solicitando os pilares. Se
  o deslocamento for apenas uma translação na direção horizontal, o
  problema é análogo ao de distribuição de esforços longitudinais, ou seja,
  cada eixo recebe um quinhão de carga proporcional à sua rigidez na direção
  transversal (Figura. <a href="#fig7">7</a>). Neste caso, a rigidez transversal de cada pilar (ou eixo) deve ser calculada levando em conta a existência de vigas transversais
  ligando os pilares que formam, assim, pórticos nessa direção. Para tanto, a
  rigidez pode ser calculada como o inverso do deslocamento do topo do
  pórtico quando nesta posição é aplicada uma força unitária (ARAÚJO, 2010).
</p>
<br>

<p id="fig7"></p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_7.png" width="90%"></center>
<p align = "justify"><b>Figura 7.</b> Vista em planta da atuação de esforços transversais no tabuleiro (a); translação horizontal do tabuleiro (b); determinação da rigidez transversal do pórtico (c)
.</p>
<br>

<p id="fig8"></p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_8.png" width="90%"></center>
<p align = "justify"><b>Figura 8.</b> Vista em planta da atuação de esforços transversais no tabuleiro (a);
translação horizontal do tabuleiro (b); rotação horizontal do tabuleiro em torno do ponto (c).</p>
<br>

<p align = "justify">
  Quando ocorre a rotação do tabuleiro, cada pilar Pi, distante xi do ponto O,
  sofre um deslocamento horizontal θh xi, perpendicular ao eixo da ponte na
  posição original. Ao deslocamento do pilar corresponde um esforço Ki. θh. xi
  na direção do deslocamento, sendo Ki a rigidez do pilar (ou eixo) na direção
  desse deslocamento (ARAUJO, 2010).
</p>
<br>

<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_c.png" width="90%"></center>
<br>


<h1>Cálculo dos esforços longitudinais e transversais</h1>

<h2>Frenagem ou Aceleração</h2>

<p align = "justify">
  Um veículo qualquer em movimento sobre uma ponte representa, em virtude
  de sua massa, uma certa força-viva de que é possuída. A força resultante é
  chamada frenagem. Do mesmo modo, ao iniciar seu movimento apoia-se
  sobre a estrutura transmitindo à mesma um esforço chamado aceleração.
  <br><br>
  O item 7.2.1.5 da NBR 7187 (ABNT, 2003) cita as orientações relativas a essa
  carga. No caso são os seguintes valores:
  <br><br>
  a) Pontes rodoviárias: sem impacto, aplicada na pavimentação:
  Aceleração: 5% da carga móvel aplicada sobre o tabuleiro;
  Frenagem: 30% do peso do veículo-tipo.
  <br><br>
  Deve-se adotar o valor mais desfavorável segundo Pfeil (1983).
</p>
<br>

<h2>Empuxo de terra</h2>

<p align = "justify">
  O item 7.1.4 da NBR 7187 (ABNT, 2003) apresenta as condições para o cálculo
  dos empuxos de terra atuantes sobre os pilares.
  <br><br>
  O empuxo de terra nas estruturas é determinado de acordo com os princípios
  da mecânica dos solos, em função de sua natureza (ativo, passivo ou de
  repouso), das características do terreno, assim como das inclinações dos
  taludes e dos paramentos. Como simplificação, pode ser suposto que o solo
  não tenha coesão e que não haja atrito entre o terreno e a estrutura, desde
  que as solicitações assim determinadas estejam a favor da segurança.
  <br><br>
  O peso específico do solo úmido deve ser considerado no mínimo igual a 18
  kN/m³ e o ângulo de atrito interno no máximo igual a 30º. Os empuxos ativo e
  de repouso devem ser considerados nas situações mais desfavoráveis. A
  atuação do empuxo passivo só pode ser levada em conta quando sua
  ocorrência puder ser garantida ao longo de toda a vida útil da obra.
  <br><br>
  Quando a superestrutura funciona como arrimo dos aterros de acesso, a
  ação do empuxo de terra proveniente desses aterros pode ser considerada
  simultaneamente em ambas as extremidades somente no caso em que não
  haja juntas intermediárias do tabuleiro e desde que seja feita a verificação
  também para a hipótese de existir a ação em apenas uma das extremidades,
  agindo isoladamente (sem outras forças horizontais) e para o caso de
  estrutura em construção.
  <br><br>
  Nos casos de tabuleiro em curva ou esconso, deve ser considerada a
  atuação simultânea dos empuxos em ambas as extremidades, quando for
  mais desfavorável.
  <br><br>
  No caso de pilares implantados em taludes de aterro, deve ser adotada, para
  o cálculo do empuxo de terra, uma largura fictícia igual a três vezes a largura
  do pilar, devendo este valor ficar limitado à largura da plataforma do aterro.
</p>
<br>

<p id="fig9"></p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_9.png" width="90%"></center>
<p align = "justify"><b>Figura 9.</b> Distribuição das cargas variáveis sobre o tabuleiro da ponte.</p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_9_1.png" width="90%"></center>
<br>

<h2>Deformações internas no estrado</h2>

<p align = "justify">
  Sob a ação da retração do concreto, o tabuleiro se encurta. Sob ação da
  temperatura, o tabuleiro se alonga ou se encurta, conforme a temperatura
  cresça ou decresça. Dada a sua ligação com o tabuleiro, os pilares são
  obrigados a acompanhar esse movimentos, resultando esforços aplicados nos
  topos dos pilares (ARAÚJO, 2010).
  <br><br>
  O efeito da retração pode ser assimilado a uma variação de temperatura de
  -15C. Quando todos os pilares sobre os quais o estrado se apoia são elásticos,
  os movimentos de alongamento e encurtamento ocorrem nos dois sentidos
  da direção longitudinal do tabuleiro e há, evidentemente, um plano
  perpendicular a essa direção no qual não ocorrem deslocamentos. Esse plano
  fica localizado no “centro de gravidade” das rigezas longitudinais, o qual é
  determinado de forma análoga ao “centro de gravidade” das rigezas
  transversais (ARAÚJO, 2010).
  <br><br>
  Conhecida a distância x de cada pilar ao ponto indeslocável, o
  deslocamento de seu topo é dado pela expressão αc.ΔT. x , no qual ac é o
  coeficiente de dilatação térmica do concreto armado (10<sup>-5</sup>/C) e ΔT é a
  variação de temperatura. O esforço aplicado no topo de cada pilar, devido
  à retração e à variação de temperatura, é dado por (ARAÚJO, 2010):
</p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_c1.png" width="90%"></center>
<br>

<h2> Vento na Estrutura</h2>

<p align = "justify">
  De acordo com a NBR 7187, o vento é considerado uma força horizontal agindo normalmente ao eixo da estrutura e unifimemente distribuído ao longo desse eixo. O valor dessa força é o seguite: (MARCHETTI, 2008)
  <br><br>
  a)  Ponte descarregada - pv = 1,5 kN / m<sup>2</sup> - agindo sobre uma superfície representada pela projeção da estrutura sobre um plano vertical normal à direção do vento.
  <br><br>
  b)  Ponte carregada: 
  <br>
  para pontes rodovíarias: pv = 1 kN / m<sup>2</sup>
  <br>
  para passarelas: pv = 0,7 kN / m<sup>2</sup>
</p>
<br>


<p id="fig10"></p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_10.png" width="90%"></center>
<p align = "justify"><b>Figura 10.</b> Configuração das cargas de vento atuantes considerando a ponte descarregada.</p>
<p><b>F<sub>vento</sub> = 1,50 x (H<sup>guarde-rodas</sup> + H<sup>viga</sup>) x L<sup>ponte</sup></b></p>
<br><br>

<p id="fig11"></p>
<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_11.png" width="90%"></center>
<p align = "justify"><b>Figura 11.</b> – Configuração das cargas de vento atuantes considerando a ponte carregada.</p>
<p><b>F<sub>vento</sub> = 1,00 x (H<sup>viga</sup> + e<sup>pavimentação</sup> + 2,0) x L<sup>ponte</sup></b></p>
<br>

<h2>Pressão da água nos pilares</h2>

<p align = "justify">
  A água correte exerce um esforço na infraestrutura da ponte que pode ser expresso por:<br><br>
  p = <i>k</i>v<sup>2</sup> (KN / m)
  <br><br>
  Onde:<br>
  <i>k</i> é o coeficiente dimensional e <br>
  <i>v</i> é a velocidade da água corrente
</p>
<br>

<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_c2.png" width="90%"></center>

<p align = "justify">
  No caso de não existir informação da velocidade da água, adotaremos a velocidade da água v = 2 m/s (adotado), ou então, se não houver medição no local.
</p>
<br>

<h2>Impacto nos Pilares</h2>

<p align = "justify">
  A NBR 7187 estabelece que, no caso da possibilidade desses choques, deverão ser tomadas medidas especiais de proteção dos pilares, as quais podem ser representadas por defensas, "Duques de Alba" (embarcações) etc.
</p>
<br>

<center><img src="./assets/images/aula_pontes_CA_dimen_pilares/FIG_c3.png" width="90%"></center>
<br>

<p align = "justify">
  A NBR 7187, todavia, não estabelece qual o valor a assumir para a força horizontal devido ao choque dos veículos ou embracações. Outras normas, porém, como a norma alemã (D.I.N), estabelecem para essa força horizontal valores bastante elevados. Por exemplo, na D.I.N:<br><br>
   H = 1000 kN no sentido longitudinal<br>
   H = 500 kN no sentido transversal
   <br><br>
   aplicados a 1 m de altura
</p>

<p>---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------</p>

<p>aula "determinação dos esforços no tabuleiro"</p>

<h1>Conceitos Iniciais sobre o tabuleiro</h1>
<br>

<h2>O tabuleiro da Ponte</h2>

<p align = "justify">
  Stucchi (2006) primeiramente classifica geometricamente uma estrutura superficial que forma a ponte. Para o autor os elementos de superfície são  estruturas  que  têm  uma  de  suas  dimensões  bem  menor  que  as  outras  duas.  Ela  é chamada de espessura. 
  <br><br>
  A superfície média é a definida a meia espessura, perpendicularmente à ela. 
  <br><br>
  As estruturas de superfície são classificadas em: 
  <br><br>
  a) Placa: Estrutura de superfície média plana carregada perpendicularmente à ela.
  As placas de concreto armado são chamadas lajes;<br>
  b) Chapa: Estruturas de superfície média plana carregada paralelamente a ela. As chapas de concreto armado são chamadas vigas parede. <br>
  c) Casca: Estruturas de superfície média curva.
</p>
<br>

<p id="fig1"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_1.png" width="90%"></center>
<p align = "justify"><b>Figura 1.</b> Exemplos de estruturas de superfície.</p>
<br>

<p align = "justify">
  O tabuleiro das pontes em concreto é constituído por lajes ligadas de diversas
  maneiras aos demais elementos da superestrutura. Esses elementos, que servem de apoio paras as lajes, são as longarinas, as transversinas e as vigas de fechamento. As dimensões e as condições de apoio das lajes são função da distribuição dos demais elementos da superestrutura. A forma mais comum para as lajes de ponte são aquelas em que uma dimensão é muito maior que a outra. Quanto às condições de apoio, as lajes podem ser apoiadas, em balanço ou com engastamento parcial (ARAÚJO, 2010). 
  <br><br>
  Araújo (2010) apresenta na Figura. <a href="#fig7">7</a> uma seção transversal típica de uma ponte de concreto.
</p>
<br>

<p id="fig2"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_2.png" width="90%"></center>
<p align = "justify"><b>Figura 2.</b> Tipos de ciclos de tensão.</p>
<br>

<p align = "justify">
  Segundo Araújo (2010) o dimensionamento das lajes pode ser feito por métodos elásticos ou métodos baseados nas linhas de ruptura (ou charneiras plásticas). Os métodos elásticos baseiam-se na teoria da elasticidade levando em consideração a forma de distribuição das cargas móveis sobre o tabuleiro. Os métodos baseados nas linhas de ruptura definem uma provável configuração de fissuras na laje e, a partir do equilíbrio estático do painel, fornecem os momentos fletores empregados no dimensionamento da laje. Atualmente tem sido empregados métodos discretos para avaliação dos esforços em lajes de pontes. Dentre esses métodos, destaca-se o método dos elementos finitos que, empregado com o auxílio de microcomputadores, agiliza os cálculos dos esforços além de fornecer uma visão mais completa do comportamento do tabuleiro.
  <br><br>
  Nesse texto será apresentado o método elástico para determinação dos esforços e superfícies de influência do tabuleiro da ponte. Para tanto será explicado o método do professor Hubert Rush mais conhecidos como tabelas de Rush.
</p>
<br>

<h2>Conceitos Iniciais de Superfície de influência</h2>

<p align = "justify">
  No tabuleiro de pontes os responsáveis por gerar esforços nessa peças, são os veículos tipos que transitam ao longo do eixo da peça. Portanto a análise dos esforços em uma placa seguirá os mesmos conceitos das linhas de influência visto no capitulo anterior, porém agora o conceito terá o nome de superfície de influência, pois será admitido para um elementos de placa.

  Como o método descrito é elástico a sua solução será dada através da solução da equação da placa conforme apresentado nas disciplinas de lajes de concreto armado.

  Admitindo que tem transmite os esforços para a placa são as rodas do veículo tipo o problema será dado em função dessa ordenada. Araújo (2010) afirma que a força se distribuirá em uma certa área – em geral, considera-se o espalhamento da força a 45º até o plano médio da laje, o momento então será dado pela ordenada média da superfície nessa área, cujo valor pode ser calculado numericamente (Ver Figura. <a href="#fig3">3</a>).
</p>
<br>

<p id="fig3"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_3.png" width="90%"></center>
<p align = "justify"><b>Figura 3.</b> Superfície média para cálculo de uma distância média.</p>
<br>

<p align = "justify">
  Como o conceito é estendido do problema unidimensional, têm-se então a versão bi-dimensional da determinação da superfície de influência do sólido, dado pela equação a abaixo:
</p>

<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_c1.png" width="90%"></center>
<br>

<p align = "justify">
  Logo o efeito que será simulado é dado na Figura. <a href="#fig4">4</a>
</p>
<br>

<p id="fig4"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_4.png" width="90%"></center>
<p align = "justify"><b>Figura 4.</b> Superfície de influência para um efeito S específico.</p>
<br>

<p align = "justify">
  Resolvendo o problema geral dado anteriormente o esforço final em uma placa será dado pela equação abaixo:
</p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_c2.png" width="90%"></center>

<p align = "justify">
  Onde V<sub>i</sub> e A<sub>i</sub> são, respectivamente, os volumes e as áreas determinadas na superfície de influência pela projeção no plano da laje das áreas ou linhas de atuação das forças, e  δ<sub>i</sub> são as ordenadas dos pontos de atuação das forças concentradas (ARAÚJO, 2010).

  Algumas bibliografias como Timoshenko; Krieger (1987) e Araújo (2010) apresentam exemplos e superfícies de influência. Portanto ver as Figuras. <a href="#fig5">5</a> e <a href="#fig6">6</a>
</p>
<br>

<p id="fig5"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_5.png" width="90%"></center>
<p align = "justify"><b>Figura 5.</b> Superfície de influência de uma placa retangular.</p>
<br>

<p id="fig6"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_6.png" width="90%"></center>
<p align = "justify"><b>Figura 6.</b> Superfície de influência do momento fletor na seção do meio do vão de uma
laje retangular apoiada nos quatro lados.
</p>
<br>

<h1>Ações no Tabuleiro</h1>

<h2>Tipo e Cálculo das Ações no Tabuleiro</h2>

<p align = "justify">
  De maneira geral as cargas irão ser divididas em permanentes e variável. A seguir serão listadas algumas cargas que são encontradas comumente em lajes de concreto. 
  <br><br>
  Carregamentos em lajes maciças são normalmente anotados em função de uma área, portanto na maioria das vezes é dada pelo equacionamento abaixo:
</p>
<p id="eque1">
<b>
G<sub>tipo</sub> = h . desnsidade
</b>
</p>
<p align = "justify">
  O peso próprio da laje é o peso do concreto armado que forma a laje maciça. Para o peso específico do concreto armado a NBR 6118 (ABNT, 2014) indica o valor de 25 kN/m<sup>3</sup>.
  <br><br>
  Para as pontes de concreto considera-se o pavimento da pista de rolamento. Essa consideração deve ser feita em função do tipo de material. Para sistemas mais comuns que usam o CBUQ esse valor é de 24 kN/m<sup>3</sup> com a possibilidade de consideração do recapeamento sobre o sistema aumentando assim a carga permanente em 2 kN/m<sup>3</sup>.
  <br><br>
  A ação variável do sistema é a carga móvel, que irá depender do trem tipo escolhido.
  <br><br>
  Para a carga variável os valores serão definidas em função da NBR 7188 (ABNT, 2012). O trem tipo padrão estabelecido por essa norma é o TB-450 com carga total de 450 kN e carga por roda de 75 kN. Já a carga de multidão que circunda esse veiculo tipo é de 5 kN/m<sup>2</sup>.
</p>
<br>

<p id="fig7"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_7.png" width="90%"></center>
<p align = "justify"><b>Figura 7.</b> Seção transversal de uma ponte típica de 2 longarinas.
</p>
<br>

<h1>Utilização das Tabelas de RUSCH para Determinação dos Momentos</h1>

<h2>Apresentação da Tabela de RüSCH (1960)</h2>

<p align = "justify">
  As tabelas de Rüsch permitem a determinação das solicitações nas lajes, mediante condições de apoio prefixadas, incluindo apoio simples, engaste perfeito ou bordo livre. Para os diversos tipos de apoios são apresentados diagramas de cobrimento de momentos fletores para toda a superfície da laje a partir de máximos calculados no centro e nos bordos (ARAUJO, 2014).

  Nessa Tabela são fornecidos os valores do momento fletor, Mxm e Mym, no meio do vão da laje devido ao efeito das cargas das rodas do veículo (P = 1 t) e da sobrecarga uniformemente distribuída em volta do veículo (p = p’ = 1 t/m<sup>2</sup> ). A direção do tráfego é admitida, nessa tabela, na direção y, sendo a direção y adotada paralela ao maior vão da laje (ARAUJO, 2014).

  Para maiores detalhes é apresentada a tradução de Araújo (2014) referente a Tabela de Rüsch (1960) e o veículo tipo utilizado.
</p>
<br>

<p id="fig8"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_8.png" width="90%"></center>
<p align = "justify"><b>Figura 8.</b> Carga móvel da norma alemã DIN-1072 (classe 30 t a 60 t).
</p>
<br>

<p id="tab1"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/TAB_1.png" width="90%"></center>
<p align = "justify"><b>Tabela 1.</b> –  Tabela de Rüsch (1960) para momentos fletores em laje apoiada com tráfego na direção y (ly / lx = 1) 
</p>
<br>

<h2>Leitura da Tabela de RüSCH (1960)</h2>

<p align = "justify">
  A primeira identificação que deve ser feita é relativo ao tipo de engastamento da laje. Nas Tabelas de Rusch (1960) a identificação desse contorno é feito de acordo com a Figura. <a href="#fig9">9</a>
</p>
<br>

<p id="fig9"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_9.png" width="90%"></center>
<p align = "justify"><b>Figura 9.</b> Apresentação dos apoios na Tabela de Rusch
</p>
<br>

<p align = "justify">
  A segunda avaliação deve ser feita em relação a direção do tráfego (palavra Fahrtrichtung na Tabela) em relação ao tipo do engastamento. Veja os exemplos dados na Figura. <a href="#fig10">10</a>
  <br><br>
  A terceira tarefa se diz a respeito da geometria da laje pelo cálculo do fator 𝜆=𝑙_𝑦/𝑙_𝑥 , muito utilizada nas tabelas de cálculo de lajes em estruturas de concreto armado.
</p>

<p id="fig10"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_10.png" width="90%"></center>
<p align = "justify"><b>Figura 10.</b> Apresentação dos apoios na Tabela de Rusch
</p>
<br>

<p align = "justify">
  Identificada a Tabela através dessas características iniciais, deve-se então verificar os fatores. O primeiro fator é a relação \[𝑙_𝑥⁄𝑎\]. O fator a se diz respeito a distância adjacente entre as  rodas de um mesmo eixo. No caso do TB 450 o valor de a=200,00 cm ou 2,00 m. O segundo fator é a relação 𝑡⁄𝑎, onde t é a largura de distribuição da pressão da roda. Para maiores detalhes ver a Figura. <a href="#fig11">11</a>
</p>
<br>

<p id="fig11"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_11.png" width="90%"></center>
<p align = "justify"><b>Figura 11.</b> Representação das variáveis b e t na planta da laje
</p>
<br>

<p align = "justify">
  A largura t é dada por:
  <br>
  𝑡<sub>𝑥</sub> 𝑜𝑢 𝑡<sub>𝑦</sub> = 𝑏+2 . ℎ<sub>𝑝𝑎𝑣</sub> + ℎ<sub>𝑙𝑎𝑗𝑒</sub>
  <br>
  Como a roda tem contato nas duas direções é necessário fazer o valor médio de t, dado pela equação abaixo. Maiores detalhes na Figura. <a href="#fig12">12</a>
</p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_c3.png" width="90%"></center>
<p align = "justify">
  Portanto para finalizar a leitura da tabela de Rusch a mesma fornecerá os fatores de momento k para lançamento na equação de momentos descrita logo abaixo:
</p>
<br>

<p id="fig12"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_12.png" width="90%"></center>
<p align = "justify"><b>Figura 11.</b> Exemplo de perfil das rodas nas seções da ponte
</p>
<br>

<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_c4.png" width="90%"></center>
<br>

<p align = "justify">
  Para valores intermediários de t/a e l/a deve-se aplicar a interpolação. Para o caso de uma interpolação linear utiliza-se:
</p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_c5.png" width="90%"></center>
<br>

<p align = "justify">
  Os valores de k são recolhidos na parte superior da Tabela de Rusch (1960) conforme Tabela. <a href="#tab2">2</a> abaixo.
</p>
<br>

<p id="tab2"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/TAB_2.png" width="90%"></center>
<p align = "justify"><b>Tabela 2.</b> Fatores k da Tabela de Rusch
</p>
<br>

<p align = "justify">
  A escrita Gleichlast über die ganze platte significa carga uniformemente distribuída ao longo de toda a placa.  Ao lado dos valores de k são indicados os momentos a qual se deve usar o fator. Todos aqueles com terminação m são momento relativos ao meio da placa e a terminação e para os engastes.
  <br><br>
  Os fatores de carga móvel podem ser escolhidos através da visualização na Tabela ou uma interpolação linear simples. Vale salientar que para esses valores é necessário observar a posição da virgula na mesma, para não fazer nenhuma leitura errada.
</p>
<br>

<p id="tab3"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/TAB_3.png" width="90%"></center>
<p align = "justify"><b>Tabela 3.</b> Fatores de carga móvel da Tabela de Rusch
</p>
<br>

<p align = "justify">
  Os fatores do lado esquerdo são para o peso de cada roda do eixo ou o 𝑀<sub>𝐿</sub> da equação citada anteriormente enquanto os fatores do lado esquerdo são para as cargas de multidão da pontes (p interna e p’ carga externa) conforme orientação da Tabela. <a href="#tab1">1</a>
</p>
<br>

<h1>Correção da Continuidade da Laje</h1>

<h2>Considerações da Continuidade da Laje</h2>

<p align = "justify">
  Para o emprego das Tabelas de Rüsch (1960) na determinação das solicitações das lajes do tabuleiro de pontes, deve-se estabelecer condições de contorno ideais para os diversos painéis da laje. Esta escolha é, forçosamente, arbitrária dentro de certos limites. Existe ainda a necessidade de levar em conta a continuidade das lajes nos projetos, ao menos de forma aproximada, caso não se deseja fazer um cálculo rigoroso (ARAÚJO, 2010).
  <br><br>
  Um procedimento simplificado para avaliação da continuidade de lajes contínuas é apresentado pela NB2 (1961) para lajes apoiadas em vigas no contorno e com vãos iguais, ou em que o menor vão não seja inferior a 70% do maior vão. Esse procedimento faz uso de certa liberdade na distribuição dos momentos entre o apoio e o vão das lajes contínuas. Cada painel é calculado isoladamente como simplesmente apoiado no contorno. Para este fim, pode-se empregar qualquer dos métodos já mencionados, dos quais obtêm-se o momento máximo 𝑀<sub>(0,𝑚𝑎𝑥)</sub> no meio do vão. Adota-se a seguir um valor (𝑀<sub>𝑏</sub>) para o momento negativo no apoio que deverá estar compreendido entre 2/3 e 1/3 de 𝑀<sub>(0,𝑚𝑎𝑥)</sub>, sem ultrapassar 3/4 do maior momento na direção perpendicular à do momento máximo. Nos trechos em que 𝑀<sub>0</sub> < 𝑀<sub>𝑏</sub>, adota-se para o dimensionamento momentos negativos avaliados por: M = 𝑀<sub>0</sub> - 𝑀<sub>𝑏</sub>. Nos trechos em que 𝑀<sub>0</sub> > 0,6. 𝑀<sub>𝑏</sub>, adota-se para o dimensionamento momentos positivos avaliados por: M = 𝑀<sub>0</sub> - 0,6. 𝑀<sub>𝑏</sub> (ARAÚJO, 2010).
  <br><br>
  Primeiramente deve-se definir o eixo de continuidade da laje de acordo com a Figura. <a href="#fig13">13</a>
</p>
<br>

<p id="fig13"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_13.png" width="90%"></center>
<p align = "justify"><b>Figura 13.</b> Direção de continuidade da laje de tabuleiro
</p>
<br>

<p align = "justify">
  Por causa da preponderância dos momentos devidos à carga móvel frente àqueles devidos à carga permanente, faz-se a correção apenas nos primeiros. A Figura. <a href="#fig14">14</a> apresenta a consideração do tabuleiro como um todo. 
</p>
<br>

<p id="fig14"></p>
<center><img src="./assets/images/aula_esforco_tabuleiro/FIG_14.png" width="90%"></center>
<p align = "justify"><b>Figura 14.</b> Vista do painel de considerando os engastamento
</p>
<br>

<h1>Construção de Envoltória de Esforços</h1>

<h2>Considerações da Continuidade da Laje</h2>

<p align = "justify">
  Após  a  determinação  dos  valores  extremos  dos  momentos  fletores  ,  no
  centro  e  no  engaste  das  lajes    ,  é  necessário  obter  a  envoltória  dos  momentos  das  lajes  ,  para  que  se  possa retratar  as  condições  reais  de  vinculação  das  lajes  e  ,portanto,  possibilitar  um  melhor  detalhamento  das armaduras (TAGUTI, 2002).
  <br><br>
  Rüsch  fornece  envoltórias  de  momentos  fletores  ,construídas  a  partir  dos
  valores extremos obtidos por meio de suas tabelas ,  para os tipos usuais de vinculação. As envoltórias são fornecidas  para  momentos  devidos  à  carga  permanente  e  à  carga  móvel  (TAGUTI, 2002).
<p>
<br>



<p>------------------------------------------------------------------------------------------------------------------------------------------------</p>

<h1>Detalhamento da Seção Transversal</h1>


<p id="tab1"></p>
<center><img src="./assets/images/ECA_detalhamento_secao_transversal/TAB_1.png" width="90%"></center>
<p align = "justify"><b>Tabela 1.</b> Tabela de aços
</p>
<br>

<P align = "justify">
  Segundo Carvalho e Figueiredo Filho (2014) a armadura mínima deve ser colocada para evitar rupturas bruscas da seção, pois o aço faz com que ela apresente uma deformação razoável antes de entrar em ruína, já os valores máximos decorrem da necessidade de assegurar condições de ductilidade e de respeitar o campo de validade dos ensaios que deram origem as prescrições de funcionamento do conjunto  aço-concreto.
</p>
<br>

<center><img src="./assets/images/ECA_detalhamento_secao_transversal/FIG_c1.png" width="90%"></center>

<p align = "justify">
  Onde:
  <br>
  W<sub>o</sub> = Módulo de resistência da seção transversal bruta de concreto, relativo à fibra mais tracionada<br>
  f<sub>(ctk,sup)</sub> = Resistência característica superior do concreto à tração<br>
  f<sub>ctm</sub> = Resistência característica média do concreto à tração
</p>
<br>

<p id="tab2"></p>
<center><img src="./assets/images/ECA_detalhamento_secao_transversal/TAB_2.png" width="90%"></center>
<p align = "justify"><b>Tabela 2.</b> 
</p>
<br>
<br>
<center><img src="./assets/images/ECA_detalhamento_secao_transversal/FIG_c2.png" width="90%"></center>
<br>

<p align = "justify">
  Segundo Carvalho (2014) as armaduras de pele tem função de mitigar efeitos decorrentes da fissuração, retração e variação da temperatura nas faces de vigas de concreto, servindo também para controlar melhor a abertura de fissuras em vigas. <br>
  O critério de armadura de pele é aplicado para peças com altura maior ou igual a 60 cm, sendo que a ABNT NBR descreve suas caraterísticas no item 17.3.5.2.3. Sendo a armadura descrita pela equação a seguir:
</p>
<br>

<p id="fig1"></p>
<center><img src="./assets/images/ECA_detalhamento_secao_transversal/FIG_1.png" width="90%"></center>
<p align = "justify"><b>Figura 1.</b> 
</p>
<center><img src="./assets/images/ECA_detalhamento_secao_transversal/FIG_c3.png" width="90%"></center>
<br>

<p align = "justify">
  Segundo ABNT NBR 6118:2014 não é necessário uma armadura superior a 5 cm²/m por face do elemento.
  <br><br><br>
  Alguns projetistas recomendam o uso da armadura de pela para alturas superiores a 40 cm, melhorando assim o controle a fissuração. Bastos (2015) cita para altura maiores que 50 cm por exemplo.
  <br><br>
  O espaçamento disponível pode ser horizontal ou vertical, são dados através das seguintes equações:
</p>
<center><img src="./assets/images/ECA_detalhamento_secao_transversal/FIG_c4.png" width="90%"></center>
<br>

<p align = "justify">
  Fusco (1995) recomenda o acréscimo de mossas no cálculo do diâmetro final das barras. Sendo mossa, as saliências da armadura nervurada (CA 50)
</p>
<br>

<p id="tab3"></p>
<center><img src="./assets/images/ECA_detalhamento_secao_transversal/TAB_3.png" width="90%"></center>
<p align = "justify"><b>Tabela 3.</b> 
</p>
<br>
<br><br>

<p id="fig2"></p>
<center><img src="./assets/images/ECA_detalhamento_secao_transversal/FIG_2.png" width="90%"></center>
<p align = "justify"><b>Figura 2.</b> Espaçamento armaduras –Armadura simples 
<br><br><br>

<p id="fig3"></p>
<center><img src="./assets/images/ECA_detalhamento_secao_transversal/FIG_3.png" width="90%"></center>
<p align = "justify"><b>Figura 3.</b> Espaçamento entre feixes de armaduras 
<br>

<p align = "justify">
  Segundo Carvalho (2014) os esforços na armadura só podem ser considerados concentrados no centro de gravidade das barras se a distância deste centro ao ponto de armadura mais afastado da linha neutra(𝑎_𝑡𝑒𝑠𝑡𝑒), medida formalmente a ela, for menor que 10% de h. Já para a armadura concentrada considera-se o cálculo abaixo:
</p>
<br>
<center><img src="./assets/images/ECA_detalhamento_secao_transversal/FIG_c5.png" width="90%"></center>
<br>

<p>-----------------------------------------------------------------------------------------------------------------------------------------------------</p>

<h1>Determinação das ações na estrutura</h1>


<p id="tab1"></p>
<table border="1">
    <thead>
        <tr>
            <th colspan = "2">Materiais</th>
            <th>γ<sub>ap</sub> (kN/m³)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan ="5">1 Rochas</td>
            <td>Arenito</td>
            <td>21 a 27 (24)</td>
        </tr>
        <tr>
            <td>Basalto, diorito, gabro</td>
            <td>28</td>
        </tr>
        <tr>
            <td>Gnaisse</td>
            <td>30</td>
        </tr>
        <tr>
            <td>Granito, sienito, pórfiro</td>
            <td>27 a 30 (28,5)</td>
        </tr>
        <tr>
            <td>Mármore e Calcário</td>
            <td>28</td>
        </tr>
        <tr>
            <td rowspan ="6">2 Blocos artificiais e pisos</td>
            <td>Blocos de concreto vazados (função estrutural, classes A e B, ABNT NBR 6136)</td>
            <td>14</td>
        </tr>
        <tr>
            <td>Blocos cerâmicos vazados com paredes vazadas (função estrutural, ABNT NBR 15270-1)</td>
            <td>12</td>
        </tr>
        <tr>
            <td>Blocos cerâmicos vazados com paredes maciças (função estrutural, ABNT NBR 15270-1)</td>
            <td>14</td>
        </tr>
        <tr>
            <td>Blocos cerâmicos maciços</td>
            <td>18</td>
        </tr>
        <tr>
            <td>Lajotas cerâmicas</td>
            <td>18</td>
        </tr>
        <tr>
            <td>Porcelanato</td>
            <td>23</td>
        </tr>
        <tr>
            <td rowspan="6">3 Revestimentos e concretos</td>
            <td>Argamassa de cal, cimento e areia</td>
            <td>19</td>
        </tr>
        <tr>
            <td>Argamassa de cal</td>
            <td>12 a 18 (15)</td>
        </tr>
        <tr>
            <td>Argamassa de cimento e areia</td>
            <td>19 a 23 (21)</td>
        </tr>
        <tr>
            <td>Argamassa de gesso</td>
            <td>12 a 18 (15)</td>
        </tr>
        <tr>
            <td>Concreto simples</td>
            <td>24</td>
        </tr>
        <tr>
            <td>Concreto armado</td>
            <td>25</td>
        </tr>
    </tbody>
</table>
<p align = "justify"><b>Tabela 1.</b> [NOME A COLOCAR] </p>
<br>
<br>


<p id="tab2"></p>
<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th colspan = "2">Local</th>
      <th >Carga uniformemente distribuída (kN/m²)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="5">Áreas Técnicas</td>
      <td>Barrilete</td>
      <td>1,50<sup>1</sup></td>
    </tr>
    <tr>
      <td>Áreas Técnicas em Geral</td>
      <td>3,00</td>
    </tr>
    <tr>
      <td>Casa de máquinas de elevador de passageiros (vel ≤ 1,00 m/s)</td>
      <td>30,00<sup>2, 3, 4</sup></td>
    </tr>
    <tr>
      <td>Sala de gerador e transformador (sem leiaute)</td>
      <td>10,00</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td rowspan="7">Edifícios residenciais</td>
      <td>Dormitório</td>
      <td>1,50</td>
    </tr>
    <tr>
      <td>Sala, Copa e Cozinha</td>
      <td>1,50</td>
    </tr>
    <tr>
      <td>Despensa, área de serviço e lavanderia</td>
      <td>2,00</td>
    </tr>
    <tr>
      <td>Academia</td>
      <td>3,00<sup>5</sup></td>
    </tr>
    <tr>
      <td>Salão de festas, salão de jogos</td>
      <td>3,00<sup>5</sup></td>
    </tr>
    <tr>
      <td>Corredores de uso comum</td>
      <td>3,00</td>
    </tr>
    <tr>
      <td>Corredores dentro de unidades autônomas</td>
      <td>1,50</td>
    </tr>
    <tr>
      <td rowspan="5">Edifícios comerciais</td>
      <td>Salas de uso geral e sanitários</td>
      <td>2,50</td>
    </tr>
    <tr>
      <td>Regiões de arquivos deslizantes</td>
      <td>5,00</td>
    </tr>
    <tr>
      <td><i>Call center</i></td>
      <td>3,00</td>
    </tr>
    <tr>
      <td>Corredores de uso comum</td>
      <td>3,00</td>
    </tr>
    <tr>
      <td>Corredores dentro de unidades autônomas</td>
      <td>2,50</td>
    </tr>
  </tbody>
</table>
<p align = "justify"><b>Tabela 2.</b> [NOME A COLOCAR] </p>
<br>

<p align = "justify">
  Carga para Telhado
</p>
<center><img src="./assets/images/ECA_determinacao_acoes_estrutura/FIG_c1.png" width="90%"></center>
<br>



<p id="tab=3"></p>
<table border="1">
    <thead>
        <tr>
            <th rowspan = "2">Alvenaria</th>
            <th rowspan = "2">Espessura nominal do elemento (cm)</th>
            <th colspan="4">Peso - Espessura de revestimento por face (kN/m²)</th>
        </tr>
        <tr>
            <th>0 cm</th>
            <th>1 cm</th>
            <th>2 cm</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan="6"><b>ALVENARIA ESTRUTURAL</b></td>
        </tr>
        <tr>
            <td>Bloco de concreto vazado (Classes A e B - ABNT NBR 6136)</td>
            <td style = "text-align:center">
              14<br>
              19
            </td>
            <td>
              2,0<br>
              2,7
            </td>
            <td>
              2,3<br>
              3,0
            </td>
            <td>
              2,7<br>
              3,4
            </td>
        </tr>
        <tr>
            <td>Bloco cerâmico vazado com paredes maciças (Furo vertical - ABNT NBR 15270-1)</td>
            <td style = "text-align:center">14</td>
            <td>2,0</td>
            <td>2,3</td>
            <td>2,7</td>
        </tr>
        <tr>
            <td>Bloco cerâmico vazado com paredes vazadas (Furo vertical - ABNT NBR 15270-1)</td>
            <td style = "text-align:center">
              9<br>
              11,5<br>
              14<br>
              19
            </td>
            <td style = "text-align:center">
              1,1<br>
              1,4<br>
              1,7<br>
              2,3<br>
            </td>
            <td style = "text-align:center">
              1,5<br>
              1,8<br>
              2,1<br>
              2,7
            </td>
            <td style = "text-align:center">
              1,9<br>
              2,2<br>
              2,5<br>
              3,1
            </td>
        </tr>
        <tr>
            <td>Tijolo cerâmico maciço (ABNT NBR 15270-1)</td>
            <td style = "text-align:center">
              9<br>
              11,5<br>
              14<br>
              19
            </td>
            <td style = "text-align:center">
              1,6<br>
              2,1<br>
              2,5<br>
              3,4
            </td>
            <td style = "text-align:center">
              2,0<br>
              2,5<br>
              2,9<br>
              3,8
            </td>
            <td style = "text-align:center">
              2,4<br>
              2,9<br>
              3,3<br>
              4,2
            </td>
        </tr>
        <tr>
            <td>Bloco silico-calcário vazado (Classe E - ABNT NBR 14741-1)</td>
            <td style = "text-align:center">
              9<br>
              14<br>
              19
            </td>
            <td style = "text-align:center">
              1,1<br>
              1,5<br>
              1,9
            </td>
            <td style = "text-align:center">
              1,5<br>
              1,9<br>
              2,3
            </td>
            <td style = "text-align:center">
              1,9<br>
              2,3<br>
              2,7
            </td>
        </tr>
        <tr>
            <td>Bloco silico-calcário perfurado (Classes F, E, G - ABNT NBR 14741-1)</td>
            <td style = "text-align:center">
              11,5<br>
              14<br>
              17,5
            </td>
            <td style = "text-align:center">
              1,9<br>
              2,1<br>
              2,8
            </td>
            <td style = "text-align:center">
              2,3<br>
              2,5<br>
              3,2
            </td>
            <td style = "text-align:center">
              2,7<br>
              2,9<br>
              3,6
            </td>
        </tr>
        <tr>
            <td colspan="6"><b>ALVENARIA DE VEDAÇÃO</b></td>
        </tr>
        <tr>
            <td>Bloco de concreto vazado (Classe C - ABNT NBR 6136)</td>
            <td style = "text-align:center">
              6,5<br>
              9<br>
              11,5<br>
              14<br>
              19
            </td>
            <td style = "text-align:center">
              1,0<br>
              1,1<br>
              1,3<br>
              1,4<br>
              1,8
            </td>
            <td style = "text-align:center">
              1,4<br>
              1,5<br>
              1,7<br>
              1,8<br>
              2,2
            </td>
            <td style = "text-align:center">
              1,8<br>
              1,9<br>
              2,1<br>
              2,2<br>
              2,6
            </td>
        </tr>
        <tr>
            <td>Bloco cerâmico vazado (Furo horizontal - ABNT NBR 15270-1)</td>
            <td style = "text-align:center">
              9<br>
              1,5<br>
              14<br>
              19
            </td>
            <td style = "text-align:center">
              0,7<br>
              0,9<br>
              1,1<br>
              1,4
            </td>
            <td style = "text-align:center">
              1,1<br>
              1,3<br>
              1,5<br>
              1,8
            </td>
            <td style = "text-align:center">
              1,6<br>
              1,7<br>
              1,9<br>
              2,3
            </td>
        </tr>
        <tr>
            <td>Bloco de concreto celular autoclavado (Classe C25 - ABNT NBR 13438)</td>
            <td style = "text-align:center">
              7,5<br>
              10<br>
              12,5<br>
              15<br>
              17,5<br>
              20
            </td>
            <td style = "text-align:center">
              0,5<br>
              0,6<br>
              0,8<br>
              0,9<br>
              1,1<br>
              1,2
            </td>
            <td style = "text-align:center">
              0,9<br>
              1,0<br>
              1,2<br>
              1,3<br>
              1,5<br>
              1,6
            </td>
            <td style = "text-align:center">
              1,3<br>
              1,4<br>
              1,6<br>
              1,7<br>
              1,9<br>
              2,0
            </td>
        </tr>
        <tr>
            <td>Bloco de vidro (decorativo, sem resistência ao fogo)</td>
            <td style = "text-align:center">8</td>
            <td style = "text-align:center">0,8</td>
            <td style = "text-align:center">--</td>
            <td style = "text-align:center">--</td>
        </tr>
    </tbody>
</table>
<p>
    <b>NOTA</b>: Na composição de pesos de alvenarias desta Tabela foi considerado o seguinte:
    <ul>
        <li>Argamassa de revestimento vertical e horizontal de cal, cimento e areia com 1 cm de espessura e peso específico de 19 kN/m³;</li>
        <li>Revestimento com peso específico médio de 19 kN/m³;</li>
        <li>Peso equivalente de uma peça para cada dois blocos interiores;</li>
        <li>Sem preenchimento de vazios (com graute etc.).</li>
    </ul>
</p>
<p align = "justify"><b>Tabela 3.</b> [NOME A COLOCAR] </p>
<br>


<p id="tab=4"></p>
<table border="1">
    <thead>
        <tr>
            <th>Material</th>
            <th>Peso na superfície inclinada (kN/m²)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Telha cerâmica em geral (exceto tipo germânica e colonial)</td>
            <td style = "text-align:center">0,45</td>
        </tr>
        <tr>
            <td>Telha cerâmica tipo germânica ou colonial</td>
            <td style = "text-align:center">0,60</td>
        </tr>
        <tr>
            <td>Telha de fibrocimento ondulada com espessura 4 mm</td>
            <td style = "text-align:center">0,14</td>
        </tr>
        <tr>
            <td>Telha de fibrocimento ondulada com espessura 5 mm</td>
            <td style = "text-align:center">0,16</td>
        </tr>
        <tr>
            <td>Telha de fibrocimento ondulada com espessura 6 mm</td>
            <td style = "text-align:center">0,18</td>
        </tr>
        <tr>
            <td>Telha de fibrocimento ondulada com espessura 8 mm</td>
            <td style = "text-align:center">0,24</td>
        </tr>
        <tr>
            <td>Telha de fibrocimento modulada com espessura 8 mm</td>
            <td style = "text-align:center">0,26</td>
        </tr>
        <tr>
            <td>Telha de fibrocimento tipo canalete com espessura 8 mm</td>
            <td style = "text-align:center">0,25</td>
        </tr>
        <tr>
            <td>Telha de alumínio com espessura 0,6 mm</td>
            <td style = "text-align:center">0,025</td>
        </tr>
        <tr>
            <td>Telha de alumínio com espessura 0,8 mm</td>
            <td style = "text-align:center">0,035</td>
        </tr>
        <tr>
            <td>Telha plástica em geral (exceto tipo colonial)</td>
            <td style = "text-align:center">0,05</td>
        </tr>
        <tr>
            <td>Telha plástica tipo colonial</td>
            <td style = "text-align:center">0,15</td>
        </tr>
        <tr>
            <td>Telha de aço ondulada ou trapezoidal com espessura 0,5 mm</td>
            <td style = "text-align:center">0,06</td>
        </tr>
        <tr>
            <td>Telha de aço ondulada ou trapezoidal com espessura 0,8 mm</td>
            <td style = "text-align:center">0,10</td>
        </tr>
        <tr>
            <td>Telha de aço ondulada ou trapezoidal com espessura 1,25 mm</td>
            <td style = "text-align:center">0,14</td>
        </tr>
        <tr>
            <td>Telha de vidro</td>
            <td style = "text-align:center">0,45</td>
        </tr>
    </tbody>
</table>
<p align = "justify"><b>Tabela 4.</b> [NOME A COLOCAR] </p>
<br>



<p id="tab=5"></p>
<table border="1">
    <thead>
        <tr>
            <th>Material</th>
            <th>Espessura (cm)</th>
            <th>Peso (kN/m²)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Impermeabilização com manta asfáltica simples (apenas manta com 15% de sobreposição e pintura asfáltica, sem camada de regularização nem proteção mecânica)</td>
            <td style = "text-align:center">
              0,3<br>
              0,4<br>
              0,5
            </td>
            <td style = "text-align:center">
              0,08<br>
              0,10<br>
              0,11
            </td>
        </tr>
        <tr>
            <td>Piso elevado interno com placas de aço, sem revestimento (até 30 cm de altura)</td>
            <td style = "text-align:center">---</td>
            <td style = "text-align:center">0,5</td>
        </tr>
        <tr>
            <td>Piso elevado interno com placas de polipropileno, sem revestimento (até 30 cm de altura)</td>
            <td style = "text-align:center">---</td>
            <td style = "text-align:center">0,15</td>
        </tr>
        <tr>
            <td>Revestimentos de pisos de edifícios residenciais e comerciais (γ<sub>ap-m</sub> = 20 kN/m³)</td>
            <td style = "text-align:center">
              5<br>
              7
            </td>
            <td style = "text-align:center">
              1,0<br>
              1,4
            </td>
        </tr>
        <tr>
            <td>Revestimentos de pisos de edifícios industriais (γ<sub>ap-m</sub> = 34 kN/m³)</td>
            <td style = "text-align:center">
              5<br>
              7
            </td>
            <td style = "text-align:center">
              1,7<br>
              2,4
            </td>
        </tr>
        <tr>
            <td>Impermeabilizações em coberturas com manta asfáltica e proteção mecânica, sem revestimento (γ<sub>ap-m</sub> = 18 kN/m³)</td>
            <td style = "text-align:center">
              10<br>
              15
            </td>
            <td style = "text-align:center">
              1,8<br>
              2,7
            </td>
        </tr>
    </tbody>
</table>
<p align = "justify"><b>Tabela 5.</b> [NOME A COLOCAR] </p>
<br>
<br>

<p id="fig1"></p>
<center><img src="./assets/images/ECA_determinacao_acoes_estrutura/FIG_c.png" width="90%"></center>
<p align = "justify"><b>Figura 1.</b> Laje Maciça
<br>



<p id="fig2"></p>
<center><img src="./assets/images/ECA_determinacao_acoes_estrutura/FIG_c3.png" width="90%"></center>
<p align = "justify"><b>Figura 2.</b> Laje Nervurada
<br>

<h2>Carga de Alvenaria em lajes</h2>
<br>

<li>Para 𝜆 ≤ 2:
<img src="./assets/images/ECA_determinacao_acoes_estrutura/FIG_c4.png" width="90%">
<br>
<br>

<li>Para 𝜆 > 2:
<img src="./assets/images/ECA_determinacao_acoes_estrutura/FIG_c5.png" width="90%">
<br>


<p id="fig3"></p>
<center><img src="./assets/images/ECA_determinacao_acoes_estrutura/FIG_3.png" width="90%"></center>
<p align = "justify"><b>Figura 3.</b> [A COLOCAR]
<br>

<p id="fig4"></p>
<center><img src="./assets/images/ECA_determinacao_acoes_estrutura/FIG_4.png" width="90%"></center>
<p align = "justify"><b>Figura 4.</b> [A COLOCAR]
<br><br><br>


<h2>Em Vigas</h2>

<br>

<center><img src="./assets/images/ECA_determinacao_acoes_estrutura/FIG_c6.png" width="90%"></center>
<br>


<p id="fig4"></p>
<center><img src="./assets/images/ECA_determinacao_acoes_estrutura/FIG_5.png" width="90%"></center>
<p align = "justify"><b>Figura 5.</b> [A COLOCAR]
<br>


<p>-----------------------------------------------------------------------------------------------------------------------------------------------------</p>

<h1>Carga de Vento em Edifícos</h1>

<p id="fig1"></p>
<center><img src="./assets/images/ECA_carga_d_vento_em_edificio/FIG_1.png" width="90%"></center>
<p align = "justify"><b>Figura 1.</b> [A COLOCAR]
<br><br>

<p align = "justify">
  𝑉<sub>𝑘</sub>  = 𝑉<sub>0</sub> ⋅ 𝑆<sub>1</sub> ⋅ 𝑆<sub>2</sub> ⋅ 𝑆<sub>3</sub>
  <br><br>
  𝑉<sub>0</sub> – Velocidade básica;
  <br><br>
  𝑆<sub>1</sub> – Fator topográfico;
  <br><br>
  𝑆<sub>2</sub> – Fator de rugosidade do terreno (dimensões e altura da edificação);
  <br><br>
  𝑆<sub>3</sub> – Fator estatístico.
</p>
<br>

<p id="fig2"></p>
<center><img src="./assets/images/ECA_carga_d_vento_em_edificio/FIG_2.jpg" width="90%"></center>
<p align = "justify"><b>Figura 2.</b> [A COLOCAR]
<br><br><br>


<p id="tab1"></p>
<center><img src="./assets/images/ECA_carga_d_vento_em_edificio/TAB_1.png" width="90%"></center>
<p align = "justify"><b>Tabela 1.</b> [A COLOCAR]
<br>



<p id="tab=1"></p>
<table border="1" style="border-collapse: collapse; text-align: left; background-color: #FFFFCC;">
        <tr>
          <th colspan = "2"><b>QUADRO 4: Classes de relevo do terreno</b></th>
        </tr>
        <tr>
            <td>S<sub>1</sub></td>
            <td>TIPO DE RELEVO DO TERRENO</td>
        </tr>
    <tbody>
        <tr>
            <td>1,0</td>
            <td>Terreno Plano ou fracamente acidentado</td>
        </tr>
        <tr>
            <td>VARIÁVEL</td>
            <td>Taludes e Morros</td>
        </tr>
        <tr>
            <td>0,9</td>
            <td>Vales Profundos e protegidos de ventos de qualquer direção.</td>
        </tr>
    </tbody>
</table>
<p align = "justify"><b>Tabela 1.</b> [NOME A COLOCAR] </p>
<br>

<p id="fig3"></p>
<center><img src="./assets/images/ECA_carga_d_vento_em_edificio/FIG_3.jpg" width="90%"></center>
<p align = "justify"><b>Figura 3.</b> [A COLOCAR]
<br><br><br>


<p id="fig4"></p>
<center><img src="./assets/images/ECA_carga_d_vento_em_edificio/FIG_4.jpg" width="90%"></center>
<p align = "justify"><b>Figura 4.</b> [A COLOCAR]
<br><br><br>




<p id="tab=2"></p>
<table border="1" style="border-collapse: collapse; text-align: left; background-color: #FFFFCC;">
    <tr><th colspan = "2"><b>QUADRO 5: Categorias de Rugosidade do terreno</b></th></tr>
        <tr >
            <th>CATEGORIA</th>
            <th>TIPO DE SUPERFÍCIE DO TERRENO</th>
        </tr>
        <tr>
            <td>I</td>
            <td>Superfícies Lisas de grandes dimensões, com mais de 5 km de extensão, medida na direção e sentido do vento incidente.</td>
        </tr>
        <tr>
            <td>II</td>
            <td>Terrenos abertos em nível ou aproximadamente em nível, com poucos obstáculos isolados, tais como árvores e edificações baixas. Obstáculos com altura média abaixo de 1,0 metros.</td>
        </tr>
        <tr>
            <td>III</td>
            <td>Terrenos planos ou ondulados com obstáculos, tais como sebes e muros, poucos quebra-ventos. Obstáculos com altura média de 3,0 metros.</td>
        </tr>
        <tr>
            <td>IV</td>
            <td>Terrenos cobertos por obstáculos numerosos e pouco espaçados, em zona florestal, industrial ou urbanizada. Altura média dos obstáculos de 10 metros.</td>
        </tr>
        <tr>
            <td>V</td>
            <td>Terrenos cobertos por obstáculos numerosos, grandes, altos e pouco espaçados. Obstáculos com altura média de 25 metros ou mais.</td>
        </tr>
</table>
<p align = "justify"><b>Tabela 2.</b> [NOME A COLOCAR] </p>
<br><br>




<p id="tab=3"></p>
<table border="1" style="border-collapse: collapse; text-align: left; background-color: #FFFFCC;">
    <caption><b>QUADRO 8: Classes de Edifícios em função de suas dimensões.</b></caption>
    <thead>
        <tr>
            <th>CLASSE</th>
            <th>DIMENSÕES DO EDIFÍCIO</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>A</td>
            <td>
                Todas as unidades de vedação, seus elementos de fixação e peças individuais de estruturas sem vedação.<br>
                Toda edificação na qual a maior dimensão horizontal ou vertical seja inferior a <b>20 metros</b>.
            </td>
        </tr>
        <tr>
            <td>B</td>
            <td>
                Toda edificação ou parte de edificação para a qual a maior dimensão horizontal ou vertical da superfície frontal esteja entre <b>20 e 50 metros</b>.
            </td>
        </tr>
        <tr>
            <td>C</td>
            <td>
                Toda edificação ou parte de edificação para a qual a maior dimensão horizontal ou vertical da superfície frontal exceda <b>50 metros</b>.
            </td>
        </tr>
    </tbody>
</table>
<p align = "justify"><b>Tabela 3.</b> [NOME A COLOCAR] </p>
<br><br>

<img src="./assets/images/ECA_carga_d_vento_em_edificio/FIG_c1.png" width="90%">
<br><br><br>



<p id="tab=4"></p>
<table border="1" style="border-collapse: collapse; text-align: left; background-color: #FFFFCC;">
    <caption><b>QUADRO 8: Determinação do Fator Estatístico S<sub>3</sub> conforme os Grupos de ocupação.</b></caption>
    <thead>
        <tr>
            <th>GRUPO</th>
            <th>DESCRIÇÃO</th>
            <th>FATOR S<sub>3</sub></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>
                Edificações cuja ruína total ou parcial pode afetar a segurança ou possibilidade de socorro a pessoas após uma tempestade destrutiva (hospitais, quartéis de bombeiros e de forças de segurança, centrais de comunicação, etc.)
            </td>
            <td>1,10</td>
        </tr>
        <tr>
            <td>2</td>
            <td>
                Edificações para hotéis e residências. Edificações para comércio e indústria com alto fator de ocupação.
            </td>
            <td>1,00</td>
        </tr>
        <tr>
            <td>3</td>
            <td>
                Edificações e instalações industriais com baixo fator de ocupação (depósitos, silos, construções rurais, etc.)
            </td>
            <td>0,95</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Vedações (telhas, vidros, painéis de vedação, etc.)</td>
            <td>0,88</td>
        </tr>
        <tr>
            <td>5</td>
            <td>
                Edificações temporárias. Estruturas dos grupos 1 a 3 durante a construção.
            </td>
            <td>0,83</td>
        </tr>
    </tbody>
</table>
<p align = "justify"><b>Tabela 4.</b> [NOME A COLOCAR] </p>
<br><br>


<h2>Força do Vento</h2>

<p align = "justify">
  𝑞 = 0,613 ∙ 𝑉<sub>𝑘</sub><sup>2</sup> 
  <br><br>    
  𝐹<sub>𝑎</sub> = 𝐶𝑎 ∙ 𝑞 ∙ 𝐴<sub>𝑒</sub>
</p>
<br>


<p id="fig5"></p>
<center><img src="./assets/images/ECA_carga_d_vento_em_edificio/FIG_5.png" width="90%"></center>
<p align = "justify"><b>Figura 5.</b> [A COLOCAR]
<br><br><br>


<p id="fig6"></p>
<center><img src="./assets/images/ECA_carga_d_vento_em_edificio/FIG_6.jpg" width="90%"></center>
<p align = "justify"><b>Figura 6.</b> [A COLOCAR]
<br><br><br>


<img src="./assets/images/ECA_carga_d_vento_em_edificio/FIG_c2.png" width="90%">
<br><br>
<br><br>

<p id="fig7"></p>
<center><img src="./assets/images/ECA_carga_d_vento_em_edificio/FIG_7.png" width="90%"></center>
<p align = "justify"><b>Figura 7.</b> [A COLOCAR]
<br><br><br>


<h3>Conversão de Desaprumo em Força Horizontal no Pavimento</h3>

<br>

<p id="fig8"></p>
<center><img src="./assets/images/ECA_carga_d_vento_em_edificio/FIG_8.png" width="90%"></center>
<p align = "justify"><b>Figura 8.</b> [A COLOCAR]
<br><br><br>

<p>-----------------------------------------------------------------------------------------------------------------------------------------------------------</p>


<h1>Verificaçoes preliminares do Sistema Estrutural</h1><br>

<p align = "justify">
  Antes de começar o detalhamento de uma estrutura é essencial que o projetista já tenha uma planta de fôrma pré-executiva para que na fase final do projeto não sejam necessárias grandes modificações.
  <br><br>
  <li>Verificações de cisalhamento;<br>
  <li>Verificações de flecha;<br>
  <li>Verificações de estabilidade.
</p>
<br>

<h2>Verificação de cisalhamento para lajes sem armaduras</h2>

<p align = "justify">
  𝑉<sub>𝑠𝑑</sub> ≤ 𝑉<sub>𝑅𝑑1</sub><br>
  𝑉<sub>𝑅𝑑1</sub> = [𝜏<sub>𝑅𝑑</sub> ⋅ 𝑘 ⋅ (1,2 + 40 ⋅ 𝜌<sub>1</sub>) + 0,15 ⋅ 𝜎<sub>𝑐𝑝</sub>] ⋅ 𝑏<sub>𝑤</sub> ⋅ 𝑑
</p>
<br>

<h2>Verificação de Flexa</h2>


<table border = "0">
  <tr>
    <td>𝐼<sub>𝑒𝑞</sub> = 𝐼<sub>𝑐</sub> <br></td>
    <td>𝑀<sub>𝑎</sub> ≤ 𝑀<sub>𝑟</sub><br></td>
    <td rowspan = "2">𝑎<sub>(𝑡=∞)</sub> = 𝑎<sub>(𝑡=0)</sub> . (1 + 𝛼<sub>𝑓</sub>)</td>
  </tr>
  <tr>
    <td>𝐼<sub>𝑒𝑞</sub> = 0,30 ⋅ 𝐼<sub>𝑐</sub></td>
    <td>𝑀<sub>𝑎</sub> > 𝑀<sub>𝑟</sub></td>
  </tr>
</table>
<br>

<h2>Verificação de Estabilidade Global</h2>
<br>
<br>

<p id="fig1"></p>
<center><img src="./assets/images/ECA_verificacoes_preliminares_sistema_aula20/FIG_1.png" width="90%"></center>
<p align = "justify"><b>Figura 1.</b> [A COLOCAR]
<br><br><br>

<p id="fig2"></p>
<center><img src="./assets/images/ECA_verificacoes_preliminares_sistema_aula20/FIG_2.png" width="90%"></center>
<p align = "justify"><b>Figura 2.</b> Coluna de Euller
<br><br><br>

<p align  = "justify">
<b>
  Parâmetro alfa: O termômetro da análise de 2º ordem
</b>
</p>

<br><br>


<p id="fig3"></p>
<center><img src="./assets/images/ECA_verificacoes_preliminares_sistema_aula20/FIG_3.png" width="90%"></center>
<p align = "justify"><b>Figura 3.</b> [colocar]
<br><br><br>

<center><img src="./assets/images/ECA_verificacoes_preliminares_sistema_aula20/FIG_c1.png" width="90%"></center>
<br><br><br>

<p align = "justify">
  O coeficiente 𝛾<sub>𝑍</sub>  : Quantifica os esforços de 2º ordem que ocorrem na estrutura
</p>



<center><img src="./assets/images/ECA_verificacoes_preliminares_sistema_aula20/FIG_c2.png" width="90%"></center>
<br><br><br>

<h2>Limitações de Deslocamento</h2>


<p id="fig4"></p>
<center><img src="./assets/images/ECA_verificacoes_preliminares_sistema_aula20/FIG_4.png" width="90%"></center>
<p align = "justify"><b>Figura 4.</b> [colocar]
<br><br><br>

<p id="fig5"></p>
<center><img src="./assets/images/ECA_verificacoes_preliminares_sistema_aula20/FIG_5.png" width="90%"></center>
<p align = "justify"><b>Figura 5.</b> [colocar]
<br><br><br>


<p>--------------------ECA2 - AULA 9 CONSIDERAÇÃO SOBRE O PROJETO DE VIGAS DE CONCRETO ----------------------------------------------------------------------------------------------------------------------------------------</p>

<h1>Revisão sobre o cálculo da área de aço das seções das vigas</h1>


<h2>Introdução</h2>

<p align = "justify">
  Vigas são elementos lineares, em que uma das suas dimensões, isto é, o comprimento (representado pelo vão 𝑙), é muito maior que as outras duas, sendo elas a altura ℎ e largura 𝑏<sub>𝑤</sub>.
  <br>
  São chamadas de vigas chatas quando apresentam ℎ ≤ 𝑏<sub>𝑤</sub>. Normalmente, as vigas são geralmente encontradas apresentando proporções como 2 ≤ ℎ / 𝑏<sub>𝑤</sub> ≤ 5.
</p>
<br>


<p id="fig1"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_1.png" width="90%"></center>
<p align = "justify"><b>Figura 1.</b> Dimensões das vigas  <a href="#ref6">[7]</a>
<br><br><br>

<p align = "justify">
  A NBR 6118 (2014) <a href="#ref1">[1]</a> estabelece que, baseando-se na relação 𝑙/ℎ, nota-se que a relação 𝑙/ℎ≥3 referem-se a vigas isostáticas; a relação 𝑙/ℎ≥2 refere-se a vigas contínuas; e a relação 𝑙/ℎ < 2 refere-se a vigas-parede.<br><br>
  Sendo:<br>
  𝑙 – Comprimento do vão teórico, (ou o dobro do valor do vão no caso do balanço);<br>
  ℎ –  Altura total da viga.<br>
  Conforme o item 13.2.2 da NBR 6118 (2014) <a href="#ref1">[1]</a>, vigas não podem apresentar largura menor que 12 cm, e vigas-parede não podem apresentar largura menor que 15 cm.
  Segundo i item 14.6.2.4 da NBR 6118 (2014) <a href="#ref1">[1]</a>, é estabelecido que para os vãos efetivos das vigas, faz-se:
  <br><br>

  <p id="Eq1"></p>
  <table>
    <tr>
      <td>
        𝑙<sub>𝑒𝑓</sub> = 𝑙<sub>𝑜</sub> + 𝑙<sub>𝑎1</sub> + 𝑙<sub>𝑎2</sub> 
      </td>
      <th> 
        Equação 1
      </th>
    </tr>
  </table>
  <br>
  Com 𝑎<sub>1</sub> igual ao menor valor entre (𝑡<sub>1</sub>/2 e 0,3ℎ) e 𝑎<sub>2</sub> igual ao menor valor entre (𝑡<sub>2</sub>/2 e 0,3ℎ). Conforme a Figura. <a href="#fig2">2</a>, expressa a seguir.
</p>

<br>
<p id="fig2"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_2.png" width="90%"></center>
<p align = "justify"><b>Figura 2.</b> Vão efetivo   <a href="#ref1">[1]</a>
<br><br><br>

<p align = "justify">
  As vigas podem apresentar diversas configurações quanto sua forma, sendo as mais comuns:<br>
  <li>Retangular (Figura. <a href="#fig3">3</a>);<br>
  <li>Seção T (Figura. <a href="#fig4">4</a>)<br>
  <li>Viga caixão (Figura. <a href="#fig5">5</a>)<br>
  <li>Duplo T (Figura. <a href="#fig6">6</a>);
</p>
<br><br><br><br>

<p id="fig3"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_3.png" width="90%"></center>
<p align = "justify"><b>Figura 3.</b> Seção retangular <a href="#ref7">[8]</a>
<br><br><br>

<p id="fig4"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_4.png" width="90%"></center>
<p align = "justify"><b>Figura 4.</b> Seção T <a href="#ref8">[9]</a>
<br><br><br>

<p id="fig5"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_5.png" width="90%"></center>
<p align = "justify"><b>Figura 5.</b> Seção caixão  <a href="#ref9">[10]</a>
<br><br><br>

<p id="fig6"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_6.png" width="90%"></center>
<p align = "justify"><b>Figura 6.</b> Seção caixão  <a href="#ref10">[11]</a>
<br><br><br>

<p align = "justify">
  Podem ser classificadas também quanto sua fabricação, sendo elas:<br><br>
  <li>Moldada in loco (Figura. <a href="#fig7">7</a>); <br>
  <li>Pré-moldada (Figura. <a href="#fig8">8</a>).
</p>
<br><br><br>

<p id="fig7"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_7.png" width="90%"></center>
<p align = "justify"><b>Figura 7.</b> Moldada in loco <a href="#ref12">[12]</a>
<br><br><br>

<p id="fig8"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_8.png" width="90%"></center>
<p align = "justify"><b>Figura 8.</b> Pré-moldada <a href="#ref13">[13]</a>
<br><br><br>


<h2>Modos de Ruptura</h2>

<p align = "justify">
  Conforme o item 14.4.1.1, vigas são elementos lineares em que a flexão é preponderante. Nesse sentido, são expostas, na Figura. <a href="#fig9">9</a>, uma série de modos de ruptura em que uma viga pode ser submetida:
</p>
<br><br><br>

<p id="fig9"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_9.png" width="90%"></center>
<p align = "justify"><b>Figura 9.</b> Variedades de situações de modo de ruptura de uma viga (SUSSEKIND, 1981). <a href="#ref6">[6]</a>
<br><br><br>

<p align = "justify">
  Para melhores esclarecimentos, conforme Dumet (2008) <a href="#ref5">[5]</a>, pode-se tomar uma série de medidas preventivas essenciais para o dimensionamento baseado no E.L.U:<br>
  São elas:<br>
  Flexão – compressão (A): Categoriza-se no tipo frágil/dúctil, caracterizada pelo avanço da fissura de flexão, fazendo a redução do banzo comprimido até o esmagamento do banzo comprimido do concreto. Conforme Figura. <a href="#fig10">10</a> 
</p>
<br><br><br>

<p id="fig10"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_10.png" width="90%"></center>
<p align = "justify"><b>Figura 10.</b> Modo de ruptura flexão-compressão (A) (DUMET, 2008). <a href="#ref5">[5]</a>
<br><br><br>

<p align = "justify">
  Cortante – Tração (B): Categoriza-se no tipo dúctil, caracterizada pela ruptura da armadura de cisalhamento por tração. Conforme Figura. <a href="#fig11">11</a>.
</p>
<br><br><br>


<p id="fig11"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_11.png" width="90%"></center>
<p align = "justify"><b>Figura 11.</b> Modo de ruptura cortante-tração (B) (DUMET, 2008). <a href="#ref5">[5]</a>
<br><br><br>


<p align = "justify">
  Cortante – Flexão (C): Categoriza-se no tipo frágil/dúctil, caracterizada pela interação momento/cortante, juntamente com o avanço da fissura diagonal cortando o banzo comprimido do elemento. Conforme Figura. <a href="#fig12">12</a>.
</p>
<br><br><br>


<p id="fig12"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_12.png" width="90%"></center>
<p align = "justify"><b>Figura 12.</b> Modo de ruptura cortante-flexão (C) <a href="#ref5">[5]</a>
<br><br><br>


<p align = "justify">
  Rompimento da ligação Aço – Concreto (D): Categoriza-se no tipo frágil, caracterizada pelo fendilhamento do concreto, e o esgotamento da capacidade aderente do elemento estrutural. Conforme Figura. <a href="#fig13">13</a>.
</p>
<br><br><br>


<p id="fig13"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_13.png" width="90%"></center>
<p align = "justify"><b>Figura 13.</b> Modo de ruptura rompimento da ligação aço-concreto (D) <a href="#ref5">[5]</a>
<br><br><br>

<p align = "justify">
  Cortante – Compressão (E): Categoriza-se no tipo frágil, caracterizada pelo esmagamento da biela comprimida na região junto ao apoio. Conforme Figura. <a href="#fig14">14</a>.
</p>
<br><br><br>


<p id="fig14"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_14.png" width="90%"></center>
<p align = "justify"><b>Figura 14.</b> Modo de ruptura cortante-compressão (E)  <a href="#ref5">[5]</a>
<br><br><br>


<h2>Flexão Simples na Ruina: Hipóteses</h2>

<p align = "justify">
  Conforme Pinheiro (2007) <a href="#ref4">[4]</a>, fazendo uma análise mais simples, pode-se tomar que os efeitos do esforço cortante são analisados de forma separada. Nessas condições, o foco volta-se à flexão pura, isto é, somente o momento fletor.
  <br>
  Visto que, nessas condições, a tensão no concreto pode ser considerada nula, já que a resistência do concreto à tração é desprezada.
  <br>
  Pautada na Equação. <a href="#Eq2">2</a>, torna-se possível analisar a validade da hipótese de manutenção da forma da planta da seção transversal, visto que os elementos estruturais estão submetidos a solicitações normais. Dessa forma:
  <br>
  <p id="Eq2"></p>
  <table>
    <tr>
      <td>
        𝑙<sub>0</sub>/𝑑 > 2      
      </td>
      <th> 
        Equação 2
      </th>
    </tr>
  </table>
  <br>
  Onde:
  <br><br>
  𝑙<sub>0</sub> - Distância entre as seções de momento fletor nulo;<br>
  𝑑 – Altura útil da seção.
  <br>
  Fazendo a conferência e verificando a validade da hipótese, as deformações específicas longitudinais em cada ponto da seção transversal são proporcionais à distância até a linha neutra do elemento estrutural.
</p>
<br><br>

<h2>Equações de Equilíbrio</h2>

<p align = "justify">
  Conforme a Figura. <a href="#fig15">15</a>, é possível extrair as seguintes análises:
</p>
<br><br><br>

<p id="fig15"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_15.png" width="90%"></center>
<p align = "justify"><b>Figura 15.</b> [COLOCAR] <a href="#ref5">[5]</a></p>
<br><br><br>


<p align = "justify">
  As equações de equilíbrio de forças e momentos são:<br>
  <br>
  <p id="Eq3"></p>
  <table>
    <tr>
      <td>
        𝑅<sub>𝑐</sub> + 𝑅′<sub>𝑠</sub> − 𝑅<sub>𝑠</sub> = 0       
      </td>
      <th> 
        Equação 3
      </th>
    </tr>
    <tr>
      <td>
        𝑀<sub>𝑑</sub> = 𝛾<sub>𝑓</sub> ∙ 𝑀<sub>𝑘</sub> = 𝑅<sub>𝑐</sub> (𝑑 − 𝑦/2) + 𝑅′<sub>𝑠</sub> (𝑑 − 𝑑′)      
      </td>
      <th> 
        Equação 4
      </th>
    </tr>
  </table>
  <br>
  Visto que, as resultantes no concreto 𝑅<sub>𝑐</sub> e nas armaduras (𝑅<sub>𝑠</sub> e 𝑅′<sub>𝑠</sub>), são concebidas através das expressões:
  <br>


  <p id="Eq5"></p>
  <table>
  <tr>
      <td>
        𝑅<sub>𝑐</sub> = 𝑏 ∙ 𝑦 ∙ 𝜎<sub>𝑐𝑑</sub> = 𝑏 ∙ 0,8𝑥 ∙ 0,85 ∙ 𝑓<sub>𝑐𝑑</sub> = 0,68 ∙ 𝑏 ∙ 𝑑 ∙ 𝛽<sub>𝑥</sub> ∙ 𝑓<sub>𝑐𝑑</sub>   
      </td>
      <th> 
        Equação 5
      </th>
    </tr>
  </table>
  <br>

  <p id="Eq6"></p>
  <table>
  <tr>
      <td>
       𝑅<sub>𝑠</sub> = 𝐴<sub>𝑠</sub> ∙ 𝜎<sub>𝑠</sub> 
      </td>
      <th> 
        Equação 6
      </th>
    </tr>
  </table>
    <br>
  
  <p id="Eq7"></p>
  <table>
  <tr>
      <td>
       𝑅′<sub>𝑠</sub> = 𝐴′<sub>𝑠</sub> ∙ 𝜎′<sub>𝑠</sub>
      </td>
      <th> 
        Equação 7
      </th>
    </tr>
  </table>
  <br>
  Tem-se, para diagrama retangular de tensões no concreto:
  <br><br>

  <p id="Eq8"></p>
  <table>
  <tr>
      <td>
       𝑦 = 0,8𝑥 → 𝑑− 𝑦/2 = 𝑑(1−0,8𝑥/2𝑑) = 𝑑(1− 0,4 ∙ 𝛽<sub>𝑥</sub>)      
      </td>
      <th> 
        Equação 8
      </th>
    </tr>
  </table>
  <br>
  Com as análises supramencionadas, tem-se, para armadura simples (𝐴′<sub>𝑠</sub> = 0), as seguintes equações:
  <br><br>

  <p id="Eq9"></p>
  <table>
  <tr>
      <td>
       0,68 ∙ 𝑏 ∙ 𝑑 ∙ 𝛽<sub>𝑥</sub>𝑓<sub>𝑐𝑑</sub> − 𝐴<sub>𝑠</sub> ∙ 𝜎<sub>𝑠</sub> = 0      
      </td>
      <th> 
        Equação 9
      </th>
    </tr>
  </table>
  <br>

  <p id="Eq10"></p>
  <table>
  <tr>
      <td>
       𝑀<sub>𝑑</sub> = 0,68 ∙ 𝑏 ∙ 𝑑<sup>2</sup> ∙ 𝛽<sub>𝑥</sub> ∙ 𝑓<sub>𝑐𝑑</sub> (1 − 0,4 ∙ 𝛽<sub>𝑥</sub>)       
      </td>
      <th> 
        Equação 10
      </th>
    </tr>
  </table>
  <br>
  E para armadura dupla, tem-se, respectivamente:
  <br><br>

  <p id="Eq11"></p>
  <table>
  <tr>
      <td>
       0,68 ∙ 𝑏 ∙ 𝑑 ∙ 𝛽<sub>𝑥</sub>𝑓<sub>𝑐𝑑</sub> + 𝐴′<sub>𝑠</sub> ∙ 𝜎′<sub>𝑠</sub> - 𝐴<sub>𝑠</sub> ∙ 𝜎<sub>𝑠</sub> = 0
      </td>
      <th> 
        Equação 11
      </th>
    </tr>
  </table>
  <br>

  <p id="Eq12"></p>
  <table>
  <tr>
      <td>
      𝑀<sub>𝑑</sub> = 0,68 ∙ 𝑏 ∙ 𝑑<sup>2</sup> ∙ 𝛽<sub>𝑥</sub> ∙ 𝑓<sub>𝑐𝑑</sub> (1 − 0,4 ∙ 𝛽<sub>𝑥</sub>) - 𝐴′<sub>𝑠</sub> ∙ 𝜎′<sub>𝑠</sub>(𝑑 − 𝑑′)
      </td>
      <th> 
        Equação 12
      </th>
    </tr>
  </table>
</p>
<br>


<h1>Aproximações Permitidas para Cálculo dos Esforços</h1>
<br>
<h2>Aproximações Permitidas para Cálculo dos Esforços de Edifícios</h2>

<p align = "justify">
  Conforme o item 14.6.6.1 da ABNT NBR 6118 (2014) <a href="#ref1">[1]</a>, o modelo clássico de viga contínua, simplesmente apoiada nos pilares, pode ser utilizado para o estudo de cargas verticais. Ao considerar o modelo clássico de viga contínua, é necessário que se faça uso das correções adicionais, sendo:
  <br><br>
  a) Não podem ser considerados momentos positivos menores que os que se obteriam se houvesse engastamento perfeito da viga nos apoios internos;
</p>
<br>

<p id="fig16"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_16.png" width="90%"></center>
<p align = "justify"><b>Figura 16.</b> [COLOCAR]  <a href="#ref5">[colocar referencia]</a>
<br><br><br>

<p align = "justify">
  b) Quando a viga for solidária com o pilar intermediário e a largura do apoio, medida na direção do eixo da viga, for maior que a quarta parte da altura do pilar, não pode ser considerado o momento negativo de valor absoluto menor do que o engastamento perfeito nesse apoio;
</p>
<br><br>

<p id="fig17"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_17.png" width="90%"></center>
<p align = "justify"><b>Figura 17.</b> [COLOCAR]  <a href="#ref5">[colocar referencia]</a>
<br><br><br>

<p align = "justify">
  c) Quando não for realizado o cálculo exato da influência da solidariedade dos pilares com a viga, deve ser considerado, nos apoios extremos, momento fletor igual ao momento de engastamento perfeito multiplicado pelos coeficientes estabelecidos conforme as expressões a seguir:
</p>
<br><br>

<p id="fig18"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_18.png" width="90%"></center>
<p align = "justify"><b>Figura 18.</b> [COLOCAR]  <a href="#ref5">[colocar referencia]</a>
<br><br><br>

<p align = "justify">
  Na viga, usa-se:<br>
  <br>

  <p id="Eq13"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula9/FIG_c1.png" width="90%">
      </td>
      <th> 
        Equação 13
      </th>
    </tr>
  </table>
  <br>
  <li>No tramo inferior do pilar:

  <p id="Eq14"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula9/FIG_c2.png" width="90%">
      </td>
      <th> 
        Equação 14
      </th>
    </tr>
  </table>
  <br>

  <li>No tramo superior do pilar:
   <p id="Eq15"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula9/FIG_c3.png" width="90%">
      </td>
      <th> 
        Equação 15
      </th>
    </tr>
  </table>
  <br>
  Onde
  <br><br>
  𝑀<sub>𝑒𝑛𝑔</sub> – Momento fletor de ligação entre a viga e o pilar;<br>
  𝑟<sub>𝑖𝑛𝑓</sub> – Rigidez do lance inferior do pilar;<br>
  𝑟<sub>𝑠𝑢𝑝</sub> – Rigidez do lance superior do pilar;<br>
  𝑟<sub>𝑣𝑖𝑔</sub> – Rigidez do tramo extremo da viga. <br>
  𝑟<sub>𝑖</sub> = 𝐼<sub>𝑖</sub> / 𝑙<sub>𝑖</sub>  – Corresponde à rigidez do elemento 𝑖 no nó considerado e pode ser calculado através da relação entre o momento de inercia 𝐼<sub>𝑖</sub> e seu comprimento de flambagem do pilar 𝑙<sub>𝑖</sub>.
  <br><br>
  A Figura. <a href="#fig19">19</a> demonstra a disposição dos momentos fletores na base e no topo de um pilar:
</p>
<br>

<p id="fig19"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_19.png" width="90%"></center>
<p align = "justify"><b>Figura 19.</b> momentos fletores nos pilares provenientes da ligação com as vigas   <a href="#ref13">[13]</a>
<br><br><br>

<p align = "justify">
  A Figura. <a href="#fig20">20</a> dispõe-se para demonstrar que, no caso da rigidez da viga, 𝑙<sub>𝑖</sub> corresponde ao vão efetivo entre o apoio extremo e o apoio intermediário. Visto que, em pilares, 𝑙<sub>𝑖</sub> é adotado como metade do comprimento de flambagem do lance do piar.
</p>
<br>

<p id="fig20"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_20.png" width="90%"></center>
<p align = "justify"><b>Figura 20.</b> aproximação em apoios extremos <a href="#ref1">[1]</a>
<br><br><br>

<p align = "justify">
  Conforme o item 14.6.6.1 da NBR 6118:2014 <a href="#ref1">[1]</a>, é possível fazer um melhoramento do modelo de viga contínua, fazendo a consideração da solidariedade dos pilares com a viga, com a introdução da rigidez à flexão dos pilares extremos e intermediários. Pautando-se na análise cuidadosa e minuciosa dos resultados obtidos. 
  <br>
  Bastos (2015) <a href="#ref2">[2]</a>, declara que, na intenção de introduzir a rigidez à flexão dos pilares extremos, nota-se que o apoio extremo fica vinculado à viga em função de um engastamento elástico, isto é, uma mola. Sendo então avaliada conforme a Equação. <a href="#Eq16">16</a>, expressa a seguir:
  <br>

  <p id="Eq16"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula9/FIG_c4.png" width="90%">
      </td>
      <th> 
        Equação 16
      </th>
    </tr>
  </table>
  <br>
  Onde:
  <br>
  𝐾<sub>(𝑝.𝑠𝑢𝑝)</sub> - Rigidez do lance superior do pilar extremo;<br>
  𝐾<sub>(𝑝,𝑖𝑛𝑓)</sub> - Rigidez do lance inferior do pilar extremo;<br>
  <br>
  <br>
  Estes, sendo:
  
  <p id="Eq17"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula9/FIG_c5.png" width="90%">
      </td>
      <th> 
        Equação 17
      </th>
    </tr>
  </table>
  <br>

  <p id="Eq18"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula9/FIG_c6.png" width="90%">
      </td>
      <th> 
        Equação 18
      </th>
    </tr>
  </table>
  <br>

  Visto que:
  <br>
  𝐸=𝐸_𝑐𝑠 - Modulo de elasticidade secante do concreto;
  𝐼 – Momento de inércia do lance do pilar;
  𝑙_𝑒 - Comprimento de flambagem do lance inferior ou superior do pilar.
  <br>
  Nota-se há o incremento do coeficiente 4 nas Equações. <a href="#Eq17">17</a> e <a href="#Eq18">18</a>, tal incremento é feito devido ao caso de serem barras com vínculos de apoios simples e engastes perfeitos em suas extremidades. Na condição de ambos os vínculos serem apoiados, o valor do incremento muda-se para o coeficiente de valor 3.
  Bastos( 2015) <a href="#ref2">[2]</a>, afirma, ainda, que para condições em que há uma continuidade do pilar nos pavimentos, típicos de pavimentos tipos em edifícios, tem-se que:
  <br>

  <p id="Eq19"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula9/FIG_c7.png" width="90%">
      </td>
      <th> 
        Equação 19
      </th>
    </tr>
  </table>
  <br>

  <p id="Eq20"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula9/FIG_c8.png" width="90%">
      </td>
      <th> 
        Equação 20
      </th>
    </tr>
  </table>
</p>
<br>
<br>


<h1>Armadura de Suspensão em Vigas</h1>

<h2>Armadura de Suspensão</h2>

<p align = "justify">
  Conforme o item 18.3.6 da NBR 6118:2014 <a href="#ref1">[1]</a>, é esclarecido que nas proximidades de cargas concentradas transmitidas à viga por outras vigas ou elementos discretos que nela se apoiam ao longo ou em parte de sua altura, ou fiquem pendurados, deve ser colocada armadura de suspensão.
  <br><br>
  Bastos (2015) <a href="#ref2">[2]</a>, afirma que é necessário fazer a distinção entre os tipos de apoio, sendo apoio direto e apoio indireto. Visto que, no apoio direto, o carregamento é transmitido diretamente para o apoio, por exemplo, um pilar. No apoio indireto, a carga da viga se transfere pelo corpo do elemento estrutural em direção a parte inferior da viga que serve de suporte.
</p>
<br>

<p id="fig21"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_21.png" width="90%"></center>
<p align = "justify"><b>Figura 21.</b> apoios indiretos e diretos  <a href="#ref14">[14]</a></p>
<br><br><br>

<p align = "justify">
  Em uma situação intermediária, Chamberlain (2001) <a href="#ref3">[3]</a>, observa que há a necessidade de suspender apenas parte da reação, uma vez que o restante pode ser transferido para a treliça, através da Figura. <a href="#fig22">22</a>, que simula o elemento estrutural como viga de apoio
</p>
<br>

<p id="fig22"></p>
<center><img src="./assets/images/ECA2_aula9/FIG_22.png" width="90%"></center>
<p align = "justify"><b>Figura 22.</b> [colocar]  <a href="#ref3">[3]</a></p>
<br><br><br>

<p align = "justify">
  Realçando que, a reação de apoio 𝑅<sub>𝑑</sub>, a força de suspensão pode ser estimada como:
  <br><br>
  <p id="Eq21"></p>
  <table>
  <tr>
      <td>
        <center><img src="./assets/images/ECA2_aula9/FIG_c9.png" width="90%"></center>
      </td>
      <th> 
        Equação 21
      </th>
    </tr>
  </table>
  <br>
  Visto que: <br><br>
  ℎ - altura da viga apoiada;<br>
  ℎ<sub>𝑎</sub> - altura da viga de apoio;
  <br>
  <br>
  <br>
  A equação que expressa a armadura de suspensão, baseando-se na força de suspensão 𝑍<sub>𝑑</sub>, é:
  <br><br>

  <p id="Eq22"></p>
  <table>
  <tr>
      <td>
        <center><img src="./assets/images/ECA2_aula9/FIG_c10.png" width="90%"></center>
      </td>
      <th> 
        Equação 22
      </th>
    </tr>
  </table>
  <br><br>

  E que, conforme a Figura. <a href="#fig23">23</a>, a armadura de suspensão, estimada a partir da Equação. <a href="#Eq22">22</a>, pode ser atribuída na zona de suspensão, conforme a seguir:
  <br><br>

  <p id="fig23"></p>
  <center><img src="./assets/images/ECA2_aula9/FIG_23.png" width="90%"></center>
  <p align = "justify"><b>Figura 23.</b> Zona de suspensão <a href="#ref3">[3]</a></p>
  <br><br><br>
</p>
<br><br><br>


<h3>Bibliografia</h3>

<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Referências</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><p align = "center" id = "ref1">[1']</p></td>
            <td><p align = "left">Associação Brasileira de Normas Técnicas ABNT 6118. Projeto de Estruturas de Concreto. Rio de Janeiro, 2014.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref2">[2']</p></td>
            <td><p align = "left">Bastos, P. S. dos S. Vigas de Concreto Armado. Bauru: Departamento de engenharia civil, 2015. Apostila.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref3">[3']</p></td>
            <td><p align = "left">Chamberlain, Z. Exemplo de um projeto completo de edifício de concreto armado. capítulo 3 -  Cálculo de Vigas. 2001.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref4">[4']</p></td>
            <td><p align = "left">Pinheiro, L. M. Projeto de Estruturas de Concreto. Departamento de engenharia de Estruturas. EESC-USP. 2007. Apostila. </p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref5">[5']</p></td>
            <td><p align = "left">Dumet, T. B. Estruturas de Concreto Armado I, Departamento de Construção e Estruturas. EP-UFBA. 2008. Apostila. </p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref6">[6']</p></td>
            <td><p align = "left">SUSSEKIND, 1981 </p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref7">[7']</p></td>
            <td><p align = "left">http://pt.slideshare.net/mackenzista2/aula-4-vigas.
            </p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref7">[8']</p></td>
            <td><p align = "left">http://www.scielo.br/scielo.php?pid=S198341952014000500002&script=sci_arttext&tlng=pt.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref7">[9']</p></td>
            <td><p align = "left">http://www.multcalc.com.br/calculos/calculoviga.html.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref7">[10']</p></td>
            <td><p align = "left">http://admportodemanaus.blogspot.com.br/2012/04/cais-das-torres-instalacao-de-viga.html.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref7">[11']</p></td>
            <td><p align = "left">http://www.femco.com.br/solucoes.php?produto=Estrutura+de+Mesanino+em+Duplo+T.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref7">[12']</p></td>
            <td><p align = "left">https://premonta.com.br/montagem-de-vigas-em-premoldados/.http://apstecnologia.eng.br/pre-viga.php.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref7">[13']</p></td>
            <td><p align = "left">FUSCO, 1981</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref7">[14']</p></td>
            <td><p align = "left">FUSCOS, 2000.</p></td>
        </tr>
    </tbody>
    </tbody>
</table>
<br>
<p>----------------------------ECA2 aula 10---------------------------------------------------------------------------------------------------------------------------------------------------------------</p>

<br>


<h1>Detalhamento de peças de concreto: Seção Transversal</h1>

<h2>Características das barras de aço</h2>

<p align = "justify">
  Segundos Bastos (2015a) <a href="#ref2">[2]</a> os aços (vergalhões) utilizados em estruturas de Concreto Armado no Brasil são estabelecidos pela ABNT NBR 7480:1996. São produzidos em usinas siderúrgicas com teores de carbono entre 0,4 e 0,6 %. A ABNT NBR 7480:1996 classifica como barras os vergalhões de diâmetro nominal 5 mm ou superior, obtidos exclusivamente por laminação a quente, e como fios aqueles de diâmetro nominal 10 mm ou inferior, obtidos por trefilação ou processo equivalente, como estiramento e laminação a frio. 
  <br><br>
  A ABNT NBR 6118:2014 indica os seguintes valores para as características dos aço:<br><br>
  a) Massa específica: 7.850 kg/m3; <br>
  b) Coeficiente de dilatação térmica: 10-5/ºC para intervalos de temperatura entre – 20ºC e 150ºC;<br>
  c) Módulo de elasticidade longitudinal: 210 GPa ou 210.000 MPa.
</p>
<br>

<p id="fig1"></p>
<center><img src="./assets/images/ECA2_aula10/FIG_1.png" width="90%"></center>
<p align = "justify"><b>Figura 1.</b> Formato do aço para construção civil CA-25, CA-50 e CA-60  <a href="#ref8">[8]</a></p>
<br><br><br>


<p id="tab1"></p>
<table border="0">
    <thead>
        <tr>
            <th>Diâmetro (mm)</th>
            <th>Tipo</th>
            <th>Massa Linear (kg/m)</th>
            <th>Área (cm²)</th>
        </tr>
    </thead>
    <tbody>
        <tr style="background-color: yellow;">
            <td>4,20</td>
            <td>CA 60</td>
            <td>0,109</td>
            <td>0,139</td>
        </tr>
        <tr style="background-color: yellow;">
            <td>5,00</td>
            <td>CA 60</td>
            <td>0,154</td>
            <td>0,196</td>
        </tr>
        <tr>
            <td>6,30</td>
            <td>CA 50</td>
            <td>0,245</td>
            <td>0,312</td>
        </tr>
        <tr>
            <td>8,00</td>
            <td>CA 50</td>
            <td>0,395</td>
            <td>0,503</td>
        </tr>
        <tr>
            <td>10,00</td>
            <td>CA 50</td>
            <td>0,617</td>
            <td>0,785</td>
        </tr>
        <tr>
            <td>12,50</td>
            <td>CA 50</td>
            <td>0,963</td>
            <td>1,227</td>
        </tr>
        <tr>
            <td>16,00</td>
            <td>CA 50</td>
            <td>1,578</td>
            <td>2,011</td>
        </tr>
        <tr>
            <td>20,00</td>
            <td>CA 50</td>
            <td>2,466</td>
            <td>3,142</td>
        </tr>
        <tr>
            <td>25,00</td>
            <td>CA 50</td>
            <td>3,853</td>
            <td>4,909</td>
        </tr>
        <tr>
            <td>32,00</td>
            <td>CA 50</td>
            <td>6,313</td>
            <td>8,042</td>
        </tr>
    </tbody>
</table>
<p align = "justify"><b>Tabela 1.</b> Características da seção do aço </p>
<br>

<h2>Armadura Máxima e Mínima</h2>

<p align = "justify">
  Segundo Carvalho (2014) <a href="#ref4">[4]</a> a armadura mínima deve ser colocada para evitar rupturas bruscas da seção, pois o aço faz com que ela apresente uma deformação razoável antes de entrar em ruína, já os valores máximos decorrem da necessidade de assegurar condições de ductilidade e de respeitar o campo de validade dos ensaios que deram origem as prescrições de funcionamento do conjunto  aço-concreto.
  <br>
  <p id="Eq1"></p>
  <table>
  <tr style = "width=100%">
      <td>
        <img src="./assets/images/ECA2_aula10/Eq_1.png" >
      </td>
      <th> 
        Equação 1
      </th>
    </tr>
  </table>
  
  <p id="Eq2"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula10/Eq_2.png" >
      </td>
      <th> 
        Equação 2
      </th>
    </tr>
  </table>
  
  <p id="Eq3"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula10/Eq_3.png" >
      </td>
      <th> 
        Equação 3
      </th>
    </tr>
  </table>
  <br>
  Onde:
  <br>
  Wo = Módulo de resistência da seção transversal bruta de concreto, relativo à fibra mais tracionada<br>
  f<sub>ctk,sup</sub> = Resistência característica superior do concreto à tração<br>
  f<sub>ctm</sub> = Resistência característica média do concreto à tração
  <br>


  <p id="tab1"></p>
  <table border="0" style = "text-align:center">
    <thead>
        <tr>
            <th rowspan="2">Forma da seção</th>
            <th colspan="10">Valores de p<sub>min</sub>* (Asmin/Ac) %</th>
        </tr>
        <tr>
            <td>20</td>
            <td>25</td>
            <td>30</td>
            <td>35</td>
            <td>40</td>
            <td>45</td>
            <td>50</td>
            <td>55</td>
            <td>60</td>
            <td>65</td>
            <td>70</td>
            <td>75</td>
            <td>80</td>
            <td>85</td>
            <td>90</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Retangular</td>
            <td>0,2</td>
            <td>0,2</td>
            <td>0,2</td>
            <td>0,16</td>
            <td>0,18</td>
            <td>0,19</td>
            <td>0,21</td>
            <td>0,21</td>
            <td>0,22</td>
            <td>0,23</td>
            <td>0,24</td>
            <td>0,25</td>
            <td>0,25</td>
            <td>0,26</td>
        </tr>
        <tr>
          <th colspan = "20" style="text-align: left; font-weight: bold; color: red;">Os valores de p<sub>min</sub> estabelecidos nesta tabela pressupõem o uso do aço CA-50, d/h = 0,8 e γ<sub>c</sub> = 1,4 e γ<sub>s</sub> = 1,15. Caso esses fatores sejam diferentes, p<sub>min</sub> deve ser recalculado.</th>
        </tr>
    </tbody>
</table>
<p align = "justify"><b>Tabela 1.</b> Taxa mínima de armadura para vigas de concreto armado <a href="#ref1">[1]</a></p>
  <br>
  <p id="Eq4"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula10/Eq_4.png" >
      </td>
      <th> 
        Equação 4
      </th>
    </tr>
  </table>
  <br>
  Para a armadura máxima o valor respeitado deve ser de no máximo 4% da área de concreto quando somadas todas as armaduras tracionadas e comprimidas da seção, calculada fora da região de emendas.
</p>
<br>

<h2>Armadura de Pele</h2>

<p align = "justify">
  Segundo Carvalho (2014) <a href="#ref4">[4]</a> as armaduras de pele tem função de mitigar efeitos decorrentes da fissuração, retração e variação da temperatura nas faces de vigas de concreto, servindo também para controlar melhor a abertura de fissuras em vigas. 
  O critério de armadura de pele é aplicado para peças com altura maior ou igual a 60 cm, sendo que a ABNT NBR descreve suas caraterísticas no item 17.3.5.2.3. Sendo a armadura descrita pela equação a seguir:
  <br><br>

  <p id="Eq5"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula10/Eq_5.png" >
      </td>
      <th> 
        Equação 5
      </th>
    </tr>
  </table>
  <br>
  Segundo ABNT NBR 6118:2014 <a href="#ref1">[1]</a> não é necessário uma armadura superior a 5 cm²/m por face do elemento.
  <br>
  <br>
  Alguns projetistas recomendam o uso da armadura de pela para alturas superiores a 40 cm, melhorando assim o controle a fissuração. Bastos (2015) cita para altura maiores que 50 cm por exemplo.
</p>
<br><br><br>

<p id="fig2"></p>
<center><img src="./assets/images/ECA2_aula10/FIG_2.png" width="90%"></center>
<p align = "justify"><b>Figura 2.</b> [COLOCAR]  <a href="#ref2">[2]</a></p>
<br><br><br>

<h2>Espaçamento Entre Barras Longitudinais</h2>

<p align = "justify">
  O espaçamento disponível tem como função adequar as peças para que as mesmas possibilitem condições de trabalho no momento da concretagem. Como colocação de vibradores de imersão, passagem dos agregados pela armadura, evitando assim problemas de segregação em peças de concreto. 
  <br><br>
  Vários cuidados sobre segregação são abordados na ABNT NBR 14931:2004. No item 9.5 já é possível perceber algumas recomendações sobre o momento do lançamento e adensamento da armadura
</p>
<br><br><br>

<p id="fig3"></p>
<center><img src="./assets/images/ECA2_aula10/FIG_3.png" width="90%"></center>
<p align = "justify"><b>Figura 3.</b> Segregação em peças de concreto   <a href="#ref9">[9]</a></p>
<br><br><br>


<p align = "justify">
  O espaçamento disponível pode ser horizontal ou vertical, são dados através das seguintes equações:
  <br><br>
  Fusco (1995) recomenda o acréscimo de mossas no cálculo do diâmetro final das barras. Sendo mossa, as saliências da armadura nervurada (CA 50)
  <br><br>

  <p id="Eq6"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula10/Eq_6.png" >
      </td>
      <th> 
        Equação 6
      </th>
    </tr>
  </table>
  <br>

  <p id="Eq7"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula10/Eq_7.png" >
      </td>
      <th> 
        Equação 7
      </th>
    </tr>
  </table>
    <br>

  <p id="Eq8"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula10/Eq_8.png" >
      </td>
      <th> 
        Equação 8
      </th>
    </tr>
  </table>
  <br>

  <p id="Eq9"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula10/Eq_9.png" >
      </td>
      <th> 
        Equação 9
      </th>
    </tr>
  </table>
</table>
<br>

  <p id="Eq10"></p>
  <table>
  <tr>
      <td>
        <img src="./assets/images/ECA2_aula10/Eq_10.png" >
      </td>
      <th> 
        Equação 10
      </th>
    </tr>
  </table>
</p>
<br>


<p id="tab1"></p>
<table>
  <tr>
    <th>Tipo de Brita</th>
    <th>Diamêtro (mm)</th>
  </tr>
  <tr>
    <td>Brita 0</td>
    <td>4,8 a 9,5</td>
  </tr>
  <tr>
    <td>Brita 1</td>
    <td>9,5 a 19</td>
  </tr>
  <tr>
    <td>Brita 2</td>
    <td>19 a 25</td>
  </tr>
  <tr>
    <td>Brita 3</td>
    <td>25 a 38</td>
  </tr>
</table>
<p align = "justify"><b>Tabela 2.</b> Características dos agregados graúdos  <a href="#ref4">[4]</a></p>
<br>
<br><br><br>

<p id="fig4"></p>
<center><img src="./assets/images/ECA2_aula10/FIG_4.png" width="90%"></center>
<p align = "justify"><b>Figura 4.</b> Espaçamento armaduras –Armadura simples  <a href="#ref9">[9]</a></p>
<br><br><br>
<br><br><br>

<p id="fig5"></p>
<center><img src="./assets/images/ECA2_aula10/FIG_5.png" width="90%"></center>
<p align = "justify"><b>Figura 5.</b> Espaçamento entre feixes de armaduras  <a href="#ref6">[6]</a></p>
<br><br><br>

<h2>Proteção das Armaduras</h2>

<p align = "justify">
  O cobrimento das armaduras é um dos principais fatores para a qualidade das estruturas de concreto armado e protendido. Segundo Fusco (2013) <a href="#ref6">[6]</a> é importante ressaltar que a camada de cobrimento deve proteger todas as barras de armadura, devendo por isso ser medida a partir das barras mais próximas à superfície da peça, considerando-se inclusive a presença de estribos ou de barras de armaduras secundárias e mesmo de armaduras construtivas.
  As armaduras de aço dentro da massa de concreto são protegidas contra a corrosão pelo fenômeno de passivação do aço, que ocorre em virtude da grande alcalinidade do meio ambiente, pois o pH da água existente nos poros do concreto atinge valores superiores a 12,5 (FUSCO, 2013) <a href="#ref6">[6]</a>.
  <br><br>
  A passivação é um fenômeno químico ligado aos metais, que devido a alcalinidade do meio cria uma micro película de óxido de ferro protegendo a mesma da corrosão.
</p>
<br><br><br>

<p id="fig6"></p>
<center><img src="./assets/images/ECA2_aula10/FIG_6.png" width="90%"></center>
<p align = "justify"><b>Figura 6.</b> Câmara passivadora <a href="#ref5">[5]</a></p>
<br><br><br>


<p id="Eq2"></p>
<table border="1" style = "text-align:center">
    <thead>
        <tr>
            <th rowspan = "3">Tipo de estrutura</th>
            <th rowspan = "3">Componente ou elemento</th>
            <th colspan = "5">Classe de agressividade ambiental (Tabela 6.1)</th>
        </tr>
        <tr>
            <th>I</th>
            <th>II</th>
            <th>III</th>
            <th>IV<sup>c</sup></th>
        </tr>
        <tr>
             <th colspan="4">Cobrimento nominal (mm)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="3">Concreto armado</td>
            <td>Laje <sup>b</sup></td>
            <td>20</td>
            <td>25</td>
            <td>35</td>
            <td>45</td>
        </tr>
        <tr>
            <td>Viga/pilar</td>
            <td>25</td>
            <td>30</td>
            <td>40</td>
            <td>50</td>
        </tr>
        <tr>
            <td>Elementos estruturais em contato com o solo <sup>d</sup></td>
            <td colspan = "2">30</td>
            <td>40</td>
            <td>50</td>
        </tr>
        <tr>
            <td rowspan="2">Concreto protendido <sup>a</sup></td>
            <td>Laje</td>
            <td>25</td>
            <td>30</td>
            <td>40</td>
            <td>50</td>
        </tr>
        <tr>
            <td>Viga/pilar</td>
            <td>30</td>
            <td>35</td>
            <td>45</td>
            <td>55</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td colspan="7" align = "left">
                <p><sup>a</sup> Cobrimento nominal da bainha ou dos fios, cabos e cordoalhas. O cobrimento da armadura passiva deve respeitar os cobrimentos para concreto armado.</p>
                <p><sup>b</sup> Para a face superior de lajes e vigas que serão revestidas com argamassa de contrapiso, com revestimentos finais secos tipo carpete e madeira, com argamassa de revestimento e acabamento, como pisos de elevado desempenho, pisos cerâmicos, pisos asfálticos e outros, as exigências desta Tabela podem ser substituídas pelos itens 7.4.7.5, respeitando um cobrimento nominal ≥ 15 mm.</p>
                <p><sup>c</sup> Nas superfícies expostas a ambientes agressivos, como reservatórios, estações de tratamento de água e esgoto, conduções de esgoto, canais de efluentes e outras obras em ambientes químico e intensamente agressivos, devem ser atendidos os cobrimentos da classe de agressividade IV.</p>
                <p><sup>d</sup> No trecho dos pilares em contato com o solo junto aos elementos de fundação, a armadura deve ter...</p>
            </td>
        </tr>
    </tfoot>
</table>
<p align = "justify"><b>Tabela 2.</b> [COLOCAR] <a href="#ref1">[1]</a></p>
<br>
<br>

<h2>Centro de Gravidade para as Armaduras</h2>

<p align = "justify">
  Segundo Carvalho (2014) <a href="#ref4">[4]</a> os esforços na armadura só podem ser considerados concentrados no centro de gravidade das barras se a distância deste centro ao ponto de armadura mais afastado da linha neutra(𝑎<sub>𝑡𝑒𝑠𝑡𝑒</sub>), medida formalmente a ela, for menor que 10% de h. Já para a armadura concentrada considera-se o cálculo abaixo:
</p>
<br>

<h4>centro da primeira barra</h4>

<img src="./assets/images/ECA2_aula10/FIG_c1.png" >

<p id="Eq11"></p>
<table>
<tr>
    <td>
      <img src="./assets/images/ECA2_aula10/Eq_11.png" >
    </td>
    <th> 
        Equação 11
    </th>
  </tr>
</table>
<br>

<img src="./assets/images/ECA2_aula10/FIG_c2.png" >
<br><br><br>


<h3>Bibliografia</h3>

<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Referências</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><p align = "center" id = "ref1">[1]</p></td>
            <td><p align = "left">Associação Brasileira de Normas Técnicas ABNT 6118. Projeto de Estruturas de Concreto. Rio de Janeiro, 2014.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref2">[2]</p></td>
            <td><p align = "left">Bastos, P. S. dos S. Vigas de Concreto Armado. Bauru: Departamento de engenharia civil, 2015. Apostila.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref3">[3]</p></td>
            <td><p align = "left">Bastos, P. S. dos S. Flexão normal simples-vigas. Bauru: Departamento de engenharia civil, 2015b. 78 p. Apostila. </p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref4">[4]</p></td>
            <td><p align = "left">Carvalho, R. C.; Figueiredo Filho, J. R. Cálculo e detalhamento de estruturas usuais de concreto armado segundo a NBR 6118:2014. Vol. 1 4. ed. São Carlos: Edufscar, 2014. 415 p.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref5">[5]</p></td>
            <td><p align = "left">Rossi, D. A. Z.; Brito, F. C.; Sperandio, L. S. Recuperação estrutural: estudo de caso de um edifício residencial. Vitória: Centro tecnológico PPGEC, 2010. 48 p. Trabalho de pós graduação.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref6">[6]</p></td>
            <td><p align = "left">Fusco, P. B. Técnica de armar as estruturas de concreto. 2. ed. São Paulo: PINI, 2013. 391 p.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref7">[7]</p></td>
            <td><p align = "left">Leonhardt, F.; Monning, E. Construções de concreto. Vol. 1 4. ed. Stuttgart: Interciência, 2007. 273 p. </p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref7">[8]</p></td>
            <td><p align = "left">Disponível em: http://goo.gl/NwVt66, acesso em: 08/05/2016 as 11:31</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref7">[9]</p></td>
            <td><p align = "left">Disponível em: http://goo.gl/XzmLxn, acesso em: 08/05/2016 as 11:42</p></td>
        </tr>
    </tbody>
    </tbody>
</table>
<br>