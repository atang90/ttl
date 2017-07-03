
<!DOCTYPE html>
 <html ng-app="myApp">
   <head>

    <!-- /// Meta tags ///-->
    <meta id='viewport' name="viewport" content="maximum-scale=1.0, initial-scale=1.0" />
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="description" content="Throughthelens is a gallery of the photographs I have taken since 2016.">
    <meta name="keywords" content="Photography, photo, gallery">

     <!-- /// Import Materialize ///-->
     <!--Import Google Icon Font-->
     <link href="http://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
     <link href="https://fonts.googleapis.com/css?family=Raleway:300,400,400i,700|Ubuntu:300,400,700" rel="stylesheet">

     <!--Import materialize.css-->
     <link type="text/css" rel="stylesheet" href="css/materialize.min.css"  media="screen,projection"/>
     <link type="text/css" rel="stylesheet" href="css/style.css"  media="screen,projection"/>
     <link type="text/css" rel="stylesheet" href="css/mediaqueries.css"  media="screen,projection"/>

     <!--script src="../angular/css/custom.css"></script-->

     <title>Throughthelens.gallery</title>

   </head>

   <body>

     <!-- /// Navigation Bar ///-->
     <nav class="light-blue darken-2">
       <div class="nav-wrapper container"><a href="index.html" class="brand-logo">Throughthelens.gallery</a>
         <a href="#" data-activates="mobile-demo" class="button-collapse"><i class="material-icons">menu</i></a>
         <ul class="right hide-on-med-and-down valign-wrapper" id="menusymbols">
           <li><a href="about.php"><img class="left" src="images/navi/viewmenu_symbol.svg"><span style="padding-left:7px">About</span></a></li>
           <li><a href="gallery.html"><img class="left" src="images/navi/viewmenu_symbol.svg"><span style="padding-left:7px">Gallery</span></a></li>
           <li><a href="contact.html"><img class="left" src="images/navi/viewmenu_symbol.svg"><span style="padding-left:7px">Contact</span></a></li>
         </ul>
       </div>
     </nav>

     <!-- /// Add Parallax Effect ///-->
     <div class"parallax-containter">
        <div class="parallax"><imag src="heroimage.jpg"></div>
     </div>

     <div class="section white">
       <div class="row container">
         <h4 class="header"><b>Gallery<b></h4>
       </div>
     </div>

  <main>

    <div class="row container">
      <div class="col s12 m6">
        <div class="grid center-align col">

            <div class="card grid-item left-align">
              <div class="card-image">
                <img src="cambo17team.jpg" alt="team">
                <span class="card-title">Cambodian Mission Team 2017</span>
              </div>
            </div>

            <div class="card grid-item left-align">
              <div class="card-image">
                <img src="cambo17team.jpg" alt="team">
                <span class="card-title">Cambodian Mission Team 2017</span>
              </div>
            </div>

        </div>
      </div>
    <div>

  </main>

      <!-- /// Footer /// -->
      <footer class="page-footer light-blue darken-2">
        <div class="container">
          <div class="footer-copyright"> Copyright &copy; 2017 Andrew Tang</div>
        </div>
      </footer>

      <!--Import jQuery before materialize.js-->
      <script src="js/jquery-3.2.1.min.js"></script>
      <script src="js/materialize.min.js"></script>
      <script src="js/init.js"></script>

   </body>
 </html>
