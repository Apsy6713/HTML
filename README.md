From Beginner to Advanced — Apsy's Tech Edition

HTML is one of the most important technologies used to create websites. If you want to build professional websites, understand web development, create your own technology platform, or eventually develop powerful online tools, learning HTML is an excellent starting point.

Since you're building Apsy's Tech, this guide will help you understand HTML from the basics to more advanced concepts, with examples you can practise in Notepad and use in your website.

6
📚 What you'll learn

A structured roadmap to HTML, from your first tag to building complete webpages.

Introduction to HTML and how websites work
HTML document structure, tags, elements and attributes
Headings, paragraphs, text formatting and comments
Links, images, lists and tables
Forms, input fields, checkboxes, radio buttons and buttons
Audio, video, semantic elements and page layouts
HTML5, accessibility, metadata and search engine basics
Advanced HTML concepts and useful browser features
Complete practical projects and exercises
1. What is HTML?

HTML stands for HyperText Markup Language.

It is the standard markup language used to structure content on webpages.

HTML tells a web browser what different pieces of content are, such as:

A heading.

A paragraph.

An image.

A hyperlink.

A table.

A form.

A video.

A navigation menu.

HTML is a markup language, not a programming language in the traditional sense. It describes the structure and meaning of content rather than implementing general-purpose programming logic.

Example
<h1>Welcome to Apsy's Tech</h1>
<p>Your place for gaming and technology.</p>

In this example:

<h1> represents a main heading.

<p> represents a paragraph.

The browser uses these elements to display the content appropriately.

2. The three major technologies of websites
HTML — Structure

Defines the content and organization of a webpage.

Example: headings, images, navigation and forms.

CSS — Presentation

Controls how the webpage looks.

Example: colors, fonts, spacing, animations and responsive layouts.

JavaScript — Behavior

Adds interactive features and dynamic functionality.

Example: interactive menus, calculators, live updates and form validation.

Think of a website as a building:

HTML is the structure of the building.

CSS is its paint, decoration and appearance.

JavaScript is the mechanism that makes things work interactively.

For example, on Apsy's Tech, HTML can create a GPU information card, CSS can make it look futuristic, and JavaScript can let visitors filter GPUs or calculate PC configurations.

3. How HTML works

When you open a website in a browser, the browser reads the HTML document and builds a structured representation of its elements, commonly called the Document Object Model (DOM). It then uses that structure, along with CSS, JavaScript and other resources, to display and operate the page. 
HTML Living Standard
+1

1. HTML file

Contains the webpage's content and structure.

2. Browser parses HTML

Reads the elements and organizes them into a document tree.

3. Webpage appears

The browser renders the page using its structure, styling and other resources.

4. What is an HTML tag?

A tag is a piece of markup written inside angle brackets.

Examples:

<h1>
<p>
<img>
<a>

Most HTML elements have an opening tag and a closing tag.

<p>This is a paragraph.</p>

Here:

<p> is the opening tag.

This is a paragraph. is the content.

</p> is the closing tag.

The complete structure is called an HTML element.

Some elements are void elements and do not have closing tags, such as <img>, <br>, <hr> and <input>.

5. HTML document structure

Every beginner should learn this basic document structure first.

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <title>Apsy's Tech</title>
</head>

<body>

    <h1>Welcome to Apsy's Tech</h1>
    <p>Your place for gaming and technology.</p>

</body>
</html>

This is a standard modern HTML document structure. 
HTML Living Standard
+1

Explanation of every important part

Code

	

Meaning




<!DOCTYPE html>

	

Declares the document as modern HTML.




<html>

	

The root element of the page.




lang="en"

	

Identifies English as the document's language.




<head>

	

Contains metadata and information about the document.




<meta charset="UTF-8">

	

Specifies the character encoding.




<meta name="viewport">

	

Helps the page adapt to different screen sizes.




<title>

	

Sets the document title shown in the browser tab.




<body>

	

