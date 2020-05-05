+++
comments = false
date = 2020-05-04T18:56:36+02:00
draft = false
noauthor = true
share = false
title = " "
type = "page"
[menu.main]
   name = "Research"
weight = 250

+++

>We focus on population dynamics, usually of host-natural enemy interactions, to understand fundamental processes in epidemiology, ecology and evolution of infectious disease. Our works are based on a combination of Mathematical analysis and Modeling with a particular focus on Dynamical Systems. 

## Population dynamics
By involving many fields (mathematics, social sciences, biology), the aim here is to describe variations over time of biological systems. These systems involve a time variable and one or more structuring variables (time since infection, chronological age, space, phenotypic trait, etc.).  In a deterministic framework, these systems are usually described by ODEs (Ordinary Differential Equations), DDEs (Delayed Differential Equations) or PDEs (Partial Derivative Equations). Their study is based on dynamical systems theory.


<html>
<head>
<style>
img {
  float: left;
}
</style>
</head>
<body>

<p><img src="/SEAIR_COVID_severe.svg" alt="Pineapple" style="width:170px;height:170px;margin-right:15px;">
## Scientific computing 
Quite often, a very high complexity (i.e., too strong nonlinearity) of the modeling problem leads to situations where it is difficult to conduct a complete mathematical analysis of the model dynamics. In such cases, it is useful to be able to use the techniques of scientific calculation. It is a discipline that allows a complete numerical experimentation of the model by bringing together a set of mathematical and computer science tools.</p>
</body>
</html>



