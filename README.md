<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>Food Gallery</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* Custom Styles for Cool Appearance */
        .hero-section {
            background-image: url('https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=1080');
            background-size: cover;
            background-position: center;
            color: white;
            text-shadow: 0 0 10px rgba(0, 0, 0, 0.7);
            padding: 100px 0;
        }

        .hero-section h1 {
            font-size: 3rem;
        }

        .gallery-card img {
            transition: transform 0.3s ease;
        }

        .gallery-card img:hover {
            transform: scale(1.05);
        }

        footer {
            background-color: #343a40;
            color: white;
            padding: 20px 0;
        }

        footer p {
            margin: 0;
        }

        .social-icons img {
            width: 30px;
            margin: 0 10px;
            transition: transform 0.3s ease;
        }

        .social-icons img:hover {
            transform: scale(1.2);
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">FOOD GALLERY</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section text-center">
        <div class="container">
            <h1>Welcome to Food Gallery</h1>
            <p class="lead">Experience the taste of culinary perfection. Quality food at its best!</p>
            <a href="#contact" class="btn btn-primary btn-lg">Contact Us</a>
        </div>
    </section>

    <!-- Food Gallery -->
    <div id="gallery" class="container my-5">
        <h2 class="text-center mb-4">Our Food Gallery</h2>
        <div class="row g-4">
            <div class="col-md-4">
                <div class="card gallery-card">
                    <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=600" class="card-img-top" alt="Appetizers">
                    <div class="card-body">
                        <h5 class="card-title">Appetizers</h5>
                        <p class="card-text">Kickstart your meal with these delightful starters.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card gallery-card">
                    <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=600" class="card-img-top" alt="Main Dishes">
                    <div class="card-body">
                        <h5 class="card-title">Main Dishes</h5>
                        <p class="card-text">Savor our delicious main courses made with fresh ingredients.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card gallery-card">
                    <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=600" class="card-img-top" alt="Desserts">
                    <div class="card-body">
                        <h5 class="card-title">Desserts</h5>
                        <p class="card-text">Indulge in our sweet and delightful desserts.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Contact Form -->
    <div id="contact" class="container my-5">
        <h2 class="text-center mb-4">Contact Us</h2>
        <form>
            <div class="mb-3">
                <label for="name" class="form-label">Name</label>
                <input type="text" class="form-control" id="name" placeholder="Your Name" required>
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="email" placeholder="Your Email" required>
            </div>
            <div class="mb-3">
                <label for="phone" class="form-label">Phone Number</label>
                <input type="text" class="form-control" id="phone" placeholder="Your Phone Number" required>
            </div>
            <div class="mb-3">
                <label for="message" class="form-label">Message</label>
                <textarea class="form-control" id="message" rows="4" placeholder="Your Message" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </div>
<!-- Footer -->
<footer class="text-center text-white" style="background-color: #2c3e50; padding: 40px 0;">
    <div class="container">
        <!-- Footer Text -->
        <h4 class="mb-4">Location: West Legon</h4>
        <p class="mb-4">Contact: (+233547383809)</p>
        <p class="mb-4" style="font-family: 'Helvetica', sans-serif; font-weight: bold; font-style: italic;">
            Quality food at its best
        </p>

        <!-- Social Media Links -->
        <div class="d-flex justify-content-center">
            <a href="#" class="text-white me-3">
                <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook" style="width: 40px;">
            </a>
            <a href="#" class="text-white">
                <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram" style="width: 40px;">
            </a>
        </div>
    </div>

    <!-- Decorative Separator -->
    <div style="height: 1px; background: #f39c12; margin: 20px auto; width: 80%;"></div>

    <!-- Copyright -->
    <p class="mb-0" style="font-size: 0.9rem;">&copy; 2024 Food Gallery. All Rights Reserved.</p>
</footer>
