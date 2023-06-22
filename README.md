# Ex-02 Create a commercial website using HTML & CSS
## AIM:-
To create a commercial website using HTML & CSS.

## PROCEDURE:-
### STEP 1:
Create basic outline for website using html.

### STEP 2:
Create style part of the website using css.

### STEP 3:
Link the css file with html code using link tag

### STEP 4:
Run the code and check the webpage in an web browser.

## PROGRAM:-
#### Developed By : Sarankumar J
#### Register Number : 212221230087
### HTML:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Bakery Website</title>
    <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css" />


    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Caveat:wght@700&family=Dancing+Script:wght@600&family=Montserrat:wght@700&display=swap" rel="stylesheet">
    

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery-js/1.4.0/css/lightgallery.min.css">

    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    


    <header class="header">

        <a href="#" class="logo"> <i class="fas fa-bread-slice"></i> bakery </a>

        <nav class="navbar">
            <a href="#home">home</a>
            <a href="#about">about</a>
            <a href="#product">product</a>
            <a href="#gallery">gallery</a>
            <a href="#team">team</a>
            <a href="#review">review</a>
            <a href="#order">order</a>
        </nav>

        <div class="icons">
            <div id="cart-btn" class="fas fa-shopping-cart"></div>
            <div id="menu-btn" class="fas fa-bars"></div>
        </div>

    </header>

   

    <section class="home" id="home">

       <img class="we" src="1.jpg">
        <div class="bg-image"></div>

        <div class="bg-text">
          <h1 class="words">"Step into our bakery and experience the magic of freshly baked goodness. Every treat we make is a little piece of heaven, crafted with love and served with a smile. Welcome to our world of delicious delights."</h1>
          <p>And </p>
        </div>

    </section>


    <section class="banner">
        <img src="images/banner.png" alt="">
    </section>



    <section class="about" id="about">

        <h1 class="heading"> <span>about</span> us </h1>

        <div class="row">

            <div class="image">
                <img src="images/about.png" alt="">
            </div>

            <div class="content">
                <h3>good things come to those <span>who bake </span> for others</h3>
                <p>"At Our Bakery, we're passionate about crafting delectable cakes that leave a lasting impression. Indulge in our exquisite creations and experience a taste that's simply divine.".</p>
                <p>baking artistry meets irresistible flavors. From elegant wedding cakes to whimsical birthday creations, we pride ourselves in delivering mouthwatering treats that bring joy to every celebration.</p>
                <a href="#" class="btn">read more</a>
            </div>

        </div>

    </section>


    

    <section class="product" id="product">

        <h1 class="heading">our <span> products</span></h1>

        <div class="box-container">

            <div class="box">
                <div class="image">
                    <img src="images/product-1.jpg" alt="">
                </div>
                <div class="content">
                    <h3>apple pie</h3>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <span class="price">$15.99</span>
                    <a href="#" class="btn">add to cart</a>
                </div>
            </div>

            <div class="box">
                <div class="image">
                    <img src="images/product-2.jpg" alt="">
                </div>
                <div class="content">
                    <h3>pakcakes+</h3>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <span class="price">$18.99</span>
                    <a href="#" class="btn">add to cart</a>
                </div>
            </div>

            <div class="box">
                <div class="image">
                    <img src="images/product-3.jpg" alt="">
                </div>
                <div class="content">
                    <h3>breads</h3>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <span class="price">$11.99</span>
                    <a href="#" class="btn">add to cart</a>
                </div>
            </div>

            <div class="box">
                <div class="image">
                    <img src="images/product-4.jpg" alt="">
                </div>
                <div class="content">
                    <h3>cake</h3>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <span class="price">$15.99</span>
                    <a href="#" class="btn">add to cart</a>
                </div>
            </div>

            <div class="box">
                <div class="image">
                    <img src="images/product-5.jpg" alt="">
                </div>
                <div class="content">
                    <h3>pan cake</h3>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <span class="price">$27.99</span>
                    <a href="#" class="btn">add to cart</a>
                </div>
            </div>

            <div class="box">
                <div class="image">
                    <img src="images/product-6.jpg" alt="">
                </div>
                <div class="content">
                    <h3>apple pie</h3>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <span class="price">$25.99</span>
                    <a href="#" class="btn">add to cart</a>
                </div>
            </div>

        </div>

    </section>


   

    <section class="gallery" id="gallery">

        <h1 class="heading">our <span> gallery</span></h1>

        <div class="gallery-container">

            <a href="images/gallery1.jpg" class="box">
                <img src="images/gallery1.jpg" alt="">
                <div class="icons"><i class="fas fa-plus"></i></div>
            </a>

            <a href="images/gallery2.jpg" class="box">
                <img src="images/gallery2.jpg" alt="">
                <div class="icons"><i class="fas fa-plus"></i></div>
            </a>

            <a href="images/gallery3.jpg" class="box">
                <img src="images/gallery3.jpg" alt="">
                <div class="icons"><i class="fas fa-plus"></i></div>
            </a>

            <a href="images/gallery4.jpg" class="box">
                <img src="images/gallery4.jpg" alt="">
                <div class="icons"><i class="fas fa-plus"></i></div>
            </a>

            <a href="images/gallery5.jpg" class="box">
                <img src="images/gallery5.jpg" alt="">
                <div class="icons"><i class="fas fa-plus"></i></div>
            </a>

            <a href="images/gallery6.jpg" class="box">
                <img src="images/gallery6.jpg" alt="">
                <div class="icons"><i class="fas fa-plus"></i></div>
            </a>

        </div>

    </section>

  

    <section class="promotion">

        <h1 class="heading">weekly <span>promotions</span></h1>

        <div class="box-container">

            <div class="box">
                <div class="content">
                    <h3>chocolat cake</h3>
                    <p>.</p>
                </div>

                <img src="images/promotion1.png" alt="">
            </div>

            <div class="box">
                <img src="images/promotion2.png" alt="">
                <div class="content">
                    <h3>nut cake</h3>
                    <p>.</p>
                </div>
                
            </div>

        </div>

    </section>

   

    <section class="team" id="team">

        <h1 class="heading">our  <span>team</span></h1>

        <div class="box-container">

            <div class="box">
                <div class="image">
                    <img src="data:image/png;base64,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" alt="">
                </div>
                <div class="content">
                    <h3>erica lacy</h3>
                    <p>CEO</p>
                    <div class="share">
                        <i class="fab fa-facebook-f"></i>
                        <i class="fab fa-twitter"></i>
                        <i class="fab fa-instagram"></i>
                    </div>
                </div>
            </div>

            <div class="box">
                <div class="image">
                    <img src="data:image/png;base64,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" alt="">
                </div>
                <div class="content">
                    <h3>doe lacy</h3>
                    <p>manager</p>
                    <div class="share">
                        <i class="fab fa-facebook-f"></i>
                        <i class="fab fa-twitter"></i>
                        <i class="fab fa-instagram"></i>
                    </div>
                </div>
            </div>

            <div class="box">
                <div class="image">
                    <img src="data:image/png;base64,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" alt="">
                </div>
                <div class="content">
                    <h3>john lacy</h3>
                    <p>manager</p>
                    <div class="share">
                        <i class="fab fa-facebook-f"></i>
                        <i class="fab fa-twitter"></i>
                        <i class="fab fa-instagram"></i>
                    </div>
                </div>
            </div>

        </div>

    </section>

   

    <section class="review" id="review">

        <h1 class="heading"> customer's <span>review</span> </h1>

        <div class="box-container">

            <div class="box">
                <img src="https://st4.depositphotos.com/15648834/23779/v/600/depositphotos_237795814-stock-illustration-unknown-person-silhouette-glasses-profile.jpg" class="user" alt="">
                <h3>lacy deo</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <p>cook.</p>
            </div>

            <div class="box">
                <img src="https://st4.depositphotos.com/15648834/23779/v/600/depositphotos_237795814-stock-illustration-unknown-person-silhouette-glasses-profile.jpg" class="user" alt="">
                <h3>lacy deo</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <p>cook.</p>
            </div>

            <div class="box">
                <img src="https://st4.depositphotos.com/15648834/23779/v/600/depositphotos_237795814-stock-illustration-unknown-person-silhouette-glasses-profile.jpg" class="user" alt="">
                <h3>lacy deo</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <p>cook.</p>
            </div>

        </div>

    </section>

  

    <section class="order" id="order">

        <h1 class="heading"><span>order</span> now </h1>

        <div class="row">

            <div class="image">
                <img src="https://img.freepik.com/premium-vector/happy-guy-apron-mixing-ingredients-preparing-dough-bowl-vector-flat-illustration-smiling-man-cooking-dessert-kitchen-table-isolated-white-preparation-homemade-pastry-baking_198278-14614.jpg" alt="">
            </div>

            <form action="">

                <div class="inputBox">
                    <input type="text" placeholder="first name">
                    <input type="text" placeholder="last name">
                </div>

                <div class="inputBox">
                    <input type="email" placeholder="email address">
                    <input type="number" placeholder="phone number">
                </div>

                <div class="inputBox">
                    <input type="text" placeholder="food name">
                    <input type="number" placeholder="how much">
                </div>

                <textarea placeholder="your address" name="" id="" cols="30" rows="10"></textarea>
                <input type="submit" value="order now" class="btn">
            </form>

        </div>

    </section>

   
    <section class="footer">

        <div class="box-container">

            <div class="box">
                <h3>address</h3>
                <p>1989 Barfield Lane,Indianapolis,Indiana.</p>
                <div class="share">
                    <a href="#" class="fab fa-facebook-f"></a>
                    <a href="#" class="fab fa-twitter"></a>
                    <a href="#" class="fab fa-instagram"></a>
                    <a href="#" class="fab fa-linkedin"></a>
                </div>
            </div>

            <div class="box">
                <h3>E-mail</h3>
                <a href="#" class="link">cakes@gmail.com</a>
                <a href="#" class="link">cakes@gmail.com</a>
            </div>

            <div class="box">
                <h3>call us</h3>
                <p> 1478 2369</p>
                <p> 1478 2369</p>
            </div>

            <div class="box">
                <h3> opening hours</h3>
                <p>Monday - Friday: 9:00 - 23:00 <br> Saturday: 8:00 - 24:00 </p>
            </div>

        </div>

       

    </section>
