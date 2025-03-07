
# Full Stack Wed Development

## Hyper Text Mark-Up Language(HTML) :-
HTML is a code that defines the structure and content of web pages. It's the basic building block of the web and is used by all major web browsers. 

### Heading Element :-
In HTML, "heading elements" are tags like "h1,h2,h3,h4,h5,h6". which are used to define different levels of titles or headings on a webpage.

### Example Code :-
		<h1>Book</h1>
		<h2>Chapter 1</h2>
		<h3>Section 1</h3>
		<h3>Section 2</h3>
		<h2>Chapter 2</h2>
		<h3>Section 1</h3>
		<h4>Diagram 1</h4>
		<h2>Chapter 3</h2>
		<h3>Section 1</h3>
		<h3>Section 2</h3>


### Output :-
![image](https://github.com/user-attachments/assets/014c4042-4f20-46e3-9c5c-4d7733b74c7e)


### Paragraph Element :-
A "paragraph element" is simply a piece of code in website design (HTML) that tells the browser to display a block of text as a separate paragraph.

### Example Code :-
	<p> Hi this Rajesh from VIGNAN UNIVERSITY’S.</p><p>I am studying BCA in your college. </p>

### output :-
![image](https://github.com/user-attachments/assets/695463e9-701a-4af5-90d8-1d0e18c1b648)

### Void Elements :-
In HTML, a void element is an HTML tag that doesn't require an end tag because it can't contain any content. They are also known as empty or self-closing tags.

### Example Code :-
	<h1>William Blake</h1> 
	
	<p>17 south molton street<br>
	London<br>
	W1K 5QT<br>
	UK</p>
	
	<hr />
	
	<p>William Blake (28 November 1757 – 12 August 1827) was an English poet, painter, and printmaker. Largely unrecognised
	during his life, Blake is now considered a seminal figure in the history of the poetry and visual art of the Romantic
	Age. human existence itself".[7]</p>
	
	<p>Although Blake was considered mad by contemporaries for his idiosyncratic views, he is held in high regard by later
	critics for his expressiveness and creativity, and for the philosophical and mystical undercurrents within his work. His
	 Rossetti characterised him as a "glorious luminary",[13] and "a man not
	forestalled by predecessors, nor to be classed with contemporaries, nor to be replaced by known or readily surmisable
	successors".[14]</p>

### Output :-
![image](https://github.com/user-attachments/assets/a51ed035-db1c-4a88-913b-2df567862d89)

## The List Elements :-
2-Types of List Elements

### Unordered List :-
An "unordered list" is simply a list of items displayed with bullet points.

 ### Eaxmple Code :-
	 <ul>
	  <li>¾ cup warm milk</li>
	  <li>2 ¼ teaspoons yeast </li>
	  <li>¼ cup granulated sugar</li>
	  <li>1 egg plus 1 egg yolk</li>
	  <li>¼ cup butter</li>
	  <li>3 cups bread flour</li>
	</ul>

### Output :-
![image](https://github.com/user-attachments/assets/b101850a-c34e-44e5-bf50-20c3cf4e286f)

### Ordered List :-
An ordered list typically is a numbered list of items.

 ### Example Code :-
	 <ol>
	  <li>Mix the milk with the yeast, sugar, eggs.</li>
	  <li>Melt the butter and add to the mixture.</li>
	  <li>Add in the flour and mix until combined into a dough.</li>
	  <li>Knead the dough for 10 minuites.</li>
	  <li>Transfer the dough into a large bowl and cover with plastic wrap.</li>
	  <li>After the dough has doubled in size, roll it out into a large rectangle.</li>
	  <li>Melt the butter for the filling and mix in the sugar and cinnamon.</li>
	  <li>Spread the filling onto the dough dough into a swiss roll.</li>
	  <li>Cut the roll into 3cm sections and place flat into a baking tray.</li>
	  <li>Preheat the oven to 350F or 180C, for 20-25min until lightly brown.</li>
	</ol>

### Output :-
![image](https://github.com/user-attachments/assets/56261f8b-651d-4407-bff3-be9c159e23a3)

## Nesting & Indentation :-	
This is used for inside the list having more lists
	
### Example Code :-
	<ul>
	    <li>A</li>
	    <li>
	      B
	      <ol>
	        <li>B1</li>
	        <li>B2
	          <ul>
	            <li>B2a
	              <ul>
	                <li>B2aa</li>
	                <li>B2ab</li>
	              </ul>
	            </li>
	            <li>B2b</li>
	            <li>B2c</li>
	          </ul>
	        </li>
	        <li>B3
	          <ol>
	            <li>B31</li>
	            <li>B32</li>
	          </ol>
	        </li>
	      </ol>
	    </li>
	    <li>C</li>
	  </ul>

### Output :-
![image](https://github.com/user-attachments/assets/afe47b15-3279-4039-8186-fee495faf4d5)

## The Anchor Element :-
This Anchor Element is used to creating link in the web page.

### Example Code :
	<h1>Enter The Favourite Websites</h1>
	<ol>
	    <li><a href="https://www.instagram.com/">Instagram</a></li>
	    <li><a href="https://www.facebook.com/">Facebook</a></li>
	</ol>
### Output :-
![image](https://github.com/user-attachments/assets/ae320cd6-7289-4e7c-ab59-c3bc428ac569)

### The Image Element : -
This Image Element are used to inseting the image in the webpage.

### Example Code :-
	<h1>This is Cat</h1>
	<img src="https://raw.githubusercontent.com/appbrewery/webdev/main/kitten.jpeg">
	
	 <h1>This is Dog</h1>
	<img src="https://raw.githubusercontent.com/appbrewery/webdev/main/puppy.gif">

### Output :-
![image](https://github.com/user-attachments/assets/70f88d7c-b9b4-47c8-b892-d9ad34ac4f11)
![image](https://github.com/user-attachments/assets/e5b7d975-4cf5-4b96-a3ff-e87371200391)

## File Path :-
This File Path is use to find the path of file in your system.

### Example :-
	<h1>All the Animals</h1>
	<h2>Rabbit:</h2>
	<img src="./rabbit.png" alt="rabbit" />

### output :-
![image](https://github.com/user-attachments/assets/0b72c8d6-92da-4535-977d-28ab9837d9e6)

## Cascading Style Sheets(CSS) :-
CSS are used to create the web page into colour fully, with border, different types of fronts sizes, etc. There 3 types of css,
	• Inline css
	• Internal css
	• External css

## Inline CSS :-
Inline CSS applies styles directly to an HTML element using the style attribute.

### Syntax :-
     <tag style = “css”/>

### Example Code :-
		<!DOCTYPE html>
		<html lang="en">
		<head>
		<meta charset="UTF-8">
		<title>Inline</title>
		</head>
		<body>
		<h1 style="color: blue;">Style Me in Blue!</h1>
		</body>
		</html>

### Output :-
![image](https://github.com/user-attachments/assets/2ca39682-adea-45c1-ae2b-d18049a99aa0)

## Internal CSS :-
Internal CSS is written inside a <style> tag within the <head> section of an HTML document.

### Syntax :-
      <style >css</style>

### Example Code :-
		<!DOCTYPE html>
		<html lang="en">
		<head>
		<meta charset="UTF-8">
		<title>Internal</title>
		<style>
		h1 {
		color: red;
		}
		</style>
		</head>
		<body>
		<h1>Style Me in Red!</h1>
		</body>
		</html>

### Output :-
![image](https://github.com/user-attachments/assets/96a1d9fd-92be-4679-afe1-f7965d75e744)

## External CSS :-
External CSS is written in a separate .css file and linked to an HTML document using the <link> tag.

### Syntax :-
     <link herf = “style.css”/>

### Syntax for style.css :-
		html{
		background:green;
		}

  ### Example Code(inde.html) :-
	<!DOCTYPE html>
	<html lang="en">
		<head>
		  <meta charset="UTF-8">
		  <title>External</title>
		  <link rel="stylesheet" href="./style.css" />
		</head>
		<body>
		  <h1>Style Me in Green</h1>
		</body>
	</html>

### Example Code(style.css) :-
h1 {  
color: green;
}

### Output :-
![image](https://github.com/user-attachments/assets/e036def6-88ce-44cf-b7a9-c92bf6b3587d)

## CSS Selectors :-
Selectors are used to choosing where to apply the css in web page.

## Element Selector :-
This Element selector is used to write the h2.

### Syntax(style.css) :-
	h2{
	color:blue
	}

## Class Selector :-
This Class selector write with dot(.) and one class element.

### Syntax(style.css) :-
	.red-heading{
	Color:red
	}

## Id Selector :-
This Id selector write with # and one id.

### Syntax(style.css) :-
	#main{
	Color:red
	}

## Attribute Selector :-
This Attribute Selector write with the p.

### Syntax(style.css)
    <p draggoble = “true”>Drag Me</p>

## Universal Selector :-
This Universal Selector write with the * .This apple for hole code of the web page.

### Syntax(style.css) :-
	*{
	Color:red;
	Text-align:center;
	}

### Selector(index.html) :-
	<!DOCTYPE html>
	<html lang="en">
	<head>
	<meta charset="UTF-8">
	<title>CSS Selectors</title>
	<link rel="stylesheet" href="./style.css" />
	</head>
	<body>
	<h1>CSS Selectors</h1>
	<h2>Applying CSS to Different Parts of HTML</h2>
	<!-- TODO 1: Set the CSS for all paragraph tags to "color: red" -->
	<p class="note">1. The element selector targets elements based on their HTML tag name.</p>
	<ol>
	<!-- TODO 2: Set the CSS for all elements with a class of "note" to "font-size: 20px" -->
	<li class="note" value="2">Class selectors target elements based on the value of the class attribute.</li>
	<!-- TODO 3: Set the CSS for the element with an id of "id-selector-demo" to "color: green" -->
	<li class="note" id="id-selector-demo" value="3">ID selectors target elements based on the value of the id
	attribute.</li>
	<!-- TODO 4: Set the CSS for the li elements that have the "value" attribute set to "4" to have "color: blue" -->
	<li class="note" value="4">Attribute selectors target elements based on their attributes and values.</li>
	<!-- TODO 5: Set all elements to have "text-align: center" -->
	<li class="note" value="5">The universal selector targets all elements.</li>
	</ol>
	</body>
	</html>

### Selector(style.css) :-
	ol {
	margin-left: -40px;
	margin-top: -20px;
	list-style-position: inside;
	}
	/* Write your CSS below, don't change the rules above. */
	p {
	color: red;
	}
	
	.note {
	font-size: 20px;
	}
	
	#id-selector-demo {
	color: green;
	}
	
	li[value="4"] {
	color: blue;
	}
	
	* {
	text-align: center;
	}

### Output :-
![image](https://github.com/user-attachments/assets/f61e1236-20aa-4766-a975-ab0709a1d3ba)

