[OK_Holidays_V2_Only_Honeymoon_Photos.html](https://github.com/user-attachments/files/32702067/OK_Holidays_V2_Only_Honeymoon_Photos.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>OK Holidays | Honeymoon & Holiday Packages in Kerala, India & Abroad</title>
<meta name="description" content="OK Holidays offers honeymoon, Kerala, India and international holiday packages. Plan your perfect honeymoon, family holiday or customized trip with OK Holidays.">
<meta name="theme-color" content="#0f6b68">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

<style>
:root{
  --ink:#102a2e;--muted:#607174;--cream:#f7f5ef;--white:#fff;
  --teal:#0f6b68;--gold:#e6b85c;--line:#e7e3d9;
  --shadow:0 18px 50px rgba(16,42,46,.12)
}
*{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:85px}
body{margin:0;font-family:"DM Sans",sans-serif;color:var(--ink);background:var(--cream);line-height:1.6}
a{text-decoration:none;color:inherit}
nav{
  position:fixed;top:0;left:0;right:0;z-index:20;
  background:rgba(255,255,255,.94);backdrop-filter:blur(14px);
  border-bottom:1px solid rgba(0,0,0,.06)
}
.nav-inner{
  max-width:1200px;margin:auto;display:flex;align-items:center;
  justify-content:space-between;padding:16px 24px
}
.logo{font-weight:800;letter-spacing:.08em;font-size:18px}
.logo span{color:var(--gold)}
.navlinks{display:flex;gap:20px;font-size:14px;font-weight:600;align-items:center}
.navlinks a:hover{color:var(--teal)}
.cta,.btn{
  background:var(--teal);color:#fff;padding:11px 17px;border-radius:999px;
  font-weight:700;font-size:14px
}
.menu-toggle{
  display:none;border:0;background:transparent;font-size:27px;
  cursor:pointer;color:var(--ink);padding:4px 8px
}
.mobile-menu{
  display:none;background:#fff;border-top:1px solid var(--line);
  padding:10px 24px 18px
}
.mobile-menu a{display:block;padding:12px 0;font-weight:600;border-bottom:1px solid var(--line)}
.mobile-menu .mobile-cta{margin-top:12px;text-align:center;background:var(--teal);color:#fff;border-radius:999px;border:0}

.hero{
  min-height:92vh;display:grid;place-items:center;position:relative;overflow:hidden;
  background:linear-gradient(90deg,rgba(7,31,34,.82),rgba(7,31,34,.28)),
  url("https://okholidays.my.canva.site/images/315892db69b290111d6728c46f352ea1.jpg") center/cover
}
.hero-inner{width:min(1200px,92%);padding:130px 0 90px;color:#fff}
.eyebrow{text-transform:uppercase;letter-spacing:.22em;font-size:13px;font-weight:700;color:#f4d58f}
.hero h1{
  font-family:"Playfair Display",serif;font-size:clamp(50px,8vw,92px);
  line-height:.98;max-width:820px;margin:15px 0 22px
}
.hero p{font-size:19px;max-width:650px;color:#f3f5f3}
.buttons{display:flex;gap:12px;flex-wrap:wrap;margin-top:28px}
.btn{padding:14px 22px;display:inline-block}
.btn.primary{background:var(--gold);color:#1d2b2b}
.btn.light{border:1px solid rgba(255,255,255,.55);color:#fff;background:transparent}
.btn.small{padding:10px 15px;font-size:13px}

section{padding:90px 0}
.container{width:min(1200px,92%);margin:auto}
.section-head{max-width:760px;margin-bottom:38px}
.section-head .eyebrow{color:var(--teal)}
h2{font-family:"Playfair Display",serif;font-size:clamp(36px,5vw,58px);line-height:1.05;margin:10px 0 14px}
.lead{color:var(--muted);font-size:17px}

.intro{background:#fff}
.intro-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:55px;align-items:center}
.intro-photo{
  height:470px;border-radius:30px;
  background:url("https://okholidays.my.canva.site/images/e1f5fd462267390dff7c7eea05912290.jpg") center/cover;
  box-shadow:var(--shadow)
}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:30px}
.stat{padding:20px;border:1px solid var(--line);border-radius:18px}
.stat b{font-size:25px}
.stat span{display:block;color:var(--muted);font-size:13px}

.cards{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
.card{
  background:#fff;border-radius:22px;overflow:hidden;border:1px solid var(--line);
  transition:.25s
}
.card:hover{transform:translateY(-5px);box-shadow:var(--shadow)}
.card-img{height:210px;background-size:cover;background-position:center}
.card-body{padding:24px}
.card h3{margin:0 0 8px;font-size:22px}
.card p{color:var(--muted);margin:0 0 17px}
.link{color:var(--teal);font-weight:800}

.honeymoon{background:#fff}
.honeymoon .section-head{text-align:center;margin-left:auto;margin-right:auto}
.honeymoon-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.honeymoon-card{
  background:var(--cream);border:1px solid var(--line);border-radius:22px;
  overflow:hidden;transition:.25s
}
.honeymoon-card:hover{transform:translateY(-5px);box-shadow:var(--shadow)}
.honeymoon-img{height:220px;background-size:cover;background-position:center}
.honeymoon-body{padding:22px}
.honeymoon-body h3{margin:0 0 5px;font-size:22px}
.honeymoon-body .route{color:var(--teal);font-weight:700;font-size:13px;margin-bottom:12px}
.honeymoon-body ul{padding-left:18px;margin:0 0 18px;color:var(--muted);font-size:14px}
.honeymoon-body li{margin:5px 0}
.price{font-weight:800;font-size:17px;margin-bottom:12px;color:var(--ink)}
.price-note{font-size:11px;color:var(--muted);font-weight:400;display:block;margin-top:2px}

.filters{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:24px}
.filter{
  border:1px solid var(--line);background:#fff;padding:9px 15px;
  border-radius:999px;cursor:pointer;font-weight:600
}
.filter.active{background:var(--ink);color:#fff}
.package-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.package{background:#fff;border:1px solid var(--line);border-radius:20px;padding:22px}
.package h3{margin:0 0 7px;font-size:20px}
.package .route{color:var(--teal);font-weight:700;font-size:13px;margin-bottom:13px}
.package ul{padding-left:18px;margin:0 0 18px;color:var(--muted);font-size:14px}
.package li{margin:6px 0}
.package .package-cta{margin-top:14px;display:inline-block;color:var(--teal);font-weight:800;font-size:14px}

.features{background:var(--ink);color:#fff}
.feature-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.feature{border:1px solid rgba(255,255,255,.14);padding:28px;border-radius:20px;background:rgba(255,255,255,.04)}
.feature .num{font-size:13px;color:var(--gold);font-weight:800;letter-spacing:.12em}
.feature h3{font-size:22px;margin:10px 0}
.feature p{color:#c7d2d1;margin:0}

.trust-strip{background:#f0eee7}
.trust-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:16px}
.trust-item{background:#fff;border:1px solid var(--line);border-radius:18px;padding:22px}
.trust-item b{display:block;font-size:18px;margin-bottom:5px}
.trust-item span{font-size:13px;color:var(--muted)}

.banner{
  background:linear-gradient(100deg,#0f6b68,#16484a);color:#fff;
  border-radius:28px;padding:55px;display:flex;justify-content:space-between;
  gap:25px;align-items:center
}
.banner h2{margin:0;font-size:45px}
.banner p{color:#d8e8e7}

.contact{background:#fff}
.contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:40px}
.contact-card{background:var(--cream);border-radius:24px;padding:30px}
.contact-item{padding:17px 0;border-bottom:1px solid var(--line)}
.contact-item:last-child{border:0}
.contact-item small{
  display:block;text-transform:uppercase;letter-spacing:.12em;
  color:var(--muted);font-size:11px;font-weight:800
}
.contact-item a{font-weight:700;color:var(--teal)}

.floating-whatsapp{
  position:fixed;right:18px;bottom:18px;z-index:30;
  background:#25D366;color:#fff;border-radius:999px;
  padding:13px 18px;font-weight:800;box-shadow:0 10px 30px rgba(0,0,0,.18)
}
footer{background:#0b2023;color:#b9c8c7;padding:30px 0}
.footer-inner{display:flex;justify-content:space-between;gap:20px;align-items:center}
.footer-logo{color:#fff;font-weight:800}

@media(max-width:900px){
  .navlinks,.desktop-cta{display:none}
  .menu-toggle{display:block}
  .intro-grid,.contact-grid{grid-template-columns:1fr}
  .cards,.package-grid,.feature-grid,.honeymoon-grid{grid-template-columns:1fr 1fr}
  .trust-grid{grid-template-columns:1fr 1fr}
  .intro-photo{height:330px}
}
@media(max-width:600px){
  section{padding:65px 0}
  .cards,.package-grid,.feature-grid,.stats,.honeymoon-grid,.trust-grid{grid-template-columns:1fr}
  .hero h1{font-size:54px}
  .hero p{font-size:17px}
  .banner{padding:32px;display:block}
  .banner h2{font-size:36px}
  .footer-inner{display:block}
  .footer-inner>div{margin-bottom:8px}
  .floating-whatsapp{right:12px;bottom:12px;padding:11px 15px;font-size:13px}
}
</style>
</head>

<body>

<nav>
  <div class="nav-inner">
    <a class="logo" href="#home">OK <span>HOLIDAYS</span></a>

    <div class="navlinks">
      <a href="#honeymoon">Honeymoon</a>
      <a href="#packages">Domestic</a>
      <a href="#international">International</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </div>

    <a class="cta desktop-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27d%20like%20to%20plan%20a%20holiday.">Book Now</a>
    <button class="menu-toggle" id="menuToggle" aria-label="Open menu">☰</button>
  </div>

  <div class="mobile-menu" id="mobileMenu">
    <a href="#honeymoon">Honeymoon</a>
    <a href="#packages">Domestic</a>
    <a href="#international">International</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
    <a class="mobile-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27d%20like%20to%20plan%20a%20holiday.">Book / Enquire on WhatsApp</a>
  </div>
</nav>

<header class="hero" id="home">
  <div class="hero-inner">
    <div class="eyebrow">Honeymoon Specialists · Since 2021</div>
    <h1>Your Honeymoon.<br>Your Story.<br>Your Journey.</h1>
    <p>Beautifully planned honeymoon experiences across India and beyond, with handpicked stays, private transfers and personalized travel support.</p>

    <div class="buttons">
      <a class="btn primary" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20looking%20for%20a%20honeymoon%20package.%20Please%20help%20me%20plan%20my%20trip.">Plan My Honeymoon </a>
      <a class="btn light" href="#honeymoon">Explore Honeymoon Packages</a>
    </div>
  </div>
</header>

<section class="intro" id="about">
  <div class="container intro-grid">
    <div>
      <div class="section-head">
        <div class="eyebrow">About OK Holidays</div>
        <h2>Make your next journey unforgettable.</h2>
        <p class="lead">OK Holidays has been offering vacation packages since 2021, with a focus on memorable trips, practical travel support and personalized holiday planning.</p>
      </div>

      <div class="stats">
        <div class="stat"><b>2021</b><span>Serving travellers since</span></div>
        <div class="stat"><b>India</b><span>Kerala & nationwide tours</span></div>
        <div class="stat"><b>Worldwide</b><span>International holidays</span></div>
      </div>
    </div>

    <div class="intro-photo"></div>
  </div>
</section>

<section id="services">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">Our Packages</div>
      <h2>Choose the trip that fits your dream.</h2>
      <p class="lead">From romantic escapes to family adventures and educational journeys, choose a holiday experience that fits your needs.</p>
    </div>

    <div class="cards">
      <div class="card">
        <div class="card-img" style="background-image:url('https://okholidays.my.canva.site/images/dbb42f45b8d507d456e94f90b2c95e95.jpg')"></div>
        <div class="card-body">
          <h3>Honeymoon Packages</h3>
          <p>Romantic stays, beautiful destinations and thoughtfully planned experiences for couples.</p>
          <a class="link" href="#honeymoon">Explore Honeymoon →</a>
        </div>
      </div>

      <div class="card">
        <div class="card-img" style="background-image:url('https://okholidays.my.canva.site/images/2624c34b8f6e4c3f6018d960a15cf635.jpg')"></div>
        <div class="card-body">
          <h3>Educational Trips</h3>
          <p>Explore historical sites and unique destinations through carefully planned educational journeys.</p>
          <a class="link" href="#packages">Explore India →</a>
        </div>
      </div>

      <div class="card">
        <div class="card-img" style="background-image:url('https://okholidays.my.canva.site/images/5a368213c191abc81bdb53d81ba7f5f0.jpg')"></div>
        <div class="card-body">
          <h3>Family Tours</h3>
          <p>Spend quality time together with comfortable stays, sightseeing and family-friendly experiences.</p>
          <a class="link" href="#packages">Explore Packages →</a>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="honeymoon" id="honeymoon">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">Honeymoon Collection</div>
      <h2>Begin your forever somewhere beautiful.</h2>
      <p class="lead">Romantic escapes designed for couples who want beautiful stays, memorable experiences and stress-free travel.</p>
    </div>

    <div class="honeymoon-grid">

      <div class="honeymoon-card">
        <div class="honeymoon-img" style="background-image:url('https://images.unsplash.com/photo-1569852837213-00d97a707a83?auto=format&fit=crop&w=1200&q=80')"></div>
        <div class="honeymoon-body">
          <h3> Kashmir Honeymoon</h3>
          <div class="route">Srinagar · Gulmarg · Pahalgam</div>
          <ul>
            <li>5 Nights / 6 Days</li>
            <li>Comfortable hotel stays</li>
            <li>Private transfers</li>
            <li>Breakfast</li>
            <li>Dal Lake Shikara experience</li>
          </ul>
          <div class="price">Custom Quote <span class="price-note">Based on travel date & hotel category</span></div>
          <a class="btn small" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20a%20Kashmir%20honeymoon%20package.%20Please%20send%20me%20a%20quote.">Get Kashmir Quote</a>
        </div>
      </div>

      <div class="honeymoon-card">
        <div class="honeymoon-img" style="background-image:url('https://images.unsplash.com/photo-1661174607003-d9d36388c916?auto=format&fit=crop&w=1200&q=80')"></div>
        <div class="honeymoon-body">
          <h3> Kerala Honeymoon</h3>
          <div class="route">Munnar · Thekkady · Alleppey</div>
          <ul>
            <li>4 Nights / 5 Days</li>
            <li>Romantic stays</li>
            <li>Private AC transfers</li>
            <li>Breakfast</li>
            <li>Houseboat experience</li>
          </ul>
          <div class="price">Custom Quote <span class="price-note">Customized to your budget</span></div>
          <a class="btn small" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20a%20Kerala%20honeymoon%20package.%20Please%20send%20me%20a%20quote.">Get Kerala Quote</a>
        </div>
      </div>

      <div class="honeymoon-card">
        <div class="honeymoon-img" style="background-image:url('https://images.unsplash.com/photo-1759675592313-cc0facf4b078?auto=format&fit=crop&w=1200&q=80')"></div>
        <div class="honeymoon-body">
          <h3> Maldives Honeymoon</h3>
          <div class="route">Resort Island Escape</div>
          <ul>
            <li>3 Nights / 4 Days</li>
            <li>Resort accommodation</li>
            <li>Speedboat transfers</li>
            <li>Meals as per resort plan</li>
            <li>Romantic island experience</li>
          </ul>
          <div class="price">Custom Quote <span class="price-note">Based on resort & travel date</span></div>
          <a class="btn small" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20a%20Maldives%20honeymoon%20package.%20Please%20send%20me%20a%20quote.">Get Maldives Quote</a>
        </div>
      </div>

      <div class="honeymoon-card">
        <div class="honeymoon-img" style="background-image:url('https://images.unsplash.com/photo-1518925591184-152905776d4f?auto=format&fit=crop&w=1200&q=80')"></div>
        <div class="honeymoon-body">
          <h3> Bali Honeymoon</h3>
          <div class="route">Ubud · Kuta · Nusa Dua</div>
          <ul>
            <li>5 Nights / 6 Days</li>
            <li>Handpicked hotel stays</li>
            <li>Private sightseeing</li>
            <li>Breakfast</li>
            <li>Couple experiences</li>
          </ul>
          <div class="price">Custom Quote <span class="price-note">Based on travel date & inclusions</span></div>
          <a class="btn small" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20a%20Bali%20honeymoon%20package.%20Please%20send%20me%20a%20quote.">Get Bali Quote</a>
        </div>
      </div>

      <div class="honeymoon-card">
        <div class="honeymoon-img" style="background-image:url('https://images.unsplash.com/photo-1768737817105-756189e1251c?auto=format&fit=crop&w=1200&q=80')"></div>
        <div class="honeymoon-body">
          <h3> Mauritius Honeymoon</h3>
          <div class="route">Island Tours · Beaches · Resorts</div>
          <ul>
            <li>4 Nights / 5 Days</li>
            <li>Resort accommodation</li>
            <li>Island sightseeing</li>
            <li>Breakfast</li>
            <li>Romantic experiences</li>
          </ul>
          <div class="price">Custom Quote <span class="price-note">Customized for couples</span></div>
          <a class="btn small" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20a%20Mauritius%20honeymoon%20package.%20Please%20send%20me%20a%20quote.">Get Mauritius Quote</a>
        </div>
      </div>

      <div class="honeymoon-card">
        <div class="honeymoon-img" style="background-image:url('https://images.unsplash.com/photo-1769679863653-f678115696eb?auto=format&fit=crop&w=1200&q=80')"></div>
        <div class="honeymoon-body">
          <h3> Thailand Honeymoon</h3>
          <div class="route">Phuket · Krabi · Bangkok</div>
          <ul>
            <li>5 Nights / 6 Days</li>
            <li>Comfortable hotel stays</li>
            <li>Private transfers</li>
            <li>Island tours</li>
            <li>Couple-friendly experiences</li>
          </ul>
          <div class="price">Custom Quote <span class="price-note">Based on dates & hotel category</span></div>
          <a class="btn small" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20a%20Thailand%20honeymoon%20package.%20Please%20send%20me%20a%20quote.">Get Thailand Quote</a>
        </div>
      </div>

    </div>
  </div>
</section>

<section class="features">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">Why travel with us</div>
      <h2>Support from planning to return.</h2>
    </div>

    <div class="feature-grid">
      <div class="feature"><div class="num">01</div><h3>Personalized Planning</h3><p>Every trip can be planned around your preferences, dates and budget.</p></div>
      <div class="feature"><div class="num">02</div><h3>Handpicked Stays</h3><p>We help you choose comfortable hotels and resorts suited to your journey.</p></div>
      <div class="feature"><div class="num">03</div><h3>Transparent Pricing</h3><p>Clear package inclusions so you know what your holiday covers.</p></div>
      <div class="feature"><div class="num">04</div><h3>Private Transfers</h3><p>Comfortable transportation options for a smoother travel experience.</p></div>
      <div class="feature"><div class="num">05</div><h3>Travel Support</h3><p>Assistance before and during your trip whenever you need it.</p></div>
      <div class="feature"><div class="num">06</div><h3>Honeymoon Focus</h3><p>Romantic itineraries and experiences designed especially for couples.</p></div>
    </div>
  </div>
</section>

<section class="trust-strip">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">Travel with confidence</div>
      <h2>Simple planning. Thoughtful journeys.</h2>
    </div>
    <div class="trust-grid">
      <div class="trust-item"><b>Since 2021</b><span>Serving travellers with holiday planning and support.</span></div>
      <div class="trust-item"><b>Customized Trips</b><span>Packages can be adjusted to suit your travel style.</span></div>
      <div class="trust-item"><b>Direct Assistance</b><span>Speak with OK Holidays directly for your trip planning.</span></div>
      <div class="trust-item"><b>India & Worldwide</b><span>Domestic and international holiday options.</span></div>
    </div>
  </div>
</section>

<section id="packages">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">India Tours</div>
      <h2>Explore India.</h2>
      <p class="lead">Selected packages from Kerala and destinations across India.</p>
    </div>

    <div class="filters">
      <button class="filter active" data-filter="all">All</button>
      <button class="filter" data-filter="kerala">Kerala</button>
      <button class="filter" data-filter="india">India</button>
    </div>

    <div class="package-grid">
      <div class="package" data-cat="kerala"><h3>Kerala Package</h3><div class="route">Cochin · Munnar · Alleppey · Cochin</div><ul><li>03 nights accommodation</li><li>Breakfast at all hotels</li><li>All food in houseboat</li><li>Exclusive AC cab for transfers & sightseeing</li><li>Experienced Hindi/English-speaking driver</li><li>Arrival/departure assistance</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20the%20Kerala%20Package.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package" data-cat="kerala"><h3>Premium Kerala Package</h3><div class="route">Cochin · Munnar · Thekkady · Houseboat · Cochin</div><ul><li>05 nights accommodation</li><li>Breakfast at all hotels</li><li>Spice plantation & tea tasting</li><li>Wildlife boating and elephant ride</li><li>Kalari martial arts show</li><li>AC Innova transportation</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20the%20Premium%20Kerala%20Package.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package" data-cat="kerala"><h3>Kerala Family Package</h3><div class="route">Cochin · Munnar · Thekkady · Houseboat · Kovalam · Trivandrum</div><ul><li>07 nights accommodation</li><li>Two rooms in mentioned hotels</li><li>Breakfast at all hotels</li><li>All meals in AC deluxe houseboat</li><li>AC Innova transportation</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20the%20Kerala%20Family%20Package.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package" data-cat="kerala"><h3>Wayanad Honeymoon</h3><div class="route">Wayanad · Calicut</div><ul><li>02 nights accommodation</li><li>Daily breakfast, lunch & dinner</li><li>AC Innova transportation</li><li>Wayanad & Calicut sightseeing</li><li>English-speaking driver</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20the%20Wayanad%20Honeymoon%20package.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package" data-cat="kerala"><h3>Kerala Ayurveda & Wellness</h3><div class="route">Cochin · Munnar · Thekkady · Kumarakom · Alleppey · Kovalam</div><ul><li>10 nights accommodation</li><li>Houseboat with all meals</li><li>Yoga & meditation</li><li>Village walk & guided trekking</li><li>Ayurveda treatment</li><li>AC vehicle & driver</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20the%20Kerala%20Ayurveda%20%26%20Wellness%20package.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package" data-cat="india"><h3>Golden Triangle</h3><div class="route">Delhi · Agra · Jaipur</div><ul><li>04 nights accommodation</li><li>Delhi sightseeing & UNESCO sites</li><li>Taj Mahal & Agra city tour</li><li>Fatehpur Sikri</li><li>Jaipur sights and local bazaars</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20the%20Golden%20Triangle%20package.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package" data-cat="india"><h3>Colours of Rajasthan</h3><div class="route">Jodhpur · Jaisalmer · Bikaner · Jaipur</div><ul><li>05 nights accommodation</li><li>Blue City & Mehrangarh Fort</li><li>Jaisalmer sightseeing</li><li>Bikaner camel experience</li><li>Jaipur Hawa Mahal</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20the%20Rajasthan%20package.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package" data-cat="india"><h3>Shimla Manali</h3><div class="route">Shimla · Manali · Kullu · Delhi</div><ul><li>05 nights accommodation</li><li>Delhi pickup options</li><li>Breakfast and dinner</li><li>Exclusive vehicle for transfers & sightseeing</li><li>Applicable taxes</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20the%20Shimla%20Manali%20package.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package" data-cat="india"><h3>Andaman</h3><div class="route">2N Port Blair · 2N Havelock Island</div><ul><li>04 nights accommodation</li><li>Daily buffet breakfast</li><li>Private AC car with chauffeur</li><li>Private cruise or government ferry</li><li>24-hour on-call assistance</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20the%20Andaman%20package.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package" data-cat="india"><h3>Best of Kashmir</h3><div class="route">Srinagar · Sonmarg · Gulmarg · Pahalgam</div><ul><li>Srinagar sightseeing</li><li>Gulmarg Gondola Cable Car</li><li>Pahalgam sightseeing</li><li>Apple Valley & Aru Valley</li><li>Shikara ride on Dal Lake</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20the%20Best%20of%20Kashmir%20package.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package" data-cat="india"><h3>Sikkim · Darjeeling · Gangtok</h3><div class="route">Gangtok · Darjeeling</div><ul><li>3N Gangtok + 2N Darjeeling</li><li>Changu Lake & Baba Mandir</li><li>Rumtek Monastery</li><li>Tiger Hill & Batasia Loop</li><li>Peace Pagoda & Himalayan attractions</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20the%20Sikkim%20Darjeeling%20package.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package" data-cat="india"><h3>Goa</h3><div class="route">03 Nights · North & South Goa</div><ul><li>North Goa sightseeing</li><li>Fort Aguada & beaches</li><li>South Goa temples & churches</li><li>Panjim & Dona Paula</li><li>Water sports available at own cost</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20the%20Goa%20package.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>
    </div>
  </div>
</section>

<section id="international" style="background:#fff">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">International Holidays</div>
      <h2>See the world beyond India.</h2>
      <p class="lead">International options include Southeast Asia, the Middle East, island escapes and European holidays.</p>
    </div>

    <div class="package-grid">
      <div class="package"><h3>Singapore</h3><div class="route">3 nights</div><ul><li>Daily breakfast</li><li>Singapore City Tour with Flyer</li><li>Gardens By the Bay</li><li>Night Safari</li><li>Universal Studios & S.E.A. Aquarium</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Singapore.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Malaysia</h3><div class="route">Kuala Lumpur · Genting Highlands</div><ul><li>2 nights Kuala Lumpur</li><li>1 night Genting Highlands</li><li>City tour & Putrajaya</li><li>Cable car ride</li><li>Airport & hotel transfers</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Malaysia.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Thailand</h3><div class="route">Pattaya · Bangkok</div><ul><li>2 nights Pattaya + 1 Bangkok</li><li>Alcazar Show</li><li>Coral Island tour with lunch</li><li>Safari World with Marine Park</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Thailand.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Dubai</h3><div class="route">3 nights</div><ul><li>Airport transfers & breakfast</li><li>Dhow cruise with buffet dinner</li><li>Desert Safari with BBQ</li><li>Dubai city tour</li><li>Burj Khalifa & Miracle Garden</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Dubai.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Bali</h3><div class="route">Island escape</div><ul><li>Sunset dinner cruise for two</li><li>Kintamani & Ubud tour</li><li>Tanah Lot Temple</li><li>Water sports at Tanjung Benoa</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Bali.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Maldives</h3><div class="route">03 nights</div><ul><li>Resort accommodation</li><li>Return speedboat transfers</li><li>Breakfast, lunch & dinner</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Maldives.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Romantic Mauritius</h3><div class="route">04 nights</div><ul><li>North & South Island tours</li><li>Tea factory visit</li><li>Ile Aux Cerf island tour</li><li>Honeymoon hotel freebies</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Mauritius.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Phuket</h3><div class="route">03 nights</div><ul><li>Phuket city tour</li><li>Phi Phi Island tour with lunch</li><li>Fantasia Show with dinner</li><li>James Bond Island tour</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Phuket.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Langkawi</h3><div class="route">03 nights</div><ul><li>Island hopping</li><li>Sky Bridge & cable car</li><li>Mangrove tour</li><li>Sunset dinner cruise</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Langkawi.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Seychelles</h3><div class="route">04 nights</div><ul><li>Island hopping to Praslin & La Digue</li><li>Victoria city</li><li>Natural History Museum & Clock Tower</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Seychelles.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>London City Break</h3><div class="route">04 nights</div><ul><li>Daily breakfast</li><li>Hop-on hop-off + London Eye</li><li>Madame Tussauds</li><li>Warner Bros Studio</li><li>LEGOLAND</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20London.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Swiss Paris</h3><div class="route">06 nights · Paris · Lucerne · Interlaken</div><ul><li>Paris sightseeing & Seine cruise</li><li>Louvre & Eiffel Tower</li><li>Zurich & Lucerne sightseeing</li><li>Mt Titlis Rotair</li><li>Swiss Travel Pass</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Swiss%20Paris.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Best of Europe</h3><div class="route">12 nights</div><ul><li>France</li><li>Belgium</li><li>Germany</li><li>Switzerland & Liechtenstein</li><li>Austria, Italy & Vatican</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Best%20of%20Europe.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Greece · Turkey</h3><div class="route">7 nights</div><ul><li>Istanbul tours</li><li>Santorini & Athens</li><li>Bed & breakfast accommodation</li><li>Airport transfers</li><li>Flights/ferry tickets in program</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Greece%20and%20Turkey.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>

      <div class="package"><h3>Spain · Portugal</h3><div class="route">8 nights</div><ul><li>Accommodation with breakfast</li><li>Tagus River sunset cruise</li><li>Madrid hop-on hop-off</li><li>Flamenco show</li><li>Barcelona highlights</li></ul><a class="package-cta" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27m%20interested%20in%20Spain%20and%20Portugal.%20Please%20send%20me%20a%20quote.">Get Quote →</a></div>
    </div>
  </div>
</section>

<section>
  <div class="container">
    <div class="banner">
      <div>
        <div class="eyebrow">Ready to travel?</div>
        <h2>Let's plan your next escape.</h2>
        <p>Tell us where you want to go and we'll help you turn the idea into a holiday.</p>
      </div>
      <a class="btn primary" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27d%20like%20help%20planning%20a%20holiday.">WhatsApp Us</a>
    </div>
  </div>
</section>

<section class="contact" id="contact">
  <div class="container contact-grid">
    <div>
      <div class="section-head">
        <div class="eyebrow">Contact us</div>
        <h2>Start your journey with OK Holidays.</h2>
        <p class="lead">For bookings and enquiries, reach out directly or request an appointment.</p>
      </div>
      <div class="buttons">
        <a class="btn" href="https://forms.gle/Zmx8ttP6BYkj5ArA7">Book / Request Appointment</a>
        <a class="btn" style="background:var(--gold);color:var(--ink)" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27d%20like%20to%20make%20an%20enquiry.">WhatsApp Enquiry</a>
      </div>
    </div>

    <div class="contact-card">
      <div class="contact-item"><small>Location</small>No. 3, LL Buildings<br>Opp. Club Mahendra Road, Poovar</div>
      <div class="contact-item"><small>Email</small><a href="mailto:okholidays7@gmail.com">okholidays7@gmail.com</a></div>
      <div class="contact-item"><small>Contact</small><a href="tel:+918086066676">80 - 86 - 06 - 66 - 76</a></div>
    </div>
  </div>
</section>

<a class="floating-whatsapp" href="https://wa.me/918086066676?text=Hi%20OK%20Holidays%2C%20I%27d%20like%20to%20plan%20a%20trip." aria-label="WhatsApp OK Holidays">💬 WhatsApp</a>

<footer>
  <div class="container footer-inner">
    <div class="footer-logo">OK HOLIDAYS</div>
    <div>Travel the world through OK.</div>
    <div>© 2026 OK Holidays</div>
  </div>
</footer>

<script>
const buttons=document.querySelectorAll('.filter');
const cards=document.querySelectorAll('.package[data-cat]');

buttons.forEach(btn=>{
  btn.addEventListener('click',()=>{
    buttons.forEach(b=>b.classList.remove('active'));
    btn.classList.add('active');
    const f=btn.dataset.filter;
    cards.forEach(c=>{
      c.style.display=(f==='all'||c.dataset.cat===f)?'block':'none';
    });
  });
});

const menuToggle=document.getElementById('menuToggle');
const mobileMenu=document.getElementById('mobileMenu');

menuToggle.addEventListener('click',()=>{
  const isOpen=mobileMenu.style.display==='block';
  mobileMenu.style.display=isOpen?'none':'block';
  menuToggle.textContent=isOpen?'☰':'✕';
});

document.querySelectorAll('#mobileMenu a').forEach(link=>{
  link.addEventListener('click',()=>{
    mobileMenu.style.display='none';
    menuToggle.textContent='☰';
  });
});
</script>

</body>
</html>
