# HTML
**What is HTML?**
1. HTML stands for Hyper Text Markup Language
2. HTML describes the structure of a Web page
3. The <<code>!DOCTYPE html</code>> declaration defines that this document is an **HTML5 document**.
4. The <<code>html</code>> element is the **root element** of an HTML page.
5. The <<code>head</code>> element contains **meta information** about the HTML page
6. The <<code>title</code>> element specifies a **title for the HTML page** (which is shown in the browser's title bar or in the page's tab)
7. The <<code>body</code>> element defines the document's body, and is a **container for all the visible contents**, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.

**What is an HTML Element?**
1. An HTML element is defined by a start tag, some content, and an end tag:
Example: <<code>p</code>>This is a paragraph      with no extra spaces<<code>/p</code>>
2. Unexpected results and errors may occur if you forget the end tag!
3. HTML elements with no content are called empty elements. The <br> tag defines a line break, and is an empty element without a closing tag.
4. HTML is Not Case Sensitive, but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.

**HTML Attributes:**
1. HTML attributes provide additional information about HTML elements.
2. Attributes are always specified in the start tag
3. Attributes usually come in name/value pairs like: name="value"
4. The style attribute is used to add styles to an element, such as color, font, size, and more.
5. The lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

**Web Browsers:**
1. The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to **read HTML documents and display them correctly**.

**HTML History:**
1. In 1989, **Tim Berners-Lee** invented **www**(world wide web).
2. In 1991,	Tim Berners-Lee invented **HTML**.

**How to save and run html files:**
*You can use either **.htm or .html** as file extension. There is no difference; it is up to you.*

**HTML Headings:**
1. HTML headings are defined with the <<code>h1</code>> to <<code>h6</code>> tags.
2. <<code>h1</code>> defines the **most important heading**. <<code>h6</code>> defines the **least important heading**.

**HTML Paragraphs:**
1. HTML paragraphs are defined with the <<code>p</code>> tag.
2. *Generally all other tags need ending tag mandatorily but in case of p it is ok to not close sometimes.*

**HTML Links:**
HTML links are hyperlinks. <br/>
Links are found in nearly all web pages. Links allow users to click their way from page to page. <br/>

<pre> By default, links will appear as follows in all browsers:
      An unvisited link is underlined and blue
      A visited link is underlined and purple
      An active link is underlined and red
  <strong>Tip:</strong> Links can of course be styled with CSS, to get another look! </pre>

1. HTML links are defined with the <<code>a</code>> tag.
2. href is used to link either external websites or internal html files. (example for linking google: <a href="www.google.com">google</a>).
3. Link to an Email Address, Use <code>mailto:</code> inside the <code>href</code> attribute to create a link that opens the user's email program (<a href="mailto:someone@example.com">Send email to someone@example.com</a>).
4. To use an HTML button as a link, you have to add some JavaScript code. JavaScript allows you to specify what happens at certain events, such as a click of a button (<button onclick="document.location='default.asp'">HTML Tutorial</button>)
5. Link Titles, The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.
(Example <a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>)
6. The target attribute can have one of the following values:
  <pre> <strong>_self</strong> - Default. Opens the document in the same window/tab as it was clicked
  <strong>_blank</strong> - Opens the document in a new window or tab
  <strong>_parent</strong> - Opens the document in the parent frame
  <strong>_top</strong> - Opens the document in the full body of the window. </pre>
7. For getting user assumed colors for a hyper link visit <a href="https://www.w3schools.com/html/html_links_colors.asp">HTML Links - Different Colors</a>
8. To Create a Bookmark in HTML:
<pre>Use the id attribute (id="value") to define bookmarks in a page
Use the href attribute (href="#value") to link to the bookmark or also (href="website.com#value")</pre>

**HTML Images:**
1. HTML images are defined with the <img> tag.
2. The source file (src), alternative text (alt), width, and height are provided as attributes.
<pre><strong>Note:</strong> Always specify the width and height of an image. If width and height are not specified, the web page might flicker while the image loads.</pre>
3. Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.
4. HTML allows animated GIFs. (just give the path of animated gif to src attribute).
5. Use the CSS float attribute or property to let the image float to the right or to the left of a text.
6. **Image Maps**: The HTML <<code>map</code>> tag defines an image map. An image map is an image with clickable areas. The areas are defined with one or more <<code>area</code>> tags.
7. The only difference from other images is that you must add a **usemap attribute**. The usemap value starts with a hash tag # followed by the name of the image map, and is used to create a relationship between the image and the image map.
<pre>You must define the shape of the clickable area, and you can choose one of these values:
rect - defines a rectangular region
circle - defines a circular region
poly - defines a polygonal region
default - defines the entire region
You must also define some coordinates to be able to place the clickable area onto the image. 
</pre>

**HTML Horizontal Rules:**
1. The <<code>hr</code>> tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.
2. The <<code>hr</code>> tag is an empty tag, which means that it has no end tag.

**HTML Line Breaks:**
1. The HTML <<code>br</code>> element defines a line break. (A new line).