Contains the main visible webpage content.

The <head> is not the same as the visible page header. The visible header is usually created with <header> inside the body.

6. HTML syntax rules

Follow these rules when writing HTML.

Write tags inside angle brackets.

Close elements that require closing tags.

Nest elements correctly.

Put attributes inside the opening tag.

Use quotation marks around attribute values.

Use meaningful element names for their intended purpose.

Keep your code organized and easy to read.

Correct nesting
<p>This is <strong>important</strong> text.</p>
Incorrect nesting
<p>This is <strong>important</p></strong>

The elements must be nested properly, rather than overlapping. 
HTML Living Standard
+1

7. HTML headings

HTML provides six heading levels, from <h1> to <h6>.

<h1>Gaming</h1>
<h2>PC Gaming</h2>
<h3>Gaming Components</h3>
<h4>Graphics Cards</h4>
<h5>GPU Memory</h5>
<h6>Technical Details</h6>
Heading preview
H1 — Gaming
H2 — PC Gaming
H3 — Gaming Components
H4 — Graphics Cards

H5 — GPU Memory

H6 — Technical Details

Use headings to organize information into a logical hierarchy, not simply to make text bigger or smaller.

8. HTML paragraphs and line breaks
Paragraph
<p>HTML is used to structure webpages.</p>
<p>CSS is used to style webpages.</p>
Line break
<p>
    Welcome to Apsy's Tech.<br>
    Explore gaming and PC building.
</p>

<br> creates a line break. It is a void element.

Horizontal rule
<h2>Gaming</h2>
<hr>
<p>Explore gaming information.</p>

<hr> represents a thematic break between content.

9. HTML text formatting

Tag

	

Purpose




<strong>

	

Indicates strong importance.




<em>

	

Adds emphasis.




<b>

	

Draws attention without necessarily indicating importance.




<i>

	

Represents text in an alternate voice or mood, among other uses.




<u>

	

Marks text with a non-textual annotation.




<mark>

	

Highlights text.




<small>

	

Represents side comments or small print.




<del>

	

Represents deleted content.




<ins>

	

Represents inserted content.




<sub>

	

Represents subscript text.




<sup>

	

Represents superscript text.




<code>

	

Represents a fragment of computer code.




<pre>

	

Represents preformatted text.

Example:

<p><strong>Important:</strong> Save your work.</p>

<p><em>Gaming is more than entertainment.</em></p>

<p>GPU stands for
   <abbr title="Graphics Processing Unit">GPU</abbr>.
</p>

<p>Water: H<sub>2</sub>O</p>

<p>Mathematics: x<sup>2</sup></p>

<p><mark>New technology update</mark></p>

<p><del>Old price: ₹50,000</del></p>

<p><ins>New price: ₹45,000</ins></p>
10. HTML comments

Comments allow you to write notes in your HTML source code.

<!-- This is a comment -->

<h1>Welcome to Apsy's Tech</h1>

<!-- Gaming section starts here -->
<section>
    <h2>Gaming</h2>
    <p>Explore the world of gaming.</p>
</section>

Comments are not displayed as ordinary webpage content, but visitors may still be able to inspect the page source. Do not put passwords or secrets in comments.

11. HTML attributes

Attributes provide additional information about an element or control how it behaves.

Example:

<a href="https://www.example.com">
    Visit Website
</a>

In this example, href is an attribute that specifies the link destination.

Common HTML attributes

Attribute

	

Purpose




id

	

Gives an element a unique identifier within the document.




class

	

Assigns one or more class names to an element.




style

	

Applies inline CSS styling.




title

	

Provides advisory information, often shown as a tooltip.




href

	

Specifies a link destination.




src

	

Specifies the source of an embedded resource, such as an image.




alt

	

Provides alternative text for an image.




width

	

Specifies a width where supported.




height

	

Specifies a height where supported.




target

	

Specifies where a link should open.




name

	

Names a form control or other element-specific value.




