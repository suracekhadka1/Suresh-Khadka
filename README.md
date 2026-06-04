<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Suresh Khadka | Portfolio</title>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Poppins', sans-serif;
      scroll-behavior:smooth;
    }

    body{
      background:#0f172a;
      color:white;
      line-height:1.6;
    }

    nav{
      position:fixed;
      width:100%;
      top:0;
      left:0;
      padding:20px 10%;
      display:flex;
      justify-content:space-between;
      align-items:center;
      background:rgba(15,23,42,0.9);
      backdrop-filter:blur(10px);
      z-index:1000;
    }

    nav h1{
      color:#38bdf8;
      font-size:1.5rem;
    }

    nav ul{
      display:flex;
      list-style:none;
      gap:25px;
    }

    nav a{
      color:white;
      text-decoration:none;
      transition:0.3s;
    }

    nav a:hover{
      color:#38bdf8;
    }

    header{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      text-align:center;
      padding:20px;
      background:
      linear-gradient(rgba(0,0,0,0.7), rgba(15,23,42,0.9)),
      url('https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=2071');
      background-size:cover;
      background-position:center;
    }

    .hero h1{
      font-size:4rem;
      margin-bottom:10px;
    }

    .hero h2{
      color:#38bdf8;
      font-weight:400;
      margin-bottom:20px;
    }

    .hero p{
      max-width:700px;
      margin:auto;
      margin-bottom:30px;
      color:#cbd5e1;
    }

    .btn{
      display:inline-block;
      padding:12px 28px;
      background:#38bdf8;
      color:#0f172a;
      text-decoration:none;
      border-radius:30px;
      font-weight:600;
      transition:0.3s;
    }

    .btn:hover{
      background:white;
      transform:translateY(-3px);
    }

    section{
      padding:100px 10%;
    }

    .section-title{
      font-size:2.5rem;
      color:#38bdf8;
      margin-bottom:40px;
      text-align:center;
    }

    .about{
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:40px;
    }

    .card{
      background:#1e293b;
      padding:30px;
      border-radius:20px;
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-5px);
    }

    .timeline{
      display:grid;
      gap:20px;
    }

    .skills{
      display:flex;
      flex-wrap:wrap;
      justify-content:center;
      gap:15px;
    }

    .skill{
      background:#38bdf8;
      color:#0f172a;
      padding:12px 22px;
      border-radius:25px;
      font-weight:600;
    }

    footer{
      text-align:center;
      padding:30px;
      background:#020617;
      color:#94a3b8;
    }

    @media(max-width:768px){

      nav{
        flex-direction:column;
        gap:10px;
      }

      nav ul{
        gap:15px;
      }

      .hero h1{
        font-size:2.5rem;
      }

      .about{
        grid-template-columns:1fr;
      }

      section{
        padding:80px 7%;
      }

    }

  </style>

</head>

<body>

  <nav>
    <h1>Suresh Khadka</h1>

    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <header>

    <div class="hero">

      <h1>Suresh Khadka</h1>

      <h2>Master of Social Work Student</h2>

      <p>
        Passionate about community engagement, leadership, social advocacy,
        and creating meaningful impact through social work and youth empowerment.
      </p>

      <a 
        href="https://www.linkedin.com/in/suresh-khadka-631153232/" 
        target="_blank"
        class="btn">
        View LinkedIn
      </a>

    </div>

  </header>

  <section id="about">

    <h2 class="section-title">About Me</h2>

    <div class="about">

      <div class="card">

        <h3>Who I Am</h3>
        <br>

        <p>
          I am currently pursuing a Master of Social Work at Western Sydney University.
          I enjoy understanding social issues, helping communities,
          and building leadership through education and practical experience.
        </p>

      </div>

      <div class="card">

        <h3>My Vision</h3>
        <br>

        <p>
          My goal is to contribute toward stronger communities,
          support youth empowerment, and advocate for positive social change
          both locally and internationally.
        </p>

      </div>

    </div>

  </section>

  <section id="education">

    <h2 class="section-title">Education & Experience</h2>

    <div class="timeline">

      <div class="card">
        <h3>Western Sydney University</h3>
        <p>Master of Social Work</p>
      </div>

      <div class="card">
        <h3>Club Burwood Group</h3>
        <p>Professional Experience • Australia</p>
      </div>

    </div>

  </section>

  <section id="skills">

    <h2 class="section-title">Skills</h2>

    <div class="skills">

      <div class="skill">Leadership</div>
      <div class="skill">Communication</div>
      <div class="skill">Community Engagement</div>
      <div class="skill">Public Speaking</div>
      <div class="skill">Teamwork</div>
      <div class="skill">Social Advocacy</div>

    </div>

  </section>

  <section id="contact">

    <h2 class="section-title">Contact</h2>

    <div class="card" style="text-align:center;">

      <p>Feel free to connect with me professionally.</p>

      <br>

      <a 
        href="https://www.linkedin.com/in/suresh-khadka-631153232/" 
        target="_blank"
        class="btn">
        Connect on LinkedIn
      </a>

    </div>

  </section>

  <footer>
    © 2026 Suresh Khadka | Personal Portfolio
  </footer>

</body>
</html>
