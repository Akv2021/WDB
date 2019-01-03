
<!--!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!-->
<!--     _   _  ____  __  __  __       -->
<!--    ( )_( )(_  _)(  \/  )(  )      -->
<!--     ) _ (   )(   )    (  )(__     -->
<!--    (_) (_) (__) (_/\/\_)(____)    -->
<!--!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!-->

Forms

1. Name value pair are used to show the fields and values in query string (or POST request).
2. for (in <label> ) and id (in <input> ) bind them together and keep the label in view while filling the input.
3. size (in px) sets the input box size. 
4. maxlength is length validator for input box.
5. min can be used in password
6. In drop down , select > name & option > value
7. By default form uses GET method. (send info in url)
8. If value not explicitly given, value = On.
9. We can use Label in two ways, either nesting the input element in label OR using for/id pair.
<!-- 9. label tag contains radio input as a child (label > radio) [usually label + input (i.e label is sibling, not parent)] -->
10. textarea contains rows and cols attribute (with name,id)
11. To keep checkbox tick in begin, set checked="checked".
12. input boxes can exist without form tag but then clicking the submit button wont submit the form details. (form is block element.)
13. Default "action" (page where data is sent) is current page.
14. General validations = required(browser dependent)/type = email,pass.
15. All radioboxes must have same name.
16. If value attribute is absent in option tag, the text which we see in dropdown is treated as value.
17. The max and min attributes works with the following input types: number, range, date, datetime, datetime-local, month, time and week. (<input min="number|date">)
18. If min/minlength is not supported by browser, pattern+required can be used.
			eg. <input pattern=".{3,}"   required title="3 characters minimum">
				<input pattern=".{5,10}" required title="5 to 10 characters">
				<input pattern=".{0}|.{5,10}" required title="Either 0 OR (5 to 10 chars)">
19. title attribute is used to display custom error message.
20. use <div> instead of <br> for new line.

iFrame

1. iFrame is used to add web pages (external documents) in our page.
2. iFrame has attributes similar to img. Eg. src,width,height (frameborder,allowfullscreen).
3. To open link in iFrame, we use name attribute and use same name in "target" attribute of anchor tag.
4. Tip: To deal with browsers that do not support <iframe>, add a text between the opening <iframe> tag and the closing </iframe> tag.
5. Use CSS to style the <iframe> (even to include scrollbars).

* Block elements have <br> before and after it by default.
* Description list : dt for terms, dd for definition.
* When a word is too long, or you are afraid that the browser will break your lines at the wrong place, you can use the <wbr> element to add word break opportunities.
* The <track> tag specifies text tracks for media elements (<audio> and <video>).
* The <base> tag specifies the base URL/target for all relative URLs in a document. (base must be inside head tag.) The <base> tag must have either an href attribute or a target attribute, or both.



Table

1. tr = table row, th = heading (only 1st row), td = data. 
	We can use <th> in subsequent rows as well for all the bold cells.	
2. rowspan ,colspan . Rowspan = "2", then do not provide <td> for that cell in next row. 
	The cell for which rowspan/colspan has been provided is already defined, so skip that one. 
	[But, for example, what if you added an extra cell? Well, it would just pop off the edge to the right.]
3. for SEO purpose we can put 1st row in <thead> , and rest in <tbody>.
4. for testing only,we can use border ="1" in <table>.
5. The <tfoot> tag is used to group footer content in an HTML table.
6. Browsers can use thead,tbody,tfoot to enable scrolling of the table body independently of the header and footer. Also, when printing a large table that spans multiple pages, these elements can enable the table header and footer to be printed at the top and bottom of each page. you can also use CSS to style these elements.
7. The <tfoot> element must have one or more <tr> tags inside. 
8. The <caption> tag defines a table caption. The <caption> tag must be inserted immediately after the <table> tag.
9. Rowspan = vertically, colspan = horizontally. If we use both then use multiplication. [2*2 = 4]


HTML entities

1. Entities are reserved characters in html. 
2. Entity can be in form of name or number (hex or decimal)
				 &entity_name;
					OR
				 &#entity_number;

3. Browsers may not support all entity names, but the support for numbers is good.
				 


