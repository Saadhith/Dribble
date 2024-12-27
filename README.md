# Project Responsive Web Design using Bootstrap
## Date:27.12.24

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
        <a class="navbar-brand" href="#">Dribbble Clone</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#features">Features</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#gallery">Gallery</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                </li>
            </ul>
        </div>
    </div>
</nav>
<div class="bg-light py-5 text-center">
    <div class="container">
        <h1 class="display-4">Welcome to Dribbble Clone</h1>
        <p class="lead">Showcase your design work and connect with a creative community.</p>
        <a href="#gallery" class="btn btn-primary btn-lg">Explore Gallery</a>
    </div>
</div>
<section id="features" class="py-5">
    <div class="container">
        <div class="row text-center">
            <div class="col-md-4">
                <div class="mb-4">
                    <i class="bi bi-brush fs-1 text-primary"></i>
                </div>
                <h5>Creative Showcase</h5>
                <p>Share your best work with a global audience.</p>
            </div>
            <div class="col-md-4">
                <div class="mb-4">
                    <i class="bi bi-people fs-1 text-primary"></i>
                </div>
                <h5>Community Connections</h5>
                <p>Engage with designers, artists, and creators.</p>
            </div>
            <div class="col-md-4">
                <div class="mb-4">
                    <i class="bi bi-globe fs-1 text-primary"></i>
                </div>
                <h5>Global Reach</h5>
                <p>Expand your influence and get inspired by others.</p>
            </div>
        </div>
    </div>
</section>

<section id="gallery" class="py-5 bg-light">
    <div class="container">
        <h2 class="text-center mb-4">Gallery</h2>
        <div class="row g-4">
            <div class="col-md-4">
                <div class="card">
                    <img src="C:\Users\admin\Desktop\mona lisa.jpg" class="card-img-top" alt="..." height="300">
                    <div class="card-body">
                        <p class="card-text">MONA LISA</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="C:\Users\admin\Desktop\mountain.jpg" class="card-img-top" alt="..." height="300">
                    <div class="card-body">
                        <p class="card-text">MOUNTAIN</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="C:\Users\admin\Desktop\sun.jpg" class="card-img-top" alt="..." height="300">
                    <div class="card-body">
                        <p class="card-text">SUN</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<footer class="py-4 bg-dark text-light">
    <div class="container text-center">
        <p class="mb-0">&copy; DESIGNED BY SUDHINDRA.R</p>
    </div>
</footer>


</body>
</html>
```


## OUTPUT:
![Screenshot 2024-12-27 184222](https://github.com/user-attachments/assets/f4966021-6025-48b8-8b1e-22b7b5478a2f)

![Screenshot 2024-12-27 184235](https://github.com/user-attachments/assets/f9e5e314-961a-4e87-b053-5b57cf31d300)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
