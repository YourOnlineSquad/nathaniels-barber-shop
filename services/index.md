---
layout: default
title: Grooming Services | Nathaniel’s Barber Shop in Sioux Falls SD
---

<style>
  /* Local styles for the services grid */
  .services-header {
    text-align: center;
    padding: 100px 20px 60px;
    background: linear-gradient(180deg, #0a0a0a 0%, var(--bg-dark, #121212) 100%);
    animation: fadeIn 1s ease-in-out;
  }
  .services-header h1 {
    font-size: clamp(2.2rem, 4vw, 3.5rem);
    color: var(--accent-gold, #D4AF37);
    margin-bottom: 20px;
    letter-spacing: 1px;
    font-weight: 700;
  }
  .services-header p {
    color: var(--text-muted, #a0a0a0);
    font-size: 1.2rem;
    max-width: 700px;
    margin: 0 auto;
    line-height: 1.6;
  }
  .services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 40px;
    padding: 40px 20px 100px;
    max-width: 1200px;
    margin: 0 auto;
  }
  .service-card {
    background: var(--bg-card, #1e1e1e);
    border: 1px solid rgba(255,255,255,0.05);
    border-radius: 8px;
    padding: 50px 40px;
    text-align: center;
    text-decoration: none;
    transition: all 0.4s ease;
    box-shadow: 0 10px 30px rgba(0,0,0,0.5);
    display: flex;
    flex-direction: column;
    height: 100%;
  }
  .service-card:hover {
    transform: translateY(-8px);
    border-color: rgba(212, 175, 55, 0.4);
    box-shadow: 0 15px 40px rgba(212, 175, 55, 0.15);
  }
  .service-card svg {
    margin: 0 auto 25px;
  }
  .service-card h2 {
    color: var(--text-light, #f5f5f5);
    font-size: 1.8rem;
    margin-bottom: 15px;
  }
  .service-card p {
    color: var(--text-muted, #a0a0a0);
    line-height: 1.6;
    margin-bottom: 30px;
    flex-grow: 1;
  }
  .service-card .learn-more {
    color: var(--accent-gold, #D4AF37);
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 1.5px;
    font-size: 0.9rem;
    transition: color 0.3s ease;
  }
  .service-card:hover .learn-more {
    color: #f5f5f5;
  }
  
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }
</style>

<div class="services-header">
  <h1>Premium Grooming Services in Sioux Falls SD</h1>
  <p>At Nathaniel’s Barber Shop, we offer a curated menu of high-end grooming services designed for the modern gentleman. Explore our offerings below and discover the pinnacle of precision and style.</p>
</div>

<div class="services-grid">
  <a href="/services/mens-haircut" class="service-card">
    <svg width="50" height="50" viewBox="0 0 24 24" fill="none" stroke="#D4AF37" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M20 4L4 20M4 4l16 16M9 9a2 2 0 1 0-4 0 2 2 0 0 0 4 0zm10 10a2 2 0 1 0-4 0 2 2 0 0 0 4 0z"/></svg>
    <h2>Mens Haircut</h2>
    <p>A precision cut tailored specifically to your head shape, hair type, and personal style. Executed with flawless attention to detail.</p>
    <span class="learn-more">View Details &rarr;</span>
  </a>

  <a href="/services/beard-trim" class="service-card">
    <svg width="50" height="50" viewBox="0 0 24 24" fill="none" stroke="#D4AF37" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2v20M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"/></svg>
    <h2>Beard Trim</h2>
    <p>Expert shaping and sculpting to keep your beard looking sharp and well-maintained. Finished with premium conditioning oils.</p>
    <span class="learn-more">View Details &rarr;</span>
  </a>

  <a href="/services/shave" class="service-card">
    <svg width="50" height="50" viewBox="0 0 24 24" fill="none" stroke="#D4AF37" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><rect x="4" y="4" width="16" height="16" rx="2" ry="2"/><line x1="8" y1="12" x2="16" y2="12"/></svg>
    <h2>Straight Razor Shave</h2>
    <p>The ultimate relaxation experience. A traditional hot towel straight razor shave utilizing rich lather for a buttery smooth finish.</p>
    <span class="learn-more">View Details &rarr;</span>
  </a>

  <a href="/services/kids-haircut" class="service-card">
    <svg width="50" height="50" viewBox="0 0 24 24" fill="none" stroke="#D4AF37" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="8" r="5"/><path d="M20 21a8 8 0 1 0-16 0"/></svg>
    <h2>Kids Haircut</h2>
    <p>Quality grooming for the next generation. A patient, precise haircut ensuring the young gentlemen look as sharp as their dads.</p>
    <span class="learn-more">View Details &rarr;</span>
  </a>

  <a href="/services/line-up" class="service-card">
    <svg width="50" height="50" viewBox="0 0 24 24" fill="none" stroke="#D4AF37" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline></svg>
    <h2>Line Up</h2>
    <p>Clean up your edges between full haircuts. Crisp, sharp lines around the hairline and beard to keep you looking fresh and defined.</p>
    <span class="learn-more">View Details &rarr;</span>
  </a>
</div>
