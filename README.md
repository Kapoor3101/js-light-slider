<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightslider/1.1.6/css/lightslider.min.css">
<link rel="stylesheet" href="index.css">

    <title></title>
  </head>
  <body>
    <!-- navbar content -->


    <nav class="navbar navbar-expand-lg navbar-dark bg-dark custom_nav">
  <div class="container">
    <a class="navbar-brand" href="#">MySite</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu drop_down" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class=" btn btn-success btn-sm form-control me-2" data-bs-toggle="modal" data-bs-target="#Reg_Online" type="submit" value="Register Online">
      </form>
    </div>
  </div>
</nav>


<!-- Register online pop up section -->

<div class="modal fade" id="Reg_Online" tabindex="-1" aria-labelledby="Reg_Online" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Register Online</h5>

        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
<div class="custom-divider">

</div>

      <div class="modal-body">

          <p class="modal_para">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        <form class="" action="index.html" method="post">

          <div class="mb-3">
            <input class="form-control form-control-sm" type="text" name="" placeholder="Name"required>
          </div>
          <div class="mb-3">
            <input class="form-control form-control-sm" type="email" name="" placeholder="Email"required>
          </div>
          <div class="mb-3">
            <input class="form-control form-control-sm" type="tel" name="" placeholder="Employee Number"required>
          </div>
          <div class="mb-3">
          <input class="form-control form-control-sm" type="text" name="" placeholder="Course Name"required>

          </div>
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-success btn-sm form-control">Register Online</button>
          </div>
        </div>
      </div>

      </div>

      <!-- Home page banner -->


      <header class="main-header">
        <div class="container">

      <div class="row">
      <div class="col-lg-8 col-md-8 mt-4">
        <div class="header-text-holder text-white">
            <h1 class="ban_head">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</h1>
            <p class="ban_para"> Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

          </div>
          </div>
          </div>

<div class="row">
    <div class="col-lg-6 col-md-6">
      <form>
      <div class="input-group">
        <input class="form-control form-control-sm srch_btn d-none d-sm-block"type="search" name="" placeholder="Search Here..." aria-label="Searchspace" aria-describedby="button-addon2">
        <button class="btn btn btn-sm btn-success d-none d-sm-block"  type="submit"  id="button-addon2" <i class="icon-search">&#128270;</button>>
      </div>

      </form>
    </div>






  </div>

  <div class="row d-xl-none d-xl-block">
    <div class="col-lg-6 col-md-6">
      <div class="subscribe-holder">
        <a class="btn btn-light mt-4 onl_btn text-white call_btn" href="#" data-bs-toggle="modal" data-bs-target="#registeremodal" name="button">Register Online</a>

      </div>

    </div>

  </div>





        </div>




      </header>

      <!-- register Modal -->

      <div class="modal fade" id="registeremodal" tabindex="-1" aria-labelledby="registeremodal" aria-hidden="true">
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title" id="exampleModalLabel">Register Online</h5>

              <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
      <div class="custom-divider">

      </div>

            <div class="modal-body">

                <p class="modal_para">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
              <form class="" action="index.html" method="post">

                <div class="mb-3">
                  <input class="form-control form-control-sm" type="text" name="" placeholder="Name"required>
                </div>
                <div class="mb-3">
                  <input class="form-control form-control-sm" type="email" name="" placeholder="Email"required>
                </div>
                <div class="mb-3">
                  <input class="form-control form-control-sm" type="tel" name="" placeholder="Employee Number"required>
                </div>
                <div class="mb-3">
                <input class="form-control form-control-sm" type="text" name="" placeholder="Course Name"required>

                </div>
                </div>
                <div class="modal-footer">
                  <button type="button" class="btn btn-success btn-sm form-control">Register Online</button>
                </div>
              </div>
            </div>

            </div>


            <!-- Section features -->

            <section class="features">

              <div class="container">
                <div class="row">
                  <div class="col-lg-3 col-md-6 col-sm-6 col-6 mt-4">


                    <div class="feature-holder">
