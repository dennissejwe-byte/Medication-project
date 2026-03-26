# Index.html  
  
<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>Medication Adherence Awareness</title>  
  
<style>  
body {  
  font-family: Arial, sans-serif;  
  margin: 0;  
  background: #0f172a;  
  color: #fff;  
}  
  
/* NAVIGATION */  
nav {  
  background: #1e293b;  
  padding: 15px;  
  text-align: center;  
}  
nav a {  
  color: #22c55e;  
  margin: 0 15px;  
  text-decoration: none;  
  font-weight: bold;  
}  
  
/* SECTIONS */  
section {  
  padding: 50px 20px;  
  text-align: center;  
}  
  
/* HERO */  
.hero {  
  background: linear-gradient(to right, #22c55e, #4ade80);  
  color: black;  
}  
  
/* BUTTON */  
button {  
  padding: 12px 20px;  
  border: none;  
  background: black;  
  color: white;  
  border-radius: 8px;  
  cursor: pointer;  
}  
  
/* CARDS */  
.card {  
  background: #1e293b;  
  margin: 15px;  
  padding: 20px;  
  border-radius: 10px;  
  display: inline-block;  
  width: 250px;  
}  
  
/* FOOTER */  
footer {  
  background: #020617;  
  padding: 20px;  
  text-align: center;  
}  
</style>  
</head>  
  
<body>  
  
<!-- NAV -->  
<nav>  
  <a href="#home">Home</a>  
  <a href="#about">About</a>  
  <a href="#importance">Why It Matters</a>  
  <a href="#tips">Tips</a>  
  <a href="#contact">Contact</a>  
</nav>  
  
<!-- HERO -->  
<section id="home" class="hero">  
  <h1>Medication Adherence</h1>  
  <p>Helping Patients Take Their Medication Correctly</p>  
  <button onclick="alert('Stay consistent with your medication!')">Learn More</button>  
</section>  
  
<!-- ABOUT -->  
<section id="about">  
  <h2>What is Medication Adherence?</h2>  
  <p>  
    Medication adherence refers to how well a patient follows their prescribed  
    treatment plan, including taking medication at the correct time, dose, and frequency.  
  </p>  
</section>  
  
<!-- IMPORTANCE -->  
<section id="importance">  
  <h2>Why is it Important?</h2>  
  
  <div class="card">  
    <h3>Prevents Complications</h3>  
    <p>Missing medication can worsen diseases like diabetes or hypertension.</p>  
  </div>  
  
  <div class="card">  
    <h3>Improves Recovery</h3>  
    <p>Following treatment properly leads to faster healing.</p>  
  </div>  
  
  <div class="card">  
    <h3>Reduces Hospital Visits</h3>  
    <p>Proper adherence lowers emergency admissions.</p>  
  </div>  
  
</section>  
  
<!-- TIPS -->  
<section id="tips">  
  <h2>How to Improve Medication Adherence</h2>  
  
  <div class="card">  
    <h3>Set Reminders</h3>  
    <p>Use phone alarms or apps to remember doses.</p>  
  </div>  
  
  <div class="card">  
    <h3>Use Pill Boxes</h3>  
    <p>Organize medication for each day of the week.</p>  
  </div>  
  
  <div class="card">  
    <h3>Understand Your Medication</h3>  
    <p>Know why you are taking it and its benefits.</p>  
  </div>  
  
  <div class="card">  
    <h3>Support System</h3>  
    <p>Family or nurses can help monitor adherence.</p>  
  </div>  
  
</section>  
  
<!-- CONTACT -->  
<section id="contact">  
  <h2>Contact / Feedback</h2>  
  <p>Have questions? Reach out below:</p>  
  
  <form>  
    <input type="text" placeholder="Your Name" required><br><br>  
    <input type="email" placeholder="Your Email" required><br><br>  
    <textarea placeholder="Your Message"></textarea><br><br>  
    <button type="submit">Send</button>  
  </form>  
</section>  
  
<!-- FOOTER -->  
<footer>  
  <p>&copy; 2026 Medication Awareness Project</p>  
  <p>Sources: WHO, CDC, Nursing Textbooks</p>  
</footer>  
  
</body>  
</html>  
