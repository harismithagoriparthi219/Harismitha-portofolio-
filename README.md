<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Harismitha Devi | Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- HERO -->
<header class="hero fade-in">
  <h1>Goriparthi Harismitha Devi</h1>
  <p>Electronics & Communication Engineering Student</p>
  <p class="sub">Web Development | IoT | Embedded Systems</p>

  <div class="buttons">
    <a href="https://github.com/YOUR_GITHUB_USERNAME" target="_blank">GitHub</a>
    <a href="https://www.linkedin.com/in/YOUR_LINKEDIN_USERNAME" target="_blank">LinkedIn</a>
  </div>
</header>

<!-- ABOUT -->
<section class="fade-in">
  <h2>About Me</h2>
  <p>
    I am <strong>Goriparthi Harismitha Devi</strong>, an Electronics and Communication
    Engineering undergraduate at <strong>Vel Tech University</strong>, with a strong
    academic foundation and hands-on technical exposure.
  </p>
  <p>
    I completed a Diploma in Electronics & Communication Engineering with a
    <strong>CGPA of 9.3</strong> and secured <strong>9.7 CGPA in Class X</strong>.
    I also completed a <strong>2-month internship at South Central Railway (WWO) in 2025</strong>,
    gaining exposure to railway signaling and telecommunication systems.
  </p>
  <p>
    My interests include web development, IoT, embedded systems, and electronics
    circuit design. I am passionate about applying theory to real-world problems
    and continuously enhancing my skills.
  </p>
</section>

<!-- EDUCATION -->
<section class="fade-in">
  <h2>Education</h2>

  <div class="card">
    <h3>B.Tech – Electronics & Communication Engineering</h3>
    <p>Vel Tech University, Tamil Nadu</p>
    <span>2023 – 2027 | YOP: 2027</span>
  </div>

  <div class="card">
    <h3>Diploma – Electronics & Communication Engineering</h3>
    <p>AANM & VVRSR Polytechnic, Gudlavalleru</p>
    <span>CGPA: 9.3</span>
  </div>

  <div class="card">
    <h3>Class X (SSC)</h3>
    <p>ZP High School, Ventrapragada</p>
    <span>CGPA: 9.7</span>
  </div>
</section>

<!-- EXPERIENCE -->
<section class="fade-in">
  <h2>Experience</h2>
  <div class="card">
    <h3>Intern – South Central Railway (WWO)</h3>
    <span>2025 | Duration: 2 Months</span>
    <ul>
      <li>Observed railway signaling and telecommunication systems</li>
      <li>Worked with relays, batteries, and control equipment</li>
      <li>Understood railway safety and operations</li>
    </ul>
  </div>
</section>

<!-- PROJECTS -->
<section class="fade-in">
  <h2>Projects</h2>
  <div class="card">
    <h3>Arduino-Based Home Automation System</h3>
    <p><strong>Technologies:</strong> Arduino, Relays, Sensors, Embedded C, IoT</p>
    <ul>
      <li>Developed a home automation system to control appliances</li>
      <li>Used relay modules for ON/OFF switching</li>
      <li>Integrated sensors for automation and safety</li>
      <li>Hands-on experience with microcontrollers</li>
    </ul>
  </div>
</section>

<!-- SKILLS -->
<section class="fade-in">
  <h2>Skills</h2>
  <div class="skills">
    <span>HTML</span>
    <span>CSS</span>
    <span>JavaScript</span>
    <span>IoT</span>
    <span>Embedded Systems</span>
    <span>Electronics Circuits</span>
    <span>GitHub</span>
  </div>
</section>

<!-- CONTACT -->
<section class="fade-in">
  <h2>Contact</h2>
  <p>Email: <strong>harismithagoriparthi219@gmail.com</strong></p>
  <p>Phone: <strong>9652553426</strong></p>
  <p>Location: Andhra Pradesh, India</p>
</section>

<footer>
  <p>© 2025 Harismitha Devi | Portfolio</p>
</footer>

<script>
  const faders = document.querySelectorAll('.fade-in');
  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, { threshold: 0.2 });

  faders.forEach(fade => observer.observe(fade));
</script>

</
.card:hover {
  transform: translateY(-8px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.15);
}

.skills span {
  display: inline-block;
  background: #2563eb;
  color: white;
  padding: 6px 12px;
  border-radius: 20px;
  margin: 5px;
  font-size: 14px;
  transition: transform 0.3s ease;
}

.skills span:hover {
  transform: scale(1.⁷1
