# D.H.Hausmeister Garten Landschaftsservice-
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>D. H. Hausmeister Gartenlandschaftsservice</title>

<meta name="description" content="D. H. Hausmeister Gartenlandschaftsservice – Gartenpflege, Hausmeisterservice, Winterdienst, Fensterreinigung, Fassadenreinigung und Steinreinigung. Kontaktieren Sie uns für Ihre Anfrage.">

<meta name="theme-color" content="#142c22">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Manrope:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<style>
:root {
    --green: #142c22;
    --green-light: #244737;
    --cream: #f5f4ed;
    --white: #ffffff;
    --gold: #c5a66b;
    --text: #202923;
    --muted: #6e776f;
    --border: rgba(20,44,34,.14);
    --radius: 18px;
    --shadow: 0 18px 55px rgba(20,44,34,.10);
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: 90px;
}

body {
    font-family: 'DM Sans', sans-serif;
    color: var(--text);
    background: var(--cream);
    line-height: 1.7;
    overflow-x: hidden;
}

h1, h2, h3, h4 {
    font-family: 'Manrope', sans-serif;
    line-height: 1.15;
    letter-spacing: -.035em;
}

a {
    color: inherit;
    text-decoration: none;
}

img {
    display: block;
    width: 100%;
    object-fit: cover;
}

button, input, textarea, select {
    font: inherit;
}

.container {
    width: min(1180px, 90%);
    margin-inline: auto;
}

.eyebrow {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    color: var(--green-light);
    font-size: .75rem;
    font-weight: 700;
    letter-spacing: .16em;
    text-transform: uppercase;
    margin-bottom: 20px;
}

.eyebrow::before {
    content: "";
    width: 26px;
    height: 2px;
    background: var(--gold);
}

.section {
    padding: 110px 0;
}

.section-heading {
    max-width: 700px;
    margin-bottom: 48px;
}

.section-heading h2 {
    font-size: clamp(2rem, 5vw, 3.6rem);
    color: var(--green);
    margin-bottom: 20px;
}

.section-heading p {
    color: var(--muted);
    max-width: 580px;
}

/* Navigation */

.navbar {
    position: fixed;
    inset: 0 0 auto;
    z-index: 1000;
    background: rgba(245,244,237,.94);
    backdrop-filter: blur(16px);
    border-bottom: 1px solid rgba(20,44,34,.08);
}

.nav-inner {
    min-height: 82px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 24px;
}

.logo {
    display: flex;
    align-items: center;
    gap: 12px;
    color: var(--green);
    font-family: 'Manrope', sans-serif;
    font-weight: 800;
    font-size: 1.02rem;
    line-height: 1.2;
}

.logo-mark {
    width: 44px;
    height: 44px;
    border: 1px solid var(--gold);
    display: grid;
    place-items: center;
    border-radius: 12px;
    font-size: .9rem;
    letter-spacing: -.04em;
}

.logo small {
    display: block;
    margin-top: 4px;
    font-family: 'DM Sans', sans-serif;
    font-size: .65rem;
    font-weight: 500;
    color: var(--muted);
    letter-spacing: .04em;
}

.nav-links {
    display: flex;
    align-items: center;
    gap: 27px;
    font-size: .86rem;
    font-weight: 600;
}

.nav-links a:not(.button):hover {
    color: #9a7a40;
}

.button {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
    padding: 14px 22px;
    border: 1px solid transparent;
    border-radius: 6px;
    background: var(--green);
    color: var(--white);
    font-size: .88rem;
    font-weight: 700;
    transition: background .25s ease,
                color .25s ease,
                transform .25s ease;
    cursor: pointer;
}

.button:hover {
    background: var(--green-light);
    transform: translateY(-2px);
}

.button-light {
    color: var(--green);
    background: var(--white);
}

.button-light:hover {
    background: var(--cream);
}

.button-outline {
    color: var(--green);
    border-color: var(--border);
    background: transparent;
}

.button-outline:hover {
    background: var(--green);
    color: var(--white);
}

.menu-toggle {
    display: none;
    background: transparent;
    border: 0;
    color: var(--green);
    font-size: 1.7rem;
    cursor: pointer;
}

/* Hero */

.hero {
    position: relative;
    min-height: 760px;
    min-height: min(850px, 100svh);
    display: flex;
    align-items: center;
    padding: 150px 0 90px;
    background: var(--green);
    color: var(--white);
    overflow: hidden;
}

.hero-image {
    position: absolute;
    inset: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
    opacity: .65;
    animation: heroZoom 14s ease-in-out infinite alternate;
}

