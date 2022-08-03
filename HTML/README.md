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
<br>

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

1. Inline - by using the `style` attribute inside HTML elements.

```html
<h1 style="color:blue;">A Blue Heading</h1>
```

2. Internal - by using a `<style>` element in the `<head>` section.

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      body {
        background-color: powderblue;
      }
      h1 {
        color: blue;
      }
      p {
        color: red;
      }
    </style>
  </head>
  <body>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

3. External - by using a `<link>` element to link to an external CSS file.

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles.css" />
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

1. `Ordered list` : which is used to group related items in a specific order
2. `Unordered list` : which is used to group related items in no particular order
3. `Description list` : which is used to group terms and their descriptions

<br>

## ✍ 19. What is the role of formatting tags in HTML?

Answer :

#### Formatting tags allow text to be stylized in HTML5 without the need for CSS. There are a number of HTML5 formatting tags, and the most popular ones include:

- `<b>` - used to make text bold
- `<i>` - used to italicize text
- `<u>` - used to underline text
- `<mark>` - used to highlight text
- `<strong>` - used to mark text as important

<br>

## ✍ 20. What are some of the most important APIs in HTML?

Answer :

#### HTML5 supports a wide range of APIs. Some of the most popular ones include:

- `Geolocation API` : used to identify the user’s location
- `Web Speech API` : which provides speech recognition functionality
- `Clipboard API` : which provides copy, cut, and paste functionality
- `History API` : which provides access to the browser navigation history
- `Web Notifications API` : used to send web-based notifications to users

<br>

## ✍ 21. What are the different types of storage in HTML?

Answer :

#### HTML5 supports two types of web storage. These are:

1. `sessionStorage` : temporary storage available for the duration of the page session
2. `localStorage` : permanent storage available until data is deleted by the user

<br>

## ✍ 22. What is metadata in HTML5 and how is it specified?

Answer :

Metadata is data that describes other data, providing additional information about an HTML document. Its purpose is to help browsers, search engines .

The `<meta>` tag is used to define metadata about an HTML document. `<meta>` tags are always enclosed within the `<head>` of the HTML document.

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

| HTML Elements                                                   | Tags                                                                               |
| --------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| 1. HTML Elements hold the content.                              | 1. HTML Tags hold the HTML element.                                                |
| 2. They specify the general content.                            | 2. HTML tags are like keywords. Each tag has a unique meaning.                     |
| 3. For example, `<p>` This is an example of a paragraph. `</p>` | 3. For example, `<a>` is an opening anchor tag and `</a>` is a closing anchor tag. |

<br>

## ✍ 26. What is the difference between a block-level element and an inline element?

Answer :

#### The differences between block-level elements and inline elements are:

<br>

| Block-level Elements                                                                            | Inline Elements                                                                                    |
| ----------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| 1. They start on a new line.                                                                    | 1. Do not start on a new line and can begin within a line.                                         |
| 2. Stretch to fill the full width available to them.                                            | 2. Take up as much width as necessary. Its width only extends as far as it is defined by its tags. |
| 3. They have a top and a bottom margin.                                                         | 3. Inline elements do not have a top and a bottom margin.                                          |
| 4. Examples of block-level elements in HTML : `<div>, <img>, <form>, <main>, <table>, <video>`. | 4. Examples of inline elements : `<span>, <img>, <strong>, <code>, <input>, <time>, <i>`.          |

<br>

## ✍ 27. What are void elements in HTML?

Answer :

HTML elements which do not have closing tags or do not need to be closed are Void elements. For Example `<br />, <img />, <hr />`, etc.

<br>

## ✍ 28. How can we create a new HTML element?

Answer :

We can even create new elements for the document as follows :

```js
<script>document.createElement﴾"myElement"﴿</script>
```

It can be used in the HTML as :

```html
<myElement>hello</myElement>
```

<br>

## ✍ 29. How can we create a new HTML element?

Answer :

The `<fieldset>` tag groups related form elements. It is like a box. In other words, it draws a box around related elements.

It must start with a `<legend>` tag because the `<legend>` tag defines the title of the fieldset.

Following is the Syntax of the `<fieldset>` tag in HTML5.

```html
<fieldset>Controls</fieldset>
```

<br>

## ✍ 30. Can we display a web page inside a web page or Is nesting of webpages possible?

Answer :

Yes, we can display a web page inside another HTML web page. HTML provides a tag `<iframe>` using which we can achieve this functionality.

```html
<iframe src="”url" of the web page to embed” />
```

<br>

## ✍ 31. In how many ways can we position an HTML element? Or what are the permissible values of the position attribute?

Answer :

There are mainly 7 values of position attribute that can be used to position an HTML element:

<br>

