# -HTML-Full-Course
A complete step-by-step guide for beginners to learn HTML. BY, MUHMMAD MISHRAZ ALI KHAN 

HTML Structure (Buniyadi Dhaancha)
Har HTML document ka ek standard (manak) structure hota hai. Yeh structure browser ko batata hai ki page ka kaunsa hissa display karna hai, aur kaunsa sirf information ke liye hai.

1. 📄 Buniyadi HTML Code
Yahan woh code hai jise aap har HTML file mein sabse pehle likhenge:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mera Pehla HTML Page</title>
</head>
<body>
    <h1>Hello World!</h1>
    <p>Yeh mera HTML Learning Guide project ka pehla page hai.</p>
</body>
</html>
```

 
* 1. `<!DOCTYPE html>` * This line tells the browser that the document is using the **latest version of HTML (HTML5)**.

* 2. `<html>` * This is the **main container of the entire document**. Everything on the page — including `<head>` and `<body>` — is written inside this tag.

* 3. `<head>` * This contains all the **“behind-the-scenes information”** that the browser needs, such as the page title, character settings, and links to CSS or JavaScript files.

* 4. `<body>` * This is the part that **contains everything visible to the user on the screen**, such as text, images, buttons, and forms.


<h2>2. ✍️ Text Formatting Tags </h2>

Yeh tags text ke roop (visual style) ya uski ehmiyat (semantic importance) ko badalte hain.

```html
 <h1>Heading 1</h1>
<p>This is a paragraph.</p>
<a href="https://example.com">This is a link</a>
<img src="image.jpg" alt="Description of image">
<div class="container">This is a div</div>
<span>This is a span</span>

```
```html


Tag,Maqsad (Purpose),Example Code
<h1> to <h6>,Headings define karta hai (h1 sabse zaroori/bada).,<h1>Main Heading</h1>
<p>,Text ke ek paragraph ko define karta hai.,<p>This is text.</p>
<br>,Current line ko force karke naye line se shuru karta hai (line break).,Line 1<br>Line 2
<strong>,Batata hai ki text bahut zaroori hai (semantic bold).,<strong>Important!</strong>
<em>,Text par zor dene ke liye istemaal hota hai (semantic italic).,<em>Emphasis here.</em>
<span>,Text ke ek chote se hisse ko define karta hai (inline container).,Hello <span>World</span>


```


<h2>3. 🖼️ Images and Media Tags</h2>

```html
<img src="pic.jpg" alt="A flower">  
<audio controls>
    <source src="audio.mp3" type="audio/mp3">
    Your browser does not support the audio element.
</audio>
<video width="320" height="240" controls>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

* `<img>` — Used to **insert an image** on a web page (self-closing tag).
* `<audio>` — Used to **embed audio content** on a web page.
* `<video>` — Used to **embed video content** on a web page.

<h2>4. 🔗 Links and Navigation Tags</h2>

```html
 <a href="page.html">Click Me</a>
 <a href="#section1">Go to Section 1</a>
 <nav>...</nav>
```
 

 * `<a>` —	Hyperlink (link) banata hai. href zaroori attribute hai.
 * `<nav>` — Navigation links ka ek set define karta hai (main menu).

<h2>5. 📝 Forms and Input Types</h2>
<p>Yeh tags user se information lene ke liye forms create karte hain.</p>

```html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    <label for="password">Password:</label>
    <input type="password" id="password" name="password">
    <input type="submit" value="Submit">
</form>

```
   Here’s the English translation 👇

---

* `<form>` — Defines a **form area** to collect user input.
  Example: `<form action="submit.php">...</form>`

* `<input>` — Defines **input fields** such as text boxes, checkboxes, or radio buttons.
* `<input type="submit">` — Creates a **button** to submit the form.
* `<label>` — Defines a **caption** or description for a form control (like an input field).
* `<action>` — The **URL** where the form data will be sent.
* `<method>` — The **HTTP method** used to send the data (either `GET` or `POST`).

---
 <h2>6. 🏛️ **Semantic Tags (Modern Structure)**</h2>
  These tags not only define the structure but also **convey the meaning** of the content.


```html
<header>
        <h1>My Semantic HTML Page</h1>
        <p>Using HTML5 semantic elements for better structure and SEO</p>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Blog</a>
        <a href="#">Contact</a>
    </nav>

    <main>
        <article>
            <h2>Article Title</h2>
            <section>
                <h3>Section 1</h3>
                <p>This is the first section of the article explaining semantic HTML structure.</p>
            </section>
            <section>
                <h3>Section 2</h3>
                <p>Semantic tags improve accessibility and help search engines understand content better.</p>
            </section>
        </article>

        <aside>
            <h3>Related Links</h3>
            <ul>
                <li><a href="#">HTML5 Documentation</a></li>
                <li><a href="#">MDN Web Docs</a></li>
                <li><a href="#">W3Schools HTML Guide</a></li>
            </ul>
        </aside>
    </main>

    <footer>
        <p>&copy; 2025 My GitHub Project | Built with ❤️ using Semantic HTML</p>
    </footer>
  
```


 
 
* `<"header">` —  → Top section with the title or logo       

 * `<"nav">` —  → Navigation bar for links     

 * `<"main">` —  → Main content area      

 * `<"article">` —  → Independent piece of content (like a blog post)    

 * `<"section">` —  → Logical divisions within the article          

 * `<"aside">` —  → Sidebar with related content

 * `<"footer">` —  → Bottom area with credits or contact info

 

<h2>7. ⚙️ **Attributes (Tag Features)**</h2>
   Attributes are the **properties** that provide **additional information** about HTML tags.


   <h1>HTML Attributes Example</h1>

   
```html
<h1>HTML Attributes Example</h1>

    <!-- 1. Image Tag with Attributes -->
    <img src="https://via.placeholder.com/200" alt="Sample Image" width="200">

    <!-- 2. Link Tag with Attributes -->
    <a href="https://github.com" target="_blank" title="Go to GitHub">Visit GitHub</a>

    <!-- 3. Input Tag with Attributes -->
    <form action="#" method="post">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <input type="submit" value="Submit">
    </form>

    <!-- 4. Paragraph with Style Attribute -->
    <p style="color: blue;">This paragraph uses the style attribute to make text blue.</p>

    <!-- 5. Button with Title and Onclick Attributes -->
    <button title="Click to see alert" onclick="alert('Hello!')">Click Me</button>

  ```
  * `"src"` —  →   * `"alt"` —  →  * `width"` —  →  Image attributes        
  * `"href"` —  →   * `"target"` —  →  * `title"` —  →   → Link attributes
  * `"type"` —  →   * `"placeholder"` —  →  * `required"` —  →   Input attributes         
  * `style"` —  →  Inline styling         
  * `onclick"` —  →   * `title"` —  →  → Button attributes      




