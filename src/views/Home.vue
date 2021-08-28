<template>
  <div class="home">
    <div id="carouselExampleFade" class="carousel slide carousel-fade" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item  data-bs-interval='200' active">
          <div class="img-container">

            <img src="@/assets/slide-images/woman-working2.jpeg" class="d-block w-100" alt="...">
            <div class="img-overlay"></div>
          </div>

          <div class="carousel-caption d-none d-md-block">
            <h5>Since 2005</h5>
            <h1>Textilery Creating The Best <span>Textile</span> Solutions</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco</p>
          </div>

        </div>
        <div class="carousel-item  data-bs-interval='200' ">
          <div class="img-container">
            <img src="@/assets/slide-images/womanworking.jpeg" class="d-block w-100" alt="...">
            <div class="img-overlay"></div>
          </div>

          <div class="container">
            <div class="carousel-caption d-none d-md-block">
              <h5>Since 2006</h5>
              <h1>Textilery Creating The Best <span>Textile</span> Solutions</h1>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco</p>
            </div>
          </div>

        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

    <div class="container">
      <div class="after-carousel">
        <div class="d-flex flex-md-row flex-column-reverse">
          <div class="col-md-3 d-flex align-items-end">
            <div class="">
              <h2>Location</h2>
              <p>Jl. Sunset Road No.815, Kuta</p>
            </div>
          </div>
          <div class="col-md-3 d-flex align-items-end">
            <div>
              <h2>Email</h2>
              <p>support@domain.com</p>
            </div>
          </div>
          <div class="col-md-3 d-flex align-items-center box-left">
            <div>
              <h2>Quality Product</h2>
              <p>Lorem ipsum dolor sitatu amet consec teturarisa adipiscing elit samed.</p>
              <button type="button" class="btn btn-light">Read More -></button>
            </div>
          </div>
          <div class="col-md-3 d-flex align-items-center box-right">
            <div>
              <h2>Project Overview</h2>
              <p>2,476</p>
              <span>Export Projects</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="home-about">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <div class="about-img-container">
              <img class="main-img" src="@/assets/about-images/about-img.jpeg" alt="">
              <img class="second-img" src="@/assets/about-images/about-img2.jpeg" alt="">
            </div>
          </div>
          <div class="col-md-6">
            <div class="about-content">
              <h4>About Textilery</h4>
              <h1>We Provide The Best Textile Industry Since 2005</h1>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam quis nostrud</p>
              <div class="row">
                <div class="col-md-6">
                  <div class="experience-year-box">
                    <span>Icon</span>
                    <h2>16 +</h2>
                    <h2>Years Of Experiences</h2>
                  </div>
                </div>
                <div class="col-md-6">
                  <ul>
                    <li>Best Quality Standards</li>
                    <li>100% Satisfaction Guarantee</li>
                    <li>Quality Control System</li>
                    <li>Commitment to Customers</li>
                    <li>Highly Professional Team</li>
                    <li>Global fabrics Distributor</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="home-services">
      <div class="container">

      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
  components: {

  }
}
</script>
<style>
body {
  height: 2000px;
}
html {
  font-size: 16px;
}

.title-bottom-line {
  display: inline-block;
  border-bottom: 3px solid greenyellow;
}
.carousel-item .img-container {
  position: relative;
  max-height: 600px;
}

.img-overlay {
  display: block;
  background-color: rgba(0, 0, 0, 0.56);
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0;
  left: 0;

}
.carousel-caption {
  left: 7%;
  bottom: 30%;
  text-align: left;
}
.carousel-caption h1 {
  font-size: 4rem;
  width: 70%;
}
.carousel-caption p {
  width: 50%;
}
.carousel-caption h5 {
  display: inline-block;
  border-bottom: 3px solid greenyellow;
}
.carousel-caption span {
  color: greenyellow;
}
.after-carousel {
  height: 400px;
  position: relative;
  top: -140px;
  z-index: 10;
  padding: 20px;
}
.after-carousel .box-left {
  background-color: cadetblue;
  padding: 30px;
  color: #fff;

}
.after-carousel .box-right {
  background-color: green;
  padding: 30px;
  color: #fff;

}

.home-about .about-img-container .main-img{
  width: 90%;

}
.home-about .about-img-container {
  position: relative;
}
.home-about .about-img-container .second-img {
  width: 60%;
  position: absolute;
  top: 20%;
  right: -20px;
  border: 20px solid #fff;
}
.about-content {
  padding-left: 20px;
}
.about-content h4 {
  display: inline-block;
  border-bottom: 3px solid greenyellow;
  padding-bottom: 10px;
  margin-bottom: 20px;
  color: #545454;
}
.about-content h1 {
  color: #545454;
}
.about-content {
  color: #758994;
}
.experience-year-box {
  width: 100%;
  height: 100%;
  background-color: #0A2B43;
  color: #ffffff;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.about-content ul li {
  padding-bottom: 15px;
}

</style>
