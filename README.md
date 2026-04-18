<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="PearlSmile Dental – Award-winning cosmetic & general dentistry on Harley Street, London. Implants, Invisalign®, whitening & emergency care. Book your free consultation today.">
<meta name="keywords" content="dentist London, cosmetic dentistry, teeth whitening, dental implants, Invisalign, emergency dentist, Harley Street dentist">
<meta property="og:title" content="PearlSmile Dental – Where Confidence Begins">
<meta property="og:description" content="Modern dentistry with a warm approach. Free consultations, 0% finance, same-day emergencies.">
<meta property="og:image" content="https://images.unsplash.com/photo-1629909613654-28e377c37b09?w=1200&q=80">
<meta property="og:type" content="website">
<meta name="theme-color" content="#060E1E">
<title>PearlSmile Dental | Award-Winning Cosmetic Dentist London</title>
<link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='85'>🦷</text></svg>">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;0,700;1,300;1,400&family=DM+Sans:ital,wght@0,300;0,400;0,500;0,600;1,400&family=Bebas+Neue&display=swap" rel="stylesheet">
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"Dentist","name":"PearlSmile Dental","url":"https://www.pearlsmiledental.com","telephone":"+442000000000","priceRange":"££","image":"https://images.unsplash.com/photo-1629909613654-28e377c37b09?w=1200","address":{"@type":"PostalAddress","streetAddress":"1 Harley Street","addressLocality":"London","addressRegion":"England","postalCode":"W1G 9QD","addressCountry":"GB"},"geo":{"@type":"GeoCoordinates","latitude":51.5194,"longitude":-0.1490},"openingHoursSpecification":[{"@type":"OpeningHoursSpecification","dayOfWeek":["Monday","Tuesday","Wednesday","Thursday","Friday"],"opens":"08:00","closes":"19:00"},{"@type":"OpeningHoursSpecification","dayOfWeek":["Saturday"],"opens":"09:00","closes":"15:00"}],"aggregateRating":{"@type":"AggregateRating","ratingValue":"4.9","reviewCount":"247","bestRating":"5"}}
</script>
<style>
:root {
  --night:#050C1A; --deep:#080F1E; --navy:#0A1628; --card:#0D1B30; --card2:#102040;
  --mint:#00DEB6; --gold:#C8A96E; --gold2:#E5C98A; --pearl:#F0E8DF;
  --white:#FFFFFF; --slate:#7A8FAA; --red:#E8344A;
  --border:rgba(0,222,182,0.12); --border2:rgba(0,222,182,0.22);
  --glow:0 0 40px rgba(0,222,182,0.28);
  --nav-h:72px; --ban-h:48px; --radius:10px;
  --ease:cubic-bezier(.16,1,.3,1);
}
*,*::before,*::after{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{background:var(--night);color:var(--pearl);font-family:'DM Sans',sans-serif;overflow-x:hidden;line-height:1.6;}
a{color:inherit;text-decoration:none;}
img{max-width:100%;display:block;height:auto;}
button{font-family:'DM Sans',sans-serif;}

/* SCROLL BAR */
#scroll-bar{position:fixed;top:0;left:0;height:2px;background:linear-gradient(90deg,var(--mint),var(--gold));z-index:9999;width:0;}

/* EMERGENCY BANNER */
#ebanner{position:sticky;top:0;z-index:950;height:var(--ban-h);background:var(--red);display:flex;align-items:center;justify-content:space-between;padding:0 60px;}
.ban-btn{color:#fff;font-size:.76rem;font-weight:800;letter-spacing:.06em;text-transform:uppercase;text-decoration:none;display:flex;align-items:center;gap:8px;transition:opacity .3s;}
.ban-btn:hover{opacity:0.8;}
.ban-ico{font-size:1.15rem;}
.ban-lbl{white-space:nowrap;}

/* NAV */
nav{position:sticky;top:var(--ban-h);z-index:900;height:var(--nav-h);display:flex;align-items:center;justify-content:space-between;padding:0 60px;background:rgba(5,12,26,.95);backdrop-filter:blur(24px);border-bottom:1px solid var(--border);}
.nav-address-btn{position:absolute;left:50%;transform:translateX(-50%);display:flex;align-items:center;gap:10px;background:rgba(255,255,255,.05);border:1px solid var(--border);padding:8px 16px;border-radius:30px;font-size:.8rem;color:var(--pearl);text-decoration:none;transition:all .3s ease;}
.nav-address-btn:hover{background:rgba(255,255,255,.1);border-color:var(--mint);transform:translate(-50%, -2px);}
.nav-address-btn .g-icon{color:#4285F4;font-weight:800;font-size:1rem;}
.nav-address-btn .clinic-icon{font-size:1rem;}
.nav-address-btn .stars{color:var(--gold);letter-spacing:1px;font-size:.8rem;}
@media(max-width:900px){.nav-address-btn .address-text,.nav-address-btn .stars{display:none;} .nav-address-btn{padding:6px 10px; position:static; transform:none;}}
.logo{font-family:'Cormorant Garamond',serif;font-size:1.7rem;font-weight:600;color:var(--white);display:flex;align-items:center;gap:5px;}
.logo em{font-style:normal;color:var(--mint);}
.logo-star{color:var(--gold);font-size:1.1rem;margin-left:3px;}
.nav-links{display:flex;align-items:center;gap:28px;}
.nav-links a{font-size:.78rem;font-weight:500;letter-spacing:.08em;text-transform:uppercase;color:var(--slate);transition:color .25s;white-space:nowrap;}
.nav-links a:hover{color:var(--mint);}
.nav-phone{color:var(--pearl)!important;}
.nav-phone::before{content:'📞 ';}
.nav-book{background:var(--mint);color:var(--night)!important;padding:10px 22px;border-radius:3px;font-weight:700!important;}
.nav-book:hover{background:var(--white)!important;box-shadow:var(--glow);}
.ham{display:none;flex-direction:column;gap:5px;background:none;border:none;cursor:pointer;padding:5px;}
.ham span{display:block;width:22px;height:2px;background:var(--pearl);border-radius:2px;transition:all .3s;}
.ham.open span:nth-child(1){transform:translateY(7px) rotate(45deg);}
.ham.open span:nth-child(2){opacity:0;}
.ham.open span:nth-child(3){transform:translateY(-7px) rotate(-45deg);}
.mob-menu{display:none;position:fixed;top:calc(var(--ban-h)+var(--nav-h));left:0;width:100%;z-index:890;background:rgba(5,12,26,.98);backdrop-filter:blur(20px);border-bottom:1px solid var(--border);flex-direction:column;padding:18px 24px 26px;}
.mob-menu.open{display:flex;}
.mob-menu a{padding:13px 0;color:var(--pearl);font-size:.95rem;font-weight:500;border-bottom:1px solid var(--border);transition:color .2s;}
.mob-menu a:hover{color:var(--mint);}
.mob-cta{margin-top:14px!important;background:var(--mint);color:var(--night)!important;padding:13px;border-radius:3px;text-align:center;font-weight:700!important;border-bottom:none!important;}

/* SHARED */
.pad{padding:90px 60px;}
.eyebrow{display:flex;align-items:center;gap:10px;font-size:.72rem;letter-spacing:.2em;text-transform:uppercase;color:var(--mint);margin-bottom:14px;}
.eyebrow::before{content:'';width:22px;height:1px;background:var(--mint);}
.section-h2{font-family:'Cormorant Garamond',serif;font-size:clamp(2rem,3.5vw,3.3rem);font-weight:300;color:var(--white);line-height:1.1;}
.section-h2 em{font-style:italic;color:var(--mint);}
.sec-head{display:flex;align-items:flex-end;justify-content:space-between;gap:20px;margin-bottom:54px;flex-wrap:wrap;}
.more-link{font-size:.78rem;color:var(--mint);letter-spacing:.09em;text-transform:uppercase;border-bottom:1px solid var(--border2);padding-bottom:3px;transition:all .25s;white-space:nowrap;}
.more-link:hover{border-color:var(--mint);}
.btn-primary{display:inline-block;background:var(--mint);color:var(--night);padding:14px 34px;border-radius:3px;font-size:.86rem;font-weight:700;letter-spacing:.05em;transition:all .4s var(--ease);}
.btn-primary:hover{background:var(--white);box-shadow:var(--glow);}
.reveal{opacity:0;transform:translateY(36px);transition:opacity .7s var(--ease),transform .7s var(--ease);}
.reveal.in{opacity:1;transform:translateY(0);}

/* HERO */
#hero{min-height:calc(100vh - var(--ban-h) - var(--nav-h));display:grid;grid-template-columns:1fr 1fr;align-items:stretch;position:relative;overflow:hidden;}
.hero-left{padding:80px 60px;display:flex;flex-direction:column;justify-content:center;position:relative;z-index:2;}
.hero-orb{position:absolute;inset:0;background:radial-gradient(ellipse 60% 70% at 30% 50%,rgba(0,222,182,.06),transparent 65%);pointer-events:none;}
.hero-grid{position:absolute;inset:0;opacity:.022;background-image:linear-gradient(var(--mint) 1px,transparent 1px),linear-gradient(90deg,var(--mint) 1px,transparent 1px);background-size:55px 55px;animation:gridMove 24s linear infinite;}
@keyframes gridMove{from{transform:translateY(0);}to{transform:translateY(55px);}}
.hero-right{position:absolute;inset:0;z-index:0;overflow:hidden;}
.hero-right img{width:100%;height:100%;object-fit:cover;object-position:center;}
.hero-right::after{content:'';position:absolute;inset:0;background:linear-gradient(90deg,var(--night) 0%,rgba(5,12,26,.8) 40%,rgba(5,12,26,.2) 100%);}
.hero-eyebrow{display:inline-flex;align-items:center;gap:8px;font-size:.7rem;letter-spacing:.22em;text-transform:uppercase;color:var(--mint);margin-bottom:28px;opacity:0;animation:fadeUp .7s .3s forwards;}
.hero-eyebrow::before{content:'';width:24px;height:1px;background:var(--mint);}
@keyframes fadeUp{from{opacity:0;transform:translateY(18px);}to{opacity:1;transform:translateY(0);}}
.hero-h1{font-family:'Cormorant Garamond',serif;font-size:clamp(2.8rem,5vw,5.2rem);font-weight:300;line-height:1.02;color:var(--white);margin-bottom:24px;}
.hero-h1 em{font-style:italic;color:var(--mint);}
.hline{display:block;overflow:hidden;}
.hline-inner{display:block;opacity:0;transform:translateY(100%);animation:slideIn .9s var(--ease) forwards;}
.hline:nth-child(1) .hline-inner{animation-delay:.5s;}
.hline:nth-child(2) .hline-inner{animation-delay:.65s;}
.hline:nth-child(3) .hline-inner{animation-delay:.8s;}
@keyframes slideIn{to{opacity:1;transform:translateY(0);}}
.hero-sub{font-size:.97rem;color:var(--slate);line-height:1.85;max-width:460px;margin-bottom:38px;opacity:0;animation:fadeUp .7s 1.05s forwards;}
.hero-btns{display:flex;gap:16px;align-items:center;flex-wrap:wrap;opacity:0;animation:fadeUp .7s 1.2s forwards;}
.btn-ghost-hero{display:flex;align-items:center;gap:10px;color:var(--pearl);font-size:.86rem;font-weight:500;transition:all .3s;}
.circle{width:38px;height:38px;border:1px solid var(--border2);border-radius:50%;display:flex;align-items:center;justify-content:center;transition:all .3s;}
.btn-ghost-hero:hover .circle{border-color:var(--mint);background:rgba(0,222,182,.1);transform:translateX(4px);}
.hero-trust{display:flex;gap:28px;margin-top:50px;opacity:0;animation:fadeUp .7s 1.4s forwards;flex-wrap:wrap;}
.trust-num{font-family:'Cormorant Garamond',serif;font-size:1.6rem;font-weight:600;color:var(--white);line-height:1;display:block;}
.trust-lbl{font-size:.71rem;color:var(--slate);text-transform:uppercase;letter-spacing:.08em;line-height:1.3;display:block;}
.trust-sep{width:1px;height:36px;background:var(--border2);}
.hero-badge{position:absolute;bottom:36px;right:clamp(16px, 4vw, 40px);z-index:10;background:var(--card);border:1px solid var(--border2);border-radius:12px;padding:14px 18px;animation:floatY 5s ease-in-out infinite;white-space:nowrap;}
.hero-badge .bn{font-family:'Cormorant Garamond',serif;font-size:1.8rem;font-weight:600;color:var(--mint);display:block;line-height:1;}
.hero-badge .bl{font-size:.68rem;color:var(--slate);letter-spacing:.1em;text-transform:uppercase;margin-top:3px;}
@keyframes floatY{0%,100%{transform:translateY(0);}50%{transform:translateY(-10px);}}

/* MARQUEE */
.marquee-wrap{padding:15px 0;background:var(--mint);overflow:hidden;}
.marquee-track{display:flex;gap:48px;animation:marquee 20s linear infinite;white-space:nowrap;}
@keyframes marquee{from{transform:translateX(0);}to{transform:translateX(-50%);}}
.m-item{display:flex;align-items:center;gap:10px;font-size:.76rem;font-weight:700;letter-spacing:.16em;text-transform:uppercase;color:var(--night);}
.m-dot{width:4px;height:4px;background:var(--night);border-radius:50%;flex-shrink:0;opacity:.5;}

/* STATS */
#stats{display:grid;grid-template-columns:repeat(4,1fr);border-top:1px solid var(--border);border-bottom:1px solid var(--border);}
.stat-cell{padding:52px 30px;text-align:center;border-right:1px solid var(--border);}
.stat-cell:last-child{border-right:none;}
.s-num{font-family:'Cormorant Garamond',serif;font-size:3.6rem;font-weight:600;color:var(--white);line-height:1;display:block;}
.s-num .acc{color:var(--mint);}
.s-lbl{font-size:.73rem;letter-spacing:.1em;text-transform:uppercase;color:var(--slate);margin-top:9px;display:block;}

/* SERVICES */
#services{padding:90px 60px;}
.svc-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:2px;}
.svc-card{background:var(--card);padding:44px 34px;border:1px solid var(--border);position:relative;overflow:hidden;cursor:pointer;transition:all .4s var(--ease);}
.svc-card::after{content:'';position:absolute;bottom:0;left:0;right:0;height:2px;background:linear-gradient(90deg,var(--mint),var(--gold));transform:scaleX(0);transform-origin:left;transition:transform .4s var(--ease);}
.svc-card:hover{background:var(--card2);transform:translateY(-7px);box-shadow:0 28px 60px rgba(0,0,0,.5);}
.svc-card:hover::after{transform:scaleX(1);}
.svc-icon{width:52px;height:52px;background:rgba(0,222,182,.08);border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:1.5rem;margin-bottom:26px;transition:all .4s;}
.svc-card:hover .svc-icon{background:rgba(0,222,182,.16);box-shadow:var(--glow);}
.svc-n{position:absolute;top:22px;right:22px;font-family:'Bebas Neue',sans-serif;font-size:3.4rem;color:rgba(255,255,255,.025);}
.svc-title{font-family:'Cormorant Garamond',serif;font-size:1.5rem;font-weight:600;color:var(--white);margin-bottom:12px;}
.svc-desc{font-size:.86rem;color:var(--slate);line-height:1.8;}
.svc-more{display:inline-flex;align-items:center;gap:7px;color:var(--mint);font-size:.76rem;letter-spacing:.1em;text-transform:uppercase;margin-top:22px;opacity:0;transition:opacity .3s;}
.svc-card:hover .svc-more{opacity:1;}

/* GALLERY / CAROUSEL */
#gallery{padding:90px 60px;background:linear-gradient(180deg,transparent,rgba(0,222,182,.02),transparent);}
.carousel-wrap{position:relative;margin-top:50px;}
.carousel-outer{overflow:hidden;border-radius:var(--radius);}
.carousel-track{display:flex;transition:transform .55s var(--ease);}
.c-slide{min-width:100%;display:grid;grid-template-columns:1fr 1fr;border:1px solid var(--border);border-radius:var(--radius);overflow:hidden;}
.slide-info{padding:50px 44px;display:flex;flex-direction:column;justify-content:center;background:var(--card);}
.slide-num{font-family:'Bebas Neue',sans-serif;font-size:5rem;color:rgba(0,222,182,.06);line-height:1;margin-bottom:-8px;}
.slide-eyebrow{font-size:.7rem;letter-spacing:.2em;text-transform:uppercase;color:var(--mint);margin-bottom:10px;}
.slide-title{font-family:'Cormorant Garamond',serif;font-size:2rem;font-weight:600;color:var(--white);margin-bottom:14px;line-height:1.15;}
.slide-desc{font-size:.88rem;color:var(--slate);line-height:1.8;margin-bottom:26px;}
.slide-tags{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:26px;}
.slide-tag{background:rgba(0,222,182,.08);border:1px solid var(--border2);border-radius:20px;padding:5px 14px;font-size:.73rem;color:var(--mint);}
.slide-cta{display:inline-flex;align-items:center;gap:8px;background:var(--mint);color:var(--night);padding:12px 24px;border-radius:3px;font-size:.82rem;font-weight:700;transition:all .4s var(--ease);align-self:flex-start;}
.slide-cta:hover{background:var(--white);}
/* Before/After interactive */
.ba-wrap{position:relative;aspect-ratio:1/1;overflow:hidden;cursor:ew-resize;user-select:none;-webkit-user-select:none;}
.ba-img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;object-position:center;}
.ba-before{clip-path:inset(0 50% 0 0);}
.ba-line{position:absolute;top:0;bottom:0;left:50%;width:3px;background:var(--white);z-index:4;transform:translateX(-50%);box-shadow:0 0 12px rgba(0,0,0,.5);}
.ba-handle{position:absolute;top:50%;left:50%;z-index:5;width:46px;height:46px;border-radius:50%;background:var(--white);transform:translate(-50%,-50%);display:flex;align-items:center;justify-content:center;box-shadow:0 2px 20px rgba(0,0,0,.4);color:var(--night);font-weight:700;font-size:.9rem;pointer-events:none;letter-spacing:-1px;}
.ba-lbl{position:absolute;bottom:14px;z-index:6;font-size:.68rem;font-weight:700;letter-spacing:.12em;text-transform:uppercase;padding:5px 12px;border-radius:3px;pointer-events:none;}
.ba-lbl.bef{left:14px;background:rgba(0,0,0,.7);color:var(--slate);}
.ba-lbl.aft{right:14px;background:var(--mint);color:var(--night);}
/* Carousel controls */
.carousel-ctrl{display:flex;align-items:center;justify-content:space-between;margin-top:26px;}
.carousel-dots{display:flex;gap:8px;align-items:center;}
.c-dot{width:8px;height:8px;border-radius:50%;background:var(--border2);border:none;cursor:pointer;transition:all .3s;padding:0;}
.c-dot.active{background:var(--mint);width:24px;border-radius:4px;}
.carousel-arrows{display:flex;gap:10px;}
.c-arr{width:46px;height:46px;border-radius:50%;border:1px solid var(--border2);background:var(--card);color:var(--pearl);font-size:1.1rem;cursor:pointer;transition:all .4s var(--ease);display:flex;align-items:center;justify-content:center;}
.c-arr:hover{border-color:var(--mint);background:rgba(0,222,182,.1);color:var(--mint);}
.slide-counter{font-size:.8rem;color:var(--slate);}
.slide-counter strong{color:var(--pearl);}

/* SMILE OF THE MONTH */
#sotm{padding:90px 60px;}
.sotm-layout{display:flex;flex-direction:column;gap:50px;margin-top:50px;}
.sotm-main{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);overflow:hidden;}
.sotm-imgs{display:grid;grid-template-columns:1fr 1fr;gap:3px;}
.sotm-img-big{grid-column:span 2;}
.sotm-img-big img{width:100%;height:380px;object-fit:cover;}
.sotm-img-half img{width:100%;height:180px;object-fit:cover;}
.sotm-body{padding:32px 34px;}
.sotm-award{display:inline-flex;align-items:center;gap:8px;background:linear-gradient(90deg,rgba(200,169,110,.15),rgba(200,169,110,.05));border:1px solid rgba(200,169,110,.3);border-radius:20px;padding:5px 14px;font-size:.7rem;font-weight:700;letter-spacing:.12em;text-transform:uppercase;color:var(--gold2);margin-bottom:16px;}
.sotm-patient{font-family:'Cormorant Garamond',serif;font-size:1.7rem;font-weight:600;color:var(--white);margin-bottom:6px;}
.sotm-tx{font-size:.78rem;color:var(--mint);letter-spacing:.1em;text-transform:uppercase;margin-bottom:16px;display:flex;align-items:center;gap:6px;}
.sotm-tx::before{content:'';width:14px;height:1px;background:var(--mint);}
.sotm-quote{font-family:'Cormorant Garamond',serif;font-size:1.06rem;font-style:italic;color:var(--pearl);line-height:1.75;opacity:.9;}
.sotm-stars{color:var(--gold);font-size:.9rem;letter-spacing:2px;margin-top:14px;}