value

	

Specifies a value for a form control.




type

	

Specifies a type, such as an input type.




placeholder

	

Provides a short hint in an input.




required

	

Indicates that a form control must be completed.




disabled

	

Disables a supported control.




checked

	

Indicates a checked checkbox or radio button by default.

The id and class attributes
<h1 id="main-heading">Apsy's Tech</h1>

<p class="intro">Welcome to our website.</p>

<p class="intro">Explore gaming and technology.</p>

An id identifies a particular element, while a class can be shared by multiple elements. CSS and JavaScript can use these attributes to select elements.

12. HTML hyperlinks

The <a> element creates hyperlinks.

Link to another webpage
<a href="gaming.html">Gaming</a>
Link to an external website
<a href="https://www.wikipedia.org/">
    Visit Wikipedia
</a>
Open a link in a new tab
<a href="https://www.wikipedia.org/"
   target="_blank"
   rel="noopener">
    Open Wikipedia
</a>
Link to an email address
<a href="mailto:example@example.com">
    Contact Us
</a>
Link to a section on the same page
<a href="#components">Go to Components</a>

<h2 id="components">PC Components</h2>

Important: The value after # must match the target element's id.

13. HTML images

The <img> element embeds an image in a webpage.

<img src="gpu.jpg"
     alt="A graphics card"
     width="400">

Explanation:

src specifies the image file or URL.

alt provides a text alternative.

width specifies the rendered width.

Images can be JPEG, PNG, WebP, SVG, GIF and other supported formats.

Example for Apsy's Tech
<h2>Graphics Cards</h2>

<img src="gpu.jpg"
     alt="A modern graphics card">

<p>Graphics cards process images and graphics
   for games and other applications.</p>

If an image is purely decorative, an empty alt="" can be appropriate. Meaningful images should have useful alternative text. 
MDN
+1

14. HTML lists

HTML provides ordered lists, unordered lists and description lists.

Unordered list

Uses <ul> and <li>.

<h2>PC Components</h2>

<ul>
    <li>CPU</li>
    <li>GPU</li>
    <li>RAM</li>
    <li>SSD</li>
    <li>Motherboard</li>
</ul>
Ordered list

Uses <ol> and <li>.

<h2>How to Build a PC</h2>

<ol>
    <li>Select your components.</li>
    <li>Install the CPU.</li>
    <li>Install the RAM.</li>
    <li>Connect the storage.</li>
    <li>Test the system.</li>
</ol>
Description list

Uses <dl>, <dt> and <dd>.

<dl>
    <dt>CPU</dt>
    <dd>The central processing unit.</dd>

    <dt>GPU</dt>
    <dd>The graphics processing unit.</dd>
</dl>
15. HTML tables

Tables are useful for displaying structured data in rows and columns.

Example: a PC components comparison table.

<table>
    <caption>PC Components</caption>

    <thead>
        <tr>
            <th scope="col">Component</th>
            <th scope="col">Purpose</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>CPU</td>
            <td>Processes instructions.</td>
        </tr>

        <tr>
            <td>GPU</td>
            <td>Processes graphics.</td>
        </tr>

        <tr>
            <td>RAM</td>
            <td>Stores data temporarily for active tasks.</td>
        </tr>
    </tbody>
</table>

Element

	

Purpose




<table>

	

Creates a table.




<caption>

	

Gives the table a title or description.




<thead>

	

Groups the header rows.




<tbody>

	

Groups the main data rows.




<tfoot>

	

Groups footer rows, if needed.




<tr>

	

Creates a table row.




<th>

	

Creates a header cell.




<td>

	

Creates a data cell.

Use tables for data, not as your main method of arranging an entire webpage. Meaningful row and column headings help people understand the data, including those using assistive technology. 
MDN
+1

16. HTML forms

Forms allow websites to collect information from users. They can contain text fields, checkboxes, radio buttons, dropdowns, buttons and more. 
MDN
+1

