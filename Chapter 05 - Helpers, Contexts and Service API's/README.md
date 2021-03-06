# Overview

![5852022211_66215f281b_o.jpg](assets/5852022211_66215f281b_o.jpg)
>Photo by Doug Robar

Umbraco comes full of helpers, contexts and services.  Before you decide to roll your own implementation of CRUD operations, you should be familiar with some of the basic things Umbraco provides through it's public classes and methods.

For instance, you may be tempted to install and use Entity Framework to handle custom table operations.  You should know that Umbraco uses a micro-ORM named PetaPoco to handle some basic database operations. 

Also, keep in mind that the items in this chapter are in regards to C# functionality.  There are AngularJS resources, directives and services you should be aware of as well.  We'll cover those later in [Chapter 11](/Chapter%2011%20-%20Working%20with%20AnuglarJs%20for%20Customizing%20the%20Backoffice).

>For the record you can still use Entity Framework in parallel with PetaPoco.

[Next> 01 - ApplicationContext](01%20-%20ApplicationContext.md)
