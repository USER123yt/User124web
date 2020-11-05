Welcome!

<!DOCTYPE html>
<html>
<body>

<body style = "text-align:center;">

<h2>US£R_124</h2>
<img src="images" alt="US3R" width="500" height="600">
<p>Discord</p>
<a href="https://discord.gg/B3yJcFY">My discord</a>
<p>Twitter</p>
<a href="https://twitter.com/User12418226185">My Twitter</a>
<p>Instagram</p>
<a href="https://www.instagram.com/user124_yt/">My Instagram</a>
<P>Subscribe to Gamers channel -</p>
<a href="https://www.youtube.com/channel/UC851xC5_v-0AsiCuk_MJlHA">Gamers Channel</a>
          
        <p id = "GFG_UP" style = 
            "font-size: 16px; font-weight: bold;">      
        </p> 
          
        <button onclick = "gfg_Run()">  
            Dark mode
        </button> 
          
        <p id = "GFG_DOWN" style = 
            "color:green; font-size: 20px; font-weight: bold;"> 
        </p> 
          
        <script> 
            var el_up = document.getElementById("GFG_UP"); 
            var el_down = document.getElementById("GFG_DOWN"); 
            var str = "Click on the button for Dark mode"; 
          
            el_up.innerHTML = str; 
          
            function changeColor(color) { 
                document.body.style.background = color; 
            } 
              
            function gfg_Run() { 
                changeColor('Black'); 
                el_down.innerHTML = "Done!"; 
            }
        </script>  
</body>
</html>
