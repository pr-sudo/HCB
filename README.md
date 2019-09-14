# HCB<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
  <link rel="stylesheet" href="styles.css">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" >
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.9.0/css/all.css">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" ></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
</head>
<body>
<!---navigationbar--------->
<section id="nav-bar">
  <nav class="navbar navbar-expand-lg navbar-light">
  <a class="navbar-brand" href="#"><img src="img/google-play.svg"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item">
        <a class="nav-link" href="#slider">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#about">ABOUT US</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#services">SERVICES</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#team">OUR TEAM</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#promo">PRICE PLANS</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#testimonials">TESTIMONIALS</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#contact">CONTACT</a>
      </li>
    </ul>
  </div>
</nav>

</section>
<!-- -----slider----- -->
<div id="slider">
  <div id="header-slider" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#header-slider" data-slide-to="0" class="active"></li>
    <li data-target="#header-slider" data-slide-to="1"></li>
    <li data-target="#header-slider" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="img/携帯.jpg" class="d-block img-fluid">
      <div class="carousel-caption">
        <h5>How To Make A Website</h5>
      </div>
    </div>
    <div class="carousel-item">
      <img src="img/御礼.jpg" class="d-block img-fluid">
      <div class="carousel-caption">
        <h5>Create Responsive Website</h5>
      </div>
    </div>
    <div class="carousel-item">
      <img src="img/資源２.jpg" class="d-block img-fluid">
      <div class="carousel-caption">
        <h5>Business Website</h5>
      </div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#header-slider" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#header-slider" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
</div>
<!-- -------About------- -->
<section id="about">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <h2>About Us</h2>
        <div class="about-content">
            We review psychological research studies on children in infancy and early and middle
            childhood which were published in a number of psychological journals, including the
            Japanese Journal of Educational Psychology, Japanese Journal of Developmental Psychology,
            Japanese Journal of Psychology, Japanese Psycho- logical Research from July 2016 to June 2017,
             and the Proceedings of the 59th Annual Meeting of the
        </div>
        <button type="button" class="btn btn-primary">Read More>></button>
      </div>
      <div class="col-md-6 skills-bar">
        <p>Adobe Photoshop</p>
        <div class="progress">
          <div class="progress-bar" style="width:80%;">80%</div>
        </div>
        <p> UI Design</p>
        <div class="progress">
          <div class="progress-bar" style="width:85%;">85%</div>
        </div>
        <p>WordPress</p>
        <div class="progress">
          <div class="progress-bar" style="width:75%;">75%</div>
        </div>
        <p>Graphics Design</p>
        <div class="progress">
          <div class="progress-bar" style="width:50%;">50%</div>
        </div>
      </div>
    </div>
  </div>
</section>
<!-- ---------services--------- -->
<section id="services">
  <div class="container">
    <h1>Our Services</h1>
    <div class="row services">
      <div class="col-md-3 text-center">
        <div class="icon">
          <i class="fas fa-desktop"></i>
        </div>
        <h3>Web Development</h3>
        <p>Japanese Association of Educational Psychology. The studies were
          presented in five areas: (a) cognitive development, (b) social
          development, (c) development of self, </p>
      </div>
      <div class="col-md-3 text-center">
        <div class="icon">
          <i class="fas fa-tablet"></i>
        </div>
        <h3>App Development</h3>
        <p>Japanese Association of Educational Psychology. The studies were
          presented in five areas: (a) cognitive development, (b) social
          development, (c) development of self, </p>
      </div>
      <div class="col-md-3 text-center">
        <div class="icon">
          <i class="fas fa-line-chart"></i>
        </div>
        <h3>Digital Marketing</h3>
        <p>Japanese Association of Educational Psychology. The studies were
          presented in five areas: (a) cognitive development, (b) social
          development, (c) development of self, </p>
      </div>
      <div class="col-md-3 text-center">
        <div class="icon">
          <i class="fas fa-paint-brush"></i>
        </div>
        <h3>Graphics Designing</h3>
        <p>Japanese Association of Educational Psychology. The studies were
          presented in five areas: (a) cognitive development, (b) social
          development, (c) development of self, </p>
      </div>
    </div>
  </div>
