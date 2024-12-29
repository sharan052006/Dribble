# Project Responsive Web Design using Bootstrap
## Date:29-12-2024

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
<head>
    <title>Creative Showcase</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">Dribble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Discover</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Designers</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Projects</a>
                    </li>
                </ul>
                <button class="btn btn-outline-light" data-bs-toggle="modal" data-bs-target="#signUpModal">Sign Up</button>
            </div>
        </div>
    </nav>

    <header class="bg-dark text-white text-center py-5" style="background-image: url('https://source.unsplash.com/1600x900/?creative,design'); background-size: cover;">
        <div class="container">
            <h1 class="display-4 fw-bold">Showcase Your Creativity</h1>
            <p class="lead">Join our community of designers, find inspiration, and share your projects.</p>
        </div>
    </header>

    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Why Join Us?</h2>
            <div class="row text-center">
                <div class="col-md-4 mb-4">
                    <div class="card shadow-sm border-0 rounded">
                        <div class="card-body">
                            <h5 class="card-title">Inspiration</h5>
                            <p class="card-text">Discover new design ideas from creative minds around the world.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card shadow-sm border-0 rounded">
                        <div class="card-body">
                            <h5 class="card-title">Collaboration</h5>
                            <p class="card-text">Work with others to bring your design concepts to life.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card shadow-sm border-0 rounded">
                        <div class="card-body">
                            <h5 class="card-title">Exposure</h5>
                            <p class="card-text">Get recognized for your work and expand your portfolio.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-5">
        <div class="container">
            <h2 class="fw-bold text-center mb-4">Popular Projects</h2>
            <div class="row row-cols-1 row-cols-md-3 g-4">
                <div class="col">
                    <div class="card border-0 shadow-sm rounded">
                        <img src="dribble 1.webp" class="card-img-top rounded" alt="Creative Design">
                        <div class="card-body text-center">
                            <h5 class="card-title">Creative Design</h5>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card border-0 shadow-sm rounded">
                        <img src="dribble 2.webp" class="card-img-top rounded" alt="Unique Concepts">
                        <div class="card-body text-center">
                            <h5 class="card-title">Unique Concepts</h5>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card border-0 shadow-sm rounded">
                        <img src="dribble 3.webp" class="card-img-top rounded" alt="Innovative Ideas">
                        <div class="card-body text-center">
                            <h5 class="card-title">Innovative Ideas</h5>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <div class="modal fade" id="signUpModal" tabindex="-1" aria-labelledby="signUpModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="signUpModalLabel">Sign Up</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <form>
                        <div class="mb-3">
                            <label for="name" class="form-label">Full Name</label>
                            <input type="text" class="form-control" id="name" placeholder="Enter your full name" required>
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Email address</label>
                            <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
                        </div>
                        <div class="mb-3">
                            <label for="password" class="form-label">Password</label>
                            <input type="password" class="form-control" id="password" placeholder="Enter your password" required>
                        </div>
                        <div class="mb-3">
                            <label for="confirmPassword" class="form-label">Confirm Password</label>
                            <input type="password" class="form-control" id="confirmPassword" placeholder="Confirm your password" required>
                        </div>
                        <div class="d-grid">
                            <button type="submit" class="btn btn-primary">Sign Up</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>

    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p class="mb-0">Designed by Sharan I 24010956</p>
        </div>
    </footer>

    
</body>
</html>

    
```

## OUTPUT:
![alt text](<Screenshot (95).png>) 
![alt text](<Screenshot (96).png>) 
![alt text](<Screenshot (97).png>) 

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
