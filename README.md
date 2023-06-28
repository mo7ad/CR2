# CR2
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <link rel="stylesheet" href="css/style.css">
            <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
            <title>Document</title>
            <style>
                #sortButton {
                display: block;
                margin: 0 auto;
                text-align: center;
                margin-bottom: 20px;
                }
                .row {                
                padding-top: var(--main-padding-top);
                padding-bottom: var(--main-padding-bottom);
                position: relative;
                background-color: #eeeeee54;
                border-radius: 80px;
                }
                
                </style>
                
        </head>
        <body>
            <nav class="navbar navbar-expand-md ">
                <div class="container-fluid">
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
                    <a class="navbar-brand text-info" href="#">Alrifaie</a>
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#go-down">Tasks</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#footer">Footer</a>
                    </li>
                    <!-- <li class="nav-item">
                        <a class="nav-link disabled">Disabled</a>
                    </li> -->
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                        Dropdown link
                        </a>
                        <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Action</a></li>
                        <li><a class="dropdown-item" href="#">Another action</a></li>
                        <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>
                    </ul>
                    <form class="d-flex" role="search">
                    <input class="form-control me-2" type="search" placeholder="Write Hire" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit">Subscribe</button>
                    </form>
                </div>
                </div>
            </nav>
            <div class="svg">
            <svg  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#a2d9ff" fill-opacity="1"  d="M0,320L120,298.7C240,277,480,235,720,229.3C960,224,1200,256,1320,272L1440,288L1440,0L1320,0C1200,0,960,0,720,0C480,0,240,0,120,0L0,0Z"></path></svg>
            <span id="title">Weekly Planner</span>
        </div>

            <main class="mainImg">
                <img src="../media/checklisti.png"  alt="">
                </main>
                <div class="arrow">
                    <a href="#go-down"><img src="../media/arrow.png" alt=""></a>
        </div>
        <article>
            <div id="go-down">
                <h2>Weekly Tasks</h2>
            </div>
        </article>
        
        <div class="container">
            <button id="sortButton" class="btn btn-primary">Sort</button>
            <div class="row row-cols-lg-3 row-cols-md-2 row-cols-sm-1 justify-content-center" id="result">
        </div>
            </div>
        
        
        <footer id="footer" class="footer">
            <div class="foot-link">
                <a href="#" target="_blank">About</a>
                <a href="#" target="_blank">|About Us</a>
                <a href="#">|FAQ</a>
                <a href="#" target="_blank">|Contact Us</a>
            </div>

            <div class="social">
                <a href="http://facebook.com" target="_blank" title="go to facebook"><img src="media/face.png" alt=""></a>
                <a href="http://instgram.com" target="_blank" title="go to instagram"><img src="media/inst.png" alt=""></a>
                <a href="http://twitter.com" target="_blank" title="go to twitter"><img src="media/twit.png" alt=""></a>
            </div>
            
            <div class="copy">
                <p>&copy; <b>Alrifaie Mohammad</b></p>
            </div>
        </footer>
        <script src="/js/script.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script> 
        </body>
        </html>
