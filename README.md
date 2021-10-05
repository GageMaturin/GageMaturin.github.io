<!DOCTYPE HTML>
<html>
    <head>
        <title>Gage's Awesome Website</title>
        <style>
            body {
                background: rgb(196, 37, 217);
                color: rgb(0, 0, 0);
                padding: 10px;
                font-family: arial;
            }
            #all-contents {
                max-width: 800px;
                margin: auto;
            }
            /* navigation menu */
            nav {
                background: rgb(239, 80, 41);
                margin: 0 auto;
                margin-bottom: 30px;
                display: flex;
                padding: 15px;
            }
            h1 {
                display: flex;
                align-items: center;
                color: black;
                flex: 1;
                margin: 0;
            }
            #nav-ul {
                list-style-image: none;
            }
            .nav-li {
                display: inline-block;
                padding: 0 10px;
            }
            a {
                text-decoration: none;
                color: rgb(0, 0, 0);
            }
            /* main container area beneath menu */
            main {
                background: rgb(216, 203, 203);
                display: flex;
            }
            .sidebar {
                margin-right: 25px;
                padding: 10px;
            }
            .sidebar-img {
                width: 200px;
            }
            .content {
                flex: 1;
                padding: 5px;
            }
            #interests {
                border: 4px silver ridge;
                padding: 8px;
            }
            h2, h3 {
                margin: 0px;
            }
        </style>
    </head>
    <body>
        <!-- All content goes here -->
        <div id="all-contents">
            ...
            <nav>
                <h1>Gage's Awesome Website</h1>
                <ul id="nav-ul">
                    <li class="nav-li">
                      <a href="index.html"> Home </a>
                    </li>
                    <li class="nav-li">
                      <a href="portfolio.html"> Portfolio </a>
                    </li>
                </ul>
            </nav>
            <main>
                <!-- Sidebar section -->
                <div id="sidebar">
                        <img src=https://pyxis.nymag.com/v1/imgs/bb2/701/c4787eccc4a76307518ae0632fb9196faa-rick-and-morty.rsquare.w300.jpg
                </div>
                <!-- Content section -->
                <div class="content">
                    <h2>Gage Maturin</h2>
                        <p>Student at Mandeville High</p>
                        <!-- Interests section -->
                        <div id="interests">
                            <h3>Interests</h3>
                            <ul>
                                <li>Drawing</li>
                                <li>Gaming</li>
                                <li>Fishing</li>
                            </ul>
                        </div>
                </div>
            </main>
        </div>
    </body>
</html>

