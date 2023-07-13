# HTML Cheatsheet [![My Skills](https://skillicons.dev/icons?i=html&theme=dark)](https://skillicons.dev)

Welcome to my HTML5 Cheatsheet repository! This repository serves as a comprehensive reference guide for HTML5, providing a collection of HTML tags, elements, and their usage. Whether you're a beginner learning HTML or an experienced developer looking for a quick reference, this cheatsheet has got you covered.

The cheatsheet includes essential HTML5 elements categorized by their purpose, such as basic document structure, text formatting, lists, links, images, forms, tables, multimedia, semantic elements, and more. Each section provides example code snippets to help you understand how to use the HTML tags correctly.

Feel free to explore and utilize this cheatsheet to enhance your HTML coding skills, create well-structured webpages, and save time by quickly finding the right HTML element for your needs. The cheatsheet is written in Markdown format, making it easy to view, copy, and paste into your own projects.

If you have any suggestions or would like to contribute to this cheatsheet, please feel free to open an issue or submit a pull request. Let's collaborate and make this cheatsheet a valuable resource for the HTML developer community!

Happy coding!

## **Basic HTML5 Structure**

An HTML5 document follows a basic structure known as the HTML5 boilerplate. Here's an example of how to set up a basic HTML5 document:

### Boilerplate
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Title</title>
  <link rel="stylesheet" href="styles.css">
  <script src="script.js" defer></script>
</head>
<body>
  <!-- Content goes here -->

  <script>
    // JavaScript code goes here
  </script>
</body>
</html>
```

Explanation:

`<!DOCTYPE html>`: This is the doctype declaration that tells the browser that this document is an HTML5 document.

`<html lang="en">`: The opening `<html>` tag represents the root element of an HTML document. The lang attribute specifies the language of the document (in this case, English).

`<head>:` The `<head>` section contains meta information and references to external files. It doesn't directly display any content on the page.

`<meta charset="UTF-8">`: This meta tag specifies the character encoding for the document, ensuring proper rendering of special characters.

`<meta name="viewport" content="width=device-width, initial-scale=1.0">`: This meta tag sets the viewport properties for responsive design, ensuring that the webpage adapts to different device sizes.

`<title>My HTML5 Document</title>`: The `<title>` tag specifies the title of the document, which is displayed in the browser's title bar or tab.

`<body>`: The <body> tag represents the content of the HTML document that is displayed in the browser window.

`<!-- Your content goes here -->`: This is a placeholder comment where you can insert your actual content, including various HTML elements and tags.


## **Document Structure**

HTML5 introduces new semantic elements that help structure the content of a webpage. These elements provide better accessibility and convey the meaning of the content. Here are some commonly used structural elements:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My HTML5 Document</title>
</head>
<body>
  <header>
    <!-- Header content -->
  </header>

  <nav>
    <!-- Navigation content -->
  </nav>

  <main>
    <!-- Main content -->
  </main>

  <section>
    <!-- Section content -->
  </section>

  <article>
    <!-- Article content -->
  </article>

  <aside>
    <!-- Sidebar or additional content -->
  </aside>

  <footer>
    <!-- Footer content -->
  </footer>
</body>
</html>
```

Explanation:

`<header>`: The `<header>` element represents the introductory content or a group of introductory content in a document or section. It typically contains the site logo, site title, or the main heading of the page.

`<nav>`: The `<nav>` element represents a section of the page that contains navigation links, such as a menu or a list of links to other pages or sections within the website.

`<main>`: The `<main>` element represents the main content of the document. It should be unique to the document and not used for repeated content such as site navigation or footer.

`<section>`: The `<section>` element defines a standalone section of the document. It is often used to group related content together, such as chapters, tabbed content, or different parts of an article.

`<article>`: The `<article>` element represents a self-contained composition in a document, such as a blog post, a news article, or a forum post. It should make sense on its own, even if it's extracted from the surrounding content.

`<aside>`: The `<aside>` element represents content that is tangentially related to the main content of the document. It can be used for sidebars, pull quotes, or other content that enhances the main content but can be skipped without losing overall meaning.

`<footer>`: The `<footer>` element represents the footer or the closing section of a document or a section. It typically contains information about the author, copyright, or links to related documents.

These structural elements help organize the content of your HTML document, making it more meaningful and easier to understand for both humans and assistive technologies. Remember to place your actual content within each element accordingly.