<h2>
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="30" fill="currentColor" class="bi bi-clock-history svg_img" viewBox="0 0 16 16">
<path d="M8.515 1.019A7 7 0 0 0 8 1V0a8 8 0 0 1 .589.022l-.074.997zm2.004.45a7.003 7.003 0 0 0-.985-.299l.219-.976c.383.086.76.2 1.126.342l-.36.933zm1.37.71a7.01 7.01 0 0 0-.439-.27l.493-.87a8.025 8.025 0 0 1 .979.654l-.615.789a6.996 6.996 0 0 0-.418-.302zm1.834 1.79a6.99 6.99 0 0 0-.653-.796l.724-.69c.27.285.52.59.747.91l-.818.576zm.744 1.352a7.08 7.08 0 0 0-.214-.468l.893-.45a7.976 7.976 0 0 1 .45 1.088l-.95.313a7.023 7.023 0 0 0-.179-.483zm.53 2.507a6.991 6.991 0 0 0-.1-1.025l.985-.17c.067.386.106.778.116 1.17l-1 .025zm-.131 1.538c.033-.17.06-.339.081-.51l.993.123a7.957 7.957 0 0 1-.23 1.155l-.964-.267c.046-.165.086-.332.12-.501zm-.952 2.379c.184-.29.346-.594.486-.908l.914.405c-.16.36-.345.706-.555 1.038l-.845-.535zm-.964 1.205c.122-.122.239-.248.35-.378l.758.653a8.073 8.073 0 0 1-.401.432l-.707-.707z"/>
<path d="M8 1a7 7 0 1 0 4.95 11.95l.707.707A8.001 8.001 0 1 1 8 0v1z"/>
<path d="M7.5 3a.5.5 0 0 1 .5.5v5.21l3.248 1.856a.5.5 0 0 1-.496.868l-3.5-2A.5.5 0 0 1 7 9V3.5a.5.5 0 0 1 .5-.5z"/>
</svg>
                    </h2>
<h3 class="Sec_head text-sm">Feature Title</h3>

<p class="sec_para">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt.</p>

                  </div>


      </div>


                    <div class="col-lg-3 col-md-6 col-sm-6 col-6 mt-4">
                    <div class="feature-holder">
  <h2>
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="30" fill="currentColor" class="bi bi-clock-history svg_img" viewBox="0 0 16 16">
  <path d="M8.515 1.019A7 7 0 0 0 8 1V0a8 8 0 0 1 .589.022l-.074.997zm2.004.45a7.003 7.003 0 0 0-.985-.299l.219-.976c.383.086.76.2 1.126.342l-.36.933zm1.37.71a7.01 7.01 0 0 0-.439-.27l.493-.87a8.025 8.025 0 0 1 .979.654l-.615.789a6.996 6.996 0 0 0-.418-.302zm1.834 1.79a6.99 6.99 0 0 0-.653-.796l.724-.69c.27.285.52.59.747.91l-.818.576zm.744 1.352a7.08 7.08 0 0 0-.214-.468l.893-.45a7.976 7.976 0 0 1 .45 1.088l-.95.313a7.023 7.023 0 0 0-.179-.483zm.53 2.507a6.991 6.991 0 0 0-.1-1.025l.985-.17c.067.386.106.778.116 1.17l-1 .025zm-.131 1.538c.033-.17.06-.339.081-.51l.993.123a7.957 7.957 0 0 1-.23 1.155l-.964-.267c.046-.165.086-.332.12-.501zm-.952 2.379c.184-.29.346-.594.486-.908l.914.405c-.16.36-.345.706-.555 1.038l-.845-.535zm-.964 1.205c.122-.122.239-.248.35-.378l.758.653a8.073 8.073 0 0 1-.401.432l-.707-.707z"/>
  <path d="M8 1a7 7 0 1 0 4.95 11.95l.707.707A8.001 8.001 0 1 1 8 0v1z"/>
  <path d="M7.5 3a.5.5 0 0 1 .5.5v5.21l3.248 1.856a.5.5 0 0 1-.496.868l-3.5-2A.5.5 0 0 1 7 9V3.5a.5.5 0 0 1 .5-.5z"/>
  </svg>
                    </h2>
  <h3 class="Sec_head">Feature Title</h3>

  <p class="sec_para">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt.</p>

                  </div>


