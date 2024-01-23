* After successfully cloning the project template on desktop, you will be able to see folder named with your user id. (e.g. user@gmail.com)

* Go to below path and open solution file with Visual Studio.
  - Path: user@gmail.com > ContactManagementApp > ContactManagementApp.sln

* Press Ctrl + S to save your code.
		
* Steps to Apply Migration(Code first approach):
  - Go to "Tools" -> "NuGet Package Manager" -> "Package Manager Console" from the top menu bar of Visual Studio.
  - After clicking on "Package Manager Console," a new tab should open at the bottom of the Visual Studio window, displaying the Package Manager Console.
  - Run following command to apply migration : update-database


* To build your project in Visual Studio, click on "Build" in the top menu, then select "Build Solution" or press Ctrl + Shift + B.

* To launch your application, press F5 or use Ctrl + F5 to start your application without debugging.
  (Note:If you get below screens regarding SSL certificate, Click on YES for both screens.)
  - The application will run in the local browser, Run Application again.

* To test any applications on a browser, use the internal browser in the workspace. 
  (Note: Copy Url from your local browser, e.g.base URL is https://localhost:44350)

* To test any Restful application, you can use POSTMAN.
  (Note: Before sending the request from postman you need to disable “Enable SSL certificate verification” from settings.)
  - Use the same base URL from local browser to test on postman.(e.g.https://localhost:44350/api/Contact/GetAllContacts)

* To run test cases in your project in Visual Studio, click on "Test" -> “Run All Tests” in the top menu.  
  (You can run this command multiple times to identify the test case status, and refactor code to make maximum test cases passed before final submission).

* Steps to push changes to GitHub:
  - Go to "View" -> "Git Changes" from the top menu bar of Visual Studio.
  - In the "Changes" window on the right side of Visual Studio, you'll see the modified files.
  - Enter any commit message in the "Message" box at the top of the window, and click on “Commit All” button.
  - After committing your changes, Click the "Push" button (Up Arrow Button) to push your committed changes to the GitHub repository.