## **Text Formatting**

HTML5 provides several tags and attributes for text formatting. Here are some commonly used ones:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My HTML5 Document</title>
</head>
<body>
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h6>

  <p>This is a paragraph.</p>

  <em>This text is emphasized.</em>
  <strong>This text is strong.</strong>

  <blockquote>
    This is a blockquote.
  </blockquote>

  <code>This is inline code.</code>

  <pre>
    This is preformatted text.
    It preserves whitespace.
  </pre>
</body>
</html>
```

Explanation:

`<h1>, <h2>, <h3>, <h4>, <h5>, <h6>`: These are the heading tags used to define different levels of headings, with h1 being the highest level and h6 being the lowest level.

`<p>`: The `<p>` tag represents a paragraph of text.

`<em>`: The `<em>` tag is used to emphasize text. By default, it usually renders as italic text.

`<strong>`: The `<strong>` tag is used to indicate strongly emphasized text. By default, it usually renders as bold text.

`<blockquote>`: The `<blockquote>` tag is used to indicate a block of quoted text. It typically indents the content and may render with quotation marks or other styling depending on the browser's default stylesheet.

`<code>`: The `<code>` tag is used to represent a fragment of computer code. It typically renders as monospaced text.

`<pre>`: The `<pre>` tag is used to enclose preformatted text. It preserves whitespace, such as line breaks and indentation, exactly as it appears in the HTML source code.

These tags and attributes help structure and format text content within your HTML document. Use them according to the desired effect and visual presentation you want to achieve. Remember to replace the example text with your actual content.

## **Lists**

HTML5 provides tags for creating different types of lists. Here are examples of unordered lists, ordered lists, and description lists:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My HTML5 Document</title>
</head>
<body>
  <h2>Unordered List</h2>
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ul>

  <h2>Ordered List</h2>
  <ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ol>

  <h2>Description List</h2>
  <dl>
    <dt>Term 1</dt>
    <dd>Description 1</dd>
    <dt>Term 2</dt>
    <dd>Description 2</dd>
    <dt>Term 3</dt>
    <dd>Description 3</dd>
  </dl>
</body>
</html>
```

Explanation:

`<ul>`: The ul tag represents an unordered list, where each list item is preceded by a bullet point.

`<li>`: The li tag represents a list item within an unordered or ordered list.

`<ol>`: The ol tag represents an ordered list, where each list item is numbered.

`<dl>`: The dl tag represents a description list, which consists of terms (defined by dt) and their corresponding descriptions (defined by dd).

`<dt>`: The dt tag represents a term or item in a description list.

`<dd>`: The dd tag represents the description of a term in a description list.

Use these list tags to structure and organize your content in a list format according to your specific needs. Replace the example items and descriptions with your own content.

## **Links**

HTML5 provides the `<a>` tag for creating hyperlinks. Here are some examples of different types of links:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My HTML5 Document</title>
</head>
<body>
  <h2>Hyperlink</h2>
  <a href="https://www.example.com">Visit Example</a>

  <h2>Internal Link</h2>
  <a href="#section1">Go to Section 1</a>

  <h2>Phone Link</h2>
  <a href="tel:+1234567890">Call +1234567890</a>

  <h2>Email Link</h2>
  <a href="mailto:info@example.com">Send Email</a>
</body>
</html>
```

Explanation:

`<a href="https://www.example.com">`: The <a> tag represents a hyperlink. The href attribute specifies the URL of the destination page or resource. In this example, it links to "https://www.example.com".

`<a href="#section1">`: You can create internal links within the same HTML document by using the # symbol followed by the target element's id attribute. This example creates a link that jumps to an element with id="section1".

`<a href="tel:+1234567890">`: To create a link for phone numbers, use the tel: protocol followed by the phone number. This example creates a link that allows users to initiate a phone call to the number "+1234567890".

`<a href="mailto:info@example.com">`: To create an email link, use the mailto: protocol followed by the email address. This example creates a link that opens the default email client with a new message addressed to "info@example.com".

Use the <a> tag with the appropriate href attribute to create various types of links in your HTML document. Customize the URLs, phone numbers, or email addresses to fit your specific use case.

## **Images**

HTML5 provides the <img> tag for displaying images. Here's an example of how to insert an image along with <figure> and <figcaption> for image captions:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My HTML5 Document</title>
</head>
<body>
  <h2>Image</h2>
  <img src="image.jpg" alt="Description of the image">

  <h2>Image with Caption</h2>
  <figure>
    <img src="image.jpg" alt="Description of the image">
    <figcaption>Caption for the image</figcaption>
  </figure>
</body>
</html>
```

