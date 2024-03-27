# EX01 Developing a Simple Webserver
## Date:

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>
<body>
    <nav class="navbar bg-body-tertiary">
        <div class="container-fluid">
          <a class="navbar-brand">Home</a>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            
            <button class="btn btn-outline-success" type="submit">Search</button>
            
          </form>
        </div>
      </nav>
      <div id="carouselExample" class="carousel slide">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="c:\Users\admin\Documents\sam 3.jpg" class="d-block w-100" alt=" ">
          </div>
          <div class="carousel-item">
            <img src="c:\Users\admin\Documents\sam pic2.jpg" class="d-block w-100" alt=" ">
          </div>
          <div class="carousel-item">
            <img src="c:\Users\admin\Documents\sam.jpg" class="d-block w-100" alt=" ">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <div class="card-group">
        <div class="card">
          <img src="c:\Users\admin\Documents\sports.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">FootBall</h5>
            <p class="card-text">If it was a boxing match, the referee would have stopped it. If this was baseball, they would have invoked the mercy rule. If this was a park game, they would have mixed up the teams.</p>
            <p class="card-text"><small class="text-body-secondary">SPORTS NEWS...!!</small></p>
          </div>
        </div>
        <div class="card">
          <img src="c:\Users\admin\Documents\ambani.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Costly Wedding</h5>
            <p class="card-text">This was a costly wedding all around the world.iIt costs moree than 1000 croce</p>
            <p class="card-text"><small class="text-body-secondary">TRENDING MARRIGE...!!</small></p>
          </div>
        </div>
        <div class="card">
          <img src="c:\Users\admin\Documents\sam pic1.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Samantha</h5>
            <p class="card-text">This is a samantha's lastest photoshoot picture.It was going trend in all the online platforms...</p>
            <p class="card-text"><small class="text-body-secondary">HOT NEWS...!!</small></p>
          </div>
        </div>
      </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>

## OUTPUT:
 ![alt text](output.png)

## RESULT:
The program for implementing simple webserver is executed successfully.
