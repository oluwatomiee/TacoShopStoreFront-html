# Tomi-html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="author" content="Tomi Owolabi">
    <meta
      name="description"
      content="This is going to be a webpage detailing all my adventures in web programming">
    <link
      rel="icons"
      href="img/html5.png" type="image/x-icon">
    <title>My First Web Page</title>
    <link rel="stylesheet" href="main.css">
  </head>
  <body>
    <header>
    <h1>My First WebPage</h1>
    <hr>
    <nav>
      <ul>
        <li><a href="#TestingOne">Who Is Tomi</a></li>
        <li><a href="#TestingTwo">Random Facts About Tomi</a></li>
        <li><a href="#Lists">Tomi's Favourite Things</a></li>
        <li><a href="#Links">About Tomi</a></li>
        <li><a href="#Table">School Schedule</a></li>
      </ul>
    </nav>
  </header>
    <hr>
  <main>
    <section id="TestingOne">
      <h2>Welcome To Tomi's First HTML Paragraph</h2>
      <figure>
        <figcaption>A Workstation</figcaption>
      </figure>
      <img
        src="img/Workstation.jpg"
        alt="Workstation LOGO"
        width="580"
        height="400">
        
      <p>
        Hi!!!! My name is Tomi, this is going to be a short paragraph, i am learning html from
        <em>Freecodecamp for free!!!!!</em>
      </p>
      <h3>Second Heading</h3>
      <p>
        Holla!!! &nbsp;&nbsp;&nbsp; this is going top be another short paragraph
        for testing what i learned on Freecodecamp:
      </p>
      <p>I will do the following things:</p>
      <ul>
        <li>Finish, this you tube video on freecodecamp</li>

        <li>Start another course on CSS</li>
        <li>Start a <strong>Project</strong></li>
      </ul>
    </section>

    <hr>

    <section id="TestingTwo">
      <h2>Second Situation for Testing Purposes</h2>
      <img src="img/Minimalist.jpg" alt="Home" width="400" height="300">
      <p>
        This is going to be a second short paragraph,
        <em>i am learning html from free studio camp for free!!!!!</em>
      </p>
      <h3>What are my Plans after this Process?</h3>
      <p>
        Holla!!!!! &nbsp;this section will document what i will do
        after learning html on <strong>Freecodecamp:</strong>
      </p>
      &nbsp; Learn CSS <br>
      &nbsp; Learn javascript fundamentals <br>
      &nbsp; Create a portfolio <br>
      &nbsp; Apply to jobs
      <hr>
      <!--Add More content to this code blocks-->
      <p>At the moment i live at:</p>
      <address>
        102b, Francis road,<br>
        SA8 9NW, West Glarmorgan <br>
        Swansea, United Kingdom
      </address>
    </section>

    <hr>

    <section id="Lists">
      <h2>Lists Creation</h2>
      <p>
        This section is going to talk about list creation, there are three types
        of lists:
      </p>
      <ol>
        <li>Ordered lists.</li>
        <li>Unordered lists.</li>
        <li>Descriptive lists.</li>
      </ol>

      <p>
        The above list is an example of ordrerd list, while the listt with the
        bullet points, was an example of unordered lists; below is an example of
        Descriptive list:
      </p>

      <dl>
        <dt>Descriptive Term</dt>
        <dd>DT stands for descriptive term, or tittle, so to speak</dd>

        <dt>Descriptive Details</dt>
        <dd>
          DD stands for the deails or explanation of what you are describing.
        </dd>
      </dl>
    </section>

    <hr>
    <section id="Links">
      <h2>Anchor Reference</h2>
      <p>
        If you need any help anchoring webpages to each other via links, you can
        use the anchor tag,
        <br>
        Example;
      </p>

      <a href="https://developer.mozilla.org/">
        MDN link to Resources for Developers</a>
      
    </section>

    <section id="Table">
       <h2>Creation Of Tables</h2>
       <p>Lets create a table, showing my school schedule below:</p>
       <table>

    <caption>My School Timetable</caption>
        <thead>
        <tr>
            <th scope="col">Days of the Week</th>
            <th scope="col"><time datetime="09:00">9am</time>-<time datetime="12:00">12pm</time></th>
            <th scope="col"><time datetime="12:00">12pm</time>-<time datetime="17:00">5pm</time></th>
            <th scope="col"><time datetime="17:00">5pm</time>-<time datetime="21:00">9pm</time></th>
        </tr>
        </thead>

<tbody>
        <tr>
            <td>Monday</td>
            <td>Network Security</td>
            <td>Strategy</td> 
            <td>Leadership Seminar</td>
            
        </tr>

        <tr>
            <td>Tuesday</td>
            <td>Network Security</td>
            <td>No Class</td>
            <td>No Class</td>
        </tr>

        <tr>
            <td>Wednesday</td>
            <td>No School</td>
            <td>No School</td>
            <td>No Class</td>
        </tr>
    
        <tr>
            <td>Thursday</td>
            <td>Research Methodology lectures</td>
            <td>No class</td>
            <td>Research Methodology Seminar</td>
        </tr>
       

         <tr>
            <td>Friday</td>
            <td>Leadership lectures</td>
            <td>No class</td>
            <td>Network Security Labs</td>
        </tr>

    </tbody>
       </table>
      </section>
    </main>

    <hr>
    <footer>
    &lt;&lt;&lt;&lt;&lt;&copy;<a href="about.html">Tomisin Ajiboye</a
    >&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;
    <hr>
    <a href="#">Back to Top</a>
  </footer>
  </body>
</html>
