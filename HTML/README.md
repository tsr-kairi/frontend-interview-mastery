<div align="center">	
	<p>	
		<a href="#">	
      <div>	
<div style="width:60px;">

![alt fim-max](/HTML/html.png)
</div>

</div>
<br>
</p>
</a>
<b>

### 🖲 Top 50 HTML5 Interview <br> Questions and Answers - Freshers, Experienced in 2022

#### These 50 solved HTML questions will help you prepare for technical interviews and online selection tests.

</div>

<br/>
<br/>
<br/>

[↩ Back To Home](/README.md)

<br>
<br>

## ✍ 1. What is HTML?

Answer :

HTML stands for Hyper Text Markup Language. It is a language of World Wide Web.It is the standard text formatting language for creating Web pages.

<br>

## ✍ 2. What is a tag in HTML?

Answer :

Content is placed in between HTML tags in order to properly format it. It makes use of the less than symbol (<) and the greater than symbol (>). A slash symbol is also used as a closing tag. For example:

```html
<strong>sample</strong>
```

<br>

## ✍ 3. Do all HTML tags come in a pair?

Answer :

No, there are single HTML tags that do not need a closing tag. Examples are the `<img>` tag and `<br>` tags.

<br>

## ✍ 4. How many types of heading does an HTML contain?

Answer :

The HTML contains six types of headings which are defined with the `<h1>` to `<h6>` tags. Each type of heading tag displays different text size from another. So, `<h1>` is the largest heading tag and `<h6>` is the smallest one. For example:

<br>

## ✍ 5. What are Semantic Elements?

Answer :

A semantic element is an element of code that uses words to clearly represent what that element contains, in human language.

Examples of non-semantic elements: `<div>` and `<span>` - Tells nothing about its content.

Examples of semantic elements: `<form>`, `<table>`, and `<article>` - Clearly defines its content.

<br>

## ✍ 6. How to create a nested webpage in HTML?

Answer :

The HTML iframe tag is used to display a nested webpage. In other words, it represents a webpage within a webpage. The HTML `<iframe>` tag defines an inline frame. For example:

```html
<!DOCTYPE html>
<html>
  <body>
    <h2>HTML Iframes example</h2>
    <p>Use the height and width attributes to specify the size of the iframe:</p>
    <iframe src="https://www.javatpoint.com/" height="300" width="400"></iframe>
  </body>
</html>
```

<br>

## ✍ 7. Explain the layout of HTML?

Answer :

HTML layout specifies a way in which the web page is arranged.

<br>

