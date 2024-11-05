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
<table border = 1 aligin ="center">
  <tr style="text-align: center;" >
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
<br><br>
<p style = "text-align:justify">
    Nesse material são abordados os aspectos de dimensionamento das pontes. Mas para isso é necessário fazer uma série de classificações da diversidade desses modelos de projeto. Normalmente essa classificação pode ser feita em função do modelo de estrutura, finalidade dessa estrutura, material componente da estrutura, sistema construtivo, etc. Pfeil, Vitório, Stucchi e El Debs & Takeya [3]–[6] apresentam as características dessa classificação e as mesmas serão detalhadas conforme esses autores.
</p>
<br>
<h3><b>2.1 - Classificações nos projetos de pontes: Finalidade</b></h3>
<br>
<p>
    Quanto a finalidade ou uso as pontes podem ser definidas como: (a) Rodoviárias: são aquelas em que a carga acidental é definida na norma NBR 7188 [1]; (b) Ferroviárias: são aquelas em que a carga acidental é definida antiga NBR 7189 [7]; (c) Passarelas (pontes para pedestres): são aquelas em que a carga acidental corresponde à multidão de pessoas. Adota-se de um modo geral, a carga de 5 KN/m² (0,5 tf /m²); (d) Aeroviárias; (e) Aquedutos; e (f) Mistas.     
</p>
<br>
<table align = "center" border = "1">
       <tr>
        <th colspan = "3">
            Figura 1.3 – Modelo de pontes e viadutos segundo a sua finalidade: (a) Aeroviária ou taxiway do aeroporto de Leipzig/Halle [8]; (b) Ponte ferroviária de High Bridge [9] no estado da Dakota do Norte; e (c) Ponte Rio-Niterói [10] no estado do Rio de Janeiro.
        </th>
    </tr>
    <tr>
        <th>
        <img  src="https://bordalo.observador.pt/v2/rs:fill:900/c:770:433:nowe:0:0/q:70/f:webp/plain/https://s3.observador.pt/wp-content/uploads/2018/01/30202838/11426900743_52842c0a60_o_770x433_acf_cropped.jpg" alt="" >
        </th>
        <th>
            <img  src="https://i.pinimg.com/736x/1a/58/cf/1a58cf588a4592919206c129d6a1c815.jpg" alt="" width="1100" height="150">
        </th>
        <th>
             <img  src="https://estradas.com.br/wp-content/uploads/2021/05/Rodovia_BR_101_Ponte_Rio_Niteroi_3.png.webp" alt="" >
        </th>
    </tr>
    <tr>
        <th>
          (a)
        </th>
        <th>
          (b)
        </th>
        <th>
          (c)
        </th>
    </tr>
</table>
<br>


<br><br>
<h3><b>2.2 – Classificações nos projetos de pontes: Material</b></h3>
<br>
<p style = "text-align:justify">
    Quanto ao uso do material as pontes podem ser as mais diversas possíveis variando desde a madeira até estruturas mistas aço-concreto. Nos primórdios da engenharia as pontes eram construídas em pedra, alvenaria ou madeira. A Fig. 1.4 apresenta esses vários modelos de materiais que compõem o sistema estrutural de uma ponte.
</p>
<br>
<table align = "center" border = "1">
       <tr>
        <th colspan = "2">
           Figura 1.4 – Variações dos materiais constituintes de uma ponte: (a) Ponte de Pedras na cidade de Zaragoza-Espanha [11]; (b) Ponte Anita Garibaldi na cidade de Laguna-Brasil [12].
        </th>
    </tr>
    <tr>
        <th>
        <img  src="https://umbrasileironaespanha.wordpress.com/wp-content/uploads/2012/03/19-basc3adlica-do-pilar-e-ponte-de-pedra.jpg" alt="Ponte de Pedras na cidade de Zaragoza-Espanha" >
        </th>
        <th>
            <img  src="https://live.staticflickr.com/4175/34475416095_2f4a63061a_h.jpg" alt="Ponte Anita Garibaldi na cidade de Laguna-Brasil " >
        </th>
    </tr>
    <tr>
        <th>
          (a)
        </th>
        <th>
          (b)
        </th>
    </tr>
</table>
<br><br>
<p style = "text-align:justify">
    No final do século XVIII surgiram as pontes metálicas, e nessas estruturas aplicava-se o ferro fundido. Vitório [4] assegura que com a revolução industrial e a competitividade dos produtos siderúrgicos, as pontes em aço estrutural passaram a ser largamente utilizadas a partir do final do século XIX, com destaque para as pontes pênseis.<br><br>

Uma das primeiras pontes em estrutura metálica é a ponte do Forth a mesma é localizada no Reino Unido, situada próximo a cidade escocesa de Edimburgo. A mesma tem mais de 2,5 km de comprimento, e é destinada em exclusivo ao tráfego ferroviário.
</p>
<br><br><br>