</section>
<!-- ----------team menber---------- -->
<section id="team">
  <div class="container">
    <h1>Our Team</h1>
    <div class="row">
      <div class="col-md-3 profile-pic text-center">
        <div class="img-box">
          <img src="img/girl-2696947_1280.jpg"　class="img-resposive" width="160px;" height="200px;">
          <ul>
            <a href="#"><li><i class="fab fa-facebook-f"></i></li></a>
            <a href="#"><li><i class="fab fa-twitter"></i></li></a>
            <a href="#"><li><i class="fab fa-linkedin-in"></i></li></a>
          </ul>
        </div>
        <h2>Akshay Kumar</h2>
        <h3>Founder / CEO</h3>
        <p>Japanese Association of Educational Psychology. The studies were
          presented </p>
      </div>
      <div class="col-md-3 profile-pic text-center">
        <div class="img-box">
          <img src="img/passion-1690965_1280.jpg"　class="img-resposive" width="160px;" height="200px;">
          <ul>
            <a href="#"><li><i class="fab fa-facebook-f"></i></li></a>
            <a href="#"><li><i class="fab fa-twitter"></i></li></a>
            <a href="#"><li><i class="fab fa-linkedin-in"></i></li></a>
          </ul>
        </div>
        <h2>Akshay Kumar</h2>
        <h3>Founder / CEO</h3>
        <p>Japanese Association of Educational Psychology. The studies were
          presented </p>
      </div>
      <div class="col-md-3 profile-pic text-center">
        <div class="img-box">
          <img src="img/girl-1848472_1280.jpg"　class="img-resposive" width="160px;" height="200px;">
          <ul>
            <a href="#"><li><i class="fab fa-facebook-f"></i></li></a>
            <a href="#"><li><i class="fab fa-twitter"></i></li></a>
            <a href="#"><li><i class="fab fa-linkedin-in"></i></li></a>
          </ul>
        </div>
        <h2>Akshay Kumar</h2>
        <h3>Founder / CEO</h3>
        <p>Japanese Association of Educational Psychology. The studies were
          presented </p>
      </div>
      <div class="col-md-3 profile-pic text-center">
        <div class="img-box">
          <img src="img/woman-3075743_1280.jpg"　class="img-resposive" width="160px;" height="200px;">
          <ul>
            <a href="#"><li><i class="fab fa-facebook-f"></i></li></a>
            <a href="#"><li><i class="fab fa-twitter"></i></li></a>
            <a href="#"><li><i class="fab fa-linkedin-in"></i></li></a>
          </ul>
        </div>
        <h2>Akshay Kumar</h2>
        <h3>Founder / CEO</h3>
        <p>Japanese Association of Educational Psychology. The studies were
          presented </p>
      </div>
    </div>
  </div>
</section>
<!-- -------------promo-------------- -->
<section id="promo">
  <div class="container">
    <p>Get Free Domain Name and Web Hosting</p>
    <a href="#" class="btn btn-primary">Contact Us</a>
  </div>
</section>
<!-- --------price------ -->
<section id="price">
  <div class="container">
    <h1>Price Plans</h1>
    <div class="row">
      <div class="col-md-3">
        <div class="single-price">
          <div class="price-head">
            <h2>Free</h2>
            <p>$0/<span>month</span></p>
          </div>
          <div class="price-content">
            <ul>
              <li><i class="fas fa-check-circle"></i>5GB space</li>
              <li><i class="fas fa-check-circle"></i>10GB Bandwidth</li>
              <li><i class="fas fa-times-circle"></i>15 Email Account</li>
              <li><i class="fas fa-times-circle"></i>Unlimited Domain</li>
              <li><i class="fas fa-times-circle"></i>Unlimited support</li>
            </ul>
          </div>
          <div class="price-button">
            <a href="#" class="buy-btn">Join Free</a>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="single-price">
          <div class="price-head">
            <h2>START UP</h2>
            <p>$0/<span>month</span></p>
          </div>
          <div class="price-content">
            <ul>
              <li><i class="fas fa-check-circle"></i>10GB space</li>
              <li><i class="fas fa-check-circle"></i>100GB Bandwidth</li>
              <li><i class="fas fa-check-circle"></i>15 Email Account</li>
              <li><i class="fas fa-times-circle"></i>Unlimited Domain</li>
              <li><i class="fas fa-times-circle"></i>Unlimited support</li>
            </ul>
          </div>
          <div class="price-button">
            <a href="#" class="buy-btn">Buy Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="single-price">
          <div class="price-head">
            <h2>BUSINESS</h2>
            <p>$0/<span>month</span></p>
          </div>
          <div class="price-content">
            <ul>
              <li><i class="fas fa-check-circle"></i>20GB space</li>
              <li><i class="fas fa-check-circle"></i>200GB Bandwidth</li>
              <li><i class="fas fa-check-circle"></i>50 Email Account</li>
              <li><i class="fas fa-check-circle"></i>Unlimited Domain</li>
              <li><i class="fas fa-times-circle"></i>Unlimited support</li>
            </ul>
          </div>
          <div class="price-button">
            <a href="#" class="buy-btn">Buy Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="single-price">
          <div class="price-head">
            <h2>ADVANCED</h2>
            <p>$0/<span>month</span></p>
          </div>
          <div class="price-content">
            <ul>
              <li><i class="fas fa-check-circle"></i>5GB space</li>
              <li><i class="fas fa-check-circle"></i>Unlimited Bandwidth</li>
              <li><i class="fas fa-check-circle"></i>Unlimited Account</li>
              <li><i class="fas fa-check-circle"></i>Unlimited Domain</li>
              <li><i class="fas fa-check-circle"></i>Unlimited support</li>
            </ul>
          </div>
          <div class="price-button">
            <a href="#" class="buy-btn">Buy Now</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<!-- -------testimonials-------- -->
