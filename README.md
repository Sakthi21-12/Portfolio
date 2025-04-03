# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        /* Global Styles */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #ff66cc, #ff6600);
            color: #ffffff;
            transition: background-color 0.5s ease;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #ff0080, #4caf50);
            color: #ffffff;
            text-align: center;
            padding: 5rem 0;
            position: relative;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            border-bottom: 5px solid #ffcc00;
        }

        header h1 {
            font-size: 3.8rem;
            font-weight: 700;
            margin: 0;
            letter-spacing: 3px;
            text-transform: uppercase;
            color: #ffffff;
        }

        header p {
            font-size: 1.7rem;
            font-weight: 300;
            margin-top: 10px;
        }

        /* Profile Picture */
        .profile-picture {
            width: 250px;
            height: 250px;
            border-radius: 180%;
            object-fit:cover;
 object-position: 80% 10%;
            position: absolute;
            top: 20px;
            left: 50px;
            border: 5px solid #ffcc00;
            box-shadow: 0 6px 25px rgba(0, 0, 0, 0.2);
        }

        /* Navigation */
        nav {
            background-color: #111;
            text-align: center;
            padding: 1.5rem 0;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            transition: 0.3s ease-in-out;
        }

        nav:hover {
            background-color: #222;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            gap: 30px;
        }

        nav ul li {
            display: inline;
        }

        nav ul li a {
            text-decoration: none;
            color: #ffcc00;
            font-size: 1.3rem;
            font-weight: 500;
            letter-spacing: 1px;
            transition: 0.3s ease;
        }

        nav ul li a:hover {
            color: #f39c12;
            transform: scale(1.1);
            text-decoration: underline;
        }

        /* Contact Section */
        .contact {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            background-color: rgba(0, 255, 255, 0.5);
            padding: 2.5rem;
            margin: 30px;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .contact div {
            flex: 1;
            margin: 0 15px;
        }

        .contact a {
            color: #ffcc00;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.2rem;
            transition: 0.3s ease;
        }

        .contact a:hover {
            color: #f39c12;
            transform: scale(1.1);
            text-decoration: underline;
        }

        /* Section Content */
        .section-content {
            background-color: #212121;
            padding: 3.5rem;
            margin: 2rem auto;
            border-radius: 15px;
            box-shadow: 0 0 30px rgba(255, 255, 255, 0.2);
            max-width: 950px;
            transition: 0.3s ease;
        }

        .section-content:hover {
            background-color: #2c2c2c;
            box-shadow: 0 0 40px rgba(255, 255, 255, 0.4);
        }

        .section-content h2 {
            color: #ffcc00;
            font-size: 2.4rem;
            margin-bottom: 15px;
            font-weight: bold;
            letter-spacing: 1.5px;
            text-transform: uppercase;
        }

        /* Table */
        table {
            width: 100%;
            margin-top: 25px;
            border-collapse: collapse;
        }

        table th, table td {
            padding: 12px;
            text-align: left;
            border: 1px solid #444;
        }

        table th {
            background-color: #f39c12;
            color: #ffffff;
        }

        table td {
            background-color: #333;
            color: #ffffff;
        }

        /* Button Styles */
        .download-button {
            background-color: #ffcc00;
            color: #000;
            padding: 1rem 2.2rem;
            text-decoration: none;
            border-radius: 40px;
            display: inline-block;
            font-weight: bold;
            font-size: 1.3rem;
            margin-top: 25px;
            transition: 0.3s ease;
        }

        .download-button:hover {
            background-color: #f39c12;
            color: #fff;
            transform: scale(1.1);
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 1.5rem 0;
            background-color: #111;
            color: #fff;
            box-shadow: 0 -4px 12px rgba(0, 0, 0, 0.2);
        }

    </style>
</head>
<body>

    <header>
        <img src="https://lh3.google.com/u/0/d/1kVzMTekAucYjiNLVjqIfi9fDi1EorTvh=w1925-h923-iv1" alt="Profile Picture" class="profile-picture">
        <div class="header-content">
            <h1>SAKTHIMURUGAN S</h1><br>
            <h3>Bachelor of Computer Applications</h3>
        </div>
    </header>

    <section class="contact">
        <div>
            <h2>Contact Information</h2>
            <p>Email: <a href="mailto:bca23s2023@alphagroup.edu">bca23s2023@alphagroup.edu</a></p>
            <p>Phone: +91 6374537712</p>
 <p>Linkedin:https://www.linkedin.com/in/sakthi-murugan-b12aa132a </p>
 <p>Github: https://github.com/Sakthi21-12</p>
        </div>
        <div>
            <h2>Links</h2>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/sakthi-murugan-b12aa132a" target="_blank">Visit LinkedIn</a></p>
            <p>GitHub: <a href="https://github.com/Sakthi21-12" target="_blank">Visit GitHub</a></p>
        </div>
    </section>

    <nav>
        <ul>
            <li><a href="#CareerObjective">Career Objective</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#certifications">Certifications</a></li>
            <li><a href="#languages">Languages</a></li>
            <li><a href="#resume">Resume</a></li>
        </ul>
    </nav>

    <section id="CareerObjective">
        <div class="section-content">
            <h2>Career Objective</h2>
            <p>To leverage technical expertise and innovative problem-solving skills in a dynamic IT environment. Seeking to contribute to cutting-edge technology projects, enhance organizational efficiency, and continuously develop my skills in areas like software development, system analysis, and cybersecurity. Committed to driving technological advancements while ensuring robust and secure digital solutions.</p>
        </div>
    </section>

    <section id="education">
        <div class="section-content">
            <h2>Education</h2>
            <p><b>Bachelor of Computer Applications</b> (Pursuing, Expected 2026)<br>Alpha Arts and Science College, Porur - University of Madras</p>
            <p><b>Higher Secondary Education</b> (12th Standard, 2022-2023)<br>Government Higher Secondary School - Thanikkotagam - State Board (80.5%)</p>
            <p><b>Higher Secondary Education</b> (10th Standard, 2020-2021)<br>Government Higher Secondary School- Thanikkotagam - State Board (80%)</p>
        </div>
    </section>

    <section id="skills">
        <div class="section-content">
            <h2>Skills</h2>
            <table>
                <tr>
                    <th>Technical Skills</th>
                    <th>Soft Skills</th>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>Microsoft Word, PowerPoint, Excel</li>
                            <li>Basic Programming Languages: Python, Java, HTML, CSS, C++, MYSQL</li>
                            <li>Basic computer Knowledge</li>
                        </ul>
                    </td>
                    <td>
                        <ul>
                            <li>Communication</li>
                            <li>Leadership</li>
                            <li>Teamwork</li>
                            <li>Time Management</li>
                        </ul>
                    </td>
                </tr>
            </table>
        </div>
    </section>

    <section id="certifications">
        <div class="section-content">
            <h2>Certifications</h2>
            <ul>
                <li>CDAC AI Certificate - Centre for Development of Advanced Computing (2024)</li>
                <li>Lingua Skill Cambridge Certificate (B1 Level) - Cambridge Assessment English (2024)</li>
                <li>Object-Oriented Programming using Python (Infosys Springboard, 2024)</li>
                <li>Basics of Python (Infosys Springboard, 2024)</li>
            </ul>
        </div>
    </section>

    <section id="languages">
        <div class="section-content">
            <h2>Languages</h2>
            <ul>
                <li>English</li>
                <li>Tamil</li>
            </ul>
        </div>
    </section>

    <section id="resume">
        <div class="section-content">
            <h2>Resume</h2>
            <a href="https://lh3.google.com/u/0/d/1JNfkBAMQKkzSUe3fQ1GeI4ug4kAOs3py=w1925-h923-iv1" target="_blank" class="download-button">View Resume</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 SAKTHIMURUGAN S</p>
    </footer>

</body>
</html>