<!DOCTYPE html>
<html lang="en"><head>
<meta http-equiv="content-type" content="text/html; charset=UTF-8">
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="Samuel Alizon's research website">
	<meta  name="keywords" content="virulence evolution parasites pathogens evolutionary epidemiology phylodynamics within-host virus bacteria drug resistance HPV papillomavirus vaccine multiple infections coinfection superinfection population adaptive dynamics">
    <meta name="author" content="Samuel Alizon">
    <link rel="icon" href="http://www.cnrs.fr/fr/z-tools/newune/themes/CNRSTheme/images/favicon.png">

    <title>Research</title>

    <!-- Bootstrap core CSS -->
    <link href="bootstrap_files/bootstrap.css" rel="stylesheet">

    <!-- Bootstrap theme -->
    <link href="bootstrap_files/bootstrap-theme.css" rel="stylesheet">


    <!-- Custom styles for this template -->
    <!--     <link href="bootstrap_files/blog.css" rel="stylesheet"> --->
    <!--     <link href="bootstrap_files/theme.css" rel="stylesheet"> --->
    <!--     <link href="bootstrap_files/offcanvas.css" rel="stylesheet"> --->
    <link href="bootstrap_files/jumbotron-narrow.css" rel="stylesheet">
    <link href="bootstrap_files/navbar-fixed-top.css" rel="stylesheet">
    <link href="bootstrap_files/sticky-footer-navbar.css" rel="stylesheet">


    <link href="bootstrap_files/carousel.css" rel="stylesheet">
	<style type="text/css" id="holderjs-style"></style></head>



    <!-- Just for debugging purposes. Don't actually copy these 2 lines! -->
    <!--[if lt IE 9]><script src="../../assets/js/ie8-responsive-file-warning.js"></script><![endif]-->
    <script src="bootstrap_files/ie-emulation-modes-warning.js"></script>

    <!-- HTML5 shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>

  <body>

 <!-- Static navbar -->
    <div class="navbar navbar-sam navbar-fixed-top" role="navigation">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target=".navbar-collapse">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="http://alizon.ouvaton.org/">Alizon</a>
        </div>
        <div class="navbar-collapse collapse">
          <ul class="nav navbar-nav">
            <li  class="active"><a href="research.html">Research</a></li>
            <li><a href="people.html">People</a></li>            
            <li><a href="publications.php">Publications</a></li>
         <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown">Projects <span class="caret"></span></a>
              <ul class="dropdown-menu" role="menu">
                <li class="dropdown-header">ERC</li>
                <li><a href="EVOLPROOF.html">EVOLPROOF</a></li>
                <li class="divider"></li>
                <li class="dropdown-header">Ongoing PhDs</li>
                <li><a href="phyloepid.html">Phylodynamics</a></li>
		<li><a href="cancerHPV.html">HPV cancers</a></li>
		<li><a href="virome.html">Virome</a></li>
                <li class="divider"></li>
                <li class="dropdown-header">Other projects</li> 
		<li><a href="mi.html">Multiple infections</a></li>               
                <li><a href="evolvir.html">Virulence evolution</a></li>
                <li><a href="evolemergence.html">Emergence</a></li>
                <li><a href="HIVres.html">Drug resistance</a></li>
                <li><a href="networks.html">Epidemics on networks</a></li>                
                <li><a href="h2.html">Infection trait heritability</a></li>   
              </ul>
            </li>
          </ul>
          <ul class="nav navbar-nav navbar-right">
            <li><a href="contact.html">Contact</a></li>
            <li><a href="research_fr.html"><img title="Recherche" alt="FR" src="figures/flag_fr.png" height="12"></a></li>                                                          
            
          </ul>
        </div><!--/.nav-collapse -->
      </div><!--/.container -->
    </div><!--/.navbar -->
    
  <!-- Carousel
    ==================================================
    <div id="myCarousel" class="carousel slide" data-ride="carousel">

      <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li class="" data-target="#myCarousel" data-slide-to="1"></li>
        <li class="" data-target="#myCarousel" data-slide-to="2"></li>
      </ol>
      <div class="carousel-inner">
        <div class="item active">
          <img src="figures/erc.png" alt="First slide">
          <div class="container">
            <div class="carousel-caption">
              <h1>EVOLPROOF</h1>
              <p>Studying the within-host ecology and the evolutionary epidemiology of human papillomaviruses to assess whether the vaccines are “evolution-proof”.</p>
              <p><a class="btn btn-lg btn-primary" href="#" role="button">Sign up today</a></p>
            </div>
          </div>
        </div>
        <div class="item">
          <img src="data:image/gif;base64,R0lGODlhAQABAIAAAGZmZgAAACH5BAAAAAAALAAAAAABAAEAAAICRAEAOw==" alt="Second slide">
          <div class="container">
            <div class="carousel-caption">
              <h1>Multiple infections and virulence evolution</h1>
              <p>Hosts are often co-infections by more than one parasite strain or species and this greatly affects the expression and evolution of virulence.</p>
              <p><a class="btn btn-lg btn-primary" href="#" role="button">Learn more</a></p>
            </div>
          </div>
        </div>
        <div class="item">
          <img src="figures/phyloepid.png" alt="Third slide">
          <div class="container">
            <div class="carousel-caption">
              <h1>PHYLOEPID</h1>
              <p>For rapidly evolving parasites (such as RNA viruses), the way they spread leads footprints into their genomes. We use ABC methods to infer epidemiological parameters from phylogeny shapes.</p>
              <p><a class="btn btn-lg btn-primary" href="#" role="button">Browse gallery</a></p>
            </div>
          </div>
        </div>
      </div>
      <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev"><span class="glyphicon glyphicon-chevron-left"></span></a>
      <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next"><span class="glyphicon glyphicon-chevron-right"></span></a>
    </div><!-- /.carousel -->




 <div class="container">
 
          <div class="col-12 col-sm-12">    
          
           <div class="jumbotron">
            <h2> Infectious diseases ecology & evolution </h2>
            </div>

          <p> Parasite evolution is usually ignored in public health decisions, but we (and others) think it is key to elaborating robust public health policies. A challenge, which can explain this worrying state of affairs, is that epidemiology and evolution need to be studied toguether. Indeed, evolution affects the way parasites spread and in return the epidemiology shapes the selective pressures undergone by parasites. The goal of medical doctors is to cure but that of scientists is to understand, which is why we prefer to ask fundamental questions such as “Why do parasites harm their host?”.
          
          <p>           Below are some research projects that are active, less active and sleeping.

          <br>
          <br>          
          <hr>
          <br>
          <br>          

      <!-- Three columns of text below the carousel -->
      <div class="row">
        <div class="col-4 col-sm-4">
          <img class="img-circle" src="figures/phyloepid.png" alt="Generic placeholder image" style="width: 140px; height: 140px;">
          <h3>Phylodynamics</h3>
          <p>We analyse microbial genomes to understand the way they spread using simulation-based appoaches (Approximate Bayesian Computation).</p>
          <p><a class="btn btn-default" href="phyloepid.html" role="button">View details »</a></p>
        </div><!-- /.col-lg-4 -->
       <div class="col-4 col-sm-4">
          <img class="img-circle" src="figures/ruban_cancer_col.png" alt="cervical cancer ribbon" style="width: 140px; height: 140px;">
          <h3>HPV cancers</h3>
          <p>We use mathematical modelling approaches from ecology and evolution to understand the role of stochasticity in HPV-associated cancers.</p>
          <p><a class="btn btn-default" href="cancerHPV.html" role="button">View details »</a></p>
        </div><!-- /.col-lg-4 -->
       <div class="col-4 col-sm-4">
          <img class="img-rounded" src="figures/erc.png" alt="Generic placeholder image" style="width: 140px; height: 140px;">
          <h3>EVOLPROOF</h3>
          <p>Studying the within-host ecology and the evolutionary epidemiology of human papillomaviruses to assess whether the vaccines are “evolution-proof”.</p>
          <p><a class="btn btn-default" href="EVOLPROOF.html" role="button">View details »</a></p>
        </div><!-- /.col-lg-4 -->
       <div class="col-4 col-sm-4">
          <img class="img-rounded" src="figures/microbiota.png" alt="Generic placeholder image" style="width: 140px; height: 140px;">
          <h3>Vaginal microbiome</h3>
          <p>Genomics of the vaginal microbiota, with a focus on viruses and plasmids.</p>
          <p><a class="btn btn-default" href="virome.html" role="button">View details »</a></p>
        </div><!-- /.col-lg-4 -->		  
       <div class="col-4 col-sm-4">
          <img class="img-circle" src="figures/mi.png" alt="Generic placeholder image" style="width: 140px; height: 140px;">
          <h3>Multiple infections</h3>
          <p>Hosts are often co-infections by more than one parasite strain or species and this greatly affects the expression and evolution of virulence.</p>
          <p><a class="btn btn-default" href="mi.html" role="button">View details »</a></p>
        </div><!-- /.col-lg-4 -->
        <div class="col-4 col-sm-4">
          <img class="img-circle" src="data:image/gif;base64,R0lGODlhAQABAIAAAHd3dwAAACH5BAAAAAAALAAAAAABAAEAAAICRAEAOw==" alt="Generic placeholder image" style="width: 140px; height: 140px;">
          <h3>Virulence evolution</h3>
          <p>For many parasites, the evolution and maintenance of virulence is intruiguing because it seems to decrease the parasite's epidemiological fitness.</p>
          <p><a class="btn btn-default" href="evolvir.html" role="button">View details »</a></p>
        </div><!-- /.col-lg-4 -->          
        <div class="col-4 col-sm-4">
          <img class="img-circle" src="figures/h2.png" alt="Generic placeholder image" style="width: 140px; height: 140px;">
          <h3>Infection trait heritability</h3>
          <p>Many infection traits are partly governed by the parasite and are as such “heritable” from one infection to the next. We use phylogenies to estimate this trait heritability.</p>
          <p><a class="btn btn-default" href="h2.html" role="button">View details »</a></p>
        </div><!-- /.col-lg-4 -->        

