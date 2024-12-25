<?php
/**
 * Template Name: Hamid Personal Profile
 */
get_header();
?>

<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f9f9f9;
        color: #333;
    }
    header {
        background-color: #4CAF50;
        color: white;
        text-align: center;
        padding: 30px 0;
    }
    header h1 {
        margin: 0;
        font-size: 2.5em;
    }
    header p {
        margin: 10px 0 0;
        font-size: 1.2em;
    }
    nav {
        text-align: center;
        background-color: #333;
        padding: 10px 0;
    }
    nav a {
        color: white;
        text-decoration: none;
        margin: 0 15px;
        font-size: 18px;
    }
    nav a:hover {
        text-decoration: underline;
    }
    .container {
        max-width: 1200px;
        margin: 20px auto;
        padding: 20px;
    }
    .section {
        margin-bottom: 40px;
    }
    .section h2 {
        font-size: 2em;
        margin-bottom: 10px;
    }
    .section p {
        font-size: 1.1em;
        line-height: 1.6;
    }
    .profile-photo {
        text-align: center;
        margin-bottom: 20px;
    }
    .profile-photo img {
        width: 150px;
        height: 150px;
        border-radius: 50%;
        border: 3px solid #4CAF50;
    }
    footer {
        text-align: center;
        background-color: #333;
        color: white;
        padding: 20px;
        margin-top: 40px;
    }
    footer a {
        color: #4CAF50;
        text-decoration: none;
    }
</style>

<header>
    <h1>Hamid's Personal Profile</h1>
    <p>Welcome to my personal space where you can learn more about me and my work.</p>
</header>

<nav>
    <a href="#about">About Me</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="about" class="section">
        <h2>About Me</h2>
        <div class="profile-photo">
            <img src="<?php echo get_template_directory_uri(); ?>/images/profile-photo.jpg" alt="Hamid's Photo">
        </div>
        <p>Hi, I am Hamid, a researcher and engineer specializing in data-driven approaches for signal processing, uncertainty quantification, and machine learning. With a background in mechanical engineering and experience in academic and industrial projects, I am passionate about solving complex problems in mechanical systems, manufacturing, and aerospace applications.</p>
    </section>

    <section id="skills" class="section">
        <h2>Skills</h2>
        <ul>
            <li>Machine Learning and Data Analysis</li>
            <li>Signal Processing and Stochastic Modeling</li>
            <li>Uncertainty Quantification and Bayesian Methods</li>
            <li>Programming: Python, MATLAB, SQL</li>
            <li>Cloud Platforms: Microsoft Azure</li>
        </ul>
    </section>

    <section id="projects" class="section">
        <h2>Projects</h2>
        <div class="project">
            <h3>1. Robust Signal Decomposition</h3>
            <p>Developed novel Sparse NMF methods based on Maximum Correntropy Criterion to separate signal components effectively in noisy environments.</p>
        </div>
        <div class="project">
            <h3>2. Fleet Monitoring Framework</h3>
            <p>Designed strategies for monitoring multiple engines under noisy conditions using advanced machine learning and Bayesian approaches.</p>
        </div>
        <div class="project">
            <h3>3. Manufacturing Process Monitoring</h3>
            <p>Utilized sensing technologies and machine learning to optimize monitoring and control of manufacturing systems.</p>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact</h2>
        <p>If you’d like to collaborate or learn more about my work, feel free to reach out:</p>
        <ul>
            <li>Email: <a href="mailto:hamid@example.com">hamid@example.com</a></li>
            <li>GitHub: <a href="https://github.com/hamid" target="_blank">github.com/hamid</a></li>
            <li>LinkedIn: <a href="https://www.linkedin.com/in/hamid" target="_blank">linkedin.com/in/hamid</a></li>
        </ul>
    </section>
</div>

<footer>
    <p>&copy; 2024 Hamid. All rights reserved. Built with passion and dedication.</p>
</footer>

<?php get_footer(); ?>
