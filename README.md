<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Eloheh Healthcare - Our Story</title>
    <style>
        body {
            font-family: 'Verdana', sans-serif;
            background-color: #ffffff;
            color: #333333;
            margin: 0;
            padding: 0;
        }

        .banner {
            background-image: url('https://www.odu.edu/sites/default/files/program-page/headerimages/global-health-header.jpeg');
            background-size: cover;
            background-position: center;
            height: 250px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 4px #000;
        }

        .banner h1 {
            font-size: 36px;
            font-family: 'Georgia', serif;
            background-color: rgba(0, 0, 0, 0.4);
            padding: 10px 20px;
            border-radius: 8px;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        h2 {
            font-size: 22px;
            color: #004c3f;
        }

        .highlight {
            font-style: italic;
            color: #0077b6;
        }

        .important {
            font-weight: bold;
            font-size: 18px;
            font-family: 'Arial', sans-serif;
            color: #b22222;
        }

        img {
            width: 100%;
            max-width: 800px;
            display: block;
            margin: 20px auto;
        }

        a {
            color: #0077b6;
            text-decoration: none;
        }

        footer {
            margin-top: 40px;
            font-size: 14px;
            text-align: center;
            color: gray;
        }

        ul, ol {
            padding-left: 20px;
        }

        /* Button styling */
        .download-btn {
            display: inline-block;
            background-color: #004c3f;
            color: white;
            padding: 10px 20px;
            border-radius: 6px;
            font-size: 16px;
            font-weight: bold;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }

        .download-btn:hover {
            background-color: #006b50;
        }
    </style>
</head>
<body>

    <div class="banner">
        <h1>Eloheh Healthcare</h1>
    </div>

    <div class="container">
        <p><i>Your Partner in Holistic Wellness</i></p>

        <h2>Our Story</h2>
        <p><span class="important">Eloheh Healthcare</span> was <u>established in 2015</u> with a mission to deliver inclusive, compassionate, and accessible healthcare to individuals from all walks of life.</p>
        
        <p class="highlight">We began as a small, community-driven clinic and have evolved into a nationally trusted provider serving diverse populations through innovation and care.</p>

        <h2>Our Journey</h2>
        <ol>
            <li>2015 – Founded in Portland, Oregon</li>
            <li>2017 – Introduced mobile wellness units</li>
            <li>2020 – Rolled out virtual telehealth platform</li>
            <li>2023 – Expanded into school-based partnerships</li>
        </ol>

        <h2>Our Core Values</h2>
        <ul>
            <li>Integrity in care</li>
            <li>Equitable access</li>
            <li>Innovation through technology</li>
            <li>Sustainability and community support</li>
        </ul>

        <img src="https://via.placeholder.com/800x300.png?text=Eloheh+Team+and+Community+Wellness" alt="Eloheh Team Photo">

        <p>For more on global health efforts, visit the <a href="https://www.who.int" target="_blank">World Health Organization</a>.</p>

        <p>
            <a class="download-btn" href="eloheh_services_brochure.pdf" download>📄 Download Our Brochure</a>
        </p>

        <p><a href="mailto:raleight@elohehhealth.org">📧 Contact Me</a></p>
    </div>

    <footer>
        <p>Last updated: 
            <script>
                document.write(new Date(document.lastModified).toLocaleDateString());
            </script>
        </p>
    </footer>

</body>
</html>
