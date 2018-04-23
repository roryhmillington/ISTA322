ISTA-322 HomeWork Asp.Net Mvc Chapter 5

Rory H Millington

16 Apr 2018

1. What is a view engine?

	A view engine procezses ASP.NET content and looks for instructions, typically to insert dynamic content into the output sent to a browser and Razor is the name of the MVC Framework view engine.

	In the Model-View-Controller (MVC) pattern, views are intended exclusively for encapsulating presentation logic. They should not contain any application logic or database retrieval code. All application logic should be handled by the controller. A view renders the appropriate UI by using the data that is passed to it from the controller. This data is passed to a view from a controller action method by using the View method.

2. What is Razor?
	
	Razor Engine is an advanced view engine that was introduced with MVC3. This is not a new language but it is a new markup syntax.

	Razor supports C# and uses the @ symbol to transition from HTML to C#. Razor evaluates C# expressions and renders them in the HTML output.
	When an @ symbol is followed by a Razor reserved keyword, it transitions into Razor-specific markup. Otherwise, it transitions into plain C#.
	To escape an @ symbol in Razor markup, use a second @ symbol:	

3. What do views do? List two specific things in your answer to this question.

	A view renders the appropriate UI by using the data that is passed to it from the controller. This data is passed to a view from a controller action method by using the View method.


4. How does Razor respond when it encounters statements that begin with the at character (@)? Be specific.
	
	? represents a nullable type. Nullable types represent value-type variables that can be assigned the value of null

5. How does Razor respond when it encounters statements that begin with the at character followed by the colon (@:)? Be specific.

	The @: characters prevent Razor from interpreting this as a C# statement, which is the default behavior when it encounters text.

	Use the @: operator or the <text> element. The @: outputs a single line of content containing plain text or unmatched HTML tags; the <text> element encloses multiple lines to output. These options are useful when you don't want to render an HTML element as part of the output.

6. Describe how you implement a standard formatting for all pages in an ASP.NET application.
	
	The basic mechanism for formatting is the default implementation of the Object.ToString method, 

7. What is the difference in using Razor to interpolate data values as stand-alone HTML elements and as attributes to HTML elements. What is the similarity?
	
	It detracts from the pattern of MVC

8. What is a view start file and where is it located?

	_ViewStart.cshtml is located in the views folder


9. What is a Razor code block? What is the syntax of a Razor code block?

	The Razor syntax is based on the C# programming language, and that's the language that's used most often with ASP.NET Web Pages. 

	The @ character starts inline expressions, single statement blocks, and multi-statement blocks:

	A code block includes one or more code statements and is enclosed in braces.

	Inside a code block, each complete code statement must end with a semicolon. Inline expressions don't end with a semicolon.


10. Describe the different roles of action methods and views.

	

	ViewResult – Represents HTML and markup.
	EmptyResult – Represents no result.
	RedirectResult – Represents a redirection to a new URL.
	JsonResult – Represents a JavaScript Object Notation result that can be used in an AJAX application.
	JavaScriptResult – Represents a JavaScript script.
	ContentResult – Represents a text result.
	FileContentResult – Represents a downloadable file (with the binary content).
	FilePathResult – Represents a downloadable file (with a path).
	FileStreamResult – Represents a downloadable file (with a file stream).
	




11. Describe the use of the @using statement. Give an example of how you would use it.

	the @using expression to bring a namespace into context for a view, just like I would in a regular C# class.

 