.hero::after {
    content: "";
    position: absolute;
    inset: 0;
    background: linear-gradient(
        90deg,
        rgba(10,28,20,.92) 0%,
        rgba(10,28,20,.75) 48%,
        rgba(10,28,20,.20) 100%
    );
}

.hero-content {
    position: relative;
    z-index: 1;
    max-width: 780px;
}

.hero .eyebrow {
    color: #e7d5ad;
}

.hero h1 {
    font-size: clamp(2.8rem, 7.5vw, 6.2rem);
    font-weight: 700;
    line-height: 1.04;
    margin-bottom: 28px;
}

.hero h1 span {
    color: #d7bd86;
}

.hero p {
    max-width: 590px;
    color: rgba(255,255,255,.83);
    font-size: clamp(1rem, 2vw, 1.15rem);
    margin-bottom: 34px;
}

.hero-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 14px;
}

.hero-note {
    margin-top: 55px;
    display: flex;
    flex-wrap: wrap;
    gap: 24px;
    color: rgba(255,255,255,.8);
    font-size: .85rem;
}

.hero-note span::before {
    content: "✓";
    color: #d7bd86;
    margin-right: 8px;
}

.scroll-cue {
    position: absolute;
    z-index: 2;
    right: 5%;
    bottom: 35px;
    color: rgba(255,255,255,.75);
    font-size: .7rem;
    letter-spacing: .15em;
    text-transform: uppercase;
    writing-mode: vertical-rl;
}

.scroll-cue::after {
    content: "";
    display: inline-block;
    width: 1px;
    height: 45px;
    background: var(--gold);
    margin-top: 12px;
    animation: lineMove 1.8s ease-in-out infinite;
}

/* Intro */

.intro-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 75px;
    align-items: center;
}

.intro-image-wrap {
    position: relative;
}

.intro-image {
    height: 520px;
    border-radius: var(--radius);
    box-shadow: var(--shadow);
}

.image-caption {
    position: absolute;
    right: -20px;
    bottom: 24px;
    padding: 20px 24px;
    max-width: 230px;
    background: var(--white);
    border-radius: 12px;
    box-shadow: var(--shadow);
    color: var(--green);
    font-size: .88rem;
    font-weight: 700;
}

.intro-copy h2 {
    font-size: clamp(2.2rem, 4.5vw, 3.7rem);
    color: var(--green);
    margin-bottom: 24px;
}

.intro-copy p {
    color: var(--muted);
    margin-bottom: 18px;
}

.intro-copy .button {
    margin-top: 14px;
}

/* Services */

.services {
    background: var(--white);
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 22px;
}

.service-card {
    background: var(--cream);
    border-radius: var(--radius);
    overflow: hidden;
    transition: transform .35s ease, box-shadow .35s ease;
}

.service-card:hover {
    transform: translateY(-7px);
    box-shadow: var(--shadow);
}

.service-card img {
    height: 230px;
    transition: transform .6s ease;
}

.service-card:hover img {
    transform: scale(1.045);
}

.service-image {
    overflow: hidden;
}

.service-body {
    padding: 26px;
}

.service-number {
    display: block;
    color: #a58a54;
    font-size: .75rem;
    font-weight: 700;
    letter-spacing: .13em;
    margin-bottom: 14px;
}

.service-body h3 {
    color: var(--green);
    font-size: 1.35rem;
    margin-bottom: 12px;
}

.service-body p {
    color: var(--muted);
    font-size: .93rem;
    margin-bottom: 20px;
}

.text-link {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    color: var(--green);
    font-size: .86rem;
    font-weight: 700;
}

.text-link span {
    transition: transform .25s ease;
}

.text-link:hover span {
    transform: translateX(5px);
}

/* Gallery */

.gallery {
    overflow: hidden;
}

.gallery-grid {
    display: grid;
    grid-template-columns: 1.15fr .85fr 1fr;
    grid-template-rows: 250px 250px;
    gap: 16px;
}

.gallery-item {
    position: relative;
    border-radius: 14px;
    overflow: hidden;
    background: var(--green);
}

.gallery-item:first-child {
    grid-row: span 2;
}

.gallery-item img {
    height: 100%;
    transition: transform .7s ease;
}

.gallery-item:hover img {
    transform: scale(1.07);
}

.gallery-item::after {
    content: "";
    position: absolute;
    inset: 30% 0 0;
    background: linear-gradient(transparent, rgba(10,25,18,.82));
}

