<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ES Editing Services</title>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Poppins', sans-serif; background-color: #000; color: #fff; line-height: 1.6; }

    header { text-align: center; padding: 60px 20px; background-color: #111; }
    header img { width: 150px; margin-bottom: 20px; border-radius: 12px; }
    header h1 { font-size: 48px; letter-spacing: 2px; font-weight: 700; }

    section { padding: 50px 20px; max-width: 1000px; margin: auto; }
    h2 { font-size: 36px; margin-bottom: 20px; text-align: center; font-weight: 600; }
    p { font-size: 18px; margin-bottom: 15px; text-align: center; }

    .pricing { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 30px; }
    .plan { background-color: #111; padding: 20px; border: 2px solid #fff; border-radius: 12px; width: 250px; text-align: center; transition: transform 0.2s, border-color 0.2s; }
    .plan:hover { transform: scale(1.05); border-color: #00ffcc; }
    .plan h3 { font-size: 24px; margin-bottom: 15px; font-weight: 600; }

    .btn { display: inline-block; background: #00ffcc; color: #000; padding: 12px 25px; margin-top: 15px; border-radius: 8px; text-decoration: none; font-weight: bold; transition: background 0.2s; }
    .btn:hover { background: #00ddaa; }

    .discounts p { font-weight: bold; color: #00ffcc; }

    .payment { background-color: #111; padding: 30px 20px; border-radius: 12px; text-align: center; }

    footer { text-align: center; padding: 30px 20px; background-color: #111; font-size: 16px; color: #888; margin-top: 30px; }

    @media (max-width: 600px) {
      header h1 { font-size: 32px; }
      h2 { font-size: 28px; }
      .plan { width: 90%; }
    }
  </style>
</head>
<body>

  <header>
    <img src="ESlogo.png" alt="ES Logo">
    <h1>ES Editing Services</h1>
    <p>Sharp, fast, and creative video edits for your content!</p>
  </header>

  <section>
    <h2>Try Your First Edit for Free!</h2>
    <p>Experience my editing style with your first video completely free. See the quality, speed, and style before committing!</p>
    <a href="#pricing" class="btn">View Pricing & Bundles</a>
  </section>

  <section id="pricing">
    <h2>Pricing & Bundles</h2>
    <div class="pricing">
      <div class="plan">
        <h3>Single Short</h3>
        <p>£15 per Short</p>
        <a href="#" class="btn">Buy Now</a>
      </div>
      <div class="plan">
        <h3>Full Video</h3>
        <p>£35 (up to 10 mins)</p>
        <a href="#" class="btn">Buy Now</a>
      </div>
      <div class="plan">
        <h3>Starter Bundle</h3>
        <p>5 Shorts for £55 (Save £5)</p>
        <a href="#" class="btn">Buy Now</a>
      </div>
      <div class="plan">
        <h3>Pro Bundle</h3>
        <p>10 Shorts for £100 (Save £10)</p>
        <a href="#" class="btn">Buy Now</a>
      </div>
      <div class="plan">
        <h3>Ultimate Bundle</h3>
        <p>20 Shorts for £180 (Save £20)</p>
        <a href="#" class="btn">Buy Now</a>
      </div>
    </div>
  </section>

  <section class="discounts">
    <h2>Special Discounts</h2>
    <p>Refer a friend and get £5 off your next edit!</p>
    <p>Monthly loyalty discount: 5% off after 10+ Shorts in a month!</p>
  </section>

  <section class="payment">
    <h2>How to Pay</h2>
    <p>✅ PayPal (invoice sent directly)</p>
    <p>✅ Bank Transfer (Faster Payments UK)</p>
    <p>✅ Parent-assisted accounts (Revolut Teen or similar)</p>
    <p><strong>Payment Structure:</strong> 50% upfront, 50% after preview with watermark, final HD file delivered once fully paid.</p>
  </section>

  <section style="text-align:center;">
    <h2>Ready to Level Up Your Content?</h2>
    <p>DM now to claim your free first edit and check out the bundles!</p>
    <a href="mailto:youremail@example.com" class="btn">Contact Me</a>
  </section>

  <footer>
    &copy; 2026 ES Editing Services | Professional video editing for creators
  </footer>

</body>
</html>
