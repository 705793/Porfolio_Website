<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
<script src="Script.js"></script>
    
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#">Portfolio</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item">
                <a class="nav-link" href="#about">About</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#experience">Work Experience</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#education">Education</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#projects">Projects</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#contact">Contact</a>
            </li>
        </ul>
    </div>
</nav>

<!-- Main Content -->
<div class="container mt-5">

    <!-- About Section -->
    <section id="about" class="mb-4">
        <h2>About</h2>
        <p>Name :- Ajinkya Dattatray Tarlekar</p>
        <p>Phone Number: 7057934552</p>
        <p>Brief bio or introduction...</p>
    </section>

   <!-- Skills Section -->
<section id="skills" class="mb-4">
    <h2>Skills</h2>
    <ul class="list-unstyled" id="skillsList">
        <li>Skill A <span class="skill-rating" data-rating="4"></span></li>
        <li>Skill B <span class="skill-rating" data-rating="3"></span></li>
        <li>Skill C <span class="skill-rating" data-rating="3"></span></li>
        <!-- Add more skills here -->
    </ul>
</section>

    <!-- Hobbies Section -->
    <section id="hobbies" class="mb-4">
        <h2>Hobbies</h2>
        <ul class="list-unstyled">
            <li>Hobby 1</li>
            <li>Hobby 2</li>
            <li>Hobby 3</li>
            <!-- Add more hobbies here -->
        </ul>
    </section>

    <!-- Work Experience Section -->
    <section id="experience" class="mb-4">
        <h2>Work Experience</h2>
        <ul>
            <li>Job Title - Company Name (Date)</li>
            <li>Job Title - Company Name (Date)</li>
            <!-- Add more work experiences here -->
        </ul>
    </section>

    <!-- Education Section -->
    <section id="education" class="mb-4">
        <h2>Education</h2>
        <ul>
            <li>Degree - University Name (Year)</li>
            <li>Degree - University Name (Year)</li>
            <!-- Add more education details here -->
        </ul>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="mb-4">
        <h2>Projects</h2>
        <div class="card">
            <div class="card-body">
                <h5 class="card-title">Project Name</h5>
                <p class="card-text">Description of the project...</p>
            </div>
        </div>
        <div class="card mt-3">
            <div class="card-body">
                <h5 class="card-title">Project Name</h5>
                <p class="card-text">Description of the project...</p>
            </div>
        </div>
        <!-- Add more projects here -->
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Phone: [Your Phone Number]</p>
        <p>Email: [Your Email Address]</p>
    </section>

</div>



</body>
</html>






