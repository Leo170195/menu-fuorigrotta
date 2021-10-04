<template>
    <nav class="navbar fixed-top bg-nav" aria-label="Main navigation">
        <div class="container-fluid">
            <a class="navbar-brand" href="#"><img class="logo" src="/img/logo-b.png" alt="logo"></a>
            <button class="navbar-toggler pe-4 pb-4" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar">
                <div class="navbar-toggler-icon"><img src="/img/icon/hamburger.png" alt="" height="40"></div>
            </button>
            <div class="offcanvas offcanvas-start" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
            <div class="offcanvas-header bg-nav text-white">
                <h5 class="offcanvas-t pb-2itle" id="offcanvasNavbarLabel">Fuorigrotta</h5>
                <button type="button" class="btn-close text-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body bg-nav show">
                <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none text-light" v-on:click="closeOffCanvas" href="#stuzzicheria">
                            <!-- <i class="fas fa-utensils"></i>  -->
                            <img src="/img/icon/olives.png" alt="" height="30">
                            Stuzzicheria
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none text-light" href="#antipasti" v-on:click="closeOffCanvas">
                            <img src="/img/icon/cheese.png" alt="" height="30">
                            Antipati
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none text-light" href="#insalata" v-on:click="closeOffCanvas">
                            <img src="/img/icon/salad.png" alt="" height="30">
                            Insalate
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none text-light" href="#fritti" v-on:click="closeOffCanvas">
                            <img src="/img/icon/french-fries.png" alt="" height="30">
                            Fritti
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none text-light" href="#terrine" v-on:click="closeOffCanvas">
                            <img src="/img/icon/bitterballen.png" alt="" height="30">
                            Terrine
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none text-light" href="#carne" v-on:click="closeOffCanvas">
                            <img src="/img/icon/beef.png" alt="" height="30">
                            Carne
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none text-light" href="#panini" v-on:click="closeOffCanvas">
                            <img src="/img/icon/hamburger.png" alt="" height="30">
                            Panini
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none text-light" href="#coke" v-on:click="closeOffCanvas">
                            <img src="/img/icon/coke.png" alt="" height="30">
                            Bevande
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none text-light" href="#beers" v-on:click="closeOffCanvas">
                            <img src="/img/icon/beers.png" alt="" height="30">
                            Birre alla spina
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none text-light" href="#beerb" v-on:click="closeOffCanvas">
                            <img src="/img/icon/beerb.png" alt="" height="30">
                            Birre in bottiglia
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none text-light" href="#wine" v-on:click="closeOffCanvas">
                            <img src="/img/icon/wine.png" alt="" height="30">
                            Vini
                        </a>
                    </li>
                </ul>
            </div>
            </div>
        </div>
    </nav>  
    <div class="text-white p-3">
        <h1 id="stuzzicheria" class="text-center mb-5">Menu Fuorigrotta <img src="/img/icon/beer.png" alt="" height="50" class="ps-3"></h1>
        <div class="container pb-5">
            <div class="row">
                <div class="col-12">
                    <h2 class="mb-3 text-center">Stuzzicheria veloce <img src="/img/icon/olives.png" alt="" height="50" class="ps-3"></h2>
                    <div class="row py-3">
                        <div class="col-9">Tortillas con salsa piccante</div>
                        <div class="col-3 text-md-end">€ 3.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Arachidi</div>
                        <div class="col-3 text-md-end">€ 2.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Rice</div>
                        <div class="col-3 text-md-end">€ 2.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Olive</div>
                        <div class="col-3 text-md-end">€ 3.00</div>
                    </div>
                    <div id="antipasti" class="row pb-3">
                        <div class="col-9">Pistacchi</div>
                        <div class="col-3 text-md-end">€ 3.00</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="container pb-5">
            <div class="row">
                <div class="col-12">
                    <h2 class="mb-3 text-center">Antipasti <img src="/img/icon/cheese.png" alt="" height="50" class="ps-3"></h2>
                    <div class="row py-3">
                        <div class="col-9">Caprese 2.0</div>
                        <div class="col-3 text-md-end">€ 6.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Carpaccio di salmone affumicato con crostini</div>
                        <div class="col-3 text-md-end">€ 8.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Insalata di polpo</div>
                        <div class="col-3 text-md-end">€ 8.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Caciocavallo alla griglia</div>
                        <div class="col-3 text-md-end">€ 4.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Mortadella alla brace con pistacchi e aceto balsamico</div>
                        <div class="col-3 text-md-end">€ 4.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Crostini crudo e mozzarella</div>
                        <div class="col-3 text-md-end">€ 4.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Crostini spek e scamorza</div>
                        <div class="col-3 text-md-end">€ 4.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Crostini brie e noci</div>
                        <div class="col-3 text-md-end">€ 4.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Crostini misti della casa</div>
                        <div class="col-3 text-md-end">€ 5.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Crostini stracchino e salsiccia macinata</div>
                        <div class="col-3 text-md-end">€ 5.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Crostini stracciatella e salmone</div>
                        <div class="col-3 text-md-end">€ 6.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Crostini stracciatella e pomodori secchi</div>
                        <div class="col-3 text-md-end">€ 6.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Crostini porchetta e crema di carciofi</div>
                        <div class="col-3 text-md-end">€ 6.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Tagliere misto di salumi (x 2 persone)</div>
                        <div class="col-3 text-md-end">€ 8.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Tagliere misto di formaggi (x 2 persone)</div>
                        <div class="col-3 text-md-end">€ 8.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Tagliere misto di salumi e formaggi con marmellate</div>
                        <div class="col-3 text-md-end">€ 15.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Mozzarella di bufala e prosciutto crudo</div>
                        <div class="col-3 text-md-end">€ 9.00</div>
                    </div>
                    <div id="insalata" class="row pb-3">
                        <div class="col-9">Verdure grigliate</div>
                        <div class="col-3 text-md-end">€ 4.00</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="container pb-5">
            <div class="row">
                <div class="col-12">
                    <h2 class="mb-3 text-center">Insalate <img src="/img/icon/salad.png" alt="" height="50" class="ps-3"></h2>
                    <div class="row py-3">
                        <div class="col-9">Insalata tricolore (insalata iceberg, cubetti di mozzarella e julienne di pomodori)</div>
                        <div class="col-3 text-md-end">€ 6.00</div>
                    </div>
                    <div id="fritti" class="row pb-3">
                        <div class="col-9">Insalata sfiziosa (insalata iceberg, cubetti di mozzarella e julienne di pomodori, mais, olive nere, tonno, ravanello)</div>
                        <div class="col-3 text-md-end">€ 8.00</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="container pb-5">
            <div class="row">
                <div class="col-12">
                    <h2 class="mb-3 text-center">Fritti <img src="/img/icon/french-fries.png" alt="" height="50" class="ps-3"></h2>
                    <div class="row py-3">
                        <div class="col-9">Patatine fritte</div>
                        <div class="col-3 text-md-end">€ 3.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Frittura di calamari (x 2 persone, su prenotazione)</div>
                        <div class="col-3 text-md-end">€ 13.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Montanare napoletane (4 pz)</div>
                        <div class="col-3 text-md-end">€ 6.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Alette di pollo fritto (6 pz)</div>
                        <div class="col-3 text-md-end">€ 6.00</div>
                    </div>
                    <div id="terrine" class="row pb-3">
                        <div class="col-9">Pettole con sartascinello</div>
                        <div class="col-3 text-md-end">€ 5.00</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="container pb-5">
            <div class="row">
                <div class="col-12">
                    <h2 class="mb-3 text-center">Terrine <img src="/img/icon/bitterballen.png" alt="" height="50" class="ps-3"></h2>
                    <div class="row py-3">
                        <div class="col-9">Patate al forno</div>
                        <div class="col-3 text-md-end">€ 3.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Zucchine scamorza e pancetta</div>
                        <div class="col-3 text-md-end">€ 4.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Parmigiana di melanzane</div>
                        <div class="col-3 text-md-end">€ 5.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Gnocchetti alla sorrentina con provola di bufala</div>
                        <div class="col-3 text-md-end">€ 5.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Involtini spek e scamorza</div>
                        <div class="col-3 text-md-end">€ 3.50</div>
                    </div>
                    <div id="carne" class="row pb-3">
                        <div class="col-9">Polpette al sugo con crostini</div>
                        <div class="col-3 text-md-end">€ 5.00</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="container pb-5">
            <div class="row">
                <div class="col-12">
                    <h2 class="mb-3 text-center">Carne <img src="/img/icon/beef.png" alt="" height="50" class="ps-3"></h2>
                    <div class="row py-3">
                        <div class="col-9">Tagliata di manzo rucola e grana</div>
                        <div class="col-3 text-md-end">€ 15.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Arrosticini su letto di rucola o verdure di stagione (6 pz)</div>
                        <div class="col-3 text-md-end">€ 6.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Arrosticini con pancetta su letto di rucola o verdure di stagione (6 pz)</div>
                        <div class="col-3 text-md-end">€ 6.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Hamburger con patatine</div>
                        <div class="col-3 text-md-end">€ 5.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Salsiccia di Norcia</div>
                        <div class="col-3 text-md-end">€ 5.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Grigliata mista</div>
                        <div class="col-3 text-md-end">€ 13.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Tagliata di pollo alla thailandese</div>
                        <div class="col-3 text-md-end">€ 7.00</div>
                    </div>
                    <div id="panini" class="row pb-3">
                        <div class="col-9">Cotoletta con patatine fritte</div>
                        <div class="col-3 text-md-end">€ 4.50</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="container pb-5">
            <div class="row">
                <div class="col-12">
                    <h2 class="mb-3 text-center">Panini <img src="/img/icon/hamburger.png" alt="" height="50" class="ps-3"></h2>
                    <div class="row py-3">
                        <div class="col-9">1 - Polpo stracciatella e pomodori secchi</div>
                        <div class="col-3 text-md-end">€ 6.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">2 - Straccetti di manzo melanzane e mozzarella</div>
                        <div class="col-3 text-md-end">€ 5.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">3 - Prosciutto crudo mozzarella e rucola</div>
                        <div class="col-3 text-md-end">€ 4.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">4 - Parmigiana con provola di bufala</div>
                        <div class="col-3 text-md-end">€ 5.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">5 - Salsiccia di norcia pomodoro e insalata</div>
                        <div class="col-3 text-md-end">€ 4.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">6 - Cotoletta pomodoro e insalata</div>
                        <div class="col-3 text-md-end">€ 4.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">7 - Hamburger provola di bufala e patatine fritte</div>
                        <div class="col-3 text-md-end">€ 5.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">8 - Hamburger stracciatella bacon e pesto di pistacchio</div>
                        <div class="col-3 text-md-end">€ 6.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">9 - Hamburger mortadella alla brace pesto di pistacchio e ciliegine di mozzarella</div>
                        <div class="col-3 text-md-end">€ 6.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">10 - Hamburger maionese al pepe nero bacon e mozzarella</div>
                        <div class="col-3 text-md-end">€ 5.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">11 - Hamburger brie pomodori secchi prosciutto crudo e rucola</div>
                        <div class="col-3 text-md-end">€ 7.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">12 - Hamburger bacon melanzane dorate salsa cheddar e patatine fritte</div>
                        <div class="col-3 text-md-end">€ 6.50</div>
                    </div>
                    <div id="coke" class="row pb-3">
                        <div class="col-9">13 - Polpette al sugo e provola</div>
                        <div class="col-3 text-md-end">€ 5.50</div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container pb-5">
            <div class="row">
                <div class="col-12">
                    <h2 class="mb-3 text-center">Bevande<img src="/img/icon/coke.png" alt="" height="50" class="ps-3"></h2>
                    <div class="row py-3">
                        <div class="col-9">Acqua minerale/naturale 50 cl</div>
                        <div class="col-3 text-md-end">€ 1.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Acqua minerale/naturale 1 lt</div>
                        <div class="col-3 text-md-end">€ 1.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Coca-cola/Coca-cola zero 33cl</div>
                        <div class="col-3 text-md-end">€ 1.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Fanta 33cl</div>
                        <div class="col-3 text-md-end">€ 1.50</div>
                    </div>
                    <div id="beers" class="row pb-3">
                        <div class="col-9">Estathè pesca o limone 33cl</div>
                        <div class="col-3 text-md-end">€ 2.00</div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container pb-5">
            <div class="row">
                <div class="col-12">
                    <h2 class="mb-3 text-center">Birre alla spina<img src="/img/icon/beers.png" alt="" height="50" class="ps-3"></h2>
                    <div class="row pt-3 pb-1">
                        <div class="col-9">Stella Artois 20 cl.</div>
                        <div class="col-3 text-md-end">€ 2.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Stella Artois 40 cl.</div>
                        <div class="col-3 text-md-end">€ 4.50</div>
                    </div>
                    <div class="row pb-1">
                        <div class="col-9">Leffe Rousse 25 cl.</div>
                        <div class="col-3 text-md-end">€ 3.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Leffe Rousse 50 cl.</div>
                        <div class="col-3 text-md-end">€ 5.00</div>
                    </div>
                    <div class="row pb-1">
                        <div class="col-9">Leffe Blonde 25 cl.</div>
                        <div class="col-3 text-md-end">€ 3.00</div>
                    </div>
                    <div id="beerb" class="row pb-3">
                        <div class="col-9">Leffe Blonde 50 cl.</div>
                        <div class="col-3 text-md-end">€ 5.00</div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container pb-5">
            <div class="row">
                <div class="col-12">
                    <h2 class="mb-3 text-center">Birre in bottiglia<img src="/img/icon/beerb.png" alt="" height="50" class="ps-3"></h2>
                    <div class="row py-3">
                        <div class="col-9">Super 8 Export</div>
                        <div class="col-3 text-md-end">€ 3.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Landbier Original</div>
                        <div class="col-3 text-md-end">€ 4.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Bjorn</div>
                        <div class="col-3 text-md-end">€ 3.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Grinbergen Blanche</div>
                        <div class="col-3 text-md-end">€ 3.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Grinbergen Double</div>
                        <div class="col-3 text-md-end">€ 3.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Vitus Weihenstephaner</div>
                        <div class="col-3 text-md-end">€ 5.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Re Ale</div>
                        <div class="col-3 text-md-end">€ 5.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Nazionale Birra Italiana</div>
                        <div class="col-3 text-md-end">€ 5.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Chimay Premiere</div>
                        <div class="col-3 text-md-end">€ 5.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">La Trappe Triple</div>
                        <div class="col-3 text-md-end">€ 5.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Gulden Draak</div>
                        <div class="col-3 text-md-end">€ 5.50</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Monk's Stout Dupont</div>
                        <div class="col-3 text-md-end">€ 4.00</div>
                    </div>
                    <div id="wine" class="row pb-3">
                        <div class="col-9">Nora</div>
                        <div class="col-3 text-md-end">€ 5.50</div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container pb-5">
            <div class="row">
                <div class="col-12">
                    <h2 class="mb-3 text-center">Vini<img src="/img/icon/wine.png" alt="" height="50" class="ps-3"></h2>
                    <h5 class="text-center pb-2">Vini Bianchi</h5>
                    <div class="row pb-3">
                        <div class="col-9">Pecorino</div>
                        <div class="col-3 text-md-end">€ 20.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Pyrros</div>
                        <div class="col-3 text-md-end">€ 18.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Greco</div>
                        <div class="col-3 text-md-end">€ 13.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Don Franc</div>
                        <div class="col-3 text-md-end">€ 15.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Lacryma Christi</div>
                        <div class="col-3 text-md-end">€ 20.00</div>
                    </div>
                    <h5 class="text-center pb-2">Vini Rosati</h5>
                    <div class="row pb-3">
                        <div class="col-9">Merlot</div>
                        <div class="col-3 text-md-end">€ 20.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Philomena</div>
                        <div class="col-3 text-md-end">€ 15.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Versura</div>
                        <div class="col-3 text-md-end">€ 15.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Rondirosa</div>
                        <div class="col-3 text-md-end">€ 13.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Lacryma Christi</div>
                        <div class="col-3 text-md-end">€ 20.00</div>
                    </div>
                    <h5 class="text-center pb-2">Vini Rossi</h5>
                    <div class="row pb-3">
                        <div class="col-9">Primitivo magno</div>
                        <div class="col-3 text-md-end">€ 18.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Padre</div>
                        <div class="col-3 text-md-end">€ 18.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Gragnano</div>
                        <div class="col-3 text-md-end">€ 20.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Lacryma Christi</div>
                        <div class="col-3 text-md-end">€ 20.00</div>
                    </div>
                    <h5 class="text-center pb-2">Le Bollicine</h5>
                    <div class="row pb-3">
                        <div class="col-9">Curvèe Oro (extra dry)</div>
                        <div class="col-3 text-md-end">€ 15.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Fantini Gran Curvèe Rosè</div>
                        <div class="col-3 text-md-end">€ 22.00</div>
                    </div>
                    <div class="row pb-3">
                        <div class="col-9">Fantini Gran Curvèe Bianco</div>
                        <div class="col-3 text-md-end">€ 22.00</div>
                    </div>
                </div>
            </div>
        </div>
        
    </div>
</template>

<script>
// import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap/dist/js/bootstrap.bundle.min.js"

export default {
    name: 'Body',
    methods: {
        closeOffCanvas(){
            document.querySelector('#offcanvasNavbar').classList.remove('show')
            document.querySelector('.offcanvas-backdrop').remove()
            document.querySelector('body').style.removeProperty('overflow', 'padding-right');
        }
    }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
