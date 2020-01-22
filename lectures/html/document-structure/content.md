# HTML Document Structure



-
-
## Document Structure
* DOCTYPE
* Nesting
* Body
* Links



-
-
### <!DOCTYPE>
* This declarations is the very first thing in the HTML document. It defines the document type.
* <!DOCTYPE html>

-
-
### Nesting
* HTML is structured by nesting elements inside other elements. This is done by placing elements inside other containing tags.
* For example, the `<p>` nested inside of the <body> tags is a “child” or a “descendent” of the body.
``` HTML
<body>
	<p>A paragraph inside the body tag</p>
</body>
```

-
#### The `<html>` tag
* This tag tells the browser this is an HTML document
* `<html>...</html>`

```HTML
<!DOCTYPE html>
<html>
</html>
```


-
-
#### The `<head>` tag
* Follows the `<html>` tag and has opening and closing tags
* `<head>...</head>`
* Contains the title and metadata information about the page
* Meta information is mostly invisible to the user, but has many purposes, like providing information to search engines.
```HTML
<!DOCTYPE html>
  <html>
    <head>
      <title>My Page</title>
    </head>
  </html>
```      


-
-
### The `<body>` tag
* Follows the `<head>` tag and has open and closing tags
* `<body>...</body>`
* Everything that appears on a webpage is wrapped in the `<body>` tag.
* Headings, paragraphs, lists, quotes, images, and links are just a few of the elements that can be contained within the body tag.

``` HTML
<!DOCTYPE html>
	<html>
	  	<head>
	    	<title>Title of the page</title>
	  	</head>
	  	<body>
	    	The page content here.
		</body>
</html>
```


-
#### Headings
* HTML includes six levels of heading which are ranked according to importance, not size
* These are `<h1>, <h2>, <h3>, <h4>, <h5>, and <h6>`.
``` HTML
<h1>Written</h1>
<h2>In</h2>
<h3>Decreasing</h3>
<h4>Order</h4>
<h5>Of</h5>
<h6>Importance</h6>
```
-
#### Division
* This element, with opening and closing tags, defines a division or a section in an HTML document
* `<div>...</div>`

```Html
<div class="name">
	<h1> This is your title </h1>
</div>

<div class="article">
	<p> This is a sentence</p>
</div>
```

-
#### Paragraphs
* This element, with opening and closing tags, will allow you to create paragraphs.
* `<p>...</p>`
* The browser does not care about line breaks or tabs in your code. Use the `<p>`tag to split lines of text displayed on the page.

``` HTML
<p> Words of text </p>

<p>
	A
	paragraph
	inside the body tag
</p>

```

-
-

#### Images
* The image element has two required attributes: "src" and "alt"
* "src" = Source and  specifies location of the image
* "alt" = alternative text and gives description of the image when the page load incorrectly

``` HTML
<img src="image.jpg" alt="Evergreen Tree">
```

-
-
#### Horizontal Line Break
* This element represents a sectional break between paragraphs. It can be used as an indicator when changing a subject within as section.
`<hr>`

``` HTML
<html>
  <head>
    <title>first page</title>
  </head>
    <body>
        <p>This is a paragraph.</p>
        <hr>
        <p>This is another paragraph. </p>
    </body>
</html>
```

-
-
#### Single Line Break     
* Use the `<br>` tag to add a single line of text without starting a new paragraph.
* The `<br>` element is an empty HTML element. It has no closing tag.
```HTML
<html>
  <head>
      <title>first page</title>
    </head>
  <body>
    <p>This is a paragraph.</p>
      <p>This is another paragraph. </p>
    <p>This is <br> a line break </p>
  </body>
</html>
```
