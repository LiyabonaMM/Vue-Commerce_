<template>
  <div>
    <div class="header">
      <div class="container">
        <div class="navbar">
          <div class="logo">
            <router-link to="//src/components/Navbar.vue"
              ><img
                src="https://i.postimg.cc/bvDfNTP1/Lil-Media-removebg-preview.png"
                width="125px"
                class="lazyload"
            /></router-link>
          </div>

          <router-link to="/cart"
            ><img
              src="https://i.postimg.cc/XqqkZBPJ/cart.png"
              width="30px"
              height="30px"
          /></router-link>
        </div>
        <div class="row">
          <div class="col-2">
            <h1>WELCOME TO LILMEDIA <br />FEED YOUR AESTHETIC!</h1>
            <p>The EXTRA MILE</p>
            <router-link to="/products" class="btn"
              >SHOP NOW &#8594;</router-link
            >
          </div>
          <div class="col-2">
            <img
              src="https://i.postimg.cc/4xdtFKvY/joey-badass-pony-2.jpg"
              class="lazyload"
            />
          </div>
        </div>
      </div>
    </div>

    <div class="categories">
      <div class="small-container">
        <div class="row">
          <div class="col-3">
            <img
              src="https://i.postimg.cc/jqQ052p3/Converse-Chuck-70-Black-Egret-vintage.jpg"
              class="lazyload"
            />
          </div>
          <div class="col-3">
            <img
              src="https://i.postimg.cc/HnTN50qZ/I-luv-my-vans-3.jpg"
              class="lazyload"
            />
          </div>
          <div class="col-3">
            <img
              src="https://i.postimg.cc/G3JtCcqd/Vans-flame.jpg"
              class="lazyload"
            />
          </div>
        </div>
      </div>
    </div>

    <div class="small-container">
      <h2 class="title">Featured Products</h2>
      <div class="row">
        <div class="col-4">
          <router-link to="/product-details"
            ><img
              src="https://i.postimg.cc/020VDJnF/5a1e5d72423d4c1e4021e987f26cf4f7.jpg"
              class="lazyload"
          /></router-link>
          <router-link to="/product-details">
            <h4>Nike Dunk Low VI</h4>
          </router-link>
          <p>R1000</p>
        </div>
        <div class="col-4">
          <router-link to="/product-details2"
            ><img
              src="https://i.postimg.cc/yYTDF0GM/d8dc11a0e8a9797de1537ad404b712f8.jpg"
              class="lazyload"
          /></router-link>
          <h4>Lace-Up Cactus TRXVSS</h4>
          <p>R2000</p>
        </div>
        <div class="col-4">
          <router-link to="/product-details3"
            ><img
              src="https://i.postimg.cc/RZFbmLx9/0ffdfd20e661b0ecb659a2

e8c800825c.jpg"
              class="lazyload"
          /></router-link>
          <h4>Adidas XY</h4>
          <p>R3000</p>
        </div>
        <div class="col-4">
          <router-link to="/product-details4"
            ><img
              src="https://i.postimg.cc/7LQ5cDMw/afdabda8f35bf5ec67cffd64256c6556.jpg"
              class="lazyload"
          /></router-link>
          <h4>New Balance 530</h4>
          <p>R15000</p>
        </div>
      </div>
    </div>

    <div class="testimonial">
      <div class="small-container">
        <div class="row">
          <div class="col-3">
            <i class="fa fa-quote-left"></i>
            <p>
              "Fantastic selection of shoes at the store! The quality and style
              are top-notch, and the prices are unbeatable. I couldn't be
              happier with my purchase. Highly recommend shopping here!"
            </p>
            <div class="rating">
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
            </div>
            <img
              src="https://i.postimg.cc/hv7c2QKR/C12-Olwethu-Bhiya-2.jpg"
              class="lazyload"
            />
            <h3>Olwethu - Customer</h3>
          </div>
          <div class="col-3">
            <i class="fa fa-quote-left"></i>
            <p>
              "I am incredibly impressed with the customer service and product
              quality at your shoe store. The staff was knowledgeable and helped
              me find the perfect pair of shoes that fit both my style and
              comfort preferences. I will definitely be returning for future
              shoe purchases. Thank you for a wonderful shopping experience!"
            </p>
            <div class="rating">
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
            </div>
            <img
              src="https://i.postimg.cc/Rq59yC06/C12-C1-Ethan-Lesar-3.jpg"
              class="lazyload"
            />
            <h3>Ethan - Customer</h3>
          </div>
          <div class="col-3">
            <i class="fa fa-quote-left"></i>
            <p>
              "Your shoe store provided an exceptional shopping experience. The
              staff was friendly and knowledgeable, assisting me in finding the
              perfect pair of shoes. The quality of the shoes exceeded my
              expectations, and they fit comfortably. I highly recommend your
              store to anyone in search of stylish and high-quality footwear.
              Thank you for a great shopping experience!"
            </p>
            <div class="rating">
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star-o"></i>
            </div>
            <img
              src="https://i.postimg.cc/SKrs99xZ/Ridhaa.png"
              class="lazyload"
            />
            <h3>RIDHA</h3>
          </div>
        </div>
      </div>
    </div>

    <div class="brands">
      <div class="small-container">
        <div class="row">
          <div class="col-5">
            <img
              src="https://i.postimg.cc/Pr85xGwW/pngwing-com-1.png"
              alt=""
              class="lazyload"
            />
          </div>
          <div class="col-5">
            <img
              src="https://i.postimg.cc/Mpr11JG9/favpng-proudly-south-african-logo-brand-product.png"
              alt="SA logo"
              class="lazyload"
            />
          </div>
          <div class="col-5">
            <img
              src="https://i.postimg.cc/s2Q7cHQs/pngwing-com-3.png"
              alt="New Balance"
              class="lazyload"
            />
          </div>
          <div class="col-5">
            <img
              src="https://i.postimg.cc/zX7CXgYZ/pngwing-com-2.png"
              alt="Adidas"
              class="lazyload"
            />
          </div>
          <div class="col-5">
            <img
              src="https://i.postimg.cc/LXjfdq3W/pngwing-com-4.png"
              alt="Vans"
              class="lazyload"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;

}