</body>
</html>
```
### CSS:
```css
@import url('https://fonts.googleapis.com/css2?family=Vidaloka&display=swap');

:root{
  --primary-color:  #c98d83;
  --secondary : #783b31;
  --bg: #f2f1ec;
  --black: #000;
  --white: #fff;
  --box-shadow: 0 .5rem 1rem rgba(0, 0, 0, 0.1);
}

*{
  font-family: 'Vidaloka', sans-serif;
  margin:0; padding:0;
  box-sizing: border-box;
  outline: none; border:none;
  text-decoration: none;
  text-transform: capitalize;
  transition: .2s linear;
}

html{
  font-size: 62.5%;
  overflow-x: hidden;
  scroll-padding-top: 9rem;
  scroll-behavior: smooth;
}

html::-webkit-scrollbar{
  width: .8rem;
}

html::-webkit-scrollbar-track{
  background: transparent;
}

html::-webkit-scrollbar-thumb{
  background: var(--primary-color);
  border-radius: 5rem;
}

section{
  padding: 2rem 7%;
}

.heading{
  text-align: center;
  color: var(--primary-color);
  text-transform: uppercase;
  margin-bottom: 3rem;
  padding: 1.2rem 0;
  font-size: 4rem;
}

.heading span{
  color: var(--secondary);
  text-transform: uppercase;
}