<table align = "left" border = "0">
       <tr>
        <th colspan = "2">
           Figura 1.5 – Ponte ferroviária do Rio Forth na Escócia [13].
        </th>
    </tr>
    <tr>
        <th >
        <img  src="data:image/jpeg;base64,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" alt="Ponte ferroviária do Rio Forth na Escócia" >
        </th>
        <th rowspan = "2">
            <img  src="data:image/jpeg;base64,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" alt="Ponte ferroviária do Rio Forth na Escócia " >
        </th>
    </tr>
    <tr>
        <th>
          <img  src="data:image/jpeg;base64,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" alt="Ponte ferroviária do Rio Forth na Escócia " >
        </th>
    </tr>
</table>
<p style = "text-align:justify" align = "right">
    Em termos históricos, as primeiras pontes em concreto armado surgiram no final do século XIX, sendo que a primeira ponte executada com tal material foi construída por Joseph Monier na França em 1875, e está localizada no parque do palácio do Marquês Tihene de Chazedet, em forma de abóboda e com 16,50 m de vão e 4 m de largura.<br><br>

Outros modelos de pontes em concreto foram se consolidando após a segunda guerra mundial, vista a necessidade de uma rápida reconstrução das cidades. Elementos em concreto pré-moldado e concreto protendido ganharam espaço nessa cena histórica sendo que estes são os modelos mais utilizados atualmente.
</p>
<br><br><br>
<h3><b>2.3 – Classificações nos projetos de pontes: Sistema estrutural</b></h3>
<br>
<p style = "text-align:justify" >
    Outra classificação interessante se dá em relação ao sistema estrutural adotado na ponte. Os autores citados anteriormente afirmam que o sistema assumem os mais diversos formatos podendo ser: (a) Ponte em lajes; (b) Ponte em viga; (c) Ponte em pórtico; (d) Ponte em arco; (e) Ponte pênsil; (f) Ponte estaiada; e (g) Ponte treliçada.<br><br>
Segundo Vitório [4] as pontes em laje (Fig. 1.6) são usadas em situações onde o vão a ser vencido é pequeno (cerca e 15 m), apresentando as seguintes vantagens:<br>

<ol type = "a">
    <li>Pequena altura de construção;</li>
    <li>Grande resistência à torção;</li>
    <li>Grande resistência ao fissuramento;</li>
    <li>Simplicidade e rapidez de construção;</li>
    <li>Boa solução para obras esconsas.</li>
</ol>
<br><br>
Vitório [4] afirma que essas pontes devem ter esbeltez L/h em torno de 15 a 22 para situações em que o material utilizado é o concreto armado, já em concreto protendido essa relação pode ser aumenta para o intervalo de 18 a 30. Onde L representa o vão do sistema e l a espessura da laje.
</p>
<br><br><br>

<table align = "left" border = "0">
       <tr>
        <th colspan = "2">
           Figura 1.6 – Ponte formada por lajes: (a) Seção maciça [4]; (b) Seção vazada [4]; (c) Modelo de ponte em laje alveolar [14].
        </th>
    </tr>
    <tr>
        <th >
        <img  src="" alt="IMAGENS DO SLIDE 14 DA AULA 1 DE PONTES" >
        </th>
        <th rowspan = "2">
            <img  src="" alt="IMAGENS DO SLIDE 14 DA AULA 1 DE PONTE" >
        </th>
    </tr>
    <tr>
        <th>
          <img  src="" alt="IMAGENS DO SLIDE 14 DA AULA 1 DE PONTE" >
        </th>
    </tr>
</table>
<br><br><br>
<p style = "text-align:justify">
    As pontes em vigas possuem várias subdivisões pois dependerá do modelo estrutural utilizado na fabricação das vigas. Segundo Vitório [4] são elas:
    <br><br>
    Pontes em vigas simplesmente apoiadas:<br>
    <ol type = "a">
        <li>Sistema estaticamente determinado do ponto de vista da análise estrutural;</li><br>
        <li>Facilidade executiva e economia quando utiliza-se de peças pré-moldadas;</li><br>
        <li>Pode-se utilizar do recurso de balanços na estrutura para redução dos momentos positivos no vão central. Fernandes & Correia [15] afirmam que o vão do balanço deve ter cerca de 15 a 20% do vão central;</li><br>
        <li>Pode ser utilizada para vencer pequenos, médios e grandes vãos.
</li>
    </ol>
    <br><br>
    Pontes em vigas continuas:<br>
    <ol type = "a">
        <li>Permite uma melhor distribuição dos esforços quando utilizada uma inércia de seção variável e consequente redução do peso próprio da peça;</li><br>
        <li>Pista de rolamento mais uniforme evitando desconforto no tráfego [16];</li><br>
        <li>Permite a eliminação de juntas e a consequente redução do custo de manutenção [16].</li>
    </ol>
    <br><br>
    Pontes em viga Gerber:<br>
    <ol type = "a">
        <li>Formada por estruturas isostáticas;</li><br>
        <li>Não recebe esforços adicionais em caso de recalques diferenciais; </li><br>
        <li>Bastante utilizadas no passado;</li><br>
        <li>Deve-se ter bastante cuidado em relação as articulações visto que essa pode ser uma das principais fontes de patologia nesse sistema.</li>
    </ol>
