# First_html
Trying to make my first website with the help of code camp, I will add new feautures as I learn from code camp. I am unsure about what website I want to make but I want it to be related to languages
9 April 2025
Learnt about <h/headings>, <body>, <main>, void elements (open element without a closing tag e.g <img>), html attributes (words next to the opening tag that determine the behaviour of the thing [forgot the name]). <img src="Link of something" alt = "Alternate name for the thing">, <a href = ...> (links another page)
Step 1 - 11, Learn HTML by Building a Cat Photo App, 14% Completed
10 April 2025
*'target = "_blank"' attribute opens links on a new tab
*Can turn an image into a link by nesting it in an anchor
*<ul> creates an unordered list of items. use <li> before naming an item in the list. The difference between an orderlist <ol> and an unordered one <ul> is the
fact that an ordered list is numbered
*<figure> into <figcaption>....</figca...></fig...> allows you give a picture a caption
*Can place emphasis on a word using <em> element, more of an italic. The <strong> does the same but is in bold
*<form> creates a platform for the user to add information to. you give it an action element to indicate where that said information goes to.
e.g. <form action="/submit-url"></form>
*use <input>
to create the textbox for user info <input> is a void element. Can add an attributes to the <input>. 'Type' determines the way the text box appears
to the user, 'name' describes the type of information you will be collecting from said textbox, 'placeholder' gives the user hints as to what value to enter,
'required' makes the input mandatory
e.g<input type="text" name = "name" placeholder = "Your name" required>.
*<button> Self explanatory. The defualt action of clicking a button sends the information to the intended location e.g "/submit-url"
Add type to button to avoid any mishaps e.g <button type = "submit">
Step 12 - 45, 63% completed
11 April 2025
*<input type = "radio">, if you put a <label> on a radio button it will make pressing the radio button press the actual button
*the attribute "id" helps you uniquely identify elements
*to stop radio buttons from being selected at the same time/clicking one deslects the other. You give them a "name" attribute and give them the same value
*If a user wants to submit a form, the form automatically reads whatever is in the "value" attribute, so you give the element a value attribute
*<fieldset> groups related elements seperately
*<legend> is used to give a fieldset a heading
*"checkbox" attribute 
*void attribute "checked" to make radio or checkbox ticked
*<footer> element usually contains information about the author of the website
*Metadata is information about the page that isnt displayed directly on the page like the tite and the style, you put this inside a <head> element
*<title> is what shows up on the tab for your website
*<!DOCTYPE html><html><head><body> is the order of your document at the moment
*an attribute called "lang" can be added to the html
*<meta> determines a browsers behaviour
*<meta charset = "utf-8"> tells the website to encode characters on the page
Cat Photo App, 100% COMPLETED
12 April 2025
*For CSS, add <style> element to the <head> section
*In <style> element you can bring up existing values to add changes to them. 
element {
 property: value;
}
*You can just use comma if you want to apply to same style to multiple things
*Now you need to link the styles.css file, so the styles will be applied again. Inside the head element, add a link element. Give it a rel attribute with the value of "stylesheet" and an href attribute with the value of "styles.css".

Note that the link element is a void element.
*Use this code to make the browser adjust to the device the user is on. <meta name="viewport" content="width=device-width, initial-scale=1.0" />
learn-basic-css-by-building-a-cafe-menu-panel, 21% completed
13 April 2025
*use hash to specify an id when using a css
*use a class attribute instead of an id attribute in a div element for...reasons
*specify is with dot in css
*article elements commonly contain multiple elements that have related information.
*.item p{display:inline-block}
*{padding-left/right etc} creates borders around something
*{font-family} changes the font
*background-image
*{text-align} moves text
* a fallback is a failsafe for if the original option isnt found, just use a comma after stating the intented value
learn-basic-css-by-building-a-cafe-menu-panel, 67% completed
14 April 2025
learn-basic-css-by-building-a-cafe-menu-panel, 100% completed
15 April 2025
*You can have multiple meta elements on a web page. Each meta element adds information about the page that cannot be expressed by other HTML elements.

Add another meta element within the head. Give it a name attribute set to "viewport" and a content attribute set to "width=device-width, initial-scale=1.0" so your page looks the same on all devices.
*Nest a link element within the head element. Give it a rel attribute set to "stylesheet" and an href attribute set to "styles.css".
*When the shorthand margin property has two values, it sets margin-top and margin-bottom to the first value, and margin-left and margin-right to the second value.
Learn CSS Colors by Building a Set of Colored Markers
34% complete
17 April 2025
* background: linear-gradient(90deg, rgb(255, 0, 0), rgb(0, 255, 0));
* * background: linear-gradient(90deg, rgb(255, 0, 0) 75%, rgb(0, 255, 0)) to add how much space the color will occupy;
29 April 2025
*deg specifies gradient direction, without gradient direction it is sorted from top to bottom
*Opacity describes how opaque, or non-transparent, something is. For example, a solid wall is opaque, and no light can pass through. But a drinking glass is much more transparent, and you can see through the glass to the other side.

With the CSS opacity property, you can control how opaque or transparent an element is. With the value 0, or 0%, the element will be completely transparent, and at 1.0, or 100%, the element will be completely opaque like it is by default.