.btn{
  margin-top: 1rem;
  display: inline-block;
  padding: 1rem 3rem;
  font-size: 1.7rem;
  color: var(--white);
  border-radius: .5rem;
  box-shadow: var(--box-shadow);
  background: var(--primary-color);
  cursor: pointer;
}

.btn:hover{
  background: var(--secondary);
}

/* header */

.header{
  position: fixed;
  top: 0; left: 0; right: 0;
  z-index: 1000;
  background: var(--bg);
  box-shadow: var(--box-shadow);
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 2rem 9%;
}

.header .logo{
  font-size: 2.5rem;
  font-weight: bolder;
  color: var(--black);
}

.header .logo i{
  color: var(--secondary);
  padding-right: .5rem;
}

.header .navbar a{
  font-size: 1.7rem;
  color: var(--black);
  margin: 0 1rem;
}

.header .navbar a:hover{
  color: var(--primary-color);
}

.header .icons div{
  font-size: 2.5rem;
  margin-left: 1.7rem;
  color: var(--black);
  cursor: pointer;
}

.header .icons div:hover{
  color: var(--primary-color);
}

#menu-btn{
  display: none;
}

/* shopping cart */

.cart-items-container{
  position: fixed;
  top: 0; right: -105%;
  width: 35rem;
  background: var(--white);
  display: flex;
  flex-flow: column;
  gap: 2rem;
  justify-content: center;
  height: 100%;
  z-index: 1200;
  padding: 2rem;
  text-align: center;
}

