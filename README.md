<!DOCTYPE html>
<html>
<head>
<title>Dan Peacock, writer</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>

img {
  border-radius: 15px;
}

body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}

#rcorners1 {
  border-radius: 15px;
  background: #b9117e;
  padding: 20px; 
  width: 1000px;
  height: 500px;  
}

</style>
</head>
<body class="w3-light-gray w3-content" style="max-width:850px">

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-collapse w3-blue-gray w3-animate-left" style="z-index:3;width:300px;" id="mySidebar"><br>
  <div class="w3-container">
    <a href="#" onclick="w3_close()" class="w3-hide-large w3-right w3-jumbo w3-padding w3-hover-grey" title="close menu">
      <i class="fa fa-remove"></i>
    </a>
    <img src = "peacock.png" width="150"  height="250"> 
    &nbsp; 
    <h4><b>Dan Peacock</b></h4>
    
  </div>
  <div class="w3-bar-block">
      <a href="#about-me" onclick="w3_close()" class="w3-bar-item w3-button w3-padding w3-text-white"><i class="fa fa-user fa-fw w3-margin-right"></i>ABOUT ME</a>
      <a href="#short-stories" onclick="w3_close()" class="w3-bar-item w3-button w3-padding w3-text-white"><i class="fa fa-th-large fa-fw w3-margin-right"></i>SHORT STORIES</a> 
        <a href="https://twitter.com/DanPeacock92" onclick="w3_close()" class="w3-bar-item w3-button w3-padding"><i class="fa fa-twitter w3-margin-right"></i>TWITTER</a>
           
          
        
        
  </div>
  
  
</nav>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large w3-animate-opacity" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:300px">



 

  <!-- Header -->
  <header id="about-me">
    
    <span class="w3-button w3-hide-large w3-xxlarge w3-hover-text-grey" onclick="w3_open()"><i class="fa fa-bars"></i></span>
    <div class="w3-container">
     <h1><strong><p style="color: #b9117e;">Dan Peacock</p></strong></h1>
  
    <p>Dan Peacock is a sci-fi and fantasy writer from the UK.<p>
    <p>His short stories have been published or are forthcoming in <em>F&amp;SF, Kaleidotrope, The Dread Machine,</em> and others. He is also a First Reader at <em><a href="https://www.orions-belt.net/">Orion's Belt.</a></em></p>
    <p><a href="https://twitter.com/DanPeacock92?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-show-count="false">Follow @DanPeacock92</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    

        
<hr style="border: 2px solid #b9117e;">

    &nbsp;
    &nbsp;
    <header id="short-stories">
    <h3><strong>Published stories</strong></h3>
    
    
  </header>
  <table cellspacing="10">
    <tr>
    
      <td onclick="location.href=https://ethereamagazine.com/product/etherea-magazine-16/"><a href="https://ethereamagazine.com/product/etherea-magazine-16/"><img src="tidallock.jpg" width="150" height="225"></a></td>
      <td><p><strong><a href="https://ethereamagazine.com/product/etherea-magazine-16/">"The Tidal Lock"</a></strong> <p> <p>Published in <em>Interstellar Fiction</em>, Aug 2013 <p> <p>Reprinted in <a href="https://ethereamagazine.com/product/etherea-magazine-16/"><em>Etherea</em></a>, Jan 2023<p></td>        
    </tr>
  </table>
  
   &nbsp;
      <h3><strong>Forthcoming stories</strong></h3>
  
  <table cellspacing="10">
    <tr>
      <td>
        <img src="citation.jpg" width="150" height="225">
      </td>
     
      
      <td>
          <p> <p><strong>"They Came From Outer Space [citation needed]"</strong> <p> <p>Forthcoming in <a href="https://www.thedreadmachine.com"><em>The Dread Machine</em></a>, TBC<p> 
        </td>
   </tr>
   </table>
   
   <table cellspacing="10">
    <tr>
         <td>
        <img src="protagonist.jpg" width="150" height="225">
      </td>
      <td>
<p> <p><strong>"What To Do When A Protagonist Visits Your Generic Village"</strong> <p> <p>Forthcoming in <a href="https://twitter.com/fandsf"><em>The Magazine of Fantasy and Science Fiction</em></a>, July/August 2023 <p>
      </td>
    </tr>
  </table>
  
  
     <table cellspacing="10">
    <tr>
      <td>
        <img src="bound.jpg" width="150" height="225">
      </td>
      <td>
          <p> <p><strong>"Bound"</strong> <p> <p>Forthcoming in <a href="https://grendelpress.com"><em>Uncanny & Unearthly Tales</em></a>, a <em>Grendel Press</em> anthology, TBC 2023<p> 
        </td>
    </tr>
  </table>
   
   
   <table cellspacing="10">
    <tr>
      <td>
        <img src="ellipsism.jpg" width="150" height="225">
      </td>
      <td>
          <p> <p><strong>"Ellipsism"</strong> <p> <p>Forthcoming in <a href="https://kaleidotrope.net"><em>Kaleidotrope</em></a>, TBC 2024<p> 
        </td>
    </tr>
  </table>
  
  
  <script>
// Script to open and close sidebar
function w3_open() {
    document.getElementById("mySidebar").style.display = "block";
    document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
    document.getElementById("mySidebar").style.display = "none";
    document.getElementById("myOverlay").style.display = "none";
}
</script>
  
  


</div>
</body>
</html>
