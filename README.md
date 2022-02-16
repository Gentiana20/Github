
   
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <link rel="preconnect" href="https://fonts.googleapis.com">

    <link rel="stylesheet"href="stle.css">
   
    <title>My portfolio</title>
  </head>
  <body>
     <!--Navbar--> 
     <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
          <a class="navbar-brand fw-bold" href="#">Portfolio</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link"href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Skills</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Services</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Contact</a>
              </li>
          </div>
        </div>
     </nav>

      <!--Home Section-->
      <section id="home">
          <div class="container mb-5">
              <div class="row">
                  <div class="col-md-6 d-flex flex-column justify-content-center">
                      <h3 class="text-warning"> WEB DEVELOPER</h3>
                      <h1 class="display-2 fw-bold" >I'M GENTIANA <br> RAMA</h1>
                      <div class="buttons mt-4">
                          <button class="btn btn-outline-warning px-4 py-2">Hire me </button>
                          <button class="btn btn-warning text-white px-4 py-2"> About</button>
                      </div>
                  </div>
                  <div class="col-md-6"></div>
                  <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-inner">
                      <div class="carousel-item active">
                        <img src="..." class="d-block w-100" alt="..." height="600px">
                      </div>
                      <div class="carousel-item">
                        <img src="..." class="d-block w-100" alt="..." height="600px">
                      </div>
                      <div class="carousel-item">
                        <img src="..." class="d-block w-100" alt="..." height="600px">
                      </div>
                    </div>
                  </div>
              </div>
          </div>
      </section>
     
      
      <!-- About Section-->
      <section id="about">
        <div class="container my-5 py-5">
          <div class="row mb-5">
            <div class="col-12">
              <h1 class="fw-bold text-center"> About me</h1>
              <hr>
            </div>
          </div>
          <div class="row">
            <div class="col-md-6">
              <img src="download.jpg" alt=""height="500px" width="400px">
            </div>
            <div class="col-md-6">
              <h1 class="fw-bold"> Gentiana Rama</h1>
              <h3 class="text-warning-mb-4"> WEB DEVELOPER</h3>
              <p class="lead-mb-4">  Learning programming skills will teach you to approach.  </p>
              <div class="buttons">
                <button class="btn btn-outline-warning px-5 py-2">DOWNLOAD CV</button>
                <button class="btn btn-warning text-white px-4 py-2"> CONTACT</button>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Skills section -->
      <section id="skills">
        <div class="container my-5 py-5">
          <div class="'row mb-5">
            <div class="col-12">
              <h1 class="fw-bold text-center">My Skills</h1>
              <hr>
            </div>
          </div>
          <div class="row">
            <div class="col-md-6">
              <h1 class="fw-bold mb-4"> Skills & Experience</h1>
              <p class="lead"> LOremdkfjslkjfhnkjzhkjhkjczysaugyzghzhgihgchzhjzhjhjxhjcxzhjcx</p>
            </div>
            <div class="col-md-5 d-flex flex-column justify-content-center">
              <div class="progress mb-4">
                <div class="progress-bar bg-danger" role="progressbar" style="width: 80%" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"> HTML</div>
              </div>
              <div class="progress mb-4">
                <div class="progress-bar bg-promary" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">CSS</div>
              </div>
              <div class="progress mb-4">
                <div class="progress-bar bg-warning" role="progressbar" style="width: 60%" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100">JavaScript</div>
              </div>
              <div class="progress mb-4">
                <div class="progress-bar bg-info" role="progressbar" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">React</div>
              </div>
              <div class="progress mb-4">
                <div class="'progress-bar bg-success" role="progress" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">Express JS</div>
              </div>
 
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- Service section -->
        <section id="service">
            <div class="container my-5 py-5">
                <div class="row mb-5">
                    <div class="col-12">
                        <h1 class = "fw-bold text-ceneter"> Services</h1>
                        <hr>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-4">
                        <div class="card p-4" style="width: 18rem;">
                            
                            <div class="card-body text-center">
                            <h3>BackEnd Deverlopment</h3>
                              <p class="card-text text-center">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            </div>
                          </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card p-4" style="width: 18rem;">
                            
                            <div class="card-body text-center">
                            <h3>Database Management</h3>
                              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            </div>
                          </div>
                    </div>
                </div>
            </div>
        </section>

        <!--Contact Section-->
        <section id="contact">
            <div class="container my-5 bg-promary">
                <div class="row mb-5">
                    <div class="col-mb-6 mx-auto">
                        <h1 class="fw-bold text-center"> Contact</h1>
                        <hr>
                    </div>
                </div>
                <div class="row">
                    <div class="cpl-md-6">
                        <form action="">
="">
                            <div class="mb-3">
                                <label for="exampleFormControlInput1" class="form-label">Email address</label>
                                <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
                              </div>
                              <div class="mb-3">
                                <label for="exampleFormControlTextarea1" class="form-label">Example textarea</label>
                                <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
                              </div>
                              </div>
                              <button type="submit" class="btn btn-outline-warning">Send Message</button>

                        </form>
                    </div>
                </div>
            </div>
        <section/>
