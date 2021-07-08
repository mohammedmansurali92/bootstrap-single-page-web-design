# bootstrap-single-page-web-design
Bootstrap Single Page Web-design
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  
  <script src="https://kit.fontawesome.com/b99e675b6e.js"></script>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
   <link rel="stylesheet" type="text/css" href="style.css">
  <style>
 html{
      scroll-behavior: smooth;
    }
    body{
   font-family: 'Montserrat',sans-serif;
    }
    h1,h2,h3,h4,h5,h6{
       font-family: 'Roboto', sans-serif;
    }
    .section-title h1{
      font-weight: bolder;
      margin-bottom: 0px;
    }
    .hr-style{
      border: 5px dotted white;
      border-bottom: none;
      width: 50px;
    }
    header{
      background:url(https://images.pexels.com/photos/6567331/pexels-photo-6567331.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500);
      background-position: center;
      background-attachment:fixed;
      background-repeat: no-repeat;
      background-size:cover;
      max-height: full;
        }
        .banner-container{
          height:100vh;
        }
.navbar{
    padding: 1% 10%;
    color: rgba(0,0,0,0.3);
}
.navbar-icon{
  color: white;
}
.navbar-brand img{
  width:90px;
  height:auto;
}
.nav-link{
  color: white;
  margin: 10px;
  border-radius: 5px;
  transition: 4s;
}
.nav-link:hover{
  background:#2980b9;
  outline:white;
  transform: scale(1.1);
}
.banner-container h1{
  font-size: 3.5rem;
 /* background-color: rgba(7,101,189,0.5);*/
  padding: 10px 20px;
  font-family:'Handlee', cursive;
}  
/*features section start*/
#features{
  padding: 5% 10%;
  background:#e8ded2;
}  
.features-col{
  border: 1px solid #ff02c0;
  border-radius: 5px;
  padding: 15px;
  margin: 20px 0;
  transition:.4s;
}  
.features-col:hover{
  transform: scale(1.1);
  box-shadow: 2px 6px 5px black;
}  
.icon-style{
  background:#bb0aac;
  color: white;
  padding: 15px;
  margin: 5px 0;
} 
/*features section End here*/
/*About Me start*/
  #about-me{
    padding: 5% 10%;
    background: #e8ded2;
  }
  #about-me p{
  font-size: 0.9rem;
  margin-bottom: 0;
  font-weight: light;
  }
  #about-me a{
    font-size: 0.9rem;
    font-weight: lighter;
    color: black;
    text-decoration: underline;
  }
  .acheive-desc span{
    font-weight: 700!important;
  }
  .star i{
    width: 20px;
  }

/* About Section End here */   
/*tutorial start*/  
#tutorial{
  padding: 4% 10%;
  background: #a3d2ca;
}
.card{
  transition: .4s;
  border: 1px solid #ff02c0;
}
.card:hover{
  transform:scale(1.1);
  box-shadow: 2px 6px 5px black;
}

/*tutorial Ends*/  

 /* Feedback start */
 #feedback{
  padding: 5%;
  background: #5eaaa8;
 }
.feedback-image{
  width: 220px;
  height: auto;
  margin: bottom 5px;
}
.carousel-item{
  text-align: center;
  padding: 7% 15%;
  font-style: italic;
  font-size: 1.2rem;
}
 /* feedback Ends */ 
 /* contact me start */
 #contact{
  padding: 5% 7%;
  background:#5eaaa8;
   }
   form-group label{
    margin-bottom: 0;
    font-weight: bold;
   }
 /* contact me end */
/*footer start here */
footer{
  padding: 1% 10%;
  background:#056676;
}
/*footer end here */
footer{
  padding: 1% 10%;
  background:#056676;
}
footer a{
  color: white;
  margin: 0 10px;
}
footer a:hover{
  color: black;
}
@media(max-width:768px){
  nav-link:rgba(0,0,0,0.7);
}
  </style>
  
  <title>My Website</title>
</head>
<body> 
  <div class="container">
    
    <header>     
     <nav class="navbar navbar-expand-md">
  
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
    <span><i class="fas fa-bars navbar-icon"></i></span>
  </button>
  <a class="navbar-brand" href="#">
    <img src="D:\New image1\logo1a.jpg">
  </a>

  <div class="collapse navbar-collapse" id="navbarNavDropdown">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link text-center text-md-left" href="#Home">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link text-center text-md-left" href="#about-me">About Me</a>
      </li>
      <li class="nav-item">
        <a class="nav-link text-center text-md-left" href="#tutorial">Tutorial</a>
      </li>
       <li class="nav-item">
        <a class="nav-link text-center text-md-left" href="#contact">Contect</a>
      </li>
       <li class="nav-item">
        <a class="nav-link text-center text-md-left" href="#">Services</a>
      </li>
       <li class="nav-item">
        <a class="nav-link text-center text-md-left" href="#feedback">Feedback</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Dropdown link
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </li>
    </ul>
  </div>
