# Kashi: The Unexplored City

## SEO-Friendly Frontend Website (HTML, CSS, JavaScript Only)

**Project Level:** BCA\
**Technology Stack:** HTML5, CSS3, Vanilla JavaScript\
**Architecture:** Static Website (No Framework, No Backend, No Database)

------------------------------------------------------------------------

# 1. Project Overview

This project is a fully static, SEO-optimized website titled:

**"Kashi: The Unexplored City"**

The goal is to highlight lesser-known spiritual places, hidden ghats,
and unexplored cultural dimensions of Varanasi using clean semantic HTML
and optimized frontend design.

------------------------------------------------------------------------

# 2. Project Folder Structure

    kashi-unexplored/
    │
    ├── index.html
    ├── styles.css
    ├── script.js
    ├── sitemap.xml
    └── assets/
        └── images/

------------------------------------------------------------------------

# 3. index.html

``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Kashi: The Unexplored City | Hidden Spiritual Places of Varanasi</title>

    <meta name="description" content="Explore hidden spiritual places of Kashi including lesser-known temples, unexplored ghats, and sacred sites beyond mainstream tourism.">
    <meta name="keywords" content="Kashi unexplored, Hidden temples Varanasi, Lesser known ghats, Spiritual tourism India">
    <meta name="author" content="Your Name">

    <meta property="og:title" content="Kashi: The Unexplored City">
    <meta property="og:description" content="Discover unexplored spiritual gems of Varanasi.">
    <meta property="og:type" content="website">

    <link rel="stylesheet" href="styles.css">
</head>

<body>

<header>
    <h1>Kashi: The Unexplored City</h1>
    <p>Discover the Spiritual Depth Beyond the Famous Ghats</p>
</header>

<nav>
    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#temples">Hidden Temples</a></li>
        <li><a href="#ghats">Unexplored Ghats</a></li>
        <li><a href="#research">Research</a></li>
    </ul>
</nav>

<section id="about">
    <h2>About Kashi</h2>
    <p>
        Kashi is one of the oldest living cities in the world. 
        While most visitors focus on major temples, the deeper spiritual experience
        lies within its silent shrines, hidden ghats, and sacred geography.
    </p>
</section>

<section id="temples">
    <h2>Hidden Spiritual Temples</h2>

    <article>
        <h3>Sankata Devi Temple</h3>
        <p>A powerful local Shakti temple dedicated to relief from hardships.</p>
    </article>

    <article>
        <h3>Kilkari Bhairav Temple</h3>
        <p>Dedicated to Kala Bhairava, known for intense ritual traditions.</p>
    </article>

    <article>
        <h3>Ratneshwar Mahadev Temple</h3>
        <p>The leaning temple of Varanasi, symbolizing devotion and impermanence.</p>
    </article>
</section>

<section id="ghats">
    <h2>Lesser Known Ghats</h2>

    <article>
        <h3>Rana Mahal Ghat</h3>
        <p>Architecturally unique and peaceful during sunrise.</p>
    </article>

    <article>
        <h3>Chet Singh Ghat</h3>
        <p>Historically significant and relatively less crowded.</p>
    </article>

    <article>
        <h3>Raj Ghat</h3>
        <p>Located near the Varuna-Ganga confluence, spiritually symbolic.</p>
    </article>
</section>

<section id="research">
    <h2>Spiritual Research Perspective</h2>
    <p>
        Kashi represents sacred urban planning where temples form symbolic networks,
        ghats serve as ritual nodes, and narrow alleys preserve living traditions.
    </p>
</section>

<footer>
    <p>© 2026 Kashi: The Unexplored City | BCA Project</p>
</footer>

<script src="script.js"></script>
</body>
</html>
```

------------------------------------------------------------------------

# 4. styles.css

``` css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f8f5f0;
    color: #333;
    line-height: 1.6;
}

header {
    background: #5e3023;
    color: white;
    padding: 40px 20px;
    text-align: center;
}

nav {
    background: #895737;
    padding: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-weight: bold;
}

section {
    padding: 40px 20px;
    max-width: 900px;
    margin: auto;
}

h2 {
    border-bottom: 2px solid #895737;
    padding-bottom: 5px;
}

footer {
    background: #5e3023;
    color: white;
    text-align: center;
    padding: 20px;
}
```

------------------------------------------------------------------------

# 5. script.js

``` javascript
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener("click", function(e) {
        e.preventDefault();
        document.querySelector(this.getAttribute("href"))
            .scrollIntoView({ behavior: "smooth" });
    });
});
```

------------------------------------------------------------------------

# 6. sitemap.xml

``` xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
   <url>
      <loc>https://yourdomain.com/</loc>
      <priority>1.00</priority>
   </url>
</urlset>
```

------------------------------------------------------------------------

# 7. SEO Highlights

-   Semantic HTML5 structure
-   Meta description & keywords
-   Open Graph tags
-   Mobile responsive viewport
-   Lightweight & fast loading
-   Sitemap ready for search engines

------------------------------------------------------------------------

**End of Document**