body::-webkit-scrollbar {
  background-color: #f5f5f5;
  color: #333;
  line-height: 1.5;
  display: none;
}

body {
  font-family: 'Poppins', sans-serif;
  -ms-overflow-style: none;
  scrollbar-width: none;
}

.navbar {
  display: flex;
  align-items: center;
  padding: 20px;
}


nav {
  flex: 1;
  text-align: right;
}


nav ul {
  display: inline-block;
  list-style-type: none;
}


nav ul li {
  display: inline-block;
  margin-right: 50px;
}

a {
  text-decoration: none;
  color: #555;
}

p {
  color: #555;
}

.container {
  max-width: 1300px;
  margin: auto;
  padding-left: 25px;
  padding-right: 25px;
}

.row {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  justify-content: space-around;
}

.col-2 {
  flex-basis: 50%;
  min-width: 300px;
}

.col-2 img {
  max-width: 100%;
  padding: 50px 0;
}

.col-2 h1 {
  font-size: 50px;
  line-height: 60px;
  margin: 25px 0;
}

.btn {
  display: inline-block;
  background: black;
  color: #fff;
  padding: 8px 30px;
  margin: 30px 0px;
  border-radius: 30px;
  transition: background 0.5s;
}

.btn:hover {
  background: #563434;
}

.header {
  background: radial-gradient(#fff, white);
}

.header .row {
  margin-top: 70px;
}

.categories {
  margin: 70px 0;
}

.col-3 {
  flex-basis: 30%;
  min-width: 250px;
  margin-bottom: 30px;
}

.col-3 img {
  width: 100%;
}

.small-container {
  max-width: 2000px;
  margin: auto;
}

.col-4 {
  flex-basis: 25%;
  padding: 10px;
  min-width: 200px;
  margin-bottom: 50px;
  transition: transform 0.5s;
}

.col-4 img {
  width: 100%;
}

.title {
  text-align: center;
  margin: 0 auto 80px;
  position: relative;
  line-height: 60px;
  color: #555;
}

.title::after {
  content: '';
  background: black;
  width: 80px;
  height: 5px;
  border-radius: 5px;
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
}

h4 {
  color: #555;
  font-weight: normal;
}

.col-4 p {
  font-size: 14px;
}

.rating .fa {
  color: black;
}

.col-4:hover {
  transform: translateY(-5px);
}

.col-2 .offer-img {
  padding: 50px;
}

small {
  color: #555;
}

/*-----------------------Testimonial -----------------------*/
.testimonial {
  padding-top: 100px;
}

.testimonial .col-3 {
  text-align: center;
  padding: 40px 20px;
  box-shadow: 0 0 20px 0px rgba(0, 0, 0, 0.1);
  cursor: pointer;
  transition: transform 0.5s;
}

.testimonial .col-3 img {
  width: 50px;
  margin-top: 20px;
  border-radius: 50%;
  /*square images converted to round shape box*/
}

.testimonial .col-3:hover {
  transform: translateY(-10px);
}

.fa.fa-quote-left {
  font-size: 34px;
  color: black;
}

.col-3 p {
  font-size: 12px;
  margin: 12px 0;
  color: #777;
}

.testimonial .col-3 h3 {
  font-weight: 600;
  color: #555;
  font-size: 16px;
}

/*-----------------------Brands -----------------------*/
.brands {
  margin: 100px auto;
}

.col-5 {
  width: 100px;
}

.col-5 img {
  width: 100%;
  cursor: pointer;
  filter: grayscale(100%);
}

.col-5 img:hover {
  filter: grayscale(0);
}
</style>