</div>
                      <div class="col-lg-3 col-md-6 col-sm-6 col-6 mt-4">
                    <div class="feature-holder">
  <h2>
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="30" fill="currentColor" class="bi bi-clock-history svg_img" viewBox="0 0 16 16">
  <path d="M8.515 1.019A7 7 0 0 0 8 1V0a8 8 0 0 1 .589.022l-.074.997zm2.004.45a7.003 7.003 0 0 0-.985-.299l.219-.976c.383.086.76.2 1.126.342l-.36.933zm1.37.71a7.01 7.01 0 0 0-.439-.27l.493-.87a8.025 8.025 0 0 1 .979.654l-.615.789a6.996 6.996 0 0 0-.418-.302zm1.834 1.79a6.99 6.99 0 0 0-.653-.796l.724-.69c.27.285.52.59.747.91l-.818.576zm.744 1.352a7.08 7.08 0 0 0-.214-.468l.893-.45a7.976 7.976 0 0 1 .45 1.088l-.95.313a7.023 7.023 0 0 0-.179-.483zm.53 2.507a6.991 6.991 0 0 0-.1-1.025l.985-.17c.067.386.106.778.116 1.17l-1 .025zm-.131 1.538c.033-.17.06-.339.081-.51l.993.123a7.957 7.957 0 0 1-.23 1.155l-.964-.267c.046-.165.086-.332.12-.501zm-.952 2.379c.184-.29.346-.594.486-.908l.914.405c-.16.36-.345.706-.555 1.038l-.845-.535zm-.964 1.205c.122-.122.239-.248.35-.378l.758.653a8.073 8.073 0 0 1-.401.432l-.707-.707z"/>
  <path d="M8 1a7 7 0 1 0 4.95 11.95l.707.707A8.001 8.001 0 1 1 8 0v1z"/>
  <path d="M7.5 3a.5.5 0 0 1 .5.5v5.21l3.248 1.856a.5.5 0 0 1-.496.868l-3.5-2A.5.5 0 0 1 7 9V3.5a.5.5 0 0 1 .5-.5z"/>
  </svg>
                    </h2>
  <h3 class="Sec_head">Feature Title</h3>

  <p class="sec_para">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt.</p>
</div>
                  </div>

                        <div class="col-lg-3 col-md-6 col-sm-6 col-6 mt-4">
                      <div class="feature-holder">
  <h2>
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="30" fill="currentColor" class="bi bi-clock-history svg_img" viewBox="0 0 16 16">
  <path d="M8.515 1.019A7 7 0 0 0 8 1V0a8 8 0 0 1 .589.022l-.074.997zm2.004.45a7.003 7.003 0 0 0-.985-.299l.219-.976c.383.086.76.2 1.126.342l-.36.933zm1.37.71a7.01 7.01 0 0 0-.439-.27l.493-.87a8.025 8.025 0 0 1 .979.654l-.615.789a6.996 6.996 0 0 0-.418-.302zm1.834 1.79a6.99 6.99 0 0 0-.653-.796l.724-.69c.27.285.52.59.747.91l-.818.576zm.744 1.352a7.08 7.08 0 0 0-.214-.468l.893-.45a7.976 7.976 0 0 1 .45 1.088l-.95.313a7.023 7.023 0 0 0-.179-.483zm.53 2.507a6.991 6.991 0 0 0-.1-1.025l.985-.17c.067.386.106.778.116 1.17l-1 .025zm-.131 1.538c.033-.17.06-.339.081-.51l.993.123a7.957 7.957 0 0 1-.23 1.155l-.964-.267c.046-.165.086-.332.12-.501zm-.952 2.379c.184-.29.346-.594.486-.908l.914.405c-.16.36-.345.706-.555 1.038l-.845-.535zm-.964 1.205c.122-.122.239-.248.35-.378l.758.653a8.073 8.073 0 0 1-.401.432l-.707-.707z"/>
  <path d="M8 1a7 7 0 1 0 4.95 11.95l.707.707A8.001 8.001 0 1 1 8 0v1z"/>
  <path d="M7.5 3a.5.5 0 0 1 .5.5v5.21l3.248 1.856a.5.5 0 0 1-.496.868l-3.5-2A.5.5 0 0 1 7 9V3.5a.5.5 0 0 1 .5-.5z"/>
  </svg>
                    </h2>
  <h3 class="Sec_head">Feature Title</h3>

  <p class="sec_para">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt.</p>