**HTML <<code>pre</code>> Element:**
1. The HTML <<code>pre</code>> element defines preformatted text.
2. The text inside a <<code>pre</code>> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks.

**HTML Styles:**
1. The HTML style attribute is used to add styles to an element, such as color, font, size, and more.
2. Use the style attribute for styling HTML elements
3. Use background-color for background color.
4. Use color for text colors.
5. Use font-family for text fonts.
6. Use font-size for text sizes.
7. Use text-align for text alignment.
8. Use border for giving border to the element.

**HTML Formatting Elements:**
1. Formatting elements were designed to display special types of text:
2. <b> Bold text </b>
3. <strong> Important text </strong>
4. <i> Italic text </i>
5. <em> Emphasized text </em>
6. <mark> Marked text </mark>
7. <small> Smaller text </small> Normal Text
8. <del> Deleted text </del>
9. <ins> Inserted text </ins>
10. <sub> Subscript text </sub> Normal Text
11. <sup> Superscript text </sup> Normal Text

**HTML Quotation and Citation Elements:**
<a href="https://www.w3schools.com/html/html_quotation_elements.asp" target="_blank"> Visit this for reference </a>
1. the <<code>blockquote</code>>,<<code>q</code>>, <<code>abbr</code>>, <<code>address</code>>, <<code>cite</code>>, and <<code>bdo</code>> HTML elements.
2. The HTML <<code>blockquote</code>> element defines a section that is quoted from another source. Browsers usually indent <<code>blockquote</code>> elements.
    cite is the attribute for which the citation need to be provided.
3. The HTML <<code>q</code>> tag defines a short quotation. Browsers normally insert quotation marks around the quotation.
4. The HTML <<code>abbr</code>> tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM". 
    Marking abbreviations can give useful information to browsers, translation systems and search-engines.
    Tip: Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element. 
5. The HTML <<code>address</code>> tag defines the contact information for the author/owner of a document or an article.
    The contact information can be an email address, URL, physical address, phone number, social media handle, etc.
    The text in the <<code>address</code>> element usually renders in italic, and browsers will always add a line break before and after the <<code>address</code>> element.
6. The HTML <<code>cite</code>> tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).
    Note: A person's name is not the title of a work.
    The text in the <<code>cite</code>> element usually renders in italic.
7. BDO stands for Bi-Directional Override.
    The HTML <<code>bdo</code>> tag is used to override the current text direction.

**HTML Comment Tag:**
1. You can add comments to your HTML source by using the following syntax: <br/>
<<code>!-- Write your comments here --</code>>
2. Notice that there is an exclamation point (!) in the start tag, but not in the end tag.
3. Note: Comments are not displayed by the browser, but they can help document your HTML source code.

**HTML Colors:**
1. HTML colors are specified with predefined color names, or with **RGB, HEX, HSL, RGBA, or HSLA** values.
2. An **RGB** color value represents RED, GREEN, and BLUE light sources. An **RGBA** color value is an extension of RGB with an Alpha channel (opacity).
3. Each parameter (red, green, and blue) defines the intensity of the color with a value between 0 and 255. <br/>
    Note: You can get gray color by mentioning all the rgb values equal, and remember lesser the value more darker tone of gray it would be.
4. For **HEX**, a hexadecimal color is specified with: #RRGGBB, where the RR (red), GG (green) and BB (blue) hexadecimal integers specify the components of the color. <br/>
     Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).
5. **HSL** stands for hue, saturation, and lightness. **HSLA** color values are an extension of HSL with an Alpha channel (opacity).

**HTML Styles - CSS:**
Cascading Style Sheets (CSS) is used to format the layout of a webpage. <br/>
With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more! <br/>
1. Use the HTML style attribute for inline styling
2. Use the HTML <<code>style</code>> element to define internal CSS
3. Use the HTML <<code>link</code>> element to refer to an external CSS file
4. Use the HTML <<code>head</code>> element to store <<code>style</code>> and <<code>link</code>> elements
5. Use the CSS color property for text colors
6. Use the CSS font-family property for text fonts
7. Use the CSS font-size property for text sizes
8. Use the CSS text-decoration property to remove bold, italic, underline...
9. Use the CSS border property for borders
10. Use the CSS **padding** property for space inside the border
11. Use the CSS **margin** property for space outside the border

# Day-2
**HTML Images Continuation:**
1. To add a background image on an HTML element, use the HTML style attribute and the CSS background-image property.
2. If you want the entire page to have a background image, you must specify the background image on the <body> element.
3. If the background image is smaller than the element, the image will repeat itself, horizontally and vertically, until it reaches the end of the element.
4. To avoid the background image from repeating itself, set the background-repeat property to no-repeat.
5. If you want the background image to cover the entire element, you can set the background-size property to cover.
6. Also, to make sure the entire element is always covered, set the background-attachment property to fixed, This way, the background image will cover the entire element, with no stretching (the image will keep its original proportions)
7. If you want the background image to stretch to fit the entire element, you can set the background-size property to 100% 100%, Try resizing the browser window, and you will see that the image will stretch, but always cover the entire element.
8. The HTML <<code>picture</code>> element allows you to display different pictures for different devices or screen sizes.
9. The <<code>picture</code>> element contains one or more <<code>source</code>> elements, each referring to different images through the <code>srcset</code> attribute. This way the browser can choose the image that best fits the current view and/or device.
10. Each <<code>source</code>> element has a <code>media</code> attribute that defines when the image is the most suitable. <br/>

