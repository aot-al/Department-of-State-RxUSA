# U.S. Department of State (RxUSA)
The U.S. Department of State website provides official information on American diplomacy, foreign policy, international relations, travel advisories, visas, passports, global partnerships, press releases, and government services. It also features news, speeches, embassy resources, and updates on worldwide political and security matters.
Please note that this website is not affiliated with any real organization or government. It has been created for purely fictional purposes related to roleplay within the “RxUSA” community. Copyright regulations apply to this website. For any questions regarding these rights or any matter related to the website, please contact “hzf.mtp”.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Department of International Affairs</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: #f5f7fa;
      color: #111827;
      line-height: 1.6;
    }

    .topbar {
      background: #0a3161;
      color: white;
      padding: 10px 40px;
      font-size: 14px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .topbar span {
      opacity: 0.9;
    }

    header {
      background: white;
      border-bottom: 1px solid #dbe3ec;
    }

    .navbar {
      max-width: 1400px;
      margin: auto;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 15px;
    }

    .logo-circle {
      width: 60px;
      height: 60px;
      border-radius: 50%;
      background: #0a3161;
      border: 4px solid #b31942;
    }

    .logo h1 {
      font-size: 22px;
      color: #0a3161;
      font-weight: 700;
    }

    .logo p {
      font-size: 13px;
      color: #6b7280;
    }

    nav {
      display: flex;
      gap: 30px;
    }

    nav a {
      text-decoration: none;
      color: #111827;
      font-weight: 500;
      transition: 0.2s;
    }

    nav a:hover {
      color: #0a3161;
    }

    .hero {
      height: 600px;
      background:
        linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)),
        url('https://images.unsplash.com/photo-1529107386315-e1a2ed48a620?q=80&w=2070&auto=format&fit=crop') center/cover;
      display: flex;
      align-items: center;
      padding: 0 80px;
      color: white;
    }

    .hero-content {
      max-width: 700px;
    }

    .hero h2 {
      font-size: 58px;
      line-height: 1.1;
      margin-bottom: 25px;
      font-weight: 700;
    }

    .hero p {
      font-size: 20px;
      margin-bottom: 35px;
      color: #e5e7eb;
    }

    .hero button {
      background: #b31942;
      color: white;
      border: none;
      padding: 16px 28px;
      font-size: 16px;
      font-weight: 600;
      border-radius: 6px;
      cursor: pointer;
      transition: 0.2s;
    }

    .hero button:hover {
      background: #8f1239;
    }

    .section {
      max-width: 1300px;
      margin: auto;
      padding: 80px 40px;
    }

    .section-title {
      font-size: 38px;
      margin-bottom: 40px;
      color: #0a3161;
      font-weight: 700;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 30px;
    }

    .card {
      background: white;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 6px 18px rgba(0,0,0,0.06);
      transition: 0.2s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }

    .card-content {
      padding: 25px;
    }

    .card-content h3 {
      margin-bottom: 15px;
      color: #0a3161;
      font-size: 24px;
    }

    .card-content p {
      color: #4b5563;
    }

    .info-banner {
      background: #0a3161;
      color: white;
      padding: 60px 40px;
      text-align: center;
    }

    .info-banner h2 {
      font-size: 42px;
      margin-bottom: 15px;
    }

    .info-banner p {
      max-width: 900px;
      margin: auto;
      color: #dbeafe;
    }

    footer {
      background: #111827;
      color: #d1d5db;
      padding: 50px 40px;
    }

    .footer-container {
      max-width: 1300px;
      margin: auto;
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 30px;
    }

    .footer-column h4 {
      color: white;
      margin-bottom: 15px;
    }

    .footer-column p,
    .footer-column a {
      color: #d1d5db;
      text-decoration: none;
      display: block;
      margin-bottom: 8px;
      font-size: 15px;
    }

    .disclaimer {
      margin-top: 40px;
      border-top: 1px solid #374151;
      padding-top: 20px;
      text-align: center;
      font-size: 13px;
      color: #9ca3af;
    }

    @media (max-width: 900px) {
      .navbar {
        flex-direction: column;
        gap: 20px;
      }

      nav {
        flex-wrap: wrap;
        justify-content: center;
      }

      .hero {
        padding: 40px;
        height: auto;
      }

      .hero h2 {
        font-size: 42px;
      }
    }
  </style>
</head>
<body>

  <div class="topbar">
    <span>Official Roleplay Government Portal</span>
    <span>RxUSA Community</span>
  </div>

  <header>
    <div class="navbar">
      <div class="logo">
        <div class="logo-circle"></div>

        <div>
          <h1>Department of International Affairs</h1>
          <p>Government of RxUSA</p>
        </div>
      </div>

      <nav>
        <a href="#">Home</a>
        <a href="#">News</a>
        <a href="#">Diplomacy</a>
        <a href="#">Services</a>
        <a href="#">Press</a>
        <a href="#">Contact</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h2>Promoting Stability, Diplomacy and International Cooperation</h2>

      <p>
        The Department of International Affairs represents the interests of the Republic of RxUSA through diplomacy, strategic partnerships and public service.
      </p>

      <button>Latest Statements</button>
    </div>
  </section>

  <section class="section">
    <h2 class="section-title">Latest Updates</h2>

    <div class="grid">

      <div class="card">
        <img src="https://images.unsplash.com/photo-1575320181282-9afab399332c?q=80&w=1974&auto=format&fit=crop">

        <div class="card-content">
          <h3>International Summit</h3>
          <p>
            Officials met with foreign representatives to discuss security cooperation and economic development.
          </p>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1521295121783-8a321d551ad2?q=80&w=1974&auto=format&fit=crop">

        <div class="card-content">
          <h3>Travel Advisory</h3>
          <p>
            Updated international travel guidance has been published for citizens and visitors.
          </p>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1520607162513-77705c0f0d4a?q=80&w=2070&auto=format&fit=crop">

        <div class="card-content">
          <h3>Public Services</h3>
          <p>
            Access diplomatic services, administrative support and international coordination resources.
          </p>
        </div>
      </div>

    </div>
  </section>

  <section class="info-banner">
    <h2>Serving the Nation Through Diplomacy</h2>

    <p>
      This fictional department works alongside international partners to ensure security, cooperation and strategic development across the Republic of RxUSA.
    </p>
  </section>

  <footer>
    <div class="footer-container">

      <div class="footer-column">
        <h4>Department</h4>
        <a href="#">About Us</a>
        <a href="#">Leadership</a>
        <a href="#">Offices</a>
      </div>

      <div class="footer-column">
        <h4>Resources</h4>
        <a href="#">Newsroom</a>
        <a href="#">Press Releases</a>
        <a href="#">Archives</a>
      </div>

      <div class="footer-column">
        <h4>Contact</h4>
        <p>contact@rxusa.gov</p>
        <p>Washington District</p>
      </div>

    </div>

    <div class="disclaimer">
      Please note that this website is not affiliated with any real organization or government. It has been created for fictional roleplay purposes within the RxUSA community.
    </div>
  </footer>

</body>
</html>
