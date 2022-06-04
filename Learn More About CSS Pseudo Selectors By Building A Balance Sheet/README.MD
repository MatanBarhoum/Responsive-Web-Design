# Learn More About CSS Pseudo Selectors By Building A Balance Sheet

<img src="Capture.PNG">

<h1>Class notes</h1>
•	Aria-hidden will hide element from the screen reader. 
<br>
•	Table element should have the caption element to describe what the table is about.
This can also be used within the css property of caption-side.
<br>
•	Thead and tbody element are used to indicate which portion of tour table is the header, wand which portion is the body (aka data).
<br>
•	“tr” element is used to indicate a table row.
<br>
within a td (table data) and th (table header) will be nested.
<br>
•	A proper build of a table should be as follow :
<br>
“table”
<br>
“caption” “/caption”
<br>
“thead” “/thead”
<br>
“tbody”
<br>
“tr” 
<br>
“th” “/th”
<br>
“td” “/td”
<br>
“/tr”
<br>
“/tbody”
 <br>
 “/table”
•	I can use CSS to make element with a class completely hidden from visual page but not from screen readers.
For example, span[class~=”sr-only”] will select any span element whose class includes sr-only.
<br>
•	Css first-of-type and last-of-type will target the first and last of that element.
<br>
•	CSS calc() function allow to calculate a value based on other values.
<br>
•	I can target elements with #id element[class] and it will target every element that have a class regardless of the attribute. 
<br>
•	!important before the ; will make sure the property will not be override.
<br>
•	The :nth-of-type() pseudo-selector is used to target specific elemnts baed of their order among sibligns of the same type. (tr.total td:nth-of-type(3))
<br>
•	Vertical-align and text-align
