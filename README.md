<!DOCTYPE html>
<html>
<head>
  <title></title>
   <meta charset="utf-8">
    

    <!--Let browser know website is optimized for mobile-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    
    <!--Import Google Icon Font-->
    <link href="http://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <!-- Compiled and minified CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.3/css/materialize.min.css">

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
    <!-- Custom Styles -->
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
 <div class="container">
  
 
    <nav>
       <div class="nav-wrapper  grey darken-1" grey darken-1>
        <a href="#" class="brand-logo right"></a>
        <ul id="nav-mobile" class="left hide-on-med-and-down">
           <li><a href="sass.html">Home</a></li>
           <li><a href="badges.html">Bio</a></li>
           <li><a href="collapsible.html">Contacta</a></li>
           <li><a href="sass.html">Research</a></li>
           <li><a href="sass.html">Projects</a></li>
           <li><a href="sass.html">Publications</a></li>
           <li><a href="sass.html">Teaching</a></li>
           <li><a href="sass.html">Events</a></li>
        </ul>
       </div>
    </nav>

    <div class="slider">
    <ul class="slides">
      <li>
        <img src="http://lorempixel.com/580/250/nature/1"> <!-- random image -->
        <div class="caption center-align">
          <h3>This is our big Tagline!</h3>
          <h5 class="light grey-text text-lighten-3">Here's our small slogan.</h5>
        </div>
      </li>
      <li>
        <img src="http://lorempixel.com/580/250/nature/2"> <!-- random image -->
        <div class="caption left-align">
          <h3>Left Aligned Caption</h3>
          <h5 class="light grey-text text-lighten-3">Here's our small slogan.</h5>
        </div>
      </li>
      <li>
        <img src="http://lorempixel.com/580/250/nature/3"> <!-- random image -->
        <div class="caption right-align">
          <h3>Right Aligned Caption</h3>
          <h5 class="light grey-text text-lighten-3">Here's our small slogan.</h5>
        </div>
      </li>
      <li>
        <img src="http://lorempixel.com/580/250/nature/4"> <!-- random image -->
        <div class="caption center-align">
          <h3>This is our big Tagline!</h3>
          <h5 class="light grey-text text-lighten-3">Here's our small slogan.</h5>
        </div>
      </li>
    </ul>
  </div>


   <div class="row">
      <div class="col s8">
       <h4>Featured Apps</h4>
        <ul class="collection">
          
          <li><img src="img/img.jpg" alt="">
          <h6>Advanced Box Plot for Matlab Power Users<h6>
          <p class="parrafo"> To illustrate the statistical properties of large data sets, Matlab includes a builtin box plot function. Although this function is a suitable tool in everyday use, some circumstances may require a more powerful...</p>
          </li>
           <a class="waves-effect waves-light btn ">Stuff</a>
            
        </ul>
    <h4>Featured Code</h4>
        <ul class="collection">
          
          <li><img src="img/img.jpg" alt="">
          <h6>Advanced Box Plot for Matlab Power Users<h6>
          <p class="parrafo"> To illustrate the statistical properties of large data sets, Matlab includes a builtin box plot function. Although this function is a suitable tool in everyday use, some circumstances may require a more powerful...</p>
          </li>
           <a class="waves-effect waves-light btn ">Stuff</a>
            
        </ul>
          
        <ul class="collection">
          
          <li><img src="img/img" alt="">
          <h6>Advanced Box Plot for Matlab Power Users<h6>
          <p class="parrafo"> To illustrate the statistical properties of large data sets, Matlab includes a builtin box plot function. Although this function is a suitable tool in everyday use, some circumstances may require a more powerful...</p>
          </li>
           <a class="waves-effect waves-light btn ">Stuff</a>
            
        </ul>


      </div>
      <div class="col s4">

      <ul class="collection with-header">
        <li class="collection-header  amber darken-2"><h6>Latest News and Events</h6></li>
        
      <li class="collection-item">Our research paper Revealing Hidden Interconnections between Access ISPs and Content Providers has been accepted at the 20th Eunice Open European Summer School and Conference, organized in Rennes, France between September 1 - 5, 2014.</li>

      <li class="collection-item">Started as a developer at the network virtualization company Midokura, while continuing as part-time visiting lecturer at the Network Technologies and Strategies research group from Pompeu Fabra University.</li>

      <li class="collection-item">PlanetLab Manager, a software application that helps you manage your PlanetLab site, is released and available for download.</li>

      <li class="collection-item">The paper The Impact of Content Delivery Networks on the Internet Ecosystem has been accepted for publication in the Journal of Information Policy by Open Journals System.</li>
    </ul>     
      </div>
  </div>

    <div id="links">
      <ul>
      <li class="icono"><a href=""><i class="fa fa-linkedin-square fa-3x"></i></a></li>
      <li class="icono"><a href="#"><i class="fa fa-github-square fa-3x"></i></a></li>
      <li class="icono"><a href="#"><i class="fa fa-flickr fa-3x"></i></a></li>
      <li class="icono"><a href="#"><i class="fa fa-facebook-official fa-3x"></i></a></li>
      <li class="icono"><a href="#"><i class="fa fa-twitter-square fa-3x"></i></a></li>
      <li class="icono"><a href="#"><i class="fa fa-lastfm-square  fa-3x"></i></a></li>
    </ul>
    </div>
    <p class="palabra">Last updated: September 14, 2014</p>
   <p class="fecha  grey darken-1">alex bikfalvi reseacher enginner developer</p>
   <a class ="ultimo" href="#">Accessibility | Copyright Information</a>

   
 </div>
 <script type="text/javascript" src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
       <script>
         $(document).ready(function(){
           $('.slider').slider({full_width: false, height: "100hv",});
            });  
       </script>
       <!-- Compiled and minified JavaScript -->
       <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.3/js/materialize.min.js"></script>
       
</body>
</html>

body{
	background-color: #bdbdbd;
}
.container{
	background-color: #fafafa ;
	border: 1px solid #000000;
}
h4{
	margin-left: 25px;
}
img {
	margin-top: -10px;
	margin-bottom: -5px;
    float: left;  
}
.collection{
	 border: 2px solid #e0e0e0;
	 box-shadow: 0px 1px 10px #e0e0e0; /* Sombra */
	margin-right: 0px;
     margin-left: 25px; 

}
.collection.with-header{
	float: left;
	margin-bottom: 25px;
	margin-left: 0px;
	margin-right: 25px;
    border: 1px solid #000000;
    box-shadow: 0px 3px 10px  #9e9e9e; /* Sombra */
    position: relative;
    top:-50px;
    z-index: 5;
    
}

.parrafo{
	position: relative;
	left: 5px;
	font-family: 'Arial';
}

.waves-effect.waves-light.btn {
	top: -10px;
	left: 10px;
}
#links {
    width: 100%;
    height: 30px;
    left: 0;
    text-align: left;
      
}
.icono {
    float: left;
    margin: 5px;
    position: relative;
    top: -150px;
    left: 20px;
}

.links{
	position: absolute;
	left: 290px;
}
.cuadro{
	position: relative;
	top: -50px;
	bottom: 0px;
}

.fecha{

    left:0px;
    position: relative;
    top: -90px;
    font-size: 25px;
    text-align: center;
    

}

.palabra{
	text-align: justify;
    font-size: 15px;
    position: relative;
    top: -125px;
    right: 250px;
}
.ultimo {
	   float: left;
    text-align: center;
    position: relative;
    left: 350px;
    top: -90px;
}

