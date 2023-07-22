### Domain Hosting for the project
*  https://ornate-bienenstitch-1711fe.netlify.app/
###
The project uses html, css and javascript to run, there's no need for installing any package at the moment


https://www.figma.com/file/MZICCjaOIpIJILsqzzMJck/Grocery-Store?node-id=396%3A740&mode=dev

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Name????</title>
    <!-- swiper cdn  -->
  
    <link rel="stylesheet"href="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.css"/>
    <!-- font awesome cdn link -->
    
    <link rel="stylesheet" href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css'>
   
    <!-- custom css file link -->
    <link rel="stylesheet" href="./css/style.css">
</head>
<body>

    <!-- header section starts -->
    <header class="header">
        <a href="#" class="logo"> <img src="" alt="logo"></a>
            <!-- <i class="fas fa-shopping-basket"></i> groco</a> -->
        
        <nav class="navbar">
           <a href="#home">Home</a> 
           <!-- <a href="#features">Features</a>  -->
           <a href="#products">Products</a> 
           <a href="#categories">Categories</a> 
           <!-- <a href="#review">Review</a> 
           <a href="#blogs">Blog</a>  -->
        </nav>
        
        <div class="icons">
            <div class="fas fa-bars" id="menu-btn"></div>
            <div class="fas fa-search" id="search-btn"></div>
            <div class="fas fa-shopping-cart" id="cart-btn"></div>
           
        </div> 
        <div class="reg" id="login-btn"><p>Register</p></div>
        <form action="" class="search-form">
            <input type="search" placeholder="search here..." id="search-box">
            <label for="search-box" class="fas fa-search"></label>
        </form>
        <div class="shopping-cart">
            <div class="box">
                <i class="fas fa-trash"></i>
                <img src="image/cart-img-1.png" alt="cart-img-1">
                <div class="content">
                    <h3>watermelon</h3>
                    <span class="price">$4.99/-</span>
                    <span class="quantity">qty : 1</span>
                </div>
            </div>
            <div class="box">
                <i class="fas fa-trash"></i>
                <img src="image/cart-img-2.png" alt="cart-img-2">
                <div class="content">
                    <h3>onion</h3>
                    <span class="price">$4.99/-</span>
                    <span class="quantity">qty : 1</span>
                </div>
            </div>
            <div class="box">
                <i class="fas fa-trash"></i>
                <img src="image/cart-img-3.png" alt="cart-img-3">
                <div class="content">
                    <h3>chicken</h3>
                    <span class="price">$4.99/-</span>
                    <span class="quantity">qty : 1</span>
                </div>
            </div>
            <div class="total">total : $19.69/- </div>
            <a href="#" class="btn">checkout</a>
        </div>
        <form action="" class="login-form">
            <h3>Login now</h3>
            <input type="email" placeholder="your email" class="box">
            <input type="password" placeholder="your password" class="box">
            <p>forget your password <a href="#">click here</a></p>
            <p>don't have an account <a href="#">create now</a></p>
            <input type="submit" value="login now" class="btn">
        </form>
    </header>
    <!-- header section ends -->
<!-- home section starts -->
<section class="home" id="home">
    <div class="left">
        <i class="fa-brands fa-twitter"></i>
        <i class="fas fa-twitter">twitter</i>
        <i class="fas fa-twitter">twitter</i>
        <p>folow on</p>
    </div>
    <div class="content">
        
        <h1>Groceries 
            Made Easy!!!!</h1>
        <p>Experience Seamless Shopping and Fresh Deliveries at Your Convenience</p>
         <a href="#" class="btn-shop">shop now</a>
    </div>
    <div>
        <img src="./images/food-basket-removebg-preview (1) 1.png" alt="">
    </div>
</section>
<!-- home section ends -->

<!-- features section starts -->
<section class="features" id="features">
    <!-- <h1 class="heading">Our <span>features</span></h1> -->
    <div class="box-container">
        <div class="box">
            <div>
                <button class="reg">free delivery</button>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente, esse.</p>
                <a href="#" class="reg">Shop Now</a>
            </div>
            <img src="images/unsplash_wU_TbWqdPJI.png" alt="">         
        </div>
        <div class="box">
            <div>
                <button class="reg">60% off</button>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente, esse.</p>
                <a href="#" class="btn">Order now</a>
            </div>
            <img src="images/unsplash_nXKDqpmdx_8 1.png" alt="">         
        </div>
        <!-- <div class="box">
            <img src="image/feature-img-3.png" alt="">
            <h3>easy payment</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente, esse.</p>
            <a href="#" class="btn">read more</a>
        </div> -->
    </div>