</p>
<br><br>
<table align = "left" border = "1">
       <tr>
        <th colspan = "2">
           Figura 1.7 – Modelos de ponte em vigas: (a) Ponte em viga simplesmente apoiada; (b) Ponte em viga contínua; e (c) Ponte em viga Gerber [4].
        </th>
    </tr>
    <tr>
        <th >
        <img  src="" alt="IMAGENS DO SLIDE 16 DA AULA 1 DE PONTES" >
        </th>
        <th>
            <img  src="" alt="IMAGENS DO SLIDE 16 DA AULA 1 DE PONTE" >
        </th>
    </tr>
     <tr>
        <th >
        (a)
        </th>
        <th>
         (b)
        </th>
    </tr>
    <tr>
        <th colspan = "2">
          <img  src="" alt="IMAGENS DO SLIDE 16 DA AULA 1 DE PONTE" >
        </th>
    </tr>
    <tr>
        <th colspan = "2">
        (c)
        </th>
    </tr>
</table>
<br><br><br>
<p style = "text-align:justify">
	Segundo Vitório [4] o sistema estrutural em arco foi muito utilizado no  passado  como a única alternativa viável para vencer grandes vãos,  principalmente diante da dificuldade da execução  de  apoios  intermediários  e  escoramentos  sobre  cursos  d’água  ou vales profundo.<br>

	O’Connor [17] apresenta as denominações desse modelo estrutural (Ver Fig. 1.8 e 1.9) que é bastante vantajoso. O formato em arco permite a redução dos esforços de flexão na superestrutura.  Apesar dessa vantagem o autor ainda afirma que tal modelo estrutural pode ter custo elevado devido a dificuldade de fabricação das nervuras do arco.
</p>
<br><br>

 <table align = "left" border = "1">
       <tr>
        <th colspan = "2">
           Figura 1.8 – Nomenclatura da ponte em arco [17].
        </th>
    </tr>
    <tr>
        <th colspan = "2">
          <img  src="" alt="IMAGENS DO SLIDE 17 DA AULA 1 DE PONTE" >
        </th>
    </tr>
</table>
<br><br>
 <table align = "left" border = "1">
       <tr>
        <th colspan = "2">
           Figura 1.9 – Tipos de ponte em arco [17].
        </th>
    </tr>
    <tr>
        <th colspan = "2">
          <img  src="" alt="IMAGENS DO SLIDE 18 DA AULA 1 DE PONTE" >
        </th>
    </tr>
</table>
 <table align = "right" border = "1">
       <tr>
        <th colspan = "2">
          Figura 1.10 – Ponte Rainbow sobre o Rio Niágara que fica na fronteira do Canadá com EUA [18].
        </th>
    </tr>
    <tr>
        <th colspan = "2">
          <img  src="https://a.travel-assets.com/findyours-php/viewfinder/images/res70/56000/56416-Rainbow-Bridge.jpg" alt="Ponte Rainbow sobre o Rio Niágara que fica na fronteira do Canadá com EUA" >
        </th>
    </tr>
</table>
<br><br><br>
<p style = "text-align:justify">
	A Ponte Pênsil se caracteriza com um modelo de ponte suspenso, Vitório [4] afirma que as pontes pênseis são constituídas por cabos  dispostos parabolicamente e pendurais verticais. Tais cabos normalmente são presos sem sistemas de torres e ancoragens externas. Juntamente com as pontes em arco esse modelo suspenso é considerado como uma das estruturas mais antigas da história da Engenharia Civil [19].<br><br>

	Normalmente esse sistema é executado com vigamentos metálicos. Os vigamentos podem ser em executados em treliças ou vigas de alma cheia. Os mesmos devem ter grande rigidez à flexão e principalmente à torção, de modo a minimizar os efeitos dos movimentos  vibratórios transversais que podem causar desconforto aos usuários ou mesmo risco à estrutura.<br><br>

	A Fig. 1.11 apresenta a ponte Hercílio Luz que é a maior ponte Pênsil do Brasil e a Fig. 1.12 apresenta uma das pontes mais famosas do mundo a ponte Golden Gate.
</p>
<br><br>

<table align = "left" border = "1">
       <tr>
        <th colspan = "2">
          Figura 1.11 – A ponte Hercílio Luz em Florianópolis que é um dos exemplos de uma ponte pênsil [20].
        </th>
    </tr>
    <tr>
        <th colspan = "2">
          <img  src="https://estado.sc.gov.br/noticias/wp-content/uploads/sites/3/2022/05/ponte_hercilio_luz_completa_96_anos_com_programacao_especial_20220512_1673447418.jpg" alt=" Hercílio Luz em Florianópolis " >
        </th>
    </tr>
</table>

<table align = "center" border = "1">
       <tr>
        <th colspan = "2">
         Figura 1.12 – A ponte Golden Gate que é um dos exemplos de uma ponte pênsil [21].
        </th>
    </tr>
    <tr>
        <th colspan = "2">
           <img  src="https://www.vidadeturista.com/wp-content/uploads/2020/10/the-golden-gate-bridge-san-francisco-1.jpg" alt="Ponte Golden Gate" >
        </th>
    </tr>
