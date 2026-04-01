 ---
---

<style>
  /* Booking Page Styles */
  .book-hero {
    padding: 100px 20px 40px;
    text-align: center;
    background: linear-gradient(180deg, #0a0a0a 0%, var(--bg-dark, #121212) 100%);
    animation: fadeIn 1s ease-in-out;
  }
  .book-hero h1 {
    font-size: clamp(2.2rem, 4vw, 3.5rem);
    color: var(--accent-gold, #D4AF37);
    margin-bottom: 20px;
    letter-spacing: 1px;
    font-weight: 700;
  }
  .book-hero p {
    font-size: 1.2rem;
    color: var(--text-muted, #a0a0a0);
    max-width: 600px;
    margin: 0 auto 40px;
    line-height: 1.6;
  }
  
  /* Process Steps */
  .process-container {
    max-width: 900px;
    margin: 0 auto 60px;
    padding: 0 20px;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
  }
  .step-card {
    background: var(--bg-card, #1e1e1e);
    padding: 40px 30px;
    border-radius: 8px;
    text-align: center;
    border: 1px solid rgba(255,255,255,0.05);
    box-shadow: 0 10px 30px rgba(0,0,0,0.3);
  }
  .step-number {
    background: var(--accent-gold, #D4AF37);
    color: #121212;
    width: 40px;
    height: 40px;
    line-height: 40px;
    border-radius: 50%;
    font-size: 1.2rem;
    font-weight: bold;
    margin: 0 auto 20px;
    display: inline-block;
  }
  .step-card h3 {
    color: var(--text-light, #f5f5f5);
    margin-bottom: 15px;
    font-size: 1.3rem;
  }
  .step-card p {
    color: var(--text-muted, #a0a0a0);
    line-height: 1.5;
    font-size: 0.95rem;
  }

  /* Main CTA Section */
  .cta-section {
    text-align: center;
    padding: 40px 20px 100px;
    animation: fadeUp 1s ease-out forwards;
    opacity: 0;
    transform: translateY(20px);
  }
  .btn-massive {
    background-color: var(--accent-gold, #D4AF37);
    color: #121212;
    padding: 24px 50px;
    font-size: 1.5rem;
    text-decoration: none;
    font-weight: 800;
    border-radius: 6px;
    text-transform: uppercase;
    letter-spacing: 2px;
    transition: all 0.3s ease;
    display: inline-block;
    box-shadow: 0 10px 30px rgba(212, 175, 55, 0.3);
  }
  .btn-massive:hover {
    background-color: #b5952f;
    transform: translateY(-5px);
    box-shadow: 0 15px 40px rgba(212, 175, 55, 0.5);
  }
  
  /* Fine Print */
  .policies {
    max-width: 600px;
    margin: 60px auto 0;
    text-align: center;
    color: #777;
    font-size: 0.9rem;
    line-height: 1.6;
    border-top: 1px solid rgba(255,255,255,0.1);
    padding-top: 30px;
  }

  @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
  }
  @keyframes fadeUp {
    to { opacity: 1; transform: translateY(0); }
  }
</style>

<div class="book-hero">
  <h1>Secure Your Appointment</h1>
  <p>Experience the premier barber shop in Sioux Falls SD. We operate strictly by appointment to ensure every client receives our undivided attention and absolute precision.</p>
</div>

<div class="process-container">
  <div class="step-card">
    <div class="step-number">1</div>
    <h3>Select Service</h3>
    <p>Choose from our menu of premium haircuts, beard trims, and straight razor shaves.</p>
  </div>
  <div class="step-card">
    <div class="step-number">2</div>
    <h3>Choose a Time</h3>
    <p>Find a date and time that fits perfectly into your schedule using our live calendar.</p>
  </div>
  <div class="step-card">
    <div class="step-number">3</div>
    <h3>Look Sharp</h3>
    <p>Arrive at our Sioux Falls shop, relax in the chair, and let us handle the rest.</p>
  </div>
</div>

<div class="cta-section">
  <p style="color: var(--text-light, #f5f5f5); margin-bottom: 30px; font-size: 1.2rem;">Booking is fast, secure, and available 24/7 via StyleSeat.</p>
  
  <a href="https://www.styleseat.com/" class="btn-massive" target="_blank" rel="noopener noreferrer">
    Book Now on StyleSeat
  </a>

  <div class="policies">
    <p><strong>Shop Policy:</strong> Please arrive 5 minutes prior to your scheduled time. If you need to cancel or reschedule, we kindly ask for at least 24 hours' notice. No-shows or late cancellations may be subject to a fee.</p>
  </div>
</div>
