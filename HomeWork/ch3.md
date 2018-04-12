ISTA322 Homework Chapter 3

Rory H Millington

11 April 2018

1. The book states, “Interactions with an MVC application follow a natural cycle of user actions and view updates, where the view is assumed to be stateless.” What does it mean for the view to be stateless?

	[A stateless protocol] treats each request as an independent transaction that is unrelated to any previous request so that the communication consists of independent pairs of request and response.

2. The book identiﬁes two kinds of models. Brieﬂy desdribe each of them.
	
	Models. Model objects are the parts of the application that implement the logic for the application's data domain. Often, model objects retrieve and store model state in a database. For example, a Product object might retrieve information from a database, operate on it, and then write updated information back to a Products table in a SQL Server database.

In small applications, the model is often a conceptual separation instead of a physical one. For example, if the application only reads a dataset and sends it to the view, the application does not have a physical model layer and associated classes. In that case, the dataset takes on the role of a model object.

3. Give an example of separation of concerns from your own life experience. This should be a simple, everyday example.

	Family, Job

4. What is a view engine?

	


5. The book notes that the three-tier structure, or n-tier model, is “the most widely used pattern for business applications.” Why do you think that this is true? An answer like, “Because it works well,” is not a suﬃcient answer to this question.


6. This question requires some outside research. When we study UWP, you will see that the UWP design pattern is the Model-View-ViewModel (MVVM). What is the diﬀerence between MVC and MVVM that makes the ﬁrst good for ASP.NET MVC and the second good for UWP?


7. Describe the two parts of the dependency injection (DI) design pattern.


8. Give an example of loose coupling from your own life experience. This should be a simple, everyday example.


9. What are the two types of testing discussed in the book?


10. What are the seven steps of the test driven development (TDD) workﬂow, as stated in the book?
