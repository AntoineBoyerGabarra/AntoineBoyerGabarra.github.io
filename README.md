<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Academic Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: #f5f7fb;
      color: #1f2937;
      line-height: 1.7;
    }

    header {
      background: linear-gradient(135deg, #1e293b, #0f172a);
      color: white;
      padding: 80px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.1rem;
      opacity: 0.9;
    }

    nav {
      margin-top: 25px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 500;
      transition: opacity 0.3s;
    }

    nav a:hover {
      opacity: 0.7;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 50px 20px;
    }

    section {
      margin-bottom: 60px;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: #0f172a;
      border-bottom: 3px solid #cbd5e1;
      display: inline-block;
      padding-bottom: 6px;
    }

    .card {
      background: white;
      border-radius: 18px;
      padding: 25px;
      margin-bottom: 25px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.06);
      transition: transform 0.2s ease;
    }

    .card:hover {
      transform: translateY(-4px);
    }

    .publication-title {
      font-size: 1.2rem;
      font-weight: 600;
      margin-bottom: 8px;
    }

    .meta {
      color: #64748b;
      font-size: 0.95rem;
      margin-bottom: 12px;
    }

    .btn-group {
      margin-top: 15px;
    }

    .btn {
      display: inline-block;
      padding: 10px 16px;
      border-radius: 10px;
      text-decoration: none;
      margin-right: 10px;
      margin-top: 10px;
      font-weight: 500;
      transition: all 0.3s ease;
    }

    .btn-primary {
      background: #2563eb;
      color: white;
    }

    .btn-primary:hover {
      background: #1d4ed8;
    }

    .btn-secondary {
      background: #e2e8f0;
      color: #1e293b;
    }

    .btn-secondary:hover {
      background: #cbd5e1;
    }

    footer {
      text-align: center;
      padding: 30px 20px;
      color: #64748b;
      background: white;
      border-top: 1px solid #e2e8f0;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2.2rem;
      }

      nav a {
        display: inline-block;
        margin: 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Antoine Boyer Gabarra</h1>
    <p> Computer Sciences Engineer</p>

    <nav>
      <a href="#about">About</a>
      <a href="#thesis">Master Thesis</a>
      <a href="#publications">Publications</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="container">

    <section id="about">
      <h2>About</h2>
      <div class="card">
        <p>
          Welcome to my academic portfolio. I currently hold a master's degree in Computer Sciences from EPFL. My research interests include computer vision, 3D/4D reconstruction, and machine/deep learning.
        </p>
      </div>
    </section>

    <section id="thesis">
      <h2>Master Thesis</h2>

      <div class="card">
        <div class="publication-title">
          Thesis Title Goes Here
        </div>

        <div class="meta">
          Master's Thesis • 2026 • University Name
        </div>

        <p>
          Short abstract of your thesis. Explain the research problem, methodology, and contributions in a concise paragraph.
        </p>

        <div class="btn-group">
          <a class="btn btn-primary" href="thesis/master_thesis.pdf" target="_blank">
            Read Thesis
          </a>
          <a class="btn btn-secondary" href="thesis/master_thesis.pdf" download>
            Download Thesis
          </a>
        </div>
      </div>
    </section>

    <section id="publications">
      <h2>Publications</h2>

      <div class="card">
        <div class="publication-title">
          Geometry-aware 3D Gaussian Model for View-Dependent Rendering of 3D Morphable Models
        </div>

        <div class="meta">
          Web3D • 2025
        </div>

        <p>
          Brief summary of the publication and its contributions.
        </p>

        <div class="btn-group">
          <a class="btn btn-primary" href="papers/Web3D2025.pdf" target="_blank">
            Read Paper
          </a>
          <a class="btn btn-secondary" href="papers/Web3D2025.pdf" download>
            Download Paper
          </a>
          <a class="btn btn-secondary" href="bibtex/Web3D2025.bib" target="_blank">
            BibTeX
          </a>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>

      <div class="card">
        <p><strong>Email:</strong> antoine.boyer-gabarra@outlook.com</p>
        <p><strong>Phone:</strong> +33676578348</p>
      </div>
    </section>

  </div>

  <footer>
    © 2026 Antoine Boyer Gabarra • Academic Portfolio
  </footer>

</body>
</html>