</section>

<!-- features section ends -->
<!-- product section start  -->
<section class="products" id="products">
    <div class="heading">
        <h2>100% Organic Food Provide</h2>
         <h1>Browse All Categories</h1>
          <p>Sticky niche markets via goal-oriented networks Completely recapitualise</p>
    </div>
    <div class="swiper product-slider">
        <div class="swiper-wrapper">
            <div class="swiper-slide box">
                <img src="image/product-1.png" alt="">
                <h3>fresh orange</h3>
                <div class="price">$4.99/- - 10.99/- </div>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <a href="#" class="btn">add to cart</a>
            </div>
            <div class="swiper-slide box">
                <img src="image/product-2.png" alt="">
                <h3>fresh onion</h3>
                <div class="price">$4.99/- - 10.99/- </div>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <a href="#" class="btn">add to cart</a>
            </div>
            <div class="swiper-slide box">
                <img src="image/product-3.png" alt="">
                <h3>fresh meat</h3>
                <div class="price">$4.99/- - 10.99/- </div>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <a href="#" class="btn">add to cart</a>
            </div>
            <div class="swiper-slide box">
                <img src="image/product-4.png" alt="">
                <h3>fresh cabbage</h3>
                <div class="price">$4.99/- - 10.99/- </div>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <a href="#" class="btn">add to cart</a>
            </div>
           

        </div>
    </div>
    <div class="swiper product-slider">
        <div class="swiper-wrapper">
            <div class="swiper-slide box">
                <img src="image/product-5.png" alt="">
                <h3>fresh potato</h3>
                <div class="price">$4.99/- - 10.99/- </div>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <a href="#" class="btn">add to cart</a>
            </div>
            <div class="swiper-slide box">
                <img src="image/product-6.png" alt="">
                <h3>fresh avocado</h3>
                <div class="price">$4.99/- - 10.99/- </div>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <a href="#" class="btn">add to cart</a>
            </div>
            <div class="swiper-slide box">
                <img src="image/product-7.png" alt="">
                <h3>fresh carrot</h3>
                <div class="price">$4.99/- - 10.99/- </div>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <a href="#" class="btn">add to cart</a>
            </div>
            <div class="swiper-slide box">
                <img src="image/product-8.png" alt="">
                <h3>green lemon</h3>
                <div class="price">$4.99/- - 10.99/- </div>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <a href="#" class="btn">add to cart</a>
            </div>
        </div>
    </div>



</section>


<!-- product section ends  -->

<!-- Categories section starts  -->
<section class="categories" id="categories">
    <h1 class="heading">product <span>categories</span></h1>
    <div class="box-container">
        <div class="box">
            <img src="image/cat-1.png" alt="">
            <h3>vegitables</h3>
            <p>upto 45% off</p>
            <a href="#" class="btn">shop now</a>
        </div>
        <div class="box">
            <img src="image/cat-2.png" alt="">
            <h3>fresh fruits</h3>
            <p>upto 45% off</p>
            <a href="#" class="btn">shop now</a>
        </div>
        <div class="box">
            <img src="image/cat-3.png" alt="">
            <h3>dairy products</h3>
            <p>upto 45% off</p>
            <a href="#" class="btn">shop now</a>
        </div>
        <div class="box">
            <img src="image/cat-4.png" alt="">
            <h3>fresh meat</h3>
            <p>upto 45% off</p>
            <a href="#" class="btn">shop now</a>
        </div>
    </div>
</section>


<!-- Categories section ends  -->

<!-- review section start  -->
<section class="review" id="review">
    <h1 class="heading">customer's <span>review</span></h1>
    <div class="swiper review-slider">
        <div class="swiper-wrapper">
            <div class="swiper-slide box">
                <img src="image/pic-1.png" alt="">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut officia commodi ipsa. Quos fugiat, quas nostrum eveniet consequuntur dolorum sed.</p>
                <h3>john deo</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
            </div>
            <div class="swiper-slide box">
                <img src="image/pic-2.png" alt="">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut officia commodi ipsa. Quos fugiat, quas nostrum eveniet consequuntur dolorum sed.</p>
                <h3>john deo</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
            </div>
            <div class="swiper-slide box">
                <img src="image/pic-3.png" alt="">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut officia commodi ipsa. Quos fugiat, quas nostrum eveniet consequuntur dolorum sed.</p>
                <h3>john deo</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
            </div>
            <div class="swiper-slide box">
                <img src="image/pic-4.png" alt="">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut officia commodi ipsa. Quos fugiat, quas nostrum eveniet consequuntur dolorum sed.</p>
                <h3>john deo</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
            </div>
        </div>
    </div>