</table>
<br><br><br>
<p style = "text-align:justify">
	Nas  pontes estaiadas (Fig. 1.13 e 1.14) o tabuleiro é suspenso através de cabos inclinados  fixados em torres. O tabuleiro, geralmente metálico ou em concreto protendido, deve ter grande rigidez à torção, de modo a reduzir os movimentos vibratórios causados pela ação transversal do vento [4].<br><br>
	Alguns autores afirmam que esse modelo de pontes é uma evolução dos modelos pênseis pois a ideia do modelo estrutural é o mesmo, a busca por redução do número de apoios, peso próprio e atingindo vãos maiores.<br><br>
	Como dito anteriormente esses modelos de pontes são de pontes suspensas, porém na ponte pênsil os cabos principais acompanham o desenvolvimento longitudinal da ponte se apoiando nas torres e fixadas nas extremidades. Já no modelo estaiado o não possui a forma de uma catenária e os cabos estão fixados as torres intermediárias [22].<br><br>
	Nos modelos pênseis a forma da curva deve ser preservada para manter a eficiência de transporte dos esforços até os apoios, logo para vão maiores, maior deve ser o pilar que servirá de apoio [22].
</p>
<br><br>

 <table align = "right" border = "1">
       <tr>
        <th colspan = "2">
        Figura 1.13 – Complexo Turístico Mirante da Ponte Estaiada em Teresina, Piauí [23].
        </th>
    </tr>
    <tr>
        <th colspan = "2">
           <img  src="https://i0.wp.com/nordestetur.com.br/wp-content/uploads/2021/10/Complexo-Turistico-Mirante-Ponte-Estaiada-semdec.teresina.pi_.gov_.br_.jpg?resize=960%2C540&ssl=1" alt="Complexo Turístico Mirante da Ponte Estaiada em Teresina" >
        </th>
    </tr>
</table>

 <table align = "center" border = "1">
       <tr>
        <th colspan = "2">
        Figura 1.14 – Viaduto Milau no vale do rio Tarn [24].
        </th>
    </tr>
    <tr>
        <th colspan = "2">
           <img  src="https://axialengenharia.eng.br/wp-content/uploads/2016/12/viadutomillau.jpg" alt="Viaduto Milau no vale do rio Tarn " >
        </th>
    </tr>
</table>
<br><br>
<p style = "text-align:justify">
	A ideia básica do sistema estrutural estaiado é baseada em um conjunto de cabos inclinados que são conectados a torres. Os cabos nesses caso simulam apoios intermediários ao longo do vão [25].<br><br>
Existem vários tipos de sub modelos estruturais associados as pontes estaiadas. Alguns desses submodelos descrevem características de distribuição longitudinal e transversal dos cabos estaiados. Em relação a distribuição longitudinal  os mesmos são definidos como: (a) Leque; (c) Harpa; (c) Semi-Harpa; e (d) Assimétrico (Ver Fig. 1.15).
</p>
<br>

<table align = "center" border = "1">
       <tr>
        <th colspan = "2">
       Figura 1.15 – Modelos para arranjo dos cabos em pontes estaiadas [26].
        </th>
    </tr>
    <tr>
        <th colspan = "2">
           <img  src="" alt="IMAGEM DO SLIDE 23 DA AULA 1 DE PONTES" >
        </th>
    </tr>
</table>
<br>
<p style = "text-align:justify">
	Em relação a distribuição transversal de essa poderá ser feita em um ou dois planos verticais (Ver Fig. 1.16) ou até mesmo em sistemas de torres únicas com distribuição dos cabos em planos inclinados.
</p>
<br>

<table align = "center" border = "1">
    <tr>
       <th colspan = "5">
      Figura 1.16 – Modelos estruturais de pontes estaiadas; (a) Distribuição em apenas um plano vertical; (b) Distribuição em dois planos verticais [27].
       </th>
    </tr>
    <tr>
        <th colspan = "2">
              (a)
        </th>
        <th colspan = "2">
           <img  src="" alt="IMAGEM DO SLIDE 24 DA AULA 1 DE PONTES" >
        </th>
        <th colspan = "2">
           <img  src="" alt="IMAGEM DO SLIDE 24 DA AULA 1 DE PONTES" >
        </th>
    </tr>
    <tr>
     	<th colspan = "2">
          (b)
        </th>
        <th colspan = "2">
           <img  src="" alt="IMAGEM DO SLIDE 24 DA AULA 1 DE PONTES" >
        </th>
        <th colspan = "2">
           <img  src="" alt="IMAGEM DO SLIDE 24 DA AULA 1 DE PONTES" >
        </th>
    </tr>
</table>
<br><br>
<p style = "text-align:justify">
	O modelos em Harpa utilizam uma simetria no espaçamento dos cabos logo tal fato contribui para estética do modelo estrutural apesar não ser o sistema estrutural mais eficiente [27]. Em casos de assimetria do carregamento (Ver Fig. 1.17) o sistema de tabuleiro deverá ter uma rigidez maior tornando assim a  estrutura mais robusta.
</p>
<br><br>

<table align = "center" border = "1">
       <tr>
        <th colspan = "2">
       Figura 1.17 – Cargas assimétricas no sistema de ponte estaiada com distribuição de cabos em harpa [27].
        </th>
    </tr>
    <tr>
        <th colspan = "2">
           <img  src="" alt="IMAGEM DO SLIDE 25 DA AULA 1 DE PONTES" >
        </th>
    </tr>
