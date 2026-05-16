<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stronger Bones Exercise Physiology | Osteoporosis Exercise Programs for Adults 50+</title>
    <meta name="description" content="Evidence-based exercise programs for adults 50+ with osteoporosis. Improve bone density, strength, and balance. Reduce falls risk with Accredited Exercise Physiologists in Geelong/Melbourne.">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #1e5f74;
            --primary-dark: #133d4a;
            --primary-light: #2d8a9e;
            --accent: #e8a838;
            --accent-hover: #d49730;
            --text: #2d3748;
            --text-light: #4a5568;
            --bg: #ffffff;
            --bg-alt: #f7f9fb;
            --bg-dark: #1a202c;
            --success: #48bb78;
            --border: #e2e8f0;
            --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
            --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            --radius: 12px;
            --radius-sm: 8px;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            color: var(--text);
            line-height: 1.6;
            background: var(--bg);
        }

        h1, h2, h3, h4 {
            font-family: 'Playfair Display', Georgia, serif;
            line-height: 1.2;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 24px;
        }

        /* Navigation */
        .nav {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            z-index: 1000;
            border-bottom: 1px solid var(--border);
        }

        .nav-inner {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 16px 24px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary);
            text-decoration: none;
        }

        .logo span {
            color: var(--accent);
        }

        .nav-links {
            display: flex;
            gap: 32px;
            list-style: none;
        }

        .nav-links a {
            color: var(--text);
            text-decoration: none;
            font-weight: 500;
            font-size: 0.95rem;
            transition: color 0.2s;
        }

        .nav-links a:hover {
            color: var(--primary);
        }

        .nav-cta {
            background: var(--accent);
            color: white;
            padding: 10px 20px;
            border-radius: var(--radius-sm);
            text-decoration: none;
            font-weight: 600;
            font-size: 0.9rem;
            transition: background 0.2s;
        }

        .nav-cta:hover {
            background: var(--accent-hover);
        }

        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            font-size: 1.5rem;
            cursor: pointer;
            color: var(--text);
        }

        /* Hero Section */
        .hero {
            padding: 160px 0 100px;
            background: linear-gradient(135deg, var(--bg-alt) 0%, #e8f4f8 100%);
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: -50%;
            right: -20%;
            width: 60%;
            height: 150%;
            background: radial-gradient(circle, rgba(30, 95, 116, 0.08) 0%, transparent 70%);
            pointer-events: none;
        }

        .hero-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
        }

        .hero-text h1 {
            font-size: 3.5rem;
            color: var(--primary-dark);
            margin-bottom: 8px;
        }

        .hero-text h1 span {
            color: var(--accent);
        }

        .hero-subtitle {
            font-size: 1.5rem;
            color: var(--primary);
            margin-bottom: 24px;
            font-weight: 500;
        }

        .hero-description {
            font-size: 1.15rem;
            color: var(--text-light);
            margin-bottom: 32px;
            max-width: 500px;
        }

        .hero-cta {
            display: flex;
            gap: 16px;
            flex-wrap: wrap;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 16px 32px;
            border-radius: var(--radius-sm);
            font-weight: 600;
            font-size: 1rem;
            text-decoration: none;
            transition: all 0.2s;
            cursor: pointer;
            border: none;
        }

        .btn-primary {
            background: var(--accent);
            color: white;
        }

        .btn-primary:hover {
            background: var(--accent-hover);
            transform: translateY(-2px);
            box-shadow: var(--shadow-lg);
        }

        .btn-secondary {
            background: white;
            color: var(--primary);
            border: 2px solid var(--primary);
        }

        .btn-secondary:hover {
            background: var(--primary);
            color: white;
        }

        .hero-image {
            position: relative;
        }

        .hero-image-placeholder {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
            border-radius: var(--radius);
            padding: 40px;
            color: white;
            text-align: center;
            aspect-ratio: 4/3;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            box-shadow: var(--shadow-lg);
        }

        .hero-image-placeholder .icon {
            font-size: 4rem;
            margin-bottom: 16px;
        }

        .hero-stats {
            display: flex;
            gap: 40px;
            margin-top: 48px;
            padding-top: 32px;
            border-top: 1px solid var(--border);
        }

        .stat {
            text-align: center;
        }

        .stat-number {
            font-size: 2rem;
            font-weight: 700;
            color: var(--primary);
            font-family: 'Playfair Display', serif;
        }

        .stat-label {
            font-size: 0.9rem;
            color: var(--text-light);
        }

        /* Section Styles */
        section {
            padding: 100px 0;
        }

        .section-header {
            text-align: center;
            max-width: 700px;
            margin: 0 auto 60px;
        }

        .section-header h2 {
            font-size: 2.5rem;
            color: var(--primary-dark);
            margin-bottom: 16px;
        }

        .section-header p {
            font-size: 1.1rem;
            color: var(--text-light);
        }

        /* About Section */
        .about {
            background: var(--bg);
        }

        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 80px;
            align-items: center;
        }

        .about-image {
            background: linear-gradient(135deg, var(--bg-alt) 0%, #e8f4f8 100%);
            border-radius: var(--radius);
            padding: 40px;
            text-align: center;
        }

        .team-icons {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            justify-items: center;
            gap: 24px 32px;
            margin-bottom: 24px;
            max-width: 320px;
            margin-left: auto;
            margin-right: auto;
        }

        .team-member {
            text-align: center;
        }

        .team-avatar {
            width: 80px;
            height: 80px;
            background: var(--primary);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 12px;
            font-size: 2rem;
        }

        .team-member h4 {
            font-family: 'Inter', sans-serif;
            font-size: 1rem;
            color: var(--text);
        }

        .team-member p {
            font-size: 0.85rem;
            color: var(--text-light);
        }

        .about-content h2 {
            font-size: 2.2rem;
            color: var(--primary-dark);
            margin-bottom: 24px;
        }

        .about-content p {
            color: var(--text-light);
            margin-bottom: 24px;
            font-size: 1.05rem;
        }

        .benefits-list {
            list-style: none;
        }

        .benefits-list li {
            display: flex;
            align-items: flex-start;
            gap: 12px;
            padding: 12px 0;
            border-bottom: 1px solid var(--border);
        }

        .benefits-list li:last-child {
            border-bottom: none;
        }

        .check-icon {
            color: var(--success);
            font-size: 1.2rem;
            flex-shrink: 0;
        }

        /* Why Exercise Section */
        .why-exercise {
            background: var(--bg-alt);
        }

        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 24px;
        }

        .benefit-card {
            background: white;
            padding: 32px 24px;
            border-radius: var(--radius);
            text-align: center;
            box-shadow: var(--shadow);
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .benefit-card:hover {
            transform: translateY(-4px);
            box-shadow: var(--shadow-lg);
        }

        .benefit-icon {
            width: 64px;
            height: 64px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 20px;
            font-size: 1.8rem;
        }

        .benefit-card h3 {
            font-family: 'Inter', sans-serif;
            font-size: 1.1rem;
            font-weight: 600;
            color: var(--text);
            margin-bottom: 12px;
        }

        .benefit-card p {
            font-size: 0.95rem;
            color: var(--text-light);
        }

        /* Program Section */
        .program {
            background: var(--bg);
        }

        .program-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: start;
        }

        .program-details {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            border-radius: var(--radius);
            padding: 48px;
            color: white;
        }

        .program-details h3 {
            font-size: 1.8rem;
            margin-bottom: 24px;
        }

        .program-features {
            list-style: none;
        }

        .program-features li {
            display: flex;
            align-items: flex-start;
            gap: 16px;
            padding: 16px 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
        }

        .program-features li:last-child {
            border-bottom: none;
        }

        .program-features .icon {
            font-size: 1.3rem;
            flex-shrink: 0;
        }

        .program-goal {
            background: rgba(255, 255, 255, 0.15);
            border-radius: var(--radius-sm);
            padding: 24px;
            margin-top: 24px;
            text-align: center;
        }

        .program-goal h4 {
            font-family: 'Inter', sans-serif;
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 8px;
            opacity: 0.9;
        }

        .program-goal p {
            font-size: 1.1rem;
            font-weight: 600;
        }

        .who-we-help h3 {
            font-size: 1.8rem;
            color: var(--primary-dark);
            margin-bottom: 24px;
        }

        .criteria-list {
            list-style: none;
            margin-bottom: 32px;
        }

        .criteria-list li {
            display: flex;
            align-items: center;
            gap: 12px;
            padding: 16px 0;
            border-bottom: 1px solid var(--border);
            font-size: 1.05rem;
        }

        .criteria-list .icon {
            color: var(--primary);
            font-size: 1.3rem;
        }

        /* Delivery Methods Grid (NEW) */
        .delivery-section {
            background: var(--bg-alt);
        }

        .delivery-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 24px;
            margin-top: 40px;
        }

        .delivery-card {
            background: white;
            padding: 28px 24px;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            transition: transform 0.2s, box-shadow 0.2s;
            display: flex;
            flex-direction: column;
        }

        .delivery-card:hover {
            transform: translateY(-4px);
            box-shadow: var(--shadow-lg);
        }

        .delivery-icon {
            width: 56px;
            height: 56px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 20px;
            font-size: 1.5rem;
        }

        .delivery-card h3 {
            font-family: 'Inter', sans-serif;
            font-size: 1.1rem;
            font-weight: 600;
            color: var(--text);
            margin-bottom: 8px;
        }

        .delivery-frequency {
            font-size: 0.85rem;
            color: var(--accent);
            font-weight: 600;
            margin-bottom: 12px;
        }

        .delivery-card p {
            font-size: 0.95rem;
            color: var(--text-light);
            flex-grow: 1;
        }

        /* Phase Timeline (NEW) */
        .phases-section {
            background: var(--bg);
        }

        .phases-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 24px;
            margin-top: 40px;
            position: relative;
        }

        .phase-card {
            background: white;
            border-radius: var(--radius);
            padding: 32px 24px;
            box-shadow: var(--shadow);
            border-top: 4px solid var(--primary);
            position: relative;
        }

        .phase-card:nth-child(1) { border-top-color: #2d8a9e; }
        .phase-card:nth-child(2) { border-top-color: #1e5f74; }
        .phase-card:nth-child(3) { border-top-color: #e8a838; }
        .phase-card:nth-child(4) { border-top-color: #48bb78; }

        .phase-number {
            display: inline-block;
            background: var(--primary);
            color: white;
            font-weight: 700;
            font-size: 0.8rem;
            padding: 4px 12px;
            border-radius: 20px;
            margin-bottom: 12px;
            letter-spacing: 1px;
        }

        .phase-card:nth-child(2) .phase-number { background: #1e5f74; }
        .phase-card:nth-child(3) .phase-number { background: #e8a838; }
        .phase-card:nth-child(4) .phase-number { background: #48bb78; }

        .phase-card h3 {
            font-family: 'Inter', sans-serif;
            font-size: 1.15rem;
            font-weight: 600;
            color: var(--primary-dark);
            margin-bottom: 8px;
        }

        .phase-weeks {
            font-size: 0.9rem;
            color: var(--text-light);
            font-weight: 500;
            margin-bottom: 16px;
        }

        .phase-card ul {
            list-style: none;
            padding: 0;
        }

        .phase-card ul li {
            padding: 8px 0;
            font-size: 0.92rem;
            color: var(--text-light);
            padding-left: 20px;
            position: relative;
            border-bottom: 1px solid var(--border);
        }

        .phase-card ul li:last-child {
            border-bottom: none;
        }

        .phase-card ul li::before {
            content: '→';
            position: absolute;
            left: 0;
            color: var(--accent);
            font-weight: 700;
        }

        /* Outcome Measures Section (NEW) */
        .outcomes-section {
            background: var(--bg-alt);
        }

        .outcomes-table-wrap {
            background: white;
            border-radius: var(--radius);
            overflow: hidden;
            box-shadow: var(--shadow);
            margin-top: 40px;
        }

        .outcomes-table {
            width: 100%;
            border-collapse: collapse;
        }

        .outcomes-table thead {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: white;
        }

        .outcomes-table th {
            padding: 18px 20px;
            text-align: left;
            font-weight: 600;
            font-size: 0.95rem;
        }

        .outcomes-table td {
            padding: 16px 20px;
            border-bottom: 1px solid var(--border);
            font-size: 0.95rem;
            color: var(--text);
        }

        .outcomes-table tbody tr:last-child td {
            border-bottom: none;
        }

        .outcomes-table tbody tr:hover {
            background: var(--bg-alt);
        }

        .outcomes-table td:first-child {
            font-weight: 600;
            color: var(--primary-dark);
        }

        /* Contact Section */
        .contact {
            background: linear-gradient(135deg, var(--primary-dark) 0%, var(--primary) 100%);
            color: white;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
        }

        .contact-info h2 {
            font-size: 2.2rem;
            margin-bottom: 24px;
        }

        .contact-info p {
            opacity: 0.9;
            margin-bottom: 32px;
            font-size: 1.1rem;
        }

        .contact-details {
            list-style: none;
        }

        .contact-details li {
            display: flex;
            align-items: center;
            gap: 16px;
            padding: 16px 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
            font-size: 1.05rem;
        }

        .contact-details .icon {
            font-size: 1.3rem;
            width: 40px;
            height: 40px;
            background: rgba(255, 255, 255, 0.15);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .contact-form {
            background: white;
            border-radius: var(--radius);
            padding: 40px;
        }

        .contact-form h3 {
            color: var(--primary-dark);
            font-size: 1.5rem;
            margin-bottom: 24px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            font-weight: 500;
            color: var(--text);
            margin-bottom: 8px;
            font-size: 0.95rem;
        }

        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 14px 16px;
            border: 2px solid var(--border);
            border-radius: var(--radius-sm);
            font-size: 1rem;
            font-family: inherit;
            transition: border-color 0.2s;
        }

        .form-group input:focus,
        .form-group textarea:focus,
        .form-group select:focus {
            outline: none;
            border-color: var(--primary);
        }

        .form-group textarea {
            resize: vertical;
            min-height: 120px;
        }

        /* Footer */
        .footer {
            background: var(--bg-dark);
            color: white;
            padding: 60px 0 30px;
        }

        .footer-grid {
            display: grid;
            grid-template-columns: 2fr 1fr 1fr 1fr;
            gap: 48px;
            margin-bottom: 48px;
        }

        .footer-brand .logo {
            color: white;
            font-size: 1.8rem;
            margin-bottom: 16px;
            display: inline-block;
        }

        .footer-brand p {
            opacity: 0.7;
            font-size: 0.95rem;
            line-height: 1.7;
        }

        .footer-links h4 {
            font-family: 'Inter', sans-serif;
            font-size: 1rem;
            font-weight: 600;
            margin-bottom: 20px;
        }

        .footer-links ul {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 12px;
        }

        .footer-links a {
            color: rgba(255, 255, 255, 0.7);
            text-decoration: none;
            font-size: 0.95rem;
            transition: color 0.2s;
        }

        .footer-links a:hover {
            color: white;
        }

        .footer-bottom {
            padding-top: 30px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            text-align: center;
            font-size: 0.9rem;
            opacity: 0.6;
        }

        /* Mobile Menu */
        .mobile-menu {
            display: none;
            position: fixed;
            top: 72px;
            left: 0;
            right: 0;
            background: white;
            padding: 24px;
            box-shadow: var(--shadow-lg);
            z-index: 999;
        }

        .mobile-menu.active {
            display: block;
        }

        .mobile-menu a {
            display: block;
            padding: 12px 0;
            color: var(--text);
            text-decoration: none;
            font-weight: 500;
            border-bottom: 1px solid var(--border);
        }

        .mobile-menu .nav-cta {
            display: block;
            text-align: center;
            margin-top: 16px;
        }

        /* Responsive Design */
        @media (max-width: 1024px) {
            .hero-content,
            .about-grid,
            .program-content,
            .contact-grid {
                grid-template-columns: 1fr;
                gap: 48px;
            }

            .benefits-grid,
            .delivery-grid,
            .phases-grid {
                grid-template-columns: repeat(2, 1fr);
            }

            .footer-grid {
                grid-template-columns: repeat(2, 1fr);
            }

            .outcomes-table {
                font-size: 0.85rem;
            }

            .outcomes-table th,
            .outcomes-table td {
                padding: 12px 14px;
            }
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }

            .mobile-menu-btn {
                display: block;
            }

            .hero-text h1 {
                font-size: 2.5rem;
            }

            .hero-stats {
                flex-direction: column;
                gap: 24px;
            }

            .benefits-grid,
            .delivery-grid,
            .phases-grid {
                grid-template-columns: 1fr;
            }

            .section-header h2 {
                font-size: 2rem;
            }

            .footer-grid {
                grid-template-columns: 1fr;
            }

            .hero-cta {
                flex-direction: column;
            }

            .btn {
                width: 100%;
                justify-content: center;
            }

            .outcomes-table-wrap {
                overflow-x: auto;
            }

            .outcomes-table {
                min-width: 600px;
            }
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="nav">
        <div class="nav-inner">
            <a href="#" class="logo">Stronger<span>Bones</span></a>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#program">Our Program</a></li>
                <li><a href="#delivery">How It Works</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <a href="#contact" class="nav-cta">Book Assessment</a>
            <button class="mobile-menu-btn" onclick="toggleMobileMenu()">☰</button>
        </div>
    </nav>

    <!-- Mobile Menu -->
    <div class="mobile-menu" id="mobileMenu">
        <a href="#" onclick="toggleMobileMenu()">Home</a>
        <a href="#about" onclick="toggleMobileMenu()">About</a>
        <a href="#program" onclick="toggleMobileMenu()">Our Program</a>
        <a href="#delivery" onclick="toggleMobileMenu()">How It Works</a>
        <a href="#contact" onclick="toggleMobileMenu()">Contact</a>
        <a href="#contact" class="nav-cta" onclick="toggleMobileMenu()">Book Assessment</a>
    </div>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <div class="hero-text">
                    <h1>Stronger Bones.<br><span>Better Balance.</span><br>Fewer Falls.</h1>
                    <p class="hero-subtitle">Exercise Physiology for Adults 50+</p>
                    <p class="hero-description">Evidence-based exercise programs designed specifically for adults with osteoporosis or osteopenia. Build bone strength, improve balance, and reduce your risk of falls.</p>
                    <div class="hero-cta">
                        <a href="#contact" class="btn btn-primary">👉 Book Your Initial Assessment</a>
                        <a href="#program" class="btn btn-secondary">Learn About Our Program</a>
                    </div>
                    <div class="hero-stats">
                        <div class="stat">
                            <div class="stat-number">12</div>
                            <div class="stat-label">Month Program</div>
                        </div>
                        <div class="stat">
                            <div class="stat-number">≥3%</div>
                            <div class="stat-label">BMD Improvement Goal</div>
                        </div>
                        <div class="stat">
                            <div class="stat-number">50+</div>
                            <div class="stat-label">Age Group Focus</div>
                        </div>
                    </div>
                </div>
                <div class="hero-image">
                    <div class="hero-image-placeholder">
                        <div class="icon">🏋️</div>
                        <h3>Supervised Training</h3>
                        <p>Safe, effective exercises with Accredited Exercise Physiologists</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about" id="about">
        <div class="container">
            <div class="about-grid">
                <div class="about-image">
                    <div class="team-icons">
                        <div class="team-member">
                            <div class="team-avatar">👨‍⚕️</div>
                            <h4>Tyrone</h4>
                            <p>Exercise Physiologist</p>
                        </div>
                        <div class="team-member">
                            <div class="team-avatar">👨‍⚕️</div>
                            <h4>John</h4>
                            <p>Exercise Physiologist</p>
                        </div>
                        <div class="team-member">
                            <div class="team-avatar">👨‍⚕️</div>
                            <h4>Zac Powell</h4>
                            <p>Exercise Physiologist</p>
                        </div>
                        <div class="team-member">
                            <div class="team-avatar">👨‍⚕️</div>
                            <h4>Aidan Frai</h4>
                            <p>Exercise Physiologist</p>
                        </div>
                    </div>
                    <p style="color: var(--text-light); font-size: 0.95rem;">Accredited Exercise Physiologists specialising in osteoporosis management</p>
                </div>
                <div class="about-content">
                    <h2>About Stronger Bones Exercise Physiology</h2>
                    <p>At Stronger Bones Exercise Physiology, our team of Accredited Exercise Physiologists — Tyrone, John, Zac Powell, and Aidan Frai — provide evidence-based exercise programs designed specifically for adults aged 50+ with osteoporosis or osteopenia.</p>
                    <p>Our programs are tailored to ensure safety and effectiveness, focusing on three key areas:</p>
                    <ul class="benefits-list">
                        <li>
                            <span class="check-icon">✓</span>
                            <div>
                                <strong>Bone Mineral Density (BMD)</strong><br>
                                <span style="color: var(--text-light);">Exercises that stimulate bone growth and slow bone loss</span>
                            </div>
                        </li>
                        <li>
                            <span class="check-icon">✓</span>
                            <div>
                                <strong>Strength & Muscle Mass</strong><br>
                                <span style="color: var(--text-light);">Resistance training to build functional strength</span>
                            </div>
                        </li>
                        <li>
                            <span class="check-icon">✓</span>
                            <div>
                                <strong>Balance & Fall Prevention</strong><br>
                                <span style="color: var(--text-light);">Targeted exercises to improve stability and confidence</span>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Exercise Section -->
    <section class="why-exercise">
        <div class="container">
            <div class="section-header">
                <h2>Why Exercise for Osteoporosis?</h2>
                <p>Regular, targeted exercise is one of the most effective ways to manage osteoporosis and reduce fracture risk.</p>
            </div>
            <div class="benefits-grid">
                <div class="benefit-card">
                    <div class="benefit-icon">🦴</div>
                    <h3>Improves Bone Strength</h3>
                    <p>Weight-bearing and resistance exercises stimulate bone formation and slow bone loss</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">🛡️</div>
                    <h3>Reduces Fracture Risk</h3>
                    <p>Stronger bones and better balance significantly lower your risk of fractures</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">⚖️</div>
                    <h3>Enhances Balance & Mobility</h3>
                    <p>Improved stability and coordination for safer daily movement</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">💪</div>
                    <h3>Builds Confidence</h3>
                    <p>Feel stronger and more confident in your daily activities</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Program Overview Section -->
    <section class="program" id="program">
        <div class="container">
            <div class="section-header">
                <h2>Our 12-Month Program</h2>
                <p>A comprehensive, evidence-based clinical program combining in-person assessments, telehealth consultations, and app-based exercise prescription — designed to reach you wherever you live.</p>
            </div>
            <div class="program-content">
                <div class="program-details">
                    <h3>What's Included</h3>
                    <ul class="program-features">
                        <li>
                            <span class="icon">📋</span>
                            <div>
                                <strong>3 Face-to-Face Assessments</strong><br>
                                Comprehensive in-person testing at initial visit (Week 1), mid-program (Week 26), and end-of-program (Week 52)
                            </div>
                        </li>
                        <li>
                            <span class="icon">💻</span>
                            <div>
                                <strong>Fortnightly Telehealth Consultations</strong><br>
                                1-on-1 Zoom video calls for exercise prescription, program reviews, and goal setting
                            </div>
                        </li>
                        <li>
                            <span class="icon">📱</span>
                            <div>
                                <strong>Physitrack Exercise App</strong><br>
                                Individualised exercise programs with video demonstrations and adherence tracking, updated every 4 weeks
                            </div>
                        </li>
                        <li>
                            <span class="icon">📞</span>
                            <div>
                                <strong>Phone Check-ins</strong><br>
                                Brief structured calls in alternating weeks for adherence support and safety screening
                            </div>
                        </li>
                        <li>
                            <span class="icon">📚</span>
                            <div>
                                <strong>12 Monthly Education Modules</strong><br>
                                Video and PDF content covering osteoporosis, nutrition, falls prevention, and self-management
                            </div>
                        </li>
                        <li>
                            <span class="icon">👥</span>
                            <div>
                                <strong>Monthly Group Telehealth Sessions</strong><br>
                                Small group sessions (8–10 clients) for community, peer support, and guided exercise
                            </div>
                        </li>
                        <li>
                            <span class="icon">📊</span>
                            <div>
                                <strong>Progress Reports to You & Your GP</strong><br>
                                Written summaries at Week 12, 26, and 52 with outcome measures and clinical recommendations
                            </div>
                        </li>
                    </ul>
                    <div class="program-goal">
                        <h4>🎯 Program Goal</h4>
                        <p>≥3% improvement in BMD + reduced falls risk</p>
                    </div>
                </div>
                <div class="who-we-help">
                    <h3>Who We Help</h3>
                    <ul class="criteria-list">
                        <li>
                            <span class="icon">👤</span>
                            Adults aged 50 and over
                        </li>
                        <li>
                            <span class="icon">🦴</span>
                            Diagnosed with osteoporosis or osteopenia
                        </li>
                        <li>
                            <span class="icon">⚠️</span>
                            History or risk of falls
                        </li>
                        <li>
                            <span class="icon">📄</span>
                            Referred by GP or specialist
                        </li>
                        <li>
                            <span class="icon">📍</span>
                            Living in regional areas (remote delivery available)
                        </li>
                    </ul>
                    <h4 style="margin-bottom: 16px; color: var(--primary-dark);">Ready to Get Started?</h4>
                    <a href="#contact" class="btn btn-primary">👉 Book Online</a>
                    <p style="margin-top: 16px; color: var(--text-light); font-size: 0.95rem;">Or ask your GP for a referral to our program. Medicare EPC and DVA referrals accepted.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Delivery Methods Section (NEW) -->
    <section class="delivery-section" id="delivery">
        <div class="container">
            <div class="section-header">
                <h2>How We Deliver Your Care</h2>
                <p>A blended service delivery model that combines the best of in-person clinical care with the convenience of telehealth and app-based support.</p>
            </div>
            <div class="delivery-grid">
                <div class="delivery-card">
                    <div class="delivery-icon">🏥</div>
                    <h3>Face-to-Face Assessment</h3>
                    <p class="delivery-frequency">3 visits over 12 months</p>
                    <p>Comprehensive in-person testing at regional hubs including DXA referrals, Berg Balance Scale, Four Square Step Test, grip strength, sit-to-stand, and timed up-and-go.</p>
                </div>
                <div class="delivery-card">
                    <div class="delivery-icon">💻</div>
                    <h3>Telehealth Consultations</h3>
                    <p class="delivery-frequency">Fortnightly (Weeks 2–52)</p>
                    <p>1-on-1 video consultations via Zoom for exercise prescription, program reviews, goal setting, and subjective reassessment from the comfort of your home.</p>
                </div>
                <div class="delivery-card">
                    <div class="delivery-icon">📱</div>
                    <h3>Physitrack App</h3>
                    <p class="delivery-frequency">Updated every 4 weeks</p>
                    <p>Individualised exercise programs delivered via the Physitrack app, with video demonstrations, sets/reps/load prescription, and adherence tracking.</p>
                </div>
                <div class="delivery-card">
                    <div class="delivery-icon">📞</div>
                    <h3>Phone Check-ins</h3>
                    <p class="delivery-frequency">Alternating weeks</p>
                    <p>Brief structured phone calls between telehealth sessions for adherence monitoring, barrier identification, motivational support, and safety screening.</p>
                </div>
                <div class="delivery-card">
                    <div class="delivery-icon">📚</div>
                    <h3>Education Modules</h3>
                    <p class="delivery-frequency">1 module per month</p>
                    <p>Pre-recorded video and written content covering osteoporosis, nutrition, falls prevention, medication interactions, and exercise self-management.</p>
                </div>
                <div class="delivery-card">
                    <div class="delivery-icon">👥</div>
                    <h3>Group Telehealth Sessions</h3>
                    <p class="delivery-frequency">Monthly (12 sessions)</p>
                    <p>Online group sessions (8–10 clients) for community building, peer support, Q&A, and guided exercise — fostering social connection for remote clients.</p>
                </div>
                <div class="delivery-card">
                    <div class="delivery-icon">📊</div>
                    <h3>Progress Reports</h3>
                    <p class="delivery-frequency">Weeks 12, 26 & 52</p>
                    <p>Written progress summaries emailed to you and your GP, including outcome measure results, adherence data, and clinical recommendations.</p>
                </div>
                <div class="delivery-card">
                    <div class="delivery-icon">📝</div>
                    <h3>Self-Monitoring Tools</h3>
                    <p class="delivery-frequency">Ongoing</p>
                    <p>Falls diary, exercise log (within Physitrack), and weekly symptom/pain tracker accessed via our website to support your self-management.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Phases Section (NEW) -->
    <section class="phases-section">
        <div class="container">
            <div class="section-header">
                <h2>Your 12-Month Journey</h2>
                <p>The program is structured into four distinct phases, each designed to build on the last — from establishing your baseline to becoming confident and independent in managing your bone health.</p>
            </div>
            <div class="phases-grid">
                <div class="phase-card">
                    <span class="phase-number">PHASE 1</span>
                    <h3>Onboarding & Baseline</h3>
                    <p class="phase-weeks">Weeks 1–4</p>
                    <ul>
                        <li>Initial face-to-face assessment</li>
                        <li>Full baseline testing (DXA, BBS, FSST)</li>
                        <li>Individualised program via Physitrack</li>
                        <li>First education module released</li>
                        <li>Home exercise environment review</li>
                    </ul>
                </div>
                <div class="phase-card">
                    <span class="phase-number">PHASE 2</span>
                    <h3>Building Foundation</h3>
                    <p class="phase-weeks">Weeks 5–12</p>
                    <ul>
                        <li>Fortnightly telehealth reviews</li>
                        <li>Progressive overload guidance</li>
                        <li>Technique refinement</li>
                        <li>First group session at Week 8</li>
                        <li>Telehealth reassessment at Week 12</li>
                    </ul>
                </div>
                <div class="phase-card">
                    <span class="phase-number">PHASE 3</span>
                    <h3>Progressive Development</h3>
                    <p class="phase-weeks">Weeks 13–38</p>
                    <ul>
                        <li>Continued progressive overload</li>
                        <li>Introduction of impact exercises</li>
                        <li>Monthly group telehealth sessions</li>
                        <li>Mid-program reassessment (Week 26)</li>
                        <li>Self-efficacy building focus</li>
                    </ul>
                </div>
                <div class="phase-card">
                    <span class="phase-number">PHASE 4</span>
                    <h3>Independence & Transition</h3>
                    <p class="phase-weeks">Weeks 39–52</p>
                    <ul>
                        <li>Reduced telehealth frequency</li>
                        <li>Self-management strategies</li>
                        <li>Maintenance goal-setting</li>
                        <li>Final reassessment at Week 52</li>
                        <li>Long-term discharge plan</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Outcome Measures Section (NEW) -->
    <section class="outcomes-section">
        <div class="container">
            <div class="section-header">
                <h2>How We Measure Your Progress</h2>
                <p>We use a comprehensive set of validated outcome measures to track your progress across bone health, balance, strength, mobility, and quality of life.</p>
            </div>
            <div class="outcomes-table-wrap">
                <table class="outcomes-table">
                    <thead>
                        <tr>
                            <th>Measure</th>
                            <th>Tool</th>
                            <th>What It Tracks</th>
                            <th>Reassessed At</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Bone Mineral Density</td>
                            <td>DXA (referred)</td>
                            <td>Bone strength (T-score)</td>
                            <td>Week 52</td>
                        </tr>
                        <tr>
                            <td>Static Balance</td>
                            <td>Berg Balance Scale</td>
                            <td>Falls risk (score /56)</td>
                            <td>Weeks 26, 52</td>
                        </tr>
                        <tr>
                            <td>Dynamic Balance</td>
                            <td>Four Square Step Test</td>
                            <td>Stepping speed (seconds)</td>
                            <td>Weeks 26, 52</td>
                        </tr>
                        <tr>
                            <td>Grip Strength</td>
                            <td>Hand Dynamometer</td>
                            <td>Functional strength (kg)</td>
                            <td>Weeks 26, 52</td>
                        </tr>
                        <tr>
                            <td>Lower Limb Strength</td>
                            <td>30-Second Sit-to-Stand</td>
                            <td>Leg strength & endurance (reps)</td>
                            <td>Weeks 26, 52</td>
                        </tr>
                        <tr>
                            <td>Functional Mobility</td>
                            <td>Timed Up-and-Go</td>
                            <td>Mobility & falls risk (seconds)</td>
                            <td>Weeks 26, 52</td>
                        </tr>
                        <tr>
                            <td>Quality of Life</td>
                            <td>EQ-5D-5L</td>
                            <td>Overall wellbeing (index value)</td>
                            <td>Weeks 12, 26, 52</td>
                        </tr>
                        <tr>
                            <td>Self-Efficacy</td>
                            <td>Osteoporosis Self-Efficacy Scale</td>
                            <td>Confidence in exercise (/100)</td>
                            <td>Weeks 12, 26, 52</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <div class="contact-grid">
                <div class="contact-info">
                    <h2>Get In Touch</h2>
                    <p>Ready to start your journey to stronger bones and better balance? Book your initial assessment today or reach out with any questions.</p>
                    <ul class="contact-details">
                        <li>
                            <span class="icon">📍</span>
                            Geelong / Melbourne
                        </li>
                        <li>
                            <span class="icon">📞</span>
                            Call Us: (03) XXXX XXXX
                        </li>
                        <li>
                            <span class="icon">📧</span>
                            info@strongerbones.com.au
                        </li>
                        <li>
                            <span class="icon">🌐</span>
                            Online Booking Available
                        </li>
                    </ul>
                </div>
                <div class="contact-form">
                    <h3>Book Your Assessment</h3>
                    <form>
                        <div class="form-group">
                            <label for="name">Full Name</label>
                            <input type="text" id="name" name="name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email Address</label>
                            <input type="email" id="email" name="email" required>
                        </div>
                        <div class="form-group">
                            <label for="phone">Phone Number</label>
                            <input type="tel" id="phone" name="phone" required>
                        </div>
                        <div class="form-group">
                            <label for="referral">How did you hear about us?</label>
                            <select id="referral" name="referral">
                                <option value="">Select an option</option>
                                <option value="gp">GP Referral</option>
                                <option value="specialist">Specialist Referral</option>
                                <option value="facebook">Facebook</option>
                                <option value="google">Google Search</option>
                                <option value="flyer">Flyer/Letter Drop</option>
                                <option value="community">Community Presentation</option>
                                <option value="friend">Friend/Family</option>
                                <option value="other">Other</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label for="message">Message (Optional)</label>
                            <textarea id="message" name="message" placeholder="Tell us about your health goals or any questions you have..."></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary" style="width: 100%;">Submit Booking Request</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-grid">
                <div class="footer-brand">
                    <a href="#" class="logo">Stronger<span>Bones</span></a>
                    <p>Evidence-based exercise programs for adults 50+ with osteoporosis. Improve bone density, strength, and balance with Accredited Exercise Physiologists.</p>
                </div>
                <div class="footer-links">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#program">Our Program</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-links">
                    <h4>Resources</h4>
                    <ul>
                        <li><a href="#delivery">How It Works</a></li>
                        <li><a href="#">GP Referral Form</a></li>
                        <li><a href="#">FAQs</a></li>
                    </ul>
                </div>
                <div class="footer-links">
                    <h4>Contact</h4>
                    <ul>
                        <li><a href="#">Geelong / Melbourne</a></li>
                        <li><a href="tel:">Call Us</a></li>
                        <li><a href="mailto:">Email Us</a></li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 Stronger Bones Exercise Physiology. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile Menu Toggle
        function toggleMobileMenu() {
            const menu = document.getElementById('mobileMenu');
            menu.classList.toggle('active');
        }

        // Smooth scroll for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                const href = this.getAttribute('href');
                if (href !== '#') {
                    const target = document.querySelector(href);
                    if (target) {
                        e.preventDefault();
                        const navHeight = document.querySelector('.nav').offsetHeight;
                        const targetPosition = target.offsetTop - navHeight - 20;
                        window.scrollTo({
                            top: targetPosition,
                            behavior: 'smooth'
                        });
                    }
                }
            });
        });

        // Form submission handling
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your booking request! We will be in touch within 24–48 hours to confirm your initial assessment.');
            this.reset();
        });

        // Navbar scroll effect
        window.addEventListener('scroll', function() {
            const nav = document.querySelector('.nav');
            if (window.scrollY > 50) {
                nav.style.boxShadow = '0 2px 10px rgba(0,0,0,0.1)';
            } else {
                nav.style.boxShadow = 'none';
            }
        });
    </script>
</body>
</html>
