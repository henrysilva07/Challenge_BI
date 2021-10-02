<h1 style="text-align: center;">🚀&nbsp;Alura Challenge BI</h1>
<p style="text-align: justify;">Três empresas nos contrataram para entender suas bases de dados e exibir informações relevantes com o objetivo de auxiliar suas tomadas de decisão.

Conceitos e técnicas de BI serão utilizados para desenvolver um dashboard para uma das empresas.

A primeira empresa, Alura Log, necessita analisar dados sobre a logística de entregas do seu negócio.
A segunda empresa, Alura Shop, precisa de um dashboard para monitorar a campanha de marketing durante um mês.
A terceira empresa, Alura Store, precisa entender como anda a sua área financeira, pensando em hipóteses.:</p>
<p>&nbsp;</p>
<ul>
<li><a href="#Semana 01">Semana 01: Dashboard de Logística (AluraLog)</a></li>
<li><a href="#Semana02">Semana 02: Dashboard de Marketing (AluraShop)</a></li>
<li>Week 03 and 04: Coming Soon&hellip;</li>
</ul>
<p>&nbsp;</p>
<h3>&nbsp; <a id="Semana 01"</a>Semana 01: Dashboard de Logística (AluraLog)</h3>
<p style="text-align: justify;">A pessoa que gerencia a área de logística da Alura Log, está enfrentando algumas mudanças em sua área por conta do aumento da demanda dos serviços de logística no período da pandemia. Ela quer manter a qualidade de seu serviço, mas para isso precisa acompanhar constantemente as métricas do seu departamento para tomar as melhores decisões. Quando nos contou isso, analisamos que para auxiliar nesse desafio precisaremos fazer um dashboard para logística. Para isso, vamos visualizar algumas métricas muito importantes para a área.</p>

<p style="text-align: justify;">
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/Painel.png)</p>
  
<p>✔ Quantas entregas foram realizadas no período?</p>

<p>Foi criado um cartão para indicar o número total de pedidos no período selecionado. Além disso, uma dica de ferramenta foi adicionada para informar o número de entregas por tipo de veículo</p>
<p style="text-align: justify;">
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/Total_pedidos.png)</p>
  
<p style="text-align: justify;">
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/pedidos_dica.png)</p>
  
<p>✔ Quantas entregas foram realizadas dentro e fora do prazo?</p>
<p>Foram criados dois cartões, um para indicar os envios no prazo e atrasados. Mais uma vez foi adicionada uma dica de ferramenta demostrando o número de entregas por tipo de veículo</p>
<p style="text-align: justify;">
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/No_prazo.png)</p>
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/atrasados.png)
  
<p style="text-align: justify;">&nbsp;</p>
<p style="text-align: justify;">
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/pedidos_dica.png)</p>
  
<p>✔ Número de Veículos disponíveis ? </p>
<p>Um cartão foi criado indicando o número de veículos disponíveis e uma dica de ferramenta mostrando qual é o tipo de veículo.</p>
<p style="text-align: justify;">
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/Veiculos.png)</p>

  
<p style="text-align: justify;">
  
   ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/veiculos_2.png)</p>
  

<p>✔ Calcule o estoque médio por ano </p>
<p>Foi utilizado um gráfico de barras com o estoque médio de cada ano.</p>
<p style="text-align: justify;">
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/Estoque_medio.png)</p>
    
<p>✔ Calcule o número de pedidos ao longo do tempo </p>
<p>Para analisar o número de pedidos ao longo do tempo, foi utilizando um gráfico de linhas por mês , sendo possível filtrar o ano por meio do filtro de seleção.</p>
<p style="text-align: justify;">
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/pedidoxtempo.png)</p>    

  
<p>✔ Calcule S2D (Ship to Door) médio por mês </p>
<p>Utilizando um DATEDIFF para calcular a diferença de dias desde a data da compra até data de entrega.</p>
<p style="text-align: justify;">
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/S2D.png)</p>
 

<p style="text-align: justify;">
  
  
<p style="text-align: justify;">Uma dica de ferramenta foi criada para mostrar o S2D por Ano</p>
<p style="text-align: justify;">
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/S2D_dica.png)</p>
  
<p>✔ Mostre  o total de ocorrências por Estados </p>
<p>Um mapa foi criado por utilizando a UF </p>
<p style="text-align: justify;">
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/mapa.png)</p>
  
<p style="text-align: justify;"> O modelo dimensional utilizado foi o star schema , definindo-se duas tabelas fatos : festoque e fpedidos, que por sua vez, são filtradas pelas dimensões dCalendário , dVeículo e dProduto por meio de um relacionamento um pra muitos. 
  
  ![image](https://github.com/henrysilva07/Challenge_BI/blob/main/Semana%2001/img/relacionamentos.png)</p>
  
  * **Acesso ao Dashboard logístico:** [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiODBiNTIzNTktYjgwZS00OWEwLTllZWEtYmE0NGE5YzdhNTRlIiwidCI6ImI1OTFhZTU0LTMzYzItNDU4OS1iZTY2LTkwMjFhNDE5NmM3YyJ9)