.gallery-caption {
    position: absolute;
    z-index: 1;
    bottom: 22px;
    left: 22px;
    right: 22px;
    color: var(--white);
}

.gallery-caption small {
    display: block;
    color: #e3c995;
    margin-bottom: 5px;
    font-size: .72rem;
    letter-spacing: .12em;
    text-transform: uppercase;
}

.gallery-caption h3 {
    font-size: 1.2rem;
}

/* Process */

.process {
    background: var(--green);
    color: var(--white);
}

.process .eyebrow {
    color: #e7d5ad;
}

.process .section-heading h2 {
    color: var(--white);
}

.process .section-heading p {
    color: rgba(255,255,255,.7);
}

.process-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 28px;
}

.process-step {
    padding-top: 25px;
    border-top: 1px solid rgba(255,255,255,.24);
}

.process-step .number {
    color: #d7bd86;
    font-family: 'Manrope', sans-serif;
    font-size: 2.6rem;
    font-weight: 700;
    margin-bottom: 24px;
}

.process-step h3 {
    font-size: 1.15rem;
    margin-bottom: 13px;
}

.process-step p {
    color: rgba(255,255,255,.7);
    font-size: .91rem;
}

/* Contact */

.contact {
    background: #eae9df;
}

.contact-grid {
    display: grid;
    grid-template-columns: .85fr 1.15fr;
    gap: 75px;
    align-items: start;
}

.contact-copy h2 {
    color: var(--green);
    font-size: clamp(2.4rem, 5vw, 4rem);
    margin-bottom: 22px;
}

.contact-copy > p {
    color: var(--muted);
    margin-bottom: 32px;
}

.contact-detail {
    display: flex;
    gap: 15px;
    align-items: flex-start;
    margin-bottom: 24px;
}

.contact-icon {
    width: 46px;
    height: 46px;
    flex-shrink: 0;
    display: grid;
    place-items: center;
    border: 1px solid rgba(20,44,34,.17);
    border-radius: 12px;
    color: var(--green);
    font-size: 1.2rem;
}

.contact-detail small {
    display: block;
    color: var(--muted);
    margin-bottom: 3px;
}

.contact-detail strong {
    color: var(--green);
    overflow-wrap: anywhere;
}

.contact-form {
    padding: 35px;
    border-radius: var(--radius);
    background: var(--white);
    box-shadow: var(--shadow);
}

.contact-form h3 {
    font-size: 1.65rem;
    color: var(--green);
    margin-bottom: 25px;
}

.form-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 18px;
}

.form-group {
    display: flex;
    flex-direction: column;
    gap: 7px;
    margin-bottom: 18px;
}

.form-group.full {
    grid-column: 1 / -1;
}

.form-group label {
    color: var(--green);
    font-size: .83rem;
    font-weight: 700;
}

.form-group input,
.form-group select,
.form-group textarea {
    width: 100%;
    padding: 13px 14px;
    background: #fafaf7;
    border: 1px solid #dedfd6;
    border-radius: 7px;
    outline: none;
    color: var(--text);
}

.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus {
    border-color: var(--green-light);
    box-shadow: 0 0 0 3px rgba(36,71,55,.09);
}

.form-group textarea {
    min-height: 130px;
    resize: vertical;
}

.form-note {
    color: var(--muted);
    font-size: .78rem;
    margin-top: 15px;
}

/* Footer */

.footer {
    padding: 35px 0;
    background: #0e2119;
    color: rgba(255,255,255,.75);
}

.footer-inner {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 25px;
    flex-wrap: wrap;
}

.footer .logo {
    color: var(--white);
}

.footer .logo small {
    color: rgba(255,255,255,.6);
}

.footer-links {
    display: flex;
    gap: 22px;
    flex-wrap: wrap;
    font-size: .82rem;
}

.footer-links a:hover {
    color: #e3c995;
}

.copyright {
    margin-top: 25px;
    padding-top: 20px;
    border-top: 1px solid rgba(255,255,255,.13);
    font-size: .76rem;
    color: rgba(255,255,255,.5);
}

/* Scroll animations */

.reveal {
    opacity: 0;
    transform: translateY(35px);
    transition: opacity .75s ease, transform .75s ease;
}

.reveal.visible {
    opacity: 1;
    transform: translateY(0);
}

.reveal-left {
    opacity: 0;
    transform: translateX(-35px);
    transition: opacity .75s ease, transform .75s ease;
}

.reveal-left.visible {
    opacity: 1;
    transform: translateX(0);
}

.reveal-right {
    opacity: 0;
    transform: translateX(35px);
    transition: opacity .75s ease, transform .75s ease;
}

