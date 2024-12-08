# Julius-Prosper
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Julius Prosper Olamide</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600&family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        /* Base styles */
        body {
            font-family: 'Open Sans', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #2c3e50;
            color: #fff;
            line-height: 1.6;
        }
        .container {
            width: 80%;
            max-width: 900px;
            padding: 30px;
            margin: 30px auto;
            background-color: #34495e;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            opacity: 0;
            animation: fadeIn 1.5s forwards;
        }

        /* Title and Heading Styles */
        h1 {
            font-size: 36px;
            text-align: center;
            color: #ecf0f1;
            font-family: 'Montserrat', sans-serif;
        }

        .section-title {
            font-size: 24px;
            font-weight: 600;
            margin-top: 30px;
            color: #2980b9;
        }

        p {
            font-size: 18px;
            color: #ecf0f1;
            line-height: 1.75;
        }

        .info {
            margin-bottom: 20px;
        }

        .footer {
            text-align: center;
            font-size: 14px;
            color: #aaa;
            margin-top: 30px;
        }

        .contact-info {
            font-weight: bold;
            margin-bottom: 20px;
        }

        .skills ul, .experience ul, .volunteer ul, .memberships ul {
            list-style-type: none;
            padding-left: 0;
        }

        .skills li, .experience li, .volunteer li, .memberships li {
            margin-bottom: 10px;
        }

        /* Accent Color and Interactive Elements */
        a {
            text-decoration: none;
            color: #2980b9;
            transition: color 0.3s ease-in-out;
        }

        a:hover {
            color: #ecf0f1;
        }

        /* Button Hover Animation */
        button {
            background-color: #2980b9;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }

        button:hover {
            background-color: #3498db;
            transform: scale(1.05);
        }

        /* Scrolling Effects */
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            animation: fadeInScroll 1s forwards;
        }

        /* Loading animation */
        .loading {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #34495e;
        }

        .loading .spinner {
            border: 4px solid #f3f3f3;
            border-top: 4px solid #2980b9;
            border-radius: 50%;
            width: 50px;
            height: 50px;
            animation: spin 1s linear infinite;
        }

        /* Keyframes for animations */
        @keyframes fadeIn {
            to {
                opacity: 1;
            }
        }

        @keyframes fadeInScroll {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* Responsive Design */
        @media screen and (max-width: 768px) {
            .container {
                width: 95%;
                padding: 15px;
            }
            h1 {
                font-size: 28px;
            }
            .section-title {
                font-size: 20px;
            }
            p {
                font-size: 16px;
            }
        }

    </style>
</head>
<body>
    <div class="loading" id="loading">
        <div class="spinner"></div>
    </div>

    <div class="container" id="content" style="display:none;">
        <h1>Julius Prosper Olamide</h1>

        <div class="contact-info fade-in">
            <p><strong>Phone:</strong> 07057575283, 09014112671</p>
            <p><strong>Email:</strong> <a href="mailto:juliusprosper881@gmail.com">juliusprosper881@gmail.com</a></p>
            <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/julius-prosper-8b0a20312" target="_blank">Julius Prosper LinkedIn</a></p>
        </div>

        <div class="summary fade-in">
            <div class="section-title">Summary</div>
            <p>Highly creative and versatile professional with expertise in front-end development, cinematography, and education. Proven ability to leverage technical skills and creative vision to deliver impactful results, demonstrated through experience in freelance modeling, program management, and corporate website development. Passionate about utilizing technology and visual storytelling to inspire and educate.</p>
        </div>

        <div class="skills fade-in">
            <div class="section-title">Skills</div>
            <ul>
                <li><strong>Front-End Development:</strong> HTML5, CSS3, JavaScript, Responsive Web Design</li>
                <li><strong>Cinematography & Photography:</strong> Cinematography Techniques, Photography Composition, Video Editing (Adobe Premiere Pro, Photoshop)</li>
                <li><strong>Education & Training:</strong> Curriculum Development, Public Speaking, Program Management</li>
                <li><strong>Software/Tools:</strong> (List any other relevant software or tools)</li>
                <li><strong>Languages:</strong> (List any additional languages)</li>
            </ul>
        </div>

        <div class="experience fade-in">
            <div class="section-title">Experience</div>
            <ul>
                <li><strong>Front-End Developer | RCCG in Partnership with Patience Comm. & Airtel SME Operator</strong> | 2023 - 2024</li>
                <ul>
                    <li>Engineered and maintained dynamic user interfaces for corporate websites and applications.</li>
                    <li>Implemented responsive design principles to enhance user engagement and accessibility across devices.</li>
                    <li>Collaborated with cross-functional teams to optimize website performance and user experience.</li>
                </ul>

                <li><strong>Freelance Model | The Saint TS & Prosper Innovation PI</strong> | 2021 - Present</li>
                <ul>
                    <li>Modeled for high-profile fashion, commercial, and editorial projects.</li>
                    <li>Collaborated effectively with photographers and designers to create visually compelling campaigns.</li>
                    <li>Developed a strong personal brand recognized for versatility and creativity in the fashion industry.</li>
                </ul>

                <li><strong>Cinematographer | Capacity Development & Skills Enhancement Initiative (CDSEI)</strong> | 2019 - 2021</li>
                <ul>
                    <li>Completed a Certificate in Cinematography, focusing on camera work, lighting, and editing.</li>
                    <li>Gained practical experience in film and video production.</li>
                </ul>
            </ul>
        </div>

        <div class="education fade-in">
            <div class="section-title">Education</div>
            <ul>
                <li><strong>Bachelor of Education in Mathematics | Prince Abubakar Audu University</strong> | 2021 - 2024</li>
                <ul>
                    <li>Developed a strong foundation in mathematical concepts and educational methodologies.</li>
                    <li>Applied knowledge effectively in diverse teaching environments.</li>
                </ul>
                <li><strong>Harvard University | CS50S: Introduction to Programming with Scratch</strong></li>
            </ul>
        </div>

        <div class="awards fade-in">
            <div class="section-title">Awards and Recognition</div>
            <ul>
                <li>2022 Young Innovator Award</li>
            </ul>
        </div>

        <div class="volunteer fade-in">
            <div class="section-title">Volunteer Experience</div>
            <ul>
                <li>Active Volunteer, The Brain and Body Foundation NGO</li>
                <li>Active Volunteer, Red Cross Society</li>
            </ul>
        </div>

        <div class="memberships fade-in">
            <div class="section-title">Memberships</div>
            <ul>
                <li>Nigerian Society of Cinematographers</li>
                <li>The New Dawn Conference</li>
                <li>Tech Innovation (A Catalyst for Economic Growth in Kogi State)</li>
                <li>Solana AllStars Nigeria Kogi Connect</li>
            </ul>
        </div>

        <div class="footer">
            <button onclick="alert('Thank you for visiting my website!')">Contact Me</button>
            <p>&copy; 2024 Julius Prosper Olamide. All rights reserved.</p>
        </div>
    </div>

    <script>
        // Simulate content loading
        window.addEventListener("load", function () {
            setTimeout(function () {
                document.getElementById("loading").style.display = "none";
                document.getElementById("content").style.display = "block";
            }, 2000); // 2 seconds delay for loading animation
        });
    </script>
</body>
</html>
