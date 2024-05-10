# Project Responsive Web Design using Bootstrap
## Date: 10-05-2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.


### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
#### home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .navbar {
      background-color: #5210c57d; /* Change header color to green */
    }
    footer {
      position: fixed;
      bottom: 0;
      width: 100%;
      background-color: #343a40; /* Change footer color to dark */
      color: white; /* Change text color to white */
      padding: 10px 0;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Dettol</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="w1.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="w2.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="w3.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="w4.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Welcome to Dettol</h1>
        <br>
        <br>
        <br>
        <p>At Dettol we make products to help you protect your family from harmful germs that can cause illness and to keep your home clean and fresh.</p>
        <p>We take pride in providing products that are simple, safe and effective. Our products are made from ingredients that are transparent to all, and used by millions around the globe.
        </p>

    </div>
      <div class="col-md-8">
        <img src="d.jpg.png" class="img-fluid" alt="Pharmacy Image">
      </div>
    </div>
  </div>
  <body background="download (1).jpeg" style="background-repeat: no-repeat; background-size: cover;"></body>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center">
    <div class="container">
      <p>&copy;  All rights reserved by Dettol [Prajin S(212223230151)]</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
#### about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
    .content {
      flex: 1;
    }
    footer {
      background-color: #343a40; /* Dark background color */
      color: white; /* Text color */
      text-align: center;
      padding: 20px 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand href="#">Dettol</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="w1.html">Home</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="w2.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#vision">Vision</a>
            <a class="dropdown-item" href="#mission">Mission</a>
            <a class="dropdown-item" href="#values">Values</a>
            <!-- Add more subheadings as needed -->
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="w3.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5 content">
    <div class="row">
      <div class="col-md-12">
        <h1>About Dettol</h1>
        <div id="vision">
          <h2>Dettol's Purpose</h2>
          <p>Our objective is to be a leading provider of innovative healthcare solutions that improve the quality of life for people around the world.</p>
        </div>
        <div id="mission">
        </div>
        <div id="values">
          
          <ul>
            <li>Today, Dettol is used by families around the world for cleanliness. Our products can be used to cleanse skin, disinfect surfaces, remove mould and even be used for laundry. We’re a part of the furniture - and proud of this responsibility.</li>
            <li>Our Research, Development & Innovation Centres can be found across the globe. From our main laboratory hub sitting in the US to our regional labs in the UK, China and India. It’s here we research, develop and rigorously test products to make sure they’re right for you and the home.</li>
            <li>It is our mission to always look for opportunities to educate families on healthy habits to practice and the best methods of doing so. Learn how we aim to help new parents provide protection for their family.</li>
            <li>We believe in creating a cleaner world, which is why we’ve launched our new wipes made from 100% biodegradable plant fibre and why we’re working on launching more sustainable innovations. In the end, being kinder to the planet starts at home.</li>
            <li>We’re proud to be partnered with many leading health organisations around the world, including Allergy UK, The Global Hygiene Council, National Day Nursery Association and more.</li>
          </ul>
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>
  <body background="download (1).jpeg" style="background-repeat: no-repeat; background-size: cover;"></body>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy;   All rights reserved by Dettol [Prajin S(212223230151)]</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
#### products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      margin: 0;
      padding: 0;
      background: url('download.jpeg') no-repeat center center fixed;
      background-size: cover;
    }
    .content {
      flex: 1;
    }
    footer {
      background-color: rgba(0, 0, 0, 0.8); /* Dark background color with opacity */
      color: white; /* Text color */
      text-align: center;
      padding: 20px 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Dettol</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="w1.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="w2.html">About</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="w3.html">Products <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="w4.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5 content">
    <div class="row">
      <div class="col-md-12">
        <h1>Our Products</h1>
        <div class="card-deck">
          <div class="card">
            <img src="d11.png" class="card-img-top" alt="Product 1" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Sanitizer</h5>
              <p class="card-text">Dettol Hand Sanitizer kills 99.9% of germs instantly, without water. Use anytime, anywhere: while in car, office, handbag, picnics, nappy change, travel, sports etc. Leaves your hands refreshed. Use as often as required.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="d12.png" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Disinfectant</h5>
              <p class="card-text">Dettol Disinfectant Liquid is a multi-purpose hygiene liquid available in Lime Fresh and Menthol Cool variants. It is specially formulated to meet a wide range of uses, and gives you and your family the trusted Dettol protection every day.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="d13.png" class="card-img-top" alt="Product 3" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Antiseptic Liquid</h5>
              <p class="card-text">Dettol Liquid Antiseptic Disinfectant is a proven effective concentrated antiseptic disinfectant that kills bacteria and provides protection against bacteria which can cause infection and illness. It can be used for gentle antiseptic wound cleansing and disinfection and antiseptic skin cleansing.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <body background="download (1).jpeg" style="background-repeat: no-repeat; background-size: cover;"></body>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy;   All rights reserved by Dettol [Prajin S(212223230151)]</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

#### contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Dettol</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="w1.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="w2.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="w3.html">Products</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="w4.html">Contact <span class="sr-only">(current)</span></a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Contact Us</h1>
        <p>For any inquiries or feedback, please fill out the form below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">Your Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <label for="email">Your Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4">
        <h2>PharmaCompany</h2>
        <address>
          <strong>Address:</strong><br>
          Dettol Towers , West Veli ,
          Kochuveli , Thiruvananthapuram - 695001.<br><br>
          <strong>Email:</strong><br>
          info@dettolcaresyou.com<br><br>
          <strong>Phone:</strong><br>
          +9446708291
        </address>
      </div>
    </div>
  </div>
  <body background="download (1).jpeg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy;   All rights reserved by Dettol [Prajin S(212223230151)]</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```


## OUTPUT:
![Screenshot 2024-05-10 225723](https://github.com/Prajin19/Pharma/assets/144979377/cb756f41-789c-4860-a882-dabb35cd8855)
![Screenshot 2024-05-10 225738](https://github.com/Prajin19/Pharma/assets/144979377/57384272-1aea-4302-bf36-d3dc4f0e83ea)
![Screenshot 2024-05-10 225751](https://github.com/Prajin19/Pharma/assets/144979377/7b14ad18-eb4a-468e-b1b7-27d8a8d60149)
![Screenshot 2024-05-10 225806](https://github.com/Prajin19/Pharma/assets/144979377/6544136a-073c-4cdd-bd69-7413c1bd3afa)





## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
