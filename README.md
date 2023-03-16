<!DOCTYPE html>
<html>
<head>
	<title>My GitHub Profile</title>
	<style>
		body {
			font-family: Arial, sans-serif;
			background-color: #f2f2f2;
			color: #333;
		}
		.container {
			max-width: 800px;
			margin: 0 auto;
			padding: 40px;
			background-color: #fff;
			box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
			border-radius: 5px;
			display: flex;
			flex-wrap: wrap;
			align-items: center;
		}
		.profile-image {
			flex-basis: 200px;
			margin-right: 40px;
			margin-bottom: 40px;
		}
		.profile-image img {
			width: 100%;
			height: auto;
			border-radius: 50%;
			border: 5px solid #fff;
			box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
		}
		.profile-info {
			flex-basis: calc(100% - 240px);
			margin-bottom: 40px;
		}
		.profile-info h1 {
			font-size: 32px;
			margin: 0 0 20px;
		}
		.profile-info p {
			font-size: 18px;
			margin: 0;
			line-height: 1.5;
		}
		.profile-info a {
			color: #333;
			text-decoration: none;
			font-weight: bold;
			margin-right: 20px;
		}
		.profile-info a:hover {
			text-decoration: underline;
		}
		.skill-badge {
			display: inline-block;
			background-color: #007bff;
			color: #fff;
			padding: 5px 10px;
			border-radius: 20px;
			margin-right: 10px;
			margin-bottom: 10px;
			font-size: 14px;
			font-weight: bold;
			transition: all 0.2s ease-in-out;
		}
		.skill-badge:hover {
			background-color: #0056b3;
			transform: scale(1.05);
		}
	</style>
</head>
 <body>
    <div class="container">
      <h1>My GitHub Profile</h1>
      <p>Hi there, I'm John Doe, a full-stack developer with a passion for building great websites and applications.</p>
      <ul>
        <li>👨‍💻 I'm currently working on a React project</li>
        <li>📚 I'm learning GraphQL</li>
        <li>🌱 I'm interested in machine learning and artificial intelligence</li>
        <li>📫 How to reach me: <a href="mailto:john.doe@example.com">john.doe@example.com</a></li>
        <li>💼 My LinkedIn profile: <a href="https://www.linkedin.com/in/john-doe/">https://www.linkedin.com/in/john-doe/</a></li>
      </ul>
    </div>
    <div class="profile-image">
			<img src="your-profile-image.jpg" alt="Your Name">
		</div>
		<div class="profile-info">
			<h1>Your Name</h1>
			<p>Hi there! I'm a passionate software developer with experience in web development and data analysis. I'm currently studying computer science and constantly learning new skills.</p>
			<p>Connect with me:</p>
			<a href="https://www.linkedin.com/in/your-linkedin-profile" target="_blank">LinkedIn</a>
			<a href="https://twitter.com/your-twitter-handle" target="_blank">Twitter</a>
			<a href="https://your-personal-website.com" target="_blank">Website</a>
			<br><br>
			<p>My skills:</p>
			<span class="skill-badge">HTML</span>
			<span class="skill-badge">CSS</span>
			<span class="skill-badge">JavaScript</span>
			<span class="skill-badge">React</span>
		</div>	
  </body>
</html>
