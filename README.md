<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Eloheh Healthcare - Our Story</title>
  <style>
    body {
      font-family: 'Verdana', sans-serif;
      background-color: #ffffff;
      color: #333333;
      margin: 0;
      padding: 0;
      background-color: #fff;
      color: #333;
      margin: 0; padding: 0;
    }

    .banner {
@@ -20,14 +19,14 @@
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      color: #fff;
      text-shadow: 2px 2px 4px #000;
    }

    .banner h1 {
      font-size: 36px;
      font-family: 'Georgia', serif;
      background-color: rgba(0, 0, 0, 0.4);
      background: rgba(0,0,0,0.4);
      padding: 10px 20px;
      border-radius: 8px;
    }
@@ -38,15 +37,9 @@
      padding: 20px;
    }

    h2 {
      font-size: 22px;
      color: #004c3f;
    }
    h2 { font-size: 22px; color: #004c3f; }

    .highlight {
      font-style: italic;
      color: #0077b6;
    }
    .highlight { font-style: italic; color: #0077b6; }

    .important {
      font-weight: bold;
@@ -55,10 +48,7 @@
      color: #b22222;
    }

    a {
      color: #0077b6;
      text-decoration: none;
    }
    a { color: #0077b6; text-decoration: none; }

    .download-btn {
      display: inline-block;
@@ -72,9 +62,7 @@
      transition: background-color 0.3s ease;
    }

    .download-btn:hover {
      background-color: #006b50;
    }
    .download-btn:hover { background-color: #006b50; }

    img {
      width: 100%;
@@ -90,7 +78,6 @@
      color: gray;
    }

    /* Collapsible section */
    .collapsible {
      background-color: #e6f1ed;
      color: #004c3f;
@@ -105,9 +92,7 @@
      border-radius: 5px;
    }

    .collapsible:hover {
      background-color: #d1e8e0;
    }
    .collapsible:hover { background-color: #d1e8e0; }

    .content {
      padding: 0 18px;
@@ -118,38 +103,79 @@
      margin-bottom: 20px;
    }

    /* Timeline */
    .timeline {
    /* Horizontal Timeline */
    .timeline-horizontal {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      position: relative;
      margin: 30px 0;
      padding-left: 30px;
      border-left: 4px solid #004c3f;
      margin: 40px 0;
      padding: 40px 0;
      border-top: 4px solid #004c3f;
    }

    .timeline-event {
      margin-bottom: 20px;
    .timeline-horizontal::before {
      content: '';
      position: absolute;
      top: 36px;
      left: 0;
      width: 100%;
      height: 4px;
      background: #004c3f;
      z-index: 1;
    }

    .timeline-block {
      position: relative;
      flex: 1;
      min-width: 220px;
      padding: 20px;
      text-align: center;
      z-index: 2;
    }

    .timeline-event::before {
    .timeline-block::before {
      content: '';
      position: absolute;
      left: -10px;
      top: 0;
      top: 28px;
      left: 50%;
      transform: translateX(-50%);
      width: 16px;
      height: 16px;
      background-color: #004c3f;
      border-radius: 50%;
      z-index: 3;
    }

    .timeline-event h4 {
      margin: 0;
    .timeline-block h4 {
      margin: 20px 0 5px;
      font-size: 18px;
      color: #004c3f;
    }

    .timeline-event p {
      margin: 5px 0 0 0;
    .timeline-block p {
      font-size: 14px;
      margin: 0;
    }

    @media (max-width: 768px) {
      .timeline-horizontal {
        flex-direction: column;
        border-top: none;
      }

      .timeline-block {
        border-left: 4px solid #004c3f;
        margin-left: 20px;
        padding-left: 20px;
        text-align: left;
      }

      .timeline-block::before {
        top: 0;
        left: -12px;
        transform: none;
      }
    }
  </style>
</head>
@@ -167,67 +193,62 @@
    <div class="content">
      <p><span class="important">Eloheh Healthcare</span> was <u>established in 2015</u> with a mission to deliver inclusive, compassionate, and accessible healthcare to individuals from all walks of life.</p>
      <p class="highlight">We began as a small, community-driven clinic and have evolved into a nationally trusted provider serving diverse populations through innovation and care.</p>
      <p>The word <b>Eloheh</b> comes from a Native American term meaning <i>“harmony”</i> and <i>“spirit of life”</i> — a guiding principle in our approach to care. Founded by a team of nurses, public health advocates, and educators, Eloheh set out to bridge the gap in healthcare access through mobile units, culturally responsive services, and community education.</p>
      <p>The word <b>Eloheh</b> comes from a Native American term meaning <i>“harmony”</i> and <i>“spirit of life”</i>. Founded by a team of nurses, public health advocates, and educators, Eloheh set out to bridge healthcare access gaps through mobile units, culturally responsive services, and community education.</p>
    </div>

    <!-- Timeline: Our Journey -->
    <!-- Horizontal Timeline -->
    <h2>⏳ Our Journey Through the Years</h2>
    <div class="timeline">
      <div class="timeline-event">
        <h4>2015–2016: Laying the Foundation</h4>
        <p>Opened our first clinic in Portland. Hosted free community screenings and piloted a culturally inclusive care model.</p>
    <div class="timeline-horizontal">
      <div class="timeline-block">
        <h4>2015–2016</h4>
        <p>Laying the Foundation: First clinic in Portland, free screenings, inclusive care model.</p>
      </div>
      <div class="timeline-event">
        <h4>2017–2019: Mobile Outreach</h4>
        <p>Launched mobile wellness units, expanded multilingual telehealth services, and established school partnerships.</p>
      <div class="timeline-block">
        <h4>2017–2019</h4>
        <p>Mobile Outreach: Wellness vans, multilingual telehealth, school partnerships.</p>
      </div>
      <div class="timeline-event">
        <h4>2020–2021: Pandemic Response</h4>
        <p>Rolled out testing and telemedicine during COVID-19. Created the Eloheh Cares relief fund and trained 200+ community health workers.</p>
      <div class="timeline-block">
        <h4>2020–2021</h4>
        <p>Pandemic Response: COVID testing, virtual care, community health workers.</p>
      </div>
      <div class="timeline-event">
        <h4>2022–2024: Innovation & Growth</h4>
        <p>Launched our wellness app, began academic partnerships, and expanded to eight U.S. states.</p>
      <div class="timeline-block">
        <h4>2022–2024</h4>
        <p>Innovation & Growth: Wellness app, research partnerships, 8-state expansion.</p>
      </div>
    </div>

    <!-- Collapsible: Looking Ahead -->
    <button class="collapsible">🔮 Looking Ahead</button>
    <div class="content">
      <p>Eloheh Healthcare is shaping the future of wellness through policy advocacy, climate-resilient clinics, and telepsychology platforms. We continue to fight for equitable care, support elder communities, and bring compassion to every community we serve.</p>
      <p>Eloheh Healthcare is shaping the future of wellness through policy advocacy, climate‑resilient clinics, and telepsychology platforms. We continue to fight for equitable care, support elder communities, and bring compassion to every community we serve.</p>
    </div>

    <!-- Image -->
    <img src="https://via.placeholder.com/800x300.png?text=Eloheh+Team+and+Community+Wellness" alt="Eloheh Team Photo" />
    <!-- Updated Team Photo -->
    <img src="https://www.studentdoctor.net/wp-content/uploads/2007/10/shutterstock_317578871.png" alt="Eloheh Team Photo" />

    <!-- External Link -->
    <p>For more on global health efforts, visit the <a href="https://www.who.int" target="_blank">World Health Organization</a>.</p>

    <!-- Download Button -->
    <p>
      <a class="download-btn" href="eloheh_services_brochure.pdf" download>📄 Download Our Brochure</a>
    </p>
    <p><a class="download-btn" href="eloheh_services_brochure.pdf" download>📄 Download Our Brochure</a></p>

    <!-- Email Contact -->
    <!-- Contact -->
    <p><a href="mailto:contact@elohehhealth.org">📧 Contact Me</a></p>
  </div>

  <footer>
    <p>Last updated:
      <script>
        document.write(new Date(document.lastModified).toLocaleDateString());
      </script>
      <script>document.write(new Date(document.lastModified).toLocaleDateString());</script>
    </p>
  </footer>

  <!-- Collapsible Section Script -->
  <!-- Collapsible Logic -->
  <script>
    const collapsibles = document.querySelectorAll(".collapsible");
    collapsibles.forEach((btn) => {
      btn.addEventListener("click", function () {
    document.querySelectorAll(".collapsible").forEach(btn => {
      btn.addEventListener("click", function() {
        this.classList.toggle("active");
        const content = this.nextElementSibling;
        content.style.display = content.style.display === "block" ? "none" : "block";
        const c = this.nextElementSibling;
        c.style.display = c.style.display === "block" ? "none" : "block";
      });
    });
  </script>
