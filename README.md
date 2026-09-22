# l<!DOCTYPE html>
<html lang="te">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sri Lakshmi Dental Hospital | Best Dental Care</title>
    <style>
        :root {
            --primary: #0284c7;
            --primary-dark: #0369a1;
            --secondary: #0f172a;
            --light-bg: #f8fafc;
            --text: #334155;
            --white: #ffffff;
            --whatsapp: #25d366;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
        }

        body {
            color: var(--text);
            line-height: 1.6;
            background-color: var(--white);
        }

        /* Header */
        header {
            background-color: var(--white);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .nav-container {
            max-width: 1100px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 1.5rem;
        }

        .logo {
            font-size: 1.3rem;
            font-weight: 700;
            color: var(--primary);
        }

        .btn-call {
            background-color: var(--whatsapp);
            color: var(--white);
            padding: 0.6rem 1.2rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            font-size: 0.9rem;
            display: inline-flex;
            align-items: center;
            gap: 6px;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #e0f2fe 0%, #f8fafc 100%);
            padding: 3.5rem 1.5rem;
            text-align: center;
        }

        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }

        .hero h1 {
            font-size: 2.2rem;
            color: var(--secondary);
            margin-bottom: 1rem;
            line-height: 1.2;
        }

        .hero p {
            font-size: 1.1rem;
            margin-bottom: 2rem;
            color: #475569;
        }

        .btn-group {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .btn-primary {
            background-color: var(--primary);
            color: var(--white);
            padding: 0.8rem 1.6rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
        }

        .btn-secondary {
            background-color: var(--white);
            color: var(--primary);
            border: 2px solid var(--primary);
            padding: 0.8rem 1.6rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
        }

        /* Services Section */
        .services {
            max-width: 1100px;
            margin: 4rem auto;
            padding: 0 1.5rem;
        }

        .section-title {
            text-align: center;
            font-size: 1.8rem;
            color: var(--secondary);
            margin-bottom: 2rem;
        }

        .grid-3 {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
        }

        .service-card {
            background: var(--light-bg);
            padding: 1.5rem;
            border-radius: 12px;
            border: 1px solid #e2e8f0;
        }

        .service-card h3 {
            color: var(--primary);
            margin-bottom: 0.5rem;
        }

        /* Booking Form */
        .booking-section {
            background-color: var(--light-bg);
            padding: 4rem 1.5rem;
        }

        .form-container {
            max-width: 500px;
            margin: 0 auto;
            background: var(--white);
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }

        .form-group {
            margin-bottom: 1.2rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.4rem;
            font-weight: 600;
            font-size: 0.9rem;
        }

        .form-group input, .form-group select {
            width: 100%;
            padding: 0.75rem;
            border: 1px solid #cbd5e1;
            border-radius: 6px;
            font-size: 1rem;
        }

        .btn-submit {
            width: 100%;
            background-color: var(--primary);
            color: var(--white);
            padding: 0.85rem;
            border: none;
            border-radius: 6px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
        }

        /* Footer */
        footer {
            background-color: var(--secondary);
            color: var(--white);
            padding: 2.5rem 1.5rem;
            text-align: center;
        }

        footer a {
            color: #38bdf8;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <header>
        <div class="nav-container">
            <div class="logo">Sri Lakshmi Dental Hospital</div>
            <a href="https://wa.me/?text=Hi,%20I%20want%20to%20book%20a%20dental%20appointment" class="btn-call" target="_blank">
                WhatsApp Booking
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h1>Mee Navvuni Reddinta Azhagugaa Marchukondi</h1>
            <p>Advanced Dental Care for Healthy & Beautiful Smiles. Expert Doctors and Painless Treatments.</p>
            <div class="btn-group">
                <a href="#book" class="btn-primary">Book Appointment</a>
                <a href="https://share.google/snBlBjVttZAviFU2s" target="_blank" class="btn-secondary">Google Maps Location</a>
            </div>
        </div>
    </section>

    <!-- Services -->
    <section class="services">
        <h2 class="section-title">Mana Services (చికిత్సలు)</h2>
        <div class="grid-3">
            <div class="service-card">
                <h3>Teeth Cleaning & Whitening</h3>
                <p>పళ్ళు శుభ్రపరచడం మరియు తెల్లగా మెరిసేలా చేసే అధునాతన లేజర్ ట్రీట్‌మెంట్.</p>
            </div>
            <div class="service-card">
                <h3>Painless Root Canal</h3>
                <p>నొప్పి లేని సింగిల్-సిట్టింగ్ రూట్ కెనాల్ ట్రీట్‌మెంట్.</p>
            </div>
            <div class="service-card">
                <h3>Dental Implants</h3>
                <p>ఊడిపోయిన పళ్ళ స్థానంలో సహజమైన శాశ్వత కృత్రిమ పళ్ళు అమర్చడం.</p>
            </div>
            <div class="service-card">
                <h3>Braces & Aligners</h3>
                <p>వంకర పళ్ళను సరిచేసే మెటల్ బ్రేసెస్ మరియు క్లియర్ అలైపర్స్.</p>
            </div>
            <div class="service-card">
                <h3>Pediatric Dentistry</h3>
                <p>చిన్న పిల్లల పళ్ళ సమస్యలకు ప్రత్యేకమైన, సున్నితమైన వైద్యం.</p>
            </div>
            <div class="service-card">
                <h3>Smile Designing</h3>
                <p>మీ ముఖ రూపానికి తగ్గట్టు అందమైన నవ్వును డిజైన్ చేసే కాస్మెటిక్ కేర్.</p>
            </div>
        </div>
    </section>

    <!-- Appointment Form -->
    <section class="booking-section" id="book">
        <h2 class="section-title">Appointment Book Chesukondi</h2>
        <div class="form-container">
            <form onsubmit="event.preventDefault(); alert('Mee details submit ayyayi! Mamu twaraloni mimmalni contact chestamu.');">
                <div class="form-group">
                    <label>Mee Peru (Full Name)</label>
                    <input type="text" required placeholder="Ex: Ramesh Kumar">
                </div>
                <div class="form-group">
                    <label>Phone Number</label>
                    <input type="tel" required placeholder="Ex: 9876543210">
                </div>
                <div class="form-group">
                    <label>Chikitsa (Select Service)</label>
                    <select>
                        <option>General Dental Checkup</option>
                        <option>Teeth Cleaning / Whitening</option>
                        <option>Root Canal Treatment</option>
                        <option>Dental Implants</option>
                        <option>Braces / Clear Aligners</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>Preferred Date</label>
                    <input type="date" required>
                </div>
                <button type="submit" class="btn-submit">Submit Request</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <h3>Sri Lakshmi Dental Hospital</h3>
        <p>Timings: Mon – Sat: 9:00 AM – 8:30 PM | Sun: By Appointment</p>
        <p><a href="https://share.google/snBlBjVttZAviFU2s" target="_blank">Open in Google Maps</a></p>
        <br>
        <p style="font-size: 0.85rem; color: #94a3b8;">&copy; 2026 Sri Lakshmi Dental Hospital. All Rights Reserved.</p>
    </footer>

</body>
</html>
