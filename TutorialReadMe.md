https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-2.2&tabs=visual-studio

Create a Web API with ASP.NET Core MVC

This tutorial teaches the basics of building a web API with ASP.NET Core.

In this tutorial, you learn how to:

Create a web API project.
Add a model class.
Create the database context.
Register the database context.
Add a controller.
Add CRUD methods.
Configure routing and URL paths.
Specify return values.
Call the web API with Postman.
Call the web API with jQuery.

At the end, you have a web API that can manage "to-do" items stored in a relational database

API	                  Description	              Request body	          Response body
GET/api/todo	        Get all to-do items	      None	                  Array of to-do items
GET/api/todo/{id}	    Get an item by ID	        None	                  To-do item
POST/api/todo	        Add a new item	          To-do item	            To-do item
PUT/api/todo/{id}	    Update an existing item   To-do item	            None
DELETE/api/todo/{id}  Delete an item    	      None	                  None

https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api/_static/architecture.png?view=aspnetcore-2.2

