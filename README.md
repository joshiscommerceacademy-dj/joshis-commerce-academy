# joshis-commerce-academy
Joshi's Commerce Academy 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Joshi's Commerce Academy - Commerce coaching from 11th Commerce to TY B.Com in Ahilyanagar. Personal attention, doubt sessions, tests, career guidance and competitive exam guidance.">
<title>Joshi's Commerce Academy | Ahilyanagar</title>
<style>
:root{
  --navy:#071b4b; --blue:#123a91; --gold:#f7c515; --gold2:#ffdc4a;
  --ink:#101828; --muted:#667085; --bg:#f7f9fc; --white:#fff;
  --shadow:0 18px 50px rgba(7,27,75,.12); --radius:24px;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;color:var(--ink);background:var(--bg);line-height:1.6}
a{text-decoration:none;color:inherit}
img{max-width:100%;display:block}
.container{width:min(1160px,92%);margin:auto}
header{position:sticky;top:0;z-index:50;background:rgba(255,255,255,.94);backdrop-filter:blur(14px);border-bottom:1px solid #e8edf5}
.nav{height:76px;display:flex;align-items:center;justify-content:space-between;gap:24px}
.brand{display:flex;align-items:center;gap:12px;font-weight:900;color:var(--navy);letter-spacing:-.4px}
.brand img{width:50px;height:50px;object-fit:contain;border-radius:12px}
.brand span{font-size:17px}
nav{display:flex;align-items:center;gap:24px;font-size:14px;font-weight:750}
nav a{color:#344054}
nav a:hover{color:var(--blue)}
.menu{display:none;background:none;border:0;font-size:28px;color:var(--navy)}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:9px;border-radius:13px;padding:13px 20px;font-weight:800;border:1px solid transparent;transition:.25s}
.btn-primary{background:var(--gold);color:var(--navy);box-shadow:0 10px 22px rgba(247,197,21,.25)}
.btn-primary:hover{transform:translateY(-2px);background:var(--gold2)}
.btn-dark{background:var(--navy);color:white}
.btn-outline{border-color:#d8dfeb;background:#fff;color:var(--navy)}
.hero{background:
 radial-gradient(circle at 78% 25%,rgba(247,197,21,.24),transparent 25%),
 linear-gradient(135deg,#061741 0%,#0b2868 60%,#123a91 100%);
 color:white;padding:78px 0 70px;overflow:hidden;position:relative}
.hero:after{content:"";position:absolute;right:-180px;bottom:-250px;width:560px;height:560px;border:90px solid rgba(247,197,21,.13);border-radius:50%}
.hero-grid{display:grid;grid-template-columns:1.08fr .92fr;gap:50px;align-items:center;position:relative;z-index:1}
.eyebrow{display:inline-flex;gap:8px;align-items:center;background:rgba(255,255,255,.1);border:1px solid rgba(255,255,255,.18);padding:8px 13px;border-radius:999px;color:#ffe56e;font-weight:800;font-size:13px}
.hero h1{font-size:clamp(42px,6vw,72px);line-height:1.02;margin:20px 0 18px;letter-spacing:-2.5px}
.hero h1 span{color:var(--gold)}
.hero p{font-size:18px;color:#dbe6ff;max-width:650px}
.hero-actions{display:flex;gap:12px;flex-wrap:wrap;margin:28px 0 30px}
.trust{display:flex;gap:26px;flex-wrap:wrap;color:#dbe6ff;font-size:14px}
.trust strong{display:block;color:white;font-size:22px}
.hero-card{background:#fff;border-radius:28px;padding:10px;box-shadow:0 25px 80px rgba(0,0,0,.3);transform:rotate(1deg)}
.hero-card img{border-radius:20px;width:100%;height:470px;object-fit:cover;object-position:center}
.section{padding:82px 0}
.section-head{text-align:center;max-width:760px;margin:0 auto 42px}
.kicker{color:var(--blue);font-weight:900;text-transform:uppercase;letter-spacing:1.7px;font-size:12px}
.section h2{font-size:clamp(30px,4vw,46px);line-height:1.12;color:var(--navy);margin:8px 0 12px}
.section-head p{color:var(--muted)}
.stats{margin-top:-28px;position:relative;z-index:3}
.stat-grid{display:grid;grid-template-columns:repeat(4,1fr);background:#fff;border:1px solid #e6ebf3;border-radius:22px;box-shadow:var(--shadow);overflow:hidden}
.stat{padding:24px;text-align:center;border-right:1px solid #edf0f5}
.stat:last-child{border-right:0}.stat strong{font-size:30px;color:var(--navy);display:block}.stat span{font-size:13px;color:var(--muted);font-weight:700}
.about{display:grid;grid-template-columns:.9fr 1.1fr;gap:60px;align-items:center}
.about-visual{position:relative}
.about-visual img{width:100%;height:470px;object-fit:cover;border-radius:28px;box-shadow:var(--shadow)}
.badge{position:absolute;right:-18px;bottom:25px;background:var(--gold);color:var(--navy);padding:18px 20px;border-radius:18px;font-weight:900;box-shadow:var(--shadow)}
.about-copy h3{font-size:29px;color:var(--navy);margin-bottom:14px}
.about-copy p{color:#475467;margin-bottom:16px}
.quote{border-left:4px solid var(--gold);background:#fff;padding:18px 20px;border-radius:0 15px 15px 0;color:var(--navy);font-weight:800;margin:24px 0}
.courses{background:#fff}
.course-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:16px}
.course{background:linear-gradient(180deg,#fff,#f6f8fc);border:1px solid #e6ebf3;border-radius:20px;padding:24px 17px;min-height:180px;display:flex;flex-direction:column;justify-content:space-between;box-shadow:0 8px 25px rgba(7,27,75,.05);transition:.25s}
.course:hover{transform:translateY(-6px);box-shadow:var(--shadow)}
.icon{width:50px;height:50px;border-radius:15px;background:#eaf0ff;color:var(--blue);display:grid;place-items:center;font-size:25px}
.course:nth-child(even) .icon{background:#fff4c9;color:#a67b00}
.course h3{font-size:19px;color:var(--navy)}
.course p{font-size:13px;color:var(--muted)}
.subject-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:18px}
.subject{background:var(--navy);color:white;border-radius:20px;padding:28px;position:relative;overflow:hidden}
.subject:after{content:"";position:absolute;width:100px;height:100px;border:22px solid rgba(247,197,21,.16);border-radius:50%;right:-35px;top:-35px}
.subject .icon{background:rgba(255,255,255,.1);color:var(--gold);margin-bottom:20px}
.subject h3{font-size:22px}.subject p{color:#cbd8f6;font-size:13px;margin-top:4px}
.feature-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
.feature{background:white;border:1px solid #e5eaf2;border-radius:18px;padding:20px;display:flex;gap:16px;align-items:flex-start}
.feature .num{min-width:40px;height:40px;border-radius:12px;background:var(--gold);display:grid;place-items:center;font-weight:950;color:var(--navy)}
.feature h3{font-size:17px;color:var(--navy)}.feature p{font-size:13px;color:var(--muted)}
.highlight{background:linear-gradient(135deg,#061741,#123a91);color:white;border-radius:30px;padding:45px;display:grid;grid-template-columns:1.4fr .6fr;gap:30px;align-items:center;box-shadow:var(--shadow)}
.highlight h2{color:white}.highlight p{color:#dbe6ff}.highlight .big{font-size:50px;font-weight:950;color:var(--gold);text-align:center}
.gallery{display:grid;grid-template-columns:repeat(4,1fr);gap:14px}
.gallery button{border:0;padding:0;background:none;cursor:pointer;overflow:hidden;border-radius:18px}
.gallery img{width:100%;height:260px;object-fit:cover;transition:.35s}
.gallery button:hover img{transform:scale(1.05)}
.contact{background:#fff}
.contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:28px}
.contact-card{border:1px solid #e3e8f1;border-radius:24px;padding:30px;background:#fbfcfe}
.contact-item{display:flex;gap:15px;margin:20px 0}.contact-item .ci{min-width:44px;height:44px;border-radius:14px;background:#eef3ff;color:var(--blue);display:grid;place-items:center}
.contact-item h4{color:var(--navy);margin-bottom:2px}.contact-item p,.contact-item a{color:#667085;font-size:14px}
.socials{display:flex;gap:10px;flex-wrap:wrap;margin-top:20px}
footer{background:#061741;color:#dbe6ff;padding:42px 0 25px}
.footer-grid{display:grid;grid-template-columns:1.3fr .7fr .7fr;gap:30px}
footer h3{color:white;margin-bottom:10px}footer p,footer a{font-size:14px;color:#b9c7e6}footer a:hover{color:var(--gold)}
.footer-bottom{border-top:1px solid rgba(255,255,255,.1);margin-top:30px;padding-top:18px;text-align:center;font-size:12px;color:#93a5cc}
.whatsapp{position:fixed;right:20px;bottom:20px;z-index:60;width:58px;height:58px;border-radius:50%;display:grid;place-items:center;background:#20c463;color:white;font-size:27px;box-shadow:0 14px 30px rgba(0,0,0,.2)}
.modal{position:fixed;inset:0;background:rgba(2,9,28,.86);z-index:100;display:none;align-items:center;justify-content:center;padding:20px}
.modal.open{display:flex}.modal img{max-height:90vh;max-width:94vw;border-radius:16px}.close{position:absolute;right:24px;top:18px;color:white;background:none;border:0;font-size:40px;cursor:pointer}
@media(max-width:950px){
 nav{display:none}.menu{display:block}
 nav.open{display:flex;position:absolute;top:76px;left:0;right:0;background:white;padding:18px 4%;flex-direction:column;align-items:flex-start;border-bottom:1px solid #e8edf5}
 .hero-grid,.about,.contact-grid,.highlight{grid-template-columns:1fr}
 .hero-card{max-width:650px;margin:auto}.hero-card img{height:420px}
 .course-grid{grid-template-columns:repeat(3,1fr)}.subject-grid{grid-template-columns:repeat(2,1fr)}
 .gallery{grid-template-columns:repeat(2,1fr)}
 .footer-grid{grid-template-columns:1fr 1fr}
}
@media(max-width:600px){
 .nav{height:68px}.brand span{font-size:14px}.brand img{width:44px;height:44px}
 .hero{padding:55px 0}.hero h1{font-size:43px}.hero p{font-size:16px}
 .hero-card img{height:330px}.section{padding:60px 0}
 .stat-grid{grid-template-columns:repeat(2,1fr)}.stat{border-bottom:1px solid #edf0f5}.stat:nth-child(2){border-right:0}
 .about-visual img{height:340px}.badge{right:10px}
 .course-grid,.subject-grid,.feature-grid,.gallery{grid-template-columns:1fr}
 .gallery img{height:340px}.highlight{padding:30px}.highlight .big{text-align:left}
 .footer-grid{grid-template-columns:1fr}
}
</style>
</head>
<body>
<header>
  <div class="container nav">
    <a class="brand" href="#home">
      <img src="assets/logo.jpg" alt="JCA Logo">
      <span>JOSHI'S COMMERCE ACADEMY</span>
    </a>
    <button class="menu" aria-label="Open menu" onclick="toggleNav()">☰</button>
    <nav id="nav">
      <a href="#home">Home</a><a href="#about">About</a><a href="#courses">Courses</a>
      <a href="#features">Why JCA</a><a href="#gallery">Gallery</a><a href="#contact">Contact</a>
      <a class="btn btn-primary" href="tel:+917350476625">Call Now</a>
    </nav>
  </div>
</header>

<main>
<section class="hero" id="home">
  <div class="container hero-grid">
    <div>
      <div class="eyebrow">🎓 Since 2017 • Commerce Education</div>
      <h1>Build Knowledge.<br><span>Gain Confidence.</span><br>Achieve Success.</h1>
      <p>Quality Commerce education with personal attention, proper guidance and continuous support — from 11th Commerce to TY B.Com.</p>
      <div class="hero-actions">
        <a class="btn btn-primary" href="tel:+917350476625">📞 Enquire Now</a>
        <a class="btn btn-outline" href="https://wa.me/917350476625?text=Hello%20Joshi's%20Commerce%20Academy,%20I%20want%20to%20know%20about%20admissions." target="_blank">💬 WhatsApp Us</a>
      </div>
      <div class="trust">
        <div><strong>2017</strong>Journey Started</div>
        <div><strong>100%</strong>12th Board Passing* </div>
        <div><strong>5 Levels</strong>11th to TY B.Com</div>
      </div>
    </div>
    <div class="hero-card">
      <img src="assets/admission-open.jpg" alt="Joshi's Commerce Academy admission poster">
    </div>
  </div>
</section>
