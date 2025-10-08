# Project Responsive Web Design using Bootstrap
## Date:08.10.25

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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dribbble Clone (Bootstrap Only)</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg bg-white shadow-sm py-3">
    <div class="container">
      <a class="navbar-brand fw-bold text-danger" href="#">dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#">Inspiration</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Go Pro</a></li>
          <li class="nav-item"><a class="btn btn-danger text-white ms-lg-3" href="#">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="bg-light text-center py-5">
    <div class="container py-5">
      <h1 class="fw-bold display-5 mb-3">Discover the world’s top designers & creatives</h1>
      <p class="lead mb-4">Dribbble is the leading destination to find & showcase creative work.</p>
      <a href="#" class="btn btn-danger btn-lg">Get Started</a>
    </div>
  </section>

  <!-- Shots Grid -->
  <section class="py-5">
    <div class="container">
      <h2 class="mb-4 text-center">Explore Shots</h2>
      <div class="row g-4">
        <div class="col-md-4 col-sm-6">
          <div class="card border-0">
            <img src="https://picsum.photos/400/300?random=1" class="card-img-top rounded" alt="Shot 1">
          </div>
        </div>
        <div class="col-md-4 col-sm-6">
          <div class="card border-0">
            <img src="https://picsum.photos/400/300?random=2" class="card-img-top rounded" alt="Shot 2">
          </div>
        </div>
        <div class="col-md-4 col-sm-6">
          <div class="card border-0">
            <img src="https://picsum.photos/400/300?random=3" class="card-img-top rounded" alt="Shot 3">
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4">
    <div class="container">
      <p class="mb-1">&copy; 2025 Dribbble Clone. All rights reserved.</p>
      <div>
        <a href="#" class="text-white-50 text-decoration-none me-3">Terms</a>
        <a href="#" class="text-white-50 text-decoration-none me-3">Privacy</a>
        <a href="#" class="text-white-50 text-decoration-none">Contact</a>
      </div>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

~~~

## OUTPUT:
![alt text](<Screenshot 2025-10-08 152846.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
