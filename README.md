# cephas_website

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cephas Omondi - Health Records Manager</title>
  <style>
    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    /* Navigation bar */
    nav {
      background-color: #333;
      color: white;
      padding: 10px 20px;
      position: sticky;
      top: 0;
      z-index: 999;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    nav h1 {
      margin: 0;
      font-size: 1.2rem;
    }

    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      align-items: center;
      flex-wrap: wrap;
    }

    nav ul li {
      margin-left: 20px;
    }

    nav ul li a,
    .download-btn {
      color: white;
      text-decoration: none;
      font-weight: bold;
      background-color: transparent;
      border: 2px solid white;
      padding: 5px 10px;
      border-radius: 4px;
      transition: 0.3s;
    }

    nav ul li a:hover,
    .download-btn:hover {
      background-color: white;
      color: #333;
    }

    /* Header */
    header {
      text-align: center;
      padding: 30px 20px;
      background-color: #555;
      color: white;
    }

    .profile-pic {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 10px;
      border: 3px solid #fff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    }

    /* Sections */
    section {
      background: white;
      margin: 20px auto;
      padding: 20px;
      width: 90%;
      max-width: 900px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    h2 {
      border-bottom: 2px solid #eee;
      padding-bottom: 5px;
      margin-bottom: 10px;
    }

    ul {
      padding-left: 20px;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #333;
      color: white;
    }

    a {
      color: #007BFF;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

<!-- Navigation Bar -->
<nav>
  <h1>Cephas Omondi</h1>
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#education">Education</a></li>
    <li><a href="#certifications">Certifications</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#contact">Contact</a></li>
    <li>
      <a href="Cephas_Omondi_CV.pdf/Updated Cv 2025 1.pdf updated cv 2025 1.pdf" class="download-btn" download>Download CV</a>
    </li>
  </ul>
</nav>

<!-- Header -->
<header>
  <img src="cephas_omondi.jpg" alt="Cephas Omondi" class="profile-pic" />
  <h2>Health Records and Information Manager</h2>
</header>

<!-- About -->
<section id="about">
  <h2>About Me</h2>
  <p>I am a flexible and dynamic Health Records and Information Manager (HRIM) with over 2 years of experience. I bring technical and leadership skills to Health Management Information Systems (HMIS) to improve patient outcomes and ensure operational efficiency. My strengths include data reporting in DHIS2, training healthcare staff, and maintaining compliance with International Health Regulations (IHR 2005).</p>
</section>

<!-- Experience -->
<section id="experience">
  <h2>Experience</h2>
  <ul>
    <li><strong>Health Records Officer</strong> – Oasis Health Doctors Plaza, Migori (May 2025 – Present)</li>
    <li><strong>Health Records Officer</strong> – Chulaimbo Sub County Hospital, Kisumu (Sept 2024 – Apr 2025)</li>
    <li><strong>Health Records Intern</strong> – Kisumu County Referral Hospital (May 2024 – Jun 2024)</li>
    <li><strong>Health Records Attachee</strong> – St. Joseph’s Mission Hospital, Migori (Jan 2023 – Apr 2023)</li>
    <li><strong>Health Records Attachee</strong> – Asumbi Mission Hospital, Homa Bay (Apr 2022 – Sept 2022)</li>
  </ul>
</section>

<!-- Education -->
<section id="education">
  <h2>Education</h2>
  <p><strong>Bachelor of Science in Health Records and Information Management</strong><br>Rongo University, Migori (Sept 2020 – Apr 2024)</p>
  <p><strong>KCSE</strong><br>Wang’apala High School, Homa Bay (Feb 2016 – Nov 2019)</p>
</section>

<!-- Certifications -->
<section id="certifications">
  <h2>Certifications</h2>
  <ul>
    <li>Covid-19 Response Training – Chanjo Health System, April 2022</li>
    <li>Leadership & Governance for Health Systems – Feb 2021</li>
    <li>HIV M&E Tools – UoN/NASCOP, June 2023</li>
    <li>Kenya Health Information System (DHIS2)</li>
    <li>Master Health Facility List – MOH Virtual Academy</li>
    <li>KenyaEMR+ Level I</li>
    <li>KHIS Aggregate Course (DHIS2)</li>
    <li>HIS Security Management Course</li>
    <li>Monitoring & Evaluation in Cancer Management</li>
    <li>Pandemic & Epidemic-Prone Disease Certificate – WHO (2022)</li>
    <li>AI in Health Ethics Certificate – WHO (2022)</li>
    <li>Data Protection Act – JKUAT/KenyaHMIS</li>
    <li>Research Ethics – JKUAT/KenyaHMIS</li>
    <li>Certificate in Computer Training</li>
  </ul>
</section>

<!-- Skills -->
<section id="skills">
  <h2>Skills</h2>
  <ul>
    <li>Health Information Management</li>
    <li>ICT Proficiency & Troubleshooting</li>
    <li>Data Entry & Analytics</li>
    <li>Customer Relations & Administration</li>
    <li>Excellent Communication (Oral & Written)</li>
    <li>Teamwork & Leadership</li>
    <li>Problem Solving & Critical Thinking</li>
    <li>Organizational & Planning Skills</li>
  </ul>
</section>

<!-- Contact -->
<section id="contact">
  <h2>Contact</h2>
  <p><strong>Email:</strong> <a href="mailto:cephasomondi610@gmail.com">cephasomondi610@gmail.com</a></p>
  <p><strong>Phone:</strong> +254 795 775 218</p>

  <h3>Send Me a Message</h3>
  <form action="https://formsubmit.co/cephasomondi610@gmail.com" method="POST" style="display: flex; flex-direction: column; gap: 12px; max-width: 600px;">
    <input type="text" name="name" placeholder="Your Name" required style="padding: 10px; border: 1px solid #ccc; border-radius: 5px;" />
    <input type="email" name="email" placeholder="Your Email" required style="padding: 10px; border: 1px solid #ccc; border-radius: 5px;" />
    <input type="text" name="_subject" placeholder="Subject" required style="padding: 10px; border: 1px solid #ccc; border-radius: 5px;" />
    <textarea name="message" placeholder="Your Message" rows="5" required style="padding: 10px; border: 1px solid #ccc; border-radius: 5px;"></textarea>
    <button type="submit" style="padding: 10px 20px; background-color: #007BFF; color: white; border: none; border-radius: 5px; cursor: pointer;">Send Message</button>
  </form>
</section>


<!-- Footer -->
<footer>
  &copy; 2025 Cephas Omondi. All Rights Reserved.
</footer>

</body>
</html>
