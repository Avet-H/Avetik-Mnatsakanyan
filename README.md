  <html>
  <head>
  
<!--
Yellow #F3AE03
Mulberry #620210
Dark Blue #0C0064
-->
<style>
      body{
          color: #41010C;
          background-color:#FCF5E4;
          }

      h2{
      color:#780216;
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
 <p> I used STATA as a data analytical tool in scope of AGRIS project implemented by FAO with ARMSTAT. Since the reporting tool for the organization was Excel, my task was to develop STATA do.files that will import data,reshape ,run some validation rulles, make imputations if needed, and import the generated final output tables directly into Excel spreadsheet. To see the full examples available click  <a href="https://github.com/Avet-H/Stata/tree/main/agris">here </a> </p>
  
<img title="Agris Project" alt="agris" src="https://github.com/Avet-H/Avetik_Portfolio/blob/main/Images/Image_agris.JPG?raw=true">
  
  
  
  
  
<hr style = "color:white;size:20;align:center;">
  <h2> R projects</h2>
  <h3> 1. Principal Component Analysis (PCA) </h3>
 <p>In this project I show how we can analyze our large dataset by using only 2 dimensions(principal components) of aggregated data as they represent 95% of variabilities. That is, dimensions of data are reduced to 2 while keeping the 95% information and variations of actual data. Thus, we can get an interesting insight about yogurt market and positions of brands in the market with respect to the product features using principal components as shown below. Click <a href="https://github.com/Avet-H/R.git">here</a> to access the R.markdown file. </p>
 
<img title="PCA image" alt="PCA image" src="https://github.com/Avet-H/Avetik_Portfolio/blob/main/Images/PCA image.JPG?raw=true">
  
  <h3> 2. Conjoint Analysis </h3>
  <p> This project presents choice-based conjoint analysis conducted for yogurt market. Respondents were asked to chose one of the 3 alternative options from 15 different combinations of yogurt product attributes. By running logit (multidimensional) model I got the result presented below. If you are curious about interpretations  click <a href="https://github.com/Avet-H/R.git">here</a> to access the R.markdown file. </p>
  
 <img title="PCA image" alt="PCA image" src="https://github.com/Avet-H/Avetik_Portfolio/blob/main/Images/Conjoint Image.JPG?raw=true">
  
  
  
  
<hr style = "color:white;size:20;align:center;">
<h2> Tableau projects</h2>
  
  <p> The following Tableau dashboards are developed based on e-commerse data. To access the data and T-SQL script you can click  <a href="https://github.com/Avet-H/Tableau.git">here</a> </p>
  <div class='tableauPlaceholder' id='viz1673852449699' style='position: relative'><noscript><a href='#'><img alt='Stock Performance ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProductInventoryv&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ProductInventoryv&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProductInventoryv&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1673852449699');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='1024px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='795px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='1024px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='795px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.minWidth='1024px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='795px';vizElement.style.maxHeight=(divElement.offsetWidth*1.77)+'px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
  <br>
  <br>
  <div class='tableauPlaceholder' id='viz1673852816983' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sa&#47;SalesAnalysis_16689889283080&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SalesAnalysis_16689889283080&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sa&#47;SalesAnalysis_16689889283080&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>       
    <script type='text/javascript'>                    var divElement = document.getElementById('viz1673852816983');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1600px';vizElement.style.height='927px';} else if ( divElement.offsetWidth > 800 ) { vizElement.style.width='800px';vizElement.style.height='927px';} else { vizElement.style.width='100%';vizElement.style.height='2127px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);   </script>
  
  
  </body>
<html>
