<!-- Hero Section -->
<section id="home" class="hero">
    <div class="hero-content">
        <h1 class="hero-title">Clean Air, Clean Planet</h1>
        <p class="hero-subtitle">SDG 13 & SDG 3 in Action</p>
        <p class="hero-description">
            Join the movement to combat air pollution and protect our climate and health. 
            Together, we can create a sustainable future for generations to come.
        </p>
        <div class="hero-buttons">
            <a href="#action" class="btn btn-primary">Take Action Now</a>
            <a href="#about" class="btn btn-secondary">Learn More</a>
        </div>
    </div>
    <div class="hero-visual">
        <div class="air-quality-indicator">
            <div class="aqi-value">150</div>
            <div class="aqi-label">Current AQI</div>
            <div class="aqi-status unhealthy">Unhealthy</div>
        </div>
    </div>
</section>

<!-- About Section -->
<section id="about" class="about">
    <div class="container">
        <h2 class="section-title">Understanding the Crisis</h2>
        <div class="about-grid">
            <div class="about-card">
                <i class="fas fa-smog"></i>
                <h3>Air Pollution Reality</h3>
                <p>9 out of 10 people breathe air containing high levels of pollutants, causing 7 million premature deaths annually.</p>
            </div>
            <div class="about-card">
                <i class="fas fa-temperature-high"></i>
                <h3>Climate Change Impact</h3>
                <p>Air pollution contributes significantly to global warming, threatening ecosystems and communities worldwide.</p>
            </div>
            <div class="about-card">
                <i class="fas fa-heartbeat"></i>
                <h3>Health Consequences</h3>
                <p>Polluted air causes respiratory diseases, heart problems, and reduces life expectancy by up to 2 years.</p>
            </div>
        </div>
    </div>
</section>

<!-- SDG 13 Section -->
<section id="sdg13" class="sdg-section sdg13">
    <div class="container">
        <div class="sdg-header">
            <div class="sdg-logo">
                <span class="sdg-number">13</span>
                <span class="sdg-text">CLIMATE ACTION</span>
            </div>
            <h2 class="section-title">SDG 13: Climate Action</h2>
            <p class="sdg-description">
                Take urgent action to combat climate change and its impacts through reduced air pollution and sustainable practices.
            </p>
        </div>
        
        <div class="sdg-content">
            <div class="sdg-targets">
                <h3>Key Targets</h3>
                <div class="target-list">
                    <div class="target-item">
                        <i class="fas fa-bullseye"></i>
                        <span>Strengthen resilience to climate-related hazards</span>
                    </div>
                    <div class="target-item">
                        <i class="fas fa-bullseye"></i>
                        <span>Integrate climate measures into policies</span>
                    </div>
                    <div class="target-item">
                        <i class="fas fa-bullseye"></i>
                        <span>Improve education on climate change</span>
                    </div>
                </div>
            </div>
            
            <div class="sdg-stats">
                <div class="stat-card">
                    <div class="stat-number">4.2°C</div>
                    <div class="stat-label">Temperature Rise Without Action</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number">2030</div>
                    <div class="stat-label">Deadline for Climate Action</div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- SDG 3 Section -->
<section id="sdg3" class="sdg-section sdg3">
    <div class="container">
        <div class="sdg-header">
            <div class="sdg-logo">
                <span class="sdg-number">3</span>
                <span class="sdg-text">GOOD HEALTH</span>
            </div>
            <h2 class="section-title">SDG 3: Good Health and Well-being</h2>
            <p class="sdg-description">
                Ensure healthy lives and promote well-being for all at all ages by addressing air pollution's health impacts.
            </p>
        </div>
        
        <div class="sdg-content">
            <div class="health-impact">
                <h3>Health Impacts of Air Pollution</h3>
                <div class="impact-grid">
                    <div class="impact-card">
                        <i class="fas fa-lungs"></i>
                        <h4>Respiratory Diseases</h4>
                        <p>Asthma, COPD, and lung cancer rates increase with air pollution exposure.</p>
                    </div>
                    <div class="impact-card">
                        <i class="fas fa-heart"></i>
                        <h4>Cardiovascular Problems</h4>
                        <p>Air pollution increases risk of heart attacks, strokes, and hypertension.</p>
                    </div>
                    <div class="impact-card">
                        <i class="fas fa-brain"></i>
                        <h4>Neurological Effects</h4>
                        <p>Cognitive development in children and brain function in adults are affected.</p>
                    </div>
                </div>
            </div>
            
            <div class="health-solutions">
                <h3>Protecting Our Health</h3>
                <ul class="solutions-list">
                    <li>Monitor air quality daily</li>
                    <li>Use air purifiers indoors</li>
                    <li>Wear masks during high pollution days</li>
                    <li>Exercise in clean air environments</li>
                    <li>Support clean energy initiatives</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<!-- Interactive Impact Section -->
