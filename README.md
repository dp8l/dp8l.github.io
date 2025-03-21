<!--
   ____            _                       _     
  |  _ \ __ _  ___| |__   ___  _   _ _ __ | |__  
  | |_) / _` |/ __| '_ \ / _ \| | | | '_ \| '_ \ 
  |  __/ (_| | (__| | | | (_) | |_| | |_) | | | |
  |_|   \__,_|\___|_| |_|\___/ \__,_| .__/|_| |_|
                                   |_|            
-->

# Devansh Patel  
*Research Engineer & PhD Student*

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <!-- Profile Picture -->
  <div style="flex: 0 0 auto; margin-right: 20px;">
    <img src="images/profile.jpg" alt="Devansh Patel" style="width: 200px; border-radius: 50%; border: 2px solid #ccc;">
  </div>
  <!-- Intro Text -->
  <div style="flex: 1;">
    <p>Welcome to my GitHub page—a simple, retro-styled hub where I share my research, projects, and software tools. I'm a research engineer and PhD student specializing in AI research. My work blends timeless aesthetics with cutting-edge innovation.</p>
  </div>
</div>

---

## Latest Research

Stay tuned for my latest research papers, articles, and publications.  
- **[Paper Title 1](#)** – A brief description of the research and its outcomes.  
- **[Paper Title 2](#)** – A brief description of the research and its outcomes.  
- *More to be added...*

---

## Software Links

Here you'll find links to the software tools and projects I've developed:  
- **[Software Tool 1](#)** – Short description of the tool and its features.  
- **[Software Tool 2](#)** – Short description of the tool and its features.  
- *More tools coming soon...*

---

## Projects

A collection of my projects and collaborative works:  
- **[Project Name 1](#)** – Overview of the project and its objectives.  
- **[Project Name 2](#)** – Overview of the project and its objectives.  
- *Stay tuned for updates...*

---

## Photo Gallery

Below is a dynamic photo slideshow. Simply upload your images to the designated folder (for example, `images/`) and update the JavaScript array with your file names and descriptions.

<div id="slideshow-container" style="max-width: 600px; margin: auto; text-align: center;">
  <img id="slide" src="images/photo1.jpg" alt="Slideshow Image" style="width: 100%; max-height: 400px; object-fit: cover; border: 1px solid #ccc;">
  <div id="slide-description" style="margin-top: 10px; font-style: italic;">Description for photo 1</div>
</div>

<script>
  // Array of slides - add as many images and descriptions as needed.
  const slides = [
    { image: "images/photo1.jpg", description: "Description for photo 1" },
    { image: "images/photo2.jpg", description: "Description for photo 2" },
    { image: "images/photo3.jpg", description: "Description for photo 3" }
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
  
  // Change slide every 3 seconds
  setInterval(nextSlide, 3000);
</script>

---

## Contact

If you'd like to connect or have any inquiries, feel free to reach out:  
- **Email:** [your.email@example.com](mailto:your.email@example.com)  
- **LinkedIn:** [LinkedIn Profile](#)

---

*This page is continually updated with my latest work and contributions. Check back often for new research and project updates!*
