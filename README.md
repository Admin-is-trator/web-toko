<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>E-Commerce Website</title>
        <!----Boostrap--->
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        <!---bootstrap JS--->
        <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    </head>
    <body>
        <div class="top-nav-bar">
            <div class="search-box">
                <i class="fa fa-bars" id="menu-btn" onclick="openmenu()"></i>
                <i class="fa fa-times" id="close-btn" onclick="closemenu()"></i>
                <img src="img/logo.png" class="logo">
                <input type="text" class="form-control">
                <span class="input-group-text"><i class="fa fa-search"></i></span>
            </div>
            <div class="menu-bar">
                <ul>
                    <li class="fa fa-shopping-basket">Cart</li>
                    <li>Sign Up</li>
                    <li>Sign In</li>
                </ul>
            </div>
        </div>
        <section class="header">
            <div class="side-menu" id="side-menu">
                <ul>
                    <li>On Sale <i class="fa fa-angle-right"></i>
                        <ul>
                            <li>Sub Menu-1</li>
                            <li>Sub Menu-1</li>
                            <li>Sub Menu-1</li>
                            <li>Sub Menu-1</li>
                        </ul>
                    </li>
                    <li>Mobiles <i class="fa fa-angle-right"></i>
                        <ul>
                            <li>Sub Menu-2</li>
                            <li>Sub Menu-2</li>
                            <li>Sub Menu-2</li>
                            <li>Sub Menu-2</li>
                        </ul>
                    </li>
                    <li>Fashion <i class="fa fa-angle-right"></i>
                        <ul>
                            <li>Sub Menu-3</li>
                            <li>Sub Menu-3</li>
                            <li>Sub Menu-3</li>
                            <li>Sub Menu-3</li>
                        </ul>
                    </li>
                    <li>Sports <i class="fa fa-angle-right"></i>
                        <ul>
                            <li>Sub Menu-4</li>
                            <li>Sub Menu-4</li>
                            <li>Sub Menu-4</li>
                            <li>Sub Menu-4</li>
                        </ul>
                    </li>
                    <li>Foods <i class="fa fa-angle-right"></i>
                        <ul>
                            <li>Sub Menu-5</li>
                            <li>Sub Menu-5</li>
                            <li>Sub Menu-5</li>
                            <li>Sub Menu-5</li>
                        </ul>
                    </li>
                    <li>Hobbies <i class="fa fa-angle-right"></i>
                        <ul>
                            <li>Sub Menu-6</li>
                            <li>Sub Menu-6</li>
                            <li>Sub Menu-6</li>
                            <li>Sub Menu-6</li>
                        </ul>
                    </li>
                    <li>Beauty <i class="fa fa-angle-right"></i>
                        <ul>
                            <li>Sub Menu-7</li>
                            <li>Sub Menu-7</li>
                            <li>Sub Menu-7</li>
                            <li>Sub Menu-7</li>
                        </ul>
                    </li>
                    <li>Schools <i class="fa fa-angle-right"></i>
                        <ul>
                            <li>Sub Menu-8</li>
                            <li>Sub Menu-8</li>
                            <li>Sub Menu-8</li>
                            <li>Sub Menu-8</li>
                        </ul>
                    </li>
                    <li>Home & Furniture <i class="fa fa-angle-right"></i>
                        <ul>
                            <li>Sub Menu-9</li>
                            <li>Sub Menu-9</li>
                            <li>Sub Menu-9</li>
                            <li>Sub Menu-9</li>
                        </ul>
                    </li>
                    <li>Games <i class="fa fa-angle-right"></i>
                        <ul>
                            <li>Sub Menu-10</li>
                            <li>Sub Menu-10</li>
                            <li>Sub Menu-10</li>
                            <li>Sub Menu-10</li>
                        </ul>
                    </li>
                    <li>Pets <i class="fa fa-angle-right"></i>
                        <ul>
                            <li>Sub Menu-11</li>
                            <li>Sub Menu-11</li>
                            <li>Sub Menu-11</li>
                            <li>Sub Menu-11</li>
                        </ul>
                    </li>
                </ul>
            </div>

            <div class="slider">
                <div id="slider" class="carousel slide carousel-fade" data-ride="carousel">
                    <div class="carousel-inner">
                      <div class="carousel-item active">
                        <img src="img/banner1.jpg" class="d-block w-100">
                      </div>
                      <div class="carousel-item">
                        <img src="img/banner2.jpg" class="d-block w-100">
                      </div>
                      <div class="carousel-item">
                        <img src="img/banner3.jpg" class="d-block w-100">
                      </div>
                      <div class="carousel-item">
                        <img src="img/banner4.jpg" class="d-block w-100">
                      </div>
                    </div>
                    <ol class="carousel-indicators">
                        <li data-target="#slider" data-slide-to="0" class="active"></li>
                        <li data-target="#slider" data-slide-to="1"></li>
                        <li data-target="#slider" data-slide-to="2"></li>
                        <li data-target="#slider" data-slide-to="3"></li>
                      </ol>
                  </div>
            </div>
        </section>

        <section class="featured-categories">
            <div class="container">
                <div class="row">
                    <div class="col-md-4">
                        <img src="img/head1.jpg">
                    </div>
                    <div class="col-md-4">
                        <img src="img/jam1.jpg">
                    </div>
                    <div class="col-md-4">
                        <img src="img/merah.jpg">
                    </div>
                </div>
            </div>
        </section>

        <section class="on-sale">
            <div class="container">
                <div class="title-box">
                    <h2>On sale</h2>
                </div>
                <div class="row">
                    <div class="col-md-3">
                        <div class="product-top">
                            <a href="product.html"><img src="img/Jaketkul.jpg"></a>
                            <div class="overlay-right">
                                <button type="button" class="btn btn-secondary" title="Quick Shop">
                                    <i class="fa fa-eye"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Wishlist">
                                    <i class="fa fa-heart-o"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Cart">
                                    <i class="fa fa-shopping-cart"></i>
                                </button>
                            </div>
                        </div>

                        <div class="product-bottom text-center">
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star-half-o"></i>
                            <h3>Casual Jacket</h3>
                            <h5>Rp.200.000</h5>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="product-top">
                            <a href="product.html"><img src="img/jam1.jpg"></a>
                            <div class="overlay-right">
                                <button type="button" class="btn btn-secondary" title="Quick Shop">
                                    <i class="fa fa-eye"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Wishlist">
                                    <i class="fa fa-heart-o"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Cart">
                                    <i class="fa fa-shopping-cart"></i>
                                </button>
                            </div>
                        </div>

                        <div class="product-bottom text-center">
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star-half-o"></i>
                            <h3>Fittness Watch</h3>
                            <h5>Rp.150.000</h5>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="product-top">
                            <a href="product.html"><img src="img/shoes.jpg"></a>
                            <div class="overlay-right">
                                <button type="button" class="btn btn-secondary" title="Quick Shop">
                                    <i class="fa fa-eye"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Wishlist">
                                    <i class="fa fa-heart-o"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Cart">
                                    <i class="fa fa-shopping-cart"></i>
                                </button>
                            </div>
                        </div>

                        <div class="product-bottom text-center">
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star-half-o"></i>
                            <h3>Sport Shoes</h3>
                            <h5>Rp.300.000</h5>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="product-top">
                            <a href="product.html"><img src="img/apple.jpeg"></a>
                            <div class="overlay-right">
                                <button type="button" class="btn btn-secondary" title="Quick Shop">
                                    <i class="fa fa-eye"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Wishlist">
                                    <i class="fa fa-heart-o"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Cart">
                                    <i class="fa fa-shopping-cart"></i>
                                </button>
                            </div>
                        </div>

                        <div class="product-bottom text-center">
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star-half-o"></i>
                            <h3>Smartphone</h3>
                            <h5>Rp.12.300.000</h5>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="new-products">
            <div class="container">
                <div class="title-box">
                    <h2>New Arrivals</h2>
                </div>
                <div class="row">
                    <div class="col-md-3">
                        <div class="product-top">
                            <img src="img/kimono.jpeg">
                            <div class="overlay-right">
                                <button type="button" class="btn btn-secondary" title="Quick Shop">
                                    <i class="fa fa-eye"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Wishlist">
                                    <i class="fa fa-heart-o"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Cart">
                                    <i class="fa fa-shopping-cart"></i>
                                </button>
                            </div>
                        </div>

                        <div class="product-bottom text-center">
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                        
                            <h3>Kimono</h3>
                            <h5>Rp.200.000</h5>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="product-top">
                            <img src="img/tas.jpg">
                            <div class="overlay-right">
                                <button type="button" class="btn btn-secondary" title="Quick Shop">
                                    <i class="fa fa-eye"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Wishlist">
                                    <i class="fa fa-heart-o"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Cart">
                                    <i class="fa fa-shopping-cart"></i>
                                </button>
                            </div>
                        </div>

                        <div class="product-bottom text-center">
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star-half-o"></i>
                            <h3>Bag</h3>
                            <h5>Rp.150.000</h5>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="product-top">
                            <img src="img/smart.jpg">
                            <div class="overlay-right">
                                <button type="button" class="btn btn-secondary" title="Quick Shop">
                                    <i class="fa fa-eye"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Wishlist">
                                    <i class="fa fa-heart-o"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Cart">
                                    <i class="fa fa-shopping-cart"></i>
                                </button>
                            </div>
                        </div>

                        <div class="product-bottom text-center">
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star-half-o"></i>
                            <h3>Smart Watch</h3>
                            <h5>Rp.300.000</h5>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="product-top">
                            <img src="img/topi1.jpeg">
                            <div class="overlay-right">
                                <button type="button" class="btn btn-secondary" title="Quick Shop">
                                    <i class="fa fa-eye"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Wishlist">
                                    <i class="fa fa-heart-o"></i>
                                </button>
                                <button type="button" class="btn btn-secondary" title="Add to Cart">
                                    <i class="fa fa-shopping-cart"></i>
                                </button>
                            </div>
                        </div>

                        <div class="product-bottom text-center">
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star-half-o"></i>
                            <h3>Had Black</h3>
                            <h5>Rp.12.300.000</h5>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="website-features">
            <div class="container">
                <div class="row">
                    <div class="col-md-3 feature-box">
                        <img src="img/ori.png">
                        <div class="feature-text">
                            <p><b>100% Original Items </b>are available at company</p>
                        </div>
                    </div>
                    <div class="col-md-3 feature-box">
                        <img src="img/garansi.png">
                        <div class="feature-text">
                            <p><b>30 hari garansi </b>untuk setiap produk</p>
                        </div>
                    </div>
                    <div class="col-md-3 feature-box">
                        <img src="img/free.png">
                        <div class="feature-text">
                            <p><b>Gratis ongkir </b> untuk setiap pembelian</p>
                        </div>
                    </div>
                    <div class="col-md-3 feature-box">
                        <img src="img/emon.jpeg">
                        <div class="feature-text">
                            <p><b>Tesedia pembayaran virtual </b>melalui ATM M-Banking</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="footer">
            <div class="container text-center">
                <div class="row">
                    <div class="col-md-3">
                        <h1>Usefull Links</h1>
                        <p>Privacy Policy</p>
                        <p>Terms of Use</p>
                        <p>Return Policy</p>
                        <p>Discount Coupons</p>
                    </div>
                    <div class="col-md-3">
                        <h1>Company</h1>
                        <p>About</p>
                        <p>Contact</p>
                        <p>Career</p>
                        <p>Affiliate</p>
                    </div>
                    <div class="col-md-3">
                        <h1>Follow Us On</h1>
                       <p><i class="fa fa-facebook-official"></i>Facebook</p>
                       <p><i class="fa fa-instagram"></i>Instagram</p>
                       <p><i class="fa fa-twitter"></i>Twitter</p>
                       <p><i class="fa fa-youtube-play"></i>Youtube</p>
                    </div>
                    <div class="col-md-3 footer-image">
                        <h1>Downlaod App</h1>
                        <img src="img/vb.png">
                    </div>
                </div>
                <hr>
                <p class="copyright">Made With <i class="fa fa-heart-o"></i>by Mora Hakim</p>
            </div>
        </section>

        <script>
            function openmenu(){
                document.getElementById("side-menu").style.display="block";
                document.getElementById("menu-btn").style.display="none";
                document.getElementById("close-btn").style.display="block";
            }

            function closemenu(){
                document.getElementById("side-menu").style.display="none";
                document.getElementById("menu-btn").style.display="block";
                document.getElementById("close-btn").style.display="none";

            }
        </script>
    </body>
</html>
