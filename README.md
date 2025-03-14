<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Subh12m's Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <img src="./profile.jpg" alt="Your Profile Image" class="profile-img">
            <h1>Welcome to my Portfolio</h1>
            <p>I'm a passionate developer and open-source enthusiast.</p>
        </div>
    </header>
    <section class="about">
        <div class="container">
            <img src="./subham.jpg" alt="Subh12m Profile Image" class="about-img">
            <div class="bio">
                <h2>About Me</h2>
                <p>Hi, I'm Subh12m. I specialize in building web applications and have a keen interest in machine learning and AI. Feel free to check out my projects below!</p>
            </div>
        </div>
    </section>
    <section class="projects">
        <div class="container">
            <h2>My Projects</h2>
            <ul>
                <li>
                    <h3>Project 1</h3>
                    <p>Brief description of project 1.</p>
                    <a href="https://github.com/Subh12m/portfolio02" target="_blank">Check it out on GitHub</a>
                </li>
                <li>
                    <h3>Project 2</h3>
                    <p>Brief description of project 2.</p>
                    <a href="https://github.com/Subh12m/Subh12m" target="_blank">Check it out on GitHub</a>
                </li>
                <!-- Add more projects as needed -->
            </ul>
        </div>
    </section>
    <footer>
        <div class="container">
            <p>Connect with me: <a href="https://github.com/Subh12m" target="_blank">GitHub</a> | <a href="mailto:subh12m@example.com">Email</a></p>
        </div>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background: #f4f4f4;
}

.container {
    width: 80%;
    margin: 0 auto;
    padding: 20px;
}

header {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header .profile-img {
    width: 100px;
    height: 100px;
    object-fit: cover;
    border-radius: 50%;
    margin: 20px auto;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

header p {
    font-size: 1.2em;
    margin-bottom: 20px;
}

.about {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 50px 0;
}

.about .about-img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 50%;
    margin-right: 20px;
}

.bio {
    max-width: 500px;
    margin-left: 20px;
    padding: 20px;
}

.bio > h2 {
    font-size: 2em;
    margin-top: 0;
}

.bio > p {
    font-size: 1.1em;
    margin-bottom: 20px;
}

.projects {
    background: #fff;
    padding: 50px 0;
    text-align: center;
}

.projects h2 {
    font-size: 2.5em;
    margin-bottom: 30px;
}

.projects ul {
    list-style-type: none;
    padding: 0;
}

.projects li {
    margin: 20px 0;
    padding: 20px;
    background: #f4f4f4;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.projects li h3 {
    margin: 0 0 10px 0;
    font-size: 1.8em;
}

.projects li p {
    margin-bottom: 20px;
}

.projects li a {
    color: #333;
    text-decoration: none;
    font-weight: bold;
}

footer {
    background: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
    clear: both;
}

footer a {
    color: #fff;
    text-decoration: none;
}


