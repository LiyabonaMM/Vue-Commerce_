<template>
  <div class="footer">
    <div class="container">
      <div class="row">
        <div class="footer-col-1">
          <h3>Download Our App</h3>
          <p>Download App for Android and iOS mobile phones.</p>
          <div class="app-logo">
            <a
              href="https://play.google.com/store/apps/details?id=com.heinrichreimersoftware.iloveyou&hl=en&gl=US"
              ><img
                src="https://i.postimg.cc/MGh9fMGz/pngegg.png"
                alt="App store"
                class="lazyload"
            /></a>
          </div>
        </div>
        <div class="footer-col-2">
          <img
            src="https://i.postimg.cc/W1M2Dr87/1686734383073.png"
            class="lazyload"
          />
          <p>STAY SHINING</p>
        </div>
        <div class="footer-col-4">
          <h3>Follow us</h3>
          <ul>
            <li><a href="https://github.com">Github</a></li>
            <li><a href="https://www.instagram.com">Instagram</a></li>
          </ul>
        </div>
      </div>
    </div>
    <hr />
    <p class="copyright">
      &copy; 2023 Liyabona Mxhalisa. All rights reserved. partnership with
      LifeChoiceAcademy
    </p>
  </div>
</template>
<style>
.footer {
  background: #000;
  /*black;*/
  color: #8a8a8a;
  font-size: 14px;
  padding: 60px 0 20px;
}

.footer p {
  color: #8a8a8a;
}

.footer h3 {
  color: #fff;
  margin-bottom: 20px;
}

.footer-col-1,
.footer-col-2,
.footer-col-3,
.footer-col-4 {
  min-width: 250px;
  margin-bottom: 20px;
}

.footer-col-1 {
  flex-basis: 30%;
}

.footer-col-2 {
  flex: 1;
  text-align: center;
}

.footer-col-2 img {
  width: 180px;
  margin-bottom: 20px;
}

.footer-col-3,
.footer-col-4 {
  flex-basis: 12%;
  text-align: center;
}

ul {
  list-style-type: none;
}

.app-logo {
  margin-top: 20px;
}

.app-logo img {
  width: 140px;
}

.footer hr {
  border: none;
  background: #b5b5b5;
  height: 1px;
  margin: 20px 0;
}

.copyright {
  text-align: center;
}



.menu-icon {
  width: 28px;
  margin-left: 20px;
  display: none;
}

/*-----------------------media query for menu -----------------------*/
@media only screen and (max-width:800px) {
  nav ul {
    position: absolute;
    top: 70px;
    left: 0;
    background: #333;
    width: 100%;
    overflow: hidden;
    transition: max-height 0.5s;



  }

  nav ul li {
    display: block;
    margin-right: 50px;
    margin-top: 10px;
    margin-bottom: 10px;
  }

  nav ul li a {
    color: #fff;
  }

  .menu-icon {
    display: block;
    cursor: pointer;
  }
}

/*-----------------------media query for less than 600 screen size(mobile device) -----------------------*/
@media only screen and (max-width:600px) {
  .row {
    text-align: center;
  }

  .col-2 .col-3 .col-4 {
    flex-basis: 100%;
  }

  .single-product .row {
    text-align: left;
  }

  .single-product .col-2 {
    padding: 20px 0;
  }

  .single-product h1 {
    font-size: 20px;
    line-height: 32px;
  }

  .cart-info p {
    display: none;
  }
}
</style>
