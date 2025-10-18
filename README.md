# Project-01
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nikhil Grewal - Portfolio</title>
<style>
/* Reset and base styles */
* {
margin: 0;
padding: 0;
box-sizing: border-box;
}

body {
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
line-height: 1.6;
color: #333;
background: linear-gradient(135deg, #a1c4fd, #c2e9fb);
min-height: 100vh;
}

.container {
max-width: 1200px;
margin: 0 auto;
padding: 20px;
}

/* Header styles */
header {
text-align: center;
padding: 60px 0;
}

h1 {
font-size: 3rem;
margin-bottom: 10px;
color: #2c3e50;
font-weight: 700;
}

.subtitle {
font-size: 1.2rem;
color: #34495e;
font-weight: 400;
}

/* Card styles */
.card {
background: white;
border-radius: 15px;
box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
padding: 30px;
margin-bottom: 30px;
transition: transform 0.3s ease;
}

.card:hover {
transform: translateY(-5px);
}

/* Section titles */
h2 {
font-size: 2rem;
margin-bottom: 20px;
color: #2c3e50;
position: relative;
padding-bottom: 10px;
}

h2:after {
content: '';
position: absolute;
bottom: 0;
left: 0;
width: 50px;
height: 3px;
background: linear-gradient(to right, #3498db, #2ecc71);
border-radius: 2px;
}

/* About section */
.about p {
font-size: 1.1rem;
line-height: 1.8;
color: #555;
}

/* Skills section */
.skills-container {
display: flex;
flex-wrap: wrap;
gap: 20px;
justify-content: center;
}

.skill-card {
background: linear-gradient(135deg, #3498db, #2980b9);
color: white;
border-radius: 10px;
padding: 20px 30px;
text-align: center;
min-width: 150px;
box-shadow: 0 5px 15px rgba(52, 152, 219, 0.3);
transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.skill-card:hover {
transform: translateY(-5px);
box-shadow: 0 8px 20px rgba(52, 152, 219, 0.4);
}

.skill-card h3 {
font-size: 1.5rem;
margin-bottom: 5px;
}

/* Contact section */
.contact-form {
display: grid;
gap: 20px;
}

.form-group {
display: flex;
flex-direction: column;
}

.form-group label {
margin-bottom: 8px;
font-weight: 500;
color: #2c3e50;
}

.form-group input,
.form-group textarea {
padding: 12px 15px;
border: 1px solid #ddd;
border-radius: 8px;
font-family: inherit;
font-size: 1rem;
transition: border-color 0.3s ease;
}

.form-group input:focus,
.form-group textarea:focus {
outline: none;
border-color: #3498db;
}

.form-group textarea {
resize: vertical;
min-height: 150px;
}

.submit-btn {
background: linear-gradient(135deg, #3498db, #2980b9);
color: white;
border: none;
border-radius: 8px;
padding: 12px 20px;
font-size: 1rem;
font-weight: 500;
cursor: pointer;
transition: transform 0.3s ease, box-shadow 0.3s ease;
justify-self: start;
}

.submit-btn:hover {
transform: translateY(-2px);
box-shadow: 0 5px 15px rgba(52, 152, 219, 0.3);
}

/* Footer */
footer {
text-align: center;
padding: 30px 0;
color: #2c3e50;
font-size: 0.9rem;
}

/* Responsive design */
@media (max-width: 768px) {
h1 {
font-size: 2.5rem;
}

.subtitle {
font-size: 1rem;
}

h2 {
font-size: 1.7rem;
}

.skill-card {
min-width: 120px;
padding: 15px 20px;
}

.skill-card h3 {
font-size: 1.3rem;
}
}

@media (max-width: 480px) {
h1 {
font-size: 2rem;
}

.card {
padding: 20px;
}

.skills-container {
flex-direction: column;
align-items: center;
}

.skill-card {
width: 100%;
max-width: 300px;
}
}
</style>
</head>
<body>
<div class="container">
<header>
<h1>Nikhil Grewal</h1>
<p class="subtitle">Passionate Learner | Exploring Web Development & Programming</p>
</header>

<section class="about card">
<h2>About Me</h2>
<p>I'm a passionate learner with a keen interest in coding and technology. Currently, I'm exploring the fascinating world of web development and programming, focusing on building a strong foundation in HTML, Python, and MySQL. I believe in continuous learning and enjoy solving problems through code. My journey in programming has just begun, and I'm excited to see where this path leads me as I expand my knowledge and skills.</p>
</section>

<section class="skills card">
<h2>Skills</h2>
<div class="skills-container">
<div class="skill-card">
<h3>HTML</h3>
<p>Markup Language</p>
</div>
<div class="skill-card">
<h3>Python</h3>
<p>Programming Language</p>
</div>
<div class="skill-card">
<h3>MySQL</h3>
<p>Database Management</p>
</div>
</div>
</section>

<section class="contact card">
<h2>Contact Me</h2>
<form class="contact-form">
<div class="form-group">
<label for="name">Name</label>
<input type="text" id="name" name="Nikhil Grewal" placeholder="Your Name">
</div>
<div class="form-group">
<label for="email">Email</label>
<input type="email" id="email" name="email" placeholder="nikhilgrewal9229@gmail.com">
</div>
<div class="form-group">
<label for="message">Message</label>
<textarea id="message" name="message" placeholder="Your message here..."></textarea>
</div>
<button type="submit" class="submit-btn">Send Message</button>
</form>
</section>

<footer>
<p>©️ 2025 Nikhil Grewal | Built with 💙 and Curiosity</p>
</footer>
</div>
</body>
</html>