1. `static:` Default value. Here the element is positioned according to the normal flow of the document.
2. `absolute:` Here the element is positioned relative to its parent element. The final position is determined by the values of left, right, top, bottom.
3. `fixed:` This is similar to absolute except here the elements are positioned relative to the `<html>` element.
4. `relative:` Here the element is positioned according to the normal flow of the document and positioned relative to its original/ normal position.
5. `initial:` This resets the property to its default value.
6. `inherit:` Here the element inherits or takes the property of its parent.

<br>

## ✍ 32. What is the difference between `“display: none”` and `“visibility: hidden”`, when used as attributes to the HTML element.

Answer :

When we use the attribute “visibility: hidden” for an HTML element then that element will be hidden from the webpage but still takes up space. Whereas, if we use the “display: none” attribute for an HTML element then the element will be hidden, and also it won’t take up any space on the webpage.

<br>

## ✍ 33. How to specify the link in HTML and explain the target attribute?

Answer :

HTML provides a hyperlink - `<a>` tag to specify the links in a webpage. The ‘href’ attribute is used to specify the link and the ‘target’ attribute is used to specify, where do we want to open the linked document. The ‘target’ attribute can have the following values:

1. `_self:` This is a default value. It opens the document in 2.the same window or tab as it was clicked.
2. `_blank:` It opens the document in a new window or tab.
3. `_parent:` It opens the document in a parent frame.
4. `_top:` It opens the document in a full-body window.

<br>

## ✍ 34. Difference between link tag `<link>` and anchor tag `<a>`?

Answer :

The anchor tag `<a>` is used to create a hyperlink to another webpage or to a certain part of the webpage and these links are clickable, whereas, link tag `<link>` defines a link between a document and an external resource and these are not clickable.

<br>

## ✍ 35. How to include javascript code in HTML?

Answer :

HTML provides a `<script>` tag using which we can run the javascript code and make our HTML page more dynamic.

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>
      <span>This is a demo for </span>
      <u><span id="demo"></span></u>
    </h1>
    <script>
      document.getElementById("demo").innerHTML = "script Tag";
    </script>
  </body>
</html>
```

<br>

## ✍ 36. How to handle events in HTML?

Answer :

HTML allows event trigger actions in browsers using javascript or JQuery. There are a lot of events like `‘onclick’, ‘ondrag’, ‘onchange’,` etc.

```html
<!DOCTYPE html>
<html>
  <body style="padding-top:50px">
    <h3 id="event_demo">0</h3>
    <input type="button" onclick="myFunction()" value="Click Me" />
    <input type="reset" onclick="reset()" value="Reset" />
  </body>

  <script>
    function myFunction() {
      var value = document.getElementById("event_demo").innerHTML;
      value = parseInt(value) + 1;
      document.getElementById("event_demo").innerHTML = value;
    }
    function reset() {
      document.getElementById("event_demo").innerHTML = 0;
    }
  </script>
</html>
```

<br>

## ✍ 37. How to specify the metadata in HTML5?

Answer :

To specify we can use `<meta>` tag which is a void tag,i.e., it does not have a closing tag. Some of the attributes used with meta tags are name, content, http-equiv, etc. The below image tells how to specify the metadata.

```html
<head>
  <meta charset="UTF-8" />
  <meta name="description" content="Free Web tutorials" />
  <meta name="keywords" content="HTML, CSS, JavaScript" />
  <meta name="author" content="John Doe" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</head>
```

<br>

## ✍ 38. Is the `<datalist>` tag and `<select>` tag same?

Answer :

No. The `<datalist>` tag and `<select>` tag are different. In the case of `<select>` tag a user will have to choose from a list of options, whereas `<datalist>` when used along with the `<input> `tag provides a suggestion that the user selects one of the options given or can enter some entirely different value.


```html
<!DOCTYPE html>
<html>
  
<body>
    <h1>frontend-interview-mastery</h1>
    <h3>Using Datalist</h3>
    <label for="courses">
        Choose your favorite course from the list:
    </label>
      
    <input list="courses" name="course" id="course">
      
    <datalist id="courses">
        <option value="Java">
        <option value="C++">
        <option value="Python">
        <option value="DSA">
        <option value="ML and AI">
    </datalist>
  
    <p style="color: gray;">
        User can choose an option from a 
        given options <br>and also give 
        an input and filter values from 
        the option list.
    </p>
</body>
  
</html>
```

<br>

## ✍ 39. What are Semantic Elements?

Answer :

Semantic elements are those which describe the particular meaning to the browser and the developer. Elements like ``<form>, <table>, <article>,`` ``<figure>``, etc., are semantic elements.

<br>

## ✍ 40.  Which tag is used for representing the result of a calculation? Explain its attributes.

Answer :

The ``<output>`` tag is used for representing the result of a calculation. It has the following attributes:

- ``for -``  It defines the relationship between the elements used in calculation and result.
- ``form -`` This is used to define the form the output element belongs to.
- ``name -`` The name of the output element.

```html
<form oninput = "result.value=parseInt(n1.value)+parseInt(n2.value)">
     <input type = "number" name = "n1" value = "1" /> +
     <input type = "number" name = "n2" value = "2" /><br />
     The output is: <output name = "result"></output>