16.1 Text input
<form>
    <label for="username">Enter your name:</label>
    <input type="text" id="username" name="username">
</form>
16.2 Email input
<label for="email">Email:</label>
<input type="email" id="email" name="email">
16.3 Password input
<label for="password">Password:</label>
<input type="password" id="password" name="password">

A password input visually masks the entered characters. It does not, by itself, securely store or transmit passwords.

16.4 Checkbox

A checkbox lets users select or deselect an option.

<form>
    <p>Select your interests:</p>

    <input type="checkbox" id="gaming" name="interest"
           value="gaming">
    <label for="gaming">Gaming</label>

    <br>

    <input type="checkbox" id="technology" name="interest"
           value="technology">
    <label for="technology">Technology</label>

    <br>

    <input type="checkbox" id="pcbuilding" name="interest"
           value="pc-building">
    <label for="pcbuilding">PC Building</label>
</form>
16.5 Radio buttons

Radio buttons allow the user to select one option from a group when they share the same name.

<form>
    <p>Choose your preferred platform:</p>

    <input type="radio" id="pc" name="platform" value="pc">
    <label for="pc">PC</label>

    <input type="radio" id="laptop" name="platform" value="laptop">
    <label for="laptop">Laptop</label>
</form>
16.6 Dropdown menu
<label for="gpu">Choose a GPU brand:</label>

<select id="gpu" name="gpu">
    <option value="">Select a brand</option>
    <option value="nvidia">NVIDIA</option>
    <option value="amd">AMD</option>
    <option value="intel">Intel</option>
</select>
16.7 Textarea
<label for="message">Your message:</label>

<textarea id="message" name="message"
          rows="5" cols="30"></textarea>
16.8 Submit button
<button type="submit">Submit</button>
16.9 Complete HTML form project

This combines several form elements into one example.

Live form example
Apsy's Tech — Visitor Form

Try filling out this demonstration form. It previews the kinds of controls HTML can provide.

Full name
Email address
Preferred platform
PC
Laptop
Console
Mobile
Interests
Gaming
PC Building
Technology
Programming
Message
Preview Submission

The form above is an interactive demonstration. The following code is the corresponding HTML pattern to study and use in your own webpage.

<form action="/submit" method="post">

    <label for="name">Full name:</label>
    <input type="text" id="name" name="name" required>

    <br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <br><br>

    <p>Preferred platform:</p>

    <input type="radio" id="pc" name="platform" value="PC">
    <label for="pc">PC</label>

    <input type="radio" id="laptop" name="platform" value="Laptop">
    <label for="laptop">Laptop</label>

    <br><br>

    <p>Interests:</p>

    <input type="checkbox" id="gaming" name="interests"
           value="Gaming">
    <label for="gaming">Gaming</label>

    <input type="checkbox" id="tech" name="interests"
           value="Technology">
    <label for="tech">Technology</label>

    <br><br>

    <label for="message">Message:</label>
    <textarea id="message" name="message"></textarea>

    <br><br>

    <button type="submit">Submit</button>

</form>

Important: The /submit address is only an example. A real form needs a suitable server endpoint or another configured form-processing service to receive and process submissions. HTML alone does not create a database or send data to an arbitrary destination.

17. Semantic HTML

Semantic HTML means using elements according to their intended meaning.

For example, use <nav> for navigation, <main> for the main content and <footer> for footer information. Semantic elements help browsers, developers and assistive technologies understand a page's structure. 
MDN
+1

Important semantic elements

Element

	

Meaning




<header>

	

Introductory content for a page or section.




<nav>

	

A section containing navigation links.




<main>

	

The dominant content of the document.




<section>

	

A thematic section of content.




<article>

	

Self-contained content that can stand on its own.




<aside>

	

Content indirectly related to the main content.




<footer>

	

Footer information for a page or section.




<figure>

	

Self-contained content such as an illustration or diagram.




<figcaption>

	