<section id="impact" class="impact">
    <div class="container">
        <h2 class="section-title">Measure Your Impact</h2>
        
        <div class="interactive-tools">
            <!-- Carbon Calculator -->
            <div class="calculator-card">
                <h3><i class="fas fa-calculator"></i> Carbon Footprint Calculator</h3>
                <div class="calculator-form">
                    <div class="form-group">
                        <label for="transport">Daily Transportation (km)</label>
                        <input type="number" id="transport" placeholder="Enter km traveled">
                    </div>
                    <div class="form-group">
                        <label for="electricity">Daily Electricity Usage (kWh)</label>
                        <input type="number" id="electricity" placeholder="Enter kWh">
                    </div>
                    <div class="form-group">
                        <label for="waste">Weekly Waste (kg)</label>
                        <input type="number" id="waste" placeholder="Enter kg of waste">
                    </div>
                    <button class="btn btn-primary" onclick="calculateCarbon()">Calculate Impact</button>
                    <div id="carbon-result" class="result-box"></div>
                </div>
            </div>

            <!-- Air Quality Quiz -->
            <div class="quiz-card">
                <h3><i class="fas fa-question-circle"></i> Air Quality Quiz</h3>
                <div class="quiz-container">
                    <div class="question" id="quiz-question">
                        <p>What is the main cause of air pollution in urban areas?</p>
                        <div class="options">
                            <button class="option-btn" onclick="checkAnswer('A')">A) Industrial emissions</button>
                            <button class="option-btn" onclick="checkAnswer('B')">B) Vehicle emissions</button>
                            <button class="option-btn" onclick="checkAnswer('C')">C) Natural sources</button>
                            <button class="option-btn" onclick="checkAnswer('D')">D) Agricultural burning</button>
                        </div>
                    </div>
                    <div id="quiz-feedback" class="quiz-feedback"></div>
                </div>
            </div>
        </div>

                </div>
</section>

<!-- Call to Action Section -->
<section id="action" class="action">
    <div class="container">
        <h2 class="section-title">Take Action Today</h2>
        <p class="action-subtitle">Every small step counts towards a cleaner, healthier planet</p>
        
        <div class="action-grid">
            <div class="action-card">
                <i class="fas fa-bicycle"></i>
                <h3>Sustainable Transport</h3>
                <p>Use public transport, cycle, or walk instead of driving alone.</p>
                <button class="action-btn">Learn How</button>
            </div>
            
            <div class="action-card">
                <i class="fas fa-solar-panel"></i>
                <h3>Renewable Energy</h3>
                <p>Switch to clean energy sources and reduce electricity consumption.</p>
                <button class="action-btn">Get Started</button>
            </div>
            
            <div class="action-card">
                <i class="fas fa-recycle"></i>
                <h3>Reduce, Reuse, Recycle</h3>
                <p>Minimize waste and choose sustainable products.</p>
                <button class="action-btn">Take Pledge</button>
            </div>
            
            <div class="action-card">
                <i class="fas fa-tree"></i>
                <h3>Plant Trees</h3>
                <p>Support reforestation and create green spaces in your community.</p>
                <button class="action-btn">Join Initiative</button>
            </div>
            
            <div class="action-card">
                <i class="fas fa-users"></i>
                <h3>Spread Awareness</h3>
                <p>Educate others and advocate for clean air policies.</p>
                <button class="action-btn">Share Now</button>
            </div>
            
            <div class="action-card">
                <i class="fas fa-hand-holding-heart"></i>
                <h3>Support Organizations</h3>
                <p>Donate to or volunteer with environmental organizations.</p>
                <button class="action-btn">Find Groups</button>
            </div>
        </div>
        
        <div class="pledge-section">
            <h3>Make Your Clean Air Pledge</h3>
            <div class="pledge-form">
                <input type="text" id="pledge-name" placeholder="Your name">
                <textarea id="pledge-text" placeholder="I pledge to..."></textarea>
                <button class="btn btn-primary" onclick="submitPledge()">Submit Pledge</button>
            </div>
        </div>
    </div>
