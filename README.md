# Project Responsive Web Design using Bootstrap
## Date:

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
Design a navigation bar with links: Inspiration, Find Work, Learn Design, Go Pro, Sign In, Sign Up.

### Step 5:
Add a catchy headline with a search bar.

### Step 6:
Use ```<div>``` containers for each dribbble shot thumbnail.

### Step 7:
Include designer name and likes count below each image.

### Step 8:
Include text like “Find your next design inspiration” with a button (“Join Dribbble” or “Explore”).

### Step 9:
Create a footer with your name and register number.

### Step 10:
Publish the website in the LocalHost.

## PROGRAM :
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
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
                        <a class="nav-link" href="#">Discover</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Jobs</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Sign In</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="bg-primary text-white py-5">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <h1 class="display-4">Discover the world's top designers & creatives.</h1>
                    <p class="lead">Dribbble is the leading destination to find & showcase creative work and home to the world's best design professionals.</p>
                    <a href="#" class="btn btn-light btn-lg">Get Started</a>
                </div>
                <div class="col-lg-6">
                    <img src="image1.jpg" class="img-fluid rounded" alt="Hero Image">
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Section -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Featured Work</h2>
            <div class="row">
                <div class="col-md-6 mb-4">
                    <div class="card">
                        <img src="image2.jpg" class="card-img-top" alt="Featured Image 1">
                        <div class="card-body">
                            <h5 class="card-title">Creative Design</h5>
                            <p class="card-text">A stunning piece of design work showcasing creativity.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 mb-4">
                    <div class="card">
                        <img src="image3.jpg" class="card-img-top" alt="Featured Image 2">
                        <div class="card-body">
                            <h5 class="card-title">Innovative UI</h5>
                            <p class="card-text">An innovative user interface design.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Trending Section -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Trending Now</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <img src="image4.jpg" class="img-fluid rounded" alt="Trending Image">
                    <h5 class="mt-3">Trending Design</h5>
                    <p>Check out the latest trends in design.</p>
                </div>
                <div class="col-md-4 mb-4">
                    <img src="image1.jpg" class="img-fluid rounded" alt="Trending Image 2">
                    <h5 class="mt-3">Creative Ideas</h5>
                    <p>Explore creative ideas from top designers.</p>
                </div>
                <div class="col-md-4 mb-4">
                    <img src="image2.jpg" class="img-fluid rounded" alt="Trending Image 3">
                    <h5 class="mt-3">Modern Art</h5>
                    <p>Modern art pieces that inspire.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Popular Shots Section -->
    <section class="bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-4">Popular Shots</h2>
            <div class="row">
                <div class="col-md-3 mb-4">
                    <img src="image3.jpg" class="img-fluid rounded" alt="Shot 1">
                    <h6 class="mt-2">Shot Title 1</h6>
                    <p class="small">By Designer 1</p>
                </div>
                <div class="col-md-3 mb-4">
                    <img src="image4.jpg" class="img-fluid rounded" alt="Shot 2">
                    <h6 class="mt-2">Shot Title 2</h6>
                    <p class="small">By Designer 2</p>
                </div>
                <div class="col-md-3 mb-4">
                    <img src="image1.jpg" class="img-fluid rounded" alt="Shot 3">
                    <h6 class="mt-2">Shot Title 3</h6>
                    <p class="small">By Designer 3</p>
                </div>
                <div class="col-md-3 mb-4">
                    <img src="image2.jpg" class="img-fluid rounded" alt="Shot 4">
                    <h6 class="mt-2">Shot Title 4</h6>
                    <p class="small">By Designer 4</p>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works Section -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">How Dribbble Works</h2>
            <div class="row text-center">
                <div class="col-md-4 mb-4">
                    <h5>1. Discover</h5>
                    <p>Find inspiration from the world's best designers.</p>
                </div>
                <div class="col-md-4 mb-4">
                    <h5>2. Share</h5>
                    <p>Share your work and get feedback from the community.</p>
                </div>
                <div class="col-md-4 mb-4">
                    <h5>3. Hire</h5>
                    <p>Connect with top talent for your projects.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; 2023 Dribbble Clone. Created by AYSHWARIYA j</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


## OUTPUT:
<img width="1904" height="908" alt="Screenshot 2025-11-13 191633" src="https://github.com/user-attachments/assets/a57a22b5-6fbe-4b3d-9aa8-e5e2ffdacab3" />

<img width="1899" height="911" alt="Screenshot 2025-11-13 191647" src="https://github.com/user-attachments/assets/f16c354a-0ced-49ff-85b6-0bbabeb22c90" />



<img width="1897" height="907" alt="Screenshot 2025-11-13 191659" src="https://github.com/user-attachments/assets/b3d2999f-a259-4237-8399-51a805ffab0c" />

<img width="1897" height="902" alt="Screenshot 2025-11-13 191721" src="https://github.com/user-attachments/assets/c699001e-8bff-4a0c-b342-611b2783c359" />





## RESULT:
The project for responsive web design in creating a clone of dribble.com is completed successfully.
