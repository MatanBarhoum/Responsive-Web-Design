# Learn Accessibility by Building a Quiz

<img src="Capture.PNG">

<h1>Class Notes</h1>
•	In form there’s 2 methods I should know about: POST and GET
<br>
•	Every element can have an accessibility to make things easier to disabled people. The role and the aria-labelledby. The role will be the What the element is about and the aria-labelledby will be the reference to the Element id.
aria-labelledby=”123”
<h1 id=”123”>123</h1> 
<br>
•	Label for will indicate what label is for what input.
<label for=”INPUT_ID”>
<input id=”INPUT_ID”>
  <br>
•	Every input should have id, type, value, name
  <br>
•	Pseudo property :before will add content before. For example. If I have p element that represent a question number, instead of writing Question #1, #2 and so on, I will create a property for p:before { content: “Question #” } and will only number the Questions accordingly.
  <br>
•	To remove underline of a text I will use Text-decoration: none;
  <br>
•	Using hover – element:hover
  <br>
•	Changing the cursor with cursor: value
  <br>
•	Accesskey attribute is using a shortcut (keyboard key) to focus on a element. (not best-practice, but sometimes necessarily) 
