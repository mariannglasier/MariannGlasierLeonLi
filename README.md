<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Piet Mondrian 3D Space</title>
    <meta name="description" content="A-Frame Piet Mondrian 3D Space">
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-entity position="0 1.6 0">
        <a-camera></a-camera>
      </a-entity>


      <!-- Lines in front -->
      <a-plane position=".2 1.1 -3" rotation="0 0 0" color="#000000" height="0.1" width="3.75"></a-plane>
      <a-plane position="2.1 2.4 -3" rotation="0 0 90" color="#000000" height="0.1" width="3.5"></a-plane>
      <a-plane position="2.4 2.8 -3" rotation="0 0 0" color="#000000" height="0.1" width=".7"></a-plane>
      <a-plane position="0 4.1 -3" rotation="0 0 0" color="#000000" height="0.1" width="5.5"></a-plane>
      <a-plane position="-1.65 3 -3" rotation="0 0 90" color="#000000" height="0.1" width="4.7"></a-plane>
      <a-plane position="-2.8 3 -3" rotation="0 0 90" color="#000000" height="0.1" width="4.7"></a-plane>
      <a-plane position="2.8 3 -3" rotation="0 0 90" color="#000000" height="0.1" width="4.7"></a-plane>
      <a-plane position="0 5.3 -3" rotation="0 0 0" color="#000000" height="0.1" width="5.5"></a-plane>
      <a-plane position="0 .6 -3" rotation="0 0 0" color="#000000" height="0.1" width="5.7"></a-plane>

      <!-- Geometric shapes in front -->
      <a-box position="-2.3 4.7 -3.1" rotation="0 0 0" color="#FF0000" depth="0.1" height="1.2" width="1.2"></a-box>
      <a-box position="-.4 .75 -3.1" rotation="0 0 0" color="#FFFF00" depth="0.1" height=".5" width="2.5"></a-box>
      <a-box position="2.5 3.45 -3.1" rotation="0 0 0" color="#0000FF" depth="0.1" height="1.3" width=".6"></a-box>
      <a-box position="1.5 .75 -3.1" rotation="0 0 0" color="#000000" depth="0.1" height=".5" width="1.25"></a-box>
      <a-box position="0 0 -3.15" rotation="0 0 0" color="#FFFFFF"depth="0.1" height="20" width="20"></a-box>

      <!-- Lines on the sides -->
      <a-plane position="-2.8 2.2 0" rotation="0 90 0" color="#000000" height="0.1" width="6"></a-plane>
      <a-plane position="-2.8 2.95 .8" rotation="0 90 90" color="#000000" height="0.1" width="4.8"></a-plane>
      <a-plane position="-2.8 5.3 0" rotation="0 90 0" color="#000000" height="0.1" width="6"></a-plane>
      <a-plane position="-2.8 .6 0" rotation="0 90 0" color="#000000" height="0.1" width="6"></a-plane>
      <a-plane position="-2.8 2.95 3" rotation="0 90 90" color="#000000" height="0.1" width="4.8"></a-plane>
      <a-plane position="-2.8 1.4 -2" rotation="0 90 90" color="#000000" height="0.2" width="1.6"></a-plane>
      <a-plane position="-2.8 1.6 -2.5" rotation="0 90 0" color="#000000" height="0.2" width="1"></a-plane>
      <a-plane position="-2.8 3.85 1.9" rotation="0 90 0" color="#000000" height="0.3" width="2.2"></a-plane>

      <!-- Geometric shapes on the sides -->
      <a-box position="-2.9 3.75 -1.1" rotation="0 -90 0" color="#FF0000" depth="0.1" height="3.15" width="3.9"></a-box>
      <a-box position="-2.9 1.1 -2.6" rotation="0 -90 0" color="#FFFF00" depth="0.1" height="1" width="1"></a-box>
      <a-box position="-2.9 1.4 1.95" rotation="0 -90 0" color="#0000FF" depth="0.1" height="1.6" width="2.3"></a-box>
      <a-box position="-3 0 0" rotation="0 -90 0" color="#FFFFFF"depth="0.1" height="20" width="20"></a-box>

      <a-plane position="2.8 2.2 0" rotation="0 -90 0" color="#000000" height="0.1" width="6"></a-plane>
      <a-plane position="2.8 2.95 .8" rotation="0 -90 90" color="#000000" height="0.1" width="4.8"></a-plane>
      <a-plane position="2.8 5.3 0" rotation="0 -90 0" color="#000000" height="0.1" width="6"></a-plane>
      <a-plane position="2.8 .6 0" rotation="0 -90 0" color="#000000" height="0.1" width="6"></a-plane>
      <a-plane position="2.8 1.7 1.9" rotation="0 -90 0" color="#000000" height="0.1" width="2.2"></a-plane>
      <a-plane position="2.8 2.95 3" rotation="0 -90 90" color="#000000" height="0.1" width="4.8"></a-plane>
      <a-plane position="2.8 3.8 1.9" rotation="0 -90 0" color="#000000" height="0.1" width="2.2"></a-plane>

      <a-box position="2.9 3.8 -1.1" rotation="0 -90 0" color="#FF0000" depth="0.1" height="3.15" width="3.9"></a-box>
      <a-box position="2.9 4.6 1.95" rotation="0 -90 0" color="#FFFF00" depth="0.1" height="1.5" width="2.25"></a-box>
      <a-box position="2.9 1.1 1.95" rotation="0 -90 0" color="#0000FF" depth="0.1" height="1" width="2.2"></a-box>
      <a-box position="2.9 1.4 -2.2" rotation="0 -90 0" color="#000000" depth="0.1" height="1.6" width="1.6"></a-box>
      <a-box position="3 0 0" rotation="0 -90 0" color="#FFFFFF"depth="0.1" height="20" width="20"></a-box>

      <!-- Geometric shapes above and below -->
      <a-box position="-2.2 .4 -2" rotation="-90 0 0" color="#FFFF00" depth="0.1" height="3.5" width="2.5"></a-box>
      <a-box position="2.7 .4 .8" rotation="-90 0 0" color="#0000FF" depth="0.1" height="2" width="1.5"></a-box>
      <a-box position="0 .35 0" rotation="-90 0 0" color="#FFFFFF"depth="0.1" height="50" width="50"></a-box>

      <a-box position="3 5.4 -2.5" rotation="-90 0 0" color="#FFFF00" depth="0.1" height="2.5" width="1"></a-box>
      <a-box position="2.7 5.4 2.65" rotation="-90 0 0" color="#0000FF" depth="0.1" height="1" width="3"></a-box>
      <a-box position="-3 5.4 -2.5" rotation="-90 0 0" color="#FF0000" depth="0.1" height="2.5" width="2"></a-box>
      <a-box position="0 5.45 0" rotation="-90 0 0" color="#FFFFFF"depth="0.1" height="20" width="20"></a-box>

      <!-- Lines above and below -->
      <a-plane position="0 5.3 3" rotation="90 0 0" color="#000000" height="0.1" width="7"></a-plane>
      <a-plane position="2.4 5.3 0" rotation="90 0 90" color="#000000" height="0.1" width="7.4"></a-plane>
      <a-plane position="0 5.3 -1.2" rotation="90 0 0" color="#000000" height="0.1" width="7"></a-plane>
      <a-plane position="1 5.3 2" rotation="90 0 0" color="#000000" height="0.1" width="5.9"></a-plane>
      <a-plane position="1.15 5.3 0" rotation="90 0 90" color="#000000" height="0.1" width="7.4"></a-plane>
      <a-plane position="-1.9 5.3 0" rotation="90 0 90" color="#000000" height="0.1" width="7.4"></a-plane>
      <a-plane position="0 5.3 -2.3" rotation="90 0 0" color="#000000" height="0.1" width="7"></a-plane>
      <a-plane position="-2.4 5.3 -2.5" rotation="90 0 90" color="#000000" height="0.1" width="2.5"></a-plane>

      <a-plane position="0 .5 -.2" rotation="-90 0 0" color="#000000" height="0.1" width="7"></a-plane>
      <a-plane position="-.9 .5 0" rotation="-90 0 90" color="#000000" height="0.1" width="7.4"></a-plane>
      <a-plane position="0 .5 3.7" rotation="-90 0 0" color="#000000" height="0.1" width="7"></a-plane>
      <a-plane position="2.7 .5 1.8" rotation="-90 0 0" color="#000000" height="0.2" width="1.7"></a-plane>
      <a-plane position="1.9 .5 1.8" rotation="-90 0 90" color="#000000" height="0.1" width="3.9"></a-plane>
      <a-plane position=".5 .5 2.7" rotation="-90 0 0" color="#000000" height="0.1" width="2.9"></a-plane>

      <!-- Geometric shapes and lines behind -->
      <a-box position="1.3 5.1 3.1" rotation="0 0 0" color="#FF0000" depth="0.1" height=".5" width="3"></a-box>
      <a-box position="-2.3 2 3.1" rotation="0 0 0" color="#FFFF00" depth="0.1" height="3" width="1"></a-box>
      <a-box position=".7 2.75 3.1" rotation="0 0 0" color="#0000FF" depth="0.1" height="1.5" width="1.8"></a-box>
      <a-box position="0 0 3.2" rotation="0 0 0" color="#FFFFFF"depth="0.1" height="20" width="20"></a-box>
      <a-box position="-2.35 5.1 3.1" rotation="0 0 0" color="#000000" depth="0.1" height=".5" width="1.1"></a-box>

      <a-plane position=".7 2 3" rotation="0 180 0" color="#000000" height="0.1" width="1.8"></a-plane>
      <a-plane position="0 3.5 3" rotation="0 180 0" color="#000000" height="0.1" width="5.6"></a-plane>
      <a-plane position="-2.25 4.3 3" rotation="0 180 0" color="#000000" height="0.1" width="1.1"></a-plane>
      <a-plane position="-1.7 2.95 3" rotation="0 180 90" color="#000000" height="0.1" width="4.65"></a-plane>
      <a-plane position="-.2 2.95 3" rotation="0 180 90" color="#000000" height="0.1" width="4.65"></a-plane>
      <a-plane position="1.6 2.1 3" rotation="0 180 90" color="#000000" height="0.1" width="2.9"></a-plane>
      <a-plane position="1.3 4.8 3" rotation="0 180 0" color="#000000" height="0.1" width="3"></a-plane>
      <a-plane position="0 .6 3" rotation="0 180 0" color="#000000" height="0.1" width="5.6"></a-plane>

    </a-scene>
  </body>
</html>