</div>
                  </div>


                </div>

              </div>

            </section>


            <!-- Online course section -->

            <section class="online-course mt-4">
              <div class="container">
                <div class="row justify-content-center">
                  <div class="col-lg-6 col-md-6">

                      <h2 class="h1">Online Courses</h2>
                      <p class="onl9_para">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt. consectetur adipisicing elit, sed do eiusmod tempor incididunt</p>
<a class="btn btn-dark btn-sm view" href="#">View All Courses</a>

                  </div>

                </div>

                <div class="row mt-4">
                  <div class="col-lg-4 col-md-4 col-6">
                    <div class="card my_card mt-2">
                      <img src="https://source.unsplash.com/random/3000x1500" alt="" class="img-fluid">
                      <div class="card-body my_cardbody">
                        <h3 class="card-title card_title">Graphic Course</h3>
                        <p class="card-content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                      <a class="btn btn-dark btn-sm" href="">View Course</a>

                      </div>

                    </div>


                  </div>


                  <div class="col-lg-4 col-md-4 col-6">
                    <div class="card my_card mt-2">
                      <img src="https://source.unsplash.com/random/3000x1500" alt="" class="img-fluid">
                      <div class="card-body my_cardbody">
                        <h3 class="card-title card_title">Graphic Course</h3>
                        <p class="card-content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                      <a class="btn btn-dark btn-sm" href="">View Course</a>

                      </div>

                    </div>


                  </div>

                  <div class="col-lg-4 col-md-4 col-6">
                    <div class="card my_card mt-2">
                      <img src="https://source.unsplash.com/random/3000x1500" alt="" class="img-fluid">
                      <div class="card-body my_cardbody">
                        <h3 class="card-title card_title">Graphic Course</h3>
                        <p class="card-content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                      <a class="btn btn-dark btn-sm" href="">View Course</a>

                      </div>

                    </div>


                  </div>

                  <div class="col-lg-4 col-md-4 col-6">
                    <div class="card my_card mt-2">
                      <img src="https://source.unsplash.com/random/3000x1500" alt="" class="img-fluid">
                      <div class="card-body my_cardbody">
                        <h3 class="card-title card_title">Graphic Course</h3>
                        <p class="card-content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>

                      <a class="btn btn-dark btn-sm" href="">View Course</a>

                      </div>

                    </div>


                  </div>
                  <div class="col-lg-4 col-md-4 col-6">
                    <div class="card my_card mt-2">
                      <img src="https://source.unsplash.com/random/3000x1500" alt="" class="img-fluid">
                      <div class="card-body my_cardbody">
                        <h3 class="card-title card_title">Graphic Course</h3>
                        <p class="card-content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                      <a class="btn btn-dark btn-sm" href="">View Course</a>

                      </div>

                    </div>


                  </div>
                  <div class="col-lg-4 col-md-4 col-6">
                    <div class="card my_card mt-2">
                      <img src="https://source.unsplash.com/random/3000x1500" alt="" class="img-fluid">
                      <div class="card-body my_cardbody">
                        <h3 class="card-title card_title">Graphic Course</h3>
                        <p class="card-content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                      <a class="btn btn-dark btn-sm" href="">View Course</a>

                      </div>

                    </div>


                  </div>


                </div>

              </div>

            </section>

            <!-- classroom training courses-->

            <section class="classroom-training">
              <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-6 col-md-6">

                        <h2 class="h1">Classroom Training Courses</h2>
                        <p class="onl9_para">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt. consectetur adipisicing elit, sed do eiusmod tempor incididunt</p>
  <a class="btn btn-dark btn-sm view btn_ " href="#">View All Courses</a>

                    </div>

                  </div>

                </div>

              </div>

            </section>



            <!-- Morecourse section 2 ways -->
<section>

<div class="container">


<div class="row">

            <div class="col-lg-4 col-md-4 mt-4">

              <aside class="">

                <div class="card text-white bg-dark mb-3 d-none d-sm-block">
                      <div class="card-body">
                        <h5 class="card-title text-white">Sign-Up to get more details</h5>
                        <div class="card-text">
                          <p class="text-white card_smtext">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut.</p>

                        </div>
                        <form class="" action="index.html" method="post">
                          <input class="form-control form-control-sm mt-3" type="Name" name="" placeholder="Please Enter Your Name"required>
                          <input class="form-control form-control-sm mt-3" type="email" name="" placeholder="Enter Your Email Id"required>
                          <input class="form-control form-control-sm mt-3" type="tel" name="" placeholder="Phone">
                          <input class="form-control form-control-sm mt-3" type="text" name="" placeholder="Please Enter Your Course Name">
                          <button class=" btn btn btn-sm btn-primary mt-3 w-100" type="submit" name="button">Register Online Now!</button>
                        </form>

                      </div>
                    </div>
