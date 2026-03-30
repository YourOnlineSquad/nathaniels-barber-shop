---
layout: default
title: Frequently Asked Questions | Nathaniel’s Barber Shop in Sioux Falls SD
---

<style>
  /* FAQ Page Styles */
  .faq-hero {
    padding: 100px 20px 40px;
    text-align: center;
    background: linear-gradient(180deg, #0a0a0a 0%, var(--bg-dark, #121212) 100%);
    animation: fadeIn 1s ease-in-out;
  }
  .faq-hero h1 {
    font-size: clamp(2.2rem, 4vw, 3.5rem);
    color: var(--accent-gold, #D4AF37);
    margin-bottom: 20px;
    letter-spacing: 1px;
    font-weight: 700;
  }
  .faq-hero p {
    font-size: 1.2rem;
    color: var(--text-muted, #a0a0a0);
    max-width: 600px;
    margin: 0 auto 40px;
    line-height: 1.6;
  }
  
  /* Accordion Styles */
  .faq-container {
    max-width: 800px;
    margin: 0 auto 80px;
    padding: 0 20px;
    animation: fadeUp 1s ease-out forwards;
    opacity: 0;
    transform: translateY(20px);
  }
  .faq-item {
    background: var(--bg-card, #1e1e1e);
    border: 1px solid rgba(255,255,255,0.05);
    border-radius: 8px;
    margin-bottom: 15px;
    overflow: hidden;
    transition: border-color 0.3s ease, box-shadow 0.3s ease;
  }
  .faq-item:hover {
    border-color: rgba(212, 175, 55, 0.3);
    box-shadow: 0 5px 15px rgba(0,0,0,0.5);
  }
  .faq-question {
    width: 100%;
    text-align: left;
    padding: 25px 30px;
    background: none;
    border: none;
    color: var(--text-light, #f5f5f5);
    font-size: 1.2rem;
    font-weight: 600;
    cursor: pointer;
    display: flex;
    justify-content: space-between;
    align-items: center;
    transition: color 0.3s ease;
  }
  .faq-question:hover, .faq-question.active {
    color: var(--accent-gold, #D4AF37);
  }
  .faq-icon {
    font-size: 1.5rem;
    transition: transform 0.3s ease;
    color: var(--accent-gold, #D4AF37);
  }
  .faq-question.active .faq-icon {
    transform: rotate(45deg);
  }
  .faq-answer {
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.4s ease-in-out;
    background: rgba(0,0,0,0.2);
  }
  .faq-answer-inner {
    padding: 0 30px 25px;
    color: var(--text-muted, #a0a0a0);
    line-height: 1.7;
    font-size: 1.05rem;
  }
  .faq-answer-inner a {
    color: var(--accent-gold, #D4AF37);
    text-decoration: none;
    border-bottom: 1px solid transparent;
    transition: border-color 0.3s ease;
  }
  .faq-answer-inner a:hover {
    border-color: var(--accent-gold, #D4AF37);
  }

  /* CTA Section */
  .faq-cta {
    text-align: center;
    padding: 40px 20px 80px;
  }
  .btn-gold {
    background-color: var(--accent-gold, #D4AF37);
    color: #121212;
    padding: 16px 36px;
    text-decoration: none;
    font-weight: 700;
    border-radius: 4px;
    text-transform: uppercase;
    letter-spacing: 1.5px;
    transition: all 0.3s ease;
    display: inline-block;
  }
  .btn-gold:hover {
    background-color: #b5952f;
    transform: translateY(-3px);
    box-shadow: 0 6px 20px rgba(212, 175, 55, 0.4);
  }

  @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
  }
  @keyframes fadeUp {
    to { opacity: 1; transform: translateY(0); }
  }
</style>

<div class="faq-hero">
  <h1>Frequently Asked Questions</h1>
  <p>Everything you need to know about booking, services, and policies at the premier barber shop in Sioux Falls SD.</p>
</div>

<div class="faq-container">
  
  <div class="faq-item">
    <button class="faq-question">
      Do I need an appointment?
      <span class="faq-icon">+</span>
    </button>
    <div class="faq-answer">
      <div class="faq-answer-inner">
        Yes. Nathaniel’s Barber Shop operates strictly by appointment. This ensures that every client receives our undivided attention, zero wait times, and the highest level of precision craftsmanship.
      </div>
    </div>
  </div>

  <div class="faq-item">
    <button class="faq-question">
      Do you accept walk ins?
      <span class="faq-icon">+</span>
    </button>
    <div class="faq-answer">
      <div class="faq-answer-inner">
        No, we do not accept walk-ins. To maintain our exclusive environment and respect the schedules of our clientele in Sioux Falls, we require all services to be booked in advance through our <a href="/book/">online booking system</a>.
      </div>
    </div>
  </div>

  <div class="faq-item">
    <button class="faq-question">
      What services do you offer?
      <span class="faq-icon">+</span>
    </button>
    <div class="faq-answer">
      <div class="faq-answer-inner">
        We specialize in premium men's grooming. Our core services include tailored <a href="/services/mens-haircut">Mens Haircuts</a>, precise <a href="/services/beard-trim">Beard Trims</a>, traditional hot towel <a href="/services/shave">Straight Razor Shaves</a>, sharp <a href="/services/line-up">Line Ups</a>, and professional <a href="/services/kids-haircut">Kids Haircuts</a>.
      </div>
    </div>
  </div>

  <div class="faq-item">
    <button class="faq-question">
      How long does a haircut take?
      <span class="faq-icon">+</span>
    </button>
    <div class="faq-answer">
      <div class="faq-answer-inner">
        A standard bespoke haircut typically takes between 45 to 60 minutes. We do not rush our work. The allotted time allows for a thorough consultation, precision cutting, and detailed finishing.
      </div>
    </div>
  </div>

  <div class="faq-item">
    <button class="faq-question">
      What payment methods are accepted?
      <span class="faq-icon">+</span>
    </button>
    <div class="faq-answer">
      <div class="faq-answer-inner">
        We accept all major credit and debit cards (Visa, MasterCard, American Express, Discover), mobile payments including Apple Pay and Google Pay, as well as cash.
      </div>
    </div>
  </div>

</div>

<div class="faq-cta">
  <h2 style="color: var(--text-light, #f5f5f5); margin-bottom: 25px; font-size: 1.8rem;">Still have questions or ready to sit in the chair?</h2>
  <a href="/book/" class="btn-gold">Book Your Appointment</a>
</div>

<script>
  // Lightweight vanilla JS for accordion functionality
  document.addEventListener("DOMContentLoaded", function() {
    const questions = document.querySelectorAll(".faq-question");

    questions.forEach(question => {
      question.addEventListener("click", function() {
        // Close all other open answers
        questions.forEach(q => {
          if (q !== this) {
            q.classList.remove("active");
            q.nextElementSibling.style.maxHeight = null;
          }
        });

        // Toggle the clicked answer
        this.classList.toggle("active");
        const answer = this.nextElementSibling;
        
        if (answer.style.maxHeight) {
          answer.style.maxHeight = null;
        } else {
          answer.style.maxHeight = answer.scrollHeight + "px";
        }
      });
    });
  });
</script>
