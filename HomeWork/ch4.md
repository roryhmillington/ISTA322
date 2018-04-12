ISTA 322_4 Chapter 4

Rory H Millington

11 Apr 2018

Using automatic properties is a shortcut that avoids several explicit steps. List the steps that the use of automatic properties avoids.

	Creates a pattern of a field back property, without defining the fielid or specifiing the code in the getter and setter. 


2. Using the object initializer syntax is a shortcut that avoids several explicit steps. List the steps that the use of object initializers avoids.

	Create a product object and produce the result. 
	Create the object.
	Set the perameter values.
	Call the view method.


3. What is the purpose of creating extension methods?

	Extension methods enable you to "add" methods to existing types without creating a new derived type, recompiling, or otherwise modifying the original type. Extension methods are a special kind of static method, but they are called as if they were instance methods on the extended type.

	Used to extend a sealed class like adding factorial method in int class or adding todouble method in string class. 

	Extension methods are methods that, although static, can be called on an instance (object) of a class rather than on the class itself. 

	Specifying a method’s first argument with the “this” keyword modifier will make that method an extension method. 

	Extension methods can be declared only in static classes. 

	

4. What is the one feature of extension methods that will always allow you to identify a method as an extension method?

	Extension methods are defined as static methods but are called by using instance method syntax. Their first parameter specifies which type the method operates on, and the parameter is preceded by the this modifier. Extension methods are only in scope when you explicitly import the namespace into your source code with a using directive. 

5. How do you create an extension method that ﬁlters the results returned by the method on a user speciﬁed criterion? 
 
	 An extension method that operates on an IEnumerable < T > and that also returns an IEnumerable < T > can use the yield keyword to apply selection criteria to items in the source data to produce a reduced set of results.

6. Explain the syntax of a lambda expression. The term “lambda expression” originates in the lambda calculus developed by the mathematician Alonzo Church in the 1930’s. There is a class of programming languages that are based on the fundamental ideas of lambda calculus.

	To create a lambda expression, you specify input parameters (if any) on the left side of the lambda operator =>, and you put the expression or statement block on the other side. For example, the lambda expression x => x * x specifies a parameter that’s named x and returns the value of x squared.  Asynchronous Programming


7. This will require some outside research. What is the distinction between an anonymously typed variable and a dynamically typed variable?
	
	NET framework 4.0 introduced new keyword called "Dynamic". Object of type dynamic bypasses the static type checking at time of compilation whereas for anonymous type, creating static type and checking type at compile time.

	Anonymous type is a class type that contain one or more read only properties whereas dynamic can be any type it may be any type integer, string, object or class.

	Anonymous types are assigned type by the compiler.

	Anonymous type is directly derived from System.Object whereas Dynamic is differ from object type and DLR (dynamic Language Runtime) define and assign type runtime.

	Anonymous types throw compile time errors, Dynamic types does not throw any compile time error but throw run-time errors.

	For Anonymous type, Visual studio able to show intellisense because type is known at the time compilation whereas intellisense is not available with dynamic because type is defines at runtime.

8. You are having a discussion about C# with a friend of yours that uses another language. You are tellig him about C#’s LINQ library. How would you describe to him the diﬀerence between LINQ’s SQL-like notation and LINQ’s dot notation?
	
	LINQ to SQL is designed to be non-intrusive to your application. 
	It is possible to migrate current ADO.NET solutions to LINQ to SQL in a piecemeal fashion (sharing the same connections and transactions) since LINQ to SQL is simply another component in the ADO.NET family. LINQ to SQL also has extensive support for stored procedures, allowing reuse of the existing enterprise assets.
	LINQ to SQL applications are easy to get started. 
	Objects linked to relational data can be defined just like normal objects, only decorated with attributes to identify how properties correspond to columns. Of course, it is not even necessary to do this by hand. A design-time tool is provided to automate translating pre-existing relational database schemas into object definitions for you.

 

9. What, exactly, does the await keyword do?
	
	This tells the C# compiler that I want to wait for the result of the Task that the GetAsync method returns and then carry on executing other statements in the same method.

10. What is the connection between await and the async keywords?

	When you use the await keyword, you must also add the async keyword to the method signature.
 
	The await and async are implemented using some clever compiler tricks, meaning that they allow a more natural syntax, but they do not change what is happening in the methods to which they are applied.