</table>
<br><br>
<p style = "text-align: justify">
	Na concepção em Leque [27] os esforços horizontais introduzidos pelo tabuleiro são reduzidos devido a verticalidade dos cabos evitando assim um acúmulo de tensões por esse efeito. Nessa situação de leque o espaçamento entre os estais é relativamente pequeno permitindo uma melhor distribuição dos esforços entre os cabos. Porém nessa geometria o emaranhado de cabos no topo dos pilares causa uma certa dificuldade no projeto dos sistemas de ancoragem.
	<br><br>
	Os sistemas treliçados são amplamente utilizados desde o início do desenvolvimento da engenharia estrutural. Estes  caracterizam-se por possuírem um peso próprio inferior que outros tipos de estruturas, além de que devido a sua alta parcela rigidez o sistema também admite grandes vãos.
	<br><br>
	Uma das desvantagens do sistema é que o mesmo necessita de uma mão de obra altamente especializada, além de que os custos com fabricação e montagem do sistema são elevados.
	<br><br>
	Em sistemas de pontes treliçadas os momentos fletores teoricamente devem ser nulos. Tal condição poderia ser alcançada caso houvesse a introdução de articulações sem atrito em todos os nós. Na prática de projeto, a maioria dos elementos são rigidamente ligados nas juntas, transmitindo uma parcela de momento fletor para as peças. No caso esse momento fletor ainda é pequeno e é controlado através das dimensões da treliça como também pelo processo de fabricação e montagem [17].
	<br><br><br><br>
	Sobre o formato o mesmo poderá ser os mais diversos possíveis. Normalmente alguns formatos são bastante tradicionais, como as treliças tipo: Pratt, Howe, Warren e sistema K. A seguir na Fig. 1.18 são apresentados esses modelos.
</p>
<br>
<table align = "center" border = "1">
       <tr>
        <th colspan = "2">
     Figura 1.18 – Modelos de treliça: (a) Treliça Pratt; (b) Treliça Howe; (c) Treliça Warren; (d) Sistema K contraventado; e (e) Sistema contraventado em losangos [17].
        </th>
    </tr>
    <tr>
        <th colspan = "2">
           <img  src="" alt="IMAGEM DO SLIDE 27 DA AULA 1 DE PONTES" >
        </th>
    </tr>
</table>
<br><br>
<p style = "text-align:justify">
	Segundo  O’Connor [17] o sistema Pratt é vantajoso visto que a compressão atua prioritariamente nos elementos de montante que são mais curtos que as diagonais que por definição são tracionadas.
	<br><br>
	O’Connor [17] afirma que os sistemas contraventados tipo K são utilizados quando a altura do painel é da ordem de duas a três vezes o seu comprimento.
	<br><br>
	Pinho e Bellei [28] afirmar que treliças são econômicas com altura variando de 1/8 a 1/15 do vão em estudo. Os mesmos afirmam que o modelo de treliça é utilizado para um vão entre 50 m e 120 m quando ditas isostáticas e vãos de até 250 m quando utilizadas em modelos contínuos.
	<br><br><br>
	Segundo Vitório [4] as pontes, os pórticos são formados pela ligação das vigas com os pilares ou com as paredes dos encontros, caracterizando a continuidade entre esses elementos em substituição às articulações.
	<br><br>
	Como as extremidades da viga são engastadas nos encontros, os momentos negativos de engastamento reduzem o momento positivo, possibilitando a redução de altura no vão.
</p>
<br><br>

<table align = "center" border = "1">
       <tr>
        <th colspan = "2">
      Figura 1.19 – Modelos de pontes em pórtico aberto e fechado de concreto [29].
        </th>
    </tr>
    <tr>
        <th colspan = "2">
           <img  src="" alt="IMAGEM DO SLIDE 29 DA AULA 1 DE PONTES" >
        </th>
    </tr>
</table>
<br><br>
<h3><b>2.3 – Classificações nos projetos de pontes: Comprimento</b></h3>
<br><br>
<p style = "text-align:justify">
	El Debs e Takeya [3] classifica da seguinte forma em função do comprimento:<br><br>
 	<ol type = "a">
		<li>Galerias (Bueiros): de 2 a 3 metros;</li>
		<li>Pontilhões: de 3 a 10 metros; </li>
		<li>Pontes: acima de 10 metros.</li>
	</ol>
    <br>
    Existe ainda uma divisão, também de contornos não muito definidos, que é:<br><br>
    <ol type = "a">
		<li>Pontes de pequenos vãos: até 30 metros; </li>
		<li>Pontes de médios vãos: 30 a 60 a 80 metros </li>
		<li>Pontes de grandes vãos: acima de 60 a 80 metros</li>
	</ol>
	<br><br><br>
</p>
<br><br>

<h3><b>2.3 – Classificações nos projetos de pontes: Desenvolvimento planimétrico </b></h3>
<br><br>

<p>
	El Debs e Takeya [3] apresenta alguns formatos da superestrutura:
</p>
<br><br>

