<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Syed Aabid Ahamed - Portfolio</title>

  <!-- Favicon -->
  <link rel="shortcut icon" href="./assets/images/geniuS.png" type="image/x-icon">

  <!-- Custom CSS link -->
  <link rel="stylesheet" href="./assets/css/style.css">

  <!-- Devicon CSS link -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">

  <!-- Google Font link -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

  <style>
    /* Reset some default styles */
    body,
    h1,
    h2,
    h3,
    h4,
    p,
    ul,
    li {
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Poppins', sans-serif;
    }

    /* Main styles */
    main {
      display: flex;
      justify-content: space-between;
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }

    /* Sidebar styles */
    .sidebar {
      width: 25%;
      background-color: #333;
      color: #fff;
      padding: 20px;
    }

    /* Main Content styles */
    .main-content {
      width: 70%;
    }

    /* Navbar styles */
    .navbar {
      display: flex;
      margin-bottom: 20px;
    }

    .navbar-list {
      display: flex;
      list-style: none;
    }

    .navbar-item {
      margin-right: 10px;
    }

    .navbar-link {
      background-color: #333;
      color: #fff;
      border: none;
      padding: 10px 15px;
      cursor: pointer;
    }

    /* About section styles */
    .about {
      display: block;
    }

    .about-text {
      margin-bottom: 20px;
    }

    /* Service section styles */
    .service {
      margin-bottom: 30px;
    }

    .service-title {
      margin-bottom: 10px;
    }

    .service-list {
      list-style: none;
    }

    .service-item {
      display: flex;
      align-items: center;
      margin-bottom: 10px;
    }

    .service-icon-box {
      margin-right: 10px;
    }

    /* Technical Skills section styles */
    .service-list {
      list-style: none;
    }

    /* Contact section styles */
    .contact {
      display: block;
    }

    .contact-item {
      display: flex;
      align-items: center;
      margin-bottom: 10px;
    }

    .icon-box {
      margin-right: 10px;
    }

    /* Add more styles as needed */
  </style>

</head>

<body>

  <!-- Main Content -->

  <main>

    <!-- Sidebar -->
    <aside class="sidebar" data-sidebar>
      <div class="sidebar-info">
        <!-- Sidebar content goes here -->
      </div>
    </aside>

    <!-- Main Content -->
    <div class="main-content">

      <!-- Navbar -->
      <nav class="navbar">
        <ul class="navbar-list">
          <li class="navbar-item">
            <button class="navbar-link  active" data-nav-link>About</button>
          </li>
          <!-- Add more navbar items as needed -->
        </ul>
      </nav>

      <!-- About Section -->
      <article class="about active" data-page="about">
        <header>
          <h2 class="h2 article-title">About me</h2>
        </header>
        <section class="about-text">
          <!-- About section content goes here -->
        </section>
      </article>

      <!-- Service Section -->
      <article class="service" data-page="service">
        <header>
          <h2 class="h2 article-title">Services</h2>
        </header>
        <section class="service-list">
          <!-- Service section content goes here -->
        </section>
      </article>

      <!-- Technical Skills Section -->
      <article class="technical-skills" data-page="technical-skills">
        <header>
          <h2 class="h2 article-title">Technical Skills</h2>
        </header>
        <section class="technical-skills-list">
          <!-- Technical skills section content goes here -->
        </section>
      </article>

      <!-- Contact Section -->
      <article class="contact" data-page="contact">
        <header>
          <h2 class="h2 article-title">Contact</h2>
        </header>
        <section class="contact-list">
          <!-- Contact section content goes here -->
        </section>
      </article>

    </div>

  </main>

  <!-- Custom JS link -->
  <script src="./assets/js/script.js"></script>

  <!-- Ionicon link -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>

</html>
