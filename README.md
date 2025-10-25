# Project Responsive Web Design using Bootstrap
## Date:25/10/2025

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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>dribble</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" />
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <b><a class="navbar-brand" href="dribble.html">Dribble</a></b>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="home.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="service.html">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="text-white text-center py-5">
    <div class="container">
      <h1>Discover the New</h1>
      <p class="lead">Explore our Best and Quality Clothes</p>
    </div>
  </header>

  <!-- Features Section -->
  <section class="container">
    <div class="row text-center">
      <!-- Feature Cards -->
      <div class="col-md-4 mb-4">
        <div class="card h-100">
          <div class="card-body">
            <img src="shirt1.jpg">
          </div>
        
        </div>
        <b>Shirt</b>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card h-100">
          <div class="card-body">
            <img src="pant1.jpg">
          </div>
        </div>
        <b>Pant</b>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card h-100">
          <div class="card-body">
             <img src="tshirt.jpg">
          </div>
        </div>
        <b>T-Shirt</b>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card h-100">
          <div class="card-body">
            <img src="coat.jpg">
          </div>
        </div>
        <b>Coat</b>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card h-100">
          <div class="card-body">
            <img src="shoe.jpg">
          </div>
        </div>
        <b>Shoe</b>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card h-100">
          <div class="card-body">
            <img src="shorts.jpg">
          </div>
        </div>
        <b>Shorts</b>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center py-3">
    <div class="container">
      <p class="mb-0">Designed by ASHFAK N(25003270)</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f8f9fa;
    }

    .navbar {
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    header {
      background: linear-gradient(90deg, #007bff, #00c6ff);
    }

    .card {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card-body{
      
      height:10px;
    }
    
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    }
    .col-md-4{
      height: 240px;
    }
    footer {
      
      background-color: #343a40;
      color: #fff;
    }

```

## OUTPUT:
<img width="1920" height="1200" alt="Screenshot (45)" src="https://github.com/user-attachments/assets/7887af58-b4cd-409a-a38b-053be71e6431" />


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
