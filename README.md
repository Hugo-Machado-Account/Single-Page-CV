# CV HTML/CSS

## HTML

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Hugo Machado</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <main>
        <header>
            <h1>Hugo Machado</h1>
            <hr>
            <h2 class="job-title">Junior Frontend Developer</h2>
            <address class="address">
                177 rue de la paix<br>
                Paris, 75000<br>
                06 66 66 66 66<br>
                <a href="mailto:hugo.machado1@ecoles-epsi.net">hugo.machado1@ecoles-epsi.net</a>
            </address>
        </header>
        <section>
            <h3 class="section-title green">Skills</h3>
            <p class="skills">HTML, CSS, JavaScript, Accessibility, Figma to Design, Responsive Web Design, Technical Writing, Presentation</p>
        </section>
        <section>
            <h3 class="section-title green">Education</h3>
            <div class="edu-block">
                <span class="edu-title blue">School Name, Location - Degree</span><br>
                <span class="edu-date">Month 20xx to Month 20xx</span>
                <ul>
                    <li>List of exciting things you did at university</li>
                </ul>
            </div>
        </section>
        <section>
            <h3 class="section-title green">Experience</h3>
            <div class="exp-block">
                <span class="exp-title blue">Company Name, Location - Job Title</span><br>
                <span class="exp-date">Month 20xx to Month 20xx</span>
                <ul>
                    <li>List of achievements</li>
                    <li>List of achievements</li>
                    <li>List of achievements</li>
                </ul>
                <span class="exp-skills">Skills: List of skills used or gained at this company</span>
            </div>
            <div class="exp-block">
                <span class="exp-title blue">Company Name, Location - Job Title</span><br>
                <span class="exp-date">Month 20xx to Month 20xx</span>
                <ul>
                    <li>List of achievements</li>
                    <li>List of achievements</li>
                    <li>List of achievements</li>
                </ul>
                <span class="exp-skills">Skills: List of skills used or gained at this company</span>
            </div>
        </section>
        <section>
            <h3 class="section-title green">Across the Internet</h3>
            <p>Ajoutez vos liens LinkedIn, GitHub, etc.</p>
        </section>
    </main>
</body>
</html>
```

## CSS

```css
body {
  max-width: 700px;
  margin: 30px auto;
  border: 2px solid #222;
  padding: 40px 40px 30px 40px;
  font-family: Arial, sans-serif;
  background: #fff;
  color: #222;
}

header h1 {
  font-size: 2.2em;
  font-weight: 400;
  margin-bottom: 0.2em;
}

header hr {
  border: none;
  border-top: 3px solid #222;
  margin: 0.5em 0 1.2em 0;
}

.job-title {
  color: #2ecc40;
  font-weight: 400;
  margin-top: 0;
  margin-bottom: 1em;
  font-size: 1.2em;
}

.address {
  margin-bottom: 1.5em;
  font-style: normal;
}

.section-title {
  margin-bottom: 0.2em;
  margin-top: 1.2em;
  font-size: 1.1em;
  font-weight: 400;
}

.green {
  color: #2ecc40;
}

.blue {
  color: #0074d9;
  font-weight: bold;
}

.skills {
  margin-bottom: 1.2em;
}

.edu-block, .exp-block {
  margin-bottom: 1.2em;
}

ul {
  margin-top: 0.2em;
  margin-bottom: 0.8em;
  padding-left: 1.2em;
}

.exp-skills {
  display: block;
  margin-top: 0.2em;
}

a {
  color: #0074d9;
  text-decoration: none;
}
```