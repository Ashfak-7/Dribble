# Project Responsive Web Design using Bootstrap
## Date:16/10/2025

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
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dribbble Clone</title>
 
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
    rel="stylesheet"
  </link>
<link rel="stylesheet" href="style.css" >
</head>
<body>

  
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Explore</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Shots</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Sign In</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero text-center py-5">
    <div class="container">
      <h1>Discover Creative Work</h1>
      <p class="lead">Explore the best design shots from around the world</p>
      <button class="btn btn-primary" onclick="showAlert()">Get Started</button>
    </div>
  </section>

  <!-- Featured Shots -->
  <section class="shots py-5 bg-light">
    <div class="container">
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card">
            
            <img src="s1.jpg" class="card-img-top" alt="Shot 1" />
            <div class="card-body">
              <h5 class="card-title">Design Title 1</h5>
            </div>
          </div>
        </div>
        <!-- Repeat for more cards -->
        <div class="col-md-4">
          <div class="card">
            <img src="s2.jpg" class="card-img-top" alt="Shot 2" />
            <div class="card-body">
              <h5 class="card-title">Design Title 2</h5>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="s3.jpg" class="card-img-top" alt="Shot 3" />
            <div class="card-body">
              <h5 class="card-title">Design Title 3</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  
  <footer class="bg-dark text-white text-center py-3">
    <p>created by ASHFAK N(25003270).</p>
  </footer>

  
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  
  <script src="script.js"></script>
</body>
</html>

.hero {
  background-color: #f8f9fa;
}

.hero h1 {
  font-size: 3rem;
  font-weight: bold;
}

.card-title {
  text-align: center;
  font-weight: 600;
}



function showAlert() {
  alert("Welcome to the Dribbble Clone!");
}


```

## OUTPUT:
![alt text](<Screenshot (42).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
