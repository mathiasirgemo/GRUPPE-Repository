Flaggoppgaven

### Canvasflagg.html
<!DOCTYPE html>
<html lang="no-NB">
<head>
   <meta charset="UTF-8">
   <title>Muritius-Nasjonalflagg</title>
</head>
<body>
   <canvas id="canvas" width="900px" height="600" style="margin-top:150px; margin-left: 25%;"></canvas>
   <script>

      //getElementById tar elementet fra html basert på ID
      //getContext sier noe om hvordan utformingen skal være
const canvas = document.getElementById("canvas");
const ctx = canvas.getContext("2d");

//fillStyle setter farge på området
//fillRect setter området som skal farges

ctx.fillStyle = "#D01C1F";
ctx.fillRect(0, 0, 900, 150);
ctx.fillStyle = "#2D3347";
ctx.fillRect(0, 150, 900, 150);
ctx.fillStyle = "#F7B718";
ctx.fillRect(0, 300, 900, 150);
ctx.fillStyle ="#008614";
ctx.fillRect(0, 450, 900, 150);

   </script>
</body>
</html>
Rapport

