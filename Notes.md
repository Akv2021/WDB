
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

1. 



