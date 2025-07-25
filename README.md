<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Pandey Lab</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
      background-color: #fdfdfd;
      color: #333;
    }

    nav {
      background-color: #004f6e;
      color: white;
      display: flex;
      justify-content: space-between;
      padding: 1rem 2rem;
    }

    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: 500;
    }

    .container {
      padding: 2rem;
      max-width: 1100px;
      margin: auto;
    }

    header {
      text-align: center;
      padding: 3rem 0;
    }

    header h1 {
      font-size: 3rem;
      color: #004f6e;
    }

    .photo-placeholder {
      width: 200px;
      height: 200px;
      background-color: #ccc;
      margin: 1rem auto;
      border-radius: 50%;
    }

    h2 {
      color: #004f6e;
      margin-top: 2rem;
      margin-bottom: 1rem;
    }

    .team-grid, .alumni-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 1rem;
    }

    .team-member, .alumni-member {
      background: #f0f0f0;
      padding: 1rem;
      text-align: center;
      border-radius: 8px;
    }

    footer {
      background-color: #004f6e;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 3rem;
    }
  </style>
</head>

<body>
  <nav>
    <div>The Pandey Lab</div>
    <div>
      <a href="#home">Home</a>
      <a href="#research">Research</a>
      <a href="#team">Team</a>
      <a href="#alumni">Alumni</a>
      <a href="#publications">Publications</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <div id="home" class="container">
    <header>
      <h1>The Pandey Lab</h1>
      <div class="photo-placeholder"></div>
      <p><strong>Udai Bhan Pandey</strong><br />
        Professor, Pediatrics and Human Genetics<br />
        Director, Children's Neuroscience Institute<br /><br />
        <strong>Education:</strong><br />
        B.S. – Dr. RML Avadh University, India<br />
        M.S. – Dr. RML Avadh University, India<br />
        Ph.D. – SGPGIMS, India<br />
      </p>
    </header>
  </div>

  <div id="research" class="container">
    <h2>Research</h2>
    <p>The Pandey laboratory focuses on the molecular mechanisms of amyotrophic lateral sclerosis (ALS) and other motor neuron diseases, exploring how RNA-binding protein mutations contribute to disease pathology using fly and mammalian models. The lab also studies GEMIN5's role in RNA metabolism and its implications in neurodevelopmental disorders.</p>
    <ul>
      <li>Neurobiology</li>
      <li>Cell Biology</li>
      <li>Genetics</li>
    </ul>
  </div>

  <div id="team" class="container">
    <h2>Team</h2>
    <div class="team-grid">
      <div class="team-member">Udai Pandey, PhD</div>
      <div class="team-member">Sukhleen Kour</div>
      <div class="team-member">Eric Anderson</div>
      <div class="team-member">Snehal Patil</div>
      <div class="team-member">Shun Kubota</div>
      <div class="team-member">Veronica Ferrari</div>
      <div class="team-member">John Wang</div>
      <div class="team-member">Anjali Bajaj</div>
      <div class="team-member">Christopher Zammerilla</div>
      <div class="team-member">Carter White</div>
      <div class="team-member">Sheryl Rodriguez</div>
      <div class="team-member">Shreya George</div>
      <div class="team-member">Rhheaa Metha</div>
    </div>
  </div>

  <div id="alumni" class="container">
    <h2>Alumni</h2>
    <div class="alumni-grid">
      <div class="alumni-member">To be added</div>
    </div>
  </div>

  <div id="publications" class="container">
    <h2>Publications</h2>
    <p>Coming soon. This section will feature selected publications with journal logos and links.</p>
  </div>

  <div id="contact" class="container">
    <h2>Contact</h2>
    <p>
      Udai Pandey, PhD<br />
      Professor, Department of Pediatrics<br />
      Director, Children’s Neuroscience Institute<br />
      Children’s Hospital of Pittsburgh<br />
      University of Pittsburgh Medical Center<br />
      Pittsburgh, PA 15224<br />
      Email: <a href="mailto:udai@pitt.edu">udai@pitt.edu</a><br />
      Phone: 412-692-3192
    </p>
  </div>

  <footer>
    <p>&copy; 2025 The Pandey Lab, University of Pittsburgh</p>
  </footer>
</body>

</html>
