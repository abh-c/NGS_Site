# Next Gen Stem

html code for thenextgenstem.net

## TO CONTRIBUTORS:

Every html page should be surrounded by `<html>` tags and begin with a declaration of doctype (html5):

```html
<!DOCTYPE html>
<html lang="en-US">
    
    # The rest of the code # 
    
</html>
```

Every html page should have an appropriate `<head>` section with important information in it:

```html
<head>
    <meta charset="utf-8" />
    <meta name="keywords" content="HTML, CSS, JavaScript, Java, Python" />
    <meta name="description" content="Free programming tutorials" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="../style.css" />
    <title>Next Gen Stem</title>
</head>
```

Between the body tags, you should have the header, navigation panel, next and previous buttons and footer. 

Remember to add the appropriate links to the previous and next elements.

```html
<body>
    <nav class="nav-top">
        <ul class="nav-top-ul">
            <li><b><a href="../index.html" class="nav-top-link">Home</a></b></li>
            <li><b><a href="../learntocode.html" class="nav-top-link">Learn to Code</a></b></li>
            <li><b><a href="../about.html" class="nav-top-link">About</a></b></li>
        </ul>
    </nav>
  
  
  # YOUR LESSON CODE GOES HERE #
  
  <!-- Add the appropriate links to each <a> tag -->
  <section class="next-previous-wrapper">
        <a href="" class="previous">&lt; Previous</a>
        <a href="" class="next">Next &gt;</a>
  </section>
  
  <nav class="course-nav">
        <ul>
            <li><a href="js1.html">Introduction</a></li>
            <li><a href="js2.html">Lesson 1</a></li>
            <li><a href="js3.html">Lesson 2</a></li>
            <li><a href="js4.html">Lesson 3</a></li>
            <li><a href="js5.html">Lesson 4</a></li>
            <li><a href="js6.html">Lesson 5</a></li>
            <li><a href="js7.html">Lesson 6</a></li>
            <li><a href="js8.html">Lesson 7</a></li>
            <li><a href="js9.html">Lesson 8</a></li>
            <li><a href="js10.html">Lesson 9</a></li>
            <li><a href="js11.html">Lesson 10</a></li>
        </ul>
    </nav>

    <footer>
        <p>
            NEXT GEN STEM <br> CONNECTICUT, USA
        </p>
        <img src="../images/Mail-Icon-White-on-Grey.jpg" style="width:65px; height:65px">
    </footer>
</body>
```

Use the `section-1` class for every section that you insert. Paragraphs `<p>` and ordered lists `<ol>` are supported,
as well as headings `<h1>` and `<h2>`. Example:

```html
<section class="section-1">
        <h1>JavaScript</h1>
        <p>
            JavaScript (JS) is an incredibly widespread and popular
            programming language that is present in most of the
            websites you have ever visited. JS allows for greater
            interactivity with the user of a website, including things
            we take for granted in websites today, like playing audio,
            playing video, animating certain elements, and even drop-down
            menus! The language is easy to get started with and is
            used in both front and back-end development professionally.
        </p>
</section>
```

You can add inline code with the `<code>` tag inside a `<p>` pararaph inside a class `section-1` section.

Horizontal division lines can be added with `<hr class="hr-1">`.

Look at the `course-landing-page-template.html` file for more examples.

Videos can also be inserted using the `<iframe>` tag. Get from youtube with `share --> embed`. See `video-lesson-template.html`
for more details.

```html
<section class="section-1">
        <!-- Copy and paste this buy going to the respective YouTube lesson and clicking "share"-> "embed" -->
        <iframe width="560" height="315" src="https://www.youtube.com/embed/mD3GmqjmqXQ" frameborder="0"
            allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</section>
```

Code blocks can be inserted with the section class `code`, as seen below. Copy paste each line of code into separate `<code>` tags and preserve the spacing.
Code lines can be highlighted using the code class `hl`.

```html
<section class="code">
        <pre>
            <code>let playerScore = 0; </code>
            <code>let opponentScore = 0; </code>
            <p>...</p>
            <code class="hl">function drawScore() { </code>
            <code class="hl">   context.font = "64px Courier New"; </code>
            <code class="hl">   context.textAlign = "center"; </code>
            <code class="hl">   context.fillStyle = "#e0e0e0"; </code>
            <code class="hl">   context.fillText(`${playerScore} ${opponentScore}`, canvas.width / 2, 60);</code>
            <code class="hl">}</code>
        </pre>
</section>
```

Images can be inserted with the `<img>` tag.



[Link to website in progress](https://abh-c.github.io/NGS_Site/)

[Link to template](https://abh-c.github.io/NGS_Site/templates/course-landing-page-template.html)

[Link to video template](https://abh-c.github.io/NGS_Site/templates/video-course-template.html)