<section id="testimonials">
  <div class="container">
    <h1>Testimonials</h1>
    <p class="text-center">Subscribe Easy Tutorials Youtube
       Channel to watch more videos</p>
       <div class="row">
         <div class="col-md-4 text-center">
           <div class="profile">
             <img src="img/fashion-3179178_1280.jpg" class="user">
             <blockquote>
               We review psychological research studies on children in infancy and early and middle
               childhood which were published in a number of psychological journals, including the
               Japanese Journal of Educational Psychology Japanese Journal
             </blockquote>
             <h3>Avinash Kr <span>Co-Founder at XYZ</span></h3>
           </div>
         </div>
         <div class="col-md-4 text-center">
           <div class="profile">
             <img src="img/medieval-276019_1280.jpg" class="user">
             <blockquote>
               We review psychological research studies on children in infancy and early and middle
               childhood which were published in a number of psychological journals, including the
               Japanese Journal of Educational Psychology Japanese Journal
             </blockquote>
             <h3>Avinash Kr <span>Co-Founder at XYZ</span></h3>
           </div>
         </div>
         <div class="col-md-4 text-center">
           <div class="profile">
             <img src="img/people-2563491_1280.jpg" class="user">
             <blockquote>
               We review psychological research studies on children in infancy and early and middle
               childhood which were published in a number of psychological journals, including the
               Japanese Journal of Educational Psychology Japanese Journal
             </blockquote>
             <h3>Avinash Kr <span>Co-Founder at XYZ</span></h3>
           </div>
         </div>
       </div>
  </div>
</section>
<!-- -----------get in touch------------ -->
<section id="contact">
  <div class="container">
    <h1>Get In Touch</h1>
    <div class="row">
      <div class="col-md-6">
        <form class="contact-form">
          <div class="form-group">
            <input type="text" class="form-control" placeholder="Your Name">
          </div>
          <div class="form-group">
            <input type="number" class="form-control" placeholder="Phone no.">
          </div>
          <div class="form-group">
            <input type="email" class="form-control" placeholder="Email id">
          </div>
          <div class="form-group">
            <textarea class="form-control" rows="4" placeholder="Your Message" ></textarea>
          </div>
          <button type="submit" class="btn btn-primary">SEND MESSAGE</button>
        </form>
      </div>
      <div class="col-md-6 contact-info">
        <div class="follow"><b>Address:</b>   <i class="fas fa-map-marker-alt"></i>XYZ Road, Bangalore, In</div>
        <div class="follow"><b>Phone:</b>     <i class="fas fa-phone-alt"></i>+1 1234567890</div>
        <div class="follow"><b>Email:</b>     <i class="fas fa-envelope"></i>example@website.com</div>
        <div class="follow"><label><b>Get Social:</b></label>
         <a href="#"><i class="fab fa-facebook-f"></i></a>
         <a href="#"><i class="fab fa-youtube"></i></a>
         <a href="#"><i class="fab fa-twitter"></i></a>
         <a href="#"><i class="fab fa-google-plus"></i></a>
        </div>
      </div>
</section>
<!-- ------fotter-------- -->
<section id="footer">
  <div class="container text-center">
    <p>Made With <i class="far fa-heart"></i> by Easy Tutorials</p>
  </div>
</section>


<script type="text/javascript">
  function(){

  $('li a').click(function(){
    var id=$(this).attr('href');
    var position=$(id).offset().top;
    $('html , body').animate({
      'scrollTop':position
    },500);
  })










});
</script>
</body>
</html>
