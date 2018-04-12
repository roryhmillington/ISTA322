ISTA322_4 Homework Ch2

Rory H Millington

03 April 2018


1. Describe what a controller does in the MVC design pattern.

	Controllers are the components that handle user interaction, work with the model, and ultimately select a view to render that displays UI. In an MVC application, the view only displays information; the controller handles and responds to user input and interaction. For example, the controller handles query-string values, and passes these values to the model, which in turn might use these values to query the database.


2. What is the ASP.NET MVC convention in naming controllers? What does HomeController.cs do?

	The MVC convention is to put controllers in the Controllers folder. In ASP.NET MVC, controllers are just C# classes.

	If you expand the Controllers folder, you should see a file named AccountController.cs and a file named HomeController.cs. If you expand the Views folder, you should see three subfolders named Account, Home and Shared. If you expand the Home folder, you'll see two additional files named About.aspx and Index.aspx (see Figure 3). These files make up the sample application included with the default ASP.NET MVC template.


3. What is the name of the routing conﬁguration ﬁle? Where is it located?

	ASP.NET Routing is enabled in your application's Web configuration file (Web.config file). 	**ROUTECONFIG**

	Second, and more importantly, a route table is created in the application's Global.asax file. The Global.asax file is a special file that contains event handlers for ASP.NET application lifecycle events. The route table is created during the Application Start event.
	

4. What is Razor? How does Razor treat an expression beginning with the at symbol (@)?

	Key to a strongly typed view and the conveince it offers. he @ character starts inline expressions, single statement blocks, and multi-statement blocks:


5. How do View methods work?

	The path to the view is inferred from the name of the controller and the name of the controller action.

	A view contains the HTML markup and content that is sent to the browser. A view is the equivalent of a page when working with an ASP.NET MVC application.
	


6. What is the purpose of MVC models?

	An MVC model contains all of your application logic that is not contained in a view or a controller. 

	In general, you should strive for fat models and skinny controllers. Your controller methods should contain only a few lines of code. If a controller action gets too fat, then you should consider moving the logic out to a new class in the Models folder


7. What is a strongly typed view and why do we use strongly typed views?

	Strongly typed views are used for rendering specific types of model objects, instead of using the general ViewData structure. By specifying the type of data, you get access to intellisense for the model class.

8. What is the purpose of setting a start page URL?

	To be helpful and make the browser request a URL based on the current view being edited.

9. Describe the diﬀerences between HTTP GET and HTTP POST.

	Issued each time someone clicks a link.
	
	Receives submitted data and decides what to do with it.

10. Describe the two approaches to validation in web applications.

	Assume all input is malicious.

	Input validation starts with a fundamental supposition that all input is malicious until proven otherwise. 

	Whether input comes from a service, a file share, a user, or a database, validate your input if the source is outside your trust boundary.

	Centralize your approach.
	This ensures that validation rules are applied consistently. It also reduces development effort and helps with future maintenance.

11. What is the role of Cascading Style Sheets (CSS) in web development?

	People started using CSS to develop the design of websites because it can save a lot of time and effort for website designers. It has the ability to control the layout of multiple pages at a time, which if you look at many websites you will see they have similar layouts to all of their pages. 