Explanation:

`<img src="image.jpg" alt="Description of the image">`: The `<img>` tag is used to insert an image into the HTML document. The src attribute specifies the URL or file path of the image, and the alt attribute provides a text description of the image, which is displayed if the image fails to load or for accessibility purposes.

`<figure>` and `<figcaption>`: You can use the `<figure>` and `<figcaption>` tags to group an image with its caption. The <figure> tag represents self-contained content, such as images, illustrations, diagrams, or code snippets. The `<figcaption>` tag provides the caption or description for the associated <figure> element.

Replace "image.jpg" with the actual URL or file path of your image. Additionally, provide appropriate descriptions and captions for your images to enhance accessibility and provide context.


## **Forms**

HTML5 provides the <form> tag for creating forms. Here are examples of different form elements and their usage:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My HTML5 Document</title>
</head>
<body>
  <h2>Text Input</h2>
  <form>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your name">
  </form>

  <h2>Password Input</h2>
  <form>
    <label for="password">Password:</label>
    <input type="password" id="password" name="password">
  </form>

  <h2>Checkbox</h2>
  <form>
    <input type="checkbox" id="check1" name="check1" value="option1">
    <label for="check1">Option 1</label><br>
    <input type="checkbox" id="check2" name="check2" value="option2">
    <label for="check2">Option 2</label><br>
  </form>

  <h2>Radio Buttons</h2>
  <form>
    <input type="radio" id="radio1" name="radio" value="option1">
    <label for="radio1">Option 1</label><br>
    <input type="radio" id="radio2" name="radio" value="option2">
    <label for="radio2">Option 2</label><br>
  </form>

  <h2>Submit Button</h2>
  <form>
    <input type="submit" value="Submit">
  </form>

  <h2>Text Area</h2>
  <form>
    <label for="message">Message:</label><br>
    <textarea id="message" name="message" rows="4" cols="30"></textarea>
  </form>

  <h2>Dropdown List</h2>
  <form>
    <label for="country">Country:</label>
    <select id="country" name="country">
      <option value="usa">USA</option>
      <option value="canada">Canada</option>
      <option value="uk">UK</option>
    </select>
  </form>
</body>
</html>
```

Explanation:

`<form>`: The `<form>` tag represents a section of the document that contains interactive controls for submitting user data.

`<input type="text"`>: The `<input>` tag with type="text" creates a text input field.

`<input type="password">`: The `<input>` tag with type="password" creates a password input field where the characters are masked.

`<input type="checkbox">`: The `<input>` tag with type="checkbox" creates a checkbox input. Use the value attribute to assign a value to each checkbox.

`<input type="radio">`: The `<input>` tag with type="radio" creates a radio button input. Use the value attribute to assign a value to each radio button. The name attribute should be the same for all radio buttons within a group.

`<input type="submit">`: The `<input>` tag with type="submit" creates a submit button.

`<textarea>`: The `<textarea>` tag creates a multi-line text input field.

`<select>`: The `<select>` tag creates a dropdown list. Use the `<option>` tags to define the selectable options within the list.

These examples demonstrate different form elements that you can use to collect and submit user input. Customize the labels, names, and values according to your specific form requirements.


## **Tables**

HTML5 provides the `<table>`, `<tr>`, `<th>`, and `<td>` tags for creating tables. Here's an example of how to create a basic table:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My HTML5 Document</title>
</head>
<body>
  <table>
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
      <th>Header 3</th>
    </tr>
    <tr>
      <td>Data 1</td>
      <td>Data 2</td>
      <td>Data 3</td>
    </tr>
    <tr>
      <td>Data 4</td>
      <td>Data 5</td>
      <td>Data 6</td>
    </tr>
  </table>
</body>
</html>
```

Explanation:

`<table>`: The `<table>` tag is used to create a table.

`<tr`>: The `<tr>` tag represents a table row.

`<th>`: The `<th>` tag represents a table header cell. It is used to define header cells for each column of the table.

