<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Professional CV</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>

    <div class="container">
        <!-- Header Section -->
        <header>
            <h1>Kimsang Silalahi</h1>
            <p class="job-title">Junior Frontend Developer</p>
            <address>
                Berdikari 44<br>
                Medan City, The Githam Places<br>
                (+62) 81263999625<br>
                <a href="kimsilalahi0@.com">kimsilalahi0@gmail.com</a>
            </address>
        </header>

        <!-- Skills Section -->
        <section>
            <h2>Skills</h2>
            <p>HTML, CSS, JavaScript, Accessibility, Figma to Design, Responsive Web Design, Technical Writing, Presentation</p>
        </section>

        <!-- Education Section -->
        <section>
            <h2>Education</h2>
            <p><strong>University of Sumatera Utara, Medan, Sumatera Utara - Ilmu Komputer</strong></p>
            <p>August 2021 to Oktober 2024</p>
            <ul>
                <li>Nyentuh Mythic Immortal di Mobile Legend</li>
            </ul>
        </section>

        <!-- Experience Section -->
        <section>
            <h2>Experience</h2>
            <p><strong>IT Consultant Kim, Medan - Full Stack Web Developer</strong></p>
            <p>August 2021 to Oktober 2024</p>
            <ul>
                <li>Ranking 1 BYON COMBAT 2024</li>
                <li>JUARA 1 M5 Mobile Legends</li>
                <li>The Best of Scopus Journal in the world</li>
            </ul>
            <p><strong>Skills:</strong> List of skills used or gained at this company</p>

            <p><strong>Company Name, Location - Job Title</strong></p>
            <p>Month 20xx to Month 20xx</p>
            <ul>
                <li>Back End Developer</li>
                <li>Front End Developer</li>
                <li>Artificial Intelligence </li>
            </ul>
            <p><strong>Skills:</strong> List of skills used or gained at this company</p>
        </section>

        <!-- Internet Links Section -->
        <section>
            <h2>Across the Internet</h2>
            <p>www.linkedin.com/in/kimsang-silalahi-3a8b13308, https://github.com/KimiSilalahi766</p>
        </section>
    </div>

</body>
</html>

/* Reset and basic styling */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    background-color: #f4f4f9;
    color: #333;
    line-height: 1.6;
    display: flex;
    justify-content: center;
    padding: 20px;
}

.container {
    max-width: 700px;
    padding: 20px;
    background-color: #fff;
    border: 1px solid #ddd;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

/* Header styles */
header {
    text-align: left;
    margin-bottom: 20px;
}

header h1 {
    font-size: 2em;
    margin-bottom: 5px;
    color: #333;
}

.job-title {
    font-size: 1.2em;
    color: #32CD32; /* green for job title */
}

address {
    font-style: normal;
    color: #555;
    margin-top: 10px;
}

a {
    color: #555;
    text-decoration: none;
}

/* Section styles */
h2 {
    font-size: 1.5em;
    color: #444;
    border-bottom: 1px solid #ddd;
    padding-bottom: 5px;
    margin-top: 20px;
    margin-bottom: 10px;
}

section p,
section ul {
    margin-top: 5px;
    margin-left: 15px;
    color: #333;
}

ul {
    list-style: disc;
    padding-left: 20px;
}

/* Skills and education styles */
section p strong {
    color: #0073e6; /* blue for headings */
}

/* Footer links styling */
footer p {
    margin-top: 20px;
    font-size: 0.9em;
    color: #777;
}

footer a {
    color: #333;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}
