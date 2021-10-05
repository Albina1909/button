# button<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home | PromoVideoLab</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,
    wght@0,400;0,700;1,400&family=Ubuntu:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">


    <link rel="stylesheet" href="css/style.css">
</head>

<body>

    <!-- HEADER (НАЧАЛО) -->

    <header>
        <div class="container">
<a href="#">
    <img src="img/logo.svg" alt="PromoVideoLab" class="logo">
</a>
<nav>
    <ul class="main-menu">
        <li><a href="#">Types of videos </a></li>
        <li><a href="#">Portfolio </a></li>
        <li><a href="#">Blog</a></li>
        <li><a class="btn" href="#">schedule a call</a></li>

        <li class="burger-menu" ><button></button></li>
    </ul>
</nav>
        </div>
    </header>
    <!-- HEADER (КОНЕЦ)  -->


    <main>

        <!-- 1.СЕКЦИЯ ПРОМО (НАЧАЛО) -->
        <section class="promo">
            <div class="container">

            </div>
        </section>
        <!-- СЕКЦИЯ ПРОМО (КОНЕЦ)  -->




        <!-- 2.СЕКЦИЯ КОМПАНИ (НАЧАЛО) -->
        <section class="companies">
            <div class="container">

            </div>
        </section>
        <!-- СЕКЦИЯ КОМПАНИ (КОНЕЦ)  -->




        <!-- 3.СЕКЦИЯ СТЕПС (НАЧАЛО) -->

        <section class="steps">
            <div class="container">

            </div>
        </section>

        <!-- СЕКЦИЯ СТЕПС (КОНЕЦ)  -->




        <!-- 4.СЕКЦИЯ ПОРТФОЛИО (НАЧАЛО) -->
        <section class="portfolio">
            <div class="container">

            </div>
        </section>
        <!-- СЕКЦИЯ ПОРТФОЛИО (КОНЕЦ)  -->




        <!-- 5.СЕКЦИЯ АДВАНТАГЕС (НАЧАЛО) -->
        <section class="advantages">
            <div class="container">

            </div>
        </section>

        <!-- СЕКЦИЯ АДВАНТАГЕС (КОНЕЦ)  -->



        <!-- 6.СЕКЦИЯ РЕВЬЮЗ (НАЧАЛО) -->
        <section class="reviews">
            <div class="container">

            </div>
        </section>
        <!-- СЕКЦИЯ РЕВЬЮЗ (КОНЕЦ)  -->



                          </main> <!-- В <main> получилось 6 секций -->

    <footer>
<!-- 1.СЕКЦИЯ ПОДВАЛ-ВЕРХ (НАЧАЛО) -->

        <section class="footer-top">
            <div class="container">

            </div>
        </section>
        <!-- 1.СЕКЦИЯ ПОДВАЛ-ВЕРХ (КОНЕЦ) -->


        <!-- 1.СЕКЦИЯ ПОДВАЛ-НИЗ (НАЧАЛО) -->
        <section class="footer-bottom">
            <div class="container">

            </div>
        </section>
        <!-- 1.СЕКЦИЯ ПОДВАЛ-НИЗ (КОНЕЦ) -->

    </footer>


</body>

</html>

CSS
***** ОБЩИЕ СТИЛИ (начало) *****/
html {
    font-size: 17px;
}

body { margin: 0;
    font-family: "Ubuntu", sans-serif
     Verdana, Geneva, Tahoma, sans-serif;
     font-weight: normal;
    background-color:#f4f6fb ;
}


.container {
    margin: auto;
}
.btn {
    position: relative;
    display: inline-block;
    padding: 18px  48px;
    text-transform: uppercase;
    font-size: 15px;
    color:#ffff;
    font-weight: bold;
background-color: #EF5E42;
border-radius: 30px;  }

.btn:hover {
    color: #ffff;
    background-color: #ef8042;}

.btn:active {
     color: #ffff; 
    background-color: #B54029;
}

.btn::before {
    box-sizing: border-box;
    top: 0px;
    left: 0px;
    position: absolute;

    width: 100%;
    height: 100%;
    content: "";
    border :2px solid #041032;
border-radius: 30px;
transform: rotate(-3deg);
transition: all 0.5s;}
.btn:hover::before {
    transform: rotate(3deg);
}
.btn:active::before {
    transform: rotate(0);}

ul { list-style-type: none;
    margin: 0;
padding: 0;
}

a {
 font-weight: bold;
    text-decoration: none;
    color: #4050a5;
    transition:all 0,25s;
}
a:hover {
    color:#EF5E42;
}

/***** ОБЩИЕ СТИЛИ (конец) *****/



/***** HEADER (начало) *****/
.burger-menu {
    display: none;
}
/***** HEADER (конец) *****/

/***** 1.СЕКЦИЯ ПРОМО (начало) *****/
/***** СЕКЦИЯ ПРОМО (конец) *****/

/***** 2.СЕКЦИЯ КОМПАНИ (начало) *****/
/***** СЕКЦИЯ КОМПАНИ (конец) *****/


/***** 3.СЕКЦИЯ СТЕПС (начало) *****/
/***** СЕКЦИЯ СТЕПС (конец) *****/


/***** 4.СЕКЦИЯ ПОРТФОЛИО (начало) *****/
/***** СЕКЦИЯ ПОРТФОЛИО (конец) *****/




/***** 5.СЕКЦИЯ АТВАНТАГЕС (начало) *****/
/***** СЕКЦИЯ АТВАНТАГЕС (конец) *****/



/***** 6.СЕКЦИЯ РЕВЬЮЗ (начало) *****/
/***** СЕКЦИЯ РЕВЬЮЗ (конец) *****/

/***** СЕКЦИЯ ПОДВАЛ (НАЧАЛО) ******/
/***** СЕКЦИЯ ПОДВАЛ (КОНЕЦ) ******/  


/***** СЕКЦИЯ МЕДИА-ЗАПРОС (НАЧАЛО) ******/

@media ( max-width: 992px) {
    .burger-menu {
        display: block;
    }
    }

@media( min-width: 1300px) {
    .container {
        max-width: 1290px;
    }

}

/***** СЕКЦИЯ МЕДИА-ЗАПРОС (КОНЕЦ) ******/  
