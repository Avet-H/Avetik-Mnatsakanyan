  <html>
  <head>
  
<!--
Yellow #F3AE03
Mulberry #620210
Dark Blue #0C0064
-->
<style>
      body{
          color: #0C0064;
          background-color:#F3AE03;
          }

      h2{
      color:#620210;
      text-align: center;
      }

      h3{
      color:#0C0064;
       }
</style>
  </head>
  
<body>


<h1> Data Analysis example projects with PowerBI, R, Stata, Tableau</h1>

<p style="font-family:courier;font-size:120%;color:#233C6F;"> Hi! My name is Avetik Mnatsakanyan. <br>
 I am a data analyst with a solid academic background in economics, econometrics, and statistics.  I have more than 5 years of experience in different types of data analysis, data management, data cleaning and visualization, survey design, and data modeling.<br> <br>
  With this webpage, I'm presenting to you some of my technical skills.</p>
<hr style = "color:white;size:20;align:center;">
  
<h2 style = "color:#620210">  Power BI projects </h2>
<p>The projects listed in this section are developed using Power BI desktop (click on titles to access .pbix files in GitHub) </p>

 <a href="https://github.com/Avet-H/PowerBI/blob/main/Contoso_DAX%20examples.pptx"> <h3>1. Contoso_DAXexamples </h3> </a>
 <p> Data Analytics Expression is a powerful tool that can be used to generate more complex measures and calculated column for dynamic vizualizations. This project is developed using the "Contoso" sample data provided by microsoft and shows some of commonly used calculations with DAX.</p>

<div>
  <!--  <img title="main" alt="pic1" src="https://github.com/Avet-H/Avet-H/blob/main/Images/Slide1.PNG?raw=true"> -->
   
    <img title="share" alt="pic2" src="https://github.com/Avet-H/Avet-H/blob/main/Images/Slide2.PNG?raw=true">
   
    <img title="cumulative" alt="pic3" src="https://github.com/Avet-H/Avet-H/blob/main/Images/Slide3.PNG?raw=true">
   
    <img title="pareto" alt="pic4" src="https://github.com/Avet-H/Avet-H/blob/main/Images/Slide4.PNG?raw=true">
   
    <!--  <img title="daily" alt="pic5" src="https://github.com/Avet-H/Avet-H/blob/main/Images/Slide5.PNG?raw=true">
   
    <img title="time-intelligence" alt="pic6" src="https://github.com/Avet-H/Avet-H/blob/main/Images/Slide6.PNG?raw=true"> -->
</div>
    
 <!--  ![Shares](https://github.com/Avet-H/Avet-H/blob/main/Images/Slide2.PNG?raw=true)
![Cumulative](https://github.com/Avet-H/Avet-H/blob/main/Images/Slide3.PNG?raw=true)
![Pareto](https://github.com/Avet-H/Avet/blob/main/Images/Slide4.PNG?raw=true)
![Daily](https://github.com/Avet-H/Avet-H/blob/main/Images/Slide5.PNG?raw=true)
![Time Intelligence](https://github.com/Avet-H/Avet-H/blob/main/Images/Slide6.PNG?raw=true)
-->

<a href="https://github.com/Avet-H/PowerBI/blob/main/Billionaires.pbix"> <h3>   2. Billionaire </h3> </a>
<p> I've always been curious about wealth distribution across countries, industries, companies and even individuals. Here are some descriptive graphs and indicators that I developed based on the data published by Forbes about Billionaires at the end of 2022. In the same file, you can find a page report presenting GDP data from 2021 according to WorldBank data and compare those numbers to get an interesting insight. Apparently, if we sort countries by their GDP in ascending order and combine the GDPs of the first 165 countries we will get about $11.5 trillion which is approximately the same amount as 2490 billionaires' net worth together! </p>

<img title="Billionaire" alt="Billionaire" src="https://github.com/Avet-H/Avet-H/blob/main/Images/Billionaires.JPG?raw=true">
    
<img title="GDP" alt="GDP" src="https://github.com/Avet-H/Avet-H/blob/main/Images/GDP.JPG?raw=true">
    
 <!--  ![Billionaires2022](https://github.com/Avet-H/Avet-H/blob/main/Images/Billionaires.JPG?raw=true)
![GDP2021](https://github.com/Avet-H/Avet-H/blob/main/Images/GDP.JPG?raw=true) -->


<a href="https://github.com/Avet-H/PowerBI/blob/main/NBA%20visuals.pbix"> <h3>  3. NBA visual </h3> </a>
<p> Using some historical data from NBA I created the interesting vizual about shots and distances in 2010 - 2018 period. </p>

<img title="NBA vizuals" alt="NBA" src="https://github.com/Avet-H/Avet-H/blob/main/Images/NBA.JPG?raw=true">
    
 <!-- ![GDP2021](https://github.com/Avet-H/Avet-H/blob/main/Images/NBA.JPG?raw=true) -->

<br>

  
  <hr style = "color:white;size:20;align:center;">
  <h2> STATA projects</h2>
  <h3> 1. Inferential and causal analysis</h3>
<p> I have used Stata for economic estimations during my both graduate programs: at ATC,Yerevan,Armenia and at UCDavis,CA,US. AS an example, I present one of the projects completed during master program at UCDavis where we were trying to replicate econometric papers. We used Jupyter notebook with Stata to present both discussions and calculation in one place. The screenshot presented below is a part of the project where we replicated the <a href="https://github.com/Avet-H/Stata/blob/main/Labor%20Supply%20and%20the%20Value%20of%20Non-Work%20Time_original%20article.pdf"> "Labor Supply and the Value of Non-Work Time" </a> article by Alexandre Mas and Amanda Pallais. Click <a href="https://github.com/Avet-H/Stata/blob/main/Replication_Labor%20Supply%20and%20the%20Value%20of%20Non-Work%20Time.ipynb">here </a> to access the full Jupyter file. </p>

<img title="Paper replication" alt="paper_Jup" src="https://github.com/Avet-H/Avet-H/blob/main/Images/paper_jupiter.JPG?raw=true">

   <h3> 2. Data Manipulation and output table calculation </h3>
 <p> I used STATA as a data analitical tool in scope of AGRIS project implemented by FAO with ARMSTAT. Since the reporting tool for the organization was Excel, my task was to develop STATA do.files that will import data,reshape ,run some validation rulles, make imputations if needed, and import the generated final output tables directly into Excel spreadsheet. To see the full examples available click  <a href="https://github.com/Avet-H/Stata/tree/main/agris">here </a> </p>
  
<img title="Agris Project" alt="agris" src="https://github.com/Avet-H/Avetik_Portfolio/blob/main/Images/Image_agris.JPG?raw=true">
  
  </body>
<html>
