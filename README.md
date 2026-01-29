<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arfan Ahmad Faiz - LinkedIn Profile</title>
    <style>
        /* Color Palette Variables */
        :root {
            --black-bg: #000000;
            --light-blue: #0061b1;
            --dark-blue: #2B115A;
            --red: #F11A22;
            --white-text: #ffffff;
            --light-gray-text: #cccccc;
            --medium-gray-text: #999999;
        }

        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Modern Font and Body Styles */
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            background-color: var(--black-bg);
            color: var(--white-text);
            line-height: 1.6;
            /* Good spacing and centering */
            padding: 40px 20px;
            min-height: 100vh;
        }

        /* Center container with good spacing */
        .container {
            max-width: 900px;
            margin: 0 auto;
            /* Center the content */
        }

        /* Navigation Menu Styles */
        .navigation {
            background: rgba(43, 17, 90, 0.9);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(0, 97, 177, 0.3);
            border-radius: 15px;
            padding: 15px 0;
            margin-bottom: 30px;
            position: sticky;
            top: 20px;
            z-index: 100;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
        }

        .nav-content {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 30px;
            flex-wrap: wrap;
        }

        .nav-link {
            color: var(--white-text);
            text-decoration: none;
            font-weight: 600;
            font-size: 0.8rem;
            padding: 8px 16px;
            border-radius: 20px;
            transition: all 0.3s ease;
            background: rgba(0, 97, 177, 0.2);
            border: 1px solid rgba(0, 97, 177, 0.3);
        }

        .nav-link:hover {
            background: var(--light-blue);
            color: var(--white-text);
            transform: translateY(-2px);
            box-shadow: 0 4px 15px rgba(0, 97, 177, 0.4);
        }

        /* Header Styles - Enhanced with more visual impact */
        .header {
            text-align: center;
            padding: 60px 0;
            background: linear-gradient(135deg, var(--dark-blue) 0%, var(--black-bg) 50%, var(--dark-blue) 100%);
            position: relative;
            overflow: hidden;
        }

        .header-content {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
        }

        .profile-picture {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid var(--light-blue);
            box-shadow: 0 8px 25px rgba(0, 97, 177, 0.4);
            object-fit: cover;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .profile-picture:hover {
            transform: scale(1.05);
            box-shadow: 0 12px 35px rgba(0, 97, 177, 0.6);
        }

        .header-text {
            text-align: left;
        }

        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: radial-gradient(circle at 20% 50%, rgba(0, 97, 177, 0.1) 0%, transparent 50%),
                        radial-gradient(circle at 80% 50%, rgba(43, 17, 90, 0.1) 0%, transparent 50%);
            animation: headerGlow 8s ease-in-out infinite alternate;
        }

        @keyframes headerGlow {
            0% { opacity: 0.5; }
            100% { opacity: 1; }
            position: relative;
            z-index: 1;
        }

        .profile-name {
            font-family: 'Times New Roman', Times, serif;
            font-size: 3.2rem;
            font-weight: 800;
            font-style: italic;
            margin-bottom: 20px;
            letter-spacing: -1px;
            text-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
        }

        .profile-headline {
            font-family: 'Pilot', 'Economic', 'Baller', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            font-size: 1.4rem;
            font-weight: 700;
            opacity: 0.95;
            color: rgba(255, 255, 255, 0.95);
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.5;
        }

        /* Section Styles - Enhanced card design */
        .section {
            background: rgba(43, 17, 90, 0.85);
            backdrop-filter: blur(15px);
            border: 1px solid rgba(0, 97, 177, 0.4);
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 35px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5), 0 2px 10px rgba(0, 97, 177, 0.2);
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
        }

        .section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, var(--light-blue), var(--red));
            border-radius: 20px 20px 0 0;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .section:hover::before {
            opacity: 1;
        }

        .section:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 50px rgba(0, 0, 0, 0.6), 0 5px 20px rgba(0, 97, 177, 0.3);
        }

        .section-title {
            font-size: 2rem;
            font-weight: 700;
            color: var(--white-text);
            margin-bottom: 30px;
            padding-bottom: 15px;
            border-bottom: 3px solid transparent;
            background: linear-gradient(90deg, var(--light-blue), var(--red)) bottom;
            background-size: 100% 3px;
            background-repeat: no-repeat;
            letter-spacing: -0.5px;
            display: flex;
            align-items: center;
            gap: 15px;
        }

        /* Add icon indicators to section titles */
        .section-title::before {
            content: '';
            width: 8px;
            height: 8px;
            background: var(--light-blue);
            border-radius: 50%;
            box-shadow: 0 0 20px var(--light-blue);
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; transform: scale(1); }
            50% { opacity: 0.7; transform: scale(1.2); }
        }

        /* About Section */
        .about-content {
            font-size: 1.1rem;
            line-height: 1.9;
            color: var(--light-gray-text);
        }

        .about-content p {
            margin-bottom: 20px;
        }

        .about-content p:last-child {
            margin-bottom: 0;
        }

        /* Subheading and Sub-subheading Styles */
        .subheading {
            font-size: 1.5rem;
            font-weight: 600;
            color: var(--light-blue);
            margin: 30px 0 20px 0;
            padding-bottom: 10px;
            border-bottom: 2px solid rgba(0, 97, 177, 0.3);
        }

        .sub-subheading {
            font-size: 1.2rem;
            font-weight: 500;
            color: var(--white-text);
            margin: 20px 0 15px 0;
            padding-left: 15px;
            border-left: 3px solid var(--light-blue);
        }

        .studies-content {
            margin-top: 15px;
        }

        .grades-content {
            margin-top: 10px;
        }

        /* Achievement Level Badge Styles */
        .achievement-level {
            position: absolute;
            top: 15px;
            right: 15px;
            padding: 6px 12px;
            border-radius: 15px;
            font-weight: 700;
            font-size: 0.8rem;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
        }

        .level-gold {
            background: linear-gradient(135deg, #FFD700, #FFA500);
            color: #000000;
            border: 2px solid #FFD700;
        }

        .level-silver {
            background: linear-gradient(135deg, #C0C0C0, #808080);
            color: #000000;
            border: 2px solid #C0C0C0;
        }

        .level-bronze {
            background: linear-gradient(135deg, #CD7F32, #8B4513);
            color: #FFFFFF;
            border: 2px solid #CD7F32;
        }

        /* Achievements Section - Enhanced with better highlighting */
        .achievement-item {
            margin-bottom: 30px;
            padding: 25px;
            background: linear-gradient(135deg, rgba(0, 97, 177, 0.15) 0%, rgba(0, 97, 177, 0.05) 100%);
            border-radius: 15px;
            border-left: 5px solid var(--light-blue);
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
            overflow: hidden;
        }

        .achievement-item::before {
            content: '';
            position: absolute;
            top: 0;
            right: 0;
            width: 60px;
            height: 60px;
            background: radial-gradient(circle, var(--light-blue) 0%, transparent 70%);
            opacity: 0.1;
            border-radius: 50%;
            transform: translate(20px, -20px);
        }

        .achievement-item:hover {
            background: linear-gradient(135deg, rgba(0, 97, 177, 0.25) 0%, rgba(0, 97, 177, 0.1) 100%);
            transform: translateX(10px) scale(1.02);
            box-shadow: 0 8px 30px rgba(0, 97, 177, 0.3);
        }

        .achievement-item:last-child {
            margin-bottom: 0;
        }

        .achievement-title {
            font-weight: 700;
            font-size: 1.3rem;
            color: var(--white-text);
            margin-bottom: 12px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .achievement-title::before {
            content: '🏆';
            font-size: 1.2rem;
        }

        .achievement-description {
            color: var(--light-gray-text);
            font-size: 1.05rem;
            line-height: 1.7;
            margin-bottom: 10px;
        }

        .achievement-date {
            color: var(--medium-gray-text);
            font-size: 0.9rem;
            font-style: italic;
            margin-top: 10px;
            display: inline-block;
            background: rgba(0, 97, 177, 0.2);
            padding: 4px 12px;
            border-radius: 20px;
            border: 1px solid rgba(0, 97, 177, 0.3);
        }

        /* Skills Section - Enhanced tag-style design */
        .skills-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }

        .skill-item {
            background: linear-gradient(135deg, rgba(0, 97, 177, 0.2) 0%, rgba(0, 97, 177, 0.1) 100%);
            border: 2px solid rgba(0, 97, 177, 0.4);
            padding: 12px 20px;
            border-radius: 25px;
            text-align: center;
            font-weight: 600;
            color: var(--white-text);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            font-size: 0.9rem;
            position: relative;
            overflow: hidden;
            cursor: default;
        }

        .skill-item::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 0;
            height: 0;
            background: radial-gradient(circle, var(--light-blue) 0%, transparent 70%);
            transition: all 0.4s ease;
            transform: translate(-50%, -50%);
            border-radius: 50%;
        }

        .skill-item:hover {
            background: linear-gradient(135deg, var(--light-blue) 0%, rgba(0, 97, 177, 0.8) 100%);
            color: var(--white-text);
            transform: translateY(-4px) scale(1.05);
            box-shadow: 0 8px 25px rgba(0, 97, 177, 0.5);
            border-color: var(--light-blue);
        }

        .skill-item:hover::before {
            width: 100%;
            height: 100%;
        }

        /* Hobbies Section - Enhanced with modern styling */
        .hobbies-list {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }

        .hobby-item {
            background: linear-gradient(135deg, var(--red) 0%, rgba(241, 26, 34, 0.8) 100%);
            color: var(--white-text);
            padding: 12px 22px;
            border-radius: 25px;
            font-weight: 600;
            box-shadow: 0 4px 15px rgba(241, 26, 34, 0.3);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            font-size: 0.9rem;
            position: relative;
            overflow: hidden;
        }

        .hobby-item::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
            transition: left 0.5s ease;
        }

        .hobby-item:hover {
            transform: translateY(-4px) scale(1.05);
            box-shadow: 0 8px 25px rgba(241, 26, 34, 0.5);
        }

        .hobby-item:hover::before {
            left: 100%;
        }

        /* Responsive Design - Enhanced for better mobile experience */
        @media (max-width: 768px) {
            body {
                padding: 20px 15px;
            }

            .header {
                padding: 40px 25px;
                margin-bottom: 35px;
            }

            .profile-name {
                font-size: 2.5rem;
            }

            .profile-headline {
                font-size: 1.1rem;
            }

            .section {
                padding: 30px 25px;
                margin-bottom: 30px;
            }

            .section-title {
                font-size: 1.6rem;
                margin-bottom: 25px;
            }

            .achievement-item {
                padding: 20px;
                margin-bottom: 25px;
            }

            .achievement-title {
                font-size: 1.1rem;
            }

            .skills-grid {
                gap: 12px;
            }

            .skill-item {
                padding: 10px 16px;
                font-size: 0.85rem;
            }

            .hobbies-list {
                gap: 12px;
            }

            .hobby-item {
                padding: 10px 18px;
                font-size: 0.85rem;
            }
        }

        /* Collapsible content styles */
        .collapsible-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.5s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .collapsible-content.expanded {
            max-height: 1000px;
        }

        /* Clickable section titles */
        .clickable-title {
            cursor: pointer;
            transition: all 0.3s ease;
            user-select: none;
        }

        .clickable-title:hover {
            color: var(--light-blue);
            transform: translateX(5px);
        }

        .clickable-title::after {
            content: ' ▼';
            font-size: 0.8rem;
            margin-left: 10px;
            transition: transform 0.3s ease;
        }

        .clickable-title.collapsed::after {
            transform: rotate(-90deg);
        }

        /* Smooth scrolling and additional polish */
        html {
            scroll-behavior: smooth;
        }

        /* Add subtle animation to page load */
        .section {
            animation: fadeInUp 0.6s ease-out;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Navigation Menu -->
        <nav class="navigation">
            <div class="nav-content">
                <a href="#about" class="nav-link">About Me</a>
                <a href="#studies" class="nav-link">Studies</a>
                <a href="#achievements" class="nav-link">Achievements</a>
                <a href="#skills" class="nav-link">Soft Skills</a>
                <a href="#hard-skills" class="nav-link">Hard Skills</a>
                <a href="#hobbies" class="nav-link">Hobbies</a>
                <a href="#contact" class="nav-link">Contact</a>
            </div>
        </nav>

        <!-- Header Section -->
        <header class="header">
            <div class="header-content">
                <img src="file:///C:/Users/f.makkar/CascadeProjects/linkedin-profile/Arfan.png" alt="Arfan Ahmad Faiz" class="profile-picture">
                <div class="header-text">
                    <h1 class="profile-name">Arfan Ahmad Faiz</h1>
                    <p class="profile-headline">IGCSE Stuent l Aspiring Pilot</p>
                </div>
            </div>
        </header>

        <!-- About Me Section -->
        <section id="about" class="section">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <p>My name is Arfan Ahmad and I am currently studying in Gems New Millennium School (GNMS). I am currently pursuing Economics, Math and Physics. My future plan is to get into an Aviation training course for pilot. It has been a dream for me to become a Pilot as its such a nice job since you are getting paid to travel around the world while landing the people who comes to visit the places. I want to pursue economics as my major as it a good stream and has many door to do different types of jobs with economics.</p>
            </div>
        </section>

        <!-- Studies Section -->
        <section id="studies" class="section">
            <h2 class="section-title">Studies</h2>
            <div class="studies-content">
                <!-- Grades Subheading -->
                <h3 class="subheading">Grades for IGCSE Board Exams</h3>
                <div class="grades-content">
                    <p><strong>A*:</strong> Physics, Maths, Economics</p>
                    <p><strong>A:</strong> EVM, Business Studies</p>
                </div>
            </div>
        </section>

        <!-- Achievements Section -->
        <section id="achievements" class="section">
            <h2 class="section-title clickable-title collapsed" onclick="toggleSection('achievements-content', this)">Achievements</h2>
            <div id="achievements-content" class="collapsible-content">
                <!-- Achievement item 1: DoFe Program -->
                <div class="achievement-item">
                    <div class="achievement-level level-bronze">Bronze</div>
                    <div class="achievement-title">Duke of Edinburgh's Award</div>
                    <div class="achievement-description">Currently pursuing the Bronze Award level, developing skills and character</div>
                    <div class="achievement-date">2024</div>
                </div>
                <!-- Achievement item 2: Swimming Competition -->
                <div class="achievement-item">
                    <div class="achievement-level level-gold">Gold</div>
                    <div class="achievement-level level-bronze" style="top: 60px;">Bronze</div>
                    <div class="achievement-title">Swimming Championship</div>
                    <div class="achievement-description">1st Place in 100m freestyle<br>3rd in Relay 100x4<br>3rd in 100m backstroke</div>
                    <div class="achievement-date">2020-2021</div>
                </div>
                <!-- Achievement item 3: Trinity College London -->
                <div class="achievement-item">
                    <div class="achievement-level level-gold">Grade 5</div>
                    <div class="achievement-title">Trinity College London</div>
                    <div class="achievement-description">Grade 5 in Trinity College London Plays in Production</div>
                    <div class="achievement-date">2023</div>
                </div>
                <!-- Achievement item 4: Football Interhouse -->
                <div class="achievement-item">
                    <div class="achievement-level level-bronze">3rd Place</div>
                    <div class="achievement-title">Football Interhouse</div>
                    <div class="achievement-description">Achieved bronze in the competitive interhouse football tournament, showcasing athletic ability and team spirit</div>
                    <div class="achievement-date">2022</div>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="section">
            <h2 class="section-title">Soft Skills</h2>
            <div class="skills-grid">
                <!-- Skill item 1: Communication -->
                <div class="skill-item">Communication</div>
                <!-- Skill item 2: Teamwork -->
                <div class="skill-item">Teamwork</div>
                <!-- Skill item 3: Problem Solving -->
                <div class="skill-item">Problem Solving</div>
                <!-- Skill item 4: Creative Thinking -->
                <div class="skill-item">Creative Thinking</div>
                <!-- Skill item 5: Self Awareness -->
                <div class="skill-item">Self Awareness</div>
                <!-- Skill item 6: Time Management -->
                <div class="skill-item">Time Management</div>
                <!-- Skill item 7: Adaptability -->
                <div class="skill-item">Adaptability</div>
            </div>
        </section>

        <!-- Hard Skills Section -->
        <section id="hard-skills" class="section">
            <h2 class="section-title">Hard Skills</h2>
            <div class="skills-grid">
                <!-- Hard Skill item 1: Money Management -->
                <div class="skill-item">Money Management</div>
                <!-- Hard Skill item 2: Cooking -->
                <div class="skill-item">Cooking</div>
                <!-- Hard Skill item 3: Basic Repairs -->
                <div class="skill-item">Basic Repairs</div>
            </div>
        </section>

        <!-- Hobbies Section -->
        <section id="hobbies" class="section">
            <h2 class="section-title">Hobbies</h2>
            <div class="hobbies-list">
                <!-- Hobby item 1: Football -->
                <div class="hobby-item">Football</div>
                <!-- Hobby item 2: Swimming -->
                <div class="hobby-item">Swimming</div>
                <!-- Hobby item 3: Gaming -->
                <div class="hobby-item">Gaming</div>
                <!-- Hobby item 4: Chess -->
                <div class="hobby-item">Chess</div>
                <!-- Hobby item 5: Cycling -->
                <div class="hobby-item">Cycling</div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="section">
            <h2 class="section-title clickable-title collapsed" onclick="toggleSection('contact-content', this)">Contact</h2>
            <div id="contact-content" class="collapsible-content">
                <div class="contact-content">
                    <p><strong>Phone:</strong> +971 552811077</p>
                    <p><strong>Gmail:</strong> arfaibnfaiz@gmail.com</p>
                </div>
            </div>
        </section>
    </div>
    
    <script>
        // Toggle collapse/expand functionality for clickable titles
        function toggleSection(sectionId, titleElement) {
            const section = document.getElementById(sectionId);
            const isCollapsed = titleElement.classList.contains('collapsed');
            
            if (isCollapsed) {
                section.classList.add('expanded');
                titleElement.classList.remove('collapsed');
            } else {
                section.classList.remove('expanded');
                titleElement.classList.add('collapsed');
            }
        }
    </script>
</body>
</html>
