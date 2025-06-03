# My-Portfolio
new repo
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>My Portfolio - Data Analyst</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://cdn.jsdelivr.net/npm/remixicon/fonts/remixicon.css" rel="stylesheet" />
</head>
<body>
  <div id="preloader"></div>

  <main class="page page1">
    <header>
      <div class="portfolio-title">My Portfolio</div>
      <div class="top-right-info">
        <span><i class="ri-map-pin-fill"></i> Bhubaneswar, Ind</span>
        <span><i class="ri-phone-fill"></i> +91 72054 44744</span>
        <span><i class="ri-briefcase-fill"></i> Gita Autonomous College</span>
      </div>
    </header>

    <section class="intro-section">
      <h1>I'm <span class="animated-name">Akshaya Kumar Rautaray</span></h1>
      <h2 class="animated-role">Data Analyst</h2>

      <div class="about box">
        <h3>About Me</h3>
        <p> I am currently pursuing my 6th semester of 
B.Tech, with a strong passion for 
programming and technology. Throughout 
my academic journey, I have worked on 
multiple projects, honing my skills in 
software development and problem
solving. I also have hands-on internship 
experience in the Machine Learning and 
Data Science domains, where I applied 
theoretical knowledge to real-world 
challenges. I am eager to contribute my 
technical skills, work collaboratively with 
teams, and continue growing in the field of 
technology.</p>
      </div>

      <a class="resume-download" href="Akshaya Routaray.pdf" download>
        <i class="ri-download-line"></i> Download Resume
      </a>

      <a href="#page2" class="scroll-icon scroll-down" aria-label="Scroll Down">
        <i class="ri-arrow-down-s-line"></i>
      </a>
    </section>

    <div class="background-3d bg1"></div>
  </main>

  <section id="page2" class="page page2">
    <div class="content-wrapper">
      <div class="content-boxes-vertical">
        <div class="key Achivement box">
          <h3>Key Ahievements</h3>
          <li>Implemented and compared multiple machine learning algorithms for optimal performance. </li>
          <li>Achieved high classification accuracy and low false positive/negative rates. </li>
          <li>Conducted thorough model evaluation using metrics like precision, recall, and F1-score.</li>
        </div>

        <div class="projects box">
          <h3>Projects</h3>
          <h4> Email spam detection with machine learning:-</h4>
          <ul>
            <li>Objective: The goal of the project was to design and develop an efficient and user-friendly Online 
Hotel Management System that streamlines hotel operations.</li>
            <li> Solution :As a team member, contributed to the system analysis, flow design, and development of key 
features, ensuring a seamless interface for both customers and hotel staff. </li>
            <li>Future Scope :Future enhancements could include integrating AI-based recommendations for 
personalized booking experiences, implementing a mobile application for customer convenience.</li>
          </ul>
        </div>

        <div class="internships box">
          <h3>Internships</h3>
          <ul>
            <li>Cognifyz Technology - Data Analyst Intern</li>
            <li> Oasis Infobyte - Data Science Intern</li>
          </ul>
        </div>
      </div>

      <div class="socials">
        <h3>Connect with Me</h3>
        <a href="https://www.linkedin.com/in/akshaya-kumar-rautaray-7a0584288?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank" aria-label="LinkedIn"><i class="ri-linkedin-box-fill"></i></a>
        <a href="https://github.com/royakshayakumar45" target="_blank" aria-label="GitHub"><i class="ri-github-fill"></i></a>
        <a href="https://x.com/royakshay_45?t=AezXd9aaXLwbPpIrSkvN-A&s=09" target="_blank" aria-label="X (Twitter)"><i class="ri-twitter-x-fill"></i></a>
        <a href="mailto:rautarayakshay09@gmail.com" aria-label="Email"><i class="ri-mail-line"></i></a>
      </div>

      <section class="contact-form box stylish-contact">
        <h3>Contact Me</h3>
        <form>
          <input type="text" placeholder="Name" required />
          <input type="email" placeholder="Email" required />
          <input type="tel" placeholder="Phone Number" required />
          <textarea placeholder="Message" required></textarea>
          <button type="submit">Send</button>
        </form>
      </section>
    </div>

    <a href="#top" class="scroll-icon scroll-up" aria-label="Scroll Up">
      <i class="ri-arrow-up-s-line"></i>
    </a>

    <div class="background-3d bg2"></div>
  </section>

  <script>
    window.onload = () => {
      document.getElementById('preloader').style.display = 'none';
    };
  </script>
</body>
</html>


/* Basic resets */
* {
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body, html {
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: #0d1117;
  color: #c9d1d9;
  overflow-x: hidden;
  animation: fadeIn 1s ease-in;
}

#preloader {
  position: fixed;
  top: 0; left: 0;
  width: 100vw; height: 100vh;
  background: #0d1117;
  z-index: 9999;
}

/* Page containers */
.page {
  position: relative;
  min-height: 100vh;
  padding: 2rem 3rem;
  display: flex;
  flex-direction: column;
  z-index: 10;
  overflow: hidden;
}

/* Header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 2rem;
  z-index: 10;
}

.portfolio-title {
  font-size: 1.5rem;
  font-weight: 600;
  color: #58a6ff;
}

.top-right-info span {
  margin-left: 1.5rem;
  font-size: 0.9rem;
  display: inline-flex;
  align-items: center;
  color: #8b949e;
}

.top-right-info i {
  margin-right: 6px;
  color: #58a6ff;
}

/* Intro Section - Page 1 */
.intro-section {
  max-width: 600px;
  z-index: 10;
}

