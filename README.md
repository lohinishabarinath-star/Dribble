# Project Responsive Web Design using Bootstrap
## Date:16.10.2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>PharmEasy - Online E-Commerce Store</title>
  
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #f8f9fa;
    }
    header {
      background: linear-gradient(135deg, #9c28a7, #502c9f);
      padding: 50px 0;
      color: white;
    }
    .navbar {
      background-color: #191987;
    }
    .navbar-nav .nav-link {
      color: white !important;
      font-weight: 500;
    }
    .hero {
      background:#ea4c89 url('shop easy-hero.jpg) no-repaet centrer');
      padding: 100px 0;
      color: white;
      text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.6);
      text-align: center;
    }
    .card img {
      height: 200px;
      object-fit: contain;
      padding: 10px;
    }
    .card {
      border: none;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: scale(1.05);
    }
    footer {
      background-color: #343a40;
      padding: 20px;
      color: white;
      margin-top: 50px;
    }
  </style>
</head>

<body>

  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">PharmEasy</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#products">Products</a></li>
          <li class="nav-item"><a class="nav-link" href="#offers">Offers</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact Us</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
   
  <section class="hero">
    <div class="container">
      <h1 class="display-4 fw-bold">S K SHOPPING ZONE</h1>
      <p class="lead">Style it. Love it.Because fashion starts here.❤️ Shop with trust.
Delivered with love.</p>
      <a href="#products" class="btn btn-light btn-lg mt-3">Shop Now</a>
    </div>
  </section>

  <section class="container my-5" id="shop">
  <h2 class="text-center mb-4 fw-bold">🛍️ Shop Now</h2>
  <p class="text-center text-muted mb-5"><h1>WOMENS FASION</h1></p>

  <!-- Featured Products -->
  <section class="container my-5" id="products">
    <h2 class="text-center mb-4">fashion</h2>
    <div class="row g-4">

      <!-- Product 1 -->
      <div class="col-md-3 col-sm-6">
        <div class="card shadow-sm text-center">
          <img src="kurthi.webp" class="card-img-top" alt="Tablet">
          <div class="card-body">
            <h5 class="card-title">kurti</h5>
            <p class="card-text text-success fw-bold">Rs:250</p>
            <button class="btn btn-success btn-sm">Add to Cart</button>
          </div>
        </div>
      </div>

      <!-- Product 2 -->
      <div class="col-md-3 col-sm-6">
        <div class="card shadow-sm text-center">
          <img src="slippers.jpg" class="card-img-top" alt="Capsule">
          <div class="card-body">
            <h5 class="card-title">soft slippers</h5>
            <p class="card-text text-success fw-bold">₹250</p>
            <button class="btn btn-success btn-sm">Add to Cart</button>
          </div>
        </div>
      </div>

      <!-- Product 3 -->
      <div class="col-md-3 col-sm-6">
        <div class="card shadow-sm text-center">
          <img src="makeup.jpg" class="card-img-top" alt="Syrup">
          <div class="card-body">
            <h5 class="card-title">Dazller makeup products</h5>
            <p class="card-text text-success fw-bold">₹350</p>
            <button class="btn btn-success btn-sm">Add to Cart</button>
          </div>
        </div>
      </div>

      <!-- Product 4 -->
      <div class="col-md-3 col-sm-6">
        <div class="card shadow-sm text-center">
          <img src="jewellery.jpg" class="card-img-top" alt="Drips">
          <div class="card-body">
            <h5 class="card-title">jewllery</h5>
            <p class="card-text text-success fw-bold">₹650</p>
            <button class="btn btn-success btn-sm">Add to Cart</button>
          </div>
        </div>
      </div>

    </div>
  </section>

  <section class="container my-5" id="shop">
  <h2 class="text-center mb-4 fw-bold">🛍️ Shop Now</h2>
  <p class="text-center text-muted mb-5"><h1>MENS FASION</h1></p>

  <!-- Featured Products -->
  <section class="container my-5" id="products">
    <h2 class="text-center mb-4">fashion</h2>
    <div class="row g-4">

      <!-- Product 1 -->
      <div class="col-md-3 col-sm-6">
        <div class="card shadow-sm text-center">
          <img src="bracelets.jpg" class="card-img-top" alt="Tablet">
          <div class="card-body">
            <h5 class="card-title">Braclets</h5>
            <p class="card-text text-success fw-bold">Rs:250</p>
            <button class="btn btn-success btn-sm">Add to Cart</button>
          </div>
        </div>
      </div>

      <!-- Product 2 -->
      <div class="col-md-3 col-sm-6">
        <div class="card shadow-sm text-center">
          <img src="watch.jpeg" class="card-img-top" alt="Capsule">
          <div class="card-body">
            <h5 class="card-title">watch</h5>
            <p class="card-text text-success fw-bold">₹350</p>
            <button class="btn btn-success btn-sm">Add to Cart</button>
          </div>
        </div>
      </div>

      <!-- Product 3 -->
      <div class="col-md-3 col-sm-6">
        <div class="card shadow-sm text-center">
          <img src="shirts.jpg" class="card-img-top" alt="Syrup">
          <div class="card-body">
            <h5 class="card-title">Shirt</h5>
            <p class="card-text text-success fw-bold">₹450</p>
            <button class="btn btn-success btn-sm">Add to Cart</button>
          </div>
        </div>
      </div>

      <!-- Product 4 -->
      <div class="col-md-3 col-sm-6">
        <div class="card shadow-sm text-center">
          <img src="shoe.jpg" class="card-img-top" alt="Drips">
          <div class="card-body">
            <h5 class="card-title">Mens shoes</h5>
            <p class="card-text text-success fw-bold">₹650</p>
            <button class="btn btn-success btn-sm">Add to Cart</button>
          </div>
        </div>
      </div>

    </div>
  </section>


  <!-- Offers Section -->
  <section class="bg-light py-5" id="offers">
    <div class="container text-center">
      <h2>Exclusive Offers</h2>
      <p class="lead">Up to 40% off on your first order! Use code <strong></strong></p>
      <a href="#products" class="btn btn-success">Shop Offers</a>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="container my-5" id="contact">
    <h2 class="text-center mb-4">Contact Us</h2>
    <div class="row justify-content-center">
      <div class="col-md-6">
        <form>
          <div class="mb-3">
            <label class="form-label">Name</label>
            <input type="text" class="form-control" placeholder="Your Name">
          </div>
          <div class="mb-3">
            <label class="form-label">Email</label>
            <input type="email" class="form-control" placeholder="Your Email">
          </div>
          <div class="mb-3">
            <label class="form-label">Message</label>
            <textarea class="form-control" rows="4" placeholder="Your Message"></textarea>
          </div>
          <button class="btn btn-success w-100">Submit</button>
        </form>
      </div>
    </div>
  </section>


  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![womens fashion](https://github.com/user-attachments/assets/9a5e3d61-4699-411e-962c-38fb719126d0)
![mens fashion](https://github.com/user-attachments/assets/710779c7-21d7-429a-8cce-9286c4d8c4a3)
![S K shopping zone](https://github.com/user-attachments/assets/eb6bd32b-8b7b-42b6-b4c6-c358e3f8c7ba)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