**Note:** Always specify an <<code>img</code>> element as the last child element of the <<code>picture</code>> element. The <<code>img</code>> element is used by browsers that do not support the <<code>picture</code>> element, or if none of the <<code>source</code>> tags match.

**HTML Tables:**
1. HTML tables allow web developers to arrange data into rows and columns.
2. **Table Rows:** Each table row starts with a <<code>tr</code>> and ends with a <<code>/tr</code>> tag. tr stands for **table row.**
3. You can have as many rows as you like in a table; just make sure that the number of cells are the same in each row. There are times when a row can have less or more cells than another.
4. **Table Cells:** Each table cell is defined by a <<code>td</code>> and a <<code>/td</code>> tag. td stands for **table data.**
5. **Note:** A table cell can contain all sorts of HTML elements: text, images, lists, links, other tables, etc.
6. **Table Headers:** Sometimes you want your cells to be table header cells. In those cases use the <<code>th</code>> tag instead of the <<code>td</code>> tag: th stands for **table header.**
7. By default, the text in <<code>th</code>> elements are **bold and centered**, but you can change that with CSS.
8. HTML tables can have **borders of different styles and shapes**, To add a border, use the CSS border property on table, th, and td elements.
9. **Collapsed Table Borders:** To avoid having double borders set the CSS **border-collapse property to collapse**.
    Example:
         table, th, td {
              border: 1px solid black;
              border-collapse: collapse;
         }
10. If you set a background color of each cell, and give the border a white color (the same as the document background), you get the impression of an invisible border.
11. With the **border-radius property**, the borders get rounded corners.
12. With the **border-style property**, you can set the appearance of the border, below are some examples:
      **dotted
      dashed
      solid
      double
      groove
      ridge
      inset
      outset
      none
      hidden**
14. With the **border-color property**, you can set the color of the border.
15. HTML tables can have different sizes for each column, row or the entire table. Use the <code>style</code> attribute with the <code>width</code> or <code>height</code> properties to specify the size of a table, row or column.
16. Cell padding is the space between the cell edges and the cell content. By default the padding is set to 0, You can change it using CSS.
17. Cell spacing is the space between each cell. By default the space is set to 2 pixels. To change the space between table cells, use the CSS border-spacing property on the table element.
18. HTML tables can have cells that span over multiple rows and/or columns. <br/>
      To make a cell span over multiple columns, use the <code>colspan attribute.</code> <br/>
      **Note: The value of the colspan attribute represents the number of columns to span.** <br/>
      To make a cell span over multiple rows, use the <code>rowspan attribute</code> <br/>
      **Note: The value of the rowspan attribute represents the number of rows to span.**

Some other useful tags of table are:
1. <<code>caption</code>> Defines a table caption. <br/>
Note: The <caption> tag should be inserted immediately after the <table> tag.
2. <<code>colgroup</code>> Specifies a group of one or more columns in a table for formatting.
3. <<code>col</code>> Specifies column properties for each column within a <<code>colgroup</code>> element.
4. <<code>thead</code>> Groups the header content in a table.
5. <<code>tbody</code>> Groups the body content in a table.
6. <<code>tfoot</code>> Groups the footer content in a table.


**HTML Table - Zebra Stripes, Horizontal Dividers, Hoverable Table:**
<a href="https://www.w3schools.com/html/html_table_styling.asp" target="_blank"> Visit this page </a> <br/>

**HTML Table Colgroup:**
<a href="https://www.w3schools.com/html/html_table_colgroup.asp" target="_blank"> Visit this page </a> <br/>

**HTML Lists:**
1. <<code>ul</code>>	Defines an unordered list (The list items will be marked with bullets (small black circles) by default.) <br/>
      The list items will be marked with bullets (small black circles) by default:<br/>
         1. disc	      Sets the list item marker to a bullet (default)
         2. circle	Sets the list item marker to a circle
         3. square	Sets the list item marker to a square
         4. none	      The list items will not be marked

3. <<code>ol</code>>	Defines an ordered list
4. <<code>li</code>>	Defines a list item
5. <<code>dl</code>>	Defines a description list
6. <<code>dt</code>>	Defines a term in a description list
7. <<code>dd</code>>	Describes the term in a description list

<pre>Note: A list item (<<code>li</code>>) can contain a new list, and other HTML elements, like images and links, etc.</pre>

**Horizontal List with CSS: (for creating nav bars)**
1. Use the CSS property float:left to display a list horizontally