<table align = "center" border = "0">
		<tr>
          <th colspan = "2">
       Figura 1.20 – Modelos de desenvolvimento planimétrico da superestrutura [3].
          </th>
    	</tr>
       <tr>
        <th colspan = "1">
    		 (a)
        </th>
        <th colspan = "1">
     		(b)
        </th>
      </tr>
      <tr>
        <th colspan = "1">
           <img  src="" alt="IMAGEM DO SLIDE 31 DA AULA 1 DE PONTES" >
        </th>
        <th colspan = "1">
           <img  src="" alt="IMAGEM DO SLIDE 31 DA AULA 1 DE PONTES" >
        </th>
      </tr>
      <tr>
        <th colspan = "2">
          (c)
        </th>
      </tr>
      <tr>
        <th colspan = "2">
           <img  src="" alt="IMAGEM DO SLIDE 31 DA AULA 1 DE PONTES" >
        </th>
      </tr>
</table>
<br><br><br>

<h3><b>2.3 – Classificações nos projetos de pontes: Desenvolvimento altimétrico </b></h3>
<br><br>
<p>
	El Debs e Takeya [3] apresenta alguns formatos da superestrutura e seu desenvolvimento altimétrico:
</p>
<br><br>

<table align = "center" border = "0">
		<tr>
          <th colspan = "2">
       Figura 1.21 – Modelos de desenvolvimento altimétrico da superestrutura [3].
       <br>
       &nbsp;
          </th>
    	</tr>
       <tr>
        <th colspan = "1">
    		 (a)
             <br>
       &nbsp;
        </th>
        <th colspan = "1">
     		(b)
            <br>
       &nbsp;
        </th>
      </tr>
      <tr>
        <th colspan = "1">
           <img  src="" alt="IMAGEM DO SLIDE 32 DA AULA 1 DE PONTES" >
           <br>
       &nbsp;
        </th>
        <th colspan = "1">
           <img  src="" alt="IMAGEM DO SLIDE 32 DA AULA 1 DE PONTES" >
           <br>
       &nbsp;
        </th>
      </tr>
      <tr>
        <th colspan = "">
          (c)
          <br>
       &nbsp;
        </th>
        <th colspan = "">
          (d)
          <br>
       &nbsp;
        </th>
      </tr>
      <tr>
        <th colspan = "">
           <img  src="" alt="IMAGEM DO SLIDE 32 DA AULA 1 DE PONTES" >
           <br>
       &nbsp;
        </th>
        <th colspan = "">
           <img  src="" alt="IMAGEM DO SLIDE 32 DA AULA 1 DE PONTES" >
           <br>
       &nbsp;
        </th>
      </tr>
</table>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<h1><b>Aula 2: Processo Construtivo</b></h1>
<br><br><br>
<table border = 1 aligin ="center">
  <tr style="text-align: center;" >
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

<h2><b>INFRAESTRUTURA</b></h2>
<br><br>
<p style = "text-align:justify">
	Os métodos construtivos dos elementos de infraestrutura seguem as premissas básicas dos elementos tradicionais de fundações, sejam essas fundações rasas ou profundas. Lembrando que as característica para dimensionamento das fundações são relativos a normativa NBR 6122 [1].
	<br><br>
	fundações rasa: São aqueles elementos executadas para descarregar seu esforços nas primeiras camadas do solo. A profundidade de assentamento do elemento no terreno é de no máximo duas vezes a sua menor dimensão em planta;
	<br><br>
	fundações profunda: São aqueles elementos executadas para descarregar seus esforços em camadas mais profundas de solo. A transmissão dos esforços é feito por resistência de ponta e/ou fuste ou por uma combinação das duas. O assentamento dos elementos é superior ao dobro de sua menor dimensão em planta, e no mínimo 3 m.
</p>
<br><br><br>

<h3><b>1.1 - Tubulão e tubulão ao ar comprimido</b></h3>
<br><br>
<p>
	A fundação tipo tubulão é bastante utilizada para aplicações em pontes de concreto armado. Devido a magnitude dos carregamentos essas estruturas tendem a ser mais robustas que a de estruturas usuais. 
	<br><br>
	Os tubulões pode ser de dois tipos:
	<br><br>
	<ul>
		<li>Céu aberto;</li>
		<li>Ar comprimido – Neste é permitida a escavação abaixo do lençol freático (muito útil em pontes).</li>
	</ul>
</p>
<br><br>

<table align = "center" border = "1">
       <tr>
        <th colspan = "3">
			Figura 1.1 – Esquema tradicional de carregamento em um tubulão em estruturas usuais [2].
        </th>
    </tr>
    <tr>
        <th colspan = "2">
           <img  src="" alt="IMAGEM DO SLIDE 5 DA AULA 2 DE PONTES" >
        </th>
        <th colspan = "2">
           <img  src="" alt="IMAGEM DO SLIDE 5 DA AULA 2 DE PONTES" >
        </th>
    </tr>
</table>
<br><br><br>

<table align = "center" border = "1">
       <tr>
        <th >
			Figura 1.2 – Tubulão de ar comprimido [3] apud Fogaça1.
        </th>
    </tr>
    <tr>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 6 DA AULA 2 DE PONTES" >
        </th>
    </tr>