</div>
                    <div class="col-lg-8 col-md-8 col-sm-12 col-12 mt-4">

<div class="card_3 bg-dark">



                      <ol class="breadcrumb">
                        <li class="breadcrumb-item"><a class="text-white" href="#">Classroom Training</a></li>
                        <li class="breadcrumb-item "><a class="text-white" href="#">Career Based</a></li>
                        <li class="breadcrumb-item"><a class="text-white"href="#">Short Term</a></li>
                        <li class="breadcrumb-item"><a class="text-white"href="#">Personality Development</a></li>
                      </ol>
                    </div>
<hr class="solid">

<div class="container">
  <div class="row"

  <div class="col-lg-12 col-md-12 col-12">
    <div class="list-group">
      <div class="list-group-item">
        <a href="#">


  <div class="row">
    <div class="col-lg-3 col-md-3 col-3">
      <img class="img_1" src="https://source.unsplash.com/random/300x150" alt="" class="img-fluid">

    </div>
    <div class="col-lg-9 col-md-9 col-9">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.

    </div>

  </div>



        </a>

      </div>

    </div>

    <a class="list-group-item" href="#">
    <div class="row">
      <div class="col-lg-3 col-md-3 col-3">
        <img class="img_1" src="https://source.unsplash.com/random/300x150" alt="" class="img-fluid">

      </div>
      <div class="col-lg-9 col-md-9 col-9">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.

      </div>

    </div>
  </a>
  <a class="list-group-item" href="#">
  <div class="row">
    <div class="col-lg-3 col-md-3 col-3">
      <img class="img_1" src="https://source.unsplash.com/random/300x150" alt="" class="img-fluid">

    </div>
    <div class="col-lg-9 col-md-9 col-9">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.

    </div>

  </div>
</a>
  </div>






    </div>
  </div>





        </div>

      </div>


    </div>



  </div>




</div>

          </aside>


          <!-- Review section slider -->

          <section class="review-slider">

          <div class="container mt-5 text-center rvw_container">
            <div class="row">
            <div class="row justify-content-center">
<div class="col-lg-6 col-md-6">
  <h5 class="rvw_head">What Do Customers Think About Us?</h5>
  <div class="col-lg-12">
    <div id="review-slider-holder">
      <ul id="review_slider_content">
        <li>
<div class="card mt-3">
<div class="card-body">
<svg class="" xmlns="http://www.w3.org/2000/svg" width="66" height="36" fill="currentColor" class="bi bi-people-fill" viewBox="0 0 16 16">
<path d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1H7zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"/>
<path fill-rule="evenodd" d="M5.216 14A2.238 2.238 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.325 6.325 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1h4.216z"/>
<path d="M4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5z"/>
</svg>
<h6 class="card-title">Kshitij</h6>
<h5 class="star">
<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
  <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
</svg>
<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
  <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
</svg>
<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
  <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
</svg>
<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
  <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
</svg>
<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
  <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
</svg>



</h5>
<p class="card-text">
Good Service</p>

</div>

