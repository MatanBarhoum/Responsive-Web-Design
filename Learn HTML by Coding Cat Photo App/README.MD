# Class notes 
<br>
HTML Class :
1.	H1, H2 .. have an hierarchy. H1 should be your title and H2 should be your 2nd title.
For example :
Cats
cats photos
<br>
2.	Img figures – if you want to put an caption for an image your should contain the image in a <figure> </figure> element and then call the <figcaption> </figcaption> element.
you can also put some words In <em> </em> elements. <strong> is similar to <em> but do the similar action as <b>
<br>
3.	There are 2 types of lists, UL = unordered list and OL = Ordered List.
They should start with <ol> </ol> and inside them should be <il></il> nested.
For example for ordered list : 
<ol> (Can be replaced with ul)
     <li>Item 1</li>
     <li>Item 2</li>
</ol>  (Can be replaced with ul)
<br>
4.	When calling an <a> (anchor) element there few things to know :
alt and target.
alt is the description of a link and target is how the link should be opened.
A target = “_blank” mean in a new windows.
<br>
5.	Forms Element - 
Forms need to have a target inside their element to declare where to send the data.
for example <form target=”dataProccessor.php”> will send the data to an php page called “DataProccessor”.
<br>
6.	An input element do not need a closing tag, and open a textbox to the user to input words or links (whatever they want) and Is similar to TextBox in powershell or c#.
inside an input element we can add an attributes. These attributes are to be added using the “Type” attribute. Type attribute can be Text for texts, Password for password fields, Reset for reset button and control for picking files, radio for radio buttons.
Label elements help the input / radio buttons to be clickable and read-able.
<label> <input type=”radio”> Cats </label> will make clicking on cats also as clicking the radio button.
ID attribute is used to define an input or element as unique and can be used more than once.
For example: <input Type=”Text”> or <input type=”password”>
Name attribute define how the data sent to the “Action” in the Forms element. Therefore we need to declare a name which is match in the Action file we send the data to. 
Name is also used for identifiers. For example, we have 4 radio buttons as input element and we want that when user pick a radio button and want to replace it, it will let him pick only one and switch. If the name on the Name=”123” will be the same, it will happen.
Placeholder is an attribute to let users understand what type of data do we want them to process. For example we create a new input element, with a type and a name and then a placeholder so they understand what they are needed to fill.
For example: <input type=”password” name=”password” placeholder=”Your password”>
Required attribute define if a field is a required field or not.
Value is important attribute to how the submit button will send the data. Without him the button will send the data with the name only and this is not useful with multiple buttons.
Checked is used to check by default an option on the label.
<br>
7.	Fieldset element is used to enclose with border an selected inputs or radio button of your choice. 
The Legend element should be inside and nested above the inputs and is used to tell the users a question or info about what they should do. 

