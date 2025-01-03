# Ex.07 Restaurant Website
## Date:26-12-24

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-light bg-secondary">
    <a class="navbar-brand" href="#">Restaurant Name</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item">
                <a class="nav-link" href="#">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Menu</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">About</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Contact</a>
            </li>
        </ul>
    </div>
</nav>

<!-- Hero Section -->
<div class="jumbotron jumbotron-fluid text-center">
    <div class="container">
        <h1 class="display-4">Welcome to Akshaay's Restaurant</h1>
        <p class="lead">Experience the best culinary delights.</p>
        <a class="btn btn-primary btn-lg" href="#" role="button">Explore Menu</a>
    </div>
</div>

<!-- Menu Section -->
<div class="container mt-5">
    <h2 class="text-center">Our Menu</h2>
    <div class="row">
        <div class="col-md-4">
            <div class="card mb-4">
                <img src="image1.png" height="300" width="300" class="card-img-top" alt="Dish 1">
                <div class="card-body">
                    <h5 class="card-title">Dish 1</h5>
                    <p class="card-text">A delicious description of Dish 1.</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card mb-4">
                <img src="image2.png" width="300" height="300" class="card-img-top" alt="Dish 2">
                <div class="card-body">
                    <h5 class="card-title">Dish 2</h5>
                    <p class="card-text">A delicious description of Dish 2.</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card mb-4">
                <img src="image.png" width="300" height="300" class="card-img-top" alt="Dish 3">
                <div class="card-body">
                    <h5 class="card-title">Dish 3</h5>
                    <p class="card-text">A delicious description of Dish 3.</p>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- Footer -->
<footer class="bg-secondary text-center py-4">
    <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
</footer>

<!-- Scripts -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](image.png)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
