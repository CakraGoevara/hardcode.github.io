<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>ALI CAKRA GOEVARA</title>
	<style>
		body{
			font-family: Arial, sans-serif;
			margin: 0;
			padding: 0;
		}

		header {
			background-color: #142196;
			color: white;
			padding: 10px 0;
			text-align: center;
		}

		nav {
			display: flex;
			justify-content: center;
			background-color: #161a17;
		}

		nav a {
			color: white;
			padding: 10px 20px;
			text-decoration: none;
			text-align: center;
		}

		nav a:hover {
			background-color: #ddd;
			color: black;
		}

		.container {
			padding: 20px;
		}

		footer {
			text-align: center;
			padding: 10px 0;
			background-color: #4c82af;
			color: white;
			position: relative;
			bottom: 0;
			width: 100%;
		}

		@media (max-width: 600px;){
			nav {
				flex-direction: column;
			}
		}
			
		.skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 30px 0;
        }

        .skill-card {
            background-color: rgb(0, 0, 0);
            border-radius: 10px;
            padding: 20px;
            margin: 10px;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .skill-card:hover {
            transform: scale(1.05);
        }

        .skill-card h3 {
            font-size: 1.5rem;
            color: #0077b6;
            margin-bottom: 10px;
        }

        .skill-card p {
            font-size: 1rem;
            color: #ffffff;
        }
		
	</style>
</head>
<body>
	<header>
		<h1>WELCOME TO MY WEBSITE</h1>
	</header>
	<nav class="nav-container">
		<a href="#home">Home</a>
		<a href="#about">About</a>
		<a href="contact.html">Contact</a>
	</nav>
	<div class="container">
		<h2>Selamat Datang</h2>
		<p>Ali Cakra Goevara</p>
	</div>

	<section id="about"  class="skills">
		<h3>ABOUT</h3>
		<div class="skill-card">
			<h3>Web Development</h3>
			<p>Saya memiliki keahlian dalam HTML, CSS, JavaScript, dan framework seperti React dan Vue.js.</p>
		</div>
		<div class="skill-card">
			<h3>UI/UX Design</h3>
			<p>Saya merancang antarmuka yang intuitif dan mudah digunakan dengan fokus pada pengalaman pengguna yang positif.</p>
		</div>
		<div class="skill-card">
			<h3>Problem Solving</h3>
			<p>Saya ahli dalam menganalisis masalah kompleks dan menemukan solusi kreatif menggunakan teknologi terbaru.</p>
		</div>
		<div class="skill-card">
			<h3>Cyber Security</h3>
			<p>Saya ahli dalam mengamankan akun dan data data seseorang melalui aplikasi yang saya telah buat.</p>
		</div>
	</section>

	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	
	<footer>
		<p>&copy; Ali Cakra Goevara</p>
	</footer>
</body>
</html>
