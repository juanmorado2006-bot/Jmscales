# Jmscales
from zipfile import ZipFile
from pathlib import Path

html_content = """<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jmscales</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #ffffff;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #f8f8f8;
      padding: 2rem;
      text-align: center;
      border-bottom: 1px solid #ddd;
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
      color: #222;
    }

    header p {
      color: #555;
    }

    section {
      padding: 3rem 1rem;
      max-width: 800px;
      margin: auto;
    }

    h2 {
      margin-bottom: 1rem;
      color: #111;
      font-size: 1.5rem;
      border-bottom: 2px solid #eee;
      padding-bottom: 0.5rem;
    }

    .results, .services {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1.5rem;
    }

    .card {
      background: #fafafa;
      padding: 1rem;
      border: 1px solid #e0e0e0;
      border-radius: 6px;
    }

    .card h3 {
      margin-top: 0;
      color: #222;
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      background: #f0f0f0;
      color: #555;
      font-size: 0.9rem;
    }

    footer a {
      color: #333;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }

    @media (max-width: 600px) {
      .results, .services {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Jmscales</h1>
    <p>Delivering Results with Simplicity</p>
  </header>

  <section>
    <h2>Our Results</h2>
    <div class="results">
      <div class="card">
        <h3>Real Results Coming Soon</h3>
        <p>We’re tracking data with our pixel — check back soon for verified performance metrics.</p>
      </div>
      <div class="card">
        <h3>Performance-Driven Growth</h3>
        <p>Our focus is delivering measurable value to every client, every time.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>Consulting</h3>
        <p>Strategic business advice to drive growth and efficiency.</p>
      </div>
      <div class="card">
        <h3>Web Development</h3>
        <p>Creating modern, responsive websites tailored to your brand.</p>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 Jmscales. All rights reserved.<br/>
    📞 <a href="tel:8632347911">863-234-7911</a> |
    📧 <a href="mailto:juanmorado2006@gmail.com">juanmorado2006@gmail.com</a>
  </footer>

</body>
</html>
"""