.cart-items-container.active{
  right: 0;
  box-shadow: 0 0 0 100vw rgba(0, 0, 0, 0.8);
}

.cart-items-container #close-form{
  position: absolute;
  top: 1.5rem;
  right: 2.5rem;
  font-size: 4rem;
  cursor: pointer;
  color: var(--black);
}

.cart-items-container #close-form:hover{
  transform: rotate(90deg);
  color: var(--primary-color);
}

.cart-items-container .title{
  font-size: 2.5rem;
  color: var(--secondary);
  text-transform: uppercase;
  letter-spacing: .2rem;
}

.cart-items-container .cart-item{
  position: relative;
  margin: 1rem 0;
  display: flex;
  align-items: center;
  gap: 1.5rem;
}

.cart-items-container .cart-item .fa-times{
  position: absolute;
  top: 1rem; right: 1rem;
  font-size: 2rem;
  color: var(--black);
  cursor: pointer;
}

.cart-items-container .cart-item .fa-times:hover{
  color: var(--primary-color);
}

.cart-items-container .cart-item img{
  height: 7rem;
}

.cart-items-container .cart-item .content h3{
  font-size: 2rem;
  color: var(--black);
  padding-bottom: .5rem;
}

.cart-items-container .cart-item .content .price{
  font-size: 1.5rem;
  color: var(--primary-color);
  text-align: left;
}

/* end */

/* home */

@keyframes fadeIn{
  0%{
    transform: translateY(-4rem) scale(1.1);
    opacity: 0;
  }
}

.home{
  padding: 0;
}

.home .slide{
  min-height: 100vh;
  background-size: cover !important;
  background-position: center !important;
  display: flex;
  align-items: center;
  justify-content: center;
}

.home .slide::before{
  content: '';
  position: absolute;
  top: 0; left: 0;
  height: 100%; width: 100%;
  background: rgba(0, 0, 0, 0.7);
  z-index: -1;
}

.home .slide .content{
  text-align: center;
  width: 70rem;
  display: none;
}

.home .slide .content h3{
  font-size: 6rem;
  text-transform: uppercase;
  color: var(--white);
  line-height: 1.2;
  padding: 2rem 0;
  animation: fadeIn 0.4s cubic-bezier(.54, 1.3,.63,1.34) .2s backwards;
}

.home .slide .content .btn{
  animation: fadeIn 0.4s cubic-bezier(.54, 1.3,.63,1.34) .4s backwards;
}

.home .swiper-slide-active .content{
  display: inline-block;
}

.swiper-button-next,
.swiper-button-prev{
  height: 4rem;
  width: 4rem;
  line-height: 4rem;
  margin-left: 1.5rem;
  background: var(--white);
  color: var(--black);
}

.swiper-button-next:hover,
.swiper-button-prev:hover{
  background: var(--primary-color);
  color: var(--white);
}

.swiper-button-next::after,
.swiper-button-prev::after{
  font-size: 1.5rem;
}