</form>
```

<br>

## ✍ 41.  Are ``<br>`` tags the only way to separate sections of text?

Answer :

No. The ``<br>`` tag is only one way to separate lines of text. Other tags, like the ``<p>`` tag and ``<blockquote>`` tag, also separate sections of text.

<br>

## ✍ 42. How can you apply CSS style using ID value in HTML?

Answer :

So let’s say you have a HTML paragraph tag with id “mytext” as shown in the below snippet.

```html
<p id="mytext">This is HTML interview questions.</p> 
```

You can create a style using “#” selector with the “id” name and apply the CSS value to the paragraph tag. So to apply style to “mytext” element we can use “#mytext” as shown in the below CSS code.

```html
<style>
#mytext
{
background-color:yellow;
}
</style>
```

<br>

## ✍ 42. What is the difference between ``<span>`` and ``<div>`` ?

Answer :

The difference is that span gives the output with ``display: inline`` and div gives the output with ``display: block``.

span is used when we need our elements to be shown in a line, one after the other.

<br>

## ✍ 43.  What is the difference between HTML elements and tags?

Answer :

Consider the following :

| Elements                                                                            | Tags                                                                                    |
| ----------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| The element is an individual component of the HTML web page or document. It represents semantics or meaning. For example, the title element represents the title of the document.                                                                    | It is the root of the HTML document which is used to specify that the document is HTML. For example, the Head tag is used to contain all the head element in the HTML file.                                         |

<br

## ✍ 44. What are Attributes and how do you use them?

Answer :

Each tag has additional attributes that change the way the tag behaves or is displayed. For example, a ``<input> ``tag has a type attribute, which you can use to specify whether it’s a text field, checkbox, radio button or one of many more options.
``Attributes`` are specified directly after the name of the ``tag``, inside the two angled brackets. They should only ever appear in opening tags or in self-closing tags. But, they can never be in ``closing tags``.

``Example:``

```html
<!-- Text field -->
<input type="text" />
<!-- Checkbox -->
<input type="checkbox" />
<!-- Radio button -->
<input type="radio" value="on" />
```

<br>

## ✍ 45. How to create a nested webpage in HTML?

Answer :

The HTML iframe tag is used to display a nested webpage. In other words, it represents a webpage within a webpage. The HTML ``<iframe>`` tag defines an inline frame. For example:

```html
<!DOCTYPE html>
<html>
<body>
<h2>HTML example</h2>
Use the height and width attributes to specify the size of the iframe:
<iframe src="<a href="https://www.edureka.co/">https://www.edureka.co/</a>" height="300" width="400"></iframe>
</body>
</html>
```

<br>

## ✍ 46. How to insert a picture into a background image of a web page?

Answer :

To insert a picture into the background image, you need to place a tag code after the </head> tag in the following way:

```html
<body background = “image.gif”>
  ```
  Now, replace image.gif with the name of your image file. This will take the picture and make it the background image of your web page.

  <br>

## ✍ 47. What happens if you open the external CSS file in a browser?
  
  Answer :

When you try to open the external CSS file in a browser, the browser cannot open the file, because the file has a different extension. The only way to use an external CSS file is to reference it using <link/> tag within another HTML document.

<br>

## ✍ 48. How do you create text on a webpage that allows you to send an email when clicked?

Answer :

To change the text into a clickable link to send an email, you need to use the mailto command within the href tag. You can write it in the following way:

```html
<a href=”mailto:youremailaddress”>text to be clicked</a>
```

<br>

## ✍ 49. What is Anchor tag and how can you open an URL into a new tab when clicked?

Answer :

Anchor tag in HTML is used to link between two sections or two different web pages or website templates.

To open an URL into a new tab in the browser upon a click, we need to add target attribute equal to ``_blank``.

```html
<a href=”#” target=”_blank”></a>
```

## ✍ 50. Can we modify the attribute’s value of the HTML tag dynamically?

Answer :

Yes, we can modify the value of the attributes by using JavaScript.

Below is the input element whose attribute will be modified from ``text`` to ``password`` , JS code to modify the attribute value:


```html
<input type=“text” id=“inputField”>
document.getElementById(“inputField”).attr(“type”, “password”);
```

<br>
<br>
<br>
<br>

<div align="center">

## Thanks for stay connected lovely readers
### For more →  [Continue](/README.md)


</div>