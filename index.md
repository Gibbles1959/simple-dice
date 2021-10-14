<!DOCTYPE html>
<html>
    <head><link href="styles.css" rel = "stylesheet"> <title>Dice Roller v0.0.1</title></head>
    <body>
        <h1>Dice Roller</h1>
        <p class="text1">Simple 6 Sided Die Roller made by Clint Gibbs on 14/10/21</p>
        <p class="text2">Click button or refresh page to roll again! <br> <button onClick="window.location.reload();">Roll Again</button></p>
        <script> const now = new Date();
         console.log("JavaScript is active. . ."); 
        var Dice = Math.floor(Math.random() * 6) + 1; 
        console.log(Dice);
        setTimeout(function(){ alert("You rolled a " + Dice);  }, 100);
        
        </script>  
        <a href="https://github.com/Gibbles1959/simple-dice" target="_blank"><img alt="GitHub" src="https://cdn.afterdawn.fi/v3/news/original/github-logo.png" width="80" height="80"></a>
    </body>
    <footer>
        <hr>
        <script>
        document.write("You rolled the dice on " + now)
        </script>
    </footer>
</html>
