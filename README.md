<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
  <link rel="icon" href="images/favicon.png" type="image/gif" />
  <title> Cafeesa </title>

  <link rel="stylesheet" type="text/css" href="css/bootstrap.css" />
  <link href="css/font-awesome.min.css" rel="stylesheet"/>
  <link href="cafeesa.css" rel="stylesheet"/>
  <link href="css/responsive.css" rel="stylesheet"/>
</head>

<body>
  
  <!-- header -->

  <header class="header_section">
    <div class="container-fluid">
      <nav class="navbar navbar-expand-lg custom_nav-container">
        <a href="index.html" class="navbar-brand">
          <span>Cafeesa</span>
        </a>
        <div class="" id="">
          <div class="custom_menu-btn">
            <button onclick="openNav()">
            <span class="s-1"></span>
            <span class="s-2"></span>
            <span class="s-3"></span>
          </button>
          <div class="overlay" id="myNav">
            <div class="overlay-content">
              <a href="cafeesa.html">Home</a>
              <a href="about.html">About</a>
              <a href="book.html">Book Table</a>
              <a href="cafeesa.html">Testimonial</a>
            </div>
          </div>
          </div>
        </div>
      </nav>
    </div>
  </header>
 

  <!-- slider -->
  <section class="slider_section position-relative">
    <div class="slider_bg_box">
      <img src="images/slider-bg.jpg" alt="">
    </div>
    <div class="slider_bg"></div>
    <div class="container">
      <div class="col-md-6 ml-auto">
        <div class="detail-box">
          <h1>Welcome To <br>Our Cafe</h1>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda obcaecati fuga nulla ipsa dolores quisquam at illum ipsam rerum. Officia odio exercitationem illum deserunt! Veritatis harum similique autem corrupti laboriosam!

          </p>

        </div>
      </div>
    </div>
  </section>
  

  <!-- content -->
  <section class="spcl_section layout_padding">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <div class="detail_container">
            <div class="detail-box">
              <img src="images/s1.png" alt="">
              <h5>Original Coffee</h5>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias dolores qui quisrum vel ad voluptates vero earum quos esse

              </p>
            </div>
            <div class="detail-box">
              <img src="images/s2.png" alt="">
              <h5>Self Roasted</h5>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. In blanditiis accusanfugit recusandae itaque fugiat ex praesentium,

              </p>
            </div>
            <div class="detail-box">
              <img src="images/s3.png" alt="">
              <h5>15 COffee Items</h5>
              <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptate eveniet consectetur quasi perspiciatis modi consequuntur quasi perspiciatis modi consequuntur  

              </p>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-5 ml-auto">
          <div class="img-box">
            <img src="images/spcl-img.jpg" alt="">
          </div> </div>
      </div>
    </div>
  </section>
  

  <!-- about  -->
  <section class="about_section layout_padding-bottom">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <div class="img-box">
            <img src="images/about-img.jpg" alt="">

          </div>
        </div>
        <div class="col-md-6"><div class="detail-box">
          <div class="heading_container">
            <h2>About Us</h2>
          </div>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam cum consequuntur aliquid, asperiores accusamus, rem explicabo perferendis, dolor repellat numquam adipisci esse. Nobis quisquam, recusandae iusto perferendis porro libero vel.

          </p>
          <a href="">Read More</a>
        </div></div>
      </div>
    </div>
  </section>


<!-- contact  -->
<section class="contact_section layout_padding">
  <div class="contact_bg_box">
    <img src="images/contact-bg.jpg" alt="">
  </div>
  <div class="container">
    <div class="heading_container heading_center">
      <h2>Book A Table</h2>
    </div> 
    <div class="">
      <div class="row">
        <div class="col-md-7 mx-auto">
          <form action="">
            <div class="contact_form-container">
              <div class="row">
                <div class="col-sm-6">
                  <input type="text" placeholder="Full Name">
                </div>
                <div class="col-sm-6">
                  <input type="text" placeholder="Email">
                </div>
              </div>
              <div class="row">
                <div class="col-sm-6">
                  <input type="number" placeholder="Phone Number" />
                </div>
                <div class="col-sm-6">
                  <input type="number" placeholder="Number of People" />
                </div> 
              </div>
              <div class="row">
                <div class="col-sm-6">
                  <input type="date" placeholder="Select date" />
                </div>
                <div class="col-sm-6">
                  <input type="time" placeholder="Select Time" />
                </div>
              </div>
              <div class="">
                <input type="text" placeholder="Additional Note" class="message_input" />
              </div>
              <div class="btn_box">
                <button type="submit">Send</button>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</section>


