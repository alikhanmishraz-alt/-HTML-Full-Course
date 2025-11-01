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

 
 1. `<!DOCTYPE html>` * This line tells the browser that the document is using the **latest version of HTML (HTML5)**.

 2. `<html>` * This is the **main container of the entire document**. Everything on the page — including `<head>` and `<body>` — is written inside this tag.

 3. `<head>` * This contains all the **“behind-the-scenes information”** that the browser needs, such as the page title, character settings, and links to CSS or JavaScript files.

 4. `<body>` * This is the part that **contains everything visible to the user on the screen**, such as text, images, buttons, and forms.


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