.intro-section h1 {
  font-size: 3rem;
  margin: 0 0 0.25rem 0;
}

.animated-name {
  color: #58a6ff;
  display: inline-block;
  animation: slideInLeft 1s ease forwards;
}

.intro-section h2 {
  font-size: 1.8rem;
  margin: 0 0 1.5rem 0;
  color: #79c0ff;
  animation: slideInRight 1s ease forwards;
}

.about.box {
  background: rgba(21, 32, 43, 0.85);
  padding: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 0 15px #58a6ffaa;
  margin-bottom: 1.5rem;
}

.about h3 {
  margin-top: 0;
  color: #58a6ff;
}

.resume-download {
  display: inline-flex;
  align-items: center;
  color: #58a6ff;
  font-weight: 600;
  text-decoration: none;
  background: transparent;
  border: 2px solid #58a6ff;
  padding: 0.6rem 1.2rem;
  border-radius: 8px;
  cursor: pointer;
  transition: background-color 0.3s ease;
  margin-bottom: 3rem;
  z-index: 10;
}

.resume-download i {
  margin-right: 8px;
  font-size: 1.2rem;
}

.resume-download:hover {
  background-color: #58a6ff;
  color: #0d1117;
}

/* Scroll icons */
.scroll-icon {
  font-size: 3rem;
  color: #58a6ff;
  cursor: pointer;
  user-select: none;
  display: inline-block;
  transition: color 0.3s ease;
  text-decoration: none;
  z-index: 10;
}

.scroll-icon:hover {
  color: #1f6feb;
  transform: scale(1.1);
  transition: transform 0.3s ease;
}

/* Page 2 content wrapper and vertical stacking */
.content-wrapper {
  z-index: 10;
  max-width: 900px;
  margin: 0 auto;
  padding-bottom: 4rem;
}

.content-boxes-vertical {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  margin-bottom: 3rem;
}

.box {
  background: rgba(21, 32, 43, 0.85);
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 0 20px #58a6ff88;
}

.box h3 {
  margin-top: 0;
  color: #58a6ff;
}

.projects ul, .internships ul {
  list-style: disc inside;
  margin: 0.5rem 0 0 0;
  padding: 0;
}

.projects li, .internships li {
  margin-bottom: 0.5rem;
}

/* Social media icons */
.socials {
  text-align: center;
  margin-bottom: 3rem;
  color: #58a6ff;
}

.socials h3 {
  margin-bottom: 1rem;
}

.socials a {
  color: #58a6ff;
  font-size: 2.2rem;
  margin: 0 0.8rem;
  transition: color 0.3s ease;
}

.socials a:hover {
  color: #1f6feb;
}

/* Stylish Contact Form */
.stylish-contact form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.stylish-contact input,
.stylish-contact textarea {
  background: #161b22;
  border: 1.5px solid #58a6ff;
  border-radius: 8px;
  padding: 0.8rem 1rem;
  color: #c9d1d9;
  font-size: 1rem;
  transition: border-color 0.3s ease;
}

.stylish-contact input:focus,
.stylish-contact textarea:focus {
  outline: none;
  border-color: #1f6feb;
  box-shadow: 0 0 8px #1f6febaa;
}

.stylish-contact textarea {
  resize: vertical;
  min-height: 100px;
}

.stylish-contact button {
  background: #58a6ff;
  color: #0d1117;
  font-weight: 700;
  border: none;
  padding: 0.8rem 1.5rem;
  border-radius: 10px;
  cursor: pointer;
  font-size: 1.1rem;
  transition: background-color 0.3s ease;
}

.stylish-contact button:hover {
  background-color: #1f6feb;
}

/* 3D black background styles */
.background-3d {
  position: fixed;
  top: 0; left: 0;
  width: 100vw;
  height: 100vh;
  pointer-events: none;
  z-index: 0;
  opacity: 0.5;
  filter: drop-shadow(0 0 10px #58a6ffaa);
  animation: backgroundPulse 10s ease-in-out infinite alternate;
  transform-style: preserve-3d;
  border-radius: 0 0 30% 30% / 0 0 10% 10%;
}

.bg1 {
  background: linear-gradient(135deg, #000000, #0a0a0a, #101010);
  clip-path: polygon(0 0, 100% 0, 100% 80%, 0 100%);
  animation-delay: 0s;
}

.bg2 {
  background: linear-gradient(45deg, #000000, #121212, #202020);
  clip-path: polygon(0 0, 100% 0, 100% 100%, 0 85%);
  animation-delay: 5s;
}

@keyframes backgroundPulse {
  0% { filter: drop-shadow(0 0 10px #58a6ffcc) drop-shadow(0 0 30px #58a6ffdd); }
  100% { filter: drop-shadow(0 0 30px #58a6ffee) drop-shadow(0 0 50px #58a6ffff); }
}

/* Animations for name & role */
@keyframes slideInLeft {
  0% { opacity: 0; transform: translateX(-100%); }
  100% { opacity: 1; transform: translateX(0); }
}

@keyframes slideInRight {
  0% { opacity: 0; transform: translateX(100%); }
  100% { opacity: 1; transform: translateX(0); }
}

/* Fade in on load */
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

/* Responsive */
@media (max-width: 768px) {
  header {
    flex-direction: column;
    align-items: flex-start;
  }

  .top-right-info {
    margin-top: 1rem;
    font-size: 0.85rem;
  }

  .intro-section {
    max-width: 100%;
  }

  .content-wrapper {
    padding: 1rem;
  }

  .socials a {
    font-size: 1.8rem;
    margin: 0 0.5rem;
  }
}
