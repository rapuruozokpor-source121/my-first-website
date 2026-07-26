<!DOCTYPE html>
<html>
<head>
  <title>My Business</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(135deg, #2c3e50, #34495e);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.5em;
      margin: 0 0 10px 0;
    }
    header p {
      font-size: 1.2em;
      opacity: 0.9;
      margin: 0;
    }
    section {
      max-width: 800px;
      margin: 0 auto;
      padding: 50px 20px;
    }
    h2 {
      color: #2c3e50;
      font-size: 1.8em;
      border-bottom: 3px solid #2c3e50;
      padding-bottom: 10px;
      margin-bottom: 25px;
    }
    p {
      font-size: 18px;
    }
    .service {
      background: white;
      padding: 25px;
      margin-bottom: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.08);
      transition: transform 0.2s;
    }
    .service:hover {
      transform: translateY(-3px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.12);
    }
    .service strong {
      color: #2c3e50;
      font-size: 1.1em;
    }
    footer {
      text-align: center;
      padding: 25px;
      background-color: #2c3e50;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Business</h1>
    <p>Video editing, videography & ad management</p>
  </header>

  <section id="about">
    <h2>About</h2>
    <p>I help businesses create engaging video content and run effective ad campaigns to reach more customers.</p>
  </section>

  <section id="services">
    <h2>Services</h2>
    <div class="service">
      <strong>Video Editing</strong> — Professional editing for promos, social media, and events.
    </div>
    <div class="service">
      <strong>Ad Creative & Campaign Management</strong> — I create ad content and run your Facebook/Instagram/Google ads.
    </div>
    <div class="service">
      <strong>Content Strategy</strong> — Help planning what to post and how often to grow your audience.
    </div>
    <div class="service">
      <strong>AI Chatbot Setup</strong> — Custom AI chatbots to answer customer questions and support your business 24/7.
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Have a question or want to work together? Send me a message below.</p>

    <form action="https://formspree.io/f/mlgqovya" method="POST" style="max-width: 500px;">
      <div style="margin-bottom: 15px;">
        <label>Name</label><br>
        <input type="text" name="name" required style="width: 100%; padding: 10px; border-radius: 5px; border: 1px solid #ccc;">
      </div>
      <div style="margin-bottom: 15px;">
        <label>Email</label><br>
        <input type="email" name="email" required style="width: 100%; padding: 10px; border-radius: 5px; border: 1px solid #ccc;">
      </div>
      <div style="margin-bottom: 15px;">
        <label>Message</label><br>
        <textarea name="message" rows="5" required style="width: 100%; padding: 10px; border-radius: 5px; border: 1px solid #ccc;"></textarea>
      </div>
      <button type="submit" style="background-color: #2c3e50; color: white; padding: 12px 30px; border: none; border-radius: 5px; font-size: 16px; cursor: pointer;">Send Message</button>
    </form>

    <p style="margin-top: 20px;">Or reach me directly: janedoe@gmail.com</p>
  </section>

  <footer>
    <p>&copy; 2026 My Business. All rights reserved.</p>
  </footer>

</body>
</html>