`<td>`: The `<td>` tag represents a table data cell. It is used to define regular cells within the table that contain data.

Within the `<table>` element, you can create multiple `<tr>` elements to represent different rows of the table. Inside each row, you can use `<th>` for the table header cells and `<td>` for the table data cells.

Customize the content within the table cells to match your data and structure the table accordingly. You can also use additional attributes like colspan and rowspan to merge cells or span them across multiple columns or rows as needed.


## **Multimedia**

HTML5 provides tags for embedding videos and audio. Here's an example of how to embed videos and audio in HTML5:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My HTML5 Document</title>
</head>
<body>
  <h2>Video</h2>
  <video src="video.mp4" controls width="320" height="240">
    Your browser does not support the video tag.
  </video>

  <h2>Audio</h2>
  <audio src="audio.mp3" controls>
    Your browser does not support the audio tag.
  </audio>
</body>
</html>
```

Explanation:

`<video>`: The `<video>` tag is used to embed videos into an HTML document. The src attribute specifies the URL or file path of the video file. The controls attribute enables the default video player controls. You can also specify the width and height attributes to set the dimensions of the video player.

`<audio>`: The <audio> tag is used to embed audio into an HTML document. The src attribute specifies the URL or file path of the audio file. The controls attribute enables the default audio player controls.

The content placed between the opening and closing tags of the <video> and <audio> elements serves as a fallback message for browsers that do not support the respective multimedia tags.

Replace "video.mp4" and "audio.mp3" with the actual URLs or file paths of your video and audio files, respectively. Adjust the dimensions of the video player as needed.


## **Semantic Elements**

HTML5 introduces semantic elements that provide meaning and structure to the content. Here are some commonly used semantic elements:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My HTML5 Document</title>
</head>
<body>
  <header>
    <h1>Website Title</h1>
    <!-- Header content -->
  </header>

  <nav>
    <!-- Navigation content -->
  </nav>

  <main>
    <!-- Main content -->
    <article>
      <!-- Article content -->
    </article>
    <aside>
      <!-- Sidebar or additional content -->
    </aside>
  </main>

  <footer>
    <!-- Footer content -->
  </footer>
</body>
</html>
```

Explanation:

`<header>`: The `<header>` element represents the introductory content or a group of introductory content in a document or section. It typically contains the site logo, site title, or the main heading of the page.

`<nav>`: The `<nav>` element represents a section of the page that contains navigation links, such as a menu or a list of links to other pages or sections within the website.

`<main>`: The `<main>`element represents the main content of the document. It should be unique to the document and not used for repeated content such as site navigation or footer.

`<article`>: The `<article>` element represents a self-contained composition in a document, such as a blog post, a news article, or a forum post. It should make sense on its own, even if it's extracted from the surrounding content.

`<aside>`: The `<aside>` element represents content that is tangentially related to the main content of the document. It can be used for sidebars, pull quotes, or other content that enhances the main content but can be skipped without losing overall meaning.

`<footer>`: The `<footer>` element represents the footer or the closing section of a document or a section. It typically contains information about the author, copyright, or links to related documents.

These semantic elements help structure and organize the content of your HTML document, making it more meaningful, accessible, and search engine-friendly. Use them to provide clearer semantics and improve the overall structure of your web pages.

## **Miscellaneous**

HTML5 provides various elements and features for additional functionality and customization. Here are some commonly used miscellaneous elements:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My HTML5 Document</title>
</head>
<body>
  <!-- Comment -->
  <p>This is a regular paragraph.</p>

  <div>
    <p>This is a div container.</p>
  </div>

  <span>This is a span element.</span>

  <meta name="description" content="Description of the webpage">

  <script src="script.js"></script>