</section>

<!-- Resources Section -->
<section id="resources" class="resources">
    <div class="container">
        <h2 class="section-title">Educational Resources</h2>
        
        <div class="resources-grid">
            <div class="resource-card">
                <i class="fas fa-book"></i>
                <h3>Research Papers</h3>
                <p>Latest scientific studies on air pollution and climate change.</p>
                <a href="#" class="resource-link">Access Papers</a>
            </div>
            
            <div class="resource-card">
                <i class="fas fa-video"></i>
                <h3>Educational Videos</h3>
                <p>Documentaries and tutorials about air quality and health.</p>
                <a href="#" class="resource-link">Watch Videos</a>
            </div>
            
            <div class="resource-card">
                <i class="fas fa-download"></i>
                <h3>Downloadable Guides</h3>
                <p>PDF guides for schools and communities on clean air initiatives.</p>
                <a href="#" class="resource-link">Download</a>
            </div>
            
            <div class="resource-card">
                <i class="fas fa-gamepad"></i>
                <h3>Interactive Games</h3>
                <p>Learn about air pollution through fun educational games.</p>
                <a href="#" class="resource-link">Play Games</a>
            </div>
        </div>
        
        <div class="contact-section">
            <h3>Get Involved</h3>
            <p>Join our community of change-makers working for cleaner air and a healthier planet.</p>
            <div class="contact-info">
                <div class="contact-item">
                    <i class="fas fa-envelope"></i>
                    <span>info@cleanairplanet.org</span>
                </div>
                <div class="contact-item">
                    <i class="fas fa-phone"></i>
                    <span>+1 (555) 123-4567</span>
                </div>
                <div class="contact-item">
                    <i class="fas fa-map-marker-alt"></i>
                    <span>Global Environmental Initiative</span>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Footer -->
<footer class="footer">
    <div class="container">
        <div class="footer-content">
            <div class="footer-section">
                <h4>About This Project</h4>
                <p>An educational website created to raise awareness about air pollution and its impact on climate change and human health, supporting SDG 13 and SDG 3.</p>
            </div>
            
            <div class="footer-section">
                <h4>Quick Links</h4>
                <ul>
                    <li><a href="#about">About Air Pollution</a></li>
                    <li><a href="#sdg13">SDG 13 Climate Action</a></li>
                    <li><a href="#sdg3">SDG 3 Good Health</a></li>
                    <li><a href="#action">Take Action</a></li>
                </ul>
            </div>
            
            <div class="footer-section">
                <h4>Follow Us</h4>
                <div class="social-links">
                    <a href="#" class="social-link"><i class="fab fa-facebook"></i></a>
                    <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="social-link"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="social-link"><i class="fab fa-linkedin"></i></a>
                    <a href="#" class="social-link"><i class="fab fa-youtube"></i></a>
                </div>
            </div>
        </div>
        
        <div class="footer-bottom">
            <p>&copy; 2026 Clean Air, Clean Planet. Created for ICT Competition 2026. Supporting SDG 13 & SDG 3.</p>
            <p>Theme: Clean Air, Clean Planet - SDG 13 & SDG 3 in Action | Dates: 26-28 January 2026</p>
        </div>
    </div>
</footer>

<script src="script.js"></script>