</nav>
      <section id="banner">
        <div class="banner-container d-flex justify-content-center align-items-center">
          <div class="banner-contents text-center">
            <h1 class="font-weight-bold text-white mb-5">Learn Something New!!!</h1>
            <button class="btn btn-primary mr-3" onclick="location.href'#tutorial'"><i class="fas fa-play mr-2"></i>Tutorial</button>
            <button class="btn btn-primary mr-3" onclick="window.open('https://www.youtube.com/channel/UClzMRrxuW2SQwog7Wil2J7Q')" class="request-callback"><i class="fab fa-youtube mr-2"></i>Subcribe</button>
          </div>
        </div>
      </section>
    </div>
    </header>
    <main>
      <!--features section start here-->
      <section id="features" class="text-center">
        <div class="row">
          <div class="col-lg-4 d-block d-lg-flex">
            <div class="features-col">
              <i class="fas fa-hand-holding-usd fa-3x icon-style rounded-circle"></i>
              <h5 class="font-weight-bold">Free to Use</h5>
              <p class="small">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient. </p>
            </div>
          </div>
          <div class="col-lg-4 d-block d-lg-flex">
            <div class="features-col">
              <i class="fas fa-hand-holding-usd fa-3x icon-style rounded-circle"></i>
              <h5 class="font-weight-bold">Free to Use</h5>
              <p class="small">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient. </p>
            </div>
          </div>
          <div class="col-lg-4 d-block d-lg-flex">
            <div class="features-col">
              <i class="fas fa-hand-holding-usd fa-3x icon-style rounded-circle"></i>
              <h5 class="font-weight-bold">Free to Use</h5>
              <p class="small">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa.</p>
            </div>
          </div>
        </div>
      </section>
      <!--features section End here-->

      <!--about Me start-->
       <section id="about-me">
        <div class="section-title">
          <h3 class="text-center">About Me</h3>
           <hr class="hr-style" style="border-color: black">
         </div>
          <div class="row">
            <div class="col-lg-5">
              <div class="basic-desc text-center text-lg-left">
                <i class="icon-style rounded-circle far fa-user fa-2x"></i>
                <h5 class="font-weight-bolder">Personal Info</h5>
                <p>Name: Mohammad Mansur</p>
                <p>Profesion:Web Developer specialist in Frontend</p>
                <p>Current Address: Al Bawadi, Jeddah</p>
                <p>website:<a> https://trmorning.com</a></p>
                <p><a href="https://www.youtube.com/channel/UClzMRrxuW2SQwog7Wil2J7Q">Link</a></p>
                <button class="btn btn-primary">Download CV</button>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-lg-7">
              
            </div>
        
          <div class="col-lg-5">
            <div class="acheive-desc text-center text-lg-left">
              <i class="icon-style rounded-circle fas fa-trophy fa-2x"></i>
              <h5 class="font-weight-bolder">Acheivements</h5>
              <p><span>Grameen bank Service:</span> Best of achedemic qualification get servises </p>
              <p><span>Al Raya.com.sa Services:</span> More experience of web devloping get job</p>
              <p><span>Wesite Viwer:</span>All over the World Many people visit my website.</p>
             </div>
            </div>
          </div>
        </div>
        <div class="row">
            <div class="col-lg-5">
              <div class="skills-desc text-center text-lg-left">
              <i class=" icon-style rounded-circle fas fa-briefcase fa-2x"></i>
              <h5 class="font-weight-bolder">Skills</h5>
              <table>
                <tr>
                  <td>HTML</td>
                  <td>
                    <span class="start">
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star-half"></i>
                    </span>
                  </td>
                </tr>
                <tr>
                   <td>CSS</td>
                  <td>
                    <span class="start">
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="far fa-star"></i>
                    </span>
                  </td>
                </tr>
                <tr>
                   <td>Bootstrap</td>
                  <td>
                    <span class="start">
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="far fa-star"></i>
                      <i class="far fa-star"></i>
                    </span>
                  </td>
                </tr>
                <tr>
                   <td>JavaScript</td>
                  <td>
                    <span class="start">
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="far fa-star"></i>
                      <i class="far fa-star"></i>
                    </span>
                  </td>
                </tr>
                <tr>
                   <td>jQuery</td>
                  <td>
                    <span class="start">
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="far fa-star"></i>
                    </span>
                  </td>
                </tr>
                <tr>
                   <td>PHP</td>
                  <td>
                    <span class="start">
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="far fa-star"></i>
                      <i class="far fa-star"></i>
                    </span>
                  </td>
                </tr>
                <tr>
                   <td>SQL</td>
                  <td>
                    <span class="start">
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="far fa-star"></i>
                    </span>
                  </td>
                </tr>
                <tr>
                    <td>WordPress</td>
                  <td>
                    <span class="start">
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="far fa-star"></i>
                    </span>
                  </td>
                </tr>
                <tr>
                    <td>Photoshop</td>
                  <td>
                    <span class="start">
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="far fa-star"></i>
                    </span>
                  </td>
                </tr>
                <tr>
                    <td>Illustrator</td>
                  <td>
                    <span class="start">
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="far fa-star"></i>
                    </span>
                  </td>
                </tr>
                <tr>
                    <td>Basic React</td>
                  <td>
                    <span class="start">
                      <i class="fas fa-star"></i>
                      <i class="fas fa-star"></i>
                      <i class="far fa-star"></i>
                      <i class="far fa-star"></i>
                      <i class="far fa-star"></i>
                    </span>
                  </td>
                </tr>
              </table>
            </div>
            </div>
          </div>
          <div class="row">
            <div class="col-lg-7">
              
            </div>
        
          <div class="col-lg-5">
            <div class="acheive-desc text-center text-lg-left">
              <i class="icon-style rounded-circle fas fa-trophy fa-2x"></i>
              <h5 class="font-weight-bolder">Acheivements</h5>
              <p><span>Grameen bank Service:</span> Best of achedemic qualification get servises </p>
              <p><span>Al Raya.com.sa Services:</span> More experience of web devloping get job</p>
              <p><span>Wesite Viwer:</span>All over the World Many people visit my website.</p>
             
            </div>
          </div>
        </div>
       
       </section>
      <!--About me End here-->

      <!--Tutorial Start here-->
      <section id="tutorial">
       <div class="title text-center mb-3">
        <h2 class="font-weight-bolder">Tutorial</h2>
        <hr class="hr-style" style="border-color: black">
        </div>                                                      
    <div class="row text-center mb-3">
      <div class="col-lg-3 col-md-6 col-sm-12 d-block d-lg-flex">
        <div class="card mb-5 text-center text-white bg-info">
          <img class="card-img-top" src="D:\New image1\images (3).jpg">
          <div class="card-body">
            <h4 class="card-title font-weight-bolder">HSC ICT</h4>
            <a class=" stretched-link" href="#Tutorial">Visit this playlist</a>
           </div>
          </div>
      </div>
      <div class="col-lg-3 col-md-6 col-sm-12 d-block d-lg-flex">
        <div class="card mb-5 text-center text-white bg-primary">
          <img class="card-img-top" src="D:\New image1\images_card.jpg" style="width:253px;height:250px">
          <div class="card-body">
            <h4 class="card-title font-weight-bolder">HSC ICT</h4>
            <a class=" stretched-link" href="https://trmorning.com" target="_blank">Visit this playlist</a>
           </div>
           </div>
      </div>
      <div class="col-lg-3 col-md-6 col-sm-12 d-block d-lg-flex">
        <div class="card mb-5 text-center text-white bg-success">
          <img class="card-img-top" src="D:\New image1\download.jpg" style="height:250px">
          <div class="card-body">
            <h4 class="card-title font-weight-bolder">HSC ICT</h4>
            <a class=" stretched-link" href="https://trmorning.com" target="_blank">Visit this playlist</a>
           </div>
           </div>
      </div>
      <div class="col-lg-3 col-md-6 col-sm-12 d-block d-lg-flex">
        <div class="card mb-5 text-center text-white bg-warning">
          <img class="card-img-top" src="D:\New image1\images (4).jpg">
          <div class="card-body">
            <h4 class="card-title font-weight-bolder">HSC ICT</h4>
            <a class=" stretched-link" href="https://trmorning.com" target="_blank">Visit this playlist</a>
           </div>
          </div>
      </div>
     </div>
    <div class="row text-center mb-3 ">
      <div class="col-lg-3 col-md-6 col-sm-12 d-block d-lg-flex">
        <div class="card mb-5 text-center text-white bg-info">
          <img class="card-img-top" src="D:\New image1\images (3).jpg">
          <div class="card-body">
            <h4 class="card-title">HSC ICT</h4>
            <a class="stretched-link" href="https://trmorning.com" target="_blank">Visit this playlist</a>
           </div>
          </div>
      </div>
      <div class="col-lg-3 col-md-6 col-sm-12 d-block d-lg-flex">
        <div class="card mb-5 text-center text-white bg-primary">                                                                                                                         
          <img class="card-img-top" src="D:\New image1\images_card.jpg" style="width:253px;height:250px">
          <div class="card-body">
            <h4 class="card-title font-weight-bolder">HSC ICT</h4>
            <a class=" stretched-link" href="https://trmorning.com" target="_blank">Visit this playlist</a>
           </div>
           </div>
      </div>
      <div class="col-lg-3 col-md-6 col-sm-12 d-block d-lg-flex">
        <div class="card mb-5 text-center text-white bg-success">
          <img class="card-img-top" src="D:\New image1\download.jpg" style="height:250px">
          <div class="card-body">
            <h4 class="card-title font-weight-bolder">HSC ICT</h4>
            <a class=" stretched-link" href="https://trmorning.com" target="_blank">Visit this playlist</a>
           </div>
           </div>
      </div>
      <div class="col-lg-3 col-md-6 col-sm-12 d-block d-lg-flex">
        <div class="card mb-5 text-center text-white bg-warning">
          <img class="card-img-top" src="D:\New image1\images (4).jpg">
          <div class="card-body">
            <h4 class="card-title font-weight-bolder">HSC ICT</h4>
            <a class="  stretched-link" href="https://trmorning.com" target="_blank">Visit this playlist</a>
           </div>
          </div>
      </div>
    </div>
     
        </section>
        <!--Tutorial Ends here-->

        <!--feedback start here-->
        <section id="feedback">
          <div class="title text-center mb-3">
        <h2 class="font-weight-bolder text-light">Feedback</h2>
        <hr class="hr-style">
        </div>  
            <div class="row">
                   <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
             <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
             <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
           <div class="carousel-item active">
            <p>Item 1: Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
           <img src="D:\New image1\img_v5.jpg" class=" rounded-circle feedback-img">
             
           
           <h4>Towfiqure</h4>
           </div>
           <div class="carousel-item">
            <p>Item 2: Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
           <img src="D:\New image1\img_v5.jpg" class=" rounded-circle feedback-img">
           <h4>Towfiqure</h4>
            </div>
            <div class="carousel-item">
            <p>Item 3: Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
            <img src="D:\New image1\towhid_pr.jpg" class=" rounded-circle feedback-img">
           <h4>Towhidur</h4>
        </div>
        </div>
         <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
         <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
          </a>
          </div>
        </div>   
         </div>        
        </section>

        <!--feedback Ends here-->
         <!-- contact form start here-->
         <section id="contact">
          <div class="row">
            <div class="col-lg-12">
       <div class="contact-section p-3 my-5 text-white">
          <div class="title text-left my-5">
      <h3 class="font-weight-bolder background-light text-center">Contact Me</h3>
      <hr class="hr-style">
       </div>
     <form action="mailto:mohammedmansurali12@gmail.com" method="post" enctype="text/plain" class="w-50 m-auto was-validated">
      <div class="form-group mb-1">
         <label for="fullname">Fullname:</label>
        <input type="text" class="form-control" name="fullname" required>
        <div class="valid-feedback">Valid</div>
        <div class="invalid-feedback">Enter fullname before submitting the form</div>
        </div>
       <div class="form-group mb-1">
          <label for="email">Email:</label>
        <input type="email" class="form-control" name="email">
        <div class="form-group mb-1">
          <label for="phone">Mobile No:</label>
        <input type="phone" class="form-control" name="phone">
      </div>
      </div>
       <div class="form-group mb-1">
          <label for="subject">Subject:</label>
        <input type="text" class="form-control" name="subject">
      </div>
       <div class="form-group mb-1">
          <label for="message">Message:</label>
        <textarea name="message" style="resize: none" class="form-control" cols="30" rows="10"></textarea>
      </div>
      <div class="form-group">
        <input class="btn btn-secondary" type="submit" value="submit" placeholder="">
        <input class="btn btn-secondary" type="reset" value="Reset">
      </div>
     </form>
       </div>
     </form>
    </div>
       </div>
     </div>
     </div>
       </section>
       <!--contact From End Here-->
    </main>
    <footer>
      <div class="row text-white">
        <div class="col-lg-6 text-center text-lg-left mb-3 m-lg-0">
          <p class="small mb-0 mt-1">$copy; Copyright mohammad Mansur</p>
        </div>
        <div class="col-lg-6 text-center text-lg-right">
          <a href="#">Home</a>
          <a href="#"><i class="fab fa-facebook"></i></a>
          <a href="#"><i class="fab fa-likedin"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
          <a href="#"><i class="fab fa-youtube"></i></a>
          <a href="#"><i class="fab fa-instagram"></i></a>
        </div>
      </div>
    </footer>
  </div>
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
