# WEB PAGE
<!DOCTYPE html>
<html>
<head> 
<title>INFORMATION TECHNOLOGY</title>
<style>
dl{color:blue}
d1{color:red}
tr{background-color:green}
*{background-color:#f7f7f087}
</style>
</head>
<body>
<marquee behavior="alternate" style="text-align:center;font-size:50px;color:blue;padding:30px">welcome to our webpage </marquee><hr>
<h2 style="background-color:rgba(228, 14, 139, 0.89);font-size:39px">12th std Information Technology 1st lesson some basic concept:-<h2><br><hr>
<dl><b>advanced web designing:-</b></dl>
<dd>we have been introduced to basic terminologies related to creation of web 
pages. the hypertext mark-up language(HTML) is an evolving language,
with different version supporting different features.
HTML5 is currently used beacuse it supports mobile technology.</dd><br> 
<dl><b>id:-</b></dl>
<dd>This is used to identify the html element uniguely through the document object
model.</dd><br>
<dl><b>class:-</b></dl>
<dd>It is used to apply CSS style to the
individual input element.</dd><br>
<dl><b>Cascading style sheets in HTML5:- </b></dl>
<dd>CSS stand for cascading style sheets. CSS describe how HTML elements are to be displayed on screen, paper,or in other media. CSS save a lot
of work. It can control the layout of multiple web pages all at once. CSS allows you to control the look and feel of several pages by changing 
a single source.</dd><br><br>
<dl><b>Type of CSS:-</b></dl> 
<dd>there are three methods of implementing styling information to an HTML document. </dd>
<ol>
<li>Inline CSS </li>
<li>Embedded stylesheet or  Internal CSS	</li>
<li>external CSS</li>
</ol>
<ol>
<li><d1>Inline stylesheet:</d1> It uses the style attribute in the HTML start tag. Inline CSS is used to apply CSS on a single line or element.</li><br>
<li><d1>Embedded stylesheet or internal CSS:</d1> This is used to apply CSS an a single document or page . it can affect all the element of the page . it can affect all the element of the page. it is written inside the style tag within head section of html.</li><br>
<h1 style="text-align:center;color:#d01884ff">CSS Properties </h1>
<table border="4" style="text-align:center;;font-size:30px">
<tr style="background-color:orange"><th>Property</th>
<th style="background-color:orange">Use</th>
<th style="background-color:orange">value</th>
<th style="background-color:orange">Example</th></tr>
<tr> <td>Color</td> <td>Change the color of the text</td> <td>Color name</td> <td>h1{color:maroon}</td></tr>
<tr> <td>Background-color</td> <td>To set the background color in your webpage</td> <td>Color name</td> <td>body{background-color:yellow}</td></tr>
<tr> <td>Font-weight</td> <td>Used to bold text </td> <td>bold or 100,200...900</td> <td>p{font-weight:300}</td></tr>
<tr> <td>Font-style</td> <td>used to italicize text</td> <td>Italic,oblique or normal</td> <td>p{font-style:italic}</td></tr> 
<tr> <td>Text-decoration</td> <td>This property is used to add <ol><li>strike-through marks</li> <li>underline</li> <li>overstrike</li> <li>to remove underline from links</li></ol></td> <td><ol> <li>line-through</li> <li>underline</li> <li>overline</li> <li>none</li></ol></td> <td>p{text-decoration:underline}<br>a{text-decoration:none}</td></tr>
<tr> <td>Text-align</td> <td>This property is used to control the horizontal alignment of any block-level text that are paragraph, tables and other elements</td> <td>left,right,center or justify</td> <td>h1{text-align:center}</td></tr>
<tr> <td>Font-family</td> <td>This is used to control the font</td> <td>Font name</td> <td>p{font-family:arial}</td></tr>
<tr> <td>Font-size</td> <td>This property allows you to control the size of the font</td> <td>px,in,mm,cm,pt</td> <td>p{font-size:10px}</td></tr>
<tr> <td>Letter-spacing</td> <td>This helps in controlling the horizontal spacing between characters of text</td> <td>px,in,mm,cm,pt</td> <td>h1{letter-spacing:5pt}</td></tr>
<tr> <td>Padding</td> <td>This property is used when you want to add padding (black space) around the content of an element.</td> <td>pixel</td> <td>l1{padding:30px}</td></tr>
<tr> <td>border</td> <td>This property adds a border to a webpage element</td> <td>Solid,double,groove,ridge,inset,outset,dotted or dashed</td> <td>h1{border:double}</td></tr>
<tr> <td>Background-image</td> <td>To set an image as the background of your webpage</td> <td>url("X") where X is the path of image file</td> <td>body{background-image:url('background.jpg')}</td></tr>
<tr> <td>Background-repeat</td> <td>To set the background image to repeat or not</td> <td>repeat no-repeat</td> <td>background-repeat:repeat   background-repeat:no-repeat</td></tr>
<tr> <td>Margin-left</td> <td>Sets margin area on the left side of the element.</td> <td>px,pt,cm etc.</td> <td>h1{margin-left;10px}</td></tr>
</table><br><br><br>
<li><d1>External stylesheet :</d1> the external style sheet is generally used when you want to make changes on multiple pages.It facilitates to changes the look of the entire web site by changing just one file . It uses the "link tag" on every page and the "link tag" should be put inside the head section.<br> An external style sheet can be written in any text editor, and must be saved with a .css extention. the external css file should not contain any HTML tags. </li> 
</ol><br><br>
<dl><b>CSS Id selector:-</b></dl>
<dd>The Id selector select the id attribute of an  HTML element to select a specific element.An id is always unique within the page so it is unique element . It is written with the hash character(#), followed by the id name.
</dd><br><br>
<dl><b>CSS class selector:</b></dl>
<dd>The class selector select HTML element with a specific class attribute . It is used with a period character '.'(full stop symbol) followed by the class name.The class selector is used when you want to change a group of elements within your HTML page. <br> The class name should not start with number.</dd><br><br>
<d1>class selecter for specific element (*)</d1><dd>To specify only specific HTML element should be affected then you should use the element name with class selector.</dd><br><br>
<d1>Universal selector </d1><dd>The universal selector is used as a wildcard character. it select all the element on the webpages. </dd><br><br><br>
<dl><b>Group selector</b></dl>
<dd>The grouping selector is used to select all the element with the same style all the element with the same style definitions. It is used to minimize the code . commas are used to seperate each selector in grouping. <br> let's see the CSS code without grouping selector.<br>
<ul>
<li>h1{text-align:center;color:blue}</li>
<li>h2{text-align:center;color:blue}</li>
<li>p{text-align:center;color:blue}</li><br><br>
As you can see , you need to define CSS properties for all the elements. it can be grouped as-</dd><br>
<li>h1,h2,p{text-align:center;color:blue}</li>
</ul><br><br><br>
<dl><b>Positioning in CSS</b></dl>
<dd> CSS help to position the HTML element . the position property is used to set position for an element . The element can be positioned using the top , bottom, left and right properties.</dd>
<d1>syntax</d1>
<dd><b>selector{position:value;top:values;<br>left:value:bottom:value;right:value}</b></dd><br>
<dd><b> where value in poisitions are fixed , absolute , relative and values of top , bottom , left , right are in pixels</b></dd><br><br>
<d1><b>There are four types of positioning in CSS</b></d1> <br>
<ol>
<li><d1>static positioning</d1><dd>this is a by-default
position for HTML elements. It is not affected by the top , bottom , left and right properties </dd></li>
<li><d1>Fixed positioning :</d1><dd>This properity hepls to put the text fixed on the browser.THE FIXED properity forces an element into a fixed position relative to the browser window. The fixed element will not move , even when the page is scrolled. </dd></li>
</ol><br><br><br><hr>
<marquee behavior="alternate" style="text-align:center;font-size:40px;color:blue;padding:20px">JAI SHREE RAM🚩🚩🚩🚩 RADHE RADHE </marquee><hr>
<h1 style="color:blue;text-align:center;font-size:20px">TO BE CONTINUE...........</h1>
<h2> THE WEB PAGE IS CLASS 12TH FIRST LESSON BASIC KNOWLEDGE </h2><br>
<h2> THE WEB PAGE IS MADE BY "PANDEY DEVESH MANIKCHANDRA " </h2><br>
</body>
</html>
