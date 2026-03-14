# Royal-agency1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Royal Agency | Professional Female Hosting</title>
    <style>
        :root {
            --royal-blue: #002366;
            --gold: #D4AF37;
            --white: #ffffff;
            --light-gray: #f4f4f4;
            --dark: #1a1a1a;
        }

        * {
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Segoe UI', Roboto, Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: var(--light-gray);
            color: var(--dark);
        }

        /* Navigation */
        nav {
            background: var(--royal-blue);
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 3px solid var(--gold);
        }

        .logo {
            color: var(--gold);
            font-size: 24px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-size: 14px;
            font-weight: 500;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 35, 102, 0.85), rgba(0, 35, 102, 0.85)), url('https://images.unsplash.com/photo-1497366216548-37526070297c?auto=format&fit=crop&w=1200&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 100px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
            color: var(--gold);
            text-transform: uppercase;
        }

        .hero p {
            font-size: 22px;
            margin-bottom: 30px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }

        .cta-btn {
            background: var(--gold);
            color: var(--royal-blue);
            padding: 18px 40px;
            text-decoration: none;
            font-weight: bold;
            font-size: 20px;
            border-radius: 50px;
            transition: 0.3s;
            display: inline-block;
            box-shadow: 0 4px 15px rgba(212, 175, 55, 0.4);
        }

        .cta-btn:hover {
            background: white;
            transform: translateY(-3px);
        }

        /* Benefits Grid */
        .container {
            max-width: 1100px;
            margin: auto;
            padding: 60px 20px;
        }

        h2.section-title {
            text-align: center;
            color: var(--royal-blue);
            font-size: 32px;
            margin-bottom: 40px;
            position: relative;
        }

        h2.section-title::after {
            content: '';
            width: 60px;
            height: 3px;
            background: var(--gold);
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 12px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            border-top: 4px solid var(--gold);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            color: var(--royal-blue);
            margin-bottom: 15px;
        }

        /* Legal Sections */
        .legal-section {
            background: white;
            padding: 40px;
            border-radius: 10px;
            margin-top: 40px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }

        .legal-content {
            height: 250px;
            overflow-y: auto;
            border: 1px solid #eee;
            padding: 20px;
            background: #fafafa;
            font-size: 14px;
            color: #555;
        }

        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            padding: 50px 20px;
            text-align: center;
        }

        .footer-info p {
            margin: 5px 0;
            opacity: 0.8;
        }

        .footer-links {
            margin: 20px 0;
        }

        .footer-links a {
            color: var(--gold);
            text-decoration: none;
            margin: 0 10px;
        }

        @media (max-width: 768px) {
            .hero h1 { font-size: 32px; }
            .hero p { font-size: 18px; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">👑 Royal Agency</div>
        <div class="nav-links">
            <a href="#benefits">Benefits</a>
            <a href="#terms">Terms</a>
            <a href="#privacy">Privacy</a>
        </div>
    </nav>

    <section class="hero">
        <h1>Join Royal Agency</h1>
        <p>Start your professional streaming career today. Earn <strong>$20 - $50+ daily</strong> from the comfort of your home.</p>
        <a href="https://wa.me/917428132358" class="cta-btn">APPLY NOW ON WHATSAPP</a>
    </section>

    <div class="container" id="benefits">
        <h2 class="section-title">Why Choose Us?</h2>
        <div class="grid">
            <div class="card">
                <h3>🏠 Flexible Work</h3>
                <p>100% Work from home. You are the boss of your own schedule and timings.</p>
            </div>
            <div class="card">
                <h3>💰 Fast Payouts</h3>
                <p>Direct self-withdrawal to your Bank, USDT, or PayPal. No delays.</p>
            </div>
            <div class="card">
                <h3>🎓 Expert Training</h3>
                <p>New to streaming? We provide 1-on-1 coaching to help you reach your goals.</p>
            </div>
            <div class="card">
                <h3>📞 24/7 Support</h3>
                <p>Our dedicated management team is always here to assist our hosts.</p>
            </div>
        </div>
    </div>

    <div class="container" id="legal">
        <div class="legal-section" id="terms">
            <h2 style="color: var(--royal-blue); margin-top: 0;">Terms & Conditions</h2>
            <div class="legal-content">
                <p><strong>1. Eligibility:</strong> All hosts must be 18 years of age or older. You must provide valid identification for platform verification.</p>
                <p><strong>2. No Joining Fees:</strong> Royal Agency is a recruitment partner. We 100% guarantee that there are NO registration fees or hidden charges to join.</p>
                <p><strong>3. Host Conduct:</strong> Hosts must maintain professional behavior. Violation of platform rules (nudity, hate speech) will lead to immediate termination.</p>
                <p><strong>4. Earnings:</strong> Earnings are based on performance and gifts. Royal Agency facilitates self-withdrawal through official platform channels.</p>
                <p><strong>5. Management:</strong> Royal Agency, owned by Vikas Kannojia, acts as your official talent management partner.</p>
            </div>
        </div>

        <div class="legal-section" id="privacy">
            <h2 style="color: var(--royal-blue); margin-top: 0;">Privacy Policy</h2>
            <div class="legal-content">
                <p><strong>Data Collection:</strong> We collect name, age, and contact details solely for platform registration.</p>
                <p><strong>Usage:</strong> Your data is used for recruitment and training within Royal Agency. We do not sell your personal details.</p>
                <p><strong>Security:</strong> All information is managed securely under the supervision of Vikas Kannojia.</p>
                <p><strong>Removal:</strong> You can request to have your data deleted from our records by contacting us at +91 74281 32358.</p>
            </div>
        </div>
    </div>

    <footer>
        <div class="footer-info">
            <p><strong>ROYAL AGENCY</strong></p>
            <p>Owned & Managed by Vikas Kannojia</p>
            <p>Location: Faridabad, Haryana | Global Support</p>
            <p>WhatsApp: +91 74281 32358</p>
        </div>
        <div class="footer-links">
            <a href="#terms">Terms & Conditions</a> | 
            <a href="#privacy">Privacy Policy</a>
        </div>
        <p style="font-size: 12px; margin-top: 20px; opacity: 0.6;">&copy; 2026 Royal Agency. All Rights Reserved.</p>
    </footer>

</body>
</html>
