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
 
 

 

