<!DOCTYPE html>
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
            background: linear-gradient(135deg, #667eea 0%, #764ba2 25%, #f093fb 50%, #f5576c 75%, #4facfe 100%);
            background-attachment: fixed;
            color: #000000e0;
            padding: 20px;
            margin: 0;
        }
        
        /* Colorful container with rainbow effects */
        .profile-container {
            max-width: 1128px;
            margin: 0 auto;
            background: linear-gradient(135deg, #ffffff 0%, #f8f9ff 50%, #ffffff 100%);
            box-shadow: 0 0 0 2px rgba(102, 126, 234, 0.3), 0 8px 32px rgba(102, 126, 234, 0.2), 0 16px 48px rgba(240, 147, 251, 0.15);
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
            background: linear-gradient(90deg, #667eea, #764ba2, #f093fb, #f5576c, #4facfe, #667eea);
            background-size: 200% 100%;
            animation: rainbow 3s linear infinite;
        }
        
        @keyframes rainbow {
            0% { background-position: 0% 0%; }
            100% { background-position: 200% 0%; }
        }
        
        /* Vibrant header with colorful gradient */
        .header {
            position: relative;
            height: 200px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 25%, #f093fb 50%, #f5576c 75%, #4facfe 100%);
            overflow: hidden;
            animation: gradientShift 8s ease infinite;
            background-size: 400% 400%;
        }
        
        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 200"><defs><pattern id="pattern" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse"><circle cx="20" cy="20" r="2" fill="white" opacity="0.3"/></pattern></defs><rect width="1200" height="200" fill="url(%23pattern)"/></svg>');
            opacity: 0.6;
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
            border-color: transparent transparent #0a66c2 transparent;
            transform: rotate(-45deg);
        }
        
        /* Colorful cards with gradients */
        .item {
            background: linear-gradient(135deg, #f8f9ff 0%, #e8f0ff 50%, #f5f7ff 100%);
            border-radius: 12px;
            padding: 16px;
            margin-bottom: 16px;
            transition: all 0.3s ease;
            border: 1px solid rgba(102, 126, 234, 0.1);
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
            background: linear-gradient(90deg, transparent, rgba(102, 126, 234, 0.1), transparent);
            transition: left 0.6s ease;
        }
        
        .item:hover::before {
            left: 100%;
        }
        
        .item:hover {
            background: linear-gradient(135deg, #e8f0ff 0%, #dce7ff 50%, #e8f0ff 100%);
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(102, 126, 234, 0.15);
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
            background-color: #0a66c2;
            color: white;
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
        
        /* Rainbow skill colors */
        .skill-item:nth-child(1) {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            border: 2px solid #667eea;
        }
        
        .skill-item:nth-child(2) {
            background: linear-gradient(135deg, #f093fb, #f5576c);
            color: white;
            border: 2px solid #f093fb;
        }
        
        .skill-item:nth-child(3) {
            background: linear-gradient(135deg, #4facfe, #00f2fe);
            color: white;
            border: 2px solid #4facfe;
        }
        
        .skill-item:nth-child(4) {
            background: linear-gradient(135deg, #43e97b, #38f9d7);
            color: white;
            border: 2px solid #43e97b;
        }
        
        .skill-item:nth-child(5) {
            background: linear-gradient(135deg, #fa709a, #fee140);
            color: white;
            border: 2px solid #fa709a;
        }
        
        .skill-item:nth-child(6) {
            background: linear-gradient(135deg, #30cfd0, #330867);
            color: white;
            border: 2px solid #30cfd0;
        }
        
        .skill-item:nth-child(n+7) {
            background: linear-gradient(135deg, #a8edea, #fed6e3);
            color: #333;
            border: 2px solid #a8edea;
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
        
        /* Colorful about section */
        .about-text {
            font-size: 15px;
            color: #000000e0;
            line-height: 1.6;
            background: linear-gradient(135deg, #f8f9ff 0%, #e8f0ff 50%, #f5f7ff 100%);
            padding: 20px;
            border-radius: 12px;
            border: 1px solid rgba(102, 126, 234, 0.2);
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
            background: linear-gradient(90deg, #667eea, #764ba2, #f093fb, #f5576c, #4facfe);
            background-size: 200% 100%;
            animation: rainbow 3s linear infinite;
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
        
        <!-- LinkedIn-style header with cover photo -->
        <header class="header"></header>
        
        <!-- Profile section with centered heading -->
        <div class="profile-section">
            <div class="profile-info">
                <h1 class="name">Arfan Ahmad Faiz</h1>
                <p class="headline">Motivated Student | Swimming Champion | DoFe Award Recipient</p>
            </div>
        </div>
        
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
                    <span class="badge">Completed</span>
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
                    <span class="badge">Sports</span>
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
        
        <!-- Hobbies section -->
        <section class="section">
            <h2 class="section-title">Interests</h2>
            <div class="skills-grid">
                <div class="skill-item">Playing Football</div>
                <div class="skill-item">Swimming</div>
                <div class="skill-item">Gaming</div>
            </div>
        </section>
        
    </div>

</body>
</html>
