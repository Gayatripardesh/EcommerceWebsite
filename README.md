# Brainwave_Matrix_Intern-EcommereceWebsite
# HTML FILE
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

# CSS FILE
/* Google Fonts  */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');

/* Globals  */
*{
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    list-style: none;
    text-decoration: none;
    scroll-behavior: smooth;
    scroll-padding: 2rem;
}

body{
    overflow-x: hidden;
}
/* Variables  */
:root{
    --main-color: #fd4646;
    --sec-color: #4946fd;
    --text-color: #171427;
    --bg-color: #fff;
}
::selection{
    color: var(--text-color);
    background-color: var(--main-color);
}
.container{
    max-width: 1068px;
    margin: auto;
    width: 100%;
}
section{
    padding: 4rem 0 3rem;
}
body{
    color: var(--text-color);
}
img{
    width: 100%;
}

/* =======================================  */
/* HEADER  */
header{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: var(--bg-color);
    box-shadow: 0 1px 4px hsl(0 4% 15% / 10%);
    z-index: 100;
}
.nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 0;
}
.logo{
    font-size: 1.1rem;
    font-weight: 600;
    color: var(--sec-color);
    text-transform: uppercase;
}
.logo span{
    color: var(--main-color);
    font-weight: 700;
}
#cart-icon{
    font-size: 1.8rem;
    cursor: pointer;
}

/* CART  */
.cart{
    position: fixed;
    top: 0;
    right: 0;
    right: -100%; 
    width: 360px;
    height: 100vh;
    overflow-y: auto;
    overflow-x: hidden;
    padding: 20px;
    background-color: var(--bg-color);
    box-shadow: -2px solid 4px hsl(0 4% 15% / 10%);
    border: 1px solid var(--main-color);
    transition: 1.5s;
}
.cart.active{
    right: 0;
    transition: .5s;
}
.cart-title{
    text-align: center;
    font-size: 1.5rem;
    font-weight: 600;
    margin-top: 2rem;
}
.cart-box{
    display: grid;
    grid-template-columns: 32% 50% 18%;
    align-items: center;
    gap: 1rem;
    margin-top: 1rem;
}
.cart-img{
    width: 100px;
    height: 100px;
    object-fit: contain;
    padding: 10px;
}
.detail-box{
    display: grid;
    row-gap: .5rem;
}
.cart-product-title{
    font-size: 1rem;
    text-transform: uppercase;
}
.cart-price{
    font-weight: 500;
}
.cart-quantity{
    border: 1px solid var(--text-color);
    outline-color: var(--main-color);
    width: 2.4rem;
    text-align: center;
    font-size: 1rem;
}
.cart-remove{
    font-size: 24px;
    color: var(--main-color);
    cursor: pointer;
}
.total{
    display: flex;
    justify-content: flex-end;
    margin-top: 1.5rem;
    border-top: 1px solid var(--text-color);
}
.total-title{
    font-size: 1rem;
    font-weight: 600;
}
.total-price{
    margin-left: .5rem;
}
.btn-buy{
    display: flex;
    margin: 1.5rem auto 0 auto;
    padding: 12px 20px;
    border: none;
    background-color: var(--sec-color);
    color: var(--bg-color);
    font-size: 1rem;
    font-weight: 500;
    cursor: pointer;
}
.btn-buy:hover{
    background-color: var(--text-color);
}
#cart-close{
    position: absolute;
    top: 1rem;
    right: .8rem;
    font-size: 2rem;
    color: var(--text-color);
    cursor: pointer;
}

/* SHOP SECTION  */
.shop{
    margin-top: 2rem;
}
.section-title{
    font-style: 1.5rem;
    font-weight: 600;
    text-align: center;
    margin-bottom: 1.5rem;
}
.shop-content{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, auto));
    gap: 1.5rem;
}
.product-box{
    position: relative;
}
.product-box:hover{
    padding: 10px;
    border: 1px solid var(--text-color);
    transition: .4s;
}
.product-img{
    width: 100%;
    aspect-ratio: 1/1;
    object-fit: cover;
    margin-bottom: .5rem;
}
.product-title{
    font-size: 1.1rem;
    font-weight: 600;
    text-transform: uppercase;
    margin-bottom: .5rem;
}
.product-price{
    font-weight: 500;
}
.add-cart{
    position: absolute;
    bottom: 0;
    right: 0;
    background-color: var(--text-color);
    color: var(--bg-color);
    padding: 10px;
    cursor: pointer;
}
.add-cart:hover{
    background-color: hsl(249, 32%, 17%);
}


/* ================ RESPONSIVE & BREAKPOINTS ============= */
@media (max-width: 1080px){
    .nav{
        padding: 15px;
    }
    .container{
        width: 90%;
        margin: 0 auto;
    }
    section{
        padding: 3rem 0 2rem;
    }
    .shop{
        margin-top: 2rem;
    }
}

/* For Medium Devices */
@media (max-width: 400px){
    .nav{
        padding: 11px;
    }
    .logo{
        font-size: 1rem;
    }
    .cart{
        width: 320px;
    }
}

/* For Small Devices */
@media (max-width: 360px){
    .shop{
        margin-top: 1rem;
    }
    .cart{
        width: 280px;
    }
}



.navspan{
    display: none;
    font-size: 20px;
    color: var(--text-color);
}