<!--                         <div class="col-4 col-sm-4">
          <img class="img-circle" src="figures/sexnet.jpg" alt="Generic placeholder image" style="width: 140px; height: 140px;">
          <h3>Epidemics on networks</h3>
          <p>Classical epidemiology models assume that sexual contact networks between hosts are unweighted but this seems to be at odds with existing data. We develop models to estimate and understand the impact of this weighting.</p>
          <p><a class="btn btn-default" href="networks.html" role="button">View details »</a></p>
        </div><!-- /.col-lg-4 -->   

        
<!--        <div class="col-4 col-sm-4">
          <img class="img-circle" src="data:image/gif;base64,R0lGODlhAQABAIAAAHd3dwAAACH5BAAAAAAALAAAAAABAAEAAAICRAEAOw==" alt="Generic placeholder image" style="width: 140px; height: 140px;">
          <h3>HIV drug resistance</h3>
          <p>We use nested models that incorporate both within-host and between-host dynamics to study the evolution of resistance in the case of HIV.</p>
          <p><a class="btn btn-default" href="HIVres.html" role="button">View details »</a></p>
        </div>-->
        <!-- /.col-lg-4 --> 
        

<!--           <div class="col-4 col-sm-4">
          <img class="img-circle" src="data:image/gif;base64,R0lGODlhAQABAIAAAHd3dwAAACH5BAAAAAAALAAAAAABAAEAAAICRAEAOw==" alt="Generic placeholder image" style="width: 140px; height: 140px;">
          <h3>Sex heterogeneity</h3>
          <p>Males and females often strongly differ in the way they resist or tolerate infection by parasites. We study how this heterogeneity affects the evolution of parasite virulence.</p>
          <p><a class="btn btn-default" href="sexhet.html" role="button">View details »</a></p>
        </div><!-- /.col-lg-4 -->   

        
          <div class="col-4 col-sm-4">
          <img class="img-circle" src="data:image/gif;base64,R0lGODlhAQABAIAAAHd3dwAAACH5BAAAAAAALAAAAAABAAEAAAICRAEAOw==" alt="Generic placeholder image" style="width: 140px; height: 140px;">
          <h3>Evolutionary emergence</h3>
          <p>The emergence of new parasites is a stochastic process because the parasite is rare. We study the interplay between parasite evolution and epidemiology to understand such dynamics.</p>
          <p><a class="btn btn-default" href="evolemergence.html" role="button">View details »</a></p>
        </div><!-- /.col-lg-4 -->   
        
      </div><!-- /.row -->
      
   </br>
   </br>

</div>
</body></html>




### Antimicrobial resistance

### Malaria 

### HIV and ART

### HBV

