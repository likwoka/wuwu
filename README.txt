A GAE version of my homepage.

TODO:
1) Use iUI
2) Do a gmail client?
3) Track my portfolio (can use scheduler to update holdings..etc)
4) Track house hunting effort (ie, do a RSS feed for mls.ca)
4a) Save house hunting portfolio

5) The dream flickr: black background, flickriver/facebook keyboard shortcut, big picture
6) A read/write web folder


This is an experiment with HTML 5, Javascript, and of course GAE.


HTML 5:
1) Canvas (draw graphs ... animation is hard though)
2) SQL database
3) Offline Cache
4) Web Worker
5) Video
6) Geo location

<html>
 <head>
  <script type="application/x-javascript">
    function draw() {
      var canvas = document.getElementById("canvas");
      if (canvas.getContext) {
        var ctx = canvas.getContext("2d");

        ctx.fillStyle = "rgb(200,0,0)";
        ctx.fillRect (10, 10, 55, 50);

        ctx.fillStyle = "rgba(0, 0, 200, 0.5)";
        ctx.fillRect (30, 30, 55, 50);
      }
    }
  </script>
 </head>
 <body onload="draw();">
   <canvas id="canvas" width="150" height="150"></canvas>
 </body>
</html>

7) Google Notes Super (use Django, javasript/JQuery, GoogleGear for offline support; allow posting link which make a copy of the page and images)
Google notes are done.

8) Radio Station (Kamaelia backend, Django frontend?)

9) MLS.CA Super (greasemonkey)
- keep track of sale data in an area?

10)Warranty database (Django, a place to enter thing, warranty date, where it is stored, contact method ... then add web crawling later)

11) wuwu.ws django (http://p1k3.com/, Ryan Tomayko, Prilgrim)

12) Toronto Weather Shootout
http://www.citynews.ca/weather/weather.aspx
http://www.theweathernetwork.com/weather/caon0696
http://www.weatheroffice.gc.ca/city/pages/on-143_metric_e.html