</table>
<br><br><br>

<table align = "center" border = "1">
       <tr>
        <th >
		Figura 1.3 – Geometria de um tubulão [2].
        </th>
    </tr>
    <tr>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 6 DA AULA 2 DE PONTES" >
        </th>
    </tr>
</table>
<br><br>
<p>
	Esquema de construção:<br><br>
	<ul>
		<li>Escavação dos poços primários e colocação das camisas metálicas;</li>
		<li>Escavação completo do poço;</li>
		<li>Colocação da armação;</li>
		<li>Concretagem.</li>
	</ul>
</p>
<br><br>

<table align = "right" border = "1"> 
    <tr>
        <th>
           <iframe width="560" height="315" src="https://www.youtube.com/embed/WYBGEbbL6vE" ></iframe>
    </tr>
</table>
<br><br><br>

<h3><b>1.2 – Estacas</b></h3>
<br><br>

<p>
	Bastos [4] afirma que os tubulões vêm sendo atualmente substituídos por estacas (pré-moldadas ou moldadas in loco). São exemplos de elementos de estacas para construção de pontes:
	<br><br>
	<ul>
		<li>Escavada de Grande Diâmetro (Estacão);</li>
		<li>Escavada Embutida em Rocha;</li>
		<li>Hidrofesa;</li>
		<li>Hélice Contínua;</li>
		<li>Raiz;</li>
		<li>Pré-moldada.</li>
	</ul>
</p>
<br>
<table align = "right" border = "1"> 
    <tr>
        <th>
           <iframe width="560" height="315" src="https://youtube.com/embed/JR0xGsdqxyU" ></iframe>
    </tr>
    <tr>
        <th>
           <iframe width="560" height="315" src="https://youtube.com/embed/bS-bcN8LRWc" ></iframe>
    </tr>
</table>
<br><br><br>

<h2><b>2 - MESOESTRUTURA</b></h2>
<br><br>
<p style = "text-align:justify">
	Segundo a normativa DNIT [5] o método construtivo da mesoestrutura depende principalmente de sua altura, os pilares podem ser executados, pelo menos, de quatro maneiras distintas: 
	<br><br>
	<ol type = "a">
		<li>Através de peças pré-moldadas, em passarelas e obras de pequenos vãos; </li>
		<li>Através de concretagem convencional, isto é, executadas as fôrmas completas, concreta-se de baixo para cima, em concretagens contínuas, concreto lançado ou bombeado e vibrado;</li>
		<li>Através de fôrmas deslizantes, fôrmas desmontáveis de cerca de 1,0 m de altura, empurradas continuamente para cima, simultaneamente com a concretagem, contínua e vibrada;</li>
		<li>Através de fôrmas trepantes, fôrmas desmontáveis de cerca de 3,0 m de altura e concretagem por segmentos, vibrada e interrompida. </li>
	</ol>
 	<br><br>
  	O sistema construtivo da mesoestrutura influi no seu detalhamento; no caso particular de fôrmas deslizantes recomenda-se um cobrimento adicional das armaduras, de 3 a 4 cm, para combater a tendência à fissuração da camada superficial do concreto, provocada pelo arrasto das fôrmas. 
   	<br><br>
    	As imagens sequências são retiradas de Bastos [4]. 
</p>
<br><br>

<table align = "center" border = "1">
       <tr>
        <th colspan = "2">
			Figura 2.1 – Peças pré-moldadas, em passarelas e obras de pequenos vãos [4], Mold2.
        </th>
    </tr>
    <tr>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 11 DA AULA 2 DE PONTES" >
        </th>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 11 DA AULA 2 DE PONTES" >
        </th>
    </tr>
</table>
<br><br><br>

<table align = "center" border = "1">
       <tr>
        <th colspan = "2">
			Figura 2.2 – Convencional, com fôrmas completas, concretagem contínua com concreto lançado ou bombeado e vibrado [4], SH3.
        </th>
    </tr>
    <tr>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 12 DA AULA 2 DE PONTES" >
        </th>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 12 DA AULA 2 DE PONTES" >
        </th>
    </tr>
</table>
<br><br><br>

<table align = "center" border = "1">
       <tr>
        <th colspan = "2">
			Figura 2.3 – Fôrma deslizante, desmontável com cerca de 1 m de altura, empurrada continuamente para cima, simultaneamente com concretagem, contínua e vibrada[4], SH3.
        </th>  
    </tr>
    <tr>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 13 DA AULA 2 DE PONTES" >
        </th>
       <th rowspan = "2">
           <iframe width="560" height="315" src="https://youtube.com/embed/WRPs5EtK8vE" ></iframe>
        </th>
    </tr>
</table>
<br><br><br>

<table align = "center" border = "1">
       <tr>
        <th colspan = "3">
			Figura 2.4 – Fôrma trepante, desmontável, com cerca de 3 m de altura e concretagem por segmentos, vibrada e interrompida [4], ULMA4.
        </th>  
    </tr>
    <tr>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 14 DA AULA 2 DE PONTES" >
        </th>
       <th rowspan = "2">
           <img  src="" alt="IMAGEM DO SLIDE 14 DA AULA 2 DE PONTES" >
        </th>
        <th rowspan = "2">
           <iframe width="560" height="315" src="https://youtube.com/embed/uPUsl5_2c14" ></iframe>
        </th>
    </tr>
