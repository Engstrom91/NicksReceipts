I built this Spring MVC application to be able to demonstrate how the Swedish public health insurance works. 
Using this service, healthcare workers would be able to view a patient's prescriptions and decide which of their costs should be covered by the insurance.

The data for each patient is stored in a MySQL table which is accessed through the application's Spring repository. 
I developed a Controller class that returns relevant views to be rendered in the browser. The frontend was built using Thymeleaf.

Follow the steps below to launch the application:

1. Set up MySQL on your machine.
2. Edit the application.properties file to reflect the credentials for your MySQL server. 
3. Run the project from the ReceiptApplication class in your IDE.
4. By default the application's address is localhost:8080