.sotm-side{display:flex;gap:24px;overflow-x:auto;scroll-snap-type:x mandatory;scrollbar-width:none;-ms-overflow-style:none;padding-bottom:10px;}
.sotm-side::-webkit-scrollbar{display:none;}
.sotm-mini{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);overflow:hidden;display:flex;flex-direction:column;transition:all .4s var(--ease);flex:0 0 calc(50% - 12px);scroll-snap-align:start;}
.sotm-mini:hover{border-color:var(--mint);transform:translateY(-4px);}
.sotm-mini img{width:100%;aspect-ratio:1/1;height:auto;object-fit:cover;flex-shrink:0;}
.sotm-mini-body{padding:24px;display:flex;flex-direction:column;justify-content:center;flex:1;}
.sotm-mini-badge{font-size:.66rem;letter-spacing:.12em;text-transform:uppercase;color:var(--mint);margin-bottom:5px;}
.sotm-mini-name{font-family:'Cormorant Garamond',serif;font-size:1.1rem;font-weight:600;color:var(--white);margin-bottom:4px;}
.sotm-mini-tx{font-size:.76rem;color:var(--slate);}
.sotm-mini-stars{color:var(--gold);font-size:.72rem;margin-top:6px;}

.sotm-hz-card{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);padding:24px 34px;display:flex;align-items:center;justify-content:space-between;gap:20px;}
.sotm-hz-title{font-family:'Cormorant Garamond',serif;font-size:1.5rem;font-weight:600;color:var(--white);margin-bottom:6px;}
.sotm-hz-desc{font-size:.84rem;color:var(--slate);line-height:1.7;}
.sotm-hz-btn{font-size:.82rem;padding:12px 28px;white-space:nowrap;}

.doc-card{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);overflow:hidden;display:flex;flex-direction:column;height:100%;transition:all .4s var(--ease);}
.doc-card:hover{border-color:var(--mint);transform:translateY(-4px);}
.doc-card img{width:100%;height:220px;object-fit:cover;object-position:top;flex-shrink:0;}
.doc-body{padding:24px;display:flex;flex-direction:column;flex:1;}
.doc-ey{font-size:.66rem;letter-spacing:.14em;text-transform:uppercase;color:var(--mint);margin-bottom:6px;}
.doc-name{font-family:'Cormorant Garamond',serif;font-size:1.2rem;font-weight:600;color:var(--white);margin-bottom:4px;}
.doc-title{font-size:.77rem;color:var(--slate);margin-bottom:10px;}
.doc-quote{font-size:.82rem;color:var(--pearl);font-style:italic;line-height:1.65;opacity:.85;}

/* VIDEO STORIES */
#video-stories { padding: 90px 60px; background: linear-gradient(180deg, var(--night), rgba(0,222,182,0.02)); border-top: 1px solid var(--border); overflow: hidden; }
.vs-carousel-wrap { position: relative; margin-top: 30px; margin-left: -60px; margin-right: -60px; padding: 20px 60px; }
.vs-track { display: flex; gap: 24px; overflow-x: auto; scroll-snap-type: x mandatory; scroll-behavior: smooth; scrollbar-width: none; -ms-overflow-style: none; }
.vs-track::-webkit-scrollbar { display: none; }
.vs-card { flex: 0 0 calc(25% - 18px); scroll-snap-align: start; background: var(--card); border: 1px solid var(--border); border-radius: var(--radius); overflow: hidden; display: flex; flex-direction: column; transition: transform 0.4s var(--ease), box-shadow 0.4s var(--ease), border-color 0.4s; cursor: pointer; }
.vs-card:hover { transform: translateY(-8px); box-shadow: 0 20px 40px rgba(0,0,0,0.4); border-color: var(--mint); }
.vs-img-wrap { position: relative; aspect-ratio: 9/16; max-height: 340px; overflow: hidden; }
.vs-img-wrap img { width: 100%; height: 100%; object-fit: cover; transition: transform 0.7s var(--ease); }
.vs-card:hover .vs-img-wrap img { transform: scale(1.05); }
.vs-play { position: absolute; bottom: 14px; left: 14px; background: rgba(5, 12, 26, 0.65); backdrop-filter: blur(8px); border: 1px solid rgba(255,255,255,0.1); color: var(--white); font-size: 0.68rem; font-weight: 700; letter-spacing: 0.1em; padding: 7px 14px; border-radius: 20px; display: flex; align-items: center; gap: 8px; z-index: 2; transition: all 0.3s; text-transform: uppercase; }
.vs-play::before { content: '▶'; color: var(--mint); font-size: 0.75rem; }
.vs-card:hover .vs-play { background: var(--mint); color: var(--night); border-color: var(--mint); }
.vs-card:hover .vs-play::before { color: var(--night); }
.vs-body { padding: 22px 24px; display: flex; flex-direction: column; flex: 1; }
.vs-name { font-family: 'Cormorant Garamond', serif; font-size: 1.45rem; font-weight: 600; color: var(--white); margin-bottom: 20px; }
.vs-row { display: flex; justify-content: space-between; align-items: center; padding: 12px 0; border-top: 1px solid var(--border); font-size: 0.8rem; }
.vs-lbl { font-weight: 700; color: var(--pearl); }
.vs-val { color: var(--slate); }

@media(max-width: 1100px) {
  .vs-carousel-wrap { margin-left: -36px; margin-right: -36px; padding: 20px 36px; }
  .vs-card { flex: 0 0 calc(33.333% - 16px); }
}
@media(max-width: 900px) {
  .sotm-layout{gap:30px;}
  .sotm-mini { flex: 0 0 calc(50% - 12px); }
  .vs-carousel-wrap { margin-left: -22px; margin-right: -22px; padding: 10px 22px; }
  .vs-card { flex: 0 0 calc(50% - 12px); }
}
@media(max-width: 600px) {
  .vs-carousel-wrap { margin-left: -16px; margin-right: -16px; padding: 10px 16px; }
  .vs-card { flex: 0 0 75%; }
  .vs-track { gap: 14px; }
}

/* TESTIMONIALS */
#testimonials{padding:90px 60px;background:linear-gradient(180deg,rgba(10,22,40,.5),transparent);}
.t-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:50px;}
.t-card{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);padding:32px;}
.t-stars{color:var(--gold);font-size:.95rem;letter-spacing:2px;margin-bottom:16px;}
.t-text{font-family:'Cormorant Garamond',serif;font-size:1.06rem;font-style:italic;color:var(--pearl);line-height:1.72;opacity:.9;}
.t-author{display:flex;align-items:center;gap:12px;margin-top:22px;}
.t-avatar{width:44px;height:44px;border-radius:50%;object-fit:cover;flex-shrink:0;border:2px solid var(--border2);}
.t-av-fb{width:44px;height:44px;border-radius:50%;background:linear-gradient(135deg,var(--mint),var(--gold));display:flex;align-items:center;justify-content:center;font-size:.9rem;font-weight:700;color:var(--night);flex-shrink:0;}
.t-name{font-size:.87rem;font-weight:600;color:var(--white);}
.t-label{font-size:.72rem;color:var(--slate);}
.t-verified{display:inline-flex;align-items:center;gap:5px;background:rgba(0,222,182,.07);border:1px solid var(--border);border-radius:20px;padding:3px 10px;font-size:.66rem;color:var(--mint);letter-spacing:.07em;margin-top:8px;}

/* FAQ */
#faq{padding:90px 60px;}
.faq-layout{display:grid;grid-template-columns:1fr 1.6fr;gap:80px;align-items:start;}
.faq-side p{color:var(--slate);font-size:.9rem;line-height:1.8;margin-top:14px;}
.faq-item{border-bottom:1px solid var(--border);}
.faq-q{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:20px 0;cursor:pointer;}
.faq-q-txt{font-size:.94rem;font-weight:500;color:var(--pearl);transition:color .25s;}
.faq-q:hover .faq-q-txt{color:var(--mint);}
.faq-ico{width:28px;height:28px;border:1px solid var(--border2);border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:.8rem;color:var(--slate);transition:all .3s;flex-shrink:0;}
.faq-item.open .faq-ico{background:var(--mint);color:var(--night);border-color:var(--mint);transform:rotate(45deg);}
.faq-body{max-height:0;overflow:hidden;transition:max-height .4s ease,padding .4s;}
.faq-item.open .faq-body{max-height:220px;padding-bottom:18px;}
.faq-body p{font-size:.87rem;color:var(--slate);line-height:1.8;}

