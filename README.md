{% extends 'base.html' %} {% block title %} {% endblock title %} {% block body %}


<section>
    <style>
        .neveimg {
            transform: translate(0%, 0%);
            margin-left: 571px;
            margin-top: 100px;
        }
    </style>
    <div>
        <a>
            <img class="neveimg" src="/static/img/pic1.webp" alt="">
        </a>
    </div>
</section>

<div>
    <style>
        .element1 {
            border-radius: 100px;
            height: 70px;
            color: red;
            margin-top: 5px;
            background-image: url(/static/img/c.jpg);
            opacity: 0.7;
        }
    </style>

    <!---First part of font page -->
    <section>
        <div>
            <img src="/static/img/firstimg.jpg" height="670px" width="100%" alt="">
        </div>
        <div>
            <style>
                .hand {
                    font-size: 45px;
                    font-family: Arial, Helvetica, sans-serif;
                    text-align: center;
                    position: absolute;
                    top: 60%;
                    left: 50%;
                    transform: translate(-50%, -50%);
                    color: lemonchiffon;
                }
                
                .ice {
                    font-size: 100px;
                    font-family: Arial, Helvetica, sans-serif;
                    text-align: center;
                    position: absolute;
                    top: 70%;
                    left: 50%;
                    transform: translate(-50%, -50%);
                    color: lemonchiffon;
                }
                
                .menu {
                    position: absolute;
                    top: 78%;
                    left: 47%;
                }
            </style>
            <p class="hand">HAND CRAFTED</p>
            <b><h1 class="ice">ICE CREAM</h1></b>
            <button class="menu btn-lg" type="menu">MENU</button>
        </div>
    </section>
    <!---first  part of font page close -->
    <!---second part of font page start-->


    <br>
    <section class="container">
        <div>
            <div class="row row-cols-1 row-cols-md-2">
                <div class="col mb-4">
                    <div class="card">
                        <img src="/static/img/mycard.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">No Sugar Added Ice Cream </h5>
                            <p class="card-text">Made by using only artificial sweeteners or natural sugar substitutes keeps the mixture smooth, creamy and soft.</p>
                        </div>
                    </div>
                </div>
                <div class="col mb-4">
                    <div class="card">
                        <img src="/static/img/mycard2.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Lactose-free Ice Cream </h5>
                            <p class="card-text">Ice creams that have no detectable lactose are perfect for people who cannot digest this enzyme.</p>
                        </div>
                    </div>
                </div>
                <div class="col mb-4">
                    <div class="card">
                        <img src="/static/img/mycard3.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Gluten-Free Ice Cream </h5>
                            <p class="card-text">Same as with lactose, several brands of ice cream are targeted for people who have problems digesting gluten.</p>
                        </div>
                    </div>
                </div>
                <div class="col mb-4">
                    <div class="card">
                        <img src="/static/img/mycard4.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Cones </h5>
                            <p class="card-text">Edible hollow cone in which ice cream is poured.This type of ice cream became absolute most favorite of them all.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!--close second part-->
    <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
            <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="/static/img/2.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block element1">
                    <h6>Welcome to the best Ice Cream Of Bhopal</h6>
                    <p>I know you eat icecream but I know you have not eaten my IceCream.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="/static/img/3.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block element1">
                    <h6>We serve love with our Ice Cream</h6>
                    <p>This is IceCream shop .</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="/static/img/2.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block element1">
                    <h6>Welcome to the best Ice Cream Of India</h6>
                    <p>I know you eat icecream but I know you have not eaten my IceCream.</p>
                </div>
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
</div>
<br>


<!---card section-->
<style>
    .cent {
        text-align: center;
        font-size: 35px;
        border-radius: 100px;
        height: 70px;
        color: red;
        margin-top: 5px;
    }
</style>
<p class=cent element1> Select From Our Range Of Ice Cream
    <p>>
        <div class=container>
            <div class="card-deck">
                <div class="card">
                    <img src="/static/img/card1.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Soft Serve</h5>
                        <p class="card-text"> It gets its super-smooth texture from air that's introduced as the ingredients are frozen.</p>
                    </div>
                    <div class="container">
                        <button type="button" class="btn btn-danger btn-lg btn-block">BUY NOW</button>
                    </div>
                </div>
                <div class="card">
                    <img src="/static/img/cadr2.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Frozen Yogurt</h5>
                        <p class="card-text">It's based on the model of soft-serve but is lower in fat and offers a tangy taste, thanks to, well, the yogurt</p>
                    </div>
                    <div class="container-fluid">
                        <button type="button" class="btn btn-danger btn-lg btn-block">BUY NOW</button>
                    </div>
                </div>
 <div class="card">
                    <img src="/static/img/cadr2.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Frozen Yogurt</h5>
                        <p class="card-text">It's based on the model of soft-serve but is lower in fat and offers a tangy taste, thanks to, well, the yogurt</p>
                    </div>
                    <div class="container-fluid">
                        <button type="button" class="btn btn-danger btn-lg btn-block">BUY NOW</button>
                    </div>
                </div>
                <div class="card">
                    <img src="/static/img/card3.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Gelato</h5>
                        <p class="card-text">Italian gelato ripples and forms imperfect scoops because it is so much denser than standard American ice cream. </p>
                    </div>
                    <div class="container">
                        <button type="button" class="btn btn-danger btn-lg btn-block">BUY NOW</button>
                    </div>
                </div>
            </div>
        </div>
        <br>
        <section>
            <div>
                <img src="/static/img/baner.jpg" height="400px" width="100%" alt="">
            </div>
        </section>
        <!--Start footer section-->
        <style>
            .bgimg {
                background-color: #df391096;
            }
        </style>
        <section class="navcolr">
            <DIV>
                <div class="card text-center">
                    <div class="card-header bgimg">
                        Featured
                    </div>
                    <div class="card-body">
                        <h5 class="card-title">Special offer</h5>
                        <p class="card-text">With love .</p>
                        <a href="#" class="btn btn-primary">Go to IceCream</a>
                    </div>
                    <div class="card-footer text-muted bgimg">
                        @copyright kameshwar sah
                    </div>
                </div>
            </DIV>
        </section>
        <!--close footer section-->
        {% endblock body %}