</body>
</html>
```
Explanation:

<!-- Comment -->: HTML comments are used to add notes or remarks that are not displayed in the rendered webpage. They are useful for documenting code or temporarily disabling portions of HTML.

`<div>`: The `<div>` element is a generic container used for grouping elements together or applying styling using CSS. It does not inherently convey any semantic meaning.

`<span>`: The `<span>` element is an inline container used for grouping inline elements together or applying styling using CSS. It does not inherently convey any semantic meaning.

`<meta>`: The `<meta>` tag is used to provide metadata about the HTML document. Commonly used attributes include name (specifying the type of metadata) and content (providing the value of the metadata).

`<script src="script.js"></script>`: The `<script>` tag is used to embed or reference external JavaScript files. The src attribute specifies the file path or URL of the JavaScript file.

These miscellaneous elements and features provide additional flexibility and customization options for your HTML document. Use them as needed to enhance your webpage's functionality, structure, and styling.


## **Responsive Design**
Responsive design allows web pages to adapt and provide an optimal viewing experience across different devices and screen sizes. Here are some techniques to achieve responsive design in HTML5:

### Media Queries
Media queries allow you to apply different styles based on the characteristics of the device or viewport. Here's an example of a media query that targets devices with a maximum width of 600 pixels:

``` css
@media (max-width: 600px) {
  /* Styles for devices with a maximum width of 600 pixels */
  body {
    font-size: 14px;
  }
}
```

Explanation:

`@media (max-width: 600px)`: This media query targets devices with a maximum width of 600 pixels. You can adjust the max-width value to target different screen sizes.
`body { font-size: 14px; }`: This CSS rule applies a font size of 14 pixels to the body element when the device width is 600 pixels or less.

### Viewport Meta Tag

The viewport meta tag helps control the dimensions and scaling of the webpage on mobile devices. Include the following meta tag in the <head> section of your HTML document:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Explanation:

`<meta name="viewport" content="width=device-width, initial-scale=1.0">`: This meta tag sets the width of the viewport to the device width `(width=device-width`) and sets the initial zoom level to 1` (initial-scale=1.0)`.

### Responsive Images

To ensure images scale and adapt to different screen sizes, you can use the max-width: 100% CSS rule. For example:

``` css
img {
  max-width: 100%;
  height: auto;
}
```

Explanation:

`max-width: 100%`: This CSS rule ensures that the image width does not exceed the width of its container, allowing it to scale down as needed.
`height: auto;`: This rule maintains the aspect ratio of the image by automatically adjusting the height according to the scaled width.
By using media queries, the viewport meta tag, and applying responsive image styles, you can create web pages that are visually appealing and optimized for different screen sizes and devices.

Feel free to customize the example code and add more advanced techniques or examples based on your specific responsive design needs.

## **Audio and Video Controls**

HTML5 provides built-in controls for audio and video elements. Here's an example of how to use them:

### Audio Controls

``` html
<audio src="audio.mp3" controls>
  Your browser does not support the audio element.
</audio>
```
Explanation:

<audio src="audio.mp3" controls>: The <audio> tag is used to embed audio content. The src attribute specifies the URL or file path of the audio file. The controls attribute enables the default audio player controls, such as play/pause, volume, and progress bar.
Your browser does not support the audio element.: This text is displayed if the browser does not support the <audio> tag.

### Video Controls

``` html
<video src="video.mp4" controls width="640" height="360">
  Your browser does not support the video element.
</video>
```
Explanation:

`<video src="video.mp4" controls width="640" height="360">`: The `<video>` tag is used to embed video content. The src attribute specifies the URL or file path of the video file. The controls attribute enables the default video player controls. You can also specify the width and height attributes to set the dimensions of the video player.
Your browser does not support the video element.: This text is displayed if the browser does not support the `<video>` tag.
By using the controls attribute, the audio and video elements display the default player controls, allowing users to play, pause, adjust volume, and seek through the media content. The fallback message within the opening and closing tags is displayed for browsers that do not support the respective media element.

Replace "audio.mp3" and "video.mp4" with the actual URLs or file paths of your audio and video files, respectively. Adjust the dimensions of the video player as needed.



## Additional Resources

Here are some additional resources and references for learning more about HTML5:

Mozilla Developer Network (MDN) - HTML: MDN provides comprehensive documentation and guides on HTML, covering various elements, attributes, and best practices.

W3Schools - HTML: W3Schools offers interactive tutorials, examples, and references for HTML, including detailed explanations of tags, attributes, and related concepts.

HTML5 Doctor: HTML5 Doctor is a website dedicated to promoting best practices and providing expert advice on HTML5 markup and usage.

HTML5 Rocks: HTML5 Rocks is an informative resource that provides articles, tutorials, and demos related to HTML5, including advanced features and techniques.

HTML5 Spec: The HTML5 specification is the official technical specification for HTML5. It provides detailed information on the syntax, semantics, and behavior of HTML elements and attributes.