/* end */

/* banner */

.banner{
  background: url(../images/banner-bg.jpg);
  background-size: cover !important;
  background-position: center !important;
}

.banner img{
  margin-top: 3rem;
  height: 100%;
  width: 100%;
}

/* banner end*/

/* about */

.about .row{
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 2rem;
}

.about .row .image{
  flex: 1 1 40rem;
}

.about .row .image img{
  width: 100%;
  height: 100%;
}

.about .row .content{
  flex: 1 1 40rem;
}

.about .row .content h3{
  color: var(--black);
  font-size: 3.5rem;
  line-height: 1.5;
}

.about .row .content h3 span{
  color: var(--secondary);
}

.about .row .content p{
  font-size: 1.4rem;
  color: #444;
  padding: 1rem 0;
  line-height: 2;
}

/* about end*/

/* product */

.product{
  background: var(--bg);
}

.product .box-container{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(30rem,1fr));
  gap: 2rem;
}

.product .box-container .box{
  background: var(--white);
  border-radius: .5rem;
  box-shadow: var(--box-shadow);
  position: relative;
  overflow: hidden;
  text-align: center;
}

.product .box-container .box .image{
  height: 35rem;
  width: 100%;
  padding: 1.1rem;
}

.product .box-container .box .image img{
  height: 100%;
  width: 100%;
  border-radius: .5rem;
  object-fit: cover;
}

.product .box-container .box .content{
  padding: 2rem;
  padding-top: 0;
}

.product .box-container .box .content h3{
  color: var(--black);
  font-size: 2.5rem;
}

.product .box-container .box .content .stars{
  padding: 1rem 0;
}

.product .box-container .box .content .stars i{
  font-size: 1.7rem;
  color: var(--secondary);
}

.product .box-container .box .content .price{
  font-size: 2.5rem;
  font-weight: bolder;
  color: var(--secondary);
  margin-right: 1rem;
}

/* product end */

/* gallery */

.gallery .gallery-container{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
  gap: 2rem;
}

.gallery .gallery-container .box{
  height: 40rem;
  position: relative;
  overflow: hidden;
}

.gallery .gallery-container .box img{
  height: 100%;
  width: 100%;
  object-fit: cover;
}

.gallery .gallery-container .box:hover img{
  transform: scale(1.1);
}

.gallery .gallery-container .box .icons{
  display: none;
  align-items: center;
  justify-content: center;
  position: absolute;
  top: 0; left: 0;
  z-index: 10;
  height: 100%;
  width: 100%;
  background: rgba(0, 0, 0, 0.7);
}

.gallery .gallery-container .box .icons i{
  font-size: 6rem;
  color: var(--white);
}

.gallery .gallery-container .box:hover .icons{
  display: flex;
}


/* gallery end*/


/* weekly promotions */

.promotion{
  background: url(../images/promotion.jpg) no-repeat;
  background-size: cover !important;
  background-position: center !important;
}

.promotion .box-container{
  display: flex;
  flex-wrap: wrap;
  padding-bottom: 4rem;
}

