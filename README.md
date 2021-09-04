# ahaanverma.github.io
Intro to DIgital Fabrication - Ahaan Verma
<!DOCTYPE html>
<html lang="en">
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">
<style>
body,h1,h2,h3,h4,h5 {font-family: "Poppins", sans-serif}
body {font-size:16px;}
.w3-half img{margin-bottom:-6px;margin-top:16px;opacity:0.8;cursor:pointer}
.w3-half img:hover{opacity:1}
</style>
<body>

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-red w3-collapse w3-top w3-large w3-padding" style="z-index:3;width:300px;font-weight:bold;" id="mySidebar"><br>
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-button w3-hide-large w3-display-topleft" style="width:100%;font-size:22px">Close Menu</a>
  <div class="w3-container">
    <h3 class="w3-padding-64"><b>Digital<br>Fabrication<br>by Ahaan Verma</b></h3>
  </div>
  <div class="w3-bar-block">
    <a href="#" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Title</a> 
      <a href="#showcase" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Portfolio</a> 
    <a href="#services" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">About Me</a> 
    <a href="#designers" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Week 1</a> 
    <a href="#packages" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Week 2</a> 
    <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Week 3</a>
    <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Week 4</a>
    <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Week 5</a>
    <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Week 6</a>
  </div>
</nav>

<!-- Top menu on small screens -->
<header class="w3-container w3-top w3-hide-large w3-red w3-xlarge w3-padding">
  <a href="javascript:void(0)" class="w3-button w3-red w3-margin-right" onclick="w3_open()">☰</a>
  <span>Company Name</span>
