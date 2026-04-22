<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pears Green Acne Soap | Face Forward with Confidence</title>
  <style>
    :root{
      --primary:#1f8a5b;
      --primary-dark:#146c46;
      --accent:#6ed3a6;
      --light:#f7fbf8;
      --white:rgba(255,255,255,0.82);
      --text:#556B2F;
      --muted:#5c6f66;
      --card:#ffffffcc;
      --shadow:0 12px 35px rgba(0,0,0,0.12);
      --radius:20px;
      --max-width:1200px;
    }

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      scroll-behavior:smooth;
    }

    body{
      font-family: "Segoe UI", Arial, sans-serif;
      color:var(--text);
      background:linear-gradient(180deg,#eef8f1 0%, #f8fcf9 100%);
      line-height:1.6;
      overflow-x:hidden;
    }

    img{
      max-width:100%;
      display:block;
    }

    a{
      text-decoration:none;
      color:inherit;
    }

    .container{
      width:min(90%, var(--max-width));
      margin:auto;
    }

    /* Navbar */
    header{
      position:fixed;
      top:0;
      left:0;
      width:100%;
      z-index:1000;
      padding:16px 0;
      transition:0.3s ease;
    }

    header.scrolled{
      background:rgba(255,255,255,0.12);
      backdrop-filter:blur(16px);
      -webkit-backdrop-filter:blur(16px);
      box-shadow:0 8px 24px rgba(0,0,0,0.08);
    }

    .nav{
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:14px 22px;
      border-radius:999px;
      background:rgba(255,255,255,0.14);
      border:1px solid rgba(255,255,255,0.28);
      backdrop-filter:blur(18px);
      -webkit-backdrop-filter:blur(18px);
      box-shadow:0 10px 30px rgba(0,0,0,0.08);
    }

    .logo{
      font-size:1.2rem;
      font-weight:800;
      color:#556B2F;
      letter-spacing:0.4px;
    }

    .nav-links{
      display:flex;
      gap:22px;
      list-style:none;
      color:#556B2F;
      font-weight:700;
      font-size:0.95rem;
    }

    .nav-links a{
      transition:0.3s ease;
      position:relative;
    }

    .nav-links a:hover{
      color:#dff8eb;
    }

    .menu-toggle{
      display:none;
      font-size:1.8rem;
      color:#fff;
      cursor:pointer;
    }

    /* Hero */
    .hero{
      min-height:100vh;
      display:flex;
      align-items:center;
      position:relative;
      background:
        linear-gradient(rgba(12,32,22,0.52), rgba(12,32,22,0.52)),
        url('./soap.jpg.jpeg') center/cover no-repeat;
      color:#fff;
    }

    .hero-layout{
      display:grid;
      grid-template-columns:minmax(0,1.1fr) minmax(0,0.9fr);
      gap:40px;
      align-items:center;
    }

    .hero-content{
      max-width:700px;
      animation:fadeUp 1.2s ease forwards;
      opacity:0;
      transform:translateY(30px);
    }

    .hero-banner{
      justify-self:end;
      width:min(100%, 460px);
      border-radius:28px;
      overflow:hidden;
      border:1px solid rgba(255,255,255,0.3);
      box-shadow:0 20px 45px rgba(0,0,0,0.2);
      background:rgba(255,255,255,0.08);
      backdrop-filter:blur(4px);
    }

    .hero-banner img{
      width:100%;
      height:100%;
      object-fit:cover;
    }

    .hero-tag{
      display:inline-block;
      padding:8px 16px;
      margin-bottom:18px;
      border-radius:999px;
      background:rgba(255,255,255,0.14);
      border:1px solid rgba(255,255,255,0.22);
      backdrop-filter:blur(8px);
      font-size:0.9rem;
      letter-spacing:0.5px;
    }

    .hero h1{
      font-size:clamp(2.7rem, 6vw, 5rem);
      line-height:1.05;
      margin-bottom:18px;
      font-weight:800;
    }

    .hero p{
      font-size:1.15rem;
      max-width:560px;
      color:#eaf8f0;
      margin-bottom:30px;
    }

    .hero-buttons{
      display:flex;
      gap:16px;
      flex-wrap:wrap;
    }

    .btn{
      padding:14px 28px;
      border-radius:999px;
      border:none;
      cursor:pointer;
      font-weight:700;
      font-size:0.98rem;
      transition:all 0.3s ease;
      display:inline-block;
    }

    .btn-primary{
      background:linear-gradient(135deg,var(--accent),var(--primary));
      color:#fff;
      box-shadow:0 12px 25px rgba(31,138,91,0.28);
    }

    .btn-primary:hover{
      transform:translateY(-3px);
      box-shadow:0 16px 30px rgba(31,138,91,0.35);
    }

    .btn-secondary{
      background:rgba(255,255,255,0.12);
      color:#fff;
      border:1px solid rgba(255,255,255,0.28);
      backdrop-filter:blur(10px);
    }

    .btn-secondary:hover{
      background:rgba(255,255,255,0.2);
      transform:translateY(-3px);
    }

    /* Sections */
    section{
      padding:100px 0;
    }

    .section-intro{
      text-align:center;
      max-width:760px;
      margin:0 auto 50px;
    }

    .section-intro span{
      color:var(--primary);
      font-weight:700;
      text-transform:uppercase;
      letter-spacing:1.2px;
      font-size:0.82rem;
    }

    .section-intro h2{
      font-size:clamp(2rem, 4vw, 3rem);
      margin:12px 0 14px;
      color:var(--text);
    }

    .section-intro p{
      color:var(--muted);
      font-size:1rem;
    }

    /* About */
    .about-grid{
      display:grid;
      grid-template-columns:1.1fr 0.9fr;
      gap:36px;
      align-items:center;
    }

    .glass-card{
      background:var(--card);
      border:1px solid rgba(255,255,255,0.5);
      backdrop-filter:blur(14px);
      -webkit-backdrop-filter:blur(14px);
      border-radius:var(--radius);
      padding:32px;
      box-shadow:var(--shadow);
    }

    .about-text p{
      color:var(--muted);
      margin-bottom:16px;
      font-size:1rem;
    }

    .about-points{
      display:grid;
      grid-template-columns:repeat(3,1fr);
      gap:16px;
      margin-top:24px;
    }

    .mini-card{
      background:#fff;
      border-radius:16px;
      padding:18px;
      box-shadow:0 8px 20px rgba(0,0,0,0.06);
      text-align:center;
    }

    .mini-card h4{
      color:var(--primary-dark);
      margin-bottom:8px;
      font-size:1rem;
    }

    .mini-card p{
      color:var(--muted);
      font-size:0.92rem;
    }

    /* Product */
    .product-grid{
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:40px;
      align-items:center;
    }

    .product-image{
      position:relative;
      width:100%;
    }

    .product-image .frame{
      border-radius:28px;
      overflow:hidden;
      box-shadow:0 18px 40px rgba(0,0,0,0.12);
      background:#dff6ea;
      min-height:560px;
    }

    .product-image img{
      width:100%;
      height:100%;
      object-fit:cover;
    }

    .badge{
      position:absolute;
      top:18px;
      left:18px;
      background:rgba(255,255,255,0.85);
      color:var(--primary-dark);
      padding:10px 16px;
      border-radius:999px;
      font-weight:700;
      box-shadow:0 8px 20px rgba(0,0,0,0.08);
    }

    .product-info h3{
      font-size:2rem;
      margin-bottom:14px;
    }

    .product-info p{
      color:var(--muted);
      margin-bottom:18px;
    }

    .usp-list{
      list-style:none;
      display:grid;
      gap:14px;
      margin-top:10px;
    }

    .usp-list li{
      background:#fff;
      padding:16px 18px;
      border-radius:16px;
      box-shadow:0 8px 20px rgba(0,0,0,0.05);
      font-weight:600;
      color:#2b4036;
    }

    /* Benefits */
    .benefit-grid{
      display:grid;
      grid-template-columns:repeat(3,1fr);
      gap:22px;
    }

    .benefit-card{
      background:rgba(255,255,255,0.86);
      border:1px solid rgba(31,138,91,0.09);
      border-radius:22px;
      padding:28px 24px;
      box-shadow:0 10px 25px rgba(0,0,0,0.05);
      transition:all 0.35s ease;
    }

    .benefit-card:hover{
      transform:translateY(-8px);
      box-shadow:0 18px 35px rgba(31,138,91,0.14);
      background:linear-gradient(180deg,#ffffff 0%, #f0fbf4 100%);
    }

    .benefit-icon{
      width:56px;
      height:56px;
      border-radius:16px;
      display:grid;
      place-items:center;
      background:linear-gradient(135deg,#d8f7e7,#b9efcf);
      color:var(--primary-dark);
      font-size:1.5rem;
      margin-bottom:18px;
    }

    .benefit-card h4{
      margin-bottom:10px;
      font-size:1.08rem;
    }

    .benefit-card p{
      color:var(--muted);
      font-size:0.96rem;
    }

    /* Ingredients */
    .ingredients-wrap{
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:32px;
      align-items:stretch;
    }

    .ingredient-list{
      list-style:none;
      display:grid;
      gap:14px;
      margin-top:20px;
    }

    .ingredient-list li{
      background:#fff;
      padding:16px 18px;
      border-radius:16px;
      box-shadow:0 8px 18px rgba(0,0,0,0.05);
      color:#335045;
      font-weight:600;
    }

    .ingredient-visual{
      background:linear-gradient(135deg, rgba(31,138,91,0.9), rgba(110,211,166,0.85));
      color:#fff;
      border-radius:28px;
      padding:36px;
      box-shadow:var(--shadow);
      display:flex;
      flex-direction:column;
      justify-content:center;
    }

    .ingredient-visual h3{
      font-size:2rem;
      margin-bottom:12px;
    }

    .ingredient-visual p{
      color:#eefbf4;
      font-size:1rem;
    }

    /* Campaign + CSR */
    .two-column{
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:28px;
    }

    .campaign-card,
    .csr-card{
      border-radius:24px;
      padding:34px;
      box-shadow:var(--shadow);
      min-height:100%;
    }

    .campaign-card{
      background:linear-gradient(135deg,#163f2b,#26885d);
      color:#fff;
    }

    .campaign-card p,
    .csr-card p{
      margin-top:12px;
      color:inherit;
      opacity:0.95;
    }

    .campaign-list,
    .csr-list{
      list-style:none;
      margin-top:20px;
      display:grid;
      gap:14px;
    }

    .campaign-list li,
    .csr-list li{
      padding:14px 16px;
      border-radius:16px;
      background:rgba(255,255,255,0.12);
      backdrop-filter:blur(8px);
    }

    .csr-card{
      background:#ffffff;
      color:var(--text);
      border:1px solid rgba(31,138,91,0.08);
    }

    .csr-list li{
      background:#f4fbf7;
    }

    /* Testimonials */
    .testimonial-grid{
      display:grid;
      grid-template-columns:repeat(3,1fr);
      gap:22px;
    }

    .testimonial{
      background:rgba(255,255,255,0.9);
      border-radius:22px;
      padding:28px;
      box-shadow:0 10px 25px rgba(0,0,0,0.06);
      transition:transform 0.3s ease;
    }

    .testimonial:hover{
      transform:translateY(-6px);
    }

    .stars{
      color:#f6b73c;
      margin-bottom:14px;
      letter-spacing:2px;
    }

    .testimonial p{
      color:var(--muted);
      margin-bottom:16px;
    }

    .testimonial h4{
      color:var(--primary-dark);
      font-size:1rem;
    }

    .testimonial span{
      color:#6a7d74;
      font-size:0.9rem;
    }

    /* CTA */
    .cta{
      padding:110px 0;
    }

    .cta-box{
      text-align:center;
      padding:60px 30px;
      border-radius:30px;
      background:
        linear-gradient(rgba(18,74,49,0.74), rgba(18,74,49,0.74)),
        url('./d4daaec3-52fc-4a26-9187-9df083dabb56.829be74c6a2147d1e7b000628f34fcb0.avif') center/cover no-repeat;
      color:#fff;
      box-shadow:0 18px 40px rgba(0,0,0,0.14);
    }

    .cta-box h2{
      font-size:clamp(2rem,4vw,3.3rem);
      margin-bottom:14px;
    }

    .cta-box p{
      max-width:700px;
      margin:0 auto 24px;
      color:#ebf8f1;
      font-size:1.05rem;
    }

    /* Footer */
    footer{
      background:#10251a;
      color:#d8eee3;
      padding:28px 0;
      text-align:center;
      font-size:0.95rem;
    }

    /* Reveal animation */
    .reveal{
      opacity:0;
      transform:translateY(40px);
      transition:all 0.9s ease;
    }

    .reveal.active{
      opacity:1;
      transform:translateY(0);
    }

    @keyframes fadeUp{
      to{
        opacity:1;
        transform:translateY(0);
      }
    }

    /* Responsive */
    @media (max-width: 992px){
      .about-grid,
      .product-grid,
      .ingredients-wrap,
      .two-column{
        grid-template-columns:1fr;
      }

      .benefit-grid,
      .testimonial-grid{
        grid-template-columns:repeat(2,1fr);
      }

      .about-points{
        grid-template-columns:1fr;
      }

      .product-image .frame{
        min-height:440px;
      }

      .product-image img{
        object-fit:cover;
        }
    }

    @media (max-width: 768px){
      .nav-links{
        position:absolute;
        top:82px;
        right:5%;
        width:220px;
        flex-direction:column;
        background:rgba(17,48,33,0.92);
        padding:20px;
        border-radius:18px;
        display:none;
      }

      .nav-links.show{
        display:flex;
      }

      .menu-toggle{
        display:block;
      }

      .hero{
        text-align:left;
      }

      .hero-layout{
        grid-template-columns:1fr;
      }

      .hero-banner{
        justify-self:start;
        width:min(100%, 380px);
      }

      .hero h1{
        font-size:2.6rem;
      }

      .benefit-grid,
      .testimonial-grid{
        grid-template-columns:1fr;
      }

      section{
        padding:80px 0;
      }
    }

    @media (max-width: 520px){
      .hero-buttons{
        flex-direction:column;
        align-items:flex-start;
      }

      .btn{
        width:100%;
        text-align:center;
      }

      .nav{
        padding:12px 16px;
      }

      .logo{
        font-size:1rem;
      }
    }
  </style>
</head>
<body>

  <header id="header">
    <div class="container">
      <nav class="nav">
        <div class="logo">Pears Green Acne Soap</div>
        <div class="menu-toggle" id="menuToggle">&#9776;</div>
        <ul class="nav-links" id="navLinks">
          <li><a href="#about">About</a></li>
          <li><a href="#product">Product</a></li>
          <li><a href="#benefits">Benefits</a></li>
          <li><a href="#ingredients">Ingredients</a></li>
          <li><a href="#campaign">Campaign</a></li>
          <li><a href="#testimonials">Reviews</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <div class="hero-layout">
        <div class="hero-content">
          <div class="hero-tag">Premium Acne-Care Skincare</div>
          <h1>Face Forward with Confidence</h1>
          <p>Pears Green Acne Soap – Pure Care for Clear Skin. A refined cleansing solution created to support acne-prone skin with gentle, skin-respecting care.</p>
          <div class="hero-buttons">
            <a href="#product" class="btn btn-primary">Shop Now</a>
            <a href="#about" class="btn btn-secondary">Explore More</a>
          </div>
        </div>
        <div class="hero-banner">
          <img src="./soap.jpg.jpeg" alt="Pears Green Acne Soap banner image">
        </div>
      </div>
    </div>
  </section>

  <section id="about">
    <div class="container">
      <div class="about-grid reveal">
        <div class="glass-card about-text">
          <div class="section-intro" style="text-align:left; margin:0 0 20px 0;">
            <span>About the Brand</span>
            <h2>Pure heritage, modern acne care</h2>
          </div>
          <p>Pears Green Acne Soap is designed for a new generation of skincare users who seek visible clarity without compromising skin comfort. Rooted in the trusted legacy of transparent soap care, this formulation brings together cleansing purity and targeted acne support in one premium daily essential.</p>
          <p>Crafted with a gentle skincare philosophy, the product is positioned as more than a cleanser. It is a confidence-building ritual that helps students and young adults feel fresh, presentable, and ready to face the day with assurance.</p>
          <p>Its brand identity reflects purity, self-respect, and the belief that healthy-looking skin can positively influence self-image, social confidence, and everyday wellbeing.</p>
        </div>

        <div class="about-points">
          <div class="mini-card">
            <h4>Acne Care</h4>
            <p>Targets excess oil and impurities that commonly affect acne-prone skin.</p>
          </div>
          <div class="mini-card">
            <h4>Gentle Ingredients</h4>
            <p>Formulated to cleanse effectively while remaining considerate to delicate skin.</p>
          </div>
          <div class="mini-card">
            <h4>Confidence Building</h4>
            <p>Supports a cleaner, fresher complexion that encourages self-confidence.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="product">
    <div class="container">
      <div class="section-intro reveal">
        <span>Product Showcase</span>
        <h2>Skincare that looks premium and performs with purpose</h2>
        <p>A clear, botanical-inspired cleansing bar developed to elevate acne-care into a refined daily skincare experience.</p>
      </div>

      <div class="product-grid reveal">
        <div class="product-image">
          <div class="badge">Premium Acne Solution</div>
          <div class="frame">
            <img src="./d4daaec3-52fc-4a26-9187-9df083dabb56.829be74c6a2147d1e7b000628f34fcb0.avif" alt="Pears Green Acne Soap Product Display">
          </div>
        </div>

        <div class="product-info">
          <h3>Pears Green Acne Soap</h3>
          <p>Pears Green Acne Soap is created to purify the skin surface, help reduce pore-clogging impurities, and deliver a clean, balanced finish suitable for everyday use. The product combines aesthetic simplicity with functional skincare value, making it an ideal fit for consumers seeking both effectiveness and elegance.</p>
          <ul class="usp-list">
            <li>✔ Acne control support for visibly clearer-looking skin</li>
            <li>✔ Skin purification through gentle yet effective cleansing</li>
            <li>✔ Suitable for sensitive skin with a comfort-first approach</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <section id="benefits">
    <div class="container">
      <div class="section-intro reveal">
        <span>Benefits</span>
        <h2>Why consumers connect with the formula</h2>
        <p>Every benefit is positioned around clarity, comfort, and confidence—three pillars of a strong skincare brand identity.</p>
      </div>

      <div class="benefit-grid reveal">
        <div class="benefit-card">
          <div class="benefit-icon">🌿</div>
          <h4>Acne Reduction</h4>
          <p>Helps reduce buildup and surface impurities associated with recurring breakouts.</p>
        </div>
        <div class="benefit-card">
          <div class="benefit-icon">💧</div>
          <h4>Deep Cleansing</h4>
          <p>Removes dirt, oil, and daily residue to refresh the skin without harsh stripping.</p>
        </div>
        <div class="benefit-card">
          <div class="benefit-icon">🍃</div>
          <h4>Natural Ingredients</h4>
          <p>Inspired by botanical care to promote a clean and naturally balanced skincare routine.</p>
        </div>
        <div class="benefit-card">
          <div class="benefit-icon">🫧</div>
          <h4>Skin Hydration</h4>
          <p>Maintains a soft, comfortable feel through a moisture-conscious cleansing experience.</p>
        </div>
        <div class="benefit-card">
          <div class="benefit-icon">✨</div>
          <h4>Oil Control</h4>
          <p>Supports a fresher complexion by helping manage excess surface oil throughout the day.</p>
        </div>
        <div class="benefit-card">
          <div class="benefit-icon">🤍</div>
          <h4>Confidence Boost</h4>
          <p>Encourages self-assurance by helping skin appear cleaner, calmer, and more cared for.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="ingredients">
    <div class="container">
      <div class="ingredients-wrap reveal">
        <div class="glass-card">
          <div class="section-intro" style="text-align:left; margin:0;">
            <span>Ingredients</span>
            <h2>Botanical-inspired purity</h2>
            <p>A naturally positioned ingredient story that reinforces premium acne-care and skin comfort.</p>
          </div>
          <ul class="ingredient-list">
            <li>🌱 <strong>Neem</strong> – traditionally valued for purifying and clarifying care</li>
            <li>💚 <strong>Aloe Vera</strong> – known for soothing and refreshing skin comfort</li>
            <li>🫧 <strong>Glycerin</strong> – helps support softness and moisture retention</li>
            <li>🌿 <strong>Herbal Oils</strong> – contribute to a balanced, nourishing cleansing ritual</li>
          </ul>
        </div>

        <div class="ingredient-visual">
          <h3>Cleanse with calm. Care with confidence.</h3>
          <p>Pears Green Acne Soap is presented as a harmony of botanical care and modern skincare refinement. Its ingredient identity supports the brand’s premium image while communicating gentleness, purity, and skin-respecting daily use.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="campaign">
    <div class="container">
      <div class="section-intro reveal">
        <span>Brand Campaign</span>
        <h2>The Face Forward Campaign</h2>
        <p>A youth-centered activation designed to connect skincare with confidence, visibility, and authentic self-expression.</p>
      </div>

      <div class="two-column reveal">
        <div class="campaign-card">
          <h3>Face Forward Campaign</h3>
          <p>This campaign positions Pears Green Acne Soap as more than a skincare product. It becomes a confidence platform for students navigating appearance-related pressure in academic and social spaces.</p>
          <ul class="campaign-list">
            <li><strong>University Activation:</strong> on-campus brand booths offering skin analysis, product trials, and branded photo spaces.</li>
            <li><strong>Confidence Booth:</strong> a safe, interactive zone where students record uplifting messages about self-image and confidence.</li>
            <li><strong>#FaceForwardChallenge:</strong> a social media campaign inviting students to share honest skincare journeys and confidence stories.</li>
          </ul>
        </div>

        <div class="csr-card">
          <h3>Corporate Social Responsibility</h3>
          <p>The brand’s social purpose extends beyond product communication, reinforcing Pears Green Acne Soap as a responsible and empathetic skincare brand.</p>
          <ul class="csr-list">
            <li><strong>Mental Health Awareness:</strong> support conversations around self-esteem, skin anxiety, and emotional wellbeing.</li>
            <li><strong>Acne Confidence Workshops:</strong> educational sessions for students on skincare routines and self-confidence building.</li>
            <li><strong>Free Skincare Awareness Programs:</strong> accessible campus outreach promoting healthy skin habits and informed product use.</li>
            <li><strong>Support for Skincare Access:</strong> donation-based partnerships helping underserved communities access basic skincare products.</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <section id="testimonials">
    <div class="container">
      <div class="section-intro reveal">
        <span>Testimonials</span>
        <h2>Realistic stories, relatable confidence</h2>
        <p>Emotionally grounded student reviews help make the brand feel authentic, human, and commercially believable.</p>
      </div>

      <div class="testimonial-grid reveal">
        <div class="testimonial">
          <div class="stars">★★★★★</div>
          <p>“After a few weeks of using Pears Green Acne Soap, my skin felt cleaner and less oily. What surprised me most was how much more confident I felt attending classes without worrying about breakouts.”</p>
          <h4>Amira S.</h4>
          <span>University Student</span>
        </div>

        <div class="testimonial">
          <div class="stars">★★★★★</div>
          <p>“I liked that it felt gentle on my skin while still giving that deep-clean feeling. My acne looked calmer, and I became much more comfortable being in photos again.”</p>
          <h4>Daniel R.</h4>
          <span>Media & Communication Student</span>
        </div>

        <div class="testimonial">
          <div class="stars">★★★★★</div>
          <p>“The product feels premium, fresh, and trustworthy. It gave me a sense of control over my skincare routine, and that small change made a big difference to my self-esteem.”</p>
          <h4>Nadia T.</h4>
          <span>Business Student</span>
        </div>
      </div>
    </div>
  </section>

  <section class="cta">
    <div class="container">
      <div class="cta-box reveal">
        <h2>Your skin. Your confidence. Your story.</h2>
        <p>Pears Green Acne Soap invites a new generation to embrace clear skin with dignity, confidence, and premium daily care that feels both modern and meaningful.</p>
        <a href="#hero" class="btn btn-primary">Join the Movement</a>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <p><strong>Pears Green Acne Soap</strong> &copy; 2026. All rights reserved.</p>
    </div>
  </footer>

  <script>
    // Navbar background on scroll
    const header = document.getElementById("header");
    window.addEventListener("scroll", () => {
      header.classList.toggle("scrolled", window.scrollY > 40);
    });

    // Mobile menu
    const menuToggle = document.getElementById("menuToggle");
    const navLinks = document.getElementById("navLinks");

    menuToggle.addEventListener("click", () => {
      navLinks.classList.toggle("show");
    });

    document.querySelectorAll(".nav-links a").forEach(link => {
      link.addEventListener("click", () => {
        navLinks.classList.remove("show");
      });
    });

    // Reveal on scroll
    const reveals = document.querySelectorAll(".reveal");

    function revealOnScroll() {
      const windowHeight = window.innerHeight;
      reveals.forEach(item => {
        const itemTop = item.getBoundingClientRect().top;
        if (itemTop < windowHeight - 100) {
          item.classList.add("active");
        }
      });
    }

    window.addEventListener("scroll", revealOnScroll);
    window.addEventListener("load", revealOnScroll);
  </script>
</body>
</html>