.promotion .box-container .box{
  flex: 1 1 55rem;
  padding: 2rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.promotion .box-container .box .content{
  text-align: center;
}

.promotion .box-container .box .content h3{
  font-size: 3rem;
  color: var(--black);
}

.promotion .box-container .box .content p{
  font-size: 1.4rem;
  color: #444;
  padding: 1rem 0;
  line-height: 1.8;
}

/* weekly promotions ends*/

/* team */

.team .box-container{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
  gap: 2rem;
}

.team .box-container .box{
  background: var(--white);
  border-radius: .5rem;
  box-shadow: var(--box-shadow);
  text-align: center;
}

.team .box-container .box .image{
  height: 35rem;
  width: 100%;
  padding: 1.1rem;
  overflow: hidden;
  position: relative;
}

.team .box-container .box .image img{
  height: 100%;
  width: 100%;
  border-radius: .5rem;
  object-fit: cover;
}

.team .box-container .box:hover .image img{
  transform: scale(1.1);
}

.team .box-container .box .content{
  padding: 2rem;
  padding-top: 0;
}

.team .box-container .box .content h3{
  color: var(--black);
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.team .box-container .box .content p{
  color: var(--black);
  font-size: 1.7rem;
  margin-bottom: 1rem;
}

.team .box-container .box .content .share i{
  height: 4.5rem;
  width: 4.5rem;
  line-height: 4.5rem;
  background: none;
  border-radius: .5rem;
  font-size: 2rem;
  color: var(--primary-color);
  border: .1rem solid var(--primary-color);
  margin: .5rem;
}

.team .box-container .box .content .share i:hover{
  color: var(--white);
  border: .1rem solid var(--secondary);
  background: var(--secondary);
  box-shadow: var(--box-shadow);
  transition: .4s linear;
  cursor: pointer;
}

/* team */

/* parallax */

.parallax{
  background: url(../images/parallax.jpg) no-repeat;
  min-height: 100vh;
  background-attachment: fixed;
  background-size: cover !important;
  background-position: center !important;
  z-index: 0;
  position: relative;
}

.parallax::before{
  content: '';
  position: absolute;
  top: 0; left: 0; 
  height: 100%;
  width: 100%;
  background: rgba(0, 0, 0, 0.7);
  z-index: -1;
}

.parallax .box-container{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
  gap: 2rem;
}

.parallax .box-container .box{
  text-align: center;
  justify-content: center;
}

.parallax .box-container .box .image{
  padding-top: 5rem;
}

.parallax .box-container .box .image img{
  height: 35%;
  width: 35%;
  object-fit: cover;
}

.parallax .box-container .box .content{
  padding: 2rem;
}

.parallax .box-container .box .content h3{
  color: var(--white);
  font-size: 2.5rem;
  padding-top: 2rem;
  padding-bottom: 4rem;
}

.parallax .box-container .box .content p{
  color: var(--white);
  font-size: 1.4rem;
  line-height: 1.8;
}

/* parallax end */

/* review */

.review{
  background: var(--bg);
}

.review .box-container{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
  gap: 1.5rem;
}

.review .box-container .box{
  border: .1rem solid rgba(0, 0, 0, 0.2);
  border-radius: .5rem;
  box-shadow: var(--box-shadow);
  text-align: center;
  padding: 3rem 2rem;
  background: var(--white);
}

.review .box-container .box .user{
  height: 7rem;
  width: 7rem;
  border-radius: 50%;
  object-fit: cover;
}

.review .box-container .box h3{
  padding: 1rem 0;
  font-size: 2rem;
  color: var(--primary-color);
}

.review .box-container .box .stars i{
  font-size: 1.5rem;
  color: var(--secondary);
}

.review .box-container .box p{
  font-size: 1.5rem;
  line-height: 1.8;
  color: #444;
  padding-top: 1rem;
}

/* review end */

/* order */

.order .row{
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
}

.order .row .image{
  flex: 1 1 30rem;
}

.order .row .image img{
  height: 100%;
  width: 100%;
  object-fit: cover;
}

.order .row form{
  flex: 1 1 50rem;
  padding: 5rem;
}

.order .row form .inputBox{
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.order .row form .inputBox input,
.order .row form textarea{
  padding: 1rem;
  margin: 1rem 0;
  font-size: 1.7rem;
  color: var(--secondary);
  text-transform: capitalize;
  background: var(--bg);
  border-radius: .5rem;
  width: 49%;
}

.order .row form .inputBox input:focus,
.order .row form textarea:focus{
  border: .1rem solid var(--primary-color);
}

.order .row form textarea{
  width: 100%;
  resize: none;
  height: 15rem;
}

/* order */

/* footer */

.footer{
  background: var(--bg);
  text-align: center;
}

.footer .box-container{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(25rem, 1fr));
  gap: 2rem;
}

.footer .box-container .box h3{
  text-transform: capitalize;
  font-size: 2.2rem;
  color: var(--secondary);
  padding: 1rem 0;
}

.footer .box-container .box p{
  font-size: 1.5rem;
  line-height: 2;
  color: #444;
  padding: .5rem 0;
}

.footer .box-container .box .share{
  margin-top: 1rem;
}

.footer .box-container .box .share a{
  height: 4.5rem;
  width: 4.5rem;
  line-height: 4.5rem;
  border-radius: 10%;
  font-size: 1.7rem;
  background: var(--primary-color);
  color: var(--white);
  margin-right: .3rem;
}

.footer .box-container .box .share a:hover{
  background: var(--secondary);
}

.footer .box-container .box .link{
  font-size: 1.7rem;
  line-height: 2;
  color: var(--primary-color);
  padding: .5rem 0;
  display: block;
}

.footer .box-container .box .link:hover{
  color: var(--secondary);
  text-decoration: underline;
}

.footer .credit{
  text-align: center;
  margin-top: 3rem;
  padding-top: 3rem;
  font-size: 2rem;
  text-transform: capitalize;
  color: var(--primary-color);
  border-top: .1rem solid var(--secondary);
}

.footer .credit span{
  color: var(--secondary);
}





/* footer */

/* media queries */

@media (max-width: 991px){

  html{
    font-size: 55%;
  }

  .header{
    padding: 2rem;
  }

  section{
    padding: 2rem;
  }

}

@media (max-width: 768px){
  #menu-btn{
    display: inline-block;
  }

  .fa-times{
    transform: rotate(180deg);
  }

  .header .navbar{
    position: absolute;
    top: 99%;
    left: 0; right: 0;
    background: var(--white);
    border-top: .1rem solid var(--secondary);
    clip-path: polygon(0 0, 100% 0, 100% 0, 0 0);
  }

  .header .navbar.active{
    clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
  }

  .header .navbar a{
    display: block;
    margin: 2rem;
  }

  .home .slide .content{
    width: 40rem;
  }

  .home .slide .content h3{
    font-size: 4rem;
  }

}

@media (max-width: 450px){

  html{
    font-size: 50%;
  }

  .home .slide .content h3{
    font-size: 3rem;
  }

}

.bg-image {
  /* The image used */
  background-image: url("https://getwallpapers.com/wallpaper/full/6/8/4/818759-popular-bakery-wallpapers-1920x1200-for-ipad-2.jpg");

  
  filter: blur(80px);
  -webkit-filter: blur(80px);

  /* Full height */
  height: 100%;

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/* Position text in the middle of the page/image */
.bg-text {
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0, 0.4); /* Black w/opacity/see-through */
  color: rgb(255, 255, 255);
  font-weight: bold;
  border: 3px solid rgb(210, 130, 55);
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  width: 80%;
  padding: 20px;
  text-align: center;
}
.we{
  width: 100%;
  height: auto;
}
.words{
  font-family: 'Caveat', cursive;
  font-size: 50px;
  color:#f2f1ec;
}
```
## OUTPUT:-
![image](https://github.com/Kirupanandhan/Create-a-commercial-website-using-HTML-CSS/assets/94386222/38592f47-0914-4ccb-a36e-72cfa01df54a)
![image](https://github.com/Kirupanandhan/Create-a-commercial-website-using-HTML-CSS/assets/94386222/193f97d2-ebec-47d9-9ebd-8ab2c325c121)
![image](https://github.com/Kirupanandhan/Create-a-commercial-website-using-HTML-CSS/assets/94386222/61280a27-78c5-481b-bab1-a8972cc933ee)
![image](https://github.com/Kirupanandhan/Create-a-commercial-website-using-HTML-CSS/assets/94386222/7cefd859-64bf-455c-823d-2dfed641a299)
![image](https://github.com/Kirupanandhan/Create-a-commercial-website-using-HTML-CSS/assets/94386222/42a05e02-ef87-4153-84b5-3949cd27ef9e)
![image](https://github.com/Kirupanandhan/Create-a-commercial-website-using-HTML-CSS/assets/94386222/660745bd-bbac-4a42-ac3c-16092bfac55a)


## RESULT:-
A commercial website using HTML & CSS has been created and output verified sucessfully.