</div>


        </li>
        <li>
          <div class="card">
            <div class="card-body">
              <svg xmlns="http://www.w3.org/2000/svg" width="66" height="36" fill="currentColor" class="bi bi-people-fill" viewBox="0 0 16 16">
              <path d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1H7zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"/>
              <path fill-rule="evenodd" d="M5.216 14A2.238 2.238 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.325 6.325 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1h4.216z"/>
              <path d="M4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5z"/>
            </svg>
              <h6 class="card-title">Sandhya</h6>
              <h5 class="star">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                  <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                </svg>
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                  <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                </svg>
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                  <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                </svg>
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                  <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                </svg>
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                  <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                </svg>



              </h5>
              <p class="card-text">
              Timely Delivery</p>
            </li>

            <li>
              <div class="card">
                <div class="card-body">
                  <svg xmlns="http://www.w3.org/2000/svg" width="66" height="36" fill="currentColor" class="bi bi-people-fill" viewBox="0 0 16 16">
                  <path d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1H7zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"/>
                  <path fill-rule="evenodd" d="M5.216 14A2.238 2.238 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.325 6.325 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1h4.216z"/>
                  <path d="M4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5z"/>
                </svg>
                  <h6 class="card-title">Aakash</h6>
                  <h5 class="star">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                      <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                    </svg>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                      <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                    </svg>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                      <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                    </svg>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                      <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                    </svg>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                      <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                    </svg>



                  </h5>
                  <p class="card-text">
                  Great Experience</p>
            </li>

            <li>
              <div class="card">
                <div class="card-body">
                  <svg xmlns="http://www.w3.org/2000/svg" width="66" height="36" fill="currentColor" class="bi bi-people-fill" viewBox="0 0 16 16">
                  <path d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1H7zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"/>
                  <path fill-rule="evenodd" d="M5.216 14A2.238 2.238 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.325 6.325 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1h4.216z"/>
                  <path d="M4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5z"/>
                </svg>
                  <h6 class="card-title">Charu</h6>
                  <h5 class="star">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                      <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                    </svg>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                      <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                    </svg>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                      <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                    </svg>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                      <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                    </svg>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-star-fill" viewBox="0 0 16 16">
                      <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                    </svg>



                  </h5>
                  <p class="card-text">
                  Good Offers</p>
            </li>

      </ul>

    </div>


</div>
            </div>

            </div>
          </div>






          </section>



</div>
        </section>


<!-- Footer section -->

<div class="main-footer">
  <div class="container">
    <div class="row">
      <div class="col-lg-3 col-md-6 col-sm-6 col-6">
        <aside class="footer-widget">
          <h5 class="head_foot text-white">Follow Us</h5>

          <ul class="item_widget">
            <li>
<a class="text1" href="#">Facebook</a>
            </li>
            <li>
<a class="text1" href="#">Instragram</a>
            </li>

            <li>
<a class="text1" href="#">Twitter</a>

            </li>
          </ul>

        </aside>



      </div>


        <div class="col-lg-3 col-md-6 col-sm-6 col-6">
          <aside class="footer-widget">
            <h5 class="head_foot text-white">Site Map</h5>

            <ul class="item_widget">
              <li>
  <a class="text1" href="#">Home</a>
              </li>
              <li>
  <a class="text1" href="#">About Us</a>
              </li>

              <li>
  <a class="text1" href="#">Courses</a>

              </li>

              <li>
  <a class="text1" href="#">Contact Support</a>

              </li>
            </ul>

          </aside>

        </div>


          <div class="col-lg-3 col-md-6 col-sm-6 col-6">
            <aside class="footer-widget">
              <h5 class="head_foot text-white">Recent Additions</h5>

              <ul class="item_widget">
                <li>
    <a class="text1" href="#">New Courses</a>
                </li>
                <li>
    <a class="text1" href="#">New Offers</a>
                </li>

                <li>
    <a class="text1" href="#">New Plans</a>

                </li>
              </ul>

            </aside>

          </div>



          <div class="col-lg-3 col-md-6 col-sm-6 col-6">
            <aside class="footer-widget">
              <h5 class="head_foot text-white">Company</h5>

<b class="text-white">Email:
<a class="item_email" href="#">care@tabletshablet.com</a>

</b>
<p></p>

<b class="text-white">Phone:
<a class="item_widget" href="#">9810574704</a>

</b>



            </aside>

          </div>

        </div>

      </div>


    </div>




  </div>

</div>





    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-U1DAWAznBHeqEIlVSCgzq+c9gqGAJn5c/t99JyeKa9xxaYpSvHU5awsuZVVFIhvj" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightslider/1.1.6/js/lightslider.min.js">

</script>
<script type="text/javascript">
  $(document).ready(function() {
    $("#review_slider_content").lightSlider()

  });

</script>
    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js" integrity="sha384-eMNCOe7tC1doHpGoWe/6oMVemdAVTMs2xqW4mwXrXsW0L84Iytr2wi5v2QjrP/xp" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.min.js" integrity="sha384-cn7l7gDp0eyniUwwAZgrzD06kc/tftFf19TOAs2zVinnD/C7E91j9yyk5//jjpt/" crossorigin="anonymous"></script>
    -->
  </body>
</html>
