<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Szablon strony internetowej</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-F3w7mX95PdgyTmZZMECAngseQB83DfGTowi0iMjiWaeVhAn4FJkqJByhZMI3AhiU" crossorigin="anonymous">
    <link rel='stylesheet' type='text/css' media='screen' href='/main.css'>
</head>
<body>
    <main>
        <header class="sticky-top">
            <nav class="navbar navbar-expand-lg navbar-dark color-rgb-navbar">
                <div class="container">
                    <a class="navbar-brand" href="#">
                        <h3>Usługi Geodezyjne i Komputerowe</h3>
                    </a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse flex-row-reverse" id="navbarNav">
                        <ul class="navbar-nav">
                            <li class="nav-item nav-item-size">
                                <a class="nav-link active text-center" href="/index.html">
                                    <i class="fas fa-home fa-3x"></i>
                                    <div class="">Home</div>
                                </a>
                            </li>
                            <li class="nav-item nav-item-size text-center">
                                <a class="nav-link active" href="info.html">
                                    <i class="fas fa-info fa-3x"></i>
                                    <div class="">O nas</div>
                                </a>
                            </li>
                            <li class="nav-item nav-item-size">
                                <a class="nav-link active text-center" href="services.html">
                                    <i class="fas fa-chart-pie fa-3x"></i>
                                    <div class="">Usługi</div>
                                </a>
                            </li>
                            <li class="nav-item nav-item-size nav-item-border-active">
                                <a class="nav-link active text-center" href="#">
                                    <i class="fas fa-phone fa-3x"></i>
                                    <div class="">Kontakt</div>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
        </header>
        <article>
            <div class="container">
                <div class="row pad-80">
                    <div class="col">
                        <h3>Kontakt</h3>
                        <div class="special-inner-heading-border"></div>
                    </div>
                    <div class="col">
                        <h3>Jak do nas dojechać</h3>
                        <div class="special-inner-heading-border"></div>
                    </div>
                </div>
                <div class="row">
                    <div class="col text-format-contact">
                        <p>
                            USŁUGI GEODEZYJNE I KOMPUTEROWE Tomasz Wojtczak
                            <br>
                            ul. Staroprzygodzka 25
                            <br>
                            63-400 Ostrów Wielkopolski
                            <br>
                            NIP : 622-129-83-08
                        </p>
                        <p>
                            tel : 693-279-365
                            <br>
                            email : tomasz.wojtczak@poczta.fm
                        </p>
                        <p>
                            Zapraszamy do naszego biura:
                            <br>
                            ul. Staroprzygodzka 25
                        </p>
                    </div>
                    <div class="col">
                        <iframe width="420" height="450" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" id="gmap_canvas" src="https://maps.google.com/maps?width=420&amp;height=450&amp;hl=en&amp;q=ul.%20Staroprzygodzka%2025%20Ostr%C3%B3w%20Wielkopolski+()&amp;t=&amp;z=12&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"></iframe> <a href='https://www.symptoma.pl/pl/info/covid-19#info'>COVID-19</a> <script type='text/javascript' src='https://embedmaps.com/google-maps-authorization/script.js?id=ce4da1fd421ec0a10f4ce68c915e4e92e15b57ce'></script>
                    </div>
                </div>
                <div class="row">
                    <div class="col mrg-top"></div>
                </div>
            </div>
        </article>
        <footer>
            <div class="parallax-effect position-relative" style="background-image: url(/assets/parralax/parallax-1.jpg); height: 500px;">
                <div class="footer-section position-absolute bottom-0 start-50 translate-middle-x w-100">
                    <div class="container text-center">
                        <div class="row m-0 p-2">
                            <div class="col">
                                <h5>Kontakt</h5>
                                <p>
                                    tel : 693-279-365
                                    <br>
                                    email : tomasz.wojtczak@poczta.fm
                                </p>
                            </div>
                            <div class="col-1">
    
                            </div>
                            <div class="col">
                                <h5>Adres</h5>
                                <p>
                                    USŁUGI GEODEZYJNE I KOMPUTEROWE Tomasz Wojtczak
                                    <br>
                                    ul. Staroprzygodzka 25
                                    <br>
                                    63-400 Ostrów Wielkopolski
                                    <br>
                                    NIP : 622-129-83-08
                                </p>
                                <p>
                                    Zapraszamy do naszego biura:
                                    <br>
                                    ul. Staroprzygodzka 25
                                </p>
                            </div>
                        </div>
                        <div class="row m-0 p-2">
                            <div class="col"></div>
                        </div>
                        <div class="row m-0 p-3">
                            <div class="col text-center">
                                <a href="pdf/RODO.pdf">RODO</a>
                            </div>
                            <div class="col text-end">
                                <p>&copy; 2021 TheN3RO, all rights reserved.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </footer>
    </main>
    <script src="https://kit.fontawesome.com/875e35017f.js" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-/bQdsTh/da6pkI1MST/rWKFNjaCP5gBSY4sEBT38Q/9RBh9AH40zEOg7Hlq2THRZ" crossorigin="anonymous"></script>
</body>
</html>
