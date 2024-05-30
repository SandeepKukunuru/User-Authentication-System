User Registration, Authentication , Authorization implemented in MVC application with the help of ASP.NET Core Identity Library.


I have created this project in .NET 7.0 version


Selected Login and Register Razor pages from Identity library. 


TO display both Login and Register tabs in one page I created one layout (Razor layout). 

Added customized bootstrap html code cshtml to navigate both Login and Logout 


Added first name and Last name by using properties. We could see that IdentityUser (model) is inheriting base class(Identity user into Application User)

Entity framework: Connection string is  given in a appsettings.json.Now DB migration is ready ass entity framework is setup.

Created Migration using Package Manager Console then used Add-Migration "Initial create" and Update-DB commands to do migration.


In order to add First name and Last name in register page , Add the properties to Register.cshtml.cs file.

Removed unnecessary things in the login page.


Authorization: In order to prevent unauthorized user accessing Home controller , added Attribute Authorize in HomeCOntroller.CS







