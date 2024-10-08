<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <title>Aman Chand's Portfolio</title>
  <link rel="stylesheet" href="style.css"> <!-- Link to CSS file -->
</head>

<body>

<header>
  <h2>Aman.</h2>
  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Portfolio</a>
    <a href="#">Contact</a>
    <a href="#"><strong>Let's Talk</strong></a>
  </nav>
</header>

<section class="intro">
  <h1>Hi, I'm Aman Chand</h1>
  <h3>Web Designer (Currently Learning)</h3>
  <p>I’m Aman, a 17-year-old aspiring web developer from Nepal. Currently learning HTML, I practice by cloning popular websites to sharpen my skills. I aim to create engaging web content that meets local digital needs and trends. I'm excited to share my journey and projects as I grow in this field.</p>
  
  <!-- Add your picture here -->
  <div class="profile-image">
    <img src="IMG_20241008_085901.png" alt="Aman Chand" width="200"> <!-- Change the width if needed -->
  </div>

  <main>
    <a href="#"><strong>Hire Me!!</strong></a>
    <a href="#">See Projects</a>
  </main>
</section>

<footer>
  <a href="https://facebook.com" target="_blank">
    <img src="facebook.png" alt="Facebook" width="20">
  </a>
  <a href="https://gmail.com" target="_blank">
    <img src="gmail.png" alt="Gmail" width="20">
  </a>
  <a href="https://twitter.com" target="_blank">
    <img src="twitter.png" alt="Twitter" width="20">
  </a>
</footer>

</body>
</html>
/* General styling for body and text */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
  color: #333;
}

/* Background Gradient for the introduction section */
.intro {
  background: linear-gradient(120deg, #ffffff 50%, #f3f0ff 50%);
  padding: 50px;
  text-align: center;
  color: #333;
}

header {
  background-color: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 50px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

header h2 {
  color: #6c43fc;
  font-size: 24px;
}

header nav a {
  margin-left: 30px;
  text-decoration: none;
  font-size: 18px;
  color: #333;
}

header nav a:hover {
  color: #6c43fc;
}

header nav a strong {
  background-color: #6c43fc;
  color: white;
  padding: 10px 20px;
  border-radius: 5px;
}

header nav a strong:hover {
  background-color: #4a2fc4;
}

.intro h1 {
  font-size: 48px;
  color: #6c43fc;
  margin-bottom: 20px;
}

.intro h3 {
  font-size: 24px;
  color: #333;
  margin-bottom: 30px;
}

.intro p {
  font-size: 18px;
  line-height: 1.8;
  color: #666;
  max-width: 800px;
  margin: 0 auto 40px;
}

main a {
  text-decoration: none;
  background-color: #6c43fc;
  color: white;
  padding: 15px 30px;
  border-radius: 5px;
  font-size: 20px;
  margin: 10px;
  display: inline-block;
}

main a:hover {
  background-color: #4a2fc4;
}

/* Footer styling */
footer {
  background-color: #fff;
  padding: 20px;
  text-align: center;
}

footer a img {
  margin-right: 20px;
  vertical-align: middle;
}

footer a img:hover {
  opacity: 0.8;
}
.profile-image {
    margin: 20px auto;
    text-align: center;
}

.profile-image img {
    border-radius: %; /* Makes the image circular */
    border: 1px solid #6c43fc; /* Purple border around the image */
}
