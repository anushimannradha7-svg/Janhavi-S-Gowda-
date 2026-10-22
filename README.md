# Janhavi-S-Gowda-
• "My personal developer portfolio website showcasing my skills, projects, and experience." • "A repository dedicated to my personal projects, coding journey, and resume."
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Janhavi S. Gowda</title>
    <style>
        /* Global Styles & Reset */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0b111e;
            color: #ffffff;
            padding: 40px 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 60px;
        }

        .container {
            width: 100%;
            max-width: 900px;
            background-color: #0f172a;
            border-radius: 12px;
            padding: 40px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
        }

        /* Section 1: Hero / Home Page */
        .hero-section {
            display: grid;
            grid-template-columns: 1.2fr 0.8fr;
            gap: 40px;
            align-items: center;
        }

        .hero-text h3 {
            color: #38bdf8;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 12px;
        }

        .hero-text h1 {
            font-size: 42px;
            line-height: 1.2;
            margin-bottom: 20px;
            font-weight: 700;
        }

        .hero-text p {
            color: #94a3b8;
            font-size: 16px;
            line-height: 1.6;
            margin-bottom: 30px;
        }

        .btn-group {
            display: flex;
            flex-direction: column;
            gap: 12px;
            max-width: 200px;
        }

        .btn {
            display: inline-block;
            padding: 12px 20px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: 600;
            text-align: center;
            font-size: 14px;
            transition: all 0.3s ease;
        }

        .btn-primary {
            background-color: #38bdf8;
            color: #0f172a;
        }

        .btn-primary:hover {
            background-color: #0ea5e9;
        }

        .btn-secondary {
            background-color: transparent;
            color: #ffffff;
            border: 1px solid #334155;
        }

        .btn-secondary:hover {
            background-color: #1e293b;
        }

        .hero-image-box {
            position: relative;
            background-color: #1e293b;
            border-radius: 12px;
            overflow: hidden;
            aspect-ratio: 4/5;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        /* Section 2: Education & Skills */
        .edu-skills-section {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 50px;
        }

        .section-title {
            font-size: 14px;
            color: #38bdf8;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 8px;
        }

        .section-heading {
            font-size: 32px;
            margin-bottom: 16px;
        }

        .section-desc {
            color: #94a3b8;
            margin-bottom: 30px;
            font-size: 14px;
        }

        .edu-card {
            background-color: #1e293b;
            padding: 24px;
            border-radius: 8px;
            border-left: 4px solid #38bdf8;
        }

        .edu-date {
            color: #38bdf8;
            font-size: 12px;
            font-weight: 600;
            margin-bottom: 8px;
        }

        .edu-card h4 {
            font-size: 20px;
            margin-bottom: 8px;
        }

        .edu-card p {
            color: #94a3b8;
            font-size: 14px;
            line-height: 1.5;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 16px;
        }

        .skill-item {
            background-color: #1e293b;
            padding: 16px;
            border-radius: 8px;
            display: flex;
            flex-direction: column;
            gap: 4px;
        }

        .skill-name {
            font-weight: 600;
            font-size: 15px;
        }

        .skill-level {
            font-size: 12px;
            color: #94a3b8;
        }

        /* Section 3: Learning Paths / Certificates */
        .cert-section {
            display: grid;
            grid-template-columns: 0.8fr 1.2fr;
            gap: 40px;
        }

        .cert-list {
            display: flex;
            flex-direction: column;
            gap: 16px;
        }

        .cert-row {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #1e293b;
            border-radius: 8px;
            border-left: 4px solid transparent;
            transition: all 0.3s ease;
        }

        .cert-row:hover {
            border-left-color: #38bdf8;
            background-color: #273549;
        }

        .cert-info h4 {
            font-size: 16px;
            margin-bottom: 4px;
        }

        .cert-info p {
            font-size: 12px;
            color: #94a3b8;
        }

        .cert-number {
            font-size: 18px;
            font-weight: bold;
            color: #334155;
        }

        .cert-row:hover .cert-number {
            color: #38bdf8;
        }

        /* Responsive Layout Optimization */
        @media (max-width: 768px) {
            .hero-section, .edu-skills-section, .cert-section {
                grid-template-columns: 1fr;
            }
            .hero-image-box {
                max-width: 320px;
                margin: 0 auto;
            }
        }
    </style>

    <!-- SCREENSHOT 1: HOME PAGE -->
    <section class="container hero-section">
        <div class="hero-text">
            <h3>A Little Introduction</h3>
            <h1>Hello, I'm<br><span style="color: #38bdf8;">Janhavi S. Gowda.</span></h1>
            <p>A BCA student at STG First Grade College, Chinakurali, learning through web, Python, database, and Android projects.</p>
            <div class="btn-group">
                <a href="#" class="btn btn-primary">Explore projects &rarr;</a>
                <a href="#" class="btn btn-secondary">Download resume &darr;</a>
                <a href="#" class="btn btn-secondary">Write me an email &nearr;</a>
            </div>
        </div>
        <div class="hero-image-box">
            <!-- Placeholder to replicate user image frame -->
            <span style="color: #475569; font-size: 14px;">[ Image Placeholder ]</span>
        </div>
    </section>

    <!-- SCREENSHOT 2: EDUCATION AND SKILLS -->
    <section class="container edu-skills-section">
        <div>
            <div class="section-title">Where I'm Learning</div>
            <div class="section-heading">Education.</div>
            <div class="section-desc">One place, a lot of possibility.</div>
            
            <div class="edu-card">
                <div class="edu-date">2024 - 2027 • CURRENTLY PURSUING</div>
                <h4>Bachelor of Computer Applications</h4>
                <p>STG First Grade College<br>Chinakurali, Mandya</p>
                <p style="margin-top: 12px; font-size: 13px; color: #38bdf8;">Focus: Web Development, SQL & MongoDB</p>
            </div>
        </div>

        <div>
            <div class="section-title">Tools & Technology</div>
            <div class="section-heading">Skills I work with.</div>
            <div class="section-desc">A snapshot of the skills I'm learning and applying in projects.</div>
            
            <div class="skills-grid">
                <div class="skill-item"><span class="skill-name">HTML</span><span class="skill-level">Working Knowledge</span></div>
                <div class="skill-item"><span class="skill-name">CSS</span><span class="skill-level">Working Knowledge</span></div>
                <div class="skill-item"><span class="skill-name">JavaScript</span><span class="skill-level">Working Knowledge</span></div>
                <div class="skill-item"><span class="skill-name">Python</span><span class="skill-level">Working Knowledge</span></div>
                <div class="skill-item"><span class="skill-name">DBMS</span><span class="skill-level">Working Knowledge</span></div>
                <div class="skill-item"><span class="skill-name">SQL</span><span class="skill-level">Working Knowledge</span></div>
            </div>
        </div>
    </section>

    <!-- SCREENSHOT 3: LEARNING PATHS -->
    <section class="container cert-section">
        <div>
            <div class="section-title">Learning Paths</div>
            <div class="section-heading">Certificates to explore.</div>
            <div class="section-desc">Suggested BCA related courses—not certificates already earned.</div>
        </div>

        <div class="cert-list">
            <div class="cert-row">
                <div class="cert-info">
                    <h4>Python Programming</h4>
                    <p>Build basic foundation in Python, problem solving, and data structures.</p>
                </div>
                <div class="cert-number">01</div>
            </div>
            <div class="cert-row">
                <div class="cert-info">
                    <h4>Web Development</h4>
                    <p>Strengthen HTML, CSS, JavaScript, and responsive website skills.</p>
                </div>
                <div class="cert-number">02</div>
            </div>
            <div class="cert-row">
                <div class="cert-info">
                    <h4>SQL & Database Management</h4>
                    <p>Practice relational data modeling, SQL queries, and database concepts.</p>
                </div>
                <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website Report - Screenshots</title>
    <style>
        :root {
            --bg-dark: #0d151c;
            --bg-light-green: #e2e9e1;
            --text-light: #ffffff;
            --text-muted: #8ba2b5;
            --text-dark: #1c2d37;
            --border-color: #334e68;
            --accent-green: #52b788;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #ffffff;
            color: #333333;
            margin: 0;
            padding: 40px 20px;
            display: flex;
            justify-content: center;
        }

        .report-page {
            max-width: 800px;
            width: 100%;
            background: #ffffff;
        }

        /* Header Styles */
        .report-header {
            border-bottom: 2px solid #e0e0e0;
            padding-bottom: 10px;
            margin-bottom: 30px;
        }

        .report-title {
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: #666666;
            margin: 0;
        }

        .section-title {
            font-size: 24px;
            font-weight: bold;
            color: #000000;
            margin: 20px 0;
        }

        .screenshot-label {
            font-size: 14px;
            color: #444444;
            margin: 25px 0 15px 0;
            font-weight: 500;
        }

        /* Common Mockup Container */
        .mockup-container {
            display: flex;
            justify-content: center;
            margin-bottom: 40px;
        }

        /* Screenshot 4: Featured Projects Grid */
        .projects-grid {
            background-color: var(--bg-dark);
            color: var(--text-light);
            width: 380px;
            padding: 25px;
            border-radius: 4px;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            font-size: 11px;
        }

        .grid-header {
            grid-column: span 2;
        }

        .grid-header h3 {
            font-size: 18px;
            margin: 0 0 5px 0;
            font-weight: 600;
        }

        .grid-header p {
            color: var(--text-muted);
            margin: 0;
            font-size: 10px;
            line-height: 1.4;
        }

        .project-card {
            border-top: 1px solid var(--border-color);
            padding-top: 10px;
            position: relative;
        }

        .project-num {
            position: absolute;
            right: 0;
            top: 10px;
            color: var(--text-muted);
            font-weight: bold;
        }

        .project-card h4 {
            margin: 0 0 8px 0;
            font-size: 12px;
            color: var(--text-light);
        }

        .project-card p {
            color: var(--text-muted);
            margin: 0 0 10px 0;
            line-height: 1.4;
            font-size: 9.5px;
        }

        .tags {
            display: flex;
            gap: 5px;
            flex-wrap: wrap;
        }

        .tag {
            background: rgba(255,255,255,0.05);
            padding: 2px 6px;
            border-radius: 3px;
            font-size: 8px;
            color: var(--text-muted);
        }

        /* Screenshot 5: Resume & Contact split section */
        .resume-contact-split {
            width: 430px;
            display: grid;
            grid-template-columns: 1fr 1.2fr;
            border-radius: 4px;
            overflow: hidden;
        }

        .left-panel {
            background-color: var(--bg-dark);
            color: var(--text-light);
            padding: 30px 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .panel-tag {
            font-size: 8px;
            text-transform: uppercase;
            color: var(--text-muted);
            letter-spacing: 1px;
            margin-bottom: 10px;
        }

        .left-panel h3 {
            font-size: 18px;
            margin: 0 0 10px 0;
            line-height: 1.3;
        }

        .left-panel p {
            color: var(--text-muted);
            font-size: 10px;
            line-height: 1.4;
            margin: 0 0 20px 0;
        }

        .btn-download {
            background-color: var(--accent-green);
            color: var(--bg-dark);
            padding: 8px 12px;
            border: none;
            border-radius: 20px;
            font-size: 9px;
            font-weight: bold;
            cursor: pointer;
            width: fit-content;
            margin-bottom: 10px;
        }

        .link-copy {
            color: var(--text-muted);
            font-size: 9px;
            text-decoration: none;
        }

        .right-panel {
            background-color: var(--bg-light-green);
            color: var(--text-dark);
            padding: 30px 25px;
            display: flex;
            flex-direction: column;
        }

        .right-panel h3 {
            font-size: 22px;
            margin: 0 0 15px 0;
            line-height: 1.2;
            font-weight: 500;
        }

        .right-panel p {
            font-size: 11px;
            line-height: 1.4;
            margin: 0 0 15px 0;
        }

        .email-display {
            font-weight: bold;
            font-size: 11px;
            margin-bottom: 15px;
        }

        .social-note {
            font-size: 9px;
            color: #556655;
            margin-bottom: 20px;
            line-height: 1.3;
        }

        .btn-email {
            background-color: var(--bg-dark);
            color: var(--text-light);
            padding: 10px 16px;
            border: none;
            border-radius: 20px;
            font-size: 10px;
            cursor: pointer;
            width: fit-content;
            margin-top: auto;
        }

        /* Screenshot 6: Contact Form */
        .contact-form-container {
            background-color: var(--bg-dark);
            color: var(--text-light);
            width: 260px;
            padding: 30px 25px;
            border-radius: 4px;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-group label {
            display: block;
            font-size: 10px;
            color: var(--text-muted);
            margin-bottom: 5px;
        }

        .form-group input, .form-group textarea {
            width: 100%;
            background: transparent;
            border: none;
            border-bottom: 1px solid var(--border-color);
            color: var(--text-light);
            padding: 4px 0;
            font-size: 11px;
            box-sizing: border-box;
        }

        .form-group input::placeholder, .form-group textarea::placeholder {
            color: rgba(255,255,255,0.2);
        }

        .form-note {
            font-size: 8px;
            color: var(--text-muted);
            text-align: center;
            margin-top: 15px;
            line-height: 1.3;
        }

        .btn-submit {
            background-color: var(--accent-green);
            color: var(--bg-dark);
            width: 100%;
            padding: 10px;
            border: none;
            border-radius: 20px;
            font-size: 10px;
            font-weight: bold;
            cursor: pointer;
            margin-top: 15px;
        }

        /* Footer Page Number */
        .report-footer {
            text-align: center;
            font-size: 12px;
            color: #666666;
            margin-top: 50px;
            border-top: 1px solid #eeeeee;
            padding-top: 15px;
        }
    </style>
</head>
<body>

    <div class="report-page">
        <!-- Header Section -->
        <div class="report-header">
            <h1 class="report-title">Portfolio Website Report</h1>
        </div>

        <h2 class="section-title">7. SCREENSHOTS</h2>

        <!-- Screenshot 4 -->
        <div class="screenshot-label">Screenshot 4 · Featured Projects</div>
        <div class="mockup-container">
            <div class="projects-grid">
                <div class="grid-header">
                    <h3>Featured projects.</h3>
                    <p>A few projects across web development, Python, and Android.</p>
                </div>
                
                <div class="project-card">
                    <span class="project-num">01</span>
                    <h4>Personal Portfolio</h4>
                    <p>A responsive portfolio introducing my education, skills, projects, and contact details.</p>
                    <div class="tags">
                        <span class="tag">HTML</span>
                        <span class="tag">CSS</span>
                        <span class="tag">JavaScript</span>
                    </div>
                </div>

                <div class="project-card">
                    <span class="project-num">03</span>
                    <h4>Classroom Automation System</h4>
                    <p>A computer vision project that detects classroom occupancy and caps control lights and fans through an Arduino relay system.</p>
                    <div class="tags">
                        <span class="tag">Python</span>
                        <span class="tag">OpenCV</span>
                        <span class="tag">Arduino</span>
                    </div>
                </div>

                <div class="project-card">
                    <span class="project-num">02</span>
                    <h4>ReUseMarket</h4>
                    <p>A localized marketplace web concept for browsing, selling, and discovering pre-owned goods online.</p>
                    <div class="tags">
                        <span class="tag">Node.js</span>
                        <span class="tag">Express</span>
                        