</section>




<!-- review section ends  -->
<!-- blogs section starts  -->
<section class="blogs" id="blogs">
    <h1 class="heading">our <span>blogs</span></h1>
    <div class="box-container">
        <div class="box">
            <img src="image/blog-1.jpg" alt="">
            <div class="content">
                <div class="icons">
                    <a href="#"> <i class="fas fa-user"></i> by user</a>
                    <a href="#"> <i class="fas fa-calendar"></i> 1st may, 2021</a>
                </div>
                <h3>fresh and organic vegitables and fruits</h3>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Perspiciatis officiis sunt nostrum culpa at amet!</p>
                <a href="#" class="btn">read more</a>
            </div>
        </div>
        <div class="box">
            <img src="image/blog-2.jpg" alt="">
            <div class="content">
                <div class="icons">
                    <a href="#"> <i class="fas fa-user"></i> by user</a>
                    <a href="#"> <i class="fas fa-calendar"></i> 1st may, 2021</a>
                </div>
                <h3>fresh and organic vegitables and fruits</h3>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Perspiciatis officiis sunt nostrum culpa at amet!</p>
                <a href="#" class="btn">read more</a>
            </div>
        </div>
        <div class="box">
            <img src="image/blog-3.jpg" alt="">
            <div class="content">
                <div class="icons">
                    <a href="#"> <i class="fas fa-user"></i> by user</a>
                    <a href="#"> <i class="fas fa-calendar"></i> 1st may, 2021</a>
                </div>
                <h3>fresh and organic vegitables and fruits</h3>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Perspiciatis officiis sunt nostrum culpa at amet!</p>
                <a href="#" class="btn">read more</a>
            </div>
        </div>
    </div>
</section>
<!-- blogs section ends  -->

<!-- footer section starts  -->
<section class="footer">
    <div class="box-container">
        <div class="box">
            <h3>groco <i class="fas fa-shopping-basket"></i></h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus, non.</p>
            <div class="share">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="#" class="fab fa-twitter"></a>
                <a href="#" class="fab fa-instagram"></a>
                <a href="#" class="fab fa-linkedin"></a>
            </div>
        </div>
        <div class="box">
            <h3>contact info</h3>
            <a href="" class="links"> <i class="fas fa-phone"></i> +234903067992</a>
            <a href="" class="links"> <i class="fas fa-phone"></i> +234903067992</a>
            <a href="" class="links"> <i class="fas fa-envelope"></i> bossman@gmail.com</a>
            <a href="" class="links"> <i class="fas fa-map-marker-alt"></i> ibadan</a>
        </div>
        <div class="box">
            <h3>quick links</h3>
            <a href="" class="links"> <i class="fas fa-arrow-right"></i> home</a>
            <a href="" class="links"> <i class="fas fa-arrow-right"></i> features</a>
            <a href="" class="links"> <i class="fas fa-arrow-right"></i> products</a>
            <a href="" class="links"> <i class="fas fa-arrow-right"></i> categories</a>
            <a href="" class="links"> <i class="fas fa-arrow-right"></i> review</a>
            <a href="" class="links"> <i class="fas fa-arrow-right"></i> blogs</a>
        </div>
        <div class="box">
            <h3>newsletter</h3>
           <p>subscribe for latest updates</p>
           <input type="email" placeholder="your email" class="email">
           <input type="submit" value="subscribe" class="btn">
           <img src="image/payment.png" class="payment-img">
        </div>
    </div>
    <div class="credit">
        created by <span>Bossman</span> | all rights reserved
    </div>
    
</section>
<!-- footer section ends  -->






<script src="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.js"></script>
    <!-- <script src="https://unpkg.com/swiper@7/swiper-bundle.min.js"></script> -->
    <!-- custom js file link -->
    <script src="./js/script.js"></script>
</body>
</html>