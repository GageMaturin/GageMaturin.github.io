<!DOCTYPE HTML>
<html>
    <head>
        <title>Gage's Awesome Website</title>
          <style type="text/css">
           body {
                background: rgb(196, 37, 217);
                color: rgb(45, 45, 45);
                padding: 10px;
               font-family: arial;
           }
           header {
               font-size: 1.5em;
               font-weight: bold;
           }
           #all-contents {
               max-width: 800px;
               margin: auto;
           }
            /* navigation menu */
            nav {
                background: rgb(239, 80, 41);
                margin: 0 auto;
                display: flex;
                padding: 10px;
            }
            h1 {
                display: flex;
                align-items: center;
                color: rgb(255, 255, 255);
                flex: 1;
            }
            #nav-ul {
                list-style-image: none;
            }
            .nav-li {
                display: inline-block;
                padding: 0 10px;
            }
            .nav-a {
                text-decoration: none;
                color: black;
            }
            /* main container area beneath menu */
            main {
                background: rgb(216, 203, 203);
                display: flex;
            }
            .content {
                flex: 1;
                padding: 15px;
            }
                        /* portfolio styles */
            .content h1 {
                color: black;
            }
            #portfolio {
                list-style-type: none;
                padding-left: 0;
            }
            #portfolio li {
                background: #fff;
                padding: 10px;
                border-radius: 10px;
                margin-bottom: 10px;
            }
            #portfolio li:hover {
                background: #eee;
            } 
            #portfolio a {
                text-decoration: none;
                color: #454545;
            }
        </style>
    </head>
    <body>
      <div id="all-contents">
        <nav>
            <h1>Gage's Awesome Website</h1>
            <ul id="nav-ul">
                <li class="nav-li">
                  <a class="nav-a" href="index.html">Home</a>
                </li>
                <li class="nav-li">
                  <a class="nav-a" href="portfolio.html">Portfolio</a>
                </li>
            </ul>
        </nav>
        <main>
            <div class="content">
                <h1>Portfolio</h1>
                <ul id="portfolio">
                  <li><a href="projects/platformer/">Platformer : A cannon - dodging, collectible - grabbing adventure game for Halleb0t</a></li>
                  <li><a href="projects/bouncing-box/">Bouncing Box : A project that gives you a taste of game development on the web </a></li>
                  <li><a href="projects/circularity/">Circularity : A motion poem using random number generation and velocity applied to circle shapes...</a></li>
                </ul>
            </div>
        </main>
      </div>
    </body>
</html>

