<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Devansh Patel - Research Engineer</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fafafa;
      margin: 0;
      padding: 20px;
      line-height: 1.6;
    }
    h1, h2, h3 {
      margin-top: 1.2em;
      margin-bottom: 0.5em;
    }
    .profile-container {
      display: flex;
      align-items: flex-start;
      margin-bottom: 20px;
    }
    .profile-container img {
      margin-right: 20px;
      border-radius: 50%;
      border: 2px solid #ccc;
    }
    #slideshow-container {
      max-width: 600px;
      margin: 40px auto;
      text-align: center;
    }
    #slide {
      width: 100%;
      max-height: 400px;
      object-fit: cover;
      border: 1px solid #ccc;
    }
    #slide-description {
      margin-top: 10px;
      font-style: italic;
      min-height: 1.5em;
    }
  </style>
</head>
<body>

  <h1>Devansh Patel</h1>
  <p><em>Research Engineer &amp; PhD Student</em></p>

  <!-- Profile Section -->
  <div class="profile-container">
    <!-- Profile Picture in root of repo -->
    <img 
      src="./Devansh%20Patel.jpg" 
      alt="Devansh Patel" 
      width="200" 
    />
    <!-- Intro Text -->
    <div>
      <p>
        Welcome to my GitHub page—a simple, retro-styled hub where I share my research, 
        projects, and software tools. I'm a research engineer and PhD student specializing 
        in AI research. My work blends timeless aesthetics with cutting-edge innovation.
      </p>
    </div>
  </div>

  <hr />

  <!-- Latest Research -->
  <h2>Latest Research</h2>
  <ul>
    <li><strong><a href="#">Paper Title 1</a></strong> – Brief description...</li>
    <li><strong><a href="#">Paper Title 2</a></strong> – Brief description...</li>
    <li>*More to be added...*</li>
  </ul>

  <hr />

  <!-- Software Links -->
  <h2>Software Links</h2>
  <ul>
    <li><strong><a href="#">Software Tool 1</a></strong> – Description...</li>
    <li><strong><a href="#">Software Tool 2</a></strong> – Description...</li>
    <li>*More tools coming soon...*</li>
  </ul>

  <hr />

  <!-- Projects -->
  <h2>Projects</h2>
  <ul>
    <li><strong><a href="#">Project Name 1</a></strong> – Overview of the project...</li>
    <li><strong><a href="#">Project Name 2</a></strong> – Overview of the project...</li>
    <li>*Stay tuned for updates...*</li>
  </ul>

  <hr />

  <!-- Photo Gallery Slideshow -->
  <h2>Photo Gallery</h2>
  <p>
    Below is a dynamic photo slideshow. Place your images in the 
    <code>shared</code> folder and update the script below with their 
    file names and descriptions.
  </p>

  <div id="slideshow-container">
    <!-- Initial slide image -->
    <img id="slide" src="./shared/photo1.png" alt="Slideshow Image" />
    <div id="slide-description">Description for photo 1</div>
  </div>

  <script>
    // Array of slides - you can use PNG, JPG, etc.
    const slides = [
      { image: "./shared/photo1.png", description: "Description for photo 1" },
      { image: "./shared/photo2.jpg", description: "Description for photo 2" },
      { image: "./shared/photo3.png", description: "Description for photo 3" }
    ];

    let currentSlide = 0;

    function showSlide(index) {
      const slide = slides[index];
      document.getElementById("slide").src = slide.image;
      document.getElementById("slide-description").innerText = slide.description;
    }

    function nextSlide() {
      currentSlide = (currentSlide + 1) % slides.length;
      showSlide(currentSlide);
    }

    // Show the first slide immediately
    showSlide(currentSlide);

    // Change slide every 3 seconds
    setInterval(nextSlide, 3000);
  </script>

  <hr />

  <!-- Contact -->
  <h2>Contact</h2>
  <p>
    If you'd like to connect or have any inquiries, feel free to reach out:
    <br />
    <strong>Email:</strong> <a href="mailto:your.email@example.com">your.email@example.com</a>
    <br />
    <strong>LinkedIn:</strong> <a href="#">LinkedIn Profile</a>
  </p>

  <hr />

  <p>
    <em>
      This page is continually updated with my latest work and contributions. 
      Check back often!
    </em>
  </p>

</body>
</html>