<!-- client -->
  <section class="client_section layout_padding">
    <div class="container">
      <div class="heading_container heading_center">
        <h2>What says our client</h2>
      </div>
      <div class="carousel slide" id="carouselExampleControls" data-ride:="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="box">
              <div class="img-box">
                <img src="Shahrukh-Khan.jpg" alt="">
              </div>
              <div class="detail-box">
                <h4>Shah Rukh Khan</h4>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Impedit nulla nemo voluptates nisi voluptatibus ullam similique tempore sapiente sint autem ratione ex nihil cupiditate exercitationem, quo, ipsa modi? Autem, veniam!

                </p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="box">
              <div class="img-box">
                <img src="prithwi.jpg" alt="">
              </div>
              <div class="detail-box">
                <h4>Prithwiraj Sukumaran</h4>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Impedit nulla nemo voluptates nisi voluptatibus ullam similique tempore sapiente sint autem ratione ex nihil cupiditate exercitationem, quo, ipsa modi? Autem, veniam!

                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel_btn-box">
          <a href="#carouselExampleControls" class="carousel-control-prev" role="button" data-slide="prev">
            <i class="fa fa-angle-left" aria-hidden="true"></i>
            <span class="sr-only">Previous</span>
          </a>
          <a href="#carouselExampleControls" class="carousel-control-next" role="button" data-slide="next">
            <i class="fa fa-angle-right" aria-hidden="true"></i>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
    </div>
  </section>


  <!-- footer -->
  <footer class="footer_section">
    <div class="container">
      <div class="row">
        <div class="col-md-4 footer-col">
          <div class="footer_content">
            <h4>Reach at...</h4>
            <div class="contact_link_box">
              <a href=""><i class="fa fa-map-marker" aria-hidden="true"></i>
              <span>Location</span></a>
              <a href=""><i class="fa fa-phone" aria-hidden="true"></i>
              <span>Call +11 123456789</span></a>
              <a href=""><i class="fa fa-envelop" aria-hidden="true"></i>
              <span>cafessa@gmail.com</span></a>
            </div>
          </div>
        </div>
        <div class="col-md-4 footer-col">
          <div class="footer_detail">
            <a href="" class="footer-logo">
              Cafessa
            </a>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.  excepturi corporis nisi magnam quod ullam magni dolorum.

            </p>
            <div class="footer_social">
              <a href=""><i class="fa fa-facebook" aria-hidden="true"></i></a>
              <a href=""><i class="fa fa-twitter" aria-hidden="true"></i></a>
              <a href=""><i class="fa fa-linkedin" aria-hidden="true"></i></a>
              <a href=""><i class="fa fa-instagram" aria-hidden="true"></i></a>
              <a href=""><i class="fa fa-pinterest" aria-hidden="true"></i></a>
            </div>
          </div>
        </div>
        <div class="col-md-4 footer-col">
          <div class="map_container">
            <div class="map">
              <div id="googleMap"></div>
            </div>
          </div>
        </div>
      </div>
      <div class="footer-info">
        <p>&copy; <span id="displayYear"></span>All Rights Reserved By
        <a href="#">THASNI</a></p>
      </div>
    </div>
  </footer>
  


  <!-- jQery -->
  <script src="js/jquery-3.4.1.min.js"></script>
  <!-- bootstrap js -->
  <script src="js/bootstrap.js"></script>
  <!-- custom js -->
  <script src="js/custom.js"></script>
  <!-- Google Map -->
  <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCh39n5U-4IoWpsVGUHWdqB6puEkhRLdmI&callback=myMap">
  </script>
  <!-- End Google Map -->


</body>

</html>
