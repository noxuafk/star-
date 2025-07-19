<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta property="og:title" content="Glide Client">
    <meta property="og:description" content="The website for Glide Client">
    <meta property="og:image" content="/assets/embed.png">
    <meta property="og:url" content="https://glideclient.github.io">
    <meta name='twitter:site' content='glideclient.github.io' />
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Glide Client">
    <meta name="twitter:description" content="The website for Glide Client">
    <meta name="twitter:image" content="/assets/embed.png">
    <meta name="description" content="The website for Glide Client">
    <meta name="keywords" content="minecraft, glide client, soar client, SoarClient, GlideClient, 1.8.9, modern website">
    <meta name="author" content="Glide Client Team">
    <meta name="theme-color" content="#6603fc">
    <meta name="google-site-verification" content="r28lqHeGOGV7C6jk6VrlYJkrt1-w8X4VbjLqQzyf6ME" />
    <title>Glide Client</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" type="image/svg+xml" href="/assets/logo.svg">
</head>

<body>
    <div class="loader-wrapper">
        <div class="loader">
            <img src="/assets/logo.svg" alt="Glide Client Logo">
        </div>
    </div>

    <header class="header">
        <nav class="navbar">
            <div class="logo">
                <a href="/">
                    <img src="/assets/logo.svg" alt="Glide Client Logo">
                </a>
            </div>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
            <ul class="nav-links">
                <li><a href="#features">Features</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="download.html">Download</a></li>
            </ul>
        </nav>
    </header>

    <main class="main">
        <section class="hero">
            <h1>Glide Client</h1>
            <p>An updated version of Soar Client</p>
            <div class="button-group">
                <a href="#features" class="cta-button">Explore Features</a>
                <a href="download.html" class="cta-button download-button">
                    <!-- Inline the SVG icon -->
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"></path>
                        <polyline points="7 10 12 15 17 10"></polyline>
                        <line x1="12" y1="15" x2="12" y2="3"></line>
                    </svg>
                    Download Now
                </a>
            </div>
            <div class="ico animated">
                <div class="circle circle-top"></div>
                <div class="circle circle-main"></div>
                <div class="circle circle-bottom"></div>
                <svg class="svg" version="1.1" xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 612 612"
                    style="enable-background:new 0 0 612 612;" xml:space="preserve">
                    <defs>
                        <clipPath id="cut-off-arrow">
                            <circle cx="306" cy="306" r="287" />
                        </clipPath>
                        <filter id="goo">
                            <feGaussianBlur in="SourceGraphic" stdDeviation="10" result="blur" />
                            <feColorMatrix in="blur" mode="matrix" values="1 0 0 0 0  0 1 0 0 0  0 0 1 0 0  0 0 0 18 -7"
                                result="goo" />
                            <feBlend in="SourceGraphic" in2="goo" />
                        </filter>
                    </defs>
                    <path class="st-arrow" d="M317.5,487.6c0.3-0.3,0.4-0.7,0.7-1.1l112.6-112.6c6.3-6.3,6.3-16.5,0-22.7c-6.3-6.3-16.5-6.3-22.7,0
                                l-86,86V136.1c0-8.9-7.3-16.2-16.2-16.2c-8.9,0-16.2,7.3-16.2,16.2v301.1l-86-86c-6.3-6.3-16.5-6.3-22.7,0
                                c-6.3,6.3-6.3,16.5,0,22.7l112.7,112.7c0.3,0.3,0.4,0.7,0.7,1c0.5,0.5,1.2,0.5,1.7,0.9c1.7,1.4,3.6,2.3,5.6,2.9
                                c0.8,0.2,1.5,0.4,2.3,0.4C308.8,492.6,313.8,491.3,317.5,487.6z" />
                </svg>
            </div>
        </section>

        <section id="features" class="features">
            <h2>Features</h2>
            <div class="feature-cards">
                <div class="card">
                    <img src="/assets/desktop.svg" alt="Computer image">
                    <h3>Cross platform</h3>
                    <p>We support Linux and Windows and we will work hard to continue that fact!</p>
                </div>
                <div class="card">
                    <img src="/assets/increase.svg" alt="chart with increase image">
                    <h3>Quality of Life</h3>
                    <p>Glide Client offers numerous quality of life enhancements and bug fixes compared to Soar Client. We are commited to continue adding more as time passes!</p>
                </div>
                <div class="card">
                    <img src="/assets/branch.svg" alt="A github branch">
                    <h3>FOSS</h3>
                    <p>At Glide Client, we're committed to openness and collaboration. Whether you make a pull request, report an issue, or fork our code, we will welcome it all!</p>
                </div>
            </div>
        </section>

        <section id="about" class="about">
            <h2>What is Glide Client?</h2>
            <p>Glide Client is a fork of Soar that aims to fix many of the issues people faced with Soar Client.</p>
            <p>We want to be one of the most unique 1.8.9 minecraft pvp clients through having a unique user experiences that you cant find elsewhere.</p>
            <p>GlideClient was started by two of the Mods at Soar Client though it was originally planned as a Soar Client update we decided to seperate it after soar went open-source so we could add features that would have not fit the soar client look.</p>
            <p>We dont want to be competiton with Soar Client as we fully support EldoDebug, therefore when Soar Client 8 releases we will discontinue glide</p>
        </section>
    </main>

    <footer class="footer">
        <div class="footer-content">
            <p>Website by Glide Client Team</p>
            <p>GlideClient is not endorsed by <a href="https://github.com/Soar-Client/Legacy-SoarClient">Soar Client</a> nor <a href="https://github.com/EldoDebug">EldoDebug</a></p>
            <p>Follow us: <a href="https://www.youtube.com/@glideclient" target="_blank">Youtube</a> | <a
                    href="https://github.com/GlideClient/" target="_blank">GitHub</a></p>
        </div>
    </footer>

    <script>
        // Loader and hamburger menu handling
        window.addEventListener('load', () => {
            const loaderWrapper = document.querySelector('.loader-wrapper');
            loaderWrapper.classList.add('fade-out');
        });

        const hamburger = document.querySelector('.hamburger');
        const navLinks = document.querySelector('.nav-links');
        
        hamburger.addEventListener('click', () => {
            hamburger.classList.toggle('active');
            navLinks.classList.toggle('active');
        });
        
        document.querySelectorAll('.nav-links a').forEach(link => {
            link.addEventListener('click', () => {
                hamburger.classList.remove('active');
                navLinks.classList.remove('active');
            });
        });
    </script>

    <!-- Separate script for card hover effects -->
    <script>
        // Use requestAnimationFrame for smooth hover animations
        document.querySelectorAll('.card').forEach(card => {
            let rafId;
            
            card.addEventListener('mousemove', (e) => {
                // Cancel any pending animation frame
                if (rafId) {
                    cancelAnimationFrame(rafId);
                }
                
                // Schedule the update for the next frame
                rafId = requestAnimationFrame(() => {
                    const rect = card.getBoundingClientRect();
                    const x = e.clientX - rect.left;
                    const y = e.clientY - rect.top;
                    
                    card.style.setProperty('--mouse-x', `${x}px`);
                    card.style.setProperty('--mouse-y', `${y}px`);
                    
                    rafId = null;
                });
            });

            // Clean up when mouse leaves
            card.addEventListener('mouseleave', () => {
                if (rafId) {
                    cancelAnimationFrame(rafId);
                    rafId = null;
                }
            });
        });
    </script>

    <!-- Separate script for card reveal animations -->
    <script>
        // Initialize observer after DOM is fully loaded
        document.addEventListener('DOMContentLoaded', () => {
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        // Add small stagger delay based on card index
                        const card = entry.target;
                        const index = Array.from(card.parentNode.children).indexOf(card);
                        card.style.transitionDelay = `${index * 100}ms`;
                        card.classList.add('visible');
                    }
                });
            }, {
                threshold: 0.1,
                rootMargin: '0px'
            });

            document.querySelectorAll('.card').forEach(card => {
                observer.observe(card);
            });
        });
    </script>
</body>

</html>
