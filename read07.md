 # **About CSS:**
## introduction:
![about html and css](https://images.tynker.com/blog/wp-content/uploads/20190226100225/02-25-2018-html-css-announcement-blog.png)

**What is CSS?** CSS is the language for describing the presentation of Web pages, including colors, layout, and fonts. It allows one to adapt the presentation to different types of devices, such as large screens, small screens, or printers. CSS is independent of HTML and can be used with any XML-based markup language.

**CSS** stands for Cascading Style Sheets with an emphasis placed on “Style.” While HTML is used to structure a web document (defining things like headlines and paragraphs, and allowing you to embed images, video, and other media), **CSS** comes through and specifies your document's style—page layouts, colors, and fonts are ..

* How i can connect the css inside the HTML
<link href  "thename of file.css rel"stylesheet" type="text/css"/>

* CSS Associates Style ruleswith HTML elements

 * Understanding external, internal, and inline CSS styles:

 **Cascading Style Sheets (CSS)** are files with styling rules that govern how your website is presented on screen. CSS rules can be applied to your website’s HTML files in various ways. You can use an external stylesheet, an internal stylesheet, or an inline style. Each method has advantages that suit particular uses.

1- **An external stylesheet** is a standalone .css file that is linked from a web page. The advantage of external stylesheets is that it can be created once and the rules applied to multiple web pages. Should you need to make widespread changes to your site design, you can make a single change in the stylesheet and it will be applied to all linked pages, saving time and effort.

2- **An internal stylesheet** holds CSS rules for the page in the head section of the HTML file. The rules only apply to that page, but you can configure CSS classes and IDs that can be used to style multiple elements in the page code. Again, a single change to the CSS rule will apply to all tagged elements on the page.

3- **Inline styles** relate to a specific HTML tag, using a style attribute with a CSS rule to style a specific page element. They’re useful for quick, permanent changes, but are less flexible than external and internal stylesheets as each inline style you create must be separately edited should you decide to make a design change.

An HTML page styled by an external CSS stylesheet must reference the .css file in the document head. Once created, the CSS file must be uploaded to your server and linked in the HTML file with code such as:

**<link href="style.css" rel="stylesheet" type="text/css">**

* Using internal CSS stylesheets
Rather than linking an external .css file, HTML files using an internal stylesheet include a set of rules in their head section. CSS rules are wrapped in <style> tags, like this**
<head>
<style type="text/css">

    h1 {
            color:#fff
            margin-left: 20px;
       }

    p {
        font-family: Arial, Helvetica, Sans Serif;     
       }


</style>
</head>

* Using inline styles
Inline styles are applied directly to an element in your HTML code. They use the style attribute, followed by regular CSS properties.

**For example:**

<h1 style="color:red;margin-left:20px;">Today’s Update</h1>

* how to write the a style in html
p {
 font-family: Arial;}

 * CSS Properties Affect  how element are Displayed

h1, h2, h3 {
 font-family: Arial;
 color: yellow;}


 ## About a color using css:
 * The color property allows you 
to specify the color of text inside 
an element. You can specify any 
color in CSS in one of three ways:
1-rgb values like :    **h1 {
color: Green;}** 
2-hex codes like: ** h2 {
color: #ee3e80;}**
3-color names like: **p {
color: rgb(0,128,0);} **