</table>
<br><br><br>

<h2><b>3 - SUPERESTRUTURA</b></h2>
<br><br>

<p>
	De acordo com Leonhardt [6] a classificação segundo o processo executivo é dada por três subdivisões, são elas:
 	<br><br>
	Construção com concreto moldado in loco:
	<br>
    <ol type = "1">
        <li>Fôrmas sobre escoramentos fixos;</li>
        <li>Fôrmas sobre escoramentos deslizantes;</li>
        <li>Balanços sucessivos com fôrma deslocável;</li>
        <li>Balanços sucessivos com treliça de lançamento e fôrma deslocável.</li>
    </ol>
    <br><br>
    Construção com elementos pré-moldados:
    <br>
    <ol type = "1">
        <li>Elementos pré-moldados sobre o vão inteiro;</li>
        <li>Segmentos pré-moldados;</li>
    </ol>
    <br><br>
    Construção por deslocamentos progressivos.
    <br><br>
    De acordo com Bastos [4] essa classificação se refere normalmente ao procedimento de execução da superestrutura, pois em os elementos de mesoestrutura e infraestrutura quase sempre utilizam concreto moldado in loco para execução
</p>
<br>
<p style = "text-align:justify">
	Segundo Quintana Ytza [7] o modelo de cimbramento (Ver Fig. 3.1) é usado geralmente em um zona de baixo gabarito e solo com boa capacidade resistente. O cruzamento não está congestionado com estradas ou ferrovias, e a estrutura em questão não tem que atravessar um curso de água.
	<br><br>
	Leonhardt [6] e Stucchi [8] citam algumas observações e cuidados que se deve com esse processo executivo com um escoramento fixo:
</p>
<br>
<ol type = "a">
	<li>Fundação e contraventamento do cimbramento; </li>
	<li>Contra flechas para compensar recalques ou deformações de vigas e treliças; </li>
	<li>Cuidados  na  concretagem - Recalques  e  deformações  devem  ocorrer  antes  do  final  da concretagem. Tratar juntas; </li>
	<li>Cuidados  na  desforma - Desencunhar  do  centro  para  os  apoios  de  cada  vão  e  só  após desmontar o cimbramento; </li>
	<li>Vistoriar antes, durante e depois da concretagem.</li>
	<li>Vantajosos para execução de uma estrutura de mais de três vãos com mesma seção transversal;</li>
	<li>Esse processo só é prático quando o terreno for nivelado.</li>
</ol>
<br><br>

<table align = "center" border = "1">
       <tr>
        <th >
			Figura 3.1 – Utilização de escoramentos metálicos fixos para concretagem1.
        </th>  
    </tr>
    <tr>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 18 DA AULA 2 DE PONTES" >
        </th>
    </tr>
</table>
<br><br><br>

<table align = "center" border = "1">
       <tr>
        <th >
			Figura 3.2 – Utilização de escoramentos metálicos fixos para concretagem [8].
        </th>  
    </tr>
    <tr>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 19 DA AULA 2 DE PONTES" >
        </th>
    </tr>
</table>
<br><br>

<table align = "center" border = "1">
       <tr>
        <th >
			Figura 3.3 – Processo construtivo de concreto moldado in loco com fôrmas sobre escoramentos deslizantes [6].
        </th>  
    </tr>
    <tr>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 19 DA AULA 2 DE PONTES" >
        </th>
    </tr>
</table>
<br><br><br>

<p>
	Sobre o método onde o sistema de escoramentos é deslizante Stucchi [8] afirma que todas as precauções anteriores são válidas porém com a seguinte adição de cuidados:
 	<br><br>
  	<ol type = "a">
		<li>O processo construtivo influência no dimensionamento da peça (ver Fig. 3.4);</li>
		<li>Definição das posições de junta e posterior tratamento;</li>
		<li>Cuidado com as interferências que podem impedir o movimento das formas ou da treliça.</li>
	</ol>
</p>
<br><br>

<table align = "center" border = "1">
       <tr>
        <th >
			Figura 3.4 – Diagrama de solicitações para o modelo construtivo [8].
        </th>  
    </tr>
    <tr>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 20 DA AULA 2 DE PONTES" >
        </th>
    </tr>
</table>
<br><br>

<table align = "center" border = "1">
       <tr>
        <th >
		Figura 3.4 – Concreto moldado in loco em balanços sucessivos com treliça de lançamento e fôrma deslocável [6].
        </th>  
    </tr>
    <tr>
        <th>
           <img  src="" alt="IMAGEM DO SLIDE 21 DA AULA 2 DE PONTES" >
        </th>
    </tr>
</table>
<br><br>

<p style = "text-align:justify">
	O sistema pré-moldado é bastante econômico, desde que se tenha estruturas com segmentos iguais [6]. Todo o processo de pré-moldagem pode ser feita fora do canteiro em fábricas especificas para esse fim. A Fig. 3.5 apresenta a sequência desse processo construtivo.
</p>
<br><br>