.bx-phone{
    color: var(--text-color);
}

.bx-home-alt-2{
    color: var(--text-color);
}

@media(min-width:678px){
    .navspan{
        display: block;
    }
}

.new{
    margin-top: 20px;
    margin-bottom: 20px;
    text-align: center;
}



/*  */

.abc{
    background-color: rgb(234, 234, 247);
}

.abc:hover{
    background-color: #FFC436;
    
}

@media(min-width:768px){
    .fit{
        width: 99%;
        margin: 0 auto;
    }
}

.lav{
    background-color: rgb(234, 234, 247);
}

.lav:hover{
    background-color: #FFC436;
}

.read{
    text-decoration: none;
}

.laven{
    background-color: rgb(234, 234, 247);
}

.black{
    background-color: #222222;
    color: white;
}

.foota{
    text-decoration: none;
}

# JAVASCRIPT FILE
// OPEN & CLOSE CART
const cartIcon = document.querySelector("#cart-icon");
const cart = document.querySelector(".cart");
const closeCart = document.querySelector("#cart-close");

cartIcon.addEventListener("click", () => {
  cart.classList.add("active");
});

closeCart.addEventListener("click", () => {
  cart.classList.remove("active");
});

// Start when the document is ready
if (document.readyState == "loading") {
  document.addEventListener("DOMContentLoaded", start);
} else {
  start();
}

// =============== START ====================
function start() {
  addEvents();
}

// ============= UPDATE & RERENDER ===========
function update() {
  addEvents();
  updateTotal();
}

// =============== ADD EVENTS ===============
function addEvents() {
  // Remove items from cart
  let cartRemove_btns = document.querySelectorAll(".cart-remove");
  console.log(cartRemove_btns);
  cartRemove_btns.forEach((btn) => {
    btn.addEventListener("click", handle_removeCartItem);
  });

  // Change item quantity
  let cartQuantity_inputs = document.querySelectorAll(".cart-quantity");
  cartQuantity_inputs.forEach((input) => {
    input.addEventListener("change", handle_changeItemQuantity);
  });

  // Add item to cart
  let addCart_btns = document.querySelectorAll(".add-cart");
  addCart_btns.forEach((btn) => {
    btn.addEventListener("click", handle_addCartItem);
  });

  // Buy Order
  const buy_btn = document.querySelector(".btn-buy");
  buy_btn.addEventListener("click", handle_buyOrder);
}

// ============= HANDLE EVENTS FUNCTIONS =============
let itemsAdded = [];

function handle_addCartItem() {
  let product = this.parentElement;
  let title = product.querySelector(".product-title").innerHTML;
  let price = product.querySelector(".product-price").innerHTML;
  let imgSrc = product.querySelector(".product-img").src;
  console.log(title, price, imgSrc);

  let newToAdd = {
    title,
    price,
    imgSrc,
  };

  // handle item is already exist
  if (itemsAdded.find((el) => el.title == newToAdd.title)) {
    alert("This Item Is Already Exist!");
    return;
  } else {
    itemsAdded.push(newToAdd);
  }

  // Add product to cart
  let cartBoxElement = CartBoxComponent(title, price, imgSrc);
  let newNode = document.createElement("div");
  newNode.innerHTML = cartBoxElement;
  const cartContent = cart.querySelector(".cart-content");
  cartContent.appendChild(newNode);

  update();
}

function handle_removeCartItem() {
  this.parentElement.remove();
  itemsAdded = itemsAdded.filter(
    (el) =>
      el.title !=
      this.parentElement.querySelector(".cart-product-title").innerHTML
  );

  update();
}

function handle_changeItemQuantity() {
  if (isNaN(this.value) || this.value < 1) {
    this.value = 1;
  }
  this.value = Math.floor(this.value); // to keep it integer

  update();
}

function handle_buyOrder() {
  if (itemsAdded.length <= 0) {
    alert("There is No Order to Place Yet! \nPlease Make an Order first.");
    return;
  }
  const cartContent = cart.querySelector(".cart-content");
  cartContent.innerHTML = "";
  alert("Your Order is Placed Successfully :)");
  itemsAdded = [];

  update();
}

// =========== UPDATE & RERENDER FUNCTIONS =========
function updateTotal() {
  let cartBoxes = document.querySelectorAll(".cart-box");
  const totalElement = cart.querySelector(".total-price");
  let total = 0;
  cartBoxes.forEach((cartBox) => {
    let priceElement = cartBox.querySelector(".cart-price");
    let price = parseFloat(priceElement.innerHTML.replace("$", ""));
    let quantity = cartBox.querySelector(".cart-quantity").value;
    total += price * quantity;
  });

  // keep 2 digits after the decimal point
  total = total.toFixed(2);
  // or you can use also
  // total = Math.round(total * 100) / 100;

  totalElement.innerHTML = "$" + total;
}

// ============= HTML COMPONENTS =============
function CartBoxComponent(title, price, imgSrc) {
  return `
    <div class="cart-box">
        <img src=${imgSrc} alt="" class="cart-img">
        <div class="detail-box">
            <div class="cart-product-title">${title}</div>
            <div class="cart-price">${price}</div>
            <input type="number" value="1" class="cart-quantity">
        </div>
        <!-- REMOVE CART  -->
        <i class='bx bxs-trash-alt cart-remove'></i>
    </div>`;
}
