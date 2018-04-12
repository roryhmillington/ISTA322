ISTA322_4 Homework Ch1

Rory H Millington

03 April 2018



Read chapter 1, pages 1 – 10 in the Pro ASP.NET MVC 5 book.
Discussion Questions

1. What year was ASP.NET introduced?
	
	2002

2. Briefly describe ASP.NET Web Forms.

	ASP.NET Web Forms is a part of the ASP.NET web application framework and is included with Visual Studio. It is one of the four programming models you can use to create ASP.NET web applications, the others are ASP.NET MVC, ASP.NET Web Pages, and ASP.NET Single Page Applications.

3. Briefly describe ASP.NET.

	ASP.NET is a unified Web development model that includes the services necessary for you to build enterprise-class Web applications with a minimum of coding. ASP.NET is part of the .NET Framework, and when coding ASP.NET applications you have access to classes in the .NET Framework. 

4. Briefly describe .NET.
	
	A multi-language managed code platform

5. What is Representational State Transfer (REST)? This will take some independent research.

	REST was first introduced and defined in 2000 by Roy Fielding at the University of California, Irvine, in his academic dissertation, "Architectural Styles and the Design of Network-based Software Architectures". It is an architectural style which is derived from many existing network architectural styles. It acts as a guiding framework for web standards and designing web services. It exploits the full potential of web by using existing web standards and adding constraints on them in order to ensure the modelling of well matured distributed hypermedia system. 

6. What is Agile Development? This will take some independent research.

	AP is a collection of principles and techniques that try to overcome the inflexibility of the strictly-design-based development cycle. 

	Simple Design: use the simplest design that solves your immediate needs.

	Design as you go: Always scrub and exercise the code you work on while the project develops, to make sure it remains well structured, designed and written. (Techniques for this are called Refactoring).

	Incremental steps: When changing or adding code, take the smallest step you can, then compile and test again.
 
	Independent steps: Don't mix up the things you do when you fix a bug, fix the bug, when you add a feature, add the feature.
 
	Know and use your tools with purpose: Especially for tasks beyond writing code like design and documentation, know the available tools, use those that help you (not just a single one), and always understand why you do what you do. 

	The Meta Rule: Use only the principles and techniques that actually work for you.

7. What is unit testing?

	Unit testing, sometimes referred to as developer testing, focuses on testing small pieces of code, such as a class, that a developer is writing. These tests are critical for helping you ensure that the pieces you build work as expected and will operate correctly when combined with other parts of the application. Such testing helps support management of the application over time by ensuring that changes you make don't inadvertently affect other parts of the system. 


8. What year was ASP.NET MVC introduced?

	October 2007

9. Describe URL routing. As part of your answer, discuss the concept of “clean URLs.”
	
	URL routing is a capability first introduced with ASP.NET 3.5 SP1, and which is already used within ASP.NET MVC applications to expose clean, SEO-friendly URLs.  URL routing lets you configure an application to accept request URLs that do not map to physical files. Instead, you can use routing to define URLs that are semantically meaningful to users and that can help with search-engine optimization (SEO).
	

10. What is the relationship between Microsoft’s .NET platform and ASP.NET MVC?

	The Model-View-Controller (MVC) architectural pattern separates an application into three main components: the model, the view, and the controller. The ASP.NET MVC framework provides an alternative to the ASP.NET Web Forms pattern for creating Web applications. The ASP.NET MVC framework is a lightweight, highly testable presentation framework that (as with Web Forms-based applications) is integrated with existing ASP.NET features, such as master pages and membership-based authentication. 


11. Chapter 1 does not discuss the MVC pattern specifically, and in a sense this entire course is an extended examination of the MVC pattern. Using an independent resource (such as Wikipedia) briefly state the responsibility of (a) the model, (b) the controller, and (c) the view.

	Model objects are the parts of the application that implement the logic for the application's data domain. Often, model objects retrieve and store model state in a database.

	Views are the components that display the application's user interface (UI). Typically, this UI is created from the model data. An example would be an edit view of a Products table that displays text boxes, drop-down lists, and check boxes based on the current state of a Product object.

	Controllers are the components that handle user interaction, work with the model, and ultimately select a view to render that displays UI. In an MVC application, the view only displays information; the controller handles and responds to user input and interaction. For example, the controller handles query-string values, and passes these values to the model, which in turn might use these values to query the database.

	The MVC pattern helps you create applications that separate the different aspects of the application (input logic, business logic, and UI logic), while providing a loose coupling between these elements. 
	
