# Html_Foundation, <Read more: https://html.com/#ixzz8LKL86alE>
HTML is the language in which most websites are written. HTML is used to create pages and make them functional.

Hypertext means that the document contains links that allow the reader to jump to other places in the document or to another document altogether. The latest version is known as HTML5.

A Markup Language is a way that computers speak to each other to control how text is processed and presented. To do this HTML uses two things: ## tags and ## attributes

## What Are HTML Tags?
Tags are used to mark up the start of an HTML element and they are usually enclosed in angle brackets. An example of a tag is: <h1>.

Most tags must be opened <h1> and closed </h1> in order to function.

## What are HTML Attributes?
Attributes contain additional pieces of information. Attributes take the form of an opening tag and additional info is placed inside.

An example of an attribute is:

<img src="mydog.jpg" alt="A photo of my dog.">

In this instance, the image source (src) and the alt text (alt) are attributes of the <img> tag.

## Element	Meaning	Purpose
<b>	          Bold	                   Highlight important information
<strong>	    Strong                   Similarly to bold, to highlight key text
<i>	          Italic	                 To denote text
<em>         	Emphasised Text	         Usually used as image captions
<mark>	       Marked Text	           Highlight the background of the text
<small>	      Small Text	             To shrink the text
<strike>	     Striked Out Text       	To place a horizontal line across the text
<u>	           Underlined Text	        Used for links or text highlights
<ins>	         Inserted Text	           Displayed with an underline to show an inserted text
<sub>	         Subscript Text	            Typographical stylistic choice
<sup>	         Superscript Text         	Another typographical present choice

## The Anchor Tag
The <a> (or anchor) opening tag is written in the format:

<a href="https://blogging.com/how-to-start-a-blog/">Your Link Text Here </a>

The first part of the attribute points to the page that will open once the link is clicked.

Meanwhile, the second part of the attribute contains the text which will be displayed to a visitor in order to entice them to click on that link.

If you are building your own website then you will most likely host all of your pages on professional web hosting. In this case, internal links on your website will     <a href=”mylinkedpage.html”>Linktle Here</a>.

## Create an Anchor TAG

Let’s try it out. Make a duplicate of the code from your current index.html page. Copy / paste it into a new window in your HTML editor.
Save this new page as “page2.html” and ensure that it is saved in the same folder as your index.html page.

On page2.html add the following code:

<a href="http://www.google.com">Google</a>

This will create a link to Google on page 2. Hit save and return to your index.html page.

On a new line on index.html add the following code:

<a href="*folder(s)*/page2.html">Page2</a>

Ensure the folder path to the file (page2.html) is correct. Hit save and preview index.html in your browser.

If everything is correct then you will see a link which will take you to your second page. On the second page, there will be a link that will take you to google.com.

## how to ADD Image on HTML
<img src="yourimage.jpg" alt="Describe the image" height="X" width="X">

## HTML Attributes
   ## The Href Attribute
the hyper link attribute-href
<a href="https://www.w3schools.com">Visit W3Schools</a>
   ## The src Attribute
The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:
<img src="img_girl.jpg">

There are two ways to specify the URL in the src attribute:

  ## Absolute URL - Links to an external image that is hosted on another website. 
  Example: <image src="https://www.w3schools.com/images/img_girl.jpg" />.

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

  ## Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. 
  Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. 
  Example: src="/images/img_girl.jpg".

Tip: It is almost always best to use relative URLs. They will not break if you change domain.

  ## The alt Attribute
The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.
Example
<img src="img_girl.jpg" alt="Girl with a jacket"

   ## The width and height Attributes
The <img> tag should also contain the width and height attributes, which specify the width and height of the image 
(in pixels):
<img src="img_girl.jpg" width="500px" height="600px">

   ##The style Attribute
The style attribute is used to add styles to an element, such as color, font, size, and more.
<p style="color:red;">This is a red paragraph.</p>

   ## The lang Attribute
You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

   ## The title Attribute
The title attribute defines some extra information about an element.
The value of the title attribute will be displayed as a tooltip when you mouse over the element:
<p title="I'm a tooltip">This is a paragraph.</p>

## Chapter Summary
All HTML elements can have attributes
The href attribute of <a> specifies the URL of the page the link goes to
The src attribute of <img> specifies the path to the image to be displayed
The width and height attributes of <img> provide size information for images
The alt attribute of <img> provides an alternate text for an image
The style attribute is used to add styles to an element, such as color, font, size, and more
The lang attribute of the <html> tag declares the language of the Web page
The title attribute defines some extra information about an element


