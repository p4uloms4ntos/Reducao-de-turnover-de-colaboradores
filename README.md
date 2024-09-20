<h1 dir="auto">Objetivo</h1>

<p dir="auto">Este projeto de an&aacute;lise de dados visa utilizar um conjunto diversificado de m&eacute;todos estat&iacute;sticos para investigar e responder ao questionamento levantado pelo departamento de Gest&atilde;o de Pessoas:<strong>&nbsp;quais estrat&eacute;gias organizacionais ou fatores internos, se alterados, poderiam auxiliar na diminui&ccedil;&atilde;o da rotatividade de funcion&aacute;rios&nbsp;</strong><em>(Turnover)</em><strong>?</strong></p>

<h3 dir="auto">T&eacute;cnicas aplicadas:</h3>

<ul dir="auto">
	<li>An&aacute;lise explorat&oacute;ria das vari&aacute;veis com as bibliotecas YData-Profiling e SweetViz;</li>
	<li>Coeficiente de Person;</li>
	<li>Information Value (IV).</li>
</ul>

<h3 dir="auto">C&oacute;digos desenvolvidos.</h3>

<ul dir="auto">
	<li>Fun&ccedil;&atilde;o para gerar os relat&oacute;rios Ydata e SweetViz de forma autom&aacute;tica;</li>
	<li>Classe com fun&ccedil;&otilde;es para explorarmos a t&eacute;cnica de&nbsp;<strong>Information Value.</strong></li>
</ul>

<h1 dir="auto"><strong>Introdu&ccedil;&atilde;o</strong></h1>

<p>&nbsp;</p>

<p dir="auto">A introdu&ccedil;&atilde;o deste artigo destaca a import&acirc;ncia do turnover, ou rotatividade de funcion&aacute;rios, como um desafio significativo para as corpora&ccedil;&otilde;es, pois a sa&iacute;da de um colaborador implica custos financeiros e de tempo para a empresa, que precisa investir em processos de recrutamento e treinamento de novos funcion&aacute;rios, al&eacute;m de enfrentar uma poss&iacute;vel queda na produtividade do setor afetado.</p>

<p dir="auto">Diversos fatores podem influenciar a decis&atilde;o de um funcion&aacute;rio de deixar a organiza&ccedil;&atilde;o, tais como a busca por melhores oportunidades, um ambiente organizacional desfavor&aacute;vel, rela&ccedil;&otilde;es interpessoais inadequadas com superiores, ou a falta de um equil&iacute;brio saud&aacute;vel entre a vida pessoal e profissional. Para investigar as causas do&nbsp;<em>turnover</em>&nbsp;em empresas de tecnologia, o departamento de RH conduziu uma pesquisa com&nbsp;<strong>1470 funcion&aacute;rios</strong>, resultando na identifica&ccedil;&atilde;o de&nbsp;<strong>19 fatores potenciais</strong>&nbsp;que podem explicar essa din&acirc;mica. A an&aacute;lise desses fatores &eacute; crucial para que a gest&atilde;o de recursos humanos possa desenvolver estrat&eacute;gias eficazes para a reten&ccedil;&atilde;o de talentos e a manuten&ccedil;&atilde;o de uma for&ccedil;a de trabalho est&aacute;vel e engajada.</p>

<p dir="auto">A&nbsp;<strong>base de dados</strong>&nbsp;empregada&nbsp;<strong>neste estudo</strong>&nbsp;foi fornecida de forma fict&iacute;cia pela empresa&nbsp;<strong>Preditiva Analytics</strong>, permitindo uma simula&ccedil;&atilde;o realista de cen&aacute;rios organizacionais.</p>

<p dir="auto">___________________________________________________________________________________________________________________</p>

<p dir="auto">&nbsp;</p>

<h1 dir="auto"><strong>Conclus&atilde;o</strong></h1>

<p>&nbsp;</p>

<p dir="auto">A an&aacute;lise realizada neste estudo demonstrou que a taxa de Turnover da empresa, atualmente em&nbsp;<strong><code>16,12%</code></strong>, &eacute; significativamente superior ao ideal sugerido pela literatura, de cerca de 10%. Este excesso de rotatividade implica custos diretos e indiretos &agrave; organiza&ccedil;&atilde;o, tais como processos de recrutamento, treinamento e impactos na produtividade. Diante dos fatores identificados, sugerimos uma s&eacute;rie de pol&iacute;ticas corporativas e estrat&eacute;gias para mitigar esse impacto causado pela sa&iacute;da de funcion&aacute;rio acima do limite &oacute;timo.</p>

<p dir="auto">As principais vari&aacute;veis que influenciam a m&eacute;trica de turnover, est&atilde;o associadas a&nbsp;<strong>horas extras</strong>,&nbsp;<strong>tempo de empresa,</strong>&nbsp;&nbsp;<strong>sal&aacute;rio, tempo no mesmo cargo, idade e tempo de carreira</strong>.<br />
Colaboradores que realizam horas extras apresentam uma taxa de turnover alarmante de&nbsp;<code>31%</code>, comparado aos&nbsp;<code>10%</code>&nbsp;de quem n&atilde;o realiza. Isso indica uma clara necessidade de revis&atilde;o das pr&aacute;ticas de gest&atilde;o de carga de trabalho e controle de horas extras, a fim de evitar a sobrecarga dos colaboradores e promover um equil&iacute;brio mais saud&aacute;vel entre a vida profissional e pessoal.<br />
Uma pol&iacute;tica corporativa que incentiva o controle de horas extras, o desenvolvimento de programas de bem-estar e o incentivo ao uso de folgas e f&eacute;rias pode reduzir significativamente a rotatividade.<br />
&nbsp;</p>