/* BOOKING */
#book{padding:90px 60px;}
.book-layout{display:grid;grid-template-columns:1fr 1fr;gap:80px;align-items:start;margin-top:50px;}
.book-info > p{font-size:.91rem;color:var(--slate);line-height:1.85;margin-top:14px;}
.book-bullets{list-style:none;margin-top:26px;display:flex;flex-direction:column;gap:12px;}
.book-bullets li{display:flex;align-items:center;gap:11px;font-size:.86rem;color:var(--slate);}
.book-bullets li::before{content:'✓';width:22px;height:22px;background:rgba(0,222,182,.1);border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:.7rem;color:var(--mint);flex-shrink:0;}
.book-contacts{margin-top:30px;display:flex;flex-direction:column;gap:14px;}
.book-contacts a{display:flex;align-items:center;gap:12px;color:var(--pearl);font-size:.9rem;transition:color .25s;}
.book-contacts a:hover{color:var(--mint);}
.book-contacts .ico{width:40px;height:40px;background:rgba(0,222,182,.07);border:1px solid var(--border);border-radius:8px;display:flex;align-items:center;justify-content:center;font-size:1.05rem;flex-shrink:0;}
.form-card{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);padding:40px;}
.form-ttl{font-family:'Cormorant Garamond',serif;font-size:1.75rem;font-weight:600;color:var(--white);margin-bottom:6px;}
.form-sub{font-size:.8rem;color:var(--slate);margin-bottom:28px;}
.fg{margin-bottom:18px;}
.fg label{display:block;font-size:.76rem;font-weight:600;letter-spacing:.07em;text-transform:uppercase;color:var(--slate);margin-bottom:8px;}
.fg input,.fg select{width:100%;background:rgba(255,255,255,.04);border:1px solid var(--border);border-radius:4px;padding:13px 15px;font-size:.89rem;color:var(--pearl);font-family:'DM Sans',sans-serif;outline:none;transition:border-color .3s,background .3s;-webkit-appearance:none;}
.fg input:focus,.fg select:focus{border-color:var(--mint);background:rgba(0,222,182,.04);}
.fg select{background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='7'%3E%3Cpath d='M1 1l5 5 5-5' stroke='%237A8FAA' stroke-width='1.5' fill='none'/%3E%3C/svg%3E");background-repeat:no-repeat;background-position:right 14px center;cursor:pointer;}
.fg select option{background:var(--navy);}
.form-privacy{font-size:.74rem;color:var(--slate);line-height:1.6;margin-top:6px;}
.form-privacy a{color:var(--mint);}
.btn-submit{width:100%;background:var(--mint);color:var(--night);padding:15px;border:none;border-radius:3px;font-size:.88rem;font-weight:700;letter-spacing:.06em;text-transform:uppercase;cursor:pointer;transition:all .4s var(--ease);margin-top:6px;}
.btn-submit:hover{background:var(--white);box-shadow:var(--glow);}

/* GUIDE */
#guide{padding:90px 60px;position:relative;overflow:hidden;}
.guide-orb{position:absolute;inset:0;background:radial-gradient(ellipse 70% 70% at 50% 50%,rgba(0,222,182,.04),transparent 65%);pointer-events:none;}
.guide-layout{display:grid;grid-template-columns:1fr 1fr;gap:80px;align-items:center;position:relative;z-index:2;}
.guide-book{max-width:300px;margin:0 auto;position:relative;}
.book-cover{background:linear-gradient(150deg,#0b2040 0%,#082a44 50%,#0a2035 100%);border-radius:4px 14px 14px 4px;border:1px solid rgba(0,222,182,.18);padding:36px 30px 34px 34px;box-shadow:-10px 10px 0 rgba(0,0,0,.35),0 24px 60px rgba(0,0,0,.5);position:relative;overflow:hidden;aspect-ratio:3/4;display:flex;flex-direction:column;justify-content:space-between;}
.book-cover::before{content:'';position:absolute;left:0;top:0;bottom:0;width:9px;background:linear-gradient(180deg,var(--mint),var(--gold));border-radius:4px 0 0 4px;}
.book-cover::after{content:'';position:absolute;inset:0;background:radial-gradient(circle at 65% 30%,rgba(0,222,182,.07),transparent 55%);}
.book-tag{font-size:.63rem;letter-spacing:.22em;text-transform:uppercase;color:var(--mint);position:relative;z-index:1;}
.book-title{font-family:'Cormorant Garamond',serif;font-size:1.95rem;font-weight:600;color:var(--white);line-height:1.18;position:relative;z-index:1;}
.book-title em{color:var(--mint);font-style:italic;}
.book-sub{font-size:.73rem;color:var(--slate);line-height:1.65;position:relative;z-index:1;}
.book-brand{font-family:'Cormorant Garamond',serif;font-size:.95rem;font-weight:600;color:var(--white);position:relative;z-index:1;}
.book-brand em{font-style:normal;color:var(--mint);}
.book-pages{position:absolute;top:10px;right:-7px;background:rgba(0,0,0,.4);width:13px;height:calc(100% - 20px);border:1px solid rgba(255,255,255,.05);border-radius:0 3px 3px 0;}
.book-badge{position:absolute;bottom:-16px;right:-16px;width:72px;height:72px;border-radius:50%;background:var(--mint);color:var(--night);display:flex;flex-direction:column;align-items:center;justify-content:center;font-size:.6rem;font-weight:800;text-transform:uppercase;letter-spacing:.04em;text-align:center;line-height:1.25;box-shadow:0 6px 24px rgba(0,222,182,.35);}
.book-badge strong{font-size:1.15rem;display:block;}
.guide-text > p{font-size:.91rem;color:var(--slate);line-height:1.85;margin:14px 0 24px;}
.guide-checks{list-style:none;display:flex;flex-direction:column;gap:10px;margin-bottom:28px;}
.guide-checks li{display:flex;align-items:flex-start;gap:11px;font-size:.87rem;color:var(--slate);}
.ck{width:20px;height:20px;background:rgba(0,222,182,.1);border:1px solid rgba(0,222,182,.25);border-radius:4px;display:flex;align-items:center;justify-content:center;font-size:.68rem;color:var(--mint);flex-shrink:0;margin-top:2px;}
.guide-form-box{background:var(--card);border:1px solid var(--border);border-radius:8px;padding:24px;}
.gf-ttl{font-size:.86rem;font-weight:600;color:var(--white);margin-bottom:14px;display:flex;align-items:center;gap:8px;}
.gf-pill{background:var(--mint);color:var(--night);padding:2px 9px;border-radius:3px;font-size:.7rem;font-weight:700;letter-spacing:.06em;text-transform:uppercase;}
.gf-row{display:flex;gap:8px;}
.gf-row input{flex:1;background:rgba(255,255,255,.05);border:1px solid var(--border);border-radius:4px;padding:12px 14px;font-size:.86rem;color:var(--pearl);font-family:'DM Sans',sans-serif;outline:none;transition:border-color .3s;}
.gf-row input:focus{border-color:var(--mint);}
.gf-row input::placeholder{color:var(--slate);}
.gf-btn{background:var(--mint);color:var(--night);border:none;border-radius:4px;padding:12px 18px;font-size:.8rem;font-weight:700;cursor:pointer;transition:all .4s var(--ease);font-family:'DM Sans',sans-serif;white-space:nowrap;}
.gf-btn:hover{background:var(--white);}
.gf-note{font-size:.71rem;color:var(--slate);margin-top:9px;line-height:1.5;}
.gf-note a{color:var(--mint);}
.guide-success{display:none;background:rgba(0,222,182,.07);border:1px solid rgba(0,222,182,.25);border-radius:8px;padding:22px;text-align:center;}
.guide-success.show{display:block;}
.guide-success .gs-ico{font-size:2rem;margin-bottom:8px;}
.guide-success h4{font-family:'Cormorant Garamond',serif;font-size:1.3rem;color:var(--white);margin-bottom:6px;}
.guide-success p{font-size:.83rem;color:var(--slate);}
.guide-success a{color:var(--mint);font-weight:600;}

/* LOCATION */
#location{padding:90px 60px 0;}
.loc-layout{display:grid;grid-template-columns:1fr 2fr;gap:50px;align-items:start;margin-top:46px;}
.loc-details{display:flex;flex-direction:column;gap:24px;}
.loc-item{display:flex;gap:14px;align-items:flex-start;}
.loc-ico{width:42px;height:42px;background:rgba(0,222,182,.07);border:1px solid var(--border);border-radius:9px;display:flex;align-items:center;justify-content:center;font-size:1.1rem;flex-shrink:0;margin-top:2px;}
.loc-label{font-size:.76rem;letter-spacing:.09em;text-transform:uppercase;color:var(--slate);margin-bottom:4px;}
.loc-val{font-size:.9rem;color:var(--pearl);line-height:1.65;}
.loc-val a{color:var(--mint);}
.hrs{display:grid;grid-template-columns:auto 1fr;gap:5px 20px;margin-top:4px;}
.hrs .day{font-size:.83rem;color:var(--pearl);font-weight:500;}
.hrs .time{font-size:.83rem;color:var(--slate);}
.map-embed{border-radius:var(--radius);overflow:hidden;border:1px solid var(--border);height:400px;}
.map-embed iframe{width:100%;height:100%;border:none;display:block;}

/* FOOTER */
footer{background:var(--deep);border-top:1px solid var(--border);padding:70px 60px 32px;margin-top:90px;}
.footer-grid{display:grid;grid-template-columns:2fr 1fr 1fr 1fr;gap:50px;margin-bottom:60px;}
.footer-brand p{font-size:.85rem;color:var(--slate);line-height:1.85;max-width:275px;margin-top:12px;}
.trust-badges{display:flex;gap:10px;flex-wrap:wrap;margin-top:20px;}
.tbadge{background:rgba(255,255,255,.04);border:1px solid var(--border);border-radius:5px;padding:7px 13px;font-size:.7rem;color:var(--slate);letter-spacing:.06em;text-transform:uppercase;}
.f-social{display:flex;gap:9px;margin-top:20px;}
.f-social a{width:36px;height:36px;border:1px solid var(--border);border-radius:6px;display:flex;align-items:center;justify-content:center;color:var(--slate);font-size:.82rem;font-weight:700;transition:all .4s var(--ease);}
.f-social a:hover{border-color:var(--mint);color:var(--mint);background:rgba(0,222,182,.06);}
.f-col h4{font-size:.75rem;letter-spacing:.13em;text-transform:uppercase;color:var(--white);font-weight:600;margin-bottom:18px;}
.f-col a{display:block;font-size:.84rem;color:var(--slate);margin-bottom:10px;transition:color .25s;}
.f-col a:hover{color:var(--mint);}
.footer-bottom{border-top:1px solid var(--border);padding-top:28px;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:14px;}
.footer-bottom p{font-size:.76rem;color:var(--slate);}
.legal-links{display:flex;gap:22px;flex-wrap:wrap;}
.legal-links a{font-size:.76rem;color:var(--slate);transition:color .25s;}
.legal-links a:hover{color:var(--mint);}

/* POPUPS */
.pop-overlay{position:fixed;inset:0;background:rgba(0,0,0,.65);z-index:8000;display:flex;align-items:center;justify-content:center;padding:20px;opacity:0;pointer-events:none;transition:opacity .35s;backdrop-filter:blur(6px);}
.pop-overlay.show{opacity:1;pointer-events:all;}
.pop-box{background:var(--card);border:1px solid var(--border2);border-radius:16px;max-width:460px;width:100%;position:relative;overflow:hidden;transform:scale(.92) translateY(20px);transition:transform .4s var(--ease);}
.pop-overlay.show .pop-box{transform:scale(1) translateY(0);}
.pop-img{width:100%;height:200px;object-fit:cover;object-position:center 30%;}
.pop-body{padding:30px 32px 36px;}
.pop-tag{font-size:.68rem;letter-spacing:.2em;text-transform:uppercase;color:var(--mint);margin-bottom:10px;}
.pop-h{font-family:'Cormorant Garamond',serif;font-size:1.9rem;font-weight:300;color:var(--white);line-height:1.15;margin-bottom:10px;}
.pop-h em{font-style:italic;color:var(--mint);}
.pop-p{font-size:.87rem;color:var(--slate);line-height:1.75;margin-bottom:22px;}
.pop-btns{display:flex;gap:10px;flex-wrap:wrap;}
.pop-cta{flex:1;background:var(--mint);color:var(--night);padding:13px 20px;border-radius:3px;font-size:.84rem;font-weight:700;text-align:center;transition:all .4s var(--ease);min-width:140px;}
.pop-cta:hover{background:var(--white);}
.pop-dismiss{flex:1;background:transparent;color:var(--slate);padding:13px 20px;border-radius:3px;font-size:.84rem;border:1px solid var(--border);cursor:pointer;font-family:'DM Sans',sans-serif;transition:all .4s var(--ease);min-width:100px;}
.pop-dismiss:hover{border-color:var(--slate);color:var(--pearl);}
.pop-close{position:absolute;top:14px;right:14px;background:rgba(0,0,0,.5);border:none;color:#fff;width:32px;height:32px;border-radius:50%;cursor:pointer;font-size:1rem;display:flex;align-items:center;justify-content:center;z-index:2;transition:background .2s;}
.pop-close:hover{background:rgba(0,0,0,.8);}

/* ORALYN CHATBOT */
/* Floating bubbles */
#oralyn-bubbles{position:fixed;bottom:112px;right:26px;z-index:6998;display:flex;flex-direction:column;align-items:flex-end;gap:8px;pointer-events:none;}
#oralyn-bubbles.visible{pointer-events:all;}
.obubble-q{display:flex;align-items:center;gap:8px;background:#fff;color:#0a1628;padding:10px 18px 10px 14px;border-radius:26px;font-size:.79rem;font-weight:600;box-shadow:0 6px 24px rgba(0,0,0,.14),0 2px 6px rgba(0,0,0,.07);cursor:pointer;white-space:nowrap;opacity:0;transform:translateX(28px) scale(.9);transition:opacity .4s var(--ease),transform .4s var(--ease),background .2s,color .2s;border:1.5px solid rgba(0,222,182,.18);position:relative;}
.obubble-q::before{content:'';position:absolute;left:0;top:0;bottom:0;width:4px;background:linear-gradient(180deg,#00DEB6,#00a88a);border-radius:26px 0 0 26px;}
.obubble-q:hover{background:linear-gradient(135deg,#00DEB6,#00b393);color:#050C1A;transform:translateX(0) scale(1.03) !important;box-shadow:0 8px 28px rgba(0,222,182,.4);border-color:transparent;}
.obubble-q:hover::before{background:rgba(0,0,0,.15);}
.obubble-q.in{opacity:1;transform:translateX(0) scale(1);}
.obubble-q.gone{opacity:0 !important;transform:translateX(28px) scale(.88) !important;pointer-events:none;transition:all .3s ease;}
.ob-ico{font-size:.95rem;flex-shrink:0;}
/* Chat button */
#oralyn-btn{position:fixed;bottom:26px;right:26px;z-index:7000;width:64px;height:64px;border-radius:50%;background:linear-gradient(135deg,#00DEB6,#00b393);color:#050C1A;border:none;cursor:pointer;display:flex;align-items:center;justify-content:center;box-shadow:0 4px 24px rgba(0,222,182,.5),0 8px 48px rgba(0,0,0,.25);transition:all .38s var(--ease);}
#oralyn-btn:hover{transform:scale(1.1);}
#oralyn-btn.open{background:linear-gradient(135deg,#0D1B30,#0a1628);color:rgba(255,255,255,.8);border:1.5px solid rgba(0,222,182,.22);box-shadow:0 4px 20px rgba(0,0,0,.35);}
.ob-btn-ico{font-size:1.75rem;transition:transform .35s var(--ease);}
#oralyn-btn.open .ob-btn-ico{transform:rotate(180deg);}
.ob-notif{position:absolute;top:-4px;right:-4px;width:20px;height:20px;border-radius:50%;background:#E8344A;border:2.5px solid #050C1A;font-size:.58rem;font-weight:800;color:#fff;display:flex;align-items:center;justify-content:center;opacity:0;animation:nIn .5s 3.8s var(--ease) forwards;}
@keyframes nIn{0%{transform:scale(0);opacity:0;}65%{transform:scale(1.25);}100%{transform:scale(1);opacity:1;}}
/* Chat window */
.oralyn-win{position:fixed;bottom:108px;right:26px;z-index:6999;width:388px;background:#F8FAFC;border-radius:24px;display:flex;flex-direction:column;overflow:hidden;box-shadow:0 28px 80px rgba(0,0,0,.18),0 4px 16px rgba(0,0,0,.1),0 0 0 1px rgba(0,0,0,.06);transform:scale(.88) translateY(32px);opacity:0;pointer-events:none;transition:all .44s var(--ease);transform-origin:bottom right;max-height:590px;}
.oralyn-win.open{transform:scale(1) translateY(0);opacity:1;pointer-events:all;}
/* Header */
.o-head{background:linear-gradient(145deg,#050C1A 0%,#0A1628 60%,#0D2040 100%);padding:20px 18px 18px;display:flex;align-items:center;gap:14px;flex-shrink:0;position:relative;overflow:hidden;}
.o-head::before{content:'';position:absolute;right:-20px;top:-20px;width:140px;height:140px;background:radial-gradient(circle,rgba(0,222,182,.12),transparent 65%);pointer-events:none;}
.o-ava{width:50px;height:50px;border-radius:50%;flex-shrink:0;background:linear-gradient(135deg,#00DEB6,#00a88a);display:flex;align-items:center;justify-content:center;font-size:1.4rem;box-shadow:0 0 0 3px rgba(0,222,182,.28),0 0 0 6px rgba(0,222,182,.07);position:relative;z-index:1;}
.o-head-info{position:relative;z-index:1;flex:1;}
.o-name{font-size:1.05rem;font-weight:700;color:#fff;line-height:1.2;}
.o-sub{font-size:.71rem;color:rgba(255,255,255,.45);margin-top:2px;}
.o-status{display:inline-flex;align-items:center;gap:5px;font-size:.69rem;color:#00DEB6;margin-top:5px;background:rgba(0,222,182,.1);border-radius:20px;padding:3px 9px 3px 6px;}
.o-status::before{content:'';width:6px;height:6px;border-radius:50%;background:#00DEB6;display:inline-block;animation:sPulse 2s ease-in-out infinite;}
@keyframes sPulse{0%,100%{opacity:1;}50%{opacity:.3;}}
.o-close{margin-left:auto;background:rgba(255,255,255,.07);border:none;color:rgba(255,255,255,.55);width:36px;height:36px;border-radius:50%;cursor:pointer;font-size:1.15rem;display:flex;align-items:center;justify-content:center;transition:all .2s;flex-shrink:0;position:relative;z-index:1;}
.o-close:hover{background:rgba(255,255,255,.15);color:#fff;}
/* Messages */
.o-msgs{flex:1;overflow-y:auto;padding:16px 14px 10px;display:flex;flex-direction:column;gap:12px;background:#F8FAFC;scroll-behavior:smooth;}
.o-msgs::-webkit-scrollbar{width:3px;}
.o-msgs::-webkit-scrollbar-thumb{background:rgba(0,0,0,.09);border-radius:2px;}
.o-day-sep{text-align:center;font-size:.65rem;color:#a0aec0;letter-spacing:.08em;text-transform:uppercase;margin:4px 0 2px;display:flex;align-items:center;gap:10px;}
.o-day-sep::before,.o-day-sep::after{content:'';flex:1;height:1px;background:rgba(0,0,0,.07);}
.omsg{max-width:90%;animation:omsgIn .3s var(--ease);}
@keyframes omsgIn{from{opacity:0;transform:translateY(10px);}to{opacity:1;transform:translateY(0);}}
.omsg.bot{align-self:flex-start;}
.omsg.usr{align-self:flex-end;}
.o-row{display:flex;align-items:flex-end;gap:8px;}
.omsg.bot .o-row{flex-direction:row;}
.omsg.usr .o-row{flex-direction:row-reverse;}
.o-ava-sm{width:30px;height:30px;border-radius:50%;flex-shrink:0;background:linear-gradient(135deg,#00DEB6,#00a88a);display:flex;align-items:center;justify-content:center;font-size:.8rem;margin-bottom:2px;box-shadow:0 2px 6px rgba(0,222,182,.25);}
.o-bubble{padding:11px 15px;border-radius:18px;font-size:.84rem;line-height:1.62;}
.omsg.bot .o-bubble{background:#fff;color:#1a2535;border-radius:4px 18px 18px 18px;box-shadow:0 1px 3px rgba(0,0,0,.07),0 0 0 1px rgba(0,0,0,.04);}
.omsg.usr .o-bubble{background:linear-gradient(135deg,#00DEB6,#00b393);color:#050C1A;font-weight:500;border-radius:18px 4px 18px 18px;box-shadow:0 2px 8px rgba(0,222,182,.3);}
.omsg.bot .o-bubble a{color:#00a88a;text-decoration:underline;}
.o-time{font-size:.6rem;color:#b0bec5;margin-top:5px;padding:0 4px;display:flex;align-items:center;gap:4px;}
.omsg.usr .o-time{justify-content:flex-end;}
.o-read{color:#00DEB6;font-size:.65rem;}
/* Quick replies */
.o-qrs{display:flex;flex-wrap:wrap;gap:7px;margin-top:8px;padding-left:38px;}
.o-qr{background:#fff;border:1.5px solid rgba(0,222,182,.3);color:#057a63;padding:7px 15px;border-radius:20px;font-size:.77rem;font-weight:600;cursor:pointer;transition:all .2s;font-family:'DM Sans',sans-serif;white-space:nowrap;box-shadow:0 1px 4px rgba(0,0,0,.06);}
.o-qr:hover{background:linear-gradient(135deg,#00DEB6,#00b393);color:#050C1A;border-color:transparent;box-shadow:0 4px 14px rgba(0,222,182,.32);transform:translateY(-1px);}
/* Typing */
.otyping .o-bubble{display:flex;align-items:center;gap:5px;padding:13px 16px;}
.otd{width:7px;height:7px;background:#c8d3de;border-radius:50%;animation:otdB 1.3s ease-in-out infinite;}
.otd:nth-child(2){animation-delay:.18s;}
.otd:nth-child(3){animation-delay:.36s;}
@keyframes otdB{0%,60%,100%{transform:translateY(0);}30%{transform:translateY(-6px);}}
/* Input */
.o-input-row{border-top:1px solid rgba(0,0,0,.07);padding:11px 12px;display:flex;gap:9px;flex-shrink:0;background:#fff;align-items:center;}
#o-input{flex:1;background:#EFF3F8;border:1.5px solid transparent;border-radius:22px;padding:10px 16px;font-size:.84rem;color:#1a2535;font-family:'DM Sans',sans-serif;outline:none;transition:border-color .25s,background .25s,box-shadow .25s;}
#o-input:focus{border-color:#00DEB6;background:#fff;box-shadow:0 0 0 3px rgba(0,222,182,.12);}
#o-input::placeholder{color:#9db0c5;}
.o-send{width:40px;height:40px;border-radius:50%;background:linear-gradient(135deg,#00DEB6,#00b393);border:none;cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:1rem;color:#050C1A;font-weight:700;transition:all .25s;flex-shrink:0;box-shadow:0 2px 10px rgba(0,222,182,.4);}
.o-send:hover{transform:scale(1.12);box-shadow:0 4px 18px rgba(0,222,182,.55);}
.o-powered{padding:6px 12px;background:#fff;border-top:1px solid rgba(0,0,0,.05);text-align:center;font-size:.6rem;color:#c5cdd8;flex-shrink:0;letter-spacing:.02em;}

/* RESPONSIVE */
@media(max-width:1100px){
  nav,#services,#gallery,#sotm,#video-stories,#testimonials,#faq,#book,#guide,#location{padding-left:36px;padding-right:36px;}
  footer{padding:60px 36px 28px;}
  #hero{grid-template-columns:1fr;}
  .hero-right{height:100%;}
  .hero-right::after{background:linear-gradient(0deg, var(--night) 15%, rgba(5,12,26,.85) 60%, rgba(5,12,26,.3) 100%);}
  .hero-left{padding:60px 36px 50px;}
  .vs-carousel-wrap { margin-left: -36px; margin-right: -36px; padding: 20px 36px; }
  .vs-card { flex: 0 0 calc(33.333% - 16px); }
}
@media(max-width:900px){
  #ebanner{padding:0 22px;}
  nav{padding:0 22px;}
  .nav-links{display:none;}
  .ham{display:flex;}
  #hero{display:block;}
  .hero-right{height:100%;}
  .hero-left{padding:48px 22px 52px;}
  #stats{grid-template-columns:1fr 1fr;}
  .stat-cell:nth-child(2){border-right:none;}
  .stat-cell:nth-child(3){border-top:1px solid var(--border);}
  #services,#gallery,#sotm,#video-stories,#testimonials,#faq,#book,#guide,#location{padding:60px 22px;}
  footer{padding:50px 22px 24px;}
  .svc-grid{grid-template-columns:1fr 1fr;}
  .c-slide{grid-template-columns:1fr;}
  .ba-wrap{aspect-ratio:4/3;}
  .slide-info{padding:34px 28px;}
  .sotm-layout{gap:30px;}
  .sotm-mini { flex: 0 0 calc(50% - 12px); }
  .t-grid{grid-template-columns:1fr 1fr;}
  .faq-layout{grid-template-columns:1fr;gap:36px;}
  .book-layout{grid-template-columns:1fr;gap:36px;}
  .guide-layout{grid-template-columns:1fr;gap:40px;}
  .loc-layout{grid-template-columns:1fr;gap:30px;}
  .footer-grid{grid-template-columns:1fr 1fr;gap:36px;}
  .vs-carousel-wrap { margin-left: -22px; margin-right: -22px; padding: 10px 22px; }
  .vs-card { flex: 0 0 calc(50% - 12px); }
}
@media(max-width:600px){
  :root{--ban-h:42px;}
  #ebanner{padding:0 12px; height:var(--ban-h); flex-wrap:nowrap;}
  .ban-btn{flex-direction:row; gap:4px; padding:0;}
  .ban-ico{font-size:1.1rem;}
  .ban-lbl{font-size:.65rem; white-space:nowrap;}

  nav{padding:0 16px;}
  .logo{font-size:1.4rem;}

  .hero-left{padding:60px 16px; min-height:85vh; justify-content:flex-end;}
  .hero-right::after{background:linear-gradient(0deg, var(--night) 15%, rgba(5,12,26,.85) 60%, rgba(5,12,26,.3) 100%);}
  .hero-h1{font-size:clamp(2.5rem,10vw,3.2rem); margin-bottom:16px;}
  .hero-sub{font-size:.92rem; margin-bottom:30px;}
  .hero-btns{flex-direction:column; align-items:stretch; width:100%;}
  .btn-primary, .btn-ghost-hero{width:100%; justify-content:center; text-align:center; padding:16px;}
  
  #stats{grid-template-columns:1fr 1fr; padding:40px 16px;}
  .stat-cell{padding:24px 10px; border:none;}
  .stat-cell:nth-child(1), .stat-cell:nth-child(2){border-bottom:1px solid var(--border);}
  .stat-cell:nth-child(odd){border-right:1px solid var(--border);}

  #services,#gallery,#sotm,#video-stories,#testimonials,#faq,#book,#guide,#location{padding:56px 16px;}
  
  .svc-grid{display:flex; flex-wrap:nowrap; overflow-x:auto; scroll-snap-type:x mandatory; gap:16px; padding:10px 16px 30px; margin-left:-16px; margin-right:-16px; background:transparent; scrollbar-width:none; -ms-overflow-style:none;}
  .svc-grid::-webkit-scrollbar{display:none;}
  .svc-card{flex:0 0 85%; scroll-snap-align:center; border:1px solid var(--border); border-radius:var(--radius);}
  
  .slide-info{padding:32px 24px;}
  .slide-title{font-size:1.6rem;}
  .c-slide{grid-template-columns:1fr;}
  .ba-wrap{aspect-ratio:4/3;}
  
  .sotm-layout{gap:32px;}
  .sotm-img-big img{height:220px;}
  .sotm-img-half img{height:140px;}
  .sotm-body{padding:26px 20px;}
  
  .sotm-side { gap: 16px; margin-left: 0; margin-right: 0; padding-bottom: 10px; }
  .sotm-mini { flex: 0 0 100%; }
  .sotm-hz-card { flex-direction:column; text-align:center; padding:24px 20px; }
  
  .t-grid{display:flex; flex-wrap:nowrap; overflow-x:auto; scroll-snap-type:x mandatory; gap:16px; padding:10px 16px 30px; margin-left:-16px; margin-right:-16px; scrollbar-width:none; -ms-overflow-style:none;}
  .t-grid::-webkit-scrollbar{display:none;}
  .t-card{flex:0 0 85%; scroll-snap-align:center;}
  
  .faq-layout{grid-template-columns:1fr; gap:40px;}
  .faq-q{padding:18px 0;}
  
  .book-layout{grid-template-columns:1fr; gap:40px;}
  .form-card{padding:32px 20px;}
  
  .guide-layout{grid-template-columns:1fr; gap:40px;}
  .gf-row{flex-direction:column;}
  .gf-btn{width:100%; padding:14px;}
  
  .loc-layout{grid-template-columns:1fr; gap:40px;}
  .loc-item{flex-direction:column; align-items:center; text-align:center;}
  .loc-ico{margin-bottom:10px;}
  .hrs{grid-template-columns:1fr; text-align:center; gap:4px;}
  .hrs .day{margin-top:10px; display:block;}
  .map-embed{height:300px;}
  
  .footer-grid{grid-template-columns:1fr; gap:40px; text-align:center;}
  footer{padding:60px 16px 30px;}
  .footer-brand{display:flex; flex-direction:column; align-items:center;}
  .trust-badges, .f-social, .legal-links{justify-content:center;}
  .footer-bottom{flex-direction:column; text-align:center; gap:20px;}
  
  .oralyn-win{width:calc(100vw - 18px); right:9px; bottom:104px; max-height:70vh;}
  #oralyn-bubbles{right:12px; bottom:108px;}
  #oralyn-btn{right:12px; bottom:12px; width:58px; height:58px;}
  .pop-box{margin:0 10px;}
  
  .vs-carousel-wrap { margin-left: -16px; margin-right: -16px; padding: 10px 16px; }
  .vs-card { flex: 0 0 75%; }
  .vs-track { gap: 14px; }
}
</style>
</head>
<body>
<div id="scroll-bar"></div>

<div id="ebanner">
  <a href="https://wa.me/442000000000" class="ban-btn"><span class="ban-ico">💬</span><span class="ban-lbl">WhatsApp</span></a>
  <a href="https://maps.google.com/?q=1+Harley+Street,+London+W1G+9QD" target="_blank" class="ban-btn"><span class="ban-ico">📍</span><span class="ban-lbl">Clinic Address</span></a>
  <a href="tel:+442000000000" class="ban-btn"><span class="ban-ico">📞</span><span class="ban-lbl">Call Now</span></a>
</div>

<nav>
  <a href="index.html" class="logo">Pearl<em>Smile</em><span class="logo-star">✦</span></a>
  <a href="https://maps.google.com/?q=1+Harley+Street,+London+W1G+9QD" target="_blank" class="nav-address-btn" aria-label="View on Google Maps">
    <div style="display:flex; flex-direction:column; align-items:center; line-height:1.2;">
      <div><span class="g-icon">G</span> <span class="clinic-icon">🏥</span></div>
      <div style="color:var(--gold); font-size:0.75rem; letter-spacing:1px;">★★★★★</div>
    </div>
    <span class="address-text">1 Harley St, London</span>
  </a>
  <div class="nav-links">
    <a href="#services">Treatments</a>
    <a href="#gallery">Gallery</a>
    <a href="#sotm">Smile Stories</a>
    <a href="#testimonials">Reviews</a>
    <a href="#faq">FAQ</a>
    <a href="tel:+442000000000" class="nav-phone">020 0000 0000</a>
    <a href="#book" class="nav-book">Book Free Consult</a>
  </div>
  <button class="ham" id="ham" aria-label="Menu"><span></span><span></span><span></span></button>
</nav>
<div class="mob-menu" id="mob-menu">
  <a href="#services" class="mob-link">Treatments</a>
  <a href="#gallery" class="mob-link">Gallery</a>
  <a href="#sotm" class="mob-link">Smile Stories</a>
  <a href="#testimonials" class="mob-link">Reviews</a>
  <a href="#faq" class="mob-link">FAQ</a>
  <a href="tel:+442000000000" class="mob-link">📞 020 0000 0000</a>
  <a href="#book" class="mob-cta">Book Free Consultation →</a>
</div>

<section id="hero">
  <div class="hero-orb"></div>
  <div class="hero-grid"></div>
  <div class="hero-left">
    <div class="hero-eyebrow">London's Premier Cosmetic Dentist · Harley Street</div>
    <h1 class="hero-h1">
      <span class="hline"><span class="hline-inner">Your Most</span></span>
      <span class="hline"><span class="hline-inner"><em>Confident</em> Smile</span></span>
      <span class="hline"><span class="hline-inner">Starts Here</span></span>
    </h1>
    <p class="hero-sub">Award-winning cosmetic & general dentistry on Harley Street. Implants, Invisalign®, whitening, and same-day emergency care — always delivered with warmth.</p>
    <div class="hero-btns">
      <a href="#book" class="btn-primary">Book Free Consultation</a>
      <a href="#gallery" class="btn-ghost-hero">See Smile Gallery <span class="circle">→</span></a>
    </div>
    <div class="hero-trust">
      <div><span class="trust-num">4.9<span style="color:var(--gold)">★</span></span><span class="trust-lbl">Google Rating</span></div>
      <div class="trust-sep"></div>
      <div><span class="trust-num">2,500<span style="color:var(--mint);font-size:1.2rem">+</span></span><span class="trust-lbl">Happy Patients</span></div>
      <div class="trust-sep"></div>
      <div><span class="trust-num">15<span style="color:var(--mint);font-size:1.2rem">+</span></span><span class="trust-lbl">Years Experience</span></div>
    </div>
  </div>
  <div class="hero-right">
    <img src="https://images.unsplash.com/photo-1629909613654-28e377c37b09?w=900&q=85&auto=format&fit=crop" alt="Patient receiving dental care at PearlSmile" loading="eager" fetchpriority="high">
    <div class="hero-badge"><span class="bn">0%</span><span class="bl">Finance Available</span></div>
  </div>
</section>

<div class="marquee-wrap" aria-hidden="true">
  <div class="marquee-track">
    <span class="m-item"><span class="m-dot"></span> Dental Implants</span>
    <span class="m-item"><span class="m-dot"></span> Invisalign® Diamond Provider</span>
    <span class="m-item"><span class="m-dot"></span> Teeth Whitening</span>
    <span class="m-item"><span class="m-dot"></span> Porcelain Veneers</span>
    <span class="m-item"><span class="m-dot"></span> Same-Day Emergencies</span>
    <span class="m-item"><span class="m-dot"></span> 0% Finance Available</span>
    <span class="m-item"><span class="m-dot"></span> Free Consultations</span>
    <span class="m-item"><span class="m-dot"></span> GDC Registered · CQC Regulated</span>
    <span class="m-item"><span class="m-dot"></span> Dental Implants</span>
    <span class="m-item"><span class="m-dot"></span> Invisalign® Diamond Provider</span>
    <span class="m-item"><span class="m-dot"></span> Teeth Whitening</span>
    <span class="m-item"><span class="m-dot"></span> Porcelain Veneers</span>
    <span class="m-item"><span class="m-dot"></span> Same-Day Emergencies</span>
    <span class="m-item"><span class="m-dot"></span> 0% Finance Available</span>
    <span class="m-item"><span class="m-dot"></span> Free Consultations</span>
    <span class="m-item"><span class="m-dot"></span> GDC Registered · CQC Regulated</span>
  </div>
</div>

<section id="stats">
  <div class="stat-cell reveal"><span class="s-num" data-count="2500">0<span class="acc">+</span></span><span class="s-lbl">Happy Patients</span></div>
  <div class="stat-cell reveal"><span class="s-num"><span class="acc">4.9</span><span style="color:var(--gold)">★</span></span><span class="s-lbl">Google Rating</span></div>
  <div class="stat-cell reveal"><span class="s-num" data-count="15">0<span class="acc">+</span></span><span class="s-lbl">Years Experience</span></div>
  <div class="stat-cell reveal"><span class="s-num" data-count="247">0<span class="acc">+</span></span><span class="s-lbl">Verified Reviews</span></div>
</section>

<section id="services">
  <div class="sec-head">
    <div><div class="eyebrow">What We Offer</div><h2 class="section-h2">Treatments Tailored<br>to <em>Your Smile</em></h2></div>
    <a href="#book" class="more-link">All Treatments →</a>
  </div>
  <div class="svc-grid">
    <div class="svc-card reveal"><div class="svc-icon">🦷</div><span class="svc-n">01</span><h3 class="svc-title">Dental Implants</h3><p class="svc-desc">Permanent, natural-looking replacements fused to your jawbone. The gold standard for missing teeth — built to last a lifetime.</p><a href="#book" class="svc-more">Learn More →</a></div>
    <div class="svc-card reveal"><div class="svc-icon">😁</div><span class="svc-n">02</span><h3 class="svc-title">Invisalign®</h3><p class="svc-desc">Clear, removable aligners that straighten teeth discreetly. We're a Diamond-level Invisalign provider — top 1% in the UK.</p><a href="#book" class="svc-more">Learn More →</a></div>
    <div class="svc-card reveal"><div class="svc-icon">✨</div><span class="svc-n">03</span><h3 class="svc-title">Teeth Whitening</h3><p class="svc-desc">Professional-grade whitening up to 8 shades brighter in a single session. Safe, fast, and beautifully long-lasting results.</p><a href="#book" class="svc-more">Learn More →</a></div>
    <div class="svc-card reveal"><div class="svc-icon">💎</div><span class="svc-n">04</span><h3 class="svc-title">Porcelain Veneers</h3><p class="svc-desc">Ultra-thin porcelain shells that transform shape, colour, and confidence. The Hollywood smile, crafted precisely for you.</p><a href="#book" class="svc-more">Learn More →</a></div>
    <div class="svc-card reveal"><div class="svc-icon">🚨</div><span class="svc-n">05</span><h3 class="svc-title">Emergency Care</h3><p class="svc-desc">Same-day appointments for toothache, cracked teeth, and lost fillings. Call us now — we prioritise you when pain strikes.</p><a href="tel:+442000000000" class="svc-more">Call Now →</a></div>
    <div class="svc-card reveal"><div class="svc-icon">🔬</div><span class="svc-n">06</span><h3 class="svc-title">Hygiene & Check-ups</h3><p class="svc-desc">Comprehensive exams, digital X-rays, and professional cleaning. Prevention is the most powerful dental treatment of all.</p><a href="#book" class="svc-more">Learn More →</a></div>
  </div>
</section>

<section id="gallery">
  <div class="sec-head">
    <div><div class="eyebrow">Visual Proof</div><h2 class="section-h2">Real <em>Smile Transformations</em></h2></div>
    <div class="slide-counter"><strong id="slide-cur">1</strong> / <span id="slide-tot">5</span></div>
  </div>
  <div class="carousel-wrap">
    <div class="carousel-outer">
      <div class="carousel-track" id="carousel-track">

        <div class="c-slide">
          <div class="slide-info">
            <div class="slide-num">01</div>
            <div class="slide-eyebrow">Treatment</div>
            <h3 class="slide-title">Teeth Whitening</h3>
            <p class="slide-desc">Professional in-chair whitening delivering up to 8 shades brighter in a single 90-minute session. Safe, effective, and built to last.</p>
            <div class="slide-tags"><span class="slide-tag">1 Session</span><span class="slide-tag">From £299</span><span class="slide-tag">8 Shades Brighter</span></div>
            <a href="#book" class="slide-cta">Book Whitening →</a>
          </div>
          <div class="ba-wrap">
            <img class="ba-img" src="https://res.cloudinary.com/dcrg3tllm/image/upload/v1776235228/1000120004_cleanup_vwvif1.png" alt="After teeth whitening" loading="lazy">
            <img class="ba-img ba-before" src="https://res.cloudinary.com/dcrg3tllm/image/upload/v1776235262/1000120001_cleanup_cshzj1.png" alt="Before teeth whitening" loading="lazy">
            <div class="ba-line"></div><div class="ba-handle">⟨⟩</div>
            <span class="ba-lbl bef">Before</span><span class="ba-lbl aft">After</span>
          </div>
        </div>

        <div class="c-slide">
          <div class="slide-info">
            <div class="slide-num">02</div>
            <div class="slide-eyebrow">Treatment</div>
            <h3 class="slide-title">Porcelain Veneers</h3>
            <p class="slide-desc">Ultra-thin porcelain shells bonded to the front of your teeth. Transform colour, shape, and size in just 2–3 appointments.</p>
            <div class="slide-tags"><span class="slide-tag">2–3 Visits</span><span class="slide-tag">From £650/tooth</span><span class="slide-tag">10–15 Year Lifespan</span></div>
            <a href="#book" class="slide-cta">Book Veneer Consult →</a>
          </div>
          <div class="ba-wrap">
            <img class="ba-img" src="https://res.cloudinary.com/dcrg3tllm/image/upload/v1776314185/1000120011_cleanup_jlje52.png" alt="After veneers" loading="lazy">
            <img class="ba-img ba-before" src="https://res.cloudinary.com/dcrg3tllm/image/upload/v1776262492/1000120021_cleanup_qwwdbj.png" alt="Before veneers" loading="lazy">
            <div class="ba-line"></div><div class="ba-handle">⟨⟩</div>
            <span class="ba-lbl bef">Before</span><span class="ba-lbl aft">After</span>
          </div>
        </div>

        <div class="c-slide">
          <div class="slide-info">
            <div class="slide-num">03</div>
            <div class="slide-eyebrow">Treatment</div>
            <h3 class="slide-title">Dental Implants</h3>
            <p class="slide-desc">A titanium root permanently fused to the jawbone, topped with a custom crown. Indistinguishable from a natural tooth — for life.</p>
            <div class="slide-tags"><span class="slide-tag">Permanent</span><span class="slide-tag">From £2,800</span><span class="slide-tag">0% Finance</span></div>
            <a href="#book" class="slide-cta">Book Implant Consult →</a>
          </div>
          <div class="ba-wrap">
            <img class="ba-img" src="https://res.cloudinary.com/dcrg3tllm/image/upload/v1776313988/1000120095_cleanup_nvuhom.png" alt="After dental implants" loading="lazy">
            <img class="ba-img ba-before" src="https://res.cloudinary.com/dcrg3tllm/image/upload/v1776262518/IMG_20260415_133950_ddipbi.jpg" alt="Before dental implants" loading="lazy">
            <div class="ba-line"></div><div class="ba-handle">⟨⟩</div>
            <span class="ba-lbl bef">Before</span><span class="ba-lbl aft">After</span>
          </div>
        </div>

        <div class="c-slide">
          <div class="slide-info">
            <div class="slide-num">04</div>
            <div class="slide-eyebrow">Treatment</div>
            <h3 class="slide-title">Invisalign® Braces</h3>
            <p class="slide-desc">Clear, removable aligners that straighten your smile without anyone knowing. Diamond-level provider — top 1% in the UK.</p>
            <div class="slide-tags"><span class="slide-tag">6–18 Months</span><span class="slide-tag">From £2,400</span><span class="slide-tag">Diamond Provider</span></div>
            <a href="#book" class="slide-cta">Book Invisalign Scan →</a>
          </div>
          <div class="ba-wrap">
            <img class="ba-img" src="https://res.cloudinary.com/dcrg3tllm/image/upload/v1776262969/1000120086_cleanup_s6zxky.png" alt="After Invisalign" loading="lazy">
            <img class="ba-img ba-before" src="https://res.cloudinary.com/dcrg3tllm/image/upload/v1776262932/1000120084_cleanup_bcjqw0.png" alt="Before Invisalign" loading="lazy">
            <div class="ba-line"></div><div class="ba-handle">⟨⟩</div>
            <span class="ba-lbl bef">Before</span><span class="ba-lbl aft">After</span>
          </div>
        </div>

        <div class="c-slide">
          <div class="slide-info">
            <div class="slide-num">05</div>
            <div class="slide-eyebrow">Treatment</div>
            <h3 class="slide-title">Full Smile Makeover</h3>
            <p class="slide-desc">A bespoke combination — whitening, veneers, Invisalign, and bonding — designed to give you the complete smile of your dreams.</p>
            <div class="slide-tags"><span class="slide-tag">Bespoke Plan</span><span class="slide-tag">0% Finance</span><span class="slide-tag">Free Consultation</span></div>
            <a href="#book" class="slide-cta">Start My Makeover →</a>
          </div>
          <div class="ba-wrap">
            <img class="ba-img" src="https://res.cloudinary.com/dcrg3tllm/image/upload/v1776263964/IMG_20260415_193813_obfhzz.png" alt="After smile makeover" loading="lazy">
            <img class="ba-img ba-before" src="https://res.cloudinary.com/dcrg3tllm/image/upload/v1776263957/IMG_20260415_193520_s7qfki.png" alt="Before smile makeover" loading="lazy">
            <div class="ba-line"></div><div class="ba-handle">⟨⟩</div>
            <span class="ba-lbl bef">Before</span><span class="ba-lbl aft">After</span>
          </div>
        </div>

      </div>
    </div>
    <div class="carousel-ctrl">
      <div class="carousel-dots" id="carousel-dots"></div>
      <div class="carousel-arrows">
        <button class="c-arr" id="c-prev" aria-label="Previous">←</button>
        <button class="c-arr" id="c-next" aria-label="Next">→</button>
      </div>
    </div>
  </div>
</section>

<section id="sotm">
  <div class="sec-head">
    <div><div class="eyebrow">Patient Spotlight</div><h2 class="section-h2">Smile of the <em>Month</em></h2></div>
    <a href="#book" class="more-link">Get Your Smile →</a>
  </div>
  <div class="sotm-layout">
    <div class="sotm-main reveal">
      <div class="sotm-imgs">
        <div class="sotm-img-big"><img src="https://images.unsplash.com/photo-1606813907291-d86efa9b94db?w=800&q=85&auto=format&fit=crop" alt="Emma – after veneers and whitening" loading="lazy"></div>
        <div class="sotm-img-half"><img src="https://images.unsplash.com/photo-1588776814546-1ffcf47267a5?w=400&q=80&auto=format&fit=crop" alt="Before treatment" loading="lazy"></div>
        <div class="sotm-img-half"><img src="https://images.unsplash.com/photo-1607746882042-944635dfe10e?w=400&q=80&auto=format&fit=crop" alt="Dr Chen" loading="lazy"></div>
      </div>
      <div class="sotm-body">
        <div class="sotm-award">⭐ June 2025 · Smile of the Month</div>
        <div class="sotm-patient">Emma Richardson</div>
        <div class="sotm-tx">Porcelain Veneers + Professional Whitening</div>
        <p class="sotm-quote">"I'd been hiding my smile for fifteen years. After just three appointments with Dr. Chen, I couldn't stop looking in the mirror. My confidence has completely transformed. I only wish I hadn't waited so long."</p>
        <div class="sotm-stars">★★★★★</div>
        <div style="display:flex;align-items:center;justify-content:space-between;margin-top:16px;flex-wrap:wrap;gap:10px;">
          <span style="font-size:.76rem;color:var(--slate);">Kensington, London · Treated by Dr. James Chen</span>
          <a href="#book" class="btn-primary" style="font-size:.8rem;padding:10px 20px;">Get My Result →</a>
        </div>
      </div>
    </div>
    
    <div class="sotm-side" id="sotm-track">
      <div class="sotm-mini reveal">
        <img src="https://images.unsplash.com/photo-1502685104226-ee32379fefbe?w=400&q=80&auto=format&fit=crop" alt="James T." loading="lazy">
        <div class="sotm-mini-body">
          <div class="sotm-mini-badge">May 2025</div>
          <div class="sotm-mini-name">James T.</div>
          <div class="sotm-mini-tx">Invisalign® — 7 months · Complete alignment transformation</div>
          <div class="sotm-mini-stars">★★★★★</div>
        </div>
      </div>
      <div class="sotm-mini reveal">
        <img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?w=400&q=80&auto=format&fit=crop" alt="Sophia M." loading="lazy">
        <div class="sotm-mini-body">
          <div class="sotm-mini-badge">April 2025</div>
          <div class="sotm-mini-name">Sophia M.</div>
          <div class="sotm-mini-tx">Full Smile Makeover — Veneers + Whitening + Hygiene</div>
          <div class="sotm-mini-stars">★★★★★</div>
        </div>
      </div>
      <div class="sotm-mini reveal">
        <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=400&q=80&auto=format&fit=crop" alt="Olivia R." loading="lazy">
        <div class="sotm-mini-body">
          <div class="sotm-mini-badge">March 2025</div>
          <div class="sotm-mini-name">Olivia R.</div>
          <div class="sotm-mini-tx">Teeth Whitening — Single Session · 8 Shades Brighter</div>
          <div class="sotm-mini-stars">★★★★★</div>
        </div>
      </div>
      <div class="sotm-mini reveal">
        <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=400&q=80&auto=format&fit=crop" alt="Marcus B." loading="lazy">
        <div class="sotm-mini-body">
          <div class="sotm-mini-badge">February 2025</div>
          <div class="sotm-mini-name">Marcus B.</div>
          <div class="sotm-mini-tx">Porcelain Veneers — 3 Appointments · Complete Restoration</div>
          <div class="sotm-mini-stars">★★★★★</div>
        </div>
      </div>
      <a href="#gallery" class="sotm-mini reveal" style="text-decoration:none; background:rgba(0,222,182,0.05); border:1px solid var(--border2); display:flex; align-items:center; justify-content:center; flex-direction:column; text-align:center;">
        <div style="padding:40px;">
          <div style="font-size:3rem; margin-bottom:16px;">📸</div>
          <h3 style="font-family:'Cormorant Garamond',serif; font-size:1.6rem; font-weight:600; color:var(--white); margin-bottom:10px;">See Full Gallery</h3>
          <div style="font-size:.76rem; color:var(--mint); letter-spacing:.1em; text-transform:uppercase;">Explore More Transformations →</div>
        </div>
      </a>
    </div>

    <div class="sotm-hz-card reveal">
      <div>
        <div class="sotm-hz-title">Want to be our next Smile of the Month?</div>
        <p class="sotm-hz-desc">Book your free consultation today.</p>
      </div>
      <a href="#book" class="btn-primary sotm-hz-btn">Book Free Consultation →</a>
    </div>
  </div>
</section>

<section id="video-stories">
  <div class="sec-head">
    <div><div class="eyebrow">Real People</div><h2 class="section-h2">Real <em>Stories</em></h2></div>
    <div class="carousel-arrows">
      <button class="c-arr" id="vs-prev" aria-label="Previous">←</button>
      <button class="c-arr" id="vs-next" aria-label="Next">→</button>
    </div>
  </div>
  <div class="vs-carousel-wrap">
    <div class="vs-track" id="vs-track">
      <div class="vs-card reveal">
        <div class="vs-img-wrap">
          <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9?w=400&h=700&fit=crop" alt="Isla" loading="lazy">
          <div class="vs-play">Play Video</div>
        </div>
        <div class="vs-body">
          <h3 class="vs-name">Isla's Journey</h3>
          <div class="vs-row"><span class="vs-lbl">Package</span><span class="vs-val">Moderate</span></div>
          <div class="vs-row"><span class="vs-lbl">Duration</span><span class="vs-val">6 Months</span></div>
        </div>
      </div>
      <div class="vs-card reveal">
        <div class="vs-img-wrap">
          <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=400&h=700&fit=crop" alt="Victoria" loading="lazy">
          <div class="vs-play">Play Video</div>
        </div>
        <div class="vs-body">
          <h3 class="vs-name">Victoria's Journey</h3>
          <div class="vs-row"><span class="vs-lbl">Package</span><span class="vs-val">Mild</span></div>
          <div class="vs-row"><span class="vs-lbl">Duration</span><span class="vs-val">3 Months</span></div>
        </div>
      </div>
      <div class="vs-card reveal">
        <div class="vs-img-wrap">
          <img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?w=400&h=700&fit=crop" alt="Heavenleigh" loading="lazy">
          <div class="vs-play">Play Video</div>
        </div>
        <div class="vs-body">
          <h3 class="vs-name">Heavenleigh's Journey</h3>
          <div class="vs-row"><span class="vs-lbl">Package</span><span class="vs-val">Moderate</span></div>
          <div class="vs-row"><span class="vs-lbl">Duration</span><span class="vs-val">4 Months</span></div>
        </div>
      </div>
      <div class="vs-card reveal">
        <div class="vs-img-wrap">
          <img src="https://images.unsplash.com/photo-1531746020798-e6953c6e8e04?w=400&h=700&fit=crop" alt="Kersha" loading="lazy">
          <div class="vs-play">Play Video</div>
        </div>
        <div class="vs-body">
          <h3 class="vs-name">Kersha's Journey</h3>
          <div class="vs-row"><span class="vs-lbl">Package</span><span class="vs-val">Complex</span></div>
          <div class="vs-row"><span class="vs-lbl">Duration</span><span class="vs-val">9 Months</span></div>
        </div>
      </div>
      <div class="vs-card reveal">
        <div class="vs-img-wrap">
          <img src="https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e?w=400&h=700&fit=crop" alt="Chloe" loading="lazy">
          <div class="vs-play">Play Video</div>
        </div>
        <div class="vs-body">
          <h3 class="vs-name">Chloe's Journey</h3>
          <div class="vs-row"><span class="vs-lbl">Package</span><span class="vs-val">Mild</span></div>
          <div class="vs-row"><span class="vs-lbl">Duration</span><span class="vs-val">4 Months</span></div>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="testimonials">
  <div class="sec-head">
    <div><div class="eyebrow">Patient Stories</div><h2 class="section-h2">What Our <em>Patients Say</em></h2></div>
    <div style="display:flex;align-items:center;gap:8px;"><span style="color:var(--gold);font-size:1.05rem;">★★★★★</span><span style="font-size:.8rem;color:var(--slate);">4.9/5 · 247 Google Reviews</span></div>
  </div>
  <div class="t-grid">
    <div class="t-card reveal"><div class="t-stars">★★★★★</div><p class="t-text">"I'd been putting off Invisalign for years out of fear. The team at PearlSmile made me feel completely at ease from my very first visit. My smile has changed my confidence entirely."</p><div class="t-author"><img class="t-avatar" src="https://images.unsplash.com/photo-1502685104226-ee32379fefbe?w=100&q=80&auto=format&fit=crop" alt="Sarah J." loading="lazy" onerror="this.style.display='none';this.nextElementSibling.style.display='flex'"><div class="t-av-fb" style="display:none">SJ</div><div><div class="t-name">Sarah J.</div><div class="t-label">Invisalign Patient · London</div></div></div><div class="t-verified">✓ Verified Google Review</div></div>
    <div class="t-card reveal"><div class="t-stars">★★★★★</div><p class="t-text">"Dental emergency on a Saturday morning — cracked tooth, real pain. They saw me within two hours. The level of care and professionalism was extraordinary."</p><div class="t-author"><div class="t-av-fb">MP</div><div><div class="t-name">Mark P.</div><div class="t-label">Emergency Patient · Kensington</div></div></div><div class="t-verified">✓ Verified Google Review</div></div>
    <div class="t-card reveal"><div class="t-stars">★★★★★</div><p class="t-text">"My veneers look absolutely stunning. Dr. Chen took the time to understand exactly what I wanted and delivered results beyond my expectations."</p><div class="t-author"><img class="t-avatar" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?w=100&q=80&auto=format&fit=crop" alt="Amelia L." loading="lazy" onerror="this.style.display='none';this.nextElementSibling.style.display='flex'"><div class="t-av-fb" style="display:none">AL</div><div><div class="t-name">Amelia L.</div><div class="t-label">Veneer Patient · Mayfair</div></div></div><div class="t-verified">✓ Verified Google Review</div></div>
    <div class="t-card reveal"><div class="t-stars">★★★★★</div><p class="t-text">"Eight shades brighter in one sitting. The whitening gave me results I didn't think were possible without veneers. Worth every penny."</p><div class="t-author"><div class="t-av-fb">RH</div><div><div class="t-name">Rachel H.</div><div class="t-label">Whitening Patient · Chelsea</div></div></div><div class="t-verified">✓ Verified Google Review</div></div>
    <div class="t-card reveal"><div class="t-stars">★★★★★</div><p class="t-text">"Two implants after an accident. The process was explained thoroughly and the results are indistinguishable from my natural teeth. Life-changing."</p><div class="t-author"><div class="t-av-fb">DK</div><div><div class="t-name">David K.</div><div class="t-label">Implant Patient · Islington</div></div></div><div class="t-verified">✓ Verified Google Review</div></div>
    <div class="t-card reveal"><div class="t-stars">★★★★★</div><p class="t-text">"As someone terrified of the dentist, finding PearlSmile changed everything. Gentle, patient, kind. I actually look forward to my check-ups now."</p><div class="t-author"><div class="t-av-fb">FT</div><div><div class="t-name">Fatima T.</div><div class="t-label">Regular Patient · Shoreditch</div></div></div><div class="t-verified">✓ Verified Google Review</div></div>
  </div>
</section>

<section id="faq">
  <div class="faq-layout">
    <div class="faq-side">
      <div class="eyebrow">Common Questions</div>
      <h2 class="section-h2">Everything You<br>Need to <em>Know</em></h2>
      <p>We've answered the questions patients ask most. Still unsure? Call us — there's never any obligation.</p>
      <div style="margin-top:28px;"><a href="tel:+442000000000" class="btn-primary">📞 Call Us Free</a></div>
    </div>
    <div>
      <div class="faq-item"><div class="faq-q"><span class="faq-q-txt">Does the treatment hurt?</span><span class="faq-ico">+</span></div><div class="faq-body"><p>Most treatments are pain-free or minimally uncomfortable. We use the finest anaesthetic techniques and work entirely at your pace. For nervous patients, sedation options are available. Your comfort is always our priority.</p></div></div>
      <div class="faq-item"><div class="faq-q"><span class="faq-q-txt">Do you accept NHS patients?</span><span class="faq-ico">+</span></div><div class="faq-body"><p>PearlSmile is a private practice. However, we offer 0% finance for up to 24 months to make treatments genuinely accessible. Your free consultation includes a full, transparent cost breakdown with no hidden fees.</p></div></div>
      <div class="faq-item"><div class="faq-q"><span class="faq-q-txt">How long does Invisalign take?</span><span class="faq-ico">+</span></div><div class="faq-body"><p>Most Invisalign treatments complete in 6–18 months, with mild cases as short as 3 months. At your free consultation, we take digital scans and show you a projected timeline specific to your teeth.</p></div></div>
      <div class="faq-item"><div class="faq-q"><span class="faq-q-txt">What does a dental implant involve?</span><span class="faq-ico">+</span></div><div class="faq-body"><p>A titanium post is placed into the jawbone in a minor procedure, followed by a 3–6 month healing period. A custom crown is then attached. The result is a permanent, natural-looking tooth. Most patients are surprised by how straightforward it is.</p></div></div>
      <div class="faq-item"><div class="faq-q"><span class="faq-q-txt">Can I get same-day emergency treatment?</span><span class="faq-ico">+</span></div><div class="faq-body"><p>Yes. We keep emergency slots available every day including Saturdays. Call the moment you're in pain and we will do everything possible to see you the same day. Don't suffer in silence.</p></div></div>
      <div class="faq-item"><div class="faq-q"><span class="faq-q-txt">Is the consultation really free?</span><span class="faq-ico">+</span></div><div class="faq-body"><p>Absolutely — no charge, no obligation. We'll discuss your goals, examine your teeth, and present a personalised plan with full transparent costs. You decide if and when to proceed.</p></div></div>
      <div class="faq-item"><div class="faq-q"><span class="faq-q-txt">Do you offer payment plans?</span><span class="faq-ico">+</span></div><div class="faq-body"><p>Yes. 0% interest finance is available for up to 24 months on most treatments over £500, subject to approval. Exceptional dental care should be accessible — we'll help you find a plan that works.</p></div></div>
      <div class="faq-item"><div class="faq-q"><span class="faq-q-txt">I'm very nervous about dentists. Can you help?</span><span class="faq-ico">+</span></div><div class="faq-body"><p>Dental anxiety is very common. Our whole team is trained to support nervous patients. We work at your pace, offer sedation, and maintain a calm, judgement-free environment. You are in safe hands.</p></div></div>
    </div>
  </div>
</section>

<section id="book">
  <div class="eyebrow">Get Started</div>
  <h2 class="section-h2">Book Your <em>Free Consultation</em></h2>
  <div class="book-layout">
    <div class="book-info">
      <p>Take the first step towards your best smile. Your free consultation includes a full examination, personalised treatment plan, and a no-obligation cost breakdown.</p>
      <ul class="book-bullets">
        <li>Completely free — no fees, no commitment</li>
        <li>Our coordinator calls within 2 hours</li>
        <li>0% finance options explained clearly</li>
        <li>Digital scans and full treatment planning</li>
        <li>Mon–Fri 8am–7pm · Sat 9am–3pm</li>
      </ul>
      <div class="book-contacts">
        <a href="tel:+442000000000"><span class="ico">📞</span><span><strong>020 0000 0000</strong><br><small style="color:var(--slate)">Mon–Fri 8am–7pm · Sat 9am–3pm</small></span></a>
        <a href="mailto:hello@pearlsmiledental.com"><span class="ico">✉️</span>hello@pearlsmiledental.com</a>
        <a href="#location"><span class="ico">📍</span>1 Harley Street, London W1G 9QD</a>
      </div>
    </div>
    <div class="form-card">
      <h3 class="form-ttl">Request an Appointment</h3>
      <p class="form-sub">We'll call you within 2 hours to confirm. ★ No spam, ever.</p>
      <form id="booking-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
        <input type="hidden" name="_subject" value="New Appointment Request – PearlSmile Dental">
        <input type="hidden" name="_next" value="thank-you.html">
        <div class="fg"><label for="fname">Full Name *</label><input type="text" id="fname" name="name" placeholder="e.g. Sarah Johnson" required autocomplete="name"></div>
        <div class="fg"><label for="fphone">Phone Number *</label><input type="tel" id="fphone" name="phone" placeholder="e.g. 07700 000000" required autocomplete="tel"></div>
        <div class="fg"><label for="femail">Email Address *</label><input type="email" id="femail" name="email" placeholder="e.g. sarah@email.com" required autocomplete="email"></div>
        <div class="fg">
          <label for="fservice">Treatment of Interest</label>
          <select id="fservice" name="service">
            <option value="">Select a treatment (optional)</option>
            <option>General Check-up & Hygiene</option>
            <option>Teeth Whitening</option>
            <option>Invisalign®</option>
            <option>Porcelain Veneers</option>
            <option>Dental Implants</option>
            <option>Full Smile Makeover</option>
            <option>Emergency Appointment</option>
            <option>Not sure yet</option>
          </select>
        </div>
        <p class="form-privacy">By submitting you agree to our <a href="pages/privacy-policy.html">Privacy Policy</a>. We only collect name, phone & email — never sold.</p>
        <button type="submit" class="btn-submit">Book My Free Consultation →</button>
      </form>
    </div>
  </div>
</section>

<section id="guide">
  <div class="guide-orb"></div>
  <div class="guide-layout">
    <div class="guide-book reveal">
      <div class="book-cover">
        <div class="book-tag">Free Expert Guide · 2025 Edition</div>
        <div class="book-title">The Complete<br>Guide to a<br><em>Perfect Smile</em></div>
        <div class="book-sub">Whitening · Aligners · Implants · Veneers — What Really Works</div>
        <div class="book-brand">Pearl<em>Smile</em> ✦ <span style="font-size:.7rem;color:var(--slate);margin-left:6px;">32 pages · Free PDF</span></div>
      </div>
      <div class="book-pages"></div>
      <div class="book-badge"><strong>FREE</strong>PDF Guide</div>
    </div>
    <div class="guide-text reveal">
      <div class="eyebrow">Free Download</div>
      <h2 class="section-h2">Get Your Free<br><em>Perfect Smile</em> Guide</h2>
      <p>Our 32-page expert guide breaks down every cosmetic dental treatment in plain English — what it costs, how long it takes, and whether it's right for you.</p>
      <ul class="guide-checks">
        <li><span class="ck">✓</span>The truth about teeth whitening (and what actually works)</li>
        <li><span class="ck">✓</span>Is Invisalign really as good as traditional braces?</li>
        <li><span class="ck">✓</span>Veneers vs bonding vs crowns — the clear comparison</li>
        <li><span class="ck">✓</span>Dental implants: the complete patient timeline</li>
        <li><span class="ck">✓</span>Daily habits that protect your smile investment</li>
        <li><span class="ck">✓</span>How to choose the right dentist (checklist inside)</li>
      </ul>
      <div class="guide-form-box" id="gf-wrap">
        <div class="gf-ttl">Get Instant Access <span class="gf-pill">Free</span></div>
        <form id="guide-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
          <input type="hidden" name="_subject" value="Free Guide Download – PearlSmile">
          <div class="gf-row">
            <input type="email" name="email" id="gf-email" placeholder="Your email address" required autocomplete="email">
            <button type="submit" class="gf-btn">Send Guide →</button>
          </div>
          <p class="gf-note">Sent instantly. No spam. See our <a href="pages/privacy-policy.html">Privacy Policy</a>.</p>
        </form>
      </div>
      <div class="guide-success" id="guide-success">
        <div class="gs-ico">📬</div>
        <h4>Your Guide is On Its Way!</h4>
        <p>Check your inbox in 2 minutes. Can't find it? <a href="mailto:hello@pearlsmiledental.com">Email us</a>.</p>
      </div>
    </div>
  </div>
</section>

<section id="location">
  <div class="eyebrow">Find Us</div>
  <h2 class="section-h2">How to <em>Get Here</em></h2>
  <div class="loc-layout">
    <div class="loc-details">
      <div class="loc-item"><div class="loc-ico">📍</div><div><div class="loc-label">Address</div><div class="loc-val">1 Harley Street<br>London, W1G 9QD<br><a href="https://maps.google.com/?q=1+Harley+Street+London" target="_blank" rel="noopener">Get Directions →</a></div></div></div>
      <div class="loc-item"><div class="loc-ico">🚇</div><div><div class="loc-label">Nearest Tube</div><div class="loc-val">Regent's Park (Bakerloo) — 4 min<br>Oxford Circus — 6 min walk</div></div></div>
      <div class="loc-item"><div class="loc-ico">📞</div><div><div class="loc-label">Phone</div><div class="loc-val"><a href="tel:+442000000000">020 0000 0000</a></div></div></div>
      <div class="loc-item"><div class="loc-ico">🕐</div><div><div class="loc-label">Opening Hours</div><div class="loc-val"><div class="hrs"><span class="day">Mon–Fri</span><span class="time">8:00am – 7:00pm</span><span class="day">Saturday</span><span class="time">9:00am – 3:00pm</span><span class="day">Sunday</span><span class="time" style="color:var(--red)">Closed</span></div></div></div></div>
    </div>
    <div class="map-embed">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2482.5285074839697!2d-0.14923812306107!3d51.519409!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48761acec1d2df6d%3A0x6b6aaae7b6f1c62b!2s1%20Harley%20St%2C%20London%20W1G%209QD!5e0!3m2!1sen!2suk!4v1700000000000" width="600" height="400" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" title="PearlSmile Dental on Google Maps"></iframe>
    </div>
  </div>
</section>

<footer>
  <div class="footer-grid">
    <div class="footer-brand">
      <a href="index.html" class="logo" style="font-size:1.5rem;">Pearl<em>Smile</em><span class="logo-star">✦</span></a>
      <p>Award-winning cosmetic and general dentistry on Harley Street, London. Trusted by over 2,500 patients since 2009.</p>
      <div class="trust-badges"><span class="tbadge">🔒 SSL Secured</span><span class="tbadge">GDC Registered</span><span class="tbadge">CQC Regulated</span><span class="tbadge">BDA Member</span></div>
      <div class="f-social">
        <a href="https://facebook.com/pearlsmiledental" target="_blank" rel="noopener" aria-label="Facebook">f</a>
        <a href="https://instagram.com/pearlsmiledental" target="_blank" rel="noopener" aria-label="Instagram">ig</a>
        <a href="https://g.page/pearlsmiledental" target="_blank" rel="noopener" aria-label="Google">G</a>
      </div>
    </div>
    <div class="f-col"><h4>Treatments</h4><a href="#services">Dental Implants</a><a href="#services">Invisalign®</a><a href="#services">Teeth Whitening</a><a href="#services">Porcelain Veneers</a><a href="#services">Emergency Dental</a><a href="#services">Hygiene & Check-ups</a></div>
    <div class="f-col"><h4>Practice</h4><a href="pages/about.html">About Us</a><a href="#testimonials">Patient Reviews</a><a href="#gallery">Smile Gallery</a><a href="#faq">FAQs</a><a href="#location">Location & Hours</a></div>
    <div class="f-col"><h4>Legal</h4><a href="pages/privacy-policy.html">Privacy Policy</a><a href="pages/terms.html">Terms & Conditions</a><a href="pages/cookie-policy.html">Cookie Policy</a><a href="pages/accessibility.html">Accessibility</a><a href="pages/complaints.html">Complaints Policy</a><a href="pages/sitemap.html">Sitemap</a></div>
  </div>
  <div class="footer-bottom">
    <p>© 2025 PearlSmile Dental Ltd. All rights reserved. Registered in England & Wales No. 00000000. GDC No. 000000.</p>
    <div class="legal-links"><a href="pages/privacy-policy.html">Privacy</a><a href="pages/terms.html">Terms</a><a href="pages/cookie-policy.html">Cookies</a></div>
  </div>
</footer>

<div class="pop-overlay" id="pop-welcome" role="dialog" aria-modal="true">
  <div class="pop-box">
    <button class="pop-close" onclick="closePopup('pop-welcome')" aria-label="Close">×</button>
    <img src="https://images.unsplash.com/photo-1629909613654-28e377c37b09?w=600&q=80&auto=format&fit=crop&crop=top" alt="PearlSmile Dental" class="pop-img" loading="lazy">
    <div class="pop-body">
      <div class="pop-tag">Welcome to PearlSmile ✦</div>
      <h2 class="pop-h">Hi 👋 Need Help with<br>Your <em>Smile</em> Today?</h2>
      <p class="pop-p">Your free consultation includes a full examination, personalised treatment plan, and transparent pricing — completely no obligation.</p>
      <div class="pop-btns">
        <a href="#book" class="pop-cta" onclick="closePopup('pop-welcome')">Book Free Consultation →</a>
        <button class="pop-dismiss" onclick="closePopup('pop-welcome')">Maybe Later</button>
      </div>
    </div>
  </div>
</div>

<div class="pop-overlay" id="pop-exit" role="dialog" aria-modal="true">
  <div class="pop-box">
    <button class="pop-close" onclick="closePopup('pop-exit')" aria-label="Close">×</button>
    <img src="https://images.unsplash.com/photo-1588776814546-ec7e33caa1f0?w=600&q=80&auto=format&fit=crop" alt="PearlSmile Dental interior" class="pop-img" loading="lazy">
    <div class="pop-body">
      <div class="pop-tag">Before You Go…</div>
      <h2 class="pop-h">Want a <em>Free Consultation</em><br>Before You Leave?</h2>
      <p class="pop-p">Takes 30 seconds to book. Our coordinator will call you within 2 hours to confirm — completely free, completely no pressure.</p>
      <div class="pop-btns">
        <a href="#book" class="pop-cta" onclick="closePopup('pop-exit')">Yes, Book My Free Consult</a>
        <button class="pop-dismiss" onclick="closePopup('pop-exit')">No thanks</button>
      </div>
    </div>
  </div>
</div>

<div id="oralyn-bubbles" aria-label="Quick chat questions">
  <div class="obubble-q" data-q="Book an appointment"><span class="ob-ico">📅</span> Book Appointment</div>
  <div class="obubble-q" data-q="I have tooth pain"><span class="ob-ico">🦷</span> Tooth Pain Help</div>
  <div class="obubble-q" data-q="Teeth whitening info"><span class="ob-ico">✨</span> Teeth Whitening</div>
  <div class="obubble-q" data-q="Dental implant cost"><span class="ob-ico">💰</span> Implant Cost</div>
  <div class="obubble-q" data-q="Emergency help needed"><span class="ob-ico">🚨</span> Emergency Help</div>
</div>

<button id="oralyn-btn" aria-label="Chat with Oralyn" aria-expanded="false">
  <span class="ob-btn-ico" id="ob-ico">💬</span>
  <span class="ob-notif" id="ob-notif">1</span>
</button>

<div class="oralyn-win" id="oralyn-win" role="dialog" aria-modal="true" aria-label="Oralyn Dental Assistant">
  <div class="o-head">
    <div class="o-ava" aria-hidden="true">🦷</div>
    <div class="o-head-info">
      <div class="o-name">Oralyn</div>
      <div class="o-sub">Your Dental Guide</div>
      <div class="o-status">Online · Replies instantly</div>
    </div>
    <button class="o-close" id="o-close" aria-label="Close">✕</button>
  </div>
  <div class="o-msgs" id="o-msgs" aria-live="polite"></div>
  <div class="o-input-row">
    <input type="text" id="o-input" placeholder="Ask me anything…" autocomplete="off" maxlength="260">
    <button class="o-send" id="o-send" aria-label="Send">➤</button>
  </div>
  <div class="o-powered">Powered by <strong>PearlSmile</strong> · Always here, never pushy</div>
</div>

<script>
/* ══════════ SCROLL PROGRESS ══════════ */
const _sb = document.getElementById('scroll-bar');
window.addEventListener('scroll', () => { _sb.style.width = (window.scrollY / (document.body.scrollHeight - window.innerHeight) * 100) + '%'; }, { passive: true });

/* ══════════ MOBILE MENU ══════════ */
const _ham = document.getElementById('ham');
const _mob = document.getElementById('mob-menu');
_ham.addEventListener('click', () => { _ham.classList.toggle('open'); _mob.classList.toggle('open'); });
document.querySelectorAll('.mob-link, .mob-cta').forEach(l => l.addEventListener('click', () => { _ham.classList.remove('open'); _mob.classList.remove('open'); }));

/* ══════════ SCROLL REVEAL ══════════ */
new IntersectionObserver((entries) => {
  entries.forEach((e, i) => { if (e.isIntersecting) { setTimeout(() => e.target.classList.add('in'), i * 70); } });
}, { threshold: 0.1 }).observe = (function(origObserve) {
  return function(el) { origObserve.call(this, el); };
})(IntersectionObserver.prototype.observe);

const _revObs = new IntersectionObserver((entries) => {
  entries.forEach((e, i) => { if (e.isIntersecting) { setTimeout(() => e.target.classList.add('in'), i * 70); _revObs.unobserve(e.target); } });
}, { threshold: 0.1 });
document.querySelectorAll('.reveal, .stat-cell, .svc-card, .t-card').forEach(el => _revObs.observe(el));

/* ══════════ COUNT-UP ══════════ */
const _cntObs = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (!e.isIntersecting) return;
    const el = e.target, target = +el.dataset.count;
    if (!target) return;
    const suffix = el.querySelector('.acc') ? el.querySelector('.acc').outerHTML : '';
    let cur = 0, step = Math.ceil(target / 55);
    const t = setInterval(() => { cur = Math.min(cur + step, target); el.innerHTML = cur.toLocaleString() + suffix; if (cur >= target) clearInterval(t); }, 22);
    _cntObs.unobserve(el);
  });
}, { threshold: 0.5 });
document.querySelectorAll('[data-count]').forEach(el => _cntObs.observe(el));

/* ══════════ BEFORE/AFTER SLIDERS ══════════ */
document.querySelectorAll('.ba-wrap').forEach(wrap => {
  const bef = wrap.querySelector('.ba-before');
  const line = wrap.querySelector('.ba-line');
  const handle = wrap.querySelector('.ba-handle');
  let drag = false;
  const set = x => {
    const r = wrap.getBoundingClientRect();
    const p = Math.max(4, Math.min(96, (x - r.left) / r.width * 100));
    bef.style.clipPath = 'inset(0 ' + (100 - p) + '% 0 0)';
    line.style.left = p + '%';
    handle.style.left = p + '%';
  };
  wrap.addEventListener('mousedown', e => { drag = true; set(e.clientX); e.preventDefault(); });
  window.addEventListener('mousemove', e => { if (drag) set(e.clientX); });
  window.addEventListener('mouseup', () => drag = false);
  wrap.addEventListener('touchstart', e => { drag = true; set(e.touches[0].clientX); }, { passive: true });
  window.addEventListener('touchmove', e => { if (drag) set(e.touches[0].clientX); }, { passive: true });
  window.addEventListener('touchend', () => drag = false);
});

/* ══════════ CAROUSEL ══════════ */
(function() {
  const track = document.getElementById('carousel-track');
  const dotsWrap = document.getElementById('carousel-dots');
  const curEl = document.getElementById('slide-cur');
  const totEl = document.getElementById('slide-tot');
  const slides = track.querySelectorAll('.c-slide');
  const N = slides.length;
  let cur = 0;
  totEl.textContent = N;
  for (let i = 0; i < N; i++) {
    const d = document.createElement('button');
    d.className = 'c-dot' + (i === 0 ? ' active' : '');
    d.setAttribute('aria-label', 'Slide ' + (i + 1));
    d.addEventListener('click', () => go(i));
    dotsWrap.appendChild(d);
  }
  function go(n) {
    cur = (n + N) % N;
    track.style.transform = 'translateX(-' + (cur * 100) + '%)';
    document.querySelectorAll('.c-dot').forEach((d, i) => d.classList.toggle('active', i === cur));
    curEl.textContent = cur + 1;
  }
  document.getElementById('c-prev').addEventListener('click', () => go(cur - 1));
  document.getElementById('c-next').addEventListener('click', () => go(cur + 1));
  let auto = setInterval(() => go(cur + 1), 6000);
  const wrap = track.closest('.carousel-wrap');
  wrap.addEventListener('mouseenter', () => clearInterval(auto));
  wrap.addEventListener('mouseleave', () => { auto = setInterval(() => go(cur + 1), 6000); });
  let tx0 = 0;
  track.addEventListener('touchstart', e => tx0 = e.touches[0].clientX, { passive: true });
  track.addEventListener('touchend', e => { const dx = e.changedTouches[0].clientX - tx0; if (Math.abs(dx) > 48) go(cur + (dx < 0 ? 1 : -1)); });
})();

/* ══════════ FAQ ══════════ */
document.querySelectorAll('.faq-q').forEach(q => {
  q.addEventListener('click', () => {
    const item = q.parentElement, was = item.classList.contains('open');
    document.querySelectorAll('.faq-item.open').forEach(i => i.classList.remove('open'));
    if (!was) item.classList.add('open');
  });
});

/* ══════════ BOOKING FORM ══════════ */
document.getElementById('booking-form').addEventListener('submit', function() {
  const b = this.querySelector('.btn-submit'); b.textContent = 'Sending…'; b.style.opacity = '.7';
});

/* ══════════ GUIDE FORM ══════════ */
document.getElementById('guide-form').addEventListener('submit', function(e) {
  e.preventDefault();
  if (!document.getElementById('gf-email').value) return;
  fetch(this.action, { method: 'POST', body: new FormData(this), headers: { Accept: 'application/json' } }).catch(() => {});
  document.getElementById('gf-wrap').style.display = 'none';
  document.getElementById('guide-success').classList.add('show');
});

/* ══════════ POPUPS ══════════ */
const _dism = new Set(JSON.parse(sessionStorage.getItem('ps_pop') || '[]'));
function closePopup(id) {
  document.getElementById(id).classList.remove('show');
  _dism.add(id);
  sessionStorage.setItem('ps_pop', JSON.stringify([..._dism]));
}
function showPopup(id) { if (!_dism.has(id)) document.getElementById(id).classList.add('show'); }
document.querySelectorAll('.pop-overlay').forEach(o => o.addEventListener('click', e => { if (e.target === o) closePopup(o.id); }));
setTimeout(() => showPopup('pop-welcome'), 5000);
let _exitDone = false;
document.addEventListener('mouseleave', e => {
  if (e.clientY < 50 && !_exitDone && !_dism.has('pop-welcome')) { _exitDone = true; showPopup('pop-exit'); }
});
let _lastSY = 0;
window.addEventListener('scroll', () => {
  const sy = window.scrollY;
  if (sy < _lastSY - 130 && sy > 300 && !_exitDone && !_dism.has('pop-welcome')) { _exitDone = true; setTimeout(() => showPopup('pop-exit'), 800); }
  _lastSY = sy;
}, { passive: true });

/* ══════════ ORALYN CHATBOT ══════════ */
(function() {
  const oBtn = document.getElementById('oralyn-btn');
  const oWin = document.getElementById('oralyn-win');
  const oIco = document.getElementById('ob-ico');
  const oNotif = document.getElementById('ob-notif');
  const oMsgs = document.getElementById('o-msgs');
  const oInput = document.getElementById('o-input');
  const oSend = document.getElementById('o-send');
  const oClose = document.getElementById('o-close');
  const oBubbles = document.getElementById('oralyn-bubbles');

  let open = false, inited = false;
  let bFlow = false, bStep = 0, bData = {};

  const now = () => new Date().toLocaleTimeString('en-GB', { hour: '2-digit', minute: '2-digit' });
  const fmt = t => t.replace(/\*\*(.*?)\*\*/g, '<strong>$1</strong>').replace(/\n/g, '<br>');

  const KB = [
    { k: ['emergency','pain','hurt','hurts','ache','toothache','broken tooth','cracked','swollen','swelling','bleeding','abscess','fell out','chipped','lost filling'],
      r: ["Oh no, I'm so sorry to hear you're in pain 😔\n\nPlease call us right now — don't wait:\n\n📞 **<a href='tel:+442000000000' style='color:#00a88a;font-weight:700'>020 0000 0000</a>**\n\nWe hold emergency slots every day including Saturdays and will do everything to see you today.",
          "That sounds really painful — let's get you help straight away.\n\n📞 **<a href='tel:+442000000000' style='color:#00a88a;font-weight:700'>020 0000 0000</a>**\n\nCall us now and we'll get you seen today if at all possible. You don't have to suffer through this."],
      q: ['📞 Call emergency line', 'How quickly can I be seen?', 'What causes tooth pain?'] },
    { k: ['nervous','scared','anxious','anxiety','fear','phobia','terrified','worried','hate dentist','dental fear','needle'],
      r: ["I completely understand — and you're absolutely not alone. Dental anxiety affects so many people.\n\nAt PearlSmile:\n• We work entirely **at your pace** — never rushed\n• **Sedation options** are available\n• Calm, warm, judgement-free environment\n\nHundreds of our most anxious patients are now our most loyal. You're in safe hands 💙"],
      q: ['Tell me about sedation', '📅 Book gentle appointment', '📞 Call to chat first'] },
    { k: ['what causes tooth pain','why tooth hurts','sensitivity','sensitive teeth','pain when biting'],
      r: ["Tooth pain can have several causes — only an exam can confirm for certain:\n\n• **Cavity** reaching the nerve\n• **Cracked tooth** (can be subtle)\n• **Gum disease** or infection\n• **Abscess** — needs urgent attention\n• **Teeth grinding** (bruxism)\n• **Exposed root / sensitivity**\n\nIf pain is severe or constant — please call us today."],
      q: ['📅 Book urgent appointment', '📞 Call now', 'How quickly can I be seen?'] },
    { k: ['price','cost','how much','fee','afford','finance','0%','payment plan','pay monthly','what does it cost'],
      r: ["Here's an honest price guide:\n\n• Hygiene clean — from **£95**\n• Teeth whitening — from **£299**\n• Composite bonding — from **£250**\n• Invisalign — from **£2,400**\n• Veneers — from **£650/tooth**\n• Dental implants — from **£2,800**\n\nWe offer **0% finance up to 24 months** — making world-class dentistry genuinely accessible."],
      q: ['0% finance explained', '📅 Book free consultation', 'Invisalign cost'] },
    { k: ['invisalign','aligner','clear braces','straight teeth','straighten','crooked','orthodontic'],
      r: ["Invisalign is one of our most-loved treatments 😊 We're a **Diamond-level provider** — top 1% in the UK.\n\n• Nearly invisible — most people won't notice\n• Removable for eating and brushing\n• Most cases: **6–18 months**\n• From **£2,400** with 0% finance\n• Digital scan shows your result day one"],
      q: ['📅 Book Invisalign scan', 'How long does it take?', 'Invisalign cost'] },
    { k: ['whiten','whitening','yellow teeth','stained','brighter smile','discoloured teeth'],
      r: ["Teeth whitening is our most popular treatment 🤩\n\n• Up to **8 shades brighter** in a single 90-min session\n• Safe, GDC-approved, professionally supervised\n• Results last **12–24 months**\n• From **£299** including take-home maintenance kit\n\nSo much more effective than anything over-the-counter."],
      q: ['📅 Book whitening', 'Is whitening safe?', 'How long do results last?'] },
    { k: ['veneer','veneers','porcelain','hollywood smile','chipped tooth','gaps in teeth','bonding'],
      r: ["Veneers are truly transformative ✨ Your dream smile in 2–3 visits.\n\n• Ultra-thin shells bonded to front of teeth\n• Transform colour, shape & size\n• Completely natural-looking\n• From **£650/tooth** · Full smile from **£3,900**\n• Last **10–15 years** · 0% finance available"],
      q: ['📅 Book veneer consultation', 'Veneers vs whitening', 'How many visits?'] },
    { k: ['implant','implants','missing tooth','missing teeth','replace tooth','permanent tooth'],
      r: ["Dental implants are genuinely life-changing 🦷\n\n• Titanium post fused to jawbone (minor procedure)\n• Healing takes **3–6 months**\n• Crown attached — **indistinguishable from a real tooth**\n• From **£2,800** · 0% finance available\n• Protects jawbone & neighbouring teeth"],
      q: ['📅 Book implant consultation', 'How long does it take?', 'Implant cost & finance'] },
    { k: ['book','appointment','schedule','reserve','free consult','book an appointment'],
      r: ["I'd love to help! 😊 Your **free consultation** includes:\n✓ Full dental examination\n✓ Personalised treatment plan\n✓ Transparent cost breakdown\n✓ Zero pressure or obligation\n\nShall I take your details? Just need your name & number — takes 30 seconds.",
          "Of course — booking is easy and completely free.\n\nCould I start with your **full name**? Our coordinator will call you within 2 hours to confirm."],
      q: ['📅 Yes, book me in', '📞 Call to book instead', 'What happens at my consultation?'] },
    { k: ['first visit','new patient','what happens','what to expect','consultation process'],
      r: ["Your first visit is completely relaxed — promise! Here's what happens:\n\n1. **Welcome** — friendly chat, cup of tea\n2. **Your goals** — we listen\n3. **Gentle examination**\n4. **Digital X-rays** if needed (free)\n5. **Treatment plan** personalised to you\n6. **Full cost breakdown** — no surprises\n\nNo pressure to start any treatment whatsoever 😊"],
      q: ['📅 Book free consultation', 'Is it really free?', 'What should I bring?'] },
    { k: ['hours','open','opening','what time','saturday','sunday','weekend','closed'],
      r: ["We're open most of the week:\n\n🗓 **Mon–Fri**: 8:00am – 7:00pm\n🗓 **Saturday**: 9:00am – 3:00pm\n🗓 **Sunday**: Closed\n\nEmergency slots available every day including Saturdays."],
      q: ['📅 Book appointment', '📍 Find us', '📞 Call us'] },
    { k: ['where are you','location','address','harley','directions','tube','underground'],
      r: ["We're in London's medical heart:\n\n📍 **1 Harley Street, London W1G 9QD**\n\n🚇 Regent's Park (Bakerloo) — 4 min walk\n🚇 Oxford Circus — 6 min walk\n🚗 NCP Cavendish Square nearby"],
      q: ['🗺 Get directions', 'Opening hours', '📅 Book appointment'] },
    { k: ['nhs','insurance','bupa','axa','covered','private'],
      r: ["PearlSmile is a **private practice** — we don't work with NHS or insurance plans directly.\n\nHowever, we offer **0% finance up to 24 months**, making treatments very manageable. Initial consultation is always completely free."],
      q: ['See treatment prices', '0% finance explained', '📅 Book free consultation'] },
    { k: ['sedation','sedated','sleep dentist','conscious sedation','gas and air'],
      r: ["Absolutely — sedation is something we offer and are very experienced with 💙\n\n**Conscious sedation** means you stay awake but feel deeply relaxed and calm. Many patients remember very little. Everything is entirely on your terms."],
      q: ['📅 Book sedation consultation', 'Tell me about anxiety support', '📞 Call to discuss'] },
    { k: ['how long','timeline','how many appointments','how many visits','treatment time'],
      r: ["Timelines vary by treatment:\n\n• Hygiene — 45–60 mins\n• Whitening — single 90-min session\n• Veneers — 2–3 appointments (~2 weeks)\n• Invisalign — **6–18 months**\n• Implants — **3–9 months** (mostly healing)\n\nWe give you a precise personal timeline at your free consultation."],
      q: ['📅 Book free consultation', 'Invisalign timeline', 'Implant timeline'] },
    { k: ['hi','hello','hey','hiya','good morning','good afternoon','howdy'],
      r: ["Hi there! 😊 How are you doing today? I'm Oralyn — here to help with anything dental. What's on your mind?",
          "Hello! 😊 I'm Oralyn, PearlSmile's virtual guide. Anything I can help with today?",
          "Hey! 👋 How are you? I'm Oralyn — happy to help with dental questions, bookings, or anything else."],
      q: ['📅 Book appointment', 'Treatments & prices', '🚨 Emergency help'] },
    { k: ['how are you','how are you doing'],
      r: ["I'm doing really well, thanks for asking! 😊 More importantly — how are you? Anything I can help with today?"],
      q: ['📅 Book appointment', 'Ask a question'] },
    { k: ['who are you','are you a robot','are you ai','are you human','what is oralyn'],
      r: ["I'm **Oralyn** — PearlSmile Dental's virtual assistant 🦷 I answer questions, explain treatments, and help you book appointments.\n\nI try to be as helpful and human as possible. If I can't help, I'll connect you with our team directly."],
      q: ['📅 Book appointment', 'Ask a dental question'] },
  ];

  const ACTIONS = {
    '📞 Call emergency line': () => { window.location.href = 'tel:+442000000000'; },
    '📞 Call to chat first':  () => { window.location.href = 'tel:+442000000000'; },
    '📞 Call us now':         () => { window.location.href = 'tel:+442000000000'; },
    '📞 Call to book instead':() => { window.location.href = 'tel:+442000000000'; },
    '📞 Call now':            () => { window.location.href = 'tel:+442000000000'; },
    '📞 Call us':             () => { window.location.href = 'tel:+442000000000'; },
    '📞 Call to discuss':     () => { window.location.href = 'tel:+442000000000'; },
    '🗺 Get directions':      () => { window.open('https://maps.google.com/?q=1+Harley+Street+London', '_blank'); },
    '📍 Find us':             () => { scrollTo('#location'); },
    '📅 Book appointment':          () => startBook(),
    '📅 Book free consultation':    () => startBook(),
    '📅 Book gentle appointment':   () => startBook(),
    '📅 Book urgent appointment':   () => startBook(),
    '📅 Yes, book me in':           () => startBook(),
    '📅 Book whitening':            () => startBook(),
    '📅 Book veneer consultation':  () => startBook(),
    '📅 Book implant consultation': () => startBook(),
    '📅 Book Invisalign scan':      () => startBook(),
    '📅 Book sedation consultation':() => startBook(),
    'Book an appointment':          () => startBook(),
    'Go to booking form':           () => scrollTo('#book'),
    'Opening hours':     () => bot(reply('hours')),
    'Treatments & prices': () => bot({ t: "Quick price guide:\n• Hygiene from **£95**\n• Whitening from **£299**\n• Invisalign from **£2,400**\n• Veneers from **£650/tooth**\n• Implants from **£2,800**\n\n0% finance available.", q: ['📅 Book free consultation', '0% finance explained'] }),
    '0% finance explained': () => bot({ t: "**0% finance** lets you spread cost over up to **24 months with zero interest** (subject to approval).\n\n• Invisalign £2,400 = **£100/month** (24 mo)\n• Implant £2,800 = **£116/month** (24 mo)\n\nWe walk you through all options at your free consultation.", q: ['📅 Book free consultation', '📞 Call us'] }),
    'Invisalign cost':    () => bot({ t: "Invisalign starts from **£2,400** for mild cases. Most full treatments: £2,800–£4,200.\n\nAs a Diamond-level provider we handle more complex cases than most UK practices. 0% finance from **£100/month**.", q: ['📅 Book Invisalign scan', '0% finance explained'] }),
    'Implant cost & finance': () => bot({ t: "Dental implants start from **£2,800** per implant — covering the full procedure, healing, and final crown.\n\nWith 0% finance: from **£116/month** over 24 months.", q: ['📅 Book implant consultation', '0% finance explained'] }),
    'Whitening cost':     () => bot({ t: "Professional whitening starts from **£299** — including the 90-min in-chair session (up to 8 shades brighter) plus a take-home maintenance kit.", q: ['📅 Book whitening', 'Is whitening safe?'] }),
    'Veneers vs whitening': () => bot({ t: "**Whitening** — best when teeth are healthy but discoloured. Quick, affordable, reversible.\n\n**Veneers** — best to also change shape, size, or fix chips. More transformative, bigger investment.\n\nNot sure which? That's what your free consultation is for.", q: ['📅 Book free consultation'] }),
    'How long does it take?':  () => bot(reply('how long')),
    'How many visits?':        () => bot(reply('how many visits')),
    'Is whitening safe?':      () => bot({ t: "Yes — completely safe when done by a trained dentist. We use clinically-approved agents at personalised concentrations.\n\nOver-the-counter products can cause damage because concentrations aren't controlled or personalised.", q: ['📅 Book whitening'] }),
    'How long do results last?': () => bot({ t: "Professional whitening lasts **12–24 months** depending on diet and oral hygiene. We include a take-home top-up kit. Most patients do a quick annual refresh.", q: ['📅 Book whitening'] }),
    'Tell me about sedation':     () => bot(reply('sedation')),
    'Tell me about anxiety support': () => bot(reply('nervous')),
    'What causes tooth pain?':    () => bot(reply('what causes tooth pain')),
    'How quickly can I be seen?': () => bot({ t: "For emergencies we aim for **same day** — we hold slots every day including Saturdays.\n\nFor routine bookings: usually **1–3 working days**.\n\nIf in pain now, please call:\n📞 **<a href='tel:+442000000000' style='color:#00a88a;font-weight:700'>020 0000 0000</a>**", q: ['📞 Call now', '📅 Book appointment'] }),
    'Invisalign timeline':   () => bot({ t: "Most Invisalign treatments complete in **6–18 months**. Mild cases can be as quick as 3 months.\n\nAt your free consultation we take a digital scan and show you a projected animated result on the same day!", q: ['📅 Book Invisalign scan'] }),
    'Implant timeline':      () => bot({ t: "Full implant process takes **3–9 months** — most of which is healing time:\n\n1. Post placed (minor procedure)\n2. Healing: 3–6 months\n3. Crown fitted (1–2 appointments)\n\nMost patients are surprised by how comfortable it is.", q: ['📅 Book implant consultation'] }),
    'What happens at my consultation?': () => bot(reply('first visit')),
    'Is it really free?':    () => bot({ t: "100% free — no card needed, no obligation. We believe once you see what we can do for your smile, you'll want to proceed. But there's never any pressure at all.", q: ['📅 Book free consultation'] }),
    'What should I bring?':  () => bot({ t: "Just yourself! 😊 Bring any old dental records or X-rays if you have them — but it's not necessary. We take our own digital scans as part of your free consultation.", q: ['📅 Book free consultation'] }),
    'Ask a dental question': () => bot({ t: "Of course — go ahead! Ask me anything about treatments, costs, what to expect, or anything else 😊", q: [] }),
    '🚨 Emergency help':     () => bot(reply('emergency')),
    'Teeth whitening info':  () => bot(reply('whitening')),
    'Dental implant cost':   () => bot(reply('implant')),
    'I have tooth pain':     () => bot(reply('pain')),
    'Emergency help needed': () => bot(reply('emergency')),
  };

  function scrollTo(id) { if (open) toggle(); setTimeout(() => document.querySelector(id).scrollIntoView({ behavior: 'smooth' }), 400); }

  function reply(input) {
    const txt = (input || '').toLowerCase();
    for (const item of KB) { if (item.k.some(k => txt.includes(k))) { const r = item.r[Math.floor(Math.random() * item.r.length)]; return { t: r, q: item.q || [] }; } }
    return { t: "That's a great question — let me connect you with our team for the best answer:\n\n📞 **<a href='tel:+442000000000' style='color:#00a88a;font-weight:700'>020 0000 0000</a>**\n✉️ hello@pearlsmiledental.com\n\nOr book a **free consultation** and get everything answered in person.", q: ['📅 Book free consultation', '📞 Call us'] };
  }

  function startBook() { bFlow = true; bStep = 1; bData = {}; bot({ t: "Great — let's get that booked! 😊\n\nFirst, could I get your **full name**?", q: [] }); }

  function handleBook(text) {
    if (bStep === 1) { bData.name = text; bStep = 2; bot({ t: "Lovely to meet you, **" + text + "** 😊\n\nWhat's the best **phone number** for our coordinator?", q: [] }); }
    else if (bStep === 2) { bData.phone = text; bStep = 3; bot({ t: "Perfect. What **treatment** are you interested in, or just a general free consultation?", q: ['General consultation', 'Teeth whitening', 'Invisalign®', 'Dental implants', 'Porcelain veneers', 'Emergency appointment'] }); }
    else if (bStep === 3) {
      bData.treatment = text; bStep = 0; bFlow = false;
      bot({ t: "All done ✅\n\n• Name: **" + bData.name + "**\n• Phone: **" + bData.phone + "**\n• Interest: **" + text + "**\n\nOur coordinator will **call you within 2 hours** to confirm. You're one step closer to your best smile! 😊", q: ['Go to booking form', '📞 Call us instead'] });
      setTimeout(() => document.querySelector('#book').scrollIntoView({ behavior: 'smooth' }), 2400);
    }
  }

  function bot(obj) {
    const text = obj.t || obj || '', followUp = obj.q || [];
    const typ = document.createElement('div');
    typ.className = 'omsg bot otyping';
    typ.innerHTML = '<div class="o-row"><div class="o-ava-sm">🦷</div><div class="o-bubble"><span class="otd"></span><span class="otd"></span><span class="otd"></span></div></div>';
    oMsgs.appendChild(typ); oMsgs.scrollTop = 99999;
    const delay = Math.min(450 + text.length * 1.2, 1900);
    setTimeout(() => {
      if (typ.parentNode) oMsgs.removeChild(typ);
      const m = document.createElement('div');
      m.className = 'omsg bot';
      let html = '<div class="o-row"><div class="o-ava-sm">🦷</div><div class="o-bubble">' + fmt(text) + '</div></div>';
      if (followUp.length) html += '<div class="o-qrs">' + followUp.map(q => '<button class="o-qr" data-q="' + q.replace(/"/g, '"') + '">' + q + '</button>').join('') + '</div>';
      html += '<div class="o-time">Oralyn · ' + now() + '</div>';
      m.innerHTML = html;
      oMsgs.appendChild(m); oMsgs.scrollTop = 99999;
      m.querySelectorAll('.o-qr').forEach(b => b.addEventListener('click', () => handleQR(b.dataset.q)));
    }, delay);
  }

  function user(text) {
    const m = document.createElement('div');
    m.className = 'omsg usr';
    m.innerHTML = '<div class="o-row"><div class="o-bubble">' + text + '</div></div><div class="o-time">' + now() + ' <span class="o-read">✓✓</span></div>';
    oMsgs.appendChild(m); oMsgs.scrollTop = 99999;
  }

  function handleQR(label) {
    document.querySelectorAll('.obubble-q').forEach(b => b.classList.add('gone'));
    user(label);
    if (ACTIONS[label]) { setTimeout(() => ACTIONS[label](), 120); }
    else if (bFlow) { handleBook(label); }
    else { bot(reply(label)); }
  }

  function send() {
    const v = oInput.value.trim(); if (!v) return; oInput.value = '';
    document.querySelectorAll('.obubble-q').forEach(b => b.classList.add('gone'));
    user(v);
    if (bFlow) { handleBook(v); return; }
    if (ACTIONS[v]) { setTimeout(() => ACTIONS[v](), 100); return; }
    bot(reply(v));
  }

  function toggle() {
    open = !open;
    oWin.classList.toggle('open', open);
    oBtn.classList.toggle('open', open);
    oBtn.setAttribute('aria-expanded', String(open));
    oIco.textContent = open ? '✕' : '💬';
    oNotif.style.display = 'none';
    if (open && !inited) {
      inited = true;
      const sep = document.createElement('div'); sep.className = 'o-day-sep'; sep.textContent = 'Today';
      oMsgs.appendChild(sep);
      setTimeout(() => bot({ t: "Hi, I'm **Oralyn** — your dental guide here at PearlSmile 🦷\n\nHow are you today? How can I help?", q: ['📅 Book an appointment', 'I have tooth pain', 'Teeth whitening info', 'Dental implant cost', '🚨 Emergency help needed'] }), 400);
    }
    if (open) setTimeout(() => oInput.focus(), 480);
  }

  oBtn.addEventListener('click', toggle);
  oClose.addEventListener('click', toggle);
  oSend.addEventListener('click', send);
  oInput.addEventListener('keydown', e => { if (e.key === 'Enter' && !e.shiftKey) { e.preventDefault(); send(); } });
  document.addEventListener('keydown', e => { if (e.key === 'Escape' && open) toggle(); });

  // Floating bubbles
  const bubbles = document.querySelectorAll('.obubble-q');
  setTimeout(() => {
    oBubbles.classList.add('visible');
    bubbles.forEach((b, i) => { setTimeout(() => b.classList.add('in'), i * 150); });
    setTimeout(() => { bubbles.forEach(b => b.classList.add('gone')); setTimeout(() => oBubbles.classList.remove('visible'), 500); }, 14000);
  }, 2500);
  bubbles.forEach(b => {
    b.addEventListener('click', () => {
      const q = b.dataset.q;
      bubbles.forEach(bb => bb.classList.add('gone'));
      if (!open) { open = false; toggle(); }
      const d = inited ? 250 : 950;
      setTimeout(() => { user(q); bot(reply(q)); }, d);
      inited = true;
    });
  });

  setTimeout(() => { if (!inited) oNotif.style.display = 'flex'; }, 4000);
  if (window.location.hash === '#emergency') setTimeout(toggle, 700);
})();

/* ══════════ VIDEO STORIES ══════════ */
const vsTrack = document.getElementById('vs-track');
const vsPrev = document.getElementById('vs-prev');
const vsNext = document.getElementById('vs-next');
if (vsTrack && vsPrev && vsNext) {
  vsPrev.addEventListener('click', () => { vsTrack.scrollBy({ left: -vsTrack.offsetWidth / 2, behavior: 'smooth' }); });
  vsNext.addEventListener('click', () => { vsTrack.scrollBy({ left: vsTrack.offsetWidth / 2, behavior: 'smooth' }); });
}
</script>
</body>
</html>