.reveal-right.visible {
    opacity: 1;
    transform: translateX(0);
}

@keyframes heroZoom {
    from { transform: scale(1); }
    to { transform: scale(1.07); }
}

@keyframes lineMove {
    0%, 100% { transform: scaleY(.7); transform-origin: top; }
    50% { transform: scaleY(1); transform-origin: top; }
}

/* Responsive */

@media (max-width: 950px) {
    .nav-links {
        gap: 16px;
        font-size: .8rem;
    }

    .nav-links .button {
        padding: 12px 15px;
    }

    .intro-grid,
    .contact-grid {
        gap: 40px;
    }

    .services-grid {
        grid-template-columns: repeat(2, 1fr);
    }

    .process-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (max-width: 720px) {
    .nav-inner {
        min-height: 72px;
    }

    .menu-toggle {
        display: block;
    }

    .nav-links {
        position: absolute;
        top: 72px;
        left: 0;
        right: 0;
        padding: 22px 5% 28px;
        display: none;
        align-items: stretch;
        flex-direction: column;
        gap: 19px;
        background: var(--cream);
        border-bottom: 1px solid var(--border);
    }

    .nav-links.open {
        display: flex;
    }

    .nav-links a {
        font-size: .95rem;
    }

    .nav-links .button {
        align-self: flex-start;
    }

    .hero {
        min-height: 760px;
        min-height: 88svh;
        padding: 130px 0 80px;
    }

    .hero::after {
        background: linear-gradient(
            90deg,
            rgba(10,28,20,.91),
            rgba(10,28,20,.58)
        );
    }

    .hero h1 {
        font-size: clamp(2.65rem, 12vw, 4.5rem);
    }

    .hero-note {
        gap: 12px;
        flex-direction: column;
    }

    .scroll-cue {
        display: none;
    }

    .section {
        padding: 75px 0;
    }

    .intro-grid,
    .contact-grid {
        grid-template-columns: 1fr;
    }

    .intro-image {
        height: 350px;
    }

    .image-caption {
        right: 10px;
        bottom: 15px;
    }

    .services-grid {
        grid-template-columns: 1fr;
    }

    .service-card img {
        height: 245px;
    }

    .gallery-grid {
        grid-template-columns: 1fr 1fr;
        grid-template-rows: 260px 200px 200px;
    }

    .gallery-item:first-child {
        grid-column: 1 / -1;
        grid-row: auto;
    }

    .process-grid {
        grid-template-columns: 1fr;
        gap: 35px;
    }

    .contact-form {
        padding: 24px;
    }

    .form-grid {
        grid-template-columns: 1fr;
        gap: 0;
    }

    .footer-inner {
        align-items: flex-start;
        flex-direction: column;
    }
}

@media (prefers-reduced-motion: reduce) {
    html {
        scroll-behavior: auto;
    }

    *, *::before, *::after {
        animation-duration: .01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: .01ms !important;
    }

    .reveal,
    .reveal-left,
    .reveal-right {
        opacity: 1;
        transform: none;
    }
}
</style>
</head>

<body>

<header class="navbar">
    <div class="container nav-inner">

        <a class="logo" href="#start" aria-label="Zur Startseite">
            <span class="logo-mark">D.H.</span>
            <span>
                Hausmeisterservice
                <small>Gartenlandschaftsservice</small>
            </span>
        </a>

        <button class="menu-toggle"
                id="menuToggle"
                aria-label="Menü öffnen"
                aria-expanded="false">
            ☰
        </button>

        <nav class="nav-links" id="navLinks">
            <a href="#start">Startseite</a>
            <a href="#leistungen">Leistungen</a>
            <a href="#projekte">Einblicke</a>
            <a href="#ablauf">Ablauf</a>
            <a href="#kontakt" class="button">Kontakt aufnehmen ↗️</a>
        </nav>

    </div>
</header>


<main>

<!-- HERO -->

<section class="hero" id="start">

    <img
        class="hero-image"
        src="https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=2200&q=85"
        alt="Grüner Garten mit gepflegten Pflanzen"
        fetchpriority="high"
    >

    <div class="container hero-content">

        <div class="eyebrow">
            Hausmeisterservice & Gartenpflege
        </div>

        <h1>
            Ihr Zuhause.<br>
            Ihr Außenbereich.<br>
            <span>Unser Einsatz.</span>
        </h1>

        <p>
            Von der regelmäßigen Gartenpflege bis zur Reinigung
            von Fenstern und Außenflächen: Wir kümmern uns um
            die Arbeiten rund um Haus und Grundstück.
        </p>

        <div class="hero-actions">
            <a href="#leistungen" class="button button-light">
                Unsere Leistungen entdecken ↘️
            </a>

            <a href="#kontakt" class="button button-outline"
               style="border-color:rgba(255,255,255,.55);color:white;">
                Anfrage stellen
            </a>
        </div>

        <div class="hero-note">
            <span>Hausmeisterservice</span>
            <span>Garten- und Landschaftspflege</span>
            <span>Reinigungsarbeiten</span>
        </div>

    </div>

    <div class="scroll-cue">Weiter entdecken</div>

</section>


<!-- INTRO -->

<section class="section">
    <div class="container intro-grid">

        <div class="intro-image-wrap reveal-left">

            <img
                class="intro-image"
                src="https://images.unsplash.com/photo-1600566753086-00f18fb6b3ea?auto=format&fit=crop&w=1100&q=85"
                alt="Gepflegter Außenbereich an einem modernen Haus"
                loading="lazy"
            >

            <div class="image-caption">
                Pflege und Reinigung rund um Ihre Immobilie.
            </div>

        </div>

        <div class="intro-copy reveal-right">

            <div class="eyebrow">Über unsere Arbeit</div>

            <h2>
                Ein gepflegter Eindruck beginnt draußen.
            </h2>

            <p>
                Ein sauberer Außenbereich und ein gepflegter Garten
                machen einen Unterschied. Wir unterstützen Sie bei
                den Arbeiten, die rund um Haus und Grundstück anfallen.
            </p>

            <p>
                Ob regelmäßige Pflege oder ein einzelner Auftrag:
                Gemeinsam besprechen wir, was gemacht werden soll,
                und stimmen die Arbeiten auf Ihr Vorhaben ab.
            </p>

            <a href="#kontakt" class="button">
                Besprechen wir Ihr Vorhaben ↗️
            </a>

        </div>

    </div>
</section>


<!-- SERVICES -->

<section class="section services" id="leistungen">

    <div class="container">

        <div class="section-heading reveal">
            <div class="eyebrow">Unsere Leistungen</div>

            <h2>
                Was rund um Ihr Haus<br>
                erledigt werden kann.
            </h2>

            <p>
                Entdecken Sie unsere Leistungen für Haus, Garten
                und Außenflächen. Teilen Sie uns mit, wobei Sie
                Unterstützung benötigen.
            </p>
        </div>


        <div class="services-grid">

            <article class="service-card reveal">
                <div class="service-image">
                    <img
                        src="https://images.unsplash.com/photo-1599685315640-9ec1f9a6f6d5?auto=format&fit=crop&w=900&q=80"
                        alt="Garten mit gepflegtem Rasen"
                        loading="lazy"
                    >
                </div>

                <div class="service-body">
                    <span class="service-number">01 / GARTEN</span>

                    <h3>Garten- und Landschaftspflege</h3>

                    <p>
                        Rasenpflege, Hecken schneiden, Unkraut entfernen
                        und Grünflächen in Ordnung halten.
                    </p>

                    <a class="text-link" href="#kontakt">
                        Leistung anfragen <span>→</span>
                    </a>
                </div>
            </article>


            <article class="service-card reveal">
                <div class="service-image">
                    <img
                        src="https://images.unsplash.com/photo-1558618666-fcd25c85cd64?auto=format&fit=crop&w=900&q=80"
                        alt="Außenbereich eines gepflegten Hauses"
                        loading="lazy"
                    >
                </div>

                <div class="service-body">
                    <span class="service-number">02 / IMMOBILIE</span>

                    <h3>Hausmeisterservice</h3>

                    <p>
                        Unterstützung bei vereinbarten Pflege- und
                        Kontrollarbeiten rund um Ihre Immobilie.
                    </p>

                    <a class="text-link" href="#kontakt">
                        Leistung anfragen <span>→</span>
                    </a>
                </div>
            </article>


            <article class="service-card reveal">
                <div class="service-image">
                    <img
                        src="https://images.unsplash.com/photo-1558618047-3c8c76ca7d13?auto=format&fit=crop&w=900&q=80"
                        alt="Gepflegter Weg vor einem Haus"
                        loading="lazy"
                    >
                </div>

                <div class="service-body">
                    <span class="service-number">03 / WINTER</span>

                    <h3>Winterdienst</h3>

                    <p>
                        Vereinbarte Räum- und Streuarbeiten für Wege,
                        Eingänge und weitere Außenflächen.
                    </p>

                    <a class="text-link" href="#kontakt">
                        Leistung anfragen <span>→</span>
                    </a>
                </div>
            </article>


            <article class="service-card reveal">
                <div class="service-image">
                    <img
                        src="https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=900&q=80"
                        alt="Helle Fensterfront in einem modernen Gebäude"
                        loading="lazy"
                    >
                </div>

                <div class="service-body">
                    <span class="service-number">04 / FENSTER</span>

                    <h3>Fensterreinigung</h3>

                    <p>
                        Reinigung von Glasscheiben und vereinbarten
                        Fensterrahmen für einen gepflegten Eindruck.
                    </p>

                    <a class="text-link" href="#kontakt">
                        Leistung anfragen <span>→</span>
                    </a>
                </div>
            </article>


            <article class="service-card reveal">
                <div class="service-image">
                    <img
                        src="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=900&q=80"
                        alt="Moderne Hausfassade mit großen Fenstern"
                        loading="lazy"
                    >
                </div>

                <div class="service-body">
                    <span class="service-number">05 / FASSADE</span>

                    <h3>Fassadenreinigung</h3>

                    <p>
                        Reinigung geeigneter Außenflächen nach
                        vorheriger Prüfung von Material und Zustand.
                    </p>

                    <a class="text-link" href="#kontakt">
                        Leistung anfragen <span>→</span>
                    </a>
                </div>
            </article>


            <article class="service-card reveal">
                <div class="service-image">
                    <img
                        src="https://images.unsplash.com/photo-1590253230532-a67f6bc61f36?auto=format&fit=crop&w=900&q=80"
                        alt="Gepflasterte Einfahrt vor einem Haus"
                        loading="lazy"
                    >
                </div>

                <div class="service-body">
                    <span class="service-number">06 / AUSSENFLÄCHEN</span>

                    <h3>Stein- und Einfahrtsreinigung</h3>

                    <p>
                        Reinigung geeigneter Pflastersteine, Terrassen,
                        Wege und Einfahrten.
                    </p>

                    <a class="text-link" href="#kontakt">
                        Leistung anfragen <span>→</span>
                    </a>
                </div>
            </article>

        </div>

    </div>
</section>


<!-- PROJECT GALLERY -->

<section class="section gallery" id="projekte">

    <div class="container">

        <div class="section-heading reveal">
            <div class="eyebrow">Einblicke</div>

            <h2>
                Gepflegte Außenbereiche.<br>
                Klare Eindrücke.
            </h2>

            <p>
                Hier bekommen Sie einen Eindruck davon, wie
                gepflegte Gärten, saubere Wege und ordentliche
                Außenbereiche aussehen können.
            </p>
        </div>


        <div class="gallery-grid">

            <article class="gallery-item reveal">
                <img
                    src="https://images.unsplash.com/photo-1600047509807-ba8f99d2cdde?auto=format&fit=crop&w=1200&q=85"
                    alt="Garten und Außenbereich an einem Wohnhaus"
                    loading="lazy"
                >

                <div class="gallery-caption">
                    <small>Gartenpflege</small>
                    <h3>Grünflächen in gepflegtem Zustand</h3>
                </div>
            </article>


            <article class="gallery-item reveal">
                <img
                    src="https://images.unsplash.com/photo-1598902108854-10e335adac99?auto=format&fit=crop&w=900&q=80"
                    alt="Gepflegte Terrasse"
                    loading="lazy"
                >

                <div class="gallery-caption">
                    <small>Außenbereich</small>
                    <h3>Terrassen und Wege</h3>
                </div>
            </article>


            <article class="gallery-item reveal">
                <img
                    src="https://images.unsplash.com/photo-1600566753190-17f0baa2a6c3?auto=format&fit=crop&w=900&q=80"
                    alt="Moderner Wohnbereich mit großen Fenstern"
                    loading="lazy"
                >

                <div class="gallery-caption">
                    <small>Fenster</small>
                    <h3>Klare Glasflächen</h3>
                </div>
            </article>


            <article class="gallery-item reveal">
                <img
                    src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=900&q=80"
                    alt="Haus mit gepflegtem Vorgarten"
                    loading="lazy"
                >

                <div class="gallery-caption">
                    <small>Immobilienpflege</small>
                    <h3>Ein gepflegter Gesamteindruck</h3>
                </div>
            </article>


            <article class="gallery-item reveal">
                <img
                    src="https://images.unsplash.com/photo-1600607687920-4e2a09cf159d?auto=format&fit=crop&w=900&q=80"
                    alt="Gepflegter Außenbereich eines modernen Hauses"
                    loading="lazy"
                >

                <div class="gallery-caption">
                    <small>Außenflächen</small>
                    <h3>Ordentliche Wege und Flächen</h3>
                </div>
            </article>

        </div>

    </div>
</section>


<!-- PROCESS -->

<section class="section process" id="ablauf">

    <div class="container">

        <div class="section-heading reveal">
            <div class="eyebrow">So funktioniert es</div>

            <h2>
                Von der ersten Anfrage<br>
                bis zur erledigten Arbeit.
            </h2>

            <p>
                Ein klarer Ablauf hilft dabei, Ihr Vorhaben
                unkompliziert zu besprechen und zu planen.
            </p>
        </div>


        <div class="process-grid">

            <article class="process-step reveal">
                <div class="number">01</div>
                <h3>Kontakt aufnehmen</h3>
                <p>
                    Teilen Sie uns mit, welche Arbeiten anstehen
                    und wo Sie Unterstützung benötigen.
                </p>
            </article>

            <article class="process-step reveal">
                <div class="number">02</div>
                <h3>Vorhaben besprechen</h3>
                <p>
                    Wir klären gemeinsam die gewünschten Leistungen
                    und die wichtigsten Einzelheiten.
                </p>
            </article>

            <article class="process-step reveal">
                <div class="number">03</div>
                <h3>Angebot abstimmen</h3>
                <p>
                    Umfang, Termin und Kosten werden vor Beginn
                    der vereinbarten Arbeiten besprochen.
                </p>
            </article>

            <article class="process-step reveal">
                <div class="number">04</div>
                <h3>Arbeiten durchführen</h3>
                <p>
                    Nach der Abstimmung werden die vereinbarten
                    Arbeiten entsprechend dem Auftrag erledigt.
                </p>
            </article>

        </div>

    </div>
</section>


<!-- CONTACT -->

<section class="section contact" id="kontakt">

    <div class="container contact-grid">

        <div class="contact-copy reveal-left">

            <div class="eyebrow">Kontakt</div>

            <h2>
                Was können wir für Sie erledigen?
            </h2>

            <p>
                Beschreiben Sie kurz Ihr Vorhaben. Ob Gartenpflege,
                Fensterreinigung oder Hausmeisterservice – wir
                besprechen mit Ihnen die nächsten Schritte.
            </p>


            <div class="contact-detail">
                <div class="contact-icon">☎</div>

                <div>
                    <small>Telefon</small>

                    <strong>
                        <a href="tel:+491793974794">
                            0179 3974794
                        </a>
                    </strong>
                </div>
            </div>


            <div class="contact-detail">
                <div class="contact-icon">✉</div>

                <div>
                    <small>E-Mail</small>

                    <strong>
                        <a href="mailto:d.h_kontakt@icloud.com">
                            d.h_kontakt@icloud.com
                        </a>
                    </strong>
                </div>
            </div>

            <p style="font-size:.86rem;">
                Sie können uns auch direkt per E-Mail kontaktieren.
            </p>

        </div>


        <div class="contact-form reveal-right">

            <h3>Ihre Anfrage</h3>

            <form id="contactForm">

                <div class="form-grid">

                    <div class="form-group">
                        <label for="name">Ihr Name *</label>

                        <input
                            type="text"
                            id="name"
                            name="name"
                            placeholder="Vor- und Nachname"
                            autocomplete="name"
                            required
                        >
                    </div>


                    <div class="form-group">
                        <label for="phone">Telefon</label>

                        <input
                            type="tel"
                            id="phone"
                            name="phone"
                            placeholder="Ihre Telefonnummer"
                            autocomplete="tel"
                        >
                    </div>


                    <div class="form-group full">
                        <label for="email">Ihre E-Mail-Adresse *</label>

                        <input
                            type="email"
                            id="email"
                            name="email"
                            placeholder="name@beispiel.de"
                            autocomplete="email"
                            required
                        >
                    </div>


                    <div class="form-group full">
                        <label for="service">Gewünschte Leistung *</label>

                        <select id="service" name="service" required>
                            <option value="">Bitte auswählen</option>
                            <option>Hausmeisterservice</option>
                            <option>Garten- und Landschaftspflege</option>
                            <option>Winterdienst</option>
                            <option>Fensterreinigung</option>
                            <option>Fassadenreinigung</option>
                            <option>Stein- und Einfahrtsreinigung</option>
                            <option>Sonstige Anfrage</option>
                        </select>
                    </div>


                    <div class="form-group full">
                        <label for="message">Ihre Nachricht *</label>

                        <textarea
                            id="message"
                            name="message"
                            placeholder="Beschreiben Sie kurz Ihr Vorhaben ..."
                            required
                        ></textarea>
                    </div>

                </div>


                <button type="submit" class="button">
                    Anfrage vorbereiten ↗️
                </button>

                <p class="form-note">
                    Beim Absenden öffnet sich Ihr E-Mail-Programm
                    mit den eingetragenen Angaben. Die Nachricht
                    wird nicht automatisch versendet.
                </p>

            </form>

        </div>

    </div>
</section>

</main>


<!-- FOOTER -->

<footer class="footer">

    <div class="container">

        <div class="footer-inner">

            <a class="logo" href="#start">
                <span class="logo-mark">D.H.</span>

                <span>
                    D. H. Hausmeister
                    <small>Gartenlandschaftsservice</small>
                </span>
            </a>


            <div class="footer-links">
                <a href="#leistungen">Leistungen</a>
                <a href="#projekte">Einblicke</a>
                <a href="#kontakt">Kontakt</a>

                <!-- Später mit den echten Seiten verknüpfen -->
                <a href="impressum.html">Impressum</a>
                <a href="datenschutz.html">Datenschutz</a>
            </div>

        </div>


        <div class="copyright">
            ©️ <span id="year"></span>
            D. H. Hausmeister Gartenlandschaftsservice.
            Alle Rechte vorbehalten.
        </div>

    </div>

</footer>


<script>
/* Aktuelles Jahr */

document.getElementById("year").textContent =
    new Date().getFullYear();


/* Mobiles Menü */

const menuToggle = document.getElementById("menuToggle");
const navLinks = document.getElementById("navLinks");

menuToggle.addEventListener("click", () => {
    const isOpen = navLinks.classList.toggle("open");

    menuToggle.setAttribute("aria-expanded", isOpen);
    menuToggle.setAttribute(
        "aria-label",
        isOpen ? "Menü schließen" : "Menü öffnen"
    );

    menuToggle.textContent = isOpen ? "×" : "☰";
});


/* Menü nach Auswahl schließen */

navLinks.querySelectorAll("a").forEach(link => {
    link.addEventListener("click", () => {
        navLinks.classList.remove("open");
        menuToggle.setAttribute("aria-expanded", "false");
        menuToggle.setAttribute("aria-label", "Menü öffnen");
        menuToggle.textContent = "☰";
    });
});


/* Animationen beim Scrollen
   Elemente erscheinen beim Hineinscrollen.
   Beim Verlassen des sichtbaren Bereichs
   werden sie wieder ausgeblendet. */

const revealElements = document.querySelectorAll(
    ".reveal, .reveal-left, .reveal-right"
);

const prefersReducedMotion = window.matchMedia(
    "(prefers-reduced-motion: reduce)"
).matches;

if (prefersReducedMotion) {

    revealElements.forEach(element => {
        element.classList.add("visible");
    });

} else {

    const observer = new IntersectionObserver(
        entries => {

            entries.forEach(entry => {

                if (entry.isIntersecting) {
                    entry.target.classList.add("visible");
                } else {
                    entry.target.classList.remove("visible");
                }

            });

        },
        {
            threshold: 0.12,
            rootMargin: "0px 0px -35px 0px"
        }
    );

    revealElements.forEach(element => {
        observer.observe(element);
    });

}


/* Kontaktformular:
   Öffnet das E-Mail-Programm mit den Formulardaten.
   Es findet kein automatischer Versand statt. */

document.getElementById("contactForm").addEventListener(
    "submit",
    function(event) {

        event.preventDefault();

        if (!this.reportValidity()) {
            return;
        }

        const formData = new FormData(this);

        const name = formData.get("name");
        const phone = formData.get("phone") || "Nicht angegeben";
        const email = formData.get("email");
        const service = formData.get("service");
        const message = formData.get("message");

        const subject = encodeURIComponent(
            "Anfrage über die Webseite: " + service
        );

        const body = encodeURIComponent(
            "Neue Anfrage über die Webseite\n\n" +
            "Name: " + name + "\n" +
            "Telefon: " + phone + "\n" +
            "E-Mail: " + email + "\n" +
            "Gewünschte Leistung: " + service + "\n\n" +
            "Nachricht:\n" + message
        );

        window.location.href =
            "mailto:d.h_kontakt@icloud.com" +
            "?subject=" + subject +
            "&body=" + body;

    }
);
</script>

</body>
</html>
