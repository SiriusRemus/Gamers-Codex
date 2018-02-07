<!DOCTYPE html>
<html>
<title>The Gamers Codex</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif;}
body, html {
    height: 100%;
    color: #777;
    line-height: 1.8;
}

/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3 {
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

/* First image (Logo. Full height) */
.bgimg-1 {
    background-image: url("https://images7.alphacoders.com/594/thumb-1920-594320.jpg");
    min-height: 100%;
}

/* Second image (Games) */
.bgimg-2 {
    background-image: url("https://images7.alphacoders.com/594/thumb-1920-594320.jpg");
    min-height: 400px;
}

/* Third image (Movie) */
.bgimg-3 {
    background-image: url("https://images7.alphacoders.com/594/thumb-1920-594320.jpg");
    min-height: 400px;
}

.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}

/* Turn off parallax scrolling for tablets and phones */
@media only screen and (max-device-width: 1024px) {
    .bgimg-1, .bgimg-2, .bgimg-3 {
        background-attachment: scroll;
    }
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar" id="myNavbar">
    <a class="w3-bar-item w3-button w3-hover-black w3-hide-medium w3-hide-large w3-right" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
      <i class="fa fa-bars"></i>
    </a>
    <a href="#home" class="w3-bar-item w3-button">HOME</a>
    <a href="#about" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-user"></i> SERVERS</a>
    <a href="#portfolio" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-th"></i> GAMES</a>
    <a href="#contact" class="w3-bar-item w3-button w3-hide-small"><i class=""></i> MOVIES</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-right w3-hover-red">
      <i class="fa fa-search"></i>
    </a>
  </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium">
    <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">ABOUT</a>
    <a href="#portfolio" class="w3-bar-item w3-button" onclick="toggleFunction()">GAMES</a>
    <a href="#contact" class="w3-bar-item w3-button" onclick="toggleFunction()">MOVIES</a>
    <a href="#" class="w3-bar-item w3-button">SEARCH</a>
  </div>
</div>

<!-- First Parallax Image with Logo Text -->
<div class="bgimg-1 w3-display-container w3-opacity-min" id="home">
  <div class="w3-display-middle" style="white-space:nowrap;">
    <span class="w3-center w3-padding-large w3-black w3-xlarge w3-wide w3-animate-opacity">THE <span class="w3-hide-small">GAMERS</span> CODEX</span>
  </div>
</div>

<!-- Container (About Section) -->
<div class="w3-content w3-container w3-padding-64" id="about">
  <h3 class="w3-center">ABOUT THE SITE</h3>
  <p class="w3-center"><em>Do you like Games?</em></p>
  <p>We have created a Website to keep you updated on the new games every one is going after this the past year or Even his year! For Example Fortnight is a new big one every one likes to play.. An we dont stop at Games, we even Do moive revios and give you Help on were you are stuck in the games!</p>
  <div class="w3-row">
    <div class="w3-col m6 w3-center w3-padding-large">
      <p><b><i class="fa fa-user w3-margin-right"></i>Christina L.</b></p><br>
      <img src="https://scontent.fmkc2-1.fna.fbcdn.net/v/t1.0-9/15823507_1526840267330663_4040582100130804464_n.jpg?oh=99738b15914a53a16168d6646469bc29&oe=5AEA6140" class="w3-round w3-image w3-opacity w3-hover-opacity-off" alt="Photo of Me" width="500" height="333">
    </div>

    <!-- Hide this text on small devices -->
    <div class="w3-col m6 w3-hide-small w3-padding-large">
      <p>Welcome to the Gamers Codex, to be far warned the website is still being worked on!</p>
    </div>
  </div>
<div class="w3-row w3-center w3-dark-grey w3-padding-16">
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">1000+</span><br>
    Games
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">1000+</span><br>
    Servers
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">100+</span><br>
    Movies Reveiws
  </div>
    
  </div>
</div>

<!-- Second Parallax Image with Portfolio Text -->
<div class="bgimg-2 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
    <span class="w3-xxlarge w3-text-white w3-wide">GAMES</span>
  </div>
</div>

<!-- Container (Portfolio Section) -->
<div class="w3-content w3-container w3-padding-64" id="portfolio">
  <h3 class="w3-center">Top games:</h3>
  <p class="w3-center"><em>Here are some of the games people are going crazy for!</em></p><br>

  <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
  <div class="w3-row-padding w3-center">
    <div class="w3-col m3">
      <a href="https://playoverwatch.com/en-us/"> OverWatch</a> <img src="https://buzzazz.com/wp-content/uploads/2016/05/Overwatch.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="OverWatch">
      </a> Team-based multiplayer online first-person shooter</a>
    </div>

    <div class="w3-col m3">
    <a href="https://www.epicgames.com/fortnite/en-US/buy-now/battle-royale"> <img src="https://www.gamepur.com/files/images/2014/battle-royale-tips.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Fortnite">
    </a> co-op sandbox survival video game</a>
    </div>

    <div class="w3-col m3">
    <a href= "https://worldofwarcraft.com/en-us/"> World Of Warcraft </a> <img src="https://i.ytimg.com/vi/Q3RG9vz7c8g/maxresdefault.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="World of warcraft">
     </a>World of Warcraft is a massively multiplayer online role-playing game 
      </div>

    <div class="w3-col m3">
      <img src="http://mtxuk.co.uk/wp-content/uploads/2014/03/dayz.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Dayz">
    </div>

  <div class="w3-row-padding w3-center w3-section">
    <div class="w3-col m3">
      <img src="https://cdn.downdetector.com/static/uploads/c/300/b48ba/Runescape_3_Logo.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Runescape">
    </div>

    <div class="w3-col m3">
      <img src="http://www.mjga.ca/wp-content/uploads/2013/05/neverwinter-logo.png?scrlybrkr" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="NeverWinter">
    </div>

    <div class="w3-col m3">
      <img src="http://www.justpushstart.com/wp-content/uploads/2014/04/The-Elder-Scrolls-Online-Logo.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="The Elder Scrolls Online">
    </div>

    <div class="w3-col m3">
      <img src="https://eteknix-eteknixltd.netdna-ssl.com/wp-content/uploads/2017/07/1a-4-800x300.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Player Ground Unkown">
    </div>
    <button class="w3-button w3-padding-large w3-light-grey" style="margin-top:64px">LOAD MORE</button>
  </div>
</div>

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-large w3-black w3-display-topright" title="Close Modal Image"><i class="fa fa-remove"></i></span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- Third Parallax Image with Portfolio Text -->
<div class="bgimg-3 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
     <span class="w3-xxlarge w3-text-white w3-wide">MOVIES</span>
  </div>
</div>


<!-- Movie Container (Contact Section) -->
<div class="w3-content w3-container w3-padding-64" id="portfolio">
  <h3 class="w3-center">The Movies that are hot:</h3>
  <p class="w3-center"><em>Here are some of the movies that we think you would like!</em></p><br>
 <div class="w3-row-padding w3-center">
    <div class="w3-col m3">
    
      <img src="https://usercontent1.hubstatic.com/13519958.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Logan">
      </a>Logan</a>
      <a href =>
    </div>

    <div class="w3-col m3">
      <img src="http://t2.gstatic.com/images?q=tbn:ANd9GcRgcIU4MKHZkZNeDt_tAewyfwX7PAmSdj_7wdg_FInkZw8Um9F_" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Star Wars: The Last Jedi">
      </a>Star Wars: The Last Jedi</a>
      <a href ="https://www.youtube.com/watch?v=Q0CbN8sfihY">
    </div>

    <div class="w3-col m3">
      <img src="http://t1.gstatic.com/images?q=tbn:ANd9GcTALjGaaCwNAfgH2Fa0jVpp2mEOhGRRw1v0lkRrHlUtXyKW0buX" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="It">
      </a>It (2017 film)</a>
    </div>

    <div class="w3-col m3">
      <img src="http://t3.gstatic.com/images?q=tbn:ANd9GcQ9X6j4i6DrRVFaT9U3QmJJIrOnlNpQDvMc96SNGE1yVe_M_gla" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Alien: Covenant">
      </a>Alien: Covenant</a>
    </div>
  </div>

  <div class="w3-row-padding w3-center w3-section">
    <div class="w3-col m3">
      <img src="http://t0.gstatic.com/images?q=tbn:ANd9GcQXQ66_-tErPgqEkMUts-hfi5KFvyf-yO77hE5OBHXKvvq1EoV7" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Downsizing">
      </a>Downsizing</a>
    </div>

    <div class="w3-col m3">
      <img src="http://t2.gstatic.com/images?q=tbn:ANd9GcQwPz1BaxQrIzlQSAo0zVYIW8lXGFJQPXt7wCkicMrqBBPl8xih" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Wonder">
      </a>Wonder</a>
    </div>

    <div class="w3-col m3">
      <img src="http://t3.gstatic.com/images?q=tbn:ANd9GcST1uigGrukMvSAVUefFNuQ0NMZAR-FjfFIwSZFCR5ZkyMSgCyj" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Thor: Ragnarok">
      </a>Thor: Ragnarok</a>
    </div>

    <div class="w3-col m3">
      <img src="http://t0.gstatic.com/images?q=tbn:ANd9GcT8W3Fe7DD101g0M7OCalJN9u675sQAJFslGCjvs74PTOfEKt_t" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Spider-Man: Homecoming">
      </a>Spider-Man: Homecoming</a>
    </div>
    <button class="w3-button w3-padding-large w3-light-grey" style="margin-top:64px">LOAD MORE</button>
  </div>
</div>

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-large w3-black w3-display-topright" title="Close Modal Image"><i class="fa fa-remove"></i></span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>
 
<!-- Add Google Maps -->
<script>
function myMap()
{
  myCenter=new google.maps.LatLng(41.878114, -87.629798);
  var mapOptions= {
    center:myCenter,
    zoom:12, scrollwheel: false, draggable: false,
    mapTypeId:google.maps.MapTypeId.ROADMAP
  };
  var map=new google.maps.Map(document.getElementById("googleMap"),mapOptions);

  var marker = new google.maps.Marker({
    position: myCenter,
  });
  marker.setMap(map);
}

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}

// Change style of navbar on scroll
window.onscroll = function() {myFunction()};
function myFunction() {
    var navbar = document.getElementById("myNavbar");
    if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
        navbar.className = "w3-bar" + " w3-card" + " w3-animate-top" + " w3-white";
    } else {
        navbar.className = navbar.className.replace(" w3-card w3-animate-top w3-white", "");
    }
}

// Used to toggle the menu on small screens when clicking on the menu button
function toggleFunction() {
    var x = document.getElementById("navDemo");
    if (x.className.indexOf("w3-show") == -1) {
        x.className += " w3-show";
    } else {
        x.className = x.className.replace(" w3-show", "");
    }
}
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBu-916DdpKAjTmJNIgngS6HL_kDIKU0aU&callback=myMap"></script>
<!--
To use this code on your website, get a free API key from Google.
Read more at: https://www.w3schools.com/graphics/google_maps_basic.asp
-->

</body>
</html>
