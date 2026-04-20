
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Nandipha Galada CV</title>

<style>
    body {
        margin: 0;
        font-family: "Times New Roman", serif;
        background: #f3ede6; /* nude beige background */
        color: #2b2b2b;
    }

    /* TOP NAME SECTION */
    .header {
        background: #7a5c3e; /* bronze brown */
        color: white;
        text-align: center;
        padding: 50px 20px;
    }

    .header h1 {
        font-size: 48px;
        margin: 0;
        letter-spacing: 2px;
    }

    /* underline only surname vibe */
    .underline {
        width: 120px;
        height: 3px;
        background: #d6b48a; /* soft gold underline */
        margin: 8px auto 10px auto;
    }

    .contact {
        font-size: 14px;
        margin-top: 10px;
    }

    /* MAIN LAYOUT */
    .container {
        display: grid;
        grid-template-columns: 2fr 1fr; /* left main + right column */
        gap: 25px;
        padding: 30px;
        max-width: 1100px;
        margin: auto;
    }

    h2 {
        color: #7a5c3e;
        border-bottom: 1px solid #cdb9a3;
        padding-bottom: 5px;
        margin-top: 25px;
    }

    .card {
        background: #fffaf5;
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        margin-bottom: 20px;
    }

    /* RIGHT COLUMN */
    .side {
        display: flex;
        flex-direction: column;
    }

    ul {
        padding-left: 18px;
        line-height: 1.6;
    }

    iframe {
        width: 100%;
        height: 200px;
        border: none;
        border-radius: 6px;
    }

</style>
</head>

<body>

<div class="header">
    <h1>NANDIPHA GALADA</h1>
    <div class="underline"></div>

    <div class="contact">
        📞 071 088 7644 | ✉️ 221225366@mycput.ac.za | 💻 GitHub | 🔗 LinkedIn
    </div>
</div>

<div class="container">

    <!-- LEFT SIDE (MAIN CONTENT) -->
    <div>

        <div class="card">
            <h2>🪶 Career Objective</h2>
            <p>
                Motivated IT student with strong problem-solving, communication, and teamwork skills,
                supported by experience in customer service. Reliable, organized, and proactive with
                a growing focus on web design and development.
            </p>
        </div>

        <div class="card">
            <h2>🎓 Education</h2>

            <p><b>Diploma in ICT: Applications Development</b><br>
            Cape Peninsula University of Technology (CPUT)<br>
            2021 – Present (3rd Year)</p>

            <p><b>National Senior Certificate</b><br>
            Focus College, Wynberg<br>
            2015 – 2020</p>
        </div>

        <div class="card">
            <h2>💼 Experience</h2>

            <p><b>Customer Service Agent</b> – Teleperformance</p>
            <ul>
                <li>Assisted customers via chat, email, phone</li>
                <li>Maintained professionalism and clarity</li>
            </ul>

            <p><b>UniResApp Project</b> – CPUT</p>
            <ul>
                <li>Built web-based residence system</li>
                <li>Worked on coding, testing, improvements</li>
                <li>Improved teamwork & system design skills</li>
            </ul>
        </div>

    </div>

    <!-- RIGHT SIDE (COLUMN BLOCK) -->
    <div class="side">

        <div class="card">
            <h2>🧠 Skills</h2>
            <ul>
                <li>HTML, CSS, JavaScript</li>
                <li>Web Design</li>
                <li>Business Analysis</li>
                <li>Communication</li>
                <li>Team Leadership</li>
            </ul>
        </div>

        <div class="card">
            <h2>📌 References</h2>

            <p><b>Nonkululeko Biyana</b><br>
            Teleperformance<br>
            066 204 9632</p>

            <p><b>Mthuthuzeli Mrubata</b><br>
            Methodist Church<br>
            075 145 9135</p>
        </div>

        <div class="card">
            <h2>🎥 Mock Video</h2>
            <iframe src="https://drive.google.com/file/d/1_c5Jb5xEPc0yFJUKy8T6w3678DoOFPua/preview"></iframe>
        </div>

    </div>

</div>

</body>
</html>