<p dir="auto">O&nbsp;<strong>tempo de empresa</strong>&nbsp;tamb&eacute;m se mostrou um fator crucial, com funcion&aacute;rios de at&eacute; dois anos de casa apresentando&nbsp;<code>2,2</code>&nbsp;vezes mais chances de&nbsp;<strong>sair da empresa</strong>. Portanto, pol&iacute;ticas de preven&ccedil;&atilde;o para novos colaboradores s&atilde;o essenciais. Programas de onboarding robustos e mentorias estruturadas, que oferecem suporte e feedback cont&iacute;nuo, podem ajudar a integrar novos funcion&aacute;rios de maneira mais eficaz, aumentando seu engajamento e, consequentemente, sua perman&ecirc;ncia.<br />
&nbsp;</p>

<p dir="auto">O&nbsp;<strong>sal&aacute;rio</strong>&nbsp;tamb&eacute;m declarado &eacute; um fator relevante, especialmente para colaboradores que ganham at&eacute; <strong><code>R$2.695,00</code></strong>, com uma probabilidade&nbsp;<strong>2,4&nbsp;vezes maior de sair da empresa</strong>. &Agrave; medida que o sal&aacute;rio aumenta, a taxa de rotatividade diminui,&nbsp;<strong>exceto para a faixa de R$10.000,00</strong>, onde observamos uma ruptura na tend&ecirc;ncia de redu&ccedil;&atilde;o de demiss&otilde;es. Isso pode ser reflexo de uma sobrecarga de responsabilidades para cargos mais altas, ou oportunidades externas mais interessantes para profissionais de alto n&iacute;vel. Assim, &eacute; importante considerar uma pol&iacute;tica de revis&atilde;o salarial, aliada &agrave; redistribui&ccedil;&atilde;o de responsabilidades, para evitar a sa&iacute;da de colaboradores valiosos. Al&eacute;m disso, a cria&ccedil;&atilde;o de planos de carreira com progressos salariais claros e incentivos por desempenho pode ser uma ferramenta poderosa para reter talentos.</p>

<p dir="auto">Colaboradores com&nbsp;<strong>menos de um ano no cargo</strong>&nbsp;tamb&eacute;m apresentam maior propens&atilde;o ao turnover, com uma probabilidade de&nbsp;<code>2</code>&nbsp;vezes maior de deixar a empresa. Isso refor&ccedil;a a necessidade de pol&iacute;ticas de concentra&ccedil;&atilde;o focadas no desenvolvimento profissional logo no in&iacute;cio da trajet&oacute;ria do funcion&aacute;rio dentro da organiza&ccedil;&atilde;o. A implementa&ccedil;&atilde;o de programas de desenvolvimento de carreira e feedback constante s&atilde;o a&ccedil;&otilde;es fundamentais para mitigar essa sa&iacute;da precoce.</p>

<p dir="auto">O fator&nbsp;<strong>idade</strong>, que se correlaciona fortemente com o&nbsp;<strong>tempo de carreira</strong>, tamb&eacute;m aponta que funcion&aacute;rios em&nbsp;<strong>in&iacute;cio de carreira</strong>&nbsp;(at&eacute; cinco anos) t&ecirc;m&nbsp;<strong>maior tend&ecirc;ncia de sa&iacute;da</strong>. A contrata&ccedil;&atilde;o de profissionais mais experientes pode ser uma estrat&eacute;gia eficiente para diminuir a rotatividade, j&aacute; que esses colaboradores tendem a se estabilizar na empresa com mais rapidez e a contribuir de forma mais s&oacute;lida para a opera&ccedil;&atilde;o da empresa.</p>

<p dir="auto">Sugest&otilde;es de Pol&iacute;ticas Corporativas:</p>

<ul dir="auto">
	<li>Controle de Horas Extras;</li>
	<li>Onboarding e Integra&ccedil;&atilde;o;</li>
	<li>Revis&atilde;o Salarial e Carreira;</li>
	<li>Redistribui&ccedil;&atilde;o de Responsabilidades;</li>
	<li>Reten&ccedil;&atilde;o de Talentos.</li>
</ul>

<p dir="auto">Com base nessas pol&iacute;ticas e estrat&eacute;gias, a empresa poder&aacute; n&atilde;o apenas reduzir sua taxa de Turnover, mas tamb&eacute;m criar um ambiente organizacional mais saud&aacute;vel, sustent&aacute;vel e alinhado aos seus objetivos de longo prazo, promovendo reten&ccedil;&atilde;o de talentos e aumento dos resultados.</p>

<p dir="auto">__________________________________________________________________________________________________________________</p>

<p dir="auto">Para entender como essas conclus&otilde;es foram alcan&ccedil;adas, acompanhe o&nbsp;desenvolvimento do problema de neg&oacute;cio&nbsp;proposto, algoritmo criados e t&eacute;cnicas utilizadas clicando <a href="https://github.com/p4uloms4ntos/reducao-de-turnover-de-colaboradores/blob/master/Redu%C3%A7%C3%A3o%20de%20Turnover%20dos%20Colaboradores.ipynb">aqui</a>.</p>