A caption for a figure.




<address>

	

Contact information for a page or article.




<details>

	

A disclosure widget that users can open and close.




<summary>

	

A visible summary or label for a <details> element.

Example: Semantic layout for Apsy's Tech
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">
    <title>Apsy's Tech</title>
</head>

<body>

    <header>
        <h1>Apsy's Tech</h1>
        <p>Gaming | Technology | PC Building</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="gaming.html">Gaming</a>
        <a href="components.html">Components</a>
        <a href="configurator.html">Configurator</a>
        <a href="tech.html">Tech</a>
    </nav>

    <main>

        <section>
            <h2>Welcome</h2>
            <p>Explore gaming and technology.</p>
        </section>

        <section>
            <h2>PC Components</h2>

            <article>
                <h3>Processors</h3>
                <p>Learn about CPUs and their features.</p>
            </article>

            <article>
                <h3>Graphics Cards</h3>
                <p>Explore GPU specifications and performance.</p>
            </article>
        </section>

        <aside>
            <h2>Did You Know?</h2>
            <p>Different components perform different roles
               inside a computer.</p>
        </aside>

    </main>

    <footer>
        <p>© 2026 Apsy's Tech</p>
    </footer>

</body>
</html>
18. HTML audio and video

HTML has built-in elements for embedding audio and video.

Audio
<audio controls>
    <source src="music.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>
Video
<video controls width="640">
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video element.
</video>
Useful media attributes

Attribute

	

Meaning




controls

	

Displays playback controls.




autoplay

	

Requests automatic playback, subject to browser restrictions.




muted

	

Starts the media muted.




loop

	

Repeats playback.




poster

	

Specifies a preview image for a video.




preload

	

Hints how the browser should prepare the media.

For accessibility, consider providing captions for videos and text alternatives or transcripts for relevant audio content.

19. HTML iframe

An <iframe> embeds another browsing context inside a webpage.

Example:

<iframe
    src="https://www.example.com"
    title="Example website"
    width="600"
    height="400">
</iframe>

An iframe can be used for certain maps, videos, documents and other embeddable content.

Not every website allows itself to be embedded in an iframe. Some services require you to use their official embed code.

20. HTML buttons

A button is an interactive control.

<button type="button">Click Me</button>

The type attribute is important when buttons are inside forms.

Button type

	

Purpose




button

	

A general-purpose button.




submit

	

Submits its associated form.




reset

	

Resets form controls to their initial values.

A button does not automatically perform an arbitrary action just because it exists. For actions such as opening a custom menu or calculating a PC build, you generally need JavaScript or another appropriate mechanism.

21. HTML metadata

Metadata describes information about the document.

It is commonly placed inside the <head> element.

<head>
    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="Explore gaming, technology,
                   PC components and PC building.">

    <title>Apsy's Tech | Gaming and Technology</title>
</head>
Common metadata

Character encoding.

Viewport settings.

Document title.

Description of the page.

Links to stylesheets and icons.

Information used by browsers and other tools.

A good page title and meaningful content can help people and search engines understand the subject of your webpage. Metadata alone does not guarantee search rankings.

22. HTML entities

HTML entities let you represent certain characters in markup.

Entity

	

Display




&lt;

	

<




&gt;

	

>




&amp;

	

&




&quot;

	

"




&apos;

	

'




&copy;

	

©




&reg;

	

®




&nbsp;

	

Non-breaking space

Example:

<p>HTML uses &lt;tags&gt; to structure content.</p>

<p>Copyright &copy; 2026 Apsy's Tech</p>
23. HTML special input types

HTML forms provide many types of input controls.

Input type

	

Use




text

	

Ordinary text.




password

	

Password entry with masked display.




email

	

Email address entry.




number

	

Numeric entry.




tel

	

Telephone number entry.




url

	

URL entry.




date

	

Date selection.




time

	

Time selection.




datetime-local

	

Local date and time selection.




month

	

Month and year selection.




