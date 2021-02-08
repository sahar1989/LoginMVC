# Simple Login Application

### Application is developed in Visual Studio 2019, C#, MVC 5.0

#### Model

This folder includes user class and entitites class which are links to Database and table

#### View

This folder includes Index, Login and Register pages.
Login user information includes, email address and password
Register user information Firsname, Lastname, email and password


#### Controller
This folder includes HomeControler class 



#### DataBase name

MvcLoginDB

Table Users:

##### CREATE TABLE [dbo].[Users] (
#####    [Id]        INT           IDENTITY (1, 1) NOT NULL,
#####    [FirstName] NVARCHAR (50) NULL,
#####    [LastName]  NVARCHAR (50) NULL,
#####    [Email]     NVARCHAR (50) NULL,
#####    [Password]  NVARCHAR (50) NULL,
#####    PRIMARY KEY CLUSTERED ([Id] ASC)
#####);


