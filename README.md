<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shorder - Sustainable Shoe Storage</title>
  <style>
    * { margin:0; padding:0; box-sizing:border-box; font-family:'Helvetica Neue', Helvetica, Arial, sans-serif; }
    body { background-color:#fdfaf6; color:#333; line-height:1.6; }
    a { text-decoration:none; color:inherit; }

    header { background-color:#fff; padding:40px 20px; text-align:center; box-shadow:0 2px 5px rgba(0,0,0,0.05);}
    header h1 { font-size:3rem; font-weight:700; letter-spacing:2px; margin-bottom:10px; }
    header p { font-size:1.2rem; color:#555; }

    .hero { display:flex; flex-direction:column; align-items:center; justify-content:center; text-align:center; padding:80px 20px; background:url('https://images.unsplash.com/photo-1580910051072-93f39d2a4f8c?auto=format&fit=crop&w=1200&q=80') no-repeat center center/cover; color:#fff; }
    .hero h2 { font-size:2.5rem; margin-bottom:20px; background-color:rgba(0,0,0,0.5); padding:10px 20px; border-radius:5px; }
    .hero p { font-size:1.2rem; max-width:600px; margin-bottom:30px; background-color:rgba(0,0,0,0.5); padding:10px 20px; border-radius:5px; }
    .hero a { background-color:#333; color:#fff; padding:15px 30px; border-radius:5px; font-weight:bold; transition:0.3s; }
    .hero a:hover { background-color:#555; }

    .features { display:flex; flex-wrap:wrap; justify-content:center; padding:60px 20px; background-color:#f9f6f2; }
    .feature { background-color:#fff; margin:20px; padding:30px; border-radius:10px; flex:1 1 300px; max-width:350px; box-shadow:0 4px 10px rgba(0,0,0,0.05); text-align:center; }
    .feature h3 { font-size:1.5rem; margin-bottom:15px; color:#333; }
    .feature p { color:#555; }

    .newsletter { background-color:#fff; padding:60px 20px; text-align:center; }
    .newsletter h3 { font-size:2rem; margin-bottom:20px; }
    .newsletter form { max-width:400px; margin:0 auto; display:flex; flex-direction:column; gap:15px; }
    .newsletter input[type="email"] { padding:15px; border-radius:5px; border:1px solid #ccc; font-size:1rem; }
    .newsletter button { padding:15px; border:none; border-radius:5px; background-color:#333; color:#fff; font-weight:bold; cursor:pointer; transition:0.3s; }
    .newsletter button:hover { background-color:#555; }

    .authenticity { text-align:center; padding:40px 20px; }
    .authenticity a { display:inline-block; background-color:#333; color:#fff; padding:15px 30px; border-radius:5px; font-weight:bold; transition:0.3s; }
    .authenticity a:hover { background-color:#555; }

    footer { text-align:center; padding:40px 20px; background-color:#fff; border-top:1px solid #e0e0e0; font-size:0.9rem; color:#777; }

    @media (max-width:768px){ .features { flex-direction:column; align-items:center; } }
  </style>
</head>
<body>

  <header>
    <h1>Shorder</h1>
    <p>Elegant, Sustainable Shoe Storage</p>
  </header>

  <section class="hero">
    <h2>Organize Your Shoes with Style</h2>
    <p>Discover our reusable wooden shoe boxes with transparent recycled acrylic fronts – designed for a tidy, elegant wardrobe while caring for the planet.</p>
    <a href="#features">Learn More</a>
  </section>

  <section class="features" id="features">
    <div class="feature">
      <h3>Elegant Design</h3>
      <p>Minimalist wooden boxes with a luxury feel, perfectly complementing your home decor.</p>
    </div>
    <div class="feature">
      <h3>Sustainable Materials</h3>
      <p>Crafted from thin wooden panels and recycled perspex, prioritizing environmental responsibility.</p>
    </div>
    <div class="feature">
      <h3>Functional Storage</h3>
      <p>Drawer-style boxes make organizing and accessing your shoes easy and orderly.</p>
    </div>
  </section>

  <section class="newsletter">
    <h3>Subscribe to Our Newsletter</h3>
    <form action="https://example.com/subscribe" method="POST">
      <input type="email" name="email" placeholder="Enter your email" required>
      <button type="submit">Subscribe</button>
    </form>
  </section>

  <section class="authenticity">
    <h3>Check Your Shoes' Authenticity</h3>
    <a href="https://example.com/authenticate" target="_blank">Verify Now</a>
  </section>

  <footer>
    &copy; 2025 Shorder. All rights reserved. | Designed for sustainability and elegance.
  </footer>

</body>
</html>
