# SchoolProjects
School Projects

ClassRegistrationZip:
ASP.NET Web Forms project for a school classes registration application. It has a master page and several content pages, most of which use a code behind. The master page contains an internal style sheet shared by all content pages, including a menu for navigation, and a reference to a JQuery Content Delivery Network (CDN). Most pages query a SQL Server database to display class information. To view the Register and MyClasses pages, you must be logged in via the Login page, otherwise you are redirected to the Login page. Login state is maintained via a Session variable. To obtain credentials, use the NewLogin page, which will write an access request to the database. NewLogin page field validation is done via JQuery. Login page queries the database to validate credentials. The Register screen displays available classes, and facilitates registering by displaying a checkbox for each class, and a button to register for all selected classes. MyClasses displays the classes for which you have registered. All database access is done via C Sharp classes stored in the App_Code folder. Abstraction layers: The Presentation layer is achieved by having the UI in the content pages, and the Processing layer code to access the database is in the App_Code folder, which calls the stored procedures and views (with no direct database access) in the SQL Server database (Data layer). Written using Visual Studio 2015 Community.

Checkbook.zip:
WPF project for a checkbook application. It allows you to write a check, make a debit or a credit. Each transaction falls into a category. We seed the application with data contained in an XML file (included in TransactionList class). We use Regular Expressions to parse the XML file into fields, create a Transaction object, add the object to a TransactionList collection, then store the transaction in a SQL Server database. You can then use the UI to enter transactions, which trigger the same transaction activity just described. There is an <Edit> button that pops up an edit screen to modify a transaction. Project also uses abstract classes, interfaces, events, enums, properties, methods and helper methods. Written using Visual Studio 2015 Community.

VendingMachine.zip:
Windows Forms project for a vending machine. It uses two windows forms, each in a tab. First tab and form are the vending machine interface for people purchasing a can of soda, and the second tab and form is for servicing the vending machine. Project was first written as a Console application, then added as a reference to the final Windows Forms application. The Windows Forms application re-uses the logic that was added as a reference. It uses classes, enums, multiple constructors in a class, properties, methods and helper methods. Written using Visual Studio 2015 Community.

ConsoleInventory.zip:
Simple Console project for inventory system that uses an array of structs (no database) to store information. I wrote this in the very first C sharp course completed. Written using Visual Studio 2015 Community.

ConsoleInventory.cs:
Since this is the only program in the ConsoleInventory project, I uploaded it separately so you can view the code without downloading zipped project file.