![alt text](https://static.javatpoint.com/htmlpages/images/html-layouts.png "html-layout")

Every website has a specific layout to display content in a specific manner.

<br>

## ✍ 8. What are the entities in HTML?

Answer :

The HTML character entities are used as a replacement for reserved characters in HTML. You can also replace characters that are not present on your keyboard by entities. These characters are replaced because some characters are reserved in HTML.

<br>

## ✍ 9. Does a `<!DOCTYPE html>` tag is a HTML tag?

Answer :

No, the `<!DOCTYPE html>` declaration is not an HTML tag.

<br>

## ✍ 10. What is datalist tag?

Answer :

The HTML 5 datalist tag provides an autocomplete feature on the form element. It facilitates users to choose the predefined options to the users to select data.

```html
<label>
  Enter your favorite cricket player: Press any character<br />
  <input type="text" id="favCktPlayer" list="CktPlayers" />
  <datalist id="CktPlayers">
    <option value="Mahendra Singh Dhoni"></option>
    <option value="Sachin Tendulkar"></option>
    <option value="Brian Lara"></option>
    <option value="AB diVilliers"></option>
    <option value="Adam Gilchrist"></option>
  </datalist>
</label>
```

<br>

## ✍ 11. What is the use of the required attribute in HTML5?

Answer :

It forces a user to fill text on the text field or text area before submitting the form. It is used for form validation.

### <b>Example:</b>

```html
Name : <input type="text" name="name" required />
```

<br>

## ✍ 12. What are the new `<input>` types for form validation in HTML5?

Answer :

The new input types for form validation are email, URL, number, tel, and date.

### <b>Example:</b>

```html
<input type="email" />
```

 <br>

## ✍ 13. What does a DOCTYPE do?

Answer :

DOCTYPE is an abbreviation for Document Type. A DOCTYPE is always associated to a DTD - for Document Type Definition.

<br>

## ✍ 14. What is the difference between HTML elements and tags?

Answer :

HTML elements communicate to the Browser how to represent the text. They become HTML tags when enclosed within angular brackets <>.

<br>

## ✍ 15. How do I link CSS in HTML?


Answer : 

### <b>CSS can be added to HTML documents in 3 ways:</b>

<br>

1. Inline - by using the ``style`` attribute inside HTML elements.

```html 
<h1 style="color:blue;">A Blue Heading</h1>
```
2. Internal - by using a ``<style>`` element in the ``<head>`` section.

```html
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
3. External - by using a ``<link>`` element to link to an external CSS file.

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
<br>

## ✍ 16. What are elements in HTML?

Answer : 

Elements are components of HTML5 code that instruct the web browser how to structure and interpret the HTML5 document.

<br>

## ✍ 17. What are attributes in HTML?

Answer : 

Attributes are special properties or characteristics used within an element to modify its behavior. 

- <b>For example</b> 

attributes can be used to specify the dimensions or positioning values of an image. Attributes are specified within the opening tag and must be enclosed in quotation marks.

<br>

## ✍ 18. What are the three types of lists in HTML?

Answer :

- The three types of HTML5 lists are:
  
1. ``Ordered list`` : which is used to group related items in a specific order
2. ``Unordered list`` : which is used to group related items in no particular order 
3. ``Description list`` : which is used to group terms and their descriptions

<br>

## ✍ 19. What is the role of formatting tags in HTML?

Answer :

#### Formatting tags allow text to be stylized in HTML5 without the need for CSS. There are a number of HTML5 formatting tags, and the most popular ones include:

- ``<b>`` - used to make text bold
- ``<i>`` - used to italicize text
- ``<u>`` - used to underline text
- ``<mark>`` - used to highlight text
- ``<strong>`` - used to mark text as important

<br>

## ✍ 20. What are some of the most important APIs in HTML?

Answer :

#### HTML5 supports a wide range of APIs. Some of the most popular ones include:

- ``Geolocation API`` : used to identify the user’s location
- ``Web Speech API`` : which provides speech recognition functionality
- ``Clipboard API`` : which provides copy, cut, and paste functionality
- ``History API`` : which provides access to the browser navigation history
- ``Web Notifications API`` : used to send web-based notifications to users

<br>

## ✍ 21. What are the different types of storage in HTML?

Answer : 

#### HTML5 supports two types of web storage. These are:

1. ``sessionStorage`` : temporary storage available for the duration of the page session
2. ``localStorage`` : permanent storage available until data is deleted by the user

<br>

## ✍ 22. What is metadata in HTML5 and how is it specified?

Answer :

Metadata is data that describes other data, providing additional information about an HTML document. Its purpose is to help browsers, search engines .

The ``<meta>`` tag is used to define metadata about an HTML document. ``<meta>`` tags are always enclosed within the ``<head>`` of the HTML document.

<br>

## ✍ 23. What are Forms in HTML?

Answer : 

Forms are used to collect the user information when they are filled, and details are provided to save into the database.

<b>Example</b> : 

![html-form](https://www.upgrad.com/blog/wp-content/uploads/2020/07/HTML-Form.png)

<br>

## ✍ 24. What is the Use of Comments in HTML?

Answer : 

Comments are used in an HTML document to make important notes and help developers mention any modification to be incorporated afterward.

- <b>Syntax</b> :

```html
<!—‘Comment’ !–>
```

<br>

## ✍ 25. What is the difference between HTML elements and tags?

Answer :

The differences between HTML elements and tags are: 

<br>


| HTML Elements  | Tags |
| ------------- | ------------- |
| 1. HTML Elements hold the content.  | 1. HTML Tags hold the HTML element. |
| 2.  They specify the general content.  | 2. HTML tags are like keywords. Each tag has a unique meaning. |
| 3. For example, ``<p>`` This is an example of a paragraph. ``</p>``  | 3. For example, ``<a>`` is an opening anchor tag and ``</a>`` is a closing anchor tag. |

<br>

## ✍ 26. What is the difference between a block-level element and an inline element?

Answer  :

#### The differences between block-level elements and inline elements are: 

<br>


| Block-level Elements  | Inline Elements |
| ------------- | ------------- |
| 1. They start on a new line.  | 1. Do not start on a new line and can begin within a line. |
| 2.  Stretch to fill the full width available to them.  | 2. Take up as much width as necessary. Its width only extends as far as it is defined by its tags. |
| 3. They have a top and a bottom margin.  | 3. Inline elements do not have a top and a bottom margin.  |
| 4. Examples of block-level elements in HTML :  ``<div>, <img>, <form>, <main>, <table>, <video>``.  | 4. Examples of inline elements :  ``<span>, <img>, <strong>, <code>, <input>, <time>, <i>``.  |

<br>

## ✍ 27. What is the difference between a block-level element and an inline element?

