# Brainwave_Matrix_Intern-EcommereceWebsite
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ECommerce-ShoppingCart | Korsat X Parmaga</title>

    <!-- box icons  -->
    <link href='https://unpkg.com/boxicons@2.1.2/css/boxicons.min.css' rel='stylesheet'>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- styles  -->
    <link rel="stylesheet" href="assets/css/style.css">
</head>

<body>
    <!-- HEADER  -->
    <header>
        <!-- NAV  -->
        <div class="nav container">
            <a href="#" class="logo"><span>E</span>Commerce</a>
            <!-- CART ICON  -->
            <i class='bx bx-shopping-bag' id="cart-icon"><span class="navspan">Add Cart</span></i>
            <!-- <a href="home.html"><i class='bx bx-home-alt-2' id="cart-icon"><span class="navspan">Home</span></i></a> -->
            <!-- <a href="contact.html"><i class='bx bx-phone' id="cart-icon"><span class="navspan">Contact</span></i></a> -->
            

            <!-- CART  -->
            <div class="cart">
                <h2 class="cart-title">Your Cart</h2>

                <!-- CONTENT  -->
                <div class="cart-content">


                </div>

                <!-- TOTAL   -->
                <div class="total">
                    <div class="total-title">Total</div>
                    <div class="total-price">$0</div>
                </div>
                <!-- BUY BUTTON  -->
                <button type="button" class="btn-buy">Buy Now</button>
                <!-- CART CLOSE  -->
                <i class='bx bx-x' id="cart-close"></i>
            </div>
        </div>
    </header>


    <!-- SHOP SECTION  -->
    <section class="shop container">

        <h2 class="new">New Deals,Get Amazing Offer !!</h2>

        <!-- CONTENT  -->
        <div class="shop-content">
            <!-- BOX 1 -->
            <div class="product-box">
                <img src="assets/img/product1.jpg" alt="" class="product-img">
                <h2 class="product-title">Nike Shoes</h2>
                <span class="product-price">$79.5</span>
                <i class='bx bx-shopping-bag add-cart'></i>
            </div>
            <!-- BOX 2 -->
            <div class="product-box">
                <img src="assets/img/product2.jpg" alt="" class="product-img">
                <h2 class="product-title">BACKPACK</h2>
                <span class="product-price">$59.5</span>
                <i class='bx bx-shopping-bag add-cart'></i>
            </div>
            <!-- BOX 3 -->
            <div class="product-box">
                <img src="assets/img/product3.jpg" alt="" class="product-img">
                <h2 class="product-title">METAL BOTTLE</h2>
                <span class="product-price">$29.5</span>
                <i class='bx bx-shopping-bag add-cart'></i>
            </div>
            <!-- BOX 4 -->
            <div class="product-box">
                <img src="assets/img/product4.jpg" alt="" class="product-img">
                <h2 class="product-title">METAL SUNGLASSES</h2>
                <span class="product-price">$105</span>
                <i class='bx bx-shopping-bag add-cart'></i>
            </div>
            <!-- BOX 5 -->
            <div class="product-box">
                <img src="assets/img/product5.jpg" alt="" class="product-img">
                <h2 class="product-title">PS5 Controller</h2>
                <span class="product-price">$95</span>
                <i class='bx bx-shopping-bag add-cart'></i>
            </div>
            <!-- BOX 6 -->
            <div class="product-box">
                <img src="assets/img/product6.jpg" alt="" class="product-img">
                <h2 class="product-title">Galaxy Z Fold</h2>
                <span class="product-price">$1400</span>
                <i class='bx bx-shopping-bag add-cart'></i>
            </div>
            <!-- BOX 7 -->
            <div class="product-box">
                <img src="assets/img/product7.jpg" alt="" class="product-img">
                <h2 class="product-title">Nokon Camera</h2>
                <span class="product-price">$1700</span>
                <i class='bx bx-shopping-bag add-cart'></i>
            </div>
            <!-- BOX 8 -->
            <div class="product-box">
                <img src="assets/img/product8.jpg" alt="" class="product-img">
                <h2 class="product-title">Apple Watch</h2>
                <span class="product-price">$110.5</span>
                <i class='bx bx-shopping-bag add-cart'></i>
            </div>
        </div>
    </section>


    <!-- Section -->
     <!-- Why we are the best -->

    <section class="pb-4" id="service">
        <h1 class="home_h1 fw-bold text-center pt-5">Why we are the best</h1>
        <p class="p-3 text-secondary text-center">Who are in extremely love with eco friendly system.</p>

        <section class="container pt-5">
            <section class="row">
            <div class=" col-12 col-md-6 col-lg-4 pt-3">
                <div class="card">
                    <div class="card-body lav">
                      <h5 class="card-title">Expert Technicians</h5>
                      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                      
                    </div>
                  </div>
            </div>
            <div class=" col-12 col-md-6 col-lg-4 pt-3">
                <div class="card" >
                    <div class="card-body lav">
                      <h5 class="card-title">Profession Service</h5>
                      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                      
                    </div>
                  </div>
            </div>
            <div class=" col-12 col-md-6 col-lg-4 pt-3 ">
                <div class="card" >
                    <div class="card-body lav">
                      <h5 class="card-title">Great Support</h5>
                      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                      
                    </div>
                  </div>
            </div>
            <div class=" col-12 col-md-6 col-lg-4 pt-3 ">
                <div class="card" >
                    <div class="card-body lav">
                      <h5 class="card-title">Technical Skills</h5>
                      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                      
                    </div>
                  </div>
            </div>
            <div class=" col-12 col-md-6 col-lg-4 pt-3 ">
                <div class="card" >
                    <div class="card-body lav">
                      <h5 class="card-title">Highly Recomended</h5>
                      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content .</p>
                      
                    </div>
                  </div>
            </div>
            <div class=" col-12 col-md-6 col-lg-4 pt-3 ">
                <div class="card" >
                    <div class="card-body lav">
                      <h5 class="card-title">Positive Reviews </h5>
                      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                      
                    </div>
                  </div>
            </div>
            </section>
        </section>

    </section>

    <!-- Mark -->
    <section class="bg-dark  pt-5 pb-5">
        <div class="container" >
        <section class="d-md-flex gap-3">
            <div class=" bg-light">
                <div class="d-flex gap-3">
                    <div  class="p-2">
                        <img src="assets/img/product2.jpg" class="img-fluid">
                    </div>
                    <div class="p-2">
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Explicadicta labore sunt eius aperiam facere aut dolorum dolore harum alias.</p>
                        <h4>Mark Alviro Wiens</h4>
                        <p>CEO at Google </p>
                    </div>
                </div>
            </div>

            <div class=" bg-light border-top">
                <div class="d-flex gap-3">
                    <div  class="p-2">
                        <img src="assets/img/product2.jpg" class="img-fluid">
                    </div>
                    <div  class="p-2">
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Explicadicta labore sunt eius aperiam facere aut dolorum dolore harum alias.</p>
                        <h4>Mark Alviro Wiens</h4>
                        <p>CEO at Google </p>
                    </div>
                </div>
            </div>
        </section>
        </div>
    </section>

    <!-- Blog -->
    <section class="container pt-5" id="blog">
        <h1 class="home_h1 fw-bold text-center pt-5">Latest Glasses</h1>
        <p class="p-3 text-secondary text-center">Who are in extremely love with eco friendly system.</p>

        <div class="row">
        <div class="col-12 col-md-6 col-lg-4 pt-3">
            <div class="card" >
                <img src="assets/img/glasses1.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title text-Uppercase fw-bold">We do believe in Quality</h5>
                  <p class="card-text">Some quick example text to build on the card title and make up the  bulk of the card's  bulk of the card's content.</p>
                  <a href="#" class="text-dark read fw-bold">Read More</a>
                </div>
              </div>
        </div>

        <div class="col-12 col-md-6 col-lg-4 pt-3">
            <div class="card" >
                <img src="assets/img/glasses2.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title text-Uppercase fw-bold">We do believe in Quality</h5>
                  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  <a href="#" class="text-dark read fw-bold">Read More</a>
                </div>
              </div>
        </div>

        <div class="col-12 col-md-6 col-lg-4 pt-3">
            <div class="card" >
                <img src="assets/img/glasses3.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title text-Uppercase fw-bold">We do believe in Quality</h5>
                  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  <a href="#" class="text-dark read fw-bold">Read More</a>
                </div>
              </div>
        </div>

        

        </div>
    </section>

    <!-- Creative -->
    <section class="container laven mt-5 ">
        <div class="row ">
        <div class="col-12 col-md-4 col-lg">
            <img src="assets/img/foot1.png"  class="">
        </div>
        <div class="col-12 col-md-4 col-lg">
            <img src="assets/img/foot2.png" class="img-fluid">
        </div>
        <div class="col-12 col-md-4 col-lg">
            <img src="assets/img/foot3.png" class="img-fluid">
        </div>
        <div class="col-12 col-md-4 col-lg">
            <img src="assets/img/foot4.png" class="img-fluid">
        </div>
        <div class="col-12 col-md-4 col-lg">
            <img src="assets/img/foot5.png" class="img-fluid">
        </div>
        </div>
    </section>

    <!-- Contact  -->
    <section class="pt-5" id="contact">
        <h1 class="home_h1 fw-bold text-center">If you need, Just drop us a line</h1>
        <p class="p-3 text-secondary text-center">Who are in extremely love with eco friendly system.</p>

        
        <div class="container">
        <div class="row">
            <div class="col-12 col-md-6">
                <div class="pt-3">
                    <input type="text" placeholder="Enter your name" class="form-control">
                </div>
                <div class="pt-3">
                    <input type="email" placeholder="Enter email address" class="form-control">
                </div>
                <div class="pt-3">
                    <input type="text" placeholder="Enter your project" class="form-control">
                </div>

            </div>
            
            <div class="col-12 col-md-6">
                <div class="pt-3">
                    <textarea class="form-control" id="exampleFormControlTextarea1" rows="6" placeholder="Message" ></textarea>
                    <button type="button" class="btn btn-warning text-light button_warn p-2 mt-4">Send Message</button>
                </div>

            </div>
        </div>
        </div>
    </section>

    <!-- Footer -->
    <section class="black mt-5" id="pages">
    <section class="container pt-5">
        <div class="row">
        
        <div class="col-12 col-md-4 p-2">
            <h5>About Us </h5>
            <p class="text-secondary">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore dolore magna aliqua.</p>
        </div>
        <div class="col-12 col-md-4 p-2">
            <h5>Contact Us </h5>
            <p class="text-secondary">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore dolore magna aliqua.</p>
            <h3 class="text-warning fw-bold">012-6532-568-9746</h3>
            <h3 class="text-warning fw-bold">012-6532-569-9748</h3>
        </div>
        <div class="col-12 col-md-4 p-2">
            <h5>Newsletter </h5>
            <p class="text-secondary">You can trust us. we only send offers, not a single spam.</p>
            <div class="pt-3">
                <input type="email" placeholder="Enter email address" class="form-control">
            </div>
        </div>
        </div>
    </section>

    <div class="container d-md-flex justify-content-between pt-4 border-top">
        <div>
            <p>Copyright ©2025 All rights reserved | This template is made with  by <a href="#" class="text-warning"><span></span>GayatriPardeshi</a>
            </p>
        </div>
        <!-- <div>
            <a href="#"><img src="assets/img/facebook.png" class="img-fluid"></a>
            <a href="#"><img src="assets/img/twitter-sign.png" class="img-fluid"></a>
            <a href="#"><img src="assets/img/internet.png" class="img-fluid"></a>
            <a href="#"><img src="assets/img/instagram.png" class="img-fluid"></a>

        </div> -->
    </div>
    </section>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>


    <!-- link js  -->
    <script src="assets/js/main.js"></script>
</body>

</html>
