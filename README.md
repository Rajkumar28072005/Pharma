# Project Responsive Web Design using Bootstrap
## Date:13.05.24

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
home.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - RAJKUMAR PHARMA</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">RAJKUMAR PHARMA</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="web.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
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
        <h2>WELCOME TO RAJKUMAR PHARMA</h2>
        <p>Welcome to Propharma,our mission is to provide safe, effective, and accessible healthcare solutions to patients worldwide.</p>
        <p>At ProPharma, With a relentless focus on innovation and quality, we are at the forefront of cutting-edge medical advancements, ensuring that every product we create is a testament to our unwavering commitment to excellence..</p>
        <p>In addition to medications,ProPharma are pivotal in creating and distributing drugs, vaccines, and medical devices to enhance human health. </p>
        <p>Thank you for choosing ProPharma for your healthcare needs. We look forward to serving you and helping you live a healthier life.</p>
      </div>
      <div class="col-md-4">
        <img src="logo pharma.jpeg" class="img-fluid" alt="Pharmacy Image">
      </div>
    </div>
  </div>
  <body background="1.jpeg" style="background-repeat: no-repeat; background-size: cover;">
  <br>
  <br>
  <br>
  <br>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 RAJKUMAR Pharma. All rights reserved. BY RAJKUMAR G</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About RAJKUMAR Pharma</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">RAJKUMAR Pharma</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h2>ABOUT RAJKUMAR PHARMA</h2>
        <div id="vision">
          <h4>Vision</h4>
          <p>Our vision is to be a leading pharmaceutical company in India and to become a significant global player by providing high quality, affordable and innovative solutions in medicine and treatment.</p>
        </div>
        <div id="mission">
          <h4>Mission</h4>
          <p>Our mission is to We will discover, develop and successfully market pharmaceutical products to prevent, diagnose, alleviate and cure diseases.</p>
        </div>
        <div id="values">
          <h4>Values</h4>
          <ul>
            <li>Quality:From the very beginning, Quality has been the core of our existence. Unimarckens are persistently putting efforts in manufacturing high-quality products for society.</li>
            
            <li>Commitment to Excellence:We believe commitment drives the force for achieving excellence for products to stand at par in the pharmaceutical industry. We pursue </li>
            <li>Customer-oriented: Being a customer-oriented pharma company, the prospect is to digitalize the business by serving quality pharma products online.</li>
            <li>Teamwork: “Teamwork makes the dream work.”</li>
          </ul>
        </div>
        <br>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>
  <body background="2.jpeg" style="background-repeat: no-repeat; background-size: cover;"></body>
  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-3">
    <p>&copy; 2024 RAJKUMAR Pharma. All rights reserved.  BY RAJKUMAR G</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products - RAJKUMAR Pharma</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">RAJKUMAR Pharma</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Products
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">Over-the-counter (OTC) Medications</a>
            <a class="dropdown-item" href="#">Prescription Drugs</a>
            <a class="dropdown-item" href="#">Vaccines</a>
            <a class="dropdown-item" href="#">Supplements</a>
          </div>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="contact.html">Contact</a>
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
  <div class="container mt-3">
    <div class="row">
      <div class="col-md-12">
        <h2>OUR PRODUCT CATEGORIES</h2>
        <div class="card-deck">
          <div class="card">
            <img src="OTC.jpeg" class="card-img-top" alt="Product 1" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Over-the-counter (OTC)</h5>
              <p class="card-text">These drugs you can buy without a prescription. Some OTC medicines relieve aches, pains, and itches.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="DRUGS.jpeg" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title"> prescription drug</h5>
              <p class="card-text">a pharmaceutical drug that is permitted to be dispensed only to those with a medical prescription.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="VACCINE.jpeg" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Vaccine</h5>
              <p class="card-text">A vaccine is a biological preparation that provides active acquired immunity to a particular infectious or malignant disease.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="SUPPLEMENTS.jpeg" class="card-img-top" alt="Product 3" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Supplements</h5>
              <p class="card-text">These include vitamins, minerals, herbs and botanicals, probiotics, and more.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 RAJKUMAR Pharma. All rights reserved.BY RAJKUMAR G</p>
  </footer>
  <body background="3.jpeg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - RAJKUMAR Pharma</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">RAJKUMAR Pharma</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="contact.html">Contact <span class="sr-only">(current)</span></a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h2>CONTACT US</h2>
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
            <textarea class="form-control" id="message" rows=3" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4">
        <h2>RAJKUMARPharma</h2>
        <address>
          <strong>Address:</strong><br>
          MOUNT ROAD,THIRUCHY<br>
          India, 600007<br><br>
          <strong>Email:</strong><br>
          rajkumar@propharma.com<br><br>
          <strong>Phone:</strong><br>
          +91 9790213221
        </address>
      </div>
    </div>
  </div>
 
  <body background="4.jpeg" style="background-repeat: no-repeat; background-size: cover;">

    <br>
    <br>
  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-2 ">
    <p>&copy; 2024 RAJKUMAR Pharma. All rights reserved.BY RAJKUMAR G</p>

  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

## OUTPUT:
![Screenshot 2024-05-13 184911](https://github.com/Rajkumar28072005/Pharma/assets/144980101/29632315-807c-4e28-a3f2-037db4af417b)

![Screenshot 2024-05-13 184919](https://github.com/Rajkumar28072005/Pharma/assets/144980101/27366ae1-80f4-444d-97ec-4bcef2c06888)

![Screenshot 2024-05-13 184927](https://github.com/Rajkumar28072005/Pharma/assets/144980101/f0876fff-8935-44c8-bf58-159c862d3105)

![Screenshot 2024-05-13 184935](https://github.com/Rajkumar28072005/Pharma/assets/144980101/db36bf4b-6c80-435a-9c82-cb9aeeb97198)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
