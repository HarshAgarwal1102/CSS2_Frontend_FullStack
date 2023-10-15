What is CSS (Cascade Style Sheet)?
CSS is a language for how a document(HTML Page) will be presented to the 
end-user.
- Used to Style and Layout web pages.
- Font Color, Background Color, Content Spacing, 
Split to Multiple Rows and Column, Animations, Margin, Padding

Why is it called Cascade Style Sheet
In your Web Page, we have a lot of Styles
Cascade - Set of Rules & Processes to find out which style would be
apply to your document.

CSS - Rule-Based Language

Types of CSS selectors
1. Simple Selectors
	name, id, class

2. Cobinator Selectors
	'+', ' ', '>', '~' 

	div+p -> We are trying to access the p which is just next to h1 (Sibling)

	div p -> We are trying to access every p which is just next to h1
	
	div>p -> We are trying to access all the p which is near to h1 (child)

	div~p -> High priority same as div+p

3. Pseudo-class Selectors
	State -> hover, visited, focus
4. Pseudo-element Selectors
	first line, first letter
5. Attribute Selectors
	input type="text"



How does CSS Work?

1. HTML load (Web Page)
2. Parsing of HTML
	2.1 Load CSS
	2.2 Parse CSS (Attach the styling to DOM)

3. Creation of DOM tree
4. HTML display