week

	

Week and year selection.




color

	

Color selection.




range

	

A slider control.




file

	

File selection.




checkbox

	

Independent selection.




radio

	

Selection from a radio group.




search

	

Search text entry.




hidden

	

A form control not displayed to the user.




submit

	

Form submission button.




reset

	

Form reset button.




button

	

General-purpose input button.

Example:

<form>
    <label for="budget">PC budget:</label>
    <input type="number" id="budget" name="budget"
           min="10000" max="500000">

    <br><br>

    <label for="date">Build date:</label>
    <input type="date" id="date" name="date">

    <br><br>

    <label for="color">Choose a theme color:</label>
    <input type="color" id="color" name="color">
</form>
24. HTML validation

HTML forms can use built-in validation features to check certain kinds of user input before submission.

Example:

<form>
    <label for="username">Username:</label>

    <input
        type="text"
        id="username"
        name="username"
        minlength="3"
        maxlength="20"
        required>

    <button type="submit">Submit</button>
</form>

Other useful attributes include:

min

max

step

minlength

maxlength

pattern

required

multiple

These features improve the user experience, but client-side validation is not a substitute for server-side validation. A website that processes user submissions must validate the data on its server as well. 
MDN
+1

25. HTML accessibility

Accessibility means designing webpages so that people with different abilities can use them.

Important practices include:

Use semantic HTML elements.

Provide meaningful alternative text for informative images.

Associate form labels with their controls.

Use headings in a logical order.

Make interactive elements usable with a keyboard.

Give links descriptive text.

Provide captions or alternatives for multimedia where appropriate.

Maintain understandable content and navigation.

For example, this is preferable to a clickable generic element pretending to be a button:

<button type="button">Open Menu</button>

Native buttons already support expected keyboard interaction and semantics. 
MDN
+1

26. HTML and CSS together

HTML creates the content; CSS controls its presentation.

You can add CSS directly to an HTML element, but larger projects are usually easier to maintain when styles are kept in a separate stylesheet.

Inline CSS
<h1 style="color: blue;">
    Apsy's Tech
</h1>
Internal CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CSS Example</title>

    <style>
        body {
            background-color: #101820;
            color: white;
            font-family: Arial, sans-serif;
        }

        h1 {
            color: #00d9ff;
        }
    </style>
</head>

<body>
    <h1>Apsy's Tech</h1>
    <p>Gaming | Technology | PC Building</p>
</body>
</html>
External CSS

Inside the HTML document:

<link rel="stylesheet" href="style.css">

Inside style.css:

body {
    background-color: #101820;
    color: white;
    font-family: Arial, sans-serif;
}

h1 {
    color: #00d9ff;
}

The external stylesheet approach is particularly useful when multiple pages share the same design.

27. HTML and JavaScript together

JavaScript can interact with HTML elements to make a page dynamic.

Example:

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Interactive Example</title>
</head>

<body>

    <h1 id="heading">Welcome!</h1>

    <button type="button" onclick="changeText()">
        Click Me
    </button>

    <script>
        function changeText() {
            document.getElementById("heading").textContent =
                "Welcome to Apsy's Tech!";
        }
    </script>

</body>
</html>

When the button is clicked, JavaScript changes the heading text.

This is the beginning of interactive web development. More complex applications may also use external JavaScript files, APIs and server-side systems.

28. HTML file paths and folders

When creating a website, you need to understand where your files are stored.

Example folder structure:

Apsys-Tech/

index.html

gaming.html

components.html

configurator.html

tech.html

style.css

images/

gpu.jpg

logo.png

If your HTML file and image are in the same folder:

<img src="gpu.jpg" alt="Graphics card">

If the image is inside an images folder:

<img src="images/gpu.jpg" alt="Graphics card">

If two HTML pages are in the same folder:

<a href="components.html">Components</a>

File and folder names must match the paths you use. This is especially important when publishing a website on a hosting service.

29. HTML favicons