</header>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:340px;margin-right:40px">

  <!-- Header -->
  <div class="w3-container" style="margin-top:80px" id="showcase">
    <h1 class="w3-jumbo"><b>INTRO TO DIGIFAB</b></h1>
    <h1 class="w3-xxxlarge w3-text-red"><b>Portfolio.</b></h1>
    <hr style="width:50px;border:5px solid red" class="w3-round">
  </div>
  
  <!-- Photo grid (modal) -->
  <div class="w3-row-padding">
    <div class="w3-half">
      <img src="/w3images/kitchenconcrete.jpg" style="width:100%" onclick="onClick(this)" alt="Concrete meets bricks">
      <img src="/w3images/livingroom.jpg" style="width:100%" onclick="onClick(this)" alt="Light, white and tight scandinavian design">
      <img src="/w3images/diningroom.jpg" style="width:100%" onclick="onClick(this)" alt="White walls with designer chairs">
    </div>

    <div class="w3-half">
      <img src="/w3images/atrium.jpg" style="width:100%" onclick="onClick(this)" alt="Windows for the atrium">
      <img src="/w3images/bedroom.jpg" style="width:100%" onclick="onClick(this)" alt="Bedroom and office in one space">
      <img src="/w3images/livingroom2.jpg" style="width:100%" onclick="onClick(this)" alt="Scandinavian design">
    </div>
  </div>

  <!-- Modal for full size images on click-->
  <div id="modal01" class="w3-modal w3-black" style="padding-top:0" onclick="this.style.display='none'">
    <span class="w3-button w3-black w3-xxlarge w3-display-topright">×</span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
      <img id="img01" class="w3-image">
      <p id="caption"></p>
    </div>
  </div>

  <!-- About Me -->
  <div class="w3-container" id="services" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-red"><b>About Me.</b></h1>
    <hr style="width:50px;border:5px solid red" class="w3-round">
    <p>My name is Ahaan Verma and I'm from Mumbai India. And I'm a freshman attending Wheaton College!</p>
    <p>I was born in 2002 In glendale CA, but moved back to India and have grown up there. I love to play soccer (I'm trying out for varsity), cricket, play video games and 3D print. That's actually one of the reasons I chose this class! Also, I have a pug called coco back home and I miss him very much :(. So yeah that's me.
    </p>
    <img src=https://www.bdsomaniinternationalschool.com/wp-content/uploads/2019/11/liga-011.jpg alt="Ahaan Singhania"
  </div>
  
  <!-- Designers -->
  <div class="w3-container" id="designers" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-red"><b>Week 1 - Making a Website</b></h1>
    <hr style="width:50px;border:5px solid red" class="w3-round">
    <p>The first task in the Digital Fabrication course</p>
    <p>We were tasked with making our own website this week in order to upload all our forthcoming assignments on this website. Initially, I didn't know anything about coding, but slowly learned to code with the help of VSC (Visual Studio Code) and 
    <a href= "https://generalassembly.wistia.com/medias/x8e1j7uuet">General Assembly.</a> 
    </p>
    <p><b>The images of the processes used and techniques used to help me in creating this website</b>:</p>
  </div>

  <!-- The Team -->
  <div class="w3-row-padding w3-grayscale">
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <img src="https://lh3.googleusercontent.com/DeUVb_bYcYv3ESD7oLXkvtwSOdGsfzIpK1BX4mOr_qbItUzTOIVdODkrhUlmWE_9muV_9l3lwxLQdR8bVd9YfJ2zHajW0mTkoLYooO_1cE-v_4jYKcnrM56D0o29Z-I3Tpf___64=w2400" alt"coding" style="width:100%">
        <div class="w3-container">
          <h3>General Assebmbly</h3>
          <p class="w3-opacity"></p>
          <p>I used this video to learn basic html codes and ways to create code.</p>
        </div>
      </div>
    </div>
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <img src="https://lh3.googleusercontent.com/gOzT4rlGDyR4rw095vkooMy94egJJQ2ijBhCU3kSmOWUeUfpadN1Rnyt72m1pBhPnHBqXtr2NJtJL738BVa4fhMevBm0DBPq-ZBLMgaSC7KVP5tCMBx8oNNXCihjfpaJq_BBgtey=w2400" alt="anchoring code" style="width:100%">
        <div class="w3-container">
          <h3>anchoring code html</h3>
          <p class="w3-opacity"></p>
          <p>I used these anchoring codes to create hyperlinks outside my website to acknowledge where I have gotten all my infdormation from.</p>
        </div>
      </div>
    </div>
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <img src="https://lh3.googleusercontent.com/ur_a3OZw8DAojzbXYNE9CJzJs7AwcP0r7OskMqNPduWQX7p73X_bTGHCNCKwiEzf654B6i2S1nSF310YSxKh3Cvm6mcxsMPDsU62MIgYB2GKihdEglM9BkqOpGUsmE-Bc0g-8q_L=w2400" alt="Madison Dunaway Website" style="width:100%">
        <div class="w3-container">
          <h3>Madison Dunaway's website</h3>
          <p class="w3-opacity"></p>
          <p><a href= "https://mkdunaway.github.io"> Madison's website</a> got me started and directed me with various helpful resources to get the website up and running.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Packages / Pricing Tables -->
  <div class="w3-container" id="packages" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-red"><b>Week 2.</b></h1>
    <hr style="width:50px;border:5px solid red" class="w3-round">
    <p></p>
  </div>

 
    
  
  <!-- Contact -->
  <div class="w3-container" id="contact" style="margin-top:75px">
  <h1 class="w3-xxxlarge w3-text-red"><b>Week 3.</b></h1>
  <hr style="width:50px;border:5px solid red" class="w3-round">
  <p></p>
    
    <!-- Week 4 -->
    
   <div class="w3-container" id="contact" style="margin-top:75px">
   <h1 class="w3-xxxlarge w3-text-red"><b>Week 4.</b></h1>
   <hr style="width:50px;border:5px solid red" class="w3-round">
   <p></p>
    
    <!-- Week 5 --> 
    
   <div class="w3-container" id="contact" style="margin-top:75px">
   <h1 class="w3-xxxlarge w3-text-red"><b>Week 5.</b></h1>
   <hr style="width:50px;border:5px solid red" class="w3-round">
   <p></p>
    

<!-- End page content -->
</div>

<!-- W3.CSS Container -->
<div class="w3-light-grey w3-container w3-padding-32" style="margin-top:75px;padding-right:58px"><p class="w3-right">Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-opacity">w3.css</a></p></div>

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

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}
</script>

</body>
</html>
