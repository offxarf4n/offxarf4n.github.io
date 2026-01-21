<!-- LinkedIn-style Student Profile for Arfan Ahmad Faiz -->
<html lang="en">
<head>
    <!-- Meta tags for proper display and character encoding -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arfan Ahmad Faiz - Student Profile</title>
    
    <!-- Final LinkedIn-style CSS for authentic profile appearance -->
    <style>
        /* Import LinkedIn's preferred fonts */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        
        /* Reset and base styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.5;
            background: 
                radial-gradient(circle at 20% 80%, rgba(255, 255, 255, 0.1) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(255, 255, 255, 0.05) 0%, transparent 50%),
                linear-gradient(135deg, #1a1a1a 0%, #2c2c2c 25%, #dc143c 50%, #003d82 75%, #1a1a1a 100%);
            background-attachment: fixed;
            color: #000000e0;
            padding: 20px;
            margin: 0;
            position: relative;
        }
        
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 200"><defs><radialGradient id="ballGradient"><stop offset="0%" style="stop-color:white;stop-opacity:0.3"/><stop offset="100%" style="stop-color:white;stop-opacity:0.1"/></radialGradient></defs><circle cx="100" cy="100" r="80" fill="url(%23ballGradient)" stroke="rgba(255,255,255,0.4)" stroke-width="2"/><path d="M100 40 L100 160 M40 100 L160 100" stroke="rgba(255,255,255,0.3)" stroke-width="2"/><path d="M100 40 Q60 100 100 160 Q140 100 100 40" fill="none" stroke="rgba(255,255,255,0.3)" stroke-width="2"/><path d="M60 60 L100 40 L140 60 L160 100 L140 140 L100 160 L60 140 L40 100 L60 60" fill="none" stroke="rgba(255,255,255,0.25)" stroke-width="1.5"/><path d="M100 40 L140 60 L100 80 L60 60 L100 40" fill="rgba(255,255,255,0.15)"/><path d="M100 80 L140 100 L100 120 L60 100 L100 80" fill="rgba(255,255,255,0.15)"/><path d="M100 120 L140 140 L100 160 L60 140 L100 120" fill="rgba(255,255,255,0.15)"/><path d="M60 60 L100 80 L60 100 L40 100 L60 60" fill="rgba(255,255,255,0.15)"/><path d="M60 100 L100 120 L60 140 L40 140 L60 100" fill="rgba(255,255,255,0.15)"/></svg>');
            background-size: 300px 300px;
            background-position: center;
            background-repeat: no-repeat;
            opacity: 0.4;
            pointer-events: none;
            z-index: -1;
        }
        
        body::after {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2000 1200"><defs><linearGradient id="planeGradient" x1="0%" y1="0%" x2="100%" y2="100%"><stop offset="0%" style="stop-color:rgba(255,255,255,0.25)"/><stop offset="100%" style="stop-color:rgba(255,255,255,0.08)"/></linearGradient></defs><path d="M100 600 L400 480 L700 420 L1000 400 L1300 420 L1600 480 L1900 600 L1900 900 L1600 880 L1300 860 L1000 840 L700 860 L400 880 L100 900 Z" fill="none" stroke="url(%23planeGradient)" stroke-width="3"/><path d="M700 420 L800 320 L900 260 L1000 240 L1100 260 L1200 320 L1300 420 L1400 520 L1500 620 L1600 720" fill="none" stroke="url(%23planeGradient)" stroke-width="2"/><path d="M1000 240 L980 180 L970 120 L980 60 L1000 0 L1020 60 L1030 120 L1020 180 L1000 240" fill="none" stroke="url(%23planeGradient)" stroke-width="2"/><path d="M400 480 L300 380 L250 280 L270 180 L300 80 L400 30 L500 80 L530 180 L550 280 L500 380 L400 480" fill="none" stroke="url(%23planeGradient)" stroke-width="2"/><path d="M1300 420 L1400 320 L1500 260 L1520 180 L1500 80 L1400 30 L1300 80 L1280 180 L1300 280 L1350 380 L1300 420" fill="none" stroke="url(%23planeGradient)" stroke-width="2"/><path d="M1000 400 L980 380 L970 360 L980 340 L1000 320 L1020 340 L1030 360 L1020 380 L1000 400" fill="none" stroke="url(%23planeGradient)" stroke-width="1.5"/><circle cx="1000" cy="600" r="20" fill="none" stroke="url(%23planeGradient)" stroke-width="2"/><path d="M980 600 L960 580 L940 560 L960 540 L980 520" fill="none" stroke="url(%23planeGradient)" stroke-width="1.5"/><path d="M1020 600 L1040 580 L1060 560 L1040 540 L1020 520" fill="none" stroke="url(%23planeGradient)" stroke-width="1.5"/><path d="M1000 620 L1000 660 L1000 720" fill="none" stroke="url(%23planeGradient)" stroke-width="1.5"/></svg>');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            opacity: 0.6;
            pointer-events: none;
            z-index: -2;
        }
        
        /* Container with red, blue, black matte grey theme */
        .profile-container {
            max-width: 1128px;
            margin: 0 auto;
            background: linear-gradient(135deg, #ffffff 0%, #f5f5f5 50%, #ffffff 100%);
            box-shadow: 0 0 0 2px rgba(220, 20, 60, 0.3), 0 8px 32px rgba(0, 61, 130, 0.2), 0 16px 48px rgba(44, 44, 44, 0.15);
            border-radius: 16px;
            overflow: hidden;
            position: relative;
        }
        
        .profile-container::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 4px;
            background: linear-gradient(90deg, #dc143c, #003d82, #2c2c2c, #dc143c, #003d82, #2c2c2c);
            background-size: 200% 100%;
            animation: colorShift 3s linear infinite;
        }
        
        @keyframes colorShift {
            0% { background-position: 0% 0%; }
            100% { background-position: 200% 0%; }
        }
        
        /* Black banner header */
        .header {
            position: relative;
            height: 200px;
            background: linear-gradient(135deg, #000000 0%, #1a1a1a 50%, #000000 100%);
            overflow: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        
        .header-content {
            position: relative;
            z-index: 2;
            color: white;
        }
        
        .header-name {
            font-size: 3.5em;
            font-weight: 700;
            margin: 0;
            letter-spacing: -1px;
            text-shadow: 0 4px 8px rgba(0,0,0,0.5);
            background: linear-gradient(135deg, #ffffff 0%, #f0f0f0 50%, #ffffff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .header-headline {
            font-size: 1.3em;
            margin: 10px 0 0 0;
            font-weight: 400;
            color: rgba(255,255,255,0.9);
            text-shadow: 0 2px 4px rgba(0,0,0,0.3);
        }
        
        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 200"><defs><pattern id="pattern" x="0" y="0" width="60" height="60" patternUnits="userSpaceOnUse"><circle cx="30" cy="30" r="1" fill="white" opacity="0.1"/></pattern></defs><rect width="1200" height="200" fill="url(%23pattern)"/></svg>');
            opacity: 0.8;
        }
        
        /* Profile section with centered heading */
        .profile-section {
            position: relative;
            padding: 40px 24px 20px 24px;
            margin-top: -40px;
            text-align: center;
            margin-bottom: 32px;
        }
        
        .profile-info {
            padding-bottom: 16px;
        }
        
        .name {
            font-size: 24px;
            font-weight: 600;
            color: #000000e0;
            margin: 0 0 4px 0;
            line-height: 1.2;
        }
        
        .headline {
            font-size: 16px;
            color: #00000099;
            margin: 0 0 8px 0;
            line-height: 1.4;
        }
        
        /* LinkedIn-style sections */
        .section {
            padding: 24px;
            border-bottom: 1px solid #00000014;
        }
        
        .section:last-child {
            border-bottom: none;
        }
        
        .section-title {
            font-size: 20px;
            font-weight: 600;
            color: #000000e0;
            margin: 0 0 16px 0;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .section-title::before {
            content: '';
            width: 0;
            height: 0;
            border-style: solid;
            border-width: 0 0 8px 8px;
            border-color: transparent transparent #dc143c transparent;
            transform: rotate(-45deg);
        }
        
        /* Cards with red, blue, black matte grey theme */
        .item {
            background: linear-gradient(135deg, #f8f8f8 0%, #f0f0f0 50%, #f5f5f5 100%);
            border-radius: 12px;
            padding: 16px;
            margin-bottom: 16px;
            transition: all 0.3s ease;
            border: 1px solid rgba(220, 20, 60, 0.1);
            position: relative;
            overflow: hidden;
        }
        
        .item::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(220, 20, 60, 0.1), transparent);
            transition: left 0.6s ease;
        }
        
        .item:hover::before {
            left: 100%;
        }
        
        .item:hover {
            background: linear-gradient(135deg, #fff5f5 0%, #f0f0f0 50%, #f5f5f5 100%);
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(220, 20, 60, 0.15);
        }
        
        .item:last-child {
            margin-bottom: 0;
        }
        
        .item-title {
            font-size: 16px;
            font-weight: 600;
            color: #000000e0;
            margin: 0 0 8px 0;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        .item-title span {
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .item-title .badge {
            background-color: #dc143c;
            color: white;
            padding: 2px 8px;
            border-radius: 12px;
            font-size: 12px;
            font-weight: 500;
        }
        
        .item-title .badge.completed {
            background-color: #28a745;
            color: white;
            padding: 2px 8px;
            border-radius: 12px;
            font-size: 12px;
            font-weight: 500;
        }
        
        .item-title .badge.academic {
            background-color: #28a745;
            color: white;
            padding: 2px 8px;
            border-radius: 12px;
            font-size: 12px;
            font-weight: 500;
        }
        
        .item-title .badge.sports {
            background-color: #ffd700;
            color: #333;
            padding: 2px 8px;
            border-radius: 12px;
            font-size: 12px;
            font-weight: 500;
        }
        
        .item-description {
            font-size: 14px;
            color: #00000099;
            line-height: 1.6;
            margin: 0;
        }
        
        /* Vibrant skills with rainbow colors */
        .skills-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 16px;
        }
        
        .skill-item {
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: 600;
            transition: all 0.3s ease;
            cursor: default;
            position: relative;
            overflow: hidden;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        
        /* Red, blue, black matte grey skill colors */
        .skill-item:nth-child(1) {
            background: linear-gradient(135deg, #dc143c, #8b0000);
            color: white;
            border: 2px solid #dc143c;
        }
        
        .skill-item:nth-child(2) {
            background: linear-gradient(135deg, #003d82, #001f4d);
            color: white;
            border: 2px solid #003d82;
        }
        
        .skill-item:nth-child(3) {
            background: linear-gradient(135deg, #2c2c2c, #1a1a1a);
            color: white;
            border: 2px solid #2c2c2c;
        }
        
        .skill-item:nth-child(4) {
            background: linear-gradient(135deg, #dc143c, #ff6b6b);
            color: white;
            border: 2px solid #dc143c;
        }
        
        .skill-item:nth-child(5) {
            background: linear-gradient(135deg, #003d82, #4169e1);
            color: white;
            border: 2px solid #003d82;
        }
        
        .skill-item:nth-child(6) {
            background: linear-gradient(135deg, #2c2c2c, #404040);
            color: white;
            border: 2px solid #2c2c2c;
        }
        
        .skill-item:nth-child(n+7) {
            background: linear-gradient(135deg, #dc143c, #003d82);
            color: white;
            border: 2px solid #dc143c;
        }
        
        .skill-item::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            transition: left 0.5s ease;
        }
        
        .skill-item:hover::before {
            left: 100%;
        }
        
        .skill-item:hover {
            transform: translateY(-3px) scale(1.1);
            box-shadow: 0 8px 25px rgba(0,0,0,0.2);
        }
        
        /* About section with red, blue, black matte grey theme */
        .about-text {
            font-size: 15px;
            color: #000000e0;
            line-height: 1.6;
            background: linear-gradient(135deg, #f8f8f8 0%, #f0f0f0 50%, #f5f5f5 100%);
            padding: 20px;
            border-radius: 12px;
            border: 1px solid rgba(220, 20, 60, 0.2);
            position: relative;
            overflow: hidden;
        }
        
        .about-text::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, #dc143c, #003d82, #2c2c2c, #dc143c, #003d82, #2c2c2c);
            background-size: 200% 100%;
            animation: colorShift 3s linear infinite;
        }
        
        /* Mobile responsive design */
        @media (max-width: 768px) {
            .profile-container {
                border-radius: 0;
                box-shadow: none;
            }
            
            .header {
                height: 120px;
            }
            
            .profile-section {
                flex-direction: column;
                align-items: center;
                text-align: center;
                padding: 0 16px;
                margin-top: -60px;
                gap: 16px;
            }
            
            .profile-image {
                width: 120px;
                height: 120px;
            }
            
            .profile-info {
                padding-bottom: 0;
            }
            
            .section {
                padding: 16px;
            }
            
            .section-title {
                font-size: 18px;
            }
            
            .item {
                padding: 12px;
            }
            
            .skills-grid {
                gap: 6px;
            }
            
            .skill-item {
                padding: 4px 10px;
                font-size: 13px;
            }
        }
        
        @media (max-width: 480px) {
            .header {
                height: 100px;
            }
            
            .profile-section {
                padding: 0 12px;
            }
            
            .section {
                padding: 12px;
            }
            
            .name {
                font-size: 20px;
            }
            
            .headline {
                font-size: 14px;
            }
        }
    </style>
</head>
<body>

    <!-- Main container for the entire profile -->
    <div class="profile-container">
        
        <!-- Black banner header with name and headline -->
        <header class="header">
            <div class="header-content">
                <h1 class="header-name">Arfan Ahmad Faiz</h1>
                <p class="header-headline">Future Pilot | Academic Excellence | Swimming Champion</p>
            </div>
        </header>
        
        <!-- About Me section -->
        <section class="section">
            <h2 class="section-title">About</h2>
            <div class="about-text">
                Hello! I'm Arfan Ahmad Faiz, a passionate student who loves learning new skills and 
                taking on challenges. I believe in continuous growth and pushing myself to achieve my goals. 
                I enjoy sports, teamwork, and personal development activities that help me become a better person.
            </div>
        </section>
        
        <!-- Achievements section -->
        <section class="section">
            <h2 class="section-title">Achievements</h2>
            
            <!-- Duke of Edinburgh Award -->
            <div class="item">
                <h3 class="item-title">
                    <span>Duke of Edinburgh (DoFe) Award</span>
                    <span class="badge completed">Completed</span>
                </h3>
                <p class="item-description">
                    Successfully participated in and completed the DoFe program, demonstrating commitment, 
                    resilience, and personal growth through various challenges and community service.
                </p>
            </div>
            
            <!-- Swimming Achievements -->
            <div class="item">
                <h3 class="item-title">
                    <span>Swimming Competition Achievements</span>
                    <span class="badge sports">Sports</span>
                </h3>
                <p class="item-description">
                    • 1st Position - Freestyle 100m<br>
                    • 3rd Position - Relay Competition<br>
                    • 3rd Position - Backstroke 100m
                </p>
            </div>
        </section>
        
        <!-- Skills section -->
        <section class="section">
            <h2 class="section-title">Skills</h2>
            <div class="skills-grid">
                <div class="skill-item">Swimming</div>
                <div class="skill-item">Football</div>
                <div class="skill-item">Gaming</div>
                <div class="skill-item">Teamwork</div>
                <div class="skill-item">Leadership</div>
                <div class="skill-item">Time Management</div>
            </div>
        </section>
        
        <!-- Career section -->
        <section class="section">
            <h2 class="section-title">Career Aspirations</h2>
            <div class="item">
                <h3 class="item-title">
                    <span>Future Pilot</span>
                    <span class="badge">Dream Career</span>
                </h3>
                <p class="item-description">
                    I aspire to become a pilot in the future. This has been my dream since childhood, 
                    and I'm working hard to achieve this goal through dedication to my studies and 
                    personal development.
                </p>
            </div>
        </section>
        
        <!-- Education section -->
        <section class="section">
            <h2 class="section-title">Education</h2>
            <div class="item">
                <h3 class="item-title">
                    <span>IGCSE Board Exams</span>
                    <span class="badge academic">Academic Excellence</span>
                </h3>
                <p class="item-description">
                    <strong>Grade A*:</strong> Maths, Physics, Economics<br>
                    <strong>Grade A:</strong> EVM, ICT, English, Business Studies
                </p>
            </div>
            <div class="item">
                <h3 class="item-title">
                    <span>Future College Plans</span>
                    <span class="badge">Goal</span>
                </h3>
                <p class="item-description">
                    I plan to pursue Economics in college, building on my strong foundation from IGCSE 
                    where I achieved an A* grade. This aligns with my interest in understanding 
                    global markets, financial systems, and economic policies that shape our world.
                </p>
            </div>
        </section>
        
    </div>

</body>
</html>