A favicon is a small icon associated with a website. It may appear in browser tabs, bookmarks and other browser interface locations.

If you have a file named logo.png in your website folder, you can use:

<head>
    <title>Apsy's Tech</title>

    <link rel="icon" type="image/png" href="logo.png">
</head>

You can also use an .ico file or other supported favicon formats.

30. HTML responsive design basics

Responsive design allows a website to adapt to different screen sizes, such as phones, tablets, laptops and desktops.

The viewport metadata is a useful starting point:

<meta name="viewport"
      content="width=device-width, initial-scale=1.0">

However, responsive design is mainly achieved through CSS techniques such as flexible layouts, media queries, responsive images and relative sizing.

Example:

.container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

.card {
    flex: 1 1 250px;
}

The HTML defines the cards, while CSS controls how they wrap and fit the available space.

31. HTML advanced concepts

These concepts are useful as you progress beyond basic webpage creation.

The DOM (Document Object Model)

A structured representation of a document that scripts can access and modify.

Web Components

A collection of browser technologies that can be used to create reusable custom elements and encapsulated components.

Interactive HTML elements

Elements such as <details>, <summary> and <dialog> can provide useful browser-native interaction patterns.

SVG and Canvas

SVG provides scalable vector graphics, while the Canvas API allows scripts to draw graphics and other visual content.

Microdata and structured information

HTML supports ways to describe information in machine-readable forms for tools that understand the relevant vocabulary.

These concepts are part of the wider HTML and web platform ecosystem. 
HTML Living Standard
+2

32. Useful HTML elements to know

Here is an additional reference list for future study.

Category

	

Elements




Document

	

<html>, <head>, <body>, <title>, <meta>, <link>




Text

	

<p>, <h1>–<h6>, <strong>, <em>, <blockquote>, <q>




Structure

	

<header>, <nav>, <main>, <section>, <article>, <footer>




Lists

	

<ul>, <ol>, <li>, <dl>, <dt>, <dd>




Links and media

	

<a>, <img>, <audio>, <video>, <source>, <track>




Tables

	

<table>, <caption>, <thead>, <tbody>, <tfoot>, <tr>, <th>, <td>




Forms

	

<form>, <label>, <input>, <textarea>, <select>, <option>, <button>




Interactive

	

<details>, <summary>, <dialog>




Graphics

	

<svg>, <canvas>




Code and embedded content

	

<code>, <pre>, <iframe>, <script>, <noscript>

For the complete maintained element reference, see the
MDN HTML elements reference 
.

33. HTML mistakes beginners should avoid

Mistake

	

Better practice




Forgetting <!DOCTYPE html>

	

Include the document type declaration.




Incorrect element nesting

	

Close and nest elements correctly.




Using headings just to change font size

	

Use headings to represent the content hierarchy.




Using <br> repeatedly for spacing

	

Use CSS margins, padding and layout.




Forgetting image alternative text

	

Add appropriate alt text.




Using a <div> instead of a real button

	

Use <button> for button actions.




Using tables for page layout

	

Use CSS layout techniques.




Using duplicate IDs

	

Keep IDs unique within the document.




Forgetting form labels

	

Associate labels with their controls.




Assuming HTML creates a database

	

Use a backend or appropriate service for data storage.




Assuming HTML alone makes a site visually attractive

	

Learn CSS as well.




Assuming a form automatically emails you

	

Configure a suitable form-processing mechanism.

These practices help produce more understandable, accessible and maintainable websites. 
MDN
+2

34. Complete practical project: A mini technology webpage

Here is a complete HTML webpage you can practise creating in Notepad.

Save it as mini-tech.html with UTF-8 encoding and open it in your browser.


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="Learn about PC components and technology.">

    <title>Apsy's Tech - Mini Project</title>
</head>

<body>

    <header>
        <h1>Apsy's Tech</h1>
        <p>Gaming | Technology | PC Building</p>
    </header>
